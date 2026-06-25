---
layout: default
title: Contact Us | SATCO
---

<style>
  /* Custom Page Layout */
  .contact-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 40px;
    margin-top: 30px;
  }
  
  /* Form Styling */
  .contact-form {
    background: #f8f9fa;
    padding: 30px;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.05);
    border-top: 4px solid #cc7a00;
  }
  .form-group {
    margin-bottom: 20px;
  }
  .form-group label {
    display: block;
    margin-bottom: 8px;
    font-weight: bold;
    color: #1a252f;
  }
  .form-group input, .form-group textarea {
    width: 100%;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 4px;
    box-sizing: border-box;
  }
  .form-group textarea {
    resize: vertical;
    height: 120px;
  }
  .submit-btn {
    background-color: #cc7a00;
    color: white;
    padding: 12px 20px;
    border: none;
    border-radius: 4px;
    font-weight: bold;
    cursor: pointer;
    width: 100%;
    transition: background 0.3s;
  }
  .submit-btn:hover {
    background-color: #b36b00;
  }

  /* Info Details Styling */
  .contact-info {
    padding: 10px;
  }
  .info-item {
    margin-bottom: 25px;
  }
  .info-item h4 {
    color: #cc7a00;
    margin-bottom: 5px;
    font-size: 1.1em;
  }
  .info-item p {
    color: #555;
    margin: 0;
  }
</style>

<h2>Get in Touch</h2>
<p style="color: #666;">Have an inquiry or need strategic sourcing? Contact our global team today.</p>

<div class="contact-container">
  
  <!-- Contact Form -->
  <div class="contact-form">
    <!-- Replace 'your-formspree-id' later to activate the email form -->
    <form action="https://formspree.io/f/your-formspree-id" method="POST">
      <div class="form-group">
        <label for="name">Full Name</label>
        <input type="text" id="name" name="name" required placeholder="John Doe">
      </div>
      <div class="form-group">
        <label for="email">Business Email</label>
        <input type="email" id="email" name="_replyto" required placeholder="john@company.com">
      </div>
      <div class="form-group">
        <label for="message">Your Inquiry</label>
        <textarea id="message" name="message" required placeholder="Please describe your commodity or logistics requirements..."></textarea>
      </div>
      <button type="submit" class="submit-btn">Send Message</button>
    </form>
  </div>

  <!-- Office Info -->
  <div class="contact-info">
    <div class="info-item">
      <h4>Global Headquarters</h4>
      <p>SATCO International Group</p>
      <p>Financial District, Supply Chain Tower, Floor 14</p>
    </div>
    <div class="info-item">
      <h4>Direct Contact</h4>
      <p><strong>Email:</strong> info@satco-group.com</p>
      <p><strong>Phone:</strong> +1 (555) 019-2834</p>
    </div>
    <div class="info-item">
      <h4>Business Hours</h4>
      <p>Monday - Friday: 8:00 AM - 6:00 PM (GMT)</p>
      <p>24/7 Support for Active Cargo & Logistics</p>
    </div>
  </div>

</div>
