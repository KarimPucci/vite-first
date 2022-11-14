<script>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import HelloWorld from './components/HelloWorld.vue'
// importiamo il file del componente
import AppTitle from './components/AppTitle.vue';
import SecondComponent from './components/SecondComponent.vue';
// all'interno del componente "padre" bisogna dichiarare quale componente si importa
export default {
  components: { AppTitle, SecondComponent }
}
</script>

<template>
  <app-title />
  <second-component />
</template>

