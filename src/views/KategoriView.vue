<template>
<MenuUtama/>
 <JudulJenis/>
 <div class="container mt-4">
    <div class="row">
      <JenisBarang/>
    </div>
  </div>
  
           
</template>

<script>
// @ is an alias to /src
import MenuUtama from '@/components/MenuUtama.vue'
import JenisBarang from '../components/JenisBarang.vue'
import JudulJenis from '../components/JudulJenis.vue'

export default {
  name: 'HomeView',
  components: {
    MenuUtama,
    JenisBarang,
    JudulJenis
}
}
</script>
