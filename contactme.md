﻿---
layout: page
title: Contact me
subtitle: If you wanted to reach out!
css: “/css/contactme.css”
---

<form action="https://formspree.io/f/xgepoaoe" method="POST" class="form" id="contact-form">

  <div class="row">
  <p>Please leave me a message:</p>
  </div>

  <div class="row">

    <div class="col-xs-6">
      <input type="email" name="_replyto" class="form-control input-lg" placeholder="Your Email" title="Email">
    </div>

    <div class="col-xs-6">
      <input type="text" name="name" class="form-control input-lg" placeholder="Your Name" title="Name">
    </div>
  </div>

  <input type="hidden" name="_subject" value="New submission from sladewinter.github.io">

<br />
<div class="row">

  <textarea type="text" name="content" class="form-control input-lg" placeholder="Your Message" title="Message" required="required" rows="3"></textarea>

</div>

  <input type="text" name="_gotcha" style="display:none">

  <input type="hidden" name="_next" value="./aboutme?message=Your message was sent successfully, thanks!" />
  
<br />
<div class="row">
  <button type="submit" class="btn btn-lg btn-primary">Submit</button>
</div>

</form>
