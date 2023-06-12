<template>
  <div class="home">
    <navigasi/>
    <konten/>
  </div>
</template>

<script>
// @ is an alias to /src
import navigasi from '@/components/navigasi.vue'
import konten from '@/components/konten.vue'

export default {
  name: 'HomeView',
  components: {
    navigasi,
    konten
  }
}
</script>
