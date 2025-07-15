# Syca.org.ng
Sabuwa Youth Cooperative Association official site 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sabuwa Youth Cooperative Association (SYCA)</title>

  <!-- ======  Basic styling  (replace with your own stylesheet) ====== -->
  <style>
    :root {
      --syca-green:#0c6b2e;
      --syca-red:#d62828;
      --syca-purple:#6a4c93;
      --syca-blue:#005f99;
      --syca-light:#f7f7f7;
    }
    *{box-sizing:border-box;margin:0;padding:0;font-family:system-ui,Helvetica,Arial;}
    body{background:var(--syca-light);color:#222;line-height:1.6;}
    header{background:var(--syca-green);color:#fff;padding:1.5rem 1rem;text-align:center;}
    nav{display:flex;flex-wrap:wrap;gap:.5rem;justify-content:center;margin-top:1rem;}
    nav a{color:#fff;text-decoration:none;font-weight:600;padding:.25rem .75rem;border-radius:4px;}
    nav a:hover{background:rgba(255,255,255,.15);}
    section{padding:3rem 1rem;max-width:1200px;margin:auto;}
    h2{margin-bottom:1rem;color:var(--syca-green);}
    .grid{display:grid;gap:1.5rem;}
    .cards{grid-template-columns:repeat(auto-fit,minmax(220px,1fr));}
    footer{background:#222;color:#eee;text-align:center;padding:2rem 1rem;margin-top:4rem;}
    .btn{background:var(--syca-red);color:#fff;border:none;padding:.65rem 1.25rem;border-radius:4px;cursor:pointer}
    .btn:hover{opacity:.85}
  </style>

  <!-- ======  Optional JS for simple nav-toggle on mobile  ====== -->
  <script defer>
    document.addEventListener("DOMContentLoaded", ()=>{
      const btn=document.querySelector("#toggle");const nav=document.querySelector("nav");
      btn?.addEventListener("click",()=>nav.classList.toggle("show"));
    });
  </script>
</head>
<body>

  <!-- =====  HERO / INTRO  ===== -->
  <header>
    <img src="assets/syca-logo.png" alt="SYCA Logo" style="max-width:120px;">
    <h1>Sabuwa Youth Cooperative Association</h1>
    <p><em>Unity in action, growth through cooperation</em></p>

    <!-- WhatsApp quick-chat -->
    <a class="btn" href="https://wa.me/2348100011882" target="_blank">Chat on WhatsApp</a>

    <!-- small hamburger for mobile -->
    <button id="toggle" style="margin-left:.5rem;background:none;border:none;color:#fff;font-size:1.4rem">&#9776;</button>

    <!-- Main nav -->
    <nav>
      <a href="#about">About</a>
      <a href="#benefits">Benefits</a>
      <a href="#events">Events</a>
      <a href="#resources">Resources</a>
      <a href="#get-involved">Get Involved</a>
      <a href="#blog">Blog/News</a>
      <a href="#gallery">Gallery</a>
      <a href="#testimonials">Testimonials</a>
      <a href="#members">Members</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- ======  ABOUT  ====== -->
  <section id="about">
    <h2>Our Mission &amp; Vision</h2>
    <p><strong>Mission&nbsp;–</strong> The Sabuwa Youth Cooperative Association is dedicated to empowering and uplifting the youth ...</p>
    <p><strong>Vision&nbsp;–</strong> Our vision is a thriving, self-reliant, and prosperous community of young people equipped with tools ...</p>
  </section>

  <!-- ======  BENEFITS  ====== -->
  <section id="benefits">
    <h2>Member Benefits</h2>
    <div class="grid cards">
      <article><h3>Financial Support</h3><p>Interest-free loans, emergency funds, savings.</p></article>
      <article><h3>Business &amp; Career</h3><p>Training in entrepreneurship, digital skills, job readiness.</p></article>
      <article><h3>Strong Network</h3><p>Connect with like-minded youth through projects and programs.</p></article>
      <article><h3>Learning &amp; Development</h3><p>Mentorship, seminars, knowledge sharing sessions.</p></article>
      <article><h3>Support &amp; Representation</h3><p>We stand with members during challenges &amp; advocacy.</p></article>
      <article><h3>Recognition</h3><p>Awards, leadership roles, new opportunities.</p></article>
    </div>
  </section>

  <!-- ======  EVENTS  ====== -->
  <section id="events">
    <h2>Upcoming Events &amp; Webinars</h2>
    <ul>
      <li><strong>Monthly Knowledge Webinar:</strong> “Unlocking Youth Potential in the Digital Age” – Date TBA</li>
      <li><strong>Community Forum &amp; Networking Meetup:</strong> Physical/virtual – Date TBA</li>
      <li><strong>Leadership &amp; Teamwork Workshop</strong></li>
      <li><strong>Project Incubator &amp; Innovation Challenge</strong></li>
    </ul>
  </section>

  <!-- ======  RESOURCES  ====== -->
  <section id="resources">
    <h2>Resources &amp; Publications</h2>
    <ul>
      <li><a href="docs/SYCA-Constitution.pdf" target="_blank">SYCA Constitution &amp; Member Handbook</a></li>
      <li>Leadership &amp; Self-Development Manuals (PDF)</li>
      <li>Business &amp; Financial Tips Booklets</li>
      <li>Online learning links &amp; tutorials</li>
      <li>Newsletters &amp; progress reports</li>
    </ul>
  </section>

  <!-- ======  GET INVOLVED  ====== -->
  <section id="get-involved">
    <h2>Get Involved</h2>
    <p>Become a member, volunteer, or partner with us:</p>
    <div class="grid cards">
      <div>
        <h3>Become a Member</h3>
        <p>Open to all students &amp; youth of Sabuwa L.G.A and beyond.</p>
        <a class="btn" href="docs/SYCA_Registration_Form_Hausa_English.pdf" download>Download Registration Form</a>
      </div>
      <div>
        <h3>Volunteer</h3>
        <p>Help organise events or bring your skills to a working committee.</p>
      </div>
      <div>
        <h3>Partner With SYCA</h3>
        <p>Collaborate on community projects, sponsorships, and training.</p>
      </div>
    </div>
  </section>

  <!-- ======  BLOG / NEWS  ====== -->
  <section id="blog">
    <h2>Latest News</h2>
    <!-- Example post -->
    <article>
      <h3>SYCA Clean-up Campaign Success</h3>
      <p class="meta">Posted 1 June 2025 | <a href="#c1">3 comments</a></p>
      <p>Last Saturday, 60 volunteers helped tidy the central market …</p>
      <a class="btn" href="#">Read More</a>
    </article>
  </section>

  <!-- ======  GALLERY  ====== -->
  <section id="gallery">
    <h2>Gallery</h2>
    <div class="grid cards">
      <img src="assets/gallery/cleanup.jpg" alt="Clean-up campaign">
      <img src="assets/gallery/webinar.jpg" alt="Webinar">
      <img src="assets/gallery/teamwork.jpg" alt="Teamwork workshop">
    </div>
  </section>

  <!-- ======  TESTIMONIALS  ====== -->
  <section id="testimonials">
    <h2>Testimonials</h2>
    <blockquote>
      “Joining SYCA helped me launch my digital skills business. The mentorship is priceless!”  
      <footer>— Aisha K., Member</footer>
    </blockquote>
  </section>

  <!-- ======  MEMBERS  ====== -->
  <section id="members">
    <h2>Members Directory (Sample)</h2>
    <ul>
      <li>Musa Aliyu – Financial Secretary</li>
      <li>Lilian Okafor – Event Coordinator</li>
      <li>Yusuf Abdullahi – Volunteer</li>
    </ul>
  </section>

  <!-- ======  CONTACT  ====== -->
  <section id="contact">
    <h2>Contact Us</h2>
    <p>WhatsApp: <a href="https://wa.me/2348100011882">+234 810 001 1882</a></p>
    <p>Email: <a href="mailto:umarshehugaladima@gmail.com">umarshehugaladima@gmail.com</a></p>
    <p>Facebook: <a href="https://www.facebook.com/share/1EEoaKRp1U/" target="_blank">SYCA Facebook Page</a></p>
    <form>
      <input type="text" placeholder="Your name" required />
      <input type="email" placeholder="Your email" required />
      <textarea rows="4" placeholder="Your message"></textarea>
      <button class="btn" type="submit">Send Message</button>
    </form>
  </section>

  <!-- ======  FOOTER  ====== -->
  <footer>
    &copy; 2025 Sabuwa Youth Cooperative Association – All rights reserved.
  </footer>

</body>
</html>
