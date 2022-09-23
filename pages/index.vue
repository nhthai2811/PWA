<template>
  <div class="main">
    <div>
      <h2>title1</h2>
      <ul  class="carouselList">
        <li v-for="card in title1">
          <img
           aria-hidden="false"
           draggable="false"
           loading="lazy"
           :src="card.srcImg"
           alt="" 
           width="100%" height="100%">

           <h7>{{card.name}}</h7>
        </li>
      </ul>
    </div>

     <div>
      <h2>title3</h2>
      <ul  class="carouselList">
        <li v-for="card in title1">
          <img
           aria-hidden="false"
           draggable="false"
           loading="lazy"
           :src="card.srcImg"
           alt="" 
           width="100%" height="100%">

           <h7>{{card.name}}</h7>
        </li>
      </ul>
    </div>

     <div>
      <h2>title2</h2>
      <ul  class="carouselList">
        <li v-for="card in title1">
          <img
           aria-hidden="false"
           draggable="false"
           loading="lazy"
           :src="card.srcImg"
           alt="" 
           width="100%" height="100%">

           <h7>{{card.name}}</h7>
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
  body {
    width: auto;
    height: auto;
  }
  .carouselList {
    margin: 0px;
    display: flex;
    flex-flow: row nowrap;
    overflow: auto hidden;
    padding: 0px;


    li {
      list-style: none;
      flex:0 0 auto;
      margin: 0px 8px;
      position: relative;
      width: 40%;
      text-align: center;
    }
  }
  .carouselList::-webkit-scrollbar {
    display: none;
  }
</style>