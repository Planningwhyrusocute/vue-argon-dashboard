<template>
  <div class="row justify-content-center">
    <div class="col-lg-5 col-md-7">
      <div class="card bg-secondary shadow border-0">
        <div class="card-header bg-transparent pb-5">
          <div class="text-muted text-center mt-2 mb-3">

          </div>
          <div class="btn-wrapper text-center">
            
          </div>
        </div>
        <div class="card-body px-lg-5 py-lg-5">
          <div class="text-center text-muted mb-4">

          </div>
          <form role="form">
            <base-input
              formClasses="input-group-alternative"
              placeholder="Name"
              addon-left-icon="ni ni-hat-3"
              v-model="model.name"
            >

            </base-input>
              
            <base-input
              formClasses="input-group-alternative"
              placeholder="Email"
              type="Email"
              addon-left-icon="ni ni-letter-fold"
              v-model="model.Email"
            >
            </base-input>

            <base-input
              formClasses="input-group-alternative"
              placeholder="Password"
              type="password"
              addon-left-icon="ni ni-lock-circle-open"
              v-model="model.password"
            >
            </base-input>




          </form>
        </div>
      </div>
      <div class="row mt-3">
        <div class="col-6">
          <a href="#" class="text-light">

          </a>
        </div>
        <div class="col-6 text-right">
          <router-link to="/login" class="text-light">

          </router-link>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "register",
  data() {
    return {
      model: {
        name: "",
        email: "",
        password: "",
      },
    };
  },
};
</script>
<style></style>
