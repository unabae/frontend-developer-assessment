<template>
  <div class="container mt-5 py-5">
    <div class="row justify-content-center">
      <div class="col-sm-8">
        <div class="text-center">
          <div class="row g-0">
            <div class="col-md-4">
              <img
                src="./assets/product-smartphone.svg"
                class="img-fluid rounded-start"
                alt="..."
              />
            </div>
            <div class="col-md-8">
              <div class="card-body ms-5 mt-1">
                <h3 class="card-title text-start">{{ cardTitle }}</h3>
                <p class="card-text text-start">
                  {{ cardText }}
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>


<script>
export default {
  props: ["cardTitle", "cardText"],
};
</script>