<template>
  <HeaderView />
  <div class="container mx-auto">
    <router-view />
  </div>
</template>
<script>
  import HeaderView from "@/components/Header.vue";

  export default {
    name: "AppView",
    components: { HeaderView },
  };
</script>
