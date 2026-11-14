Tool tool does not exists.
# `index.html`

```html
<!DOCTYPE html>
<html lang="hi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<meta name="theme-color" content="#0f172a">
<meta name="description" content="DishaVerse Pro — 3,000 courses & skills, career discovery quiz, bilingual Hindi/English, offline-first PWA. Direct UPI micro-payments.">
<title>DishaVerse Pro — करियर खोज व स्किल्स</title>
<link rel="manifest" href="./manifest.json">
<link rel="icon" id="fav" href="data:,">
<link rel="apple-touch-icon" id="ati" href="data:,">
<script src="https://cdn.tailwindcss.com"></script>
<script>
tailwind.config={theme:{extend:{
  colors:{navy:'#0f172a',card:'#1e293b',line:'#334155',brand:'#2563eb',brand2:'#3b82f6',acid:'#a3e635',mag:'#d946ef',amber:'#f59e0b',ok:'#22c55e',bad:'#ef4444',info:'#38bdf8'},
  fontFamily:{app:['Poppins','Noto Sans Devanagari','system-ui','sans-serif']}
}}};
</script>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700;800&family=Noto+Sans+Devanagari:wght@400;500;600;700&display=swap" rel="stylesheet">
<script defer src="https://cdnjs.cloudflare.com/ajax/libs/html2pdf.js/0.10.1/html2pdf.bundle.min.js"></script>
<style>
:root{--navy:#0f172a;--card:#1e293b;--line:#334155;--brand:#2563eb;--brand2:#3b82f6;--ink:#e2e8f0;--mut:#94a3b8;--acid:#a3e635;--mag:#d946ef;--amber:#f59e0b;--ok:#22c55e;--bad:#ef4444;--info:#38bdf8}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{background:var(--navy);color:var(--ink);font-family:Poppins,'Noto Sans Devanagari',system-ui,sans-serif;-webkit-tap-highlight-color:transparent;margin:0;min-height:100vh}
body::before{content:'';position:fixed;inset:0;z-index:-2;background:
  radial-gradient(60% 40% at 15% 0%,rgba(37,99,235,.28),transparent 60%),
  radial-gradient(50% 35% at 90% 8%,rgba(217,70,239,.16),transparent 60%),
  radial-gradient(55% 40% at 50% 100%,rgba(56,189,248,.12),transparent 60%),var(--navy)}
body::after{content:'';position:fixed;inset:0;z-index:-1;pointer-events:none;opacity:.5;
  background-image:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='140' height='140'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.85' numOctaves='2'/%3E%3C/filter%3E%3Crect width='140' height='140' filter='url(%23n)' opacity='0.045'/%3E%3C/svg%3E")}
::-webkit-scrollbar{width:10px;height:10px}
::-webkit-scrollbar-track{background:#0b1222}
::-webkit-scrollbar-thumb{background:linear-gradient(#334155,#2563eb);border-radius:8px;border:2px solid #0b1222}
::-webkit-scrollbar-thumb:hover{background:linear-gradient(#3b82f6,#38bdf8)}
*{scrollbar-width:thin;scrollbar-color:#2563eb #0b1222}
.card{background:linear-gradient(160deg,#1e293b,#172033);border:1px solid var(--line);border-radius:1rem;box-shadow:0 10px 30px -18px rgba(0,0,0,.8)}
.card.hov{transition:transform .18s,border-color .18s,box-shadow .18s}
.card.hov:hover{transform:translateY(-3px);border-color:rgba(59,130,246,.7);box-shadow:0 16px 34px -16px rgba(37,99,235,.5)}
.btn{display:inline-flex;align-items:center;justify-content:center;gap:.4rem;border-radius:.75rem;font-weight:600;padding:.6rem 1rem;font-size:.85rem;transition:transform .12s,background .15s,border-color .15s,box-shadow .15s;cursor:pointer;border:0;line-height:1.2}
.btn:active{transform:scale(.96)}
.btn:focus-visible{outline:2px solid var(--info);outline-offset:2px}
.btn-p{background:linear-gradient(135deg,#2563eb,#1d4ed8);color:#fff;box-shadow:0 8px 20px -10px rgba(37,99,235,.9)}
.btn-p:hover{background:linear-gradient(135deg,#3b82f6,#2563eb)}
.btn-o{border:1px solid var(--line);color:#cbd5e1;background:rgba(15,23,42,.7)}
.btn-o:hover{border-color:var(--brand2);color:#fff}
.chip{display:inline-flex;align-items:center;gap:.25rem;font-size:.68rem;font-weight:600;padding:.2rem .55rem;border-radius:999px;border:1px solid var(--line);background:rgba(15,23,42,.8);color:var(--mut);white-space:nowrap}
.inp,.sel{background:rgba(15,23,42,.85);border:1px solid var(--line);border-radius:.75rem;color:var(--ink);padding:.6rem .8rem;font-size:.85rem;width:100%;outline:none;transition:border-color .15s,box-shadow .15s}
.inp:focus,.sel:focus{border-color:var(--brand2);box-shadow:0 0 0 3px rgba(59,130,246,.18)}
.noscroll::-webkit-scrollbar{display:none}.noscroll{scrollbar-width:none}
.sheet{animation:up .24s cubic-bezier(.2,.8,.2,1)}
@keyframes up{from{transform:translateY(26px);opacity:0}to{transform:translateY(0);opacity:1}}
@keyframes fadeUp{from{transform:translateY(14px);opacity:0}to{transform:translateY(0);opacity:1}}
.reveal{animation:fadeUp .5s cubic-bezier(.2,.8,.2,1) both}
#toast{transition:.28s cubic-bezier(.2,.8,.2,1);transform:translateY(-160%);opacity:0}
#toast.on{transform:translateY(0);opacity:1}
.navbtn{flex:1;display:flex;flex-direction:column;align-items:center;gap:2px;padding:.55rem 0 .4rem;font-size:.62rem;font-weight:600;color:#64748b;position:relative;background:none;border:0;cursor:pointer;transition:color .15s}
.navbtn.on{color:var(--brand2)}
.navbtn.on::before{content:'';position:absolute;top:0;left:25%;right:25%;height:3px;border-radius:0 0 4px 4px;background:linear-gradient(90deg,#2563eb,#38bdf8)}
.navsafe{padding-bottom:env(safe-area-inset-bottom,0px)}
details>summary{list-style:none;cursor:pointer}details>summary::-webkit-details-marker{display:none}
details[open] .arr{transform:rotate(90deg)}
.arr{transition:.15s;display:inline-block}
.clamp2{display:-webkit-box;-webkit-line-clamp:2;-webkit-box-orient:vertical;overflow:hidden}
#pdfStage{position:fixed;left:-10000px;top:0;width:780px;background:#fff;color:#0f172a;font-family:Poppins,'Noto Sans Devanagari',sans-serif}
.tabsec{min-height:62vh}
.star{color:var(--amber)}
.hero{position:relative;overflow:hidden;background:linear-gradient(150deg,#1e293b 0%,#172554 45%,#0f172a 100%)}
.hero::before{content:'';position:absolute;width:280px;height:280px;right:-70px;top:-90px;border-radius:50%;background:radial-gradient(circle,rgba(59,130,246,.5),transparent 65%);filter:blur(6px);animation:drift 9s ease-in-out infinite alternate}
.hero::after{content:'';position:absolute;width:200px;height:200px;left:-60px;bottom:-80px;border-radius:50%;background:radial-gradient(circle,rgba(217,70,239,.35),transparent 65%);filter:blur(8px);animation:drift 11s ease-in-out infinite alternate-reverse}
@keyframes drift{from{transform:translate(0,0) scale(1)}to{transform:translate(18px,14px) scale(1.12)}}
.tier-free{color:var(--acid)!important;border-color:rgba(163,230,53,.4)!important}
.tier-smart{color:var(--amber)!important;border-color:rgba(245,158,11,.45)!important}
.tier-pro{color:var(--mag)!important;border-color:rgba(217,70,239,.45)!important}
@media (prefers-reduced-motion:reduce){*{animation:none!important;transition:none!important;scroll-behavior:auto!important}}
</style>
</head>
<body class="font-app pb-24">

<header class="sticky top-0 z-40 bg-navy/90 backdrop-blur border-b border-line">
  <div class="max-w-6xl mx-auto px-4 py-3 flex items-center gap-3">
    <svg width="34" height="34" viewBox="0 0 48 48" class="shrink-0" aria-hidden="true"><defs><linearGradient id="lg" x1="0" y1="0" x2="1" y2="1"><stop offset="0" stop-color="#3b82f6"/><stop offset="1" stop-color="#2563eb"/></linearGradient></defs><rect width="48" height="48" rx="12" fill="#0f172a"/><circle cx="24" cy="24" r="19" fill="url(#lg)"/><rect x="13" y="24" width="5" height="9" rx="1" fill="#fff"/><rect x="21.5" y="20" width="5" height="13" rx="1" fill="#fff"/><rect x="30" y="16" width="5" height="17" rx="1" fill="#fff"/></svg>
    <div class="min-w-0">
      <div class="font-extrabold text-white leading-tight">DishaVerse <span class="text-brand2">Pro</span></div>
      <div class="text-[10px] text-slate-400 leading-tight" data-i18n="appTag">करियर खोज व स्किल्स</div>
    </div>
    <div class="ml-auto flex items-center gap-2">
      <span id="netDot" class="w-2.5 h-2.5 rounded-full bg-ok" title="online"></span>
      <button data-act="lang" class="btn btn-o !py-1.5 !px-3 text-xs" aria-label="Toggle language">🌐 हिंदी / EN</button>
    </div>
  </div>
</header>

<main class="max-w-6xl mx-auto px-4">

  <section id="tab-home" class="tabsec pt-5">
    <div class="card hero p-5 reveal">
      <div class="relative z-10">
        <span class="chip !text-info !border-info/40 mb-3">🇮🇳 भारत के लिए • 100% Static PWA</span>
        <h1 class="text-2xl md:text-4xl font-extrabold text-white leading-tight" data-i18n="heroTitle">सही दिशा, सही करियर।</h1>
        <p class="text-sm text-slate-300 mt-2 max-w-xl" data-i18n="heroSub">10 करियर डोमेन में 3,000+ कोर्स व स्किल्स — मुफ़्त, द्विभाषी, ऑफ़लाइन।</p>
        <div class="flex flex-wrap gap-2 mt-4">
          <button data-act="tab" data-tab="courses" class="btn btn-p">📚 <span data-i18n="ctaExplore">3,000 कोर्स देखें</span></button>
          <button data-act="tab" data-tab="quiz" class="btn btn-o">🧭 <span data-i18n="ctaQuiz">मेरा करियर खोजें</span></button>
        </div>
        <div class="grid grid-cols-4 gap-2 mt-5 text-center">
          <div class="card !bg-navy/70 p-2"><div id="statCourses" class="font-extrabold text-brand2">3,000</div><div class="text-[10px] text-slate-400" data-i18n="statCourses">कोर्स</div></div>
          <div class="card !bg-navy/70 p-2"><div class="font-extrabold text-acid">10</div><div class="text-[10px] text-slate-400" data-i18n="statDomains">डोमेन</div></div>
          <div class="card !bg-navy/70 p-2"><div class="font-extrabold text-mag">2</div><div class="text-[10px] text-slate-400" data-i18n="statLangs">भाषाएँ</div></div>
          <div class="card !bg-navy/70 p-2"><div class="font-extrabold text-info">✓</div><div class="text-[10px] text-slate-400" data-i18n="statOffline">ऑफ़लाइन</div></div>
        </div>
      </div>
    </div>

    <h2 class="font-bold text-white mt-6 mb-3 reveal">🎯 <span data-i18n="domainsTitle">10 करियर डोमेन</span></h2>
    <div id="domainGrid" class="grid grid-cols-2 md:grid-cols-5 gap-2"></div>

    <div class="flex items-center justify-between mt-6 mb-3">
      <h2 class="font-bold text-white">🔥 <span data-i18n="trendingTitle">ट्रेंडिंग कोर्स</span></h2>
      <button data-act="tab" data-tab="courses" class="text-xs text-brand2 font-semibold" data-i18n="seeAll">सभी देखें</button>
    </div>
    <div id="trendRow" class="flex gap-3 overflow-x-auto noscroll pb-1"></div>

    <div class="card p-4 mt-6 border-brand/50 flex flex-wrap items-center gap-3 reveal">
      <div class="text-2xl">⚡</div>
      <div class="flex-1 min-w-[180px]">
        <div class="font-bold text-white text-sm" data-i18n="stripTitle">माइक्रो-प्राइसिंग, डायरेक्ट UPI</div>
        <div class="text-xs text-slate-400" data-i18n="stripSub">₹14 PDF • ₹29 स्मार्ट • ₹79 प्रो — GPay / PhonePe / Paytm से भुगतान</div>
      </div>
      <button data-act="tab" data-tab="plans" class="btn btn-p" data-i18n="viewPlans">प्लान देखें</button>
    </div>
  </section>

  <section id="tab-courses" class="tabsec pt-5 hidden">
    <div class="sticky top-[61px] z-30 bg-navy/95 backdrop-blur pt-1 pb-3 -mx-4 px-4 border-b border-line">
      <input id="q" class="inp" data-i18n-ph="searchPh" placeholder="कोर्स, स्किल या ID खोजें (जैसे DV-0007)…" aria-label="Search courses">
      <div class="grid grid-cols-2 md:grid-cols-4 gap-2 mt-2">
        <select id="fDomain" class="sel" aria-label="Domain filter"></select>
        <select id="fLevel" class="sel" aria-label="Level filter"></select>
        <select id="fFee" class="sel" aria-label="Type filter">
          <option value="all" data-i18n="allTypes">सभी प्रकार</option>
          <option value="free" data-i18n="typeFree">फ्री</option>
          <option value="smart" data-i18n="typeSmart">स्मार्ट</option>
          <option value="pro" data-i18n="typePro">प्रो</option>
        </select>
        <select id="fSort" class="sel" aria-label="Sort">
          <option value="pop" data-i18n="sortPop">सबसे लोकप्रिय</option>
          <option value="rat" data-i18n="sortRating">टॉप रेटेड</option>
          <option value="new" data-i18n="sortNew">नए पहले</option>
          <option value="az" data-i18n="sortAZ">A → Z</option>
        </select>
      </div>
      <div class="flex items-center justify-between mt-2 text-xs text-slate-400">
        <span><b id="resCount" class="text-brand2">3,000</b> <span data-i18n="results">कोर्स मिले</span></span>
        <span id="srcBadge" class="chip">बिल्ट-इन इंजन: 3,000</span>
      </div>
    </div>
    <div id="courseGrid" class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-3 mt-4"></div>
    <div class="text-center mt-4"><button id="loadMore" data-act="loadmore" class="btn btn-o" data-i18n="loadMore">और देखें</button></div>
  </section>

  <section id="tab-quiz" class="tabsec pt-5 hidden">
    <h2 class="text-xl font-extrabold text-white">🧭 <span data-i18n="quizTitle">करियर डिस्कवरी क्विज़</span></h2>
    <p class="text-sm text-slate-400 mt-1" data-i18n="quizSub">5 आसान सवाल → आपके टॉप 3 डोमेन + कोर्स सुझाव।</p>
    <div id="quizBox" class="mt-4"></div>
  </section>

  <section id="tab-plans" class="tabsec pt-5 hidden">
    <h2 class="text-xl font-extrabold text-white">💎 <span data-i18n="plansTitle">सरल माइक्रो-प्लान</span></h2>
    <p class="text-sm text-slate-400 mt-1" data-i18n="plansSub">100% डायरेक्ट UPI — कोई गेटवे नहीं, कोई छिपी फीस नहीं।</p>
    <div id="planStatus" class="mt-4"></div>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-3 mt-4">
      <div class="card hov p-4">
        <div class="font-bold text-white" data-i18n="planPdfName">PDF अनलॉक</div>
        <div class="text-3xl font-extrabold text-brand2 mt-1">₹14 <span class="text-xs text-slate-400 font-medium" data-i18n="perPdf">एक PDF</span></div>
        <ul class="text-xs text-slate-300 mt-3 space-y-1.5">
          <li>✅ <span data-i18n="fPdf1">कोई 1 कोर्स/क्विज़ PDF</span></li>
          <li>✅ <span data-i18n="fPdf2">हमेशा के लिए (इसी डिवाइस)</span></li>
          <li>✅ <span data-i18n="fPdf3">हिंदी या अंग्रेज़ी</span></li>
        </ul>
        <button data-act="buy" data-plan="pdf" class="btn btn-o w-full mt-4" data-i18n="buy">UPI से भुगतान</button>
      </div>
      <div class="card hov p-4">
        <div class="font-bold text-white" data-i18n="planSmartName">स्मार्ट</div>
        <div class="text-3xl font-extrabold text-amber mt-1">₹29 <span class="text-xs text-slate-400 font-medium" data-i18n="per30">30 दिन</span></div>
        <ul class="text-xs text-slate-300 mt-3 space-y-1.5">
          <li>✅ <span data-i18n="fS1">सभी प्रीमियम सिलेबस अनलॉक</span></li>
          <li>✅ <span data-i18n="fS2">5 PDF क्रेडिट शामिल</span></li>
          <li>✅ <span data-i18n="fS3">क्विज़ रिपोर्ट शामिल</span></li>
          <li>✅ <span data-i18n="fS4">30 दिन वैध</span></li>
        </ul>
        <button data-act="buy" data-plan="smart" class="btn btn-p w-full mt-4" data-i18n="buy">UPI से भुगतान</button>
      </div>
      <div class="card hov p-4 ring-2 ring-brand relative">
        <span class="absolute -top-2.5 right-3 chip !bg-brand !text-white !border-brand">⭐ BEST</span>
        <div class="font-bold text-white" data-i18n="planProName">प्रो</div>
        <div class="text-3xl font-extrabold text-mag mt-1">₹79 <span class="text-xs text-slate-400 font-medium" data-i18n="per30">30 दिन</span></div>
        <ul class="text-xs text-slate-300 mt-3 space-y-1.5">
          <li>✅ <span data-i18n="fP1">Smart का सब कुछ</span></li>
          <li>✅ <span data-i18n="fP2">अनलिमिटेड PDF</span></li>
          <li>✅ <span data-i18n="fP3">प्राथमिकता सहायता</span></li>
          <li>✅ <span data-i18n="fP4">30 दिन वैध</span></li>
        </ul>
        <button data-act="buy" data-plan="pro" class="btn btn-p w-full mt-4" data-i18n="buy">UPI से भुगतान</button>
      </div>
    </div>
    <div class="card p-4 mt-4">
      <div class="font-bold text-white text-sm" data-i18n="howTitle">भुगतान कैसे होता है</div>
      <ol class="text-xs text-slate-300 mt-2 space-y-1.5 list-decimal list-inside">
        <li data-i18n="how1">पे दबाएँ → UPI ऐप राशि के साथ खुलेगा।</li>
        <li data-i18n="how2">भुगतान करें व 12-अंकों का UTR कॉपी करें।</li>
        <li data-i18n="how3">UTR यहाँ डालें → इस डिवाइस पर तुरंत अनलॉक।</li>
      </ol>
      <p class="text-[10px] text-amber mt-2" data-i18n="payDisclaimer">स्टैटिक ऐप: अनलॉक इसी डिवाइस पर होता है। भुगतान मैन्युअल जाँचा जाता है; रसीद सुरक्षित रखें।</p>
    </div>
    <div class="card p-4 mt-4">
      <div class="font-bold text-white text-sm" data-i18n="txnTitle">भुगतान इतिहास (यह डिवाइस)</div>
      <div id="txnList" class="mt-2 text-xs text-slate-300"></div>
    </div>
  </section>

  <section id="tab-library" class="tabsec pt-5 hidden">
    <h2 class="text-xl font-extrabold text-white">📁 <span data-i18n="libTitle">मेरी लाइब्रेरी</span></h2>
    <p class="text-xs text-slate-400 mt-1" data-i18n="guest">अतिथि (डिवाइस-लोकल प्रोफ़ाइल)</p>
    <button data-act="install" class="btn btn-p mt-3">⬇️ <span data-i18n="installApp">ऐप इंस्टॉल करें</span></button>
    <div id="planStatus2" class="mt-4"></div>
    <h3 class="font-bold text-white mt-5 mb-2">⭐ <span data-i18n="savedTitle">सेव किए कोर्स</span></h3>
    <div id="savedList" class="space-y-2"></div>
    <h3 class="font-bold text-white mt-5 mb-2">📄 <span data-i18n="pdfsTitle">मेरे PDFs</span></h3>
    <div id="unlockedList" class="space-y-2"></div>
    <h3 class="font-bold text-white mt-5 mb-2">🛠️ <span data-i18n="toolsTitle">टूल्स व सेटिंग्स</span></h3>
    <div class="card p-3 space-y-2">
      <button data-act="exicons" class="btn btn-o w-full" data-i18n="exIcons">PNG आइकन एक्सपोर्ट (PWABuilder हेतु)</button>
      <button data-act="exdata" class="btn btn-o w-full" data-i18n="exData">मेरा डेटा एक्सपोर्ट (JSON)</button>
      <button data-act="reset" class="btn btn-o w-full !text-bad !border-bad/40" data-i18n="resetApp">ऐप डेटा रीसेट</button>
    </div>
    <div class="card p-4 mt-4 text-xs text-slate-400">
      <div class="font-bold text-white text-sm mb-1" data-i18n="aboutApp">ऐप के बारे में</div>
      <div><span data-i18n="version">वर्ज़न</span>: <b id="verTxt">1.0.1</b></div>
      <div><span data-i18n="upiLabel">मर्चेंट UPI</span>: <b id="upiTxt"></b></div>
      <div><span data-i18n="supportLabel">सहायता</span>: <b id="supTxt"></b></div>
    </div>
    <p class="text-center text-[10px] text-slate-500 mt-6" data-i18n="footer">भारत में निर्मित 🇮 • ऑफ़लाइन-फर्स्ट PWA • कोई बैकएंड नहीं</p>
  </section>
</main>

<nav class="fixed bottom-0 inset-x-0 z-40 bg-card/95 backdrop-blur border-t border-line navsafe" aria-label="Primary">
  <div class="max-w-6xl mx-auto flex">
    <button class="navbtn on" data-act="tab" data-tab="home"><span class="text-lg">🏠</span><span data-i18n="navHome">होम</span></button>
    <button class="navbtn" data-act="tab" data-tab="courses"><span class="text-lg">📚</span><span data-i18n="navCourses">कोर्स</span></button>
    <button class="navbtn" data-act="tab" data-tab="quiz"><span class="text-lg">🧭</span><span data-i18n="navQuiz">खोज</span></button>
    <button class="navbtn" data-act="tab" data-tab="plans"><span class="text-lg">💎</span><span data-i18n="navPlans">प्लान</span></button>
    <button class="navbtn" data-act="tab" data-tab="library"><span class="text-lg">📁</span><span data-i18n="navLib">लाइब्रेरी</span></button>
  </div>
</nav>

<div id="courseModal" class="hidden fixed inset-0 z-50" role="dialog" aria-modal="true">
  <div class="absolute inset-0 bg-black/70 backdrop-blur-sm" data-act="closecourse"></div>
  <div class="sheet relative max-w-2xl mt-6 md:mt-12 mb-6 max-h-[88vh] overflow-y-auto card !rounded-2xl mx-4 md:mx-auto">
    <div id="courseBody"></div>
  </div>
</div>

<div id="payModal" class="hidden fixed inset-0 z-50" role="dialog" aria-modal="true">
  <div class="absolute inset-0 bg-black/70 backdrop-blur-sm" data-act="paycancel"></div>
  <div class="sheet relative max-w-md mt-10 mb-6 max-h-[85vh] overflow-y-auto card !rounded-2xl mx-4 md:mx-auto p-4">
    <div id="payBody"></div>
  </div>
</div>

<div id="toast" class="fixed top-3 inset-x-0 z-[60] flex justify-center pointer-events-none px-4">
  <div class="bg-brand text-white text-xs font-semibold px-4 py-2 rounded-full shadow-lg max-w-full flex items-center gap-3 pointer-events-auto">
    <span id="toastTxt"></span><button id="toastAct" class="hidden underline font-bold shrink-0"></button>
  </div>
</div>
<div id="updBar" class="hidden fixed bottom-20 inset-x-0 z-50 flex justify-center px-4">
  <div class="card !rounded-full px-4 py-2 flex items-center gap-3 text-xs">
    <span data-i18n="updAvail">नया वर्ज़न तैयार</span>
    <button data-act="refresh" class="btn btn-p !py-1 !px-3 !text-xs" data-i18n="refresh">रिफ्रेश</button>
  </div>
</div>
<div id="pdfStage"></div>

<script>
'use strict';
/* DishaVerse Pro v1.0.1 — 100% static EdTech PWA | Owner: Mukesh Kumar */

/* ================= OWNER CONFIG ================= */
const CFG={
  UPI_ID:'mk54682008@oksbi',
  PAYEE:'Mukesh Kumar',
  SUPPORT:'support@dishaverse.in',
  PRICES:{PDF:14,SMART:29,PRO:79},
  PLAN_DAYS:30,SMART_CREDITS:5,
  PAY_LINKS:{14:'',29:'',79:''},
  VER:'1.0.1'
};

/* ================= EMBEDDED PNG ICONS ================= */
const ICON192='iVBORw0KGgoAAAANSUhEUgAAAMAAAADACAIAAADdvvtQAAAErklEQVR42u3dMY4TQRAF0LoBCRISCREJd+AOxBByG0JuQsqVSEiIwZKTxbsga6enu6vqoR8ig9ZPVb89O5548eqdyLMTfgQCkAAkAAlAIgAJQAKQACQCkAAkAAlAIgAJQAKQACQCkAA0JK/ff7nJ288/bvL47/i5dQT08t3H69v/5sP3x0qel8tLXV/z8uIAlUUzUMw9nppgitqLaRqa/2MCiBuSqgO6rIwN3TwpqdJ2ixojZ383Tx7rAEKnO6NAB6NegIrRyc4o0MGoPqAsJ6yGJ7UEgFrRuWEE0NHB05POw2w+isLgMYqqAerWeFK3orC2rLM6gAyedOss6GGoAiB6khoKlVmtTgxIZc5eq4MehlICoqeGoaCHoXyAtOYy57Kgh6FMgOgpZijoYSgHIMW5ZKEOehhKAMjyqrrIgh6GtgZkedVeZKcD8i6uTW5Allf5RRaWl0W2KSDjp8MQOgtQk/vY3W8furM2vR0g46fPEArjxxDaC5Dx02oIhfFjCG0EyPjpNoTC+DGEdgFk/DQcQmH8GEJbAHLl6yZfv/36ffefvFfHwpWvhoAGXh0L+6shoIFbLNTnnoBGVemwv3oCGrXFwv7qy2gIVss7K+2gIassXC54edAR3/RDEUoM6AjtegUIA6Azpeg0IB6gzoeA0KBag5oIM1KBSg5oAO1qCA/nrL7wxAYwAVa9Bj3+8sgA726NCgmwM62KMBAggggDICqncEawvoSI8GCCCAAAIIIIAAAggggKYBqnf1qi2gIyd5gAACCCCAAAIIIIBSAbr/7bnzN3gA6nWMB8jnQAABBBBAAAEEEEAAAdQK0PKTPEB+JxoggAACKOmNhQClv7FwbY8GyL3xAPUGtPbrXQBK//Uua3s0QOm/YGptjwaowlfcLaxBAC0vQLm/5heg5QUo9xeNA7S8AOV+1AFAywtQ7oetALS8AOV+3BNAy/dX7gfOAbR8f+V+5CVAy/dX7ofuArR8f+V+7DdAy/fX7ofuArR8f+V+7DdAy/fX7ofuArR8f+V+7DdAy/fXSEDzP1EEaOHnh+MBzd9iAC3fX4MBTa7SAK2tz+MBTR5CAC0fP+MBzRxC9z9c59OXn2Nf8J5Xu/yjY19ww/EzHpBnGG6e4W/3eECeQrdtho+fUwAZQn3Gz1mADKEm4+csQIZQk/FzIiBDqMP4ORFQvSeq5s3AK19TAXmq/CYZeOVrKiBDqPz4OR2QNl21O88DZJFVXV6TAFlkVZfXPEAMVdUzD5BFVm95TQXEUEk9UwFZZMWW1wJADBXTswAQQ5X0rAHEUBk9ywAp1KmL83pADNXQsxIQQwX0LAbEUHY96wFdDenUz2vNy/VsAci5LNGZa19ADGXUsxcghtLp2Q6QWr15ZU4ASK3euTLnAGSdbb62cgCyzrZdW2kANR9FOw+eTIAatqJtG09WQK3utz/vPvbugMozykUnK6CSjDLSyQ2oDKO8dCoASs0oO506gHKd1BKdsHoBejiQNpR0+S/VGDn1AW0lqaqbFoAebreZmK5oKu2p7oAeYxrr6SqmD5rWgP617G7y5KHpJn5uAAlAApAAJACJACQACUACkAhAApAAJACJACQACUACkAhAApCszx+g1jGxUReIoAAAAABJRU5ErkJggg==';
const ICON512='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CIAACIAAgAAIgAAIAAiAAAiAACAAAiAAAiAACIAACIAACAACIAACIAACgAAIgAAIgBfBEAABEAAvgvkqCAflFf45nmICIAC+CkIABEAABEAABEAABEAABEAABEAABEAABEAABEAABEAABEAABEAABEAABEAABEAAEAABEAABEAAEQAAEQAAEAAEQAAEQAAFAAARAAARgqQD4OiABEAAB8EVAAoAACIAACIAAIAACIAACIAAIgAAIgAAIAAIgAAIgAGsFwJ8EEAABEIBdm/mPAcweAE+CCoAACIBnQAUAARAAARAAAUAABEAABEAAEAABEAABWDMAHgQSAAEQAI8ACQACIAACIAACgAAIgAAIgAAgAAIgAAKwbADsgQVAAATABlgAEAABEAABEAAEQAAEQACWD4A1gAAIgABYAAgAAiAAAiAAAoAACIAACEAhANYAAiAAAmABIAAIgAAIgAAIAAIgAAIgAMsHwBpAAARAACwABAABEAABEIBYAPxxYAEQAAHYkcn/FPDOAmANIAACIAAWAAKAAAiAAAhAKQDWAAIgAAJgASAACIAACIAAxAJgCiQAAiAA5j8CgAAIgAAIQCkAN4d7HywBEAABmN/xsBIAawABEAABsAAQAK+DCYAACIBXwATAGkAABEAALAAEwBpAAARAACwABMAaQAAEQAAsAATAGkAABEAALAAEwBpAAARAACwABMAUSAAEQADMfwTAh0wABEAABCAaAFMgARAAATD/iQbAw6ACIAAC4AHQaABMgQRAAATD/EQAEQAAEQABKATAFEgABEADzn24AvBIsAAIgAF4AjgbAFEgABEAAzH+iATAFEgABEADzn24ATIEEQAAEwPwnGgBTIAEQAAEw/4kGwBRIAARAAMx/ugFwEyAAAiAALv+jAfC9QAIgAALg+3+iATAFEgABEADzn24ATIEEQAAEwPwnGgBTIAEQAAEw/4kGwAsBAiAAAuDx/24ATIEEQAAEwPwnGgCrYAEQAAGw/u0GwE2AAAiAALj8jwbAKlgABEAArH+jAbAKFgABEADr324A3AQIgAAIgMv/aACsggVAAATA+rcbAKtgARAAAbD+jQbATYAACIAAuPzvBsBNgAAIgAC4/I8GwE2AAAiAALj87wbA86ACIAAC4OnPaAA8Dwp4+jMaADcBgMv/bgDcBAAu/6MBcBMAuPzvBsBNAODyPxoANwGAy/9uANwEAC7/owFwEwC4/O8GwE0A4PI/GgA3AYDL/24AfDsQcIbC2ZgIgK8IBd5kvS/+7AbATQDg8r8bADcBgMv/aABsgwG7324APBIKePQzGgA3AYDL/24A3AQALv+jAbANBux+uwHwSChQfvSzHgCDICA+/OkGwDYYKO9+6wEwCALKw596AGyDgebuVwAMgoDu8EcAbIPB7vdeAA4GQYDhjwAYBAGGPwJgEAQY/giAQRBg+CMABkGA4Y8AeDUM8NqXAFgGAEb/AmAQBBj+CIAGAE5/ATAIAgx/BEADAKe/ABgEAYY/AqABgNNfAAyCAMMfAdAAwOkvAL4mCPCFPwJgGQAY/QuABgBOfwHwVXHAZ1/3JgAWwmDxiwBoADj9EQANAKc/AmAhDBa/AuCnoAHg9BcANACc/gKABoDTXwDQAHD6CwBeEAMvfAkAHgwFD30KgAZoADj9BUADAKe/AGgA4PQXAA0AnP4CoAGA018ANABw+guABgBOfwHwnjDgXV8B0ABw+iMAGgBOfwRAA8DpjwBoADj9EQCPBoEHfhAADQCnPwKgAeD0RwCsBMDQHwHQAHD6IwDbur178PtP2fFXwDkgAFYCYOiPACQbYBxEbezj9BcArAQw9EcAMA7C2AcBMA5yTGDsgwAYB4GxDwJgHATGPgiAWwFw4Y8AeFkMvOSFANgMg30vAuBWAFz4IwBuBcCFPwLgVgBc+CMAHhACj/ogAN4VAM/4CwAmQmDmIwBYDoNlrwAgA+DoFwBMhDDzQQCQARz9CAAeFcUjnggAFgMY9yMAyACOfgQAGcDRjwAgAzj6EQBkAEc/AoAHRvFwJwKADODoRwAwF8K0BwHg2hlwQ7DeJb+jHwHgbXMhNwR7v+Q37UEAcEPgkh8EACVw7oMAYDRk1IMAgBI49xEAOKsEpkPXnPM49xEA7AnM90EAMCAy5AEBYM7bAjF406HvYh8BYM0YGBO9OtZ36CMA5LbHwZuDv5f5xjsIADzpwZL3B4//1/xXRgBg5SQ47hEAuGwVth0fPY5xnPUIAEyXh5dOBOPZgf6Sny0CAIAAACAAAAgAAAIAgAAAIAAACAAAAgCAAAAgAAAIAAACAIAAACAAAAgAAAIAgAAAIAAAAuCnACAAAAgAAAIAgAAAIAAACAAAAgCAAAAgAAAIAAACAIAAACAAAAgAAAIAgAAAIAAACAAAAgCAAAAgAAAIAAACACAAAAgAAAIAgAAAIAAACAAAAgCAAAAwvz9PFmiBlmVpvgAAAABJRU5ErkJggg==';

/* ================= I18N ================= */
const T={
appTag:{h:'करियर खोज व स्किल्स',e:'Career Discovery & Skills'},
navHome:{h:'होम',e:'Home'},navCourses:{h:'कोर्स',e:'Courses'},navQuiz:{h:'खोज',e:'Discovery'},navPlans:{h:'प्लान',e:'Plans'},navLib:{h:'लाइब्रेरी',e:'Library'},
heroTitle:{h:'सही दिशा, सही करियर।',e:'Right Direction. Right Career.'},
heroSub:{h:'10 करियर डोमेन में 3,000+ कोर्स व स्किल्स — मुफ़्त, द्विभाषी, ऑफ़लाइन।',e:'Explore 3,000+ courses & skills across 10 Indian career domains — free, bilingual, offline.'},
ctaExplore:{h:'3,000 कोर्स देखें',e:'Explore 3,000 Courses'},ctaQuiz:{h:'मेरा करियर खोजें',e:'Find My Career'},seeAll:{h:'सभी देखें',e:'See all'},
statCourses:{h:'कोर्स',e:'Courses'},statDomains:{h:'डोमेन',e:'Domains'},statLangs:{h:'भाषाएँ',e:'Languages'},statOffline:{h:'ऑफ़लाइन',e:'Offline'},
domainsTitle:{h:'10 करियर डोमेन',e:'10 Career Domains'},trendingTitle:{h:'ट्रेंडिंग कोर्स',e:'Trending Courses'},
stripTitle:{h:'माइक्रो-प्राइसिंग, डायरेक्ट UPI',e:'Micro-Pricing, Direct UPI'},
stripSub:{h:'₹14 PDF • ₹29 स्मार्ट • ₹79 प्रो — GPay / PhonePe / Paytm से भुगतान',e:'₹14 PDF • ₹29 Smart • ₹79 Pro — pay via GPay / PhonePe / Paytm'},
viewPlans:{h:'प्लान देखें',e:'View Plans'},
searchPh:{h:'कोर्स, स्किल या ID खोजें (जैसे DV-0007)…',e:'Search course, skill or ID (e.g. DV-0007)…'},
allDomains:{h:'सभी डोमेन',e:'All Domains'},allLevels:{h:'सभी लेवल',e:'All Levels'},allTypes:{h:'सभी प्रकार',e:'All Types'},
typeFree:{h:'फ्री',e:'Free'},typeSmart:{h:'स्मार्ट',e:'Smart'},typePro:{h:'प्रो',e:'Pro'},
sortPop:{h:'सबसे लोकप्रिय',e:'Most Popular'},sortRating:{h:'टॉप रेटेड',e:'Top Rated'},sortNew:{h:'नए पहले',e:'Newest First'},sortAZ:{h:'A → Z',e:'A → Z'},
results:{h:'कोर्स मिले',e:'courses found'},srcBuiltin:{h:'बिल्ट-इन इंजन: 3,000',e:'Built-in Engine: 3,000'},srcCustom:{h:'कस्टम courses.json लोडेड',e:'Custom courses.json loaded'},
loadMore:{h:'और देखें',e:'Load More'},noResults:{h:'कोई कोर्स नहीं मिला। दूसरी खोज आज़माएँ।',e:'No courses match. Try another search.'},
details:{h:'विवरण',e:'Details'},save:{h:'सेव',e:'Save'},saved:{h:'सेव्ड',e:'Saved'},
level:{h:'लेवल',e:'Level'},weeks:{h:'सप्ताह',e:'weeks'},hpw:{h:'घंटे/सप्ताह',e:'hrs/week'},learners:{h:'सीखने वाले',e:'learners'},
duration:{h:'अवधि',e:'Duration'},effort:{h:'समय',e:'Effort'},rating:{h:'रेटिंग',e:'Rating'},mode:{h:'मोड',e:'Mode'},
onlineSelf:{h:'ऑनलाइन • सेल्फ-पेस्ड',e:'Online • Self-paced'},eligibility:{h:'योग्यता',e:'Eligibility'},salaryEst:{h:'अनुमानित सैलरी (भारत)',e:'Est. Salary (India)'},
skillsTitle:{h:'आप क्या सीखेंगे',e:'Skills you will build'},syllabusTitle:{h:'सिलेबस (6 मॉड्यूल)',e:'Syllabus (6 Modules)'},
careersTitle:{h:'करियर विकल्प',e:'Career Outcomes'},aboutTitle:{h:'इस कोर्स के बारे में',e:'About this course'},
lockedSyl:{h:'पूरा सिलेबस Smart/Pro फीचर है।',e:'Full syllabus is a Smart/Pro feature.'},unlock29:{h:'₹29 में अनलॉक',e:'Unlock ₹29'},
dlPdf:{h:'PDF डाउनलोड',e:'Download PDF'},pdf14:{h:'PDF ₹14',e:'PDF ₹14'},pdfCredit:{h:'PDF (क्रेडिट)',e:'PDF (credit)'},close:{h:'बंद करें',e:'Close'},
quizTitle:{h:'करियर डिस्कवरी क्विज़',e:'Career Discovery Quiz'},quizSub:{h:'5 आसान सवाल → आपके टॉप 3 डोमेन + कोर्स सुझाव।',e:'5 quick questions → your top 3 domains + course picks.'},
quizStart:{h:'क्विज़ शुरू करें',e:'Start Quiz'},question:{h:'सवाल',e:'Question'},of:{h:'/',e:'of'},back:{h:'पीछे',e:'Back'},restart:{h:'फिर से',e:'Restart'},
matchTitle:{h:'आपके लिए सर्वश्रेष्ठ डोमेन',e:'Your Best-Fit Domains'},match:{h:'मैच',e:'match'},recommended:{h:'सुझाए गए कोर्स',e:'Recommended Courses'},
dlReport:{h:'रिपोर्ट PDF डाउनलोड',e:'Download Report PDF'},report14:{h:'रिपोर्ट ₹14',e:'Report ₹14'},
quizNote:{h:'यह केवल मार्गदर्शन है — अपने अंक, बजट व परिवार की सलाह से मिलाएँ।',e:'Guidance only — combine with your marks, budget & family advice.'},
plansTitle:{h:'सरल माइक्रो-प्लान',e:'Simple Micro-Plans'},plansSub:{h:'100% डायरेक्ट UPI — कोई गेटवे नहीं, कोई छिपी फीस नहीं।',e:'100% direct UPI — no gateway, no hidden fees.'},
planPdfName:{h:'PDF अनलॉक',e:'PDF Unlock'},planSmartName:{h:'स्मार्ट',e:'Smart'},planProName:{h:'प्रो',e:'Pro'},perPdf:{h:'एक PDF',e:'one PDF'},per30:{h:'30 दिन',e:'30 days'},
fPdf1:{h:'कोई 1 कोर्स/क्विज़ PDF',e:'Any 1 course/quiz PDF'},fPdf2:{h:'हमेशा के लिए (इसी डिवाइस)',e:'Yours forever (this device)'},fPdf3:{h:'हिंदी या अंग्रेज़ी',e:'Hindi or English'},
fS1:{h:'सभी प्रीमियम सिलेबस अनलॉक',e:'All premium syllabi unlocked'},fS2:{h:'5 PDF क्रेडिट शामिल',e:'5 PDF credits included'},fS3:{h:'क्विज़ रिपोर्ट शामिल',e:'Quiz reports included'},fS4:{h:'30 दिन वैध',e:'Valid 30 days'},
fP1:{h:'Smart का सब कुछ',e:'Everything in Smart'},fP2:{h:'अनलिमिटेड PDF',e:'Unlimited PDFs'},fP3:{h:'प्राथमिकता सहायता',e:'Priority support'},fP4:{h:'30 दिन वैध',e:'Valid 30 days'},
buy:{h:'UPI से भुगतान',e:'Pay via UPI'},curPlan:{h:'आपका प्लान',e:'Your Plan'},noPlan:{h:'कोई सक्रिय प्लान नहीं',e:'No active plan'},
validTill:{h:'वैध तिथि',e:'Valid till'},creditsLeft:{h:'PDF क्रेडिट बचे',e:'PDF credits left'},
howTitle:{h:'भुगतान कैसे होता है',e:'How payment works'},
how1:{h:'पे दबाएँ → UPI ऐप राशि के साथ खुलेगा।',e:'Tap pay → your UPI app opens with amount pre-filled.'},
how2:{h:'भुगतान करें व 12-अंकों का UTR कॉपी करें।',e:'Pay & copy the 12-digit UTR / Ref No.'},
how3:{h:'UTR यहाँ डालें → इस डिवाइस पर तुरंत अनलॉक।',e:'Enter UTR here → instant unlock on this device.'},
payDisclaimer:{h:'स्टैटिक ऐप: अनलॉक इसी डिवाइस पर होता है। भुगतान मैन्युअल जाँचा जाता है; रसीद सुरक्षित रखें।',e:'Static app: unlocks are trust-based & device-local. Payments are verified manually; keep your receipt.'},
txnTitle:{h:'भुगतान इतिहास (यह डिवाइस)',e:'Payment History (this device)'},noTxns:{h:'अभी कोई भुगतान नहीं।',e:'No payments yet.'},
payTitle:{h:'भुगतान',e:'Pay'},item:{h:'आइटम',e:'Item'},amount:{h:'राशि',e:'Amount'},
gpay:{h:'Google Pay',e:'Google Pay'},phonepe:{h:'PhonePe',e:'PhonePe'},paytm:{h:'Paytm',e:'Paytm'},anyUpi:{h:'कोई भी UPI / BHIM',e:'Any UPI / BHIM'},
cardPay:{h:'कार्ड / नेटबैंकिंग (पेमेंट लिंक)',e:'Card / NetBanking (payment link)'},
manualPay:{h:'या इस UPI ID पर मैन्युअल भुगतान करें:',e:'Or pay manually to this UPI ID:'},copy:{h:'कॉपी',e:'Copy'},copied:{h:'कॉपी हो गया!',e:'Copied!'},
desktopNote:{h:'PC पर? फोन से इस UPI ID पर भुगतान करें, फिर नीचे UTR डालें।',e:'On PC? Pay from your phone to this UPI ID, then enter UTR below.'},
opening:{h:'UPI ऐप खुल रहा है…',e:'Opening UPI app…'},paidBtn:{h:'भुगतान हो गया → UTR डालें',e:'I have Paid → Enter UTR'},
utrTitle:{h:'भुगतान पुष्टि',e:'Confirm Payment'},utrLabel:{h:'12-अंकों का UTR / UPI Ref नं.',e:'12-digit UTR / UPI Ref No.'},
utrPh:{h:'जैसे 415223344556',e:'e.g. 415223344556'},verifyBtn:{h:'जाँचें व अनलॉक करें',e:'Verify & Unlock'},
utrErr:{h:'मान्य 12-अंकों का UTR डालें।',e:'Enter a valid 12-digit UTR.'},
paySuccess:{h:'भुगतान दर्ज — अनलॉक हो गया!',e:'Payment recorded — unlocked!'},continueBtn:{h:'जारी रखें',e:'Continue'},cancel:{h:'रद्द करें',e:'Cancel'},
libTitle:{h:'मेरी लाइब्रेरी',e:'My Library'},guest:{h:'अतिथि (डिवाइस-लोकल प्रोफ़ाइल)',e:'Guest (device-local profile)'},
savedTitle:{h:'सेव किए कोर्स',e:'Saved Courses'},noSaved:{h:'किसी कोर्स पर ☆ दबाकर सेव करें।',e:'Tap ☆ on any course to save it.'},
pdfsTitle:{h:'मेरे PDFs',e:'My PDFs'},noPdfs:{h:'खरीदे गए PDF यहाँ दिखेंगे।',e:'Purchased PDFs appear here.'},redl:{h:'फिर डाउनलोड',e:'Re-download'},
installApp:{h:'ऐप इंस्टॉल करें',e:'Install App'},installed:{h:'ऐप इंस्टॉल ✓',e:'App installed ✓'},
iosHint:{h:'iPhone: Share → Add to Home Screen',e:'iPhone: Share → Add to Home Screen'},
installHint:{h:'ब्राउज़र मेनू → Install app',e:'Use browser menu → Install app'},
toolsTitle:{h:'टूल्स व सेटिंग्स',e:'Tools & Settings'},exIcons:{h:'PNG आइकन एक्सपोर्ट (PWABuilder हेतु)',e:'Export PNG icons (for PWABuilder)'},
exIconsDone:{h:'icon-192.png व icon-512.png डाउनलोड ✓',e:'icon-192.png & icon-512.png downloaded ✓'},
exData:{h:'मेरा डेटा एक्सपोर्ट (JSON)',e:'Export my data (JSON)'},resetApp:{h:'ऐप डेटा रीसेट',e:'Reset app data'},
resetConfirm:{h:'सारा लोकल डेटा हटाएँ (सेव, अनलॉक, प्लान)?',e:'Delete all local data (saves, unlocks, plan)?'},
aboutApp:{h:'ऐप के बारे में',e:'About'},version:{h:'वर्ज़न',e:'Version'},upiLabel:{h:'मर्चेंट UPI',e:'Merchant UPI'},supportLabel:{h:'सहायता',e:'Support'},
offlineMsg:{h:'ऑफ़लाइन — कैश्ड कंटेंट चालू',e:'Offline — cached content active'},onlineMsg:{h:'फिर से ऑनलाइन',e:'Back online'},
updAvail:{h:'नया वर्ज़न तैयार',e:'New version ready'},refresh:{h:'रिफ्रेश',e:'Refresh'},
pdfBusy:{h:'PDF बन रहा है…',e:'Generating PDF…'},pdfDone:{h:'PDF डाउनलोड ✓',e:'PDF downloaded ✓'},
pdfLibFail:{h:'PDF लाइब्रेरी लोड नहीं — एक बार ऑनलाइन आएँ।',e:'PDF library not loaded — go online once.'},
savedToast:{h:'सेव ✓',e:'Saved ✓'},removedToast:{h:'सेव से हटाया',e:'Removed from saved'},undo:{h:'वापस लाएँ',e:'Undo'},
footer:{h:'भारत में निर्मित 🇮🇳 • ऑफ़लाइन-फर्स्ट PWA • कोई बैकएंड नहीं',e:'Made in India 🇮🇳 • Offline-first PWA • No backend'},
free:{h:'फ्री',e:'Free'},smart:{h:'स्मार्ट',e:'Smart'},pro:{h:'प्रो',e:'Pro'},
rptCourse:{h:'कोर्स रोडमैप रिपोर्ट',e:'Course Roadmap Report'},rptQuiz:{h:'करियर डिस्कवरी रिपोर्ट',e:'Career Discovery Report'},
generated:{h:'जनरेटेड',e:'Generated'},
ns1:{h:'चुने हुए डोमेन के 2 फ्री कोर्स से शुरुआत करें।',e:'Start with 2 free courses from your top domain.'},
ns2:{h:'हर हफ्ते 6–8 घंटे तय करें, पोर्टफोलियो बनाएँ।',e:'Fix 6–8 hours weekly and build a portfolio.'},
ns3:{h:'12वीं/स्नातक के अनुसार परीक्षा या स्किल ट्रैक चुनें।',e:'Pick exam or skill track as per your 12th/degree stage.'}
};

/* ================= DATA ================= */
const p=(e,h)=>({e,h});
const DOM=[
{i:'🎓',n:p('After 10th & 12th Streams','10वीं/12वीं के बाद स्ट्रीम्स'),el:p('Class 10/12 pass (any board)','कक्षा 10/12 उत्तीर्ण (कोई भी बोर्ड)'),sal:2.4,
 sk:[p('Stream selection','स्ट्रीम चयन'),p('Entrance strategy','एंट्रेंस रणनीति'),p('Board exam planning','बोर्ड परीक्षा योजना'),p('Scholarships','स्कॉलरशिप'),p('Career mapping','करियर मैपिंग'),p('Study timetable','स्टडी टाइमटेबल')],
 ro:[p('Engineer','इंजीनियर'),p('Doctor','डॉक्टर'),p('Civil servant','सिविल अधिकारी'),p('Teacher','शिक्षक')]},
{i:'🧬',n:p('Science, Pharma & Healthcare','साइंस, फार्मा व हेल्थकेयर'),el:p('12th Science (PCB/PCM); NEET for MBBS)','12वीं साइंस (PCB/PCM); MBBS हेतु NEET'),sal:3.0,
 sk:[p('Lab & clinical skills','लैब व क्लिनिकल स्किल'),p('ICD-10 coding','ICD-10 कोडिंग'),p('Drug safety','ड्रग सेफ्टी'),p('Patient care','रोगी देखभाल'),p('Research methods','रिसर्च विधि'),p('Medical terminology','मेडिकल टर्मिनोलॉजी')],
 ro:[p('Pharmacist','फार्मासिस्ट'),p('Nurse','नर्स'),p('Medical coder','मेडिकल कोडर'),p('Clinical researcher','क्लिनिकल रिसर्चर')]},
{i:'🤖',n:p('AI, GenAI & Automation','एआई, जेनएआई व ऑटोमेशन'),el:p('Basic computer + English reading','बेसिक कंप्यूटर + अंग्रेज़ी पढ़ना'),sal:6.0,
 sk:[p('Prompt design','प्रॉम्प्ट डिज़ाइन'),p('Workflow automation','वर्कफ़्लो ऑटोमेशन'),p('LLM apps','एलएलएम ऐप्स'),p('APIs & webhooks','API व वेबहुक'),p('Vector search','वेक्टर सर्च'),p('AI product thinking','एआई प्रोडक्ट सोच')],
 ro:[p('AI engineer','एआई इंजीनियर'),p('Automation expert','ऑटोमेशन एक्सपर्ट'),p('Prompt engineer','प्रॉम्प्ट इंजीनियर'),p('AI consultant','एआई कंसल्टेंट')]},
{i:'💻',n:p('Software, Web & App Dev','सॉफ्टवेयर, वेब व ऐप डेव'),el:p('12th pass; logic aptitude','12वीं उत्तीर्ण; लॉजिक क्षमता'),sal:5.0,
 sk:[p('Coding logic','कोडिंग लॉजिक'),p('Frontend & backend','फ्रंटएंड व बैकएंड'),p('Databases','डेटाबेस'),p('Git workflow','गिट वर्कफ़्लो'),p('Testing & debugging','टेस्टिंग व डिबगिंग'),p('Deployment','डिप्लॉयमेंट')],
 ro:[p('Web developer','वेब डेवलपर'),p('App developer','ऐप डेवलपर'),p('QA engineer','क्यूए इंजीनियर'),p('DevOps engineer','डेवऑप्स इंजीनियर')]},
{i:'🏛️',n:p('Govt Jobs & Competitive Exams','सरकारी नौकरी व प्रतियोगी परीक्षा'),el:p('As per exam: 10th/12th/Graduation','परीक्षा अनुसार: 10वीं/12वीं/स्नातक'),sal:3.2,
 sk:[p('GK & current affairs','जीके व करंट अफेयर्स'),p('Quant & reasoning','क्वांट व रीज़निंग'),p('Answer writing','उत्तर लेखन'),p('Exam strategy','परीक्षा रणनीति'),p('Hindi & English','हिंदी व अंग्रेज़ी'),p('Mock test analysis','मॉक टेस्ट विश्लेषण')],
 ro:[p('IAS/PCS officer','आईएएस/पीसीएस अधिकारी'),p('SSC inspector','एसएससी इंस्पेक्टर'),p('Bank PO','बैंक पीओ'),p('Defence officer','डिफेंस अधिकारी')]},
{i:'📊',n:p('Commerce, Finance & Accounting','कॉमर्स, फाइनेंस व अकाउंटिंग'),el:p('12th Commerce (Maths for some)','12वीं कॉमर्स (कुछ में गणित)'),sal:4.0,
 sk:[p('Accounting entries','अकाउंटिंग एंट्री'),p('GST & tax filing','जीएसटी व टैक्स फाइलिंग'),p('Financial analysis','फाइनेंशियल विश्लेषण'),p('Excel modelling','एक्सेल मॉडलिंग'),p('Audit basics','ऑडिट बेसिक्स'),p('Market basics','बाज़ार बेसिक्स')],
 ro:[p('Accountant','अकाउंटेंट'),p('CA/CS/CMA','सीए/सीएस/सीएमए'),p('Financial analyst','फाइनेंशियल एनालिस्ट'),p('Tax consultant','टैक्स कंसल्टेंट')]},
{i:'🎨',n:p('Design, Media & Creative','डिज़ाइन, मीडिया व क्रिएटिव'),el:p('10th pass + creative interest','10वीं उत्तीर्ण + रचनात्मक रुचि'),sal:3.0,
 sk:[p('Visual design','विज़ुअल डिज़ाइन'),p('Editing tools','एडिटिंग टूल्स'),p('Storytelling','स्टोरीटेलिंग'),p('Brand identity','ब्रांड पहचान'),p('Portfolio building','पोर्टफोलियो'),p('Client handling','क्लाइंट हैंडलिंग')],
 ro:[p('Graphic designer','ग्राफिक डिज़ाइनर'),p('Video editor','वीडियो एडिटर'),p('UI/UX designer','यूआई/यूएक्स डिज़ाइनर'),p('Content creator','कंटेंट क्रिएटर')]},
{i:'📈',n:p('Digital Marketing & E-Commerce','डिजिटल मार्केटिंग व ई-कॉमर्स'),el:p('10th pass + smartphone/laptop','10वीं उत्तीर्ण + स्मार्टफोन/लैपटॉप'),sal:3.2,
 sk:[p('SEO & ads','एसईओ व ऐड्स'),p('Social growth','सोशल ग्रोथ'),p('Marketplace selling','मार्केटप्लेस सेलिंग'),p('Analytics','एनालिटिक्स'),p('Funnels & CRM','फनल व सीआरएम'),p('Copy & creatives','कॉपी व क्रिएटिव')],
 ro:[p('Digital marketer','डिजिटल मार्केटर'),p('E-com seller','ई-कॉम सेलर'),p('Performance marketer','परफॉर्मेंस मार्केटर'),p('Freelancer','फ्रीलांसर')]},
{i:'⚙️',n:p('Core Engineering & New-Age Tech','कोर इंजीनियरिंग व न्यू-एज टेक'),el:p('10th/ITI/Diploma (trade-wise)','10वीं/आईटीआई/डिप्लोमा (ट्रेड अनुसार)'),sal:3.0,
 sk:[p('Technical drawing','टेक्निकल ड्रॉइंग'),p('Machine handling','मशीन हैंडलिंग'),p('Safety standards','सेफ्टी मानक'),p('EV/solar systems','ईवी/सोलर सिस्टम'),p('Troubleshooting','ट्रबलशूटिंग'),p('Site practice','साइट प्रैक्टिस')],
 ro:[p('Site engineer','साइट इंजीनियर'),p('EV technician','ईवी टेक्नीशियन'),p('Solar installer','सोलर इंस्टॉलर'),p('Drone pilot','ड्रोन पायलट')]},
{i:'🗣️',n:p('Business, Languages & Soft Skills','बिज़नेस, भाषाएँ व सॉफ्ट स्किल्स'),el:p('Open to all ages','सभी उम्र के लिए खुला'),sal:3.0,
 sk:[p('Communication','कम्युनिकेशन'),p('Confidence','आत्मविश्वास'),p('Interview skills','इंटरव्यू स्किल'),p('Business basics','बिज़नेस बेसिक्स'),p('Language fluency','भाषा प्रवाह'),p('Leadership','लीडरशिप')],
 ro:[p('Business owner','बिज़नेस ओनर'),p('HR executive','एचआर एग्जीक्यूटिव'),p('Sales manager','सेल्स मैनेजर'),p('Translator','ट्रांसलेटर')]}
];

const BASE=[
[p('PCM (11th–12th)','पीसीएम (11वीं–12वीं)'),p('PCB (11th–12th)','पीसीबी (11वीं–12वीं)'),p('PCMB (11th–12th)','पीसीएमबी (11वीं–12वीं)'),p('Commerce with Maths','गणित सहित कॉमर्स'),p('Commerce without Maths','गणित रहित कॉमर्स'),p('Arts / Humanities','आर्ट्स / ह्यूमैनिटीज'),p('Polytechnic Diploma','पॉलिटेक्निक डिप्लोमा'),p('ITI Trades','आईटीआई ट्रेड्स'),p('NIOS Open Schooling','एनआईओएस ओपन स्कूल'),p('CUET UG Prep','सीयूईटी यूजी तैयारी'),p('JEE Main Foundation','जेईई मेन फाउंडेशन'),p('NEET Foundation','नीट फाउंडेशन'),p('NDA After 12th','12वीं के बाद एनडीए'),p('CLAT (Law)','क्लैट (लॉ)'),p('BBA Entrance','बीबीए एंट्रेंस'),p('Hotel Management (NCHM JEE)','होटल मैनेजमेंट (NCHM JEE)'),p('B.Sc Agriculture','बीएससी कृषि'),p('B.Ed & D.ElEd Teaching','बी.एड व डी.एल.एड'),p('BCA After 12th','12वीं के बाद बीसीए'),p('B.Com Honours','बी.कॉम ऑनर्स'),p('BA Psychology','बीए मनोविज्ञान'),p('Defence (Agniveer)','डिफेंस (अग्निवीर)'),p('Paramedical (DMLT)','पैरामेडिकल (DMLT)'),p('Aviation (Cabin Crew)','एविएशन (केबिन क्रू)'),p('Sports & PE (B.P.Ed)','स्पोर्ट्स व पीई (B.P.Ed)')],
[p('B.Pharm','बी.फार्मा'),p('D.Pharm','डी.फार्मा'),p('M.Pharm','एम.फार्मा'),p('B.Sc Biotechnology','बीएससी बायोटेक्नोलॉजी'),p('B.Sc Microbiology','बीएससी माइक्रोबायोलॉजी'),p('B.Sc BioScience','बीएससी बायोसाइंस'),p('B.Sc Nursing','बीएससी नर्सिंग'),p('GNM Nursing','जीएनएम नर्सिंग'),p('MBBS (NEET-UG)','एमबीबीएस (NEET-UG)'),p('BDS Dental','बीडीएस डेंटल'),p('BAMS Ayurveda','बीएएमएस आयुर्वेद'),p('BPT Physiotherapy','बीपीटी फिजियोथेरेपी'),p('Medical Coding ICD-10','मेडिकल कोडिंग ICD-10'),p('Pharmacovigilance','फार्माकोविजिलेंस'),p('Clinical Data Management','क्लिनिकल डेटा मैनेजमेंट'),p('Clinical Research','क्लिनिकल रिसर्च'),p('Medical Lab Technology (BMLT)','मेडिकल लैब टेक्नोलॉजी (BMLT)'),p('Radiology & Imaging','रेडियोलॉजी व इमेजिंग'),p('Hospital Administration','हॉस्पिटल एडमिनिस्ट्रेशन'),p('Public Health (BPH/MPH)','पब्लिक हेल्थ (BPH/MPH)'),p('Nutrition & Dietetics','न्यूट्रिशन व डाइटेटिक्स'),p('Drug Regulatory Affairs','ड्रग रेगुलेटरी अफेयर्स'),p('QC/QA Pharma','क्यूसी/क्यूए फार्मा'),p('Forensic Science','फोरेंसिक साइंस'),p('Biomedical Engineering','बायोमेडिकल इंजीनियरिंग')],
[p('Prompt Engineering','प्रॉम्प्ट इंजीनियरिंग'),p('ChatGPT for Work','काम के लिए ChatGPT'),p('n8n Automation','n8n ऑटोमेशन'),p('Make.com Automation','Make.com ऑटोमेशन'),p('Zapier Workflows','ज़ैपियर वर्कफ़्लो'),p('AI Agents (LangChain)','एआई एजेंट्स (LangChain)'),p('RAG & Vector DBs','RAG व वेक्टर डेटाबेस'),p('LangGraph Multi-Agent','लैंगग्राफ मल्टी-एजेंट'),p('Python for AI','एआई के लिए पायथन'),p('Machine Learning','मशीन लर्निंग'),p('Deep Learning','डीप लर्निंग'),p('NLP & LLM Fine-tuning','एनएलपी व एलएलएम फाइन-ट्यूनिंग'),p('Computer Vision','कंप्यूटर विज़न'),p('Generative Image AI','जेनरेटिव इमेज एआई'),p('AI Video & Avatars','एआई वीडियो व अवतार'),p('Voice AI & TTS','वॉइस एआई व TTS'),p('MLOps & Deployment','एमएलऑप्स व डिप्लॉयमेंट'),p('AI for Excel & Sheets','एक्सेल व शीट्स के लिए एआई'),p('No-Code AI Apps','नो-कोड एआई ऐप्स'),p('WhatsApp Bot Automation','व्हाट्सएप बॉट ऑटोमेशन'),p('AI Content Writing','एआई कंटेंट राइटिंग'),p('AI for Teachers','शिक्षकों के लिए एआई'),p('Data Annotation & RLHF','डेटा एनोटेशन व RLHF'),p('AI Product Management','एआई प्रोडक्ट मैनेजमेंट'),p('AI Ethics & Safety','एआई एथिक्स व सेफ्टी')],
[p('HTML/CSS/JavaScript','एचटीएमएल/सीएसएस/जावास्क्रिप्ट'),p('React.js','रिएक्ट.js'),p('Angular','एंगुलर'),p('Vue.js','व्यू.js'),p('Node.js & Express','नोड.js व एक्सप्रेस'),p('Python Django','पायथन जैंगो'),p('PHP & Laravel','पीएचपी व लारावेल'),p('Java & Spring Boot','जावा व स्प्रिंग बूट'),p('Android (Kotlin)','एंड्रॉइड (कोटलिन)'),p('Flutter Apps','फ्लटर ऐप्स'),p('React Native','रिएक्ट नेटिव'),p('iOS Swift','आईओएस स्विफ्ट'),p('Full-Stack MERN','फुल-स्टैक MERN'),p('SQL & Databases','एसक्यूएल व डेटाबेस'),p('MongoDB','मोंगोडीबी'),p('DevOps & Docker','डेवऑप्स व डॉकर'),p('AWS Cloud','एडब्ल्यूएस क्लाउड'),p('Git & GitHub','गिट व गिटहब'),p('Software Testing (QA)','सॉफ्टवेयर टेस्टिंग (QA)'),p('Selenium Automation','सेलेनियम ऑटोमेशन'),p('Cyber Security','साइबर सुरक्षा'),p('Ethical Hacking','एथिकल हैकिंग'),p('Blockchain & Web3','ब्लॉकचेन व Web3'),p('Game Dev (Unity)','गेम डेव (यूनिटी)'),p('PWA & Firebase','पीडब्ल्यूए व फायरबेस')],
[p('UPSC CSE','यूपीएससी CSE'),p('UPSC CAPF','यूपीएससी CAPF'),p('State PSC','स्टेट पीएससी'),p('SSC CGL','एसएससी CGL'),p('SSC CHSL','एसएससी CHSL'),p('SSC GD Constable','एसएससी GD कांस्टेबल'),p('Banking PO (IBPS)','बैंकिंग PO (IBPS)'),p('SBI Clerk','एसबीआई क्लर्क'),p('RBI Grade B','आरबीआई ग्रेड B'),p('Railway NTPC','रेलवे NTPC'),p('Railway Group D','रेलवे ग्रुप D'),p('RRB JE','आरआरबी JE'),p('Indian Army','इंडियन आर्मी'),p('Indian Navy','इंडियन नेवी'),p('Indian Air Force','इंडियन एयर फोर्स'),p('Police Constable','पुलिस कांस्टेबल'),p('Police SI','पुलिस एसआई'),p('CTET & TET','सीटेट व टेट'),p('KVS/NVS Teacher','केवीएस/एनवीएस शिक्षक'),p('Judiciary (PCS-J)','ज्यूडिशियरी (PCS-J)'),p('SSC Stenographer','एसएससी स्टेनोग्राफर'),p('Post Office GDS','पोस्ट ऑफिस GDS'),p('LIC AAO','एलआईसी AAO'),p('Forest Guard','फॉरेस्ट गार्ड'),p('UGC NET','यूजीसी नेट')],
[p('CA Foundation','सीए फाउंडेशन'),p('CA Inter','सीए इंटर'),p('CS Executive','सीएस एग्जीक्यूटिव'),p('CMA','सीएमए'),p('Tally Prime + GST','टैली प्राइम + जीएसटी'),p('GST Practitioner','जीएसटी प्रैक्टिशनर'),p('Income Tax & ITR','इनकम टैक्स व आईटीआर'),p('Advanced Excel','एडवांस्ड एक्सेल'),p('Financial Modelling','फाइनेंशियल मॉडलिंग'),p('Stock Market Basics','शेयर बाज़ार बेसिक्स'),p('Technical Analysis','टेक्निकल एनालिसिस'),p('Mutual Funds & SIP','म्यूचुअल फंड व एसआईपी'),p('NISM Certifications','एनआईएसएम सर्टिफिकेशन'),p('Banking & Finance','बैंकिंग व फाइनेंस'),p('Insurance Advisor','इंश्योरेंस एडवाइज़र'),p('Accounting Fundamentals','अकाउंटिंग फंडामेंटल्स'),p('Auditing','ऑडिटिंग'),p('Payroll Management','पेरोल मैनेजमेंट'),p('Business Analytics','बिज़नेस एनालिटिक्स'),p('Power BI','पावर बीआई'),p('Tableau','टैब्लू'),p('Fintech & UPI Systems','फिनटेक व यूपीआई सिस्टम'),p('Crypto & Taxation','क्रिप्टो व टैक्सेशन'),p('Actuarial Science','एक्चुएरियल साइंस'),p('CFA Level 1','सीएफए लेवल 1')],
[p('Graphic Design (Photoshop)','ग्राफिक डिज़ाइन (फोटोशॉप)'),p('Illustrator & Branding','इलस्ट्रेटर व ब्रांडिंग'),p('UI Design (Figma)','यूआई डिज़ाइन (फिग्मा)'),p('UX Research','यूएक्स रिसर्च'),p('Canva Pro Design','कैनवा प्रो डिज़ाइन'),p('Video Editing (Premiere)','वीडियो एडिटिंग (प्रीमियर)'),p('After Effects & Motion','आफ्टर इफेक्ट्स व मोशन'),p('CapCut & Reels Editing','कैपकट व रील्स एडिटिंग'),p('YouTube Channel Mastery','यूट्यूब चैनल मास्टरी'),p('Photography','फोटोग्राफी'),p('Mobile Videography','मोबाइल वीडियोग्राफी'),p('3D Design (Blender)','3डी डिज़ाइन (ब्लेंडर)'),p('2D Animation','2डी एनीमेशन'),p('VFX Basics','वीएफएक्स बेसिक्स'),p('Podcast Production','पॉडकास्ट प्रोडक्शन'),p('Voice Over & Dubbing','वॉइस ओवर व डबिंग'),p('Content Writing (Hindi)','कंटेंट राइटिंग (हिंदी)'),p('Copywriting','कॉपीराइटिंग'),p('Script Writing','स्क्रिप्ट राइटिंग'),p('Journalism & Reporting','जर्नलिज़्म व रिपोर्टिंग'),p('Fashion Design','फैशन डिज़ाइन'),p('Interior Design','इंटीरियर डिज़ाइन'),p('Product Design','प्रोडक्ट डिज़ाइन'),p('Game Art','गेम आर्ट'),p('Music Production','म्यूज़िक प्रोडक्शन')],
[p('Digital Marketing 360','डिजिटल मार्केटिंग 360'),p('SEO','एसईओ'),p('Google Ads','गूगल ऐड्स'),p('Meta Ads (FB/Insta)','मेटा ऐड्स (FB/Insta)'),p('Instagram Growth','इंस्टाग्राम ग्रोथ'),p('YouTube Marketing','यूट्यूब मार्केटिंग'),p('WhatsApp Marketing','व्हाट्सएप मार्केटिंग'),p('Email Marketing','ईमेल मार्केटिंग'),p('Affiliate Marketing','एफिलिएट मार्केटिंग'),p('Influencer Marketing','इन्फ्लुएंसर मार्केटिंग'),p('Amazon Seller','अमेज़न सेलर'),p('Flipkart Seller','फ्लिपकार्ट सेलर'),p('Meesho Reselling','मीशो रीसेलिंग'),p('Shopify Store','शॉपिफाई स्टोर'),p('Dropshipping','ड्रॉपशिपिंग'),p('D2C Brand Building','डी2सी ब्रांड बिल्डिंग'),p('Google Analytics 4','गूगल एनालिटिक्स 4'),p('Marketing Automation','मार्केटिंग ऑटोमेशन'),p('Local Business (GMB)','लोकल बिज़नेस (GMB)'),p('LinkedIn Personal Brand','लिंक्डइन पर्सनल ब्रांड'),p('Freelancing (Upwork)','फ्रीलांसिंग (अपवर्क)'),p('Blogging & AdSense','ब्लॉगिंग व ऐडसेंस'),p('Print-on-Demand','प्रिंट-ऑन-डिमांड'),p('Online Course Selling','ऑनलाइन कोर्स सेलिंग'),p('CRM & Sales Funnels','सीआरएम व सेल्स फनल')],
[p('Mechanical CAD','मैकेनिकल कैड'),p('AutoCAD','ऑटोकैड'),p('SolidWorks','सॉलिडवर्क्स'),p('CNC & VMC Programming','सीएनसी व वीएमसी प्रोग्रामिंग'),p('Civil Site Engineering','सिविल साइट इंजीनियरिंग'),p('Structural Design (STAAD)','स्ट्रक्चरल डिज़ाइन (STAAD)'),p('Electrical Wiring & Panel','इलेक्ट्रिकल वायरिंग व पैनल'),p('PLC & SCADA','पीएलसी व स्काडा'),p('Robotics & Arduino','रोबोटिक्स व अरडुइनो'),p('IoT','आईओटी'),p('Embedded Systems','एम्बेडेड सिस्टम्स'),p('EV Technology & Repair','ईवी टेक्नोलॉजी व रिपेयर'),p('Battery Tech (BMS)','बैटरी टेक (BMS)'),p('Solar Installation & Design','सोलर इंस्टॉलेशन व डिज़ाइन'),p('Drone Tech & Piloting','ड्रोन टेक व पायलटिंग'),p('3D Printing','3डी प्रिंटिंग'),p('HVAC & Refrigeration','एचवीएसी व रेफ्रिजरेशन'),p('Welding & Fabrication','वेल्डिंग व फैब्रिकेशन'),p('Automobile Service','ऑटोमोबाइल सर्विस'),p('Mobile Repairing','मोबाइल रिपेयरिंग'),p('Laptop & PC Repair','लैपटॉप व पीसी रिपेयर'),p('CCTV & Networking','सीसीटीवी व नेटवर्किंग'),p('Telecom & 5G','टेलीकॉम व 5जी'),p('Aerospace Basics','एयरोस्पेस बेसिक्स'),p('Industrial Safety','इंडस्ट्रियल सेफ्टी')],
[p('Spoken English','स्पोकन इंग्लिश'),p('English Grammar','इंग्लिश ग्रैमर'),p('IELTS','आईईएलटीएस'),p('PTE','पीटीई'),p('Business Communication','बिज़नेस कम्युनिकेशन'),p('Public Speaking','पब्लिक स्पीकिंग'),p('Personality Development','पर्सनैलिटी डेवलपमेंट'),p('Interview Mastery','इंटरव्यू मास्टरी'),p('Resume & LinkedIn','रिज़्यूमे व लिंक्डइन'),p('Time Management','टाइम मैनेजमेंट'),p('Leadership','लीडरशिप'),p('Emotional Intelligence','इमोशनल इंटेलिजेंस'),p('Entrepreneurship','एंटरप्रेन्योरशिप'),p('Startup Fundraising','स्टार्टअप फंडरेज़िंग'),p('MSME & Udyam Registration','एमएसएमई व उद्यम रजिस्ट्रेशन'),p('Sales Mastery','सेल्स मास्टरी'),p('Negotiation Skills','नेगोशिएशन स्किल्स'),p('Customer Service','कस्टमर सर्विस'),p('BPO & KPO Jobs','बीपीओ व केपीओ जॉब्स'),p('Data Entry & Typing','डेटा एंट्री व टाइपिंग'),p('Hindi Typing (Mangal)','हिंदी टाइपिंग (मंगल)'),p('German Language','जर्मन भाषा'),p('French Language','फ्रेंच भाषा'),p('Japanese (JLPT)','जापानी (JLPT)'),p('Yoga & Wellness Instructor','योग व वेलनेस इंस्ट्रक्टर')]
];

const LVL=[p('Foundation','फाउंडेशन'),p('Beginner','बिगिनर'),p('Intermediate','इंटरमीडिएट'),p('Advanced','एडवांस्ड'),p('Expert','एक्सपर्ट'),p('Mastery','मास्टरी'),p('Professional','प्रोफेशनल'),p('Specialist','स्पेशलिस्ट'),p('Industry Projects','इंडस्ट्री प्रोजेक्ट्स'),p('Capstone & Internship','कैपस्टोन व इंटर्नशिप'),p('Trainer Certification','ट्रेनर सर्टिफिकेशन'),p('Career Pro (Job Ready)','करियर प्रो (जॉब रेडी)')];

const SYL=[
{t:p('Orientation & Foundations','ओरिएंटेशन व नींव'),d:p('What is {c}, scope in India, tools setup.','{c} क्या है, भारत में स्कोप, टूल्स सेटअप।')},
{t:p('Core Concepts','कोर कॉन्सेप्ट्स'),d:p('Level-wise theory + daily practice drills.','लेवल अनुसार थ्योरी + डेली प्रैक्टिस।')},
{t:p('Hands-on Tools Lab','हैंड्स-ऑन टूल लैब'),d:p('Guided exercises on industry tools.','इंडस्ट्री टूल्स पर गाइडेड अभ्यास।')},
{t:p('Indian Case Studies','भारतीय केस स्टडीज़'),d:p('Real examples from Indian market & exams.','भारतीय बाज़ार व परीक्षाओं के वास्तविक उदाहरण।')},
{t:p('Project & Portfolio','प्रोजेक्ट व पोर्टफोलियो'),d:p('Build 2 portfolio-ready projects.','2 पोर्टफोलियो-रेडी प्रोजेक्ट बनाएँ।')},
{t:p('Certification & Career Prep','सर्टिफिकेशन व करियर तैयारी'),d:p('Mock tests, interview/exam strategy, next steps.','मॉक टेस्ट, इंटरव्यू/परीक्षा रणनीति, अगले कदम।')}
];

const QUIZ=[
{q:p('Which activity do you enjoy the most?','आपको सबसे ज़्यादा कौन-सा काम पसंद है?'),o:[
 {t:p('Experiments, labs & health science','प्रयोग, लैब व हेल्थ साइंस'),w:{1:3,8:1}},
 {t:p('Coding, apps & computers','कोडिंग, ऐप्स व कंप्यूटर'),w:{3:3,2:2}},
 {t:p('Business, money & markets','बिज़नेस, पैसा व बाज़ार'),w:{5:3,7:2}},
 {t:p('Art, design & content creation','कला, डिज़ाइन व कंटेंट'),w:{6:3,7:1}}]},
{q:p('What is your top priority right now?','अभी आपकी सबसे बड़ी प्राथमिकता क्या है?'),o:[
 {t:p('Sarkari job & security','सरकारी नौकरी व सुरक्षा'),w:{4:3,0:1,9:1}},
 {t:p('High-salary private career','हाई-सैलरी प्राइवेट करियर'),w:{3:2,2:2,5:1,0:1}},
 {t:p('Serve in healthcare','हेल्थकेयर में सेवा'),w:{1:3,0:1}},
 {t:p('My own business / brand','अपना बिज़नेस / ब्रांड'),w:{7:2,9:2,5:1,0:1}}]},
{q:p('Favourite subject?','पसंदीदा विषय?'),o:[
 {t:p('Maths & Logic','गणित व लॉजिक'),w:{3:2,5:2,2:1}},
 {t:p('Biology & Chemistry','जीव विज्ञान व रसायन'),w:{1:3}},
 {t:p('History, Polity & Society','इतिहास, राजव्यवस्था व समाज'),w:{4:3,9:1}},
 {t:p('Computers & Technology','कंप्यूटर व टेक्नोलॉजी'),w:{3:3,2:2}}]},
{q:p('Preferred work style?','पसंदीदा कार्य-शैली?'),o:[
 {t:p('Deep focus at a desk','डेस्क पर गहरा फोकस'),w:{3:2,2:1,5:1}},
 {t:p('Field work & machines','फील्ड वर्क व मशीनें'),w:{8:3,1:1}},
 {t:p('Creative studio flow','क्रिएटिव स्टूडियो'),w:{6:3}},
 {t:p('People, sales & leadership','लोग, सेल्स व लीडरशिप'),w:{7:2,9:2,4:1}}]},
{q:p('Your 5-year dream?','5 साल बाद का सपना?'),o:[
 {t:p('Officer / authority post','अधिकारी / सम्मानित पद'),w:{4:3}},
 {t:p('Global tech expert','ग्लोबल टेक एक्सपर्ट'),w:{2:2,3:2}},
 {t:p('Doctor / scientist','डॉक्टर / साइंटिस्ट'),w:{1:3}},
 {t:p('Creator / entrepreneur','क्रिएटर / उद्यमी'),w:{6:2,7:2,9:1}}]}
];

/* ================= STATE ================= */
const KEY='dvpro_state_v1';
let S={lang:'hi',saved:[],unlocked:[],credits:0,plan:null,planExp:0,txns:[],quiz:null};
function save(){try{localStorage.setItem(KEY,JSON.stringify(S));}catch(_){}}
function loadState(){try{const j=JSON.parse(localStorage.getItem(KEY));if(j&&typeof j==='object')S=Object.assign(S,j);}catch(_){}}

/* ================= HELPERS ================= */
const $=s=>document.querySelector(s),$$=s=>document.querySelectorAll(s);
const esc=s=>String(s).replace(/[&<>"']/g,m=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#39;'}[m]));
const fmt=n=>Number(n).toLocaleString('en-IN');
const t=k=>T[k]?(T[k][S.lang]||T[k].e):k;
const tl=o=>o?(o[S.lang]||o.e):'';
const AND=/Android/i.test(navigator.userAgent);
let toastTimer=null,toastFn=null;
function toast(msg,action,fn){
  $('#toastTxt').textContent=msg;const b=$('#toastAct');toastFn=fn||null;
  if(action){b.textContent=action;b.classList.remove('hidden');}else b.classList.add('hidden');
  $('#toast').classList.add('on');clearTimeout(toastTimer);toastTimer=setTimeout(()=>$('#toast').classList.remove('on'),action?5000:2400);
}
function lcg(seed){let s=seed%2147483647;if(s<=0)s+=2147483646;return()=> (s=s*16807%2147483647)/2147483647;}
const hasPlan=()=>!!S.plan&&Date.now()<S.planExp;
const hasPro=()=>S.plan==='pro'&&Date.now()<S.planExp;
const dt=ms=>new Date(ms).toLocaleDateString(S.lang==='hi'?'hi-IN':'en-IN',{day:'numeric',month:'short',year:'numeric'});
const idOf=(d,b,l)=>'DV-'+String((d*25+b)*12+l+1).padStart(4,'0');

/* ================= 3,000-COURSE ENGINE ================= */
let CAT=[],IDX=new Map(),CUSTOM=false;
function buildCatalog(){
  const out=[];let n=0;
  for(let d=0;d<10;d++)for(let b=0;b<25;b++)for(let l=0;l<12;l++){
    n++;const r=lcg(n*7919+13);
    out.push({id:idOf(d,b,l),n,d,b,l,tier:l>=8?'pro':l>=4?'smart':'free',
      weeks:2+l+Math.floor(r()*4),hpw:4+Math.floor(r()*6),
      rating:(40+Math.floor(r()*10))/10,learners:800+Math.floor(r()*42000)});
  }
  return out;
}
const ttl=c=>c.t?tl(c.t):tl(BASE[c.d][c.b]);
const fullTitle=c=>ttl(c)+' — '+tl(LVL[c.l])+' (L'+(c.l+1)+')';
const byId=id=>IDX.get(id);
function pickSkills(c){const r=lcg(c.n*31+7),pool=[...DOM[c.d].sk],out=[];for(let i=0;i<4&&pool.length;i++)out.push(pool.splice(Math.floor(r()*pool.length),1)[0]);return out;}
function pickRoles(c){const r=lcg(c.n*17+3),pool=[...DOM[c.d].ro];return[pool.splice(Math.floor(r()*pool.length),1)[0],pool.splice(Math.floor(r()*pool.length),1)[0]];}
function salary(c){const mn=DOM[c.d].sal+c.l*0.35,mx=mn+1.2+c.l*0.25;return '₹'+mn.toFixed(1)+'–'+mx.toFixed(1)+' LPA';}

async function loadCustom(){
  try{
    const r=await fetch('./courses.json',{cache:'no-store'});if(!r.ok)return;
    const j=await r.json();if(!Array.isArray(j)||!j.length)return;
    j.forEach(it=>{
      if(!it||typeof it!=='object')return;
      const ti=typeof it.title==='string'?p(it.title,it.title):(it.title&&typeof it.title==='object'?p(String(it.title.e||it.title.en||it.title.h||''),String(it.title.h||it.title.hi||it.title.e||'')):null);
      const ex=it.id&&IDX.get(String(it.id));
      if(ex){if(ti)ex.t=ti;if(['free','smart','pro'].includes(it.tier))ex.tier=it.tier;if(+it.weeks>0)ex.weeks=+it.weeks;if(+it.rating>0)ex.rating=Math.min(5,+it.rating);}
      else if(ti){const n=CAT.length+1;const c={id:String(it.id||'DV-X'+n),n,d:Math.min(9,Math.max(0,+it.d||0)),b:0,l:Math.min(11,Math.max(0,+it.l||0)),tier:['free','smart','pro'].includes(it.tier)?it.tier:'free',weeks:+it.weeks>0?+it.weeks:6,hpw:6,rating:+it.rating>0?Math.min(5,+it.rating):4.5,learners:+it.learners>0?+it.learners:1000,t:ti};CAT.push(c);IDX.set(c.id,c);}
    });
    CUSTOM=true;renderHome();renderCourses(true);
  }catch(_){}
}

/* ================= FILTERS / LIST ================= */
const F={q:'',d:-1,l:-1,fee:'all',sort:'pop',shown:24};
function filtered(){
  const q=F.q.trim().toLowerCase();
  let a=CAT.filter(c=>{
    if(F.d>=0&&c.d!==F.d)return false;if(F.l>=0&&c.l!==F.l)return false;if(F.fee!=='all'&&c.tier!==F.fee)return false;
    if(q){const hay=(c.id+' '+ttl(c)+' '+(c.t?(c.t.e+' '+c.t.h):(BASE[c.d][c.b].e+' '+BASE[c.d][c.b].h))+' '+DOM[c.d].n.e+' '+DOM[c.d].n.h+' '+LVL[c.l].e+' '+LVL[c.l].h).toLowerCase();if(!hay.includes(q))return false;}
    return true;
  });
  a.sort(F.sort==='pop'?(x,y)=>y.learners-x.learners:F.sort==='rat'?(x,y)=>y.rating-x.rating||y.learners-x.learners:F.sort==='new'?(x,y)=>y.n-x.n:(x,y)=>ttl(x).localeCompare(ttl(y)));
  return a;
}
function tierChip(c){return '<span class="chip tier-'+c.tier+'">'+t(c.tier)+'</span>';}
function cardHtml(c){
  const sv=S.saved.includes(c.id);
  return '<div class="card hov p-3.5 flex flex-col gap-2">'
  +'<div class="flex items-center gap-2"><span class="chip !text-brand2">'+c.id+'</span>'+tierChip(c)
  +'<button data-act="save" data-id="'+c.id+'" class="ml-auto text-lg '+(sv?'star':'text-slate-500')+'" aria-label="save">'+(sv?'★':'☆')+'</button></div>'
  +'<div class="font-semibold text-sm text-white clamp2">'+DOM[c.d].i+' '+esc(ttl(c))+'</div>'
  +'<div class="text-[11px] text-slate-400">'+esc(tl(LVL[c.l]))+' • L'+(c.l+1)+'/12</div>'
  +'<div class="text-[11px] text-slate-400 flex flex-wrap gap-x-3"><span>⏱ '+c.weeks+' '+t('weeks')+'</span><span class="star">★ '+c.rating.toFixed(1)+'</span><span>👥 '+fmt(c.learners)+'</span></div>'
  +'<div class="flex gap-2 mt-1"><button data-act="open" data-id="'+c.id+'" class="btn btn-p flex-1 !py-1.5 !text-xs">'+t('details')+'</button>'
  +'<button data-act="pdf" data-id="'+c.id+'" class="btn btn-o !py-1.5 !text-xs">📄 '+pdfBtnTxt(c.id)+'</button></div></div>';
}
function renderCourses(reset){
  if(reset)F.shown=24;const a=filtered();
  $('#resCount').textContent=fmt(a.length);$('#srcBadge').textContent=CUSTOM?t('srcCustom'):t('srcBuiltin');
  $('#courseGrid').innerHTML=a.length?a.slice(0,F.shown).map(cardHtml).join(''):'<div class="col-span-full text-center text-sm text-slate-400 py-10">'+t('noResults')+'</div>';
  $('#loadMore').style.display=a.length>F.shown?'':'none';
}
function fillFilters(){
  $('#fDomain').innerHTML='<option value="-1">'+t('allDomains')+'</option>'+DOM.map((d,i)=>'<option value="'+i+'"'+(F.d===i?' selected':'')+'>'+d.i+' '+esc(tl(d.n))+'</option>').join('');
  $('#fLevel').innerHTML='<option value="-1">'+t('allLevels')+'</option>'+LVL.map((l,i)=>'<option value="'+i+'"'+(F.l===i?' selected':'')+'>L'+(i+1)+' · '+esc(tl(l))+'</option>').join('');
}

/* ================= HOME ================= */
function renderHome(){
  $('#statCourses').textContent=fmt(CAT.length);
  $('#domainGrid').innerHTML=DOM.map((d,i)=>{const cnt=CAT.filter(c=>c.d===i).length;
    return '<button data-act="domain" data-id="'+i+'" class="card hov p-3 text-left"><div class="text-2xl">'+d.i+'</div><div class="text-xs font-semibold text-white mt-1 leading-snug">'+esc(tl(d.n))+'</div><div class="text-[10px] text-brand2 mt-1">'+fmt(cnt)+' '+t('navCourses')+'</div></button>';}).join('');
  const trend=[...CAT].sort((x,y)=>y.rating-x.rating||y.learners-x.learners).slice(0,6);
  $('#trendRow').innerHTML=trend.map(c=>'<div class="min-w-[240px] max-w-[240px]">'+cardHtml(c)+'</div>').join('');
}

/* ================= COURSE DETAIL ================= */
let CURRENT=null;
function pdfBtnTxt(key){const m=canPdf(key);return m==='pay'?t(key==='QUIZ'?'report14':'pdf14'):m==='credit'?t('pdfCredit'):t('dlPdf');}
function syllabusHtml(c){
  const locked=c.tier!=='free'&&!hasPlan();
  return SYL.map((m,i)=>{const body=tl(m.d).replaceAll('{c}',ttl(c));
    if(locked&&i>=2)return '<div class="card !bg-navy p-3 flex items-center gap-2 opacity-90"><span>🔒</span><div class="flex-1 text-xs text-slate-400">'+esc(tl(m.t))+'</div>'+(i===2?'<button data-act="goplan" class="btn btn-p !py-1 !px-2 !text-[10px]">'+t('unlock29')+'</button>':'')+'</div>';
    return '<details class="card !bg-navy p-3"'+(i===0?' open':'')+'><summary class="flex items-center gap-2 text-xs font-semibold text-white"><span class="arr text-brand2">▶</span><span class="chip !text-brand2">M'+(i+1)+'</span>'+esc(tl(m.t))+'</summary><p class="text-[11px] text-slate-400 mt-2 pl-6">'+esc(body)+'</p></details>';
  }).join('')+(locked?'<p class="text-[10px] text-amber mt-1">🔒 '+t('lockedSyl')+'</p>':'');
}
function openCourse(id){const c=byId(id);if(!c)return;CURRENT=c;renderCourseModal();$('#courseModal').classList.remove('hidden');document.body.style.overflow='hidden';}
function renderCourseModal(){
  const c=CURRENT;if(!c)return;const sv=S.saved.includes(c.id);
  const about=S.lang==='hi'
    ?ttl(c)+' — '+tl(LVL[c.l])+' (लेवल '+(c.l+1)+'/12), '+tl(DOM[c.d].n)+' डोमेन में। '+c.weeks+' सप्ताह, '+c.hpw+' घंटे/सप्ताह का सेल्फ-पेस्ड रोडमैप — प्रोजेक्ट्स, हिंदी+अंग्रेज़ी संसाधन व जॉब/परीक्षा मार्गदर्शन सहित।'
    :ttl(c)+' — '+tl(LVL[c.l])+' (Level '+(c.l+1)+'/12) in '+tl(DOM[c.d].n)+'. A '+c.weeks+'-week, '+c.hpw+' hrs/week self-paced roadmap with projects, Hindi+English resources and job/exam guidance.';
  const info=[[t('duration'),c.weeks+' '+t('weeks')],[t('effort'),c.hpw+' '+t('hpw')],[t('rating'),'★ '+c.rating.toFixed(1)],[t('learners'),fmt(c.learners)],[t('mode'),t('onlineSelf')],[t('salaryEst'),salary(c)]];
  $('#courseBody').innerHTML=
   '<div class="p-4 border-b border-line flex items-start gap-3"><div class="text-3xl">'+DOM[c.d].i+'</div>'
  +'<div class="flex-1 min-w-0"><div class="flex flex-wrap gap-1.5"><span class="chip !text-brand2">'+c.id+'</span><span class="chip">'+t('level')+' '+(c.l+1)+'/12</span>'+tierChip(c)+'</div>'
  +'<h3 class="font-bold text-white mt-1.5 leading-snug">'+esc(ttl(c))+'</h3><div class="text-xs text-slate-400">'+esc(tl(LVL[c.l]))+' • '+esc(tl(DOM[c.d].n))+'</div></div>'
  +'<button data-act="closecourse" class="btn btn-o !p-2 !rounded-full" aria-label="Close">✕</button></div>'
  +'<div class="p-4 space-y-4">'
  +'<div><div class="text-xs font-bold text-brand2 uppercase tracking-wide mb-1">'+t('aboutTitle')+'</div><p class="text-xs text-slate-300 leading-relaxed">'+esc(about)+'</p></div>'
  +'<div class="grid grid-cols-2 md:grid-cols-3 gap-2">'+info.map(x=>'<div class="card !bg-navy p-2.5"><div class="text-[10px] text-slate-500">'+esc(x[0])+'</div><div class="text-xs font-semibold text-white">'+esc(x[1])+'</div></div>').join('')+'</div>'
  +'<div class="card !bg-navy p-2.5"><div class="text-[10px] text-slate-500">'+t('eligibility')+'</div><div class="text-xs font-semibold text-white">'+esc(tl(DOM[c.d].el))+'</div></div>'
  +'<div><div class="text-xs font-bold text-brand2 uppercase tracking-wide mb-1.5">'+t('skillsTitle')+'</div><div class="flex flex-wrap gap-1.5">'+pickSkills(c).map(s=>'<span class="chip !text-slate-200">'+esc(tl(s))+'</span>').join('')+'</div></div>'
  +'<div><div class="text-xs font-bold text-brand2 uppercase tracking-wide mb-1.5">'+t('syllabusTitle')+'</div><div class="space-y-2">'+syllabusHtml(c)+'</div></div>'
  +'<div><div class="text-xs font-bold text-brand2 uppercase tracking-wide mb-1.5">'+t('careersTitle')+'</div><div class="flex flex-wrap gap-1.5">'+pickRoles(c).map(r=>'<span class="chip !text-ok !border-ok/40">💼 '+esc(tl(r))+'</span>').join('')+'</div></div></div>'
  +'<div class="sticky bottom-0 bg-card border-t border-line p-3 flex gap-2"><button data-act="save" data-id="'+c.id+'" class="btn btn-o">'+(sv?'★ '+t('saved'):'☆ '+t('save'))+'</button>'
  +'<button data-act="pdf" data-id="'+c.id+'" class="btn btn-p flex-1">📄 '+pdfBtnTxt(c.id)+'</button></div>';
}
function closeCourse(){$('#courseModal').classList.add('hidden');CURRENT=null;if(!PAY)document.body.style.overflow='';}
function toggleSave(id){
  const i=S.saved.indexOf(id);
  if(i>=0){S.saved.splice(i,1);toast(t('removedToast'),t('undo'),()=>{if(!S.saved.includes(id)){S.saved.push(id);save();renderCourses(false);renderHome();renderLibrary();if(CURRENT)renderCourseModal();toast(t('savedToast'));}});}
  else{S.saved.push(id);toast(t('savedToast'));}
  save();renderCourses(false);renderHome();renderLibrary();if(CURRENT)renderCourseModal();
}

/* ================= ENTITLEMENTS + PDF ================= */
function canPdf(key){if(hasPro())return'pro';if(key==='QUIZ'&&hasPlan())return'plan';if(S.unlocked.includes(key))return'owned';if(S.credits>0)return'credit';return'pay';}
function requestPdf(key){
  const m=canPdf(key);
  if(m==='pay'){openPay({type:'pdfkey',key,amt:CFG.PRICES.PDF,label:p('PDF: '+key,'PDF: '+key),after:()=>requestPdf(key)});return;}
  if(m==='credit'){S.credits--;save();renderPlans();renderLibrary();}
  if(key==='QUIZ')genQuizPdf();else{const c=byId(key);if(c)genCoursePdf(c);}
}
const pdfHead=(title,sub)=>'<div style="padding:26px 30px 14px;border-bottom:4px solid #2563eb"><div style="font-size:22px;font-weight:800;color:#0f172a">DishaVerse <span style="color:#2563eb">Pro</span></div><div style="font-size:11px;color:#64748b">'+esc(t('appTag'))+' • '+esc(t('generated'))+': '+new Date().toLocaleString(S.lang==='hi'?'hi-IN':'en-IN')+'</div><div style="font-size:18px;font-weight:800;margin-top:12px;color:#0f172a">'+esc(title)+'</div><div style="font-size:12px;color:#334155;margin-top:2px">'+esc(sub)+'</div></div>';
const pdfFoot=()=>'<div style="padding:12px 30px;border-top:1px solid #e2e8f0;font-size:9px;color:#64748b">DishaVerse Pro • UPI: '+esc(CFG.UPI_ID)+' • '+esc(CFG.SUPPORT)+' • '+esc(t('payDisclaimer'))+'</div>';
const sec=(h,b)=>'<div style="margin:14px 30px"><div style="font-size:12px;font-weight:800;color:#2563eb;text-transform:uppercase;letter-spacing:.5px;margin-bottom:6px">'+esc(h)+'</div>'+b+'</div>';
const tbl=rows=>'<table style="width:100%;border-collapse:collapse;font-size:11px">'+rows.map(r=>'<tr><td style="border:1px solid #e2e8f0;padding:6px 8px;color:#64748b;width:38%">'+esc(r[0])+'</td><td style="border:1px solid #e2e8f0;padding:6px 8px;font-weight:600;color:#0f172a">'+esc(r[1])+'</td></tr>').join('')+'</table>';
async function makePdf(html,name){
  if(typeof html2pdf==='undefined'){toast(t('pdfLibFail'));return;}
  toast(t('pdfBusy'));const st=$('#pdfStage');st.innerHTML=html;
  try{await html2pdf().set({margin:[8,8,10,8],filename:name,image:{type:'jpeg',quality:.95},html2canvas:{scale:2,useCORS:true,backgroundColor:'#ffffff',windowWidth:780},jsPDF:{unit:'mm',format:'a4',orientation:'portrait'},pagebreak:{mode:['css','legacy']}}).from(st).save();toast(t('pdfDone'));}
  catch(e){toast('PDF error: '+e.message);}
  st.innerHTML='';
}
function genCoursePdf(c){
  const rows=[[t('level'),tl(LVL[c.l])+' (L'+(c.l+1)+'/12)'],[t('navCourses'),tl(DOM[c.d].n)],[t('duration'),c.weeks+' '+t('weeks')],[t('effort'),c.hpw+' '+t('hpw')],[t('rating'),'★ '+c.rating.toFixed(1)+' • '+fmt(c.learners)+' '+t('learners')],[t('eligibility'),tl(DOM[c.d].el)],[t('salaryEst'),salary(c)],['ID',c.id]];
  const syl=SYL.map((m,i)=>'<div style="border:1px solid #e2e8f0;border-radius:8px;padding:8px 10px;margin-bottom:6px"><div style="font-size:12px;font-weight:700;color:#0f172a">M'+(i+1)+' · '+esc(tl(m.t))+'</div><div style="font-size:10px;color:#475569;margin-top:2px">'+esc(tl(m.d).replaceAll('{c}',ttl(c)))+'</div></div>').join('');
  const chips=a=>a.map(s=>'<span style="display:inline-block;border:1px solid #cbd5e1;border-radius:999px;padding:3px 10px;font-size:10px;margin:0 4px 4px 0;color:#0f172a">'+esc(tl(s))+'</span>').join('');
  makePdf(pdfHead(fullTitle(c),t('rptCourse'))+sec(t('aboutTitle'),tbl(rows))+sec(t('skillsTitle'),chips(pickSkills(c)))+sec(t('syllabusTitle'),syl)+sec(t('careersTitle'),chips(pickRoles(c)))+pdfFoot(),'DishaVerse-Pro-'+c.id+'.pdf');
}
function genQuizPdf(){
  const q=S.quiz;if(!q){toast(t('noResults'));return;}
  const dom=q.top.map((d,i)=>'<div style="border:1px solid #e2e8f0;border-left:4px solid #2563eb;border-radius:8px;padding:8px 10px;margin-bottom:6px"><div style="font-size:13px;font-weight:800;color:#0f172a">#'+(i+1)+' '+DOM[d].i+' '+esc(tl(DOM[d].n))+'</div><div style="font-size:10px;color:#2563eb;font-weight:700">'+q.pct[i]+'% '+esc(t('match'))+'</div></div>').join('');
  const picks=q.picks.map(id=>{const c=byId(id);return c?'<tr><td style="border:1px solid #e2e8f0;padding:6px 8px;font-size:10px;color:#2563eb;font-weight:700">'+c.id+'</td><td style="border:1px solid #e2e8f0;padding:6px 8px;font-size:10px;font-weight:600">'+esc(ttl(c))+'</td><td style="border:1px solid #e2e8f0;padding:6px 8px;font-size:10px">'+esc(tl(LVL[c.l]))+'</td><td style="border:1px solid #e2e8f0;padding:6px 8px;font-size:10px">'+c.weeks+' '+esc(t('weeks'))+'</td></tr>':'';}).join('');
  const ns='<ul style="font-size:11px;color:#334155;padding-left:16px"><li>'+esc(t('ns1'))+'</li><li>'+esc(t('ns2'))+'</li><li>'+esc(t('ns3'))+'</li></ul>';
  makePdf(pdfHead(t('rptQuiz'),t('quizNote'))+sec(t('matchTitle'),dom)+sec(t('recommended'),'<table style="width:100%;border-collapse:collapse">'+picks+'</table>')+sec(t('careersTitle'),ns)+pdfFoot(),'DishaVerse-Pro-Career-Report.pdf');
}

/* ================= DIRECT UPI PAYMENTS ================= */
let PAY=null;
function upiParams(amt,note,ref){return 'pa='+encodeURIComponent(CFG.UPI_ID)+'&pn='+encodeURIComponent(CFG.PAYEE)+'&am='+amt+'&cu=INR&tn='+encodeURIComponent(note)+'&tr='+ref;}
function payHref(app,amt,note,ref){
  const q=upiParams(amt,note,ref),upi='upi://pay?'+q;
  const pk={gpay:'com.google.android.apps.nbu.paisa.user',phonepe:'com.phonepe.app',paytm:'net.one97.paytm'}[app];
  if(!AND||!pk)return upi;
  return 'intent://pay?'+q+'#Intent;scheme=upi;package='+pk+';S.browser_fallback_url='+encodeURIComponent('https://play.google.com/store/apps/details?id='+pk)+';end';
}
function openPay(order){PAY=Object.assign({step:1,ref:'DVP'+Date.now().toString(36).toUpperCase()},order);renderPay();$('#payModal').classList.remove('hidden');document.body.style.overflow='hidden';}
function renderPay(){
  if(!PAY)return;const B=$('#payBody');
  const head='<div class="flex items-center gap-2 mb-3"><div class="font-bold text-white">💳 '+t('payTitle')+'</div><button data-act="paycancel" class="ml-auto btn btn-o !p-2 !rounded-full" aria-label="Close">✕</button></div>';
  if(PAY.step===1){
    const link=CFG.PAY_LINKS[PAY.amt];
    B.innerHTML=head
    +'<div class="card !bg-navy p-3 flex items-center gap-3"><div class="flex-1"><div class="text-[10px] text-slate-500">'+t('item')+'</div><div class="text-xs font-semibold text-white">'+esc(tl(PAY.label))+'</div></div><div class="text-right"><div class="text-[10px] text-slate-500">'+t('amount')+'</div><div class="text-2xl font-extrabold text-brand2">₹'+PAY.amt+'</div></div></div>'
    +'<div class="grid grid-cols-2 gap-2 mt-3">'
    +'<button data-act="payapp" data-app="gpay" class="btn btn-o !justify-start"><span class="w-6 h-6 rounded-full bg-white text-navy font-extrabold text-xs flex items-center justify-center">G</span>'+t('gpay')+'</button>'
    +'<button data-act="payapp" data-app="phonepe" class="btn btn-o !justify-start"><span class="w-6 h-6 rounded-full bg-violet-600 text-white font-extrabold text-xs flex items-center justify-center">P</span>'+t('phonepe')+'</button>'
    +'<button data-act="payapp" data-app="paytm" class="btn btn-o !justify-start"><span class="w-6 h-6 rounded-full bg-sky-500 text-white font-extrabold text-xs flex items-center justify-center">₹</span>'+t('paytm')+'</button>'
    +'<button data-act="payapp" data-app="upi" class="btn btn-o !justify-start"><span class="w-6 h-6 rounded-full bg-emerald-600 text-white font-extrabold text-xs flex items-center justify-center">U</span>'+t('anyUpi')+'</button></div>'
    +(link?'<button data-act="cardlink" class="btn btn-o w-full mt-2">💳 '+t('cardPay')+'</button>':'')
    +'<div class="card !bg-navy p-3 mt-3"><div class="text-[10px] text-slate-500 mb-1">'+t('manualPay')+'</div><div class="flex items-center gap-2"><code class="text-xs text-brand2 font-bold flex-1 truncate">'+esc(CFG.UPI_ID)+'</code><button data-act="copyupi" class="btn btn-o !py-1 !px-2 !text-[10px]">'+t('copy')+'</button></div>'
    +(!AND?'<p class="text-[10px] text-amber mt-2">'+t('desktopNote')+'</p>':'')+'</div>'
    +'<button data-act="paid" class="btn btn-p w-full mt-3">✅ '+t('paidBtn')+'</button>'
    +'<p class="text-[9px] text-slate-500 mt-2">'+t('payDisclaimer')+'</p>';
  }else if(PAY.step===2){
    B.innerHTML=head+'<div class="font-semibold text-white text-sm">'+t('utrTitle')+' • ₹'+PAY.amt+'</div>'
    +'<label class="block text-[11px] text-slate-400 mt-3 mb-1" for="utrIn">'+t('utrLabel')+'</label>'
    +'<input id="utrIn" class="inp" inputmode="numeric" maxlength="12" placeholder="'+t('utrPh')+'">'
    +'<button data-act="verify" class="btn btn-p w-full mt-3">🔓 '+t('verifyBtn')+'</button>'
    +'<p class="text-[9px] text-slate-500 mt-2">'+t('payDisclaimer')+'</p>';
    setTimeout(()=>{const i=$('#utrIn');i&&i.focus();},60);
  }else{
    B.innerHTML=head+'<div class="text-center py-6"><div class="text-5xl">✅</div><div class="font-bold text-white mt-3">'+t('paySuccess')+'</div><div class="text-xs text-slate-400 mt-1">'+esc(tl(PAY.label))+' • ₹'+PAY.amt+'</div><div class="text-[10px] text-slate-500 mt-1">UTR: '+esc(PAY.utr||'')+'</div>'
    +'<button data-act="paycont" class="btn btn-p w-full mt-5">'+t('continueBtn')+'</button></div>';
  }
}
function grant(){
  const now=Date.now();
  if(PAY.type==='pdfkey'){if(!S.unlocked.includes(PAY.key))S.unlocked.push(PAY.key);}
  else if(PAY.type==='credit'){S.credits+=1;}
  else if(PAY.type==='plan'){const add=CFG.PLAN_DAYS*864e5;if(S.plan===PAY.plan&&S.planExp>now)S.planExp+=add;else{S.plan=PAY.plan;S.planExp=now+add;}if(PAY.plan==='smart')S.credits+=CFG.SMART_CREDITS;}
  S.txns.unshift({ref:PAY.ref,amt:PAY.amt,utr:PAY.utr,item:PAY.label.e,ts:now});save();renderPlans();renderLibrary();renderCourses(false);if(CURRENT)renderCourseModal();
}
function closePay(){$('#payModal').classList.add('hidden');PAY=null;if(!CURRENT)document.body.style.overflow='';}
async function copyTxt(s){try{await navigator.clipboard.writeText(s);}catch(_){const ta=document.createElement('textarea');ta.value=s;document.body.appendChild(ta);ta.select();document.execCommand('copy');ta.remove();}toast(t('copied'));}
function buyPlan(pl){
  if(pl==='pdf')openPay({type:'credit',amt:CFG.PRICES.PDF,label:p('1 PDF credit','1 PDF क्रेडिट')});
  else if(pl==='smart')openPay({type:'plan',plan:'smart',amt:CFG.PRICES.SMART,label:p('Smart Plan (30 days)','स्मार्ट प्लान (30 दिन)')});
  else openPay({type:'plan',plan:'pro',amt:CFG.PRICES.PRO,label:p('Pro Plan (30 days)','प्रो प्लान (30 दिन)')});
}

/* ================= PLANS / LIBRARY ================= */
function planStatusHtml(){
  const act=hasPlan();
  return '<div class="card p-3 flex flex-wrap items-center gap-3 text-xs"><div class="text-2xl">'+(act?(S.plan==='pro'?'👑':''):'🔓')+'</div>'
  +'<div class="flex-1"><div class="text-[10px] text-slate-500">'+t('curPlan')+'</div><div class="font-bold text-white">'+(act?t(S.plan==='pro'?'planProName':'planSmartName'):t('noPlan'))+'</div>'
  +(act?'<div class="text-[10px] text-slate-400">'+t('validTill')+': '+dt(S.planExp)+'</div>':'')+'</div>'
  +'<div class="text-right"><div class="text-[10px] text-slate-500">'+t('creditsLeft')+'</div><div class="font-extrabold text-brand2 text-lg">'+(hasPro()?'∞':S.credits)+'</div></div></div>';
}
function renderPlans(){
  $('#planStatus').innerHTML=planStatusHtml();
  $('#txnList').innerHTML=S.txns.length?S.txns.map(x=>'<div class="flex items-center gap-2 py-1.5 border-b border-line/50 last:border-0"><span class="chip !text-ok !border-ok/40">₹'+x.amt+'</span><span class="flex-1 truncate">'+esc(x.item)+'</span><span class="text-[10px] text-slate-500">UTR '+esc(String(x.utr).slice(0,4))+'••••'+esc(String(x.utr).slice(-4))+' • '+dt(x.ts)+'</span></div>').join(''):t('noTxns');
}
function renderLibrary(){
  $('#planStatus2').innerHTML=planStatusHtml();
  $('#savedList').innerHTML=S.saved.length?S.saved.map(id=>{const c=byId(id);if(!c)return'';return '<div class="card p-3 flex items-center gap-2"><span class="text-xl">'+DOM[c.d].i+'</span><div class="flex-1 min-w-0"><div class="text-xs font-semibold text-white truncate">'+esc(ttl(c))+'</div><div class="text-[10px] text-slate-500">'+c.id+' • '+esc(tl(LVL[c.l]))+'</div></div><button data-act="open" data-id="'+c.id+'" class="btn btn-o !py-1 !px-2 !text-[10px]">'+t('details')+'</button><button data-act="save" data-id="'+c.id+'" class="star text-lg" aria-label="remove">★</button></div>';}).join(''):'<p class="text-xs text-slate-500">'+t('noSaved')+'</p>';
  const keys=[...S.unlocked];
  $('#unlockedList').innerHTML=keys.length?keys.map(k=>{const c=k==='QUIZ'?null:byId(k);const name=k==='QUIZ'?t('rptQuiz'):(c?ttl(c):k);
    return '<div class="card p-3 flex items-center gap-2"><span class="text-xl">📄</span><div class="flex-1 min-w-0"><div class="text-xs font-semibold text-white truncate">'+esc(name)+'</div><div class="text-[10px] text-slate-500">'+esc(k)+'</div></div><button data-act="redl" data-id="'+esc(k)+'" class="btn btn-p !py-1 !px-2 !text-[10px]">⬇️ '+t('redl')+'</button></div>';}).join(''):'<p class="text-xs text-slate-500">'+t('noPdfs')+'</p>';
}

/* ================= QUIZ ================= */
let QST={started:false,i:0,ans:[],scores:null};
function renderQuiz(){
  const B=$('#quizBox');
  if(S.quiz&&QST.scores){renderQuizResult();return;}
  if(!QST.started){B.innerHTML='<div class="card p-6 text-center reveal"><div class="text-5xl">🧭</div><p class="text-sm text-slate-300 mt-3">'+t('quizSub')+'</p><button data-act="quizstart" class="btn btn-p mt-4">▶️ '+t('quizStart')+'</button><p class="text-[10px] text-slate-500 mt-3">'+t('quizNote')+'</p></div>';return;}
  const q=QUIZ[QST.i],pc=Math.round(QST.i/QUIZ.length*100);
  B.innerHTML='<div class="card p-4 reveal"><div class="flex items-center justify-between text-[11px] text-slate-400"><span>'+t('question')+' '+(QST.i+1)+' '+t('of')+' '+QUIZ.length+'</span><span>'+pc+'%</span></div>'
  +'<div class="h-1.5 bg-navy rounded-full mt-2 overflow-hidden"><div class="h-1.5 rounded-full" style="width:'+pc+'%;background:linear-gradient(90deg,#2563eb,#38bdf8)"></div></div>'
  +'<div class="font-bold text-white mt-4">'+esc(tl(q.q))+'</div>'
  +'<div class="space-y-2 mt-3">'+q.o.map((o,i)=>'<button data-act="quizopt" data-id="'+i+'" class="btn btn-o w-full !justify-start text-left">'+String.fromCharCode(65+i)+'. '+esc(tl(o.t))+'</button>').join('')+'</div>'
  +(QST.i>0?'<button data-act="quizback" class="btn btn-o mt-3 !py-1.5 !text-xs">← '+t('back')+'</button>':'')+'</div>';
}
function quizAnswer(i){
  QST.ans[QST.i]=i;
  if(QST.i<QUIZ.length-1){QST.i++;renderQuiz();return;}
  const sc=Array(10).fill(0);QST.ans.forEach((a,qi)=>{const w=QUIZ[qi].o[a].w;for(const k in w)sc[+k]+=w[k];});
  const top=[...sc.keys()].sort((a,b)=>sc[b]-sc[a]).slice(0,3);const mx=Math.max(1,sc[top[0]]);const pct=top.map(d=>Math.round(sc[d]/mx*100));
  const picks=[];top.forEach((d,r)=>{const s=sc[d];[(s*7+r*5)%25,(s*11+r*3+7)%25].forEach(b=>picks.push(idOf(d,b,1)));});
  QST.scores=sc;S.quiz={scores:sc,top,pct,picks,ts:Date.now()};save();renderQuizResult();
}
function renderQuizResult(){
  const q=S.quiz;if(!q)return;
  const dom=q.top.map((d,i)=>'<div class="card hov p-3 border-l-4 !border-l-brand"><div class="flex items-center gap-2"><span class="text-2xl">'+DOM[d].i+'</span><div class="flex-1"><div class="text-sm font-bold text-white">#'+(i+1)+' '+esc(tl(DOM[d].n))+'</div><div class="text-[11px] text-brand2 font-bold">'+q.pct[i]+'% '+t('match')+'</div></div><button data-act="domain" data-id="'+d+'" class="btn btn-o !py-1 !px-2 !text-[10px]">'+t('ctaExplore')+'</button></div></div>').join('');
  const list=q.picks.map(id=>{const c=byId(id);return c?'<div class="card p-2.5 flex items-center gap-2"><span class="chip !text-brand2">'+c.id+'</span><div class="flex-1 min-w-0 text-xs font-semibold text-white truncate">'+esc(ttl(c))+'</div><button data-act="open" data-id="'+c.id+'" class="btn btn-p !py-1 !px-2 !text-[10px]">'+t('details')+'</button></div>':'';}).join('');
  $('#quizBox').innerHTML='<div class="font-bold text-white mb-2">🏆 '+t('matchTitle')+'</div><div class="space-y-2 reveal">'+dom+'</div>'
  +'<div class="font-bold text-white mt-4 mb-2">📚 '+t('recommended')+'</div><div class="space-y-2">'+list+'</div>'
  +'<div class="flex gap-2 mt-4"><button data-act="quizpdf" class="btn btn-p flex-1">📄 '+(canPdf('QUIZ')==='pay'?t('report14'):t('dlReport'))+'</button><button data-act="quizrestart" class="btn btn-o">🔄 '+t('restart')+'</button></div>'
  +'<p class="text-[10px] text-slate-500 mt-3">'+t('quizNote')+'</p>';
}

/* ================= TABS / I18N ================= */
const TABS=['home','courses','quiz','plans','library'];
function goTab(name,first){
  if(!TABS.includes(name))name='home';
  TABS.forEach(x=>$('#tab-'+x).classList.toggle('hidden',x!==name));
  $$('.navbtn').forEach(b=>b.classList.toggle('on',b.dataset.tab===name));
  if(!first){try{history.replaceState(null,'','#'+name);}catch(_){}}
  window.scrollTo({top:0});
  if(name==='courses')renderCourses(false);if(name==='quiz')renderQuiz();if(name==='plans')renderPlans();if(name==='library')renderLibrary();
}
function applyI18n(){
  document.documentElement.lang=S.lang;
  document.title=S.lang==='hi'?'DishaVerse Pro — करियर खोज व स्किल्स':'DishaVerse Pro — Career Discovery & Skills';
  $$('[data-i18n]').forEach(el=>el.textContent=t(el.dataset.i18n));
  $$('[data-i18n-ph]').forEach(el=>el.placeholder=t(el.dataset.i18nPh));
  fillFilters();renderHome();renderCourses(false);renderQuiz();renderPlans();renderLibrary();
  if(CURRENT)renderCourseModal();if(PAY)renderPay();
  $('#verTxt').textContent=CFG.VER;$('#upiTxt').textContent=CFG.UPI_ID;$('#supTxt').textContent=CFG.SUPPORT;
}

/* ================= PWA ================= */
function initIcons(){$('#fav').href='data:image/png;base64,'+ICON192;$('#ati').href='data:image/png;base64,'+ICON192;}
let DIP=null,UPDW=null;
function initInstall(){window.addEventListener('beforeinstallprompt',e=>{e.preventDefault();DIP=e;});window.addEventListener('appinstalled',()=>toast(t('installed')));}
function doInstall(){if(DIP){DIP.prompt();DIP.userChoice.then(()=>DIP=null);}else if(/iPhone|iPad|iPod/i.test(navigator.userAgent))toast(t('iosHint'));else toast(t('installHint'));}
function initNet(){const dot=$('#netDot');const upd=()=>{dot.className='w-2.5 h-2.5 rounded-full '+(navigator.onLine?'bg-ok':'bg-amber');};window.addEventListener('online',()=>{upd();toast(t('onlineMsg'));});window.addEventListener('offline',()=>{upd();toast(t('offlineMsg'));});upd();}
function initSW(){
  if(!('serviceWorker'in navigator)||location.protocol==='file:')return;
  window.addEventListener('load',()=>{navigator.serviceWorker.register('./sw.js').then(reg=>{reg.addEventListener('updatefound',()=>{const nw=reg.installing;nw&&nw.addEventListener('statechange',()=>{if(nw.state==='installed'&&navigator.serviceWorker.controller){UPDW=nw;$('#updBar').classList.remove('hidden');}});});}).catch(()=>{});navigator.serviceWorker.addEventListener('controllerchange',()=>location.reload());});
}
function exportIcons(){[['icon-192.png',ICON192],['icon-512.png',ICON512]].forEach(([n,b])=>{const a=document.createElement('a');a.href='data:image/png;base64,'+b;a.download=n;document.body.appendChild(a);a.click();a.remove();});toast(t('exIconsDone'));}
function exportData(){const b=new Blob([JSON.stringify(S,null,2)],{type:'application/json'});const a=document.createElement('a');a.href=URL.createObjectURL(b);a.download='dishaverse-data.json';document.body.appendChild(a);a.click();a.remove();setTimeout(()=>URL.revokeObjectURL(a.href),3000);}

/* ================= EVENTS ================= */
function bindEvents(){
  document.body.addEventListener('click',e=>{
    const el=e.target.closest('[data-act]');if(!el)return;const act=el.dataset.act,id=el.dataset.id;
    switch(act){
      case 'tab':goTab(el.dataset.tab);break;
      case 'lang':S.lang=S.lang==='hi'?'en':'hi';save();applyI18n();break;
      case 'domain':F.d=+id;F.q='';$('#q').value='';fillFilters();goTab('courses');renderCourses(true);break;
      case 'open':openCourse(id);break;
      case 'save':toggleSave(id);break;
      case 'pdf':requestPdf(id);break;
      case 'closecourse':closeCourse();break;
      case 'goplan':closeCourse();goTab('plans');break;
      case 'loadmore':F.shown+=24;renderCourses(false);break;
      case 'buy':buyPlan(el.dataset.plan);break;
      case 'payapp':window.location.href=payHref(el.dataset.app,PAY.amt,PAY.label.e.slice(0,40),PAY.ref);toast(t('opening'));break;
      case 'cardlink':{const l=CFG.PAY_LINKS[PAY.amt];if(l)window.open(l,'_blank');break;}
      case 'copyupi':copyTxt(CFG.UPI_ID);break;
      case 'paid':PAY.step=2;renderPay();break;
      case 'verify':{const v=($('#utrIn').value||'').trim();if(!/^\d{12}$/.test(v)){toast(t('utrErr'));break;}PAY.utr=v;grant();PAY.step=3;renderPay();break;}
      case 'paycancel':closePay();break;
      case 'paycont':{const f=PAY&&PAY.after;closePay();if(f)f();break;}
      case 'quizstart':QST={started:true,i:0,ans:[],scores:null};renderQuiz();break;
      case 'quizopt':quizAnswer(+id);break;
      case 'quizback':if(QST.i>0){QST.i--;renderQuiz();}break;
      case 'quizrestart':QST={started:false,i:0,ans:[],scores:null};S.quiz=null;save();renderQuiz();break;
      case 'quizpdf':requestPdf('QUIZ');break;
      case 'redl':requestPdf(id);break;
      case 'install':doInstall();break;
      case 'exicons':exportIcons();break;
      case 'exdata':exportData();break;
      case 'reset':if(confirm(t('resetConfirm'))){localStorage.removeItem(KEY);location.reload();}break;
      case 'refresh':if(UPDW)UPDW.postMessage({type:'SKIP_WAITING'});break;
    }
  });
  $('#toastAct').addEventListener('click',()=>{const f=toastFn;$('#toast').classList.remove('on');if(f)f();});
  let deb=null;$('#q').addEventListener('input',e=>{clearTimeout(deb);deb=setTimeout(()=>{F.q=e.target.value;renderCourses(true);},200);});
  $('#fDomain').addEventListener('change',e=>{F.d=+e.target.value;renderCourses(true);});
  $('#fLevel').addEventListener('change',e=>{F.l=+e.target.value;renderCourses(true);});
  $('#fFee').addEventListener('change',e=>{F.fee=e.target.value;renderCourses(true);});
  $('#fSort').addEventListener('change',e=>{F.sort=e.target.value;renderCourses(true);});
  window.addEventListener('hashchange',()=>goTab(location.hash.slice(1)));
  document.addEventListener('keydown',e=>{if(e.key==='Escape'){if(PAY)closePay();else if(CURRENT)closeCourse();}});
}

/* ================= BOOT ================= */
loadState();
if(S.quiz){QST.started=true;QST.scores=S.quiz.scores;}
initIcons();
CAT=buildCatalog();IDX=new Map(CAT.map(c=>[c.id,c]));
bindEvents();applyI18n();
goTab(location.hash?location.hash.slice(1):'home',true);
loadCustom();initInstall();initNet();initSW();
</script>
</body>
</html>
```

# `manifest.json`

```json
{
  "id": "./",
  "name": "DishaVerse Pro — Career Discovery & Skills",
  "short_name": "DishaVerse Pro",
  "description": "3,000 courses & skills across 10 Indian career domains. Bilingual Hindi/English career discovery, PDF roadmaps, offline-first PWA with direct UPI micro-payments.",
  "lang": "hi",
  "dir": "ltr",
  "start_url": "./index.html",
  "scope": "./",
  "display": "standalone",
  "orientation": "portrait",
  "background_color": "#0f172a",
  "theme_color": "#0f172a",
  "categories": ["education", "productivity"],
  "prefer_related_applications": false,
  "icons": [
    {
      "src": "data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAMAAAADACAIAAADdvvtQAAAErklEQVR42u3dMY4TQRAF0LoBCRISCREJd+AOxBByG0JuQsqVSEiIwZKTxbsga6enu6vqoR8ig9ZPVb89O5548eqdyLMTfgQCkAAkAAlAIgAJQAKQACQCkAAkAAlAIgAJQAKQACQCkAA0JK/ff7nJ288/bvL47/i5dQT08t3H69v/5sP3x0qel8tLXV/z8uIAlUUzUMw9nppgitqLaRqa/2MCiBuSqgO6rIwN3TwpqdJ2ixojZ383Tx7rAEKnO6NAB6NegIrRyc4o0MGoPqAsJ6yGJ7UEgFrRuWEE0NHB05POw2w+isLgMYqqAerWeFK3orC2rLM6gAyedOss6GGoAiB6khoKlVmtTgxIZc5eq4MehlICoqeGoaCHoXyAtOYy57Kgh6FMgOgpZijoYSgHIMW5ZKEOehhKAMjyqrrIgh6GtgZkedVeZKcD8i6uTW5Allf5RRaWl0W2KSDjp8MQOgtQk/vY3W8furM2vR0g46fPEArjxxDaC5Dx02oIhfFjCG0EyPjpNoTC+DGEdgFk/DQcQmH8GEJbAHLl6yZfv/36ffefvFfHwpWvhoAGXh0L+6shoIFbLNTnnoBGVemwv3oCGrXFwv7qy2gIVss7K+2gIassXC54edAR3/RDEUoM6AjtegUIA6Azpeg0IB6gzoeA0KBag5oIM1KBSg5oAO1qCA/nrL7wxAYwAVa9Bj3+8sgA726NCgmwM62KMBAggggDICqncEawvoSI8GCCCAAAIIIIAAAggggKYBqnf1qi2gIyd5gAACCCCAAAIIIIBSAbr/7bnzN3gA6nWMB8jnQAABBBBAAAEEEEAAAdQK0PKTPEB+JxoggAACKOmNhQClv7FwbY8GyL3xAPUGtPbrXQBK//Uua3s0QOm/YGptjwaowlfcLaxBAC0vQLm/5heg5QUo9xeNA7S8AOV+1AFAywtQ7oetALS8AOV+3BNAy/dX7gfOAbR8f+V+5CVAy/dX7ofuArR8f+V+7DdAy/fX7ofuArR8f+V+7DdAy/fX7ofuArR8f+V+7DdAy/fXSEDzP1EEaOHnh+MBzd9iAC3fX4MBTa7SAK2tz+MBTR5CAC0fP+MBzRxC9z9c59OXn2Nf8J5Xu/yjY19ww/EzHpBnGG6e4W/3eECeQrdtho+fUwAZQn3Gz1mADKEm4+csQIZQk/FzIiBDqMP4ORFQvSeq5s3AK19TAXmq/CYZeOVrKiBDqPz4OR2QNl21O88DZJFVXV6TAFlkVZfXPEAMVdUzD5BFVm95TQXEUEk9UwFZZMWW1wJADBXTswAQQ5X0rAHEUBk9ywAp1KmL83pADNXQsxIQQwX0LAbEUHY96wFdDenUz2vNy/VsAci5LNGZa19ADGXUsxcghtLp2Q6QWr15ZU4ASK3euTLnAGSdbb62cgCyzrZdW2kANR9FOw+eTIAatqJtG09WQK3utz/vPvbugMozykUnK6CSjDLSyQ2oDKO8dCoASs0oO506gHKd1BKdsHoBejiQNpR0+S/VGDn1AW0lqaqbFoAebreZmK5oKu2p7oAeYxrr6SqmD5rWgP617G7y5KHpJn5uAAlAApAAJACJACQACUACkAhAApAAJACJACQACUACkAhAApCszx+g1jGxUReIoAAAAABJRU5ErkJggg==",
      "sizes": "192x192",
      "type": "image/png",
      "purpose": "any"
    },
    {
      "src": "data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAgAAAAIACAIAAAB7GkOtAAAOKUlEQVR42u3dPW4U2xaA0TMDEktITohIeg6eA7FTZuOQmZAyJWJiaAnJwj9qyW2669T51tXKnm7wfNvnq9q7qj0+fDwAEDT8CAAEAAABAEAAABAAAAQAAAEAQAAAEAAABAAAAQBAAAAQAAAEAAABAEAAABAAAAQAAAEAQAAAEAAABAAAAQBAAAAEAAABAEAAABAAAAQAAAEAQAAAEAAABAAAAQBAAAAQAAAEAAABAEAAABAAAAQAAAEAQAAAEAAABAAAAQBAAAAEwE8BQAAAEAAABAB25fbu4YRPX358/vrzVcf/6fS/62eLAMBER/yJA/3SngXDfxcEAC5y1m91yp9HFRAASBz3koAAwJkn/oZjnM3HRz4DCAAVN4f7Va/x339/cPzh+IQgACx46Acv899zcyAGCAD7Hu849P9LDHyWEAB2c7Hv4L7QmMhtAQLApLtcZ/Q1FwY+dQgAhjwGRD6KCADOfSUAAcB8354ABADnvhKAAGDUYzQEAoBLfjcEIAA8Ofpd8q99QyADCACvTHucj6kbAp95BABHvwwgAJj2YC6EAODoRwYQABz9yAACgKMfGUAAcPQjAwgAU3P08/4M+D0SADzciQdGEQAc/cgAAoBxPxYDCACOfmQAAcDMBxMhBIBLX/g7htiWWwEBwCOeeFQUAcDMBxMhBADLXiyHEQBc+ONWAAHAhT9uBRAAXPjjVgABwKM+eEAIAcAz/nhXAAFw4Q9uBRAA+16wGUYAjH3AOAgBMPYB4yAEwNgHjIMQAGMfMA5CALzkBV4WQwAM/cFKAAFw+oMGIACG/mAlIAA4/UEDBACnP2iAAGDoD1YCAoDTHzRAAHD6gwYIAE5/0AABwOkPGiAAHvjxwA94NEgAnP6ABgiA0x/QAAFw+gMaIABOf0ADBMDpD2iAADj9AQ0QAKc/oAECMCO/h7AV548AeNcXvCeMADj9QQMQAKc/aAAC4PQHDUAAnP6gAQiAhz7Bg6EC4Kfg9AcNEACc/qABAoAXvsALYgKAxS9YCAuA0x/QAAGIuL178LsEe3T85XWCCYDFL1gIIwBOf9AABMDoHywDBMBPwekPGiAAGP6AQZAAOP0BDRAAwx/AIEgAnP6ABgiA4Q9gECQAvu4N2A1nnQAY/oBBkAD4KfjCH/A1QQJg9A9YBgiA4Q9gECQAhj+AQZAAGP4ABkECYPgDGAQJgOEPYBAkAF77ArwaJgCGP4BBkADY/QK2wQJg+AMYBAmA3S9gGywAhj+AQZAA2P0CtsEC4PIfcBMgAC7/ATcBAmD3C9gGC4BHPwGPhAqAy3/ATYAAuPwH3AQIgN0vYBtcDYBHPwGPhEYD4PIfcBNQDIDLf8BNQDQALv8BNwHFALj8B9wERAPg8h9wE1AMgMt/wE1ANAAu/wE3AcUAuPwH3AREA+DyH3ATEA2ATypwCQLgiz+BqPW+InS4/Ado3gQMl/8AzZuA4fIfoHkTMDz9CdB8HnR4+hOg+TzocPkP0LwJGNa/AM1V8LD+hTl9+/7r99X/8WNPrYKHy38QAAFo3gQM618QAAForoKH9S8IgAA0V8HD/AcEQACaU6Bh/QsCIADNVfAw/wEBEIDmFGiY/4AACEBzCjTMf0AABKA5BRou/0EABKB5EzA8/g8CIADNFwKG+Q8IgAA0p0DD/AcEQACaU6Bh/gMCIADNKdAw/wEBEIDmFGiY/4AACEBzCiQAIAACIADmPyAAfvKlKdD+AuD7fxAAAZjQHr8XaJj/gAAIQHMKNMx/QAAEoDkFEgAQAAEQAPMfEAA/+dIUaGcB8AIwAiAAXgmOBsAnDAEQAFOgYgA8AIoACICHQaMBsABAAATAGiAaAAsABEAArAGiAfDZQgAEwBqgGAALAARAAKwBogGwAEAABMAaQABAAARAAEoB8KlCAATAGkAAQAAEQAAyATD/QQAEwBRIAEAABEAASgHwChgCIABeB4sGwOcJARAAawABAAEQAAHIBMACAAEQAGsAAQABEAABEAD4x5IHpQAIgABYACAAAmANIAAgAAIgAAIAAiAAArB4ACwAEAABsAYQABAAARAAAQABEAABWD4APkMIgABYAwgACIAACIAAgAAIgAAIAAiAAAjAggGwAUYABMAeWABAAARAAAQABEAABEAAQAAEQADWDIA/BYwACMCuTf7HgYdHgBAAARCA5oNAAoAACIAACIAAIAAC4OMkAAKAAAgAAiAACIAAIACeAUUABICFngQVAARAAARAAAQAARAAHycBEAAEQAAQAAFAAAQAARAABEAAEAABQAAEAAEQAARAABAAAUAABAABEAAEQAAQAH8MAAEQgK6Z/yTAvAHwuUEABMDXAQkACIAACIAAgAAIgAAIAAiAAAiAACAAAiAAAiAACIAACIAACAACIAACIAACgAAIgAAIgBfBEAABEAAvgvkqCAflFf45nmICIAC+CkIABEAABEAABEAABEAABEAABEAABEAABEAABEAABEAABEAABEAABEAABEAABEAAEAABEAABEAAEQAAEQAAEAAEQAAEQAAFAAARAAARgqQD4OiABEAAB8EVAAoAACIAACIAAIAACIAACIAAIgAAIgAAIAAIgAAIgAGsFwJ8EEAABEIBdm/mPAcweAE+CCoAACIBnQAUAARAAARAAAUAABEAABEAAEAABEAABWDMAHgQSAAEQAI8ACQACIAACIAACgAAIgAAIgAAgAAIgAAKwbADsgQVAAATABlgAEAABEAABEAAEQAAEQACWD4A1gAAIgABYAAgAAiAAAiAAAoAACIAACEAhANYAAiAAAmABIAAIgAAIgAAIAAIgAAIgAMsHwBpAAARAACwABAABEAABEIBYAPxxYAEQAAHYkcn/FPDOAmANIAACIAAWAAKAAAiAAAhAKQDWAAIgAAJgASAACIAACIAAxAJgCiQAAiAA5j8CgAAIgAAIQCkAN4d7HywBEAABmN/xsBIAawABEAABsAAQAK+DCYAACIBXwATAGkAABEAALAAEwBpAAARAACwABMAaQAAEQAAsAATAGkAABEAALAAEwBpAAARAACwABMAUSAAEQADMfwTAh0wABEAABCAaAFMgARAAATD/iQbAw6ACIAAC4AHQaABMgQRAAATD/EQAEQAAEQABKATAFEgABEADzn24AvBIsAAIgAF4AjgbAFEgABEAAzH+iATAFEgABEADzn24ATIEEQAAEwPwnGgBTIAEQAAEw/4kGwBRIAARAAMx/ugFwEyAAAiAALv+jAfC9QAIgAALg+3+iATAFEgABEADzn24ATIEEQAAEwPwnGgBTIAEQAAEw/4kGwAsBAiAAAuDx/24ATIEEQAAEwPwnGgCrYAEQAAGw/u0GwE2AAAiAALj8jwbAKlgABEAArH+jAbAKFgABEADr324A3AQIgAAIgMv/aACsggVAAATA+rcbAKtgARAAAbD+jQbATYAACIAAuPzvBsBNgAAIgAC4/I8GwE2AAAiAALj87wbA86ACIAAC4OnPaAA8Dwp4+jMaADcBgMv/bgDcBAAu/6MBcBMAuPzvBsBNAODyPxoANwGAy/9uANwEAC7/owFwEwC4/O8GwE0A4PI/GgA3AYDL/24AfDsQcIbC2ZgIgK8IBd5kvS/+7AbATQDg8r8bADcBgMv/aABsgwG7324APBIKePQzGgA3AYDL/24A3AQALv+jAbANBux+uwHwSChQfvSzHgCDICA+/OkGwDYYKO9+6wEwCALKw596AGyDgebuVwAMgoDu8EcAbIPB7vdeAA4GQYDhjwAYBAGGPwJgEAQY/giAQRBg+CMABkGA4Y8AeDUM8NqXAFgGAEb/AmAQBBj+CIAGAE5/ATAIAgx/BEADAKe/ABgEAYY/AqABgNNfAAyCAMMfAdAAwOkvAL4mCPCFPwJgGQAY/QuABgBOfwHwVXHAZ1/3JgAWwmDxiwBoADj9EQANAKc/AmAhDBa/AuCnoAHg9BcANACc/gKABoDTXwDQAHD6CwBeEAMvfAkAHgwFD30KgAZoADj9BUADAKe/AGgA4PQXAA0AnP4CoAGA018ANABw+guABgBOfwHwnjDgXV8B0ABw+iMAGgBOfwRAA8DpjwBoADj9EQCPBoEHfhAADQCnPwKgAeD0RwCsBMDQHwHQAHD6IwDbur178PtP2fFXwDkgAFYCYOiPACQbYBxEbezj9BcArAQw9EcAMA7C2AcBMA5yTGDsgwAYB4GxDwJgHATGPgiAWwFw4Y8AeFkMvOSFANgMg30vAuBWAFz4IwBuBcCFPwLgVgBc+CMAHhACj/ogAN4VAM/4CwAmQmDmIwBYDoNlrwAgA+DoFwBMhDDzQQCQARz9CAAeFcUjnggAFgMY9yMAyACOfgQAGcDRjwAgAzj6EQBkAEc/AoAHRvFwJwKADODoRwAwF8K0BwHg2hlwQ7DeJb+jHwHgbXMhNwR7v+Q37UEAcEPgkh8EACVw7oMAYDRk1IMAgBI49xEAOKsEpkPXnPM49xEA7AnM90EAMCAy5AEBYM7bAjF406HvYh8BYM0YGBO9OtZ36CMA5LbHwZuDv5f5xjsIADzpwZL3B4//1/xXRgBg5SQ47hEAuGwVth0fPY5xnPUIAEyXh5dOBOPZgf6Sny0CAIAAACAAAAgAAAIAgAAAIAAACAAAAgCAAAAgAAAIAAACAIAAACAAAAgAAAIAgAAAIAAAAuCnACAAAAgAAAIAgAAAIAAACAAAAgCAAAAgAAAIAAACAIAAACAAAAgAAAIAgAAAIAAACAAAAgCAAAAgAAAIAAACACAAAAgAAAIAgAAAIAAACAAAAgCAAAAwvz9PFmiBlmVpvgAAAABJRU5ErkJggg==",
      "sizes": "512x512",
      "type": "image/png",
      "purpose": "any maskable"
    }
  ],
  "shortcuts": [
    { "name": "Courses / कोर्स", "short_name": "Courses", "url": "./index.html#courses" },
    { "name": "Discovery Quiz / करियर खोज", "short_name": "Quiz", "url": "./index.html#quiz" },
    { "name": "Plans / प्लान", "short_name": "Plans", "url": "./index.html#plans" }
  ]
}
```

# `sw.js`

```javascript
/* DishaVerse Pro — Offline-first Service Worker v1.0.1
   Cache-first + background refresh. Bump VER on every deploy. */
'use strict';
const VER='1.0.1';
const CORE='dvpro-core-v'+VER;
const RT='dvpro-rt-v'+VER;
const CORE_ASSETS=['./','./index.html','./manifest.json'];

self.addEventListener('install',e=>{
  e.waitUntil((async()=>{
    const c=await caches.open(CORE);
    await c.addAll(CORE_ASSETS);
    try{const r=await fetch('./courses.json',{cache:'no-store'});if(r&&r.ok)await c.put('./courses.json',r.clone());}catch(_){}
    await self.skipWaiting();
  })());
});

self.addEventListener('activate',e=>{
  e.waitUntil((async()=>{
    const keys=await caches.keys();
    await Promise.all(keys.filter(k=>k!==CORE&&k!==RT).map(k=>caches.delete(k)));
    await self.clients.claim();
  })());
});

async function swr(req,cacheName,event){
  const c=await caches.open(cacheName);
  const cached=await c.match(req);
  const net=fetch(req).then(r=>{if(r&&(r.ok||r.type==='opaque'))c.put(req,r.clone());return r;}).catch(()=>null);
  if(cached){event.waitUntil(net);return cached;}
  const r=await net;
  return r||new Response('',{status:504,statusText:'Offline'});
}

self.addEventListener('fetch',e=>{
  const req=e.request;
  if(req.method!=='GET')return;
  const url=new URL(req.url);
  if(!url.protocol.startsWith('http'))return;
  if(req.mode==='navigate'){
    e.respondWith((async()=>{
      const c=await caches.open(CORE);
      const cached=(await c.match('./index.html'))||(await c.match('./'));
      const net=fetch(req).then(r=>{if(r&&r.ok)c.put('./index.html',r.clone());return r;}).catch(()=>null);
      if(cached){event.waitUntil(net);return cached;}
      const r=await net;
      return r||new Response('DishaVerse Pro: open once while online to enable offline mode.',{status:503,headers:{'Content-Type':'text/plain; charset=utf-8'}});
    })());
    return;
  }
  if(url.origin===self.location.origin){e.respondWith(swr(req,CORE,e));return;}
  e.respondWith(swr(req,RT,e));
});

self.addEventListener('message',e=>{if(e.data&&e.data.type==='SKIP_WAITING')self.skipWaiting();});
```
