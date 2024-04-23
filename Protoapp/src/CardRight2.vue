<template>
  <div class="container mt-5 py-5">
    <div class="row justify-content-center">
      <div class="col-sm-8">
        <div class="text-center">
          <div class="row g-0">
            <div class="col-md-8">
              <div class="card-body me-4">
                <h3 class="card-title text-end"> {{ cardTitle }} </h3>
                <p class="card-text text-end">
                  {{ cardText }}
                </p>
              </div>
            </div>
            <div class="col-md-4">
              <img src="./assets/product-work.svg" class="img-fluid rounded-start" alt="...">
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>


<script>
export default {
    props: ['cardTitle', 'cardText']
};
</script>