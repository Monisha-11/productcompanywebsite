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
```
CSS CODE :

* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: whitesmoke;
  color: black;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  box-shadow: 15px 15px 8px lightpink;
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align:right;
  font-size: 70px;
  background-image: url("/static/img/image1.png");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 160px;
  color:darkblue;
}
.being {
    background-image: url("/static/img/image1.png")
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background: #d551e6;
  text-align: center;
  padding-top: 15px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
}
.menuitem {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
}
.menuitemselected {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  color: #d551e6;
}

.menuitem a {
  text-decoration: none;
  color: #9c1018;
}

.content {
  display: block;
  width: 100%;
  background-color: #e199e6;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
  text-align: left;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
}

.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.productcontent h1 {
  text-align: left;
}

.productitems {
  display: block;
}

.productitem {
  display: inline-block;
  width: 30%;
  height: 250px;
  text-align: center;
}

.productitem img {
  width: 100px;
  height: 100px;
  display: block;
}
.productitem .itemimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}

.productitem .itemname {
  display: block;
}
.productitem .itemprice {
  display: block;
}

.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: #d551e6 ;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: black;
}

HOME PAGE HTML CODE :

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>FASION TECH </title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/logo.jpg" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">FASHION TECH</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a herf="/static/People.html">people</a></div>
        <div class="menuitem"><a herf="/ststic/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/image.png" alt="image" />
          <div class="contenttext">
            Influential, innovative and progressive,fasion tech is reinventing a wholly modern approach to fashion.
            Under the new vision of creative director Alessandro Michele, the House has redefined luxury for the 21st century,
            further reinforcing its position as one of the world’s most desirable fashion houses.
             Eclectic, contemporary, romantic— fashion tech products represent
            the pinnacle of Italian craftsmanship and are unsurpassed for their quality and attention to detail.
            <div>                                           </div>
            <div> fasion tech is part of the Kering Group.</div>
            
            A global Luxury group, Kering manage the development of a series of renowned Houses in Fashion,
           Leather Goods, Jewelry and Discover the stories behind Alessandro Michele's collections, exclusively on
            
            <ul>
              <li>Simple way to purchase</li>
              <li>comfortable, easy to choose our design</li>
              <li>all fashion model are there.</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 FASHION TECH, Developed by MONISHA T.
      </div>
    </div>
  </body>
</html>

PRODUCT PAGE HTML CODE :

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>FASHION TECH</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/logo.jpg" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">FASHION TECH</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a herf="/ststic/people.html">People</a></div>
        <div class="menuitem"><a herf="/static/contact us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/pro 1.jpg" alt="product image">
                  </div>
                  <div class="itemname">BAGS</div>
                  <div class="itemprice">Price: Rs.40,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/pro 2.jpg"  alt="product image">
                  </div>
                  <div class="itemname">inovative shoe</div>
                  <div class="itemprice">Price: Rs.60,000.00 </div>
              </div>
                 <div class="productitem"> 
                 <div class="itemimage">
                 <img src="/static/img/pro 3.jpg"  alt="product image">
                 </div>
                 <div class="itemname"> set of shoe and handie</div>
                 <div class="itemprice">Price: Rs.45,000.00 </div>
              </div>
                 <div class="productitem"> 
                 <div class="itemimage">
                 <img src="/static/img/pro 4.jpg"  alt="product image">
              </div>
                 <div class="itemname"> set of womens wear</div>
                 <div class="itemprice">Price: Rs.65,000.00 </div>
              </div>
                 <div class="productitem"> 
                 <div class="itemimage">
                 <img src="/static/img/pro 5.jpg"  alt="product image">
              </div>
                 <div class="itemname"> lipstick </div>
                 <div class="itemprice">Price: Rs.3,000.00 </div>
              </div>
                 <div class="productitem"> 
                 <div class="itemimage">
                 <img src="/static/img/pro 6.jpg"  alt="product image">
              </div>
                 <div class="itemname"> loation </div>
                 <div class="itemprice">Price: Rs.6,000.00 </div>
              </div>
                 <div class="productitem"> 
                 <div class="itemimage">
                 <img src="/static/img/pro 7.jpg"  alt="product image">
              </div>
                 <div class="itemname">pants & tunics </div>
                 <div class="itemprice">Price: Rs.25,000.00 </div>
              </div>
                 <div class="productitem"> 
                 <div class="itemimage">
                 <img src="/static/img/pro 8.jpg"  alt="product image">
              </div>
                 <div class="itemname">modern womens wear </div>
                 <div class="itemprice">Price: Rs.47,000.00 </div>
              </div>
                 <div class="productitem"> 
                 <div class="itemimage">
                 <img src="/static/img/pro 9.jpg"  alt="product image">
              </div>
                 <div class="itemname"> glass wear </div>
                 <div class="itemprice">Price: Rs.80,000.00 </div>
              </div>
                 <div class="productitem"> 
                 <div class="itemimage">
                 <img src="/static/img/pro 10.jpg"  alt="product image">
              </div>
                 <div class="itemname"> winter wear </div>
                 <div class="itemprice">Price: Rs.70,000.00 </div>
              </div>
                 <div class="productitem"> 
                 <div class="itemimage">
                 <img src="/static/img/pro 11.jpg"  alt="product image">
              </div>
                 <div class="itemname"> normal wear </div>
                 <div class="itemprice">Price: Rs.70,000.00 </div>
              </div>
                 <div class="productitem"> 
                 <div class="itemimage">
                 <img src="/static/img/pro 12.jpg"  alt="product image">
              </div>
                 <div class="itemname"> smart watch</div>
                 <div class="itemprice">Price: Rs.90,000.00 </div>
              </div>
             </div>
           </div>          
        </div>
      <div class="footer">
        Copyright &#169; 2021 FASHION TECH, Developed by MONISHA T.
      </div>
    </div>
  </body>
</html>

PEOPLE PAGE HTML CODE :

!DOCTYPE html>
<html lang="en">
    <head>
        <title>FASHION TECH</title>
        <link rel="stylesheet" href="./css/layout.css" />
        <link rel="icon" href="./img/logo.jpg" type="image/x-icon" />    
    </head>

    <body>
        <div class="container">
            <div class="banner">FASHION TECH</div>
            <div class="menu">
                <div class="menuitem"><a href="/static/home.html">Home</a></div>    
                <div class="menuitem"><a href="/static/products.html">Products</a></div>   
                <div class="menuitemselected"><a href="/static/people.html">People</a></div>  
                <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>           
            </div>
            <div class="content">
                <div class="peoplecontent">
                    <h1>Executive Team</h1>
                    <div class="peoplepics">
                        <div class="peoplepic">
                            <div class="peopleimage">
                                <img src="./img/mo 1.jpg" alt="mo 1">
                            </div>
                            <div class="peoplename">Ms.chirstine lacuzzo </div>
                            <div class="peopledes">CEO</div>
                        </div>
                        <div class="peoplepic">
                            <div class="peopleimage">
                                <img src="./img/mo 2.jpg" alt="MO 2">
                            </div>
                            <div class="peoplename">ms.Nicole Marra</div>
                            <div class="peopledes">President</div>
                        </div>
                        <div class="peoplepic">
                            <div class="peopleimage">
                                <img src="./img/mo 3.jpg" alt="mo 3">
                            </div>
                            <div class="peoplename"> mr.Marco Bizzarri</div>
                            <div class="peopledes">Vice President</div>
                        </div>
                        <div class="peoplepic">
                            <div class="peopleimage">
                                <img src="./img/mo 4.jpg" alt="mo 4">
                            </div>
                            <div class="peoplename">Ms.Tim Hershey</div>
                            <div class="peopledes">Head of strategy</div>
                        </div>
                        <div class="peoplepic">
                            <div class="peopleimage">
                                <img src="./img/mo 5.jpg" alt="mo 5">
                            </div>
                            <div class="peoplename">Ms.Geraldine french</div>
                            <div class="peopledes">director of product manager</div>
                        </div>
                        <div class="peoplepic">
                            <div class="peopleimage">
                                <img src="./img/mo 6.jpg" alt=" mo 6">
                            </div>
                            <div class="peoplename">mr. Ed Haskovic</div>
                            <div class="peopledes">Cheif Financial Officer</div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="footer">
                Copyright &#169;2021 FASHION TECH, Developed by MONISHA T
              </div>
            </div>
          </body>
        </html>

CONTACT US PAGE HTML CODE :

<!DOCTYPE html>
<html lang="en">
    <head>
        <title>FASHION TECH</title>
        <link rel="stylesheet" href="./css/layout.css" />
        <link rel="icon" href="./img/logo.jpg" type="image/x-icon" />    
    </head>

    <body>
        <div class="container">
            <div class="banner">FASHION TECH.</div>
            <div class="menu">
                <div class="menuitem"><a href="/static/home.html">Home</a></div>    
                <div class="menuitem"><a href="/static/products.html">Products</a></div>   
                <div class="menuitem"><a href="/static/people.html">People</a></div>  
                <div class="menuitemselected"><a href="/static/contact.html">Contact Us</a></div>           
            </div>
            <div class="content">
                <div class="contactcontent">
                    <div class="contactitems">
                        <div class="contactitem">
                            <h2>Hyderabad</h2>
                            <div class="address"> Tech design Development Center, Plot No. TP1/1<br>
                                Tower City, Hosur Road<br>
                                Hyderabad 500 032</div>
                            <div class="number">Mobile: +91 85 3456 5677</div>
                            <div class="email">E-mail: fashtech@.com</div>
                        </div>
                        <div class="contactitem">
                            <h2> New Delhi</h2>
                            <div class="address">Plot No, 26A, taj center, taj Park<br>
                                taj World City<br>
                                 new delhi 110001 </div>
                            <div class="number">Mobile: +91 47 8765 2309</div>
                            <div class="email">E-mail: fashtech@.com</div>
                        </div>
                        <div class="contactitem">
                            <h2>Mumbai</h2>
                            <div class="address">Survey No. 210,tai hotel city ,<br>
                                Lingampally, Rangareddy (Dist.),<br>
                                Mumbai 230 532</div>
                            <div class="number">Mobile: +91 40 6642 0000</div>
                            <div class="email">E-mail: fashtech@.com</div>
                        </div>
                        <div class="contactitem">
                            <h2>chennai</h2>
                            <div class="address">Plot No. 24/2,central avenue,techno park(SEZ)<br>
                                Mahindra world city, <br>
                                chennai 600 001</div>
                            <div class="number">Mobile: +91 20 3982 7000</div>
                            <div class="email">E-mail: fashtech@.com</div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="footer">
                Copyright &#169; 2021 FASHION TECH, Developed by MONISHA T.
            </div>
        </div>
    </body>
</html>
```

## OUTPUT:

### Home page:
![output](./output1.png)![output 1](https://user-images.githubusercontent.com/93427240/146681546-26c7ea75-8994-44ea-8aa5-a03b36f19b34.png)

![output](./output2.png)![output 2](https://user-images.githubusercontent.com/93427240/146681553-0f898060-0284-4dd5-94be-aca36da32c65.png)

![output](./output3.png)![output 3](https://user-images.githubusercontent.com/93427240/146681558-331c067d-a818-47ba-9345-26923c65e0ca.png)

![output](./output4.png)![output 4](https://user-images.githubusercontent.com/93427240/146681564-f38101c1-b21a-46fb-869b-6caf6bf4565d.png)


## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
