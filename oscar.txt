<!doctype html>
<html lang="id">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Calon Resto</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
      body {
        font-family: Arial, sans-serif;
        background-color: #111; 
        color: #f1c40f; 
      }
      header.navbar {
        background-color: #000 !important;
      }
      header .navbar-brand {
        font-weight: bold;
        font-size: 20px;
        color: #f1c40f !important;
      }
      .sidebar {
        background-color: #222;
      }
      .sidebar .nav-link {
        color: #f1c40f;
      }
      .sidebar .nav-link.active,
      .sidebar .nav-link:hover {
        background-color: #f1c40f;
        color: #000;
        font-weight: bold;
      }
      .card {
        background-color: #222;
        border: none;
      }
      .card-title {
        color: #f1c40f;
      }
      footer {
        text-align: center;
        padding: 15px;
        background: #000;
        color: #f1c40f;
        margin-bottom: 20px;
      }
    </style>
  </head>
  <body>
    
    <header class="navbar sticky-top flex-md-nowrap p-0 shadow">
      <a class="navbar-brand col-md-3 col-lg-2 px-3" href="#">CalonResto.com</a>
    </header>

    <div class="container-fluid">
      <div class="row">
        
        <nav class="col-md-3 col-lg-2 d-md-block sidebar collapse p-3">
          <h4 class="text-warning">Menu</h4>
          <ul class="nav flex-column">
            <li class="nav-item">
              <a class="nav-link active" href="#">🏠 Beranda</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">🍕 Makanan Berat</a>
            </li>
            
            <li class="nav-item">
              <a class="nav-link" href="#">🥤 Minuman</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">🍰 Dessert</a>
            </li>
          </ul>
        </nav>

        <main class="col-md-9 ms-sm-auto col-lg-10 px-md-4">
          <div class="pt-3 pb-2 mb-3 border-bottom border-warning">
            <h1 class="h2">Selamat Datang di Restoran Lezat</h1>
            <p class="text-light">Semua makanan di sini enak, mahal? jelas, yang jual pengen naik mekleren aowkaowkao</p>
          </div>

         
          <div class="row">
            <div class="col-md-4">
              <div class="card mb-3">
                <img src="" class="card-img-top" alt="Pizza">
                <div class="card-body">
                  <h5 class="card-title">Pizza</h5>
                  <p class="card-text text-light">Hanya Rp 150.000</p>
                  <button class="btn btn-warning text-dark">Pesan</button>
                </div>
              </div>
            </div>

            <div class="col-md-4">
              <div class="card mb-3">
                <img src="" class="card-img-top" alt="Burger">
                <div class="card-body">
                  <h5 class="card-title">Cheese Burger</h5>
                  <p class="card-text text-light">Hanya Rp 70.000</p>
                  <button class="btn btn-warning text-dark">Pesan</button>
                </div>
              </div>
            </div>

            <div class="col-md-4">
              <div class="card mb-3">
                <img src="" class="card-img-top" alt="Minuman">
                <div class="card-body">
                  <h5 class="card-title">Donat  Kacang </h5>
                  <p class="card-text text-light">Hanya Rp 50.000</p>
                  <button class="btn btn-warning text-dark">Pesan</button>
                </div>
              </div>
            </div>

            <div class="col-md-4">
              <div class="card mb-3">
                <img src="" class="card-img-top" alt="Burger">
                <div class="card-body">
                  <h5 class="card-title">Milkshake</h5>
                  <p class="card-text text-light">Hanya Rp 39.000</p>
                  <button class="btn btn-warning text-dark">Pesan</button>
                </div>
              </div>
            </div>

            <div class="col-md-4">
              <div class="card mb-3">
                <img src="" class="card-img-top" alt="Burger">
                <div class="card-body">
                  <h5 class="card-title">Matcha Latte</h5>
                  <p class="card-text text-light">Hanya Rp 99.000</p>
                  <button class="btn btn-warning text-dark">Pesan</button>
                </div>
              </div>
            </div>

            <div class="col-md-4">
              <div class="card mb-3">
                <img src="" class="card-img-top" alt="Burger">
                <div class="card-body">
                  <h5 class="card-title">Capucino</h5>
                  <p class="card-text text-light">Hanya Rp 80.000</p>
                  <button class="btn btn-warning text-dark">Pesan</button>
                </div>
              </div>
            </div>
          </div>
        </main>
      </div>
    </div>
    
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
  </body>
</html>
