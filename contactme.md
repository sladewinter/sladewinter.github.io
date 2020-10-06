---
layout: page
title: Contact me
subtitle: If you want to reach out!
css: “/css/contactme.css”
---

<form action="https://formspree.io/f/xgepoaoe" method="POST" class="form" id="contact-form">

  <p>Leave me a message:</p>

  <div class="row">


      <input type="email" name="_replyto" class="form-control input-lg" placeholder="Your Email" title="Email">



      <input type="text" name="name" class="form-control input-lg" placeholder="Your Name" title="Name">
    </div>


  <input type="hidden" name="_subject" value="New submission from sladewinter.github.io">



  <textarea type="text" name="content" class="form-control input-lg" placeholder="Your Message" title="Message" required="required" rows="3"></textarea>



  <input type="text" name="_gotcha" style="display:none">

  <input type="hidden" name="_next" value="./aboutme?message=Your message was sent successfully, thanks!" />
  
  <button type="submit" class="btn btn-lg btn-primary">Submit</button>

</form>
