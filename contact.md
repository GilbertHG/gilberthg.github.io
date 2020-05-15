---
layout: default
title: Contact
---

<div id="contact">
  <h1 class="pageTitle">Contact Me</h1>
  <div class="contactContent">
    <p>Have a question or want to discuss with me? Just contact me via this form.</p>
  </div>

  <form action="http://formspree.io/gilbertgoes11@gmail.com" method="POST">
    <label for="name">Name</label>
    <input type="text" id="name" name="name" class="full-width" required><br>
    <label for="email">Email Address</label>
    <input type="email" id="email" name="_replyto" class="full-width" required><br>
    <label for="message">Message</label>
    <textarea
      name="message"
      id="message"
      cols="30"
      rows="10"
      class="full-width"
      required></textarea><br>
    <input type="submit" value="Send" class="button">
  </form>
</div>
