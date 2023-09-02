<!DOCTYPE html>
<html lang="en">
<head>
   <meta charset="UTF-8">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>Portfolio</title>
   <link rel="preconnect" href="https://fonts.googleapis.com">
   <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
   <link rel="preconnect" href="https://fonts.googleapis.com">
   <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
   <link href="https://fonts.googleapis.com/css2?family=El+Messiri&family=Oswald:wght@200;300;400;500;600;700&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap" rel="stylesheet">
   <style>
      *{
      font-family: 'El Messiri', sans-serif;
      font-family: 'Oswald', sans-serif;
      font-family: 'Roboto', sans-serif;
      margin: 0;
      text-decoration: none;
      }

      header{
         display: flex;
         width:100%;
         height: 100px;
         flex-direction: row;
         justify-content: space-between;
         align-items: center;
         box-shadow: 2px 2px 20px 3px rgba(71, 71, 71, 0.267);

      }

      ul{
         display: flex;
         font-weight: 500;
         justify-content: space-evenly;
         align-items: left;
         padding: 10px;
      }

      li{   
         list-style-type: none;
         flex-direction: row;
         padding: 0 10px;
         cursor: pointer;
      }

      li:hover{
         color:rgba(0, 0, 0, 0.582);
      }

      .logo h1{
         color: black;
      }

      .logo span{
         color:rgba(0, 0, 0, 0.479);
         cursor: pointer;
      }

      .social-media-icons{
         margin-right: 20px;
      }

      .social-media-icons a{
         color: black;
         font-size: 1.2em;
         margin: 10px;
      }

      section{
         width: 100%;
         flex-direction: row;
         display: flex;
      }

      .left{
         width: 33.333%;
         display: flex;
         flex-direction: column;
         margin: 10px;
      }

      .left h2{
         font-weight: 700;
         margin: 35% 0 35px 25%;
      }

      .cards{
         display: flex;
         flex-direction: column;
         align-items: center;
         justify-content: space-between;
      }

      .card{
         display: flex;
         flex-direction: column;
         border-radius: 10px;
         width:53%;
         height: 50%;
         margin-bottom: 35px;
      }

      .head{
         display: flex;
         flex-direction: row;
         padding: 3px;
      }

      .head h3{
         padding-left: 3px;
         font-weight: 600;
         font-size: 1.2em;
      }

      .head i{
         font-size: 1.2em;
      }

      .info{
         color: rgba(0, 0, 0, 0.356);
         font-size: 0.9em;
         padding: 3px 3px 5px 7px; 
      }

      .middle{
         display: flex;
         align-items: center;
         flex-direction: column;
         width: 33.333%;
      }

      .middle h1{
         margin: 30% 0 20px;
         font-size: 5em;
         font-weight: 800;
      }

      .middle img{
         width:300px;
         height: 300px;
         background-color: rgb(0, 132, 255);
         border: 7px solid rgb(228, 228, 228);
         border-radius: 15px;
      }

      .right{
         display: flex;
         align-items: center;
         flex-direction: column;
         width: 33.333%;
      }

      .content{
         margin: 35% 0 35px 25%;
      }

      .content h2{
         width: 90%;
         font-weight: 700;
         margin: 0 0 35px 5px;
      }

      .content .info p{
         width: 70%;
      }

      button{
         color: white;
         background-color: black;
         width: 80px;
         height: 40px;
         font-size: 1.1em;
         font-weight: 500;
         border: none;
         margin: 17px 0 25px 0;
      }

      .contaner{
         width: 100%;
         display: flex;
         flex-direction: row;
      }

      .analiyes{
         margin-right: 35px;
      }

      .analiyes h1{
         font-size: 1.8em;
         padding-bottom: 10px;
         color: black;
      }

      .analiyes span{
         font-size: 1.3em;
         font-weight: 300;
         color:rgba(0, 0, 0, 0.356);
      }
   </style>
</head>
<body>
   <header class="header">
      <div class="tabs">
         <ul>
            <li>Home</li>
            <li>Portfolio</li>
            <li>Blog</li>
            <li>About</li>
            <li>Contact</li>
         </ul>
      </div>
      <div class="logo">
         <a href=""><h1>Portfolio<span>2</span>Grow</h1></a>
      </div>
      <div class="social-media-icons">
         <a href="#"><i class="fa-brands fa-instagram"></i></a>
         <a href="#"><i class="fa-brands fa-square-facebook"></i></a>
         <a href="#"><i class="fa-brands fa-twitter"></i></a>
         <a href="#"><i class="fa-brands fa-linkedin"></i></a>
      </div>
   </header>

   <section>
      <div class="left">
         <h2>Services</h2>
         <div class="cards">
         <div class="card">
            <div class="head">
               <i class="fa-solid fa-window-maximize"></i>               
               <h3>Web Devolopment</h3>
            </div>
            <div class="info">
                  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
            </div>
         </div>

         <div class="card">
            <div class="head">
               <i class="fa-solid fa-paint-roller"></i>               
               <h3>Ui/Ux Design</h3>
            </div>
            <div class="info">
                  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
            </div>
         </div>

         
         <div class="card">
            <div class="head">
               <i class="fa-solid fa-code"></i>
               <h3>Web conculating</h3>
            </div>
            <div class="info">
                  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
            </div>
         </div>
         </div>
      </div>

      <div class="middle">
         <h1>Ahmed Sabry</h1>
         <img src="https://s3-alpha-sig.figma.com/img/ce04/e78f/477061647ee634d23d2d9322001356cc?Expires=1694390400&Signature=Jqp8bDI6i0Rmufl2tXvw3x~DKNnXS0witMpmJSMQbhWesnS5Xs-udeTmzsI6HbdZ0vOmYTBy03he4t43hq8NhTIo-QOik5IHYI2Z3XSCU7kRFPj9jFezvFPqwpEVg2GUTwQ18a7fvM9VdNTjCTp2udKMQwem2m8H8UqSALLKk9u6Hoqd4tuGK1jbEZDlQi2RKKNhUmHhbEKmiB9czzWE9~eUMqK4SM2jaJEegUQT2VFVavsbk8l8c134wk6~CkNqxbDX6Cgvn9RaBQN6jen~2U-zKdU8qhEINIQpZmtYt~m~gTjr3KosH9fziY9Ofmxlu-aFM-ngPWcaJQN4V0XEAQ__&Key-Pair-Id=APKAQ4GOSFWCVNEHN3O4" alt="">
      </div>

      <div class="right">
         <div class="content">
            <h2>Software Developer Specialized In Frontend Web Development</h2>
            <div class="info">
               <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
               <br>
               <br>
               <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
               <a class="button" href=""><button>Hire me</button></a>

               <div class="contaner">
                  <div class="analiyes">
                     <h1>9+ Years</h1>
                     <span>Experience</span>
                  </div>
                  <div class="analiyes">
                     <h1>99+</h1>
                     <span>Clients</span>
                  </div>
               </div>
            </div>
         </div>
      </div>
   </section>
</body>
</html>
