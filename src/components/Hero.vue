<template>
    <div class="hero">
        <!-- desktop -->
        <div class="d-none d-md-block">
            <div class="row mt-4">
                <div class="col-md-6">
                    <div class="d-flex h-100">
                        <div class="justify-content-center align-self-center">
                            <h2><strong>Delicious Foods</strong> in your Gadget.</h2>
                            <p>Ayo segera pilih pesanan favorit Anda.</p>
                            <router-link to="/foods" class="btn btn-lg btn-success"><b-icon-arrow-right class="mr-2"></b-icon-arrow-right>Order</router-link>
                        </div>
                    </div>
                </div>
                <div class="col-md-6">
                    <img src="../assets/img/hero.png" width="100%" alt="">
                </div>
            </div>
        </div>
        
        <!-- mobile -->
        <div class="d-sm-block d-md-none">
            <div class="row mt-4">
                <div class="col-md-6 mb-3">
                        <img src="../assets/img/hero.png" width="100%" alt="">
                    </div>
                <div class="col-md-6">
                    <div class="d-flex h-100">
                        <div class="justify-content-center align-self-center">
                            <h2><strong>Delicious Foods</strong> in your Gadget.</h2>
                            <p>Ayo segera pilih pesanan favorit Anda.</p>
                            <router-link to="/foods" class="btn btn-lg btn-success"><b-icon-arrow-right class="mr-2"></b-icon-arrow-right>Order</router-link>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        
    </div>
</template>
<script>
export default {
    name: 'deliciousFood'
}
</script>
<style>
</style>