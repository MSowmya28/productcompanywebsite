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
## HOME PAGE:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>MICROSOFT Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/p13.jpg" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/P14.png" alt="Building" />
          <div class="contenttext">
            Microsoft Corporation is an American multinational technology corporation which produces computer software,
            consumer electronics, personal computers, and related services. Its best-known software products are the 
            Microsoft Windows line of operating systems, the Microsoft Office suite, and the Internet Explorer and
            Edge web browsers.Its flagship hardware products are the Xbox video game consoles and the Microsoft
            Surface lineup of touchscreen personal computers. 
            <ul>
              <li>Programers are respected and creativity is encouraged.</li>
              <li>Microsoft employes absolutely love their company.</li>
              <li>One of the largest R&D budgets in the industry.</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 1986 microsoft private limited.
      </div>
    </div>
  </body>
</html>
~~~
## PRODUCT PAGE:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>MICROSOFT Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/p3.png" alt="product image">
                  </div>
                  <div class="itemname">BING</div>
                  <div class="itemprice">Price: Rs.1,000 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/p4.jfif"  alt="product image">
                  </div>
                  <div class="itemname">MSN</div>
                  <div class="itemprice">Price: Rs.2,000</div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/p5.jfif"  alt="product image">
                </div>
                <div class="itemname">Access</div>
                <div class="itemprice">Price: Rs.4,000</div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/p6.jfif"  alt="product image">
              </div>
              <div class="itemname">Xbox</div>
              <div class="itemprice">Price: Rs.5,000</div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/p7.jfif"  alt="product image">
            </div>
            <div class="itemname">Excel</div>
            <div class="itemprice">Price: Rs.7,000</div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/p8.jfif"  alt="product image">
          </div>
          <div class="itemname">Exchange</div>
          <div class="itemprice">Price: Rs.8,000</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/p9.jfif"  alt="product image">
        </div>
        <div class="itemname">Lync</div>
        <div class="itemprice">Price: Rs.9,500</div>
    </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/p10.jfif"  alt="product image">
            </div>
            <div class="itemname">PowerPoint</div>
            <div class="itemprice">Price: Rs.10,000</div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/p11.jfif"  alt="product image">
          </div>
          <div class="itemname">Publisher</div>
          <div class="itemprice">Price: Rs.11,000</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/p12.jfif"  alt="product image">
        </div>
        <div class="itemname">OneNote</div>
        <div class="itemprice">Price: Rs.13,000</div>
    </div>
    <div class="productitem"> 
      <div class="itemimage">
      <img src="/static/img/p2.png"  alt="product image">
      </div>
      <div class="itemname">Skype</div>
      <div class="itemprice">Price: Rs.15,000</div>
  </div>
  <div class="productitem"> 
    <div class="itemimage">
    <img src="/static/img/p15.png"  alt="product image">
    </div>
    <div class="itemname">Office</div>
    <div class="itemprice">Price: Rs.19,000</div>
</div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 1986 microsoft private limited.
      </div>
    </div>
  </body>
</html>
~~~
## PEOPLE PAGE:
~~~

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>MICROSOFT Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitemselected"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
            <h1></h1>
            <div class="productitems">
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="/static/img/Bill.jfif" alt="product image">
                    </div>
                    <div class="itemname">BILL GATES</div>
                    <div class="itemprice">FOUNDER </div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="/static/img/jeff.jfif"  alt="product image">
                    </div>
                    <div class="itemname">JEFF</div>
                    <div class="itemprice">CFO</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="/static/img/SATYA.jfif"  alt="product image">
                    </div>
                    <div class="itemname">SATYA NADELLA</div>
                    <div class="itemprice">CEO</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="/static/img/amy.jfif"  alt="product image">
                    </div>
                    <div class="itemname">AMY</div>
                    <div class="itemprice">MANAGER</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="/static/img/BRAD.jfif"  alt="product image">
                    </div>
                    <div class="itemname">BRAD</div>
                    <div class="itemprice">HR</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="/static/img/rajiv.jfif"  alt="product image">
                    </div>
                    <div class="itemname">RAJIV</div>
                    <div class="itemprice">ASSISTENT MANAGER</div>
                </div>

          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 1986 microsoft private limited.
      </div>
    </div>
  </body>
</html>

~~~


## CONTACT US PAGE:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>MICROSOFT Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
          <ul>
              <li>Address:unitedstates <br></li>
              <li>Contact:1800 102 1100;<br></li>
              <li>E-mail:microsoft@hotmail.com<br></li>
              <br>VERIFIED*
          </ul>    
        </div>
    </div>
    </div>
    </div>
      <div class="footer">
        Copyright &#169; 1986 microsoft private limited
      </div>
    </div>
  </body>
</html>
~~~
## OUTPUT:

### Home Page:

![output](./images/home.PNG)

### Products Page:

![output](./images/products.PNG)

### People Page:

![output](./images/people.PNG)

### Contact Us Page:

![output](./images/contactus.PNG)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
