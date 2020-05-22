<template>
<div>
  <h2>Profile</h2>
  <div class="profile">
    <b-container>
      <b-row>
        <!-- <b-col>
          <b-col>
            <div v-for="(item, i) in items" class="images" :key="i">
              <b-img class="top-image" :src="item.imageUrl" thumbnail fluid alt="thumbnail"></b-img>
            </div>
          </b-col>
        </b-col> -->
        <b-col>
          <p>
            Name：KENJI MINEMOTO
            <br><br>Located：Tokyo
            <br><br>Contact：kenji_cat_15@yahoo.co.jp
            <br><br>Business Details：Web Design & Coding
            <br><br>Coding Languages：HTML, CSS, Javascript, Ruby
            <br><br>Application Frameworks：Ruby on Rails, Vue.js
          </p>
        </b-col>
      </b-row>
    </b-container>
  </div>
  <div class="my-background">
    <h2>Background</h2>
    <ul>
      <li>In 2018.<br><br>Graduated from University</li>
      <li><br><br>~Presently.<br><br>3 years of experience in Web design and cording</li>
    </ul>
  </div>
</div>
</template>

<script>
// export default {
//   data () {
//     return {
//       items: [
//         { imageUrl: require('@/assets/images/home_image.png') }
//       ]
//     }
//   }
// }
</script>

<style scoped>
h2 {
  text-align: center;
  padding-top: 50px;
  padding-bottom: 80px;
  font-size: 50px;
  font-weight: 100;
}
.profile {
  margin: 0 auto;
}
.profile img {
  border-radius: 20em;
  width: 60%;
  height: 60%;
  padding: 0;
}

.profile p {
  text-align: left;
  font-size: 20px;
  padding: 20px 0 20px 50px;
  border-radius: 3em;
}

.my-background {
  margin-top: 50px;
  text-align: center;
}
 ul {
   width: 50%;
   margin: 0 auto;
   padding: 10px;
   font-size: 20px;
 }
ul li {
  list-style: none;
  padding-top: 10px;
  padding-bottom: 10px;
  border-bottom: dashed 3px #888888;
}

p {
  opacity: .8;
  background: linear-gradient(124deg, #ff2400, #e81d1d, #e8b71d, #e3e81d, #1de840, #1ddde8, #2b1de8, #dd00f3, #dd00f3);
  background-size: 1800% 1800%;

  -webkit-animation: rainbow 18s ease infinite;
  -z-animation: rainbow 18s ease infinite;
  -o-animation: rainbow 18s ease infinite;
    animation: rainbow 18s ease infinite;}

  @-webkit-keyframes rainbow {
      0%{background-position:0% 82%}
      50%{background-position:100% 19%}
      100%{background-position:0% 82%}
  }
  @-moz-keyframes rainbow {
      0%{background-position:0% 82%}
      50%{background-position:100% 19%}
      100%{background-position:0% 82%}
  }
  @-o-keyframes rainbow {
      0%{background-position:0% 82%}
      50%{background-position:100% 19%}
      100%{background-position:0% 82%}
  }
  @keyframes rainbow {
      0%{background-position:0% 82%}
      50%{background-position:100% 19%}
      100%{background-position:0% 82%}
}
</style>
