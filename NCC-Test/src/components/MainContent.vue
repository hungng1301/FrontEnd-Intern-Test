<script setup>
import FooterBar from './Footer.vue'
import HeaderBar from './Header.vue'
import Items from './ContentItem.vue'
</script>
<template>
    <div class="MainContent">
        <HeaderBar />
        <div class="content">
            <div class="content-block">
                <h3>Lorem ipsum dolor sit asmet?</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed tristique consequat placerat. Vestibulum auctor pellentesque sem, eu posuere erat hendrerit quis. Maecenas vel consequat turpis. Nam facilisis, ligula in mattis sodales, augue justo tristique nulla, sed lacinia ante eros ut mi. Morbi vitae diam augue. Aliquam vel mauris a nibh auctor commodo. Praesent et nisi eu justo eleifend convallis. Quisque suscipit maximus vestibulum. Phasellus congue mollis orci, sit amet luctus augue tristique eu. Donec vulputate odio neque, sed semper turpis pellentesque a.</p>
            </div>
            <div class="content-image-block">
                <Items>
                    <template #icon>
                        <img src="../assets/af6932e0d359fce7f35402c40d54bc99.png" alt="csslogo"/>
                    </template>
                </Items>
                <Items>
                    <template #icon>
                        <img src="../assets/html.png" alt="htmllogo"/>
                    </template>
                </Items>
                <Items>
                    <template #icon>
                        <img src="../assets/urrl.png" alt="urllogo"/>
                    </template>
                </Items>
            </div>
        </div>
        <FooterBar />
    </div>
</template>
<style scoped>
.MainContent {
    height: 100%;
}
.content {
    color: #fff;
    margin: 0px 20px;
    padding: 0px 30px;
}
.content .content-block {
    background-color: #efefef;
    text-align: center;
    color: black;
    padding: 30px 50px;
}
.content .content-block h3 {
    font-weight: bold;
}

.content-image-block {
    display: flex;
    justify-content: space-between;
}

@media (max-width: 1024px) {
    .content-image-block {
        display: block;
    }
}
</style>