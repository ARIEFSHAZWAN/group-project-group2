<!DOCTYPE html>
<html lang="en">

  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />


  <title>Lifelong Learning Hub</title>


  <style>
    body { 
      
      font-family: Arial, sans-serif; margin: 0; background: #f4f4f4; 
      background-color: #080506;
      background-position: center;
      background-repeat: no-repeat;
       min-height: 100vh;
  display: flex;
  flex-direction: column;
  
        
    }
    header{
      background-color: #decbd4;
      background-image: url('redflow.gif');
      background-size: cover;
      background-position: center;
      text-align: center; 
      padding: 1rem; 
      color: #FBEEF5;
    }
   footer{
     background-color: #0E0204;
      text-align: center; 
      padding: 0rem; 
      color: #FBEEF5;
        display: flex;
  justify-content: space-between;
  align-items: center;
  text-align: center;
  padding: 1rem;
 
  font-size: 0.9rem;
}
footer .left-links,
footer .center-text,
footer .right-links {
  margin: 0;
padding:0;

    }

    .link-container a {
    color: #774972;      /* Normal link color */
    text-decoration: none;
    transition: color 0.3s;
}

.link-container a:hover {
    color: #A30E2B;      /* Color when hovered */
    text-decoration: underline;
}   
    .link-container{
    display: flex;
    justify-content: center;   /* Center horizontally */
    align-items: center;       /* Center vertically */
    min-height: 4vh;          /* Adjust as needed */
    gap: 0rem;
    background-color: #0E0204;
    border: 3px solid #774972;
    border-color: #774972;
 max-height: fit-content;
    padding: 10px;
    font-size: 25px;
    font-weight: bold;
    text-align: center;
    margin: 0 auto; /* This centers the block horizontally */
    width: fit-content;     /* Optional: makes the block narrower and easier to center */
    border-radius: 14px; /* Optional: adds rounded corners */
    }
    nav {   background-color: #040101;
       display: flex; 
       justify-content: space-evenly;
        gap: 2rem; 
       padding: 1rem; 
      flex:1;
    }
    nav a { color: #774972; 
      text-decoration: none;
       font-weight: bold; }
    nav a:hover { color: #A30E2B; }


    main {
       padding: 2rem; text-align: center;
        flex: 1; /* This makes main take up remaining space */
       }

    .picture{

      width: auto;
  height: 500px;            /* Adjust as needed */
  max-width: 600px;
  margin: 0;                /* Remove large margin */
  float: none;
  margin-left: 330px;
 

}
.main-content {
  display: flex;
  align-items: center;      /* Vertically center image and text */
  justify-content: center;  /* Center the whole block horizontally */
  gap: 6rem;                /* Space between text and image */
  padding: 0rem;
}
.center-text {
  text-align: left;         /* Align text to the left */
  margin-left: 50px;
    border: 6px solid #000000;
  max-width: 3000px;
  max-height: 3000px;
  border-radius: 30px;
}
p h2 :hover{
  color: #A30E2B;      /* Color when hovered */
    text-decoration: bold;
}
.content-container{
    text-align: left;         /* Align text to the left */
  margin-left: 50px;
  max-width: 3000px;
  max-height: 3000px;
  font-size: 20px;
  font-weight: bold;
  color: #774972;
}

h2{
  color: #915189;
  font-size: 2.5rem;
  margin-bottom: 2rem;
  font-weight: bold;
  text-align: right;
font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
font-size: 55px;
}
p{
  font-size: 1.2rem;
  margin-bottom: 1rem;
  line-height: 1.6; 
  text-align: right;
font-family: Georgia, 'Times New Roman', Times, serif;
}
h1{
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  font-size: 55px;
  margin: 0;
  padding: 0;
  text-shadow: 2px 2px #A30E2B;
}


  </style>

<head>

</head>
  <header>
    <h1>Lifelong Learning Hub</h1>
    <h3>Empowering growth through continuous learning</h3>
  </header>


  <nav>
    <a href="mywebsite.html">ARIEF</a>
    <a href="MARCUS.web.html">MARCUS</a>
    <a href="Individual Page-Alif.html">ALIF</a>
    <a href="bio.html">ASHRAF</a>

  </nav>
</head>

  <body>
<div class="main-content">
  <div class="content-container" >
    <h2>Welcome to the Lifelong Learning Hub</h2>
    <p>Your gateway to continuous growth and knowledge.</p>

    <p>This website is a collaborative effort by four students to promote lifelong learning. Explore curated resources, meet each member, and discover how continuous education shapes our future.</p>
  </div>
  <img src="sss.png" alt="sss" class="picture">
</div>
  </body>

<footer>
    <div class="left-links"class="link-container">
     <p class=" link-container"> <a href="resource.v1.html">Resources</a></p>
    </div>
    <div class="center-text">
      <p> 2025 Lifelong Learning | Built by Group 2</p>
    </div>
    <div class="right-links"class="link-container">
     <p class="link-container" ><a href="Contact.html">Contact</a> </p>
    </div>
    </footer>
</body>
</html>

