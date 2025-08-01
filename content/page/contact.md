---
title: "Contact"
menu:
  main:
    weight: 30
---

<form name="contact" method="POST" data-netlify="true">
  <p>
    <label>Your Name:<br /> <input type="text" name="name" required /></label>
  </p>
  <p>
    <label>Email:<br /> <input type="email" name="email" required /></label>
  </p>
  <p>
    <label>Message:<br /> <textarea name="message" required></textarea></label>
  </p>
  <p><button type="submit">Send</button></p>
</form>
