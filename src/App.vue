<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import Home from './components/Home.vue'
</script>

<template>


<nav class="bg-white border-gray-200 px-2 sm:px-4 py-2.5 rounded dark:bg-gray-800 fixed" style="z-index:1000; width: 100%;">
  <div class="container flex flex-wrap justify-between items-center mx-auto">
  <a href="https://cabinetamehouga.com/" class="flex items-center">
      <img src="slider/logo.jpg" class="mr-13 h-16 sm:h1-9" alt="Flowbite Logo">
      <span class="self-center text-xl font-semibold whitespace-nowrap dark:text-white">VETERANS FCS</span>
  </a>
  <div class="flex md:order-2">
      <a href="#cv"><button type="button" class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center mr-3 md:mr-0 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">Login In</button></a>
      <button data-collapse-toggle="mobile-menu-4" type="button" class="inline-flex items-center p-2 text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600" aria-controls="mobile-menu-4" aria-expanded="false">
      <span class="sr-only">Open main menu</span>
      <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z" clip-rule="evenodd"></path></svg>
      <svg class="hidden w-6 h-6" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z" clip-rule="evenodd"></path></svg>
    </button>
  </div>
  <div class="hidden justify-between items-center w-full md:flex md:w-auto md:order-1" id="mobile-menu-4">
    <ul class="flex flex-col mt-4 md:flex-row md:space-x-8 md:mt-0 md:text-sm md:font-medium">
      <li>
        <a href="#" class="block py-2 pr-4 pl-3 text-white bg-blue-700 rounded md:bg-transparent md:text-blue-700 md:p-0 dark:text-white" aria-current="page"> Accueil</a>
      </li>
      <li>
        <a href="#matchs" class="block py-2 pr-4 pl-3 text-gray-700 border-b border-gray-100 hover:bg-gray-50 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 md:dark:hover:text-white dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">Matchs</a>
      </li>
      <li>
        <a href="#teams" class="block py-2 pr-4 pl-3 text-gray-700 border-b border-gray-100 hover:bg-gray-50 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 md:dark:hover:text-white dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">Teams</a>
      </li>
      <li>
        <a href="#stats" class="block py-2 pr-4 pl-3 text-gray-700 border-b border-gray-100 hover:bg-gray-50 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 md:dark:hover:text-white dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">Stats</a>
      </li>
       <li>
        <a href="#latests" class="block py-2 pr-4 pl-3 text-gray-700 border-b border-gray-100 hover:bg-gray-50 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 md:dark:hover:text-white dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">Latests</a>
      </li>
      <li>
        <a href="#produits" class="block py-2 pr-4 pl-3 text-gray-700 border-b border-gray-100 hover:bg-gray-50 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 md:dark:hover:text-white dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">Nos Produits</a>
      </li>
       <li>
        <a href="#contact" class="block py-2 pr-4 pl-3 text-gray-700 border-b border-gray-100 hover:bg-gray-50 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 md:dark:hover:text-white dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">Contact</a>
      </li>
    </ul>
  </div>
  </div>
</nav>

<div  class="uk-position-relative uk-visible-toggle uk-light" tabindex="-1" uk-slideshow="animation: push;min-height: 300; max-height: 600;autoplay: true">

    <ul class="uk-slideshow-items mt-20">
        <li>
            <img src="slider/foot1.jpeg" alt="" uk-cover>
            <div class="uk-overlay uk-overlay-primary uk-position-bottom uk-text-center uk-transition-slide-bottom">
                <h3 class="uk-margin-remove uk-heading-medium">UNE EQUIPE <b class="uk-text-danger">SOUDEE </b></h3>
                <p class="uk-margin-remove uk-text-large">La route du développement d'une équipe passe par une équipe soudé</p>
            </div>
        </li>
        <li>
            <img src="slider/foot4.jpeg" alt="" uk-cover>
            <div class="uk-overlay uk-overlay-primary uk-position-bottom uk-text-center uk-transition-slide-bottom">
               <h3 class="uk-margin-remove uk-heading-medium">UNE EQUIPE <b class="uk-text-danger">UNIS DANS L'ADVERSITE</b></h3>
                <p class="uk-margin-remove uk-text-large">Une équipe unis quelques soit les problèmes rencontrés</p>
               </div>
        </li>
         <li>
            <img src="slider/foot7.jpeg" alt="" uk-cover>
            <div class="uk-overlay uk-overlay-primary uk-position-bottom uk-text-center uk-transition-slide-bottom">
               <h3 class="uk-margin-remove uk-heading-medium">UNE EQUIPE <b class="uk-text-danger">VICTORIEUSE </b></h3>
                <p class="uk-margin-remove uk-text-large">La victoire est notre slogan</p>
               </div>
        </li>
    </ul>

    <a class="uk-position-center-left uk-position-small uk-hidden-hover" href="#" uk-slidenav-previous uk-slideshow-item="previous"></a>
    <a class="uk-position-center-right uk-position-small uk-hidden-hover" href="#" uk-slidenav-next uk-slideshow-item="next"></a>

     <ul class="uk-slideshow-nav uk-dotnav uk-position-bottom-center"></ul>

</div>


<section class="uk-section" id="matchs">
    <div class="uk-section uk-section-muted">
    <div class="uk-container">
        <h1 class="propos" uk-parallax="opacity: 0,1,1; y: -100,0,0; x: 100,100,0; scale: 2,1,1; end: 50vh + 50%;"><b>Matchs</b></h1>
        <h2 uk-parallax="opacity: 0,1; y: 100,0; scale: 0.5,1; end: 50vh + 50%;"><i>Ici est présenté l'historique des matchs joués</i></h2>

        <div class="">
            <div class="uk-text-lead">
                <p uk-parallax="opacity: 0,1,1; y: 100,0,0; x: -100,-100,0; scale: 0.5,1,1; end: 50vh + 50%;">En cours de saisie...</p>
            </div>
        </div>

    </div>
</div>
</section>

<div id="teams" class="uk-section-default">
    <div class="uk-section uk-light uk-background-cover" style="background-image: url(slider/dark.jpg)">
        <div class="uk-container">

            <h1 style="font-size:55px" uk-parallax="opacity: 0,1; y: -100,0; scale: 2,1; end: 50vh + 50%;"><b>Teams</b></h1><br>
            <hr>

            
                <div style="text-align: justify;">
                    <ul uk-accordion="collapsible: false">
    <li uk-scrollspy="cls: uk-animation-slide-left; repeat: true">
        <a class="uk-accordion-title" href="#">UNE RESSOURCE HUMAINE QUALIFIEE</a>
        <div class="uk-accordion-content">
            <p>Une ressource humaine qualifiée et disponible constitue le sous-bassement de nos missions d'expertise en exploitation ou en ingénierie.</p>
        </div>
    </li>
    <li uk-scrollspy="cls: uk-animation-slide-left; repeat: true">
        <a class="uk-accordion-title" href="#">ORGANISATION SIMPLIFIEE</a>
        <div class="uk-accordion-content">
            <p>Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor reprehenderit.</p>
        </div>
    </li>
    <li uk-scrollspy="cls: uk-animation-slide-left; repeat: true">
        <a class="uk-accordion-title" href="#">PRISE DE DECISION RAPIDE ET EFFICACE</a>
        <div class="uk-accordion-content">
            <p>Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat proident.</p>
        </div>
    </li>
</ul>
                </div>

        </div>
    </div>
</div>
<section class="uk-section" id="stats">
                    <div class="uk-container">
                        <h1 style="font-size:55px" uk-parallax="opacity: 0,1; y: -100,0; scale: 2,1; end: 50vh + 50%;"><b>Stats</b></h1>
                        <h3 style="font-size:30px" uk-parallax="opacity: 0,1; y: -100,0; scale: 2,1; end: 50vh + 50%;">Sont :</h3><br>
                        <div class="uk-child-width-expand@s uk-text-center" uk-grid="parallax: 150">
                            <div>
                                <div uk-scrollspy="cls: uk-animation-slide-left; repeat: true" class="uk-card uk-card-default uk-card-body uk-grid-margin miss1">
                                    <p>TOTAL DE BUT EN TOUT</p><br>
                                    En cours...
                                </div>
                                <div uk-scrollspy="cls: uk-animation-slide-left; repeat: true" class="uk-card uk-card-default uk-card-body uk-grid-margin miss2">
                                    <p>TOTAL DE BUT DU MATCH DERNIER</p><br>
                                    En cours...
                                </div>
                                <div uk-scrollspy="cls: uk-animation-slide-left; repeat: true" class="uk-card uk-card-default uk-card-body uk-grid-margin miss3">
                                    <p>TOTAL DE BUT DES PENALTY</p><br>
                                    En cours...
                                </div>
                            </div>
                            <div uk-scrollspy="cls: uk-animation-slide-bottom; target: .uk-card; delay: 300; repeat: true">
                                <div class="uk-card uk-card-default uk-card-body uk-grid-margin miss4">
                                    <p>TOTAL DE PASSE EN TOUT</p><br>
                                    En cours...
                                </div>
                                <div class="uk-card uk-card-default uk-card-body uk-grid-margin miss5">
                                    <p>TOTAL DE PASSE DU DERNIER MATCH</p><br>
                                    En cours...
                                </div>
                                <div class="uk-card uk-card-default uk-card-body uk-grid-margin miss6">
                                    <p>TOTAL DE PASSE DU DERNIER MATCH</p><br>
                                    En cours...
                                </div>
                            </div>
                            <div>
                                <div uk-scrollspy="cls: uk-animation-slide-right; repeat: true" class="uk-card uk-card-default uk-card-body uk-grid-margin miss7">
                                    <p>TOTAL DE BUT ENCAISSER</p><br>
                                    En cours...
                                </div>
                                <div uk-scrollspy="cls: uk-animation-slide-right; repeat: true" class="uk-card uk-card-default uk-card-body uk-grid-margin miss8">
                                    <p>TOTAL DE CORNER JOUE</p><br>
                                    En cours...
                                </div>
                                <div uk-scrollspy="cls: uk-animation-slide-right; repeat: true" class="uk-card uk-card-default uk-card-body uk-grid-margin miss9">
                                    <p>TOTAL DE BUT DE PENALTY ENCAISSER</p><br>
                                    En cours...
                                </div>
                            </div>
                        </div>
                    </div>
</section>

<section id="latests" class="uk-section uk-section-secondary uk-light">
    <div class="uk-container">
        <h1 style="font-size:55px" uk-parallax="opacity: 0,1; y: -100,0; scale: 2,1; end: 50vh + 50%;"><b>Latests</b></h1><br>
       <hr>
        <div class="uk-position-relative uk-visible-toggle uk-light" uk-slider>

    <ul class="uk-slider-items uk-grid">
        <li class="uk-width-1-3">
            <div class="uk-panel" tabindex="0" uk-scrollspy="target: > img; cls: uk-animation-fade; delay: 1500">
                <img src="slider/foot2.jpeg" width="1800" height="1200" alt="" class="uk-animation-reverse uk-transform-origin-top-right" uk-scrollspy="cls: uk-animation-kenburns; repeat: true" uk-scrollspy-class="uk-animation-slide-top">
                <div class="uk-position-center uk-text-center">
                    <h2 uk-slider-parallax="x: 100,-100">Heading</h2>
                    <p uk-slider-parallax="x: 200,-200">Lorem ipsum dolor sit amet.</p>
                </div>
            </div>
        </li>
        <li class="uk-width-1-3">
            <div class="uk-panel" uk-scrollspy="target: > img; cls: uk-animation-fade; delay: 1500">
                <img src="slider/foot3.jpeg" width="1800" height="1200" alt="" class="uk-animation-reverse uk-transform-origin-top-right" uk-scrollspy="cls: uk-animation-kenburns; repeat: true" uk-scrollspy-class="uk-animation-slide-bottom">
                <div class="uk-position-center uk-text-center">
                    <h2 uk-slider-parallax="x: 100,-100">Heading</h2>
                    <p uk-slider-parallax="x: 200,-200">Lorem ipsum dolor sit amet.</p>
                </div>
            </div>
        </li>
        <li class="uk-width-1-3">
            <div class="uk-panel" uk-scrollspy="target: > img; cls: uk-animation-fade; delay: 1500">
                <img src="slider/foot5.jpeg" width="1800" height="1200" alt="" class="uk-animation-reverse uk-transform-origin-top-right" uk-scrollspy="cls: uk-animation-kenburns; repeat: true" uk-scrollspy-class="uk-animation-slide-top">
                <div class="uk-position-center uk-text-center">
                    <h2 uk-slider-parallax="x: 100,-100">Heading</h2>
                    <p uk-slider-parallax="x: 200,-200">Lorem ipsum dolor sit amet.</p>
                </div>
            </div>
        </li>
        <li class="uk-width-1-3">
            <div class="uk-panel" uk-scrollspy="target: > img; cls: uk-animation-fade; delay: 1500">
                <img src="slider/foot2.jpeg" width="1800" height="1200" alt="" class="uk-animation-reverse uk-transform-origin-top-right" uk-scrollspy="cls: uk-animation-kenburns; repeat: true" uk-scrollspy-class="uk-animation-slide-bottom">
                <div class="uk-position-center uk-text-center">
                    <h2 uk-slider-parallax="x: 100,-100">Heading</h2>
                    <p uk-slider-parallax="x: 200,-200">Lorem ipsum dolor sit amet.</p>
                </div>
            </div>
        </li>
        <li class="uk-width-1-3">
            <div class="uk-panel" uk-scrollspy="target: > img; cls: uk-animation-fade; delay: 1500">
                <img src="slider/foot3.jpeg" width="1800" height="1200" alt="" class="uk-animation-reverse uk-transform-origin-top-right" uk-scrollspy="cls: uk-animation-kenburns; repeat: true" uk-scrollspy-class="uk-animation-slide-top">
                <div class="uk-position-center uk-text-center">
                    <h2 uk-slider-parallax="x: 100,-100">Heading</h2>
                    <p uk-slider-parallax="x: 200,-200">Lorem ipsum dolor sit amet.</p>
                </div>
            </div>
        </li>
    </ul>

    <a class="uk-position-center-left uk-position-small uk-hidden-hover" href="#" uk-slidenav-previous uk-slider-item="previous"></a>
    <a class="uk-position-center-right uk-position-small uk-hidden-hover" href="#" uk-slidenav-next uk-slider-item="next"></a>

</div>
    </div>
</section>

<section id="produits" class="uk-section  uk-section-muted">
    <div class="uk-container">
        <h1 style="font-size:55px" uk-parallax="opacity: 0,1; y: -100,0; scale: 2,1; end: 50vh + 50%;"><b>Nos Produits</b></h1><br>
        <hr>
        <div class="uk-position-relative uk-visible-toggle uk-light" tabindex="-1" uk-slider>

    <ul class="uk-slider-items uk-child-width-1-2 uk-child-width-1-5@m uk-grid">
        <li>
            <div class="uk-panel" uk-scrollspy="target: > img; cls: uk-animation-fade; delay: 1000">
                <img src="slider/slider1.jpg" width="200" height="100" alt="" class="">
                <div class="uk-position-center uk-panel"><h1>1</h1></div>
            </div>
        </li>
        <li>
            <div class="uk-panel" uk-scrollspy="target: > img; cls: uk-animation-fade; delay: 1500">
                <img src="slider/slider2.jpg" width="200" height="100" alt="" class="">
                <div class="uk-position-center uk-panel"><h1>2</h1></div>
            </div>
        </li>
        <li>
            <div class="uk-panel" uk-scrollspy="target: > img; cls: uk-animation-fade; delay: 2000">
                <img src="slider/slider3.jpg" width="200" height="100" alt="" class="">
                <div class="uk-position-center uk-panel"><h1>3</h1></div>
            </div>
        </li>
        <li>
            <div class="uk-panel" uk-scrollspy="target: > img; cls: uk-animation-fade; delay: 2500">
                <img src="slider/slider4.jpg" width="200" height="100" alt="" class="">
                <div class="uk-position-center uk-panel"><h1>4</h1></div>
            </div>
        </li>
        <li>
            <div class="uk-panel" uk-scrollspy="target: > img; cls: uk-animation-fade; delay: 3000">
                <img src="slider/slider5.jpg" width="200" height="100" alt="" class="">
                <div class="uk-position-center uk-panel"><h1>5</h1></div>
            </div>
        </li>
        <li>
            <div class="uk-panel" uk-scrollspy="target: > img; cls: uk-animation-fade; delay: 3500">
                <img src="slider/slider1.jpg" width="200" height="100" alt="" class="">
                <div class="uk-position-center uk-panel"><h1>6</h1></div>
            </div>
        </li>
        <li>
            <div class="uk-panel" uk-scrollspy="target: > img; cls: uk-animation-fade; delay: 4000">
                <img src="slider/slider2.jpg" width="200" height="100" alt="" class="">
                <div class="uk-position-center uk-panel"><h1>7</h1></div>
            </div>
        </li>
        <li>
            <div class="uk-panel" uk-scrollspy="target: > img; cls: uk-animation-fade; delay: 4500">
                <img src="slider/slider3.jpg" width="200" height="100" alt="" class="">
                <div class="uk-position-center uk-panel"><h1>8</h1></div>
            </div>
        </li>
        <li>
            <div class="uk-panel" uk-scrollspy="target: > img; cls: uk-animation-fade; delay: 5000">
                <img src="slider/slider4.jpg" width="200" height="100" alt="" class="">
                <div class="uk-position-center uk-panel"><h1>9</h1></div>
            </div>
        </li>
        <li>
            <div class="uk-panel" uk-scrollspy="target: > img; cls: uk-animation-fade; delay: 5500">
                <img src="slider/slider5.jpg" width="200" height="100" alt="" class="">
                <div class="uk-position-center uk-panel"><h1>10</h1></div>
            </div>
        </li>
    </ul>

    <a class="uk-position-center-left uk-position-small uk-hidden-hover" href="#" uk-slidenav-previous uk-slider-item="previous"></a>
    <a class="uk-position-center-right uk-position-small uk-hidden-hover" href="#" uk-slidenav-next uk-slider-item="next"></a>

</div>
    </div>
</section>


<section id="contact" class="uk-section  uk-section-muted">
    <div class="uk-container">
        <h1 style="font-size:55px" uk-parallax="opacity: 0,1; y: -100,0; scale: 2,1; end: 50vh + 50%;"><b>Contact</b></h1><br>
        <hr>
        <div class="uk-child-width-1-2 uk-child-width-1-4@s uk-grid-match" uk-grid>
            <div class="uk-animation-toggle" tabindex="0">
                <div class="uk-card uk-card-default uk-card-body uk-animation-shake">
                    <p class="uk-text-center">ADRESSE</p>
                </div>
            </div>
            <div class="uk-animation-toggle" tabindex="0">
                <div class="uk-card uk-card-default uk-card-body uk-animation-shake">
                    <p class="uk-text-center">MAIL</p>
                </div>
            </div>
            <div class="uk-animation-toggle" tabindex="0">
                <div class="uk-card uk-card-default uk-card-body uk-animation-shake">
                    <p class="uk-text-center">NUMERO</p>
                </div>
            </div>
            <div class="uk-animation-toggle" tabindex="0">
                <div class="uk-card uk-card-default uk-card-body uk-animation-shake">
                    <p class="uk-text-center">Shake</p>
                </div>
            </div>
        </div>
    </div>  
</section>




<section class="uk-section uk-section-default uk-preserve-color">
    <div>
    <div class="uk-container">

        <div class="uk-grid-match uk-child-width-expand@m" uk-grid>
            <div>
                <div class="uk-animation-toggle" tabindex="0">
                    <img class="uk-animation-stroke" src="slider/image1.png" width="400" height="400" alt="" uk-svg="stroke-animation: true">
                </div>
            </div>
            <div>
                
<div class="uk-section uk-section-default">
    <div class="uk-container">

        <div class="uk-grid-match uk-child-width-1-3@m" uk-grid>
            <div>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</p>
            </div>
            <div>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</p>
            </div>
            <div>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</p>
            </div>
        </div>

    </div>
</div>


            </div>
        </div>

    </div>
</div>
</section>

</template>


<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0px;
}
</style>