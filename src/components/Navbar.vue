<template>
    <nav class="navbar navbar-expand-lg shadow navbar-dark navbarbg  ">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Portafolio</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarTogglerDemo02" aria-controls="navbarTogglerDemo02" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarTogglerDemo02">
      <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <router-link to="/" class="nav-link">Home</router-link>
        </li>
        <li class="nav-item">
          <router-link to="/about" class="nav-link">About</router-link>
        </li>
        
      </ul>
      
    </div>
  </div>
</nav>
</template>

<script>
export default {
    name: 'Navbar'
}
</script>