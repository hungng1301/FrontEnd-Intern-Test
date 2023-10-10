<template>
    <div class="sidebar">
        <ul>
            <li class="active"><a href="#">Home</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#">News</a></li>
            <li><a href="#">Blog</a></li>
            <li><a href="#">Contract</a></li>
        </ul>
    </div>
</template>

<style scoped>
.sidebar {
    background: #191718;
    /* width: 15%; */
    flex: 0 0 10%;
    height: 100%;
}

.active a {
    color: #fff;
}

ul {
    padding-left: 0px;
}

ul li {
    border-bottom: 1px solid #5c5c5c;
    list-style: none;
}

ul li a {
    display: block;
    color: #5c5c5c;
    padding: 10px;
}

ul li :hover {
    background-color: #5c5c5c;
    color: #fff;
}

@media (max-width: 1024px) {
  .sidebar ul {
    display: flex;
    justify-content: space-around;
    padding: 10px;
  }

  ul li {
    border-bottom: none;
  }
}
</style>