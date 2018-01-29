# sparta-global-mini-website
A website profile of myself

## Arsenal football club website

### Introduction ###

This is a portfolio website of the Arsenal football page displaying a description
of the club and positioned elements around at a normal screen size and when responsive. This also is styled with different attributes using css.

### Getting Started ###

First installed atom to your device in order for code to be displayed.

I opened terminal to run create folder and files.

### In Terminal ###
In terminal the commands

*This is some **combined** text in a sentence*

To access the html file In your terminal
Telling someone to run `a command` inline with a sentence

Here below is the **index.html** **hobbies.html** **gallery.html** **style.css** **gallery.css**

## index.html

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">



    <script src="http://code.jquery.com/jquery-3.3.1.min.js" integrity="sha256-FgpCb/KJQlLNfOu91ta32o/NMZxltwRo8QtmkMRdAu8=" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="./css/style.css">

    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
 <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
<!--Modal will not work without this link above-->





    <title></title>
  </head>
  <body class="body">
    <header>
      <nav class="navbar navbar-inverse navbar-fixed-top">
      <div class="container">
        <div class="navbar-header">
          <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar" aria-expanded="false" aria-controls="navbar">
            <span class="sr-only">Toggle navigation</span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
          </button>
          <a class="navbar-brand" href="#">The James Site</a>
        </div>
        <div id="navbar" class="collapse navbar-collapse">
          <ul class="nav navbar-nav">
            <li class="active"><a href="#">Home</a></li>
            <li><a href="hobbies.html">Hobbies</a></li>
            <li><a href="gallery.html">Gallery</a></li>
          </ul>
        </div><!--/.nav-collapse -->
      </div>
    </nav>
    </header>

    <div class="jumbotron">
        <h1 class="display-3">Jumbotron heading</h1>
        <p class="lead">Cras justo odio, dapibus ac facilisis in, egestas eget quam. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus.</p>
      </div>

      <div class="container bootstrap snippets">
<div class="row">
    <div class="col-lg-3 col-md-3 col-sm-4">
        <div class="panel rounded shadow">
            <div class="panel-body">
                <div class="inner-all">
                    <ul class="list-unstyled">
                        <li class="text-center">
                            <img data-no-retina="" class="img-circle img-responsive img-bordered-primary" src="img/profile-pic.jpg" alt="John Doe">
                        </li>
                        <li class="text-center">
                            <h4 class="text-capitalize">James Buabin</h4>
                            <p class="text-muted text-capitalize">Trainee Tech Consultant</p>
                        </li>
                    </ul>
                </div>
            </div>


        </div><!-- /.panel -->
        <div class="container">

        </div>


      </div>
      <div class="col-lg-8">

        <h2>Description of Me</h2>
        <p class="description">"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
           Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
           Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
           Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."</p>

      </div>

      <hr>

      <div class="container">
        <h2>Favourite Quote</h2>
        <!-- Trigger the modal with a button -->
        <button type="button" class="btn btn-info btn-lg" data-toggle="modal" data-target="#myModal">Open to see</button>

        <!-- Modal -->
        <div class="modal fade" id="myModal" role="dialog">
          <div class="modal-dialog">

            <!-- Modal content-->
            <div class="modal-content">
              <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal">&times;</button>
                <h4 class="modal-title">Modal Header</h4>
              </div>
              <div class="modal-body">
                <p>“You are what you are today because of the choices you made in the past.”</p>
              </div>
              <div class="modal-footer">
                <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
              </div>
            </div>

          </div>
        </div>

      </div>

      <footer class="footer">
  <p>Posted by: Hege Refsnes</p>
  <p>James&copy;</p>
</footer>




<link rel="stylesheet" href="css/bootstrap.min.css">




  <footer class="footer">
<p>James&copy;</p>
<ul class="footer-sitemap">
  <li><a href="index.html">Homepage</li>
  <li><a href="gallery.html">Gallery</li>
</ul>
</footer>

</body>
</html>

## hobbies.html

```hobbies

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title></title>
    <link rel="stylesheet" href="./css/style.css">
  </head>
  <body>

    <nav class="navbar navbar-inverse navbar-fixed-top">
    <div class="container">
      <div class="navbar-header">
        <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar" aria-expanded="false" aria-controls="navbar">
          <span class="sr-only">Toggle navigation</span>
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>
        </button>
        <a class="navbar-brand" href="#">The James Site</a>
      </div>
      <div id="navbar" class="collapse navbar-collapse">
        <ul class="nav navbar-nav">
          <li><a href="index.html">Home</a></li>
          <li class="active"><a href="hobbies.html">Hobbies</a></li>
          <li><a href="gallery.html">Gallery</a></li>
        </ul>
      </div><!--/.nav-collapse -->
    </div>
  </nav>

  <br>
  <br>

  <div class="col-md-12">


    <div class="container">
    <h2>Some of my interests</h2>
    <div id="myCarousel" class="carousel slide" data-ride="carousel">
      <!-- Indicators -->
      <ol class="carousel-indicators">
        <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
        <li data-target="#myCarousel" data-slide-to="1"></li>
        <li data-target="#myCarousel" data-slide-to="2"></li>
      </ol>

      <!-- Wrapper for slides -->
      <div class="carousel-inner">
        <div class="item active">
          <img src="img/background-image.jpg" alt="Los Angeles" style="width:100%;">
          <p class="image-descrip">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
             Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
              Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
          </p>
        </div>

        <div class="item">
          <img src="img/profile-pic.jpg" alt="Chicago" style="width:100%;">
        </div>

        <div class="item">
          <img src="img/background-image.jpg" alt="New york" style="width:100%;">
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

<br>
<div class="container">


<div class="row">
  <div class="col-md-4">

  </div>
</div>

<div class="row">

        <div class="col-md-8">
          <table class="table table-hover">
            <thead>
              <tr>
                <th>Week</th>
                <th>Hobbies</th>

              </tr>
            </thead>
            <tbody>
              <tr>
                <td>Monday</td>
                <td><li><a href="#"></a>Link 1</li>
                <li><a href="#"></a>Link 1</li>
                <li><a href="#"></a>Link 1</li></td>
              </tr>
              <tr>
                <td>Tuesday</td>
                <td><li><a href="#"></a>Link 1</li>
                <li><a href="#"></a>Link 1</li>
                <li><a href="#"></a>Link 1</li></td>
              </tr>
              <tr>
                <td>Wednesday</td>
                <td><li><a href="#"></a>Link 1</li>
                <li><a href="#"></a>Link 1</li></td>

              </tr>
            </tbody>
          </table>
        </div>


    </main>

  </div>
  </div>
<br>
<br>
  <footer class="footer">
<p>James&copy;</p>
<ul class="footer-sitemap">
  <li><a href="index.html">Homepage</li>
  <li><a href="gallery.html">Gallery</li>
</ul>
</footer>




  <link rel="stylesheet" href="css/bootstrap.min.css">

  </body>
</html>

## style.css ##
.body {
  background-image: url("./img/background-image.jpg");
}

body > header > div > div > p:nth-child(3) > a{
  background:#3d2f5a;
  border-radius: 30px;
}

.footer {
   position: fixed;
   left: 0;
   bottom: 0;
   width: 100%;
   background-color: #000099;
   color: white;
   text-align: center;
}

.description {
  font-size: 20px;
}

.image-descrip{
  color: blue;
}

.footer-sitemap{
  list-style-type: none;
  float: left;
}

## gallery.css ##

.footer {
   position: fixed;
   left: 0;
   bottom: 0;
   width: 100%;
   background-color: #000099;
   color: white;
   text-align: center;
}

.description {
  font-size: 20px;
}

.image-descrip{
  color: blue;
}

.footer-sitemap{
  list-style-type: none;
  float: left;
}
