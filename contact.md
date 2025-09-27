---
layout: default
title: Contact
---

<!-- Featured Image -->
<section class="hero" style="background-image: url('{{ site.baseurl }}/assets/images/contact-bg.jpg'); height: 80vh;">
  <div class="hero-overlay"></div>
  <div class="hero-content">
    <h1>Contact Us</h1>
  </div>
</section>

<!-- Contact Info + Form -->
<section class="container py-5">
  <div class="row">
    <div class="col-md-6 mb-4">
      <h3 class="contact-section">Get In Touch</h3>
      <p class="mt-3"><strong>Email:</strong> info@thurmanbrownconsultant.com</p>
      <p><strong>Phone:</strong> (123) 456-7890</p>
      <p><strong>Address:</strong> 123 Main Street, City, State</p>
    </div>
    <div class="col-md-6 mb-4">
      <h3 class="contact-section">Submit Your Query</h3>
      <form>
        <input type="text" class="form-control mb-2" placeholder="Your Name" required>
        <input type="email" class="form-control mb-2" placeholder="Your Email" required>
        <textarea class="form-control mb-2" placeholder="Your Message" required></textarea>
        <button type="submit" class="btn btn-primary">Send Message</button>
      </form>
    </div>
  </div>
  <div class="map mt-4">
    <iframe src="https://www.google.com/maps/embed?pb=!1m18..." width="100%" height="350" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
  </div>
</section>
