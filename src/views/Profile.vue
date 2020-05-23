<template>
<div>
  <div class="profile">
    <h2>Profile's</h2>
    <b-container class="bv-example-row">
      <b-row>
        <b-col>
          <p class="left-content">
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
    <b-container class="bv-example-row">
      <b-row>
        <b-col>
          <p class="right-content">
            Name：YUMA MINEMOTO
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
  width:40%;
  margin:auto;
  font-size: 25px;
  font-weight: 400;
  padding-bottom: 5px;
  margin-bottom: 50px;
  border-bottom: 1px dotted #888888;
}
.profile {
  margin: 0 auto;
}

.profile p {
  text-align: left;
  font-size: 12px;
  padding: 20px 5px;
  margin-bottom: 15px;
  font-weight: bold;
}

.my-background {
  text-align: center;
  margin-top: 50px;
}
ul {
 width: 100%;
 margin: 0 auto;
 padding: 10px;
 font-size: 15px;
}
ul li {
  list-style: none;
  padding-bottom: 5px;
  border-bottom: dashed 1px #888888;
}

p {
  border: 2px solid #888888;
  margin:0 auto;
}
</style>
