<template>
  <div class="sidebar">
    <b-button v-b-toggle.sidebar-backdrop>Toggle Sidebar</b-button>

    <b-sidebar
      id="sidebar-backdrop"
      title="Sidebar with backdrop"
      :backdrop-variant="variant"
      backdrop
      shadow
    >
      <div class="px-3 py-2">
        <b-form-group label="Backdrop variant" label-for="backdrop-variant">
          <b-form-select id="backdrop-variant" v-model="variant" :options="variants"></b-form-select>
        </b-form-group>
      </div>
    </b-sidebar>
  </div>
</template>

<script>
export default {
  name: 'SideBar',
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style src='./sidebar' lang='scss' scoped/>
