# manigandan-Realtor
manigandanlykarealty
[index.html](https://github.com/user-attachments/files/35205513/index.html)
<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1,viewport-fit=cover">
<meta name="description" content="Manigandan T., Portfolio Manager. Dubai property projects from Emaar, Nakheel, Sobha, Damac, Imtiaz, Tarrad and SOL.">
<style>html{scroll-behavior:smooth}body{margin:0}img{max-width:100%}[hidden]{display:none!important}</style>
<title>Manigandan T. Dubai Property</title>
<meta name="claude:viewport-fit-sides" content="cover">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:opsz,wght@12..96,500;12..96,700&family=Figtree:wght@400;500;600&display=swap">
<style>
/* Layout: navy hero with skyline and contact card; services; developer map with community panel; filterable project cards that open a detail sheet; mortgage calculator; process; contact. Navy and brass. */
:root{
  --navy:#0a1a2f;
  --navy-2:#123456;
  --brass:#c9a24b;
  --hero-fg:#eef4fb;
  --wa:#1fa855;
  --bg:#f5f7fa;
  --bg-alt:#e9eef4;
  --surface:#ffffff;
  --fg:#10202f;
  --muted:#56667a;
  --line:#d6dfe9;
  --accent:#1b4f8a;
  --on-accent:#ffffff;
  --sea:#cfe0ef;
  --land:#f1ece2;
  --road:#b7a98c;
  --warn:#8a5a00;
  --warn-bg:#fbf0d6;
  --font-display:"Bricolage Grotesque","Segoe UI",system-ui,sans-serif;
  --font-body:"Figtree","Segoe UI",system-ui,sans-serif;
}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){
  --bg:#0b1522;--bg-alt:#0f1b2b;--surface:#142235;--fg:#e8eef6;--muted:#9db0c6;--line:#243649;--accent:#7fb2ea;--on-accent:#08182b;--sea:#0e2236;--land:#1b2a38;--road:#41566b;--warn:#f0c76a;--warn-bg:#3a2e12;color-scheme:dark}}
:root[data-theme="dark"]{
  --bg:#0b1522;--bg-alt:#0f1b2b;--surface:#142235;--fg:#e8eef6;--muted:#9db0c6;--line:#243649;--accent:#7fb2ea;--on-accent:#08182b;--sea:#0e2236;--land:#1b2a38;--road:#41566b;--warn:#f0c76a;--warn-bg:#3a2e12;color-scheme:dark}
*{box-sizing:border-box}
body{background:var(--bg);color:var(--fg);font-family:var(--font-body);font-size:16px;line-height:1.6;
  padding-left:max(16px,env(safe-area-inset-left,0px));padding-right:max(16px,env(safe-area-inset-right,0px));padding-block:0}
h1,h2,h3{font-family:var(--font-display);line-height:1.1;margin:0;text-wrap:balance;letter-spacing:-.01em}
p{margin:0}
a{color:inherit}
:focus-visible{outline:3px solid var(--brass);outline-offset:2px}
.wrap{max-width:1120px;margin:0 auto}
.band{margin-left:calc(-1 * max(16px,env(safe-area-inset-left,0px)));margin-right:calc(-1 * max(16px,env(safe-area-inset-right,0px)));
  padding-left:max(16px,env(safe-area-inset-left,0px));padding-right:max(16px,env(safe-area-inset-right,0px))}
.alt{background:var(--bg-alt)}
.hero{position:relative;overflow:hidden;background:linear-gradient(180deg,var(--navy) 0%,var(--navy-2) 100%);color:var(--hero-fg)}
.hero::before{content:"";position:absolute;inset:0;background:radial-gradient(900px 420px at 85% 0%,rgba(201,162,75,.16),transparent 70%)}
.sky{position:absolute;left:0;right:0;bottom:0;width:100%;height:240px;pointer-events:none}
.hero .wrap{position:relative}
nav{display:flex;align-items:center;justify-content:space-between;gap:16px;padding-block:18px;flex-wrap:wrap}
.logo{text-decoration:none;display:flex;align-items:center;gap:12px}
.logo i{width:40px;height:40px;border-radius:50%;background:var(--brass);display:grid;place-items:center;color:var(--navy);font-style:normal;font-family:var(--font-display);font-weight:700;font-size:20px}
.logo span{display:flex;flex-direction:column;line-height:1.2;font-family:var(--font-display);font-weight:700;font-size:19px}
.logo small{font-family:var(--font-body);font-weight:500;font-size:12px;letter-spacing:.14em;text-transform:uppercase;color:var(--brass)}
.links{display:flex;gap:20px;flex-wrap:wrap;font-size:15px;font-weight:500}
.links a{text-decoration:none;opacity:.88}
.links a:hover{opacity:1;text-decoration:underline;text-underline-offset:4px}
.herogrid{display:grid;grid-template-columns:1.2fr .8fr;gap:40px;align-items:center;padding-block:40px 150px}
.eyebrow{font-size:13px;letter-spacing:.14em;text-transform:uppercase;color:var(--brass);font-weight:600}
.hero h1{font-size:clamp(36px,5.6vw,64px);margin-top:14px}
.hero .lead{margin-top:18px;max-width:52ch;font-size:18px;opacity:.9}
.cta{display:flex;gap:12px;flex-wrap:wrap;margin-top:28px}
.btn{display:inline-flex;align-items:center;gap:8px;padding:13px 22px;border-radius:999px;font-weight:600;text-decoration:none;border:2px solid transparent;font-family:var(--font-body);font-size:16px;cursor:pointer}
.btn.wa{background:var(--wa);color:#fff}
.btn.wa:hover{filter:brightness(1.08)}
.btn.ghost{border-color:rgba(238,244,251,.45);color:var(--hero-fg);background:transparent}
.btn.ghost:hover{border-color:var(--hero-fg)}
.btn.solid{background:var(--accent);color:var(--on-accent)}
.btn.line{border-color:var(--line);color:var(--fg);background:var(--surface)}
.btn.line:hover{border-color:var(--accent);color:var(--accent)}
.ccard{background:rgba(255,255,255,.08);border:1px solid rgba(238,244,251,.2);border-radius:18px;padding:24px;width:100%;max-width:380px;justify-self:center;backdrop-filter:blur(6px)}
.ccard h2{font-size:22px}
.clist{list-style:none;margin:14px 0 0;padding:0;display:flex;flex-direction:column;gap:12px}
.clist li{display:flex;flex-wrap:wrap;align-items:center;gap:4px 10px}
.clist .k{flex:0 0 100%;font-size:12px;letter-spacing:.12em;text-transform:uppercase;color:var(--brass);font-weight:600}
.clist a{font-weight:500;text-underline-offset:3px;overflow-wrap:anywhere;min-width:0}
.copy{font:inherit;font-size:13px;padding:4px 12px;border-radius:999px;border:1px solid rgba(238,244,251,.4);background:transparent;color:var(--hero-fg);cursor:pointer}
.copy:hover{border-color:var(--hero-fg)}
section{padding-block:64px}
.sh{max-width:64ch}
.sh h2{font-size:clamp(28px,3.6vw,40px)}
.sh p{margin-top:12px;color:var(--muted)}
.grid4{display:grid;grid-template-columns:repeat(auto-fit,minmax(230px,1fr));gap:18px;margin-top:32px}
.svc{background:var(--surface);border:1px solid var(--line);border-radius:14px;padding:22px}
.svc h3{font-size:20px}
.svc p{margin-top:8px;color:var(--muted);font-size:15px}
.svc .tag{display:inline-block;margin-bottom:12px;font-size:12px;letter-spacing:.12em;text-transform:uppercase;color:var(--accent);font-weight:600}
.filters{display:flex;flex-direction:column;gap:10px;margin-top:22px}
.frow{display:flex;flex-wrap:wrap;gap:8px;align-items:center}
.frow .fl{font-size:12px;letter-spacing:.12em;text-transform:uppercase;color:var(--muted);font-weight:600;min-width:84px}
.chip{border:1px solid var(--line);background:var(--surface);color:var(--fg);padding:7px 14px;border-radius:999px;font-size:14px;font-family:var(--font-body);cursor:pointer}
.chip:hover{border-color:var(--accent);color:var(--accent)}
.chip.on{background:var(--accent);color:var(--on-accent);border-color:var(--accent)}
.mapgrid{display:grid;grid-template-columns:1.45fr 1fr;gap:20px;margin-top:22px;align-items:start}
.mapbox{background:var(--sea);border:1px solid var(--line);border-radius:16px;overflow:hidden;min-width:0}
.mapbox svg{display:block;width:100%;height:auto}
.mk{cursor:pointer}
.mk circle.dot{fill:var(--accent);stroke:#fff;stroke-width:3}
.mk circle.halo{fill:var(--accent);opacity:.2}
.mk.sel circle.dot{fill:var(--brass);stroke:var(--navy)}
.mk.sel circle.halo{fill:var(--brass);opacity:.4}
.mk.has circle.dot{r:11}
.mk.none circle.dot{fill:var(--muted)}
.mk.off{opacity:.15;pointer-events:none}
.mk:focus-visible{outline:none}
.mk:focus-visible circle.halo{opacity:.65}
.mk text{font:600 20px var(--font-body);fill:var(--fg);paint-order:stroke;stroke:var(--land);stroke-width:5px;pointer-events:none}
.maptxt{font:500 18px var(--font-body);fill:var(--muted)}
.panel{background:var(--surface);border:1px solid var(--line);border-radius:16px;padding:22px;min-width:0}
.panel h3{font-size:24px}
.panel .dev{margin-top:6px;color:var(--accent);font-weight:600;font-size:15px}
.panel h4{margin:18px 0 8px;font-size:13px;letter-spacing:.12em;text-transform:uppercase;color:var(--muted);font-family:var(--font-body)}
.plist{list-style:none;margin:0;padding:0;display:flex;flex-direction:column;gap:8px}
.plist button{width:100%;text-align:left;border:1px solid var(--line);border-radius:12px;padding:12px;background:var(--bg);color:var(--fg);font:inherit;display:flex;flex-direction:column;gap:2px;cursor:pointer}
.plist button:hover{border-color:var(--accent)}
.plist .pd{font-size:12px;font-weight:600;color:var(--accent);letter-spacing:.08em;text-transform:uppercase}
.plist .pn{font-weight:700;font-family:var(--font-display);font-size:18px}
.plist .go{font-size:13px;color:var(--accent);font-weight:600}
.meta{color:var(--muted);font-size:14px}
.panel .acts{display:flex;flex-direction:column;gap:10px;margin-top:18px}
.panel .btn{justify-content:center;width:100%}
.note{margin-top:18px;font-size:13px;color:var(--muted);max-width:92ch}
.cards{display:grid;grid-template-columns:repeat(auto-fill,minmax(280px,1fr));gap:18px;margin-top:22px}
.card{background:var(--surface);border:1px solid var(--line);border-radius:16px;padding:0;display:flex;flex-direction:column;min-width:0;text-align:left;color:var(--fg);font:inherit;cursor:pointer}
.card:hover{border-color:var(--accent)}
.card .in{padding:20px;display:flex;flex-direction:column;gap:6px;flex:1}
.card .dv{font-size:12px;letter-spacing:.12em;text-transform:uppercase;color:var(--accent);font-weight:600}
.card h3{font-size:22px}
.card .from{font-family:var(--font-display);font-size:20px;font-weight:700;margin-top:4px}
.tags{display:flex;flex-wrap:wrap;gap:6px;margin-top:6px}
.tag2{font-size:12px;font-weight:600;padding:3px 9px;border-radius:999px;background:var(--bg-alt);color:var(--fg)}
.tag2.sold{background:var(--warn-bg);color:var(--warn)}
.card .more{padding:12px 20px;border-top:1px solid var(--line);font-size:14px;font-weight:600;color:var(--accent)}
.empty{grid-column:1/-1;color:var(--muted);padding:20px;border:1px dashed var(--line);border-radius:14px}
.count{margin-top:16px;font-size:14px;color:var(--muted)}
.calc{display:grid;grid-template-columns:1fr 1fr;gap:28px;margin-top:30px;background:var(--surface);border:1px solid var(--line);border-radius:18px;padding:26px}
.field{display:flex;flex-direction:column;gap:6px;margin-bottom:16px;min-width:0}
.field label{font-size:14px;font-weight:600}
.field input{font:inherit;padding:11px 12px;border-radius:10px;border:1px solid var(--line);background:var(--bg);color:var(--fg);width:100%}
.result{background:var(--navy);color:var(--hero-fg);border-radius:14px;padding:24px;display:flex;flex-direction:column;justify-content:center;gap:10px}
.result .big{font-family:var(--font-display);font-size:clamp(30px,5vw,42px);font-weight:700;color:var(--brass);overflow-wrap:anywhere}
.result dl{margin:8px 0 0;display:grid;grid-template-columns:1fr auto;gap:6px 16px;font-size:15px}
.result dd{margin:0;text-align:right;font-variant-numeric:tabular-nums}
.steps{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:18px;margin-top:30px}
.step{border-left:3px solid var(--brass);padding:4px 0 4px 16px}
.step h3{font-size:19px}
.step p{color:var(--muted);font-size:15px;margin-top:6px}
.contact{background:linear-gradient(180deg,var(--navy-2),var(--navy));color:var(--hero-fg)}
.contact .box{display:grid;grid-template-columns:1.1fr .9fr;gap:36px;align-items:start;padding-block:64px}
.contact h2{font-size:clamp(28px,3.6vw,40px)}
.contact p{margin-top:12px;opacity:.88;max-width:48ch}
.contact .clist{margin-top:26px}
form{display:flex;flex-direction:column;gap:12px}
form input,form select,form textarea{font:inherit;padding:12px;border-radius:10px;border:1px solid rgba(238,244,251,.3);background:rgba(255,255,255,.08);color:var(--hero-fg);width:100%}
form select option{color:#10202f}
form ::placeholder{color:rgba(238,244,251,.6)}
form label{font-size:14px;font-weight:600}
footer{font-size:13px;color:var(--muted);padding-block:26px;display:flex;justify-content:space-between;gap:12px;flex-wrap:wrap}
.float{position:fixed;right:max(16px,env(safe-area-inset-right,0px));bottom:calc(16px + env(safe-area-inset-bottom,0px));z-index:20;background:var(--wa);color:#fff;border-radius:999px;padding:13px 20px;font-weight:600;text-decoration:none;box-shadow:0 10px 26px rgba(0,0,0,.35);display:flex;gap:8px;align-items:center}
.icons{display:flex;gap:12px;flex-wrap:wrap}
.ic{width:44px;height:44px;border-radius:50%;border:1px solid rgba(238,244,251,.4);display:grid;place-items:center;color:var(--hero-fg);text-decoration:none}
.ic:hover{background:var(--brass);border-color:var(--brass);color:var(--navy)}
.fr{display:flex;align-items:center;gap:16px;flex-wrap:wrap}
.fic .ic{width:36px;height:36px;color:var(--muted);border-color:var(--line)}
.fic .ic:hover{background:transparent;border-color:var(--accent);color:var(--accent)}
.fic .ic svg{width:18px;height:18px}
/* detail sheet */
.ov{position:fixed;inset:0;z-index:60;background:rgba(5,12,22,.66);overflow-y:auto;
  padding:max(16px,env(safe-area-inset-top,0px)) max(16px,env(safe-area-inset-right,0px)) max(16px,env(safe-area-inset-bottom,0px)) max(16px,env(safe-area-inset-left,0px))}
.sheet{background:var(--surface);color:var(--fg);border-radius:18px;max-width:780px;margin:0 auto;position:relative;overflow:hidden}
.shead{background:linear-gradient(180deg,var(--navy),var(--navy-2));color:var(--hero-fg);padding:26px 26px 22px}
.shead .dv{font-size:12px;letter-spacing:.14em;text-transform:uppercase;color:var(--brass);font-weight:600}
.shead h2{font-size:clamp(26px,4vw,36px);margin-top:6px;padding-right:44px}
.shead .tags{margin-top:12px}
.shead .tag2{background:rgba(255,255,255,.14);color:var(--hero-fg)}
.shead .tag2.sold{background:var(--warn-bg);color:var(--warn)}
.xbtn{position:absolute;top:14px;right:14px;width:38px;height:38px;border-radius:50%;border:1px solid rgba(238,244,251,.4);background:rgba(255,255,255,.1);color:#fff;font-size:22px;line-height:1;cursor:pointer}
.xbtn:hover{background:rgba(255,255,255,.22)}
.sbody{padding:24px 26px 28px;display:flex;flex-direction:column;gap:22px}
.facts{display:grid;grid-template-columns:repeat(auto-fit,minmax(160px,1fr));gap:14px}
.fact{border:1px solid var(--line);border-radius:12px;padding:12px 14px;min-width:0}
.fact .k{font-size:12px;letter-spacing:.1em;text-transform:uppercase;color:var(--muted);font-weight:600}
.fact .v{margin-top:4px;font-weight:600;overflow-wrap:anywhere}
.sbody h3{font-size:18px;margin-bottom:10px}
.tw{overflow-x:auto;border:1px solid var(--line);border-radius:12px}
table{border-collapse:collapse;width:100%;min-width:360px;font-size:15px}
th,td{text-align:left;padding:10px 14px;border-bottom:1px solid var(--line);font-variant-numeric:tabular-nums}
th{font-size:12px;letter-spacing:.1em;text-transform:uppercase;color:var(--muted);background:var(--bg-alt)}
tr:last-child td{border-bottom:0}
.plan{background:var(--bg-alt);border-radius:12px;padding:14px 16px}
.am{display:flex;flex-wrap:wrap;gap:8px}
.am span{border:1px solid var(--line);border-radius:999px;padding:5px 12px;font-size:14px}
.fine{font-size:13px;color:var(--muted)}
.fine a{color:var(--accent)}
.sacts{display:flex;gap:10px;flex-wrap:wrap}
@media (max-width:820px){
  .herogrid,.calc,.contact .box,.mapgrid{grid-template-columns:1fr}
  .herogrid{padding-block:24px 120px}
  .ccard{max-width:none}
  section{padding-block:48px}
  .shead,.sbody{padding-left:18px;padding-right:18px}
}
@media (prefers-reduced-motion:no-preference){.card,.svc{transition:transform .2s}.card:hover,.svc:hover{transform:translateY(-3px)}}
</style>
</head>
<body>

<header class="hero band">
 <svg class="sky" viewBox="0 0 1200 240" preserveAspectRatio="xMidYMax slice" aria-hidden="true">
  <path fill="rgba(255,255,255,.05)" d="M0,240 L0,190 L40,190 L40,172 L80,172 L80,186 L120,186 L120,140 L150,140 L150,160 L190,160 L190,120 L215,120 L215,150 L260,150 L260,180 L300,180 L300,130 L330,130 L330,110 L350,110 L350,170 L400,170 L400,190 L450,190 L450,150 L480,150 L480,175 L520,175 L520,80 L526,80 L530,20 L534,80 L540,80 L540,135 L560,135 L560,120 L590,120 L590,170 L630,170 L630,145 L670,145 L670,185 L720,185 L720,130 L760,130 L760,160 L800,160 L800,115 L830,115 L830,170 L880,170 L880,190 L930,190 L930,155 L970,155 L970,140 L1000,140 L1000,180 L1050,180 L1050,165 L1100,165 L1100,190 L1150,190 L1150,175 L1200,175 L1200,240 Z"/>
  <path fill="rgba(201,162,75,.12)" d="M0,240 L0,215 L70,215 L70,200 L110,200 L110,212 L170,212 L170,185 L200,185 L200,205 L260,205 L260,218 L340,218 L340,196 L380,196 L380,214 L470,214 L470,200 L500,200 L500,216 L600,216 L600,190 L640,190 L640,208 L720,208 L720,196 L760,196 L760,214 L860,214 L860,198 L900,198 L900,212 L990,212 L990,192 L1030,192 L1030,210 L1120,210 L1120,200 L1200,200 L1200,240 Z"/>
 </svg>
 <div class="wrap">
  <nav>
   <a class="logo" href="#top"><i>M</i><span>Manigandan T.<small>Portfolio Manager</small></span></a>
   <div class="links"><a href="#services">Services</a><a href="#areas">Map</a><a href="#projects">Projects</a><a href="#calculator">Mortgage</a><a href="#contact">Contact</a></div>
  </nav>
  <div class="herogrid" id="top">
   <div>
    <div class="eyebrow">Manigandan T. · Portfolio Manager · Dubai</div>
    <h1>Buy properties with Manigandan</h1>
    <p class="lead">Off-plan launches and ready homes from Emaar, Nakheel, Sobha, Damac, Imtiaz, Tarrad and SOL. Open any project to see its location, unit types, payment plan and amenities, then message me for the latest availability.</p>
    <div class="cta">
     <a class="btn wa" data-wa="Hello Manigandan, I would like help finding a property in Dubai." target="_blank" rel="noopener">Chat on WhatsApp</a>
     <a class="btn ghost" href="#projects">Browse projects</a>
    </div>
   </div>
   <aside class="ccard"><h2>Get in touch</h2>
    <ul class="clist">
     <li><span class="k">WhatsApp</span><a data-wa="Hello Manigandan, I would like help finding a property in Dubai." target="_blank" rel="noopener">+971 58 837 7861</a></li>
     <li><span class="k">Email</span><a class="v" href="mailto:manigandanlykarealty@gmail.com">manigandanlykarealty@gmail.com</a><button type="button" class="copy">Copy</button></li>
     <li><span class="k">Follow</span><span class="icons"><a class="ic" href="https://www.instagram.com/mani.factslyka/?hl=en" target="_blank" rel="noopener" aria-label="Instagram" title="Instagram"><svg viewBox="0 0 24 24" width="22" height="22" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect x="3" y="3" width="18" height="18" rx="5"/><circle cx="12" cy="12" r="4"/><circle cx="17.5" cy="6.5" r="1" fill="currentColor" stroke="none"/></svg></a><a class="ic" href="https://www.youtube.com/@manilyka" target="_blank" rel="noopener" aria-label="YouTube" title="YouTube"><svg viewBox="0 0 24 24" width="22" height="22" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect x="2" y="5" width="20" height="14" rx="4"/><polygon points="10,9 16,12 10,15" fill="currentColor" stroke="none"/></svg></a><a class="ic" href="https://www.facebook.com/profile.php?id=61596023588130" target="_blank" rel="noopener" aria-label="Facebook" title="Facebook"><svg viewBox="0 0 24 24" width="22" height="22" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M18 2h-3a5 5 0 0 0-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 0 1 1-1h3z"/></svg></a></span></li>
    </ul>
   </aside>
  </div>
 </div>
</header>

<div class="band">
<main class="wrap">
 <section id="services">
  <div class="sh"><h2>What I help with</h2><p>One point of contact from the first viewing to the keys.</p></div>
  <div class="grid4">
   <div class="svc"><span class="tag">Buy</span><h3>Ready and off-plan homes</h3><p>Apartments, townhouses and villas shortlisted against your budget, payment plan and handover date.</p></div>
   <div class="svc"><span class="tag">Rent</span><h3>Short and long-term rentals</h3><p>Viewings arranged around your schedule, with tenancy paperwork explained before you sign.</p></div>
   <div class="svc"><span class="tag">Invest</span><h3>Yield and resale advice</h3><p>Compare areas by expected rental return, service charges and demand before you commit.</p></div>
   <div class="svc"><span class="tag">Finance</span><h3>Mortgage guidance</h3><p>Understand the down payment, fees and monthly cost. Use the calculator below for a first estimate.</p></div>
  </div>
 </section>
</main>
</div>

<div class="band alt">
<div class="wrap">
 <section id="areas">
  <div class="sh"><h2>Dubai map and developers</h2><p>Filter by developer and home type, then tap a marker. Larger blue markers have projects. Open a project for the full details.</p></div>
  <div class="filters">
   <div class="frow" id="devchips" role="group" aria-label="Filter by developer"><span class="fl">Developer</span></div>
   <div class="frow" id="typechips" role="group" aria-label="Filter by home type"><span class="fl">Home type</span></div>
  </div>
  <div class="mapgrid">
   <div class="mapbox"><svg id="map" viewBox="0 0 918 782" role="group" aria-label="Schematic map of Dubai with community markers"></svg></div>
   <div class="panel" id="panel" aria-live="polite"></div>
  </div>
  <p class="note">The map is a schematic outline and marker positions are approximate. Live Google Maps and satellite tiles cannot load inside this page. For communities where I am sure of the position, the satellite button opens Google Maps in satellite view. For the others it opens a Google Maps search, where you can switch to Satellite.</p>
 </section>
</div>
</div>

<div class="band">
<div class="wrap">
 <section id="projects">
  <div class="sh"><h2>Projects</h2><p>Tap a project for its location, unit types, payment plan and amenities.</p></div>
  <div class="frow" style="margin-top:18px"><button type="button" class="chip" id="hidesold" aria-pressed="false">Hide sold-out projects</button></div>
  <div class="count" id="count"></div>
  <div class="cards" id="cards"></div>
  <p class="note">Details were gathered from public developer and property portal pages (mostly Property Finder) in November 2026. Prices are launch prices and payment plans can change. Many projects show as sold out on portals, and resale units may still be available. Please confirm current availability, prices and handover dates with me before you decide.</p>
 </section>

 <section id="calculator" style="padding-top:8px">
  <div class="sh"><h2>Mortgage calculator</h2><p>An indicative monthly payment. A bank sets the final terms.</p></div>
  <div class="calc">
   <div>
    <div class="field"><label for="price">Property price (AED)</label><input id="price" type="number" inputmode="numeric" value="1500000" min="0" step="10000"></div>
    <div class="field"><label for="down">Down payment (%)</label><input id="down" type="number" inputmode="decimal" value="20" min="0" max="90" step="1"></div>
    <div class="field"><label for="rate">Interest rate (% per year)</label><input id="rate" type="number" inputmode="decimal" value="4.5" min="0" step="0.1"></div>
    <div class="field"><label for="years">Loan term (years)</label><input id="years" type="number" inputmode="numeric" value="25" min="1" max="30" step="1"></div>
   </div>
   <div class="result" aria-live="polite">
    <span style="opacity:.8;font-size:14px">Estimated monthly payment</span>
    <div class="big" id="monthly">AED 0</div>
    <dl>
     <dt>Loan amount</dt><dd id="loan">0</dd>
     <dt>Down payment</dt><dd id="dp">0</dd>
     <dt>Total interest</dt><dd id="int">0</dd>
    </dl>
    <a class="btn wa" id="calcwa" target="_blank" rel="noopener" style="margin-top:10px;justify-content:center">Discuss this on WhatsApp</a>
   </div>
  </div>
 </section>

 <section id="process" style="padding-top:8px">
  <div class="sh"><h2>How it works</h2></div>
  <div class="steps">
   <div class="step"><h3>Message me</h3><p>Share budget, area, property type and when you want to move.</p></div>
   <div class="step"><h3>Get a short list</h3><p>I send a few matched options with the real costs, not just the asking price.</p></div>
   <div class="step"><h3>View and decide</h3><p>In-person or video viewings, and answers to your questions on the spot.</p></div>
   <div class="step"><h3>Close the deal</h3><p>I stay with you through the paperwork until the keys are in your hand.</p></div>
  </div>
 </section>
</div>
</div>

<section class="contact band" id="contact" style="padding-block:0">
 <div class="wrap box">
  <div>
   <h2>Tell me what you are looking for</h2>
   <p>Fill in the form and your message opens in WhatsApp, ready to send. Or reach me directly using the details below.</p>
   <div class="cta"><a class="btn wa" data-wa="Hello Manigandan, I would like to speak about a property." target="_blank" rel="noopener">Open WhatsApp</a></div>
   <ul class="clist">
    <li><span class="k">WhatsApp</span><a data-wa="Hello Manigandan, I would like to speak about a property." target="_blank" rel="noopener">+971 58 837 7861</a></li>
    <li><span class="k">Email</span><a class="v" href="mailto:manigandanlykarealty@gmail.com">manigandanlykarealty@gmail.com</a><button type="button" class="copy">Copy</button></li>
    <li><span class="k">Follow</span><span class="icons"><a class="ic" href="https://www.instagram.com/mani.factslyka/?hl=en" target="_blank" rel="noopener" aria-label="Instagram" title="Instagram"><svg viewBox="0 0 24 24" width="22" height="22" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect x="3" y="3" width="18" height="18" rx="5"/><circle cx="12" cy="12" r="4"/><circle cx="17.5" cy="6.5" r="1" fill="currentColor" stroke="none"/></svg></a><a class="ic" href="https://www.youtube.com/@manilyka" target="_blank" rel="noopener" aria-label="YouTube" title="YouTube"><svg viewBox="0 0 24 24" width="22" height="22" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect x="2" y="5" width="20" height="14" rx="4"/><polygon points="10,9 16,12 10,15" fill="currentColor" stroke="none"/></svg></a><a class="ic" href="https://www.facebook.com/profile.php?id=61596023588130" target="_blank" rel="noopener" aria-label="Facebook" title="Facebook"><svg viewBox="0 0 24 24" width="22" height="22" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M18 2h-3a5 5 0 0 0-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 0 1 1-1h3z"/></svg></a></span></li>
   </ul>
  </div>
  <form id="form" autocomplete="on">
   <div><label for="name">Your name</label><input id="name" placeholder="Full name"></div>
   <div><label for="want">I want to</label>
    <select id="want"><option>Buy a property</option><option>Rent a property</option><option>Invest in property</option><option>Get mortgage guidance</option></select></div>
   <div><label for="budget">Budget (AED)</label><input id="budget" placeholder="e.g. 1,500,000"></div>
   <div><label for="msg">Anything else</label><textarea id="msg" rows="3" placeholder="Area, bedrooms, move-in date"></textarea></div>
   <a class="btn wa" id="formwa" target="_blank" rel="noopener" style="justify-content:center">Send on WhatsApp</a>
  </form>
 </div>
</section>

<footer class="wrap">
 <span>&copy; Manigandan T., Portfolio Manager, Dubai, UAE</span>
 <span class="fr"><span class="icons fic"><a class="ic" href="https://www.instagram.com/mani.factslyka/?hl=en" target="_blank" rel="noopener" aria-label="Instagram" title="Instagram"><svg viewBox="0 0 24 24" width="22" height="22" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect x="3" y="3" width="18" height="18" rx="5"/><circle cx="12" cy="12" r="4"/><circle cx="17.5" cy="6.5" r="1" fill="currentColor" stroke="none"/></svg></a><a class="ic" href="https://www.youtube.com/@manilyka" target="_blank" rel="noopener" aria-label="YouTube" title="YouTube"><svg viewBox="0 0 24 24" width="22" height="22" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect x="2" y="5" width="20" height="14" rx="4"/><polygon points="10,9 16,12 10,15" fill="currentColor" stroke="none"/></svg></a><a class="ic" href="https://www.facebook.com/profile.php?id=61596023588130" target="_blank" rel="noopener" aria-label="Facebook" title="Facebook"><svg viewBox="0 0 24 24" width="22" height="22" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M18 2h-3a5 5 0 0 0-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 0 1 1-1h3z"/></svg></a></span><span>RERA Licensed Realtor</span></span>
</footer>

<a class="float" data-wa="Hello Manigandan, I have a question about Dubai property." target="_blank" rel="noopener" aria-label="Chat on WhatsApp">WhatsApp</a>

<div class="ov" id="ov" hidden>
 <div class="sheet" role="dialog" aria-modal="true" aria-labelledby="dtitle" id="sheet"></div>
</div>

<script>
(function(){
  var DATA={"places": [{"n": "Dubai Marina", "d": ["Emaar"], "lo": 55.15, "la": 25.072, "c": 1, "q": null}, {"n": "Jumeirah Beach Residence", "d": ["Dubai Properties"], "lo": 55.131, "la": 25.078, "c": 1, "q": null}, {"n": "Palm Jumeirah", "d": ["Nakheel"], "lo": 55.139, "la": 25.112, "c": 1, "q": null}, {"n": "Dubai Harbour", "d": [], "lo": 55.158, "la": 25.098, "c": 1, "q": null}, {"n": "Barsha Heights (TECOM)", "d": ["TECOM Group"], "lo": 55.18, "la": 25.095, "c": 1, "q": null}, {"n": "Jumeirah Village Circle", "d": ["Nakheel"], "lo": 55.21, "la": 25.06, "c": 1, "q": null}, {"n": "Motor City", "d": [], "lo": 55.243, "la": 25.049, "c": 1, "q": null}, {"n": "Victory Heights", "d": [], "lo": 55.232, "la": 25.03, "c": 1, "q": null}, {"n": "Dubai Hills Estate", "d": ["Emaar", "Meraas"], "lo": 55.25, "la": 25.1, "c": 1, "q": null}, {"n": "Arabian Ranches", "d": ["Emaar"], "lo": 55.275, "la": 25.052, "c": 1, "q": null}, {"n": "Damac Hills", "d": ["Damac"], "lo": 55.245, "la": 25.012, "c": 1, "q": null}, {"n": "Business Bay", "d": ["Dubai Properties"], "lo": 55.262, "la": 25.185, "c": 1, "q": null}, {"n": "Downtown Dubai", "d": ["Emaar"], "lo": 55.277, "la": 25.197, "c": 1, "q": null}, {"n": "Sobha Hartland", "d": ["Sobha"], "lo": 55.302, "la": 25.172, "c": 1, "q": null}, {"n": "Dubai Creek Harbour", "d": ["Emaar", "Dubai Holding"], "lo": 55.345, "la": 25.205, "c": 1, "q": null}, {"n": "Dubai Islands", "d": ["Nakheel"], "lo": 55.31, "la": 25.302, "c": 1, "q": null}, {"n": "Dubailand", "d": [], "lo": 55.37, "la": 25.08, "c": 0, "q": "Dubai Land Residence Complex"}, {"n": "Damac Hills 2", "d": ["Damac"], "lo": 55.32, "la": 24.985, "c": 0, "q": null}, {"n": "Damac Lagoons", "d": ["Damac"], "lo": 55.33, "la": 24.94, "c": 0, "q": null}, {"n": "Damac Islands", "d": ["Damac"], "lo": 55.39, "la": 24.95, "c": 0, "q": null}, {"n": "The Valley", "d": ["Emaar"], "lo": 55.42, "la": 25.01, "c": 0, "q": null}, {"n": "Grand Polo Club & Resort", "d": ["Emaar"], "lo": 55.18, "la": 24.93, "c": 0, "q": null}, {"n": "Jebel Ali 1", "d": [], "lo": 55.06, "la": 24.995, "c": 0, "q": null}, {"n": "Palm Jebel Ali", "d": ["Nakheel"], "lo": 54.955, "la": 24.99, "c": 0, "q": null}], "projects": [{"d": "Emaar", "n": "Palace Residences Hillside A", "a": "Dubai Hills Estate", "loc": "Palace Residences Hillside sub-community, Dubai Hills Estate, with golf course and greenery views", "status": "Off-plan", "handover": "Q2 2029 (30 June 2029)", "price": 1700000, "note": "Property Finder new-projects page, fetched Nov 2026 (header AED 1.7M; FAQ AED 1,710,000); page says prices may change", "cfg": [{"label": "1 BR", "cat": "1 BR", "size": "675-770", "from": 1700000}, {"label": "2 BR", "cat": "2 BR", "size": "1061-1190", "from": null}, {"label": "3 BR", "cat": "3 BR", "size": "1882-2110", "from": null}, {"label": "Townhouse", "cat": "Townhouse", "size": "2622", "from": null}], "plan": "10% down at launch, 70% during construction, 20% on handover", "am": ["Indoor swimming pool", "Landscaped gardens", "CCTV security", "Gymnasium", "Restaurants", "Children's play area", "Jogging tracks", "Wellness centers"], "hl": "Resort-style apartments and 3-bed townhouses in 3 buildings overlooking the golf course and landscaped greenery.", "src": ["https://propertyfinder.ae/en/new-projects/emaar-properties/palace-residences-dubai-hills-estate", "https://www.bayut.com/new-projects/developers/emaar"], "sold": false}, {"d": "Emaar", "n": "Creek Waters", "a": "Dubai Creek Harbour", "loc": "Creek Island, Dubai Creek Harbour (The Lagoons)", "status": "Under construction", "handover": "Q3 2027 (September 2027)", "price": 1600000, "note": "Property Finder page, fetched Nov 2026; launch price AED 1.6M (FAQ says 1.7M); project listed as sold out, construction 62.3% as of 9 Dec 2025 per page", "cfg": [{"label": "1 BR", "cat": "1 BR", "size": "753-922", "from": 1600000}, {"label": "2 BR", "cat": "2 BR", "size": "1120-1491", "from": 2200000}, {"label": "3 BR", "cat": "3 BR", "size": "1551-2936", "from": 3000000}, {"label": "Townhouse", "cat": "Townhouse", "size": "2936-3014", "from": 3000000}, {"label": "4 BR", "cat": "4 BR+", "size": "2440-2797", "from": 6300000}], "plan": "10% down at launch, 80% during construction, 10% on handover (page FAQ elsewhere states 10/40/50)", "am": ["Fitness centre", "Shared pool", "Kids' pool", "BBQ area", "Cafes and restaurants", "Retail", "Viewing decks", "Landscaped grounds"], "hl": "High-rise island living on Dubai Creek mixing apartments, townhouses and a penthouse.", "src": ["https://www.propertyfinder.ae/en/new-projects/emaar-properties/creek-waters"], "sold": true}, {"d": "Emaar", "n": "Nara at The Valley", "a": "The Valley", "loc": "The Valley, near Al Ain Road, Dubai", "status": "Handed over", "handover": "Q4 2024 (30 Dec 2024)", "price": 1900000, "note": "Property Finder page, fetched Nov 2026; page shows conflicting figures (header AED 2.4M, FAQ AED 1,853,178, 3-bed unit listing from AED 1.9M); sold out", "cfg": [{"label": "3 BR Townhouse", "cat": "Townhouse", "size": "1,891-2,099", "from": 1900000}, {"label": "4 BR Townhouse", "cat": "Townhouse", "size": "2,139-2,249", "from": 2100000}], "plan": "12% down at launch, 38% during construction, 50% on handover", "am": ["Maids room", "Central A/C", "Balcony", "Private garden", "Shared pool", "Security", "Covered parking", "Built-in wardrobes", "Pets allowed"], "hl": "3 and 4-bedroom townhouses in a gated family community near parks and sports facilities.", "src": ["https://www.propertyfinder.ae/en/new-projects/emaar-properties/nara-at-the-valley"], "sold": true}, {"d": "Emaar", "n": "Montura at Grand Polo", "a": "Grand Polo Club & Resort", "loc": "Grand Polo Club and Resort, Dubai Investment Park 2, Dubai", "status": "Off-plan", "handover": "Q2 2029 (30 June 2029)", "price": 7060000, "note": "Property Finder page, fetched Nov 2026; unit-type prices not listed", "cfg": [{"label": "4 BR Villa", "cat": "Villa", "size": "3,838-3,842", "from": null}, {"label": "5 BR Villa", "cat": "Villa", "size": "5,115-5,157", "from": null}], "plan": "10% down at launch, 70% during construction (one option in 7 instalments), 20% on handover", "am": ["Polo fields and equestrian facilities", "Indoor and outdoor pools", "Gym and spa", "Clubhouse", "Restaurants", "Tennis and padel courts", "Walking trails", "Children's play areas", "24/7 concierge", "EV charging"], "hl": "4 and 5-bedroom villas with private gardens in an equestrian and polo-themed community.", "src": ["https://www.propertyfinder.ae/en/new-projects/emaar-properties/montura-at-grand-polo"], "sold": false}, {"d": "Emaar", "n": "Palace By The Beach", "a": "Dubai Marina", "loc": "Marsa Beach, Dubai Marina, near Marina Walk", "status": "Off-plan", "handover": "Q1 2031 (15 March 2031)", "price": null, "note": "Property Finder page, fetched Nov 2026; prices, sizes and payment plan listed as coming soon", "cfg": [{"label": "1 BR", "cat": "1 BR", "size": null, "from": null}, {"label": "2 BR", "cat": "2 BR", "size": null, "from": null}, {"label": "3 BR", "cat": "3 BR", "size": null, "from": null}, {"label": "4 BR", "cat": "4 BR+", "size": null, "from": null}], "plan": null, "am": ["Indoor swimming pool", "Landscaped gardens", "CCTV security", "Gymnasium", "Restaurants", "Children's play area", "Private beachfront access", "Infinity pools"], "hl": "861 resort-style apartments in one building with marina and Arabian Gulf views.", "src": ["https://www.propertyfinder.ae/en/new-projects/emaar-properties/palace-by-the-beach"], "sold": false}, {"d": "Nakheel", "n": "Palm Central Private Residences Phase 2", "a": "Palm Jebel Ali", "loc": "Palm Jebel Ali waterfront, Dubai", "status": "Off-plan", "handover": "Q3 2030", "price": 2700000, "note": "Property Finder Palm Central Private Residences Phase 2 page, launch price as fetched 2026-11-20; prices and availability may change; page handover text inconsistent (FAQ says 2027); The National (2026-06-24) quotes 1BR from Dh2.7M, townhouses from Dh14.9M vs 4BR townhouse AED 12M on PF", "cfg": [{"label": "1 BR", "cat": "1 BR", "size": "827", "from": 2700000}, {"label": "2 BR", "cat": "2 BR", "size": "1215-1466", "from": 4300000}, {"label": "3 BR", "cat": "3 BR", "size": "2039", "from": 7500000}, {"label": "Townhouse", "cat": "Townhouse", "size": "3269-3990 (4 BR)", "from": 12000000}, {"label": "Townhouse", "cat": "Townhouse", "size": "5041 (5 BR)", "from": 19000000}], "plan": "20/40/40: 20% at launch, 40% during construction, 40% on handover", "am": ["Infinity pool with Gulf views", "Gymnasium", "Tennis courts", "Yoga room", "Golf club and clubhouse", "Barbecue areas", "Children's play area"], "hl": "Waterfront semi-furnished apartments and townhouses with direct beach access on Palm Jebel Ali.", "src": ["https://www.propertyfinder.ae/en/new-projects/nakheel/palm-central-private-residences-phase-2", "https://www.thenationalnews.com/business/property/2026/06/24/nakheel-launches-222-homes-for-sale-at-palm-jebel-ali-with-prices-from-dh27m/", "https://www.propertyfinder.ae/en/new-projects/dev/nakheel"], "sold": false}, {"d": "Nakheel", "n": "Bay Estate", "a": "Dubai Islands", "loc": "Island E, Dubai Islands", "status": "Off-plan", "handover": "December 2029", "price": 5000000, "note": "Property Finder Bay Estate page, launch price as fetched 2026-11-20; prices and availability may change. Bedroom-to-price pairing follows the order listed on the page, so confirm each unit type with me.", "cfg": [{"label": "3 BR Townhouse", "cat": "Townhouse", "size": null, "from": 5000000}, {"label": "4 BR Townhouse", "cat": "Townhouse", "size": null, "from": 6800000}, {"label": "5 BR Villa", "cat": "Villa", "size": null, "from": 17000000}, {"label": "6 BR Villa", "cat": "Villa", "size": null, "from": 22000000}, {"label": "7 BR Villa", "cat": "Villa", "size": null, "from": 70000000}], "plan": "25/55/20: 25% at launch, 55% during construction, 20% on handover", "am": ["Restaurants and dining", "Landscaped gardens", "Gymnasium", "Indoor swimming pool", "CCTV security", "Children's play area", "Private beachfront access", "Marina-side promenades"], "hl": "First residential community on low-density Island E, offering 3 to 7 bedroom townhouses and villas (3BR and 4BR townhouses; 5, 6 and 7BR villas, in that order of listed prices).", "src": ["https://www.propertyfinder.ae/en/new-projects/nakheel/bay-estate"], "sold": false}, {"d": "Nakheel", "n": "Podium Villas", "a": "Palm Jumeirah", "loc": "Palm Beach Towers, Palm Jumeirah", "status": "Off-plan", "handover": "Q1 2027", "price": 5300000, "note": "Property Finder Podium Villas page, launch price as fetched 2026-11-20; prices and availability may change; unit tables marked coming soon. Bedroom-to-price pairing follows the order listed on the page, so confirm each unit type with me.", "cfg": [{"label": "2 BR Villa", "cat": "Villa", "size": null, "from": 5300000}, {"label": "3 BR Villa", "cat": "Villa", "size": null, "from": 8200000}, {"label": "4 BR Villa", "cat": "Villa", "size": null, "from": 13000000}], "plan": null, "am": ["Indoor swimming pool", "Landscaped gardens", "CCTV security", "Gymnasium", "Restaurants", "Children's play area"], "hl": "16 beachfront villas built into the podium levels of two Palm Beach Towers buildings (2, 3 and 4 BR from listed prices in that order).", "src": ["https://www.propertyfinder.ae/en/new-projects/nakheel/podium-villas"], "sold": false}, {"d": "Nakheel", "n": "Ibis at Jumeirah Village Circle", "a": "Jumeirah Village Circle", "loc": "District 11, Jumeirah Village Circle", "status": "Off-plan", "handover": "Q4 2027", "price": 600000, "note": "Property Finder Ibis at JVC page, launch price as fetched 2026-11-20; prices and availability may change; sizes and unit prices listed as coming soon", "cfg": [{"label": "Studio", "cat": "Studio", "size": null, "from": null}, {"label": "1 BR", "cat": "1 BR", "size": null, "from": null}, {"label": "2 BR", "cat": "2 BR", "size": null, "from": null}], "plan": null, "am": ["Fitness center", "Temperature-controlled pool with children's area", "Landscaped gardens", "Children's play areas", "Jogging and walking tracks", "24/7 security and concierge", "Smart home integration", "Multi-purpose community hall", "BBQ areas", "Business center"], "hl": "16-storey freehold apartment building with floor-to-ceiling windows and balconies.", "src": ["https://www.propertyfinder.ae/en/new-projects/nakheel/ibis"], "sold": false}, {"d": "Nakheel", "n": "Palm Springs", "a": "Palm Jebel Ali", "loc": "Hessyan First, Palm Jebel Ali waterfront", "status": "Off-plan", "handover": "October 2030", "price": 3800000, "note": "Property Finder Palm Springs page, launch price as fetched 2026-11-20; prices and availability may change; 'Studio' label on a 3,115 sqft townhouse on page looks inconsistent, omitted", "cfg": [{"label": "Townhouse", "cat": "Townhouse", "size": "2329 (3 BR)", "from": 3800000}, {"label": "Townhouse", "cat": "Townhouse", "size": "2672 (4 BR)", "from": 4600000}, {"label": "Villa", "cat": "Villa", "size": "4041 (4 BR)", "from": 7000000}, {"label": "Villa", "cat": "Villa", "size": "4921 (5 BR)", "from": 8900000}], "plan": "10/50/40: 10% at launch, 50% during construction in 6 instalments, 40% on handover", "am": ["Indoor swimming pool", "Landscaped gardens", "Gymnasium", "Children's play area", "CCTV security", "Dedicated parking"], "hl": "Townhouses and villas on the Palm Jebel Ali waterfront with open-plan layouts and some sea or island views.", "src": ["https://www.propertyfinder.ae/en/new-projects/nakheel/palm-springs"], "sold": false}, {"d": "Sobha Realty", "n": "Sobha Hartland II", "a": "Sobha Hartland", "loc": "Bukadra / Mohammed Bin Rashid City, Dubai", "status": "Under construction", "handover": "Q4 2026", "price": 16000000, "note": "Property Finder project page (Sobha Hartland Phase 2), fetched 2026-11-20; page shows 16M AED (16,203,560 in another section) and marks it sold out; page has internal inconsistencies on construction progress", "cfg": [{"label": "Villa", "cat": "Villa", "size": "8438", "from": 16000000}], "plan": "10% down payment at launch, 70% during construction, 20% on handover", "am": ["Infinity pool", "Tennis court", "Walking, jogging and cycling tracks", "Community parks and kids' play areas", "Wellness centres and fitness facilities", "Retail outlets, restaurants and cafes", "24/7 security and CCTV"], "hl": "Villas and residences of 5 and 6 bedrooms with resident access to the Blue Lagoon, per Property Finder.", "src": ["https://www.propertyfinder.ae/en/new-projects/sobha-real-estate-llc/sobha-hartland-ii"], "sold": true}, {"d": "Sobha Realty", "n": "Sobha SeaHaven", "a": "Dubai Harbour", "loc": "Dubai Harbour, Dubai (views of Palm Jumeirah, Ain Dubai and Burj Al Arab)", "status": "Under construction", "handover": "Q2 2028", "price": 3300000, "note": "Property Finder project page, fetched 2026-11-20; launch price, page marks developer stock sold out; handover text inconsistent (Q2 2028 in header/timeline, Q2 2026 in About)", "cfg": [{"label": "1 BR", "cat": "1 BR", "size": "860-1106", "from": 3300000}, {"label": "2 BR", "cat": "2 BR", "size": "1281-1474", "from": 5600000}, {"label": "3 BR", "cat": "3 BR", "size": "2029-2458", "from": 9300000}], "plan": "Option: 20% at launch, 40% during construction, 40% on handover; alternative: 20% at launch, 20% during construction, 60% on handover", "am": ["Shared pool", "Shared gym", "Children's play area", "Yoga zone", "Indoor games area", "Club lounge", "Concierge and security", "F&B retail", "Balconies", "Public beaches"], "hl": "Freehold waterfront apartment development of 4 buildings with views of Palm Jumeirah, Ain Dubai and Burj Al Arab.", "src": ["https://www.propertyfinder.ae/en/new-projects/sobha-real-estate-llc/sobha-seahaven"], "sold": true}, {"d": "Sobha Realty", "n": "Sobha Orbis", "a": "Motor City", "loc": "Motor City, near Mohammed bin Zayed Road and Al Qudra Road", "status": "Under construction", "handover": "Q4 2028", "price": 985000, "note": "Property Finder project page, fetched 2026-11-20; launch price, page marks units out of stock; handover shown as Q4 2027 in About section", "cfg": [{"label": "1 BR", "cat": "1 BR", "size": "538-580", "from": 985000}, {"label": "2 BR", "cat": "2 BR", "size": "984-988", "from": 1700000}], "plan": "20% down payment, 60% during construction (6 instalments), 20% on handover; alternative 20% down and 80% during construction (5 instalments)", "am": ["Gymnasium", "Indoor swimming pool", "Landscaped gardens", "Retail facilities", "Cafes and restaurants"], "hl": "Freehold apartment towers in Motor City with a proposed metro station stated as adjacent; sales began 1 June 2024.", "src": ["https://www.propertyfinder.ae/en/new-projects/sobha-real-estate-llc/sobha-orbis"], "sold": true}, {"d": "Sobha Realty", "n": "Sobha Elwood", "a": "Dubailand", "loc": "Dubailand, access via Sheikh Zayed Bin Hamdan Al Nahyan Street and Emirates Road", "status": "Under construction", "handover": "Q2 2028", "price": 7930000, "note": "Dubizzle and Bayut project pages, fetched 2026-11-20; launch 'from' price for villas", "cfg": [{"label": "Villa", "cat": "Villa", "size": "6190-6998", "from": 7930000}], "plan": "20% down payment, 40% pre-handover during construction, 40% on handover", "am": ["Gated low-density community", "Over 10,000 trees", "Forest trails and walking paths", "Children's play zones", "Lap pool", "Splash pads", "Clubhouse amenities", "Wellness facilities", "Sports cafe and dining"], "hl": "Low-density gated villa community with about 47% open space and forest-themed parks, 14% complete per Dubizzle.", "src": ["https://dubai.dubizzle.com/new-projects/sobha-group/sobha-elwood/", "https://www.bayut.com/area-guides/sobha-elwood"], "sold": false}, {"d": "Sobha Realty", "n": "Sobha Central", "a": "Jebel Ali 1", "loc": "Jebel Ali 1, on Sheikh Zayed Road, near Jebel Ali Metro", "status": "Off-plan", "handover": "Q4 2031", "price": 1779057, "note": "Property Finder project page, fetched 2026-11-20; page lists sales start 31 Mar 2026, shows out of stock, and gives conflicting handover dates (Q4 2031, March 2031, Q2 2030)", "cfg": [{"label": "1 BR", "cat": "1 BR", "size": "565-791", "from": 1800000}, {"label": "2 BR", "cat": "2 BR", "size": "852-1554", "from": 2500000}, {"label": "3 BR", "cat": "3 BR", "size": "1862", "from": 5800000}], "plan": null, "am": ["Yoga room", "Indoor swimming pool", "Jacuzzi and steam", "Landscaped gardens", "Gymnasium", "Restaurants and retail", "Children's play area", "Prayer hall", "Co-working areas", "Business center"], "hl": "Freehold mixed-use development with a retail mall and office areas, stated to be 2 minutes from Sheikh Zayed Road and 4 minutes from Jebel Ali Metro.", "src": ["https://www.propertyfinder.ae/en/new-projects/sobha-realty/sobha-central"], "sold": true}, {"d": "Damac", "n": "Damac Lagoons - Lagoon Views 13", "a": "Damac Lagoons", "loc": "Damac Lagoons, Dubailand; Dubai Polo & Equestrian Club about 10 min away", "status": "Off-plan", "handover": "Q4 2027", "price": 1447000, "note": "Property Finder project page (fetched Nov 2026); launch price", "cfg": [{"label": "1 BR", "cat": "1 BR", "size": "698", "from": 1447000}, {"label": "2 BR", "cat": "2 BR", "size": "1152", "from": null}], "plan": "20% at launch, 50% during construction in 11 instalments, 30% on handover", "am": ["Infinity pool", "Kids' pool", "Gym", "Yoga area", "Zen garden", "Steam and sauna", "Residence lounge and library", "Outdoor cinema", "BBQ area", "Kids' play area"], "hl": "13-storey apartment building within the family-oriented Damac Lagoons community.", "src": ["https://www.propertyfinder.ae/en/new-projects/damac-properties/damac-lagoons-views-13"], "sold": false}, {"d": "Damac", "n": "Damac Islands Phase 2", "a": "Damac Islands", "loc": "Dubailand, at Al Qudra Road and Emirates Road", "status": "Off-plan", "handover": "June 2030", "price": 2800000, "note": "Property Finder project page (fetched Nov 2026); launch price; unit prices not listed", "cfg": [{"label": "Townhouse", "cat": "Townhouse", "size": "2208-3178", "from": null}, {"label": "Villa", "cat": "Villa", "size": "4440-17078", "from": null}], "plan": "20% at launch, 55% during construction, 25% on handover", "am": ["Beach club", "Infinity pool", "Private marina berths", "Golf club and clubhouse", "Gymnasium", "Yoga room", "Children's play area", "Retail facilities"], "hl": "Island-style cluster planning with 4- and 5-bed townhouses and 6- and 7-bed villas.", "src": ["https://www.propertyfinder.ae/en/new-projects/damac-properties/damac-islands-phase-2"], "sold": false}, {"d": "Damac", "n": "Damac Bay by Cavalli", "a": "Dubai Harbour", "loc": "Dubai Harbour, off King Salman Bin Abdulaziz Al Saud Street", "status": "Under construction", "handover": "Q1 2027", "price": 3939000, "note": "Property Finder project page (fetched Nov 2026); sold out, launch price", "cfg": [{"label": "1 BR", "cat": "1 BR", "size": null, "from": 3900000}, {"label": "2 BR", "cat": "2 BR", "size": null, "from": 6100000}, {"label": "3 BR", "cat": "3 BR", "size": null, "from": null}, {"label": "Duplex", "cat": "Duplex / Penthouse", "size": null, "from": 11000000}], "plan": "20% at launch, 40% during construction, 40% on handover", "am": ["Gymnasium", "Shared pool", "Shared spa", "Private pool", "Private jacuzzi", "Private garden", "Central A/C", "Balcony"], "hl": "Cavalli-designed nautical interiors with sea views claimed for all units.", "src": ["https://propertyfinder.ae/en/new-projects/damac-properties/damac-bay-cavalli"], "sold": true}, {"d": "Damac", "n": "Violet 2", "a": "Damac Hills 2", "loc": "Violet cluster, Damac Hills 2, opposite Water Town near Al Qudra Road", "status": "Under construction", "handover": "Q1 2027", "price": 2000000, "note": "Property Finder project page (fetched Nov 2026); sold out; page shows 1.958M to 2M", "cfg": [{"label": "Townhouse", "cat": "Townhouse", "size": "2352", "from": 2000000}], "plan": "20% at launch, 40% during construction, 40% on handover", "am": ["Water Town wave pool and lazy river", "Sports Town courts", "Cycle tracks", "Jogging paths", "Green spaces"], "hl": "4-bedroom freehold townhouses in a single layout.", "src": ["https://www.propertyfinder.ae/en/new-projects/damac-properties/violet-phase-2"], "sold": true}, {"d": "Imtiaz Developments", "n": "Cove Boulevard", "a": "Dubailand", "loc": null, "status": "Off-plan", "handover": "Q4 2028 (30 Oct 2028)", "price": 1865150, "note": "Property Finder, fetched 20 Nov 2026. Launch price; project shows as sold out on the portal and unit sizes differ between sections of the page.", "cfg": [{"label": "Studio", "cat": "Studio", "size": "about 360", "from": null}, {"label": "1 BR", "cat": "1 BR", "size": "about 740", "from": null}, {"label": "2 BR", "cat": "2 BR", "size": "about 1,170", "from": null}, {"label": "3 BR", "cat": "3 BR", "size": "about 1,400", "from": null}], "plan": "Option 1: 70% during construction, 30% on handover. Option 2: 60% during construction, 40% on handover.", "am": ["Family swimming pool", "Rooftop infinity pool", "Lap lanes", "Fully equipped gym", "Yoga and meditation studio", "Kids' play area", "Sports courts", "Zen garden", "Jacuzzi", "Club room", "Running track", "Outdoor cinema", "Co-working spaces", "Social lounges", "24/7 security and concierge"], "hl": "Part of the Imtiaz Cove series in the Dubai Land Residence Complex.", "src": ["https://propertyfinder.ae/en/new-projects/imtiaz-developments/cove-boulevard"], "sold": true}, {"d": "Imtiaz Developments", "n": "Cove Grand", "a": "Dubailand", "loc": "Dubai Land Residence Complex", "status": "Under construction", "handover": "Q4 2027 (Dec 15, 2027)", "price": 765259, "note": "Property Finder project page, fetched 2026-11-20; page shows inconsistent figures, treat as indicative; launch price 765K, sold out on portal", "cfg": [{"label": "Studio", "cat": "Studio", "size": "409-719", "from": 741000}, {"label": "1 BR", "cat": "1 BR", "size": "702-919", "from": 1100000}, {"label": "2 BR", "cat": "2 BR", "size": null, "from": 1400000}, {"label": "3 BR", "cat": "3 BR", "size": null, "from": 2300000}], "plan": "Option 1: 20% at launch, 30% during construction, 50% on handover. Option 2: 20% at launch, 35% during construction, 15% on handover, 30% post-handover.", "am": ["Infinity pool", "Spa and sauna", "Rooftop garden", "Indoor and outdoor gyms", "Yoga and meditation zones", "Cinema room", "Co-working spaces", "BBQ zones", "Children's play area", "Underground parking with EV charging"], "hl": "Fully furnished smart-home apartments with rooftop skyline views; project listed as sold out on the portal.", "src": ["https://www.propertyfinder.ae/en/new-projects/imtiaz-developments/cove-grand"], "sold": true}, {"d": "Imtiaz Developments", "n": "Cove Edition 5", "a": "Dubailand", "loc": "Dubailand, Dubai (no street address given)", "status": "Off-plan", "handover": "Q2 2027", "price": 682000, "note": "Property Finder project page, fetched 2026-11-20; page shows inconsistent figures, treat as indicative; header shows 735K launch price, community range 605K-1.4M", "cfg": [{"label": "1 BR", "cat": "1 BR", "size": null, "from": null}, {"label": "2 BR", "cat": "2 BR", "size": "845", "from": null}, {"label": "3 BR", "cat": "3 BR", "size": "1,307", "from": null}], "plan": "Plan 1: 20% at launch, 30% during construction (6 instalments), 50% on handover. Plan 2: 20% at launch, 35% during construction (5 instalments), 15% on handover, 30% post-handover.", "am": ["Infinity-edge pool", "Children's splash pad", "Gym", "Yoga and meditation studio", "Spa", "Cinema room", "BBQ area", "Rooftop terrace", "Co-working spaces", "EV charging"], "hl": "Part of Imtiaz's Dubailand series, about 20-25 minutes from Downtown Dubai, Business Bay and the airport per the page.", "src": ["https://www.propertyfinder.ae/en/new-projects/imtiaz-developments/cove-edition-phase-5-by-imtiaz"], "sold": false}, {"d": "Imtiaz Developments", "n": "Sunset Bay 4", "a": "Dubai Islands", "loc": "Dubai Islands, Dubai", "status": "Under construction", "handover": "Q2 2027 (May 15, 2027)", "price": 1908481, "note": "Property Finder project page, fetched 2026-11-20; page shows inconsistent figures, treat as indicative; header shows AED 3.6M, description/FAQ AED 1,908,481; sold out on portal", "cfg": [{"label": "1 BR", "cat": "1 BR", "size": "943-1047", "from": 1900000}, {"label": "2 BR", "cat": "2 BR", "size": "1356-2185", "from": 2600000}, {"label": "3 BR", "cat": "3 BR", "size": "2058", "from": 4400000}], "plan": "Option 1: 20% at launch, 40% during construction, 40% on handover. Option 2: same split with construction portion in 5 instalments.", "am": ["Rooftop infinity pool", "Private jacuzzis", "Gym and pilates studio", "Sauna and steam rooms", "Outdoor yoga area", "Children's play area", "Clubhouse", "BBQ area", "Covered parking with EV charging", "24/7 concierge and security"], "hl": "Boutique low-rise waterfront project with sea and skyline views and direct beach access.", "src": ["https://www.propertyfinder.ae/en/new-projects/imtiaz-developments/sunset-bay-phase-4-by-imtia"], "sold": true}, {"d": "Imtiaz Developments", "n": "Beach Walk 4", "a": "Dubai Islands", "loc": "Dubai Islands, Dubai (no street address given)", "status": "Off-plan", "handover": "Q2 2027", "price": 1942000, "note": "Property Finder Imtiaz Dubai Islands listing, fetched 2026-11-20; launch price only", "cfg": [{"label": "1 BR", "cat": "1 BR", "size": null, "from": null}, {"label": "2 BR", "cat": "2 BR", "size": null, "from": null}, {"label": "3 BR", "cat": "3 BR", "size": null, "from": null}], "plan": null, "am": [], "hl": null, "src": ["https://www.propertyfinder.ae/en/new-projects/dev/imtiaz-developments/dubai/dubai-islands"], "sold": false}, {"d": "Imtiaz Developments", "n": "Cotier House 2", "a": "Dubai Islands", "loc": "Dubai Islands (formerly Deira Islands), Dubai", "status": "Under construction", "handover": "Q2 2027 (Apr 15, 2027)", "price": 3326000, "note": "Property Finder project page, fetched 2026-11-20; page shows inconsistent figures, treat as indicative; header AED 3.3M, description AED 2.1M, FAQ AED 3,326,000; sold out on portal", "cfg": [{"label": "1 BR", "cat": "1 BR", "size": "965", "from": 3300000}, {"label": "2 BR", "cat": "2 BR", "size": "1345", "from": 5100000}, {"label": "3 BR", "cat": "3 BR", "size": "1835", "from": null}, {"label": "Duplex", "cat": "Duplex / Penthouse", "size": "2455-3269", "from": null}, {"label": "Penthouse", "cat": "Duplex / Penthouse", "size": "3352", "from": null}, {"label": "Townhouse", "cat": "Townhouse", "size": "2021", "from": null}], "plan": "20% at launch, 40% during construction (5 instalments), 40% on handover.", "am": ["Private beach and marina access", "Indoor and outdoor pools", "Gym", "Sauna, steam and spa", "Yoga and meditation studios", "Rooftop terrace and BBQ areas", "Cinema room", "Kids' play areas", "24/7 concierge and valet parking", "EV charging"], "hl": "Coastal Dubai Islands community with sea views and smart-home systems.", "src": ["https://www.propertyfinder.ae/en/new-projects/imtiaz-developments/cotier-house-phase-2-by-imtiaz"], "sold": true}, {"d": "Imtiaz Developments", "n": "Pearl House III", "a": "Jumeirah Village Circle", "loc": "JVC District 11, Dubai", "status": "Check status", "handover": "Reported Q1 2026, confirm current status", "price": 630000, "note": "Property Finder project page, fetched 2026-11-20; page shows inconsistent figures, treat as indicative; header 710K, elsewhere 630K; status contradictory on page", "cfg": [{"label": "Studio", "cat": "Studio", "size": null, "from": 630000}, {"label": "1 BR", "cat": "1 BR", "size": "700", "from": 930000}, {"label": "2 BR", "cat": "2 BR", "size": "1,180", "from": 1500000}], "plan": "20% at launch, 40% during construction, 40% on handover.", "am": ["Club room", "EV charging", "Kids' playground", "Rooftop pool", "Spa and wellness center", "Gym", "Landscaped gardens"], "hl": "JVC building with spacious balconies, about 5 minutes from Circle Mall per the page.", "src": ["https://www.propertyfinder.ae/en/new-projects/imtiaz-developments/pearl-house-3"], "sold": false}, {"d": "Imtiaz Developments", "n": "Westwood Grande", "a": "Jumeirah Village Circle", "loc": "Jumeirah Village Circle", "status": "Handed over", "handover": "Early handover announced Dec 2024", "price": null, "note": "Gulf News report, Dec 2024. No unit or pricing details were collected.", "cfg": [], "plan": null, "am": [], "hl": null, "src": ["https://gulfnews.com/business/property/imtiaz-developments-marks-early-handover-of-westwood-grande-in-jvc-dubai-1.1734087113361"], "sold": false}, {"d": "Tarrad Development", "n": "Celesto Tower (Celesto 1)", "a": "Dubailand", "loc": "Dubai Land Residence Complex (per Property Finder)", "status": "Off-plan", "handover": "Q4 2027", "price": 608000, "note": "Property Finder Tarrad page, fetched 21 Nov 2026. Launch price only; unit types, sizes and amenities not stated. A press release places Celesto 2 and 3 on Sheikh Zayed bin Hamdan Street. Shown as sold out.", "cfg": [{"label": "1 BR", "cat": "1 BR", "size": null, "from": null}], "plan": null, "am": [], "hl": null, "src": ["https://www.propertyfinder.ae/en/new-projects/tarrad-development/tarrad-dubailand-residences", "https://www.gulfconstructiononline.com/ArticleTA?id=329236"], "sold": true}, {"d": "Tarrad Development", "n": "Celesto Tower 2", "a": "Dubailand", "loc": "Dubai Land Residence Complex (per Property Finder)", "status": "Off-plan", "handover": "Q2 2028", "price": 772000, "note": "Property Finder Tarrad page, fetched 21 Nov 2026. Launch price only; unit types, sizes and amenities not stated. A press release places Celesto 2 and 3 on Sheikh Zayed bin Hamdan Street.", "cfg": [], "plan": null, "am": [], "hl": null, "src": ["https://www.propertyfinder.ae/en/new-projects/tarrad-development/tarrad-dubailand-residences", "https://www.gulfconstructiononline.com/ArticleTA?id=329236"], "sold": false}, {"d": "Tarrad Development", "n": "Celesto Tower 3", "a": "Dubailand", "loc": "Dubai Land Residence Complex (per Property Finder)", "status": "Off-plan", "handover": "Q2 2028", "price": 540000, "note": "Property Finder Tarrad page, fetched 21 Nov 2026. Launch price only; unit types, sizes and amenities not stated. A press release places Celesto 2 and 3 on Sheikh Zayed bin Hamdan Street.", "cfg": [], "plan": null, "am": [], "hl": null, "src": ["https://www.propertyfinder.ae/en/new-projects/tarrad-development/tarrad-dubailand-residences", "https://www.gulfconstructiononline.com/ArticleTA?id=329236"], "sold": false}, {"d": "Tarrad Development", "n": "Celesto Tower 4", "a": "Dubailand", "loc": "Dubai Land Residence Complex (per Property Finder)", "status": "Off-plan", "handover": "Q4 2028", "price": 570000, "note": "Property Finder Tarrad page, fetched 21 Nov 2026. Launch price only; unit types, sizes and amenities not stated. A press release places Celesto 2 and 3 on Sheikh Zayed bin Hamdan Street.", "cfg": [], "plan": null, "am": [], "hl": null, "src": ["https://www.propertyfinder.ae/en/new-projects/tarrad-development/tarrad-dubailand-residences", "https://www.gulfconstructiononline.com/ArticleTA?id=329236"], "sold": false}, {"d": "SOL Properties", "n": "Oakley Square Residences", "a": "Jumeirah Village Circle", "loc": "JVC District 11; developed by Ellington with SOL Properties", "status": "Handed over", "handover": "December 2023", "price": 654000, "note": "Property Finder project page (fetched Nov 2026); sold out, header shows from 750K, studio from 654K", "cfg": [{"label": "Studio", "cat": "Studio", "size": "414-519", "from": 654000}, {"label": "1 BR", "cat": "1 BR", "size": "661-1004", "from": 1000000}, {"label": "2 BR", "cat": "2 BR", "size": "1041-1190", "from": 1400000}], "plan": "20% at launch, 50% during construction, 30% on handover", "am": ["Outdoor pool", "Pool spa", "Cinema room", "Kids play area", "Landscaped areas", "Lobby reception", "EV charging stations", "Parking", "24/7 CCTV"], "hl": "Freehold 3-unit-type apartment building, now sold out on the developer side.", "src": ["https://propertyfinder.ae/en/new-projects/ellington/oakley-square-residences"], "sold": true}, {"d": "SOL Properties", "n": "Sol Park", "a": "Jumeirah Village Circle", "loc": "JVC, Dubai (exact plot not stated)", "status": null, "handover": null, "price": null, "note": "DubaiHaus project page (fetched Nov 2026): price on request; listed handover date 2012-12-31 looks like a data error and was not used", "cfg": [{"label": "Townhouse", "cat": "Townhouse", "size": null, "from": null}], "plan": null, "am": ["Swimming pool", "Fitness centre"], "hl": "Page describes 3- and 4-bedroom townhouse residences.", "src": ["https://www.dubaihaus.com/ui/project_details/1735"], "sold": false}, {"d": "SOL Properties", "n": "Ocean House", "a": "Palm Jumeirah", "loc": "The Crescent, Palm Jumeirah; Ellington with SOL Properties and Northacre", "status": "Off-plan", "handover": "Q4 2026", "price": 23000000, "note": "Property Finder project page (fetched Nov 2026); launch price 23M, FAQ shows 22,580,828; handover dates on page conflict (Q1 2026/Dec 2026/Mar 2025). Unit-level prices on the page conflict, so only the launch price is shown.", "cfg": [{"label": "2 BR", "cat": "2 BR", "size": "1642-4213", "from": null}, {"label": "3 BR", "cat": "3 BR", "size": "3233-4769", "from": null}, {"label": "4 BR", "cat": "4 BR+", "size": "5352-9946", "from": null}, {"label": "Penthouse", "cat": "Duplex / Penthouse", "size": "14036", "from": null}], "plan": "20% at launch, 50% during construction, 30% on handover", "am": ["Pool deck", "Swimming pool", "Gym / health club", "Wellness spa", "Cinema room", "Kids play area", "Retail outlets", "Restaurants and cafes"], "hl": "Single nine-storey building of 88 freehold units with Burj Al Arab, skyline and sea views.", "src": ["https://www.propertyfinder.ae/en/new-projects/ellington/ellington-ocean-house"], "sold": false}, {"d": "SOL Properties", "n": "SOL Bay", "a": "Business Bay", "loc": "Business Bay, Dubai", "status": null, "handover": null, "price": null, "note": "Tanami Properties page (fetched Nov 2026): price 'call us', no date or prices given", "cfg": [{"label": "Studio", "cat": "Studio", "size": "546.8-1469.4", "from": null}, {"label": "1 BR", "cat": "1 BR", "size": "546.8-1469.4", "from": null}, {"label": "2 BR", "cat": "2 BR", "size": "546.8-1469.4", "from": null}], "plan": null, "am": ["Infinity pool", "Swimming pool", "Gymnasium", "Kids play area", "Tennis courts", "Basketball court", "Marina and yacht club", "24/7 security"], "hl": "Glass-facade tower with retail and ample parking per the page.", "src": ["https://tanamiproperties.com/Projects/Sol-Bay"], "sold": false}, {"d": "SOL Properties", "n": "SOL Avenue", "a": "Business Bay", "loc": "Business Bay with direct access to Marasi Drive; 17-floor tower", "status": "Handed over", "handover": "2020", "price": null, "note": "Property Finder area insights page (fetched Nov 2026): rentals only (AED 60K-155K a year), no sale price", "cfg": [{"label": "Studio", "cat": "Studio", "size": "400-500", "from": null}, {"label": "1 BR", "cat": "1 BR", "size": "750-900", "from": null}, {"label": "2 BR", "cat": "2 BR", "size": "1100-1300", "from": null}], "plan": null, "am": ["Rooftop pool", "Gym", "Children's play area", "Sauna and steam rooms", "24-hour security", "Covered parking"], "hl": "Completed freehold mid-rise tower in Business Bay.", "src": ["https://www.propertyfinder.ae/en/area-insights/dubai/compounds-and-towers/business-bay-sol-avenue"], "sold": false}, {"d": "SOL Properties", "n": "Bloomingdale Villas", "a": "Victory Heights", "loc": "Source places it in Dubai Sports City; 72 townhouses", "status": "Ready", "handover": "27 Jan 2016", "price": 4050000, "note": "FAM Properties page (fetched Nov 2026); status shown as Ready but text says under construction", "cfg": [{"label": "Townhouse", "cat": "Townhouse", "size": "3195-3331", "from": 4050000}], "plan": null, "am": ["Valet parking"], "hl": "72 townhouse units in 4- and 5-bedroom layouts.", "src": ["https://famproperties.com/dubai-sports-city/bloomingdale"], "sold": false}, {"d": "SOL Properties", "n": "Fairmont Residences Solara Tower", "a": "Downtown Dubai", "loc": "Downtown Dubai, about 2 minutes from Burj Khalifa per page", "status": "Off-plan", "handover": "Q3 2027", "price": 2700000, "note": "Property Finder project page (fetched Nov 2026); launch price 2.7M, description text says 2.9M; 10.97% progress at 27 Aug 2025", "cfg": [{"label": "1 BR", "cat": "1 BR", "size": "953-1279", "from": 2700000}, {"label": "2 BR", "cat": "2 BR", "size": "1734-2288", "from": 5600000}, {"label": "3 BR", "cat": "3 BR", "size": "2653-3022", "from": 8900000}, {"label": "4 BR", "cat": "4 BR+", "size": "3753-5570", "from": 18000000}, {"label": "Penthouse", "cat": "Duplex / Penthouse", "size": "19637", "from": 180000000}], "plan": "30% at launch, 30% during construction, 40% on handover", "am": ["Swimming pools", "Pool bar", "Spa with sauna and steam", "Zen gardens", "Padel court", "Golf simulator", "Fitness centre", "Cinema room", "Gourmet dining"], "hl": "55-storey freehold tower developed with Fairmont Hotels & Resorts.", "src": ["https://www.propertyfinder.ae/en/new-projects/sol-properties/fairmont-residences-solara-tower", "https://www.propertyfinder.ae/en/new-projects/dev/sol-properties/dubai"], "sold": false}, {"d": "SOL Properties", "n": "West Crescent", "a": "Palm Jumeirah", "loc": "Palm Jumeirah", "status": "Announced", "handover": null, "price": null, "note": "Zawya press release. Announced as an ultra-luxury project; no unit or pricing details published.", "cfg": [], "plan": null, "am": [], "hl": "Announced ultra-luxury project on Palm Jumeirah.", "src": ["https://www.zawya.com/en/press-release/companies-news/sol-properties-announces-upcoming-projects-with-anticipated-aed-12bln-gdv-dsxoslij"], "sold": false}]};
  var PHONE="971588377861";
  function wa(t){return "https://wa.me/"+PHONE+"?text="+encodeURIComponent(t)}
  function fmt(n){return "AED "+Math.round(n).toLocaleString("en-US")}
  function esc(s){return String(s==null?"":s).replace(/[&<>"']/g,function(c){return {"&":"&amp;","<":"&lt;",">":"&gt;",'"':"&quot;","'":"&#39;"}[c]})}
  function money(n){if(n==null)return "On request";if(n>=1e6){return "AED "+(Math.round(n/1e4)/100)+"M"}return "AED "+Math.round(n/1000)+"K"}
  document.querySelectorAll("[data-wa]").forEach(function(a){a.href=wa(a.getAttribute("data-wa"))});

  var places=DATA.places,projects=DATA.projects;
  function place(n){for(var i=0;i<places.length;i++)if(places[i].n===n)return places[i];return null}
  function mapLink(p){
    if(p.c)return {href:"https://www.google.com/maps/@?api=1&map_action=map&center="+p.la+","+p.lo+"&zoom=15&basemap=satellite",label:"View on Google Maps satellite"};
    return {href:"https://www.google.com/maps/search/?api=1&query="+encodeURIComponent((p.q||p.n)+", Dubai"),label:"Open in Google Maps"};
  }
  function fromPrice(q){
    if(q.price!=null)return q.price;
    var m=null;q.cfg.forEach(function(c){if(c.from!=null&&(m==null||c.from<m))m=c.from});return m;
  }

  /* ---- state and filters ---- */
  var devFilter="all",typeFilter="all",hideSold=false,selected=null;
  function visible(q){
    if(devFilter!=="all"&&q.d!==devFilter)return false;
    if(typeFilter!=="all"&&!q.cfg.some(function(c){return c.cat===typeFilter}))return false;
    if(hideSold&&q.sold)return false;
    return true;
  }
  function projectsAt(n){return projects.filter(function(q){return q.a===n&&visible(q)})}
  function filtersActive(){return devFilter!=="all"||typeFilter!=="all"||hideSold}

  /* ---- map ---- */
  var NS="http://www.w3.org/2000/svg";
  function px(lo){return (lo-54.92)*1700}
  function py(la){return (25.34-la)*1700}
  function el(t,at,p){var e=document.createElementNS(NS,t);for(var k in at)e.setAttribute(k,at[k]);if(p)p.appendChild(e);return e}
  var svg=document.getElementById("map");
  var coast=[[54.92,24.915],[54.98,24.96],[55.03,25.0],[55.08,25.04],[55.125,25.07],[55.16,25.10],[55.20,25.135],[55.235,25.18],[55.26,25.225],[55.295,25.265],[55.335,25.295],[55.38,25.325],[55.43,25.35]];
  var cp=coast.map(function(p){return px(p[0]).toFixed(0)+","+py(p[1]).toFixed(0)});
  el("path",{d:"M"+cp.join(" L")+" L930,-30 L930,800 L-10,800 L-10,"+py(24.915).toFixed(0)+" Z",fill:"var(--land)",stroke:"var(--road)","stroke-width":2},svg);
  var road=coast.slice(2,10).map(function(p){return px(p[0]+0.012).toFixed(0)+","+py(p[1]-0.022).toFixed(0)});
  el("path",{d:"M"+road.join(" L"),fill:"none",stroke:"var(--road)","stroke-width":5,"stroke-dasharray":"2 10","stroke-linecap":"round"},svg);
  el("path",{d:"M"+px(55.30)+","+py(25.268)+" L"+px(55.322)+","+py(25.24)+" L"+px(55.335)+","+py(25.215),fill:"none",stroke:"var(--sea)","stroke-width":13,"stroke-linecap":"round"},svg);
  var bx=px(55.150),by=py(25.092),cx=px(55.139),cy=py(25.112);
  el("line",{x1:bx,y1:by,x2:cx,y2:cy,stroke:"var(--land)","stroke-width":8,"stroke-linecap":"round"},svg);
  for(var i=-3;i<=3;i++){var ang=-2.5+i*0.32;el("line",{x1:cx,y1:cy,x2:cx+Math.cos(ang)*30,y2:cy+Math.sin(ang)*30,stroke:"var(--land)","stroke-width":5,"stroke-linecap":"round"},svg)}
  el("path",{d:"M"+(cx-38)+","+(cy+9)+" A45 45 0 0 1 "+(cx+26)+","+(cy-34),fill:"none",stroke:"var(--land)","stroke-width":4,"stroke-linecap":"round"},svg);
  /* Palm Jebel Ali: simple palm silhouette */
  var jx=px(54.955),jy=py(24.99);
  for(var k=-4;k<=4;k++){var an=-1.57+k*0.34;el("line",{x1:jx,y1:jy,x2:jx+Math.cos(an)*36,y2:jy+Math.sin(an)*36,stroke:"var(--land)","stroke-width":5,"stroke-linecap":"round"},svg)}
  var t1=el("text",{x:150,y:230,class:"maptxt"},svg);t1.textContent="Arabian Gulf";
  var t2=el("text",{x:24,y:760,class:"maptxt"},svg);t2.textContent="← Abu Dhabi";
  var t3=el("text",{x:720,y:46,class:"maptxt"},svg);t3.textContent="Sharjah →";
  var t4=el("text",{x:250,y:560,class:"maptxt","font-size":15,transform:"rotate(-37 250 560)"},svg);t4.textContent="Sheikh Zayed Rd";
  var markers={};
  places.forEach(function(p){
    var g=el("g",{class:"mk",tabindex:0,role:"button","aria-label":p.n,transform:"translate("+px(p.lo).toFixed(0)+","+py(p.la).toFixed(0)+")"},svg);
    var ti=el("title",{},g);ti.textContent=p.n;
    el("circle",{class:"halo",r:20},g);el("circle",{class:"dot",r:9},g);
    var tx=el("text",{x:16,y:-14},g);tx.textContent=p.n.replace(" (TECOM)","");tx.style.display="none";
    g.addEventListener("click",function(){select(p)});
    g.addEventListener("keydown",function(e){if(e.key==="Enter"||e.key===" "){e.preventDefault();select(p)}});
    markers[p.n]={g:g,t:tx,p:p};
  });
  function refreshMarkers(){
    places.forEach(function(p){
      var n=projectsAt(p.n).length,all=projects.filter(function(q){return q.a===p.n}).length;
      var m=markers[p.n].g;
      m.classList.toggle("has",n>0);
      m.classList.toggle("none",all===0);
      m.classList.toggle("off",filtersActive()&&n===0);
    });
  }
  function panelDefault(){
    var n=places.filter(function(p){return projectsAt(p.n).length>0}).length;
    document.getElementById("panel").innerHTML='<h3>Pick a community</h3><p class="meta" style="margin-top:8px">'+n+' communities have projects for the current filters. Tap a marker to see them.</p>';
  }
  function select(p){
    selected=p;
    Object.keys(markers).forEach(function(k){var m=markers[k],on=m.p===p;m.g.classList.toggle("sel",on);m.t.style.display=on?"":"none";if(on)svg.appendChild(m.g)});
    var props=projectsAt(p.n);
    var h='<h3>'+esc(p.n)+'</h3>';
    if(p.d.length)h+='<div class="dev">Master developer: '+esc(p.d.join(" and "))+'</div>';
    h+='<h4>Projects here ('+props.length+')</h4>';
    if(props.length){
      h+='<ul class="plist">'+props.map(function(q){return '<li><button type="button" data-open="'+projects.indexOf(q)+'"><span class="pd">'+esc(q.d)+'</span><span class="pn">'+esc(q.n)+'</span><span class="meta">'+esc(q.handover?("Handover: "+q.handover):(q.status||""))+'</span><span class="go">View full details</span></button></li>'}).join("")+'</ul>';
    }else{
      h+='<p class="meta">No project matches the current filters here. Message me for what is available.</p>';
    }
    var ml=mapLink(p);
    h+='<div class="acts"><a class="btn solid" target="_blank" rel="noopener" href="'+ml.href+'">'+ml.label+'</a><a class="btn wa" target="_blank" rel="noopener" href="'+wa("Hello Manigandan, I am interested in properties in "+p.n+".")+'">Ask about '+esc(p.n.replace(" (TECOM)",""))+'</a></div>';
    var pa=document.getElementById("panel");pa.innerHTML=h;
    pa.querySelectorAll("[data-open]").forEach(function(b){b.addEventListener("click",function(){openDetail(projects[+b.getAttribute("data-open")],b)})});
  }

  /* ---- chips ---- */
  var devOrder=["Emaar","Nakheel","Sobha Realty","Damac","Imtiaz Developments","Tarrad Development","SOL Properties"];
  var types=["Studio","1 BR","2 BR","3 BR","4 BR+","Townhouse","Villa","Duplex / Penthouse"];
  var typeLabel={"Studio":"Studio","1 BR":"1 BHK","2 BR":"2 BHK","3 BR":"3 BHK","4 BR+":"4+ BHK","Townhouse":"Townhouse","Villa":"Villa","Duplex / Penthouse":"Duplex / Penthouse"};
  function chipRow(id,items,labelOf,get,set){
    var row=document.getElementById(id);
    items.forEach(function(v){
      var b=document.createElement("button");b.type="button";b.className="chip"+(v==="all"?" on":"");b.textContent=v==="all"?"All":labelOf(v);b.setAttribute("data-v",v);
      b.addEventListener("click",function(){
        set(v);row.querySelectorAll(".chip").forEach(function(c){c.classList.remove("on")});b.classList.add("on");
        if(selected&&projectsAt(selected.n).length===0&&filtersActive()){selected=null;Object.keys(markers).forEach(function(k){markers[k].g.classList.remove("sel");markers[k].t.style.display="none"})}
        refresh();
      });
      row.appendChild(b);
    });
  }
  chipRow("devchips",["all"].concat(devOrder),function(v){return v},function(){return devFilter},function(v){devFilter=v});
  chipRow("typechips",["all"].concat(types),function(v){return typeLabel[v]},function(){return typeFilter},function(v){typeFilter=v});
  var hs=document.getElementById("hidesold");
  hs.addEventListener("click",function(){hideSold=!hideSold;hs.setAttribute("aria-pressed",hideSold);hs.classList.toggle("on",hideSold);refresh()});

  /* ---- cards ---- */
  var cardsEl=document.getElementById("cards");
  function drawCards(){
    cardsEl.innerHTML="";
    var list=projects.filter(visible);
    document.getElementById("count").textContent=list.length+" of "+projects.length+" projects shown";
    if(!list.length){cardsEl.innerHTML='<div class="empty">No project matches these filters. Try another home type or developer, or message me and I will search for you.</div>';return}
    list.forEach(function(q){
      var b=document.createElement("button");b.type="button";b.className="card";
      var cats=[];q.cfg.forEach(function(c){if(cats.indexOf(c.cat)<0)cats.push(c.cat)});
      var fp=fromPrice(q);
      b.innerHTML='<div class="in"><span class="dv">'+esc(q.d)+'</span><h3>'+esc(q.n)+'</h3><div class="meta">'+esc(q.a)+'</div>'+
        '<div class="from">'+(fp!=null?'From '+money(fp):'Price on request')+'</div>'+
        '<div class="tags">'+(q.sold?'<span class="tag2 sold">Sold out on portal</span>':'')+(q.handover?'<span class="tag2">'+esc(q.handover.split(" (")[0])+'</span>':'')+cats.map(function(c){return '<span class="tag2">'+esc(typeLabel[c]||c)+'</span>'}).join("")+'</div></div>'+
        '<div class="more">View full details</div>';
      b.addEventListener("click",function(){openDetail(q,b)});
      cardsEl.appendChild(b);
    });
  }
  function refresh(){refreshMarkers();drawCards();if(selected)select(selected);else panelDefault()}

  /* ---- detail sheet ---- */
  var ov=document.getElementById("ov"),sheet=document.getElementById("sheet"),lastFocus=null;
  function openDetail(q,trigger){
    lastFocus=trigger||document.activeElement;
    var pl=place(q.a),ml=pl?mapLink(pl):null;
    var fp=fromPrice(q);
    var h='<button class="xbtn" type="button" id="xbtn" aria-label="Close details">&times;</button>';
    h+='<div class="shead"><div class="dv">'+esc(q.d)+' · '+esc(q.a)+'</div><h2 id="dtitle">'+esc(q.n)+'</h2><div class="tags">'+
       (q.status?'<span class="tag2">'+esc(q.status)+'</span>':'')+(q.sold?'<span class="tag2 sold">Sold out on portal</span>':'')+'</div></div>';
    h+='<div class="sbody">';
    h+='<div class="facts">'+
       '<div class="fact"><div class="k">Community</div><div class="v">'+esc(q.a)+'</div></div>'+
       '<div class="fact"><div class="k">Location</div><div class="v">'+esc(q.loc||q.a)+'</div></div>'+
       '<div class="fact"><div class="k">Handover</div><div class="v">'+esc(q.handover||"On request")+'</div></div>'+
       '<div class="fact"><div class="k">Launch price from</div><div class="v">'+(fp!=null?esc(money(fp)):"On request")+'</div></div></div>';
    if(q.hl)h+='<p>'+esc(q.hl)+'</p>';
    h+='<div><h3>Unit types and prices</h3>';
    if(q.cfg.length){
      h+='<div class="tw"><table><thead><tr><th>Type</th><th>Size (sq ft)</th><th>From</th></tr></thead><tbody>'+
        q.cfg.map(function(c){return '<tr><td>'+esc(c.label)+'</td><td>'+(c.size?esc(c.size):"On request")+'</td><td>'+esc(money(c.from))+'</td></tr>'}).join("")+'</tbody></table></div>';
    }else{h+='<p class="meta">Unit types, sizes and prices on request. Message me and I will send the current list.</p>'}
    h+='</div>';
    h+='<div><h3>Payment plan</h3><div class="plan">'+(q.plan?esc(q.plan):'Payment plan on request. Message me for the current plan.')+'</div></div>';
    h+='<div><h3>Amenities</h3>'+(q.am.length?'<div class="am">'+q.am.map(function(a){return '<span>'+esc(a)+'</span>'}).join("")+'</div>':'<p class="meta">Amenity list on request.</p>')+'</div>';
    h+='<div class="sacts">'+(ml?'<a class="btn solid" target="_blank" rel="noopener" href="'+ml.href+'">'+ml.label+'</a>':'')+
       '<a class="btn wa" target="_blank" rel="noopener" href="'+wa("Hello Manigandan, I would like the available units, prices and payment plan for "+q.n+" by "+q.d+" ("+q.a+").")+'">Enquire on WhatsApp</a></div>';
    h+='<p class="fine">'+esc(q.note||"")+(q.src.length?' Sources: '+q.src.map(function(u){var host=u;try{host=new URL(u).hostname.replace(/^www\./,"")}catch(e){}return '<a target="_blank" rel="noopener" href="'+esc(u)+'">'+esc(host)+'</a>'}).join(", ")+'.':'')+' Figures are indicative. Confirm with me before you decide.</p>';
    h+='</div>';
    sheet.innerHTML=h;
    ov.hidden=false;ov.scrollTop=0;document.body.style.overflow="hidden";
    document.getElementById("xbtn").addEventListener("click",closeDetail);
    document.getElementById("xbtn").focus();
  }
  function closeDetail(){
    ov.hidden=true;document.body.style.overflow="";
    if(lastFocus&&lastFocus.focus)try{lastFocus.focus()}catch(e){}
  }
  ov.addEventListener("click",function(e){if(e.target===ov)closeDetail()});
  document.addEventListener("keydown",function(e){
    if(ov.hidden)return;
    if(e.key==="Escape"){closeDetail();return}
    if(e.key==="Tab"){
      var f=sheet.querySelectorAll("a[href],button");if(!f.length)return;
      var first=f[0],last=f[f.length-1];
      if(e.shiftKey&&document.activeElement===first){e.preventDefault();last.focus()}
      else if(!e.shiftKey&&document.activeElement===last){e.preventDefault();first.focus()}
    }
  });

  refresh();

  /* ---- calculator ---- */
  function calc(){
    var price=+document.getElementById("price").value||0;
    var dpp=Math.min(Math.max(+document.getElementById("down").value||0,0),90);
    var rate=Math.max(+document.getElementById("rate").value||0,0);
    var yrs=Math.max(Math.round(+document.getElementById("years").value||1),1);
    var dp=price*dpp/100, loan=price-dp, n=yrs*12, r=rate/100/12;
    var pay=r===0?loan/n:loan*r*Math.pow(1+r,n)/(Math.pow(1+r,n)-1);
    if(!isFinite(pay))pay=0;
    document.getElementById("monthly").textContent=fmt(pay);
    document.getElementById("loan").textContent=fmt(loan);
    document.getElementById("dp").textContent=fmt(dp);
    document.getElementById("int").textContent=fmt(Math.max(pay*n-loan,0));
    document.getElementById("calcwa").href=wa("Hello Manigandan, I used the mortgage calculator: price "+fmt(price)+", down payment "+dpp+"%, "+rate+"% over "+yrs+" years (about "+fmt(pay)+" per month). Can we discuss?");
  }
  ["price","down","rate","years"].forEach(function(id){document.getElementById(id).addEventListener("input",calc)});
  calc();

  /* ---- contact form ---- */
  var form=document.getElementById("form");
  function upd(){
    var g=function(i){return document.getElementById(i).value.trim()};
    var t="Hello Manigandan, "+(g("name")?"my name is "+g("name")+". ":"")+"I want to: "+g("want")+"."+(g("budget")?" Budget: AED "+g("budget")+".":"")+(g("msg")?" "+g("msg"):"");
    document.getElementById("formwa").href=wa(t);
  }
  form.addEventListener("input",upd);form.addEventListener("change",upd);
  form.addEventListener("submit",function(e){e.preventDefault()});
  upd();

  /* ---- copy email ---- */
  document.querySelectorAll(".copy").forEach(function(btn){
    btn.addEventListener("click",function(){
      var src=btn.previousElementSibling;
      var fb=function(){var r=document.createRange();r.selectNodeContents(src);var sel=window.getSelection();sel.removeAllRanges();sel.addRange(r);btn.textContent="Selected";setTimeout(function(){btn.textContent="Copy"},1500)};
      try{navigator.clipboard.writeText(src.textContent).then(function(){btn.textContent="Copied";setTimeout(function(){btn.textContent="Copy"},1500)},fb)}catch(e){fb()}
    });
  });
})();
</script>
</body>
</html>
