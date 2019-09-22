<template>
<div>
  <b-navbar class="navbar" fixed="top" toggleable="lg" type="light" variant="primary">
    <b-navbar-brand href="#"><img src="https://img.icons8.com/ultraviolet/40/000000/ninja-turtle.png" v-b-popover.hover.top="'Home'"></b-navbar-brand>
    

    <b-navbar-toggle target="nav-collapse" right></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav right>
    
      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
        <a href=""><img src="https://img.icons8.com/ultraviolet/40/000000/enter-2.png" v-b-popover.hover.top="'Login'"></a>&nbsp;
      </b-navbar-nav>

    </b-collapse>
  </b-navbar>
</div>
</template>

<script>
export default {
    
}
</script>

<style scoped>

</style>