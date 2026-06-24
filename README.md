<!DOCTYPE html>
<html lang="et">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="Teesi ja Henri pulmaleht – info pulmapäeva kohta ja ühine Google Photos pulmaalbum." />
  <title>Teesi & Henri pulm</title>

  <!-- Parisienne font -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Parisienne&family=Cormorant+Garamond:wght@400;500;600&family=Montserrat:wght@300;400;500;600&display=swap" rel="stylesheet">

  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header class="topbar">
    <a href="#avaleht" class="nav-logo">T & H</a>
    <nav>
      <a href="#info">Info</a>
      <a href="#paevakava">Päevakava</a>
      <a href="#pildid">Pildid</a>
      <a href="#kingitus">Kingitus</a>
    </nav>
  </header>

  <main>
    <section class="hero" id="avaleht">
      <div class="hero-inner">
        <img class="couple-logo" src="assets/teesi-henri-logo.png" alt="Teesi ja Henri logo" />

        <p class="eyebrow">Olete kutsutud meie pulmapäevale</p>
        <h1>Teesi & Henri</h1>
        <p class="date-line">22. august 2026 · Viinistu Kunstimuuseum</p>

        <p class="lead">
          Meil on väga hea meel tähistada seda päeva koos teiega.
          Siit lehelt leiate kogu olulise info pulmapäeva kohta ning lingi meie ühisesse pulmaalbumisse.
        </p>

        <div class="hero-actions">
          <a class="button primary" href="#pildid">Lisa pildid albumisse</a>
          <a class="button secondary" href="#info">Vaata infot</a>
        </div>
      </div>
    </section>

    <section class="section intro-section">
      <p class="script-title">Kallid külalised</p>
      <p>
        Aitäh, et olete osa meie loost. Palume teil pulmapäeval jäädvustada hetki,
        mida meie ise võib-olla ei märkagi — naeratusi, tantsu, väikeseid vahehetki ja kõike seda,
        mis teeb selle päeva päriselt meie päevaks.
      </p>
    </section>

    <section class="section cards-section" id="info">
      <div class="section-heading">
        <p class="small-label">Pulmapäeva info</p>
        <h2>Oluline teada</h2>
      </div>

      <div class="info-grid">
        <article class="info-card">
          <span class="icon">01</span>
          <h3>Asukoht</h3>
          <p>Viinistu Kunstimuuseum<br />Viinistu, Harjumaa</p>
        </article>

        <article class="info-card">
          <span class="icon">02</span>
          <h3>Algus</h3>
          <p>Kogunemine kell 15:30<br />Tseremoonia kell 16:00</p>
        </article>

        <article class="info-card">
          <span class="icon">03</span>
          <h3>Dresscode</h3>
          <p>Pidulik, suvine ja elegantne. Toonid võivad olla pehmed, mereäärsed ja romantilised.</p>
        </article>

        <article class="info-card">
          <span class="icon">04</span>
          <h3>Majutus</h3>
          <p>Majutus on organiseeritud pruutpaari poolt. Täpsem info edastatakse külalistele eraldi.</p>
        </article>
      </div>
    </section>

    <section class="section timeline-section" id="paevakava">
      <div class="section-heading">
        <p class="small-label">Päevakava</p>
        <h2>Meie pulmapäev</h2>
      </div>

      <div class="timeline">
        <div class="timeline-item"><span>15:30</span><p>Kogunemine</p></div>
        <div class="timeline-item"><span>16:00</span><p>Tseremoonia</p></div>
        <div class="timeline-item"><span>16:45</span><p>Õnnesoovid ja pildistamine</p></div>
        <div class="timeline-item"><span>18:00</span><p>Õhtusöök</p></div>
        <div class="timeline-item"><span>19:30</span><p>Bänd, tants ja trall</p></div>
        <div class="timeline-item"><span>22:30</span><p>Pulmatort</p></div>
        <div class="timeline-item"><span>09:00–11:00</span><p>Hommikusöök</p></div>
        <div class="timeline-item"><span>12:00</span><p>Kojusõit</p></div>
      </div>
    </section>

    <section class="section photos-section" id="pildid">
      <div class="photo-card">
        <div>
          <p class="small-label">Pulmaalbum</p>
          <h2>Jaga meiega oma pilte</h2>
          <p>
            Skanni QR-kood või vajuta nupule ja lisa oma fotod ning videod meie ühisesse
            Google Photos pulmaalbumisse. Kõige armsamad hetked on tihti just külaliste telefonides.
          </p>

          <a class="button primary" href="https://photos.app.goo.gl/Ma2B7o86AwjDaia17" target="_blank" rel="noopener">
            Ava Google Photos album
          </a>

          <p class="note">
            Kui lisamine ei avane kohe, kontrolli, et oled Google’i kontoga sisse logitud.
          </p>
        </div>

        <div class="qr-box">
          <img src="assets/google-photos-qr.png" alt="QR-kood Google Photos pulmaalbumisse" />
          <p>Skanni ja lisa pildid</p>
        </div>
      </div>
    </section>

    <section class="section gift-section" id="kingitus">
      <div class="section-heading">
        <p class="small-label">Kingitus</p>
        <h2>Meie suurim kingitus on teie kohalolu</h2>
      </div>
      <p>
        Kui soovite meid siiski kingitusega rõõmustada, mahub see kõige paremini ümbrikusse.
        Üllatused ja erisoovid palume koordineerida pulmaisaga.
      </p>
    </section>
  </main>

  <footer>
    <p class="footer-script">Kohtumiseni pulmas</p>
    <p>Teesi & Henri · 22.08.2026</p>
  </footer>
</body>
</html>
