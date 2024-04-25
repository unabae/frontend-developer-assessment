<script>
import AppStoreVue from "./AppStore.vue";
import CardVueRight from "./CardRight.vue";
import ContentVue from "./Content.vue";
import HeaderVue from "./Header.vue";
import NavBarVue from "./NavBar.vue";
import LeftCardVue from "./LeftCard.vue";
import CardVueRight2 from "./CardRight2.vue";
import Content3Vue from './Content3.vue';
import FooterVue from './Footer.vue';
import Footer2Vue from './Footer2.vue';

export default {
  components: {
    HeaderVue,
    NavBarVue,
    AppStoreVue,
    ContentVue,
    CardVueRight,
    LeftCardVue,
    CardVueRight2,
    Content3Vue,
    FooterVue,
    Footer2Vue
  },
};
</script>

<template>
  <div class="app">
    <NavBarVue />
    <HeaderVue />
    <AppStoreVue class="pb-5"/>
    <ContentVue class="pt-5"
      title="Meet Protoapp"
      body="The app lorem ipsum is common placeholder text used to demonstrate the graphic elements of a document or visual presentation."
    />
    <CardVueRight
      cardTitle="Discover"
      cardText="Get information on using these guidelines whenever you are using therefore they have the same style and quality."
    />
    <LeftCardVue
      cardTitle="Augmented"
      cardText="Word salad often arouses curiosity due to its seemingly intelligent and tasteful play on words."
    />
    <CardVueRight2
      cardTitle="Endless Possibilities"
      cardText="Management Systems shouldn't be a bore. Run out of words? heres some lorem ipsum: Lorem ipsum dolor sit amet."
    />
    <ContentVue
      class="py-5 bg-blue text-white"
      title="Deep dive. Ready"
      body="So are we. Unless. You're. Not. Word filler."
    />
    <AppStoreVue class="bg-blue pb-5"/>
    <ContentVue class="my-5"
      title="Last Call to Action"
      body="Another section content goes here"
    />
    <Content3Vue />
    <Footer class="imgfooter mt-3"/>
    <Footer2Vue />
  </div>
</template>
