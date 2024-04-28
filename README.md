# Ex.07 Software Product Company Website
## Date:

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
### Register Num : 212223230122
### Name : MANOJ M
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h1{
        color: black;
        font-size: 45px;
        font-family:Georgia, 'Times New Roman', Times, serif;
        position: absolute;
        top:35%;
        }
        body{
                background-image:url("spdback.jpg");  
                background-size: cover;
             }  
        .navbar ul{
        list-style-type:none;
        background-color:black;
        
        }
        .navbar a{
         color:white;
        text-decoration:none;
        padding:25px;
        display:flex;
        text-align:left;
        position: relative;
        font-size:20px;
        top:-95px;
        
        }
        nav ul li ::before,
             nav ul li ::after

            {
                position: absolute;
                content: '';
                width: 0%;
                height: 2px;
                background-color: #fff;
                transition: 0.3s all ease-in-out;

            }
            ul li ::before{
                top:0;
                left:0;
            }
            ul li ::after{
                bottom:0;
                right: 0;
            }
            nav ul li a:hover ::before {
                right: 0;
                width: 100%;
                left: auto;
                background-color:  #5607f4a7;

            }
            nav ul li a:hover ::after {
            right:auto;
            left: 0;
            width: 100%;
            background-color: #5607f4a7;
            }
            nav ul li a:hover {
              background-color:   #5607f4a7;   
            }


        .navbar li{
        float:right;
        }
        h2{
        color:white;
        font-family:monospace;
        font-size:60px;
        background-color:black;
        }
        footer{

        background-color:black;
        height:30px;
        bottom:0;
        width:100%;
        color:white;
        position:absolute;
        
        }
        header
        {
        background-color:black;
        height:10vh;
        width:100%;
        color:white;
        }
        header h2{
        position:absolute;
        color:white;
        margin-top:10px;
        margin-left:10px;
        }
        .search input{
            width:18%;
            height: 30px;

        }
        .search button{
            color:white;
            background-color: rgb(22, 165, 222);
            padding: 5px;
            text-align: center;
        }
        .search input,button{
            position: absolute;
            right: 12px;
            font-size: 18px;
            border-color:silver;
        }
        .line{
            position: absolute;
            top:43%;
        color:bisque;
            width:100%;
            size:5px;
        }
        .coform {
            background-color: wheat;
            top:43%;
        }
        .coform form{
            position: absolute;
            top:45%;
        }
        .coform form h3{
            font-size:30px;
        }
        .coform form input{
            margin-left: 10px;
            width:500px;
            height:25px;
        }
        .coform form textarea{
            margin-left: 10px;
        }
        .coform form button{
            position: absolute;
            background-color:  rgb(22, 165, 222);
            color:darkgoldenrod;
            border-radius: 20%;
            margin-left: 10px;
        }
        
        #submit{
            left: 50px;
            width: fit-content;
        }
        .vl{
            position:absolute;
            border-left: 3px solid peru;
            height: 450px;
            margin-left: 800px;
            top:44%;
        }
        #ci{
            font-size: 30px;
            margin-left: 40px;
        }
        .info{
            position:absolute;
            top:44.2%;
            font-size: 25px;
            background-color: black;
            padding:70px 250px 95px 147px ;
            margin-left: 840px;
            color: white;
            border: 4px;
            border-color: beige;
            border-style: solid;
        }
        .coform form{
            background-color:aqua;
            color: aliceblue;
            top:44.3%;
            margin-left: 20px;
            padding:0px 282px 50px 0px;
            border: 4px;
            border-color: aliceblue;
            border-style: solid;
        }
        .u{
            text-align: center;
            font-size: larger;
        }
        
        span
        {
            color: aqua;
        }
    </style>
    </head>
    <body background="spdback - Copy.jpg">
        <header>
            <h2>Syd <span>Web </span><span>Products</span></h2>
            </header>
            <nav class="navbar">
            
            <ul>
            <li><a href="contact.html">Contact</a></li>
            <li><a href="product.html">Products</a></li>
            <li><a href="people.html">People</a></li>
            <li><a href="home1.html">Home</a></li>
            </ul>
            </nav>
            <div class="search"><input type="text" placeholder="Enter to Search">
                <button>Search</button></div>
                <div class="line">
                    <hr color="darkblue">
            </div>
            <div class="coform">
            <form>
              <h3>&nbsp;Contact Us</h3>
              <input type="text" placeholder="Your Name"><br><br>
              <input type="text" placeholder="Your Email"><br><br>
              <textarea rows="10" cols="50" >Your Message
              </textarea><br>
              <button id="submit">Submit</button>
            </form>
        </div>
        <div class="info">
            <h3 id="ci" >Contact Information</h3><br>
            <b>Address: </b>305 shankar street<ch-75></ch-75><br><br>
            <b>Email: </b>spydproducts@gmail.com<br><br>
            <b>Phone: </b>044-168796378
        </div>
        <div class="vl"></div>
    </div>
                   
    </body>
    </html>
```


## OUTPUT:
![image](https://github.com/Manoj0079940/softweb/assets/149366208/ed2a0eef-e2cb-4772-88f9-c101e728b593)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
