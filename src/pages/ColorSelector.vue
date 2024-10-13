
<template>
    <div>
      <label for="color">Selecciona un color:</label>
      <select v-model="selectedColor">
        <option value="gray">Gris</option>
        <option value="red">Rojo</option>
        <option value="yellow">Amarillo</option>
        <option value="green">Verde</option>
      </select>
  
      <TrafficLight :color="selectedColor" />
    </div>
  </template>
  
  <script>
  import TrafficLight from '@/components/TrafficLight.vue';
  
  export default {
    components: { TrafficLight },
    data() {
      return {
        selectedColor: 'gray',
      };
    },
  };
  </script>