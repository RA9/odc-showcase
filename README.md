<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bootstrap demo</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js"></script>
    <style>
        .pic {
            width: 100%;
            height: 300px;
            object-fit: cover;
        }
        
        div {
            margin: 10px 90px 40px 40px;
            
        }
        
        h3 {
            color: brown;
        }
        
      </style>
  </head>
  <body>
      <main>
         <div id="stanz" class="carousel slide" data-bs-ride="carousel">
           <div class="carousel-indicators">
              <button type="botton" data-bs-target="#stanz" data-bs-slide-to="0" class="active"></button>
              <button type="botton" data-bs-target="#stanz" data-bs-slide-to="1" ></button>
              <button type="botton" data-bs-target="#stanz" data-bs-slide-to="2" ></button>
           </div>
           <div class="carousel-inner">
              <div class="carousel-item active">
                 <img src="images\River.jpg" class="pic"  alt="River">
                 <div class="carousel-caption d-none d-md-block">
                    <h3>St. John River</h3>
                    <p>Welcome to St. John River tour.</p>
                 </div>
              </div>
              <div class="carousel-item">
                 <img src="images\Flower.jpg" class="pic"  alt="Flower"> 
              </div>
              <div class="carousel-item">
                 <img src="images\Sunset.jpg" class="pic"  alt="Sunset"> 
              </div>
           </div>
           <button class="carousel-control-prev" type="button" data-bs-target="#stanz" data-bs-slide="prev">
              <span class="carousel-control-prev-icon"></span>
              <span class="visually-hidden">Previous</span>
           </button>
           <button class="carousel-control-next" type="button" data-bs-target="#stanz" data-bs-slide="next">
              <span class="carousel-control-next-icon"></span>
               <span class="visually-hidden">Next</span>
           </button>
          </div> 
      </main>
  </body>
</html>
