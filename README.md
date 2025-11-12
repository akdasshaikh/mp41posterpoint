<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>MP41 Poster Point — Design & Web Studio</title>

  <!-- Google Font: Poppins -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

  <style>
    :root{
      --blue:#0b61ff;
      --accent:#ffcc00;
      --muted:#f7f8fb;
      --dark:#0f1724;
      --radius:10px;
      --maxw:1100px;
      --gap:20px;
    }
    *{box-sizing:border-box}
    body{
      margin:0;font-family:'Poppins',system-ui,-apple-system,Segoe UI,Roboto,"Helvetica Neue",Arial;
      color:#222;background:#fff;line-height:1.5;
    }
    .container{max-width:var(--maxw);margin:0 auto;padding:40px 16px;}
    /* Portfolio hero (already provided by you) */
    .hero{background:linear-gradient(180deg,var(--blue),#1570ff);color:#fff;padding:60px 16px;border-bottom-left-radius:18px;border-bottom-right-radius:18px;}
    .hero .row{display:flex;gap:24px;align-items:center;max-width:var(--maxw);margin:0 auto;}
    .hero h1{font-size:38px;margin:0 0 8px 0;line-height:1;}
    .hero p{margin:0 0 18px 0;opacity:0.95}
    .btn{background:#fff;color:var(--blue);padding:12px 18px;border-radius:8px;font-weight:600;border:none;cursor:pointer;box-shadow:0 6px 18px rgba(11,97,255,0.12)}
    /* BELOW-FOLD SECTIONS */
    section{padding:36px 0}
    h2{font-size:26px;margin:0 0 8px}
    .sub{color:#666;margin-bottom:18px}
    /* Portfolio grid */
    .grid{display:grid;grid-template-columns:repeat(3,1fr);gap:var(--gap)}
    .card{background:#fff;border-radius:12px;overflow:hidden;box-shadow:0 6px 18px rgba(12,20,30,0.04);border:1px solid #eef2f6}
    .card img{width:100%;height:160px;object-fit:cover;display:block}
    .card .meta{padding:12px}
    .view-btn{display:inline-block;margin-top:8px;padding:8px 12px;border-radius:8px;border:1px solid var(--blue);color:var(--blue);font-weight:600;text-decoration:none}
    /* Case study */
    .case{display:flex;gap:20px;align-items:center}
    .case img{width:46%;border-radius:12px;object-fit:cover}
    .case .txt{width:54%}
    /* Testimonials */
    .test-row{display:grid;grid-template-columns:repeat(3,1fr);gap:var(--gap)}
    .test{background:var(--muted);padding:20px;border-radius:12px}
    .stars{color:var(--accent);font-weight:700;margin-bottom:8px}
    /* Pricing */
    .price-row{display:grid;grid-template-columns:repeat(3,1fr);gap:var(--gap);margin-top:8px}
    .price{background:#fff;padding:20px;border-radius:12px;border:1px solid #e9eef6;text-align:center}
    .price h3{margin:0 0 6px}
    .price .amount{font-size:22px;font-weight:700;color:var(--dark);margin:8px 0}
    .price .list{color:#555;font-size:14px;line-height:1.6;text-align:left;margin:12px 0}
    /* Contact */
    .contact-row{display:grid;grid-template-columns:1fr 340px;gap:24px;align-items:start}
    .form input,.form textarea,.form select{width:100%;padding:12px;border-radius:8px;border:1px solid #e6e9ef;margin-bottom:12px;font-size:14px}
    .wa-card{background:linear-gradient(180deg,#25d366,#1fbf4b);color:#fff;padding:20px;border-radius:12px;text-align:center}
    .wa-card a{display:inline-block;margin-top:10px;background:#fff;color:#25d366;padding:10px 16px;border-radius:8px;text-decoration:none;font-weight:600}
    /* Footer */
    footer{background:#0f1724;color:#fff;padding:26px 16px;margin-top:30px}
    footer .fcols{display:grid;grid-template-columns:repeat(4,1fr);gap:20px;max-width:var(--maxw);margin:0 auto}
    footer small{display:block;margin-top:12px;color:#cbd5e1}
    /* Responsive */
    @media(max-width:980px){
      .grid{grid-template-columns:repeat(2,1fr)}
      .test-row{grid-template-columns:repeat(2,1fr)}
      .case{flex-direction:column}
      .hero h1{font-size:30px}
      .contact-row{grid-template-columns:1fr}
      footer .fcols{grid-template-columns:repeat(2,1fr)}
    }
    @media(max-width:620px){
      .grid{grid-template-columns:1fr}
      .test-row{grid-template-columns:1fr}
      .hero .row{flex-direction:column;text-align:center}
      .hero img{width:220px}
    }
  </style>
</head>
<body>

  <!-- HERO (top given earlier) -->
  <section class="hero">
    <div class="row">
      <div style="flex:1;">
        <h1>MP41 Poster Point</h1>
        <p>Creative Graphic Design Studio — Posters, Websites & Printing. We turn ideas into designs and launch them online.</p>
        <button class="btn" onclick="document.getElementById('contact').scrollIntoView({behavior:'smooth'})">Get In Touch</button>
      </div>
      <div style="width:420px;text-align:right;">
        <!-- example graphic -->
        <img src="C:\Users\akdas\OneDrive\Desktop\New folder (3)\ChatGPT_Image_Nov_10__2025__12_50_40_PM-removebg-preview.png" alt="design" style="max-width:100%;border-radius:12px;box-shadow:0 8px 30px rgba(11,97,255,0.12)">
      </div>
    </div>
  </section>

  <div class="container">

    <!-- Portfolio -->
    <section id="portfolio">
      <h2>Portfolio</h2>
      <p class="sub">Take a look at our recent work — posters, banners and websites made for Dewas businesses.</p>

      <div class="grid">
        <div class="card">
          <img src="https://youtube.com/shorts/G9hF4eJdJ30?si=L2uhTFnIxyoUHYpT" alt="Poster 1">
          <div class="meta"><strong>The Fire Creation</strong><div><a class="view-btn" href="#">View Project</a></div></div>
        </div>
        <div class="card">
          <img src="assets/visiting_card.jpg" alt="Visiting card">
          <div class="meta"><strong>Visiting Card Sample</strong><div><a class="view-btn" href="#">View Project</a></div></div>
        </div>
        <div class="card">
          <img src="assets/banner_grocery.jpg" alt="Banner">
          <div class="meta"><strong>QuickBasket Banner</strong><div><a class="view-btn" href="#">View Project</a></div></div>
        </div>

        <div class="card">
          <img src="assets/website_mock.jpg" alt="Website">
          <div class="meta"><strong>Gangster's Gaming Hub</strong><div><a class="view-btn" href="#">View Project</a></div></div>
        </div>
        <div class="card">
          <img src="assets/invite.jpg" alt="Invitation">
          <div class="meta"><strong>Nikaah Invitation</strong><div><a class="view-btn" href="#">View Project</a></div></div>
        </div>
        <div class="card">
          <img src="assets/combo.jpg" alt="Combo">
          <div class="meta"><strong>Poster + Web Combo</strong><div><a class="view-btn" href="#">View Project</a></div></div>
        </div>
      </div>
    </section>

    <!-- Case study -->
    <section>
      <div class="case">
        <img src="assets/case_gaming.jpg" alt="Case study">
        <div class="txt">
          <h2>Case Study — Gangster's Gaming Hub</h2>
          <p class="sub">We designed a conversion-focused landing page and promotional posters. Results: +30% bookings in the first month after launch.</p>
          <a class="btn" href="#">See Full Case</a>
        </div>
      </div>
    </section>

    <!-- Testimonials -->
    <section>
      <h2>Client Love</h2>
      <p class="sub">Short feedback from our customers — trust built from real results.</p>

      <div class="test-row">
        <div class="test">
          <div class="stars">★★★★★</div>
          <p>MP41 ne hamare posters aur website banayi — result zabardast raha. Highly recommended!</p>
          <strong>— Arman, Store Owner</strong>
        </div>

        <div class="test">
          <div class="stars">★★★★★</div>
          <p>Quick delivery aur perfect design — MP41 team bahut helpful hai.</p>
          <strong>— Zeeshan, Event Organizer</strong>
        </div>

        <div class="test">
          <div class="stars">★★★★★</div>
          <p>Affordable prices & professional work. Highly satisfied.</p>
          <strong>— S. Khan, Restaurant Owner</strong>
        </div>
      </div>
    </section>

    <!-- Pricing / Packages -->
    <section>
      <h2>Simple Packages</h2>
      <p class="sub">Clear packages to get you started. Custom packages available — DM for a custom quote.</p>

      <div class="price-row">
        <div class="price">
          <h3>Basic</h3>
          <div class="amount">₹999</div>
          <div class="list">
            1 Page (Landing) Website<br>
            1 Revision<br>
            WhatsApp Support
          </div>
          <button class="btn" onclick="order('Basic - ₹999')">Order</button>
        </div>

        <div class="price">
          <h3>Standard</h3>
          <div class="amount">₹2499</div>
          <div class="list">
            3 Page Website (Home, About, Contact)<br>
            3 Revisions + Basic SEO<br>
            1 Month Support
          </div>
          <button class="btn" onclick="order('Standard - ₹2499')">Order</button>
        </div>

        <div class="price">
          <h3>Combo</h3>
          <div class="amount">₹3999</div>
          <div class="list">
            Website + Poster Design (1 Poster)<br>
            5 Revisions + WhatsApp Setup
          </div>
          <button class="btn" onclick="order('Combo - ₹3999')">Order Combo</button>
        </div>
      </div>
    </section>

    <!-- Contact -->
    <section id="contact">
      <h2>Get In Touch</h2>
      <p class="sub">Fill the form or message us directly on WhatsApp.</p>

      <div class="contact-row">
        <div>
          <form class="form" onsubmit="return sendWhatsApp(event)">
            <input id="name" type="text" placeholder="Your name" required>
            <input id="business" type="text" placeholder="Business name (optional)">
            <input id="phone" type="text" placeholder="WhatsApp number (with country code, e.g. 91XXXXXXXXXX)" required>
            <select id="service">
              <option value="Poster">Poster</option>
              <option value="Website">Website</option>
              <option value="Combo">Combo</option>
              <option value="Other">Other</option>
            </select>
            <textarea id="message" rows="4" placeholder="Your message"></textarea>
            <button class="btn" type="submit">Send Message</button>
          </form>
        </div>

        <aside>
          <div class="wa-card">
            <h3>Message on WhatsApp</h3>
            <p style="opacity:0.9">Quick response — click to start a chat</p>
            <a href="https://wa.me/918959951152" target="_blank" rel="noopener">Chat Now — +91 8959951152</a>
            <div style="margin-top:12px;font-size:14px;opacity:0.95">Dewas, Madhya Pradesh • Mon–Sat 10:00–19:00</div>
          </div>
        </aside>
      </div>
    </section>

  </div>

  <!-- FOOTER -->
  <footer>
    <div class="fcols">
      <div>
        <strong>MP41 Poster Point</strong>
        <small>Creative studio — posters, websites & printing. Based in Dewas.</small>
      </div>
      <div>
        <strong>Services</strong>
        <small>Graphic Design<br>Web Design<br>Printing<br>Branding</small>
      </div>
      <div>
        <strong>Quick Links</strong>
        <small>Home<br>Portfolio<br>Pricing<br>Contact</small>
      </div>
      <div>
        <strong>Contact</strong>
        <small>WhatsApp: +91 8959951152<br>Instagram: @mp41posterpoint</small>
      </div>
    </div>

    <div style="max-width:var(--maxw);margin:18px auto 0;padding:0 16px;color:#cbd5e1;text-align:center">
      © 2025 MP41 Poster Point — Made with ❤️ in Dewas
    </div>
  </footer>

<script>
  // Open WhatsApp with prefilled message
  function order(packageName){
    const phone = '918959951152'; // international format without '+'
    const text = encodeURIComponent(`Hello MP41, I want to order: ${packageName}. Please contact me.`);
    const url = `https://wa.me/${phone}?text=${text}`;
    window.open(url,'_blank');
  }

  function sendWhatsApp(e){
    e.preventDefault();
    const phone = '918959951152';
    const name = document.getElementById('name').value || '';
    const business = document.getElementById('business').value || '';
    const userPhone = document.getElementById('phone').value || '';
    const service = document.getElementById('service').value || '';
    const msg = document.getElementById('message').value || '';
    const message = `Hi MP41 Poster Point, I am ${name}%0ABusiness: ${business}%0AService: ${service}%0AContact: ${userPhone}%0A${msg}`;
    const url = `https://wa.me/${phone}?text=${encodeURIComponent(message)}`;
    window.open(url,'_blank');
    return false;
  }
</script>

</body>
</html>
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>MP41 Poster Point — Design & Web Studio</title>

  <!-- Google Font: Poppins -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

  <style>
    :root{
      --blue:#0b61ff;
      --accent:#ffcc00;
      --muted:#f7f8fb;
      --dark:#0f1724;
      --radius:10px;
      --maxw:1100px;
      --gap:20px;
    }
    *{box-sizing:border-box}
    body{
      margin:0;font-family:'Poppins',system-ui,-apple-system,Segoe UI,Roboto,"Helvetica Neue",Arial;
      color:#222;background:#fff;line-height:1.5;
    }
    .container{max-width:var(--maxw);margin:0 auto;padding:40px 16px;}
    /* Portfolio hero (already provided by you) */
    .hero{background:linear-gradient(180deg,var(--blue),#1570ff);color:#fff;padding:60px 16px;border-bottom-left-radius:18px;border-bottom-right-radius:18px;}
    .hero .row{display:flex;gap:24px;align-items:center;max-width:var(--maxw);margin:0 auto;}
    .hero h1{font-size:38px;margin:0 0 8px 0;line-height:1;}
    .hero p{margin:0 0 18px 0;opacity:0.95}
    .btn{background:#fff;color:var(--blue);padding:12px 18px;border-radius:8px;font-weight:600;border:none;cursor:pointer;box-shadow:0 6px 18px rgba(11,97,255,0.12)}
    /* BELOW-FOLD SECTIONS */
    section{padding:36px 0}
    h2{font-size:26px;margin:0 0 8px}
    .sub{color:#666;margin-bottom:18px}
    /* Portfolio grid */
    .grid{display:grid;grid-template-columns:repeat(3,1fr);gap:var(--gap)}
    .card{background:#fff;border-radius:12px;overflow:hidden;box-shadow:0 6px 18px rgba(12,20,30,0.04);border:1px solid #eef2f6}
    .card img{width:100%;height:160px;object-fit:cover;display:block}
    .card .meta{padding:12px}
    .view-btn{display:inline-block;margin-top:8px;padding:8px 12px;border-radius:8px;border:1px solid var(--blue);color:var(--blue);font-weight:600;text-decoration:none}
    /* Case study */
    .case{display:flex;gap:20px;align-items:center}
    .case img{width:46%;border-radius:12px;object-fit:cover}
    .case .txt{width:54%}
    /* Testimonials */
    .test-row{display:grid;grid-template-columns:repeat(3,1fr);gap:var(--gap)}
    .test{background:var(--muted);padding:20px;border-radius:12px}
    .stars{color:var(--accent);font-weight:700;margin-bottom:8px}
    /* Pricing */
    .price-row{display:grid;grid-template-columns:repeat(3,1fr);gap:var(--gap);margin-top:8px}
    .price{background:#fff;padding:20px;border-radius:12px;border:1px solid #e9eef6;text-align:center}
    .price h3{margin:0 0 6px}
    .price .amount{font-size:22px;font-weight:700;color:var(--dark);margin:8px 0}
    .price .list{color:#555;font-size:14px;line-height:1.6;text-align:left;margin:12px 0}
    /* Contact */
    .contact-row{display:grid;grid-template-columns:1fr 340px;gap:24px;align-items:start}
    .form input,.form textarea,.form select{width:100%;padding:12px;border-radius:8px;border:1px solid #e6e9ef;margin-bottom:12px;font-size:14px}
    .wa-card{background:linear-gradient(180deg,#25d366,#1fbf4b);color:#fff;padding:20px;border-radius:12px;text-align:center}
    .wa-card a{display:inline-block;margin-top:10px;background:#fff;color:#25d366;padding:10px 16px;border-radius:8px;text-decoration:none;font-weight:600}
    /* Footer */
    footer{background:#0f1724;color:#fff;padding:26px 16px;margin-top:30px}
    footer .fcols{display:grid;grid-template-columns:repeat(4,1fr);gap:20px;max-width:var(--maxw);margin:0 auto}
    footer small{display:block;margin-top:12px;color:#cbd5e1}
    /* Responsive */
    @media(max-width:980px){
      .grid{grid-template-columns:repeat(2,1fr)}
      .test-row{grid-template-columns:repeat(2,1fr)}
      .case{flex-direction:column}
      .hero h1{font-size:30px}
      .contact-row{grid-template-columns:1fr}
      footer .fcols{grid-template-columns:repeat(2,1fr)}
    }
    @media(max-width:620px){
      .grid{grid-template-columns:1fr}
      .test-row{grid-template-columns:1fr}
      .hero .row{flex-direction:column;text-align:center}
      .hero img{width:220px}
    }
  </style>
</head>
<body>

  <!-- HERO (top given earlier) -->
  <section class="hero">
    <div class="row">
      <div style="flex:1;">
        <h1>MP41 Poster Point</h1>
        <p>Creative Graphic Design Studio — Posters, Websites & Printing. We turn ideas into designs and launch them online.</p>
        <button class="btn" onclick="document.getElementById('contact').scrollIntoView({behavior:'smooth'})">Get In Touch</button>
      </div>
      <div style="width:420px;text-align:right;">
        <!-- example graphic -->
        <img src="C:\Users\akdas\OneDrive\Desktop\New folder (3)\ChatGPT_Image_Nov_10__2025__12_50_40_PM-removebg-preview.png" alt="design" style="max-width:100%;border-radius:12px;box-shadow:0 8px 30px rgba(11,97,255,0.12)">
      </div>
    </div>
  </section>

  <div class="container">

    <!-- Portfolio -->
    <section id="portfolio">
      <h2>Portfolio</h2>
      <p class="sub">Take a look at our recent work — posters, banners and websites made for Dewas businesses.</p>

      <div class="grid">
        <div class="card">
          <img src="https://youtube.com/shorts/G9hF4eJdJ30?si=L2uhTFnIxyoUHYpT" alt="Poster 1">
          <div class="meta"><strong>The Fire Creation</strong><div><a class="view-btn" href="#">View Project</a></div></div>
        </div>
        <div class="card">
          <img src="assets/visiting_card.jpg" alt="Visiting card">
          <div class="meta"><strong>Visiting Card Sample</strong><div><a class="view-btn" href="#">View Project</a></div></div>
        </div>
        <div class="card">
          <img src="assets/banner_grocery.jpg" alt="Banner">
          <div class="meta"><strong>QuickBasket Banner</strong><div><a class="view-btn" href="#">View Project</a></div></div>
        </div>

        <div class="card">
          <img src="assets/website_mock.jpg" alt="Website">
          <div class="meta"><strong>Gangster's Gaming Hub</strong><div><a class="view-btn" href="#">View Project</a></div></div>
        </div>
        <div class="card">
          <img src="assets/invite.jpg" alt="Invitation">
          <div class="meta"><strong>Nikaah Invitation</strong><div><a class="view-btn" href="#">View Project</a></div></div>
        </div>
        <div class="card">
          <img src="assets/combo.jpg" alt="Combo">
          <div class="meta"><strong>Poster + Web Combo</strong><div><a class="view-btn" href="#">View Project</a></div></div>
        </div>
      </div>
    </section>

    <!-- Case study -->
    <section>
      <div class="case">
        <img src="assets/case_gaming.jpg" alt="Case study">
        <div class="txt">
          <h2>Case Study — Gangster's Gaming Hub</h2>
          <p class="sub">We designed a conversion-focused landing page and promotional posters. Results: +30% bookings in the first month after launch.</p>
          <a class="btn" href="#">See Full Case</a>
        </div>
      </div>
    </section>

    <!-- Testimonials -->
    <section>
      <h2>Client Love</h2>
      <p class="sub">Short feedback from our customers — trust built from real results.</p>

      <div class="test-row">
        <div class="test">
          <div class="stars">★★★★★</div>
          <p>MP41 ne hamare posters aur website banayi — result zabardast raha. Highly recommended!</p>
          <strong>— Arman, Store Owner</strong>
        </div>

        <div class="test">
          <div class="stars">★★★★★</div>
          <p>Quick delivery aur perfect design — MP41 team bahut helpful hai.</p>
          <strong>— Zeeshan, Event Organizer</strong>
        </div>

        <div class="test">
          <div class="stars">★★★★★</div>
          <p>Affordable prices & professional work. Highly satisfied.</p>
          <strong>— S. Khan, Restaurant Owner</strong>
        </div>
      </div>
    </section>

    <!-- Pricing / Packages -->
    <section>
      <h2>Simple Packages</h2>
      <p class="sub">Clear packages to get you started. Custom packages available — DM for a custom quote.</p>

      <div class="price-row">
        <div class="price">
          <h3>Basic</h3>
          <div class="amount">₹999</div>
          <div class="list">
            1 Page (Landing) Website<br>
            1 Revision<br>
            WhatsApp Support
          </div>
          <button class="btn" onclick="order('Basic - ₹999')">Order</button>
        </div>

        <div class="price">
          <h3>Standard</h3>
          <div class="amount">₹2499</div>
          <div class="list">
            3 Page Website (Home, About, Contact)<br>
            3 Revisions + Basic SEO<br>
            1 Month Support
          </div>
          <button class="btn" onclick="order('Standard - ₹2499')">Order</button>
        </div>

        <div class="price">
          <h3>Combo</h3>
          <div class="amount">₹3999</div>
          <div class="list">
            Website + Poster Design (1 Poster)<br>
            5 Revisions + WhatsApp Setup
          </div>
          <button class="btn" onclick="order('Combo - ₹3999')">Order Combo</button>
        </div>
      </div>
    </section>

    <!-- Contact -->
    <section id="contact">
      <h2>Get In Touch</h2>
      <p class="sub">Fill the form or message us directly on WhatsApp.</p>

      <div class="contact-row">
        <div>
          <form class="form" onsubmit="return sendWhatsApp(event)">
            <input id="name" type="text" placeholder="Your name" required>
            <input id="business" type="text" placeholder="Business name (optional)">
            <input id="phone" type="text" placeholder="WhatsApp number (with country code, e.g. 91XXXXXXXXXX)" required>
            <select id="service">
              <option value="Poster">Poster</option>
              <option value="Website">Website</option>
              <option value="Combo">Combo</option>
              <option value="Other">Other</option>
            </select>
            <textarea id="message" rows="4" placeholder="Your message"></textarea>
            <button class="btn" type="submit">Send Message</button>
          </form>
        </div>

        <aside>
          <div class="wa-card">
            <h3>Message on WhatsApp</h3>
            <p style="opacity:0.9">Quick response — click to start a chat</p>
            <a href="https://wa.me/918959951152" target="_blank" rel="noopener">Chat Now — +91 8959951152</a>
            <div style="margin-top:12px;font-size:14px;opacity:0.95">Dewas, Madhya Pradesh • Mon–Sat 10:00–19:00</div>
          </div>
        </aside>
      </div>
    </section>

  </div>

  <!-- FOOTER -->
  <footer>
    <div class="fcols">
      <div>
        <strong>MP41 Poster Point</strong>
        <small>Creative studio — posters, websites & printing. Based in Dewas.</small>
      </div>
      <div>
        <strong>Services</strong>
        <small>Graphic Design<br>Web Design<br>Printing<br>Branding</small>
      </div>
      <div>
        <strong>Quick Links</strong>
        <small>Home<br>Portfolio<br>Pricing<br>Contact</small>
      </div>
      <div>
        <strong>Contact</strong>
        <small>WhatsApp: +91 8959951152<br>Instagram: @mp41posterpoint</small>
      </div>
    </div>

    <div style="max-width:var(--maxw);margin:18px auto 0;padding:0 16px;color:#cbd5e1;text-align:center">
      © 2025 MP41 Poster Point — Made with ❤️ in Dewas
    </div>
  </footer>

<script>
  // Open WhatsApp with prefilled message
  function order(packageName){
    const phone = '918959951152'; // international format without '+'
    const text = encodeURIComponent(`Hello MP41, I want to order: ${packageName}. Please contact me.`);
    const url = `https://wa.me/${phone}?text=${text}`;
    window.open(url,'_blank');
  }

  function sendWhatsApp(e){
    e.preventDefault();
    const phone = '918959951152';
    const name = document.getElementById('name').value || '';
    const business = document.getElementById('business').value || '';
    const userPhone = document.getElementById('phone').value || '';
    const service = document.getElementById('service').value || '';
    const msg = document.getElementById('message').value || '';
    const message = `Hi MP41 Poster Point, I am ${name}%0ABusiness: ${business}%0AService: ${service}%0AContact: ${userPhone}%0A${msg}`;
    const url = `https://wa.me/${phone}?text=${encodeURIComponent(message)}`;
    window.open(url,'_blank');
    return false;
  }
</script>

</body>
</html>
