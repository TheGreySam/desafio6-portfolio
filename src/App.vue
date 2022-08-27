<template>
  <div id="app">
    <Navbar />
    <router-view/>
    <Footer />
  </div>
</template>
<script>
import Navbar from '@/components/Navbar.vue'

import Footer from '@/components/Footer.vue';

export default {
  name: 'App',
  components: {
    Navbar,
    Footer
}
}
</script>


<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  
}

body {
 
  //background-image: linear-gradient(to bottom, #b1f7e3c8, #72799174, #7e4fcae9), url('https://source.unsplash.com/600x900/?tree,nature');
  //background-size: cover;
  		background: linear-gradient(-45deg, #b1f7e3c8, #72799174, #7e4fcae9);
	background-size: 200% 200%;
	animation: gradient 25s ease infinite;

	
}
@keyframes gradient {
	0% {
		background-position: 0% 50%;
	}
	50% {
		background-position: 100% 50%;
	}
	100% {
		background-position: 0% 50%;
	}
}
.wrapper {
  margin: 10vh;
}
.topimg {
  width: 100%;
  height: 30vw;
  object-fit: cover;
}
.navbarbg {
  //color: white;
  background: rgb(35, 79, 109);
        background: linear-gradient(
          0deg,
          rgba(109, 117, 122, 0.5) 0%,
          rgba(4, 69, 114, 1) 100%
        );
  border: none;
  transition: all 500ms cubic-bezier(0.19, 1, 0.22, 1);
 
  &:hover {
      transform: height(1.2px);
      box-shadow: 0 0 5px 5px rgba(0, 0, 0, 0.7);
      background-size: 130%;
      transition: background .8s ease-in-out, ;
      background: rgb(28, 155, 239);
        background: linear-gradient(
          0deg,
          rgba(4, 69, 114, 1) 100%
          rgba(4, 69, 114, 0.5) 0%,
          
        );

      
    }
}

.card {
  border: none;
  transition: all 500ms cubic-bezier(0.19, 1, 0.22, 1);
  overflow: hidden;
  
  min-height: 450px;
  

  @media (max-width: 768px) {
    min-height: 350px;
  }

  @media (max-width: 420px) {
    min-height: 300px;
  }

  &.card-has-bg {
    transition: all 500ms cubic-bezier(0.19, 1, 0.22, 1);
    background-size: 120%;
    background-repeat: no-repeat;
    background-position: center center;
    &:before {
      content: "";
      position: absolute;
      top: 0;
      right: 0;
      bottom: 0;
      left: 0;
      background: inherit;
      -webkit-filter: grayscale(1);
      -moz-filter: grayscale(100%);
      -ms-filter: grayscale(100%);
      -o-filter: grayscale(100%);
      filter: grayscale(100%);
    }

    &:hover {
      transform: scale(0.98);
      box-shadow: 0 0 5px -2px rgba(0, 0, 0, 0.3);
      background-size: 130%;
      transition: all 500ms cubic-bezier(0.19, 1, 0.22, 1);

      .card-img-overlay {
        transition: all 800ms cubic-bezier(0.19, 1, 0.22, 1);
        background: rgb(35, 79, 109);
        background: linear-gradient(
          0deg,
          rgba(4, 69, 114, 0.5) 0%,
          rgba(4, 69, 114, 1) 100%
        );
      }
    }
  }
  .card-footer {
    background: none;
    border-top: none;
    .media {
      img {
        border: solid 3px rgba(255, 255, 255, 0.3);
      }
    }
  }
  .card-meta {
    color: #26bd75;
  }
  .card-body {
    transition: all 500ms cubic-bezier(0.19, 1, 0.22, 1);
  }
  &:hover {
    .card-body {
      margin-top: 30px;
      transition: all 800ms cubic-bezier(0.19, 1, 0.22, 1);
    }
    cursor: pointer;
    transition: all 800ms cubic-bezier(0.19, 1, 0.22, 1);
  }
  .card-img-overlay {
    transition: all 800ms cubic-bezier(0.19, 1, 0.22, 1);
    background: rgb(35, 79, 109);
    background: linear-gradient(
      0deg,
      rgba(35, 79, 109, 0.3785889355742297) 0%,
      rgba(69, 95, 113, 1) 100%
    );
  }
}
@media (max-width: 767px) {
}

.footer {
  border: none;
  transition: all 500ms cubic-bezier(0.19, 1, 0.22, 1);
  overflow: hidden;

  min-height: 450px;
  &:hover {
      
      box-shadow: 0 0 5px -2px rgba(0, 0, 0, 0.3);
      background-size: 130%;
      transition: all 500ms cubic-bezier(0.19, 1, 0.22, 1);

      .card-img-overlay {
        transition: all 800ms cubic-bezier(0.19, 1, 0.22, 1);
        background: rgb(35, 79, 109);
        background: linear-gradient(
          0deg,
          rgba(4, 69, 114, 0.5) 0%,
          rgba(4, 69, 114, 1) 100%
        );
      }
    }
}
</style>
