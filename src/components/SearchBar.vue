<template scoped>
  <div class="search-bar">
    <img :src="require('@/assets/search.png')" alt="">
    <input type="text" placeholder="Search here..." />
  </div>
</template>

<style scoped>
.search-bar {
  display: flex;
  align-items: center;
  padding: 14px;
  background-color: #f5f5f5de;
  width: 300px;
  height: 40px;
}

.search-bar input {
  border: 0;
  padding-left: 10px;
  font-size: 12px;
  background-color: transparent;
  font-family: Verdana, Geneva, Tahoma, sans-serif;
}

.search-bar img {
  width: 29px;
  height: 20px;
  padding-right: 5px;
  padding-left: 5px;
}
</style>
