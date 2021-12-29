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


### HomePage:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>  AHTIHSKAR  SOFTWARE PRIVATE </title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"> AHTIHSKAR SOFTWARE PRIVATE </div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static\home.html">Home</a></div>
        <div class="menuitem"><a href="/static\products.html">Products</a></div>
        <div class="menuitem"><a href="/static\people.html">People</a></div>
        <div class="menuitem"><a href="/static\contact_us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/design.jpeg" alt="Building" />
          <div class="contenttext">
            At software product, we believe in the power of technology to make business
            owners efficient, empowered and happier, so they can focus on what
            matters most for their business. We design our products to focus on
            just that to make our products work for you, and not the other way
            around.
            <br />
            Our new product software takes this to a new level, making your
            start to automation, or your switch to software simpler than ever
            before. You can now discover the product much more easily and make
            the product do more for you, without learning anything new. There is
            greater flexibility as the product adapts to your business and your
            way of working. And the transformed look and feel will only make you
            love the product even more.
            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Insightful , actionable & customizable reports</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021  AHTIHSKAR  SOFTWARE PRIVATE  FOUNDER:J.RAKSHITHA DEVI
      </div>
    </div>
  </body>
</html>
```
## ProductPage:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>AHTIHSKAR Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">AHTIHSKAR SOFTWARE PRIVATE </div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact_us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:/Users/raksh/Documents/webtechnology/productcompanywebsite/companywebsite/static/img/ajax.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">AJAX</div>
                  <div class="itemprice">Price: Rs.7000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="C:/Users/raksh/Documents/webtechnology/productcompanywebsite/companywebsite/static/img/amazon.jpeg"  alt="product image">
                </div>
                <div class="itemname">AMAZON</div>
                <div class="itemprice">Price: Rs.2000.00 </div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="C:/Users/raksh/Documents/webtechnology/productcompanywebsite/companywebsite/static/img/android.jpeg"  alt="product image">
            </div>
            <div class="itemname">ANDROID</div>
            <div class="itemprice">Price: Rs.2000.00 </div>
          </div>  
          <div class="productitem"> 
            <div class="itemimage">
            <img src="C:/Users/raksh/Documents/webtechnology/productcompanywebsite/companywebsite/static/img/apple.jpeg"  alt="product image">
            </div>
            <div class="itemname">APPLE</div>
            <div class="itemprice">Price: Rs.10000.00 </div>      
      </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="C:/Users/raksh/Documents/webtechnology/productcompanywebsite/companywebsite/static/img/google%20cloud.jpeg"  alt="product image">
          </div>
          <div class="itemname">GOOGLE CLOUD</div>
          <div class="itemprice">Price: Rs.4000.00 </div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="C:/Users/raksh/Documents/webtechnology/productcompanywebsite/companywebsite/static/img/html.jpeg"  alt="product image">
            </div>
            <div class="itemname">HTML</div>
            <div class="itemprice">Price: Rs.5000.00 </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="C:/Users/raksh/Documents/webtechnology/productcompanywebsite/companywebsite/static/img/ionic.jpeg"  alt="product image">
              </div>
              <div class="itemname">IONIC</div>
              <div class="itemprice">Price: Rs.8000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="C:/Users/raksh/Documents/webtechnology/productcompanywebsite/companywebsite/static/img/mangento.jpeg"  alt="product image">
                </div>
                <div class="itemname">MANGENTO</div>
                <div class="itemprice">Price: Rs.6000.00 </div>
                </div>
                  <div class="productitem"> 
                    <div class="itemimage">
                    <img src="C:/Users/raksh/Documents/webtechnology/productcompanywebsite/companywebsite/static/img/microsoft.jpeg"  alt="product image">
                    </div>
                    <div class="itemname">MICROSOFT</div>
                    <div class="itemprice">Price: Rs.3000.00 </div>
                    </div>
                    <div class="productitem"> 
                      <div class="itemimage">
                      <img src="C:/Users/raksh/Documents/webtechnology/productcompanywebsite/companywebsite/static/img/wordpress.jpeg"  alt="product image">
                      </div>
                      <div class="itemname">WORDPRESS</div>
                      <div class="itemprice">Price: Rs.4000.00 </div>
                      </div>
      <div class="footer">
        Copyright &#169; 2021 AHTIHSKAR SOFTWARE PRIVATE FOUNDER:J RAKSHITHA DEVI
      </div>
    </div>
  </body>
</html>
```
## PeoplePage:
```
OCTYPE html>
<html lang="en">
  <head>
    <title></title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">AHTIHSKAR SOFTWARE PRIVATE</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitemselected"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact_us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
            <h1>SOFTWARE </h1>
            <div class="productitems">
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="C:/Users/raksh/Documents/webtechnology/productcompanywebsite/companywebsite/static/img/1%20andy%20rubin.jpeg" alt="product image">
                    </div>
                    <div class="itemname">ANDY RUBIN</div>
                    <div class="itemprice">CEO of Essential Products</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="C:/Users/raksh/Documents/webtechnology/productcompanywebsite/companywebsite/static/img/2%20steve%20job.jpeg"  alt="product image">
                    </div>
                    <div class="itemname">STEVE JOB</div>
                    <div class="itemprice">Business magnate</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="C:/Users/raksh/Documents/webtechnology/productcompanywebsite/companywebsite/static/img/3%20BILL%20GATES.jpeg"  alt="product image">
                    </div>
                    <div class="itemname">BILL GATES</div>
                    <div class="itemprice">American Business Magnate</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="C:/Users/raksh/Documents/webtechnology/productcompanywebsite/companywebsite/static/img/4%20ANDER%20HEJLSBERG.jpeg"  alt="product image">
                    </div>
                    <div class="itemname">ANDER HEJLSBERG</div>
                    <div class="itemprice">Software engineer</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="C:/Users/raksh/Documents/webtechnology/productcompanywebsite/companywebsite/static/img/5%20JEFF%20BENZOS.jpeg"  alt="product image">
                    </div>
                    <div class="itemname">JEFF BENZOS</div>
                    <div class="itemprice">American entrepreneur</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="C:/Users/raksh/Documents/webtechnology/productcompanywebsite/companywebsite/static/img/6%20TIM%20BERNERS-LEE.jpeg"  alt="product image">
                    </div>
                    <div class="itemname">TIM BERNERS</div>
                    <div class="itemprice">Computer scientist</div>
                </div>

          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 AHTIHSKAR SOFTWARE PRIVATE
      </div>
    </div>
  </body>
</html>
```
## ContactusPage:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>AHTIHSKAR SOFTWARE PRIVATE</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">AHTIHSKAR SOFTWARE PRIVATE</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contact_us.html">Contact Us</a></div>
      </div>
      <div class="content">
          <ul>
              <li>Address: CHENNAI <br></li>
              <li>Contact:9876543210;<br></li>
              <li>rakshithadevi0403@gmail.com.com<br></li>
              <br>VERIFIED*
          </ul>    
        </div>
    </div>
    </div>
    </div>
      <div class="footer">
        Copyright &#169; 2021 AHTIHSKAR SOFTWARE PRIVATE FOUNDER:J RAKSHITHA DEVI
      </div>
    </div>
  </body>
</html>
```
# OUTPUT:

## HomePage:
![output](C:\Users\raksh\Documents\webtechnology\productcompanywebsite\companywebsite\static\img\homeout.PNG)
## ProductsPage:
![output](./images/product.jpg)
## PeoplePage:
![output](./images/people.jpg)
## Contactus Page:
![output](./images/contact_us.jpg)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
