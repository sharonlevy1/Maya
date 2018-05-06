<!DOCTYPE HTML>
<HTML>
  <head>
    <title>Bootstrap</title>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.0.12/css/all.css" integrity="sha384-G0fIWCsCzJIMAVNQPfjH08cyYaUtMwjJwqiRKxxE/rx96Uroj1BtIQ6MLJuheaO9" crossorigin="anonymous">

    <link href="https://fonts.googleapis.com/css?family=Cambo|Crimson+Text|Josefin+Sans|Kalam|Krona+One|Rubik+Mono+One" rel="stylesheet">

    <link rel="stylesheet" href="https://bootswatch.com/4/lux/bootstrap.min.css" crossorigin="anonymous">

    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
    
        <link rel="stylesheet" type="text/css" href="quick_startcss.css">
  </head>

  <body>
    <div class="container-fluid">
      <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
        <a class="navbar-brand" href="#">Maya Mokady</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarColor01" aria-controls="navbarColor01" aria-expanded="false" 
          aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarColor01">
          <form class="form-inline my-2 my-lg-0">
            <input class="form-control mr-sm-2" type="text" placeholder="Search">
            <button class="btn btn-secondary my-2 my-sm-0" type="submit">Search</button>
          </form>
          <ul class="navbar-nav mr-auto" class="fa-ul">
            <li class="home nav-item active">  <a class="nav-link" class="home" href="#"> <i class="fas fa-home fa-fw fa-2x"></i>    Home<span class="sr-only">(current)</span></i></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" class="who" href="#"><i class="fas fa-info-circle fa-2x"></i>    Who Am I?</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" class="items" href="#"><i class="fab fa-gratipay fa-2x"></i>    Items From Shows</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" class="all" href="#"><i class="fas fa-book fa-2x"></i>    All Items</a>
            </li>
          </ul>
        </div>
      </nav>

      <!--Main-->
      <!-- Carousel -->
      <div class="container">
        <div class="row">
          <div class="col-xs-12">
            <div id="myCarousel" class="carousel slide" data-ride="carousel" data-interval="2000"
              data-pause ="hover" data-wrap-"true" >
              <!-- Indicators -->
              <ol class="carousel-indicators">
                <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
                <li data-target="#myCarousel" data-slide-to="1"></li>
                <li data-target="#myCarousel" data-slide-to="2"></li>
              </ol>

              <!-- Wrapper for slides -->
              <div class="carousel-inner">
                <div class="item active">
                  <div class="row">
                    <div class="col-xs-4">
                      <img src="https://gdurl.com/eLOR" alt="Los Angeles" style="width: 100%" class="img-fluid">
                      <div class="carousel-caption">
                        <h3>Image</h3>
                        <p>Description/Click for more</p>
                      </div>
                    </div>
                    <div class="col-xs-4">
                      <img src="https://gdurl.com/t9Pr" alt="Chicago" style="width: 100%" class="img-fluid">
                      <div class="carousel-caption">
                        <h3>Image</h3>
                        <p>Description/click for more</p>
                      </div>
                    </div>
                    <div class="col-xs-4">
                      <img src="https://gdurl.com/G-B6" alt="test" style="width: 100%" class="img-fluid">
                      <div class="carousel-caption">
                        <h3>Image</h3>
                        <p>Description/click for more</p>
                      </div>
                    </div>
                  </div>
                </div>

                <div class="item">
                  <div class="row">
                    <div class="col-xs-4">
                      <img src="https://gdurl.com/eKsL" alt="Los Angeles" style="width: 100%" class="img-fluid">
                      <div class="carousel-caption">
                        <h3>Image</h3>
                        <p>Description/Click for more</p>
                      </div>
                    </div>
                    <div class="col-xs-4">
                      <img src="https://gdurl.com/ttyT" alt="Chicago" style="width: 100%" class="img-fluid">
                      <div class="carousel-caption">
                        <h3>Image</h3>
                        <p>Description/click for more</p>
                      </div>
                    </div>
                    <div class="col-xs-4">
                      <img src="https://gdurl.com/j1nu" alt="test" style="width: 100%" class="img-fluid">
                      <div class="carousel-caption">
                        <h3>Image</h3>
                        <p>Description/click for more</p>
                      </div>
                    </div>
                  </div>
                </div>

                <div class="item">
                  <div class="row">
                    <div class="col-xs-4">
                      <img src="https://gdurl.com/pdlz" alt="Los Angeles" style="width: 100%" class="img-fluid">
                      <div class="carousel-caption">
                        <h3>Image</h3>
                        <p>Description/Click for more</p>
                      </div>
                    </div>
                    <div class="col-xs-4">
                      <img src="https://gdurl.com/q5rb" alt="Chicago" style="width: 100%" class="img-fluid">
                      <div class="carousel-caption">
                        <h3>Image</h3>
                        <p>Description/click for more</p>
                      </div>
                    </div>
                    <div class="col-xs-4">
                      <img src="https://gdurl.com/BzDc" alt="test" style="width: 100%" class="img-fluid">
                      <div class="carousel-caption">
                        <h3>Image</h3>
                        <p>Description/click for more</p>
                      </div>
                    </div>
                  </div>
                </div>
              <!-- Left and right controls -->
              <a class="left carousel-control" href="#myCarousel" data-slide="prev">
                <span class="glyphicon glyphicon-chevron-left"></span>
                <span class="sr-only">Previous</span>
              </a>
              <a class="right carousel-control" href="#myCarousel" data-slide="next">
                <span class="glyphicon glyphicon-chevron-right"></span>
                <span class="sr-only">Next</span>
              </a>
            </div>
          </div>
        </div>

        <!-- Jumbotron Header -->
        <header class="jumbotron my-4 col-xs-12">
          <h2 class="display-2">I am a fashion designer</h1>
          <p class="lead">I work hard. I am talented. I am driven.</p>
          <a id="findout" href="#" class="btn btn-lg text-white">Find out more</a>
        </header>

        <!-- Page Features -->
        <div class="row text-center">

          <div class="col-lg-3 col-md-6 mb-4">
            <div class="card">
              <img class="card-img-top" src="https://gdurl.com/3X2o" alt="" class="img-fluid">
              <div class="card-body">
                <h4 class="card-title">Bags</h4>
                <p class="card-text">Designing more than just clothes, the first accessory needed is a bag.</p>
              </div>
              <div class="card-footer">
                <a href="#" class="btn btn-primary">Go to collection!</a>
              </div>
            </div>
          </div>

          <div class="col-lg-3 col-md-6 mb-4">
            <div class="card">
              <img class="card-img-top" src="https://gdurl.com/Uy-a" alt="" class="img-fluid">
              <div class="card-body">
                <h4 class="card-title">Ethnic</h4>
                <p class="card-text">Connecting to our roots.</p>
              </div>
              <div class="card-footer">
                <a href="#" class="btn btn-primary">Go to collection!</a>
              </div>
            </div>
          </div>

          <div class="col-lg-3 col-md-6 mb-4">
            <div class="card">
              <img class="card-img-top" src="https://gdurl.com/CBFT" alt="" class="img-fluid">
              <div class="card-body">
                <h4 class="card-title">Children</h4>
                <p class="card-text">I created a collection of children clothes, inspired by summer.</p>
              </div>
              <div class="card-footer">
                <a href="#" class="btn btn-primary">Go to collection!</a>
              </div>
            </div>
          </div>

          <div class="col-lg-3 col-md-6 mb-4">
            <div class="card">
              <img class="card-img-top" src="https://gdurl.com/GmE0" alt="" class="img-fluid">
              <div class="card-body">
                <h4 class="card-title">Creativity</h4>
                <p class="card-text">No fashion designer can be such without going to the edge. This collection is it.</p>
              </div>
              <div class="card-footer">
                <a href="#" class="btn btn-primary">Go to collection!</a>
              </div>
            </div>
          </div>

        </div>
        <!-- /.row -->

      </div>
    </div>
    <!-- /.container -->

    <!-- Footer -->
    <footer class="py-5 bg-dark col-12">
      <div class="container">
        <p class="m-0 text-center text-white">Copyright &copy; Your Website 2018</p>
      </div>
      <!-- /.container -->
    </footer>

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
  </body>
</HTML>
