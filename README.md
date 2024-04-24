# 1a

!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
  <title>TravelSite</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" rel="stylesheet">
  <!-- Custom CSS -->
  <style>
    /* Add your custom styles here */
    body {
      padding-top: 56px; /* Adjust according to your navbar height */
      background-color: #f8f9fa;
      color: #343a40;
    }
    .card {
      margin-bottom: 20px;
      border: none;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }
    .navbar {
      background-color: #343a40;
    }
    .navbar-brand {
      font-size: 1.8rem;
      color: #ffffff;
    }
    .navbar-toggler-icon {
      background-color: #ffffff;
    }
    .sidebar {
      height: 100vh;
      position: fixed;
      top: 56px; /* Adjust according to your navbar height */
      border-right: 1px solid #dee2e6;
      background-color: #ffffff;
    }
    .main-content {
      margin-top: 56px; /* Adjust according to your navbar height */
    }
    .card-img-top {
      max-height: 200px;
      object-fit: cover;
      border-top-left-radius: 10px;
      border-top-right-radius: 10px;
    }
    .card-body {
      padding: 20px;
    }
    .card-title {
      color: #343a40;
    }
    .card-text {
      color: #6c757d;
    }
    .dropdown-menu {
      background-color: #343a40;
    }
    .dropdown-item {
      color: #ffffff;
    }
    .jumbotron {
      background-color: #343a40;
      color: #ffffff;
      border-radius: 0;
    }
  </style>
</head>
<body>

<!-- Navigation Bar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
  <a class="navbar-brand" href="#">TravelSite</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarResponsive">
    <ul class="navbar-nav ml-auto">
      <li class="nav-item active">
        <a class="nav-link" href="#">Home</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Destinations</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Packages</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Contact</a>
      </li>
    </ul>
  </div>
</nav>

<!-- Page Content -->
<div class="container-fluid">
  <div class="row">
    <!-- Sidebar -->
    <nav class="col-md-2 d-none d-md-block bg-light sidebar">
      <div class="sidebar-sticky">
        <ul class="nav flex-column">
          <li class="nav-item">
            <a class="nav-link" href="#">
              <span data-toggle="tooltip" data-placement="right" title="Explore destinations" style="color: #343a40;">Explore</span>
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">
              <span data-toggle="tooltip" data-placement="right" title="View packages" style="color: #343a40;">Packages</span>
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">
              <span data-toggle="tooltip" data-placement="right" title="Contact us" style="color: #343a40;">Contact</span>
            </a>
          </li>
        </ul>
      </div>
    </nav>

    <!-- Main Content -->
    <main role="main" class="col-md-9 ml-sm-auto col-lg-10 px-4 main-content">
      <div class="jumbotron">
        <h1 class="display-4">Welcome to TravelSite</h1>
        <p class="lead">Explore the world with our exciting travel packages. Unforgettable experiences await you!</p>
      </div>

      <!-- Image Grid -->
      <div class="row">
        <div class="col-md-4">
          <img src="D:\Bhavana\imeges\europe jpg.jpg" class="img-fluid rounded" alt="Destination 1 Europe">
        </div>
        <div class="col-md-4">
          <img src="D:\Bhavana\imeges\asia.jpg" class="img-fluid rounded" alt="Destination 2 Asia">
        </div>
        <div class="col-md-4">
          <img src="D:\Bhavana\imeges\north america.jpg" class="img-fluid rounded" alt="Destination 3 North America">
        </div>
      </div>

      <!-- Cards -->
      <div class="row">
        <div class="col-md-4">
          <div class="card">
            <img src="D:\Bhavana\imeges\europe2.jpg" class="card-img-top" alt="Package 1">
            <div class="card-body">
              <h5 class="card-title">Europe</h5>
              <p class="card-text">Currently offers over 210 tour packages to Europe, with prices starting as low as Rs. 37971. Explore a variety of itineraries and choose from Europe travel packages with or without flights. With our unbeatable deals and discounts, your money goes further!...</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
            <img src="D:\Bhavana\imeges\asia2.webp" class="card-img-top" alt="Package 2">
            <div class="card-body">
              <h5 class="card-title">Asia</h5>
              <p class="card-text">Currently offers over 234 tour packages to Asia, with prices starting as low as Rs. 19607. Explore a variety of itineraries and choose from Asia travel packages with or without flights. With our unbeatable deals and discounts, your money goes further!...</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
            <img src="D:\Bhavana\imeges\north america2.jpg" class="card-img-top" alt="Package 3">
            <div class="card-body">
            <h5 class="card-title">North America</h5>
            <p class="card-text">Most Popular North America Tour Packages · East Coast of Canada · Best of Canadian Rockies (Summer 2024) · Canadian Delights · Canada Delights With Alaskan Cruise</p>
          </div>
          </div>
 <!-- Dropdown -->
 <div class="dropdown mt-4">
  <button class="btn btn-secondary dropdown-toggle" type="button" id="dropdownMenuButton" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
    Destinations
   </button>
      <div class="dropdown-menu" aria-labelledby="dropdownMenuButton">
      <a class="dropdown-item" href="#">Asia</a>
      <a class="dropdown-item" href="#">Europe</a>
      <a class="dropdown-item" href="#">North America</a>
      </div>
     </div>
    </main>
  </div>
</div>

<!-- Bootstrap JS and Popper.js -->
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>

<!-- Initialize tooltips -->
<script>
  $(function () {
    $('[data-toggle="tooltip"]').tooltip()
  })
</script>

</body>
</html>
