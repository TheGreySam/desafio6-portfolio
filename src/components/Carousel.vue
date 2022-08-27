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
              <div class="card-img-overlay d-block">
                <div class="card-body text-left" >
                  <h5 class="card-title">Sebastián Gómez Letelier</h5>
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
                style="object-position: 5px 20%"
              />
              <div class="card-img-overlay d-block">
                <div class="card-body text-left" >
                  <h5 class="card-title">Diseñador 3d</h5>
                <p class="card-text ">
                  Desarrollo de material audiovisual con 
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
                style="object-position: 5px 10%"
              />
              <div class="card-img-overlay d-block">
                <div class="card-body text-left" >
                  <h5 class="card-title">Card title</h5>
                <p class="card-text ">
                  This is a wider card with supporting text below as a natural
                  lead-in to additional content. This content is a little bit
                  longer.
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