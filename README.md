<title>محمد أحمد</title>
<meta name="claude:viewport-fit-sides" content="cover">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=IBM+Plex+Sans+Arabic:wght@400;500;600&family=Reem+Kufi:wght@500;700&display=swap" rel="stylesheet">
<style>
/* Layout: RTL. Sticky header, hero = text + identity card, three brand cards, one dark contact panel, footer.
   Replace the name "محمد أحمد" and the monogram letter "م" with your own. */
:root {
  --bg: #F1F3F8;
  --surface: #FFFFFF;
  --fg: #12151F;
  --muted: #586074;
  --line: #DADFEA;
  --accent: #0F766E;
  --on-accent: #FFFFFF;
  --wa: #25D366;
  --on-wa: #062B16;
  --panel: #12151F;
  --on-panel: #F1F3F8;
  --panel-muted: #A9B0C2;
  --panel-line: #394258;
  --header-bg: #F1F3F8;
  --shadow: 0 1px 2px rgba(18, 21, 31, .06), 0 14px 34px -14px rgba(18, 21, 31, .22);
  --font-display: "Reem Kufi", "Segoe UI", Tahoma, sans-serif;
  --font-body: "IBM Plex Sans Arabic", "Segoe UI", Tahoma, sans-serif;
}
@media (prefers-color-scheme: dark) {
  :root:not([data-theme="light"]) {
    --bg: #0D1118;
    --surface: #151A24;
    --fg: #EEF0F6;
    --muted: #98A1B5;
    --line: #252C3B;
    --accent: #2DD4BF;
    --on-accent: #04201C;
    --panel: #1B2332;
    --on-panel: #EEF0F6;
    --panel-muted: #A3ACC0;
    --panel-line: #36405A;
    --header-bg: #0D1118;
    --shadow: 0 1px 2px rgba(0, 0, 0, .4), 0 14px 34px -14px rgba(0, 0, 0, .6);
    color-scheme: dark;
  }
}
:root[data-theme="dark"] {
  --bg: #0D1118;
  --surface: #151A24;
  --fg: #EEF0F6;
  --muted: #98A1B5;
  --line: #252C3B;
  --accent: #2DD4BF;
  --on-accent: #04201C;
  --panel: #1B2332;
  --on-panel: #EEF0F6;
  --panel-muted: #A3ACC0;
  --panel-line: #36405A;
  --header-bg: #0D1118;
  --shadow: 0 1px 2px rgba(0, 0, 0, .4), 0 14px 34px -14px rgba(0, 0, 0, .6);
  color-scheme: dark;
}

*, *::before, *::after { box-sizing: border-box; }
html { scroll-behavior: smooth; }
body {
  direction: rtl;
  background: var(--bg);
  color: var(--fg);
  font-family: var(--font-body);
  font-size: 17px;
  line-height: 1.75;
  -webkit-font-smoothing: antialiased;
}
body::before {
  content: "";
  position: fixed;
  inset: 0 0 auto;
  height: env(safe-area-inset-top, 0px);
  z-index: 10;
  background: var(--header-bg);
}
a { color: inherit; text-decoration: none; }
h1, h2, h3, p { margin: 0; }
h1, h2, h3 { font-family: var(--font-display); text-wrap: balance; line-height: 1.3; }
:focus-visible { outline: 3px solid var(--accent); outline-offset: 3px; border-radius: 8px; }

.wrap {
  width: 100%;
  max-width: 1120px;
  margin-inline: auto;
  padding-left: max(16px, env(safe-area-inset-left, 0px));
  padding-right: max(16px, env(safe-area-inset-right, 0px));
}
.ico {
  width: 24px; height: 24px; flex: none;
  fill: none; stroke: currentColor; stroke-width: 1.8;
  stroke-linecap: round; stroke-linejoin: round;
}
.ltr { direction: ltr; unicode-bidi: isolate; font-variant-numeric: tabular-nums; }

/* Header */
.site-header {
  position: sticky;
  top: env(safe-area-inset-top, 0px);
  z-index: 20;
  background: var(--header-bg);
  border-bottom: 1px solid var(--line);
}
.bar { display: flex; align-items: center; justify-content: space-between; gap: 12px; min-height: 68px; }
.brand { display: flex; align-items: center; gap: 12px; min-width: 0; }
.mark {
  width: 42px; height: 42px; flex: none;
  display: grid; place-items: center;
  background: var(--accent); color: var(--on-accent);
  border-radius: 13px 13px 13px 4px;
  font-family: var(--font-display); font-weight: 700; font-size: 1.5rem; line-height: 1;
  padding-bottom: 4px;
}
.brand-name { font-family: var(--font-display); font-weight: 700; font-size: 1.3rem; white-space: nowrap; }
.nav { display: flex; align-items: center; gap: 8px; }
.nav-link { padding: 8px 14px; border-radius: 999px; font-weight: 500; transition: background .2s ease; }
.nav-link:hover { background: var(--line); }
.nav-cta { background: var(--fg); color: var(--bg); }
.nav-cta:hover { background: var(--fg); opacity: .86; }
.icon-btn {
  width: 42px; height: 42px; display: grid; place-items: center;
  background: transparent; color: var(--fg);
  border: 1px solid var(--line); border-radius: 50%;
  cursor: pointer; transition: background .2s ease, transform .2s ease;
}
.icon-btn:hover { background: var(--line); transform: rotate(18deg); }

/* Hero */
.hero { position: relative; overflow: clip; }
.hero::before, .hero::after {
  content: ""; position: absolute; border-radius: 50%;
  border: 1px solid var(--line); pointer-events: none;
}
.hero::before { width: 560px; height: 560px; inset-inline-end: -160px; top: -120px; }
.hero::after { width: 360px; height: 360px; inset-inline-end: -60px; top: -20px; border-color: color-mix(in srgb, var(--accent) 35%, transparent); }
.hero-grid {
  position: relative; z-index: 1;
  display: grid; gap: 40px; align-items: center;
  grid-template-columns: minmax(0, 1.25fr) minmax(0, .75fr);
  padding-block: 64px 72px;
}
.eyebrow {
  display: inline-flex; align-items: center; gap: 10px;
  padding: 6px 14px; border: 1px solid var(--line); border-radius: 999px;
  background: var(--surface); color: var(--muted); font-size: .95rem; font-weight: 500;
}
.eyebrow i { width: 9px; height: 9px; border-radius: 50%; background: var(--accent); }
.hero h1 { font-weight: 700; font-size: clamp(2.2rem, 6vw, 4rem); margin-top: 20px; }
.hero h1 em { font-style: normal; color: var(--accent); }
.lead { margin-top: 20px; max-width: 52ch; color: var(--muted); font-size: 1.15rem; }
.actions { display: flex; flex-wrap: wrap; gap: 12px; margin-top: 32px; }
.btn {
  display: inline-flex; align-items: center; justify-content: center; gap: 10px;
  min-height: 52px; padding-inline: 26px; border-radius: 14px;
  font-family: var(--font-body); font-weight: 600; font-size: 1.05rem;
  border: 1px solid transparent; cursor: pointer;
  transition: transform .22s ease, box-shadow .22s ease, background .22s ease, border-color .22s ease;
}
.btn:hover { transform: translateY(-3px); }
.btn-primary { background: var(--fg); color: var(--bg); }
.btn-primary:hover { box-shadow: 0 14px 28px -14px var(--fg); }
.btn-ghost { background: transparent; color: var(--fg); border-color: var(--line); }
.btn-ghost:hover { border-color: var(--fg); }

.id-card {
  background: var(--surface); border: 1px solid var(--line); border-radius: 26px;
  padding: 28px; box-shadow: var(--shadow); min-width: 0;
}
.id-top { display: flex; align-items: center; gap: 16px; }
.id-top .mark { width: 76px; height: 76px; border-radius: 24px 24px 24px 6px; font-size: 2.8rem; padding-bottom: 8px; }
.id-name { font-family: var(--font-display); font-weight: 700; font-size: 1.6rem; line-height: 1.3; }
.id-handle { color: var(--muted); font-size: .95rem; }
.chip {
  display: inline-flex; align-items: center; gap: 8px; margin-top: 22px;
  padding: 4px 12px; border-radius: 999px; font-size: .9rem; font-weight: 600;
  background: color-mix(in srgb, var(--accent) 14%, transparent); color: var(--accent);
}
.chip i { width: 8px; height: 8px; border-radius: 50%; background: var(--accent); }
.quick { display: flex; flex-wrap: wrap; gap: 10px; margin-top: 18px; }
.quick a {
  width: 48px; height: 48px; display: grid; place-items: center; border-radius: 50%;
  border: 1px solid var(--line); color: var(--fg);
  transition: transform .22s ease, background .22s ease, color .22s ease, border-color .22s ease;
}
.quick a:hover { transform: translateY(-4px); background: var(--tile); border-color: transparent; color: #fff; }

/* Sections */
.section { padding-block: 56px; scroll-margin-top: 84px; }
.section-head { display: grid; gap: 10px; margin-bottom: 32px; }
.section-head h2 { font-weight: 700; font-size: clamp(1.7rem, 3.6vw, 2.5rem); }
.section-head p { color: var(--muted); max-width: 60ch; }

.cards { display: grid; gap: 20px; grid-template-columns: repeat(auto-fit, minmax(min(100%, 260px), 1fr)); }
.card {
  --brand: #888; --tile: #888;
  display: flex; flex-direction: column; gap: 16px; min-width: 0;
  padding: 24px; background: var(--surface); border: 1px solid var(--line); border-radius: 20px;
  box-shadow: var(--shadow);
  transition: transform .25s ease, border-color .25s ease, box-shadow .25s ease;
}
.card:hover, .card:focus-visible {
  transform: translateY(-6px); border-color: var(--brand);
  box-shadow: 0 20px 44px -18px color-mix(in srgb, var(--brand) 60%, transparent);
}
.tile {
  width: 64px; height: 64px; display: grid; place-items: center; border-radius: 18px;
  background: var(--tile); color: #fff; border: 1px solid var(--line);
  transition: transform .25s ease;
}
.tile .ico { width: 32px; height: 32px; }
.card:hover .tile { transform: rotate(-7deg) scale(1.07); }
.card h3 { font-weight: 700; font-size: 1.5rem; }
.card p { color: var(--muted); }
.card-foot {
  margin-top: auto; padding-top: 16px; border-top: 1px solid var(--line);
  display: flex; align-items: center; justify-content: space-between; gap: 12px;
}
.host { color: var(--muted); font-size: .92rem; min-width: 0; overflow-wrap: anywhere; }
.visit { display: inline-flex; align-items: center; gap: 6px; font-weight: 600; white-space: nowrap; }
.visit .ico { width: 20px; height: 20px; transition: transform .22s ease; }
.card:hover .visit .ico { transform: translate(-4px, -4px); }
.tt .tile .ico { filter: drop-shadow(2px 0 0 #25F4EE) drop-shadow(-2px 0 0 #FE2C55); }

/* Contact */
.panel {
  display: grid; gap: 32px; align-items: center;
  grid-template-columns: minmax(0, 1fr) minmax(0, 1fr);
  padding: clamp(28px, 5vw, 56px); border-radius: 28px;
  background: var(--panel); color: var(--on-panel);
}
.panel h2 { font-weight: 700; font-size: clamp(1.7rem, 3.6vw, 2.5rem); }
.panel p { margin-top: 12px; color: var(--panel-muted); max-width: 44ch; }
.panel-act { display: grid; gap: 16px; min-width: 0; }
.btn-wa {
  width: 100%; min-height: 70px; font-size: 1.25rem; border-radius: 18px;
  background: var(--wa); color: var(--on-wa);
}
.btn-wa .ico { width: 30px; height: 30px; }
.btn-wa:hover { filter: brightness(1.07); box-shadow: 0 18px 40px -14px color-mix(in srgb, var(--wa) 75%, transparent); }
.num-row { display: flex; flex-wrap: wrap; align-items: center; justify-content: space-between; gap: 12px; }
.num { font-size: 1.2rem; font-weight: 500; user-select: all; }
.copy {
  display: inline-flex; align-items: center; gap: 8px; min-height: 40px; padding-inline: 16px;
  background: transparent; color: var(--on-panel); border: 1px solid var(--panel-line); border-radius: 12px;
  font-family: var(--font-body); font-size: .95rem; cursor: pointer;
  transition: background .2s ease, border-color .2s ease;
}
.copy:hover { border-color: var(--on-panel); background: color-mix(in srgb, var(--on-panel) 8%, transparent); }
.copy .ico { width: 18px; height: 18px; }
.copy-status { min-height: 1.5em; font-size: .9rem; color: var(--panel-muted); }

/* Footer */
.site-footer { margin-top: 24px; border-top: 1px solid var(--line); }
.foot { display: flex; flex-wrap: wrap; justify-content: space-between; gap: 8px 24px; padding-block: 28px; color: var(--muted); font-size: .95rem; }

.sr { position: absolute; width: 0; height: 0; overflow: hidden; }

@media (max-width: 860px) {
  .hero-grid { grid-template-columns: minmax(0, 1fr); padding-block: 40px 48px; }
  .panel { grid-template-columns: minmax(0, 1fr); }
}
@media (max-width: 520px) {
  .nav-link:not(.nav-cta) { display: none; }
  .brand-name { font-size: 1.15rem; }
  .id-card { padding: 22px; }
  .btn { flex: 1 1 100%; }
}
@media (prefers-reduced-motion: reduce) {
  html { scroll-behavior: auto; }
  *, *::before, *::after { transition: none !important; }
  .btn:hover, .card:hover, .card:focus-visible, .quick a:hover, .icon-btn:hover, .card:hover .tile, .card:hover .visit .ico { transform: none; }
}
</style>

<svg class="sr" aria-hidden="true" focusable="false">
  <symbol id="i-tiktok" viewBox="0 0 24 24"><path d="M14 3.5v11a4 4 0 1 1-4-4"/><path d="M14 3.5c.4 2.6 2.1 4.3 4.6 4.6"/></symbol>
  <symbol id="i-facebook" viewBox="0 0 24 24"><path d="M16 3.5h-1.7a4 4 0 0 0-4 4v13"/><path d="M7 11.5h9"/></symbol>
  <symbol id="i-instagram" viewBox="0 0 24 24"><rect x="3.5" y="3.5" width="17" height="17" rx="5"/><circle cx="12" cy="12" r="4"/><circle cx="17.2" cy="6.8" r=".6"/></symbol>
  <symbol id="i-whatsapp" viewBox="0 0 24 24"><path d="M4 20l1.4-4.3A8.2 8.2 0 1 1 8.3 18.7L4 20z"/><path d="M9 8.2c-.4 2.4 2.8 6.6 6.6 6.8l.9-1.3-2-1.1-.9.7a5 5 0 0 1-2.5-2.5l.7-.9-1.1-2z"/></symbol>
  <symbol id="i-arrow" viewBox="0 0 24 24"><path d="M17 17L7 7"/><path d="M16 7H7v9"/></symbol>
  <symbol id="i-copy" viewBox="0 0 24 24"><rect x="9" y="9" width="11" height="11" rx="2.5"/><path d="M5.5 15V6.5A2.5 2.5 0 0 1 8 4h8.5"/></symbol>
</svg>

<div lang="ar" dir="rtl">

<header class="site-header">
  <div class="wrap bar">
    <a class="brand" href="#top" aria-label="محمد أحمد، أعلى الصفحة">
      <span class="mark" aria-hidden="true">م</span>
      <span class="brand-name">محمد أحمد</span>
    </a>
    <nav class="nav" aria-label="التنقل الرئيسي">
      <a class="nav-link" href="#social">حساباتي</a>
      <a class="nav-link nav-cta" href="#contact">تواصل معي</a>
      <button class="icon-btn" id="theme-toggle" type="button" aria-label="تبديل الوضع الليلي والنهاري">
        <svg class="ico" viewBox="0 0 24 24" aria-hidden="true"><circle cx="12" cy="12" r="8"/><path d="M12 4a8 8 0 0 1 0 16z" fill="currentColor"/></svg>
      </button>
    </nav>
  </div>
</header>

<main id="top">
  <section class="hero">
    <div class="wrap hero-grid">
      <div>
        <span class="eyebrow"><i></i>صفحتي الشخصية</span>
        <h1>كل حساباتي الرسمية في <em>مكان واحد</em></h1>
        <p class="lead">أنا محمد أحمد. من هنا تصل إلى حساباتي على تيك توك وفيسبوك وانستجرام، أو تراسلني مباشرة على واتساب.</p>
        <div class="actions">
          <a class="btn btn-primary" href="#contact">تواصل معي</a>
          <a class="btn btn-ghost" href="#social">تصفح حساباتي</a>
        </div>
      </div>

      <aside class="id-card" aria-label="بطاقة التعريف">
        <div class="id-top">
          <span class="mark" aria-hidden="true">م</span>
          <div>
            <div class="id-name">محمد أحمد</div>
            <div class="id-handle ltr">@m_ahmed_23456</div>
          </div>
        </div>
        <span class="chip"><i></i>الحسابات الرسمية</span>
        <div class="quick">
          <a href="https://tiktok.com" target="_blank" rel="noopener noreferrer" aria-label="تيك توك" style="--tile:#000"><svg class="ico"><use href="#i-tiktok"/></svg></a>
          <a href="https://www.facebook.com/share/19Pbp3aUy3/" target="_blank" rel="noopener noreferrer" aria-label="فيس بوك" style="--tile:#1877F2"><svg class="ico"><use href="#i-facebook"/></svg></a>
          <a href="https://www.instagram.com/m_ahmed_23456?cplk=MWUzMTBuZGNpY3pzeQ==" target="_blank" rel="noopener noreferrer" aria-label="انستجرام" style="--tile:linear-gradient(45deg,#FEDA75,#FA7E1E,#D62976,#962FBF,#4F5BD5)"><svg class="ico"><use href="#i-instagram"/></svg></a>
          <a href="https://wa.me/201155782157" target="_blank" rel="noopener noreferrer" aria-label="واتساب" style="--tile:#25D366"><svg class="ico"><use href="#i-whatsapp"/></svg></a>
        </div>
      </aside>
    </div>
  </section>

  <section class="section" id="social">
    <div class="wrap">
      <div class="section-head">
        <h2>حساباتي على السوشيال ميديا</h2>
        <p>هذه حساباتي الرسمية. اضغط على أي بطاقة لفتح الحساب في صفحة جديدة.</p>
      </div>
      <div class="cards">
        <a class="card tt" href="https://tiktok.com" target="_blank" rel="noopener noreferrer" style="--brand:#FE2C55; --tile:#000">
          <span class="tile"><svg class="ico" aria-hidden="true"><use href="#i-tiktok"/></svg></span>
          <h3>تيك توك</h3>
          <p>تابعني على تيك توك لمشاهدة الفيديوهات القصيرة.</p>
          <span class="card-foot"><span class="host ltr">tiktok.com</span><span class="visit">زيارة الحساب<svg class="ico" aria-hidden="true"><use href="#i-arrow"/></svg></span></span>
        </a>
        <a class="card" href="https://www.facebook.com/share/19Pbp3aUy3/" target="_blank" rel="noopener noreferrer" style="--brand:#1877F2; --tile:#1877F2">
          <span class="tile"><svg class="ico" aria-hidden="true"><use href="#i-facebook"/></svg></span>
          <h3>فيس بوك</h3>
          <p>صفحتي على فيسبوك للتواصل ومتابعة آخر المنشورات.</p>
          <span class="card-foot"><span class="host ltr">facebook.com</span><span class="visit">زيارة الحساب<svg class="ico" aria-hidden="true"><use href="#i-arrow"/></svg></span></span>
        </a>
        <a class="card" href="https://www.instagram.com/m_ahmed_23456?cplk=MWUzMTBuZGNpY3pzeQ==" target="_blank" rel="noopener noreferrer" style="--brand:#D62976; --tile:linear-gradient(45deg,#FEDA75,#FA7E1E,#D62976,#962FBF,#4F5BD5)">
          <span class="tile"><svg class="ico" aria-hidden="true"><use href="#i-instagram"/></svg></span>
          <h3>انستجرام</h3>
          <p>الصور والقصص على انستجرام.</p>
          <span class="card-foot"><span class="host ltr">@m_ahmed_23456</span><span class="visit">زيارة الحساب<svg class="ico" aria-hidden="true"><use href="#i-arrow"/></svg></span></span>
        </a>
      </div>
    </div>
  </section>

  <section class="section" id="contact">
    <div class="wrap">
      <div class="panel">
        <div>
          <h2>تواصل معي مباشرة</h2>
          <p>أسرع طريقة للوصول إليّ هي واتساب. اضغط على الزر وستفتح المحادثة مباشرة.</p>
        </div>
        <div class="panel-act">
          <a class="btn btn-wa" href="https://wa.me/201155782157" target="_blank" rel="noopener noreferrer">
            <svg class="ico" aria-hidden="true"><use href="#i-whatsapp"/></svg>ابدأ المحادثة على واتساب
          </a>
          <div class="num-row">
            <span class="num ltr" id="wa-num">+20 115 578 2157</span>
            <button class="copy" id="copy-btn" type="button"><svg class="ico" aria-hidden="true"><use href="#i-copy"/></svg>نسخ الرقم</button>
          </div>
          <span class="copy-status" id="copy-status" role="status" aria-live="polite"></span>
        </div>
      </div>
    </div>
  </section>
</main>

<footer class="site-footer">
  <div class="wrap foot">
    <span>© <span id="year">2026</span> محمد أحمد. جميع الحقوق محفوظة.</span>
    <span>جميع حقوق الملكية والنشر لهذا الموقع محفوظة لصاحبه.</span>
  </div>
</footer>

</div>

<script>
(function () {
  var root = document.documentElement;
  try {
    var saved = localStorage.getItem('theme');
    if (saved === 'dark' || saved === 'light') root.setAttribute('data-theme', saved);
  } catch (e) {}

  document.getElementById('theme-toggle').addEventListener('click', function () {
    var cur = root.getAttribute('data-theme');
    if (!cur) cur = window.matchMedia('(prefers-color-scheme: dark)').matches ? 'dark' : 'light';
    var next = cur === 'dark' ? 'light' : 'dark';
    root.setAttribute('data-theme', next);
    try { localStorage.setItem('theme', next); } catch (e) {}
  });

  document.getElementById('year').textContent = new Date().getFullYear();

  var status = document.getElementById('copy-status');
  function selectNumber() {
    var el = document.getElementById('wa-num');
    var range = document.createRange();
    range.selectNodeContents(el);
    var sel = window.getSelection();
    sel.removeAllRanges();
    sel.addRange(range);
  }
  document.getElementById('copy-btn').addEventListener('click', function () {
    var done = function () { status.textContent = 'تم نسخ الرقم'; };
    var fail = function () { selectNumber(); status.textContent = 'تم تحديد الرقم، انسخه يدويًا'; };
    try {
      if (navigator.clipboard && navigator.clipboard.writeText) {
        navigator.clipboard.writeText('+201155782157').then(done, fail);
      } else { fail(); }
    } catch (e) { fail(); }
  });
})();
</script>
