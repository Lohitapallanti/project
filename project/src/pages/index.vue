<template>
<q-page>
  <q-list>
    <div id="bottom">
    <q-item clickable tag="a" target="_blank" href="https://quasar.dev" class="q-pa-md">
  <q-item-section>
    <div class="row program">
          <q-item-label class="col">Program 2020</q-item-label>
       </div>
       </q-item-section>
        </q-item>
        <q-item clickable tag="a" target="_blank" href="https://quasar.dev" class="q-pa-md">
  <q-item-section>
    <div class="row">
      <div class="col-6">
        <q-item-label class="ml-2 belooo">Billetter</q-item-label>
        </div>
          <div class="col-6">
             <q-item-label class="ml-2 belooo">Spilletider</q-item-label>
            </div>
         </div>
         </q-item-section>
         </q-item>
          <q-item clickable tag="a" target="_blank" href="https://quasar.dev" class="q-pa-md">
<q-item-section>
   <div class="row">
     <div class="col-6">
        <q-item-label class="ml-2 belooo">Før og etter</q-item-label>
       </div>
        <div class="col-6">
           <q-item-label class="ml-2 belooo">Info</q-item-label>
          </div>
     </div>
  </q-item-section>
</q-item>
 </div>
 </q-list>
</q-page>
</template>

<script>
export default {
  name: 'PageIndex',
  data () {
    return {
    }
  }
}
</script>

<style lang="scss">
.ml-2 {
  margin-left: 8px;
}
.belooo {
  padding: 20px;
  text-align: center;
  font-weight: bold;
  font-size: 20px;
  background: white;
}
#top,
#bottom {
position: fixed;
  left: 0;
  right: 0;
  height: 50%;
}
#bottom {
  bottom: 0;
  background-color: black;
}
.program {
  background: white;
  padding: 20px;
  text-align: center;
  font-weight: bold;
  font-size: 20px;
}
</style>
