<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="theme-color" content="#111827">
  <title>iPhone Salhi | هواتف وإكسسوارات في برشلونة</title>

  <style>
    :root {
      --dark: #111827;
      --muted: #64748b;
      --purple: #7657f6;
      --pink: #ed72b5;
      --light: #f7f7fb;
      --white: #fff;
      --border: #ececf3;
      --green: #20b866;
    }

    * { box-sizing: border-box; }

    body {
      margin: 0;
      color: var(--dark);
      background: var(--light);
      font-family: Arial, Helvetica, sans-serif;
    }

    a { color: inherit; text-decoration: none; }

    .container {
      width: min(1120px, 92%);
      margin: auto;
    }

    header {
      background: rgba(255,255,255,.94);
      border-bottom: 1px solid var(--border);
      position: sticky;
      top: 0;
      z-index: 10;
      backdrop-filter: blur(12px);
    }

    .nav {
      min-height: 72px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 20px;
    }

    .brand {
      display: flex;
      align-items: center;
      gap: 10px;
      font-size: 20px;
      font-weight: 800;
    }

    .brand-mark {
      width: 42px;
      height: 42px;
      display: grid;
      place-items: center;
      border-radius: 14px;
      color: white;
      background: linear-gradient(135deg, var(--purple), var(--pink));
    }

    .nav-links {
      display: flex;
      align-items: center;
      gap: 24px;
      color: #475569;
      font-size: 14px;
    }

    .button {
      display: inline-flex;
      justify-content: center;
      align-items: center;
      gap: 8px;
      border: 0;
      border-radius: 12px;
      padding: 12px 18px;
      color: white;
      background: var(--purple);
      font-weight: 700;
      cursor: pointer;
    }

    .hero {
      padding: 72px 0 56px;
      overflow: hidden;
      background:
        radial-gradient(circle at 15% 15%, #f5d9ef 0, transparent 30%),
        radial-gradient(circle at 90% 60%, #ddd9ff 0, transparent 30%),
        linear-gradient(135deg, #fff, #f8f6ff);
    }

    .hero-grid {
      display: grid;
      grid-template-columns: 1.15fr .85fr;
      align-items: center;
      gap: 42px;
    }

    .tag {
      display: inline-block;
      color: #6548dc;
      background: #eeeaff;
      padding: 8px 13px;
      border-radius: 99px;
      font-size: 13px;
      font-weight: 700;
    }

    h1 {
      font-size: clamp(36px, 5vw, 58px);
      line-height: 1.15;
      margin: 18px 0;
      letter-spacing: -1.5px;
    }

    .hero p {
      max-width: 560px;
      color: var(--muted);
      font-size: 17px;
      line-height: 1.9;
    }

    .hero-actions {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
      margin-top: 25px;
    }

    .button.secondary {
      color: var(--dark);
      background: white;
      border: 1px solid var(--border);
    }

    .hero-art {
      min-height: 340px;
      display: grid;
      place-items: center;
      position: relative;
    }

    .glow {
      position: absolute;
      width: 290px;
      height: 290px;
      border-radius: 50%;
      background: linear-gradient(135deg, #d8ccff, #ffd8ef);
      filter: blur(2px);
    }

    .phone {
      width: 175px;
      height: 320px;
      border: 8px solid #222536;
      border-radius: 35px;
      background: linear-gradient(145deg, #d9cfff, #f9ddec 48%, #9d8aff);
      box-shadow: 0 24px 55px #4d397b44;
      position: relative;
      z-index: 1;
      transform: rotate(-8deg);
    }

    .phone::before {
      content: "";
      position: absolute;
      top: 9px;
      left: 50%;
      transform: translateX(-50%);
      width: 70px;
      height: 18px;
      border-radius: 20px;
      background: #222536;
    }

    .camera {
      position: absolute;
      top: 18px;
      right: 12px;
      display: grid;
      grid-template-columns: repeat(2, 17px);
      gap: 5px;
      padding: 7px;
      background: #d7d0e9;
      border-radius: 14px;
    }

    .camera i {
      display: block;
      width: 17px;
      height: 17px;
      border-radius: 50%;
      background: #303044;
      border: 3px solid #8e87a1;
    }

    .phone-label {
      position: absolute;
      bottom: 24px;
      left: 0;
      right: 0;
      text-align: center;
      color: #fff;
      font-weight: 800;
      text-shadow: 0 2px 8px #4b3888;
    }

    .section { padding: 62px 0; }

    .section-heading {
      display: flex;
      align-items: end;
      justify-content: space-between;
      gap: 20px;
      margin-bottom: 25px;
    }

    .section-heading h2 {
      margin: 0 0 8px;
      font-size: clamp(26px, 3vw, 36px);
    }

    .section-heading p {
      margin: 0;
      color: var(--muted);
      line-height: 1.7;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 18px;
    }

    .card {
      background: var(--white);
      border: 1px solid var(--border);
      border-radius: 20px;
      overflow: hidden;
      box-shadow: 0 8px 24px #15152a08;
    }

    .product-art {
      height: 190px;
      display: grid;
      place-items: center;
      background: linear-gradient(135deg, #f0edff, #fff0f8);
    }

    .mini-phone {
      width: 82px;
      height: 145px;
      border: 5px solid #252536;
      border-radius: 19px;
      background: linear-gradient(145deg, #a999ff, #f5aedd);
      position: relative;
      box-shadow: 0 12px 22px #54427a33;
    }

    .mini-phone::before {
      content: "";
      position: absolute;
      top: 5px;
      left: 50%;
      transform: translateX(-50%);
      width: 31px;
      height: 9px;
      background: #252536;
      border-radius: 10px;
    }

    .mini-phone.blue { background: linear-gradient(145deg, #aad8ff, #536ce9); }
    .mini-phone.black { background: linear-gradient(145deg, #55566a, #111827); }
    .mini-phone.green { background: linear-gradient(145deg, #b6f1d0, #57ac91); }

    .case-swatch {
      width: 92px;
      height: 142px;
      border: 7px solid #fff;
      outline: 2px solid #d5d3df;
      border-radius: 24px;
      background: linear-gradient(145deg, #ffbad9, #9f8aff);
      box-shadow: 0 12px 22px #54427a22;
      position: relative;
    }

    .case-swatch.blue { background: linear-gradient(145deg, #b8e3ff, #6d8dff); }
    .case-swatch.green { background: linear-gradient(145deg, #c8f2d5, #67bb9a); }

    .case-swatch::before {
      content: "● ●";
      position: absolute;
      top: 9px;
      right: 9px;
      color: #343247;
      font-size: 12px;
      line-height: 1.2;
      background: #ffffff99;
      padding: 5px;
      border-radius: 9px;
    }

    .card-content { padding: 18px; }

    .card h3 { margin: 0 0 8px; font-size: 18px; }

    .card p {
      color: var(--muted);
      margin: 0 0 16px;
      font-size: 14px;
      line-height: 1.6;
    }

    .card-bottom {
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 10px;
    }

    .price { font-weight: 800; font-size: 20px; }
    .price small { color: var(--muted); font-size: 12px; font-weight: 400; }

    .small-button {
      border: 0;
      border-radius: 10px;
      padding: 10px 12px;
      color: white;
      background: var(--dark);
      font-weight: 700;
      cursor: pointer;
    }

    .info-strip {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 14px;
      margin-top: 28px;
    }

    .info-box {
      padding: 20px;
      border: 1px solid var(--border);
      border-radius: 16px;
      background: white;
      text-align: center;
    }

    .info-box strong { display: block; margin-bottom: 7px; }
    .info-box span { color: var(--muted); font-size: 14px; }

    .contact {
      padding: 36px;
      border-radius: 24px;
      color: white;
      background: linear-gradient(135deg, #252342, #7154e8);
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 24px;
    }

    .contact h2 { margin: 0 0 10px; }
    .contact p { margin: 0; color: #e2defe; line-height: 1.7; }
    .contact .button { background: var(--green); white-space: nowrap; }

    footer {
      padding: 26px 0;
      color: var(--muted);
      font-size: 13px;
      text-align: center;
    }

    @media (max-width: 760px) {
      .nav { min-height: 64px; }
      .nav-links { display: none; }
      .nav > .button { padding: 10px 12px; font-size: 13px; }
      .hero { padding: 48px 0 30px; }
      .hero-grid { grid-template-columns: 1fr; text-align: center; gap: 8px; }
      .hero p { margin-inline: auto; font-size: 15px; }
      .hero-actions { justify-content: center; }
      .hero-art { min-height: 290px; }
      .phone { transform: rotate(-5deg) scale(.86); }
      .section { padding: 44px 0; }
      .section-heading { align-items: start; flex-direction: column; }
      .grid { grid-template-columns: 1fr; }
      .product-art { height: 175px; }
      .info-strip { grid-template-columns: 1fr; }
      .contact { flex-direction: column; align-items: stretch; text-align: center; padding: 27px 20px; }
    }

    @media (min-width: 761px) and (max-width: 1000px) {
      .grid { grid-template-columns: repeat(2, 1fr); }
    }
  </style>
</head>

<body>
  <header>
    <div class="container nav">
      <a class="brand" href="#">
        <span class="brand-mark">S</span>
        <span>iPhone Salhi</span>
      </a>

      <nav class="nav-links">
        <a href="#phones">الهواتف</a>
        <a href="#cases">الكفرات</a>
        <a href="#delivery">التوصيل</a>
        <a href="#contact">تواصل معنا</a>
      </nav>

      <a class="button" href="#phones">شوف المنتجات</a>
    </div>
  </header>

  <main>
    <section class="hero">
      <div class="container hero-grid">
        <div>
          <span class="tag">متجرك فبرشلونة 📍</span>
          <h1>اختار iPhone ديالك<br>باللون اللي كيعجبك</h1>
          <p>
            هواتف وإكسسوارات iPhone بتصميم أنيق. توصيل داخل برشلونة،
            وخدمة الزبناء مباشرة عبر واتساب.
          </p>
          <div class="hero-actions">
            <a class="button" href="#phones">تسوق الهواتف</a>
            <a class="button secondary" href="#cases">شوف الكفرات</a>
          </div>
        </div>

        <div class="hero-art" aria-label="رسم توضيحي لهاتف">
          <div class="glow"></div>
          <div class="phone">
            <div class="camera"><i></i><i></i><i></i></div>
            <div class="phone-label">iPhone Salhi</div>
          </div>
        </div>
      </div>
    </section>

    <section class="section" id="phones">
      <div class="container">
        <div class="section-heading">
          <div>
            <h2>هواتف iPhone</h2>
            <p>اختار الموديل، وتواصل معنا باش تتأكد من التوفر والألوان.</p>
          </div>
        </div>

        <div class="grid">
          <article class="card">
            <div class="product-art"><div class="mini-phone"></div></div>
            <div class="card-content">
              <h3>iPhone 18 Pro</h3>
              <p>تصميم أنيق وألوان مختلفة. سَوّلنا على التوفر.</p>
              <div class="card-bottom">
                <span class="price">1,111€</span>
                <a class="small-button" href="https://wa.me/34666784846?text=Salam%2C%20bghit%20n3ref%20wach%20iPhone%2018%20Pro%20mazal%20mowjod">
                  طلب عبر واتساب
                </a>
              </div>
            </div>
          </article>

          <article class="card">
            <div class="product-art"><div class="mini-phone blue"></div></div>
            <div class="card-content">
              <h3>iPhone 16</h3>
              <p>ألوان متعددة. تواصل معنا لمعرفة الثمن والتوفر.</p>
              <div class="card-bottom">
                <span class="price">سَوّل على الثمن</span>
                <a class="small-button" href="https://wa.me/34666784846?text=Salam%2C%20bghit%20taman%20iPhone%2016">
                  سَوّلنا
                </a>
              </div>
            </div>
          </article>

          <article class="card">
            <div class="product-art"><div class="mini-phone black"></div></div>
            <div class="card-content">
              <h3>iPhone 15</h3>
              <p>متوفر حسب اللون والمخزون. سَوّلنا على التفاصيل.</p>
              <div class="card-bottom">
                <span class="price">سَوّل على الثمن</span>
                <a class="small-button" href="https://wa.me/34666784846?text=Salam%2C%20bghit%20taman%20iPhone%2015">
                  سَوّلنا
                </a>
              </div>
            </div>
          </article>

          <article class="card">
            <div class="product-art"><div class="mini-phone green"></div></div>
            <div class="card-content">
              <h3>iPhone 15 العادي</h3>
              <p>ألوان متنوعة. راسلنا باش تعرف الثمن والتوفر.</p>
              <div class="card-bottom">
                <span class="price">سَوّل على الثمن</span>
                <a class="small-button" href="https://wa.me/34666784846?text=Salam%2C%20bghit%20taman%20iPhone%2015%20normal">
                  سَوّلنا
                </a>
              </div>
            </div>
          </article>
        </div>
      </div>
    </section>

    <section class="section" id="cases">
      <div class="container">
        <div class="section-heading">
          <div>
            <h2>كفرات وإكسسوارات</h2>
            <p>اختار اللون والتصميم المناسب للهاتف ديالك.</p>
          </div>
        </div>

        <div class="grid">
          <article class="card">
            <div class="product-art"><div class="case-swatch"></div></div>
            <div class="card-content">
              <h3>كفر وردي / بنفسجي</h3>
              <p>تصميم أنيق وحماية يومية. الثمن كيتحدد حسب الموديل.</p>
              <div class="card-bottom">
                <span class="price">من 5€</span>
                <a class="small-button" href="https://wa.me/34666784846?text=Salam%2C%20bghit%20kefr%20rose%20ou%20violet">
                  طلب عبر واتساب
                </a>
              </div>
            </div>
          </article>

          <article class="card">
            <div class="product-art"><div class="case-swatch blue"></div></div>
            <div class="card-content">
              <h3>كفر أزرق</h3>
              <p>ألوان زاهية وموديلات مختلفة لـ iPhone.</p>
              <div class="card-bottom">
                <span class="price">من 5€</span>
                <a class="small-button" href="https://wa.me/34666784846?text=Salam%2C%20bghit%20kefr%20blue">
                  طلب عبر واتساب
                </a>
              </div>
            </div>
          </article>

          <article class="card">
            <div class="product-art"><div class="case-swatch green"></div></div>
            <div class="card-content">
              <h3>كفر أخضر</h3>
              <p>اختار الموديل واللون اللي بغيتي.</p>
              <div class="card-bottom">
                <span class="price">حتى 15€</span>
                <a class="small-button" href="https://wa.me/34666784846?text=Salam%2C%20bghit%20kefr%20green">
                  طلب عبر واتساب
                </a>
              </div>
            </div>
          </article>
        </div>
      </div>
    </section>

    <section class="section" id="delivery">
      <div class="container">
        <div class="info-strip">
          <div class="info-box">
            <strong>📍 برشلونة</strong>
            <span>التوصيل داخل برشلونة</span>
          </div>
          <div class="info-box">
            <strong>🚚 التوصيل: 7€</strong>
            <span>ثمن التوصيل داخل برشلونة</span>
          </div>
          <div class="info-box">
            <strong>🎨 ألوان متنوعة</strong>
            <span>سَوّلنا على الألوان المتوفرة</span>
          </div>
        </div>
      </div>
    </section>

    <section class="section" id="contact">
      <div class="container">
        <div class="contact">
          <div>
            <h2>بغيتي تطلب ولا تسول؟</h2>
            <p>تواصل معنا عبر واتساب أو البريد الإلكتروني.</p>
          </div>
          <a class="button" href="https://wa.me/34666784846?text=Salam%2C%20bghit%20n3ref%20details%20dyal%20lproduits">
            تواصل عبر واتساب
          </a>
        </div>

        <p style="text-align:center; margin-top:20px; color:#64748b">
          البريد الإلكتروني:
          <a href="mailto:mohammedsalhi4000@gmail.com">
            mohammedsalhi4000@gmail.com
          </a>
        </p>
      </div>
    </section>
  </main>

  <footer>
    © 2026 iPhone Salhi — برشلونة
  </footer>
</body>
</html>
