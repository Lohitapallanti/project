<template>
<q-app>
  <q-layout>
<q-content id="top">
    <div class="bg-img">
      <!-- <q-header> -->
      <div class="logo">
        <q-img src="statics/background logo.png"></q-img>
      </div>
     </div>
    <!--<q-drawer
      v-model="leftDrawerOpen"
      show-if-above
      bordered
      content-class="bg-grey-2"
    >
      <q-list>
        <q-item-label header>Essential Links</q-item-label>
        <q-item clickable tag="a" target="_blank" href="https://quasar.dev">
          <q-item-section avatar>
            <q-icon name="icon-ku" />
          </q-item-section>
          <q-item-section>
            <q-item-label>Program 2020</q-item-label>
            <q-item-label caption>Hva skjer på festivalen?</q-item-label>
          </q-item-section>
        </q-item>
        <q-item clickable tag="a" target="_blank" href="https://github.quasar.dev">
          <q-item-section avatar>
            <q-icon name="code" />
          </q-item-section>
          <q-item-section>
            <q-item-label>Billetter</q-item-label>
            <q-item-label caption>Sikre din plass nå!</q-item-label>
          </q-item-section>
        </q-item>
        <q-item clickable tag="a" target="_blank" href="https://chat.quasar.dev">
          <q-item-section avatar>
            <q-icon name="chat" />
          </q-item-section>
          <q-item-section>
            <q-item-label>Spilletider</q-item-label>
            <q-item-label caption>Når spiller de?</q-item-label>
          </q-item-section>
        </q-item>
        <q-item clickable tag="a" target="_blank" href="https://forum.quasar.dev">
          <q-item-section avatar>
            <q-icon name="info" />
          </q-item-section>
          <q-item-section>
            <q-item-label>Info</q-item-label>
            <q-item-label caption>Nyttig informasjon</q-item-label>
          </q-item-section>
        </q-item>
        <q-item clickable tag="a" target="_blank" href="https://twitter.quasar.dev">
          <q-item-section avatar>
            <q-icon name="rss_feed" />
          </q-item-section>
          <q-item-section>
            <q-item-label>Twitter</q-item-label>
            <q-item-label caption>@quasarframework</q-item-label>
          </q-item-section>
        </q-item>
        <q-item clickable tag="a" target="_blank" href="https://facebook.quasar.dev">
          <q-item-section avatar>
            <q-icon name="public" />
          </q-item-section>
          <q-item-section>
            <q-item-label>Facebook</q-item-label>
            <q-item-label caption>@QuasarFramework</q-item-label>
          </q-item-section>
        </q-item>
      </q-list>
    </q-drawer>-->
<q-page-container>
<router-view />
    </q-page-container>
    </q-content>
  </q-layout>
  </q-app>
 </template>

<script>
export default {
  name: 'MyLayout',
  data () {
    return {
      leftDrawerOpen: false
    }
  }
}
</script>

<style lang="scss">
#top,
#bottom {
  position: fixed;
  left: 0;
  right: 0;
  height: 50%;
}
#top {
  top: 0;
}
.bg-img {
  position: relative;
  width: 100%;
  height: 100%;
background-size: cover;
 background-repeat: no-repeat;
  background-position:50% 50%;
  background-image: url("../statics/background image.jpg");
}
.logo {
  position: relative;
  max-width: 300px;
}
</style>
