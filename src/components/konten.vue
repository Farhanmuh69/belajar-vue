<template>
    <div class="row flex-lg-row-reverse align-items-center g-5 py-5">
      <div class="col-10 col-sm-8 col-lg-6">
        <img src="../assets/zeus.jpeg" class="bd-placeholder-img bd-placeholder-img-lg featurette-image img-fluid mx-auto ml rounded   " width="500" height="500">
      </div>
      <div class="col-lg-6">
        <h1 class="display-5 fw-bold text-body-emphasis lh-1 mb-3">Responsive left-aligned hero with image</h1>
        <p class="lead">Quickly design and customize responsive mobile-first sites with Bootstrap, the world’s most popular front-end open source toolkit, featuring Sass variables and mixins, responsive grid system, extensive prebuilt components, and powerful JavaScript plugins.</p>
        <div class="button d-grid gap-2 d-md-flex justify-content-md-center">
            <button @click="$router.push('/login')" type="button" class="btn btn-primary btn-lg px-4 me-md-2">SignIn</button>
            <button @click="$router.push('/login')" type="button" class="btn btn-outline-secondary btn-lg px-4" >SignUp</button>
        </div>
      </div>
    </div>
</template>

<script>
export default {
    name : 'konten'
}
</script>

<style>
.ml{
    margin-left: 30px!important;
}
.button{
    margin-left: 30px!important;
    margin-right: 30px!important;

}
</style>