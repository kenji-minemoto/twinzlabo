<template>
<footer>
  <div id="nav">
    <router-link to="/" class="tab" exact>Home</router-link>
    <router-link to="/profile" class="tab" exact>Profile</router-link>
    <router-link to="/gallery" class="tab" exact>Gallery</router-link>
    <router-link to="/contact" class="tab" exact>Contact</router-link>
    <p>© TwinzLabo All rights reserved.</p>
  </div>
</footer>
</template>

<style scoped>
footer {
  min-height: 50vh;
  position: relative;
}
#nav {
  width: 100%;
  padding: 20px 10px 10px 0;
  text-align: center;
  background-color: rgb(241, 241, 241);
  bottom: 0;
  position: absolute;
}

#nav .tab {
  padding-right: 30px;
  color: black;
  font-weight: bold;
  font-size: 10px;
}

#nav a.router-link-exact-active {
  color: rgb(163, 163, 163);
}

#nav p {
  font-size: 7px;
}
</style>
