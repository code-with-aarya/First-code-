<!DOCTYPE html>

<html>
<head>
  <meta http-equiv="CONTENT-TYPE" content="text/html; charset=UTF-8">
  <title>Hello, World!</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.7/dist/css/bootstrap.min.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css">
   
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.7/dist/js/bootstrap.bundle.min.js"></script>
  <style>
  .im{
     height:200px;
    
  }
  .pic{
      transition:1s;
  }
  .pic:hover{
    transform:scale(1.2);
    transition:0.8s;
      
    
  }
  
   footer {
      background-color: #2c2c2c;
      color: #fff;
      padding: 40px 0;
    }
    .social-icons a {
      color: #fff;
      margin-right: 10px;
      font-size: 20px;
    }
    .useful-links a {
      color: #fff;
      text-decoration: none;
      display: block;
      margin-bottom: 5px;
    }
    .useful-links a:hover {
      text-decoration: underline;
    }
    .footer-logo img {
      width: 150px;
      margin-bottom: 15px;
    }
   .footer{
       font-size:14px;
   }
  </style>
</head>
<body>
  <div class="container bg-secondary"style="min-height:400px;">
    <div class="row Menu bg-primary "style="min-height:75px;">
      <div class="col-sm-12">
        <nav class="navbar navbar-expand-lg ">
  <div class="container-fluid">
    <a class="navbar-brand  fs-3" href="#">Navbar</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#"><i class="fa-solid fa-house"></i> Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#"><i class="fa-solid fa-link"></i>Link</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
           <i class="fa-solid fa-graduation-cap"></i> Course
          </a>
          <ul class="dropdown-menu" data-bs-toggle="modal" data-bs-target="#exampleModal">
             <!-- Button trigger modal -->
             <div class="input-group flex-nowrap shadow-lg">
  <span class="input-group-text" id="addon-wrapping"><i class="fa-solid fa-user"></i></span>
  <input type="text" class="form-control" placeholder="inter your full name" aria-label="Username" aria-describedby="addon-wrapping">
</div>
             <div class="input-group flex-nowrap shadow-lg mt-3">
  <span class="input-group-text" id="addon-wrapping"><i class="fa-solid fa-envelope"></i></span>
  <input type="email" class="form-control" placeholder="inter your email id" aria-label="Username" aria-describedby="addon-wrapping">
</div>
       <div class="input-group flex-nowrap shadow-lg mt-3">
  <span class="input-group-text" id="addon-wrapping"><i class="fa-solid fa-phone"></i></span>
  <input type="number" class="form-control" placeholder="inter your mob no" aria-label="Username" aria-describedby="addon-wrapping">
</div>    
   <div class="input-group flex-nowrap shadow-lg mt-3">
  <span class="input-group-text" id="addon-wrapping"><i class="fa-solid fa-graduation-cap"></i></span>
  <input type="text" class="form-control" placeholder="inter your course " aria-label="Username" aria-describedby="addon-wrapping">
</div>
<div class="input-group flex-nowrap shadow-lg mt-3" >
  <span class="input-group-text" id="addon-wrapping"><i class="fa-solid fa-comment"></i></span>
  <input type="text" class="form-control" placeholder="inter your massage" aria-label="Username" aria-describedby="addon-wrapping">
</div>
<button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#exampleModal">
  Launch demo modal
</button>
            <li><a class="dropdown-item" href="#"><i class="fa-brands fa-html5"></i> Html</a></li>
            <li><a class="dropdown-item" href="#"> <i class="fa-brands fa-css3"></i> CSS</a></li>
            <li><a class="dropdown-item" href="#"><i class="fa-brands fa-js"></i> JS</a></li>
             
            <li><hr class="dropdown-divider " data-bs-toggle="modal" data-bs-target="#exampleModalLabel"> <b class="text-danger " >Dropdown</b></li>
            <li><a class="dropdown-item" href="#"><i class="fa-brands fa-python"></i>Python</a></li>
             <li><a class="dropdown-item" href="#"> <i class="fa-brands fa-java"></i>Java</a></li>
             
          </ul>
        </li>
        <li class="nav-item">
          <a class="nav-link " >contact us</a>
        </li>
      </ul>
      <form class="d-flex" role="search">
        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search"/>
        <button class="btn btn-outline-success" type="submit">Search</button>
      </form>
    </div>
  </div>
</nav>
      </div>
      
    </div>
    <div class="row Slider"  style="min-height:200px;">
      <div class="col-sm-12">
        <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
  </div>
  <div class="carousel-inner ">
    <div class="carousel-item active "data-bs-interval="10">
      <img src="/storage/emulated/0/DCIM/Camera/IMG20250713180958.jpg" class="d-block w-100 im img-fluid"  alt="...">
    </div>
    <div class="carousel-item" data-bs-interval="10">
      <img src="/storage/emulated/0/DCIM/Camera/IMG20250713180945.jpg" class="d-block w-100 im img-fluid " alt="...">
    </div>
    <div class="carousel-item"   data-bs-interval="10" >
      <img src="/storage/emulated/0/DCIM/Camera/IMG20250712173742.jpg" class="d-block w-100 im img-fluid" alt="...">
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
      </div>
    </div>
    <div class="row bg-success" style="min-height:400px;" >
      <div class="h2 text-center  mt-2">About <b class="text-danger">us</b></div>
      
      
      <div class="col-sm-6">
        <img src="/storage/emulated/0/DCIM/Camera/IMG20250712140803.jpg" class="img-thumbnail w-100">
      </div>
       <div class="col-sm-6 p-3 fs-e">
          <p>2005, at the age of 13, Bevis made her debut under the ring name Britani Knight for her family's World Association of Wrestling (WAW) promotion. She went on to hold several championships on the European independent circuit. After talent scouting in England, WWE signed Bevis in 2011 and she began wrestling in its developmental systems
            </p>
       </div>
    </div>
    <div class="container">
      
    <div class="row Picture" style="min-height:400px;">
       <div class="h2 text-center mt-2">Picture <b class="text-danger">gallery</b></div>
      
      <div class="col-sm-4 ">
        <img src="/storage/emulated/0/DCIM/Camera/IMG20250711125313.jpg" class="img-thumbnail w-100 pic">
      </div>
      <div class="col-sm-4">
                <img src="/storage/emulated/0/DCIM/Camera/IMG20250705104950.jpg" class="img-thumbnail w-100 pic">
   
      </div>
      <div class="col-sm-4">
                <img src="/storage/emulated/0/DCIM/Camera/IMG20250710215214.jpg" class="img-thumbnail w-100 pic">
   
      </div>
      
    </div>
      <div class="row  " style="min-height:200px;">
        <div class="col-sm-3">
          <img  class="img-thumbnail w-100 pic"  src="/storage/emulated/0/DCIM/Camera/IMG20250705104951.jpg">
          
        </div>
        <div class="col-sm-3">
          <img  class="img-thumbnail w-100 pic" src="/storage/emulated/0/DCIM/Camera/IMG20250710212856.jpg">
        
        </div>
         <div class="col-sm-3">
           <img class="img-thumbnail w-100 pic" src="/storage/emulated/0/DCIM/Camera/IMG20250705104951.jpg">
        
         </div>
        <div class="col-sm-3">
          <img class="img-thumbnail w-100 pic" src="/storage/emulated/0/DCIM/Camera/IMG20250705104951.jpg">
        
        </div>
        
      </div>
      <div class="row Picture" style="min-height:300px;">
       <div class="h2 text-center mt-2"></div>
      
      <div class="col-sm-4 ">
        <img src="/storage/emulated/0/DCIM/Camera/IMG20250711125313.jpg" class="img-thumbnail w-100 pic">
      </div>
      <div class="col-sm-4">
                <img src="/storage/emulated/0/DCIM/Camera/IMG20250705104950.jpg" class="img-thumbnail w-100 pic">
   
      </div>
      <div class="col-sm-4">
                <img src="/storage/emulated/0/DCIM/Camera/IMG20250710215214.jpg" class="img-thumbnail w-100 pic">
   
      </div>
      
    </div>
     </div>
    <div class="row Services bg-danger" style="min-height:200px;">
       <div class="h2 text-center mt-2"> our<b class="text-danger">services</b></div>
      
      <div class="col-sm-4" >
        <div class="card mt-5 mb-5 mx-auto shadow-lg" style="width: 15rem;">
  <img src="/storage/emulated/0/DCIM/Camera/IMG20250710215214.jpg" class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">offline course</h5>
    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card’s content.</p>
    <a href="#" class="btn btn-outline-primary" >enroll now</a>
  </div>
</div>
      </div>
      <div class="col-sm-4 " >        <div class="card mt-5 mb-5 mx-auto shadow-lg" style="width: 15rem;">
  <img src="/storage/emulated/0/DCIM/Camera/IMG20250710212856.jpg" class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">web technology   <span class="badge text-bg-secondary">New</span></h5>
    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card’s content.</p>
    <a href="#"  class="btn btn-outline-primary">SignIn/Up</a>
  </div>
</div></div>
      <div class="col-sm-4" >
              <div class="card mt-5 mb-5 mx-auto shadow-lg" style="width: 15rem;">
  <img src="/storage/emulated/0/DCIM/Camera/IMG20250711073734.jpg" class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">Data science <span class="badge text-bg-secondary">New</span> </h5>
    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card’s content.</p>
    <a href="#"   class="btn btn-outline-primary" >Buy</a>
  </div> 
      </div>   

</div>
      
      
      
    </div>
     <!--

  
-->
    <div class="row Footer bg-dark" style="min-height:400px;">
       <div class="col-sm-4">
          <img class="mt-4 mx-3" src="/storage/emulated/0/Download/gem.png" height="70">
          <img class="mt-4 mx-3"src="/storage/emulated/0/Download/start.png" height="70">
          <img class="mt-4 mx-3"src="/storage/emulated/0/Download/Playstore.png" height="70">         
          
       </div>
      <div class="col-sm-4">
        
         <div class="row" style="min-height:250px;">
            <div class="h5 mt-5 text-light">Useful link</div>
            <div class="col-sm-6 text-light">
 
               <i class="fa-solid fa-arrow-right"></i>Home<br>
             
             <i class="fa-solid fa-arrow-right"></i>about us<br>
             <i class="fa-solid fa-arrow-right"></i>picture gallery<br>
             <i class="fa-solid fa-arrow-right"></i>our services<br>
             <i class="fa-solid fa-arrow-right"></i>contact us<br>
             <i class="fa-solid fa-arrow-right"></i>our team<br>
             
               
    
            </div>
            <div class="col-sm-6 text-light">
              <i class="fa-solid fa-arrow-right"></i>online<br>
           
             <i class="fa-solid fa-arrow-right"></i>offline<br>
             <i class="fa-solid fa-arrow-right"></i>free<br>
             <i class="fa-solid fa-arrow-right"></i>login<br>
             <i class="fa-solid fa-arrow-right"></i>term condition<br>
             <i class="fa-solid fa-arrow-right"></i>pribacy and policy<br>
             
            </div>
            
         </div>
      </div>
           <div class="col-sm-4 text-light footer">
                          <div class="h5 mt-5  text-light">contact address</div>
              <i class="fa-solid fa-home "></i><p style="color:white;">Plot No-43, Behind H.P Petrol Pump,<br>
Tedhi Pulia Ring Rd<br>, Sector 5,
Vikas Nagar,<br> Lucknow,
Uttar Pradesh 226022</p></i>
       <i class="fa-solid fa-phone text-light"></i>  +91-885890xxxx   <br>
       
       
       <i class="fa-solid fa-envelope"></i> 
       
       aryacoder213@gmail.com<br>
       <b  class="  text-danger shadow-lg rounded-3">Follow </b>for more 
       <a href="https://www.instagram.com/shubhworldwide/?utm_source=ig_web_button_share_sheet"><i class="fa-brands text-warning bg-dark fa-instagram " ></i></a>
        <a href="https://www.whatshapp.com/anshu"><i class="fa-brands rounded-1 text-success bg-dark fa-whatsapp " ></i></a>
         <a href="https://www.facebook.com/Cristiano/"><i class="fa-brands text-primary bg-dark fa-square-facebook " ></i></a>
          <a href="https://youtube.com/@cristiano?si=yp7fVDxF4HmGS242"><i class="fa-brands fa-youtube text-danger "></i></a>
       <a href="https://x.com/cristiano"> <i class="fa-brands fa-x-twitter"></i></a>
         
     
       
           </div>
              </div>

  <div class="text-center ">
    <small>&copy; 2025 Your Company Name</small>  
     </div> 
</body>
</html>