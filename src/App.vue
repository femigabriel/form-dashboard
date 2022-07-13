<template>
  <div id="app">
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/line-awesome/1.3.0/line-awesome/css/line-awesome.min.css"
    />
    <SideBar />
    <SettingPage class="setting-page" />
    <FormPage class="form-page" />
  </div>
</template>

<script>
import SideBar from "./components/SideBar.vue";
import SettingPage from "./components/SettingPage.vue";
import FormPage from "./components/FormPage.vue";

export default {
  name: "App",
  components: {
    SideBar,
    SettingPage,
    FormPage,
  },
};
</script>

<style>

@import url("https://fonts.googleapis.com/css2?family=Rubik:wght@400;500;600;700&display=swap");
*,
*::before,
*::after {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  list-style: none;
  list-style-type: none;
  text-decoration: none;
}
body {
  font-family: "Rubik", ui-sans-serif, system-ui, -apple-system, sans-serif;
  font-weight: 400;
  line-height: 1.5;
}
.form-page {
  flex-grow: 1;
  /* width: 1270px; */
}
#app {
  display: flex;
  width: 100%;
}
@media only screen and (max-width: 780px) {
#app{ 
   /* width: 90%; */
  }
}
</style>
