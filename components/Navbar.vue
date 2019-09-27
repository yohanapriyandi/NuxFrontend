<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
  <nuxt-link class="navbar-brand" to="/"> YOHAN APIYANDI</nuxt-link>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav">
      <li class="nav-item active">
        <nuxt-link class="nav-link" to="/"> Home</nuxt-link>
      </li>
      <li class="nav-item">
        <nuxt-link class="nav-link" to="/about"> About</nuxt-link>
      </li>          
      <li class="nav-item">
        <nuxt-link class="nav-link" to="/projects"> Projects</nuxt-link>
      </li>          
      <li class="nav-item">
        <nuxt-link class="nav-link" to="/experience"> Download CV</nuxt-link>
      </li>          
      <li class="nav-item">
        <nuxt-link class="nav-link" to="/contact"> Contact</nuxt-link>
      </li>          
    </ul>
  </div>
</nav>
</template>