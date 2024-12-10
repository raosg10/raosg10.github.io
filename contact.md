---
layout: default
title: Contact
---

<div class="contact-form-container">
  <!-- Left Side: Image -->
  <div class="contact-image">
    <img src="Images\me.JPEG" alt="Contact Us">
  </div>

  <!-- Right Side: Contact Form -->
  <div class="contact-form">
    <h1>Contact Me</h1>
    <h3>If you have any questions, feel free to reach out to me using the form below:</h3>

    <form action="https://formspree.io/f/xbljeala" method="POST">
      <label for="name">Your Name:</label>
      <input type="text" id="name" name="name" required>
      
      <label for="email">Your Email:</label>
      <input type="email" id="email" name="email" required>
      
      <label for="message">Your Message:</label>
      <textarea id="message" name="message" rows="4" required></textarea>
      
      <button type="submit">Send Message</button>
    </form>
  </div>
</div>
