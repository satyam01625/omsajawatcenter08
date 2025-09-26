<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Wedding & Event Decor</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/7.0.0/css/all.min.css" />
<link rel="stylesheet" href="main.css">
</head>
<style>
  body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background-color: #f0f2f5;
      color: #333;
    }
    header {
      background: #e91e63;
      color: white;
      padding: 15px;
      display: flex;
      align-items: center;
      justify-content: space-between;

    }
    header h1 {
      font-size: 25px;
      margin: 0;
    }
    
   i{
      color: rgb(47, 240, 47);
      font-size: 50px;
      cursor: pointer;
    }
    #heading {
  text-align: center;
  padding: 30px 15px;
  background-color: #fff0f5;
  display: block;
  font-size: 20px;
  color: #444;
  margin-top: 10px;
}

#heading h1 {
  font-size: 36px;
  color: #b30059;
  margin-bottom: 10px;
}

#heading h1 span {
  display: block;
  font-size: 20px;
  color: #444;
  margin-top: 10px;
}

#heading p {
  font-size: 16px;
  color: #666;
  margin-top: 15px;
}
 #cars{
   background: #87cdf0;
   padding: 10px 10px;
   display: flex;
   align-items: center;
   color: black;
   justify-content: center; 
   font-size: 25px;
  

    }
 .product-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 20px;
  padding: 10px;
}
.product {
  background: white;
  width: 100%;
  max-width: 400px;
  margin: 0 auto;
  border-radius: 15px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.1);
  overflow: hidden;
  transition: transform 0.3s ease;
}

    .product-content button {
      width: 100%;
      padding: 10px;
      background: #e91e63;
      color: white;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      font-weight: bold;
    }


    .product:hover {
      transform: translateY(-5px);
    }
    .product img {
      width: 100%;
      height: 280px;
      object-fit: cover;
    }
    .product-content {
      padding: 15px;
    }
    .product-content h4 {
      margin: 10px 0 3px;
      font-size: 16px;
    }
    .product-content p {
      margin: 0 0 10px;
      color: #777;
      font-size: 14px;
    }

    .product-info {
      margin-top: 1rem;
    }

   
    .card .content {
  max-height: 0;
  overflow: hidden;
  transition: max-height 0.4s ease;
  font-size: 14px;
  margin-bottom: 10px;
}

.toggle:checked ~ .content {
  max-height: 200px;
}

/* Toggle Button */
.btn {
  display: inline-block;
  cursor: pointer;
  color: #c62828;
  font-weight: bold;
  font-size: 14px;
  text-decoration: underline;
  margin-bottom: 10px;
}

.btn .less {
  display: none;
}

.toggle:checked + .content + .btn .more {
  display: none;
}

.toggle:checked + .content + .btn .less {
  display: inline;
}

/* Book Now Button */
.book-btn {
  background-color: #c8516f;
  color: white;
  border: none;
  padding: 10px 20px;
  cursor: pointer;
  border-radius: 4px;
  transition: background 0.3s ease;
}

.book-btn:hover {
  background-color: #ff1151;
}

/* Responsive */
@media (max-width: 768px) {
  .product-grid {
    grid-template-columns: 1fr;
    justify-items: center;
  }
}


   footer {
      background: #222;
      color: #ddd;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
      font-size: 14px;
    }
</style>
<body>

<header>
  <h1>OM SAJAWAT CENTER</h1>
  <a href="https://wa.me/7765092483" target="_blank">
    <i class="fab fa-whatsapp"></i>
  </a>
</header>

<div id="heading">
  <h1>Welcome to OM SAJAWAT CENTRE<br><span>Sajawat that touches hearts!</span></h1>
  <p>Home / Engagement / Wedding Stage Decoration</p>
</div>

<h2 id="cars">Wedding Car Decoration Collection</h2>

<div class="product-grid">

  <!-- Product 1 -->
  <div class="product">
    <img src="https://stylesatlife.com/wp-content/uploads/2023/03/Extravagant-Floral-Wedding-Car-Decorations.jpg" alt="Decor 1">
    <div class="product-content">
      <h4>Classic Artifical & rajani Theme</h4>
      <p>₹14,000 <del>₹16,000</del> (12% off)</p>
      <div class="product-info">
        <div class="card">
          <input type="checkbox" id="exp1" class="toggle" hidden/>
          <div class="content">
            <p>Premium wedding car decor with floral arrangements and ribbons.
              Includes back, hood, side mirrors, and roof decoration with fresh flowers.
              Custom color themes and add-ons available on request.</p>
          </div>
          <label for="exp1" class="btn">
            <span class="more">See more</span>
            <span class="less">See less</span>
          </label>
          <a href="info.html">
            <button class="book-btn">Book Now</button>
          </a>
        </div>
      </div>
    </div>
  </div>

  <!-- Product 2 -->
  <div class="product">
    <img src="https://content.jdmagicbox.com/comp/saharanpur/q5/9999px132.x132.190912201912.k1q5/catalogue/mehfooz-thekedar-phool-decoration-saharanpur-city-saharanpur-flower-decorators-my0dgsj13s.jpg" alt="Decor 2">
    <div class="product-content">
      <h4>Classic Red Rose Theme</h4>
      <p>₹15,500 <del>₹18,500</del> (16% off)</p>
      <div class="product-info">
        <div class="card">
          <input type="checkbox" id="exp2" class="toggle" hidden/>
          <div class="content">
             <p>Premium wedding car decor with floral arrangements and ribbons.
              Includes back, hood, side mirrors, and roof decoration with fresh flowers.
              Custom color themes and add-ons available on request.</p>
          </div>
          <label for="exp2" class="btn">
            <span class="more">See more</span>
            <span class="less">See less</span>
          </label>
          <a href="info.html">
            <button class="book-btn">Book Now</button>
          </a>
        </div>
      </div>
    </div>
  </div>

  <!-- Product 3 -->
  <div class="product">
    <img src="https://i.pinimg.com/736x/71/13/05/7113056a79e556642f4df9e62385da1d.jpg" alt="Decor 3">
    <div class="product-content">
      <h4>Classic Artifical Theme</h4>
      <p>₹13,000 <del>₹15,000</del> (13% off)</p>
      <div class="product-info">
        <div class="card">
          <input type="checkbox" id="exp3" class="toggle" hidden/>
          <div class="content">
            <p>Premium wedding car decor with floral arrangements and ribbons.
              Includes back, hood, side mirrors, and roof decoration with fresh flowers.
              Custom color themes and add-ons available on request.</p>
          </div>
          <label for="exp3" class="btn">
            <span class="more">See more</span>
            <span class="less">See less</span>
          </label>
          <a href="info.html">
            <button class="book-btn">Book Now</button>
          </a>
        </div>
      </div>
    </div>
  </div>

  <!-- Product 4 -->
  <div class="product">
    <img src="https://thejarvi.com/wp-content/uploads/2023/02/shadi-gadi-2w-copy.jpg" alt="Decor 3">
    <div class="product-content">
      <h4>Rose & Rajni Theme</h4>
      <p>₹13,000 <del>₹15,000</del> (13% off)</p>
      <div class="product-info">
        <div class="card">
          <input type="checkbox" id="exp4" class="toggle" hidden/>
          <div class="content">
             <p>Premium wedding car decor with floral arrangements and ribbons.
              Includes back, hood, side mirrors, and roof decoration with fresh flowers.
              Custom color themes and add-ons available on request.</p>
          </div>
          <label for="exp4" class="btn">
            <span class="more">See more</span>
            <span class="less">See less</span>
          </label>
          <a href="info.html">
            <button class="book-btn">Book Now</button>
          </a>
        </div>
      </div>
    </div>
  </div>

  <!-- Product 5 -->
  <div class="product">
    <img src="https://i.ytimg.com/vi/5DDU-p4f4qo/maxresdefault.jpg" alt="Decor 3">
    <div class="product-content">
      <h4>Rose & Rajni+Riban Theme</h4>
      <p>₹13,000 <del>₹15,000</del> (13% off)</p>
      <div class="product-info">
        <div class="card">
          <input type="checkbox" id="exp5" class="toggle" hidden/>
          <div class="content">
            <p>Premium wedding car decor with floral arrangements and ribbons.
              Includes back, hood, side mirrors, and roof decoration with fresh flowers.
              Custom color themes and add-ons available on request.</p>
          </div>
          <label for="exp5" class="btn">
            <span class="more">See more</span>
            <span class="less">See less</span>
          </label>
          <a href="info.html">
            <button class="book-btn">Book Now</button>
          </a>
        </div>
      </div>
    </div>
  </div>

  <!-- Product 6 -->
  <div class="product">
    <img src="https://i.pinimg.com/736x/38/a0/57/38a057c8991e7a36ada803e7173834ca.jpg" alt="Decor 3">
    <div class="product-content">
      <h4>Aritfical Bonat To Back</h4>
      <p>₹13,000 <del>₹15,000</del> (13% off)</p>
      <div class="product-info">
        <div class="card">
          <input type="checkbox" id="exp6" class="toggle" hidden/>
          <div class="content">
            <p>Premium wedding car decor with floral arrangements and ribbons.
              Includes back, hood, side mirrors, and roof decoration with fresh flowers.
              Custom color themes and add-ons available on request.</p>
          </div>
          <label for="exp6" class="btn">
            <span class="more">See more</span>
            <span class="less">See less</span>
          </label>
          <a href="info.html">
            <button class="book-btn">Book Now</button>
          </a>
        </div>
      </div>
    </div>
  </div>

  <!-- Product 7 -->
  <div class="product">
    <img src="https://5.imimg.com/data5/RC/KU/DS/SELLER-69859009/flower-decoration-car-1000x1000.jpg" alt="Decor 3">
    <div class="product-content">
      <h4>Artifical Guldasta Theme</h4>
      <p>₹13,000 <del>₹15,000</del> (13% off)</p>
      <div class="product-info">
        <div class="card">
          <input type="checkbox" id="exp7" class="toggle" hidden/>
          <div class="content">
             <p>Premium wedding car decor with floral arrangements and ribbons.
              Includes back, hood, side mirrors, and roof decoration with fresh flowers.
              Custom color themes and add-ons available on request.</p>
          </div>
          <label for="exp7" class="btn">
            <span class="more">See more</span>
            <span class="less">See less</span>
          </label>
          <a href="info.html">
            <button class="book-btn">Book Now</button>
          </a>
        </div>
      </div>
    </div>
  </div>

  <!-- Product 8 -->
  <div class="product">
    <img src="https://i.pinimg.com/736x/e0/1a/1a/e01a1a421916217425461787540bae52.jpg" alt="Decor 3">
    <div class="product-content">
      <h4>Rose Heart & Riban Theme</h4>
      <p>₹13,000 <del>₹15,000</del> (13% off)</p>
      <div class="product-info">
        <div class="card">
          <input type="checkbox" id="exp8" class="toggle" hidden/>
          <div class="content">
            <p>Premium wedding car decor with floral arrangements and ribbons.
              Includes back, hood, side mirrors, and roof decoration with fresh flowers.
              Custom color themes and add-ons available on request.</p>
          </div>
          <label for="exp8" class="btn">
            <span class="more">See more</span>
            <span class="less">See less</span>
          </label>
         <a href="info.html">
            <button class="book-btn">Book Now</button>
          </a>
        </div>
      </div>
    </div>
  </div>

  <!-- Product 9 -->
  <div class="product">
    <img src="https://i.pinimg.com/736x/b7/ab/a1/b7aba1bfd0f0474f203a4c9e519897a2.jpg" alt="Decor 3">
    <div class="product-content">
      <h4>Artifical Traditional Theme</h4>
      <p>₹13,000 <del>₹15,000</del> (13% off)</p>
      <div class="product-info">
        <div class="card">
          <input type="checkbox" id="exp9" class="toggle" hidden/>
          <div class="content">
             <p>Premium wedding car decor with floral arrangements and ribbons.
              Includes back, hood, side mirrors, and roof decoration with fresh flowers.
              Custom color themes and add-ons available on request.</p>
          </div>
          <label for="exp9" class="btn">
            <span class="more">See more</span>
            <span class="less">See less</span>
          </label>
          <a href="info.html">
            <button class="book-btn">Book Now</button>
          </a>
        </div>
      </div>
    </div>
  </div>

  <!-- Product 10 -->
  <div class="product">
    <img src="https://i.pinimg.com/1200x/fb/e9/d5/fbe9d51be73a28878e46d797ae6110a3.jpg" alt="Decor 3">
    <div class="product-content">
      <h4>Heart on Bonat & Marigold</h4>
      <p>₹13,000 <del>₹15,000</del> (13% off)</p>
      <div class="product-info">
        <div class="card">
          <input type="checkbox" id="exp10" class="toggle" hidden/>
          <div class="content">
            <p>Premium wedding car decor with floral arrangements and ribbons.
              Includes back, hood, side mirrors, and roof decoration with fresh flowers.
              Custom color themes and add-ons available on request.</p>
          </div>
          <label for="exp10" class="btn">
            <span class="more">See more</span>
            <span class="less">See less</span>
          </label>
          <a href="info.html">
            <button class="book-btn">Book Now</button>
          </a>
        </div>
      </div>
    </div>
  </div>

  <!-- Product 11 -->
  <div class="product">
    <img src="https://i.pinimg.com/736x/96/aa/fd/96aafd43547b306cc939fbef6bbbd974.jpg" alt="Decor 3">
    <div class="product-content">
      <h4>Marigold & Rajani Theme1</h4>
      <p>₹13,000 <del>₹15,000</del> (13% off)</p>
      <div class="product-info">
        <div class="card">
          <input type="checkbox" id="exp11" class="toggle" hidden/>
          <div class="content">
            <p>Premium wedding car decor with floral arrangements and ribbons.
              Includes back, hood, side mirrors, and roof decoration with fresh flowers.
              Custom color themes and add-ons available on request.</p>
          </div>
          <label for="exp11" class="btn">
            <span class="more">See more</span>
            <span class="less">See less</span>
          </label>
          <a href="info.html">
            <button class="book-btn">Book Now</button>
          </a>
        </div>
      </div>
    </div>
  </div>

  <!-- Product 12 -->
  <div class="product">
    <img src="https://i.pinimg.com/736x/e6/18/a1/e618a15a4cfac854b1400a20f88bd46c.jpg" alt="Decor 3">
    <div class="product-content">
      <h4>Marigold & Rajani Theme2</h4>
      <p>₹13,000 <del>₹15,000</del> (13% off)</p>
      <div class="product-info">
        <div class="card">
          <input type="checkbox" id="exp12" class="toggle" hidden/>
          <div class="content">
            <p>Premium wedding car decor with floral arrangements and ribbons.
              Includes back, hood, side mirrors, and roof decoration with fresh flowers.
              Custom color themes and add-ons available on request.</p>
          </div>
          <label for="exp12" class="btn">
            <span class="more">See more</span>
            <span class="less">See less</span>
          </label>
          <a href="info.html">
            <button class="book-btn">Book Now</button>
          </a>
        </div>
      </div>
    </div>
  </div>

  


</div>

<footer>
  <p>OM SAJAWAT CENTRE | Andhra Tharhi Gumti Chowk</p>
  <p>Contact: 8210770922, 9709932816</p>
</footer>

</body>
</html>
``
