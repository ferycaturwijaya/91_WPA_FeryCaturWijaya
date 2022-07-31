<template>
<MenuUtama/>
 <JudulKembali/>
 
 <div class="container mt-4">
    <div class="row">
        <div class="col-6 col-sm-4 col-md-3" v-for="(daftar_produks, $index) in daftar_produk" :key="$index">
                <GroceryMenu :judul="daftar_produks.title" :harga="daftar_produks.price"/>
        </div>
    </div>
</div>
</template>

<script>
// @ is an alias to /src
import MenuUtama from '@/components/MenuUtama.vue'

import JudulKembali from '@/components/JudulKembali.vue'
import GroceryMenu from '@/components/GroceryMenu.vue'

export default {
  name: 'HomeView',
  data() {
    return {
        daftar_produk: []
    }
  },
  components: {
    MenuUtama,
   
    JudulKembali,
    GroceryMenu
},
mounted() {
      fetch('https://api.storerestapi.com/products')
        .then(response => response.json())
        .then(response => {
            this.daftar_produk = response.data
        })
}
}
</script>