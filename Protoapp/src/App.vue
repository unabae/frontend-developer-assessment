<script>
import AppStoreVue from "./AppStore.vue";
import CardVueRight from './CardRight.vue';
import ContentVue from "./Content.vue";
import HeaderVue from "./Header.vue";
import NavBarVue from "./NavBar.vue";

export default {
  components: {
    HeaderVue,
    NavBarVue,
    AppStoreVue,
    ContentVue,
    CardVueRight
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
    <CardVueRight
      cardTitle="Discover"
      cardText="Get information on using these guidelines whenever you are using therefore they have the same style and quality."
    />
  </div>
</template>
