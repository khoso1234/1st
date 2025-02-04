
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bootstrap demo</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css" integrity="sha512-Evv84Mr4kqVGRNSgIGL/F/aIDqQb7xQ2vcrdIwxfjThSH8CSR7PBEakCr51Ck+w+/U6swU2Im1vVX0SVk9ABhg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link rel="stylesheet" href="style.css">
</head>
  <body>
    <nav class="navbar navbar-expand-lg bg-light">
     <div class="container">
       <a class="navbar-brand" href="#">
         <img src="https://picsum.photos/50" class="rounded-circle" alt=""> <span class="px-2">TIME</span>
       </a>
       <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
         <span class="navbar-toggler-icon"></span>
       </button>
       <div class="collapse navbar-collapse justify-content-end" id="navbarSupportedContent">
         <ul class="navbar-nav mb-2 mb-lg-0">
           <li class="nav-item">
             <a class="nav-link active" aria-current="page" href="#home">Home</a>
           </li>

           <li class="nav-item">
            <a class="nav-link" aria-current="page" href="#about">About</a>
          </li>

          <li class="nav-item">
           <a class="nav-link" aria-current="page" href="#programs">Programs</a>
         </li>
         </ul>
       </div>
     </div>
    </nav>
    <!-- Navbar ends here -->
   <div class="container">
      <!-- step 1 Carousel section   -->
      <div class="row my-5" id="home">
       <div class="col">
        <div id="carouselExampleCaptions" class="carousel slide rounded shadow" data-bs-ride="false">
         <div class="carousel-indicators">
           <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
           <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
           <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
           <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="3" aria-label="Slide 4"></button>
         </div>
         <div class="carousel-inner">
           <div class="carousel-item active">
             <img src="https://picsum.photos/seed/6561321654/1500/400" class="d-block w-100" alt="...">
             <div class="carousel-caption d-none d-md-block">
               <h5>Web Development</h5>
               <p>Some representative placeholder content for the first slide.</p>
             </div>
           </div>

           <div class="carousel-item">
             <img src="https://picsum.photos/seed/6561321664/1500/400" class="d-block w-100" alt="...">
             <div class="carousel-caption d-none d-md-block">
               <h5>Graphic Design</h5>
               <p>Some representative placeholder content for the second slide.</p>
             </div>
           </div>

           <div class="carousel-item">
             <img src="https://picsum.photos/seed/6561621654/1500/400" class="d-block w-100" alt="...">
             <div class="carousel-caption d-none d-md-block">
               <h5>Software Services</h5>
               <p>Some representative placeholder content for the third slide.</p>
             </div>
           </div>

           <div class="carousel-item">
            <img src="https://picsum.photos/seed/6563621654/1500/400" class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block">
              <h5>AI Chatbots</h5>
              <p>Some representative placeholder content for the third slide.</p>
            </div>
          </div>

         </div>

         <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
           <span class="carousel-control-prev-icon" aria-hidden="true"></span>
           <span class="visually-hidden">Previous</span>
         </button>
         <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
           <span class="carousel-control-next-icon" aria-hidden="true"></span>
           <span class="visually-hidden">Next</span>
         </button>
        </div>
       </div>
      </div>

      <!-- step 2 About Section -->
      <div class="row justify-content-between my-5" id="about">
       <h1 class="text-center color-hover-red">About</h1>
       <div class="col-md-5">
        <a href="" class="btn btn-outline-danger">Brand</a>
        <h3>Heading About CodePro</h3>
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Cumque et quae doloremque, optio animi in quam nesciunt facilis consectetur obcaecati temporibus nobis velit atque, minima blanditiis alias esse reprehenderit distinctio.</p>
        <i class="fa-brands fa-facebook"></i>
        <i class="fa-brands fa-facebook"></i>
        <i class="fa-brands fa-facebook"></i>
       </div>

       <div class="col-md-5 overflow-hidden ">
         <div class="text-center">
          <img src="https://picsum.photos/300" alt="">
         </div>
         <div class="text-center">
          <h5>Abrar Hussain</h5>
          <p>CEO/ Founder</p>
         </div>
       </div>
      </div>

     <!-- Step 3: Programs section -->
     <div class="row my-5" id="programs">
      <h1 class="text-center">Programs</h1>
      <div class="col-md-4 ">
        <div class="card m-auto" style="width: 18rem;">
         <img src="https://picsum.photos/seed/546134686456/200" class="card-img-top" alt="...">
         <div class="card-body">
           <h5 class="card-title">Web Development</h5>
           <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
           <a href="#" class="btn btn-primary">Read More</a>
         </div>
       </div>
      </div>
      <div class="col-md-4">
        <div class="card m-auto" style="width: 18rem;">
          <img src="https://picsum.photos/seed/546134682456/200" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Graphic Designing</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="#" class="btn btn-primary">Read More</a>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card m-auto" style="width: 18rem;">
          <img src="https://picsum.photos/seed/546134681456/200" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Python Programming</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <button type="button" class="btn btn-primary" data-bs-toggle="modal" 
            data-bs-target="#pythonModal">Read More</button>
          </div>
        </div>
      </div>

     </div>
    </div>



    <!-- My Modal Boxes -->
    <div class="modal fade" id="pythonModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
     <div class="modal-dialog">
       <div class="modal-content">
         <div class="modal-header">
           <h1 class="modal-title fs-5" id="exampleModalLabel">Python Programming</h1>
           <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
         </div>
         <div class="modal-body">
           Here will be information about python programming and so on...
         </div>
         <div class="modal-footer">
           <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
           <button type="button" class="btn btn-primary">Save changes</button>
         </div>
       </div>
     </div>
   </div>
   <!-- Python Modal Ends here -->

    <!-- My layout above this script -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
  </body>
</html>
