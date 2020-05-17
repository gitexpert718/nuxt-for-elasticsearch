<template>
  <div>
    <Reactive />
  </div>
</template>

<script>
  import Vue from "vue";
  import Reactive from "./reactive";
  import ReactiveSearch from "@appbaseio/reactivesearch-vue";

  Vue.use(ReactiveSearch);
  Vue.config.productionTip = false;

  export default {
    components: {
      Reactive
    }
  }  
</script>
