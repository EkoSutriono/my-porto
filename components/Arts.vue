<template>
    <div id="arts" class="row gap-2 d-flex justify-content-center">
      <div class="content" v-for="item in arts" :key="item.src">
          <img :src="require(`../assets/arts/${item.src}`)" alt="" width="400" height="auto" class="">
      </div>
    </div>
</template>

<script>
export default {
  name: 'Arts',
  data() {
    return {
      arts: [
        {
          src: 'content1.jpeg'
        },
        {
          src: 'content2.jpeg'
        },
        {
          src: 'content3.jpg'
        },
        {
          src: 'content4.jpeg'
        },
        {
          src: 'content5.jpg'
        },
        {
          src: 'content6.jpg'
        },
        {
          src: 'content7.jpg'
        },
        {
          src: 'content8.jpg'
        },
        {
          src: 'content9.jpg'
        },
      ]
    };
  },
};
</script>

<style scoped>
#arts {
  padding-bottom: 100px;
}
.content {
  width: 30%;
}
</style>