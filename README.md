<!doctype html>
<html>
<head>
  <meta charset="utf-8">
  <title>IABFH</title>
  <link rel="stylesheet" href="css/example.css">
  <link rel="stylesheet" href="style.css">
  <script src="app.js"></script>

  <style>
    header
    {
      margin-top: 0px;
    }
    nav{
      margin-top: -10px;
    }
    body {
      -webkit-font-smoothing: antialiased;
      font: normal 15px/1.5 "Helvetica Neue", Helvetica, Arial, sans-serif;
      color: #232525;
      padding-top:0px;
    }


    #slides {
      display: none
    }

    #slides .slidesjs-navigation {
      margin-top:3px;
    }

    #slides .slidesjs-previous {
      margin-right: 5px;
      float: left;
    }

    #slides .slidesjs-next {
      margin-right: 5px;
      float: left;
    }

    .slidesjs-pagination {
      margin: 6px 0 0;
      float: right;
      list-style: none;
    }

    .slidesjs-pagination li {
      float: left;
      margin: 0 1px;
    }

    .slidesjs-pagination li a {
      display: block;
      width: 13px;
      height: 0;
      padding-top: 13px;
      background-image: url(img/pagination.png);
      background-position: 0 0;
      float: left;
      overflow: hidden;
    }

    .slidesjs-pagination li a.active,
    .slidesjs-pagination li a:hover.active {
      background-position: 0 -13px
    }

    .slidesjs-pagination li a:hover {
      background-position: 0 -26px
    }

    #slides a:link,
    #slides a:visited {
      color: #333
    }

    #slides a:hover,
    #slides a:active {
      color: #9e2020
    }

    .navbar {
      overflow: hidden
    }
  </style>
  <!-- End SlidesJS Optional-->

  <!-- SlidesJS Required: These styles are required if you'd like a responsive slideshow -->
  <style>
    #slides {
      display: none
    }

    .container {
      margin: 0 auto
    }

    /* For tablets & smart phones */
    @media (max-width: 767px) {
      body {
        padding-left: 20px;
        padding-right: 20px;
      }
      .container {
        width: auto
      }
    }

    /* For smartphones */
    @media (max-width: 480px) {
      .container {
        width: auto
      }
    }

    /* For smaller displays like laptops */
    @media (min-width: 768px) and (max-width: 979px) {
      .container {
        width: 724px
      }
    }

    /* For larger displays */
    @media (min-width: 1200px) {
      .container {
        width: 1170px
      }
    }
  </style>
  <!-- SlidesJS Required: -->
</head>
<body>
  <!--<i class="btn-up fa fa-arrow-circle-o-up hidden-xs"></i>-->
  <header class="full-reset header">
    <!--======================================== Logo(Nombre INS) ========================================-->
    <div class="full-reset logo">
      <!--<span class="hidden-lg hidden-md"></span>-->

      <span class="hidden-xs hidden-sm">Instituto Adventista</span>
    </div>
    <!--======================================== Links de navegación ========================================-->
    <nav class="full-reset navigation">
      <ul class="full-reset list-unstyled">
        <li><a href="index.html">Inicio</a></li>
        <li><a href="acerca.html">Acerca de Nosotros</a></li>
        <li><a href="secretaria.html">Secretaría</a></li>
        <li><a href="bachilleratos.html">Carreras</a></li>
        <li><a href="galeria.html">Galeria</a></li>
      </ul>

    </nav>
  </header>

  <!-- SlidesJS Required: Start Slides -->
  <!-- The container is used to define the width of the slideshow -->
  <div class="container">
    <div id="slides">
      <img src="assets/gallery/frontyard1.jpg" alt="Default">
      <img src="assets/gallery/cole.jpg" alt="Default">
      <center><img src="assets/gallery/lab.jpeg" alt="Default"></center>
      <center><img src="assets/gallery/pic2.jpg" alt="Default"></center>
      <img src="assets/gallery/se17.jpg" alt="Default">
      <a href="#" class="slidesjs-previous slidesjs-navigation"><i class="icon-chevron-left icon-large"></i></a>
      <a href="#" class="slidesjs-next slidesjs-navigation"><i class="icon-chevron-right icon-large"></i></a>

    </div>
  </div>
  

  
  <!--======================================== Enlaces importantes ========================================-->

<center><h2 class="title">Filosofia</h2></center>
<h3>El Instituto Adventista Bilingüe F.H., igual a la Iglesia Adventista del Séptimo Día, reconoce que Dios es el Creador y Sustentador 
    de la tierra y de todo el universo, es la fuente de conocimiento y de sabiduría. A su semejanza, Dios creó al hombre perfecto. Debido 
    al pecado, el hombre perdió su condición original, y la educación Adventista, al perfeccionar la fe en Cristo, tiene el propósito de 
    restaurar en él la misma imagen de su Hacedor, fomentar en el estudiante una dedicación inteligente de la obra de Dios en la tierra 
    y proporcionarle una preparación práctica para servicios concienzudos a sus semejantes. Los adventistas del séptimo día creemos que 
    el conocimiento de este Dios personal nunca puede ser obtenido únicamente por la razón humana, sino que Dios ha dado a conocer su 
    naturaleza, propósitos y planes mediante la revelación divina. La Sagrada Escritura, tanto el Antiguo Testamento como el Nuevo, 
    junto con el Espíritu de Profecía fue dada por inspiración de Dios, contiene la revelación de su voluntad a los hombres y constituye 
    la única regla de la fe y la conducta. En este respecto los adventistas del séptimo día aceptan la divina revelación como el principio 
    guiador de su filosofía de la educación. Creemos que los maestros son siervos de Dios y los estudiantes, hijos de Dios. El verdadero 
    conocimiento de Dios, compañerismo con él en el estudio y en el servicio, la semejanza a él en el desarrollo del carácter y hacer de 
    cada estudiante un fiel adventista del séptimo día, han de ser la fuente, el medio y el gran objetivo de la educación adventista del séptimo día. 
    En suma: La Iglesia Adventista del Séptimo Día, por medio de su programa educativo, desea ayudar a la juventud a prepararse para una ciudadanía 
    efectiva en esta tierra, y una ciudadanía gratificante en la tierra nueva.</h3>



  <!-- End SlidesJS Required -->
 <center> <div class="mapouter"><div class="gmap_canvas"><iframe width="600" height="500" id="gmap_canvas" 
 src="https://maps.google.com/maps?q=instituto%20adventista%20french%20harbour&t=&z=13&ie=UTF8&iwloc=&output=embed" 
 frameborder="0" scrolling="no" marginheight="0" marginwidth="0"></iframe><a href="https://www.pureblack.de">pureblack.de
 </a></div><style>.mapouter{text-align:right;height:500px;width:600px;}.gmap_canvas {overflow:hidden;background:none!important;height:500px;width:600px;}</style></div></center>

  <!--======================================== Pie de pagina ========================================-->
  <footer class="full-reset footer">
    <div class="full-reset" style="padding: 15px 0;">
      <div class="container">
        <div class="row">
          <div class="col-xs-12 col-sm-4">
            <h4 class="titles text-center">Visitenos en</h4>
            <p class="text-center">iabfhelearning.com.</p>
          </div>
          <div class="col-xs-12 col-sm-4">
            <h4 class="titles text-center">Contactenos</h4>
            <p class="text-center">Tele-Fax: +(504)8990-9662 <br>Correo Electrónico: ibelmontired@hotmail.com</p>
          </div>
          <div class="col-xs-12">
            <div class="full-reset footer-copyright"><i class="fa fa-copyright"></i> Design by Ashton Jackson</div>
          </div>

          <footer class="perfil">
            <div class="footer-left">
                <p class="footer-links">
                    <a class="link-1" href="perfil.html">Autor</a>
                </p>
                <p>Ashton &copy; 2022</p>
            </div>
            </footer>
</body>

</html>
