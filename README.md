<!doctype html>
<html class="no-js">
  <head>
    <meta charset="utf-8">
    <title> Ramsaivinod </title>
    <meta name="description" content="">
    <meta name="viewport" content="width=device-width">
    <!-- Place favicon.ico and apple-touch-icon.png in the root directory -->
    <!-- build:css(.) styles/vendor.css -->
    <!-- bower:css -->
    <link rel="stylesheet" href="bower_components/bootstrap/dist/css/bootstrap.css" />
    <!-- endbower -->
    <!-- endbuild -->
    <!-- build:css(.tmp) styles/main.css -->
    <link href='http://fonts.googleapis.com/css?family=Play' rel='stylesheet' type='text/css'>
    <link rel="stylesheet" href="styles/main.css">
    <link rel="stylesheet" href="styles/fontstyles.css">
    <!-- endbuild -->
  </head>
  <body ng-app="myDashboardApp">
    <!--[if lt IE 7]>
      <p class="browsehappy">You are using an <strong>outdated</strong> browser. Please <a href="http://browsehappy.com/">upgrade your browser</a> to improve your experience.</p>
    <![endif]-->

    <!-- Add your site or application content here -->
    <div class="container">
      <div class="header">
        <ul class="nav nav-pills ulstyle pull-right">
          <li class="active"><a ng-href="#">Home</a></li>
          <li><a ng-href="#/menu">Menu</a></li>
          <li><a ng-href="#/about">About</a></li>
          <li><a ng-href="#/contact">Contact</a></li>
        </ul>
        <h3 class="header-font">Vishnu </h3>
      </div>

      <div ng-view=""></div>

      <div class="footer">
        <p><span class="glyphicon glyphicon-copyright-mark"></span> Indian Cuisine</p>
      </div>
    </div>


    <!-- Google Analytics: change UA-XXXXX-X to be your site's ID -->
     <script>
       (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
       (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
       m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
       })(window,document,'script','//www.google-analytics.com/analytics.js','ga');
       ga('create', 'UA-XXXXX-X');
       ga('send', 'pageview');
    </script>

    <!--[if lt IE 9]>
    <script src="bower_components/es5-shim/es5-shim.js"></script>
    <script src="bower_components/json3/lib/json3.min.js"></script>
    <![endif]-->

    <!-- build:js(.) scripts/vendor.js -->
    <!-- bower:js -->
    <script src="bower_components/jquery/dist/jquery.js"></script>
    <script src="bower_components/angular/angular.js"></script>
    <script src="bower_components/json3/lib/json3.js"></script>
    <script src="bower_components/bootstrap/dist/js/bootstrap.js"></script>
    <script src="bower_components/angular-resource/angular-resource.js"></script>
    <script src="bower_components/angular-cookies/angular-cookies.js"></script>
    <script src="bower_components/angular-sanitize/angular-sanitize.js"></script>
    <script src="bower_components/angular-animate/angular-animate.js"></script>
    <script src="bower_components/angular-touch/angular-touch.js"></script>
    <script src="bower_components/angular-route/angular-route.js"></script>
    <script src="bower_components/angular-bootstrap/ui-bootstrap.js"></script>

    <!-- endbower -->
    <!-- endbuild -->

        <!-- build:js({.tmp,app}) scripts/scripts.js -->
        <script src="scripts/app.js"></script>
        <script src="scripts/controllers/main.js"></script>
        <script src="scripts/controllers/about.js"></script>
        <script src="scripts/controllers/hotel_menu.js"></script>
        <script src="scripts/controllers/contact.js"></script>
        <script src="scripts/controllers/CarouselCtrl.js"></script>
        <!-- endbuild -->
</body>
</html>
