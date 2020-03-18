---
layout: layouts/page.njk
title: Contact Us
permalink: /contact/index.html
---

Our you’re an event organizer and want some inisght into how to run an event? A speaker that wants to know what tips to put on an online presentation? Drop us a line

<form name="contact" method="POST" data-netlify="true">
  <p>
    <label>Your Name:</label>  (required)
      </p>
      <div>
    <input type="text" name="name" style="width: 50%;" required />
</div>
  <p>
    <label>Your Email:</label> (required)
      </p>
        <div>
     <input type="email" name="email" style="width: 50%;" required />
</div>

  <p>
    <label>Do you run a conference? If so, which is it:</label> 
      </p>
        <div>
     <input type="text" name="conferenece" style="width: 50%;" />
</div>

  <p>
    <label>Message:</label> (required)
</p>
<div>
    <textarea name="message" style="width: 50%; height: 6rem;" required></textarea>
</div>
  <p>
    <button type="submit">Send</button>
  </p>
</form>
