<template>
  <div class="main">
    <div class="menu">
      <span>Music</span>
      <i>icon</i>
      <button>+</button>
    </div>
    <div class="list">
      <h2>title1</h2>
      <ul  class="carouselList">
        <li v-for="(card, index) in title1" :key="index">
          <img
           aria-hidden="false"
           draggable="false"
           loading="lazy"
           :src="card.srcImg"
           alt="" 
           width="100%" height="100%">

           <span>{{card.name}}</span>
        </li>
      </ul>
    </div>

     <div class="list">
      <h2>title3</h2>
      <ul  class="carouselList">
        <li v-for="(card, index) in title1" :key="index">
          <img
           aria-hidden="false"
           draggable="false"
           loading="lazy"
           :src="card.srcImg"
           alt="" 
           width="100%" height="100%">

           <span>{{card.name}}</span>
        </li>
      </ul>
    </div>

     <div class="list">
      <h2>title2</h2>
      <ul  class="carouselList">
        <li v-for="(card, index) in title1" :key="index">
          <img
           aria-hidden="false"
           draggable="false"
           loading="lazy"
           :src="card.srcImg"
           alt="" 
           width="100%" height="100%">

           <span>{{card.name}}</span>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
  data() {
    return {
      title1: 
      [
        {
          name: 'name1',
          srcImg: 'https://lite-images-i.scdn.co/image/ab67706f00000002f423d847625bff47ad10de59',
          link: '',
        },
        {
          name: 'name2',
          srcImg: 'https://lite-images-i.scdn.co/image/ab67706f00000002f423d847625bff47ad10de59',
          link: '',
        },
        {
          name: 'name3',
          srcImg: 'https://lite-images-i.scdn.co/image/ab67706f00000002f423d847625bff47ad10de59',
          link: '',
        },
        {
          name: 'name4',
          srcImg: 'https://lite-images-i.scdn.co/image/ab67706f00000002f423d847625bff47ad10de59',
          link: '',
        },
        {
          name: 'name5',
          srcImg: 'https://lite-images-i.scdn.co/image/ab67706f00000002f423d847625bff47ad10de59',
          link: '',
        },
        {
          name: 'name6',
          srcImg: 'https://lite-images-i.scdn.co/image/ab67706f00000002f423d847625bff47ad10de59',
          link: '',
        },
        {
          name: 'name7',
          srcImg: 'https://lite-images-i.scdn.co/image/ab67706f00000002f423d847625bff47ad10de59',
          link: '',
        }
      ]
    }
  },
}
</script>

<style lang="scss" scoped>
  @import '../assets/sass/main.scss';
</style>