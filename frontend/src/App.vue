<script setup>
import RelightViewer from './components/rti/RelightViewer.vue'
import OpenLimeViewer from './components/rti/OpenLimeViewer.vue'
import Collection from './components/Collection.vue'
import Footer from './components/Footer.vue'

</script>

<template>
  <main>
    <!-- <List/> -->
    <!-- <RelightViewer url="test/bilinear18" /> -->
    <!-- <RelightViewer url="test-image" /> -->
     <!-- <OpenLimeViewer url="test-image"/> -->
  <RouterView/>
    <!-- <ArtifactDetail v-bind:artifact="artifactList[0]"/> -->
     <!-- <OpenLimeThumbnail url="test/ptm"/>
     <OpenLimeThumbnail url="test-image"/> -->
  </main>
  <Footer/>
</template>

<style scoped>
main {
  display: flex;
  flex-direction: column;
}
</style>
