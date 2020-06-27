# moja-nauka-gita-2
<!DOCTYPE html>
<html lang="pl">
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Zadanie moduł III</title>
        <link rel="stylesheet" href="style.css">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.9.0/css/all.min.css">
        <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">  
  </head>
  <body>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <a class="navbar-brand" href="#">HARBINGER</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNavDropdown">
            <ul class="navbar-nav">
                <li class="nav-item active">
                    <a class="nav-link" href="#">Ona <span class="sr-only">(current)</span></a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">On</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Dziecko</a>
                </li>
                <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                    Home
                    </a>
                    <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
                        <a class="dropdown-item" href="#">Kuchnia</a>
                        <a class="dropdown-item" href="#">Sypialnia</a>
                        <a class="dropdown-item" href="#">Salon</a>
                    </div>
                </li>
            </ul>
        </div>
        <div class="btn-group ml-auto" role="group" aria-label="Basic example">
            <button type="button" class="btn btn-secondary">Card<i class="fas fa-shopping-cart"></i></button>
            <button type="button" class="btn btn-secondary">Account<i class="fas fa-user"></i></button>
        </div>
    </nav>
    <div id="main-slider" class="carousel slide" data-ride="carousel">
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img class="w-100" src="https://i.postimg.cc/jjd2KtyH/1.jpg" alt="image">
                <div class="carousel-caption">
                <h4><a href="#" class="btn btn-primary">Nawet do 50 % rabatu</a></h4>
                <h3><a href="#" class="btn btn-primary">Jeszcze lepsze oferty sprzedaży!</a></h3>
                </div>
            </div>
            <div class="carousel-item">
                <img class="w-100" src="https://i.postimg.cc/m2YgHtw3/2.jpg" alt="image">
                <div class="carousel-caption">
                </div>
            </div>
            <div class="carousel-item">
                <img class="w-100" src="https://i.postimg.cc/GtYhz21C/3.jpg" alt="image">
                <div class="carousel-caption">
                </div>
            </div>
        </div>
        <a class="carousel-control-prev" href="#main-slider" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#main-slider" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
        </a>
    </div>
    <div class="products">
        <div class=container>
            <div class="row">
                <div class="col-3">
                    <h2>Brands</h2>
                    <div class="list-group d-flex flex-column">
                        <a href="#" class="list-group-item list-group-item-action">NIKE</a>
                        <a href="#" class="list-group-item list-group-item-action">ADIDAS</a>
                        <a href="#" class="list-group-item list-group-item-action">REEBOK</a>
                        <a href="#" class="list-group-item list-group-item-action">F4</a>
                        <a href="#" class="list-group-item list-group-item-action">Sport</a>
                    </div>
                </div>
                <div class="col-9">
                <h2>New Arrivals</h2>
                    <div class="row">
                        <div class=" col-sm-6 col-lg-4 d-flex">
                            <div class="card" style="width: 18rem;">
                                <div class="card-image">
                                    <img class="card-img-top" src="https://i.postimg.cc/fyGgT6bx/4.jpg" alt="Card image cap">
                                </div>
                                <div class="card-body">
                                    <h5 class="card-title">Topy</h5>
                                    <a href="#" class="btn btn-light">Zobacz!</a>
                                </div>
                            </div>
                        </div>
                        <div class=" col-sm-6 col-lg-4 d-flex ">
                            <div class="card" style="width: 18rem;">
                                <div class="card-image">
                                    <img class="card-img-top" src="https://i.postimg.cc/bNDrJzRd/5.jpg" alt="Card image cap">
                                </div>
                                <div class="card-body">
                                    <h5 class="card-title">Basic</h5>
                                    <a href="#" class="btn btn-light">Zobacz!</a>
                                </div>
                            </div>
                        </div>
                        <div class="col-sm-6 col-lg-4 d-flex">
                            <div class="card" style="width: 18rem;">
                                <div class="card-image">
                                    <img class="card-img-top" src="https://i.postimg.cc/kX04Rkjs/6.jpg" alt="Card image cap">
                                </div>
                                <div class="card-body">
                                    <h5 class="card-title">Swetry</h5>
                                    <a href="#" class="btn btn-light">Zobacz!</a>
                                </div>
                            </div>
                        </div>
                        <div class=" col-sm-6 col-lg-4">
                            <div class="card d-lg-none" style="width: 18rem;">
                                <div class="card-image">
                                    <img class="card-img-top" src="https://i.postimg.cc/t4Fg32wj/7.jpg" alt="Card image cap">
                                </div>
                                <div class="card-body">
                                    <h5 class="card-title">Torebki</h5>
                                    <a href="#" class="btn btn-light">Zobacz!</a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="look px-5">
            <div class=container>
                <div class="row">
                    <div class="card  mb-3 col-6">
                        <img class="card-img position-relative" src="https://i.postimg.cc/rmxBqxpR/8.jpg">
                        <div class="card-body card-img-overlay d-flex justify-content-center align-items-center">
                            <h5 class="card-title">Zimowa wysprzedaż</h5>
                            <a href="#" class="btn btn-light">Zobacz!</a>
                        </div>
                    </div>
                    <div class="card  mb-3 col-6" >
                        <img class="card-img" src="https://i.postimg.cc/mk40kkcX/9.jpg">
                        <div class="card-body card-img-overlay d-flex justify-content-center align-items-center ">
                            <h5 class="card-title">Lookbook</h5>
                            <a href="#" class="btn btn-light">Zobacz!</a>
                        </div>
                    </div>
                    <div class="card mb-3 col-12">
                        <img class="card-img" src="https://i.postimg.cc/3NZzvhmK/10.jpg">
                        <div class="card-body card-img-overlay d-flex justify-content-center align-items-center">
                            <h5 class="card-title">Nowinki</h5>
                            <a href="#" class="btn btn-light">Zobacz!</a>
                        </div>
                    </div> 
                </div>
            </div>
        </div>
        <div class="colums px-3 py-3 mb-3">
            <div class="row">
                <div class=" card col-12 col-md-3 px-3 py-3 mb-3  mr-5 d-none d-sm-block">
                    <div class="row">
                        <div class="col-md-2">
                            <i class="fas fa-truck pt-4 pl-3"></i>
                        </div>
                        <div class="col-md-10">
                            <h5>Darmowa dostawa</h5>
                            <p>powyżej 100 zł</p>
                        </div>
                    </div>
                </div>
                <div class=" card col-12 col-md-3 px-3 py-3 mb-3 mr-5">
                    <div class="row">
                        <div class="col-md-2">
                            <i class="fas fa-money-bill-wave pt-4 pl-3"></i>
                        </div>
                        <div class="col-md-10">
                            <h5>60 dni na zwrot</h5>
                            <p>bezpłatnie</p>
                        </div>
                    </div>
                </div>
                <div class="card col-12 col-md-3 px-3 py-3 mb-3 mr-5">
                    <div class="row">
                        <div class="col-md-2">
                            <i class="fas fa-life-ring pt-4 pl-3"></i>
                        </div>
                        <div class="col-md-10">
                            <h5>24/7 Pomoc</h5>
                            <p>Infolinia</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="section">
            <div class="row">
                <div class="card order-lg-1 col-12 col-md-4" style="width: 18rem;">
                    <div class="card-body">
                        <h5 class="card-title">HARBINGER</h5>
                        <p class="card-text">With supporting text below as a natural lead-in to additional content.</p>
                        <i class="fab fa-facebook-f"></i>
                        <i class="fab fa-instagram"></i>
                        <i class="fab fa-twitter"></i>
                        <i class="fab fa-youtube"></i>
                    </div>
                </div>
                <div class="card order-lg-1 col-12 col-md-4" style="width: 18rem;">
                    <div class="card-body">
                        <h5 class="card-title">Contact us</h5>
                        <p class="card-text">2795 Kingston Place<br> Richard Hill 48306 Michigan<br> support@company.com</p>
                    </div>
                </div>
                <div class="card col-12 col-md-4" style="width: 18rem;">
                    <div class="card-body">
                        <h5 class="card-title">Newsletter</h5>
                        <p class="card-text">With supporting text below as a natural lead-in to additional content.</p>
                        <input type="text" placeholder="Enter email">
                        <p>We'll never shere your email with anyone else</p>
                        <a href="#" class="btn btn-primary">Submit</a>
                    </div>
                </div>
            </div>
        </div>
        <div class="footer py-3">
            <div class="row">
            <div class="footer-body col-md-4">
                <p>HANBIRGER Ltd.</p>
            </div>
            <div class="footer-body col-md-6">
            <ul class="list-footer">
                    <li class="list-footer-item ">About</li>
                    <li class="list-footer-item">Delivery</li>
                    <li class="list-footer-item">Returns</li>
                    <li class="list-footer-item">Privacy policy</li>
                    <li class="list-footer-item">Terms i conditions</li>
                </ul>    
            </div>
            </div>
        </div>
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script
  </body>

</html>
