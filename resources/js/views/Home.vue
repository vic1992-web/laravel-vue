<template>
  <div>
    <section class="jumbotron text-center">
      <div class="container">
        <h1 class="jumbotron-header">Últimos articulos</h1>
      </div>
    </section>
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-md-8">
          <posts></posts>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  mounted() {
    console.log("Component mounted.");
  }
};
</script>
