<template>
    
<!-- <nav class="navbar navbar-expand-lg">
    <div class="container">
        <router-link class="navbar-brand" to="/">
            <img src="https://shop.hypermart.co.id/hypermart/inc/images/material/logo_store.png" alt="" >
        </router-link>
        
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <nav class="navbar-nav me-auto mb-2 mb-lg-0">
          <form class="container-fluid ">
            
    
    
    
    
    
  
            
    
  </form>
</nav>
    </div>
            
            
          
  </div>
</nav> -->
<nav class="navbar navbar-expand-lg">
    <div class="container">
      <router-link class="navbar-brand" to="/"><img src="https://shop.hypermart.co.id/hypermart/inc/images/material/logo_store.png"/></router-link>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <router-link class="btn btn-primary me-3" to="/">Home</router-link>
          </li>
          <li class="nav-item">
            <router-link class="btn btn-primary me-3" to="/about">About</router-link>
          </li>
          <li class="nav-item">
            <router-link class="btn btn-primary me-3" to="/services">Services</router-link>
          </li>
          <li class="nav-item">
            <router-link class="btn btn-primary me-3" to="/our">Our Work</router-link>
          </li>    
        </ul>
          
          
        
        <form class="d-flex" role="search">
          <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
          <button class="btn btn-primary me-3" type="submit">Search</button>
        </form>
      </div>
    </div>
  </nav>


</template>