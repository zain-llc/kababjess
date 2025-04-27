<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Kababjees Express Header</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
        }
        .header {
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 10px 30px;
            background-color: #ffffff;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .header-left {
            display: flex;
            align-items: center;
        }
        .header-left img {
            height: 50px;
            margin-right: 20px;
        }
        .header-buttons button {
            margin-right: 10px;
            background-color: #ff2e2e;
            color: #fff;
            border: none;
            padding: 8px 15px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 14px;
        }
        .header-right {
            display: flex;
            align-items: center;
        }
        .header-right img {
            height: 25px;
            margin-left: 20px;
            cursor: pointer;
        }
        .categories {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    padding: 40px 20px;
    background-color: #ffffff;
}

.category {
    background-color: rgb(0, 0, 0);
    border: 1px solid #fcfcfc;
    border-radius: 10px;
    overflow: hidden;
    text-align: center;
    width: 200px;
    cursor: pointer;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s, box-shadow 0.3s;
}

.category img {
    width: 100%;
    height: 150px;
    object-fit: cover;
}

.category p {
    margin: 15px 0;
    font-size: 18px;
    font-weight: bold;
    color: #fff1f1;
}

.category:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 12px rgba(0, 0, 0, 0.2);
}
</style>
</head>
<body>

<header class="header">
    <div class="header-left">
        <img src="kababjees.png" alt="Kababjees Express Logo">
        <div class="header-buttons">
            <button>Change Location</button>
            <button>021111666111</button>
            <button>Submit Your Complaint</button>
        </div>
    </div>
    <div class="header-right">
        <img src="kababjees2.png" alt="Cart">
        <img src="kababjees3.png" alt="Menu">
    </div>
</header>

</body>
</html>
<div class="banner">
    <img src="kababjees4.png" alt="Banner" style="width: 100%; height: auto;">
</div>
<div class="categories">
    <div class="category">
        <img src="kabab7.png" alt="Burger">
        <p>Burger</p>
    </div>
    <div class="category">
        <img src="kababjess10.png" alt="Category 2">
        <p>Roll</p>
    </div>
    <div class="category">
        <img src="kababjess11.png" alt="Category 3">
        <p>Pasta</p>
    </div>
    <div class="category">
        <img src="kababjess12.png" alt="Category 4">
        <p>Pizza</p>
    </div>
    <div class="category">
        <img src="kabab13.png" alt="Category 4">
        <p>Sandwhiches</p>
    </div>
</div>
<!-- Popular Items Section -->
<section style="padding: 40px; background-color: #f9f9f9;">
    <h2 style="font-size: 28px; margin-bottom: 20px;">🔥 Popular Items</h2>
    <p style="margin-bottom: 30px;">Most ordered right now</p>
    
    <div style="display: flex; gap: 20px; flex-wrap: wrap;">
      
      <!-- Item 1 -->
      <div style="background: #fff; border-radius: 10px; box-shadow: 0 2px 8px rgba(0,0,0,0.1); width: 250px; overflow: hidden;">
        <img src="kababjes14.png" alt="Family Combo 2" style="width: 100%; height: 160px; object-fit: cover;">
        <div style="padding: 15px;">
          <h3 style="font-size: 20px;">Family Combo 2</h3>
          <p style="margin: 5px 0;">4 Chicken Zinger Burger + 4 Chicken Chatni Roll + 1.5 Ltr Drink</p>
          <strong>Rs. 2450</strong>
          <br><br>
          <a href="#" style="display: inline-block; padding: 10px 20px; background-color: #ff5722; color: white; border-radius: 5px; text-decoration: none; font-weight: bold;">Order Now</a>
        </div>
      </div>
  
      <!-- Item 2 -->
      <div style="background: #fff; border-radius: 10px; box-shadow: 0 2px 8px rgba(0,0,0,0.1); width: 250px; overflow: hidden;">
        <img src="kababjes15.png" alt="Family Combo 3" style="width: 100%; height: 160px; object-fit: cover;">
        <div style="padding: 15px;">
          <h3 style="font-size: 20px;">Family Combo 3</h3>
          <p style="margin: 5px 0;">4 Chicken Zinger Burger + 4 Chicken Roll + Any Chicken Rice + 1.5 Ltr Drink</p>
          <strong>Rs. 2699</strong>
          <br><br>
          <a href="#" style="display: inline-block; padding: 10px 20px; background-color: #ff5722; color: white; border-radius: 5px; text-decoration: none; font-weight: bold;">Order Now</a>
        </div>
      </div>
  
      <!-- Item 3 -->
      <div style="background: #fff; border-radius: 10px; box-shadow: 0 2px 8px rgba(0,0,0,0.1); width: 250px; overflow: hidden;">
        <img src="kababjes16.png" alt="Zingo Burger" style="width: 100%; height: 160px; object-fit: cover;">
        <div style="padding: 15px;">
          <h3 style="font-size: 20px;">Zingo Burger</h3>
          <p style="margin: 5px 0;">Delicious crispy chicken burger</p>
          <strong>Rs. 299</strong>
          <br><br>
          <a href="#" style="display: inline-block; padding: 10px 20px; background-color: #ff5722; color: white; border-radius: 5px; text-decoration: none; font-weight: bold;">Order Now</a>
        </div>
      </div>
  
      <!-- Item 4 -->
      <div style="background: #fff; border-radius: 10px; box-shadow: 0 2px 8px rgba(0,0,0,0.1); width: 250px; overflow: hidden;">
        <img src="kababjes17.png" alt="Alfredo Pasta" style="width: 100%; height: 160px; object-fit: cover;">
        <div style="padding: 15px;">
          <h3 style="font-size: 20px;">Alfredo Pasta</h3>
          <p style="margin: 5px 0;">Creamy pasta with grilled chicken</p>
          <strong>Rs. 850</strong>
          <br><br>
          <a href="#" style="display: inline-block; padding: 10px 20px; background-color: #ff5722; color: white; border-radius: 5px; text-decoration: none; font-weight: bold;">Order Now</a>
        </div>
      </div>
  
      <!-- Item 5 -->
      <div style="background: #fff; border-radius: 10px; box-shadow: 0 2px 8px rgba(0,0,0,0.1); width: 250px; overflow: hidden;">
        <img src="kk3.jpeg" alt="Chicken Wrap" style="width: 100%; height: 160px; object-fit: cover;">
        <div style="padding: 15px;">
          <h3 style="font-size: 20px;">Chicken Wrap</h3>
          <p style="margin: 5px 0;">Spicy chicken wrapped in soft tortilla</p>
          <strong>Rs. 450</strong>
          <br><br>
          <a href="#" style="display: inline-block; padding: 10px 20px; background-color: #ff5722; color: white; border-radius: 5px; text-decoration: none; font-weight: bold;">Order Now</a>
        </div>
      </div>
  
      <!-- Item 6 -->
      <div style="background: #fff; border-radius: 10px; box-shadow: 0 2px 8px rgba(0,0,0,0.1); width: 250px; overflow: hidden;">
        <img src="kk2.jpeg" alt="Beef Burger" style="width: 100%; height: 160px; object-fit: cover;">
        <div style="padding: 15px;">
          <h3 style="font-size: 20px;">Beef Burger</h3>
          <p style="margin: 5px 0;">Juicy beef patty with cheese and sauces</p>
          <strong>Rs. 550</strong>
          <br><br>
          <a href="#" style="display: inline-block; padding: 10px 20px; background-color: #ff5722; color: white; border-radius: 5px; text-decoration: none; font-weight: bold;">Order Now</a>
        </div>
      </div>
  
      <!-- Item 7 -->
      <div style="background: #fff; border-radius: 10px; box-shadow: 0 2px 8px rgba(0,0,0,0.1); width: 250px; overflow: hidden;">
        <img src="kabab19,png.jpeg" alt="Grilled Sandwich" style="width: 100%; height: 160px; object-fit: cover;">
        <div style="padding: 15px;">
          <h3 style="font-size: 20px;">Grilled Sandwich</h3>
          <p style="margin: 5px 0;">Loaded with cheese and grilled chicken</p>
          <strong>Rs. 350</strong>
          <br><br>
          <a href="#" style="display: inline-block; padding: 10px 20px; background-color: #ff5722; color: white; border-radius: 5px; text-decoration: none; font-weight: bold;">Order Now</a>
        </div>
      </div>
  
      <!-- Item 8 -->
      <div style="background: #fff; border-radius: 10px; box-shadow: 0 2px 8px rgba(0,0,0,0.1); width: 250px; overflow: hidden;">
        <img src="kk1.jpg" alt="Fries Bucket" style="width: 100%; height: 160px; object-fit: cover;">
        <div style="padding: 15px;">
          <h3 style="font-size: 20px;">Fries Bucket</h3>
          <p style="margin: 5px 0;">Crispy fries served with dips</p>
          <strong>Rs. 299</strong>
          <br><br>
          <a href="#" style="display: inline-block; padding: 10px 20px; background-color: #ff5722; color: white; border-radius: 5px; text-decoration: none; font-weight: bold;">Order Now</a>
        </div>
      </div>
  
    </div>
  </section>
  <div class="banner">
    <img src="kk5.png" alt="Banner" style="width: 100%; height: auto;">
</div>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Deals</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: #f7f7f7;
            padding: 20px;
        }
        .deals-container {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .deal-card {
            background: #fff;
            border: 1px solid #ddd;
            border-radius: 10px;
            width: 250px;
            text-align: center;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
            overflow: hidden;
        }
        .deal-card img {
            width: 100%;
            height: 150px;
            object-fit: cover;
        }
        .deal-content {
            padding: 15px;
        }
        .deal-content h3 {
            font-size: 20px;
            margin: 10px 0;
        }
        .deal-content p {
            font-size: 14px;
            color: #555;
            margin-bottom: 15px;
        }
        .price {
            font-weight: bold;
            color: #e60000;
            margin-bottom: 10px;
        }
        .add-to-cart {
            display: inline-block;
            background: #ff4d4d;
            color: #fff;
            padding: 10px 20px;
            border-radius: 5px;
            text-decoration: none;
            margin-bottom: 15px;
        }
        .add-to-cart:hover {
            background: #e60000;
        }
    </style>
</head>
<body>

<div class="deals-container">

    <div class="deal-card">
        <img src="deal1.png" alt="Deal 1">
        <div class="deal-content">
            <h3>Deal 1</h3>
            <p>3 Chicken Chatni Rolls</p>
            <div class="price">Rs. 999</div>
            <a href="#" class="add-to-cart">Add to Cart</a>
        </div>
    </div>

    <div class="deal-card">
        <img src="deal3.png" alt="Deal 2">
        <div class="deal-content">
            <h3>Deal 2</h3>
            <p>2 Chicken Zingo Burgers, 2 Turkish Kabab Rolls</p>
            <div class="price">Rs. 1099</div>
            <a href="#" class="add-to-cart">Add to Cart</a>
        </div>
    </div>

    <div class="deal-card">
        <img src="deal4.png" alt="Deal 3">
        <div class="deal-content">
            <h3>Deal 3</h3>
            <p>5 Turkish Reshmi Kabab Rolls</p>
            <div class="price">Rs. 1099</div>
            <a href="#" class="add-to-cart">Add to Cart</a>
        </div>
    </div>

    <div class="deal-card">
        <img src="deal1.png" alt="Family Combo 3">
        <div class="deal-content">
            <h3>Family Combo 3</h3>
            <p>4 Zingo Burgers, 4 Chicken Chatni Rolls, 1.5L Drink</p>
            <div class="price">Rs. 2699</div>
            <a href="#" class="add-to-cart">Add to Cart</a>
        </div>
    </div>

</div>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Deals with Reviews</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: #f7f7f7;
            padding: 20px;
        }
        .deals-container {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .deal-card {
            background: #fff;
            border: 1px solid #ddd;
            border-radius: 10px;
            width: 270px;
            text-align: center;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
            overflow: hidden;
        }
        .deal-card img {
            width: 100%;
            height: 150px;
            object-fit: cover;
        }
        .deal-content {
            padding: 15px;
        }
        .deal-content h3 {
            font-size: 20px;
            margin: 10px 0;
        }
        .deal-content p {
            font-size: 14px;
            color: #555;
            margin-bottom: 10px;
        }
        .price {
            font-weight: bold;
            color: #e60000;
            margin-bottom: 10px;
        }
        .add-to-cart {
            display: inline-block;
            background: #ff4d4d;
            color: #fff;
            padding: 10px 20px;
            border-radius: 5px;
            text-decoration: none;
            margin-bottom: 10px;
        }
        .add-to-cart:hover {
            background: #e60000;
        }
        .review-section {
            padding: 10px;
            border-top: 1px solid #ddd;
            background: #fafafa;
            font-size: 13px;
            text-align: left;
        }
        .stars {
            color: #f0ad4e;
            margin-bottom: 5px;
        }
        .review-text {
            margin-bottom: 5px;
            color: #333;
        }
        .review-author {
            font-style: italic;
            color: #777;
        }
    </style>
</head>
<body>

<div class="deals-container">

    <div class="deal-card">
        <img src="deal1.png" alt="Deal 1">
        <div class="deal-content">
            <h3>Deal 1</h3>
            <p>3 Chicken Chatni Rolls</p>
            <div class="price">Rs. 999</div>
            <a href="#" class="add-to-cart">Add to Cart</a>
        </div>
        <div class="review-section">
            <div class="stars">⭐⭐⭐⭐⭐</div>
            <div class="review-text">"Amazing taste! Rolls were fresh and delicious."</div>
            <div class="review-author">- Ali Khan</div>
        </div>
    </div>

    <div class="deal-card">
        <img src="deal3.png" alt="Deal 2">
        <div class="deal-content">
            <h3>Deal 2</h3>
            <p>2 Chicken Zingo Burgers, 2 Turkish Kabab Rolls</p>
            <div class="price">Rs. 1099</div>
            <a href="#" class="add-to-cart">Add to Cart</a>
        </div>
        <div class="review-section">
            <div class="stars">⭐⭐⭐⭐</div>
            <div class="review-text">"Good quantity and very juicy burgers!"</div>
            <div class="review-author">- Sarah Malik</div>
        </div>
    </div>

    <div class="deal-card">
        <img src="deal4.png" alt="Deal 3">
        <div class="deal-content">
            <h3>Deal 3</h3>
            <p>5 Turkish Reshmi Kabab Rolls</p>
            <div class="price">Rs. 1099</div>
            <a href="#" class="add-to-cart">Add to Cart</a>
        </div>
        <div class="review-section">
            <div class="stars">⭐⭐⭐⭐⭐</div>
            <div class="review-text">"Best kababs in town. Soft and flavorful."</div>
            <div class="review-author">- Usman Sheikh</div>
        </div>
    </div>
      <div class="deal-card">
        <img src="deal1.png" alt="Family Combo 3">
        <div class="deal-content">
            <h3>Family Combo 3</h3>
            <p>4 Zingo Burgers, 4 Chicken Chatni Rolls, 1.5L Drink</p>
            <div class="price">Rs. 2699</div>
            <a href="#" class="add-to-cart">Add to Cart</a>
        </div>
        <div class="review-section">
            <div class="stars">⭐⭐⭐⭐⭐</div>
            <div class="review-text">"Perfect for family gatherings. Everyone loved it!"</div>
            <div class="review-author">- Hira Javed</div>
        </div>
     </div>
     <footer style="background-color: #d62828; color: white; padding: 40px 20px;">
        <div style="display: flex; flex-wrap: wrap; justify-content: space-between; align-items: flex-start;">
          <div style="flex: 1; min-width: 200px; margin-bottom: 20px;">
            <img src="kababjees.png" alt="Logo" style="width: 150px;">
          </div>
      
          <div style="flex: 1; min-width: 200px; margin-bottom: 20px;">
            <h3>Information</h3>
            <ul style="list-style: none; padding: 0;">
              <li><a href="#" style="color: white; text-decoration: none;">Our Locations</a></li>
              <li><a href="#" style="color: white; text-decoration: none;">Blog</a></li>
              <li><a href="#" style="color: white; text-decoration: none;">Submit Your Complaint</a></li>
              <li><a href="#" style="color: white; text-decoration: none;">Bank Discounts</a></li>
            </ul>
          </div>
      
          <div style="flex: 1; min-width: 200px; margin-bottom: 20px;">
            <h3>Contact Us</h3>
            <p>021-111-666-111</p>
          </div>
      
          <div style="flex: 1; min-width: 200px; text-align: center; margin-bottom: 20px;">
            <h3>Get The App!</h3>
            <p>App is where the fun is! It's Easy, Fast and Convenient.</p>
            <div style="margin-top: 10px;">
              <a href="#"><img src="f3.png" alt="App Store" style="height: 40px; margin-right: 10px;"></a>
              <a href="#"><img src="f2.png" alt="Google Play" style="height: 40px;"></a>
            </div>
          </div>
        </div>
      
        <script src="https://www.gstatic.com/dialogflow-console/fast/messenger/bootstrap.js?v=1"></script>
<df-messenger
  intent="WELCOME"
  chat-title="kababjees"
  agent-id="12316319-06ed-4e03-b16e-88bad79a1f22"
  language-code="en"
></df-messenger>
    <style>
        df-messenger {
         --df-messenger-bot-message: #878fac;
         --df-messenger-button-titlebar-color: #df9b56;
         --df-messenger-chat-background-color: #fafafa;
         --df-messenger-font-color: white;
         --df-messenger-send-icon: #878fac;
         --df-messenger-user-message: #479b3d;
        }
      </style>
    # kababjess
