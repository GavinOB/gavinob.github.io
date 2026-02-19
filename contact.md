---
layout: page
title: Contact
permalink: /contact/
---

Have a question about my research, a family connection, or just want to get in touch? Fill out the form below and I'll get back to you.

<form action="https://formspree.io/f/xgolloaa" method="POST" class="contact-form">

  <!-- Redirect after submission -->
  <input type="hidden" name="_next" value="https://www.gavinobrien.net/thanks/">

  <!-- Honeypot spam protection -->
  <input type="text" name="_gotcha" style="display:none">

  <div class="form-group">
    <label for="name">Name</label>
    <input type="text" id="name" name="name" required placeholder="Your name">
  </div>

  <div class="form-group">
    <label for="email">Email</label>
    <input type="email" id="email" name="_replyto" required placeholder="your@email.com">
  </div>

  <div class="form-group">
    <label for="message">Message</label>
    <textarea id="message" name="message" required rows="7" placeholder="Your message..."></textarea>
  </div>

  <button type="submit" class="contact-submit">Send Message</button>

</form>
