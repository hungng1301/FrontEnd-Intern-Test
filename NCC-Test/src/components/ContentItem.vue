<template>
    <div class="column">
        <h3>Lorem ipsum dolor sit amet</h3>
        <div class="image">
            <i>
                <slot name="icon"></slot>
            </i>
            <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed non dui sodales, faucibus libero ut, posuere
                felis. Donec imperdiet suscipit accumsan. Aenean consequat condimentum velit ut tempor. Nam porta massa in
                metus bibendum congue. Pellentesque ultrices liquam egestas nunc at
            </p>
        </div>
        <div class="details">
            ullamcorper ultricies. Donec feugiat velit nulla, vel sodales est ullamcorper id. Aenean consequat condimentum
            velit ut tempor. Nam porta massa in metus bibendum congue. Pellentesque ultrices vestibulum mattis.
        </div>
    </div>
</template>
<style scoped>
.column {
    flex-basis: 30%;
    margin: 20px;
}

h3 {
    color: black;
    font-weight: bold;
}
p {
    color: black;
}

.image {
    display: flex;
}

.details {
    color: black;
}
</style>