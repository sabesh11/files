<template>
<q-layout view="hHh lpR fFf">

   
    <q-page-container>
        <router-view />
    </q-page-container>

</q-layout>

<!-- <q-layout>
    <q-toolbar class=" fixed-top bg-deep-purple-8 text-white shadow-2 rounded-borders q-pa-sm">
      <span  class="text-white text-h5"><span class="text-red">Edex</span> Tech</span>
      <q-space />

      <q-tabs v-model="tab" shrink>
        <q-tab name="tab1" label="Tab 1" />
        <q-tab name="tab2" label="Tab 2" />
        <q-tab name="tab3" label="Tab 3" />
      </q-tabs>
    </q-toolbar>
    <q-page-container>
    <router-view />
  </q-page-container>
  </q-layout>
  -->
</template>

<script>
import {
    ref
} from 'vue'

export default {
    setup() {
        return {
            drawer: ref(false)
        }
    }
}
</script>
