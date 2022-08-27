<template>
  <div>
    <div class="">
      <div
        id="carouselExampleControls"
        class="carousel slide"
        data-ride="carousel"
      >
        <!-- Diapositivas -->
        <div class="carousel-inner">
          <div class="carousel-item active">
            <div class="card bg-dark text-white footer">
               <img
                class="card-img topimg"
                src="@/assets/img/frontimage1.jpg"
                alt="Card image"
              />
              <div class="card-img-overlay">
                <div class="card-body text-left pt-3" >
                  <h3 class="card-title">Sebastián Gómez Letelier</h3>
                <p class="card-text ">
                  Diseñador 3d, estudiante de informática y aspirante a cineasta, nacido en Alemania y emigrado a Chile con 6 años
                </p>
                
                </div>
              </div>
            </div>
          </div>
          <div class="carousel-item">
            <div class="card bg-dark text-white footer ">
              <img
                class="card-img topimg"
                src="@/assets/img/frontimage2.jpg"
                alt="Card image"
                style="object-position: 5pt 20%"
              />
              <div class="card-img-overlay d-block">
                <div class="card-body pt-3" >
                  <h3 class="card-title">Diseñador 3d</h3>
                <p class="card-text ">
                  Desarrollo de material audiovisual con 
                  
                </p>
                <p>
                  <span><img src="@/assets/img\UE_Logo_Black_Centered.svg" alt="" class="img-fluid m-5" style="width:100pt"></span>
                   <span><img src="@/assets/img\cinema4dlogo.png" alt="" class="img-fluid m-5" style="width:100pt"></span>
                    <span><img src="@/assets/img\Adobe_After_Effects_CC_icon.svg" alt="" class="img-fluid m-5" style="width:100pt"></span>
                     <span><img src="@/assets/img\DaVinci_Resolve_17_logo.svg" alt="" class="img-fluid m-5" style="width:100pt"></span>
                </p>
                </div>
              </div>
            </div>
          </div>
          <div class="carousel-item">
            <div class="card bg-dark text-white footer ">
              <img
                class="card-img topimg"
                src="@/assets/img/frontimage3.jpg"
                alt="Card image"
                style="object-position: 5pt 10%"
              />
              <div class="card-img-overlay w-100">
                <div class="card-body pt-5" >
                   <h3 class="card-title">Estudios</h3>
                   
                <p>
                  
                  <span><img src="@/assets/img\LOGO_UNIACC.png" alt="" class="img-fluid m-5" style="width:100pt"></span>
                  
                   <span><img src="@/assets/img\desafio-logo.png" alt="" class="img-fluid m-5" style="width:100pt"></span>
                </p>
                
                </div>
              </div>
            </div>
          </div>
        </div>
        <!-- Controles -->
        <a
          class="carousel-control-prev"
          href="#carouselExampleControls"
          role="button"
          data-slide="prev"
        >
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="sr-only">Previous</span>
        </a>
        <a
          class="carousel-control-next"
          href="#carouselExampleControls"
          role="button"
          data-slide="next"
        >
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="sr-only">Next</span>
        </a>
      </div>
    </div>
  </div>
</template>