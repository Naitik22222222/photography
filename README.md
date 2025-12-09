<!DOCTYPE html>
<html lang="gu">
<head>
  <meta charset="UTF-8" />
  <title>Wedding Photographer - [Your Name]</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <style>
    * { box-sizing: border-box; }
    body { margin: 0; font-family: Arial, sans-serif; line-height: 1.6; background:#fffaf8; color:#333; }
    header { padding: 80px 20px 60px; text-align: center; background: linear-gradient(to bottom, #ffe5ec, #fffaf8); }
    header h1 { font-size: 2.2rem; margin-bottom: 10px; }
    header p { max-width: 600px; margin: 10px auto; }
    .btn {
      display: inline-block; padding: 10px 22px; text-decoration: none;
      border-radius: 25px; margin: 10px 5px; border: 1px solid #f4b5c5;
      font-size: 0.9rem;
    }
    .btn-primary { background:#f4b5c5; color:#442222; }
    .btn-outline { background:transparent; color:#442222; }
    section { padding: 50px 20px; max-width: 1060px; margin: auto; }
    h2 { margin-bottom: 10px; font-size: 1.6rem; }
    h3 { margin-top: 0; }
    .grid { display: grid; gap: 20px; }
    @media (min-width: 768px) {
      .grid-3 { grid-template-columns: repeat(3, 1fr); }
      .grid-2 { grid-template-columns: repeat(2, 1fr); }
    }
    .card {
      padding: 20px; border-radius: 12px; background:#ffffff;
      box-shadow: 0 4px 10px rgba(0,0,0,0.04);
    }
    ul { padding-left:18px; }
    .hero-images {
      margin-top: 20px;
      display:flex;
      justify-content:center;
      gap:10px;
      flex-wrap:wrap;
    }
    .hero-images div {
      width:130px; height:90px; border-radius:12px;
      background:#ddd; display:flex; align-items:center; justify-content:center;
      font-size:0.8rem;
    }
    .badge-row{
      display:flex; gap:10px; flex-wrap:wrap; justify-content:center; margin-top:15px;
    }
    .badge{
      padding:6px 12px; border-radius:20px; font-size:0.75rem; background:#fff; border:1px solid #f4b5c5;
    }
    form input, form textarea {
      width: 100%; padding: 10px; margin-bottom: 10px;
      border-radius: 6px; border: 1px solid #ddd; font-family: inherit;
    }
    form button {
      padding: 10px 20px; border-radius: 20px; border:none;
      background:#f4b5c5; color:#442222; cursor:pointer;
    }
    footer {
      text-align: center; padding: 20px; font-size: 0.85rem; background:#fff0f4;
    }
    nav {
      position: sticky; top:0; z-index:10;
      background:#fff8f9; padding:8px 16px; box-shadow: 0 2px 6px rgba(0,0,0,0.04);
    }
    nav .nav-inner{
      max-width:1060px; margin:auto; display:flex; justify-content:space-between; align-items:center;
    }
    nav a{ text-decoration:none; font-size:0.9rem; margin-left:12px; color:#444; }
    nav a:hover{ text-decoration:underline; }
  </style>
</head>
<body>

  <!-- TOP NAV -->
  <nav>
    <div class="nav-inner">
      <div><strong>[Your Name]</strong> • Wedding Photographer</div>
      <div>
        <a href="#about">About</a>
        <a href="#packages">Packages</a>
        <a href="#gallery">Gallery</a>
        <a href="#contact">Contact</a>
      </div>
    </div>
  </nav>

  <!-- HERO -->
  <header id="home">
    <h1>Candid &amp; Timeless Wedding Photography</h1>
    <p>
      Hi, I’m <strong>[Your Name]</strong>, wedding photographer based in <strong>[City]</strong>.  
      હું candid moments, real emotions અને natural expressions capture કરું છું, જેથી તમારાં લગ્નની યાદો વર્ષો સુધી fresh રહે.
    </p>
    <a href="#gallery" class="btn btn-primary">View My Work</a>
    <a href="#contact" class="btn btn-outline">Book Your Date</a>

    <div class="badge-row">
      <span class="badge">Weddings</span>
      <span class="badge">Pre-wedding</span>
      <span class="badge">Haldi &amp; Mehendi</span>
      <span class="badge">Candid Stories</span>
    </div>

    <div class="hero-images">
      <div>Hero Photo 1</div>
      <div>Hero Photo 2</div>
    </div>
  </header>

  <!-- ABOUT -->
  <section id="about">
    <h2>About Me / મારા વિશે</h2>
    <p>
      હું <strong>[Your Name]</strong>, છેલ્લા <strong>[X વર્ષથી]</strong> weddings, pre-wedding shoots અને family events cover કરું છું.  
      મારી style candid + classic mix છે – no over posing, no fake smiles, બસ real moments.
    </p>
    <p>
      મારા માટે photography માત્ર કામ નથી, but તમારા પરિવારની story capture કરવાનો એક સુંદર રસ્તો છે – જેથી years પછી પણ તમે આ દિવસને ફરીથી feel કરી શકો.
    </p>
    <ul>
      <li>Candid &amp; Traditional Wedding Photography</li>
      <li>Pre-Wedding Photoshoot</li>
      <li>Haldi, Mehendi, Sangeet, Reception Coverage</li>
      <li>4K Wedding Films &amp; Teasers</li>
      <li>Premium Wedding Albums</li>
    </ul>
  </section>

  <!-- PACKAGES -->
  <section id="packages">
    <h2>Packages / સેવાઓ</h2>
    <div class="grid grid-3">
      <div class="card">
        <h3>Classic Wedding Package</h3>
        <p><em>Small &amp; sweet weddings માટે perfect.</em></p>
        <ul>
          <li>1 day coverage (main wedding day)</li>
          <li>1 photographer</li>
          <li>200+ edited photos</li>
          <li>Online gallery share</li>
          <li>Delivery: 3–4 weeks</li>
        </ul>
        <p><strong>Starting from ₹[amount]</strong></p>
      </div>
      <div class="card">
        <h3>Premium Wedding Package</h3>
        <p><em>Mehendi + Wedding + Sangeet coverage માટે ideal.</em></p>
        <ul>
          <li>2 days coverage</li>
          <li>2 photographers + 1 videographer</li>
          <li>400+ edited photos</li>
          <li>3–5 min highlight wedding film</li>
          <li>1 premium photo album</li>
        </ul>
        <p><strong>Starting from ₹[amount]</strong></p>
      </div>
      <div class="card">
        <h3>Royal Wedding Experience</h3>
        <p><em>Big fat / Destination weddings માટે.</em></p>
        <ul>
          <li>3–4 days full coverage</li>
          <li>Multi photographer &amp; videographer team</li>
          <li>Drone coverage (venue permission પર depend)</li>
          <li>Full wedding film + trailer</li>
          <li>2–3 premium albums &amp; box set</li>
        </ul>
        <p><strong>Custom quote – based on location &amp; dates</strong></p>
      </div>
    </div>
    <p>દરેક લગ્ન અલગ હોય છે, budget અને requirement મુજબ custom package પણ available છે.</p>
  </section>

  <!-- GALLERY -->
  <section id="gallery">
    <h2>Gallery / મારી કામગરી</h2>
    <p>
      અહીં કેટલાક favourite moments છે – દરેક ફોટો એક અલગ story કહે છે.  
      Scroll કરો અને તમારી dream wedding imagination કરો.
    </p>
    <div class="grid grid-3">
      <div class="card">
        <strong>Weddings</strong>
        <p>Riya &amp; Arjun – Jaipur Destination Wedding</p>
        <!-- <img src="wedding1.jpg" alt="Wedding" style="width:100%;border-radius:8px;"> -->
      </div>
      <div class="card">
        <strong>Pre-Wedding</strong>
        <p>Ananya &amp; Kabir – Sunset Pre-Wedding Shoot</p>
      </div>
      <div class="card">
        <strong>Haldi &amp; Mehendi</strong>
        <p>Fun, masti &amp; yellow vibes – Mumbai</p>
      </div>
    </div>
  </section>

  <!-- TESTIMONIALS -->
  <section id="testimonials">
    <h2>Client Love / તેઓ શું કહે છે</h2>
    <div class="grid grid-2">
      <div class="card">
        <p><strong>Riya &amp; Arjun</strong></p>
        <p>“અમારી wedding photos જોઈને literally બધાંએ પૂછ્યું – ‘Photographer કોણ હતો?’ દરેક emotion capture થયું છે – હાસ્ય, આનંદ, આંસુ બધું. Thank you so much!”</p>
      </div>
      <div class="card">
        <p><strong>Neha &amp; Kunal</strong></p>
        <p>“ખૂબજ calm, polite અને professional. અમારી family સાથે perfectly blend થઈ ગયા, જેથી કોઇ awkward feel ન થયું. Album absolutely stunning છે.”</p>
      </div>
    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact">
    <h2>Contact / Book Your Date</h2>
    <p>
      તમારી wedding date block કરવા માટે નીચે details fill કરો અથવા direct call / WhatsApp કરો.  
      I’d love to hear about your big day!
    </p>
    <p><strong>Based in:</strong> [City, India]</p>
    <p><strong>Phone / WhatsApp:</strong> [Your Phone Number]</p>
    <p><strong>Email:</strong> [youremail@example.com]</p>
    <p><strong>Instagram:</strong> @[yourhandle]</p>

    <form>
      <input type="text" placeholder="Name / નામ" required />
      <input type="text" placeholder="Wedding Date / લગ્નની તારીખ" />
      <input type="text" placeholder="City / Venue" />
      <textarea placeholder="Tell me about your wedding / તમારા લગ્ન વિશે થોડું લખો" rows="4"></textarea>
      <button type="submit">Send Enquiry</button>
    </form>
  </section>

  <!-- FOOTER -->
  <footer>
    &copy; 2025 [Your Name] · Wedding Photographer · All rights reserved.
  </footer>

</body>
</html>
