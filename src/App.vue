<template>
  <div id="app">
    <ToDo />
  </div>
</template>

<script>
import ToDo from "./components/ToDo";

export default {
  name: "App",
  components: {
    ToDo,
  },
};
</script>

<style>
#app {
  background-color: #ffeaa7;
  height: 100%;
  min-height: 80vh;
  padding: 3rem;
  box-sizing: border-box;
  display: flex;
  justify-content: center;
  align-items: center;
  color: hsl(198, 1%, 29%);
  font-family: "Architects Daughter", cursive;
  text-align: center;
  font-size: 110%;
}
</style>
