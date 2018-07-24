<template>
  <div>
    <Header/>
    <Profile/>
  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/Header.vue'
import Profile from '@/components/Profile.vue'

export default {
  name: 'home',
  components: {
    Header,
    Profile
  }
}
</script>
