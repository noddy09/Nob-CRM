<template>
  <div>
    <Navbar/>
    
    <section class="section">
      <router-view/>
    </section>
  </div>
</template>

<script>
  import Navbar from './components/layouts/Navbar';

  export default{
    name: 'App',
    components: {
      Navbar
    }
  }

</script>

<style lang="scss">
@import '../node_modules/bulma';
.is-orange {
    background-color: #ffa500;
    border-color: transparent;
    color: #fff;
}
</style>
