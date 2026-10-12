# Urban_Visionaries.github.io
Website
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Urban Visionaries: Pay rent. Own your home.</title>
<link href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:wght@500;700;800&family=Nunito+Sans:wght@400;600;700&display=swap" rel="stylesheet">
<style>
:root{--ink:#14213d;--paper:#ffffff;--soft:#eef2fa;--line:#d5dcec;--accent:#f2a33a;--muted:#4b5a85;--deep:#14213d;--deep-ink:#ffffff;
box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--ink:#eef2fa;--paper:#10182e;--soft:#18223f;--line:#2b3860;--muted:#a7b3d6;--deep:#0a1020}}
:root[data-theme="dark"]{--ink:#eef2fa;--paper:#10182e;--soft:#18223f;--line:#2b3860;--muted:#a7b3d6;--deep:#0a1020}
*{box-sizing:border-box}html{scroll-padding-top:env(safe-area-inset-top,0px);scroll-behavior:smooth}
body{margin:0;background:var(--paper);color:var(--ink);font:17px/1.6 "Nunito Sans",Arial,sans-serif}
h1,h2,h3{font-family:"Bricolage Grotesque",Arial,sans-serif;line-height:1.1;margin:0}
a{color:inherit}
.w{max-width:1040px;margin:0 auto;padding:0 20px}
.top{display:flex;justify-content:space-between;align-items:center;padding:18px 0}
.logo{font:800 1.5rem "Bricolage Grotesque",Arial,sans-serif;text-decoration:none}
.top nav{display:flex;gap:18px;font-weight:600;font-size:.95rem}
.top nav a{text-decoration:none;color:var(--muted)}
a:focus-visible{outline:3px solid var(--accent);outline-offset:3px}
.hero{display:grid;grid-template-columns:1.1fr .9fr;gap:36px;align-items:center;padding:36px 0 64px}
@media(max-width:800px){.hero{grid-template-columns:1fr}.top nav{display:none}}
.hero h1{font-size:clamp(2.6rem,6vw,4.4rem);font-weight:800;letter-spacing:-.02em}
.hero p{font-size:1.15rem;color:var(--muted);max-width:34em;margin:18px 0 26px}
.btn{display:inline-block;background:var(--accent);color:#14213d;font-weight:700;padding:14px 22px;border-radius:12px;text-decoration:none}
.btn.alt{background:transparent;border:2px solid var(--ink);color:var(--ink);margin-left:8px}
.house{background:var(--soft);border:1px solid var(--line);border-radius:20px;padding:22px}
.house svg{width:100%;height:auto;display:block}
.house label{display:flex;justify-content:space-between;font-weight:700;margin-top:10px}
.house input{width:100%;accent-color:var(--accent)}
.house small{color:var(--muted)}
section{padding:56px 0}
section h2{font-size:clamp(1.8rem,4vw,2.5rem);margin-bottom:12px;max-width:20em}
.lead{color:var(--muted);max-width:40em;margin:0 0 28px}
.steps{display:grid;grid-template-columns:repeat(3,1fr);gap:20px}
@media(max-width:800px){.steps,.who{grid-template-columns:1fr}}
.steps div{border-top:3px solid var(--accent);padding-top:14px}
.steps h3{font-size:1.25rem;margin-bottom:6px}
.band{background:var(--deep);color:var(--deep-ink)}
.band .lead{color:#c3cdea}
.who{display:grid;grid-template-columns:repeat(3,1fr);gap:20px}
.who div{background:rgba(255,255,255,.07);border-radius:14px;padding:20px}
.who h3{font-size:1.2rem;margin-bottom:6px}
.nums{display:flex;flex-wrap:wrap;gap:36px}
.nums div{min-width:150px}
.nums b{display:block;font:800 2.4rem "Bricolage Grotesque",Arial,sans-serif}
.nums span{color:var(--muted);font-size:.95rem}
.team{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:16px}
.team div{background:var(--soft);border-radius:14px;padding:18px}
.team b{display:block}
footer{border-top:1px solid var(--line);padding:26px 0 40px;color:var(--muted);font-size:.9rem}
</style>
</head>
<body>
<div class="w">
 <div class="top"><a class="logo" href="#">Urban Visionaries</a>
  <nav><a href="#how">How it works</a><a href="#who">Who it helps</a><a href="#team">Team</a></nav></div>

 <div class="hero">
  <div>
   <h1>Pay rent. Own your home.</h1>
   <p>Urban Visionaries lets families without a bank loan or salary slips pay a fixed monthly amount, and slowly become owners. Small builders and government housing schemes join on the same platform.</p>
   <a class="btn" href="https://claude.ai/artifact/7Yz2MHPo5cRknF4N9csUWf">Try the demo</a>
   <a class="btn alt" href="#how">See how it works</a>
  </div>
  <div class="house">
   <svg viewBox="0 0 320 220" role="img" aria-label="A house filling up as ownership grows">
    <defs><clipPath id="c"><path d="M40 110 L160 25 L280 110 V200 H40 Z"/></clipPath></defs>
    <path d="M40 110 L160 25 L280 110 V200 H40 Z" fill="var(--paper)" stroke="var(--ink)" stroke-width="4" stroke-linejoin="round"/>
    <rect id="fill" x="40" y="200" width="240" height="0" fill="#f2a33a" clip-path="url(#c)"/>
    <rect x="138" y="140" width="44" height="60" rx="3" fill="var(--ink)"/>
    <rect x="70" y="125" width="34" height="30" rx="3" fill="var(--soft)" stroke="var(--ink)" stroke-width="3"/>
    <rect x="216" y="125" width="34" height="30" rx="3" fill="var(--soft)" stroke="var(--ink)" stroke-width="3"/>
   </svg>
   <label for="yr"><span>After <span id="yv">5</span> years</span><span>You own <span id="pv">33</span>%</span></label>
   <input id="yr" type="range" min="0" max="15" value="5" aria-label="Years of payments">
   <small>Example: 15-year plan. Move the slider.</small>
  </div>
 </div>
</div>

<section id="how"><div class="w">
 <h2>A home is out of reach for most working families</h2>
 <p class="lead">Banks ask for income papers that daily-wage and small-business families do not have. Rents keep rising, so saving for a down payment never happens.</p>
 <div class="steps">
  <div><h3>1. Verify simply</h3><p>Families show steady income through UPI history, rent record and a local voucher. No salary slip needed.</p></div>
  <div><h3>2. Pay a fixed amount</h3><p>One monthly payment. Part is rent, and the rest builds the family's share of the home.</p></div>
  <div><h3>3. Own the home</h3><p>At the end of the term, the home is theirs. Builders get steady income all along.</p></div>
 </div>
</div></section>

<section class="band" id="who"><div class="w">
 <h2>One platform, three groups</h2>
 <p class="lead">Urban Visionaries connects the people who need homes, the people who build them, and the schemes that fund them.</p>
 <div class="who">
  <div><h3>Families</h3><p>Check eligibility, see the monthly plan, and track ownership growing.</p></div>
  <div><h3>Small builders</h3><p>List projects and get verified, paying families with steady monthly income.</p></div>
  <div><h3>Local government</h3><p>See who applied, who is verified, and which homes are matched, with scheme money reaching the right families.</p></div>
 </div>
</div></section>

<section><div class="w">
 <h2>What we want to achieve</h2>
 <p class="lead">Targets for the first year of a pilot in one city (our estimates, to be confirmed with local data).</p>
 <div class="nums">
  <div><b>10,000</b><span>families in the target area</span></div>
  <div><b>20</b><span>families in the first pilot</span></div>
  <div><b>0.4%</b><span>of home price paid as monthly rent part</span></div>
  <div><b>35%</b><span>maximum share of income for the payment</span></div>
 </div>
</div></section>

<section id="team"><div class="w">
 <h2>Team Urban Visionaries</h2>
 <p class="lead">BBA students building practical ideas for affordable housing, for the Seva Innovation Challenge 2026 (Maharashtra zone).</p>
 <div class="team">
  <div><b>Vihaan Gaurav Chandan</b>Team Lead</div>
  <div><b>Maan Faldu</b>Research Lead</div>
  <div><b>Bhavya Gala</b>Finance Analyst</div>
  <div><b>Team member 4</b>Presenter</div>
 </div>
 <p style="margin-top:28px"><a class="btn" href="https://claude.ai/artifact/7Yz2MHPo5cRknF4N9csUWf">Open the working demo</a></p>
</div></section>

<footer><div class="w">Urban Visionaries is a student prototype. Figures are illustrative and are not financial advice.</div></footer>

<script>
var yr=document.getElementById("yr");
function u(){var y=+yr.value,p=Math.round(y/15*100);
 document.getElementById("yv").textContent=y;document.getElementById("pv").textContent=p;
 var h=176*(y/15),f=document.getElementById("fill");f.setAttribute("y",200-h);f.setAttribute("height",h)}
yr.addEventListener("input",u);u();
</script>
</body>
</html>
