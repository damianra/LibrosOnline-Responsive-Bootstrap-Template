<!DOCTYPE html>
<head>
    <title>LibrosOnline</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
    <link rel="stylesheet" type="text/css" href="css/font-awesome.min.css">
    <link rel="stylesheet" type="text/css" href="css/styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Balsamiq+Sans&family=Days+One&display=swap" rel="stylesheet"> 

    <script src="https://kit.fontawesome.com/3bfb7f71dd.js" crossorigin="anonymous"></script>
</head>

<body>
    <!--LOGO AND SOCIAL ICONS-->
    <header class="encabezado-sitio container">
        <div class="row justify-content-md-between">
            <div class="col-lg-4">
                <img src="img/logo512.png" class="img-fluid mx-auto d-block pt-4 pb-4">
            </div>
            <div class="col-lg-4">
                <nav class="sociales text-center text-lg-right">
                    <ul>
                        <li>
                            <a href="https://www.facebook.com">
                            <i class="fab fa-facebook-square fa-2x" style="color: #cb3234;"></i> 
                                <span class="sr-only">Facebook</span>
                            </a>
                        </li>
                        <li>
                            <a href="https://www.twitter.com">
                                <i class="fab fa-twitter-square fa-2x" style="color: #cb3234;"></i>
                                 <span class="sr-only ">Twitter</span>
                                </a>
                            </li>
                        <li>
                            <a href="https://www.instagram.com">
                                <i class="fab fa-instagram-square fa-2x" style="color: #cb3234;"></i>
                                 <span class="sr-only">Instagram</span>
                                </a>
                            </li>
                        <li>
                            <a href="https://www.printerest.com">
                                <i class="fab fa-pinterest-square fa-2x" style="color: #cb3234;"></i>
                                 <span class="sr-only">Pinterest</span>
                                </a>
                            </li>
                        <li>
                            <a href="https://www.youtube.com"> 
                                <i class="fab fa-youtube-square fa-2x" style="color: #cb3234;"></i>
                                <span class="sr-only">Youtube</span>
                            </a>
                        </li>
                    </ul>
                </nav>
            </div>
        </div>
    </header>


    <div class="navegacion mt-3">
        <!--NAVBAR-->
        <nav class="nav-principal navbar navbar-expand-md navbar-dark bg-faded">
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#nav_principal"  aria-label="LibrosOnline">
                <span class="navbar-toggler-icon"></span>
              </button>
                    <a href="index.html" class="navbar-brand d-lg-none d-md-none">LibrosOnline</a>
            <div class="container">
                    <div class="collapse navbar-collapse " id="nav_principal">
                                <ul class="nav nav-justified w-100 flex-column flex-sm-row">
                                    <li class="nav-item">
                                        <a href="index.html" class="nav-link">Inicio</a>
                                    </li>
                                    <li class="nav-item">
                                        <a href="#" class="nav-link">Tienda</a>
                                    </li>
                                    <li class="nav-item dropdown">
                                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                                          Categorias
                                        </a>
                                        <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                                          <a class="dropdown-item" href="#">Ciencia Ficcion</a>
                                          <a class="dropdown-item" href="#">Terror</a>
                                          <a class="dropdown-item" href="#">Novelas</a>
                                          <a class="dropdown-item" href="#">Historias Reales</a>
                                          <a class="dropdown-item" href="#">Enciclopedias</a>
                                        </div>
                                      </li>
                                    <li class="nav-item">
                                        <a href="#" class="nav-link">Quienes somos</a>
                                    </li>
                                    <li class="nav-item">
                                        <a href="#" class="nav-link">Envios</a>
                                    </li>
                                </ul>
                        </div>
             </div>
        </nav>
    </div>

<!-- CAROUSEL-->
    <div class="container d-none d-sm-none d-md-none d-lg-block">
        <div id="carouselExampleControls" class="carousel slide products mb-4" data-ride="carousel">
            <div class="carousel-inner">
              <div class="carousel-item active">

                <div class="row py-5">

                    <div class="col-md-3">
                        <div class="card">
                            <a href="#">
                                <img class="card-img-top" src="img/portada_fahrenheit-451.jpg">
                                <div class="card-body">
                                    <h3 class="card-title text-center text-uppercase">Titulo</h3>
                                    <p class="card-text-textuppercase">
                                        Book description
                                    </p>
                                    <p class="precio mb-0 lead text-center btn btn-danger font-weight-bold">$10000</p>
                                </div>
                            </a>
                        </div>
                    </div>
    
                    <div class="col-md-3">
                        <div class="card">
                            <a href="#">
                                <img class="card-img-top" src="img/autonomous.jpg">
                                <div class="card-body">
                                    <h3 class="card-title text-center text-uppercase">Titulo</h3>
                                    <p class="card-text-textuppercase">
                                        Book description
                                    </p>
                                    <p class="precio mb-0 lead text-center btn btn-danger font-weight-bold">$500</p>
                                </div>
                            </a>
                        </div>
                    </div>
    
                    <div class="col-md-3">
                        <div class="card">
                            <a href="#">
                                <img class="card-img-top" src="img/cenizas.jpg">
                                <div class="card-body">
                                    <h3 class="card-title text-center text-uppercase">Titulo</h3>
                                    <p class="card-text-textuppercase">
                                        Book description
                                    </p>
                                    <p class="precio mb-0 lead text-center btn btn-danger font-weight-bold">$500</p>
                                </div>
                            </a>
                        </div>
                    </div>
    
                    <div class="col-md-3">
                        <div class="card">
                            <a href="#">
                                <img class="card-img-top" src="img/el-visitante-inesperado.jpg">
                                <div class="card-body">
                                    <h3 class="card-title text-center text-uppercase">Titulo</h3>
                                    <p class="card-text-textuppercase">
                                        Book description
                                    </p>
                                    <p class="precio mb-0 lead text-center btn btn-danger font-weight-bold">$500</p>
                                </div>
                            </a>
                        </div>
                    </div>
                </div>
              </div>


              <div class="carousel-item">
                <div class="row py-5">

                <div class="col-md-3">
                    <div class="card">
                        <a href="#">
                            <img class="card-img-top" src="img/el_descenso_de_los_angeles.jpg">
                            <div class="card-body">
                                <h3 class="card-title text-center text-uppercase">Titulo</h3>
                                <p class="card-text-textuppercase">
                                    Book description
                                </p>
                                <p class="precio mb-0 lead text-center btn btn-danger font-weight-bold">$500</p>
                            </div>
                        </a>
                    </div>
                </div>

                <div class="col-md-3">
                    <div class="card">
                        <a href="#">
                            <img class="card-img-top" src="img/nemesis.jpg">
                            <div class="card-body">
                                <h3 class="card-title text-center text-uppercase">Titulo</h3>
                                <p class="card-text-textuppercase">
                                    Book description
                                </p>
                                <p class="precio mb-0 lead text-center btn btn-danger font-weight-bold">$500</p>
                            </div>
                        </a>
                    </div>
                </div>

                <div class="col-md-3">
                    <div class="card">
                        <a href="#">
                            <img class="card-img-top" src="img/portada_ravenor.jpg">
                            <div class="card-body">
                                <h3 class="card-title text-center text-uppercase">Titulo</h3>
                                <p class="card-text-textuppercase">
                                    Book description
                                </p>
                                <p class="precio mb-0 lead text-center btn btn-danger font-weight-bold">$500</p>
                            </div>
                        </a>
                    </div>
                </div>

                <div class="col-md-3">
                    <div class="card">
                        <a href="#">
                            <img class="card-img-top" src="img/vader_ilustrado.jpg">
                            <div class="card-body">
                                <h3 class="card-title text-center text-uppercase">Titulo</h3>
                                <p class="card-text-textuppercase">
                                    Book description
                                </p>
                                <p class="precio mb-0 lead text-center btn btn-danger font-weight-bold">$500</p>
                            </div>
                        </a>
                    </div>
                </div>
            </div>
              </div>


              <div class="carousel-item">
                <div class="row py-5">

                <div class="col-md-3">
                    <div class="card">
                        <a href="#">
                            <img class="card-img-top" src="img/portada_fahrenheit-451.jpg">
                            <div class="card-body">
                                <h3 class="card-title text-center text-uppercase">Titulo</h3>
                                <p class="card-text-textuppercase">
                                    Book description
                                </p>
                                <p class="precio mb-0 lead text-center btn btn-danger font-weight-bold">$500</p>
                            </div>
                        </a>
                    </div>
                </div>

                <div class="col-md-3">
                    <div class="card">
                        <a href="#">
                            <img class="card-img-top" src="img/autonomous.jpg">
                            <div class="card-body">
                                <h3 class="card-title text-center text-uppercase">Titulo</h3>
                                <p class="card-text-textuppercase">
                                    Book description
                                </p>
                                <p class="precio mb-0 lead text-center btn btn-danger font-weight-bold">$500</p>
                            </div>
                        </a>
                    </div>
                </div>

                <div class="col-md-3">
                    <div class="card">
                        <a href="#">
                            <img class="card-img-top" src="img/cenizas.jpg">
                            <div class="card-body">
                                <h3 class="card-title text-center text-uppercase">Titulo</h3>
                                <p class="card-text-textuppercase">
                                    Book description
                                </p>
                                <p class="precio mb-0 lead text-center btn btn-danger font-weight-bold">$500</p>
                            </div>
                        </a>
                    </div>
                </div>

                <div class="col-md-3">
                    <div class="card">
                        <a href="#">
                            <img class="card-img-top" src="img/el-visitante-inesperado.jpg">
                            <div class="card-body">
                                <h3 class="card-title text-center text-uppercase">Titulo</h3>
                                <p class="card-text-textuppercase">
                                    Book description
                                </p>
                                <p class="precio mb-0 lead text-center btn btn-danger font-weight-bold">$500</p>
                            </div>
                        </a>
                    </div>
                </div>
            </div>
              </div>
            </div>
            <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
              <span class="carousel-control-prev-icon" aria-hidden="true"></span>
              <span class="sr-only">Previous</span>
            </a>
            <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
              <span class="carousel-control-next-icon" aria-hidden="true"></span>
              <span class="sr-only">Next</span>
            </a>
       </div>
    </div>

    </div>

    <div class="container">
        <!-- TEXT -->
        <section class="nuevositio mt-4">
            <h2 class="text-center text-uppercase">
                <span class="text-lowercase d-block">Los mejores libros</span> Sciencia-ficcion, Terror, Aventura, Comics
            </h2>
            <p class="text-center mt-4">Disfruta de los mejores relatos de diferentes autores</p>
        </section>

<!-- PRODUCTS-->
        <section class="products mb-4">
            <div class="row py-5">

                <div class="col-lg-3 col-md-6 col-sm-6 col-xs-12 mb-4">
                    <div class="card">
                        <a href="#">
                            <img class="card-img-top" src="img/portada_fahrenheit-451.jpg">
                            <div class="card-body">
                                <h3 class="card-title text-center text-uppercase">Titulo</h3>
                                <p class="card-text-textuppercase">
                                    Book description
                                </p>
                                <p class="precio mb-0 lead text-center btn btn-danger font-weight-bold">$500</p>
                            </div>
                        </a>
                    </div>
                </div>

                <div class="col-lg-3 col-md-6 col-sm-6 col-xs-12 mb-4">
                    <div class="card">
                        <a href="#">
                            <img class="card-img-top" src="img/el-visitante-inesperado.jpg">
                            <div class="card-body">
                                <h3 class="card-title text-center text-uppercase">Titulo</h3>
                                <p class="card-text-textuppercase">
                                    Book description
                                </p>
                                <p class="precio mb-0 lead text-center btn btn-danger font-weight-bold">$500</p>
                            </div>
                        </a>
                    </div>
                </div>

                <div class="col-lg-3 col-md-6 col-sm-6 col-xs-12 mb-4">
                    <div class="card">
                        <a href="#">
                            <img class="card-img-top" src="img/portada_ravenor.jpg">
                            <div class="card-body">
                                <h3 class="card-title text-center text-uppercase">Titulo</h3>
                                <p class="card-text-textuppercase">
                                    Book description
                                </p>
                                <p class="precio mb-0 lead text-center btn btn-danger font-weight-bold">$500</p>
                            </div>
                        </a>
                    </div>
                </div>

                <div class="col-lg-3 col-md-6 col-sm-6 col-xs-12 mb-4">
                    <div class="card">
                        <a href="#">
                            <img class="card-img-top" src="img/vader_ilustrado.jpg">
                            <div class="card-body">
                                <h3 class="card-title text-center text-uppercase">Titulo</h3>
                                <p class="card-text-textuppercase">
                                    Book description
                                </p>
                                <p class="precio mb-0 lead text-center btn btn-danger font-weight-bold">$500</p>
                            </div>
                        </a>
                    </div>
                </div>
            </div>
        </section>
        
    </div>

<!-- FOOTER -->
    <footer class="footer-sitio pt-3 mt-2">
        <div class="container">
            <div class="row">

                <div class="col-md-4">
                    <h3 class="text-uppercase text-center pb-4">Nosotros</h3>
                    <p class="text-justify">Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                     Vestibulum lobortis erat sed consectetur semper. Etiam egestas est porta sem tincidunt,
                      in placerat mi volutpat. Vivamus efficitur ligula ac augue placerat mattis. Sed eleifend justo sit amet lectus sagittis, eu posuere libero vehicula. Vivamus 
                     accumsan purus a elit aliquet scelerisque et non dolor.</p>
                </div>

                <div class="col-md-4">
                    <h3 class="text-uppercase text-center pb-4">Horarios</h3>
                    <p class="sociales text-center">visitanos en nuestro local</p>
                    <p class="sociales text-center">Lun a Vie 9 a 18</p>
                    <p class="sociales text-center">Sab 10 a 16</p>
                    <p class="sociales text-center">Feriado: Cerrado</p>
                </div>

                <div class="col-md-4">
                    <h3 class="text-uppercase text-center pb-4">Contacto</h3>
                    <p class="sociales text-center">Calle falsa 123</p>
                    <p class="sociales text-center">Buenos Aires, Argentina</p>
                    <p class="text-center">Telefono: XXXX-XXXX</p>
                    
                    <nav class="sociales text-center">
                        <ul>
                            <li>
                                <a href="https://www.facebook.com">
                                <i class="fab fa-facebook-square fa-2x" style="color: #cb3234;"></i> 
                                    <span class="sr-only">Facebook</span>
                                </a>
                            </li>
                            <li>
                                <a href="https://www.twitter.com">
                                    <i class="fab fa-twitter-square fa-2x" style="color: #cb3234;"></i>
                                     <span class="sr-only ">Twitter</span>
                                    </a>
                                </li>
                            <li>
                                <a href="https://www.instagram.com">
                                    <i class="fab fa-instagram-square fa-2x" style="color: #cb3234;"></i>
                                     <span class="sr-only">Instagram</span>
                                    </a>
                                </li>
                            <li>
                                <a href="https://www.printerest.com">
                                    <i class="fab fa-pinterest-square fa-2x" style="color: #cb3234;"></i>
                                     <span class="sr-only">Pinterest</span>
                                    </a>
                                </li>
                            <li>
                                <a href="https://www.youtube.com"> 
                                    <i class="fab fa-youtube-square fa-2x" style="color: #cb3234;"></i>
                                    <span class="sr-only">Youtube</span>
                                </a>
                            </li>
                        </ul>
                    </nav>

                </div>
                <hr class="w-100">
                <p class="text-center copyrigth w-100">Copyrigth LibrosOnline</p>
            </div>
        </div>
    </footer>










<script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
</body>
</html>