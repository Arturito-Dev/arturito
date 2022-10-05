<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
</script>
<template>
  <div class="mt-4">
    <header style="width: 100%">
      <div class="header-presentation w-full text-center">
        <img src="/logo.png" alt="logo arturito" />
        <h3 class="header-title-app">Arturito</h3>
      </div>
    </header>
    <div class="container mx-auto">
      <h2>Calidad de traducción insuperable gracias a una tecnología con IA a la
        vanguardia</h2>
      <p>
         METER FLORO
      </p>
    </div>
    <div class="body-content container mx-auto mt-5">
      <div class="card-custom">
        <div class="card-custom-header flex">
          <select class="select-custom">
            <option value="0" disabled selected>Seleccione</option>
            <option value="1">Shipibo</option>
          </select>
          <svg width="20" height="20" viewBox="0 0 20 20" fill="none">
            <path
              d="M5 13.8317L6.57731 12.2972V15.3661L5 13.8317ZM5 13.8317H14.5"
              stroke="currentColor"
              stroke-width="2"
            ></path>
            <path
              d="M14.5 6.53448L12.9227 5V8.06897L14.5 6.53448ZM14.5 6.53448H5"
              stroke="currentColor"
              stroke-width="2"
            ></path>
          </svg>
          <select class="select-custom">
            <option value="0" disabled selected>Seleccione</option>
            <option value="1">Ingles</option>
            <option value="1">Español</option>
          </select>
        </div>
        <div class="card-custom-body flex">
          <textarea
            class="text-area-custom"
            name=""
            id=""
            cols="30"
            rows="10"
          ></textarea>
          <textarea
            class="text-area-custom"
            id=""
            cols="30"
            rows="10"
          ></textarea>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
* {
  font-family: "robotoCondense";
}
.header-presentation {
  justify-content: center;
}
.card-custom-header svg:hover {
  color: #628dbb;
  transition: ease 0.3s;
}
.header-presentation img {
  margin: auto;
  width: 12rem;
}
.header-title-app {
  font-size: 44px;
}
.select-custom {
  border: none;
  background-color: transparent;
}
.select-custom:nth-child(1) {
  margin-left: 12px;
  margin-bottom: 8px;
}
.select-custom:nth-child(3) {
  margin-right: 12px;
  margin-bottom: 8px;
}
h2{
  margin-top: 25px;
  margin-bottom: 12px;
  text-align: center;
  font-size: 23px;
  font-weight: bold;
}
p{
  font-size: 18px;
  text-justify: inter-word;
  margin-bottom: 3rem;
}
.select-custom:focus {
  outline: none;
}
.select-custom:hover {
  color: #628dbb;
  transition: 0.3s ease;
}
.card-custom-header {
  justify-content: space-between;
}
.body-content {
  padding-top: 8px;
  max-width: 60%;
  border: solid 1px #235678;
  border-top-left-radius: 12px;
  border-top-right-radius: 12px;
  border-bottom-right-radius: 12px;
  border-bottom-left-radius: 12px;
  box-shadow: .5px .5px .9px #79A6D8;
}
.card-custom-body {
  gap: 4%;
  width: 100%;
}
.text-area-custom {
  padding: 0.5rem;
}
.text-area-custom:nth-child(1) {
  resize: none;
  width: 48%;
  border-bottom-left-radius: 12px;
}
.text-area-custom:nth-child(2) {
  resize: none;
  width: 48%;
  border-bottom-right-radius: 12px;
}
.text-area-custom:focus {
  outline: 1px solid #fcb51f;
}
</style>
