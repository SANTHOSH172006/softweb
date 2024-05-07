# Ex.07 Software Product Company Website
## Date:25-04-2024

## AIM:
To develop a static company website to display the softwares and services provided by the company.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
home.html

<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>CodeCraft</title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: 'Courier New', Courier, monospace;
                        }
            .banner {
                width: 100%;
                height: 100vh;
                background-size: cover;
                background-position: center;
		background-color:purple;
            }
            .navbar {
                width: 85%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .logo {
                color : black;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: black;
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(255, 255, 255, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: white;
            } 
            ::placeholder {
                color: black;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color : white;
                border-radius: 10px;
                background : black;
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative; 
            }
            .navbar li a {
                text-decoration: none;
                color: white;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color:white;
                background-color :black;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .content {
                position: absolute;
                top: 50%;
                left: 50%;
                transform: translate(-50%,-50%);
                text-align: center;
            }
            .text h2 {
                color: black;
                font-weight: 800;
                font-size: 50px;
                letter-spacing: 3px;
            }
	    .text h3 {
                color: black;
                font-weight: 800;
                font-size: 22px;
                letter-spacing: 3px;
            }
	
            .text p {
                color: white;
                text-transform: capitalize;
                font-size: 17px;
                margin-bottom: 30px;
                word-spacing: 2px;
                letter-spacing: 1px;
	
            }
                footer {
                background-color: white;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo"><span>CodeMakers</span></h1>
            <ul>
                <li><a href="home.html"> Home </a></li>
                <li><a href="product.html"> Products</a></li>
                <li><a href="people.html"> People </a></li>
                <li><a href="contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="content">
            <div class="text">
                <h2><span> CodeMakers </span></h2>
                <br>
		<h3>Welcome to Code Makers, where innovation meets collaboration and the product</h3>
		<br>
                <p> Our commitment to innovation and quality craftsmanship ensures that every product we deliver is not just functional, but a masterpiece of technological artistry. At CodeMakers, we believe in empowering businesses with the tools they need to thrive in the digital landscape, one line of code at a time.</p>
                <br>
                
            </div>
        </div>  
    </div>

    <footer>
        <center> Copyright@2024 Developed by Santhosh D </center>
    </footer>
</body>
</html>

product.html

<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>CodeCraft</title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: 'Courier New', Courier, monospace;
                        }
            .banner {
                width: 100%;
                height: 100vh;
                background-size: cover;
                background-position: center;
		background-color:red;
            }
            .navbar {
                width: 85%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .logo {
                color:black;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: black;
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(255, 255, 255, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: white;
            } 
            ::placeholder {
                color: white;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color:white;
                border-radius: 10px;
                background:black;
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: white;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: white;
                background-color:black;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .container {
                background: transparent;
                padding: 10px 5%;
                padding-bottom: 100px;
            }
            .container .box-container {
                display: grid;
                grid-template-columns: repeat(auto-fit, minmax(170px, 1fr));
                gap: 20px;
            }
            .container .box-container .box {
                color: white;
                box-shadow: 0 5px 10px rgba(0,0,0,.2);
                border-radius: 10px;
                background: transparent;
                border: 1px solid white;
                padding: 10px 5px;
            }
            .container .box-container .box img {
                height: 50px;
                border-radius: 20px;
            }
            .container .box-container .box h3 {
                color: black;
                font-size: larger;
                padding: 10px 0;
            }
            .container .box-container .box p {
                color: white;
                font-size: larger;
                line-height: 1.5;
            }
            footer {
                background-color : white;
                margin-top: auto;
            }
        </style>
    </head>
<body background="image.webp">
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo"><span> CodeMakers</span></h1>
            <ul>
                <li><a href="home.html"> Home </a></li>
                <li><a href="product.html"> Products </a></li>
                <li><a href="people.html"> People </a></li>
                <li><a href="contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="container">
            <div class="box-container">
                <div class="box">
                    <img src="1.png" alt="">
                    <h3>CraftCollab</h3>
                    <p>A collaborative project management platform designed specifically for software development teams. </p>
                </div>

                <div class="box">
                    <img src="2.jpeg" alt="">
                    <h3>CraftGuard</h3>
                    <p>A comprehensive security solution that protects software applications from cyber threats. </p>
                </div>
                <div class="box">
                    <img src="3.png"alt="">
                    <h3>CraftInsights</h3>
                    <p>An advanced analytics platform that provides actionable insights into software performance and user behavior.</p>
                </div>
               
                <div class="box">
                    <img src="4.png" alt="">
                    <h3>CraftAI</h3>
                    <p>An artificial intelligence-powered solution that enhances software functionality through machine learning and predictive analytics.</p>
                </div>
                <div class="box">
                    <img src="5.png" alt="">
                    <h3>CraftERP</h3>
                    <p>An enterprise resource planning (ERP) solution tailored for software companies. </p>
                </div>
 
            </div>
        </div>
    </div>
    <footer>
        <center> Copyright@2024 Developed by SANTHOSH D</center>
    </footer>
</body>
</html>

people.html

<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>CodeCraft</title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: 'Courier New', Courier, monospace;
                        }
            .banner {
                width: 100%;
                height: 100vh;
                background-size: cover;
                background-position: center;
		background-color:burlywood;
            }
            .navbar {
                width: 85%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .logo {
                color:black;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: yellow;
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(255, 255, 255, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: white;
            } 
            ::placeholder {
                color: white;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color:black;
                border-radius: 10px;
                background:gold;
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: white;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: white;
                background-color:gold;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .image {
                position: relative;
                border: 0;
                top: 70px;
                background: transparent;
            }
            .image table {
                border: 0;
                color: white;
                position: relative;
                left: 200px;
            }
            .image table img {
                height: 250px;
                width: 250px;
                border: 2px solid yellow;
                padding: 5px;
                border-radius: 50%;
            }
            .image table td {
                color: yellow;
            }
            footer {
                background-color: white;
                margin-top: auto;
            }
        </style>
    </head>
<body background="image.webp">
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo"><span>Code Makers</h1>
            <ul>
                <li><a href="home.html"> Home </a></li>
                <li><a href="product.html"> Products </a></li>
                <li><a href="people.html"> People </a></li>
                <li><a href="contact.html"> Contact </a></li>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div> 
        <div class="image">
            <table cellspacing="20"> 
                <tr align="center">
                    <td> <img src="vijay.jpg"> </td>
                    <td> <img src="surya.jpg"> </td>
                    <td> <img src="siva.webp"> </td>
                    <td> <img src="vikram.jpg"> </td>
                    
                </tr>
                <tr align="center">
                    <th> vijya</th>
                    <th> Surya</th>
                    <th> Siva </th>
                    <th> Vikram</th>
                   
                </tr>
                <tr align="center">
                    <td> CEO </td>
                    <td> CEO, Co-Founder </td>
                    <td> CTO, Co-Founder </td>
                    <td> Director </td>
                    
                </tr>
            </table>
        </div>
    </div>
    <footer>
        <center> Copyright@2024 Developed by SANTHOSH D</center>
    </footer>
</body>
</html>

contact.html

<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>CodeCraft</title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: 'Courier New', Courier, monospace;
                        }
            .banner {
                width: 100%;
                height: 100vh;
                background-size: cover;
                background-position: center;
		background-color:rgb(113, 128, 0);
            }
            .navbar {
                width: 85%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .logo {
                color:gold;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: yellow;
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(255, 255, 255, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: white;
            } 
            ::placeholder {
                color: white;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color:black;
                border-radius: 10px;
                background:gold;
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: white;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: white;
                background-color:gold;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .box {
                display: flex;
                column-gap: 40px;
                background: transparent;
                position: relative;
                top: 50px;
            }
            .box-1 {
                height: 400px;
                width: 400px;
                border: 3px solid white;
                border-radius: 20px;
                background: transparent;
                position: relative;
                left: 250px;
            }
            .box-2 {
                height: 400px;
                width: 400px;
                border: 3px solid gold;
                border-radius: 20px;
                background: transparent;
                position: relative;
                left: 300px;
            }
            .box-1 form {
                display: flex;
                color: white;
                background: transparent;
                padding: 10px;
                font-size: 15px;
                position: relative;
                top: 15px;
            }
            .box-1 form input {
                background: transparent;
                display: flex;
                border: 1px solid white;
                border-radius: 10px;
                padding: 15px 30px;
                font-size: 15px;
                color: white;
                position: relative;
                top: 30px;
            }
            .box-1 form textarea {
                background: transparent;
                color: white;
                padding: 15px 10px;
                position: relative;
                top: 30px;
                left: 15px;
                border: 1px solid white;
                border-radius: 10px;
            }
            .box-1 form button {
                border: 0;
                outline: none;
                padding: 10px 20px;
                color: white;
                border-radius: 30px;
                background: gold;
                cursor: pointer;
                position: relative;
                top: 50px;
            }
            .box-2 h2 {
                color: white;
                position: relative;
                top: 25px;
                left: 50px;
                font-size: 30px;
            }
            .box-2 p {
                color: white;
                position: relative;
                top: 50px;
                
                padding: 10px 80px;
            }
            .box-2 span {
                color: peru;
                font-size: 30px;
            }
            footer {
                background-color: white;
                margin-top: auto;
            }
        </style>
   </head>
   <body background="image.webp">
       <div class="banner">
           <br>
           <div class="navbar">
               <h1 class="logo"><span> CodeMakers </span></h1>
               <ul>
                <li><a href="home.html"> Home </a></li>
                <li><a href="product.html"> Products </a></li>
                <li><a href="people.html"> People </a></li>
                <li><a href="contact.html"> Contact </a></li>
               </ul>
               <form action="" method="get">
                   <input type="text" placeholder="Enter to Search">
                   <button type="submit"> Search </button>
               </form>
           </div>
           <div class="box">
               <div class="box-1">
                   <form>
                       <center>
                           <h1> <span>Contact Us </span></h1>
                           <input type="text" placeholder="Your Name">
                           <br>
                           <input type="email" placeholder="Your Email">
                           <br>
                           <textarea rows="4" cols="30" placeholder="Your Message"> </textarea>
                           <br>
                           <button type="submit"> Submit </button>
                       </center>
                   </form>
               </div>
               <div class="box-2"> 
                   <h2> Contact Information</h2>
                   <p><span> Address</span>: 1/234 , MAIN ROAD,ARNI,632316</p>
                   <p> <span>Email</span> : santhosh@gmail.com</p>
                   <p> <span>Phone</span>: 055 541 7410 </p>
               </div>
           </div>
       </div>
       <footer>
           <center> Copyright@2024 Developed by SANTHOSH D</center>
       </footer>
   </body>
   </html>

```


## OUTPUT:

![alt text](<santhosh/ludusapp/static/Screenshot 2024-05-07 104850.png>)

![alt text](<santhosh/ludusapp/static/Screenshot 2024-05-07 104919.png>)

![alt text](<santhosh/ludusapp/static/Screenshot 2024-05-07 104936.png>)

![alt text](<santhosh/ludusapp/static/Screenshot 2024-05-07 104950.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
