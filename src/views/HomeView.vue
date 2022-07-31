<template>
<MenuUtama/>
<div class="mt-2">
<HalamanUtama/>
 </div>
 <LangkahPertama/>
 <IklanUtama/>
 <div class="mt-4">
  <BawahUtama/>
 </div>
 
</template>

<script>
// @ is an alias to /src
import MenuUtama from '@/components/MenuUtama.vue'
import HalamanUtama from '../components/HalamanUtama.vue'
import LangkahPertama from '../components/LangkahPertama.vue'
import IklanUtama from '../components/IklanUtama.vue'
import BawahUtama from '@/components/BawahUtama.vue'


export default {
  name: 'HomeView',
  components: {
    MenuUtama,
    HalamanUtama,
    LangkahPertama,
    IklanUtama,
    BawahUtama
}
}
</script>
