<template>
  <div id="app">
    <img id="logo" alt="Vue logo" src="./assets/logo.png" />
    <router-link class="navlink" to="/helloworld">vue</router-link>
    <router-link class="navlink" to="/about">about</router-link>
    <router-link class="navlink" to="/books">books</router-link>
    <router-link class="navlink" to="/contact">contact</router-link>
    <router-link class="navlink" to="/declarativeRendering"
      >declarativeRendering</router-link
    >
    <router-link class="navlink" to="/vbindTitle">vbindTitle</router-link>
    <router-link class="navlink" to="/ConditionalsandLoops"
      >ConditionalsandLoops</router-link
    >
    <router-link class="navlink" to="/userImput">userImput</router-link>
    <router-link class="navlink" to="/importComponent"
      >importComponent</router-link
    >
    <router-link class="navlink" to="/passingProps">passingProps</router-link>
    <router-link class="navlink" to="/watcchAndComputed"
      >watcchAndComputed</router-link
    >
    <router-link class="navlink" to="/SpecialIsKeyword">SpecialIsKeyword</router-link>
    <router-link class="navlink" to="/accordion">accordion</router-link>
    <router-link class="navlink" to="/checkboxes">checkboxes</router-link>
    <router-link class="navlink" to="/mediumDotComModal">mediumDotComModal</router-link>
    <router-link class="navlink" to="/sass">sass</router-link>
    <router-link class="navlink" to="/OfficialVuemodal">OfficialVuemodal</router-link>
    <router-link class="navlink" to="/slotparent">slotparent</router-link>
    <router-link class="navlink" to="/classAndStyleBindings">classAndStyleBindings</router-link>
    <router-link class="navlink" to="/simpleCssModal">simpleCssModal</router-link>
    <router-link class="navlink" to="/profileSearch">profileSearch</router-link>
    <router-link class="navlink" to="/collapsable">collapsable</router-link>
    <router-link class="navlink" to="/search">search</router-link>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: "App",
  components: {},
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
#logo {
  display: flex;
  margin: auto;
}
.navlink {
  padding: 6px;
  border-radius: 6px;
  margin: 1px;
  display: inline-block;
}
</style>
