<template>
  <v-carousel hide-controls lazy>
    <v-carousel-item v-for="(item,i) in items" v-bind:src="item.src" :key="i"></v-carousel-item>
  </v-carousel>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      title: 'Izhevsk Community',
      items: [
        {
          src: '/static/city/1.jpg'
        },
        {
          src: '/static/city/2.jpg'
        },
        {
          src: '/static/city/3.jpg'
        },
        {
          src: '/static/city/4.jpg'
        },
        {
          src: '/static/city/5.jpg'
        },
        {
          src: '/static/city/6.jpg'
        },
        {
          src: '/static/city/7.jpg'
        },
        {
          src: '/static/city/8.jpg'
        },
        {
          src: '/static/city/9.jpg'
        },
        {
          src: '/static/city/10.jpg'
        },
        {
          src: '/static/city/11.jpg'
        }
      ]
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.carousel
{
  height:100%
}
</style>
