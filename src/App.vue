<script setup>



</script>

<template>

  <!-- Begin Header -->
  <header class="banner">
    <img alt="Vue logo" src="./assets/Milena_A.png"/>
  </header>
  <!-- End Header -->

  <div class="container">
    
    <div>
      <h1>Bienvenidos a mi Perfil</h1>
        <h2>¿Quien soy?</h2>
        <p>Desarrolladora en formación y actualmente estoy cursando un FP en Desarrollo de Aplicaciones Web. Después de 20 años de experiencia en el sector financiero, decidí cambiar de rumbo y adentrarme en el mundo del desarrollo tecnológico, guiada por mi interés en la programación y la creación de soluciones digitales.  Ahora mi objetivo es diseñar y desarrollar software, aprovechando las grandes oportunidades que ofrece el entorno tecnológico actual.</p>
    </div>

    <div>
      <h1>Mi Diseños</h1>
      <div class="gallery">
        <img src="./assets/Avatar_Cocinita_Mimi_muñequita_1.svg" alt="cocina_mimi">
        <img src="./assets/Logo_cocininita_mimi.svg" alt="cocina_mimi">
        <img src="./assets/Logo_Definitivo_1920x480.svg" alt="letra s">
        <img src="./assets/Logo_Famimusic_cascos_pagWeb.svg" alt="famimusic">
        <img src="./assets/Logo_code_magicians_980x468.svg" alt="codemagicians">
        <img src="./assets/Logo_QuickFlix.Team.svg" alt="quickflix">
        <img src="./assets/Logo_Famindex-02.svg" alt="famindex">
      </div>
      

    </div>
    
  </div>


  
</template>

<style>

h1 {
  font: bold;
  text-align: center;
  margin-block-start: 0.5rem;
  margin-block-end: 0.5rem;
}

h2 {
  font: bold;
  text-align: center;
  margin-bottom: 0.5rem;
}

p {
  font-style: italic;
}

header {
  display: flex;
  padding: 1rem;
  justify-content: center;
  
}

header .banner {
  background-color: #f5f5f5;
  padding: 1rem;
}

header img {
  width: 15rem;
}

button {
  cursor: pointer;
}

.container {
  font-size: 1.25rem;
}

.text-container {
  display: flex;
  flex-direction: column;
  text-align: justify;
  /* Alinear el texto de manera uniforme */
  margin-right: 3rem;
}

@media (min-width: 1024px) {
  header {
    padding-right: calc(var(--section-gap) / 2);
  }

.gallery {
    display: flex;
    flex-wrap: wrap;
    gap: 10px; /* Espacio entre imágenes */
    justify-content: center; /* Centrar las imágenes */
    padding: 20px;
}

.gallery img {
    width: 100%;
    max-width: 200px; /* Tamaño máximo de cada imagen */
    height: auto;
    border-radius: 5px; /* Bordes redondeados */
    transition: transform 0.3s ease; /* Efecto al pasar el mouse */
}
  

}
</style>
