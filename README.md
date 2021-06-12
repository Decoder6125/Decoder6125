<!doctype html>

<html lang="en">
<head>
    <style>
* {
    font-family: 'El Messiri', sans-serif;
}
      
#parent {
  height: 40px;
  white-space: nowrap;
  overflow: hidden; 
  font-family: 'Source Code Pro', monospace;  
  font-size: 28px;
  color: black;
  position: relative;
}

#border {
  border-bottom: solid 3px tomato;
  position: absolute;
  right: -7px;
  width: 20px;
}

/* Animation */
#parent {
  animation: animated-text 2s steps(30,end) 1s 1 normal both
}

#border {
   animation: animated-cursor 600ms steps(30,end) infinite;
}

/* text animation */

@keyframes animated-text{
  from{width: 0;}
  to{width: 530px;}
}

/* cursor animations */

@keyframes animated-cursor{
  from{border-bottom-color: rgba(0,255,0,.75);}
  to{border-bottom-color: transparent;}
}









        .container {
            width: 90%;
            height: 400px;
            background:white;
            display: flex;
            justify-content: space-around;
        }


        .container .left {
            width: 60%;
            background: white;
            margin-left: 0;
        }

        
        .container .right {
            width: 40%;
            background: white;
        }

        .container .left .top-left {
            top: 0;
            width: 100%;
            background: white;
            height: 80px;
        
        }

    </style>
  <meta charset="utf-8">
  <link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=El+Messiri&display=swap" rel="stylesheet">
  <title>The HTML5 Herald</title>
  <meta name="description" content="The HTML5 Herald">
  <meta name="author" content="SitePoint">

  <link rel="stylesheet" href="css/styles.css?v=1.0">

</head>

<body>
  <h2><div id="parent">Let's know about this random guy...<div id="border"></div></div></h2>


  <p>Hi, I'm Debtanu Dey, a passionate self-taught Full Stack web developer... My passion for web applications 
      lies with dreaming up ideas and making them come true with elegant interfaces. I specially take care in the user experience, architecture
      and quality of the things I build... <br><br>

      I also want to become an open-source contributor as I learned a lot from the open-source community....
      😍 The way of sharing knowledge is just awesome...




  </p>
<center>
<div class="container">
    <div class="left">
        <h3>Languages and Tools</h3>
    <div class="top-left">
   <img src="https://img.icons8.com/color/452/mongodb.png" height="50px" width="50px">
   <img src="https://camo.githubusercontent.com/13dcf86b6d12e0fd9cec2a3144b3fefa90cac83e133629902091e5fda9358e0a/68747470733a2f2f692e696d6775722e636f6d2f755477734154542e706e67" height="50px" width="60px">
   <img src="https://logowiki.net/uploads/logo/r/react-1.svg" height="50px" width="50px">
   <img src="https://cdn.iconscout.com/icon/free/png-512/node-js-1-1174935.png" height="50px" width="50px">
   <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/99/Unofficial_JavaScript_logo_2.svg/480px-Unofficial_JavaScript_logo_2.svg.png" height="50px" width="50px">
   <img src="https://cdn.dribbble.com/users/2653319/screenshots/6813714/figma_logo_animation.gif" height="50px" width="50px">
   <img src="https://firebase.google.com/images/brand-guidelines/logo-logomark.png" height="50px" width="50px">
   <img src="https://mpng.subpng.com/20180420/xwe/kisspng-web-development-cascading-style-sheets-css3-comput-css-5ada20be146fc2.8807141415242446700837.jpg" height="50px" width="50px">
   <img src="https://preview.redd.it/31b2ii8hchi31.jpg?auto=webp&s=309fe75e96212cf42c4120ca5adedaef52c41e01" height="50px" width="50px"> 
</div>
<br><br>
I'm spending time on :- <br>

👉Data structures and Algorithms <br>
👉MERN full stack developement

    </div>





    <div class="right">
        <img src ="https://cdn.dribbble.com/users/1233499/screenshots/3850691/web-development.gif" height="400px" width="450px">
    </div>
</div>
</center>


  <script src="js/scripts.js"></script>
</body>
</html>