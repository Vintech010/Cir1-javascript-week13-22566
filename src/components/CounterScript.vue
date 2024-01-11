<template>
  <div>
    <h2>Root App</h2>
    <CouterOption></CouterOption>
    <CouterCompos></CouterCompos>
    <CouterScript></CouterScript>
  </div>
</template>

<script>
import CouterOption from './components/CouterOption.vue';
import CouterCompos from './components/CounterCompos.vue'
import CouterScript from './components/CouterScript.vue';

export default {
  name: 'App',
  components: {
    CouterOption,
    CouterCompos,
    CouterScript
  },
}
</script>