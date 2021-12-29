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
### Home:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Sai Info Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Sai Info Private Limited</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contacts.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="http://im.rediff.com/money/2012/jan/11jo20.jpg  " alt="Building" />
          <div class="contenttext">
            At Tally, we believe in the power of technology to make business
            owners efficient, empowered and happier, so they can focus on what
            matters most for their business. We design our products to focus on
            just that to make our products work for you, and not the other way
            around.
            <br />
            Our new product TallyPrime takes this to a new level, making your
            start to automation, or your switch to Tally simpler than ever
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
        Copyright &#169; 2021 Sai Info Private Limited, Developed by P.Ramsai.
      </div>
    </div>
  </body>
</html>

~~~

### People:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Sai Info Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Sai Info Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitemselected">
          <a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contacts.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Crew</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://images.unsplash.com/photo-1560250097-0b93528c311a?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MXx8Y2VvfGVufDB8fDB8fA%3D%3D&w=1000&q=80" alt="product image">
                  </div>
                  <div class="itemname">Mr.Jack</div>
                  <div class="itemprice">CEO</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://cdn-prod.iasonline.org/wp-content/uploads/2017/10/Chuck.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Mr.Prathin</div>
                  <div class="itemprice">Branch Manager </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="https://cdn-prod.iasonline.org/wp-content/uploads/2017/10/Chuck.jpg"  alt="product image">
                </div>
                <div class="itemname">Mr.Raghuvaran</div>
                <div class="itemprice">capital managerr </div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="https://static01.nyt.com/images/2020/01/14/business/00renaultceo/00renaultceo-videoSixteenByNineJumbo1600.jpg"  alt="product image">
                </div>
                <div class="itemname">Mr.Ram</div>
                <div class="itemprice">Techinal Lead </div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="https://techcrunch.com/wp-content/uploads/2017/05/joe-eazor-portrait.jpg"  alt="product image">
                </div>
                <div class="itemname">Mr.Parthiv</div>
                <div class="itemprice">Senior Engineer </div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="https://akm-img-a-in.tosshub.com/businesstoday/images/story/202108/hclceo1200-sixteen_nine.jpg?size=1200:675"  alt="product image">
                </div>
                <div class="itemname">Mr.Raghu</div>
                <div class="itemprice">Senior Employee </div>
            </div>

          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 EduSoft Private Limited, Developed by Obed Otto.
      </div>
    </div>
  </body>
</html>

~~~

### Product:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Sai Info Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">EduSoft Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contacts.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://m.media-amazon.com/images/I/71yVflZyOYL._SL1500_.jpg" alt="product image">
                  </div>
                  <div class="itemname">Widnows 10</div>
                  <div class="itemprice">Price: Rs.10,000 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://m.media-amazon.com/images/I/71HYoQuZgiL._SL1500_.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Anti Virus</div>
                  <div class="itemprice">Price: Rs.999 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="https://m.media-amazon.com/images/I/61X7ZuPfp7L._SL1336_.jpg"  alt="product image">
                </div>
                <div class="itemname">Ubuntu installation drive</div>
                <div class="itemprice">Price: Rs.240 </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="https://m.media-amazon.com/images/I/61tUB2uBVtS._SL1132_.jpg"  alt="product image">
              </div>
              <div class="itemname">Vypar billing software</div>
              <div class="itemprice">Price: Rs.999</div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="https://m.media-amazon.com/images/I/71HpEfZSgkL._SL1500_.jpg"  alt="product image">
            </div>
            <div class="itemname">Ms office 365</div>
            <div class="itemprice">Price: Rs.3500 </div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="https://m.media-amazon.com/images/I/61W8fnM+u4L._SL1072_.jpg"  alt="product image">
          </div>
          <div class="itemname">MacFee Antivirus</div>
          <div class="itemprice">Price: Rs.1500 </div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="https://m.media-amazon.com/images/I/61bAOaSTIpL._SL1200_.jpg"  alt="product image">
        </div>
        <div class="itemname">Billing Software</div>
        <div class="itemprice">Price: Rs.4000 </div>
    </div>
    <div class="productitem"> 
      <div class="itemimage">
      <img src="https://m.media-amazon.com/images/I/71AMCTkRkeS._SL1500_.jpg"  alt="product image">
      </div>
      <div class="itemname">Photo Recovery Software</div>
      <div class="itemprice">Price: Rs.500 </div>
  </div>
  <div class="productitem"> 
    <div class="itemimage">
    <img src="https://m.media-amazon.com/images/I/71Vv4h65mpL._SL1080_.jpg"  alt="product image">
    </div>
    <div class="itemname">Max Secure software</div>
    <div class="itemprice">Price: Rs.5000 </div>
</div>    <div class="productitem"> 
  <div class="itemimage">
  <img src="https://m.media-amazon.com/images/I/71x7273wT5L._SL1500_.jpg"  alt="product image">
  </div>
  <div class="itemname">Disk Recovery Software</div>
  <div class="itemprice">Price: Rs.500 </div>
</div>    <div class="productitem"> 
  <div class="itemimage">
  <img src="https://m.media-amazon.com/images/I/31Zm+quTpiL.jpg"  alt="product image">
  </div>
  <div class="itemname">Bulk Messenger </div>
  <div class="itemprice">Price: Rs.575 </div>
</div>    <div class="productitem"> 
  <div class="itemimage">
  <img src="https://m.media-amazon.com/images/I/61LxBuzh54L._SL1046_.jpg"  alt="product image">
  </div>
  <div class="itemname">Norton Anti Virus Software</div>
  <div class="itemprice">Price: Rs.1500 </div>
</div>
    
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 Sai Info Private Limited, Developed by P.Ramsai.
      </div>
    </div>
  </body>
</html>


~~~

### Contact:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Sai Info Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Sai Info Private Limited</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/prople.html">People</a></div>
        <div class="menuitemselected">
          <a href="/static/contacts.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>Contact Us</h1>
        
          <div class="contenttext">
          Mail us at Saiinfoprivatelimited@gmail.com
          <br>
          contact us at 4477883399
          <br>
          Our main branch is locted at:- 5-88 parkavenue lane, mahabar street, opposite main tower, Red Building 5th floor.
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Sai Info Private Limited, Developed by P.Ramsai.
      </div>
    </div>
  </body>
</html>

~~~


## OUTPUT:
![Home Page](/images/pic1.png)
![Product Page](/images/pic2.png)
![People Page](/images/pic3.png)
![Contact Page](/images/pic4.png)
### Home Page:

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
