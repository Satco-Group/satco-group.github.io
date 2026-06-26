---
layout: default
title: About Us | SATCO
---

<style>
  /* استایل هماهنگ با صفحه اصلی */
  .custom-nav {
    background: #1a252f;
    padding: 15px 5px;
    text-align: center;
    border-radius: 4px;
    margin-bottom: 30px;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 15px;
  }
  .custom-nav a {
    color: #fff !important;
    text-decoration: none;
    font-weight: bold;
    font-size: 14px;
    cursor: pointer;
    padding: 5px 10px;
    border-bottom: 2px solid transparent;
    transition: 0.3s;
  }
  .custom-nav a:hover, .dropdown:hover .dropbtn {
    border-bottom: 2px solid #cc7a00;
  }
  
  /* Dropdown Menu Styling */
  .dropdown { display: inline-block; position: relative; }
  .dropdown-content {
    display: none; position: absolute; background-color: #f9f9f9;
    min-width: 200px; box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
    z-index: 100; text-align: left; border-radius: 4px; margin-top: 10px;
  }
  .dropdown-content a {
    color: #333 !important; padding: 10px 16px; display: block;
    margin: 0; font-weight: normal; border-bottom: none !important;
  }
  .dropdown-content a:hover { background-color: #f1f1f1; }
  .dropdown:hover .dropdown-content { display: block; }

  /* About Content Styling */
  .about-container { max-width: 800px; margin: 40px auto; padding: 20px; line-height: 1.8; color: #333; }
  .about-container h2 { color: #cc7a00; margin-bottom: 20px; }
</style>

<nav class="custom-nav">
  <a href="index.html">Home</a>
  <a href="about.html">About Us</a>
  
  <div class="dropdown">
    <a class="dropbtn">Minerals ▾</a>
    <div class="dropdown-content">
      <a href="#">Cement</a><a href="#">Clinker</a><a href="#">Dolomite</a>
      <a href="#">Gypsum Stone & Powder</a><a href="#">Microsilica</a><a href="#">Calcium Carbonate</a>
    </div>
  </div>

  <div class="dropdown">
    <a class="dropbtn">Petrochemicals ▾</a>
    <div class="dropdown-content">
      <a href="#">Bitumen</a><a href="#">Urea</a><a href="#">Methanol</a>
      <a href="#">Polyethylene</a><a href="#">Polypropylene</a><a href="#">PVC</a>
      <a href="#">Acetic Acid</a><a href="#">MEG</a>
    </div>
  </div>

  <div class="dropdown">
    <a class="dropbtn">Refined ▾</a>
    <div class="dropdown-content">
      <a href="#">Sulfur</a><a href="#">Gas Oil / Diesel</a><a href="#">Base Oil</a>
      <a href="#">Fuel Oil / Mazut</a><a href="#">LPG</a>
    </div>
  </div>
  
  <a href="#">Logistics Consulting</a>
  <a href="contact.html">Contact Us</a>
</nav>

<div class="about-container">
  <h2>Bridging Markets, Delivering Excellence</h2>
  <p>
    With a rich history spanning over two decades, SATCO has established itself as a trusted partner in global trading and supply chain management. 
    Since our inception in 1998, we have consistently focused on building long-term relationships through integrity and reliability. 
    In 2012, we expanded our footprint by establishing operations in Georgia, further strengthening our capacity to serve diverse markets.
  </p>
  <p>
    Our expertise spans across three core pillars: <strong>Industrial Minerals</strong>, <strong>Petrochemicals</strong>, and <strong>Refined Petroleum Products</strong>. 
    At SATCO, we believe that successful trade is built on trust, transparency, and timely delivery.
  </p>
  <p>
    Our mission is to simplify complex global sourcing for our clients. By combining deep market insights with robust logistics management, 
    we ensure that your requirements are met with precision—from the point of origin to your final destination. 
    Whether you are a large-scale manufacturer or a specialized trader, SATCO is your strategic partner for sustainable and reliable supply chain solutions.
  </p>
</div>
