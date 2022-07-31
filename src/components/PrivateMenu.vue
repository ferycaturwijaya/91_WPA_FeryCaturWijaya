<template>
   <div class="card mb-2">
        <img src="https://shop.hypermart.co.id/hypermart/files/dept/26.jpg" class="card-img-top" alt="...">
            <div class="card-body">
                <h5 class="card-title">{{judul}}</h5>
                    <p class="card-text">Rp.{{harga}}.000</p>
                    <a href="#" class="btn btn-primary">Beli</a>
            </div>
    </div>
</template> 

<script>
export default {
    props: ['judul', 'harga']
}
</script>