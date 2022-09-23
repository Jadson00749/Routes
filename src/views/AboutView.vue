<template>
  <div>
   <router-link to="/">Home</router-link>
   <router-link to="/">About</router-link> 
    <router-view />
  </div>
</template>

<script>
export default {
  name: 'AboutView'
}
</script>

