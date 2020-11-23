<template>
  <div id="app">
    <PictureSection />
    <MenuSection />
    <ContainerSection />
    <WordingSection />
    <FooterSection />
  </div>
</template>

<script>
import PictureSection from './components/PictureSection.vue'
import MenuSection from './components/MenuSection.vue'
import ContainerSection from './components/ContainerSection.vue'
import WordingSection from './components/WordingSection.vue'
import FooterSection from './components/FooterSection.vue'

export default {
  name: 'App',
  components: {
    PictureSection,
    MenuSection,
    ContainerSection,
    WordingSection,
    FooterSection
  }
}
</script>

<style lang="scss">
  @import 'styles/main.scss';
</style>
