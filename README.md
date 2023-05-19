# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

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

### Step 6:

Publish the website in the given URL.

## PROGRAM :

### home.html

```html

<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            Home Page
        </title>
        <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/css/styles.css">
    <style>
    .text{
        color:blueviolet;
        font-family:'Lucida Sans';
        font-size: 30px;
        text-align:center;
    }
    img{
        height: 150px;
        width: 150px;
        align-items:center;
    }
    </style>

    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color:white; text-decoration: none;"><b>Home</b></a></div>
                    <div class="prod">
                        <a href="products.html" title="Products" style="color: white; text-decoration: none;"><b>Products</b></a>
                  </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:white; text-decoration: none;"><b>People</b></a>
                    </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:white; text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>STARK ENTERPRISE</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <marquee><b>Feel alive with our store</b></marquee>
                    <p style="color:purple; font-family:'Tahoma'; font-size:20px;"> This is the Official Website of our Electronic Gadgets</p>
                    </div>
                    <p>Buy Modern Gadgets and Accessories online for changing world in <span style="background-color:orange"> Android World</span>
                         EMI starts from Rs100 per month | Buy Gadgets in Android World online | 7 Days Returns | Trend setting Electronics | And much more</p>
                    <br>
                <center></centre>
                    <img src="/static/images/product1.jpg">
                    <img src="/static/images/product2.webp">
                    <img src="/static/images/product3.png">
                    <img src="/static/images/product4.jpeg">
                    <img src="/static/images/product5.png">
                    <img src="/static/images/product6.jpeg">
                    <img src="/static/images/product7.jpg">
                </center>
                </div>
                <div class="footer">
                <footer style="color:black">
               Copyright &copy;2023 Developed by KANISHKAR M</footer></div>
            </div>
        </div>
    </body>
</html>

```

### products.html

```html

<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            Products
        </title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/css/styles.css">
        <style>
        .home{
            height: 1555px;
            width: 85%;
            border: 12px solid green;
            padding-left:10px;
            padding-right:10px;
            margin-left: auto;
            margin-right:auto;
            background-color:lightgray;
        }
        .text{
            color:blueviolet;
            font-family:'Lucida Sans';
            font-size: 30px;
            text-align:center;
        
        }
        .content{
            border:3px solid orange;
            background-color: beige;
            width:98%;
            height:1190px;
            padding:10px;
            margin-left:auto;
            margin-right:auto;
        }
        .ph1{
            background-image: url(/static/images/product1.jpg);
            background-size: 210px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid white;
            height:200px;
            width:30%;
            position:relative;
            left: 80px;
        }
        .l1{
            color: gold;
            position:relative;
            right:380px;
            
            
        }
        .ph2{
            background-image: url(/static/images/product2.webp);
            background-size: 163px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid white;
            height:200px;
            width:30%;
            position:relative;
            left: 80px;
            
        }
        .l2{
            color: sandybrown;
            position:relative;
            right:380px;
        }
      .ph3{
            background-image: url(/static/images/product3.png);
            background-size: 185px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid white;
            height:210px;
            width:30%;
            position:relative;
            left: 80px;
            
        }
        .l3{
            color: burlywood;
            position:relative;
            right:380px;
        }
        .ph4{
            background-image: url(/static/images/product4.jpeg);
            background-position-x: center;
            border:1px solid white;
            height:200px;
            width:30%;
            position:relative;
            left: 730px;
            bottom:930px;
            background-size: 190px;
            background-repeat: no-repeat;
            
            
        }
        .l4{
            color: burlywood;
            position:relative;
            left:270px;
         bottom: 930px;
        }
    
        .ph5{
            background-image: url(/static/images/product5.png);
            background-position-x: center;
            border:1px solid white;
            height:200px;
            width:30%;
            position:relative;
            left: 730px;
            bottom:930px;
            background-size: 250px;
            background-repeat: no-repeat;
            
            
        }
        .l5{
            color: cadetblue;
            position:relative;
            left:270px;
            bottom: 930px;
        }

        .ph6{
            background-image: url(/static/images/product6.jpeg);
            background-position-x: center;
            border:1px solid white;
            height:200px;
            width:30%;
            position:relative;
            left: 730px;
            bottom:930px;
            background-size: 200px;
          background-repeat: no-repeat;
            
            
        }
        .l6{
            color: crimson  ;
            position:relative;
            left:270px;
            bottom: 930px;
        }
        .bot{
            text-align:center;
            font-size:larger;
            color:black;

        }
        </style>
    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color: white; text-decoration: none;"><b>Home</a></div>
                    <div class="prod">
                        <a href="products.html" title="Products" style="color: white; text-decoration: none;"><b>Products</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:white; text-decoration: none;"><b>People</b></a>
                    </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:white; text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>Products</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <p>These are the products that are available now</p>
                    </div>
                    <div class="ph1"></div>
                    <div class="l1"><p align="center"><b>Vass Bluetooth Speaker<br> Price: 1999.00</b><br><br><br><br></p></div>
                    <div class="ph2"></div>
                    <div class="l2"><p align="center"><b>Mvidia Projecter<br> Price: 46899.00</b><br><br><br><br></p></div>
                    <div class="ph3"></div>
                    <div class="l3"><p align="center"><b>Smoketel Smart Box<br> Price: 4999.00</b><br<br><br><br></p></div>
                    <div class="ph4"></div>
                    <div class="l4"><p align="center"><b>Ship TWS Earbuds<br> Price: 6999.00</b><br><br><br><br></p></div>
                    <div class="ph5"></div>
                    <div class="l5"><p align="center"><b>Songsung Drone<br> Price: 93999.00</b><br><br><br><br></p></div>
                    <div class="ph6"></div>
                    <div class="l6"><p align="center"><b>Pikon 360 Camera<br> Price: 35999.00</b><br><br><br><br></p></div>
         
                </div>
                <div class="bot"><p>To Order Online: Call 908070 6050</p></div>

                <div class="footer">
                <footer style="color:black">
                Copyright &copy;2023 Developed by KANISHKAR M</footer></div>
                     </div>
        </div>
    </body>
</html>

  ```
  
### people.html

```html

<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            People
        </title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/css/styles.css">
        <style>
        .home{
            height: 3000px;
            width: 85%;
            border: 12px solid green;
            padding-left:10px;
            padding-right:10px;
            margin-left: auto;
            margin-right:auto;
            background-color:lightgray;
        }
        .text{
        color:blueviolet;
        font-family:'Lucida Sans';
        font-size: 30px;
        text-align:center;
        
        }
        .content{
            border:2px solid green;
            background-color:beige;
            width:98%;
            height:2690px;
            padding:10px;
            margin-left:auto;
         margin-right:auto;
        }
        .ceoph{
            background-image: url(/static/images/member1.avif);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:3px solid gold;
            height:300px;
            width:20%;
            position:relative;
            left: 0px;
            margin-left:auto;
            margin-right: auto;
        }
        .ceo{
            color: red;
            position:relative;
            text-align:center;
            
            
        }
        .manph1{
            background-image: url(/static/images/member2.jpg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:300px;
            width:20%;
            position:relative;
            margin-left:auto;
            margin-right:auto;            
        }
        .man1{
            color: red;
            position:relative;
           text-align:center;
            
        }
        .manph2{
            background-image: url(/static/images/member3.jpg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:300px;
            width:20%;
            position:relative;
            margin-left:auto;
            margin-right:auto;

            
        }
        .man2{
            color: red;
            position:relative;
            text-align:center;
        }
        
        .amph1{
            background-image: url(/static/images/member4.jpeg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:300px;
            width:20%;
            position:relative;
            margin-left:auto;
            margin-right:auto;

            
        }
        .am1{
            color: red;
            position:relative;
           text-align:center;
        }

        .amph2{
            background-image: url(/static/images/member5.webp);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:270px;
            width:20%;
            position:relative;
            margin-left:auto;
            margin-right:auto;

            
        }
        .am2{
            color: red;
            position:relative;
            text-align:center;
        }
        .amph3{
            background-image: url(/static/images/member6.jpeg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:250px;
            width:20%;
            position:relative;
            margin-left:auto;
            margin-right:auto;

            
        }
        .am3{
          color: red;
            position:relative;
            text-align:center;
        }
        </style>
    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color:white; text-decoration: none;"><b>Home</b></a></div>
                    <div class="prod">
                        <a href="products.html" title="Products" style="color: white; text-decoration: none;"><b>Products</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:white; text-decoration: none;"><b>People</b></a>
                    </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:white; text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>People</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <p>Board Members</p>
                  <h4><u>Chairman</u></h4>
                    </div>
                    <div class="ceoph"></div>
                    <div class="ceo"><p align="center"><b><h2>Andrew Tate</h2></b></div>
                    <br>
                    <div class="text">
                        <p><b><u>Head executives</u></b></p><br>
                    </div>
                    <div class="manph1"></div>
                    <div class="man1"><p align="center"><b><h2>Naomi Scott</h2></b></p></div>
                    <div class="manph2"></div>
                    <div class="man2"><p><b><h2>Jason Mamoa</h2></b></p></div>
                    <br>
                    <div class="text"><p><b><u>Managers</u></b></p></div><br>
                    <div class="amph1"></div>
                    <div class="am1"><p align="center"><b><h2>Ajith Kumar</h2></b></p></div>
                    <div class="amph2"></div>
                    <div class="am2"><p align="center"><b><h2>Paul Walker</h2></b></p></div>
                    <div class="amph3"></div>
                    <div class="am3"><p align="center"><b><h2>Dhoni</h2></b></p></div><br>
                    <div class="text">Thank you so much for your kind support!<br>Hope our products had made you day a Blaze....!</div>
                </div>
                <div class="footer">
                <footer style="color:black">
                Copyright &copy;2023 Developed by KANISHKAR M</footer></div>
            </div>
        </div>
    </body>
</html>

```

### contact.html

```html

<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            Contact Us
        </title>
        <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/css/styles.css">
    <style>
    .text{
        color:blueviolet;
        font-family:'Lucida Sans';
        font-size: 30px;
        text-align:center;
    }
    
    </style>

    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color: white; text-decoration: none;"><b>Home</b></a></div>
                    <div class="prod">
                        <a href="products.html" title="Products" style="color: white; text-decoration: none;"><b>Products</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:white; text-decoration: none;"><b>People</b></a>
                    </div>
                              <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:white; text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>Contact Us</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <p><b>Here are the details about us
                    <h5>Do contact us for any Clarification</h5></b></p>
                    
                    </div>
                    <b><h2>Contact Information:</h2></b>
                    <p><b>&emsp;&ensp;Address:</b>
                        Nigra Street,Mariana Town,Bermuda
                    </p>
                    <ul>
                        <li><b>Landline:</b> 044 1234 5678</li>
                        <li><b>Mobile</b>: 9042424694</li>
                        <li><b>Facebook</b>: stark_enterprise</li>
                        <li><b>Email Id:</b>starkenterprise@technetwork.com</li>
                    </ul>
                    <div style="text-align: center;color:violet;font-size:20px;"><b>Use our services and change your lifestyle!</b></div>

                </div>
                <div class="footer">
                <footer style="color:black">
                Copyright &copy;2023 Developed by KANISHKAR M</footer></div>
            </div>
        </div>
    </body>
</html>

```

## OUTPUT:

### SERVER OUTPUT

![image](https://github.com/KANISHKAR2607/productcompanywebsite/assets/118886772/babe4e31-6779-4b76-9a19-2c99d23b2e66)

### HOME PAGE

![image](https://github.com/KANISHKAR2607/productcompanywebsite/assets/118886772/8b569e27-4caf-4e80-ab3e-1ce8424bd694)

### PRODUCTS PAGE

![image](https://github.com/KANISHKAR2607/productcompanywebsite/assets/118886772/40655cb3-b459-4b74-a4b7-7201091abac3)

### PEOPLE PAGE

![image](https://github.com/KANISHKAR2607/productcompanywebsite/assets/118886772/0ac31f9e-50eb-4312-bc68-31c2adc24583)

### CONTACT PAGE

![image](https://github.com/KANISHKAR2607/productcompanywebsite/assets/118886772/9fba4800-f0aa-4e45-9486-72df782de3e2)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
