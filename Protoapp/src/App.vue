<script>
import AppStoreVue from "./AppStore.vue";
import ContentVue from "./Content.vue";
import HeaderVue from "./Header.vue";
import NavBarVue from "./NavBar.vue";

export default {
  components: {
    HeaderVue,
    NavBarVue,
    AppStoreVue,
    ContentVue,
  },
};
</script>

<template>
  <div class="app">
    <NavBarVue />
    <HeaderVue />
    <AppStoreVue />
    <ContentVue
      title="Meet Protoapp"
      body="The app lorem ipsum is common placeholder text used to demonstrate the graphic elements of a document or visual presentation."
    />
  </div>
</template>
