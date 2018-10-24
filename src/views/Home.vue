<template>
  <div class="home">
    <ul>
      <li v-for="index in 100" :key="index">
        <img v-lazy="imgSrc">
      </li>
    </ul>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "home",
  data() {
    return {
      repeat: 100,
      imgSrc: "https://ss1.bdstatic.com/70cFvXSh_Q1YnxGkpoWK1HF6hhy/it/u=944104808,2934969275&fm=27&gp=0.jpg"
    }
  }
};
</script>
