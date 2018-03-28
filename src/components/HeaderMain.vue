<template>
   <div class="header">
    <div class="">
    <md-avatar>
     <img src="https://cdn4.iconfinder.com/data/icons/social-media-icons-the-circle-set/48/instagram_circle-128.png" alt="">
    </md-avatar>
    </div>
    
    <div class="">
      <md-menu md-direction="bottom-end">
      <md-button md-menu-trigger>
        <md-icon>menu</md-icon>
      </md-button>

      <md-menu-content>
        <md-menu-item>My Item 1</md-menu-item>
        <md-menu-item>My Item 2</md-menu-item>
        <md-menu-item>My Item 3</md-menu-item>
      </md-menu-content>
    </md-menu>
    </div>
  </div>
</template>

<script>
export default {
  name: "HeaderMain"
};
</script>

<style>
.header {
  display: flex;
  justify-content: space-between;
}
</style>
