[index.html](https://github.com/user-attachments/files/33906625/index.html)
<!doctype html>
<html lang="th">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1,viewport-fit=cover">
<title>คลังเนื้อหาและสื่อ หน่วยการเรียนรู้ฐานสมรรถนะ “ปัญญาประดิษฐ์เพื่อแก้ปัญหาภัยธรรมชาติในจังหวัดอุตรดิตถ์”</title>
<meta name="description" content="ใบกิจกรรม 1–6 พร้อมตัวอย่างละเอียด 5 ภัย (น้ำท่วม ภัยแล้ง ไฟป่า/หมอกควัน วาตภัย ดินถล่ม) เกณฑ์ประเมิน และเครื่องจำลองระดับเตือนภัย 0–3 โรงเรียนอุตรดิตถ์">
<meta property="og:type" content="website">
<meta property="og:locale" content="th_TH">
<meta property="og:title" content="คลังเนื้อหาและสื่อ หน่วยการเรียนรู้ฐานสมรรถนะ “ปัญญาประดิษฐ์เพื่อแก้ปัญหาภัยธรรมชาติในจังหวัดอุตรดิตถ์”">
<meta property="og:description" content="ใบกิจกรรม 1–6 พร้อมตัวอย่างละเอียด 5 ภัย (น้ำท่วม ภัยแล้ง ไฟป่า/หมอกควัน วาตภัย ดินถล่ม) เกณฑ์ประเมิน และเครื่องจำลองระดับเตือนภัย 0–3 โรงเรียนอุตรดิตถ์">
<meta name="theme-color" content="#E6F4FE">
<link rel="icon" href="data:image/svg+xml,%3Csvg%20xmlns%3D%22http%3A//www.w3.org/2000/svg%22%20viewBox%3D%220%200%2064%2064%22%3E%3Crect%20width%3D%2264%22%20height%3D%2264%22%20rx%3D%2214%22%20fill%3D%22%23E6F4FE%22/%3E%3Crect%20x%3D%2224%22%20y%3D%228%22%20width%3D%2216%22%20height%3D%2248%22%20rx%3D%225%22%20fill%3D%22%23fff%22%20stroke%3D%22%2313244A%22%20stroke-width%3D%224%22/%3E%3Crect%20x%3D%2227%22%20y%3D%2212%22%20width%3D%2210%22%20height%3D%229%22%20fill%3D%22%23E5383B%22/%3E%3Crect%20x%3D%2227%22%20y%3D%2221%22%20width%3D%2210%22%20height%3D%229%22%20fill%3D%22%23F58A1F%22/%3E%3Crect%20x%3D%2227%22%20y%3D%2230%22%20width%3D%2210%22%20height%3D%229%22%20fill%3D%22%23F5C400%22/%3E%3Crect%20x%3D%2227%22%20y%3D%2239%22%20width%3D%2210%22%20height%3D%2213%22%20fill%3D%22%232FBF63%22/%3E%3C/svg%3E">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Mitr:wght@400;500;600&family=Noto+Sans+Thai:wght@400;500;600;700&display=swap">
<style>
/* Concept: "เสาวัดน้ำ" — a village water gauge (levels 0-3) is the through-line.
   Six activities = six marks on the gauge, each with its own colour.
   Chunky outlined cards + hard offset shadows: poster-like, easy to read from the back of a classroom. */
:root{
  --bg:#E6F4FE; --bg-2:#CFE9FB; --surface:#FFFFFF; --surface-2:#F2F9FF;
  --ink:#13244A; --ink-2:#46587C; --line:#13244A; --shadow:#13244A; --focus:#3F5CFF;
  --a1:#FF6B4A; --a1-ink:#BE3219; --a1-soft:#FFE9E3; --a1-on:#13244A;
  --a2:#35C46B; --a2-ink:#157A3B; --a2-soft:#DEF6E6; --a2-on:#13244A;
  --a3:#3F5CFF; --a3-ink:#2B44D6; --a3-soft:#E4E9FF; --a3-on:#FFFFFF;
  --a4:#FFB81C; --a4-ink:#8F5A00; --a4-soft:#FFF1CF; --a4-on:#13244A;
  --a5:#1FC2D6; --a5-ink:#0B7384; --a5-soft:#D9F6FA; --a5-on:#13244A;
  --a6:#7B47F0; --a6-ink:#6B36DB; --a6-soft:#EDE4FF; --a6-on:#FFFFFF;
  --lv0:#2FBF63; --lv1:#F5C400; --lv2:#F58A1F; --lv3:#E5383B;
  --sc-sky:#BFE4FA; --sc-m1:#7FD3A0; --sc-m2:#4FB985; --sc-cloud:#FFFFFF; --sc-rain:#3F8FE0;
  --sc-w1:#59BDF2; --sc-w2:#2F93E3; --sc-w3:#1D6DC4; --sc-wall:#FFD36B; --sc-roof:#E8553B; --sc-pole:#FFFFFF;
  --font-display:'Mitr','Noto Sans Thai',system-ui,sans-serif;
  --font-body:'Noto Sans Thai','Sarabun',system-ui,sans-serif;
  --font-mono:ui-monospace,SFMono-Regular,Menlo,Consolas,monospace;
  --r:18px; --r-sm:12px; --bw:2.5px; --sh:5px; --bl:#1F4E79;
}
@media (prefers-color-scheme: dark){
  :root:not([data-theme="light"]){
    --bg:#0C1733; --bg-2:#12214A; --surface:#16254F; --surface-2:#1C2E5E;
    --ink:#EAF1FF; --ink-2:#A9B9DE; --line:#8EA6EA; --shadow:#050B1F; --focus:#FFCE55;
    --a1-ink:#FF9A82; --a1-soft:#43263A;
    --a2-ink:#6FE39A; --a2-soft:#1B4040;
    --a3-ink:#9DB0FF; --a3-soft:#243A7E;
    --a4-ink:#FFCE55; --a4-soft:#4A3F26;
    --a5-ink:#5CDDEB; --a5-soft:#17475C;
    --a6-ink:#C3A8FF; --a6-soft:#3A2D74;
    --sc-sky:#1B2F66; --sc-m1:#2E7A6B; --sc-m2:#236657; --sc-cloud:#3A4F8A; --sc-rain:#7FB2F2;
    --sc-w1:#2D82D0; --sc-w2:#1F65B3; --sc-w3:#164E96; --sc-wall:#E8B94A; --sc-roof:#D2492F; --sc-pole:#EAF1FF;
    --bl:#9FC6F5; color-scheme:dark;
  }
}
:root[data-theme="dark"]{
  --bg:#0C1733; --bg-2:#12214A; --surface:#16254F; --surface-2:#1C2E5E;
  --ink:#EAF1FF; --ink-2:#A9B9DE; --line:#8EA6EA; --shadow:#050B1F; --focus:#FFCE55;
  --a1-ink:#FF9A82; --a1-soft:#43263A;
  --a2-ink:#6FE39A; --a2-soft:#1B4040;
  --a3-ink:#9DB0FF; --a3-soft:#243A7E;
  --a4-ink:#FFCE55; --a4-soft:#4A3F26;
  --a5-ink:#5CDDEB; --a5-soft:#17475C;
  --a6-ink:#C3A8FF; --a6-soft:#3A2D74;
  --sc-sky:#1B2F66; --sc-m1:#2E7A6B; --sc-m2:#236657; --sc-cloud:#3A4F8A; --sc-rain:#7FB2F2;
  --sc-w1:#2D82D0; --sc-w2:#1F65B3; --sc-w3:#164E96; --sc-wall:#E8B94A; --sc-roof:#D2492F; --sc-pole:#EAF1FF;
  --bl:#9FC6F5; color-scheme:dark;
}

*,*::before,*::after{box-sizing:border-box}
html{scroll-behavior:smooth;-webkit-text-size-adjust:100%}
body{margin:0;background:var(--bg);color:var(--ink);font-family:var(--font-body);font-size:17px;line-height:1.8;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0 0 auto;height:env(safe-area-inset-top,0px);background:var(--surface);z-index:60}
.app{min-height:100vh}
.wrap{width:100%;max-width:1160px;margin-inline:auto;padding-left:max(16px,env(safe-area-inset-left,0px));padding-right:max(16px,env(safe-area-inset-right,0px))}
h1,h2,h3,h4,h5{font-family:var(--font-display);font-weight:500;line-height:1.35;margin:0 0 .5em;text-wrap:balance}
h1{font-size:clamp(2rem,5.4vw,3.6rem);font-weight:600;line-height:1.3}
h2{font-size:clamp(1.6rem,3.6vw,2.4rem)}
h3{font-size:clamp(1.3rem,2.6vw,1.65rem)}
h4{font-size:1.15rem}
h5{font-size:1rem}
p{margin:0 0 .9em;max-width:70ch}
ul,ol{margin:0 0 1em;padding-left:1.35em}
li{margin-bottom:.35em}
a{color:var(--a3-ink);text-underline-offset:3px}
b,strong{font-weight:600}
small,.sm{font-size:.88rem}
.mute{color:var(--ink-2)}
code,.mono{font-family:var(--font-mono);font-size:.92em;background:var(--surface-2);border:1.5px solid color-mix(in srgb,var(--line) 35%,transparent);border-radius:6px;padding:.05em .4em}
:focus-visible{outline:3px solid var(--focus);outline-offset:3px;border-radius:6px}
.sr{position:absolute;width:1px;height:1px;overflow:hidden;clip:rect(0 0 0 0);white-space:nowrap}
.nb{white-space:nowrap}

/* ---------- nav ---------- */
.nav{position:sticky;top:env(safe-area-inset-top,0px);z-index:50;background:var(--surface);border-bottom:var(--bw) solid var(--line)}
.nav-in{display:flex;align-items:center;gap:10px 14px;flex-wrap:wrap;padding-block:8px}
.brand{display:flex;align-items:center;gap:10px;text-decoration:none;color:var(--ink);flex:0 1 auto;min-width:0}
.brand-ic{width:38px;height:38px;flex:none}
.brand-t{display:flex;flex-direction:column;line-height:1.25;min-width:0}
.brand-t b{font-family:var(--font-display);font-weight:500;font-size:1.05rem}
.brand-t small{color:var(--ink-2);font-size:.74rem}
.chips{display:flex;gap:6px;flex:1 1 auto;min-width:0;overflow-x:auto;padding:4px 2px;scrollbar-width:thin}
.chip{display:inline-flex;align-items:center;gap:7px;white-space:nowrap;text-decoration:none;color:var(--ink);font-weight:600;font-size:.9rem;line-height:1.3;padding:5px 12px 5px 6px;border-radius:999px;border:2px solid transparent}
.chip:hover{background:var(--surface-2)}
.chip[aria-current="page"]{background:var(--surface-2);border-color:var(--line)}
.chip.plain{padding-left:12px}
.chip i{font-style:normal;font-family:var(--font-display);width:26px;height:26px;border-radius:50%;display:grid;place-items:center;font-size:.85rem;border:2px solid var(--line);line-height:1}
.chip.c1 i{background:var(--a1);color:var(--a1-on)} .chip.c2 i{background:var(--a2);color:var(--a2-on)}
.chip.c3 i{background:var(--a3);color:var(--a3-on)} .chip.c4 i{background:var(--a4);color:var(--a4-on)}
.chip.c5 i{background:var(--a5);color:var(--a5-on)} .chip.c6 i{background:var(--a6);color:var(--a6-on)}
.theme-btn{flex:none;width:40px;height:40px;border-radius:50%;border:2px solid var(--line);background:var(--surface-2);color:var(--ink);display:grid;place-items:center;cursor:pointer;margin-left:auto}
.theme-btn svg{width:20px;height:20px}
@media (min-width:980px){.chips{order:0}.theme-btn{margin-left:0}}
@media (max-width:979px){.chips{order:3;flex-basis:100%}}
@media (max-width:560px){.brand{flex:1 1 0}.brand-t b{font-size:.9rem}.brand-t small{font-size:.7rem}}

/* ---------- generic components ---------- */
.card{background:var(--surface);border:var(--bw) solid var(--line);border-radius:var(--r);box-shadow:var(--sh) var(--sh) 0 var(--shadow);padding:clamp(16px,3vw,26px);min-width:0}
.card.flat{box-shadow:none}
.card.soft{background:var(--surface-2)}
.card > :last-child{margin-bottom:0}
.grid{display:grid;gap:clamp(14px,2.4vw,24px);min-width:0}
.g2{grid-template-columns:repeat(auto-fit,minmax(min(100%,320px),1fr))}
.g3{grid-template-columns:repeat(auto-fit,minmax(min(100%,260px),1fr))}
.g4{grid-template-columns:repeat(auto-fit,minmax(min(100%,220px),1fr))}
.stack>*+*{margin-top:clamp(16px,2.6vw,26px)}
.sec{padding-block:clamp(28px,5vw,56px)}
.eyebrow{display:inline-flex;align-items:center;gap:8px;font-weight:700;font-size:.85rem;padding:3px 12px;border-radius:999px;border:2px solid var(--line);background:var(--surface);margin-bottom:12px}
.btn{display:inline-flex;align-items:center;justify-content:center;gap:8px;font-family:var(--font-display);font-weight:500;font-size:1rem;line-height:1.3;padding:10px 20px;border-radius:999px;border:var(--bw) solid var(--line);background:var(--surface);color:var(--ink);text-decoration:none;cursor:pointer;box-shadow:3px 3px 0 var(--shadow);transition:transform .08s,box-shadow .08s}
.btn:hover{transform:translate(-1px,-1px);box-shadow:4px 4px 0 var(--shadow)}
.btn:active{transform:translate(2px,2px);box-shadow:1px 1px 0 var(--shadow)}
.btn.pri{background:var(--a1);color:var(--a1-on)}
.btn.sm{padding:5px 14px;font-size:.9rem;box-shadow:2px 2px 0 var(--shadow)}
.btn svg{width:18px;height:18px;flex:none}
.pill{display:inline-flex;align-items:center;gap:6px;font-size:.82rem;font-weight:600;line-height:1.4;padding:2px 11px;border-radius:999px;border:2px solid var(--line);background:var(--surface);white-space:nowrap}
.pill.fill{background:var(--accent,var(--a1));color:var(--accent-on,var(--a1-on))}
.tag-sim{display:inline-block;font-size:.78rem;font-weight:700;padding:0 8px;border-radius:6px;background:var(--a4-soft);color:var(--a4-ink);border:1.5px dashed var(--a4-ink);vertical-align:.1em;white-space:nowrap}
.ic{width:1.25em;height:1.25em;stroke:currentColor;fill:none;stroke-width:2;stroke-linecap:round;stroke-linejoin:round;flex:none}

.callout{display:flex;gap:14px;align-items:flex-start;border:var(--bw) solid var(--line);border-radius:var(--r-sm);padding:14px 18px;background:var(--surface-2)}
.callout .ic{width:26px;height:26px;margin-top:3px}
.callout>div{min-width:0}
.callout>div>:last-child{margin-bottom:0}
.callout.safe{background:var(--a2-soft)} .callout.safe .ic{color:var(--a2-ink)}
.callout.warn{background:var(--a4-soft)} .callout.warn .ic{color:var(--a4-ink)}
.callout.note{background:var(--a3-soft)} .callout.note .ic{color:var(--a3-ink)}
.callout.bad{background:var(--a1-soft)} .callout.bad .ic{color:var(--a1-ink)}
.callout.idea{background:var(--a6-soft)} .callout.idea .ic{color:var(--a6-ink)}
.callout h5{margin:0 0 .2em}

.tbl{overflow-x:auto;border:var(--bw) solid var(--line);border-radius:var(--r-sm);background:var(--surface);-webkit-overflow-scrolling:touch}
.tbl table{border-collapse:collapse;width:100%;min-width:560px;font-size:.95rem;line-height:1.65}
.tbl th,.tbl td{padding:9px 14px;text-align:left;vertical-align:top;border-bottom:1.5px solid color-mix(in srgb,var(--line) 30%,transparent);border-right:1.5px solid color-mix(in srgb,var(--line) 30%,transparent)}
.tbl th:last-child,.tbl td:last-child{border-right:0}
.tbl tr:last-child td{border-bottom:0}
.tbl th{background:var(--accent-soft,var(--a3-soft));font-weight:600;color:var(--ink)}
.tbl td:first-child{font-weight:600}
.tbl.tight table{min-width:0}
.tbl td p:last-child,.tbl td ul:last-child{margin-bottom:0}
.tbl ul{padding-left:1.1em;margin:0}

dl.kv{margin:0;display:grid;gap:10px}
dl.kv dt{font-weight:700;font-size:.9rem;color:var(--accent-ink,var(--a3-ink))}
dl.kv dd{margin:0 0 6px;min-width:0}
dl.kv dd p:last-child{margin-bottom:0}
.sep{border:0;border-top:2px dashed color-mix(in srgb,var(--line) 40%,transparent);margin:18px 0}

/* ---------- hero ---------- */
.hero{background:linear-gradient(180deg,var(--bg-2),var(--bg));border-bottom:var(--bw) solid var(--line);overflow:hidden}
.hero-in{display:grid;grid-template-columns:minmax(0,1.05fr) minmax(0,.95fr);gap:clamp(20px,4vw,48px);align-items:center;padding-block:clamp(28px,5vw,60px)}
@media (max-width:860px){.hero-in{grid-template-columns:1fr}}
.hero h1{margin-bottom:.45em}
.hero h1 em{font-style:normal;color:var(--a1-ink)}
.hero .lead{font-size:1.15rem;max-width:34em}
.hero-stats{display:flex;flex-wrap:wrap;gap:10px;margin:20px 0 26px}
.hero-stats .pill{font-size:.95rem;padding:4px 14px}
.hero-cta{display:flex;flex-wrap:wrap;gap:12px}
.scene{width:100%;height:auto;display:block;border:var(--bw) solid var(--line);border-radius:var(--r);box-shadow:var(--sh) var(--sh) 0 var(--shadow);background:var(--sc-sky)}
.scene .rain{stroke:var(--sc-rain);stroke-width:3;stroke-linecap:round;animation:rain 1.1s linear infinite}
.scene .rain.b{animation-delay:-.5s}
@keyframes rain{from{transform:translateY(-24px)}to{transform:translateY(34px)}}
.scene .wv{animation:drift 7s ease-in-out infinite alternate}
.scene .wv.b{animation-duration:9s;animation-direction:alternate-reverse}
@keyframes drift{from{transform:translateX(-14px)}to{transform:translateX(14px)}}
@media (prefers-reduced-motion:reduce){.scene .rain,.scene .wv,.lamp.blink,.btn{animation:none!important;transition:none!important}html{scroll-behavior:auto}}

/* scene (hero illustration) */
.s-sky{fill:var(--sc-sky)}.s-m1{fill:var(--sc-m1)}.s-m2{fill:var(--sc-m2)}.s-cloud{fill:var(--sc-cloud)}
.s-w1{fill:var(--sc-w1)}.s-w2{fill:var(--sc-w2)}.s-w3{fill:var(--sc-w3)}
.s-wall{fill:var(--sc-wall);stroke:var(--line);stroke-width:3}.s-roof{fill:var(--sc-roof);stroke:var(--line);stroke-width:3}
.s-pole{fill:var(--sc-pole);stroke:var(--line);stroke-width:3}
.s-lv0{fill:var(--lv0)}.s-lv1{fill:var(--lv1)}.s-lv2{fill:var(--lv2)}.s-lv3{fill:var(--lv3)}
.s-tick{stroke:var(--line);stroke-width:3}
.s-num{font-family:var(--font-display);font-size:20px;fill:var(--ink)}
.s-lab{font-family:var(--font-body);font-size:13px;font-weight:700;fill:var(--ink)}
.s-chip{fill:var(--surface);stroke:var(--line);stroke-width:2.5}
.lv-legend{display:flex;flex-wrap:wrap;gap:8px;margin-top:14px}
.lv-legend span{display:inline-flex;align-items:center;gap:8px;font-size:.85rem;font-weight:600;border:2px solid var(--line);border-radius:999px;padding:1px 12px 1px 3px;background:var(--surface)}
.lv-legend i{font-style:normal;width:24px;height:24px;border-radius:50%;display:grid;place-items:center;border:2px solid var(--line);font-family:var(--font-display);font-size:.8rem;color:#13244A;background:var(--lc)}

/* ---------- mission + hours ---------- */
.mission{background:var(--ink);color:var(--bg);border-block:var(--bw) solid var(--line)}
:root[data-theme="dark"] .mission{background:var(--surface-2);color:var(--ink)}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]) .mission{background:var(--surface-2);color:var(--ink)}}
.mission-in{display:grid;grid-template-columns:minmax(0,1.3fr) minmax(0,1fr);gap:clamp(18px,4vw,48px);align-items:center;padding-block:clamp(26px,4vw,48px)}
@media (max-width:800px){.mission-in{grid-template-columns:1fr}}
.mission h2{color:inherit;margin:0 0 .3em;font-size:clamp(1.5rem,3.4vw,2.2rem)}
.mission p{margin:0;opacity:.92}
.mission .goal{border:var(--bw) solid currentColor;border-radius:var(--r);padding:16px 20px;background:color-mix(in srgb,currentColor 10%,transparent)}
.mission .goal b{display:block;font-family:var(--font-display);font-weight:500;font-size:1.25rem;line-height:1.5}
.hours{display:flex;gap:6px;margin:18px 0 8px;min-width:0}
.hours a{display:flex;flex-direction:column;justify-content:flex-end;gap:6px;text-decoration:none;color:var(--ink);min-width:0}
.hours .bar{height:46px;border:var(--bw) solid var(--line);border-radius:10px;background:var(--c);color:var(--on);display:grid;place-items:center;font-family:var(--font-display);font-size:1.05rem;transition:transform .1s}
.hours a:hover .bar{transform:translateY(-3px)}
.hours small{font-size:.82rem;line-height:1.35;text-align:center;font-weight:600}
@media (max-width:640px){.hours small{font-size:.7rem}.hours .bar{height:38px}}

/* ---------- roadmap ---------- */
.rm{display:grid;grid-template-columns:repeat(auto-fit,minmax(min(100%,330px),1fr));gap:clamp(16px,2.6vw,26px)}
.rm-card{--c:var(--a1);--ci:var(--a1-ink);--cs:var(--a1-soft);--on:var(--a1-on);display:flex;flex-direction:column;gap:10px;padding:0;overflow:hidden}
.rm-card.k2{--c:var(--a2);--ci:var(--a2-ink);--cs:var(--a2-soft);--on:var(--a2-on)}
.rm-card.k3{--c:var(--a3);--ci:var(--a3-ink);--cs:var(--a3-soft);--on:var(--a3-on)}
.rm-card.k4{--c:var(--a4);--ci:var(--a4-ink);--cs:var(--a4-soft);--on:var(--a4-on)}
.rm-card.k5{--c:var(--a5);--ci:var(--a5-ink);--cs:var(--a5-soft);--on:var(--a5-on)}
.rm-card.k6{--c:var(--a6);--ci:var(--a6-ink);--cs:var(--a6-soft);--on:var(--a6-on)}
.rm-top{background:var(--c);color:var(--on);display:flex;align-items:center;gap:14px;padding:14px 20px;border-bottom:var(--bw) solid var(--line)}
.rm-n{font-family:var(--font-display);font-size:2.8rem;line-height:1;font-weight:600}
.rm-top h3{margin:0;font-size:1.25rem;color:inherit}
.rm-top small{display:block;font-size:.82rem;font-weight:600;opacity:.9}
.rm-body{padding:4px 20px 20px;display:flex;flex-direction:column;gap:12px;flex:1}
.rm-body dl{margin:0;display:grid;gap:8px}
.rm-body dt{font-size:.82rem;font-weight:700;color:var(--ci)}
.rm-body dd{margin:0;font-size:.95rem;line-height:1.6}
.rm-foot{display:flex;align-items:center;justify-content:space-between;gap:12px;margin-top:auto;flex-wrap:wrap}
.prog{font-size:.82rem;font-weight:600;color:var(--ink-2)}

/* ---------- story strip ---------- */
.story{display:grid;grid-template-columns:repeat(auto-fit,minmax(min(100%,300px),1fr));gap:16px;counter-reset:st}
.st{--c:var(--a1);position:relative;background:var(--surface);border:var(--bw) solid var(--line);border-radius:var(--r-sm);padding:14px 18px 16px}
.st.k2{--c:var(--a2)}.st.k3{--c:var(--a3)}.st.k4{--c:var(--a4)}.st.k5{--c:var(--a5)}.st.k6{--c:var(--a6)}
.st h4{display:flex;align-items:center;gap:10px;margin:0 0 .3em;font-size:1.02rem}
.st h4 i{font-style:normal;flex:none;width:30px;height:30px;border-radius:50%;background:var(--c);border:2px solid var(--line);display:grid;place-items:center;font-size:.9rem;color:var(--ink)}
.st.k3 h4 i,.st.k6 h4 i{color:#fff}
.st p{margin:0;font-size:.95rem;line-height:1.65}

/* ---------- activity header ---------- */
.ah{--c:var(--a1);--ci:var(--a1-ink);--cs:var(--a1-soft);--on:var(--a1-on);background:var(--c);color:var(--on);border-bottom:var(--bw) solid var(--line);position:relative;overflow:hidden}
.k2.ah,.view.k2{--c:var(--a2);--ci:var(--a2-ink);--cs:var(--a2-soft);--on:var(--a2-on)}
.k3.ah,.view.k3{--c:var(--a3);--ci:var(--a3-ink);--cs:var(--a3-soft);--on:var(--a3-on)}
.k4.ah,.view.k4{--c:var(--a4);--ci:var(--a4-ink);--cs:var(--a4-soft);--on:var(--a4-on)}
.k5.ah,.view.k5{--c:var(--a5);--ci:var(--a5-ink);--cs:var(--a5-soft);--on:var(--a5-on)}
.k6.ah,.view.k6{--c:var(--a6);--ci:var(--a6-ink);--cs:var(--a6-soft);--on:var(--a6-on)}
.view.k1{--c:var(--a1);--ci:var(--a1-ink);--cs:var(--a1-soft);--on:var(--a1-on)}
.ah-in{display:grid;grid-template-columns:auto minmax(0,1fr);gap:clamp(14px,3vw,34px);align-items:center;padding-block:clamp(22px,4vw,44px)}
.ah-num{font-family:var(--font-display);font-weight:600;font-size:clamp(5rem,13vw,9.5rem);line-height:.9;letter-spacing:-.02em;-webkit-text-stroke:var(--bw) var(--line);color:var(--surface);paint-order:stroke fill;text-shadow:5px 5px 0 var(--shadow)}
.ah h1{font-size:clamp(1.7rem,4.4vw,2.9rem);margin:0 0 .25em;color:inherit}
.ah .stage{font-weight:600;margin:0 0 .5em;opacity:.95}
.ah .mission-line{max-width:60ch;margin:0 0 14px;font-size:1.05rem}
.ah .pills{display:flex;flex-wrap:wrap;gap:8px}
.ah .pill{background:var(--surface);color:var(--ink)}
.ah::after{content:"";position:absolute;inset:auto 0 0 0;height:14px;background:radial-gradient(circle at 14px 0,transparent 13px,var(--bg) 14px) 0 0/28px 14px repeat-x;pointer-events:none}
@media (max-width:560px){.ah-in{grid-template-columns:1fr}.ah-num{font-size:5rem}}

/* ---------- tabs ---------- */
.tabs{display:flex;gap:8px;flex-wrap:wrap;padding-block:20px 6px}
.tab{font-family:var(--font-display);font-weight:500;font-size:1rem;line-height:1.3;padding:9px 18px;border-radius:999px;border:var(--bw) solid var(--line);background:var(--surface);color:var(--ink);cursor:pointer;display:inline-flex;align-items:center;gap:8px;box-shadow:3px 3px 0 var(--shadow)}
.tab .ic{width:18px;height:18px}
.tab:hover{background:var(--cs)}
.tab[aria-selected="true"]{background:var(--c);color:var(--on);transform:translate(2px,2px);box-shadow:1px 1px 0 var(--shadow)}
.panel{padding-block:18px 40px}
.panel>.stack>h3{display:flex;align-items:center;gap:10px}
.lede{font-size:1.1rem;max-width:62ch}
.blk{display:flex;flex-direction:column;gap:14px}
.blk>h3{margin:0}
.blk>p{margin:0}
.num-dot{display:inline-grid;place-items:center;flex:none;width:34px;height:34px;border-radius:50%;background:var(--c);color:var(--on);border:2px solid var(--line);font-family:var(--font-display);font-size:1rem}
.toc{display:flex;flex-wrap:wrap;gap:8px;margin:0 0 6px;padding:0;list-style:none}
.toc a{display:inline-flex;gap:8px;align-items:center;text-decoration:none;color:var(--ink);background:var(--surface);border:2px solid var(--line);border-radius:999px;padding:3px 14px 3px 4px;font-size:.88rem;font-weight:600}
.toc a:hover{background:var(--cs)}
.toc a i{font-style:normal;width:24px;height:24px;border-radius:50%;background:var(--c);color:var(--on);display:grid;place-items:center;font-size:.8rem;font-family:var(--font-display)}

/* ---------- worked example blocks ---------- */
.ex{scroll-margin-top:130px;background:var(--surface);border:var(--bw) solid var(--line);border-radius:var(--r);box-shadow:var(--sh) var(--sh) 0 var(--shadow);overflow:hidden}
.ex-h{display:flex;align-items:center;gap:12px;padding:12px 20px;background:var(--cs);border-bottom:var(--bw) solid var(--line)}
.ex-h h4{margin:0;font-size:1.12rem}
.ex-b{padding:18px 20px 22px;display:flex;flex-direction:column;gap:16px;min-width:0}
.ex-q{font-size:.95rem;color:var(--ink-2);border:2px dashed color-mix(in srgb,var(--line) 45%,transparent);border-radius:var(--r-sm);padding:10px 14px}
.ex-q b{color:var(--ink)}
.ex-q p{margin:.2em 0 0}
.lab{display:inline-block;font-size:.8rem;font-weight:700;padding:1px 11px;border-radius:999px;background:var(--c);color:var(--on);border:2px solid var(--line);margin-bottom:8px}
.ex-a{min-width:0}
.ex-a>:last-child{margin-bottom:0}
.why{display:flex;gap:12px;align-items:flex-start;background:var(--a4-soft);border:2px solid var(--line);border-radius:var(--r-sm);padding:10px 14px;font-size:.95rem}
.why .ic{color:var(--a4-ink);width:24px;height:24px;margin-top:2px}
.why>div{min-width:0}
.why p{margin:0}
.why b{color:var(--a4-ink)}
.quote{margin:0;padding:10px 16px;border:2px solid var(--line);border-radius:var(--r-sm);background:var(--surface-2);font-size:.98rem}
.pair{display:grid;grid-template-columns:repeat(auto-fit,minmax(min(100%,260px),1fr));gap:12px}
.pair>div{border:2px solid var(--line);border-radius:var(--r-sm);padding:10px 14px;background:var(--surface);min-width:0}
.pair h5{margin:0 0 .3em}
.pair .bad{background:var(--a1-soft)} .pair .good{background:var(--a2-soft)}
.pair p:last-child,.pair ul:last-child{margin-bottom:0}

/* ---------- chips for 3-way ---------- */
.three{display:grid;grid-template-columns:repeat(auto-fit,minmax(min(100%,240px),1fr));gap:12px}
.three>div{border:var(--bw) solid var(--line);border-radius:var(--r-sm);padding:12px 16px;background:var(--surface);min-width:0}
.three h5{margin:0 0 .3em;font-size:1rem}
.three p,.three ul{font-size:.95rem;margin:0}
.three ul{padding-left:1.1em}
.three .k-know{background:var(--a2-soft)} .three .k-guess{background:var(--a4-soft)} .three .k-ask{background:var(--a3-soft)}

/* ---------- interactive ---------- */
.reveal-box{border:2px dashed var(--line);border-radius:var(--r-sm);padding:12px 16px;background:var(--surface-2)}
.reveal-box[hidden]{display:none}
.quiz{border:var(--bw) solid var(--line);border-radius:var(--r);background:var(--surface);padding:16px 20px;box-shadow:var(--sh) var(--sh) 0 var(--shadow)}
.quiz>h5{font-size:1.05rem;margin:0 0 10px;display:flex;gap:10px;align-items:center}
.quiz>h5 .pill{background:var(--c);color:var(--on)}
.opts{display:grid;gap:8px;margin:10px 0}
.opt{text-align:left;font:inherit;line-height:1.55;padding:10px 14px;border-radius:var(--r-sm);border:2px solid var(--line);background:var(--surface-2);color:var(--ink);cursor:pointer;display:flex;gap:10px}
.opt:hover:not([disabled]){background:var(--cs)}
.opt .k{flex:none;width:26px;height:26px;border-radius:50%;border:2px solid var(--line);display:grid;place-items:center;font-size:.8rem;font-weight:700;background:var(--surface)}
.opt.ok{background:var(--a2-soft);border-color:var(--a2-ink)}
.opt.no{background:var(--a1-soft);border-color:var(--a1-ink)}
.opt[disabled]{cursor:default}
.fb{margin-top:8px;padding:10px 14px;border-radius:var(--r-sm);background:var(--a3-soft);border:2px solid var(--line)}
.fb p:last-child{margin-bottom:0}

.checks{list-style:none;margin:0;padding:0;display:grid;gap:8px}
.checks li{margin:0}
.checks label{display:flex;gap:12px;align-items:flex-start;cursor:pointer;padding:9px 14px;border-radius:var(--r-sm);border:2px solid var(--line);background:var(--surface)}
.checks label:hover{background:var(--cs)}
.checks input{appearance:none;flex:none;width:24px;height:24px;margin:3px 0 0;border:2.5px solid var(--line);border-radius:7px;background:var(--surface);display:grid;place-items:center;cursor:pointer}
.checks input:checked{background:var(--c)}
.checks input:checked::after{content:"";width:11px;height:6px;border-left:3px solid var(--on);border-bottom:3px solid var(--on);transform:rotate(-45deg) translate(1px,-1px)}
.checks input:checked+span{color:var(--ink-2);text-decoration:line-through;text-decoration-thickness:1.5px}
.meter{height:14px;border:2px solid var(--line);border-radius:999px;background:var(--surface);overflow:hidden}
.meter>i{display:block;height:100%;width:0;background:var(--c);transition:width .25s}

/* ladder (rubric) */
.ladder{display:grid;grid-template-columns:repeat(4,minmax(0,1fr));border:var(--bw) solid var(--line);border-radius:var(--r-sm);overflow:hidden;background:var(--surface)}
.rung{padding:12px 14px;font-size:.92rem;line-height:1.6;border-left:2px solid color-mix(in srgb,var(--line) 40%,transparent);position:relative;min-width:0}
.rung:first-child{border-left:0}
.rung b{display:block;font-family:var(--font-display);font-weight:500;font-size:.95rem;margin-bottom:4px}
.rung small{display:block;font-weight:600;opacity:.8;margin-bottom:6px}
.rung:nth-child(1){background:color-mix(in srgb,var(--c) 8%,var(--surface))}
.rung:nth-child(2){background:color-mix(in srgb,var(--c) 18%,var(--surface))}
.rung:nth-child(3){background:color-mix(in srgb,var(--c) 32%,var(--surface))}
.rung:nth-child(4){background:color-mix(in srgb,var(--c) 50%,var(--surface))}
.lad-h{display:flex;align-items:baseline;gap:10px;flex-wrap:wrap;margin:0 0 8px}
.lad-h h4{margin:0}
@media (max-width:760px){.ladder{grid-template-columns:1fr}.rung{border-left:0;border-top:2px solid color-mix(in srgb,var(--line) 40%,transparent)}.rung:first-child{border-top:0}}

/* hazard chooser */
.hz-bar{display:flex;gap:8px;flex-wrap:wrap}
.hz-b{font:inherit;font-weight:600;font-size:.95rem;padding:7px 16px;border-radius:999px;border:var(--bw) solid var(--line);background:var(--surface);color:var(--ink);cursor:pointer;display:inline-flex;align-items:center;gap:8px}
.hz-b:hover{background:var(--cs)}
.hz-b[aria-selected="true"]{background:var(--ink);color:var(--surface)}
.hz-b .star{font-size:.75rem;font-weight:500;opacity:.85}
.hz-p{margin-top:18px}
.hz-title{display:flex;flex-wrap:wrap;gap:10px;align-items:center;margin-bottom:10px}
.hz-title h4{margin:0}
.src{font-family:var(--font-mono);font-size:.78rem;color:var(--ink-2);margin-left:4px;vertical-align:.15em}

/* simulator */
.sim{display:grid;grid-template-columns:minmax(0,1.1fr) minmax(0,1fr);gap:20px;align-items:start}
@media (max-width:820px){.sim{grid-template-columns:1fr}}
.sim-in{display:grid;gap:16px}
.sl{display:grid;gap:4px}
.sl label{font-weight:600;font-size:.95rem;display:flex;justify-content:space-between;gap:12px;flex-wrap:wrap}
.sl output{font-family:var(--font-display);font-size:1.1rem}
.sl input[type=range]{width:100%;accent-color:var(--c);height:28px}
.sl .th{font-size:.8rem;color:var(--ink-2)}
.sim-out{border:var(--bw) solid var(--line);border-radius:var(--r);background:var(--surface-2);padding:16px 18px;display:grid;gap:12px}
.lvl{display:flex;align-items:center;gap:12px;flex-wrap:wrap}
.lvl-b{font-family:var(--font-display);font-size:1.5rem;line-height:1.2;padding:6px 18px;border-radius:14px;border:var(--bw) solid var(--line);background:var(--lc,var(--lv0));color:#13244A}
.lvl-b.l3{color:#fff}
.lamps{display:flex;gap:10px;align-items:center}
.lamp{width:34px;height:34px;border-radius:50%;border:var(--bw) solid var(--line);background:var(--surface);opacity:.35}
.lamp.g{--lc:var(--lv0)}.lamp.y{--lc:var(--lv1)}.lamp.r{--lc:var(--lv3)}
.lamp.on{background:var(--lc);opacity:1;box-shadow:0 0 0 4px color-mix(in srgb,var(--lc) 35%,transparent)}
.lamp.blink.on{animation:blink .7s steps(2,jump-none) infinite}
@keyframes blink{50%{opacity:.25}}
.sim-msg{background:var(--surface);border:2px solid var(--line);border-radius:var(--r-sm);padding:10px 14px}
.sim-msg b{display:block;font-size:.82rem;color:var(--ink-2)}
.sim-nodata{background:var(--surface);border:2px dashed var(--line);border-radius:var(--r-sm);padding:10px 14px;display:flex;gap:10px;align-items:center;font-weight:600}
.hz-sw{display:flex;gap:6px;flex-wrap:wrap}

/* diagrams */
.diagram{width:100%;height:auto;display:block}
.dg-box{fill:var(--surface);stroke:var(--line);stroke-width:2.5}
.dg-new{fill:var(--a4-soft)}
.dg-t{fill:var(--ink);font-family:var(--font-body);font-size:15px;font-weight:600}
.dg-s{fill:var(--ink-2);font-family:var(--font-body);font-size:12.5px}
.dg-ln{stroke:var(--line);stroke-width:2.5;fill:none}
.dg-arw{fill:var(--line)}
.dg-sec{fill:var(--cs)}
.dg-tag{fill:var(--a1);stroke:var(--line);stroke-width:2}
.dg-tag-t{fill:var(--a1-on);font-family:var(--font-body);font-size:12px;font-weight:700}

.chart{width:100%;height:auto;display:block}
.chart text{font-family:var(--font-body)}
.cv-t{fill:var(--ink);font-size:13px}
.cv-s{fill:var(--ink-2);font-size:12px}
.cv-grid{stroke:color-mix(in srgb,var(--line) 25%,transparent);stroke-width:1.5}
.cv-ax{stroke:var(--line);stroke-width:2.5}
.cv-r1{fill:var(--surface);stroke:var(--c);stroke-width:3}
.cv-r2{fill:var(--c);stroke:var(--line);stroke-width:2}
.cv-lim{stroke:var(--a1-ink);stroke-width:2.5;stroke-dasharray:7 5}
.cv-lim-t{fill:var(--a1-ink);font-size:12.5px;font-weight:600}

/* flow / footer / misc */
.pn{display:flex;justify-content:space-between;gap:14px;flex-wrap:wrap;padding-block:8px 48px}
.pn .btn{max-width:100%}
.foot{border-top:var(--bw) solid var(--line);background:var(--surface);padding-block:24px 40px;font-size:.9rem;color:var(--ink-2)}
.foot p{margin:0 0 .4em;max-width:none}
.copy-row{display:flex;gap:10px;align-items:flex-start;border:2px solid var(--line);border-radius:var(--r-sm);background:var(--surface);padding:10px 14px}
.copy-row>div{flex:1;min-width:0}
.copy-row b{display:block;font-size:.85rem;color:var(--ink-2)}
.copy-row q{quotes:none;display:block}
.def dt{font-family:var(--font-display);font-weight:500}
.srcs{list-style:none;padding:0;display:grid;gap:8px}
.srcs li{margin:0;padding:8px 12px;border:2px solid var(--line);border-radius:var(--r-sm);background:var(--surface);overflow-wrap:anywhere;font-size:.92rem;line-height:1.55}
.srcs .n{font-family:var(--font-mono);font-weight:700;color:var(--a3-ink);margin-right:8px}
.big-num{font-family:var(--font-display);font-size:2rem;line-height:1.1}
.flowline{display:flex;flex-wrap:wrap;gap:8px;align-items:center}
.arrow{font-family:var(--font-display);color:var(--ci)}
.inline-link{font-weight:600}

/* additions: hidden, per-view table/kv accents, builders, marks, calculators */
[hidden]{display:none!important}
.view .tbl{--accent-soft:var(--cs)}
.view dl.kv{--accent-ink:var(--ci)}
.blk{scroll-margin-top:130px}
.bld{display:grid;grid-template-columns:repeat(auto-fit,minmax(min(100%,210px),1fr));gap:12px;margin:12px 0}
.bld label{display:grid;gap:4px;font-weight:600;font-size:.9rem}
.bld input{font:inherit;font-weight:400;padding:8px 12px;border:2px solid var(--line);border-radius:var(--r-sm);background:var(--surface);color:var(--ink);min-width:0;width:100%}
.bld input:focus-visible{outline:3px solid var(--focus);outline-offset:2px}
.bld-out{border:2px dashed var(--line);border-radius:var(--r-sm);padding:10px 14px;background:var(--surface-2)}
.bld-out p{margin:.2em 0 0}
mark.seg{color:inherit;font-weight:700;border-radius:4px;padding:0 4px}
mark.seg.s1{background:var(--a1-soft)}mark.seg.s2{background:var(--a4-soft)}mark.seg.s3{background:var(--a3-soft)}mark.seg.s4{background:var(--a2-soft)}
.trial-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(150px,1fr));gap:10px}
.trial-grid .card{padding:10px 14px}
.hz-kpi{display:flex;flex-wrap:wrap;gap:8px}
.sl output.lvl-mini{font-size:.85rem;padding:0 10px;border-radius:999px;border:2px solid var(--line);background:var(--lc,var(--lv0));color:#13244A;font-family:var(--font-body);font-weight:700}
.sl output.lvl-mini.l3{color:#fff}
.copy-row q::before,.copy-row q::after{content:none}
.copy-row q{white-space:pre-line}
.svg-scroll{overflow-x:auto;overflow-y:hidden;-webkit-overflow-scrolling:touch;border-radius:var(--r-sm)}
.svg-scroll:focus-visible{outline:3px solid var(--focus);outline-offset:2px}
.svg-hint{display:none;margin:0 0 6px;font-size:.82rem;color:var(--ink-2)}
@media (max-width:760px){.svg-scroll.wide+.svg-hint,.svg-hint.on{display:block}}

/* ---------- full worked examples of the other four hazards ---------- */
.hzx{display:grid;gap:14px;margin-top:20px;min-width:0}
.hzx-h{margin:0;font-size:1.25rem}
.hzx-meta{margin:0;font-size:.95rem}
.hzx-ctl{display:flex;flex-wrap:wrap;gap:8px}
.hzx-sec{border:var(--bw) solid var(--line);border-radius:var(--r);background:var(--surface);box-shadow:4px 4px 0 var(--shadow);min-width:0}
.hzx-sec>summary{cursor:pointer;list-style:none;display:flex;align-items:center;gap:12px;padding:12px 16px;font-family:var(--font-display);font-weight:500;font-size:1.05rem;line-height:1.45}
.hzx-sec>summary::-webkit-details-marker{display:none}
.hzx-sec>summary:focus-visible{outline:3px solid var(--focus);outline-offset:2px;border-radius:var(--r)}
.hzx-sec>summary .n{flex:none;width:32px;height:32px;border-radius:50%;display:grid;place-items:center;background:var(--c,var(--a3));color:var(--on,#fff);border:2px solid var(--line);font-size:.95rem}
.hzx-sec>summary::after{content:"+";margin-left:auto;font-size:1.6rem;line-height:1;flex:none;font-family:var(--font-body)}
.hzx-sec[open]>summary::after{content:"\2212"}
.hzx-sec[open]>summary{border-bottom:2px solid color-mix(in srgb,var(--line) 30%,transparent)}
.hzx-b{padding:14px 16px 18px;display:grid;gap:12px;min-width:0}
.hzx-b p,.hzx .ans-box p{margin:0}
.hzx .q{color:var(--ink-2);font-size:.93rem}
.hzx .sh{margin:6px 0 0;font-size:1rem;padding:6px 12px;border-radius:var(--r-sm);background:var(--cs,var(--a3-soft))}
.bl{color:var(--bl);font-weight:500}
.hzx .ans-box{border:2px dashed color-mix(in srgb,var(--bl) 55%,transparent);border-radius:var(--r-sm);padding:10px 14px;background:var(--surface-2);display:grid;gap:6px}
.hzt table{min-width:0}
.hzt td:first-child{font-weight:400}
.hzt td p+p{margin-top:.35em}
.hzt th{font-size:.9rem}
@media (max-width:700px){
  .hzt.rsp table,.hzt.rsp tbody,.hzt.rsp tr,.hzt.rsp td{display:block;width:100%}
  .hzt.rsp thead{display:none}
  .hzt.rsp tr{border-bottom:2px solid color-mix(in srgb,var(--line) 45%,transparent);padding:4px 0}
  .hzt.rsp tr:last-child{border-bottom:0}
  .hzt.rsp td{border:0;padding:6px 14px}
  .hzt.rsp td[data-label]::before{content:attr(data-label);display:block;font-size:.76rem;font-weight:700;color:var(--ink-2);margin-bottom:2px}
  .hzx-b{padding-inline:12px}
}
</style>
</head>
<body>

<div class="app" lang="th">

<svg width="0" height="0" style="position:absolute" aria-hidden="true" focusable="false">
  <defs>
    <symbol id="i-eye" viewBox="0 0 24 24"><path d="M2 12s4-7 10-7 10 7 10 7-4 7-10 7S2 12 2 12z"/><circle cx="12" cy="12" r="3"/></symbol>
    <symbol id="i-search" viewBox="0 0 24 24"><circle cx="10.5" cy="10.5" r="6.5"/><path d="M15.5 15.5 21 21"/></symbol>
    <symbol id="i-chip" viewBox="0 0 24 24"><rect x="6" y="6" width="12" height="12" rx="2"/><path d="M9 2v4M15 2v4M9 18v4M15 18v4M2 9h4M2 15h4M18 9h4M18 15h4"/></symbol>
    <symbol id="i-pencil" viewBox="0 0 24 24"><path d="M4 20l1-5L16 4l4 4L9 19z"/><path d="M14 6l4 4"/></symbol>
    <symbol id="i-cube" viewBox="0 0 24 24"><path d="M12 3l8 4.5v9L12 21l-8-4.5v-9z"/><path d="M12 12l8-4.5M12 12v9M12 12 4 7.5"/></symbol>
    <symbol id="i-chart" viewBox="0 0 24 24"><path d="M5 20V11M11 20V4M17 20v-6M2 20.5h20"/></symbol>
    <symbol id="i-book" viewBox="0 0 24 24"><path d="M4 5a2 2 0 0 1 2-2h13v16H6a2 2 0 0 0-2 2z"/><path d="M4 19V5M8 7h7"/></symbol>
    <symbol id="i-flask" viewBox="0 0 24 24"><path d="M9 3h6M10 3v6L4.5 19a1.5 1.5 0 0 0 1.3 2.2h12.4a1.5 1.5 0 0 0 1.3-2.2L14 9V3"/><path d="M7.5 15h9"/></symbol>
    <symbol id="i-users" viewBox="0 0 24 24"><circle cx="9" cy="8" r="3.2"/><path d="M3 20c0-3.5 2.7-6 6-6s6 2.5 6 6"/><circle cx="17" cy="9" r="2.5"/><path d="M17 14.2c2.4.2 4 2.2 4 5"/></symbol>
    <symbol id="i-check" viewBox="0 0 24 24"><path d="M4 12.5l5 5L20 6.5"/></symbol>
    <symbol id="i-copy" viewBox="0 0 24 24"><rect x="8" y="8" width="12" height="12" rx="2"/><path d="M16 8V6a2 2 0 0 0-2-2H6a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h2"/></symbol>
    <symbol id="i-info" viewBox="0 0 24 24"><circle cx="12" cy="12" r="9"/><path d="M12 11v6M12 7.5v.1"/></symbol>
    <symbol id="i-warn" viewBox="0 0 24 24"><path d="M12 3.5 22 20H2z"/><path d="M12 10v5M12 17.5v.1"/></symbol>
    <symbol id="i-bulb" viewBox="0 0 24 24"><path d="M9 18h6M10 21h4M12 3a6 6 0 0 0-3.5 10.9c.6.5 1 1.2 1 2.1h5c0-.9.4-1.6 1-2.1A6 6 0 0 0 12 3z"/></symbol>
    <symbol id="i-shield" viewBox="0 0 24 24"><path d="M12 3l8 3v6c0 4.5-3.2 7.6-8 9-4.8-1.4-8-4.5-8-9V6z"/><path d="M8.5 12l2.5 2.5 4.5-5"/></symbol>
    <symbol id="i-no" viewBox="0 0 24 24"><circle cx="12" cy="12" r="9"/><path d="M5.6 5.6l12.8 12.8"/></symbol>
    <symbol id="i-sun" viewBox="0 0 24 24"><circle cx="12" cy="12" r="4"/><path d="M12 2v3M12 19v3M2 12h3M19 12h3M5 5l2 2M17 17l2 2M19 5l-2 2M7 17l-2 2"/></symbol>
    <symbol id="i-moon" viewBox="0 0 24 24"><path d="M20 14.5A8.5 8.5 0 0 1 9.5 4a8.5 8.5 0 1 0 10.5 10.5z"/></symbol>
    <symbol id="i-arrow-r" viewBox="0 0 24 24"><path d="M4 12h15M13 6l6 6-6 6"/></symbol>
    <symbol id="i-arrow-l" viewBox="0 0 24 24"><path d="M20 12H5M11 6l-6 6 6 6"/></symbol>
    <symbol id="i-link" viewBox="0 0 24 24"><path d="M10 14a4 4 0 0 0 5.7 0l3-3a4 4 0 0 0-5.7-5.7l-1 1M14 10a4 4 0 0 0-5.7 0l-3 3a4 4 0 0 0 5.7 5.7l1-1"/></symbol>
    <symbol id="i-gauge" viewBox="0 0 40 40">
      <rect x="14" y="3" width="12" height="34" rx="3" fill="#fff" stroke="#13244A" stroke-width="2.5"/>
      <rect x="15.2" y="4.2" width="9.6" height="7.5" fill="#E5383B"/><rect x="15.2" y="11.7" width="9.6" height="7.5" fill="#F58A1F"/>
      <rect x="15.2" y="19.2" width="9.6" height="7.5" fill="#F5C400"/><rect x="15.2" y="26.7" width="9.6" height="8.1" fill="#2FBF63"/>
      <path d="M2 31c3-3 6-3 9 0s6 3 9 0 6-3 9 0 6 3 9 0v7H2z" fill="#2F93E3" stroke="#13244A" stroke-width="2" stroke-linejoin="round"/>
    </symbol>
  </defs>
</svg>

<header class="nav" id="top">
  <div class="nav-in wrap">
    <a class="brand" href="#home" data-go="home" aria-label="หน้าแรก คลังเนื้อหาและสื่อ หน่วยการเรียนรู้ฐานสมรรถนะ “ปัญญาประดิษฐ์เพื่อแก้ปัญหาภัยธรรมชาติในจังหวัดอุตรดิตถ์”">
      <svg class="brand-ic" viewBox="0 0 40 40" aria-hidden="true"><use href="#i-gauge"/></svg>
      <span class="brand-t"><b>คลังเนื้อหาและสื่อ หน่วยการเรียนรู้ฐานสมรรถนะ</b><small>“ปัญญาประดิษฐ์เพื่อแก้ปัญหาภัยธรรมชาติในจังหวัดอุตรดิตถ์”</small></span>
    </a>
    <nav class="chips" aria-label="เมนูหลัก">
      <a class="chip plain" href="#home" data-go="home">หน้าแรก</a>
      <a class="chip c1" href="#a1" data-go="a1"><i>1</i>รู้ทันภัย</a>
      <a class="chip c2" href="#a2" data-go="a2"><i>2</i>นักสืบปัญหา</a>
      <a class="chip c3" href="#a3" data-go="a3"><i>3</i>คิดเอง คิดต่อ</a>
      <a class="chip c4" href="#a4" data-go="a4"><i>4</i>สู่แบบร่าง</a>
      <a class="chip c5" href="#a5" data-go="a5"><i>5</i>ลงมือสร้าง</a>
      <a class="chip c6" href="#a6" data-go="a6"><i>6</i>ทดลองปรับปรุง</a>
      <a class="chip plain" href="#library" data-go="library">คลังสื่อ</a>
    </nav>
    <button class="theme-btn" id="themeBtn" type="button" aria-label="สลับโหมดสว่างและโหมดมืด"><svg class="ic" id="themeIc" aria-hidden="true"><use href="#i-moon"/></svg></button>
  </div>
</header>

<main id="main">

<!-- ====================== HOME ====================== -->
<section class="view" id="v-home" data-view="home">
  <div class="hero">
    <div class="wrap hero-in">
      <div>
        <span class="eyebrow"><svg class="ic" aria-hidden="true"><use href="#i-book"/></svg>คลังเนื้อหาและสื่อ หน่วยการเรียนรู้ฐานสมรรถนะ</span>
        <h1>“ปัญญาประดิษฐ์<wbr>เพื่อแก้ปัญหา<wbr><em>ภัยธรรมชาติ</em><wbr>ในจังหวัด<wbr>อุตรดิตถ์”</h1>
        <p class="lead">เรียนจากเหตุการณ์จริงในบ้านเรา ตั้งคำถามให้มากกว่าที่รู้ คิดเองก่อนใช้ AI แล้วลงมือสร้างต้นแบบที่ช่วยลดความเสี่ยงให้คนในชุมชน</p>
        <div class="hero-stats">
          <span class="pill fill" style="--accent:var(--a1);--accent-on:var(--a1-on)">6 ใบกิจกรรม</span>
          <span class="pill fill" style="--accent:var(--a4);--accent-on:var(--a4-on)">15 ชั่วโมง</span>
          <span class="pill fill" style="--accent:var(--a2);--accent-on:var(--a2-on)">5 ภัยให้เลือกทำ</span>
        </div>
        <div class="hero-cta">
          <a class="btn pri" href="#a1" data-go="a1">เริ่มที่ใบกิจกรรมที่ 1 <svg class="ic" aria-hidden="true"><use href="#i-arrow-r"/></svg></a>
          <a class="btn" href="#roadmap" data-scroll="roadmap">ดูเส้นทางทั้ง 6 ใบ</a>
        </div>
      </div>
      <figure style="margin:0">
        <svg class="scene" viewBox="0 0 640 440" role="img" aria-labelledby="sceneT sceneD">
          <title id="sceneT">เสาวัดน้ำระดับ 0 ถึง 3 ริมแม่น้ำ</title>
          <desc id="sceneD">ภาพประกอบหมู่บ้านริมน้ำท่ามกลางภูเขาและฝนตก มีเสาวัดน้ำแบ่งเป็นสี่ระดับ คือเขียว เหลือง ส้ม และแดง</desc>
          <rect class="s-sky" width="640" height="440"/>
          <path class="s-m1" d="M0 250 L90 150 L170 230 L270 120 L380 240 L470 160 L640 260 V440 H0Z"/>
          <path class="s-m2" d="M0 310 L110 220 L210 290 L320 210 L430 300 L560 230 L640 290 V440 H0Z"/>
          <g class="s-cloud"><ellipse cx="130" cy="84" rx="66" ry="26"/><circle cx="100" cy="68" r="26"/><circle cx="148" cy="60" r="32"/></g>
          <g class="s-cloud"><ellipse cx="400" cy="58" rx="58" ry="22"/><circle cx="378" cy="44" r="22"/><circle cx="420" cy="38" r="27"/></g>
          <g>
            <line class="rain" x1="92" y1="124" x2="86" y2="140"/><line class="rain b" x1="124" y1="130" x2="118" y2="146"/><line class="rain" x1="156" y1="124" x2="150" y2="140"/><line class="rain b" x1="188" y1="130" x2="182" y2="146"/>
            <line class="rain b" x1="372" y1="96" x2="366" y2="112"/><line class="rain" x1="404" y1="102" x2="398" y2="118"/><line class="rain b" x1="436" y1="96" x2="430" y2="112"/>
          </g>
          <g>
            <rect class="s-wall" x="170" y="296" width="120" height="86"/>
            <polygon class="s-roof" points="156,298 230,240 304,298"/>
            <rect x="214" y="330" width="32" height="52" rx="3" fill="#13244A" opacity=".85"/>
            <rect x="184" y="316" width="22" height="22" rx="3" fill="#BFE4FA" stroke="#13244A" stroke-width="3"/>
            <rect x="254" y="316" width="22" height="22" rx="3" fill="#BFE4FA" stroke="#13244A" stroke-width="3"/>
          </g>
          <path class="s-w1 wv" d="M-40 342 Q-10 326 20 342 T80 342 T140 342 T200 342 T260 342 T320 342 T380 342 T440 342 T500 342 T560 342 T620 342 T680 342 V460 H-40Z"/>
          <g>
            <rect class="s-pole" x="500" y="96" width="46" height="318" rx="8"/>
            <rect class="s-lv3" x="504" y="100" width="38" height="74"/><rect class="s-lv2" x="504" y="174" width="38" height="74"/>
            <rect class="s-lv1" x="504" y="248" width="38" height="74"/><rect class="s-lv0" x="504" y="322" width="38" height="88"/>
            <line class="s-tick" x1="496" y1="174" x2="552" y2="174"/><line class="s-tick" x1="496" y1="248" x2="552" y2="248"/><line class="s-tick" x1="496" y1="322" x2="552" y2="322"/>
            <circle class="s-chip" cx="590" cy="137" r="19"/><text class="s-num" x="590" y="144" text-anchor="middle">3</text>
            <circle class="s-chip" cx="590" cy="211" r="19"/><text class="s-num" x="590" y="218" text-anchor="middle">2</text>
            <circle class="s-chip" cx="590" cy="285" r="19"/><text class="s-num" x="590" y="292" text-anchor="middle">1</text>
            <circle class="s-chip" cx="590" cy="366" r="19"/><text class="s-num" x="590" y="373" text-anchor="middle">0</text>
          </g>
          <path class="s-w2 wv b" d="M-40 366 Q-10 350 20 366 T80 366 T140 366 T200 366 T260 366 T320 366 T380 366 T440 366 T500 366 T560 366 T620 366 T680 366 V460 H-40Z"/>
          <path class="s-w3 wv" d="M-40 392 Q-10 376 20 392 T80 392 T140 392 T200 392 T260 392 T320 392 T380 392 T440 392 T500 392 T560 392 T620 392 T680 392 V460 H-40Z"/>
        </svg>
        <figcaption class="lv-legend" aria-label="ความหมายของระดับ 0 ถึง 3">
          <span style="--lc:var(--lv0)"><i>0</i>ปกติ</span><span style="--lc:var(--lv1)"><i>1</i>เฝ้าระวัง</span><span style="--lc:var(--lv2)"><i>2</i>เตือนภัย</span><span style="--lc:var(--lv3)"><i>3</i>อันตราย</span>
        </figcaption>
      </figure>
    </div>
  </div>

  <div class="mission">
    <div class="wrap mission-in">
      <div>
        <h2>ภัยบางอย่างเราห้ามไม่ให้เกิดไม่ได้ แต่เราลดความเสี่ยงและผลกระทบได้</h2>
        <p>ถ้ารู้ว่าภัยมาจากไหน ใครเสี่ยง และเตรียมตัวถูกวิธี</p>
      </div>
      <div class="goal"><small>ภารกิจของเราตลอดหน่วย</small><b>ออกแบบนวัตกรรมที่ช่วยลดความเสี่ยงจากภัยในอุตรดิตถ์</b></div>
    </div>
  </div>

  <div class="wrap sec" id="roadmap">
    <span class="eyebrow">เส้นทางการเรียนรู้</span>
    <h2>6 ใบกิจกรรม 15 ชั่วโมง</h2>
    <p class="mute">แต่ละใบกิจกรรมเก็บหลักฐานและประเมิน 1 องค์ประกอบ จบใบกิจกรรมครูให้ระดับ 1.0–4.0 ตามเกณฑ์ ครบทั้ง 6 องค์ประกอบเมื่อจบใบที่ 6 แถบด้านล่างกว้างตามจำนวนชั่วโมง กดเพื่อเข้าไปเรียนได้เลย</p>
    <div class="hours" role="list">
      <a role="listitem" href="#a1" data-go="a1" style="flex:2 1 0;--c:var(--a1);--on:var(--a1-on)"><span class="bar">1</span><small>รู้ทันภัย<br>2 ชม.</small></a>
      <a role="listitem" href="#a2" data-go="a2" style="flex:2 1 0;--c:var(--a2);--on:var(--a2-on)"><span class="bar">2</span><small>นักสืบปัญหา<br>2 ชม.</small></a>
      <a role="listitem" href="#a3" data-go="a3" style="flex:2 1 0;--c:var(--a3);--on:var(--a3-on)"><span class="bar">3</span><small>คิดเอง คิดต่อ<br>2 ชม.</small></a>
      <a role="listitem" href="#a4" data-go="a4" style="flex:2 1 0;--c:var(--a4);--on:var(--a4-on)"><span class="bar">4</span><small>สู่แบบร่าง<br>2 ชม.</small></a>
      <a role="listitem" href="#a5" data-go="a5" style="flex:5 1 0;--c:var(--a5);--on:var(--a5-on)"><span class="bar">5</span><small>ลงมือสร้างนวัตกรรม<br>5 ชม. (นานที่สุด)</small></a>
      <a role="listitem" href="#a6" data-go="a6" style="flex:2 1 0;--c:var(--a6);--on:var(--a6-on)"><span class="bar">6</span><small>ทดลองปรับปรุง<br>2 ชม.</small></a>
    </div>

    <div class="rm" style="margin-top:28px">
      <article class="card rm-card k1">
        <div class="rm-top"><span class="rm-n">1</span><div><small>ขั้นที่ 1 · 2 ชั่วโมง</small><h3>รู้ทันภัย มองปัญหาให้รอบด้าน</h3></div></div>
        <div class="rm-body">
          <dl><dt>ทำความเข้าใจบริบทและปัญหา</dt><dd>ได้ตารางข้อมูลจากแหล่งที่เชื่อถือได้ คำถามสำรวจ และความเชื่อเดิมที่ตรวจกับหลักฐานแล้ว</dd>
          <dt>ฝึกทักษะ</dt><dd>การเปิดรับและกล้าสำรวจสิ่งใหม่ (ความอยากรู้อยากเห็น · การท้าทายกรอบเดิม)</dd></dl>
          <div class="rm-foot"><span class="prog" data-prog="a1"></span><span style="display:flex;gap:8px;flex-wrap:wrap"><a class="btn sm" href="https://docs.google.com/presentation/d/1vhciPrapLk9oh_oYDUTMStihTT1Y-jvbPfN-xQLTPPk/edit?usp=sharing" target="_blank" rel="noopener">ใบกิจกรรม <svg class="ic" aria-hidden="true"><use href="#i-link"/></svg></a><a class="btn sm" href="#a1" data-go="a1">เข้าเรียน <svg class="ic" aria-hidden="true"><use href="#i-arrow-r"/></svg></a></span></div>
        </div>
      </article>
      <article class="card rm-card k2">
        <div class="rm-top"><span class="rm-n">2</span><div><small>ขั้นที่ 2 · 2 ชั่วโมง</small><h3>นักสืบปัญหา ภัยธรรมชาติ</h3></div></div>
        <div class="rm-body">
          <dl><dt>กำหนดและวิเคราะห์ปัญหา</dt><dd>ได้ข้อความกำหนดปัญหาที่เจาะจง และโจทย์ “เราจะ…ได้อย่างไร” ที่ปรับกรอบแล้ว</dd>
          <dt>ฝึกทักษะ</dt><dd>การสร้างความคิด (การกำหนดปัญหา · การสร้างความคิด · การสืบค้นเชิงสร้างสรรค์)</dd></dl>
          <div class="rm-foot"><span class="prog" data-prog="a2"></span><span style="display:flex;gap:8px;flex-wrap:wrap"><a class="btn sm" href="https://docs.google.com/presentation/d/1YeYSp4px4QHdu0ttfVBTDI7DWZmeLslWcc_OnfwDT8k/edit?usp=sharing" target="_blank" rel="noopener">ใบกิจกรรม <svg class="ic" aria-hidden="true"><use href="#i-link"/></svg></a><a class="btn sm" href="#a2" data-go="a2">เข้าเรียน <svg class="ic" aria-hidden="true"><use href="#i-arrow-r"/></svg></a></span></div>
        </div>
      </article>
      <article class="card rm-card k3">
        <div class="rm-top"><span class="rm-n">3</span><div><small>ขั้นที่ 3 · 2 ชั่วโมง</small><h3>คิดเอง คิดต่อกับ AI</h3></div></div>
        <div class="rm-body">
          <dl><dt>สร้างและขยายแนวคิดด้วย AI</dt><dd>ได้บัตรคิดเองรายบุคคล 3 แนวทาง และ 3 แนวคิดของกลุ่มที่ต่างกันจริง</dd>
          <dt>ฝึกทักษะ</dt><dd>การทำงานสร้างสรรค์ร่วมกับผู้อื่น (เปรียบเทียบ → ผสมผสาน → ต่อยอด → สังเคราะห์)</dd></dl>
          <div class="rm-foot"><span class="prog" data-prog="a3"></span><span style="display:flex;gap:8px;flex-wrap:wrap"><a class="btn sm" href="https://docs.google.com/presentation/d/1nGmlRU-OQAzPuQfKEztlUfbBJiyiDQsMnWyHxpwdaSo/edit?usp=sharing" target="_blank" rel="noopener">ใบกิจกรรม <svg class="ic" aria-hidden="true"><use href="#i-link"/></svg></a><a class="btn sm" href="#a3" data-go="a3">เข้าเรียน <svg class="ic" aria-hidden="true"><use href="#i-arrow-r"/></svg></a></span></div>
        </div>
      </article>
      <article class="card rm-card k4">
        <div class="rm-top"><span class="rm-n">4</span><div><small>ขั้นที่ 4 · 2 ชั่วโมง</small><h3>แนวคิดสู่แบบร่าง</h3></div></div>
        <div class="rm-body">
          <dl><dt>คัดเลือกและออกแบบแนวทางแก้ปัญหา</dt><dd>ได้ภาพร่างรุ่นที่ 1 และ 2 ที่เพื่อนกลุ่มอื่นอ่านแล้วรู้ว่าต้องสร้างอะไร</dd>
          <dt>ฝึกทักษะ</dt><dd>การออกแบบและปรับปรุงความคิด (การขยายความคิด · การทำซ้ำและปรับปรุง)</dd></dl>
          <div class="rm-foot"><span class="prog" data-prog="a4"></span><span style="display:flex;gap:8px;flex-wrap:wrap"><a class="btn sm" href="https://docs.google.com/presentation/d/1_kx4cvHE5S5yw-BHe1bPOHeqcBseit2YTYCW5HB4hK0/edit?usp=sharing" target="_blank" rel="noopener">ใบกิจกรรม <svg class="ic" aria-hidden="true"><use href="#i-link"/></svg></a><a class="btn sm" href="#a4" data-go="a4">เข้าเรียน <svg class="ic" aria-hidden="true"><use href="#i-arrow-r"/></svg></a></span></div>
        </div>
      </article>
      <article class="card rm-card k5">
        <div class="rm-top"><span class="rm-n">5</span><div><small>ขั้นที่ 5 · 5 ชั่วโมง</small><h3>ลงมือสร้างนวัตกรรม</h3></div></div>
        <div class="rm-body">
          <dl><dt>สร้างและพัฒนาต้นแบบด้วย AI</dt><dd>ได้ต้นแบบจำลองที่สาธิตได้ พร้อมบันทึกการสร้าง อุปสรรค และการใช้ AI</dd>
          <dt>ฝึกทักษะ</dt><dd>การสร้างสรรค์ผลงานและนวัตกรรม (กลุ่มเป้าหมาย · การใช้ทรัพยากร · การวางแผน · การผลิต)</dd></dl>
          <div class="rm-foot"><span class="prog" data-prog="a5"></span><span style="display:flex;gap:8px;flex-wrap:wrap"><a class="btn sm" href="https://docs.google.com/presentation/d/1oWbI54viUfUxMA3K5ywsokKSPJIjBtIIfMMG8mxP33Q/edit?usp=sharing" target="_blank" rel="noopener">ใบกิจกรรม <svg class="ic" aria-hidden="true"><use href="#i-link"/></svg></a><a class="btn sm" href="#a5" data-go="a5">เข้าเรียน <svg class="ic" aria-hidden="true"><use href="#i-arrow-r"/></svg></a></span></div>
        </div>
      </article>
      <article class="card rm-card k6">
        <div class="rm-top"><span class="rm-n">6</span><div><small>ขั้นที่ 6 · 2 ชั่วโมง</small><h3>ทดลองปรับปรุง</h3></div></div>
        <div class="rm-body">
          <dl><dt>ทดสอบ ประเมิน ปรับปรุง และสะท้อนผล</dt><dd>ได้ผลทดสอบ 2 รอบเทียบกับเกณฑ์ที่ตั้งไว้ก่อน และการสะท้อนคิดจากหลักฐาน</dd>
          <dt>ฝึกทักษะ</dt><dd>การกำกับตนเองและการสะท้อนคิด (การสะท้อนคิด · การวางแผน · กรอบความคิด)</dd></dl>
          <div class="rm-foot"><span class="prog" data-prog="a6"></span><span style="display:flex;gap:8px;flex-wrap:wrap"><a class="btn sm" href="https://docs.google.com/presentation/d/1aDtDVsUYh00QO1QMOxUxrfpQNuwiddnR0rajAUyevjU/edit?usp=sharing" target="_blank" rel="noopener">ใบกิจกรรม <svg class="ic" aria-hidden="true"><use href="#i-link"/></svg></a><a class="btn sm" href="#a6" data-go="a6">เข้าเรียน <svg class="ic" aria-hidden="true"><use href="#i-arrow-r"/></svg></a></span></div>
        </div>
      </article>
    </div>
  </div>

  <div class="wrap sec" style="padding-top:0">
    <span class="eyebrow">วิธีใช้เว็บไซต์นี้</span>
    <h2>ทุกใบกิจกรรมมี 4 แท็บ</h2>
    <div class="grid g4" style="margin-top:14px">
      <div class="card"><h4><svg class="ic" aria-hidden="true"><use href="#i-book"/></svg> เรียนรู้</h4><p class="sm" style="margin:0">สรุปเนื้อหาและวิธีคิดของใบกิจกรรมนั้น มีให้ลองตอบก่อนดูเฉลย</p></div>
      <div class="card"><h4><svg class="ic" aria-hidden="true"><use href="#i-search"/></svg> ตัวอย่างละเอียด</h4><p class="sm" style="margin:0">ดูว่า “ทีมยามน้ำ” กรอกใบกิจกรรมทีละส่วนอย่างไร พร้อมข้อสังเกตว่าทำไมจึงดี</p></div>
      <div class="card"><h4><svg class="ic" aria-hidden="true"><use href="#i-users"/></svg> ตัวอย่างละเอียดอีก 4 ภัย</h4><p class="sm" style="margin:0">ภัยแล้ง ไฟป่า/หมอกควัน วาตภัย ดินถล่ม เลือกภัยที่สนใจเพื่อดูคำตอบตัวอย่างครบทุกใบกิจกรรม</p></div>
      <div class="card"><h4><svg class="ic" aria-hidden="true"><use href="#i-check"/></svg> เกณฑ์และเช็กลิสต์</h4><p class="sm" style="margin:0">รู้ก่อนว่าครูดูอะไร ระดับ 1.0 ถึง 4.0 ต่างกันอย่างไร แล้วติ๊กเช็กลิสต์ก่อนส่งงาน</p></div>
    </div>
  </div>

  <div class="wrap sec" style="padding-top:0">
    <span class="eyebrow">ตัวอย่างหลักตลอดหน่วย</span>
    <h2>เรื่องของ “ทีมยามน้ำ”</h2>
    <p class="mute">ทีมสมมติ (นักเรียน ก ข ค ง) เลือกภัยน้ำท่วม/น้ำป่า แล้วทำต่อเนื่องตั้งแต่ใบกิจกรรมที่ 1 ถึง 6 จนได้ต้นแบบชื่อ “เพื่อนบ้านเตือนภัย” อ่านเรื่องย่อนี้ก่อน แล้วไปดูรายละเอียดในแท็บ “ตัวอย่างละเอียด” ของแต่ละใบ</p>
    <div class="story" style="margin-top:14px">
      <div class="st k1"><h4><i>1</i>อ่านข่าวจริง เลือกผู้ใช้</h4><p>อ่านข่าวน้ำป่าที่ฟากท่า (2568) ลับแล (2567) และน้ำปาด (2554) แล้วเลือกกลุ่มเป้าหมายหลักคือผู้สูงอายุที่อยู่คนเดียวและผู้ป่วยติดเตียงในหมู่บ้านริมลำห้วย</p></div>
      <div class="st k2"><h4><i>2</i>กำหนดปัญหา</h4><p>ปัญหาคือไม่ได้รับคำเตือนน้ำป่าทันเวลา โดยเฉพาะกลางคืนที่ไฟดับและไม่มีอินเทอร์เน็ต โจทย์แรก “ทำแอปเตือนน้ำท่วม” ถูกปรับเป็นสถานีเตือนหลายช่องทาง</p></div>
      <div class="st k3"><h4><i>3</i>คิดเอง คิดต่อกับ AI</h4><p>ได้ 3 แนวคิดที่ต่างกันจริง คือสถานีวัดน้ำพร้อมแจ้งเตือนมือถือ ไซเรนและไฟ 3 สีประจำหมู่บ้าน และเพื่อนบ้านดูแลกันพร้อมจุดนัดพบ</p></div>
      <div class="st k4"><h4><i>4</i>ร่างแบบ 2 รุ่น</h4><p>เลือกแนวคิดที่ 1 เป็นแกน รวมส่วนเตือนในพื้นที่ของแนวคิดที่ 2 แล้วร่างรุ่นที่ 2 เพิ่มข้อความ “สิ่งที่ควรทำ” พาวเวอร์แบงก์ที่ไซเรน สถานะ “ไม่มีข้อมูล” และรายชื่อหลัง PIN</p></div>
      <div class="st k5"><h4><i>5</i>สร้างต้นแบบ</h4><p>สร้าง “เพื่อนบ้านเตือนภัย” ด้วยบอร์ด IPST-WiFi เซนเซอร์วัดระยะ ไฟ 3 สี และเว็บแอป ทดสอบกับถังน้ำใสบนโต๊ะ ใช้ไฟ 5 V จากพาวเวอร์แบงก์</p></div>
      <div class="st k6"><h4><i>6</i>ทดสอบ 2 รอบ</h4><p>ตั้งเกณฑ์ก่อนทดสอบ ปิด Wi-Fi และปิดไฟห้องแทนเหตุการณ์จริง พบว่าข้อความต้องขึ้นต้นด้วยสิ่งที่ต้องทำ และสรุปว่ายังไม่ควรใช้จริงจนกว่าจะได้เกณฑ์จากท้องถิ่น</p></div>
    </div>
  </div>

  <div class="wrap sec" style="padding-top:0">
    <span class="eyebrow">กติกาของนักสร้างนวัตกรรม</span>
    <h2>4 ข้อที่ใช้ทุกใบกิจกรรม</h2>
    <div class="grid g4" style="margin-top:14px">
      <div class="card" style="--c:var(--a3)"><h4><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg> คิดเองก่อนเปิด AI</h4><p class="sm" style="margin:0">ทุกคนเขียนความคิดของตัวเองก่อน แล้วใช้ AI เป็นแหล่งเสนอเพิ่ม คนในกลุ่มเป็นผู้ตรวจและเลือก</p></div>
      <div class="card"><h4><svg class="ic" aria-hidden="true"><use href="#i-search"/></svg> ตรวจหลักฐานก่อนเชื่อ</h4><p class="sm" style="margin:0">ถามว่าใครเผยแพร่ อัปเดตเมื่อไร และมีที่อื่นบอกตรงกันไหม ถ้าตอบไม่ได้สักข้อ แปลว่ายังเชื่อไม่ได้</p></div>
      <div class="card"><h4><svg class="ic" aria-hidden="true"><use href="#i-shield"/></svg> ปลอดภัยก่อนลงมือ</h4><p class="sm" style="margin:0">ไม่ทดลองในภัยจริง ใช้ไฟ 5 V จากพาวเวอร์แบงก์ ไม่ใช้ไฟบ้าน และไม่ใส่ข้อมูลส่วนบุคคลของใครลงในระบบหรือคำสั่ง AI</p></div>
      <div class="card"><h4><svg class="ic" aria-hidden="true"><use href="#i-warn"/></svg> ต้นแบบของเราไม่ใช่ระบบทางการ</h4><p class="sm" style="margin:0">ใช้เสริมการเตือนของหน่วยงาน ไม่ใช่แทนที่ ในเหตุฉุกเฉินให้ฟังประกาศของ ปภ. สายด่วน <span class="nb">1784</span></p></div>
    </div>
    <div class="callout warn" style="margin-top:18px"><svg class="ic" aria-hidden="true"><use href="#i-info"/></svg><div><h5>ตัวอย่างในเว็บนี้ใช้เพื่อเรียนรู้ ไม่ใช่เฉลย</h5><p>ชื่อนวัตกรรม ตัวเลขเกณฑ์ระดับ ผลทดสอบ และคำตอบย่อในตัวอย่างเป็นข้อมูลสมมติ (ป้าย <span class="tag-sim">สมมติ</span>) ไม่ใช่ผลวัดจริงหรือเกณฑ์ทางการ ให้ใช้เป็นแนวทางว่า “เขียนอย่างไรให้ชัด” แล้วคิดและเขียนจากข้อมูลของกลุ่มตัวเอง ห้ามคัดลอก</p></div></div>
  </div>
</section>
<!-- ====================== ACTIVITY 1 ====================== -->
<section class="view k1" id="v-a1" data-view="a1" hidden>
  <div class="ah k1">
    <div class="wrap ah-in">
      <div class="ah-num" aria-hidden="true">1</div>
      <div>
        <p class="stage">ขั้นที่ 1 · การทำความเข้าใจบริบทและปัญหา</p>
        <h1>รู้ทันภัย<wbr> มองปัญหา<wbr>ให้รอบด้าน</h1>
        <p class="mission-line">เลือกภัยที่เกิดจริงในอุตรดิตถ์ สืบค้นจากแหล่งที่เชื่อถือได้ ตั้งคำถามให้มากกว่าที่รู้ และกล้าตรวจสิ่งที่เคยเชื่อ ก่อนเสนอวิธีแก้</p>
        <div class="pills">
          <span class="pill">2 ชั่วโมง</span>
          <span class="pill">ประเมิน องค์ประกอบที่ 3 การเปิดรับและกล้าสำรวจสิ่งใหม่</span>
          <span class="pill">ความอยากรู้อยากเห็น · การท้าทายกรอบเดิม</span>
        </div>
        <p style="margin:14px 0 0"><a class="btn" href="https://docs.google.com/presentation/d/1vhciPrapLk9oh_oYDUTMStihTT1Y-jvbPfN-xQLTPPk/edit?usp=sharing" target="_blank" rel="noopener">เปิดใบกิจกรรมที่ 1 (Google Slides) <svg class="ic" aria-hidden="true"><use href="#i-link"/></svg></a></p>
      </div>
    </div>
  </div>

  <div class="wrap">
    <div class="tabs" role="tablist" aria-label="เมนูย่อยของใบกิจกรรมที่ 1">
      <button type="button" class="tab" role="tab" id="t-a1-learn" aria-controls="p-a1-learn" aria-selected="true" data-go="a1"><svg class="ic" aria-hidden="true"><use href="#i-book"/></svg>เรียนรู้</button>
      <button type="button" class="tab" role="tab" id="t-a1-ex" aria-controls="p-a1-ex" aria-selected="false" data-go="a1-ex"><svg class="ic" aria-hidden="true"><use href="#i-search"/></svg>ตัวอย่างละเอียด</button>
      <button type="button" class="tab" role="tab" id="t-a1-hz" aria-controls="p-a1-hz" aria-selected="false" data-go="a1-hz"><svg class="ic" aria-hidden="true"><use href="#i-users"/></svg>ตัวอย่าง 4 ภัยอื่น</button>
      <button type="button" class="tab" role="tab" id="t-a1-rub" aria-controls="p-a1-rub" aria-selected="false" data-go="a1-rub"><svg class="ic" aria-hidden="true"><use href="#i-check"/></svg>เกณฑ์และเช็กลิสต์</button>
    </div>

    <!-- ---------- A1 : LEARN ---------- -->
    <div class="panel" role="tabpanel" id="p-a1-learn" aria-labelledby="t-a1-learn">
      <div class="stack">
        <div class="card">
          <p class="lede">ชั่วโมงแรกเราเป็นนักสืบก่อน ต้องรู้จักภัยให้จริง <b>ไม่เดา</b> และ<b>ไม่เชื่อทุกอย่างที่เห็นในมือถือ</b></p>
          <div class="flowline" style="margin-top:6px">
            <span class="pill fill" style="--accent:var(--a1);--accent-on:var(--a1-on)">ตั้งคำถามให้มากกว่าที่รู้</span>
            <span class="pill fill" style="--accent:var(--a1);--accent-on:var(--a1-on)">ตรวจหลักฐานก่อนเชื่อ</span>
            <span class="pill fill" style="--accent:var(--a1);--accent-on:var(--a1-on)">ปลอดภัยก่อนลงมือ</span>
          </div>
        </div>


        <ul class="toc" aria-label="หัวข้อในแท็บนี้">
          <li><a href="#" data-scroll="a1-l1"><i>1</i>ภัยกับภัยพิบัติ</a></li>
          <li><a href="#" data-scroll="a1-l2"><i>2</i>อ่านข่าวจริง</a></li>
          <li><a href="#" data-scroll="a1-l3"><i>3</i>ตรวจก่อนเชื่อ</a></li>
          <li><a href="#" data-scroll="a1-l4"><i>4</i>ใครเสี่ยงอย่างไร</a></li>
          <li><a href="#" data-scroll="a1-l5"><i>5</i>รู้ ไม่รู้ ต้องหาต่อ</a></li>
          <li><a href="#" data-scroll="a1-l6"><i>6</i>ท้าทายสิ่งที่เคยเชื่อ</a></li>
        </ul>

        <!-- 1 -->
        <div class="blk" id="a1-l1">
          <h3><span class="num-dot">1</span>ภัยธรรมชาติ กับ ภัยพิบัติ ต่างกันอย่างไร</h3>
          <div class="grid g2">
            <div class="card"><h4>ภัยธรรมชาติ</h4><p class="sm" style="margin:0">เหตุการณ์หรือปรากฏการณ์ที่เกิดขึ้นเองตามธรรมชาติ ซึ่งมีศักยภาพหรือแนวโน้มที่จะก่อให้เกิดอันตราย</p></div>
            <div class="card"><h4>ภัยพิบัติ</h4><p class="sm" style="margin:0">ภัยอันตรายหรือเหตุการณ์ร้ายแรงที่เกิดขึ้นแล้ว ส่งผลกระทบอย่างรุนแรงต่อสังคม ชุมชน หรือชีวิตและทรัพย์สินของมนุษย์เป็นวงกว้าง</p></div>
          </div>
          <div class="quiz" data-quiz="b">
            <h5><span class="pill">ลองตอบ</span> ข้อใดคือ “ภัยพิบัติ” ที่เกิดขึ้นแล้ว</h5>
            <div class="opts">
              <button type="button" class="opt" data-k="a"><span class="k">ก</span><span>ฝนตกหนักบนภูเขาทางตอนบนของจังหวัด</span></button>
              <button type="button" class="opt" data-k="b"><span class="k">ข</span><span>น้ำป่าไหลเข้าหมู่บ้าน ถนนขาด บ้านจมน้ำ และมีผู้ติดค้างรอความช่วยเหลือ</span></button>
              <button type="button" class="opt" data-k="c"><span class="k">ค</span><span>พยากรณ์อากาศบอกว่าสัปดาห์หน้าอาจมีฝนมาก</span></button>
            </div>
            <div class="fb" hidden><b class="fb-h"></b><p>ข้อ ข เป็นเหตุการณ์ร้ายแรงที่เกิดแล้วและกระทบชุมชนเป็นวงกว้าง ส่วนข้อ ก คือปรากฏการณ์ธรรมชาติ และข้อ ค ยังเป็นการคาดการณ์ ยังไม่เกิดผลกระทบ</p></div>
          </div>
        </div>

        <!-- 2 -->
        <div class="blk" id="a1-l2">
          <h3><span class="num-dot">2</span>อ่านข่าวจริง 2 เหตุการณ์ในอุตรดิตถ์</h3>
          <p class="mute">ข้อมูลตัวอย่างสำหรับฝึกถามก่อน แล้วจึงไปค้นข้อมูลของภัยที่กลุ่มเลือก</p>
          <div class="grid g2">
            <article class="card">
              <span class="pill fill" style="--accent:var(--a5);--accent-on:var(--a5-on)">เหตุการณ์ A · 22 ส.ค. 2563</span>
              <h4 style="margin-top:10px">น้ำป่าลงคลองสิงห์ อ.ท่าปลา</h4>
              <ul class="sm">
                <li>น้ำป่าจากภูเขาสูงใน อ.ท่าปลาไหลลงคลองสิงห์ ระดับน้ำเพิ่มเร็ว</li>
                <li>กระทบ อ.ท่าปลา 5 ตำบล และ อ.เมือง 2 ตำบล ถนนอุตรดิตถ์–เขื่อนสิริกิติ์ที่ ต.หาดงิ้ว ถูกน้ำท่วม</li>
                <li>น้ำสูงกว่า 2 เมตร บ้านชั้นเดียวบางหลังจมเกือบถึงหลังคา ชาวบ้านขึ้นไปอยู่บนหลังคาพร้อมสัตว์เลี้ยง</li>
                <li>อาสาสมัครกู้ภัยใช้เรือท้องแบนช่วยผู้สูงอายุและผู้ป่วยติดเตียง</li>
                <li>ฟาร์มหมูใน ต.หาดงิ้วถูกน้ำท่วม 3 โรงเรือน (หมูกว่า 1,500 ตัว)</li>
              </ul>
            </article>
            <article class="card">
              <span class="pill fill" style="--accent:var(--a4);--accent-on:var(--a4-on)">เหตุการณ์ B · 1–3 ต.ค. 2567</span>
              <h4 style="margin-top:10px">ฝนหนัก ดินสไลด์ และพายุลมแรง</h4>
              <ul class="sm">
                <li>ฝนตกหนักสะสมตั้งแต่ 1 ต.ค. ทำให้เกิดดินสไลด์ที่ถนนบ้านน้ำหมัน–บ้านผาแก่น (อ.ท่าปลา) และถนน 3 จุดใน ต.นานกก (อ.ลับแล)</li>
                <li>น้ำป่าท่วมบ้านที่อยู่ใกล้ลำน้ำ เสาไฟฟ้าหักล้ม ไฟดับ และสัญญาณโทรศัพท์ใช้งานไม่ได้</li>
                <li>ชาวสวนลองกองลำเลียงผลผลิตออกสู่ตลาดไม่ได้เพราะถนนทรุดและขาด</li>
                <li>มีเกษตรกร 1 รายได้รับอันตรายจากต้นไม้ล้ม</li>
              </ul>
            </article>
          </div>
          <div class="callout note"><svg class="ic" aria-hidden="true"><use href="#i-info"/></svg><div><h5>ลองตอบ 5 ข้อนี้ก่อนดูแนวตอบ</h5>
            <ol style="margin:.3em 0 0"><li>เกิดอะไรขึ้น</li><li>เกิดจากอะไร</li><li>ใครได้รับผลกระทบ</li><li>ผลกระทบมีอะไรบ้าง</li><li>ถ้าเกิดใกล้บ้านหรือโรงเรียนเรา จะเป็นอย่างไร</li></ol>
            <p style="margin:.7em 0 0"><button type="button" class="btn sm" data-reveal="a1-r2" aria-expanded="false" aria-controls="a1-r2">ดูแนวตอบและคำถามต่อยอด</button></p></div></div>
          <div class="reveal-box" id="a1-r2" hidden>
            <div class="tbl tight"><table>
              <thead><tr><th>คำถาม</th><th>แนวตอบตัวอย่าง</th><th>ถามต่อ</th></tr></thead>
              <tbody>
                <tr><td>เกิดอะไรขึ้น</td><td>A: น้ำป่าลงคลองสิงห์ท่วมบ้านและตัดถนนสายหลัก · B: ฝนสะสมทำให้ดินสไลด์ ถนนขาด ไฟดับ</td><td>ข่าวบอกวันที่และสถานที่ชัดไหม</td></tr>
                <tr><td>เกิดจากอะไร</td><td>ฝนตกหนักต่อเนื่อง น้ำไหลลงจากภูเขา ดินอิ่มน้ำ ลมพายุ</td><td>ธรรมชาติทำอะไร และอะไรในชุมชนทำให้หนักขึ้น</td></tr>
                <tr><td>ใครได้รับผลกระทบ</td><td>ชาวบ้านริมลำน้ำ ผู้สูงอายุ ผู้ป่วยติดเตียง เกษตรกร คนงานฟาร์ม คนที่ต้องใช้ถนน</td><td>มีใครที่ข่าวไม่ได้พูดถึงไหม</td></tr>
                <tr><td>ผลกระทบมีอะไรบ้าง</td><td>บ้านจมน้ำ ถนนขาด ไฟดับ สัญญาณหาย ขายผลผลิตไม่ได้ ต้องขอความช่วยเหลือ</td><td>อะไรเกิดทันที อะไรตามมาทีหลัง</td></tr>
                <tr><td>ถ้าเกิดใกล้บ้านหรือโรงเรียนเรา</td><td>ทางกลับบ้านถูกตัด รับข่าวไม่ได้ถ้าไฟดับ ผู้ปกครองรับนักเรียนไม่ได้ ผู้สูงอายุที่บ้านอยู่คนเดียว</td><td>เรามีช่องทางรับข่าวอะไรที่ใช้ได้เมื่อไฟดับ</td></tr>
              </tbody>
            </table></div>
            <p class="sm" style="margin:10px 0 0">สังเกตว่าทุกข้อมี “ถามต่อ” เสมอ นักสืบที่ดีไม่หยุดที่คำตอบแรก</p>
          </div>
        </div>

        <!-- 3 -->
        <div class="blk" id="a1-l3">
          <h3><span class="num-dot">3</span>ตรวจข้อมูลก่อนเชื่อ ก่อนส่งต่อ</h3>
          <blockquote class="quote" style="font-weight:600;border-width:var(--bw)">“ด่วน! พรุ่งนี้ตี 2 น้ำป่าจะถล่มเมืองลับแล ให้อพยพทันที ส่งต่อด่วน”<br><span class="sm mute" style="font-weight:400">ข้อความตัวอย่าง เพื่อฝึกตรวจ ไม่ใช่ประกาศจริง</span></blockquote>
          <div class="grid g3">
            <div class="card flat"><h4><span class="num-dot">1</span> ใครเผยแพร่?</h4><p class="sm" style="margin:0">เป็นหน่วยงานที่รับผิดชอบ หรือเป็นข้อความส่งต่อที่ไม่รู้ที่มา</p></div>
            <div class="card flat"><h4><span class="num-dot">2</span> อัปเดตเมื่อไร?</h4><p class="sm" style="margin:0">เป็นข้อมูลล่าสุดหรือข่าวเก่าที่ถูกแชร์ซ้ำ</p></div>
            <div class="card flat"><h4><span class="num-dot">3</span> มีที่อื่นบอกตรงกันไหม?</h4><p class="sm" style="margin:0">เทียบกับประกาศของ ปภ. กรมอุตุนิยมวิทยา หรือท้องถิ่น</p></div>
          </div>
          <div class="callout warn"><svg class="ic" aria-hidden="true"><use href="#i-warn"/></svg><div><p><b>ถ้าตอบไม่ได้สักข้อ แปลว่ายังเชื่อไม่ได้</b> แต่ไม่ได้แปลว่าเรานิ่งเฉย ให้ไปถามหน่วยงานที่รับผิดชอบ เช่น ปภ. จังหวัด (สายด่วน <span class="nb">1784</span>) หรือ อบต. ในพื้นที่</p></div></div>
          <div class="quiz" data-quiz="c">
            <h5><span class="pill">ลองตอบ</span> เพื่อนส่งข้อความด่วนข้างบนมาในไลน์กลุ่ม ควรทำอะไรก่อน</h5>
            <div class="opts">
              <button type="button" class="opt" data-k="a"><span class="k">ก</span><span>กดส่งต่อให้ทุกกลุ่มทันที เผื่อมีคนช่วยได้ทัน</span></button>
              <button type="button" class="opt" data-k="b"><span class="k">ข</span><span>เมินไป เพราะข่าวปลอมมีเยอะ</span></button>
              <button type="button" class="opt" data-k="c"><span class="k">ค</span><span>ถามว่าใครเผยแพร่ ข้อความอัปเดตเมื่อไร แล้วเทียบกับประกาศของหน่วยงานทางการ</span></button>
            </div>
            <div class="fb" hidden><b class="fb-h"></b><p>ข้อ ค คือวิธีที่ถูก ส่งต่อทันทีอาจทำให้คนตื่นตระหนกหรืออพยพผิดทาง ส่วนการเมินก็เสี่ยงเพราะถ้าเป็นข่าวจริงเราจะเพิกเฉยต่อภัย</p></div>
          </div>
        </div>

        <!-- 4 -->
        <div class="blk" id="a1-l4">
          <h3><span class="num-dot">4</span>ภัยเดียวกัน ผลกระทบไม่เท่ากัน</h3>
          <div class="card soft">
            <p style="margin:0">คืนหนึ่งฝนตกหนักต่อเนื่องหลายชั่วโมง คุณยายคนหนึ่งอยู่บ้านลำพังริมลำห้วย ลูกหลานทำงานต่างจังหวัด ไฟฟ้าดับ สัญญาณอินเทอร์เน็ตหายไป โทรศัพท์ปุ่มกดแบตเตอรี่เหลือน้อย ข้างนอกมืดและได้ยินเสียงน้ำดังขึ้นเรื่อย ๆ คุณยายไม่แน่ใจว่าควรรอดูสถานการณ์ต่อ หรือควรออกจากบ้านตอนนี้</p>
            <p class="sm mute" style="margin:.7em 0 0"><b>คำถาม:</b> ใครน่าจะลำบากที่สุด เพราะอะไร</p>
          </div>
          <div class="grid g3">
            <div class="card"><h4>ผู้ป่วยติดเตียง</h4><dl class="kv"><dt>ความเสี่ยง</dt><dd>เคลื่อนย้ายเองไม่ได้ ต้องใช้ไฟฟ้าหรือเครื่องมือ</dd><dt>ความต้องการสำคัญ</dt><dd>ผู้ช่วยเคลื่อนย้าย แหล่งไฟสำรอง ช่องทางติดต่อฉุกเฉิน</dd></dl></div>
            <div class="card"><h4>เด็กเล็ก</h4><dl class="kv"><dt>ความเสี่ยง</dt><dd>ตัดสินใจเองไม่ได้ เดินทางไกลไม่ได้ ตื่นกลัว</dd><dt>ความต้องการสำคัญ</dt><dd>คนดูแลอยู่ด้วย ข้อมูลที่เข้าใจง่าย ที่พักปลอดภัย</dd></dl></div>
            <div class="card"><h4>เกษตรกรและชาวสวน</h4><dl class="kv"><dt>ความเสี่ยง</dt><dd>ผลผลิตและเครื่องมือเสียหาย ขนส่งออกตลาดไม่ได้เมื่อถนนขาด</dd><dt>ความต้องการสำคัญ</dt><dd>ข้อมูลเตือนล่วงหน้าเพื่อเก็บผลผลิต เส้นทางสำรอง</dd></dl></div>
          </div>
          <div class="callout idea"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><h5>ข้อ 4 ในใบกิจกรรม เลือก 2 กลุ่ม</h5><p>กลุ่มแรกเลือกจากที่เราคุ้นเคย กลุ่มที่สองต้องเป็นกลุ่มที่เรามักมองข้าม จากนั้นเลือก<b>กลุ่มหลัก 1 กลุ่ม</b> พร้อมเหตุผล โดยลองถามว่า “ถ้าเราเป็นเขา เราจะรู้ข่าวเตือนจากช่องทางไหน และใช้ได้หรือไม่ถ้าไฟดับ”</p></div></div>
        </div>

        <!-- 5 -->
        <div class="blk" id="a1-l5">
          <h3><span class="num-dot">5</span>รู้แล้ว ยังไม่รู้ ต้องหาต่อ และตั้งคำถามสำรวจ</h3>
          <div class="tbl"><table>
            <thead><tr><th>สิ่งที่รู้จากหลักฐาน</th><th>สิ่งที่ยังไม่รู้</th><th>จะสืบค้นหรือถามใคร/ที่ใด</th></tr></thead>
            <tbody>
              <tr><td>น้ำสูงเกิน 2 เมตร ถนนสายหลักถูกตัด อาสาสมัครกู้ภัยใช้เรือท้องแบนช่วยผู้สูงอายุและผู้ป่วยติดเตียง (ข่าวสด)</td><td>ผู้ดูแลผู้ป่วยติดเตียงในพื้นที่ได้รับข่าวเตือนจากช่องทางใด</td><td>ถามเจ้าหน้าที่ ปภ. จังหวัด หรือ อบต. ในพื้นที่</td></tr>
              <tr><td>ไฟฟ้าดับและสัญญาณโทรศัพท์หายในเหตุการณ์ B (ไทยโพสต์)</td><td>มีแหล่งไฟสำรองสำหรับเครื่องมือแพทย์ในพื้นที่หรือไม่</td><td>สอบถามโรงพยาบาลส่งเสริมสุขภาพตำบล</td></tr>
            </tbody>
          </table></div>
          <p class="sm mute" style="margin:0">ในตัวอย่างนี้ คอลัมน์แรกต้องมีที่มา ส่วนคอลัมน์ที่สองต้องเป็นคำถามที่ยังไม่มีคำตอบจริง ๆ</p>
          <div class="grid g2">
            <div class="card"><h4>คำถามแบบ “ทำไม...?”</h4><p style="margin:0">ทำไมผู้ป่วยติดเตียงจึงเสี่ยงมากกว่าคนทั่วไปเมื่อไฟดับและถนนขาดพร้อมกัน <span class="mute sm">· สำคัญเพราะจะช่วยให้ออกแบบได้ตรงกลุ่ม</span></p></div>
            <div class="card"><h4>คำถามแบบ “ถ้า...จะเป็นอย่างไร?”</h4><p style="margin:0">ถ้าฝนตกหนักกลางคืนและครอบครัวมีเพียงโทรศัพท์ปุ่มกดที่แบตเตอรี่เหลือน้อย ผู้ดูแลจะขอความช่วยเหลือจากใครและอย่างไร</p></div>
          </div>
        </div>

        <!-- 6 -->
        <div class="blk" id="a1-l6">
          <h3><span class="num-dot">6</span>ท้าทายสิ่งที่เคยเชื่อ</h3>
          <p class="mute">เขียนสิ่งที่เราหรือคนทั่วไปเชื่อ แล้วตรวจกับหลักฐาน ถามต่อว่า “ถ้าข้อสมมตินี้ใช้ไม่ได้ จะเกิดอะไรขึ้น”</p>
          <div class="tbl"><table>
            <thead><tr><th>สิ่งที่เคยเชื่อ</th><th>ตรวจกับหลักฐาน</th><th>ถ้าข้อสมมตินี้ใช้ไม่ได้</th></tr></thead>
            <tbody>
              <tr><td>ถ้ามือถือไม่แจ้งเตือน แปลว่ายังปลอดภัย</td><td><b>ขัด</b> · เหตุการณ์ B สัญญาณโทรศัพท์หาย ไม่ได้รับข่าวเตือน</td><td>ต้องมีคนนำข่าวเตือนไปแจ้งถึงบ้าน</td></tr>
              <tr><td>ถนนที่เคยไปได้ยังไปได้เสมอ</td><td><b>ขัด</b> · ถนนถูกตัดหรือทรุดทั้งสองเหตุการณ์</td><td>ส่งผู้ป่วยไปสถานพยาบาลไม่ได้ ต้องมีเส้นทางสำรองหรือแผนล่วงหน้า</td></tr>
            </tbody>
          </table></div>
          <div class="card">
            <h4>ข้อมูลหรือมุมมองที่ไม่คุ้นเคย 1 เรื่อง</h4>
            <p style="margin:0">เกษตรกรให้ความสำคัญกับการเก็บผลผลิตล่วงหน้ามากกว่าการอพยพคน <b>ยังไม่สรุป</b> ว่าควรเตือนตามจังหวะนี้ จะตรวจโดยถามเกษตรกรหรือ อบต. ถ้าพบว่ามีความต้องการสองด้านพร้อมกัน จะเปลี่ยนเป็นออกแบบการเตือนที่มี 2 ระดับ</p>
            <p class="sm mute" style="margin:.6em 0 0">คำสำคัญ: <b>ชะลอการตัดสินและสำรวจเพิ่มอย่างไรก่อนสรุป</b></p>
          </div>
        </div>
      </div>
    </div>

    <!-- ---------- A1 : WORKED EXAMPLE ---------- -->
    <div class="panel" role="tabpanel" id="p-a1-ex" aria-labelledby="t-a1-ex" hidden>
      <div class="stack">
        <div class="card soft">
          <span class="tag-sim">ตัวอย่างเพื่อการเรียนรู้</span>
          <h3 style="margin-top:10px">ทีมยามน้ำ กรอกใบกิจกรรมที่ 1 ทีละส่วน</h3>
          <p class="mute" style="margin:0">ทีมสมมติ (นักเรียน ก ข ค ง) เลือกภัยน้ำท่วม/น้ำป่า ข้อมูลข่าวในตัวอย่างนี้ต่างจาก 2 เหตุการณ์ (A และ B) ในแท็บ “เรียนรู้” ให้ใช้เป็นแนวว่า “เขียนอย่างไรให้ชัด” แล้วค้นและเขียนจากข้อมูลของกลุ่มตัวเอง ห้ามคัดลอก</p>
        </div>
        <ul class="toc" aria-label="ส่วนของใบกิจกรรมที่ 1">
          <li><a href="#" data-scroll="a1-s1"><i>1</i>เลือกภัย</a></li>
          <li><a href="#" data-scroll="a1-s2"><i>2</i>แหล่งข้อมูล</a></li>
          <li><a href="#" data-scroll="a1-s3"><i>3</i>เหตุและผล</a></li>
          <li><a href="#" data-scroll="a1-s4"><i>4</i>ใครเสี่ยง</a></li>
          <li><a href="#" data-scroll="a1-s5"><i>5</i>รู้/ไม่รู้</a></li>
          <li><a href="#" data-scroll="a1-s6"><i>6</i>คำถาม</a></li>
          <li><a href="#" data-scroll="a1-s7"><i>7</i>ท้าทายความเชื่อ</a></li>
        </ul>

        <article class="ex" id="a1-s1">
          <header class="ex-h"><span class="num-dot">1</span><h4>เลือกภัยและระบุบริบทพื้นที่</h4></header>
          <div class="ex-b">
            <div class="ex-q"><b>ใบกิจกรรมถามว่า</b><p>ติ๊กภัยที่เลือก และเขียนบริบท: เกิดที่ไหน เมื่อใด มีเงื่อนไขอย่างไร</p></div>
            <div class="ex-a"><span class="lab">คำตอบของทีมยามน้ำ</span>
              <p><b>ภัยที่เลือก:</b> น้ำท่วม/น้ำป่า</p>
              <ul>
                <li><b>ฟากท่า 11 ก.ค. 2568:</b> ฝนตกหนักต่อเนื่อง น้ำป่าไหลหลาก ม.3 บ้านกกต้องเดือดร้อน 83 หลังคาเรือน สะพานขาด ต้องใช้เรือเร็วเข้าช่วย ส่วนบ้านบุ่ง/บ้านวังขวัญราว 120 ครัวเรือน น้ำสูงราว 1.5 เมตร</li>
                <li><b>ลับแล 3 ต.ค. 2567:</b> น้ำป่าท่วมบ้านใกล้ลำน้ำ ไฟดับ สัญญาณโทรศัพท์ใช้ไม่ได้ ต้องติดต่อกันด้วยรถจักรยานยนต์</li>
                <li><b>น้ำปาด 9 ก.ย. 2554:</b> น้ำป่าและโคลนไหลเข้าหมู่บ้านตอนตี 2</li>
              </ul>
              <p><b>เงื่อนไขที่สนใจ:</b> น้ำมาเร็ว มาตอนกลางคืน ไฟดับ ไม่มีอินเทอร์เน็ต ใช้หมู่บ้านริมลำห้วยสมมติ 1 แห่งในจังหวัดอุตรดิตถ์เป็นพื้นที่ทดลอง</p>
            </div>
            <div class="why"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><p><b>ทำไมดี:</b> บอกที่ไหน เมื่อไร และมีตัวเลขชัด (83 หลังคาเรือน, 1.5 ม.) ไม่ใช่แค่เขียนว่า “น้ำท่วม” และยังเลือก<b>เงื่อนไข</b>ที่อยากสำรวจต่อ คือกลางคืน ไฟดับ ไม่มีเน็ต</p></div></div>
          </div>
        </article>

        <article class="ex" id="a1-s2">
          <header class="ex-h"><span class="num-dot">2</span><h4>รวบรวมข้อมูลและตรวจสอบความน่าเชื่อถือ</h4></header>
          <div class="ex-b">
            <div class="ex-q"><b>ใบกิจกรรมถามว่า</b><p>แหล่งข้อมูล · ข้อมูลสำคัญที่พบ · ตรวจสอบได้อย่างไร และวันที่เข้าถึง (อย่างน้อย 3 แหล่ง)</p></div>
            <div class="ex-a"><span class="lab">คำตอบของทีมยามน้ำ</span>
              <div class="tbl"><table>
                <thead><tr><th>แหล่งข้อมูล</th><th>ข้อมูลสำคัญที่พบ</th><th>ตรวจสอบได้อย่างไร</th></tr></thead>
                <tbody>
                  <tr><td>1. สยามนิวส์ ผ่าน LINE TODAY · ข่าวน้ำป่า อ.ฟากท่า 11 ก.ค. 2568</td><td>น้ำป่าท่วมสูงราว 1.5 ม. สะพานบ้านกกต้องขาด ใช้เรืออพยพ · ปภ. ส่ง Cell Broadcast เตือนทั้งอำเภอฟากท่า</td><td>ข่าวระบุวัน พื้นที่ จำนวนครัวเรือน และหน่วยงานชัดเจน ควรเทียบกับประกาศ ปภ. · today.line.me/th/v3/article/RBX5Y9m · เข้าถึง 23 ต.ค. 2569</td></tr>
                  <tr><td>2. ไทยโพสต์ · ข่าวฝนถล่มอุตรดิตถ์ 3 ต.ค. 2567</td><td>ฝนตกหนักตั้งแต่ 1 ต.ค. ดินสไลด์ตัดถนน ต.นานกก อ.ลับแล · น้ำป่าท่วมบ้านใกล้ลำน้ำ ไฟดับ สัญญาณโทรศัพท์ใช้ไม่ได้</td><td>ข่าวระบุวันที่ชัดเจน แต่ไม่ระบุทุกจุดว่าเป็นหมู่บ้านใด ต้องหาข้อมูลเพิ่ม · thaipost.net/district-news/667660/ · เข้าถึง 23 ต.ค. 2569</td></tr>
                  <tr><td>3. ผู้จัดการออนไลน์ (MGR Online) · ข่าวน้ำป่าน้ำปาด 9 ก.ย. 2554</td><td>ฝนตกทั้งคืน ตี 2 น้ำป่าและโคลนพร้อมท่อนซุงไหลเข้า ต.น้ำไผ่ อ.น้ำปาด · หมู่บ้านต้นขนุน-ต้นเดื่อ 103 ครัวเรือน 365 คน</td><td>เป็นข่าวเก่า (พ.ศ. 2554) ใช้ดูรูปแบบเหตุการณ์ ไม่ใช้เป็นสถานการณ์ปัจจุบัน · mgronline.com/local/detail/9540000114707 · เข้าถึง 23 ต.ค. 2569</td></tr>
                </tbody>
              </table></div>
            </div>
            <div class="why"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><p><b>ทำไมดี:</b> คอลัมน์ “ตรวจสอบได้อย่างไร” ไม่ได้เขียนแค่ว่า “น่าเชื่อถือ” แต่บอกเหตุผลและ<b>ข้อจำกัด</b>ของแต่ละแหล่ง เช่น ข่าวเก่า ใช้ดูรูปแบบ ไม่ใช่สถานการณ์ตอนนี้ และมีลิงก์กับวันที่เข้าถึงให้คนอื่นตรวจซ้ำได้</p></div></div>
          </div>
        </article>

        <article class="ex" id="a1-s3">
          <header class="ex-h"><span class="num-dot">3</span><h4>มองเหตุและผลให้รอบด้าน</h4></header>
          <div class="ex-b">
            <div class="ex-q"><b>ใบกิจกรรมถามว่า</b><p>สาเหตุ/ปัจจัย อย่างน้อย 2 ข้อ และผลกระทบต่อชีวิต ทรัพย์สิน ชุมชน หรือสิ่งแวดล้อม</p></div>
            <div class="ex-a"><span class="lab">คำตอบของทีมยามน้ำ</span>
              <div class="tbl"><table>
                <thead><tr><th>สาเหตุ/ปัจจัย</th><th>ผลกระทบ</th></tr></thead>
                <tbody>
                  <tr><td>1. ฝนตกหนักต่อเนื่องหลายชั่วโมงในพื้นที่ภูเขา/ต้นน้ำ (ข่าวฟากท่า: ฝนตกต่อเนื่องตั้งแต่เย็นจนสาย)</td><td>1. บ้านเรือนถูกน้ำท่วมสูงราว 1.5 ม. สะพานและถนนขาด ต้องใช้เรือเร็วเข้าช่วย ไม่สามารถเดินทางได้</td></tr>
                  <tr><td>2. ลำห้วยแคบ พื้นที่ลาดเชิงเขา น้ำไหลลงเร็วและมีโคลน ท่อนซุง/เศษไม้ไหลมาด้วย (น้ำปาด 2554)</td><td>2. ไฟดับ สัญญาณโทรศัพท์ใช้ไม่ได้ ขอความช่วยเหลือยาก (ลับแล 2567) · ชาวสวนขนผลผลิตไปขายไม่ได้เพราะถนนขาด</td></tr>
                </tbody>
              </table></div>
            </div>
            <div class="why"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><p><b>ทำไมดี:</b> ทุกข้อมี<b>หลักฐานในวงเล็บ</b> และผลกระทบไม่ได้มีแค่ตัวบ้าน แต่รวมการสื่อสารและรายได้ของชาวสวนด้วย</p></div></div>
          </div>
        </article>

        <article class="ex" id="a1-s4">
          <header class="ex-h"><span class="num-dot">4</span><h4>ใครเสี่ยงอย่างไร? มองจากมุมผู้ได้รับผลกระทบ</h4></header>
          <div class="ex-b">
            <div class="ex-q"><b>ใบกิจกรรมถามว่า</b><p>เลือก 2 กลุ่ม (กลุ่มที่ 2 ต้องเป็นกลุ่มที่มักถูกมองข้าม) บอกความเสี่ยงและความต้องการ แล้วเลือกกลุ่มหลัก 1 กลุ่มพร้อมเหตุผล</p></div>
            <div class="ex-a"><span class="lab">คำตอบของทีมยามน้ำ</span>
              <div class="tbl"><table>
                <thead><tr><th>ผู้ได้รับผลกระทบ</th><th>ความเสี่ยง/สิ่งที่กังวล</th><th>ความต้องการที่สำคัญ</th></tr></thead>
                <tbody>
                  <tr><td>กลุ่มที่ 1: ผู้สูงอายุที่อยู่คนเดียว/ผู้ป่วยติดเตียง (กลุ่มที่นึกถึงเป็นอันดับแรก)</td><td>เคลื่อนที่ช้า ต้องใช้เปลหรือรถเข็น บางคนไม่ยอมออกเพราะห่วงทรัพย์สิน (ไทยโพสต์ 2561) · ถ้าน้ำท่วมขังก่อนจะย้ายยากขึ้น</td><td>คนมารับตั้งแต่เนิ่น ๆ ก่อนน้ำท่วมขัง · ยาประจำตัวและคนดูแลต่อเนื่อง</td></tr>
                  <tr><td>กลุ่มที่ 2: ผู้ที่ได้ยินเสียงไม่ชัด/ไม่ได้ยิน (กลุ่มที่มักถูกมองข้าม · เป็นสมมติฐาน ต้องไปถามผู้ใช้จริง)</td><td>อาจไม่ได้ยินเสียงไซเรนหรือประกาศตอนกลางคืน เสียงอย่างเดียวจึงอาจเตือนไม่ถึง</td><td>สัญญาณที่เห็นได้ เช่น ไฟกะพริบ · เพื่อนบ้านมาเคาะประตูหรือเรียกถึงตัว</td></tr>
                </tbody>
              </table></div>
              <p style="margin-top:12px"><b>กลุ่มหลัก:</b> ผู้สูงอายุที่อยู่คนเดียวและผู้ป่วยติดเตียงในหมู่บ้านริมลำห้วย</p>
              <p><b>เหตุผล:</b> ใช้เวลาอพยพนานที่สุดเพราะต้องมีเปล/รถเข็นและคนช่วย จึงต้องรู้ก่อนกลุ่มอื่น และมักไม่ได้ใช้สมาร์ตโฟนหรือกลุ่มไลน์ คนที่ช่วยเขาได้คือเพื่อนบ้านและอาสาสมัคร ต้นแบบจึงต้องเตือน “คนช่วย” ด้วย ส่วนกลุ่มที่ 2 ใช้เป็นผู้ใช้อื่นที่ต้องดูแล</p>
            </div>
            <div class="why"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><p><b>ทำไมดี:</b> กลุ่มที่ 2 ถูกเขียนว่าเป็น<b>สมมติฐาน</b> ไม่ใช่ข้อเท็จจริง และเหตุผลเลือกกลุ่มหลักตอบคำถามว่า “ใครช่วยเขาได้” ทำให้ผู้ใช้ของนวัตกรรมไม่ได้มีแค่ผู้สูงอายุ แต่รวมอาสาสมัครด้วย</p></div></div>
          </div>
        </article>

        <article class="ex" id="a1-s5">
          <header class="ex-h"><span class="num-dot">5</span><h4>สิ่งที่รู้แล้ว / ยังไม่รู้ / ต้องหาต่อ</h4></header>
          <div class="ex-b">
            <div class="ex-q"><b>ใบกิจกรรมถามว่า</b><p>สิ่งที่รู้จากหลักฐาน · คำถามที่ยังไม่มีคำตอบ · จะสืบค้นหรือถามใคร/ที่ใด</p></div>
            <div class="ex-a"><span class="lab">คำตอบของทีมยามน้ำ</span>
              <div class="tbl"><table>
                <thead><tr><th>รู้จากหลักฐาน</th><th>ยังไม่รู้</th><th>หาต่ออย่างไร</th></tr></thead>
                <tbody>
                  <tr><td>น้ำป่าอุตรดิตถ์มาเร็วและมาตอนกลางคืนได้ (น้ำปาด 2554 ตี 2) · ไฟดับ-สัญญาณหายเกิดจริง (ลับแล 2567)</td><td>น้ำจากต้นน้ำใช้เวลากี่นาทีกว่าจะถึงหมู่บ้านเรา · ระดับน้ำกี่เซนติเมตรที่ชาวบ้านถือว่าอันตราย</td><td>ถามผู้ใหญ่บ้าน/ผู้สูงอายุที่เคยเจอเหตุ · ดูข้อมูลสถานีวัดน้ำของหน่วยงานรัฐ เช่น ThaiWater</td></tr>
                  <tr><td>ปภ. ส่ง Cell Broadcast เตือนระดับอำเภอ (ฟากท่า 2568) · บทความไทยโพสต์ (2561) แนะนำอพยพผู้ป่วยติดเตียงตั้งแต่เนิ่น ๆ ไม่รอน้ำท่วมขัง</td><td>คำเตือนระดับอำเภอละเอียดพอสำหรับลำห้วยของหมู่บ้านเราหรือไม่ · หมู่บ้านเรามีจุดนัดพบและเส้นทางอพยพหรือยัง</td><td>ถามเทศบาล/อบต. และ ปภ.อุตรดิตถ์ (โทร 1784) · เดินสำรวจหมู่บ้านกับผู้ใหญ่บ้าน</td></tr>
                </tbody>
              </table></div>
            </div>
            <div class="why"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><p><b>ทำไมดี:</b> คอลัมน์ “ยังไม่รู้” เป็นคำถามที่<b>ตรวจสอบได้จริง</b> (กี่นาที กี่เซนติเมตร) และบอกชัดว่าจะไปถามใคร ไม่ใช่เขียนว่า “ค้นเพิ่มในอินเทอร์เน็ต”</p></div></div>
          </div>
        </article>

        <article class="ex" id="a1-s6">
          <header class="ex-h"><span class="num-dot">6</span><h4>ตั้งคำถามสำรวจปัญหา</h4></header>
          <div class="ex-b">
            <div class="ex-q"><b>ใบกิจกรรมถามว่า</b><p>ต้องมีทั้ง “ทำไม...?” พร้อมเหตุผลว่าสำคัญอย่างไร และ “ถ้า...จะเป็นอย่างไร?” พร้อมเงื่อนไขใหม่ที่อยากสำรวจ</p></div>
            <div class="ex-a"><span class="lab">คำตอบของทีมยามน้ำ</span>
              <div class="pair">
                <div class="good"><h5>ทำไม...?</h5><p>ทำไมผู้สูงอายุที่อยู่คนเดียวจึงมักอพยพช้ากว่าคนวัยอื่นเมื่อน้ำป่ามา</p><p class="sm" style="margin:0"><b>สำคัญเพราะ</b> ถ้ารู้สาเหตุ (ห่วงทรัพย์สิน เคลื่อนที่ลำบาก ไม่ได้รับข่าว) จะออกแบบการเตือนให้ตรงจุดได้</p></div>
                <div class="good"><h5>ถ้า...จะเป็นอย่างไร?</h5><p>ถ้าน้ำป่ามาตอนตี 2 ขณะไฟดับและไม่มีอินเทอร์เน็ต คนในหมู่บ้านจะรู้ได้อย่างไร</p><p class="sm" style="margin:0"><b>เงื่อนไขใหม่</b> ไม่มีไฟ ไม่มีสัญญาณ ไม่มีแสง เสียงไซเรน ไฟแบตเตอรี่ หรือเพื่อนบ้านเคาะประตู อย่างไหนช่วยได้</p></div>
              </div>
            </div>
            <div class="why"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><p><b>ทำไมดี:</b> คำถาม “ถ้า...” ไม่ได้ถามเฉย ๆ แต่เสนอ<b>ตัวเลือกให้ลองเทียบ</b> (ไซเรน ไฟ เพื่อนบ้าน) ซึ่งจะกลายเป็นวัตถุดิบของใบกิจกรรมที่ 3</p></div></div>
          </div>
        </article>

        <article class="ex" id="a1-s7">
          <header class="ex-h"><span class="num-dot">7</span><h4>ท้าทายสิ่งที่เคยเชื่อ</h4></header>
          <div class="ex-b">
            <div class="ex-q"><b>ใบกิจกรรมถามว่า</b><p>สิ่งที่เคยเชื่อ · ตรวจกับหลักฐานแล้วพบว่า (ตรง/ขัด/ยังไม่รู้) · ถ้าข้อสมมตินี้ใช้ไม่ได้ จะเกิดอะไรขึ้น และข้อมูลที่ขัดกับที่เราคิด 1 เรื่อง</p></div>
            <div class="ex-a"><span class="lab">คำตอบของทีมยามน้ำ</span>
              <div class="tbl"><table>
                <thead><tr><th>เคยเชื่อว่า</th><th>ตรวจกับหลักฐาน</th><th>ถ้าใช้ไม่ได้ จะเกิดอะไร</th></tr></thead>
                <tbody>
                  <tr><td>“มีข่าวในไลน์/โทรศัพท์ ก็รู้ทัน”</td><td><b>ขัด</b> · ลับแล 2567 สัญญาณโทรศัพท์ใช้ไม่ได้ ต้องติดต่อกันด้วยรถจักรยานยนต์</td><td>ข่าวไม่ถึงคน ต้องมีสัญญาณที่ไม่พึ่งเน็ต เช่น ไซเรน ไฟ และเพื่อนบ้านเคาะประตู</td></tr>
                  <tr><td>“ค่อยออกเมื่อเห็นน้ำเข้าบ้านก็ทัน”</td><td><b>ขัด</b> · ไทยโพสต์ (2561) แนะนำอพยพผู้ป่วยติดเตียงก่อนน้ำท่วมขัง และที่ฟากท่าน้ำสูงราว 1.5 ม.</td><td>ถนนหรือสะพานอาจใช้ไม่ได้ (บ้านกกต้อง สะพานขาด) ต้องรอเรือกู้ภัย</td></tr>
                </tbody>
              </table></div>
              <div class="three" style="margin-top:14px">
                <div class="k-know"><h5>ข้อมูลที่ขัดกับที่คิด</h5><p>เดิมคิดว่าเตือนทางมือถือก็พอ แต่บทความไทยพีบีเอส Policy Watch (1 ส.ค. 2568) อ้างงานวิจัยว่า การได้รับเตือนทันเวลา การมีหลายช่องทาง (วิทยุ โทรศัพท์ โทรทัศน์) และการรู้จุดนัดพบของชุมชน ช่วยให้คนตัดสินใจอพยพมากขึ้น</p></div>
                <div class="k-guess"><h5>ชะลอการตัดสิน</h5><p>ยังไม่สรุปว่าไซเรนดีที่สุด จะถามผู้ใหญ่บ้านว่าเคยได้ยินเสียงตามสายหรือไม่ และตรวจว่าหมู่บ้านมีจุดนัดพบหรือยัง</p></div>
                <div class="k-ask"><h5>ผลที่ปรับความคิด</h5><p>เพิ่ม “จุดนัดพบ” และ “หลายช่องทาง” เข้าไปในโจทย์ ไม่ทำแค่แอปเดียว</p></div>
              </div>
            </div>
            <div class="why"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><p><b>ทำไมดี:</b> ทีมยอมรับว่า<b>ความเชื่อเดิมของตัวเองผิด</b> มีหลักฐานรองรับ และเห็นผลชัดว่าความคิดเปลี่ยนไปอย่างไร ตรงกับสิ่งที่เกณฑ์ “การท้าทายกรอบเดิม” มองหา</p></div></div>
          </div>
        </article>

        <div class="callout note"><svg class="ic" aria-hidden="true"><use href="#i-arrow-r"/></svg><div><p><b>เชื่อมไปใบกิจกรรมที่ 2:</b> ข้อ 4 (กลุ่มหลัก) ข้อ 5 และ ข้อ 7 กลายเป็นวัตถุดิบของข้อความกำหนดปัญหา และโจทย์ “เราจะ…ได้อย่างไร” ในขั้นต่อไป</p></div></div>
      </div>
    </div>

    <!-- ---------- A1 : HAZARDS ---------- -->
    <div class="panel" role="tabpanel" id="p-a1-hz" aria-labelledby="t-a1-hz" hidden>
      <div class="stack">
        <div class="callout note"><svg class="ic" aria-hidden="true"><use href="#i-info"/></svg><div><p>ภัยน้ำท่วมอยู่ในแท็บ “ตัวอย่างละเอียด” ที่นี่เลือกดูอีก 4 ภัย ทั้งเหตุการณ์จริงที่ใช้เริ่มต้น และตัวอย่างคำตอบเต็มทุกหัวข้อของใบกิจกรรมที่ 1 ตัวเลข [n] คือหมายเลขอ้างอิงในหน้า “คลังสื่อ”</p></div></div>
        <div class="hz" data-hz-for="a1"></div>
      </div>
    </div>

    <!-- ---------- A1 : RUBRIC ---------- -->
    <div class="panel" role="tabpanel" id="p-a1-rub" aria-labelledby="t-a1-rub" hidden>
      <div class="stack">
        <div class="card soft">
          <h3>ครูดูอะไร</h3>
          <p style="margin:0">ใบนี้ประเมินเพียง <b>องค์ประกอบที่ 3 การเปิดรับและกล้าสำรวจสิ่งใหม่</b> ครูให้ระดับ 1.0–4.0 จากหลักฐานในใบกิจกรรมของแต่ละคน ผลงานกลุ่มใช้ประกอบ ต่อไปนี้คือเกณฑ์ที่คัดจากแบบวัดความคิดสร้างสรรค์และนวัตกรรม</p>
        </div>

        <div>
          <div class="lad-h"><h4>3.1 ความอยากรู้อยากเห็น</h4><span class="pill">หลักฐาน: ส่วนที่ 4–6</span></div>
          <div class="ladder">
            <div class="rung"><small>1.0 ขั้นเริ่มต้น</small>ตั้งคำถามเกี่ยวกับภาระงาน กระบวนการ หรือความคิด</div>
            <div class="rung"><small>2.0 ขั้นพื้นฐาน</small>พยายามขยายความเข้าใจด้วยการตั้งคำถาม ทดลองแนวทางใหม่ หรือพิจารณาความคิดใหม่</div>
            <div class="rung"><small>3.0 ขั้นชำนาญ</small>แสวงหาและพิจารณาความคิดที่ไม่คุ้นเคยด้วยใจเปิดกว้าง และชะลอการตัดสินความคิดจนกว่าจะได้สำรวจอย่างเพียงพอ</div>
            <div class="rung"><small>4.0 ขั้นสูง</small>แสวงหาและสำรวจความคิดใหม่ ความคิดที่ขัดแย้ง คำถามที่ยังไม่มีคำตอบ และสถานการณ์หรือแนวทางแก้ปัญหาที่ซับซ้อน</div>
          </div>
        </div>
        <div>
          <div class="lad-h"><h4>3.2 การท้าทายกรอบเดิม</h4><span class="pill">หลักฐาน: ส่วนที่ 7</span></div>
          <div class="ladder">
            <div class="rung"><small>1.0 ขั้นเริ่มต้น</small>ใช้วิธีการหรือมุมมองที่คุ้นเคยในการสร้างผลงานหรือแนวทางแก้ปัญหา</div>
            <div class="rung"><small>2.0 ขั้นพื้นฐาน</small>เสนอความคิดที่อาจดูเสี่ยง แปลก หรือไม่ปกติ แต่ยังสัมพันธ์กับภาระงานและอาจนำไปสู่แนวทางแก้ปัญหาที่มีประสิทธิผล</div>
            <div class="rung"><small>3.0 ขั้นชำนาญ</small>กล้าเสี่ยงทางความคิดโดยจงใจตั้งคำถามต่อขอบเขต ข้อจำกัด ความคิดหรือแบบแผนที่มีอยู่</div>
            <div class="rung"><small>4.0 ขั้นสูง</small>ตั้งคำถามและท้าทายข้อสรุป สมมติฐาน หรือความเชื่อของตนเอง และเสนอความคิดที่มีความเป็นไปได้ซึ่งท้าทายขอบเขต ข้อจำกัด หรือแบบแผนเดิม</div>
          </div>
        </div>

        <div class="callout idea"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><h5>อ่านเกณฑ์แล้วแปลเป็นการกระทำ</h5>
          <ul style="margin:.3em 0 0"><li>คำถามที่ดีไม่ใช่คำถามที่ตอบได้ด้วย “ใช่/ไม่ใช่” แต่เป็นคำถามที่ต้องไปหาหลักฐานหรือไปถามคนจริง</li><li>“ชะลอการตัดสิน” คือเขียนให้เห็นว่าเราสำรวจเพิ่มอะไรก่อนสรุป ตามข้อสุดท้ายของใบกิจกรรม</li><li>“ท้าทายความเชื่อของตนเอง” คือกล้าเขียนว่าสิ่งที่เราเคยคิดอาจผิด แล้วบอกว่าตรวจกับหลักฐานใด</li></ul></div></div>

        <div class="card">
          <h4>เช็กลิสต์ก่อนส่งใบกิจกรรมที่ 1</h4>
          <p class="sm mute">ติ๊กได้เลย เครื่องนี้จะจำไว้ให้ในเบราว์เซอร์ของคุณ ครูไม่เห็นเช็กลิสต์นี้</p>
          <ul class="checks" data-checks="a1">
            <li><label><input type="checkbox"><span>ระบุภัย พื้นที่ และเวลาที่เกิดชัดเจน (ไม่ใช่แค่เขียนว่า “น้ำท่วม”)</span></label></li>
            <li><label><input type="checkbox"><span>มีแหล่งข้อมูลอย่างน้อย 3 แหล่ง พร้อมวิธีตรวจสอบและวันที่เข้าถึง</span></label></li>
            <li><label><input type="checkbox"><span>เขียนสาเหตุอย่างน้อย 2 ข้อ พร้อมผลกระทบที่มีหลักฐาน</span></label></li>
            <li><label><input type="checkbox"><span>เลือกผู้ได้รับผลกระทบ 2 กลุ่ม (กลุ่มที่ 2 เป็นกลุ่มที่มักถูกมองข้าม) และเลือกกลุ่มหลัก 1 กลุ่มพร้อมเหตุผล</span></label></li>
            <li><label><input type="checkbox"><span>แยก “รู้จากหลักฐาน” กับ “ยังไม่รู้” และบอกว่าจะถามใครหรือค้นที่ไหน</span></label></li>
            <li><label><input type="checkbox"><span>มีทั้งคำถาม “ทำไม...?” และ “ถ้า...จะเป็นอย่างไร?”</span></label></li>
            <li><label><input type="checkbox"><span>เขียนสิ่งที่เคยเชื่อ ตรวจกับหลักฐาน และบอกว่าถ้าข้อสมมติใช้ไม่ได้จะเกิดอะไร</span></label></li>
            <li><label><input type="checkbox"><span>เขียนข้อมูลที่ขัดกับที่คิด 1 เรื่อง และบอกว่าชะลอการตัดสินและสำรวจเพิ่มอย่างไร</span></label></li>
          </ul>
          <div class="meter" style="margin-top:14px" aria-hidden="true"><i data-meter="a1"></i></div>
          <p class="sm mute" style="margin:.5em 0 0" data-meter-text="a1">ติ๊กแล้ว 0 จาก 8 ข้อ</p>
        </div>
      </div>
    </div>

    <div class="pn">
      <a class="btn" href="#home" data-go="home"><svg class="ic" aria-hidden="true"><use href="#i-arrow-l"/></svg> หน้าแรก</a>
      <a class="btn pri" href="#a2" data-go="a2">ใบกิจกรรมที่ 2 นักสืบปัญหา ภัยธรรมชาติ <svg class="ic" aria-hidden="true"><use href="#i-arrow-r"/></svg></a>
    </div>
  </div>
</section>
<!-- ====================== ACTIVITY 2 ====================== -->
<section class="view k2" id="v-a2" data-view="a2" hidden>
  <div class="ah k2">
    <div class="wrap ah-in">
      <div class="ah-num" aria-hidden="true">2</div>
      <div>
        <p class="stage">ขั้นที่ 2 · การกำหนดและวิเคราะห์ปัญหา</p>
        <h1>นักสืบปัญหา<wbr> ภัยธรรมชาติ</h1>
        <p class="mission-line">นำข้อมูลจากใบที่ 1 มากำหนดปัญหาที่เฉพาะเจาะจง มีผู้ใช้ชัดเจน แล้วสร้างโจทย์ออกแบบหลายแนวทาง ก่อนเลือกโจทย์ที่แก้ได้ด้วยต้นแบบ</p>
        <div class="pills">
          <span class="pill">2 ชั่วโมง</span>
          <span class="pill">ประเมิน องค์ประกอบที่ 1 การสร้างความคิด</span>
          <span class="pill">การกำหนดปัญหา · การสร้างความคิด · การสืบค้นเชิงสร้างสรรค์</span>
        </div>
        <p style="margin:14px 0 0"><a class="btn" href="https://docs.google.com/presentation/d/1YeYSp4px4QHdu0ttfVBTDI7DWZmeLslWcc_OnfwDT8k/edit?usp=sharing" target="_blank" rel="noopener">เปิดใบกิจกรรมที่ 2 (Google Slides) <svg class="ic" aria-hidden="true"><use href="#i-link"/></svg></a></p>
      </div>
    </div>
  </div>

  <div class="wrap">
    <div class="tabs" role="tablist" aria-label="เมนูย่อยของใบกิจกรรมที่ 2">
      <button type="button" class="tab" role="tab" id="t-a2-learn" aria-controls="p-a2-learn" aria-selected="true" data-go="a2"><svg class="ic" aria-hidden="true"><use href="#i-book"/></svg>เรียนรู้</button>
      <button type="button" class="tab" role="tab" id="t-a2-ex" aria-controls="p-a2-ex" aria-selected="false" data-go="a2-ex"><svg class="ic" aria-hidden="true"><use href="#i-search"/></svg>ตัวอย่างละเอียด</button>
      <button type="button" class="tab" role="tab" id="t-a2-hz" aria-controls="p-a2-hz" aria-selected="false" data-go="a2-hz"><svg class="ic" aria-hidden="true"><use href="#i-users"/></svg>ตัวอย่าง 4 ภัยอื่น</button>
      <button type="button" class="tab" role="tab" id="t-a2-rub" aria-controls="p-a2-rub" aria-selected="false" data-go="a2-rub"><svg class="ic" aria-hidden="true"><use href="#i-check"/></svg>เกณฑ์และเช็กลิสต์</button>
    </div>

    <!-- ---------- A2 : LEARN ---------- -->
    <div class="panel" role="tabpanel" id="p-a2-learn" aria-labelledby="t-a2-learn">
      <div class="stack">
        <div class="card">
          <p class="lede">ชั่วโมงที่แล้วเราเก็บข้อมูลก้อนใหญ่มาแล้ว วันนี้จะเปลี่ยนมันให้เหลือ <b>โจทย์เดียวที่ออกแบบได้</b></p>
          <div class="flowline">
            <span class="pill">แยกสาเหตุ–ปัญหา–ผลกระทบ</span><span class="arrow">→</span>
            <span class="pill">รู้จักผู้ใช้</span><span class="arrow">→</span>
            <span class="pill">เขียนข้อความกำหนดปัญหา</span><span class="arrow">→</span>
            <span class="pill">ตั้งโจทย์ “เราจะ…ได้อย่างไร”</span><span class="arrow">→</span>
            <span class="pill">เรียนจากวิธีของผู้อื่น</span><span class="arrow">→</span>
            <span class="pill">ปรับกรอบโจทย์</span>
          </div>
        </div>


        <ul class="toc" aria-label="หัวข้อในแท็บนี้">
          <li><a href="#" data-scroll="a2-l1"><i>1</i>ประโยคแบบไหนออกแบบได้</a></li>
          <li><a href="#" data-scroll="a2-l2"><i>2</i>ต้นไม้ปัญหา</a></li>
          <li><a href="#" data-scroll="a2-l3"><i>3</i>ผู้ใช้และหลายมุมมอง</a></li>
          <li><a href="#" data-scroll="a2-l4"><i>4</i>ข้อความกำหนดปัญหา</a></li>
          <li><a href="#" data-scroll="a2-l5"><i>5</i>โจทย์ “เราจะ…”</a></li>
          <li><a href="#" data-scroll="a2-l6"><i>6</i>เรียนจากผู้อื่น</a></li>
          <li><a href="#" data-scroll="a2-l7"><i>7</i>ปรับกรอบโจทย์</a></li>
        </ul>

        <!-- 1 -->
        <div class="blk" id="a2-l1">
          <h3><span class="num-dot">1</span>ประโยคไหนเอาไปออกแบบได้เลย โดยไม่ต้องถามต่อ</h3>
          <div class="quiz" data-quiz="b">
            <h5><span class="pill">ลองตอบ</span> เลือกประโยคที่พร้อมออกแบบ</h5>
            <div class="opts">
              <button type="button" class="opt" data-k="a"><span class="k">ก</span><span>ภัยแล้ง</span></button>
              <button type="button" class="opt" data-k="b"><span class="k">ข</span><span>ผู้สูงอายุที่อยู่ลำพังในพื้นที่เสี่ยงน้ำป่าไม่ได้รับข้อมูลเตือนทันเวลา</span></button>
              <button type="button" class="opt" data-k="c"><span class="k">ค</span><span>ฝนตกหนัก</span></button>
            </div>
            <div class="fb" hidden><b class="fb-h"></b>
              <p><b>ประโยคกว้าง</b> (ภัยแล้ง / ฝนตกหนัก) เป็นชื่อภัยหรือปรากฏการณ์ธรรมชาติ ยังไม่รู้ว่าเกิดกับใคร ที่ไหน เวลาใด และสิ่งใดกำลังเป็นปัญหา ต้องถามต่ออีกหลายข้อก่อนออกแบบ</p>
              <p><b>ประโยคเจาะจง</b> (ข้อ ข) ระบุผู้ได้รับผลกระทบ (ผู้สูงอายุที่อยู่ลำพัง) บอกบริบท (พื้นที่เสี่ยงน้ำป่า) และบอกความยากลำบาก (รับข่าวเตือนไม่ทันเวลา)</p></div>
          </div>
        </div>

        <!-- 2 -->
        <div class="blk" id="a2-l2">
          <h3><span class="num-dot">2</span>ต้นไม้ปัญหา แยกสาเหตุ ปัญหาหลัก และผลกระทบ</h3>
          <figure style="margin:0" class="card">
            <svg class="diagram" viewBox="0 0 680 330" role="img" aria-labelledby="treeT treeD">
              <title id="treeT">ต้นไม้ปัญหา</title>
              <desc id="treeD">ใบของต้นไม้คือผลกระทบที่ตามมา ลำต้นคือปัญหาหลักที่ต้องมีเจ้าของปัญหา ราก คือสาเหตุ</desc>
              <ellipse class="dg-box" style="fill:var(--a2-soft)" cx="340" cy="86" rx="215" ry="68"/>
              <circle class="dg-box" style="fill:var(--a2-soft)" cx="195" cy="130" r="38"/>
              <circle class="dg-box" style="fill:var(--a2-soft)" cx="485" cy="130" r="38"/>
              <ellipse style="fill:var(--a2-soft)" cx="340" cy="100" rx="200" ry="52"/>
              <text class="dg-t" x="340" y="78" text-anchor="middle">ใบ = ผลกระทบ</text>
              <text class="dg-s" x="340" y="100" text-anchor="middle">ผลที่ตามมา</text>
              <rect class="dg-box" style="fill:var(--a4-soft)" x="312" y="152" width="56" height="86" rx="6"/>
              <text class="dg-t" x="340" y="200" text-anchor="middle" style="font-size:13px">ปัญหา</text>
              <text class="dg-t" x="340" y="218" text-anchor="middle" style="font-size:13px">หลัก</text>
              <line class="dg-ln" x1="368" y1="190" x2="418" y2="190"/>
              <text class="dg-t" x="426" y="186">ลำต้น = ปัญหาหลัก</text>
              <text class="dg-s" x="426" y="206">ต้องมีเจ้าของปัญหา (ใครเป็นคนที่ลำบาก)</text>
              <line class="dg-ln" x1="60" y1="238" x2="620" y2="238"/>
              <path class="dg-ln" d="M340 238 C 340 262 300 270 250 296"/>
              <path class="dg-ln" d="M340 238 C 340 262 380 270 430 296"/>
              <path class="dg-ln" d="M328 238 C 300 258 210 262 170 286"/>
              <path class="dg-ln" d="M352 238 C 380 258 470 262 510 286"/>
              <text class="dg-t" x="340" y="322" text-anchor="middle">ราก = สาเหตุ (เหตุใดจึงเกิด)</text>
            </svg>
            <figcaption class="sm mute" style="margin-top:8px">ถามจากล่างขึ้นบน: อะไรเป็นต้นเหตุ → อะไรคือสิ่งที่ต้องแก้ → แล้วใครต้องรับผลที่ตามมา</figcaption>
          </figure>

          <p class="mute" style="margin:0"><b>ตัวอย่าง (เหตุการณ์ A น้ำป่า อ.ท่าปลา):</b></p>
          <div class="tbl"><table>
            <thead><tr><th>สาเหตุ</th><th>ปัญหาหลัก</th><th>ผลกระทบ</th></tr></thead>
            <tbody>
              <tr><td>น้ำสูงเกิน 2 เมตรและถนนอุตรดิตถ์–เขื่อนสิริกิติ์ที่ ต.หาดงิ้วถูกตัดขาด (เหตุการณ์ A ในใบกิจกรรมที่ 1)</td><td>ผู้สูงอายุและผู้ป่วยติดเตียงอพยพด้วยตนเองไม่ได้ ต้องรอความช่วยเหลือ</td><td>เสี่ยงอพยพล่าช้า ครอบครัวต้องรอโดยไม่ทราบว่าความช่วยเหลือจะมาเมื่อใด <span class="tag-sim">ข้อสันนิษฐาน ยังไม่ตรวจ</span></td></tr>
              <tr><td>การเข้าถึงต้องพึ่งอาสาสมัครกับเรือท้องแบน (ข่าวเหตุการณ์ A)</td><td>อาสาสมัครอาจไม่ทราบแน่ชัดว่าบ้านใดมีผู้ที่ต้องช่วยก่อน <span class="tag-sim">สมมติฐาน</span></td><td>ช่วยได้จำกัด ทรัพยากรที่มีถูกใช้ไม่เป็นลำดับ ไม่ตรงจุด <span class="tag-sim">สมมติฐาน</span></td></tr>
            </tbody>
          </table></div>
          <div class="card">
            <h4>เลือกปัญหาหลักมา “เรื่องเดียว”</h4>
            <dl class="kv">
              <dt>ปัญหาหลัก</dt><dd>ผู้สูงอายุและผู้ป่วยติดเตียงอพยพเองไม่ได้และต้องรอความช่วยเหลือ</dd>
              <dt>เหตุผล</dt><dd>เป็นกลุ่มที่ช่วยตัวเองได้ยากที่สุด และข่าวรายงานว่าอาสาสมัครต้องใช้เรือท้องแบนเข้าไปช่วย</dd>
              <dt>ขอบเขต</dt><dd>ที่ตำบลในอำเภอท่าปลาที่น้ำท่วมสูง กับผู้สูงอายุและผู้ป่วยติดเตียงที่ต้องพึ่งผู้อื่นในการอพยพ เมื่อน้ำสูงเกิน 2 เมตรและถนนถูกตัดขาด</dd>
            </dl>
          </div>
        </div>

        <!-- 3 -->
        <div class="blk" id="a2-l3">
          <h3><span class="num-dot">3</span>รู้จัก “ผู้ใช้” ก่อนคิดวิธีช่วย</h3>
          <div class="pair">
            <div class="bad"><h5>การมองเฉพาะภัย</h5><p class="sm" style="margin:0">รู้เพียงว่าเกิดฝนหนักหรือน้ำป่า ยังไม่เห็นว่าใครทำกิจวัตรหรือทำงานอะไรไม่ได้ อาจเลือกแก้เรื่องที่ไม่ใช่ปัญหาหลักของคนจริง</p></div>
            <div class="good"><h5>การมองจากผู้ใช้</h5><p class="sm" style="margin:0">เห็นว่าคนกลุ่มใดกำลังเผชิญปัญหา รู้ช่วงที่ประสบปัญหาและข้อจำกัด ตั้งคำถามต่อว่าความช่วยเหลือแบบใดจำเป็นจริง</p></div>
          </div>
          <div class="tbl tight"><table>
            <thead><tr><th>คำถาม</th><th>คำตอบกลุ่มพร้อมหลักฐาน (ตัวอย่าง)</th></tr></thead>
            <tbody>
              <tr><td>ผู้ที่ต้องการช่วยเหลือคือใคร</td><td>ผู้สูงอายุ ผู้ป่วยติดเตียง และครอบครัวผู้ดูแล (เหตุการณ์ A ระบุว่าอาสาสมัครใช้เรือท้องแบนช่วยกลุ่มนี้)</td></tr>
              <tr><td>ประสบปัญหาเมื่อใด</td><td>เมื่อน้ำสูงเกิน 2 เมตรและถนนถูกตัดขาด รถเข้าถึงไม่ได้</td></tr>
              <tr><td>ต้องการความช่วยเหลือแบบใด</td><td>ต้องได้รับการอพยพก่อน และมีคนรู้ว่าอยู่บ้านไหน <span class="tag-sim">ข้อสันนิษฐาน ยังไม่ยืนยันว่ามีหน่วยงานดูแลอยู่แล้วหรือไม่ ต้องสอบถามผู้ใหญ่บ้านหรือหน่วยงาน</span></td></tr>
            </tbody>
          </table></div>
          <h4 style="margin-top:6px">มองปัญหาจากมุมอื่นอย่างน้อย 2 มุม</h4>
          <div class="grid g4">
            <div class="card flat"><h5>ชุมชน / วัฒนธรรม</h5><p class="sm" style="margin:0">คนในชุมชนรับข่าวจากใคร เชื่อใคร และมีวิธีช่วยกันอย่างไร</p></div>
            <div class="card flat"><h5>เศรษฐกิจ / ค่าใช้จ่าย</h5><p class="sm" style="margin:0">ผู้ใช้ต้องเสียค่าใช้จ่ายอะไร มีทรัพยากรเท่าไร และใครได้รับผลต่ออาชีพ</p></div>
            <div class="card flat"><h5>ความปลอดภัย / จริยธรรม</h5><p class="sm" style="margin:0">การช่วยเหลือที่คิดอาจสร้างความเสี่ยงหรือกระทบข้อมูลส่วนบุคคลหรือไม่</p></div>
            <div class="card flat"><h5>หน่วยงานที่เกี่ยวข้อง</h5><p class="sm" style="margin:0">ใครรับผิดชอบข้อมูลเตือนภัย การช่วยเหลือ และการตัดสินใจอย่างเป็นทางการ</p></div>
          </div>
          <div class="callout idea"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><h5>ตัวอย่าง มุมมองเดียวทำให้เปลี่ยนความคิด</h5><p>กลุ่มเดิมจะ “รวบรวมรายชื่อ” ผู้ป่วยติดเตียง แต่เมื่อมองจากมุม<b>ความปลอดภัยและจริยธรรม</b> พบว่ารายชื่อและที่อยู่เป็นข้อมูลส่วนบุคคล ต้องขออนุญาตและเก็บอย่างระมัดระวัง กลุ่มจึงเปลี่ยนใจ มาคิดวิธีที่ไม่ต้องเก็บข้อมูลส่วนตัวแทน</p></div></div>
        </div>

        <!-- evidence vs guess -->
        <div class="blk">
          <h3>หลักฐาน ไม่เท่ากับ การคาดเดา</h3>
          <div class="three">
            <div class="k-know"><h5>รู้จากหลักฐาน</h5><p>ข้อมูลมีที่มา ระบุผู้เผยแพร่ และตรวจสอบได้ นำมาใช้ตั้งขอบเขตปัญหาอย่างมั่นใจ</p></div>
            <div class="k-guess"><h5>สันนิษฐาน / อาจ</h5><p>แนวคิดที่มีเหตุผล แต่ยังไม่มีหลักฐานเฉพาะพื้นที่ยืนยัน ให้เขียนว่า “อาจ” และไม่เขียนเป็นข้อเท็จจริง</p></div>
            <div class="k-ask"><h5>ยังไม่รู้</h5><p>สิ่งที่ต้องถามผู้ใช้ ผู้ดูแลชุมชน หรือหน่วยงาน เขียนเป็นคำถามที่ตรวจสอบได้</p></div>
          </div>
          <div class="quiz" data-quiz="b">
            <h5><span class="pill">ลองตอบ</span> “อาสาสมัครอาจไม่ทราบแน่ชัดว่าบ้านใดมีผู้ที่ต้องช่วยก่อน” จัดอยู่ในกล่องไหน</h5>
            <div class="opts">
              <button type="button" class="opt" data-k="a"><span class="k">ก</span><span>รู้จากหลักฐาน</span></button>
              <button type="button" class="opt" data-k="b"><span class="k">ข</span><span>สันนิษฐาน / อาจ</span></button>
              <button type="button" class="opt" data-k="c"><span class="k">ค</span><span>ยังไม่รู้</span></button>
            </div>
            <div class="fb" hidden><b class="fb-h"></b><p>ข่าวไม่ได้บอกเรื่องนี้ตรง ๆ เป็นแนวคิดที่มีเหตุผล จึงเป็นสมมติฐานที่ต้องเขียนว่า “อาจ” แล้วเอาไปถามผู้ใหญ่บ้านหรือหน่วยงานต่อ (ซึ่งจะย้ายไปอยู่ในกล่อง “ยังไม่รู้” เป็นคำถามที่ตรวจสอบได้)</p></div>
          </div>
        </div>

        <!-- 4 -->
        <div class="blk" id="a2-l4">
          <h3><span class="num-dot">4</span>เขียนข้อความกำหนดปัญหา (Problem Statement)</h3>
          <div class="callout note"><svg class="ic" aria-hidden="true"><use href="#i-info"/></svg><div><p><b>รูปประโยคช่วยคิด:</b> “(กลุ่มเป้าหมาย) ประสบปัญหา (ปัญหา) เมื่อ (สถานการณ์) เนื่องจาก (สาเหตุหรือข้อจำกัด) ส่งผลให้ (ผลกระทบ)”</p></div></div>
          <div class="grid g2">
            <div class="card" style="--c:var(--a2)">
              <span class="lab" style="background:var(--a2);color:var(--a2-on)">ตัวอย่าง</span>
              <p style="margin:0">“ผู้สูงอายุและผู้ป่วยติดเตียงในพื้นที่น้ำป่าท่าปลาที่ต้องพึ่งผู้อื่นในการอพยพ ประสบปัญหาไม่สามารถอพยพได้ทัน เมื่อน้ำสูงเกิน 2 เมตรและถนนถูกตัดขาด เนื่องจากอพยพด้วยตนเองไม่ได้ และการเข้าถึงต้องใช้เรือท้องแบนของอาสาสมัคร ส่งผลให้เสี่ยงอพยพล่าช้า”</p>
              <p class="sm" style="margin:.7em 0 0"><b>ตรวจ 3 ข้อ:</b> ระบุผู้ใช้ชัด · ไม่ใช่แค่ชื่อภัย · ไม่ซ่อนวิธีแก้ (ไม่มีคำว่าแอป สัญญาณ หรือระบบ)</p>
            </div>
            <div class="stack">
              <div class="pair" style="grid-template-columns:1fr">
                <div class="bad"><h5>“น้ำป่าทำให้หมู่บ้านเดือดร้อน”</h5><p class="sm" style="margin:0">กว้างเกินไป เพราะไม่บอกว่ากลุ่มใดเดือดร้อน ที่ไหน และเดือดร้อนเรื่องอะไร ควรถามว่า “ใครกำลังทำอะไรไม่ได้?”</p></div>
                <div class="bad"><h5>“ชาวบ้านขาดแอปแจ้งเตือน”</h5><p class="sm" style="margin:0">คำว่า “แอป” เป็นวิธีแก้ที่กำหนดไว้ล่วงหน้า ทั้งที่ยังไม่แน่ว่าผู้ใช้มีมือถือหรือสัญญาณ ควรถามว่า “ผู้ใช้ไม่ได้รับข้อมูลอย่างไร?”</p></div>
              </div>
            </div>
          </div>

          <div class="card" data-builder data-tpl="{0} ประสบปัญหา{1} เมื่อ{2} เนื่องจาก{3} ส่งผลให้{4}" data-sample="ผู้สูงอายุและผู้ป่วยติดเตียงในพื้นที่น้ำป่าท่าปลาที่ต้องพึ่งผู้อื่นในการอพยพ|ไม่สามารถอพยพได้ทัน|น้ำสูงเกิน 2 เมตรและถนนถูกตัดขาด|อพยพด้วยตนเองไม่ได้ และการเข้าถึงต้องใช้เรือท้องแบนของอาสาสมัคร|เสี่ยงอพยพล่าช้า">
            <h4>ลองประกอบข้อความกำหนดปัญหาของกลุ่มคุณ</h4>
            <p class="sm mute">พิมพ์ทีละช่อง ประโยคจะประกอบให้ด้านล่าง ใช้ฝึกโครงประโยคเท่านั้น ไม่ได้บันทึกอะไรไว้</p>
            <div class="bld">
              <label>กลุ่มเป้าหมาย<input type="text" data-part="0" placeholder="ใครเป็นเจ้าของปัญหา"></label>
              <label>ปัญหา<input type="text" data-part="1" placeholder="เขาทำอะไรไม่ได้ / ไม่ได้รับอะไร"></label>
              <label>สถานการณ์<input type="text" data-part="2" placeholder="เกิดขึ้นเมื่อใด"></label>
              <label>สาเหตุหรือข้อจำกัด<input type="text" data-part="3" placeholder="เพราะอะไร"></label>
              <label>ผลกระทบ<input type="text" data-part="4" placeholder="ตามมาด้วยอะไร"></label>
            </div>
            <div class="bld-out" aria-live="polite"><b class="sm mute">ผลลัพธ์</b><p style="margin:.2em 0 0" data-out></p></div>
            <div class="flowline" style="margin-top:12px">
              <button type="button" class="btn sm" data-fill>ใส่ตัวอย่าง</button>
              <button type="button" class="btn sm" data-clear>ล้างช่อง</button>
              <button type="button" class="btn sm" data-copy-out><svg class="ic" aria-hidden="true"><use href="#i-copy"/></svg> คัดลอกประโยค</button>
            </div>
          </div>

          <div class="callout safe"><svg class="ic" aria-hidden="true"><use href="#i-users"/></svg><div><h5>RECHECK กับเพื่อน</h5><p>ให้เพื่อนในกลุ่มคู่อ่าน “ข้อความกำหนดปัญหา” ที่เขียนจริง <b>โดยไม่อธิบายเพิ่มเติมก่อน</b> แล้วฟังว่าเพื่อนเข้าใจตรงกับเจตนาของเราหรือไม่ กลุ่มคู่ถามกลับ 2 ข้อ: “ผู้ใช้คือใคร?” และ “ปัญหาที่เขาประสบคืออะไร?” ถ้าเพื่อนตอบไม่ชัด ให้จดว่าคำหรือช่วงไหนต้องปรับ</p></div></div>
        </div>

        <!-- 5 -->
        <div class="blk" id="a2-l5">
          <h3><span class="num-dot">5</span>จากข้อความปัญหา สู่โจทย์ “เราจะ…ได้อย่างไร”</h3>
          <p class="mute">ข้อความกำหนดปัญหาบอกว่าเกิดอะไรกับใคร ส่วนโจทย์ HMW (How Might We) เปิดทางให้คิดวิธีแก้ได้หลายแบบ ปัญหาเดียวกันตั้ง HMW ได้หลายจุด</p>
          <div class="grid g3">
            <div class="card"><span class="pill">จุดที่ 1 ข้อมูล</span><p style="margin:.6em 0 0">เราจะช่วยให้ผู้ใช้ได้รับข้อมูลเตือนก่อนถึงช่วงเสี่ยง ภายใต้ข้อจำกัดของช่องทางรับข่าวได้อย่างไร</p></div>
            <div class="card"><span class="pill">จุดที่ 2 การตัดสินใจ</span><p style="margin:.6em 0 0">เราจะช่วยให้ผู้ใช้และผู้ดูแลตัดสินใจเตรียมพร้อมได้เร็วขึ้น ภายใต้เวลาที่จำกัดได้อย่างไร</p></div>
            <div class="card"><span class="pill">จุดที่ 3 การสื่อสาร</span><p style="margin:.6em 0 0">เราจะทำอย่างไรให้ข่าวจำเป็นไปถึงผู้ใช้ เมื่อช่องทางโทรศัพท์หรืออินเทอร์เน็ตใช้ไม่ได้</p></div>
          </div>
          <div class="pair">
            <div class="bad"><h5>ยังไม่ดี</h5><p style="margin:0">“เราจะสร้างแอปแจ้งเตือนได้อย่างไร?”</p><p class="sm" style="margin:.5em 0 0">ซ่อนคำตอบไว้แล้วว่าต้องเป็นแอปเท่านั้น และไม่ได้ถามว่าผู้ใช้มีสมาร์ตโฟนหรือมีสัญญาณหรือไม่</p></div>
            <div class="good"><h5>เหมาะสมกว่า</h5><p style="margin:0">“เราจะทำให้ข่าวเตือนถึงผู้ใช้ในพื้นที่เสี่ยงได้อย่างไร แม้ช่องทางอินเทอร์เน็ตขัดข้อง?”</p><p class="sm" style="margin:.5em 0 0">ยังเปิดให้คิดทางเลือกหลายแบบ</p></div>
          </div>
          <div class="card" data-builder data-tpl="เราจะออกแบบหรือพัฒนาอะไร เพื่อให้{0} สามารถ{1} ภายใต้{2} ได้อย่างไร?" data-sample="อาสาสมัคร|รู้ว่าบ้านหลังใดมีผู้สูงอายุหรือผู้ป่วยติดเตียงที่ต้องช่วยก่อน|เงื่อนไขว่าถนนถูกตัดและต้องใช้เรือท้องแบน">
            <h4>ลองประกอบโจทย์ “เราจะ…ได้อย่างไร”</h4>
            <p class="sm mute">รูปประโยคจากใบกิจกรรม ตัวอย่างคือโจทย์แรกในรายการด้านล่าง</p>
            <div class="bld">
              <label>ใคร (ผู้ใช้)<input type="text" data-part="0" placeholder="เช่น อาสาสมัคร"></label>
              <label>ทำอะไรเพื่อลดความเสี่ยง<input type="text" data-part="1" placeholder="สามารถทำอะไรได้"></label>
              <label>ภายใต้เงื่อนไข<input type="text" data-part="2" placeholder="เช่น ไม่มีไฟ ไม่มีเน็ต"></label>
            </div>
            <div class="bld-out" aria-live="polite"><b class="sm mute">ผลลัพธ์</b><p style="margin:.2em 0 0" data-out></p></div>
            <div class="flowline" style="margin-top:12px">
              <button type="button" class="btn sm" data-fill>ใส่ตัวอย่าง</button>
              <button type="button" class="btn sm" data-clear>ล้างช่อง</button>
              <button type="button" class="btn sm" data-copy-out><svg class="ic" aria-hidden="true"><use href="#i-copy"/></svg> คัดลอกประโยค</button>
            </div>
          </div>
          <h4>ตัวอย่างโจทย์ 2 ข้อ (ปัญหาเดียวกัน คนละมุม)</h4>
          <ol>
            <li>เราจะออกแบบอะไร เพื่อให้อาสาสมัครรู้ว่าบ้านหลังใดมีผู้สูงอายุหรือผู้ป่วยติดเตียงที่ต้องช่วยก่อน ภายใต้เงื่อนไขว่าถนนถูกตัดและต้องใช้เรือท้องแบน ได้อย่างไร</li>
            <li>เราจะออกแบบอะไร เพื่อให้ผู้ดูแลผู้ป่วยติดเตียงบอกอาสาสมัครได้ว่าต้องการความช่วยเหลือ ภายใต้เงื่อนไขที่ไฟฟ้าหรือสัญญาณโทรศัพท์อาจใช้ไม่ได้ (สมมติฐาน) ได้อย่างไร</li>
          </ol>
        </div>

        <!-- 6 -->
        <div class="blk" id="a2-l6">
          <h3><span class="num-dot">6</span>สืบค้นเชิงสร้างสรรค์ เปรียบเทียบ ไม่ใช่คัดลอก</h3>
          <div class="grid g3">
            <div class="card flat"><h5>เหมือนกันตรงไหน</h5><p class="sm" style="margin:0">ปัญหาหรือเป้าหมายของวิธีนั้นคล้ายกับที่ผู้ใช้ของเราต้องเผชิญอย่างไร</p></div>
            <div class="card flat"><h5>ต่างกันตรงไหน</h5><p class="sm" style="margin:0">ข้อจำกัดของผู้ใช้ เวลา พื้นที่ หรือทรัพยากรแตกต่างกันอย่างไร</p></div>
            <div class="card flat"><h5>นำอะไรมาปรับโจทย์</h5><p class="sm" style="margin:0">ข้อสรุปที่เปลี่ยนวิธีตั้งโจทย์ของเรา</p></div>
          </div>
          <div class="tbl"><table>
            <thead><tr><th>วิธีที่คนอื่นใช้</th><th>หลักการ</th><th>ต้องถามต่อ</th></tr></thead>
            <tbody>
              <tr><td>หอกระจายข่าวหมู่บ้าน</td><td>ส่งเสียงได้พร้อมกันหลายบ้าน</td><td>ผู้ใช้ได้ยินหรือไม่ บ้านอยู่ไกลแค่ไหน</td></tr>
              <tr><td>ข้อความเตือนผ่านโทรศัพท์</td><td>ส่งข้อมูลตรงไปยังผู้รับ</td><td>ผู้ใช้มีอุปกรณ์และสัญญาณหรือไม่</td></tr>
              <tr><td>ธงหรือไฟแสดงสี</td><td>สีหรือแสงบอกระดับความเสี่ยง</td><td>มองเห็นในเวลากลางคืนหรือไม่ และทุกคนเข้าใจสีตรงกันหรือไม่</td></tr>
              <tr><td>เสียงไซเรน</td><td>ส่งสัญญาณเตือนให้ระวัง</td><td>ผู้ฟังเข้าใจความหมายและรู้ว่าต้องทำอะไรต่อหรือไม่</td></tr>
            </tbody>
          </table></div>
          <div class="card">
            <h4>ตัวอย่างการเทียบ</h4>
            <div class="tbl tight"><table>
              <thead><tr><th>วิธีของผู้อื่น</th><th>เหมือน / ต่างจากของเรา</th></tr></thead>
              <tbody>
                <tr><td>1. หอกระจายข่าวหมู่บ้าน</td><td><b>เหมือน</b> ที่ต้องส่งข่าวหลายบ้านพร้อมกัน · <b>ต่าง</b> ที่ผู้ป่วยติดเตียงไม่ได้ต้องการแค่ข่าว แต่ต้องการคนไปช่วย</td></tr>
                <tr><td>2. เครือข่ายอาสาสมัครเคาะประตูบ้าน</td><td><b>เหมือน</b> ที่คนช่วยคนโดยตรง · <b>ต่าง</b> ที่เขาต้องรู้รายชื่อบ้านก่อนออกเรือ</td></tr>
              </tbody>
            </table></div>
            <p class="sm" style="margin:.7em 0 0"><b>แนวคิดที่นำมาปรับโจทย์:</b> โจทย์ควรเน้น “ใครต้องช่วยก่อน” ไม่ใช่แค่ “ส่งข่าว” และเพิ่มเงื่อนไขในโจทย์ว่าอาสาสมัครต้องรู้ตำแหน่งบ้านล่วงหน้า</p>
            <div class="callout idea" style="margin-top:12px"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><p><b>ถ้า...จะเป็นอย่างไร:</b> ถ้าข้อมูลบ้านที่ต้องช่วยก่อนถูกเตรียมไว้ตั้งแต่ก่อนฤดูฝน โดยครอบครัวยินยอมและผ่านหน่วยงาน อาสาสมัครจะตัดสินใจได้เร็วขึ้นไหม<br><b>คำตอบ:</b> น่าจะเร็วขึ้น เพราะไม่ต้องไล่ถามทีละบ้านตอนน้ำขึ้น แต่ทำให้เกิดคำถามใหม่ว่าจะรักษาความเป็นส่วนตัวและทำให้รายชื่อเป็นปัจจุบันได้อย่างไร จึงได้โจทย์ย่อยเพิ่มอีกหนึ่งข้อ</p></div></div>
          </div>
        </div>

        <!-- 7 -->
        <div class="blk" id="a2-l7">
          <h3><span class="num-dot">7</span>ตรวจความชัดเจนและปรับกรอบโจทย์ (Reframe)</h3>
          <div class="card">
            <h4>ตรวจ 5 ข้อก่อนเลือกโจทย์</h4>
            <ul class="checks" data-checks="a2-reframe">
              <li><label><input type="checkbox"><span>ระบุผู้ใช้ชัด</span></label></li>
              <li><label><input type="checkbox"><span>ช่วยลดความเสี่ยงจริง</span></label></li>
              <li><label><input type="checkbox"><span>ขอบเขตพอดีกับ 15 ชั่วโมง</span></label></li>
              <li><label><input type="checkbox"><span>ทำต้นแบบจำลองได้</span></label></li>
              <li><label><input type="checkbox"><span>ไม่อันตราย</span></label></li>
            </ul>
          </div>
          <div class="tbl"><table>
            <thead><tr><th>โจทย์ก่อน</th><th>ใครเสนอให้มองต่าง</th><th>โจทย์หลังปรับ</th><th>เปลี่ยนจุดเน้นตรงไหน</th></tr></thead>
            <tbody><tr>
              <td>อาสาสมัครรู้ว่าบ้านหลังใดมีผู้สูงอายุหรือผู้ป่วยติดเตียงที่ต้องช่วยก่อน</td>
              <td>กลุ่มอื่นถามว่า ถ้าเจ้าของบ้านไม่อนุญาตให้เก็บรายชื่อล่ะ</td>
              <td>อาสาสมัครรู้ว่าบ้านหลังใดต้องช่วยก่อน โดยครอบครัวเป็นผู้แจ้งเองและไม่ต้องเปิดเผยรายละเอียดสุขภาพ ภายใต้เงื่อนไขถนนถูกตัดและต้องใช้เรือ</td>
              <td>สอดคล้องกับมุมมองความปลอดภัยและจริยธรรม และไม่ต้องเก็บข้อมูลสุขภาพ</td>
            </tr></tbody>
          </table></div>
        </div>
      </div>
    </div>

    <!-- ---------- A2 : WORKED EXAMPLE ---------- -->
    <div class="panel" role="tabpanel" id="p-a2-ex" aria-labelledby="t-a2-ex" hidden>
      <div class="stack">
        <div class="card soft">
          <span class="tag-sim">ตัวอย่างเพื่อการเรียนรู้</span>
          <h3 style="margin-top:10px">ทีมยามน้ำ กรอกใบกิจกรรมที่ 2</h3>
          <p class="mute" style="margin:0">ต่อจากใบที่ 1 ของทีมยามน้ำ ใช้ข้อมูลเดิมเกือบทั้งหมด ลองสังเกตว่าคำตอบข้อไหน “ดึงมา” จากใบที่ 1 อย่างไร</p>
        </div>
        <ul class="toc" aria-label="ส่วนของใบกิจกรรมที่ 2">
          <li><a href="#" data-scroll="a2-s1"><i>1</i>แยกสาเหตุ</a></li>
          <li><a href="#" data-scroll="a2-s2"><i>2</i>ผู้ใช้และมุมมอง</a></li>
          <li><a href="#" data-scroll="a2-s3"><i>3</i>ข้อความปัญหา</a></li>
          <li><a href="#" data-scroll="a2-s4"><i>4</i>โจทย์ HMW</a></li>
          <li><a href="#" data-scroll="a2-s5"><i>5</i>เรียนจากผู้อื่น</a></li>
          <li><a href="#" data-scroll="a2-s6"><i>6</i>ปรับกรอบโจทย์</a></li>
        </ul>

        <article class="ex" id="a2-s1">
          <header class="ex-h"><span class="num-dot">1</span><h4>แยกสาเหตุ ปัญหาหลัก และผลกระทบ</h4></header>
          <div class="ex-b">
            <div class="ex-q"><b>ใบกิจกรรมถามว่า</b><p>แยกเป็น 3 ช่อง แล้วเลือก “ปัญหาหลัก” เพียง 1 เรื่อง บอกว่าสำคัญอย่างไรและขอบเขตอยู่ตรงไหน</p></div>
            <div class="ex-a"><span class="lab">คำตอบของทีมยามน้ำ</span>
              <div class="tbl"><table>
                <thead><tr><th>สาเหตุ</th><th>ปัญหาหลัก</th><th>ผลกระทบ</th></tr></thead>
                <tbody>
                  <tr><td>ฝนหนักต่อเนื่องที่ต้นน้ำ/ลาดเชิงเขา น้ำไหลลงลำห้วยเร็ว · ลำห้วยแคบ รับน้ำได้จำกัด</td><td>คนในหมู่บ้านรู้ว่าน้ำจะมาช้าเกินไป เพราะไม่มีใครเฝ้าดูระดับน้ำต้นทางต่อเนื่อง · คำเตือนระดับอำเภอไม่บอกระดับน้ำที่ลำห้วยของหมู่บ้านเรา</td><td>อพยพไม่ทัน ผู้สูงอายุและผู้ป่วยติดเตียงเสี่ยงที่สุด · บ้านเรือนเสียหาย ถนนและสะพานขาด</td></tr>
                  <tr><td>เกิดตอนกลางคืนขณะคนหลับ (น้ำปาด 2554 เวลา 02.00 น.) · ไฟดับ สัญญาณมือถือล่ม (ลับแล 2567)</td><td>ระบบเตือนที่พึ่งมือถือ/เน็ตอย่างเดียวใช้ไม่ได้ในตอนที่จำเป็นที่สุด · ไม่มีเครือข่ายเพื่อนบ้านที่รู้ว่าบ้านไหนต้องช่วยก่อน</td><td>ไม่มีเวลาเตรียมของและยาจำเป็น · ต้องรอเรือกู้ภัยเมื่อถนนขาด (ฟากท่า)</td></tr>
                </tbody>
              </table></div>
              <div class="card flat" style="margin-top:14px">
                <dl class="kv">
                  <dt>ปัญหาหลักที่เลือก (1 เรื่อง)</dt><dd>ผู้สูงอายุและผู้ป่วยติดเตียงในหมู่บ้านริมลำห้วยไม่ได้รับคำเตือนน้ำป่าทันเวลา โดยเฉพาะตอนกลางคืนที่ไฟดับและไม่มีอินเทอร์เน็ต</dd>
                  <dt>สำคัญเพราะ</dt><dd>คนกลุ่มนี้ใช้เวลาอพยพนานที่สุด ถ้าเตือนช้าก็ช่วยไม่ทัน</dd>
                  <dt>ขอบเขต</dt><dd>หมู่บ้านริมลำห้วยสมมติ 1 แห่งในจังหวัดอุตรดิตถ์ ช่วงฤดูฝน ทดลองเป็นแบบจำลองในโรงเรียน ไม่ใช่ระบบเตือนภัยทางการ</dd>
                </dl>
              </div>
            </div>
            <div class="why"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><p><b>ทำไมดี:</b> “ปัญหาหลัก” ไม่ได้เขียนว่า “น้ำท่วม” (นั่นคือภัย) แต่เขียนว่า<b>คนที่ไหนทำอะไรไม่ได้</b> และขอบเขตกำหนดทั้งที่ ใคร และเมื่อไร ทั้งยังบอกตรง ๆ ว่าเป็นแบบจำลอง ไม่ใช่ระบบทางการ</p></div></div>
          </div>
        </article>

        <article class="ex" id="a2-s2">
          <header class="ex-h"><span class="num-dot">2</span><h4>รู้จักผู้ใช้และมองปัญหาจากหลายมุม</h4></header>
          <div class="ex-b">
            <div class="ex-q"><b>ใบกิจกรรมถามว่า</b><p>ผู้ที่ต้องการช่วยคือใคร · ประสบปัญหาเมื่อใด · ต้องการความช่วยเหลือแบบใด และมองจากมุมอื่นอย่างน้อย 2 มุม</p></div>
            <div class="ex-a"><span class="lab">คำตอบของทีมยามน้ำ</span>
              <div class="tbl tight"><table>
                <thead><tr><th>คำถาม</th><th>คำตอบพร้อมหลักฐานจากใบที่ 1</th></tr></thead>
                <tbody>
                  <tr><td>ผู้ที่ต้องการช่วยคือใคร</td><td>ผู้สูงอายุที่อยู่คนเดียว/ผู้ป่วยติดเตียง และเพื่อนบ้านหรืออาสาสมัครที่ต้องไปช่วย (ผู้ใช้ระบบโดยตรงคืออาสาสมัคร)</td></tr>
                  <tr><td>ประสบปัญหาเมื่อใด</td><td>น้ำป่าหลาก ฝนหนักต่อเนื่อง ช่วงกลางคืน ไฟดับ ไม่มีเน็ต (เช่น น้ำปาด 2554 เวลา 02.00 น. และลับแล 2567)</td></tr>
                  <tr><td>ต้องการความช่วยเหลือแบบใด</td><td>ได้รับสัญญาณเตือนที่ได้ยินหรือเห็นได้ แม้ไม่มีเน็ต และมีคนมารับไปจุดนัดพบก่อนน้ำถึง</td></tr>
                </tbody>
              </table></div>
              <div class="tbl tight" style="margin-top:12px"><table>
                <thead><tr><th>มุมมอง</th><th>เห็นปัญหานี้อย่างไร และต้องการอะไร</th></tr></thead>
                <tbody>
                  <tr><td>1. ชุมชน/อาสาสมัคร (ผู้ใหญ่บ้าน อสม.)</td><td>กังวลว่าตื่นช้า ติดต่อใครไม่ได้ และไม่มีรายชื่อบ้านที่ต้องช่วยอยู่ที่เดียว · ต้องการรายชื่อที่ปลอดภัย เห็นได้เฉพาะอาสา ไม่เปิดเผยชื่อให้คนทั่วไป</td></tr>
                  <tr><td>2. ค่าใช้จ่าย/หน่วยงานท้องถิ่น (เทศบาล อบต.)</td><td>งบน้อย อุปกรณ์ต้องราคาไม่สูงและซ่อมเองได้ · ไม่อยากให้ระบบของนักเรียนไปแทนประกาศทางการ ต้องบอกชัดว่าเป็นต้นแบบ</td></tr>
                </tbody>
              </table></div>
            </div>
            <div class="why"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><p><b>ทำไมดี:</b> สองมุมมองให้ผลต่อการออกแบบจริง: มุมแรกทำให้เกิด “รายชื่อหลัง PIN” ในใบที่ 4 มุมที่สองทำให้ทุกข้อความต้องติดป้าย “ต้นแบบของโรงเรียน”</p></div></div>
          </div>
        </article>

        <article class="ex" id="a2-s3">
          <header class="ex-h"><span class="num-dot">3</span><h4>เขียนข้อความกำหนดปัญหา</h4></header>
          <div class="ex-b">
            <div class="ex-q"><b>ใบกิจกรรมถามว่า</b><p>เขียนให้เจาะจง ไม่ใช่แค่ชื่อภัย ตามรูปประโยค กลุ่มเป้าหมาย–ปัญหา–สถานการณ์–สาเหตุ–ผลกระทบ</p></div>
            <div class="ex-a"><span class="lab">คำตอบของทีมยามน้ำ</span>
              <p class="quote" style="font-weight:500">ผู้สูงอายุที่อยู่ตามลำพังและผู้ป่วยติดเตียงในหมู่บ้านริมลำห้วย<mark class="seg s1">ประสบปัญหา</mark>ไม่ได้รับคำเตือนน้ำป่าทันเวลา <mark class="seg s2">เมื่อ</mark>ฝนตกหนักตอนกลางคืนขณะไฟดับและไม่มีอินเทอร์เน็ต <mark class="seg s3">เนื่องจาก</mark>คำเตือนที่มีอยู่เป็นระดับอำเภอและพึ่งมือถือเป็นหลัก <mark class="seg s4">ส่งผลให้</mark>อพยพไม่ทันและเสี่ยงชีวิต</p>
              <p class="sm mute" style="margin:0"><b>ทีมตรวจแล้ว:</b> มีกลุ่มเป้าหมาย สถานการณ์ สาเหตุ และผลกระทบครบ ไม่ใช่แค่คำว่า “น้ำท่วม”</p>
            </div>
            <div class="why"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><p><b>ทำไมดี:</b> ลองทำ 3 ข้อตรวจ: ระบุผู้ใช้ชัดไหม (ใช่) ไม่ใช่แค่ชื่อภัยไหม (ใช่) ซ่อนวิธีแก้ไหม (ไม่ซ่อน ไม่มีคำว่า “แอป” “ระบบ” “สัญญาณ” เป็นวิธีแก้) ผ่านครบทุกข้อ</p></div></div>
          </div>
        </article>

        <article class="ex" id="a2-s4">
          <header class="ex-h"><span class="num-dot">4</span><h4>สร้างโจทย์ออกแบบหลายแนวทาง (How Might We)</h4></header>
          <div class="ex-b">
            <div class="ex-q"><b>ใบกิจกรรมถามว่า</b><p>“เราจะออกแบบหรือพัฒนาอะไร เพื่อให้ (ใคร) สามารถ (ทำอะไรเพื่อลดความเสี่ยง) ภายใต้ (เงื่อนไข) ได้อย่างไร?” และโจทย์ทางเลือกจากกลยุทธ์ที่ต่างกัน</p></div>
            <div class="ex-a"><span class="lab">คำตอบของทีมยามน้ำ</span>
              <p class="quote" style="font-weight:500">เราจะออกแบบสถานีวัดระดับน้ำราคาประหยัดที่ ม.2 ทำได้ เพื่อให้อาสาสมัครและเพื่อนบ้านของผู้สูงอายุได้รับสัญญาณเตือนล่วงหน้าและไปช่วยอพยพทัน ภายใต้เงื่อนไขกลางคืน ไฟดับ ไม่มีอินเทอร์เน็ต ได้อย่างไร?</p>
              <h5>โจทย์ทางเลือกจากกลยุทธ์ต่างกัน</h5>
              <div class="three">
                <div><h5>เทคโนโลยี</h5><p>ทำให้ลำห้วยบอกระดับน้ำเองได้อย่างไร</p></div>
                <div><h5>คน</h5><p>ทำให้เพื่อนบ้านดูแลกันได้อย่างไร</p></div>
                <div><h5>ประสาทสัมผัส</h5><p>เตือนด้วยเสียงและแสงอย่างไรให้คนที่ไม่มีมือถือรู้</p></div>
              </div>
            </div>
            <div class="why"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><p><b>ทำไมดี:</b> โจทย์หลักมี <b>ใคร / ทำอะไร / เงื่อนไข</b> ครบ และสามโจทย์ทางเลือก “เปิดทาง” ให้ใบที่ 3 คิดได้ต่างกลไก ได้แก่ เครื่องวัด คนช่วยคน และเสียงกับแสง ไม่ได้ถูกล็อกไว้ที่แอป</p></div></div>
          </div>
        </article>

        <article class="ex" id="a2-s5">
          <header class="ex-h"><span class="num-dot">5</span><h4>สืบค้นเชิงสร้างสรรค์ เรียนรู้จากวิธีของผู้อื่น</h4></header>
          <div class="ex-b">
            <div class="ex-q"><b>ใบกิจกรรมถามว่า</b><p>หาวิธีที่ผู้อื่นใช้กับปัญหาคล้ายกัน เทียบเหมือน/ต่าง และบอกว่านำอะไรมาปรับโจทย์ แล้วตั้งคำถาม “ถ้า...” 1 ข้อ</p></div>
            <div class="ex-a"><span class="lab">คำตอบของทีมยามน้ำ</span>
              <div class="tbl"><table>
                <thead><tr><th>วิธีของผู้อื่น (ที่มา)</th><th>เหมือน/ต่างจากของเรา</th><th>แนวคิดที่นำมาใช้</th></tr></thead>
                <tbody>
                  <tr><td>1. ปภ. ส่ง Cell Broadcast เตือนทั้งอำเภอฟากท่า (ข่าว LINE TODAY 11 ก.ค. 2568)</td><td><b>เหมือน</b> เตือนน้ำป่าเหมือนกัน · <b>ต่าง</b> เตือนทั้งอำเภอ ไม่ใช่เฉพาะลำห้วยของหมู่บ้านเรา และต้องมีมือถือ</td><td>ทำตัวเตือนเฉพาะจุด (ระดับน้ำที่ลำห้วยเรา) มาเสริม ไม่แทนของทางการ</td></tr>
                  <tr><td>2. ระบบสีของดัชนีคุณภาพอากาศ AQI (ภัยหมอกควัน/PM2.5) ที่ใช้ ฟ้า เขียว เหลือง ส้ม แดง (กรมควบคุมมลพิษ ผ่านข่าวไทยพีบีเอส)</td><td><b>ต่างภัย แต่ปัญหาคล้ายกัน</b> ต้องบอกระดับอันตรายให้คนทั่วไปเข้าใจได้เร็ว · <b>ต่าง</b> PM2.5 เปลี่ยนช้ากว่าน้ำป่ามาก</td><td>นำมาทำไฟ 3 สีและระดับ 0–3 ของระดับน้ำ ให้คนอ่านง่ายโดยไม่ต้องอ่านตัวเลข</td></tr>
                </tbody>
              </table></div>
              <div class="card flat" style="margin-top:14px">
                <p style="margin:0"><b>ถ้า...จะเป็นอย่างไร?</b> ถ้าเซนเซอร์ที่ลำห้วยพังหรือเงียบไป ระบบจะบอกว่า “ปลอดภัย” หรือไม่</p>
                <p style="margin:.6em 0 0"><b>คำตอบ:</b> ไม่ควรบอกว่าปลอดภัย เพราะ <b>“เงียบ ไม่เท่ากับ ปลอดภัย”</b> ระบบต้องแสดงสถานะ “ไม่มีข้อมูล” และบอกคนเฝ้าระวัง</p>
                <p style="margin:.6em 0 0"><b>ผล:</b> ได้โจทย์ใหม่ ต้องตรวจว่าเซนเซอร์ยังส่งข้อมูลอยู่ และไฟสถานะต้องแยกจากสีเขียว</p>
              </div>
            </div>
            <div class="why"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><p><b>ทำไมดี:</b> ตัวอย่างที่ 2 มาจาก<b>คนละภัย</b> (หมอกควัน) แต่เลือกมาเพราะปัญหาร่วมกัน และคำถาม “ถ้า...” เปลี่ยนเป็นข้อกำหนดของระบบ (สถานะ “ไม่มีข้อมูล”) ที่ไปปรากฏในใบที่ 4 และ 5</p></div></div>
          </div>
        </article>

        <article class="ex" id="a2-s6">
          <header class="ex-h"><span class="num-dot">6</span><h4>ตรวจความชัดเจนและปรับกรอบโจทย์ (Reframe)</h4></header>
          <div class="ex-b">
            <div class="ex-q"><b>ใบกิจกรรมถามว่า</b><p>ติ๊ก 5 ข้อ แล้วเขียน โจทย์ก่อนรับข้อเสนอแนะ · ใครเสนอให้มองต่าง · โจทย์หลังปรับ · เหตุผลที่ยืนยันว่าดีขึ้น</p></div>
            <div class="ex-a"><span class="lab">คำตอบของทีมยามน้ำ</span>
              <div class="pair">
                <div class="bad"><h5>โจทย์ก่อนรับข้อเสนอแนะ</h5><p style="margin:0">“ทำแอปเตือนน้ำท่วม”</p></div>
                <div class="good"><h5>โจทย์หลังปรับ</h5><p style="margin:0">ทำสถานีเตือนที่แจ้งทั้งมือถือ ไซเรนและไฟประจำหมู่บ้าน และบอกอาสาว่าต้องไปช่วยบ้านไหน</p></div>
              </div>
              <dl class="kv" style="margin-top:12px">
                <dt>ใครเสนอให้มองต่าง</dt><dd>เพื่อน ข และครู: แอปอย่างเดียวไปไม่ถึงคนที่ไม่มีมือถือ และตอนไฟดับ/ไม่มีเน็ตใช้ไม่ได้</dd>
                <dt>เหตุผลที่ดีขึ้น</dt><dd>ตรงกับคำถาม “ถ้าไม่มีเน็ต” และข่าวลับแล 2567 ที่สัญญาณโทรศัพท์ใช้ไม่ได้</dd>
              </dl>
              <p class="sm mute" style="margin:.6em 0 0">ทีมติ๊กครบ 5 ข้อ: ระบุผู้ใช้ชัด · ช่วยลดความเสี่ยงจริง · ขอบเขตพอดีกับ 15 ชั่วโมง · ทำต้นแบบจำลองได้ · ไม่อันตราย</p>
            </div>
            <div class="why"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><p><b>ทำไมดี:</b> เห็น<b>ก่อน–หลัง</b> ชัด บอกว่าใครเสนอ และมี “หลักฐาน” ที่ทำให้โจทย์ใหม่ดีขึ้น ไม่ใช่เปลี่ยนเพราะรู้สึกว่าอยากเปลี่ยน</p></div></div>
          </div>
        </article>

        <div class="callout note"><svg class="ic" aria-hidden="true"><use href="#i-arrow-r"/></svg><div><p><b>เชื่อมไปใบกิจกรรมที่ 3:</b> โจทย์หลังปรับ และโจทย์ทางเลือก 3 ข้อ (เทคโนโลยี คน ประสาทสัมผัส) คือโจทย์ที่ทุกคนจะใช้คิดแนวทางของตัวเองก่อนเปิด AI</p></div></div>
      </div>
    </div>

    <!-- ---------- A2 : HAZARDS ---------- -->
    <div class="panel" role="tabpanel" id="p-a2-hz" aria-labelledby="t-a2-hz" hidden>
      <div class="stack">
        <div class="callout note"><svg class="ic" aria-hidden="true"><use href="#i-info"/></svg><div><p>เลือกภัยเพื่อดูข้อความปัญหาและโจทย์ “เราจะ…ได้อย่างไร” ของภัยนั้น พร้อมตัวอย่างคำตอบเต็มทุกหัวข้อของใบกิจกรรมที่ 2 ทั้งหมดเป็นตัวอย่าง กลุ่มของคุณต้องเขียนจากข้อมูลที่ค้นเองในใบที่ 1</p></div></div>
        <div class="hz" data-hz-for="a2"></div>
      </div>
    </div>

    <!-- ---------- A2 : RUBRIC ---------- -->
    <div class="panel" role="tabpanel" id="p-a2-rub" aria-labelledby="t-a2-rub" hidden>
      <div class="stack">
        <div class="card soft">
          <h3>ครูดูอะไร</h3>
          <p style="margin:0">ใบนี้ประเมินเพียง <b>องค์ประกอบที่ 1 การสร้างความคิด</b> ด้วย 3 ประเด็นย่อย ครูให้ระดับ 1.0–4.0 จากหลักฐานรายบุคคลและผลงานกลุ่ม</p>
        </div>
        <div>
          <div class="lad-h"><h4>1.1 การกำหนดปัญหา</h4><span class="pill">หลักฐาน: ส่วนที่ 1–3</span></div>
          <div class="ladder">
            <div class="rung"><small>1.0 ขั้นเริ่มต้น</small>ระบุปัญหาหรือความท้าทายที่ต้องการวิธีแก้ปัญหาอย่างสร้างสรรค์ได้</div>
            <div class="rung"><small>2.0 ขั้นพื้นฐาน</small>อธิบายลักษณะของปัญหาหรือความท้าทาย และระบุข้อมูลที่จำเป็นต่อการแก้ปัญหา สิ่งที่ทราบ สิ่งที่ยังไม่ทราบหรือข้อกำหนด</div>
            <div class="rung"><small>3.0 ขั้นชำนาญ</small>อธิบายความสำคัญของปัญหาหรือความท้าทายและกำหนดขอบเขตของปัญหาได้</div>
            <div class="rung"><small>4.0 ขั้นสูง</small>อธิบายปัญหาหรือความท้าทายอย่างลึกซึ้ง โดยพิจารณาผ่านมุมมองที่หลากหลาย และสามารถปรับกรอบปัญหาให้มองจากมุมหรือจุดเริ่มต้นที่แตกต่างออกไปได้</div>
          </div>
        </div>
        <div>
          <div class="lad-h"><h4>1.2 การสร้างความคิด</h4><span class="pill">หลักฐาน: ส่วนที่ 4</span></div>
          <div class="ladder">
            <div class="rung"><small>1.0 ขั้นเริ่มต้น</small>ใช้วิธีระดมความคิดพื้นฐาน เช่น การเขียนรายการหรือแผนผัง เพื่อสร้างความคิดหนึ่งแนวทางที่เกี่ยวข้องกับปัญหา</div>
            <div class="rung"><small>2.0 ขั้นพื้นฐาน</small>สร้างความคิดหรือแนวทางใหม่ได้หลายแนวทางโดยใช้กลยุทธ์ที่กำหนดให้ เช่น brainstorming การคิดเชิงอุปมา การเข้าใจผู้อื่น การเขียน การคิดเชิงระบบ หรือการศึกษาวิธีแก้ปัญหาจากศาสตร์อื่น</div>
            <div class="rung"><small>3.0 ขั้นชำนาญ</small>สร้างความคิดหรือแนวทางที่เป็นไปได้หลายแนวทางที่สัมพันธ์กับปัญหาหรือความท้าทาย</div>
            <div class="rung"><small>4.0 ขั้นสูง</small>ใช้กลยุทธ์ที่หลากหลายเพื่อสร้างความคิดหลายแนวทางที่แตกต่างกันและสัมพันธ์กับความท้าทายอย่างชัดเจน จนเพียงพอที่จะกระตุ้นกระบวนการสร้างสรรค์</div>
          </div>
        </div>
        <div>
          <div class="lad-h"><h4>1.3 การสืบค้นเชิงสร้างสรรค์</h4><span class="pill">หลักฐาน: ส่วนที่ 5</span></div>
          <div class="ladder">
            <div class="rung"><small>1.0 ขั้นเริ่มต้น</small>สามารถบรรยายความคิด วิธีแก้ปัญหา หรือแนวทางของผู้อื่นได้</div>
            <div class="rung"><small>2.0 ขั้นพื้นฐาน</small>สามารถสร้างความคิดใหม่เมื่อได้รับมุมมองจากผู้อื่น</div>
            <div class="rung"><small>3.0 ขั้นชำนาญ</small>ศึกษาความคิด วิธีแก้ปัญหา หรือแนวทางของผู้อื่น และเปรียบเทียบปัญหาหรือความท้าทายนั้นกับปัญหาสถานการณ์ หรือความต้องการอื่น</div>
            <div class="rung"><small>4.0 ขั้นสูง</small>ตั้งและตอบคำถาม “ถ้า...จะเป็นอย่างไร?” เพื่อสร้างแนวทางแก้ปัญหาใหม่หรือทำความเข้าใจปัญหาให้ลึกขึ้น</div>
          </div>
        </div>

        <div class="card">
          <h4>เช็กลิสต์ก่อนส่งใบกิจกรรมที่ 2</h4>
          <p class="sm mute">ติ๊กได้เลย เครื่องนี้จะจำไว้ให้ในเบราว์เซอร์ของคุณ ครูไม่เห็นเช็กลิสต์นี้</p>
          <ul class="checks" data-checks="a2">
            <li><label><input type="checkbox"><span>แยก สาเหตุ / ปัญหาหลัก / ผลกระทบ ได้ และเลือกปัญหาหลักเพียง 1 เรื่องพร้อมขอบเขต (ที่ใด กับใคร เมื่อใด)</span></label></li>
            <li><label><input type="checkbox"><span>ตอบ 3 คำถามเรื่องผู้ใช้ โดยมีหลักฐานจากใบที่ 1 หรือเขียนว่าเป็นสมมติฐาน</span></label></li>
            <li><label><input type="checkbox"><span>มองปัญหาจากมุมอื่นอย่างน้อย 2 มุม</span></label></li>
            <li><label><input type="checkbox"><span>ข้อความกำหนดปัญหามีครบ 5 ส่วน ไม่ใช่แค่ชื่อภัย และไม่ซ่อนวิธีแก้</span></label></li>
            <li><label><input type="checkbox"><span>เพื่อนที่อ่านโดยไม่ฟังคำอธิบายตอบได้ว่า “ผู้ใช้คือใคร” และ “ปัญหาคืออะไร”</span></label></li>
            <li><label><input type="checkbox"><span>เขียนโจทย์ “เราจะ…ได้อย่างไร” ที่มี ใคร / ทำอะไร / เงื่อนไข และมีโจทย์ทางเลือกจากกลยุทธ์ที่ต่างกัน</span></label></li>
            <li><label><input type="checkbox"><span>เปรียบเทียบวิธีของผู้อื่นอย่างน้อย 2 วิธี (เหมือน/ต่าง) และตั้งคำถาม “ถ้า...จะเป็นอย่างไร?” พร้อมลองตอบ</span></label></li>
            <li><label><input type="checkbox"><span>ตรวจกรอบโจทย์ครบ 5 ข้อ และเขียนโจทย์ก่อน–หลังปรับพร้อมเหตุผล</span></label></li>
          </ul>
          <div class="meter" style="margin-top:14px" aria-hidden="true"><i data-meter="a2"></i></div>
          <p class="sm mute" style="margin:.5em 0 0" data-meter-text="a2">ติ๊กแล้ว 0 จาก 8 ข้อ</p>
        </div>
      </div>
    </div>

    <div class="pn">
      <a class="btn" href="#a1" data-go="a1"><svg class="ic" aria-hidden="true"><use href="#i-arrow-l"/></svg> ใบกิจกรรมที่ 1</a>
      <a class="btn pri" href="#a3" data-go="a3">ใบกิจกรรมที่ 3 คิดเอง คิดต่อกับ AI <svg class="ic" aria-hidden="true"><use href="#i-arrow-r"/></svg></a>
    </div>
  </div>
</section>
<!-- ====================== ACTIVITY 3 ====================== -->
<section class="view k3" id="v-a3" data-view="a3" hidden>
  <div class="ah k3">
    <div class="wrap ah-in">
      <div class="ah-num" aria-hidden="true">3</div>
      <div>
        <p class="stage">ขั้นที่ 3 · การสร้างและขยายแนวคิดด้วยปัญญาประดิษฐ์</p>
        <h1>คิดเอง<wbr> คิดต่อ<wbr>กับ AI</h1>
        <p class="mission-line">คิดเองก่อนเปิด AI จากนั้นแลกเปลี่ยนกับเพื่อนและใช้ AI เพื่อขยายหรือตรวจสอบ ไม่ใช่คัดลอกคำตอบโดยไม่คิด</p>
        <div class="pills">
          <span class="pill">2 ชั่วโมง</span>
          <span class="pill">ประเมิน องค์ประกอบที่ 4 การทำงานสร้างสรรค์ร่วมกับผู้อื่น</span>
          <span class="pill">เปรียบเทียบ → ผสมผสาน → ต่อยอด → สังเคราะห์</span>
        </div>
        <p style="margin:14px 0 0"><a class="btn" href="https://docs.google.com/presentation/d/1nGmlRU-OQAzPuQfKEztlUfbBJiyiDQsMnWyHxpwdaSo/edit?usp=sharing" target="_blank" rel="noopener">เปิดใบกิจกรรมที่ 3 (Google Slides) <svg class="ic" aria-hidden="true"><use href="#i-link"/></svg></a></p>
      </div>
    </div>
  </div>

  <div class="wrap">
    <div class="tabs" role="tablist" aria-label="เมนูย่อยของใบกิจกรรมที่ 3">
      <button type="button" class="tab" role="tab" id="t-a3-learn" aria-controls="p-a3-learn" aria-selected="true" data-go="a3"><svg class="ic" aria-hidden="true"><use href="#i-book"/></svg>เรียนรู้</button>
      <button type="button" class="tab" role="tab" id="t-a3-ex" aria-controls="p-a3-ex" aria-selected="false" data-go="a3-ex"><svg class="ic" aria-hidden="true"><use href="#i-search"/></svg>ตัวอย่างละเอียด</button>
      <button type="button" class="tab" role="tab" id="t-a3-hz" aria-controls="p-a3-hz" aria-selected="false" data-go="a3-hz"><svg class="ic" aria-hidden="true"><use href="#i-users"/></svg>ตัวอย่าง 4 ภัยอื่น</button>
      <button type="button" class="tab" role="tab" id="t-a3-rub" aria-controls="p-a3-rub" aria-selected="false" data-go="a3-rub"><svg class="ic" aria-hidden="true"><use href="#i-check"/></svg>เกณฑ์และเช็กลิสต์</button>
    </div>

    <!-- ---------- A3 : LEARN ---------- -->
    <div class="panel" role="tabpanel" id="p-a3-learn" aria-labelledby="t-a3-learn">
      <div class="stack">
        <div class="card">
          <p class="lede">ใบนี้ดูว่าเรา <b>ทำงานกับความคิดของผู้อื่น</b> อย่างไร ตั้งแต่เปรียบเทียบ ผสาน ต่อยอด จนสังเคราะห์ โดยมี AI เป็นแหล่งเสนอแหล่งหนึ่ง และ<b>คนในกลุ่มเป็นผู้ตรวจและเลือก</b></p>
          <div class="tbl tight"><table>
            <thead><tr><th>ส่วน</th><th>ทำอะไร</th><th>ทำกับใคร / ใช้อะไร</th></tr></thead>
            <tbody>
              <tr><td>1</td><td>คิดเอง 3 แนวทางลงบัตรรายบุคคล</td><td>ทำคนเดียว ก่อนเปิด AI</td></tr>
              <tr><td>2</td><td>เปรียบเทียบความคิดของเรากับความคิดของเพื่อน</td><td>ฟังและบันทึกร่วมกันในกลุ่ม</td></tr>
              <tr><td>3</td><td>ผสานส่วนที่ดีของเพื่อนอย่างน้อย 2 คนเข้ากับความคิดของเรา</td><td>สมาชิกในกลุ่ม</td></tr>
              <tr><td>4</td><td>ต่อยอดกับเพื่อนและ AI แล้วตรวจสอบก่อนนำไปใช้</td><td>กลุ่ม + AI (มนุษย์เป็นผู้ตรวจและเลือก)</td></tr>
              <tr><td>5</td><td>สังเคราะห์เป็น 3 แนวคิดที่แตกต่างกันจริงของกลุ่ม</td><td>ทั้งกลุ่ม</td></tr>
            </tbody>
          </table></div>
        </div>


        <div class="callout warn"><svg class="ic" aria-hidden="true"><use href="#i-warn"/></svg><div><h5>กติกาข้อแรก</h5><p>ทุกคนกรอกบัตรรายบุคคล 3 แนวคิดต่างกลไก <b>ก่อนเปิด AI และก่อนแลกเปลี่ยนความคิดกับเพื่อน</b> บัตรนี้คือ “ความคิดของฉัน” ที่ใช้เปรียบเทียบและผสานในส่วนที่ 2–5 ถ้าข้ามขั้นนี้ จะไม่มีหลักฐานว่าเรามีส่วนอะไรในแนวคิดสุดท้าย</p></div></div>

        <ul class="toc" aria-label="หัวข้อในแท็บนี้">
          <li><a href="#" data-scroll="a3-l1"><i>1</i>คิดเอง 3 กลไก</a></li>
          <li><a href="#" data-scroll="a3-l2"><i>2</i>เปรียบเทียบ</a></li>
          <li><a href="#" data-scroll="a3-l3"><i>3</i>ผสาน</a></li>
          <li><a href="#" data-scroll="a3-l4"><i>4</i>ต่อยอดกับ AI</a></li>
          <li><a href="#" data-scroll="a3-l5"><i>5</i>สังเคราะห์</a></li>
        </ul>

        <!-- 1 -->
        <div class="blk" id="a3-l1">
          <h3><span class="num-dot">1</span>คิดเอง 3 แนวทาง ที่ “กลไก” ต่างกัน</h3>
          <div class="card soft">
            <p class="sm mute" style="margin:0 0 .4em">โจทย์ตัวอย่าง (ทีมช่วยเหลือ น้ำป่า อ.ท่าปลา)</p>
            <p style="margin:0"><b>เราจะช่วยให้อาสาสมัครรู้ได้อย่างไรว่าบ้านใดต้องได้รับความช่วยเหลือก่อน</b> ในช่วงที่น้ำป่าตัดเส้นทางและโทรศัพท์อาจใช้ไม่ได้</p>
            <p class="sm" style="margin:.6em 0 0">เงื่อนไข: ไม่ทดลองกับน้ำท่วมจริง · ไม่ใช้ไฟบ้าน · ไม่ใช้ข้อมูลส่วนบุคคลจริง · ต้องสร้างเป็นแบบจำลองได้</p>
          </div>
          <div class="pair">
            <div class="bad"><h5>ไม่นับว่าต่างกัน</h5><p style="margin:0">ป้ายเตือนสีแดง / ป้ายเตือนสีเหลือง / ป้ายเตือนสีฟ้า</p><p class="sm" style="margin:.5em 0 0">ทั้งหมดอาศัย “ป้ายสี” เหมือนกัน ต่างกันแค่สี</p></div>
            <div class="good"><h5>ต่างกันที่หลักการทำงาน</h5><p style="margin:0">ใช้ป้ายสัญลักษณ์ให้มองเห็น / ใช้เพื่อนบ้านส่งข่าว / ใช้แผนที่ที่เตรียมไว้ล่วงหน้า</p></div>
          </div>
          <div class="quiz" data-quiz="c">
            <h5><span class="pill">ลองตอบ</span> ชุดไหนคือ “3 แนวคิดที่ต่างกันจริง” สำหรับโจทย์เดียวกัน</h5>
            <div class="opts">
              <button type="button" class="opt" data-k="a"><span class="k">ก</span><span>ไฟสีแดง · ไฟสีเหลือง · ไฟสีเขียว แขวนหน้าบ้าน</span></button>
              <button type="button" class="opt" data-k="b"><span class="k">ข</span><span>ป้ายผ้าสีใหญ่ · ป้ายผ้าสีเล็ก · ป้ายผ้ามีลวดลาย</span></button>
              <button type="button" class="opt" data-k="c"><span class="k">ค</span><span>ป้ายผ้าสีที่อาสามองเห็น · แผนที่จุดสีที่เตรียมก่อนฤดูฝน · เพื่อนบ้านคู่ดูแลที่ส่งข่าวให้กัน</span></button>
            </div>
            <div class="fb" hidden><b class="fb-h"></b><p>ข้อ ค ใช้กลไกต่างกันสามแบบ คือ <b>สายตา</b> ของอาสาสมัคร <b>ข้อมูลที่เตรียมไว้</b> และ <b>คนส่งต่อ</b> ส่วนข้อ ก และ ข เปลี่ยนแค่สีหรือรูปร่าง กลไกเหมือนเดิม</p></div>
          </div>
          <div class="tbl"><table>
            <thead><tr><th>แนวคิด</th><th>ชื่อวิธี / ทำงานอย่างไร / ช่วยใคร / เหตุผล (ตัวอย่าง)</th></tr></thead>
            <tbody>
              <tr><td>1</td><td><b>ป้ายผ้าสีหน้าบ้าน</b> ครอบครัวแขวนป้ายสีส้มที่ชายคาเมื่อมีผู้ต้องช่วย ช่วยอาสาสมัครบนเรือ เพราะเห็นได้โดยไม่ต้องอ่านหรือมีสัญญาณ <span class="pill">กลไก: สัญลักษณ์ที่มองเห็น</span></td></tr>
              <tr><td>2</td><td><b>แผนที่หมู่บ้านจุดสี</b> ผู้ใหญ่บ้านหรือ อสม. ทำแผนที่ล่วงหน้าก่อนฤดูฝน ติดจุดสีที่บ้านที่ต้องช่วยก่อน ช่วยอาสาสมัครวางเส้นทางเรือ เพราะไม่ต้องไล่ถามทีละบ้านตอนน้ำขึ้น <span class="pill">กลไก: ข้อมูลล่วงหน้า</span></td></tr>
              <tr><td>3</td><td><b>เพื่อนบ้านคู่ดูแล</b> จับคู่บ้านใกล้กัน ให้เพื่อนบ้านเป็นผู้แจ้งหาอาสาสมัครเมื่อบ้านคู่ต้องการความช่วยเหลือ ช่วยครอบครัวที่ติดต่อไม่ได้ เพราะมีคนรู้จักคอยดู <span class="pill">กลไก: คนส่งต่อ</span></td></tr>
              <tr><td>ต่างกันอย่างไร</td><td>แนวคิด 1 ใช้สายตาของอาสาสมัคร · แนวคิด 2 ใช้ข้อมูลที่เตรียมไว้ก่อน · แนวคิด 3 ใช้เครือข่ายคน ไม่ใช่แค่ต่างชื่อหรือสี</td></tr>
            </tbody>
          </table></div>
          <div class="copy-row">
            <div><b>แม่แบบบัตรคิดเองรายบุคคล (คัดลอกไปวางในสมุดหรือเอกสารของตัวเอง)</b>
              <q id="a3-card-tpl">แนวคิดที่ 1: ชื่อวิธี / ทำงานอย่างไร / ช่วยใคร / เหตุผล (เขียนโดยไม่ใช้ AI)
แนวคิดที่ 2: ชื่อวิธี / ทำงานอย่างไร / ช่วยใคร / เหตุผล (เขียนโดยไม่ใช้ AI)
แนวคิดที่ 3: ชื่อวิธี / ทำงานอย่างไร / ช่วยใคร / เหตุผล (เขียนโดยไม่ใช้ AI)
ทั้ง 3 แนวคิดต่างกันตรงหลักการทำงานหรือวิธีช่วยผู้ใช้อย่างไร (ไม่ใช่แค่ชื่อหรือสี):
เริ่มคิดเวลา ____ ส่งบัตรเวลา ____ [ ] ก่อนเปิด AI</q></div>
            <button type="button" class="btn sm" data-copy="a3-card-tpl"><svg class="ic" aria-hidden="true"><use href="#i-copy"/></svg> คัดลอก</button>
          </div>
        </div>

        <!-- 2 -->
        <div class="blk" id="a3-l2">
          <h3><span class="num-dot">2</span>เปรียบเทียบความคิดของเรากับของเพื่อน</h3>
          <p>สมาชิกแต่ละคนเล่าแนวคิดที่ตนชอบที่สุด 1 ข้อ ทุกคนฟังให้ครบ แล้วบันทึกว่า <b>เหมือนหรือต่างจากความคิดของตนเองอย่างไร</b> และกลุ่มเห็นว่าน่าสนใจตรงไหน</p>
          <div class="callout idea"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><h5>ตัวอย่างสรุป</h5><p><b>จุดร่วม:</b> ทุกคนพยายามให้อาสาสมัครรู้ว่าบ้านไหนต้องช่วย โดยไม่ต้องใช้โทรศัพท์</p><p><b>จุดต่าง:</b> แต่ละคนแก้ปัญหาต่างช่วงเวลา ป้ายผ้าแก้ตอนกลางวัน นกหวีดและแผ่นสะท้อนแสงแก้ตอนกลางคืน ฯลฯ</p><p><b>จุดอ่อนที่เห็นจากการเทียบ:</b> กลางคืนมองไม่เห็นป้าย · ฝนทำให้เสียงดังมาก จึงอาจกลบเสียงนกหวีด</p></div></div>
        </div>

        <!-- 3 -->
        <div class="blk" id="a3-l3">
          <h3><span class="num-dot">3</span>ผสานความคิด ไม่ใช่เอามากองรวมกัน</h3>
          <div class="pair">
            <div class="bad"><h5>กองรวม</h5><p style="margin:0">“เอาป้าย + นกหวีด + แผนที่ + ไฟ + แอป มาใส่รวมกัน”</p><p class="sm" style="margin:.5em 0 0">ยังไม่ตอบว่าแต่ละส่วนช่วยแก้ปัญหาจุดใด และอาจทำให้ระบบซับซ้อนเกินไป</p></div>
            <div class="good"><h5>ผสาน</h5><p style="margin:0">“ป้ายมองเห็นได้ แต่มีจุดอ่อนตอนกลางคืน เพิ่มแถบสะท้อนแสงของเพื่อน และใช้สัญญาณเสียงในกรณีป้ายมองไม่เห็น”</p><p class="sm" style="margin:.5em 0 0">ทุกส่วนที่เพิ่ม ตอบจุดอ่อนของความคิดเดิมได้</p></div>
          </div>
          <div class="card">
            <h4>ตัวอย่างการผสาน</h4>
            <div class="grid g2">
              <div class="card flat"><b class="sm">เจ้าของแนวคิดที่ 1 · ข</b><p class="sm" style="margin:.3em 0 0">เลือกส่วน “เป่านกหวีด 3 ครั้งเมื่อได้ยินเสียงเรือ”</p></div>
              <div class="card flat"><b class="sm">เจ้าของแนวคิดที่ 2 · ค</b><p class="sm" style="margin:.3em 0 0">เลือกส่วน “แถบสะท้อนแสง”</p></div>
            </div>
            <p style="margin:12px 0 0"><b>ความคิดใหม่:</b> ป้ายผ้าสีส้มติดแถบสะท้อนแสงที่ขอบ (แก้จุดอ่อนของความคิดฉันตอนมืด) ร่วมกับสัญญาณนกหวีด 3 ครั้งเมื่อเรือเข้าใกล้ (แก้กรณีป้ายอยู่ในที่มองไม่เห็น)</p>
            <p style="margin:.5em 0 0"><b>สิ่งที่ฉันเติมเอง:</b> แขวนป้ายที่ชายคาให้เรือเห็นจากระดับสายตา <span class="tag-sim">ข้อสันนิษฐาน ต้องตรวจก่อนใช้</span></p>
            <p class="sm mute" style="margin:.6em 0 0">ทดสอบว่าผสานจริง: ถ้าเอาแถบสะท้อนแสงออก ป้ายจะใช้ไม่ได้ตอนมืด · ถ้าเอานกหวีดออก ป้ายจะไม่มีสัญญาณเมื่อเรือมองไม่เห็น ทุกส่วนมีหน้าที่</p>
          </div>
          <div class="quiz" data-quiz="b">
            <h5><span class="pill">ลองตอบ</span> ข้อใดคือการ “ผสาน” ที่ดี</h5>
            <div class="opts">
              <button type="button" class="opt" data-k="a"><span class="k">ก</span><span>เอาทุกแนวคิดของทุกคนมารวมเป็นระบบเดียว ให้ครบทุกอย่าง</span></button>
              <button type="button" class="opt" data-k="b"><span class="k">ข</span><span>เลือกส่วนของเพื่อน 2 คนที่แก้จุดอ่อนของความคิดเรา แล้วบอกได้ว่าแต่ละส่วนแก้อะไร</span></button>
              <button type="button" class="opt" data-k="c"><span class="k">ค</span><span>เลือกแนวคิดของคนที่เสียงดังที่สุดในกลุ่ม</span></button>
            </div>
            <div class="fb" hidden><b class="fb-h"></b><p>การผสานที่ดีต้องมีเหตุผลรองรับว่าแต่ละส่วนมีหน้าที่อะไร และต้องใช้ส่วนของเพื่อนอย่างน้อย 2 คน การกองรวมทุกอย่างหรือเลือกตามเสียงดังไม่ใช่การทำงานสร้างสรรค์ร่วมกัน</p></div>
          </div>
        </div>

        <!-- 4 -->
        <div class="blk" id="a3-l4">
          <h3><span class="num-dot">4</span>ต่อยอดกับเพื่อนและ AI อย่างรู้เท่าทัน</h3>
          <div class="grid g3">
            <div class="card" style="--c:var(--a3)"><h4><span class="num-dot">1</span> ไม่ใส่ข้อมูลส่วนตัว</h4><p class="sm" style="margin:0">ไม่พิมพ์ชื่อจริง ที่อยู่ เบอร์โทร หรือข้อมูลสุขภาพของบุคคลจริงลงในคำสั่ง</p></div>
            <div class="card" style="--c:var(--a3)"><h4><span class="num-dot">2</span> ตรวจก่อนเชื่อ</h4><p class="sm" style="margin:0">AI อาจตอบผิดหรือแต่งข้อมูล โดยเฉพาะเรื่องความปลอดภัย การอพยพ ชื่อหน่วยงาน และตัวเลข</p></div>
            <div class="card" style="--c:var(--a3)"><h4><span class="num-dot">3</span> กลุ่มเป็นคนเลือก</h4><p class="sm" style="margin:0">ใช้ AI เป็นแหล่งเสนอความคิดเพิ่ม สมาชิกกลุ่มต้องตรวจ เลือก ปรับ หรือไม่รับ</p></div>
          </div>

          <div class="pair">
            <div class="bad"><h5>คำสั่งกว้างเกินไป</h5><p style="margin:0">“ช่วยคิดเครื่องเตือนภัย”</p><p class="sm" style="margin:.5em 0 0">ยังไม่ระบุผู้ใช้ สถานการณ์ ข้อจำกัด หลักการที่ต้องการ หรือรูปแบบคำตอบ</p></div>
            <div class="good"><h5>คำสั่งที่ชัด</h5><p style="margin:0">“ช่วยเสนอ 5 วิธีต่างหลักการ เพื่อให้ทีมช่วยเหลือสื่อสารกับบ้านเป้าหมายได้ แม้อินเทอร์เน็ตขัดข้อง โดยนักเรียน ม.2 ทำแบบจำลองจากวัสดุราคาถูก ตอบเป็นตาราง”</p></div>
          </div>
          <div class="copy-row">
            <div><b>ตัวอย่างคำสั่งถึง AI (สมมติฐาน) · ปรับให้เป็นของกลุ่มคุณก่อนใช้</b>
              <q id="a3-prompt-ex">ผู้ใช้คือผู้สูงอายุที่อยู่ลำพังและอาสาสมัครที่พายเรือท้องแบนเข้าช่วยในหมู่บ้านที่ถนนถูกตัดและน้ำสูงกว่า 2 เมตร ตอนกลางคืนอาจไม่มีไฟฟ้าและไม่มีสัญญาณโทรศัพท์ ช่วยเสนอ 5 วิธีที่ทำให้อาสาสมัครรู้ว่าบ้านไหนต้องช่วยก่อน โดยใช้หลักการทำงานต่างกัน นักเรียน ม.2 ทำเป็นต้นแบบจำลองจากวัสดุราคาถูกได้ ไม่ใช้ไฟบ้าน ตอบเป็นตารางสั้น ๆ ภาษาไทย มีชื่อวิธีและหลักการ</q></div>
            <button type="button" class="btn sm" data-copy="a3-prompt-ex"><svg class="ic" aria-hidden="true"><use href="#i-copy"/></svg> คัดลอก</button>
          </div>

          <h4>ฝึกตัดสินใจ: รับ / ปรับ / ไม่รับ ข้อเสนอของ AI</h4>
          <p class="mute" style="margin:0">ตัวอย่าง 5 ข้อเสนอ ลองตัดสินด้วยเกณฑ์ ปลอดภัย · ตรงผู้ใช้ · ทรัพยากร ก่อนกดดูเหตุผล</p>

          <div class="quiz" data-quiz="b">
            <h5><span class="pill">ข้อเสนอ 1</span> ธง/ป้ายผ้าสีแขวนหน้าบ้านบอกระดับความต้องการช่วย</h5>
            <div class="opts"><button type="button" class="opt" data-k="a"><span class="k">รับ</span><span>ใช้ได้เลย</span></button><button type="button" class="opt" data-k="b"><span class="k">ปรับ</span><span>ใช้ แต่ต้องแก้บางอย่าง</span></button><button type="button" class="opt" data-k="c"><span class="k">ไม่รับ</span><span>ไม่เหมาะ</span></button></div>
            <div class="fb" hidden><b class="fb-h"></b><p><b>ปรับ</b> ผู้สูงอายุใช้ได้โดยไม่ต้องมีโทรศัพท์ วัสดุหาง่าย แต่ความหมายของสีต้องตกลงให้ตรงกัน · ตรวจโดย: ถามผู้ใหญ่บ้านจำลอง (ครู) เรื่องความหมายสี และลดเหลือ 3 สถานะ</p></div>
          </div>
          <div class="quiz" data-quiz="c">
            <h5><span class="pill">ข้อเสนอ 2</span> แอปแจ้งพิกัดบ้านส่งตรงถึงอาสาสมัคร ลดเวลาค้นหาได้ 90%</h5>
            <div class="opts"><button type="button" class="opt" data-k="a"><span class="k">รับ</span><span>ใช้ได้เลย</span></button><button type="button" class="opt" data-k="b"><span class="k">ปรับ</span><span>ใช้ แต่ต้องแก้บางอย่าง</span></button><button type="button" class="opt" data-k="c"><span class="k">ไม่รับ</span><span>ไม่เหมาะ</span></button></div>
            <div class="fb" hidden><b class="fb-h"></b><p><b>ไม่รับ</b> ผู้ใช้อาจไม่มีสมาร์ตโฟน สัญญาณอาจหาย ทำแอปไม่ทันใน 5 ชั่วโมง และตัวเลข 90% ไม่มีแหล่งที่มา · ตรวจโดย: ถามกลับ AI ว่าตัวเลขมาจากไหน ไม่มีที่มา จึงไม่นำข้ออ้างนี้ไปใช้</p></div>
          </div>
          <div class="quiz" data-quiz="b">
            <h5><span class="pill">ข้อเสนอ 3</span> นกหวีดรหัส (1 ครั้ง = ปลอดภัย · 3 ครั้ง = ต้องการช่วย)</h5>
            <div class="opts"><button type="button" class="opt" data-k="a"><span class="k">รับ</span><span>ใช้ได้เลย</span></button><button type="button" class="opt" data-k="b"><span class="k">ปรับ</span><span>ใช้ แต่ต้องแก้บางอย่าง</span></button><button type="button" class="opt" data-k="c"><span class="k">ไม่รับ</span><span>ไม่เหมาะ</span></button></div>
            <div class="fb" hidden><b class="fb-h"></b><p><b>ปรับ</b> ไม่ใช้ไฟฟ้า ราคาถูก แต่เสียงฝนและน้ำอาจกลบ · ตรวจโดย: ใช้คู่กับป้ายผ้าสีเป็นตัวยืนยัน และลองเป่าในห้องที่เปิดเสียงรบกวนจำลอง</p></div>
          </div>
          <div class="quiz" data-quiz="c">
            <h5><span class="pill">ข้อเสนอ 4</span> ติดไซเรนไฟฟ้า 220 โวลต์ริมตลิ่ง ต่อกับเซนเซอร์ระดับน้ำ</h5>
            <div class="opts"><button type="button" class="opt" data-k="a"><span class="k">รับ</span><span>ใช้ได้เลย</span></button><button type="button" class="opt" data-k="b"><span class="k">ปรับ</span><span>ใช้ แต่ต้องแก้บางอย่าง</span></button><button type="button" class="opt" data-k="c"><span class="k">ไม่รับ</span><span>ไม่เหมาะ</span></button></div>
            <div class="fb" hidden><b class="fb-h"></b><p><b>ไม่รับ</b> ไฟบ้านอันตราย โดยเฉพาะในที่น้ำท่วม และ ม.2 ทำเองไม่ได้ · ตรวจ/ปรับ: ไม่ปรับเป็นไฟบ้าน ใช้เสียงนกหวีดแทน</p></div>
          </div>
          <div class="quiz" data-quiz="a">
            <h5><span class="pill">ข้อเสนอ 5</span> เพื่อนบ้านคู่ดูแล ทุกบ้านจับคู่กับเพื่อนบ้านที่แข็งแรงกว่า</h5>
            <div class="opts"><button type="button" class="opt" data-k="a"><span class="k">รับ</span><span>ใช้ได้เลย</span></button><button type="button" class="opt" data-k="b"><span class="k">ปรับ</span><span>ใช้ แต่ต้องแก้บางอย่าง</span></button><button type="button" class="opt" data-k="c"><span class="k">ไม่รับ</span><span>ไม่เหมาะ</span></button></div>
            <div class="fb" hidden><b class="fb-h"></b><p><b>รับ</b> ไม่พึ่งอุปกรณ์ เหมาะกับผู้สูงอายุที่อยู่ลำพัง · นำไปจัดเป็นแนวคิดที่ 3 ในส่วนที่ 5</p></div>
          </div>

          <div class="card">
            <h4>ผังที่มาของความคิดใหม่ (ตัวอย่าง)</h4>
            <div class="tbl tight"><table>
              <thead><tr><th>ความคิดตั้งต้นของใคร</th><th>ส่วนที่ต่อยอดจากเพื่อน/AI</th><th>ข้อค้นพบใหม่</th></tr></thead>
              <tbody>
                <tr><td>ก ป้ายผ้าสี · ข นกหวีด · ค แถบสะท้อนแสง</td><td>AI เตือนว่าเสียงอาจถูกกลบ</td><td>เดิมป้ายบอกได้แค่ “ต้องช่วย” จึงเพิ่มสถานะที่ 3 คือผ้าสีเขียว “ช่วยแล้ว” (3 สถานะ)</td></tr>
              </tbody>
            </table></div>
            <p class="sm" style="margin:.7em 0 0"><b>AI ช่วยตรงไหน:</b> AI ช่วยเสนอวิธีที่เราคิดไม่ถึง (แอป เพื่อนบ้านคู่ดูแล) และเตือนเรื่องเสียงถูกกลบ แต่ AI ไม่ได้ตัดสินว่าข้อไหนใช้ กลุ่มตัดสินเองด้วยกติกา 3 ข้อ ส่วนสถานะ “ช่วยแล้ว” กลุ่มคิดเอง AI ไม่ได้เสนอ</p>
          </div>
        </div>

        <!-- 5 -->
        <div class="blk" id="a3-l5">
          <h3><span class="num-dot">5</span>สังเคราะห์เป็น 3 แนวคิดที่แตกต่างกันจริง</h3>
          <p>ส่วนนี้เป็น 3 แนวทางของ<b>กลุ่ม</b> ส่วนรายบุคคลให้ตรวจบัตรคิดเอง 3 แนวทางของแต่ละคน ไม่ใช้ผลรวมกลุ่มแทนความคิดของคนใดคนหนึ่ง</p>
          <div class="tbl"><table>
            <thead><tr><th>แนวคิด / หลักการ</th><th>ที่มา (ใครคิด ใครต่อยอดส่วนไหน)</th><th>เหมาะกับใคร ลดความเสี่ยงอย่างไร</th></tr></thead>
            <tbody>
              <tr><td><b>1</b> ป้ายผ้า 3 สถานะ + แถบสะท้อนแสง + นกหวีดรหัส · ใช้สายตาและเสียงสื่อสารทางเดียวจากบ้านถึงเรือ</td><td>ก ป้ายผ้า · ข นกหวีด · ค แถบสะท้อนแสง · กลุ่มเพิ่มสถานะ “ช่วยแล้ว”</td><td>ผู้สูงอายุอยู่ลำพังไม่มีโทรศัพท์ · ลดโอกาสที่เรือเข้าผิดบ้านหรือกลับไปบ้านเดิม</td></tr>
              <tr><td><b>2</b> แผนที่หมู่บ้านจุดสีที่ศาลากลาง ผู้รายงานประจำซอยติดจุดสีตามสถานการณ์ · ใช้ข้อมูลรวมศูนย์</td><td>ก แผนที่จุดสี · ข ให้ซอยละ 1 คนรายงาน · ข้อเสนอผู้รายงานประจำซอยจาก AI (ปรับ)</td><td>ผู้นำชุมชนและศูนย์ประสาน · ลำดับความสำคัญชัดเจนก่อนออกเรือ</td></tr>
              <tr><td><b>3</b> เพื่อนบ้านคู่ดูแล · ใช้เครือข่ายคน ไม่พึ่งอุปกรณ์</td><td>ค จับคู่เพื่อนบ้าน · AI ข้อ 5 · กลุ่มเพิ่มบัตรรายชื่อคู่ไว้ที่ศาลา</td><td>หมู่บ้านที่บ้านอยู่ใกล้กัน · ลดความเสี่ยงตอนสัญญาณและไฟฟ้าหาย</td></tr>
            </tbody>
          </table></div>
          <div class="callout idea"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><h5>แนวคิดที่ภูมิใจที่สุด ต้องระบุสิ่งที่ “คิดเอง” ให้ชัด</h5><p>ตัวอย่าง: สถานะผ้าเขียว “ช่วยแล้ว” เพราะก่อนผสานเรามีแค่บอกว่าต้องช่วย ส่วนนี้พวกเราคิดเอง AI ไม่ได้เสนอ</p></div></div>
        </div>
      </div>
    </div>

    <!-- ---------- A3 : WORKED EXAMPLE ---------- -->
    <div class="panel" role="tabpanel" id="p-a3-ex" aria-labelledby="t-a3-ex" hidden>
      <div class="stack">
        <div class="card soft">
          <span class="tag-sim">ตัวอย่างเพื่อการเรียนรู้</span>
          <h3 style="margin-top:10px">ทีมยามน้ำ คิดเอง คิดต่อกับ AI</h3>
          <p class="mute" style="margin:0">คำตอบนี้เขียนจากมุมของ “นักเรียน ค” ในตัวอย่างน้ำท่วม ทีมมี 4 คน (ก ข ค ง) แต่ละคนคิดบัตรของตัวเองก่อนแล้วจึงนำมาเทียบ</p>
        </div>
        <ul class="toc" aria-label="ส่วนของใบกิจกรรมที่ 3">
          <li><a href="#" data-scroll="a3-s1"><i>1</i>บัตรคิดเอง</a></li>
          <li><a href="#" data-scroll="a3-s2"><i>2</i>เปรียบเทียบ</a></li>
          <li><a href="#" data-scroll="a3-s3"><i>3</i>ผสาน</a></li>
          <li><a href="#" data-scroll="a3-s4"><i>4</i>ต่อยอดกับ AI</a></li>
          <li><a href="#" data-scroll="a3-s5"><i>5</i>สังเคราะห์</a></li>
        </ul>

        <article class="ex" id="a3-s1">
          <header class="ex-h"><span class="num-dot">1</span><h4>บัตรคิดเองก่อนใช้ AI (รายบุคคล)</h4></header>
          <div class="ex-b">
            <div class="ex-q"><b>ใบกิจกรรมถามว่า</b><p>คิดเอง 3 แนวทางโดยให้กลไกช่วยลดความเสี่ยงต่างกัน เขียนชื่อวิธี หลักการทำงาน ผู้ใช้ และเหตุผล</p></div>
            <div class="ex-a"><span class="lab">คำตอบของทีมยามน้ำ</span>
              <div class="three">
                <div><h5>1. เสาวัดน้ำสี 3 ระดับ</h5><p>เขียว เหลือง แดง ที่สะพานหรือฝายหมู่บ้าน ผู้ใหญ่บ้านหรืออาสาถ่ายรูปส่งกลุ่มไลน์เมื่อฝนตกหนัก</p><p class="sm mute" style="margin:.4em 0 0">ช่วย: ชาวบ้านและอาสา · เข้าใจง่ายเหมือนสี AQI ใช้ได้เมื่อไฟดับ แต่ต้องมีคนไปดูด้วยตา</p></div>
                <div><h5>2. กล่องเตือนอัตโนมัติที่ตลิ่ง</h5><p>เซนเซอร์วัดระยะน้ำ + บัซเซอร์ + ไฟ เมื่อน้ำสูงเกินระดับ บอร์ดส่งเสียงและไฟทันที</p><p class="sm mute" style="margin:.4em 0 0">ช่วย: คนใกล้ลำห้วย รวมคนไม่มีมือถือ · ไม่ต้องพึ่งอินเทอร์เน็ต ใช้พาวเวอร์แบงก์ 5 V ได้</p></div>
                <div><h5>3. เพื่อนบ้านดูแลกัน</h5><p>จับคู่บ้านผู้สูงอายุกับเพื่อนบ้าน 1 บ้าน ได้ยินสัญญาณเตือนแล้วต้องไปเคาะประตูและพาไปจุดนัดพบ</p><p class="sm mute" style="margin:.4em 0 0">ช่วย: ผู้สูงอายุ ผู้ป่วยติดเตียง ผู้ได้ยินไม่ชัด · คนช่วยถึงตัวได้ แม้เทคโนโลยีไม่ทำงาน</p></div>
              </div>
              <p style="margin-top:12px"><b>ต่างกันที่กลไก ไม่ใช่แค่ชื่อหรือสี:</b> (1) คนสังเกตด้วยตา ไม่ใช้ไฟฟ้า (2) เครื่องวัดและเตือนอัตโนมัติที่หน้างาน (3) เครือข่ายคนที่ช่วยถึงตัว · แต่ละแบบแก้จุดอ่อนของอีกแบบ: (1) ต้องมีคนไปดู (2) ไม่รู้ว่าบ้านไหนต้องช่วย (3) ต้องรู้ก่อนจึงจะไปช่วยได้</p>
              <p class="sm mute" style="margin:0">บันทึกเวลา: เริ่มคิด 09.10 · ส่งบัตร 09.30 · ติ๊ก “ก่อนเปิด AI” แล้ว</p>
            </div>
            <div class="why"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><p><b>ทำไมดี:</b> สามแนวคิดใช้กลไกต่างกันจริง (ตา เครื่อง คน) และเขียน<b>จุดอ่อนของตัวเอง</b>ไว้ด้วย ทำให้ส่วนผสานต่อมามี “ช่องว่าง” ให้เติม และมีเวลาบันทึกเป็นหลักฐานว่าคิดก่อนเปิด AI</p></div></div>
          </div>
        </article>

        <article class="ex" id="a3-s2">
          <header class="ex-h"><span class="num-dot">2</span><h4>เปรียบเทียบความคิดของเรากับของเพื่อน</h4></header>
          <div class="ex-b">
            <div class="ex-q"><b>ใบกิจกรรมถามว่า</b><p>แต่ละคนเล่าแนวคิดที่ชอบที่สุด 1 ข้อ บันทึกว่าเหมือน/ต่างจากของเราอย่างไร และกลุ่มเห็นอะไรน่าสนใจ</p></div>
            <div class="ex-a"><span class="lab">คำตอบของทีมยามน้ำ (ในมุมของ ค)</span>
              <div class="tbl"><table>
                <thead><tr><th>ผู้เสนอ</th><th>ข้อเสนอ</th><th>เหมือน/ต่างจากของฉัน</th><th>ที่กลุ่มเห็นว่าน่าสนใจ</th></tr></thead>
                <tbody>
                  <tr><td>ก</td><td>ส่งแจ้งเตือนเข้า Telegram/LINE เมื่อน้ำถึงระดับเหลือง/แดง</td><td>เหมือน: ใช้เซนเซอร์วัดน้ำ · ต่าง: ของ ก ต้องใช้เน็ต ของฉันทำงานที่ตลิ่งโดยไม่ใช้เน็ต</td><td>ผู้ใหญ่บ้านที่ไม่อยู่หมู่บ้านก็รู้ได้</td></tr>
                  <tr><td>ข</td><td>ไซเรนและไฟ 3 สีกลางหมู่บ้าน ทำงานตามระดับน้ำ</td><td>เหมือน: เตือนด้วยเสียง · ต่าง: ของ ข ดังทั้งหมู่บ้าน ของฉันดังเฉพาะที่ตลิ่ง</td><td>คนทั้งหมู่บ้านรู้พร้อมกัน ไม่ต้องมีมือถือ</td></tr>
                  <tr><td>ค</td><td>กำหนดจุดนัดพบและซ้อมอพยพทุกต้นฤดูฝน</td><td>ต่างมาก: ไม่ใช้เทคโนโลยีเลย แต่เสริมกับของฉันได้</td><td>งานวิจัยที่ไทยพีบีเอสอ้างว่า รู้จุดนัดพบทำให้อพยพมากขึ้น</td></tr>
                  <tr><td>ง</td><td>ไฟกะพริบแรงสำหรับผู้ที่ได้ยินเสียงไม่ชัด</td><td>ต่าง: คิดจากผู้ใช้กลุ่มที่ 2 ส่วนของฉันคิดจากเสียงบัซเซอร์</td><td>เสียงอย่างเดียวไม่พอ ต้องมีแสงด้วย</td></tr>
                </tbody>
              </table></div>
              <p style="margin-top:12px"><b>จุดร่วม:</b> ทุกคนต้องการให้ “รู้ก่อนน้ำมา” และไม่รอประกาศทางการอย่างเดียว · <b>จุดต่าง:</b> ช่องทางที่ใช้ (มือถือ เสียง แสง คน) และพึ่งไฟฟ้า/เน็ตหรือไม่ · <b>ช่องว่าง:</b> ยังไม่มีใครคิดเรื่องเก็บรายชื่อบ้านเปราะบางให้ปลอดภัย</p>
            </div>
            <div class="why"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><p><b>ทำไมดี:</b> ช่อง “เหมือน/ต่าง” ไม่ได้เขียนว่า “ดี” หรือ “ไม่ดี” แต่เทียบกลไกทีละจุด และกลุ่มหา <b>ช่องว่าง</b> ที่ไม่มีใครคิด ซึ่งเป็นจุดเริ่มต้นของความคิดใหม่</p></div></div>
          </div>
        </article>

        <article class="ex" id="a3-s3">
          <header class="ex-h"><span class="num-dot">3</span><h4>ผสานความคิดของสมาชิก</h4></header>
          <div class="ex-b">
            <div class="ex-q"><b>ใบกิจกรรมถามว่า</b><p>เลือกส่วนที่ดีจากเพื่อนอย่างน้อย 2 คนมาผสานกับความคิดตนเอง แล้วอธิบายความคิดใหม่ที่เกิดขึ้น</p></div>
            <div class="ex-a"><span class="lab">คำตอบของทีมยามน้ำ</span>
              <div class="three">
                <div><h5>จาก ก</h5><p><b>ส่วนที่เลือก:</b> ส่งแจ้งเตือนเข้ามือถือ</p><p class="sm" style="margin:0"><b>เหตุผล:</b> อาสาที่ไม่อยู่หมู่บ้านก็รู้ · <b>ปรับ:</b> ส่งตามระดับ 1–3 ไม่ส่งซ้ำรัว ๆ</p></div>
                <div><h5>จาก ข</h5><p><b>ส่วนที่เลือก:</b> ไซเรนและไฟ 3 สี</p><p class="sm" style="margin:0"><b>เหตุผล:</b> คนไม่มีมือถือก็รู้ · <b>ปรับ:</b> ให้ไฟ “ไม่มีข้อมูล” สลับสี ไม่ติดเขียว</p></div>
                <div><h5>จาก ง</h5><p><b>ส่วนที่เลือก:</b> ไฟกะพริบสำหรับผู้ที่ได้ยินไม่ชัด</p><p class="sm" style="margin:0"><b>เหตุผล:</b> ครอบคลุมผู้ใช้กลุ่มที่ 2 · <b>ปรับ:</b> ใช้ไฟ LED ควบคู่กับเสียง</p></div>
              </div>
              <p style="margin-top:12px"><b>ความคิดใหม่ “เพื่อนบ้านเตือนภัย”</b> = กล่องเซนเซอร์ที่ลำห้วย (ของฉัน) + แจ้งเตือนมือถืออาสา (ของ ก) + ไซเรนและไฟ 3 สีประจำหมู่บ้าน (ของ ข และ ง)</p>
              <p style="margin:0"><b>ผลที่ได้:</b> มีทั้งเตือนในพื้นที่และเตือนทางไกล ถ้าเน็ตหลุดกล่องที่ตลิ่งยังส่งเสียงเอง · ส่วนของ ค (จุดนัดพบ) ใส่เป็นข้อความ “สิ่งที่ควรทำ” ในทุกระดับของหน้าเว็บ</p>
            </div>
            <div class="why"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><p><b>ทำไมดี:</b> ทุกชิ้นที่หยิบมามี <b>เหตุผล</b> และ <b>การปรับ</b> เช่น “ไม่ส่งซ้ำรัว ๆ” และ “ไฟไม่มีข้อมูลสลับสี ไม่ติดเขียว” ไม่ใช่หยิบมาวางเฉย ๆ และแนวคิดของ ค ที่ไม่ใช้เทคโนโลยี ก็ไม่ถูกทิ้ง แต่กลายเป็นข้อความบนหน้าเว็บ</p></div></div>
          </div>
        </article>

        <article class="ex" id="a3-s4">
          <header class="ex-h"><span class="num-dot">4</span><h4>ต่อยอดกับเพื่อนและ AI</h4></header>
          <div class="ex-b">
            <div class="ex-q"><b>ใบกิจกรรมถามว่า</b><p>Prompt ที่ใช้จริง (ไม่มีข้อมูลส่วนบุคคล) · ข้อเสนอที่ AI ให้และเหตุผลรับ/ไม่รับ · AI ช่วยตรงไหน · ผังที่มาของความคิดใหม่</p></div>
            <div class="ex-a"><span class="lab">คำตอบของทีมยามน้ำ</span>
              <div class="copy-row" style="margin-bottom:14px"><div><b>Prompt ที่ใช้จริง</b><q id="a3-prompt-flood">ฉันเป็นนักเรียน ม.2 ในจังหวัดอุตรดิตถ์ กำลังทำต้นแบบเตือนน้ำป่าให้หมู่บ้านริมลำห้วย ผู้ใช้คืออาสาสมัครที่ต้องช่วยผู้สูงอายุอพยพ ข้อจำกัด: กลางคืน ไฟดับ ไม่มีอินเทอร์เน็ต งบจำกัด ใช้บอร์ด IPST-WiFi (ESP32) ที่โรงเรียนมี ขอทางเลือก 5 แนวทางที่ ม.2 ทำเป็นต้นแบบจำลองได้ พร้อมข้อควรระวังด้านความปลอดภัย (ไม่ใส่ชื่อ/ที่อยู่คนจริง)</q></div>
                <button type="button" class="btn sm" data-copy="a3-prompt-flood"><svg class="ic" aria-hidden="true"><use href="#i-copy"/></svg> คัดลอก</button></div>
              <div class="tbl"><table>
                <thead><tr><th>ข้อเสนอที่ AI ให้</th><th>รับ/ไม่รับ เพราะ (ปลอดภัย–ผู้ใช้–ทรัพยากร)</th><th>ตรวจสอบหรือปรับ</th></tr></thead>
                <tbody>
                  <tr><td>1. ให้ระบบเตือนเมื่อเซนเซอร์เงียบเกิน 30 นาที (เงียบ ไม่เท่ากับ ปลอดภัย)</td><td><b>รับ:</b> ปลอดภัยขึ้น ไม่ต้องใช้อุปกรณ์เพิ่ม และตรงกับผู้ใช้ (อาสา)</td><td>ทดลองถอดปลั๊กเซนเซอร์ แล้วดูว่าหน้าเว็บขึ้น “ไม่มีข้อมูล” จริงหรือไม่</td></tr>
                  <tr><td>2. ใช้โดรนบินตรวจระดับน้ำที่ต้นน้ำ</td><td><b>ไม่รับ:</b> ราคาสูง ควบคุมยาก ไม่ปลอดภัยเมื่อฝนตก ม.2 ทำเองไม่ได้</td><td>เปลี่ยนเป็นเซนเซอร์อัลตราโซนิกติดตายตัวที่ราคาต่ำกว่าและจัดการง่ายกว่า</td></tr>
                </tbody>
              </table></div>
              <p style="margin-top:12px"><b>AI ช่วยตรงไหน:</b> เสนอแนวคิดสถานะ “ไม่มีข้อมูล” และช่วยร่างข้อความเตือน 4 ระดับ · <b>เราคัดทิ้ง:</b> โดรน และตัวเลขเกณฑ์ระดับน้ำที่ AI ให้มา เพราะไม่มีที่มา ต้องใช้ข้อมูลหมู่บ้านจริง · <b>ตรวจสอบกับ:</b> ปภ.อุตรดิตถ์/เทศบาล/อบต. และประกาศทางการ (สายด่วน ปภ. 1784)</p>
              <figure style="margin:14px 0 0" class="card flat">
                <svg class="diagram" viewBox="0 0 720 386" role="img" aria-labelledby="a3dgT a3dgD">
                  <title id="a3dgT">ผังที่มาของความคิดใหม่ เพื่อนบ้านเตือนภัย</title>
                  <desc id="a3dgD">ความคิดของ ฉัน ก ข และ ง รวมกันเป็นเพื่อนบ้านเตือนภัย ส่วนความคิดของ ค และข้อเสนอของ AI กลายเป็นข้อความสิ่งที่ควรทำและสถานะไม่มีข้อมูล</desc>
                  <defs><marker id="a3ar" viewBox="0 0 10 10" refX="9" refY="5" markerWidth="8" markerHeight="8" orient="auto"><path d="M0 0L10 5L0 10z" class="dg-arw"/></marker></defs>
                  <rect class="dg-box" x="14" y="14" width="250" height="56" rx="12"/><text class="dg-t" x="26" y="38">ของฉัน</text><text class="dg-s" x="26" y="58">กล่องเซนเซอร์ที่ตลิ่ง + บัซเซอร์ ไม่พึ่งเน็ต</text>
                  <rect class="dg-box" x="14" y="84" width="250" height="56" rx="12"/><text class="dg-t" x="26" y="108">จาก ก</text><text class="dg-s" x="26" y="128">แจ้งเตือนมือถืออาสา</text>
                  <rect class="dg-box" x="14" y="154" width="250" height="56" rx="12"/><text class="dg-t" x="26" y="178">จาก ข และ ง</text><text class="dg-s" x="26" y="198">ไซเรนและไฟ 3 สี · ไฟสำหรับผู้ได้ยินไม่ชัด</text>
                  <rect class="dg-box" x="14" y="238" width="250" height="56" rx="12"/><text class="dg-t" x="26" y="262">จาก ค</text><text class="dg-s" x="26" y="282">จุดนัดพบและการซ้อมอพยพ</text>
                  <rect class="dg-box" style="fill:var(--a3-soft)" x="14" y="308" width="250" height="56" rx="12"/><text class="dg-t" x="26" y="332">จาก AI</text><text class="dg-s" x="26" y="352">เงียบ ไม่เท่ากับ ปลอดภัย</text>
                  <rect class="dg-box dg-new" x="440" y="40" width="266" height="150" rx="16"/>
                  <text class="dg-t" x="573" y="82" text-anchor="middle" style="font-size:17px">“เพื่อนบ้านเตือนภัย”</text>
                  <text class="dg-s" x="573" y="108" text-anchor="middle">เตือน 2 ชั้น</text>
                  <text class="dg-s" x="573" y="130" text-anchor="middle">ที่ตลิ่ง (ไม่ต้องใช้เน็ต) + ทางไกล (มือถือ)</text>
                  <text class="dg-s" x="573" y="152" text-anchor="middle">ไซเรนและไฟประจำหมู่บ้าน</text>
                  <rect class="dg-box dg-new" x="440" y="238" width="266" height="126" rx="16"/>
                  <text class="dg-t" x="573" y="278" text-anchor="middle">ส่วนเสริมที่ทำให้ปลอดภัยขึ้น</text>
                  <text class="dg-s" x="573" y="304" text-anchor="middle">ข้อความ “สิ่งที่ควรทำ” ทุกระดับ</text>
                  <text class="dg-s" x="573" y="326" text-anchor="middle">สถานะ “ไม่มีข้อมูล” ไม่ใช่สีเขียว</text>
                  <path class="dg-ln" d="M264 42 C 350 42 360 80 436 86" marker-end="url(#a3ar)"/>
                  <path class="dg-ln" d="M264 112 C 340 112 360 112 436 112" marker-end="url(#a3ar)"/>
                  <path class="dg-ln" d="M264 182 C 350 182 360 150 436 138" marker-end="url(#a3ar)"/>
                  <path class="dg-ln" d="M264 266 C 350 266 370 280 436 290" marker-end="url(#a3ar)"/>
                  <path class="dg-ln" d="M264 336 C 350 336 370 320 436 316" marker-end="url(#a3ar)"/>
                </svg>
                <figcaption class="sm mute" style="margin-top:6px">ความคิดจากเพื่อน 3 คนรวมกับของฉันเป็นแกนหลัก ส่วนจุดนัดพบ (ค) และข้อเสนอของ AI กลายเป็นส่วนเสริม</figcaption>
              </figure>
            </div>
            <div class="why"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><p><b>ทำไมดี:</b> คำสั่งถึง AI ระบุ <b>ผู้ใช้ เงื่อนไข ทรัพยากร ระดับ ม.2</b> และขอความปลอดภัย กลุ่มไม่ได้รับทุกข้อเสนอ ปฏิเสธโดรนด้วยเหตุผล และทิ้งตัวเลขที่ไม่มีที่มา ซึ่งเป็นหลักฐานว่า “คนเป็นผู้ตรวจและเลือก”</p></div></div>
          </div>
        </article>

        <article class="ex" id="a3-s5">
          <header class="ex-h"><span class="num-dot">5</span><h4>สังเคราะห์เป็น 3 แนวคิดที่แตกต่างกันจริง</h4></header>
          <div class="ex-b">
            <div class="ex-q"><b>ใบกิจกรรมถามว่า</b><p>3 แนวคิดของกลุ่ม พร้อมที่มาว่าใครคิด ใครต่อยอดส่วนไหน และเหมาะกับใคร แล้วบอกแนวคิดที่ภูมิใจที่สุด</p></div>
            <div class="ex-a"><span class="lab">คำตอบของทีมยามน้ำ</span>
              <div class="tbl"><table>
                <thead><tr><th>แนวคิด / วิธีทำงาน</th><th>ที่มา</th><th>เหมาะกับใคร / ลดความเสี่ยงอย่างไร</th></tr></thead>
                <tbody>
                  <tr><td><b>1. สถานีวัดน้ำ + แจ้งเตือนมือถือ</b> เซนเซอร์ + IPST-WiFi ส่งข้อมูลไป Apps Script แล้วแจ้ง Telegram/LINE ตามระดับ 0–3</td><td>ฉันคิดเซนเซอร์ · ก คิดแจ้งเตือนมือถือ · AI เสนอสถานะ “ไม่มีข้อมูล”</td><td>อาสา/ผู้ใหญ่บ้านที่มีมือถือ · ลดความเสี่ยงโดยรู้ก่อนน้ำถึงบ้านผู้สูงอายุ</td></tr>
                  <tr><td><b>2. ไซเรนและไฟ 3 สีประจำหมู่บ้าน</b> ทำงานตามระดับ และเตือนที่ตลิ่งเองแม้เน็ตหลุด</td><td>ข คิดไซเรน · ง คิดไฟสำหรับผู้ได้ยินไม่ชัด · ฉันคิดกล่องเตือนที่ตลิ่ง</td><td>ทุกคนในหมู่บ้าน รวมคนไม่มีมือถือและผู้ได้ยินไม่ชัด · เตือนทั้งเสียงและแสง</td></tr>
                  <tr><td><b>3. เพื่อนบ้านดูแลกัน + จุดนัดพบ</b> จับคู่บ้านเปราะบางกับเพื่อนบ้าน และมีจุดนัดพบ</td><td>ค คิดจุดนัดพบ · ฉันคิดการจับคู่บ้าน · AI เตือนเรื่องข้อมูลส่วนบุคคล</td><td>ผู้สูงอายุ ผู้ป่วยติดเตียง ผู้ได้ยินไม่ชัด · มีคนช่วยถึงตัวเมื่อเทคโนโลยีล่ม</td></tr>
                </tbody>
              </table></div>
              <div class="card flat" style="margin-top:14px"><b>แนวคิดที่ภูมิใจที่สุด: เตือน 2 ชั้น</b>
                <p style="margin:.4em 0 0">กล่องที่ตลิ่งเตือนเองแม้ไม่มีเน็ต และส่งขึ้นมือถือเมื่อมีเน็ต ต่างจากก่อนผสานที่ฉันมีแค่บัซเซอร์และไม่ได้คิดถึงคนที่ได้ยินไม่ชัด</p>
                <dl class="kv" style="margin-top:8px">
                  <dt>สิ่งที่ฉันคิดเอง</dt><dd>กล่องเตือนที่ตลิ่งทำงานเองโดยไม่ใช้เน็ต</dd>
                  <dt>จากเพื่อน</dt><dd>แจ้งเตือนมือถือ ไซเรน ไฟ จุดนัดพบ</dd>
                  <dt>จาก AI</dt><dd>เงียบ ไม่เท่ากับ ปลอดภัย</dd>
                  <dt>รวมเป็นผลงานเดียวได้เพราะ</dt><dd>ทุกส่วนใช้ “ระดับ 0–3” เดียวกัน และเชื่อมกันผ่านเซิร์ฟเวอร์เดียว</dd>
                </dl>
              </div>
            </div>
            <div class="why"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><p><b>ทำไมดี:</b> คำตอบข้อสุดท้ายแยก “คิดเอง / จากเพื่อน / จาก AI” ออกจากกันชัด และอธิบายว่าทำไมจึงเป็นผลงานเดียว (ระดับ 0–3 ร่วมกัน) ครูจึงเห็นบทบาทของทุกฝ่าย</p></div></div>
          </div>
        </article>

        <div class="callout note"><svg class="ic" aria-hidden="true"><use href="#i-arrow-r"/></svg><div><p><b>เชื่อมไปใบกิจกรรมที่ 4:</b> 3 แนวคิดนี้คือวัตถุดิบ ใบที่ 4 จะเปรียบเทียบแล้ว<b>เลือกแกนหลัก</b> และตัดทิ้งส่วนที่ไม่ช่วยแก้ปัญหา</p></div></div>
      </div>
    </div>

    <!-- ---------- A3 : HAZARDS ---------- -->
    <div class="panel" role="tabpanel" id="p-a3-hz" aria-labelledby="t-a3-hz" hidden>
      <div class="stack">
        <div class="callout note"><svg class="ic" aria-hidden="true"><use href="#i-info"/></svg><div><p>เลือกภัยเพื่อดู 3 แนวคิดและการผสานของภัยนั้น พร้อมตัวอย่างคำตอบเต็มทุกหัวข้อของใบกิจกรรมที่ 3 ใช้ฝึกมอง “กลไกที่ต่างกัน” ไม่ใช่คำตอบให้คัดลอก</p></div></div>
        <div class="hz" data-hz-for="a3"></div>
      </div>
    </div>

    <!-- ---------- A3 : RUBRIC ---------- -->
    <div class="panel" role="tabpanel" id="p-a3-rub" aria-labelledby="t-a3-rub" hidden>
      <div class="stack">
        <div class="card soft">
          <h3>ครูดูอะไร</h3>
          <p style="margin:0">ใบนี้ประเมินเพียง <b>องค์ประกอบที่ 4 การทำงานสร้างสรรค์ร่วมกับผู้อื่น</b> ระดับตัดสินจาก<b>การทำงานกับความคิดของเพื่อนสมาชิกเป็นหลัก</b> ข้อเสนอจาก AI นับเป็นหลักฐานเสริมได้ แต่ไม่ใช่ตัวตัดสินระดับ และบัตรคิดเอง 3 แนวทางของแต่ละคนเป็นหลักฐานรายบุคคล</p>
        </div>
        <div>
          <div class="lad-h"><h4>4.1 การทำงานสร้างสรรค์ร่วมกับผู้อื่น</h4><span class="pill">หลักฐาน: ส่วนที่ 1–5</span></div>
          <div class="ladder">
            <div class="rung"><small>1.0 ขั้นเริ่มต้น</small>เปรียบเทียบความคิดของผู้อื่นกับความคิดของตนเอง</div>
            <div class="rung"><small>2.0 ขั้นพื้นฐาน</small>ผสมผสานความคิดของตนเองเข้ากับความคิดของผู้อื่น</div>
            <div class="rung"><small>3.0 ขั้นชำนาญ</small>เชื่อมโยงและต่อยอดความคิดของผู้อื่น เพื่อสร้าง ข้อค้นพบหรือมุมมองใหม่ที่มีลักษณะเฉพาะ</div>
            <div class="rung"><small>4.0 ขั้นสูง</small>สังเคราะห์ความคิด และใช้ประโยชน์จากจุดแข็งและมุมมองที่แตกต่างของสมาชิกแต่ละคนในกลุ่ม เพื่อพัฒนาเป็นผลงานหรือการปฏิบัติที่มีความริเริ่มและมีความเป็นเอกภาพ</div>
          </div>
        </div>
        <div class="callout idea"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><h5>ขึ้นบันไดอย่างไร</h5>
          <ul style="margin:.3em 0 0"><li><b>1.0 → 2.0:</b> จากแค่ “ฟังแล้วจด” ไปเป็นหยิบส่วนของเพื่อนมารวมกับของตัวเอง</li><li><b>2.0 → 3.0:</b> ไม่ใช่แค่รวม แต่ต่อยอดจนเกิดสิ่งใหม่ที่ไม่มีในข้อเสนอเดิมของใครคนเดียว (ผังที่มาของความคิดใหม่ ช่อง “ต่างจากข้อเสนอเดิมอย่างไร”)</li><li><b>3.0 → 4.0:</b> ใช้จุดแข็งของแต่ละคนจนเป็นผลงานเดียวที่เป็นเอกภาพ และบอกได้ว่าใครมีส่วนตรงไหน</li></ul></div></div>

        <div class="card">
          <h4>เช็กลิสต์ก่อนส่งใบกิจกรรมที่ 3</h4>
          <p class="sm mute">ติ๊กได้เลย เครื่องนี้จะจำไว้ให้ในเบราว์เซอร์ของคุณ ครูไม่เห็นเช็กลิสต์นี้</p>
          <ul class="checks" data-checks="a3">
            <li><label><input type="checkbox"><span>กรอกบัตรคิดเอง 3 แนวทางครบ ก่อนเปิด AI และก่อนแลกเปลี่ยนกับเพื่อน (มีเวลากำกับ)</span></label></li>
            <li><label><input type="checkbox"><span>เขียนได้ว่า 3 แนวคิดต่างกันที่ “กลไก” ไม่ใช่แค่ชื่อหรือสี</span></label></li>
            <li><label><input type="checkbox"><span>ฟังเพื่อนครบทุกคน และบันทึก เหมือน/ต่าง กับความคิดของตัวเอง</span></label></li>
            <li><label><input type="checkbox"><span>ผสานส่วนของเพื่อนอย่างน้อย 2 คน และบอกได้ว่าแต่ละส่วนช่วยแก้จุดอ่อนอะไร</span></label></li>
            <li><label><input type="checkbox"><span>คำสั่งถึง AI ระบุปัญหา ผู้ใช้ ข้อจำกัด และไม่มีข้อมูลส่วนบุคคลหรือข้อมูลอ่อนไหว</span></label></li>
            <li><label><input type="checkbox"><span>ตัดสินข้อเสนอของ AI ด้วยเหตุผล (ปลอดภัย ผู้ใช้ ทรัพยากร) และตรวจสอบกับแหล่งที่เชื่อถือได้</span></label></li>
            <li><label><input type="checkbox"><span>วาดผังที่มาของความคิดใหม่ (ความคิดตั้งต้นของใคร / ส่วนที่ต่อยอด / ข้อค้นพบใหม่ / ต่างจากเดิมอย่างไร)</span></label></li>
            <li><label><input type="checkbox"><span>สังเคราะห์เป็น 3 แนวคิดของกลุ่ม ระบุที่มาชัดเจน และเขียนว่าแนวคิดที่ภูมิใจที่สุดมีส่วนที่ “คิดเอง” อะไร</span></label></li>
          </ul>
          <div class="meter" style="margin-top:14px" aria-hidden="true"><i data-meter="a3"></i></div>
          <p class="sm mute" style="margin:.5em 0 0" data-meter-text="a3">ติ๊กแล้ว 0 จาก 8 ข้อ</p>
        </div>
      </div>
    </div>

    <div class="pn">
      <a class="btn" href="#a2" data-go="a2"><svg class="ic" aria-hidden="true"><use href="#i-arrow-l"/></svg> ใบกิจกรรมที่ 2</a>
      <a class="btn pri" href="#a4" data-go="a4">ใบกิจกรรมที่ 4 แนวคิดสู่แบบร่าง <svg class="ic" aria-hidden="true"><use href="#i-arrow-r"/></svg></a>
    </div>
  </div>
</section>
<!-- ====================== ACTIVITY 4 ====================== -->
<section class="view k4" id="v-a4" data-view="a4" hidden>
  <div class="ah k4">
    <div class="wrap ah-in">
      <div class="ah-num" aria-hidden="true">4</div>
      <div>
        <p class="stage">ขั้นที่ 4 · การคัดเลือกและออกแบบแนวทางแก้ปัญหา</p>
        <h1>แนวคิด<wbr>สู่แบบร่าง</h1>
        <p class="mission-line">เลือกแนวคิดอย่างมีเหตุผล วาดแบบร่างให้คนอื่นสร้างตามได้ ทดลองบนกระดาษ แล้วปรับเป็นรุ่นที่ 2 ก่อนลงมือสร้างจริง</p>
        <div class="pills">
          <span class="pill">2 ชั่วโมง</span>
          <span class="pill">ประเมิน องค์ประกอบที่ 2 การออกแบบและปรับปรุงความคิด</span>
          <span class="pill">เลือก → วาด → อธิบาย → ทดลอง → ปรับ</span>
        </div>
        <p style="margin:14px 0 0"><a class="btn" href="https://docs.google.com/presentation/d/1_kx4cvHE5S5yw-BHe1bPOHeqcBseit2YTYCW5HB4hK0/edit?usp=sharing" target="_blank" rel="noopener">เปิดใบกิจกรรมที่ 4 (Google Slides) <svg class="ic" aria-hidden="true"><use href="#i-link"/></svg></a></p>
      </div>
    </div>
  </div>

  <div class="wrap">
    <div class="tabs" role="tablist" aria-label="เมนูย่อยของใบกิจกรรมที่ 4">
      <button type="button" class="tab" role="tab" id="t-a4-learn" aria-controls="p-a4-learn" aria-selected="true" data-go="a4"><svg class="ic" aria-hidden="true"><use href="#i-book"/></svg>เรียนรู้</button>
      <button type="button" class="tab" role="tab" id="t-a4-ex" aria-controls="p-a4-ex" aria-selected="false" data-go="a4-ex"><svg class="ic" aria-hidden="true"><use href="#i-search"/></svg>ตัวอย่างละเอียด</button>
      <button type="button" class="tab" role="tab" id="t-a4-hz" aria-controls="p-a4-hz" aria-selected="false" data-go="a4-hz"><svg class="ic" aria-hidden="true"><use href="#i-users"/></svg>ตัวอย่าง 4 ภัยอื่น</button>
      <button type="button" class="tab" role="tab" id="t-a4-rub" aria-controls="p-a4-rub" aria-selected="false" data-go="a4-rub"><svg class="ic" aria-hidden="true"><use href="#i-check"/></svg>เกณฑ์และเช็กลิสต์</button>
    </div>

    <!-- ---------- A4 : LEARN ---------- -->
    <div class="panel" role="tabpanel" id="p-a4-learn" aria-labelledby="t-a4-learn">
      <div class="stack">
        <div class="card">
          <p class="lede">ใบนี้เปลี่ยน “ความคิดในหัว” ให้เป็น <b>แบบร่างที่เพื่อนกลุ่มอื่นอ่านแล้วสร้างตามได้</b> และฝึกปรับแก้จากข้อเสนอแนะที่เฉพาะเจาะจง ยังไม่ต้องสร้างของจริงในใบนี้</p>
          <div class="tbl tight"><table>
            <thead><tr><th>ส่วน</th><th>ทำอะไร</th><th>ผลงานที่ได้</th></tr></thead>
            <tbody>
              <tr><td>1</td><td>เปรียบเทียบ 3 แนวคิดจากใบที่ 3 แล้วเลือก 1 แนวคิดเป็นแกน</td><td>ตารางเปรียบเทียบ + เหตุผลที่เลือกและไม่เลือก</td></tr>
              <tr><td>2</td><td>ร่างแบบรุ่นที่ 1 เป็นผังงาน และอธิบายหลักการทำงาน</td><td>ภาพร่าง + คำอธิบาย 3 ข้อ</td></tr>
              <tr><td>3</td><td>ขยายความคิดให้ละเอียด และบอกจุดที่ยังคลุมเครือ</td><td>ตารางส่วนประกอบ + รายการสิ่งที่ต้องทดลอง</td></tr>
              <tr><td>4</td><td>ทดลองบนกระดาษ รับข้อเสนอแนะ แล้วปรับเป็นรุ่นที่ 2</td><td>บันทึกการทดลอง + ภาพร่างรุ่นที่ 2</td></tr>
              <tr><td>5</td><td>ให้ครูตรวจก่อนสร้างต้นแบบ</td><td>ครูติ๊กอนุญาตให้สร้าง</td></tr>
            </tbody>
          </table></div>
        </div>

        <div class="callout note"><svg class="ic" aria-hidden="true"><use href="#i-info"/></svg><div><h5>เรียนจากแท็บ “ตัวอย่างละเอียด”</h5><p>อ่านหัวข้อด้านล่างเพื่อเข้าใจหลักคิด แล้วเปิดแท็บ <b>ตัวอย่างละเอียด</b> เพื่อดูว่าทีมยามน้ำเขียนแต่ละส่วนอย่างไร</p><p style="margin:.6em 0 0"><button type="button" class="btn sm" data-go="a4-ex">ไปที่ตัวอย่างละเอียด <svg class="ic" aria-hidden="true"><use href="#i-arrow-r"/></svg></button></p></div></div>

        <ul class="toc" aria-label="หัวข้อในแท็บนี้">
          <li><a href="#" data-scroll="a4-l1"><i>1</i>เลือกแนวคิด</a></li>
          <li><a href="#" data-scroll="a4-l2"><i>2</i>ร่างแบบรุ่น 1</a></li>
          <li><a href="#" data-scroll="a4-l3"><i>3</i>ขยายให้ละเอียด</a></li>
          <li><a href="#" data-scroll="a4-l4"><i>4</i>ทดลองและปรับ</a></li>
          <li><a href="#" data-scroll="a4-l5"><i>5</i>ครูตรวจ</a></li>
        </ul>

        <!-- 1 -->
        <div class="blk" id="a4-l1">
          <h3><span class="num-dot">1</span>เปรียบเทียบแล้วเลือก ต้องมีเกณฑ์</h3>
          <p>เทียบแนวคิดทั้ง 3 ด้วยคำถามเดียวกัน ไม่ใช่เลือกตามที่ชอบหรือตามเสียงดังที่สุด</p>
          <div class="grid g3">
            <div class="card" style="--c:var(--a4)"><h4>ข้อดีต่อผู้ใช้</h4><p class="sm" style="margin:0">ผู้ใช้หลักได้อะไร ผู้ใช้กลุ่มอื่นได้อะไร ใช้ง่ายไหมถ้าไฟดับหรือไม่มีเน็ต</p></div>
            <div class="card" style="--c:var(--a4)"><h4>ข้อจำกัด / ความเสี่ยง</h4><p class="sm" style="margin:0">ใครไม่ได้ประโยชน์ อะไรอาจพลาด มีข้อมูลส่วนบุคคลหรืออันตรายหรือไม่</p></div>
            <div class="card" style="--c:var(--a4)"><h4>ทำได้จริงในเวลา</h4><p class="sm" style="margin:0">ใช้ของที่โรงเรียนมี ทำได้ภายในชั่วโมงลงมือ (ใบที่ 5 มี 5 ชั่วโมง) และทดสอบในที่ปลอดภัยได้</p></div>
          </div>
          <div class="callout idea"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><h5>เหตุผลที่เลือกต้องตอบ 4 ด้าน</h5><p><b>แก้ตรงโจทย์</b> · <b>ตรงผู้ใช้</b> · <b>ทรัพยากรที่มี</b> · <b>ปลอดภัย</b> และต้องเขียน <b>เหตุผลที่ไม่เลือกอีก 2 แนวคิด</b> (หรือส่วนที่ตัดสินใจละทิ้ง) พร้อม <b>เงื่อนไขที่อาจทำให้เปลี่ยนใจ</b></p></div></div>
          <div class="quiz" data-quiz="b">
            <h5><span class="pill">ลองตอบ</span> เหตุผลข้อใดแสดงว่าเลือกอย่างมีเกณฑ์</h5>
            <div class="opts">
              <button type="button" class="opt" data-k="a"><span class="k">ก</span><span>แนวคิดนี้ดูเท่และทันสมัยที่สุด</span></button>
              <button type="button" class="opt" data-k="b"><span class="k">ข</span><span>วัดน้ำที่ลำห้วยของเราเอง ใช้บอร์ดที่โรงเรียนมี ใช้ไฟ 5 V และทดสอบในถังน้ำได้</span></button>
              <button type="button" class="opt" data-k="c"><span class="k">ค</span><span>เพื่อนในกลุ่มส่วนใหญ่ชอบแนวคิดนี้</span></button>
            </div>
            <div class="fb" hidden><b class="fb-h"></b><p>ข้อ ข อ้างถึงโจทย์ ทรัพยากร และความปลอดภัย ตรวจสอบได้ ส่วนความเท่หรือเสียงส่วนใหญ่ไม่ได้บอกว่าแก้ปัญหาของผู้ใช้ได้จริง</p></div>
          </div>
          <div class="pair">
            <div class="bad"><h5>ปิดทางตัวเอง</h5><p style="margin:0">“แนวคิด 3 ไม่เอา เพราะยาก”</p><p class="sm" style="margin:.5em 0 0">ไม่บอกว่ายากเพราะอะไร และจะเปลี่ยนใจเมื่อไร</p></div>
            <div class="good"><h5>ชี้เงื่อนไขชัด</h5><p style="margin:0">“แนวคิด 3 ต้องมีผู้ใหญ่บ้านร่วม ใน 15 ชั่วโมงทำได้แค่หน้ารายชื่อสมมติ จึงตัดการเก็บชื่อจริง จะเปลี่ยนใจถ้าผู้ใหญ่บ้านขอรายชื่อจริงและอนุญาตให้จำกัดสิทธิ์ผู้เห็น”</p></div>
          </div>
        </div>

        <!-- 2 -->
        <div class="blk" id="a4-l2">
          <h3><span class="num-dot">2</span>ร่างแบบรุ่นที่ 1 เป็นผังงาน</h3>
          <p>วาดให้ใหญ่พอเห็นชัด ใช้ลูกศร หมายเลข และคำอธิบายกำกับ ผังที่ดีตอบได้ว่า <b>ข้อมูลเข้ามาจากไหน ไปทางไหน ออกมาเป็นอะไร และผู้ใช้เข้ามายุ่งตรงไหน</b></p>
          <div class="card soft">
            <div class="flowline" aria-label="ลำดับที่ควรเห็นในผังงาน">
              <span class="pill">ข้อมูลเข้า</span><span class="arrow" aria-hidden="true">→</span>
              <span class="pill">ประมวลผล</span><span class="arrow" aria-hidden="true">→</span>
              <span class="pill">ผลลัพธ์</span><span class="arrow" aria-hidden="true">→</span>
              <span class="pill">จุดที่ผู้ใช้โต้ตอบ</span><span class="arrow" aria-hidden="true">→</span>
              <span class="pill">ถ้าไฟดับ / ไม่มีเน็ต</span>
            </div>
          </div>
          <div class="tbl tight"><table>
            <thead><tr><th>ต้องเขียนอธิบายใต้ผัง</th><th>คิดถึงอะไร</th></tr></thead>
            <tbody>
              <tr><td>1) ต้นแบบเริ่มทำงานอย่างไร</td><td>ใครหรืออะไรเริ่ม วัดบ่อยแค่ไหน เปรียบเทียบกับอะไร</td></tr>
              <tr><td>2) ผู้ใช้ได้ประโยชน์อะไร</td><td>ผู้ใช้เห็น ได้ยิน หรือได้รับอะไร และทำอะไรต่อได้</td></tr>
              <tr><td>3) ถ้าไฟดับหรือไม่มีอินเทอร์เน็ต</td><td>ส่วนไหนยังทำงาน ส่วนไหนหยุด และผู้ใช้รู้ได้อย่างไรว่าระบบหยุด</td></tr>
            </tbody>
          </table></div>
          <div class="callout warn"><svg class="ic" aria-hidden="true"><use href="#i-warn"/></svg><div><h5>ข้อ 3 สำคัญที่สุดของภัยพิบัติ</h5><p>ภัยมักมาตอนที่ไฟดับและสัญญาณหาย ถ้าแบบร่างใช้ได้เฉพาะตอนที่ทุกอย่างปกติ แสดงว่ายังไม่ตรงปัญหา</p></div></div>
        </div>

        <!-- 3 -->
        <div class="blk" id="a4-l3">
          <h3><span class="num-dot">3</span>ขยายความคิดให้ละเอียดพอสร้างจริง</h3>
          <p>เขียนให้เพื่อนกลุ่มอื่นอ่านแล้วเข้าใจว่า <b>ต้องสร้างอะไร</b> ทดสอบง่าย ๆ คือ ถ้าให้เพื่อนอีกกลุ่มสร้างตามโดยไม่ถามเรา เขาจะสร้างได้หรือไม่</p>
          <div class="pair">
            <div class="bad"><h5>ยังกว้างเกินไป</h5><p style="margin:0">“มีเซนเซอร์วัดน้ำแล้วเตือนชาวบ้าน”</p><p class="sm" style="margin:.5em 0 0">เซนเซอร์อะไร วัดอะไร เตือนด้วยวิธีใด ผู้ใช้ต้องทำอะไร ยังไม่รู้</p></div>
            <div class="good"><h5>ละเอียดพอ</h5><p style="margin:0">“IPST-WiFi + เซนเซอร์อัลตราโซนิกกันน้ำ + บัซเซอร์ · <b>เข้า:</b> ระยะจากเซนเซอร์ถึงผิวน้ำ → คำนวณความลึก · <b>ออก:</b> ระดับ 0–3 + เสียง/ไฟ + ส่งขึ้นเว็บ · ผู้ใช้ไม่ต้องกดอะไร ดูไฟและฟังเสียง”</p></div>
          </div>
          <div class="quiz" data-quiz="c">
            <h5><span class="pill">ลองตอบ</span> ข้อใดเป็นการ “ระบุจุดที่ยังคลุมเครือ” ที่ดี</h5>
            <div class="opts">
              <button type="button" class="opt" data-k="a"><span class="k">ก</span><span>ไม่มีจุดคลุมเครือ เพราะเราคิดมาดีแล้ว</span></button>
              <button type="button" class="opt" data-k="b"><span class="k">ข</span><span>ยังไม่รู้ว่าจะเวิร์กไหม ต้องดูตอนทำ</span></button>
              <button type="button" class="opt" data-k="c"><span class="k">ค</span><span>ยังไม่รู้ว่าเซนเซอร์จะแม่นแค่ไหนเมื่อผิวน้ำเป็นคลื่น จะทดลองในถังน้ำที่มีคลื่นและใช้ค่ากลางของการวัดหลายครั้ง</span></button>
            </div>
            <div class="fb" hidden><b class="fb-h"></b><p>ข้อ ค ระบุ <b>สิ่งที่ยังไม่รู้</b> พร้อม <b>วิธีหาคำตอบ</b> ซึ่งนำไปทดลองได้ทันที ส่วนข้อ ก และ ข ไม่ได้บอกว่าต้องหาข้อมูลหรือทดลองอะไร</p></div>
          </div>
        </div>

        <!-- 4 -->
        <div class="blk" id="a4-l4">
          <h3><span class="num-dot">4</span>ทดลองบนกระดาษ รับข้อเสนอแนะ แล้วปรับ</h3>
          <p>เดินตามสถานการณ์จำลอง 1 รอบ บนกระดาษหรือสวมบทบาท โดยใช้แบบร่างรุ่นที่ 1 ถามว่า <b>ผู้ใช้ทำอะไรเป็นอย่างแรก และติดขัดตรงไหน</b></p>
          <div class="pair">
            <div class="bad"><h5>ข้อเสนอแนะกว้าง</h5><p style="margin:0">“ดีแล้วนะ” หรือ “ไม่ค่อยเข้าใจ”</p><p class="sm" style="margin:.5em 0 0">ไม่รู้ว่าต้องแก้ตรงไหน</p></div>
            <div class="good"><h5>ข้อเสนอแนะเฉพาะเจาะจง</h5><p style="margin:0">“ข้อความบอกแค่ ‘ระดับ 2’ ผมไม่รู้ว่าต้องทำอะไรต่อ”</p><p class="sm" style="margin:.5em 0 0">ชี้จุด เห็นผลที่เกิด แก้ได้ทันที</p></div>
          </div>
          <div class="quiz" data-quiz="b">
            <h5><span class="pill">ลองตอบ</span> ข้อไหนคือข้อเสนอแนะที่เฉพาะเจาะจงพอจะนำไปแก้แบบร่าง</h5>
            <div class="opts">
              <button type="button" class="opt" data-k="a"><span class="k">ก</span><span>ผังสวยดีนะ</span></button>
              <button type="button" class="opt" data-k="b"><span class="k">ข</span><span>ถ้าไฟดับ ไซเรนในหมู่บ้านไม่มีไฟเลี้ยง ควรมีพาวเวอร์แบงก์สำรอง</span></button>
              <button type="button" class="opt" data-k="c"><span class="k">ค</span><span>ลองคิดใหม่ให้ดีกว่านี้</span></button>
            </div>
            <div class="fb" hidden><b class="fb-h"></b><p>ข้อ ข บอกสถานการณ์ (ไฟดับ) ส่วนที่มีปัญหา (ไซเรน) และทางแก้ที่ทดสอบได้ จึงปรับในรุ่นที่ 2 ได้ทันที</p></div>
          </div>

          <div class="card" data-builder data-tpl="{0} เสนอว่า {1} จึงปรับแบบร่างโดย{2} เพราะ{3}" data-sample="เพื่อน ข (กลุ่มอื่น)|ข้อความเตือนควรบอกว่าต้องทำอะไร|เพิ่มบรรทัด “สิ่งที่ควรทำ” 4 ข้อตามระดับในข้อความและหน้าเว็บ|อาสาไม่ต้องเดา ตัดสินใจเร็วขึ้น">
            <h4>ลองบันทึกข้อเสนอแนะ 1 ข้อ ให้ครบ ใคร–อะไร–ปรับอย่างไร–เพราะอะไร</h4>
            <p class="sm mute">พิมพ์ทีละช่อง ประโยคจะประกอบให้ด้านล่าง ไม่ได้บันทึกอะไรไว้ในเว็บ</p>
            <div class="bld">
              <label>ใครเสนอ<input type="text" data-part="0" placeholder="เช่น เพื่อน ข (กลุ่มอื่น) / ครู"></label>
              <label>เสนอเรื่องอะไร<input type="text" data-part="1" placeholder="สิ่งที่เห็นว่าควรเปลี่ยน"></label>
              <label>ปรับในรุ่น 2 อย่างไร<input type="text" data-part="2" placeholder="สิ่งที่เปลี่ยนในแบบร่าง"></label>
              <label>เหตุผล / ผลที่คาดว่าดีขึ้น<input type="text" data-part="3" placeholder="ทำไมจึงดีขึ้น"></label>
            </div>
            <div class="bld-out" aria-live="polite"><b class="sm mute">ผลลัพธ์</b><p style="margin:.2em 0 0" data-out></p></div>
            <div class="flowline" style="margin-top:12px">
              <button type="button" class="btn sm" data-fill>ใส่ตัวอย่างทีมยามน้ำ</button>
              <button type="button" class="btn sm" data-clear>ล้างช่อง</button>
              <button type="button" class="btn sm" data-copy-out><svg class="ic" aria-hidden="true"><use href="#i-copy"/></svg> คัดลอกประโยค</button>
            </div>
          </div>

          <div class="callout idea"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><h5>รุ่นที่ 2 วาดเฉพาะส่วนที่เปลี่ยน</h5><p>ไม่ต้องวาดทั้งระบบใหม่ ทำเครื่องหมายส่วนที่เพิ่มหรือแก้ แล้วเขียนว่ารุ่นที่ 2 <b>ต่างจากรุ่นที่ 1 อย่างไร</b> และมี <b>ส่วนใดที่ตัดสินใจละทิ้ง</b> เพราะไม่ช่วยแก้ปัญหาหลักหรือเพิ่มความเสี่ยง การละทิ้งอย่างมีเหตุผลเป็นหลักฐานว่าเราปรับปรุงจริง</p></div></div>
        </div>

        <!-- 5 -->
        <div class="blk" id="a4-l5">
          <h3><span class="num-dot">5</span>ให้ครูตรวจก่อนสร้างต้นแบบ</h3>
          <div class="card">
            <p style="margin:0 0 .5em">ครูตรวจ 3 ข้อ และเขียนข้อเสนอแนะกลับให้ก่อนลงมือสร้าง</p>
            <ul class="plain" style="margin:0;padding-left:1.2em">
              <li>แบบร่างชัดเจนพอให้ผู้อื่นสร้างตามได้</li>
              <li>ปลอดภัย ไม่ต้องทดลองในภัยจริง</li>
              <li>อนุญาตให้สร้างต้นแบบ</li>
            </ul>
          </div>
        </div>
      </div>
    </div>

    <!-- ---------- A4 : WORKED EXAMPLE ---------- -->
    <div class="panel" role="tabpanel" id="p-a4-ex" aria-labelledby="t-a4-ex" hidden>
      <div class="stack">
        <div class="card soft">
          <span class="tag-sim">ตัวอย่างเพื่อการเรียนรู้</span>
          <h3 style="margin-top:10px">ทีมยามน้ำ จาก 3 แนวคิดสู่แบบร่างรุ่นที่ 2</h3>
          <p class="mute" style="margin:0">ต่อจากใบที่ 3 ทีมยามน้ำมี 3 แนวคิดของกลุ่ม ใบนี้เลือกหนึ่งแนวคิดเป็นแกน วาดแบบร่าง ทดลองบนกระดาษ และปรับ ตัวเลขเกณฑ์ระดับน้ำทั้งหมดเป็น <b>ค่าสมมติ</b> ที่ต้องขอข้อมูลจริงจากท้องถิ่น</p>
        </div>
        <ul class="toc" aria-label="ส่วนของใบกิจกรรมที่ 4">
          <li><a href="#" data-scroll="a4-s1"><i>1</i>เปรียบเทียบและเลือก</a></li>
          <li><a href="#" data-scroll="a4-s2"><i>2</i>แบบร่างรุ่น 1</a></li>
          <li><a href="#" data-scroll="a4-s3"><i>3</i>ขยายความคิด</a></li>
          <li><a href="#" data-scroll="a4-s4"><i>4</i>ทดลองและรุ่น 2</a></li>
          <li><a href="#" data-scroll="a4-s5"><i>5</i>ครูตรวจ</a></li>
        </ul>

        <article class="ex" id="a4-s1">
          <header class="ex-h"><span class="num-dot">1</span><h4>เปรียบเทียบ 3 แนวคิด และเลือกแกนหลัก</h4></header>
          <div class="ex-b">
            <div class="ex-q"><b>ใบกิจกรรมถามว่า</b><p>เปรียบเทียบข้อดีต่อผู้ใช้ ข้อจำกัด/ความเสี่ยง และความเป็นไปได้ในเวลา แล้วบอกว่าเลือกอะไร เพราะอะไร ไม่เลือกอะไร และอะไรอาจทำให้เปลี่ยนใจ</p></div>
            <div class="ex-a"><span class="lab">คำตอบของทีมยามน้ำ</span>
              <div class="tbl"><table>
                <thead><tr><th>แนวคิด</th><th>ข้อดีต่อผู้ใช้</th><th>ข้อจำกัด / ความเสี่ยง</th><th>ทำได้จริงภายในเวลา</th></tr></thead>
                <tbody>
                  <tr><td><b>1</b> สถานีวัดน้ำ + แจ้งเตือนมือถือ</td><td>รู้ก่อนน้ำถึง เก็บประวัติระดับน้ำได้ อาสาที่ไม่อยู่หมู่บ้านก็ได้รับ</td><td>ต้องพึ่งเน็ต ผู้สูงอายุที่ไม่มีมือถือไม่ได้รับ ตั้งเกณฑ์ผิดอาจเตือนพลาด</td><td>ใช้ IPST-WiFi + เซนเซอร์ + Apps Script (มีชุดโค้ดต้นแบบให้ปรับ) อยู่ในกรอบ 5 ชั่วโมงลงมือ</td></tr>
                  <tr><td><b>2</b> ไซเรนและไฟ 3 สีประจำหมู่บ้าน</td><td>ได้ยิน/เห็นทั้งหมู่บ้าน ไม่ต้องใช้มือถือ</td><td>เตือนผิดบ่อยแล้วคนเมิน ผู้ได้ยินไม่ชัดต้องใช้ไฟ</td><td>LED 3 สี + บัซเซอร์บนบอร์ด ทำง่าย</td></tr>
                  <tr><td><b>3</b> เพื่อนบ้านดูแลกัน + จุดนัดพบ</td><td>ช่วยถึงตัว ไม่ใช้ไฟฟ้า</td><td>รายชื่อบ้านเปราะบางเป็นข้อมูลส่วนบุคคล ต้องจำกัดคนเห็น</td><td>ทำเป็นขั้นตอน + หน้าเว็บ PIN ได้ ส่วนซ้อมอพยพจริงต้องมีผู้ใหญ่บ้านร่วม</td></tr>
                </tbody>
              </table></div>
              <div class="card flat" style="margin-top:14px"><b>แนวคิดที่เลือก: แนวคิดที่ 1 เป็นแกน + ส่วนเตือนในพื้นที่ของแนวคิดที่ 2</b>
                <dl class="kv" style="margin-top:8px">
                  <dt>แก้ตรงโจทย์</dt><dd>วัดระดับน้ำที่ลำห้วยของเราเองและเตือนก่อนน้ำถึง แล้วนำบัซเซอร์ ไซเรน ไฟ ของแนวคิดที่ 2 มารวมด้วย</dd>
                  <dt>ผู้ใช้</dt><dd>อาสาสมัครได้ข้อความที่บอกว่าต้องทำอะไร ส่วนคนไม่มีมือถือได้ยินไซเรนและเห็นไฟ</dd>
                  <dt>ทรัพยากร / ความปลอดภัย</dt><dd>ใช้บอร์ดและเซนเซอร์ที่โรงเรียนมี ใช้ไฟ 5 V จากพาวเวอร์แบงก์ ทดสอบในถังน้ำ ไม่ลงลำห้วยจริง</dd>
                </dl>
              </div>
              <div class="card flat" style="margin-top:12px"><b>ที่ไม่เลือก (หรือส่วนที่ละทิ้ง) และเงื่อนไขที่อาจเปลี่ยนใจ</b>
                <ul style="margin:.4em 0 0">
                  <li><b>แนวคิดที่ 2 เดี่ยว ๆ:</b> ไซเรนอย่างเดียวไม่มีข้อมูลระดับน้ำให้ตรวจ เสี่ยงเตือนผิด จึงเก็บไว้เป็นส่วนปลายทางของแนวคิดที่ 1</li>
                  <li><b>แนวคิดที่ 3:</b> เป็นกิจกรรมชุมชนที่ต้องมีผู้ใหญ่บ้านร่วม ใน 15 ชั่วโมงทำได้เพียงหน้ารายชื่อ (ข้อมูลสมมติ) จึงตัดการเก็บชื่อจริง</li>
                  <li><b>เปลี่ยนใจได้ถ้า:</b> หมู่บ้านไม่มีสัญญาณเน็ตเลย → เน้นแนวคิดที่ 2 · หรือผู้ใหญ่บ้านขอรายชื่อจริง → ต้องขออนุญาตและจำกัดสิทธิ์ผู้เห็น</li>
                </ul>
              </div>
            </div>
            <div class="why"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><p><b>ทำไมดี:</b> เลือก <b>แกน + ส่วนเสริม</b> ไม่ใช่ทิ้งทั้งสองแนวคิดที่เหลือ ทุกการตัดสินใจมีเหตุผลที่ตรวจสอบได้ (บอร์ดที่มี เวลา 5 ชั่วโมง ข้อมูลส่วนบุคคล) และบอกเงื่อนไขที่จะเปลี่ยนใจ ซึ่งแสดงว่ารู้ขอบเขตของการเลือก</p></div></div>
          </div>
        </article>

        <article class="ex" id="a4-s2">
          <header class="ex-h"><span class="num-dot">2</span><h4>แบบร่างรุ่นที่ 1 และหลักการทำงาน</h4></header>
          <div class="ex-b">
            <div class="ex-q"><b>ใบกิจกรรมถามว่า</b><p>วาดผังงานขนาดใหญ่ ระบุส่วนประกอบ ลำดับ ข้อมูลเข้า ผลลัพธ์ และจุดที่ผู้ใช้โต้ตอบ แล้วอธิบาย 3 ข้อ</p></div>
            <div class="ex-a"><span class="lab">ผังงานของทีมยามน้ำ (เทียบรุ่น 1 กับรุ่น 2)</span>
              <figure style="margin:0" class="card flat">
                <svg class="diagram" viewBox="0 0 720 330" role="img" aria-labelledby="a4dgT a4dgD">
                  <title id="a4dgT">ผังงานต้นแบบ เพื่อนบ้านเตือนภัย รุ่นที่ 1 และส่วนที่ปรับในรุ่นที่ 2</title>
                  <desc id="a4dgD">สถานีวัดน้ำที่ตลิ่งส่งข้อมูลไปเซิร์ฟเวอร์ Apps Script เซิร์ฟเวอร์ส่งข้อความถึงมือถืออาสา และไซเรนกับไฟสามสีถามระดับจากเซิร์ฟเวอร์ ส่วนสถานีที่ตลิ่งเตือนเองทันทีโดยไม่ต้องรอเน็ต กล่องสีเหลืองคือส่วนที่ปรับในรุ่นที่ 2</desc>
                  <defs><marker id="a4ar" viewBox="0 0 10 10" refX="9" refY="5" markerWidth="8" markerHeight="8" orient="auto"><path d="M0 0L10 5L0 10z" class="dg-arw"/></marker></defs>

                  <rect class="dg-box" x="14" y="30" width="206" height="104" rx="14"/>
                  <text class="dg-t" x="26" y="56">1 สถานีวัดน้ำที่ตลิ่ง</text>
                  <text class="dg-s" x="26" y="80">IPST-WiFi + JSN-SR04T</text>
                  <text class="dg-s" x="26" y="100">วัดระยะถึงผิวน้ำ → ระดับ 0–3</text>
                  <text class="dg-s" x="26" y="120">ใช้พาวเวอร์แบงก์ 5 V</text>

                  <rect class="dg-box dg-new" x="257" y="30" width="206" height="104" rx="14"/>
                  <rect class="dg-tag" x="266" y="19" width="76" height="22" rx="11"/><text class="dg-tag-t" x="304" y="34" text-anchor="middle">แก้รุ่น 2</text>
                  <text class="dg-t" x="269" y="62">2 เซิร์ฟเวอร์</text>
                  <text class="dg-s" x="269" y="84">Apps Script + Google Sheet</text>
                  <text class="dg-s" x="269" y="104">คำนวณระดับ เก็บประวัติ</text>
                  <text class="dg-s" x="269" y="124">รายชื่อเปราะบางหลัง PIN</text>

                  <rect class="dg-box dg-new" x="500" y="30" width="206" height="104" rx="14"/>
                  <rect class="dg-tag" x="509" y="19" width="76" height="22" rx="11"/><text class="dg-tag-t" x="547" y="34" text-anchor="middle">แก้รุ่น 2</text>
                  <text class="dg-t" x="512" y="62">3 มือถืออาสา</text>
                  <text class="dg-s" x="512" y="84">Telegram/LINE + หน้าเว็บ</text>
                  <text class="dg-s" x="512" y="104">“ระดับ 2 เตือนภัย”</text>
                  <text class="dg-s" x="512" y="124">+ สิ่งที่ควรทำ ตามระดับ</text>

                  <rect class="dg-box" x="14" y="196" width="206" height="104" rx="14"/>
                  <text class="dg-t" x="26" y="222">เตือนที่ตลิ่งทันที</text>
                  <text class="dg-s" x="26" y="246">บัซเซอร์ + ไฟบนบอร์ด</text>
                  <text class="dg-s" x="26" y="266">ไม่ต้องรอเน็ต</text>
                  <text class="dg-s" x="26" y="286">ถ้าเน็ตหลุดยังเตือนเอง</text>

                  <rect class="dg-box dg-new" x="257" y="196" width="206" height="104" rx="14"/>
                  <rect class="dg-tag" x="266" y="185" width="76" height="22" rx="11"/><text class="dg-tag-t" x="304" y="200" text-anchor="middle">แก้รุ่น 2</text>
                  <text class="dg-t" x="269" y="228">4 ไซเรนและไฟ 3 สี</text>
                  <text class="dg-s" x="269" y="250">IPST-WiFi ตัวที่ 2 + LED</text>
                  <text class="dg-s" x="269" y="270">เขียว/เหลืองนิ่ง แดงกะพริบ</text>
                  <text class="dg-s" x="269" y="290">+ พาวเวอร์แบงก์ + ไฟไม่มีข้อมูล</text>

                  <rect class="dg-box" x="500" y="196" width="206" height="104" rx="14"/>
                  <text class="dg-t" x="512" y="228">5 คนในหมู่บ้าน</text>
                  <text class="dg-s" x="512" y="250">เห็นสีไฟ ได้ยินเสียง</text>
                  <text class="dg-s" x="512" y="270">รวมคนไม่มีมือถือ</text>
                  <text class="dg-s" x="512" y="290">ผู้ได้ยินไม่ชัดดูไฟ</text>

                  <path class="dg-ln" d="M222 82 L253 82" marker-end="url(#a4ar)"/>
                  <path class="dg-ln" d="M465 82 L496 82" marker-end="url(#a4ar)"/>
                  <path class="dg-ln" d="M117 136 L117 192" marker-end="url(#a4ar)"/>
                  <path class="dg-ln" d="M360 192 L360 138" marker-end="url(#a4ar)"/>
                  <path class="dg-ln" d="M465 248 L496 248" marker-end="url(#a4ar)"/>
                  <text class="dg-s" x="368" y="170">ถามระดับทุก 10–20 วินาที</text>
                  <text class="dg-s" x="124" y="170">ทันที</text>
                  <text class="dg-s" x="224" y="72">Wi-Fi</text>
                </svg>
                <figcaption class="sm mute" style="margin-top:6px">กล่องสีเหลืองคือส่วนที่ปรับในแบบร่างรุ่นที่ 2 (รายละเอียดในส่วนที่ 4)</figcaption>
              </figure>
              <ol style="margin-top:14px">
                <li><b>เริ่มทำงาน:</b> เปิดบอร์ด ต่อ Wi-Fi วัดระยะถึงผิวน้ำ (ยามปกติทุก 5 นาที ถี่ขึ้นเมื่อน้ำสูง) แล้วเทียบเกณฑ์ ถ้าถึงระดับเตือน บัซเซอร์และไฟที่ตลิ่งทำงานทันทีและส่งข้อมูลขึ้นเว็บ</li>
                <li><b>ประโยชน์:</b> อาสา/ผู้ใหญ่บ้านได้ข้อความ “ระดับ 2 เตือนภัย” พร้อมสิ่งที่ควรทำ เช่น พาผู้สูงอายุไปจุดนัดพบ ส่วนไซเรนและไฟให้คนไม่มีมือถือรู้</li>
                <li><b>ไฟดับ / ไม่มีเน็ต:</b> กล่องที่ตลิ่งใช้พาวเวอร์แบงก์และเตือนเองด้วยเสียงและไฟ ไม่ต้องรอเน็ต ถ้าข้อมูลเงียบเกิน 30 นาที เว็บแสดง “ไม่มีข้อมูล” ไม่ใช่สีเขียว</li>
              </ol>
            </div>
            <div class="why"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><p><b>ทำไมดี:</b> ผังมีหมายเลข ลูกศรมีทิศทาง และบอกชัดว่า <b>ข้อมูลเข้าจากไหน</b> (เซนเซอร์) <b>ออกเป็นอะไร</b> (ระดับ 0–3 เสียง ไฟ ข้อความ) <b>ผู้ใช้โต้ตอบตรงไหน</b> และข้อ 3 ตอบกรณีไฟดับ/เน็ตหลุดตรง ๆ รวมถึงสถานะ “ไม่มีข้อมูล” ที่ไม่ปล่อยให้ระบบเงียบแล้วดูเหมือนปลอดภัย</p></div></div>
          </div>
        </article>

        <article class="ex" id="a4-s3">
          <header class="ex-h"><span class="num-dot">3</span><h4>ขยายความคิดให้ละเอียดพอสำหรับสร้างจริง</h4></header>
          <div class="ex-b">
            <div class="ex-q"><b>ใบกิจกรรมถามว่า</b><p>เขียนส่วนประกอบของต้นแบบให้เพื่อนกลุ่มอื่นอ่านแล้วเข้าใจว่าต้องสร้างอะไร พร้อมจุดที่ยังคลุมเครือ</p></div>
            <div class="ex-a"><span class="lab">คำตอบของทีมยามน้ำ</span>
              <div class="tbl"><table>
                <thead><tr><th>ส่วนประกอบ</th><th>ลักษณะเฉพาะ / วิธีทำงาน (ขนาด วัสดุ ข้อมูลเข้า–ออก)</th><th>ผู้ใช้โต้ตอบอย่างไร</th></tr></thead>
                <tbody>
                  <tr><td><b>1. สถานีวัดน้ำ</b><br><span class="sm mute">IPST-WiFi + เซนเซอร์อัลตราโซนิกกันน้ำ + บัซเซอร์/OLED</span></td><td><b>เข้า:</b> ระยะจากเซนเซอร์ถึงผิวน้ำ → คำนวณความลึก<br><b>ออก:</b> ระดับ 0–3 + เสียง/ไฟ + ส่งข้อมูลขึ้นเว็บ</td><td>ผู้ใช้ไม่ต้องกดอะไร ดูไฟสถานะและฟังเสียง อาสาเป็นผู้ติดตั้งและตรวจแบตเตอรี่</td></tr>
                  <tr><td><b>2. เซิร์ฟเวอร์</b><br><span class="sm mute">Google Apps Script Web App + Google Sheet</span></td><td>รับข้อมูลที่มีรหัสลับ คำนวณระดับ เก็บประวัติ แจ้ง Telegram/LINE และแสดงหน้าเว็บบนมือถือ</td><td>อาสาเปิดหน้าเว็บดูสถานะและกราฟ รับข้อความเตือนในมือถือ</td></tr>
                  <tr><td><b>3. ไซเรนและไฟ 3 สี</b><br><span class="sm mute">IPST-WiFi ตัวที่ 2 + LED เขียว/เหลือง/แดง + บัซเซอร์</span></td><td>ถามระดับจากเว็บทุก 10–20 วินาที เขียว/เหลืองนิ่ง แดงกะพริบ + เสียง ถ้าข้อมูลหายแสดงไฟสลับ</td><td>คนในหมู่บ้านดูสีไฟและฟังเสียง ผู้ได้ยินไม่ชัดดูไฟ</td></tr>
                </tbody>
              </table></div>
              <div class="card flat" style="margin-top:14px"><b>จุดที่ยังคลุมเครือ และสิ่งที่ต้องทดลองหรือหาข้อมูลก่อนสร้าง</b>
                <ul style="margin:.4em 0 0">
                  <li><b>เกณฑ์ระดับน้ำจริงของลำห้วย</b> (กี่เซนติเมตรเป็นเหลือง/แดง) ยังไม่รู้ ต้องถามเทศบาล อบต. หรือผู้ใหญ่บ้าน ตอนนี้ใช้ค่าสมมติ</li>
                  <li><b>เซนเซอร์จะแม่นแค่ไหนเมื่อผิวน้ำเป็นคลื่นหรือมีขยะลอย</b> ต้องทดลองในถังน้ำที่มีคลื่น (แนวทาง: ใช้ค่ากลางของการวัดหลายครั้ง)</li>
                  <li><b>ไซเรนเตือนผิดจะทำให้คนเมิน</b> ต้องทดลองเรื่องการยืนยันก่อนลดระดับ และการดังเป็นช่วง ๆ ไม่ดังต่อเนื่อง</li>
                </ul>
              </div>
            </div>
            <div class="why"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><p><b>ทำไมดี:</b> ระบุชื่ออุปกรณ์ ข้อมูลเข้า–ออก และวิธีที่ผู้ใช้เข้าถึง จนเพื่อนกลุ่มอื่นเริ่มสร้างได้ ส่วน “จุดคลุมเครือ” แต่ละข้อบอกทั้ง <b>สิ่งที่ยังไม่รู้</b> และ <b>วิธีหาคำตอบ</b> ซึ่งตรงกับระดับสูงของเกณฑ์การขยายความคิด</p></div></div>
          </div>
        </article>

        <article class="ex" id="a4-s4">
          <header class="ex-h"><span class="num-dot">4</span><h4>ทดลองบนกระดาษและปรับเป็นรุ่นที่ 2</h4></header>
          <div class="ex-b">
            <div class="ex-q"><b>ใบกิจกรรมถามว่า</b><p>เดินตามสถานการณ์จำลอง 1 รอบ ผู้ใช้ทำอะไรเป็นขั้นแรกและติดขัดตรงไหน · ข้อเสนอแนะเฉพาะเจาะจง (ใครเสนอ) · ปรับอะไรในรุ่น 2 · ละทิ้งอะไร</p></div>
            <div class="ex-a"><span class="lab">คำตอบของทีมยามน้ำ</span>
              <div class="card flat"><b>สถานการณ์จำลอง:</b> ฝนตกตอน 03.00 น. น้ำในลำห้วยจำลองสูงถึงระดับเหลืองแล้วแดง ผู้ใช้คืออาสา ก ถือมือถือ
                <ul style="margin:.4em 0 0">
                  <li><b>ขั้นแรกของอาสา:</b> เปิดข้อความเตือน แล้วเปิดหน้าเว็บ</li>
                  <li><b>ติดขัด 1:</b> ข้อความบอกแค่ “ระดับ 2” ไม่รู้ว่าต้องทำอะไรและบ้านไหนต้องไปก่อน</li>
                  <li><b>ติดขัด 2:</b> ตอนจำลองไฟดับ กล่องที่ตลิ่งยังดังได้ แต่ไซเรนในหมู่บ้านไม่มีไฟเลี้ยง</li>
                </ul>
              </div>
              <div class="tbl" style="margin-top:14px"><table>
                <thead><tr><th>ข้อเสนอแนะ (ใครเสนอ)</th><th>สิ่งที่ปรับในรุ่นที่ 2</th><th>เหตุผล / ผลที่คาดว่าดีขึ้น</th></tr></thead>
                <tbody>
                  <tr><td><b>1.</b> เพื่อน ข (กลุ่มอื่น): ข้อความเตือนควรบอกว่าต้องทำอะไร</td><td>เพิ่มบรรทัด “สิ่งที่ควรทำ” 4 ข้อ ตามระดับ ในข้อความและหน้าเว็บ</td><td>อาสาไม่ต้องเดา ตัดสินใจเร็วขึ้น</td></tr>
                  <tr><td><b>2.</b> ครู: ไซเรนต้องมีไฟสำรอง และห้ามเผยชื่อผู้สูงอายุในหน้าเว็บสาธารณะ</td><td>เพิ่มพาวเวอร์แบงก์ และเก็บรายชื่อไว้หลัง PIN หน้าสาธารณะแสดงแค่จำนวนครัวเรือนที่ตรวจแล้ว</td><td>ใช้ได้ตอนไฟดับ และคุ้มครองข้อมูลส่วนบุคคล</td></tr>
                </tbody>
              </table></div>
              <div class="card flat" style="margin-top:14px"><b>แบบร่างรุ่นที่ 2 ต่างจากรุ่นที่ 1 อย่างไร</b>
                <ul style="margin:.4em 0 0">
                  <li>เพิ่มข้อความ “สิ่งที่ควรทำ” ตามระดับ</li>
                  <li>เพิ่มพาวเวอร์แบงก์ที่ไซเรน</li>
                  <li>เพิ่มไฟสถานะ “ไม่มีข้อมูล”</li>
                  <li>ย้ายรายชื่อบ้านเปราะบางไปไว้หลัง PIN</li>
                </ul>
                <p style="margin:.6em 0 0"><b>ส่วนที่ละทิ้ง:</b> ส่ง SMS เอง (ต้องพึ่งบริการภายนอก) และการเก็บชื่อจริงผู้สูงอายุในระบบ <b>เพราะ</b> ไม่ช่วยแก้ปัญหาหลักและเพิ่มความเสี่ยงเรื่องข้อมูลส่วนบุคคล</p>
              </div>
            </div>
            <div class="why"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><p><b>ทำไมดี:</b> ติดขัดทั้งสองข้อมาจากการ <b>เดินตามสถานการณ์จริง</b> ไม่ใช่นั่งเดา ข้อเสนอแนะระบุว่า <b>ใครเสนอ</b> เรื่องอะไร และทุกข้อปรับแล้วมีเหตุผล การละทิ้ง SMS และชื่อจริงแสดงว่าเลือกตัดเพราะไม่ช่วยโจทย์ ไม่ใช่เพราะขี้เกียจ</p></div></div>
          </div>
        </article>

        <article class="ex" id="a4-s5">
          <header class="ex-h"><span class="num-dot">5</span><h4>ให้ครูตรวจแบบร่างก่อนสร้างต้นแบบ</h4></header>
          <div class="ex-b">
            <div class="ex-q"><b>ใบกิจกรรมให้ครูทำ</b><p>ติ๊ก 3 ข้อ และเขียนข้อเสนอแนะกลับให้ก่อนลงมือสร้าง</p></div>
            <div class="ex-a"><span class="lab">สิ่งที่ครูตรวจ</span>
              <ul style="margin:0">
                <li>แบบร่างชัดเจนพอให้ผู้อื่นสร้างตามได้</li>
                <li>ปลอดภัย ไม่ต้องทดลองในภัยจริง</li>
                <li>อนุญาตให้สร้างต้นแบบ</li>
              </ul>
              <p class="sm mute" style="margin:.6em 0 0">ช่องข้อเสนอแนะจากครูมีไว้ให้ครูเขียนในใบกิจกรรมจริง ตัวอย่างนี้ไม่มีคำตอบสมมติให้</p>
            </div>
          </div>
        </article>

        <div class="callout note"><svg class="ic" aria-hidden="true"><use href="#i-arrow-r"/></svg><div><p><b>เชื่อมไปใบกิจกรรมที่ 5:</b> แบบร่างรุ่นที่ 2 คือพิมพ์เขียวที่ใช้ลงมือสร้าง ใบที่ 5 จะทบทวนผู้ใช้ เลือกทรัพยากร วางแผน และสร้างตามที่ออกแบบไว้</p></div></div>
      </div>
    </div>

    <!-- ---------- A4 : HAZARDS ---------- -->
    <div class="panel" role="tabpanel" id="p-a4-hz" aria-labelledby="t-a4-hz" hidden>
      <div class="stack">
        <div class="callout note"><svg class="ic" aria-hidden="true"><use href="#i-info"/></svg><div><p>เลือกภัยเพื่อดูแบบร่างรุ่นที่ 1 และรุ่นที่ 2 ของภัยนั้น พร้อมตัวอย่างคำตอบเต็มทุกหัวข้อของใบกิจกรรมที่ 4 ใช้เป็นตัวอย่างวิธีคิด ไม่ใช่คำตอบให้คัดลอก</p></div></div>
        <div class="hz" data-hz-for="a4"></div>
      </div>
    </div>

    <!-- ---------- A4 : RUBRIC ---------- -->
    <div class="panel" role="tabpanel" id="p-a4-rub" aria-labelledby="t-a4-rub" hidden>
      <div class="stack">
        <div class="card soft">
          <h3>ครูดูอะไร</h3>
          <p style="margin:0">ใบนี้ประเมินเพียง <b>องค์ประกอบที่ 2 การออกแบบและปรับปรุงความคิด</b> จาก 2 ประเด็น ระดับรวมครูตัดสินจากภาพรวมของหลักฐานรายบุคคลและผลงานกลุ่ม</p>
        </div>
        <div>
          <div class="lad-h"><h4>2.1 การขยายความคิด</h4><span class="pill">หลักฐาน: ส่วนที่ 2–3</span></div>
          <div class="ladder">
            <div class="rung"><small>1.0 ขั้นเริ่มต้น</small>สามารถอธิบายรายละเอียดหรือความคิดโดยทั่วไป</div>
            <div class="rung"><small>2.0 ขั้นพื้นฐาน</small>อธิบายความคิดเฉพาะเจาะจงพร้อมรายละเอียดที่เกี่ยวข้อง</div>
            <div class="rung"><small>3.0 ขั้นชำนาญ</small>อธิบายความคิดได้ชัดเจนและมีรายละเอียดเพียงพอสำหรับนำไปปฏิบัติจริงหรือผลการปฏิบัติที่ต้องการ</div>
            <div class="rung"><small>4.0 ขั้นสูง</small>อธิบายความคิดและสามารถระบุจุดที่ยังคลุมเครือหรืออุปสรรคที่อาจเกิดขึ้น เช่น การเตรียมแผนสำรอง</div>
          </div>
        </div>
        <div>
          <div class="lad-h"><h4>2.2 การทำซ้ำและปรับปรุง</h4><span class="pill">หลักฐาน: ส่วนที่ 1 (การละทิ้งแนวคิด) · ส่วนที่ 4 · หลักฐานรายบุคคล</span></div>
          <div class="ladder">
            <div class="rung"><small>1.0 ขั้นเริ่มต้น</small>สร้างตัวแทนของความคิด เช่น ภาพร่าง แผน แผนภาพ ผังงาน หรือพิมพ์เขียว เพื่อใช้เป็นแนวทางในการผลิตจริง และสามารถปรับแก้เบื้องต้นเมื่อได้รับคำแนะนำที่ชัดเจนและเฉพาะเจาะจง</div>
            <div class="rung"><small>2.0 ขั้นพื้นฐาน</small>สร้างแบบที่สามารถทดลองใช้ได้ เช่น แบบจำลอง ต้นแบบ การทดลองนำร่อง หรือ beta version เพื่อทดสอบสมมติฐานและคุณลักษณะต่าง ๆ และปรับปรุงความคิดหรือกระบวนการอย่างมีประสิทธิผลจากข้อมูลย้อนกลับที่เฉพาะเจาะจง</div>
            <div class="rung"><small>3.0 ขั้นชำนาญ</small>สร้างและทดสอบผลงานหรือแนวทางหลายรุ่น/หลายรูปแบบ เช่น A/B testing ปรับแก้ความคิดหรือกระบวนการในระดับที่ซับซ้อนหรือละเอียดตามข้อมูลย้อนกลับหรือเกณฑ์ทั่วไป และสามารถละทิ้งแนวทางที่ไม่สามารถนำไปสู่ผลผลิตหรือผลการปฏิบัติที่ต้องการ</div>
            <div class="rung"><small>4.0 ขั้นสูง</small>วิเคราะห์ตัวแปร ตลอดจนรูปแบบของความสำเร็จ ความล้มเหลว หรือผลที่ไม่ได้คาดหมายจากการทดลองหลายรอบ แล้วใช้ข้อมูลดังกล่าวตัดสินใจเกี่ยวกับขั้นตอนต่อไป รวมทั้งแสวงหาข้อมูลย้อนกลับที่ตรงประเด็นเพื่อนำมาปรับปรุงทั้งคุณภาพและจำนวนของความคิด</div>
          </div>
        </div>
        <div class="callout warn"><svg class="ic" aria-hidden="true"><use href="#i-warn"/></svg><div><h5>หมายเหตุจากใบกิจกรรม</h5><p>การทำซ้ำและปรับปรุงในระดับ 3.0–4.0 อาจต้องใช้หลักฐานต่อเนื่องจากใบกิจกรรมที่ 5–6 ประกอบ เพราะการทดสอบหลายรุ่นเกิดขึ้นหลังจากสร้างต้นแบบแล้ว</p></div></div>

        <div class="card">
          <h4>เช็กลิสต์ก่อนส่งใบกิจกรรมที่ 4</h4>
          <p class="sm mute">ติ๊กได้เลย เครื่องนี้จะจำไว้ให้ในเบราว์เซอร์ของคุณ ครูไม่เห็นเช็กลิสต์นี้</p>
          <ul class="checks" data-checks="a4">
            <li><label><input type="checkbox"><span>เปรียบเทียบ 3 แนวคิดครบทั้ง 3 ช่อง (ข้อดีต่อผู้ใช้ ข้อจำกัด/ความเสี่ยง ทำได้จริงในเวลา)</span></label></li>
            <li><label><input type="checkbox"><span>เลือกแนวคิดและให้เหตุผลครบ 4 ด้าน (แก้ตรงโจทย์ ผู้ใช้ ทรัพยากร ความปลอดภัย)</span></label></li>
            <li><label><input type="checkbox"><span>เขียนเหตุผลที่ไม่เลือกอีก 2 แนวคิด (หรือส่วนที่ละทิ้ง) และเงื่อนไขที่อาจทำให้เปลี่ยนใจ</span></label></li>
            <li><label><input type="checkbox"><span>ผังงานมีลูกศร หมายเลข ส่วนประกอบ ลำดับ ข้อมูลเข้า–ออก และจุดที่ผู้ใช้โต้ตอบ</span></label></li>
            <li><label><input type="checkbox"><span>อธิบายครบ 3 ข้อ: เริ่มทำงานอย่างไร · ผู้ใช้ได้ประโยชน์อะไร · ถ้าไฟดับ/ไม่มีเน็ตทำอย่างไร</span></label></li>
            <li><label><input type="checkbox"><span>ตารางส่วนประกอบละเอียดพอให้กลุ่มอื่นสร้างตามได้ และระบุจุดคลุมเครือพร้อมวิธีหาคำตอบ</span></label></li>
            <li><label><input type="checkbox"><span>ทดลองบนกระดาษ 1 รอบ จดว่าติดขัดตรงไหน และได้ข้อเสนอแนะเฉพาะเจาะจง (ระบุว่าใครเสนอ)</span></label></li>
            <li><label><input type="checkbox"><span>วาดแบบร่างรุ่นที่ 2 เฉพาะส่วนที่เปลี่ยน บอกส่วนที่ละทิ้ง และให้ครูตรวจก่อนสร้างต้นแบบ</span></label></li>
          </ul>
          <div class="meter" style="margin-top:14px" aria-hidden="true"><i data-meter="a4"></i></div>
          <p class="sm mute" style="margin:.5em 0 0" data-meter-text="a4">ติ๊กแล้ว 0 จาก 8 ข้อ</p>
        </div>
      </div>
    </div>

    <div class="pn">
      <a class="btn" href="#a3" data-go="a3"><svg class="ic" aria-hidden="true"><use href="#i-arrow-l"/></svg> ใบกิจกรรมที่ 3</a>
      <a class="btn pri" href="#a5" data-go="a5">ใบกิจกรรมที่ 5 ลงมือสร้างนวัตกรรม <svg class="ic" aria-hidden="true"><use href="#i-arrow-r"/></svg></a>
    </div>
  </div>
</section>
<!-- ====================== ACTIVITY 5 ====================== -->
<section class="view k5" id="v-a5" data-view="a5" hidden>
  <div class="ah k5">
    <div class="wrap ah-in">
      <div class="ah-num" aria-hidden="true">5</div>
      <div>
        <p class="stage">ขั้นที่ 5 · การสร้างและพัฒนาต้นแบบด้วยปัญญาประดิษฐ์</p>
        <h1>ลงมือ<wbr>สร้าง<wbr>นวัตกรรม</h1>
        <p class="mission-line">สร้างต้นแบบจำลองตามแบบร่าง บันทึกสิ่งที่ทำจริง แก้ปัญหาเมื่อเจออุปสรรค และตรวจสอบการใช้ AI อย่างรอบคอบ</p>
        <div class="pills">
          <span class="pill">5 ชั่วโมง</span>
          <span class="pill">ประเมิน องค์ประกอบที่ 5 การสร้างสรรค์ผลงานและนวัตกรรม</span>
          <span class="pill">ผู้ใช้ → ทรัพยากร → แผน → ลงมือ</span>
        </div>
        <p style="margin:14px 0 0"><a class="btn" href="https://docs.google.com/presentation/d/1oWbI54viUfUxMA3K5ywsokKSPJIjBtIIfMMG8mxP33Q/edit?usp=sharing" target="_blank" rel="noopener">เปิดใบกิจกรรมที่ 5 (Google Slides) <svg class="ic" aria-hidden="true"><use href="#i-link"/></svg></a></p>
      </div>
    </div>
  </div>

  <div class="wrap">
    <div class="tabs" role="tablist" aria-label="เมนูย่อยของใบกิจกรรมที่ 5">
      <button type="button" class="tab" role="tab" id="t-a5-learn" aria-controls="p-a5-learn" aria-selected="true" data-go="a5"><svg class="ic" aria-hidden="true"><use href="#i-book"/></svg>เรียนรู้</button>
      <button type="button" class="tab" role="tab" id="t-a5-ex" aria-controls="p-a5-ex" aria-selected="false" data-go="a5-ex"><svg class="ic" aria-hidden="true"><use href="#i-search"/></svg>ตัวอย่างละเอียด</button>
      <button type="button" class="tab" role="tab" id="t-a5-hz" aria-controls="p-a5-hz" aria-selected="false" data-go="a5-hz"><svg class="ic" aria-hidden="true"><use href="#i-users"/></svg>ตัวอย่าง 4 ภัยอื่น + ลองจำลอง</button>
      <button type="button" class="tab" role="tab" id="t-a5-rub" aria-controls="p-a5-rub" aria-selected="false" data-go="a5-rub"><svg class="ic" aria-hidden="true"><use href="#i-check"/></svg>เกณฑ์และเช็กลิสต์</button>
    </div>

    <!-- ---------- A5 : LEARN ---------- -->
    <div class="panel" role="tabpanel" id="p-a5-learn" aria-labelledby="t-a5-learn">
      <div class="stack">
        <div class="card">
          <p class="lede">ใบนี้ใช้เวลามากที่สุด (5 ชั่วโมง) เพราะต้องสร้างจริง ผลงานคือ <b>ต้นแบบจำลองที่แสดงหลักการ</b> ไม่ใช่ระบบเตือนภัยจริง และทุกส่วนที่เขียนต้องมีหลักฐานว่าทำจริงหรือยังไม่ได้ทำ</p>
          <div class="tbl tight"><table>
            <thead><tr><th>ส่วน</th><th>ทำอะไร</th></tr></thead>
            <tbody>
              <tr><td>1</td><td>ทบทวนผู้ใช้และข้อกำหนดก่อนสร้าง (จากใบที่ 2 และแบบร่างรุ่น 2 จากใบที่ 4)</td></tr>
              <tr><td>2</td><td>เตรียมความพร้อมและเลือกใช้ทรัพยากรอย่างปลอดภัย</td></tr>
              <tr><td>3</td><td>วางแผนการสร้าง ผู้รับผิดชอบ หลักฐาน และอันตรายที่คาด</td></tr>
              <tr><td>4</td><td>บันทึกการสร้างอย่างมีหลักฐาน และสรุปว่าทำอะไรได้แล้ว อะไรยังไม่ได้</td></tr>
              <tr><td>5</td><td>เมื่อพบอุปสรรค คิดทางเลือก ลองแก้ และจดผล</td></tr>
              <tr><td>6</td><td>บันทึกการใช้ AI อย่างรับผิดชอบ</td></tr>
              <tr><td>7</td><td>ตรวจความพร้อมของต้นแบบ ตั้งชื่อ สาธิตอย่างปลอดภัย แนบหลักฐาน</td></tr>
              <tr><td>8</td><td>เทียบกับวิธีที่มีอยู่จริง และเขียนว่าสิ่งที่เพิ่มอาจลดความเสี่ยงได้อย่างไร</td></tr>
              <tr><td>9</td><td>สาธิตสั้น ๆ รายบุคคล พร้อมอุปสรรคที่พบ 1 เรื่อง</td></tr>
            </tbody>
          </table></div>
        </div>

        <div class="callout note"><svg class="ic" aria-hidden="true"><use href="#i-info"/></svg><div><h5>เรียนจากแท็บ “ตัวอย่างละเอียด”</h5><p>ดูหลักคิดด้านล่าง แล้วเปิดแท็บ <b>ตัวอย่างละเอียด</b> และแท็บ <b>ตัวอย่าง 4 ภัยอื่น + ลองจำลอง</b> ที่มีเครื่องจำลองระดับ 0–3 ให้ลองปรับค่า</p><p style="margin:.6em 0 0"><button type="button" class="btn sm" data-go="a5-ex">ไปที่ตัวอย่างละเอียด <svg class="ic" aria-hidden="true"><use href="#i-arrow-r"/></svg></button></p></div></div>

        <ul class="toc" aria-label="หัวข้อในแท็บนี้">
          <li><a href="#" data-scroll="a5-l1"><i>1</i>ผู้ใช้ก่อนวงจร</a></li>
          <li><a href="#" data-scroll="a5-l2"><i>2</i>ปลอดภัยก่อน</a></li>
          <li><a href="#" data-scroll="a5-l3"><i>3</i>แผนและความเสี่ยง</a></li>
          <li><a href="#" data-scroll="a5-l4"><i>4</i>บันทึกอย่างมีหลักฐาน</a></li>
          <li><a href="#" data-scroll="a5-l5"><i>5</i>ใช้ AI รับผิดชอบ</a></li>
          <li><a href="#" data-scroll="a5-l6"><i>6</i>ไม่อ้างเกินจริง</a></li>
        </ul>

        <!-- 1 -->
        <div class="blk" id="a5-l1">
          <h3><span class="num-dot">1</span>เริ่มจากผู้ใช้ ไม่ใช่เริ่มจากวงจร</h3>
          <p>ก่อนต่อสายแรก ให้ถามว่าต้นแบบนี้ตอบ <b>ใคร</b> และ <b>ต้องการอะไร</b> เกณฑ์ประเมินให้ดูทั้งผู้ใช้หลักและ <b>ผู้ใช้กลุ่มอื่นที่อาจเกี่ยวข้อง</b></p>
          <div class="tbl tight"><table>
            <thead><tr><th>ผู้ใช้</th><th>ความต้องการและข้อจำกัด</th><th>ส่วนของต้นแบบที่ตอบ</th></tr></thead>
            <tbody>
              <tr><td>ผู้ใช้หลัก</td><td>ต้องรู้ก่อนเหตุมา ข้อความสั้นและทำตามได้ทันที ใช้มือถือเครื่องเก่า ตัวหนังสืออ่านง่าย</td><td>หน้าเว็บมือถือ + แจ้งเตือน + ข้อความ “สิ่งที่ควรทำ”</td></tr>
              <tr><td>ผู้ใช้กลุ่มอื่น</td><td>ไม่มีมือถือ หรือได้ยินไม่ชัด ต้องการเสียงดังชัด แสงที่มองเห็น และไม่ถูกเปิดเผยข้อมูลส่วนตัว</td><td>ไซเรนและไฟประจำหมู่บ้าน กล่องเตือนที่ตลิ่ง</td></tr>
            </tbody>
          </table></div>
          <p class="sm mute" style="margin:0">ตารางนี้เป็นรูปแบบจากตัวอย่างน้ำท่วม (ทีมยามน้ำ) ของกลุ่มคุณต้องเขียนจากผู้ใช้ของภัยที่เลือก</p>
        </div>

        <!-- 2 -->
        <div class="blk" id="a5-l2">
          <h3><span class="num-dot">2</span>ความปลอดภัยมาก่อนการสร้าง</h3>
          <div class="grid g2">
            <div class="card" style="--c:var(--a5)"><h4>ไฟฟ้า</h4><ul class="sm" style="margin:0;padding-left:1.2em"><li>ใช้ไฟ 5 V จากพาวเวอร์แบงก์เท่านั้น</li><li>ห้ามต่อไฟบ้าน 220 V ใกล้น้ำ</li><li>วางบอร์ดห่างน้ำ ใส่กล่องกันน้ำ</li><li>ให้ครูตรวจสายก่อนเปิดไฟทุกครั้ง</li></ul></div>
            <div class="card" style="--c:var(--a5)"><h4>สถานที่ทดสอบ</h4><ul class="sm" style="margin:0;padding-left:1.2em"><li>ทดสอบในถังน้ำใสบนโต๊ะ ครูอยู่ดูแล</li><li>ไม่ลงลำห้วย สระ หรือเขาจริง</li><li>ถ้าไม่มีอุปกรณ์หรือเน็ต ใช้โหมดจำลอง</li></ul></div>
            <div class="card" style="--c:var(--a5)"><h4>รหัสลับ</h4><ul class="sm" style="margin:0;padding-left:1.2em"><li>เก็บรหัสและโทเคนใน Script Properties</li><li>ห้ามใส่ในโค้ดหรือโพสต์ในกลุ่ม</li><li>ไฟล์ config.py ที่มีรหัส Wi-Fi ไม่ส่งต่อ</li><li>ซ่อนรหัสก่อนแนบภาพหน้าจอ</li></ul></div>
            <div class="card" style="--c:var(--a5)"><h4>ข้อความทดสอบ</h4><ul class="sm" style="margin:0;padding-left:1.2em"><li>ข้อความจากโหมดจำลองหน้าตาเหมือนข้อความจริง</li><li>ทดสอบกับกลุ่ม Telegram/LINE ทดลองของนักเรียน ไม่ใช่กลุ่มหมู่บ้านจริง</li><li>แจ้งผู้เกี่ยวข้องก่อนใช้โหมดจำลอง</li></ul></div>
          </div>

          <div class="card">
            <h4>ตัวอย่างข้อควรรู้: แรงดันที่ขา ECHO</h4>
            <p class="sm" style="margin:0 0 10px">เซนเซอร์วัดระยะแบบอัลตราโซนิกบางรุ่นส่งสัญญาณ ECHO แรงดัน 5 V แต่ขาของบอร์ด 3.3 V รับตรง ๆ แล้วอาจเสียหายได้ ตัวอย่างทีมยามน้ำแก้ด้วยตัวต้านทาน 1 kΩ + 2 kΩ แบ่งแรงดัน</p>
            <figure style="margin:0">
              <svg class="diagram" viewBox="0 0 640 200" role="img" aria-labelledby="a5vdT a5vdD">
                <title id="a5vdT">วงจรแบ่งแรงดันที่ขา ECHO</title>
                <desc id="a5vdD">สัญญาณ ECHO 5 โวลต์ผ่านตัวต้านทาน 1 กิโลโอห์ม ไปยังจุดต่อซึ่งต่อกับขา GPIO ของบอร์ดและต่อลงกราวด์ผ่านตัวต้านทาน 2 กิโลโอห์ม แรงดันที่จุดต่อประมาณ 3.3 โวลต์</desc>
                <rect class="dg-box" x="12" y="46" width="118" height="44" rx="10"/><text class="dg-t" x="24" y="73">ECHO 5 V</text>
                <path class="dg-ln" d="M130 68 L200 68"/>
                <rect class="dg-box dg-new" x="200" y="50" width="90" height="36" rx="8"/><text class="dg-t" x="245" y="74" text-anchor="middle">1 kΩ</text>
                <path class="dg-ln" d="M290 68 L420 68"/>
                <circle cx="360" cy="68" r="6" fill="var(--line)"/>
                <path class="dg-ln" d="M360 68 L360 100"/>
                <rect class="dg-box dg-new" x="330" y="100" width="60" height="36" rx="8"/><text class="dg-t" x="360" y="124" text-anchor="middle">2 kΩ</text>
                <path class="dg-ln" d="M360 136 L360 160"/>
                <path class="dg-ln" d="M340 160 L380 160"/><path class="dg-ln" d="M346 168 L374 168"/><path class="dg-ln" d="M353 176 L367 176"/>
                <text class="dg-s" x="392" y="168">กราวด์ (GND)</text>
                <rect class="dg-box" x="420" y="46" width="206" height="44" rx="10"/><text class="dg-t" x="432" y="73">ขา GPIO ของบอร์ด 3.3 V</text>
                <text class="dg-s" x="14" y="130">แรงดันที่จุดต่อ = 5 × 2 ÷ (1 + 2) ≈ 3.3 V</text>
                <text class="dg-s" x="14" y="152">ตรวจเลขขา GPIO กับคู่มือบอร์ดของโรงเรียนก่อนต่อ</text>
              </svg>
            </figure>
            <div class="quiz" data-quiz="b" style="margin-top:12px">
              <h5><span class="pill">ลองตอบ</span> ทำไมต้องมีตัวต้านทาน 2 ตัวระหว่าง ECHO กับบอร์ด</h5>
              <div class="opts">
                <button type="button" class="opt" data-k="a"><span class="k">ก</span><span>ให้วงจรดูซับซ้อนขึ้น</span></button>
                <button type="button" class="opt" data-k="b"><span class="k">ข</span><span>ลดสัญญาณ 5 V ให้เหลือราว 3.3 V ก่อนเข้าขาที่รับได้ 3.3 V</span></button>
                <button type="button" class="opt" data-k="c"><span class="k">ค</span><span>ให้เซนเซอร์วัดระยะได้ไกลขึ้น</span></button>
              </div>
              <div class="fb" hidden><b class="fb-h"></b><p>ตัวต้านทานสองตัวทำหน้าที่แบ่งแรงดัน 5 × 2 ÷ (1+2) ≈ 3.3 V ปกป้องขาบอร์ดจากความเสียหาย ไม่ได้ทำให้วัดไกลขึ้น</p></div>
            </div>
          </div>
        </div>

        <!-- 3 -->
        <div class="blk" id="a5-l3">
          <h3><span class="num-dot">3</span>วางแผนเป็นขั้น มีเจ้าของ มีหลักฐาน และคาดอุปสรรค</h3>
          <div class="flowline" aria-label="ลำดับการสร้างของตัวอย่างทีมยามน้ำ">
            <span class="pill">ต่อเซนเซอร์</span><span class="arrow" aria-hidden="true">→</span>
            <span class="pill">สร้างเว็บแอป</span><span class="arrow" aria-hidden="true">→</span>
            <span class="pill">โค้ดบอร์ด + ไซเรน</span><span class="arrow" aria-hidden="true">→</span>
            <span class="pill">ทดสอบรวม + ซ้อมตัดเน็ต</span>
          </div>
          <div class="tbl tight"><table>
            <thead><tr><th>ในแผนต้องมี</th><th>ตัวอย่างที่ดู “ใช้งานได้”</th></tr></thead>
            <tbody>
              <tr><td>ขั้นตอน</td><td>ต่อเซนเซอร์และบัซเซอร์เข้าบอร์ด ทดสอบอ่านระยะในถังน้ำ</td></tr>
              <tr><td>ผู้รับผิดชอบ</td><td>ก (ฮาร์ดแวร์) · ข (เซิร์ฟเวอร์) · ค (โค้ดบอร์ด) · ง (ไซเรน)</td></tr>
              <tr><td>หลักฐานความก้าวหน้า</td><td>ภาพวงจร + ตารางระยะที่อ่านได้เทียบกับไม้บรรทัด</td></tr>
              <tr><td>อันตรายที่คาด</td><td>ลัดวงจรใกล้น้ำ · ขาบอร์ดเสียจากสัญญาณ 5 V</td></tr>
              <tr><td>มาตรการ / ทางสำรอง</td><td>ใช้ 5 V วางห่างน้ำ ครูตรวจสาย · ต่อตัวต้านทานแบ่งแรงดันก่อนเสียบไฟ</td></tr>
            </tbody>
          </table></div>
          <div class="pair">
            <div class="bad"><h5>แผนที่ยังใช้ไม่ได้</h5><p style="margin:0">“ทุกคนช่วยกันทำ ทำให้เสร็จ”</p><p class="sm" style="margin:.5em 0 0">ไม่มีขั้น ไม่มีเจ้าของ ไม่มีหลักฐานให้ตรวจ</p></div>
            <div class="good"><h5>แผนที่ตรวจความก้าวหน้าได้</h5><p style="margin:0">“ขั้น 2 ข สร้างเว็บแอป ตั้ง Script Properties ทดสอบด้วยโหมดจำลอง หลักฐาน: ภาพหน้าเว็บ + ข้อความทดสอบใน Telegram”</p></div>
          </div>
        </div>

        <!-- 4 -->
        <div class="blk" id="a5-l4">
          <h3><span class="num-dot">4</span>บันทึกสิ่งที่ “ทำจริง” อย่าแต่งเรื่อง</h3>
          <p>ช่อง “สิ่งที่ลงมือทำจริง” ต้องบอกว่า <b>ต่างจากแผนตรงไหน</b> ถ้ามี และใครเป็นผู้ลงมือ พร้อมภาพหรือไฟล์หลักฐาน ส่วนที่ยังไม่ได้ทดสอบให้เขียนตรง ๆ ว่า <b>“ยังไม่ทดสอบ”</b></p>
          <div class="grid g2">
            <div class="callout bad"><svg class="ic" aria-hidden="true"><use href="#i-no"/></svg><div><h5>อย่าเขียนแบบนี้</h5><p>“ระบบเตือนน้ำป่าได้แม่นยำ 100%” โดยยังไม่มีผลทดลอง หรือเขียนผลทดสอบที่ไม่ได้ทดสอบจริง</p></div></div>
            <div class="callout safe"><svg class="ic" aria-hidden="true"><use href="#i-check"/></svg><div><h5>เขียนแบบนี้</h5><p>“วัดระดับในถังน้ำ → ตัดสินระดับ 0–3 → เตือนด้วยเสียงและไฟ ยังทำไม่ได้: วัดน้ำในลำห้วยจริงกลางแจ้งตอนฝนตก ส่วนที่ยังไม่ได้ทดสอบกับอุปกรณ์จริงเขียนว่ายังไม่ทดสอบ”</p></div></div>
          </div>
          <div class="quiz" data-quiz="c">
            <h5><span class="pill">ลองตอบ</span> ข้อใดเป็นสรุปที่ซื่อตรงที่สุด</h5>
            <div class="opts">
              <button type="button" class="opt" data-k="a"><span class="k">ก</span><span>ต้นแบบของเราเตือนภัยได้เหมือนระบบจริงของ ปภ.</span></button>
              <button type="button" class="opt" data-k="b"><span class="k">ข</span><span>ต้นแบบทำงานได้ทุกส่วนโดยไม่มีปัญหา</span></button>
              <button type="button" class="opt" data-k="c"><span class="k">ค</span><span>ต้นแบบแสดงหลักการวัดและเตือนได้ในถังน้ำ แต่ยังไม่ได้ทดสอบในลำห้วยจริงและห้ามใช้แทนประกาศทางการ</span></button>
            </div>
            <div class="fb" hidden><b class="fb-h"></b><p>ข้อ ค บอกทั้งสิ่งที่ทำได้ ขอบเขตการทดสอบ และสิ่งที่ยังไม่ควรอ้าง ตรงกับข้อกำหนดว่าห้ามอ้างเกินจริงและห้ามแทนประกาศทางการ</p></div>
          </div>
        </div>

        <!-- 5 -->
        <div class="blk" id="a5-l5">
          <h3><span class="num-dot">5</span>ใช้ AI ช่วยสร้างอย่างรับผิดชอบ</h3>
          <div class="grid g2">
            <div class="callout safe"><svg class="ic" aria-hidden="true"><use href="#i-check"/></svg><div><h5>ใช้ AI ช่วย</h5><ul style="margin:.3em 0 0;padding-left:1.2em"><li>อธิบายโค้ดที่ไม่เข้าใจ</li><li>เรียบเรียงข้อความเตือนให้สั้น</li></ul></div></div>
            <div class="callout bad"><svg class="ic" aria-hidden="true"><use href="#i-no"/></svg><div><h5>ไม่ให้ AI ตัดสิน</h5><ul style="margin:.3em 0 0;padding-left:1.2em"><li>เกณฑ์ระดับน้ำหรือค่าความปลอดภัย</li><li>การส่งเตือนภัยจริง</li><li>คำแนะนำให้ทดลองในที่อันตราย</li></ul></div></div>
          </div>
          <div class="tbl tight"><table>
            <thead><tr><th>ตารางบันทึกการใช้ AI มี 3 ช่อง</th><th>ตัวอย่างจากทีมยามน้ำ</th></tr></thead>
            <tbody>
              <tr><td>ใช้ AI ช่วยงานใด / คำสั่งย่อ</td><td>ให้ AI อธิบายโค้ดการหาค่ากลางและสถานะข้อมูลขาดหาย</td></tr>
              <tr><td>AI เสนออะไร</td><td>อธิบายว่าค่ากลางช่วยตัดค่าที่เพี้ยนออก</td></tr>
              <tr><td>เราตรวจและปรับเองอย่างไร</td><td>ทดลองในโหมดจำลองโดยใส่ค่าเพี้ยน แล้วดูว่าผลเป็นไปตามที่ AI บอกหรือไม่</td></tr>
            </tbody>
          </table></div>
          <div class="quiz" data-quiz="c">
            <h5><span class="pill">ลองตอบ</span> AI ให้ตัวเลขเกณฑ์ระดับน้ำมา 3 ค่า กลุ่มควรทำอย่างไร</h5>
            <div class="opts">
              <button type="button" class="opt" data-k="a"><span class="k">ก</span><span>ใช้ตามที่ AI ให้ เพราะ AI น่าจะรู้ดี</span></button>
              <button type="button" class="opt" data-k="b"><span class="k">ข</span><span>ปัดตัวเลขให้สวยแล้วใช้</span></button>
              <button type="button" class="opt" data-k="c"><span class="k">ค</span><span>ไม่ใช้ ใช้ค่าสมมติที่ระบุว่าเป็นสมมติ และขอเกณฑ์จริงจากเทศบาล อบต. หรือผู้ใหญ่บ้าน</span></button>
            </div>
            <div class="fb" hidden><b class="fb-h"></b><p>ตัวเลขจาก AI ไม่มีที่มา และเกณฑ์จริงขึ้นกับลำห้วยของหมู่บ้านนั้น ต้องมาจากข้อมูลท้องถิ่น ทีมยามน้ำบันทึกว่า “ไม่ใช้” ในช่องข้อมูลที่ไม่ใช้เพราะไม่มีหลักฐานยืนยัน</p></div>
          </div>
        </div>

        <!-- 6 -->
        <div class="blk" id="a5-l6">
          <h3><span class="num-dot">6</span>บอกว่า “อาจลดความเสี่ยง” ไม่ใช่ “ลดแล้ว”</h3>
          <p>ในส่วนที่ 8 ให้เขียนเป็น <b>สมมติฐาน</b> ที่อธิบายเหตุผลสนับสนุนได้ แต่ <b>ไม่อ้างประสิทธิภาพก่อนมีผลทดลอง</b> และเทียบกับวิธีที่มีอยู่จริง (เช่น การเตือนระดับอำเภอ การเฝ้าดูด้วยตา) ว่าเราเปลี่ยนหรือเพิ่มอะไร</p>
          <div class="pair">
            <div class="bad"><h5>อ้างเกินจริง</h5><p style="margin:0">“ต้นแบบนี้ช่วยให้ผู้สูงอายุอพยพทันทุกครั้ง”</p></div>
            <div class="good"><h5>สมมติฐานที่ซื่อตรง</h5><p style="margin:0">“ถ้ารู้ระดับน้ำที่ลำห้วยหมู่บ้านเราและเตือนที่หน้างานทันที อาสาอาจมีเวลาพาผู้สูงอายุออกได้มากขึ้น (ยังไม่อ้างว่าได้ผลจนกว่าจะมีผลทดลอง)”</p></div>
          </div>
        </div>
      </div>
    </div>

    <!-- ---------- A5 : WORKED EXAMPLE ---------- -->
    <div class="panel" role="tabpanel" id="p-a5-ex" aria-labelledby="t-a5-ex" hidden>
      <div class="stack">
        <div class="card soft">
          <span class="tag-sim">ตัวอย่างเพื่อการเรียนรู้</span>
          <h3 style="margin-top:10px">ทีมยามน้ำ สร้างต้นแบบ “เพื่อนบ้านเตือนภัย”</h3>
          <p class="mute" style="margin:0">ข้อความที่ระบุ “(สมมติ)” คือตัวอย่างวิธีเขียน ไม่ใช่ผลที่วัดได้จริง นักเรียนต้องบันทึกผลจริงของกลุ่มตนเอง ตัวเลขเกณฑ์ระดับน้ำเป็นค่าสมมติทั้งหมด</p>
        </div>
        <ul class="toc" aria-label="ส่วนของใบกิจกรรมที่ 5">
          <li><a href="#" data-scroll="a5-s1"><i>1</i>ผู้ใช้</a></li>
          <li><a href="#" data-scroll="a5-s2"><i>2</i>ทรัพยากร</a></li>
          <li><a href="#" data-scroll="a5-s3"><i>3</i>แผนและความเสี่ยง</a></li>
          <li><a href="#" data-scroll="a5-s4"><i>4</i>บันทึกการสร้าง</a></li>
          <li><a href="#" data-scroll="a5-s5"><i>5</i>อุปสรรค</a></li>
          <li><a href="#" data-scroll="a5-s6"><i>6</i>บันทึก AI</a></li>
          <li><a href="#" data-scroll="a5-s7"><i>7</i>ความพร้อม</a></li>
          <li><a href="#" data-scroll="a5-s8"><i>8</i>ต่างจากเดิม</a></li>
          <li><a href="#" data-scroll="a5-s9"><i>9</i>สาธิต</a></li>
        </ul>

        <article class="ex" id="a5-s1">
          <header class="ex-h"><span class="num-dot">1</span><h4>ทบทวนผู้ใช้และข้อกำหนดก่อนสร้าง</h4></header>
          <div class="ex-b">
            <div class="ex-q"><b>ใบกิจกรรมถามว่า</b><p>ผู้ใช้/กลุ่มเป้าหมาย · ความต้องการและข้อจำกัดสำคัญ · ส่วนของต้นแบบที่จะตอบความต้องการนี้</p></div>
            <div class="ex-a"><span class="lab">คำตอบของทีมยามน้ำ</span>
              <div class="tbl"><table>
                <thead><tr><th>ผู้ใช้</th><th>ความต้องการและข้อจำกัด</th><th>ส่วนของต้นแบบที่ตอบ</th></tr></thead>
                <tbody>
                  <tr><td><b>ผู้ใช้หลัก:</b> อาสาสมัคร / เพื่อนบ้านที่ดูแลผู้สูงอายุ</td><td>ต้องรู้ก่อนน้ำมา ข้อความสั้นและทำตามได้ทันที ใช้มือถือเครื่องเก่า ตัวหนังสือต้องอ่านง่าย</td><td>หน้าเว็บมือถือ + แจ้งเตือน Telegram/LINE + ข้อความ “สิ่งที่ควรทำ”</td></tr>
                  <tr><td><b>ผู้ใช้อื่น:</b> ผู้สูงอายุที่ไม่มีมือถือ / ผู้ที่ได้ยินไม่ชัด</td><td>ต้องการเสียงที่ดังชัดและแสงที่มองเห็น และไม่ถูกเปิดเผยข้อมูลส่วนตัว</td><td>ไซเรนและไฟ 3 สีประจำหมู่บ้าน กล่องเตือนที่ตลิ่ง</td></tr>
                </tbody>
              </table></div>
            </div>
            <div class="why"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><p><b>ทำไมดี:</b> แยกผู้ใช้เป็น 2 กลุ่มและโยงแต่ละความต้องการกับส่วนของต้นแบบ ทำให้เห็นว่ากล่องที่ตลิ่ง ไซเรน และหน้าเว็บมีไว้ตอบใคร</p></div></div>
          </div>
        </article>

        <article class="ex" id="a5-s2">
          <header class="ex-h"><span class="num-dot">2</span><h4>เตรียมความพร้อมและเลือกใช้ทรัพยากร</h4></header>
          <div class="ex-b">
            <div class="ex-q"><b>ใบกิจกรรมถามว่า</b><p>ติ๊กความปลอดภัย 5 ข้อ แล้วเลือก วัสดุ–อุปกรณ์ เครื่องมือ–เทคโนโลยี และ AI พร้อมเหตุผลและข้อควรระวัง</p></div>
            <div class="ex-a"><span class="lab">คำตอบของทีมยามน้ำ</span>
              <p style="margin:0 0 10px"><span class="pill">วัสดุปลอดภัย</span> <span class="pill">ไม่ทดลองในภัยจริง</span> <span class="pill">ไม่ใช้ไฟฟ้าเสี่ยงอันตราย</span> <span class="pill">กำหนดผู้รับผิดชอบ</span> <span class="sm mute">· ข้อ “ครูตรวจแผนแล้ว” ให้ครูเป็นผู้ติ๊ก</span></p>
              <div class="tbl"><table>
                <thead><tr><th>รายการ</th><th>เลือกใช้ / เหตุผล</th><th>ข้อควรระวัง / การตรวจสอบ</th></tr></thead>
                <tbody>
                  <tr><td><b>วัสดุ–อุปกรณ์</b></td><td>IPST-WiFi 2 ตัว เซนเซอร์อัลตราโซนิกกันน้ำ (JSN-SR04T) LED เขียว/เหลือง/แดง พร้อมตัวต้านทาน 220 Ω สายจั๊มเปอร์ พาวเวอร์แบงก์ ถังใสจำลองลำห้วย · เลือกเพราะโรงเรียนมีบอร์ดอยู่แล้ว ราคาไม่สูง และทดสอบบนโต๊ะได้</td><td>ใช้ไฟ 5 V จากพาวเวอร์แบงก์เท่านั้น ไม่ใช้ไฟบ้านใกล้น้ำ · ขา ECHO ของเซนเซอร์เป็นสัญญาณ 5 V ต้องผ่านตัวต้านทาน 1 kΩ + 2 kΩ ก่อนเข้าบอร์ด 3.3 V · ทดสอบในถังน้ำเท่านั้น</td></tr>
                  <tr><td><b>เครื่องมือ–เทคโนโลยี</b></td><td>Thonny/microBlock เขียน MicroPython ลงบอร์ด · Google Apps Script + Google Sheets · Telegram Bot · เลือกเพราะฟรีและใช้บัญชี Google ของโรงเรียนได้</td><td>รหัสลับและโทเคนเก็บใน Script Properties ห้ามใส่ในโค้ดหรือโพสต์ในกลุ่ม · ไฟล์ config.py ที่มีรหัส Wi-Fi ไม่ส่งต่อ</td></tr>
                  <tr><td><b>AI (ถ้าใช้)</b></td><td>ใช้ AI อธิบายโค้ดที่ไม่เข้าใจ และช่วยเรียบเรียงข้อความเตือนให้สั้น · ไม่ให้ AI ตัดสินเกณฑ์ระดับน้ำ</td><td>ตรวจกับประกาศ ปภ./ท้องถิ่นและทดลองเอง ห้ามใส่ข้อมูลส่วนตัวใน Prompt · เกณฑ์น้ำใช้ข้อมูลหมู่บ้านจริง ไม่ใช้ตัวเลขที่ AI เดา</td></tr>
                </tbody>
              </table></div>
            </div>
            <div class="why"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><p><b>ทำไมดี:</b> ทุกทรัพยากรมี <b>เหตุผลที่เลือก</b> และ <b>มาตรการความปลอดภัยที่ตรวจได้</b> เช่น ตัวแบ่งแรงดัน 1 kΩ + 2 kΩ และ Script Properties ส่วน AI ถูกจำกัดบทบาทชัดเจนว่าอธิบายโค้ดและเรียบเรียงข้อความ ไม่ตัดสินเกณฑ์</p></div></div>
          </div>
        </article>

        <article class="ex" id="a5-s3">
          <header class="ex-h"><span class="num-dot">3</span><h4>วางแผนการสร้างและคาดการณ์อุปสรรค</h4></header>
          <div class="ex-b">
            <div class="ex-q"><b>ใบกิจกรรมถามว่า</b><p>ขั้นตอนลงมือสร้าง ผู้รับผิดชอบ หลักฐานความก้าวหน้า · อันตรายที่คาด ผลกระทบ มาตรการป้องกัน และผลที่ตรวจพบ</p></div>
            <div class="ex-a"><span class="lab">คำตอบของทีมยามน้ำ</span>
              <div class="tbl"><table>
                <thead><tr><th>ขั้นตอนลงมือสร้าง</th><th>ผู้รับผิดชอบ</th><th>หลักฐานตรวจความก้าวหน้า</th></tr></thead>
                <tbody>
                  <tr><td>ขั้น 1 ต่อเซนเซอร์และบัซเซอร์เข้าบอร์ด ทดสอบอ่านระยะในถังน้ำ</td><td>ก (ฮาร์ดแวร์)</td><td>ภาพวงจร + ตารางระยะที่อ่านได้เทียบกับไม้บรรทัด</td></tr>
                  <tr><td>ขั้น 2 สร้างเว็บแอป Apps Script + Google Sheet ตั้ง Script Properties และทดสอบด้วยโหมดจำลอง</td><td>ข (เซิร์ฟเวอร์)</td><td>ภาพหน้าเว็บ + ข้อความทดสอบใน Telegram</td></tr>
                  <tr><td>ขั้น 3 เขียนโค้ดบอร์ดส่งข้อมูลขึ้นเว็บ และต่อไซเรน/ไฟ 3 สี</td><td>ค (โค้ดบอร์ด) ง (ไซเรน)</td><td>วิดีโอสั้นไฟเปลี่ยนสีตามระดับน้ำในถัง</td></tr>
                  <tr><td>ขั้น 4 ทดสอบระบบรวมและซ้อมสถานการณ์ตัดเน็ต/ไฟดับจำลอง</td><td>ทั้งกลุ่ม</td><td>ใบบันทึกผลทดสอบ + ภาพถ่าย</td></tr>
                </tbody>
              </table></div>
              <div class="tbl" style="margin-top:14px"><table>
                <thead><tr><th>อันตราย / ข้อจำกัดที่คาด</th><th>ผลกระทบหากเกิดขึ้น</th><th>มาตรการป้องกัน / ทางสำรอง</th><th>ตรวจแล้วพบอะไร</th></tr></thead>
                <tbody>
                  <tr><td>ไฟฟ้า/พาวเวอร์แบงก์ใกล้น้ำ ลัดวงจร</td><td>ผู้ทดลองได้รับอันตราย บอร์ดเสีย</td><td>ใช้ 5 V วางบอร์ดห่างน้ำ ใส่กล่องกันน้ำ ครูตรวจสายก่อนเปิดไฟ</td><td>(สมมติ) ครูตรวจสายไฟก่อนเปิดทุกครั้ง ไม่พบสายเปลือยใกล้น้ำ</td></tr>
                  <tr><td>สัญญาณ ECHO 5 V เข้าขาบอร์ด 3.3 V ทำให้ขาบอร์ดเสีย</td><td>บอร์ดเสียหาย ต้องเปลี่ยนใหม่</td><td>ต่อตัวต้านทาน 1 kΩ + 2 kΩ แบ่งแรงดัน ก่อนเสียบไฟ</td><td>(สมมติ) วัดด้วยมัลติมิเตอร์ที่ขา ECHO ได้ไม่เกิน 3.3 V ก่อนต่อ</td></tr>
                </tbody>
              </table></div>
            </div>
            <div class="why"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><p><b>ทำไมดี:</b> ทุกขั้นมี <b>คนรับผิดชอบ</b> และ <b>หลักฐานที่เปิดดูได้</b> ส่วนตารางอันตรายคาดการณ์ปัญหาก่อนเกิด และมี “ตรวจแล้วพบอะไร” แสดงว่ามาตรการถูกตรวจจริง ไม่ใช่เขียนไว้เฉย ๆ</p></div></div>
          </div>
        </article>

        <article class="ex" id="a5-s4">
          <header class="ex-h"><span class="num-dot">4</span><h4>บันทึกการสร้างอย่างมีหลักฐาน</h4></header>
          <div class="ex-b">
            <div class="ex-q"><b>ใบกิจกรรมถามว่า</b><p>ลำดับ · สิ่งที่ลงมือทำจริง (ระบุสิ่งที่เปลี่ยนจากแผน) · ผู้ลงมือและภาพหรือไฟล์หลักฐาน · สรุปว่าทำอะไรได้ ยังทำไม่ได้อะไร</p></div>
            <div class="ex-a"><span class="lab">คำตอบของทีมยามน้ำ</span>
              <div class="tbl"><table>
                <thead><tr><th>#</th><th>สิ่งที่ลงมือทำจริง</th><th>ผู้ลงมือ / หลักฐาน</th></tr></thead>
                <tbody>
                  <tr><td>1</td><td>ต่อเซนเซอร์: TRIG เข้า GPIO25, ECHO ผ่านตัวแบ่งแรงดันเข้า GPIO19 (ตรวจเลขขากับคู่มือบอร์ดของโรงเรียนก่อน) แล้วรันโหมดจำลองก่อนต่อเซนเซอร์จริง</td><td>ก / ภาพถ่ายวงจร</td></tr>
                  <tr><td>2</td><td>สร้างเว็บแอป: วางโค้ด Code.gs และ Index.html ตั้ง Script Properties รัน setup() เลือกชุดน้ำท่วม แล้ว Deploy เป็น Web App</td><td>ข / ภาพหน้าเว็บ + ข้อความทดสอบ</td></tr>
                  <tr><td>3</td><td>ใส่ Wi-Fi/URL/รหัสลับในไฟล์ config.py แล้วอัปโหลดไฟล์ขึ้นบอร์ด รันโหมดจริง</td><td>ค / ภาพหน้าจอ (ซ่อนรหัสก่อนแนบ)</td></tr>
                  <tr><td>4</td><td>ต่อบอร์ดไซเรน: LED เขียว GPIO5 เหลือง GPIO19 แดง GPIO23 ผ่านตัวต้านทาน 220 Ω และบัซเซอร์บนบอร์ด</td><td>ง / วิดีโอไฟ 3 สี</td></tr>
                </tbody>
              </table></div>
              <div class="card flat" style="margin-top:14px"><b>สรุป (สมมติ — ตัวอย่างวิธีเขียน)</b>
                <p style="margin:.4em 0 0"><b>ทำงานได้ / แสดงหลักการ:</b> วัดระดับในถังน้ำ → ตัดสินระดับ 0–3 → เตือนด้วยเสียงและไฟที่ตลิ่ง → ส่งขึ้นเว็บและมือถือ → ไซเรนในหมู่บ้านเปลี่ยนสีตามระดับ</p>
                <p style="margin:.4em 0 0"><b>ยังทำไม่ได้:</b> วัดน้ำในลำห้วยจริงกลางแจ้งตอนฝนตก · ใช้แทนประกาศทางการ · ส่วนที่ยังไม่ได้ทดสอบกับอุปกรณ์จริงให้เขียนว่า “ยังไม่ทดสอบ”</p>
              </div>
            </div>
            <div class="why"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><p><b>ทำไมดี:</b> บอกเลขขา วิธีทดสอบ และผู้ลงมือ ทุกแถวมีหลักฐานแนบ มีข้อควรระวังเรื่องซ่อนรหัสก่อนแนบภาพ และแยก “ทำได้” กับ “ยังทำไม่ได้” ไว้ชัด</p></div></div>
          </div>
        </article>

        <article class="ex" id="a5-s5">
          <header class="ex-h"><span class="num-dot">5</span><h4>เมื่อพบอุปสรรค เราคิดและแก้อย่างไร</h4></header>
          <div class="ex-b">
            <div class="ex-q"><b>ใบกิจกรรมถามว่า</b><p>อุปสรรค/สาเหตุ · ทางเลือกที่เสนอ · วิธีที่ลองจริงและผลที่พบ · ตัวอย่าง 1 เหตุการณ์ที่กลุ่มเปลี่ยนแผนเอง (ก่อน–หลัง–เหตุผล)</p></div>
            <div class="ex-a"><span class="lab">คำตอบของทีมยามน้ำ</span>
              <div class="tbl"><table>
                <thead><tr><th>อุปสรรค / สาเหตุที่คาด</th><th>ทางเลือกที่เสนอ</th><th>วิธีที่ลองจริง / ผลที่พบ</th></tr></thead>
                <tbody>
                  <tr><td><b>1.</b> ค่าระยะแกว่งเพราะผิวน้ำเป็นคลื่น</td><td>ใช้ค่ากลางของการวัด 5 ครั้ง หรือติดท่อกันคลื่นรอบเซนเซอร์</td><td>(สมมติ) ลองค่ากลางแล้วค่ากระโดดน้อยลง ต้องวัดซ้ำหลายครั้งเพื่อยืนยัน</td></tr>
                  <tr><td><b>2.</b> Wi-Fi หลุด ข้อมูลไม่ขึ้นเว็บ</td><td>ให้กล่องที่ตลิ่งเตือนเองก่อน แล้วลองส่งใหม่ · ใช้ฮอตสปอตมือถือแทนชั่วคราว</td><td>(สมมติ) ปิด Wi-Fi ระหว่างทดสอบ บัซเซอร์ยังดังตามระดับ ข้อมูลส่งขึ้นเว็บใหม่เมื่อเชื่อมต่อได้</td></tr>
                </tbody>
              </table></div>
              <div class="card flat" style="margin-top:14px"><b>เหตุการณ์ที่กลุ่มเปลี่ยนแผนเอง</b>
                <dl class="kv" style="margin-top:8px">
                  <dt>ก่อน</dt><dd>วางแผนให้ส่งข้อมูลขึ้นเว็บก่อนแล้วจึงเตือน</dd>
                  <dt>หลัง</dt><dd>ให้เตือนที่ตลิ่งก่อน แล้วค่อยส่งขึ้นเว็บ</dd>
                  <dt>เหตุผล (สมมติ)</dt><dd>ตอนซ้อมตัดเน็ตพบว่าถ้าส่งเว็บไม่ได้จะไม่มีอะไรเตือนเลย จึงสลับลำดับ</dd>
                </dl>
              </div>
            </div>
            <div class="why"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><p><b>ทำไมดี:</b> เสนอ <b>มากกว่า 1 ทางเลือก</b> แล้วจึงลอง และผลบอกตรง ๆ ว่ายังต้องวัดซ้ำ ไม่สรุปเกินหลักฐาน การสลับลำดับเตือนเป็นการเปลี่ยนแผนที่ได้จากการซ้อมจริง</p></div></div>
          </div>
        </article>

        <article class="ex" id="a5-s6">
          <header class="ex-h"><span class="num-dot">6</span><h4>บันทึกการใช้ AI อย่างรับผิดชอบ</h4></header>
          <div class="ex-b">
            <div class="ex-q"><b>ใบกิจกรรมถามว่า</b><p>ใช้ AI ช่วยงานใด · AI เสนออะไร · เราตรวจและปรับอย่างไร · ข้อมูลใดจาก AI ที่ไม่ใช้เพราะไม่เหมาะสม ไม่ปลอดภัย หรือไม่มีหลักฐาน</p></div>
            <div class="ex-a"><span class="lab">คำตอบของทีมยามน้ำ</span>
              <div class="tbl"><table>
                <thead><tr><th>ใช้ AI ช่วยงานใด</th><th>AI เสนออะไร</th><th>เราตรวจและปรับเองอย่างไร</th></tr></thead>
                <tbody>
                  <tr><td><b>1.</b> ให้ AI อธิบายโค้ดการหาค่ากลางและสถานะข้อมูลขาดหาย</td><td>อธิบายว่าค่ากลางช่วยตัดค่าที่เพี้ยนออก</td><td>ทดลองในโหมดจำลองโดยใส่ค่าเพี้ยน แล้วดูว่าผลเป็นไปตามที่ AI บอกหรือไม่</td></tr>
                  <tr><td><b>2.</b> ให้ AI ช่วยเรียบเรียงข้อความเตือน 4 ระดับให้สั้น</td><td>ข้อความสั้น มีอีโมจิและคำที่ทำให้ตกใจ</td><td>ตัดคำที่ทำให้ตกใจเกินจริง ใส่เบอร์ ปภ. 1784 และข้อความว่าเป็นต้นแบบของโรงเรียน ให้ฟังประกาศทางการเป็นหลัก</td></tr>
                </tbody>
              </table></div>
              <div class="card flat" style="margin-top:14px"><b>ข้อมูลจาก AI ที่กลุ่มไม่ใช้</b>
                <ul style="margin:.4em 0 0">
                  <li><b>ไม่ใช้:</b> ตัวเลขเกณฑ์ระดับน้ำที่ AI ให้ เพราะไม่มีที่มา ใช้ค่าสมมติและขอข้อมูลจริงจากท้องถิ่น</li>
                  <li><b>ไม่ใช้:</b> ไอเดียส่ง SMS ฉุกเฉินเอง เพราะการเตือนภัยจริงเป็นหน้าที่หน่วยงานทางการ (เช่น Cell Broadcast ของ ปภ.)</li>
                  <li><b>ไม่ใช้:</b> คำแนะนำให้ลองในลำห้วยจริง เพราะอันตราย</li>
                </ul>
              </div>
            </div>
            <div class="why"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><p><b>ทำไมดี:</b> ทุกแถวมีการ <b>ตรวจด้วยตนเอง</b> (ทดลองใส่ค่าเพี้ยน ตัดคำที่ตกใจเกินจริง) และบอกชัดว่า <b>ไม่ใช้อะไร เพราะอะไร</b> โดยเฉพาะข้อที่เกี่ยวกับความปลอดภัยและหน้าที่ของหน่วยงานทางการ</p></div></div>
          </div>
        </article>

        <article class="ex" id="a5-s7">
          <header class="ex-h"><span class="num-dot">7</span><h4>ตรวจความพร้อมของต้นแบบจำลอง</h4></header>
          <div class="ex-b">
            <div class="ex-q"><b>ใบกิจกรรมถามว่า</b><p>ตรวจ 4 เกณฑ์พร้อมหลักฐาน · ชื่อของต้นแบบ · วิธีสาธิตอย่างปลอดภัย · หลักฐานภาพถ่าย/ไฟล์/ลิงก์</p></div>
            <div class="ex-a"><span class="lab">คำตอบของทีมยามน้ำ</span>
              <div class="tbl"><table>
                <thead><tr><th>เกณฑ์</th><th>หลักฐานที่เห็นจริง / สิ่งที่ต้องแก้</th></tr></thead>
                <tbody>
                  <tr><td>ตรงปัญหาและตอบผู้ใช้ที่กำหนด</td><td>ตรง: กล่องเตือนที่ตลิ่ง + แจ้งอาสา + ไซเรน ตอบโจทย์ “กลางคืน ไม่มีเน็ต ผู้สูงอายุ” · หลักฐาน: ใบกิจกรรมที่ 2 ข้อ 3</td></tr>
                  <tr><td>แสดงการทำงานได้ / อธิบายขั้นตอนชัด</td><td>สาธิตในถังน้ำ: ยกระดับน้ำแล้วไฟเปลี่ยนเขียว → เหลือง → แดง พร้อมเสียง · หลักฐาน: วิดีโอสาธิต</td></tr>
                  <tr><td>เลือกใช้ทรัพยากรเหมาะสมและปลอดภัย</td><td>ใช้ไฟ 5 V ไม่ใช้ไฟบ้าน เก็บรหัสลับนอกโค้ด · หลักฐาน: ตารางความเสี่ยงข้อ 3</td></tr>
                  <tr><td>ต่างจากวิธีทั่วไปอย่างมีเหตุผล</td><td>ต่างจาก Cell Broadcast ระดับอำเภอ: วัดระดับลำห้วยของหมู่บ้านเอง และเตือนที่หน้างานแม้ไม่มีเน็ต แต่ไม่ได้แทนประกาศทางการ</td></tr>
                </tbody>
              </table></div>
              <dl class="kv" style="margin-top:14px">
                <dt>ชื่อต้นแบบ</dt><dd>เพื่อนบ้านเตือนภัย (ต้นแบบเฝ้าระวังน้ำป่า)</dd>
                <dt>วิธีสาธิตอย่างปลอดภัย</dt><dd>สาธิตในถังน้ำใสบนโต๊ะ ใช้ไฟ 5 V จากพาวเวอร์แบงก์ ครูอยู่ดูแล เติมน้ำช้า ๆ ให้ถึงระดับเหลือง/แดงตามเกณฑ์ที่กำหนดไว้ · ถ้าไม่มีอุปกรณ์หรือเน็ต: ใช้โหมดจำลองในโค้ดและปุ่ม “โหมดจำลอง” ในหน้าเว็บ ไม่ต้องลงน้ำจริง</dd>
                <dt>หลักฐานที่ต้องแนบ</dt><dd>ภาพถ่ายวงจร วิดีโอสั้นสาธิต ภาพหน้าจอเว็บแอป (ลิงก์ Google Drive ของกลุ่ม ห้ามมีรหัสลับในภาพ)</dd>
              </dl>
            </div>
            <div class="why"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><p><b>ทำไมดี:</b> ทุกเกณฑ์ชี้ไปที่ <b>หลักฐานที่เปิดดูได้</b> (วิดีโอ ตารางความเสี่ยง ใบที่ 2) และมีวิธีสาธิตสำรองสำหรับกรณีไม่มีอุปกรณ์หรือเน็ต</p></div></div>
          </div>
        </article>

        <article class="ex" id="a5-s8">
          <header class="ex-h"><span class="num-dot">8</span><h4>ต้นแบบเราต่างจากวิธีที่มีอยู่จริงอย่างไร</h4></header>
          <div class="ex-b">
            <div class="ex-q"><b>ใบกิจกรรมถามว่า</b><p>วิธีที่มีอยู่ก่อน · สิ่งที่เราเปลี่ยน/เพิ่ม · ประโยชน์ต่อผู้ใช้ · หลักฐานที่ตรวจสอบได้ · ทำไมอาจลดความเสี่ยง (ไม่อ้างประสิทธิภาพ) · ถ้าผู้ใช้อีกกลุ่มต้องปรับอะไร</p></div>
            <div class="ex-a"><span class="lab">คำตอบของทีมยามน้ำ</span>
              <div class="tbl"><table>
                <thead><tr><th>วิธีที่มีอยู่ก่อน</th><th>สิ่งที่เราเปลี่ยน/เพิ่ม</th><th>ประโยชน์ต่อผู้ใช้</th><th>หลักฐานตรวจสอบได้</th></tr></thead>
                <tbody>
                  <tr><td>Cell Broadcast ของ ปภ. ระดับอำเภอ (ข่าวฟากท่า 11 ก.ค. 2568) · การเฝ้าดูน้ำด้วยตาของคนในหมู่บ้าน</td><td>เซนเซอร์วัดระดับน้ำเฉพาะลำห้วยของหมู่บ้าน · เตือนที่หน้างานแม้ไม่มีเน็ต · สถานะ “ไม่มีข้อมูล” และรายชื่อบ้านเปราะบางหลัง PIN</td><td>อาสารู้ระดับน้ำใกล้บ้านผู้สูงอายุ · คนไม่มีมือถือก็ได้ยิน/เห็นสัญญาณ · รู้เมื่อระบบเสีย</td><td>วิดีโอสาธิต · บันทึกผลทดสอบใบกิจกรรมที่ 6 · ข่าวอ้างอิงในใบกิจกรรมที่ 1</td></tr>
                </tbody>
              </table></div>
              <div class="card flat" style="margin-top:14px"><b>ทำไมสิ่งที่เพิ่มจึงอาจลดความเสี่ยงได้ (สมมติฐาน)</b>
                <p style="margin:.4em 0 0">ถ้ารู้ระดับน้ำที่ลำห้วยหมู่บ้านเราและเตือนที่หน้างานทันที อาสาอาจมีเวลาพาผู้สูงอายุออกได้มากขึ้น <b>(ยังไม่อ้างว่าได้ผลจนกว่าจะมีผลทดลอง)</b> เหตุผลสนับสนุน: ข่าวฟากท่า ลับแล น้ำปาด ชี้ว่าน้ำมาเร็ว มาตอนกลางคืน และสัญญาณล่มได้ ส่วนงานวิจัยที่ไทยพีบีเอสอ้างว่าการเตือนทันเวลาเพิ่มแนวโน้มการอพยพ</p>
              </div>
              <div class="card flat" style="margin-top:12px"><b>ถ้าผู้ใช้อีกกลุ่มต้องใช้ต้นแบบนี้</b>
                <ul style="margin:.4em 0 0">
                  <li><b>โรงเรียนริมคลอง:</b> ปรับข้อความเตือนให้ครู และให้ไซเรนได้ยินในสนาม</li>
                  <li><b>ผู้ที่ได้ยินไม่ชัด:</b> เพิ่มไฟแสงสว่างกะพริบแรงแทนเสียง หรือใช้ตัวสั่นเตือน</li>
                </ul>
              </div>
            </div>
            <div class="why"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><p><b>ทำไมดี:</b> เทียบกับวิธีที่มีอยู่จริงและไม่ได้บอกว่าดีกว่า แต่บอกว่าเพิ่มอะไร เขียนเป็นสมมติฐานที่มีเหตุผลสนับสนุนและกำกับไว้ว่ายังไม่มีผลทดลอง และคิดถึงผู้ใช้อีกกลุ่มซึ่งตรงกับระดับสูงของเกณฑ์ “กลุ่มเป้าหมาย”</p></div></div>
          </div>
        </article>

        <article class="ex" id="a5-s9">
          <header class="ex-h"><span class="num-dot">9</span><h4>สาธิตสั้น ๆ ให้ดู (รายบุคคล)</h4></header>
          <div class="ex-b">
            <div class="ex-q"><b>ใบกิจกรรมถามว่า</b><p>ฉันรับผิดชอบส่วนใด · ส่วนนี้ทำงานอย่างไร · จะสาธิตให้เห็นอะไร · ข้อบกพร่องหรืออุปสรรคที่พบ 1 เรื่อง ลองแก้อย่างไร และผลที่เกิด</p></div>
            <div class="ex-a"><span class="lab">คำตอบ (มุมของนักเรียน ก)</span>
              <dl class="kv">
                <dt>ฉันรับผิดชอบ</dt><dd>บอร์ดสถานีวัดน้ำ (ฮาร์ดแวร์)</dd>
                <dt>ทำงานอย่างไร</dt><dd>เซนเซอร์วัดระยะ → บอร์ดแปลงเป็นระดับ 0–3 → ถ้าระดับ 2 ขึ้นไป บัซเซอร์ดังและส่งข้อมูลขึ้นเว็บ</dd>
                <dt>จะสาธิต</dt><dd>เติมน้ำในถังถึงเส้นเหลือง/แดงให้ดูไฟและเสียงเปลี่ยน แล้วปิด Wi-Fi ให้ดูว่ายังเตือนเอง</dd>
                <dt>อุปสรรคที่พบ (สมมติ)</dt><dd>ตอนผิวน้ำเป็นคลื่น ค่าระยะกระโดด ทำให้ระดับสลับไปมา</dd>
                <dt>ลองแก้</dt><dd>ใช้ค่ากลางของการวัด 5 ครั้ง และติดท่อกันคลื่นรอบเซนเซอร์</dd>
                <dt>ผลที่เกิด</dt><dd>นักเรียนบันทึกผลจริงของกลุ่ม (ตัวอย่างนี้ไม่ได้กรอกผลให้)</dd>
              </dl>
            </div>
            <div class="why"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><p><b>ทำไมดี:</b> ส่วนนี้เป็น <b>หลักฐานรายบุคคล</b> ว่าแต่ละคนเข้าใจส่วนที่ตนรับผิดชอบ และสาธิตให้เห็นทั้งการทำงานปกติกับกรณีปิด Wi-Fi ที่เป็นจุดสำคัญของโจทย์</p></div></div>
          </div>
        </article>

        <div class="callout note"><svg class="ic" aria-hidden="true"><use href="#i-arrow-r"/></svg><div><p><b>เชื่อมไปใบกิจกรรมที่ 6:</b> ต้นแบบที่สร้างเสร็จจะถูกนำไปทดสอบในสถานการณ์จำลอง วัดผลตามเกณฑ์ที่ตั้งไว้ก่อน แล้วปรับปรุงและสะท้อนผล</p></div></div>
      </div>
    </div>

    <!-- ---------- A5 : HAZARDS + SIMULATOR ---------- -->
    <div class="panel" role="tabpanel" id="p-a5-hz" aria-labelledby="t-a5-hz" hidden>
      <div class="stack">
        <div class="callout note"><svg class="ic" aria-hidden="true"><use href="#i-info"/></svg><div><p>เลือกภัยเพื่อดูชิ้นงานที่ทำได้ ค่าตั้งต้น ข้อความ “สิ่งที่ควรทำ” และลองเลื่อนค่าในเครื่องจำลองระดับ 0–3 ซึ่งใช้เกณฑ์ตัวอย่างจากเอกสารเท่านั้น ไม่ใช่เกณฑ์ทางการ ด้านล่างคือตัวอย่างคำตอบเต็มทุกหัวข้อของใบกิจกรรมที่ 5</p></div></div>
        <div class="hz" data-hz-for="a5"></div>
      </div>
    </div>

    <!-- ---------- A5 : RUBRIC ---------- -->
    <div class="panel" role="tabpanel" id="p-a5-rub" aria-labelledby="t-a5-rub" hidden>
      <div class="stack">
        <div class="card soft">
          <h3>ครูดูอะไร</h3>
          <p style="margin:0">ใบนี้ประเมินเพียง <b>องค์ประกอบที่ 5 การสร้างสรรค์ผลงานและนวัตกรรม</b> จาก 4 ประเด็น ระดับรวมครูตัดสินจากภาพรวมของหลักฐานรายบุคคลและผลงานกลุ่ม</p>
        </div>

        <div>
          <div class="lad-h"><h4>5.1 กลุ่มเป้าหมาย</h4><span class="pill">หลักฐาน: ส่วนที่ 1, 8</span></div>
          <div class="ladder">
            <div class="rung"><small>1.0 ขั้นเริ่มต้น</small>ระบุรายละเอียดเกี่ยวกับกลุ่มเป้าหมาย รวมถึงความต้องการและความสนใจที่อาจมีผลต่อผลงานหรือแนวทางแก้ปัญหา</div>
            <div class="rung"><small>2.0 ขั้นพื้นฐาน</small>นำความคิดริเริ่มมาพัฒนาเป็นผลงานที่สัมพันธ์กับกลุ่มเป้าหมาย</div>
            <div class="rung"><small>3.0 ขั้นชำนาญ</small>นำความคิดริเริ่มมาพัฒนาเป็นผลิตภัณฑ์ที่ตอบสนองความต้องการหรือความสนใจของกลุ่มเป้าหมายได้อย่างมีประสิทธิผล</div>
            <div class="rung"><small>4.0 ขั้นสูง</small>พิจารณามุมมองของผู้ใช้/กลุ่มเป้าหมายหลายกลุ่มและปรับความคิดให้เหมาะกับความต้องการและความสนใจที่แตกต่างกัน</div>
          </div>
        </div>
        <div>
          <div class="lad-h"><h4>5.2 การใช้ทรัพยากร</h4><span class="pill">หลักฐาน: ส่วนที่ 2, 6 · หลักฐานรายบุคคล</span></div>
          <div class="ladder">
            <div class="rung"><small>1.0 ขั้นเริ่มต้น</small>ระบุวัสดุหรือทรัพยากรที่จำเป็นสำหรับงาน</div>
            <div class="rung"><small>2.0 ขั้นพื้นฐาน</small>เลือกวัสดุหรือทรัพยากรที่เหมาะสมกับผลงานหรือแนวทางแก้ปัญหา</div>
            <div class="rung"><small>3.0 ขั้นชำนาญ</small>บูรณาการวัสดุหรือทรัพยากรอย่างมีประสิทธิผลในการสร้างผลงานหรือแนวทางแก้ปัญหา</div>
            <div class="rung"><small>4.0 ขั้นสูง</small>ปรับประยุกต์ทรัพยากรเพื่อพัฒนาผลงานหรือแนวทางแก้ปัญหาที่เป็นนวัตกรรม และใช้ทรัพยากรในลักษณะใหม่หรือไม่คาดคิด</div>
          </div>
        </div>
        <div>
          <div class="lad-h"><h4>5.3 การวางแผน</h4><span class="pill">หลักฐาน: ส่วนที่ 3</span></div>
          <div class="ladder">
            <div class="rung"><small>1.0 ขั้นเริ่มต้น</small>อธิบายข้อกำหนดของภาระงาน</div>
            <div class="rung"><small>2.0 ขั้นพื้นฐาน</small>กำหนดขั้นตอนโดยทั่วไปเพื่อให้เป็นไปตามข้อกำหนดของงาน</div>
            <div class="rung"><small>3.0 ขั้นชำนาญ</small>วิเคราะห์องค์ประกอบของผลงานและกำหนดรายละเอียดในแผนอย่างชัดเจน เฉพาะเจาะจง และหลากหลาย</div>
            <div class="rung"><small>4.0 ขั้นสูง</small>คาดการณ์ปัญหาหรืออุปสรรคที่อาจเกิดขึ้น และวางแผนเพื่อหลีกเลี่ยง เอาชนะ หรือฟื้นตัวจากอุปสรรคอย่างมีประสิทธิผล</div>
          </div>
        </div>
        <div>
          <div class="lad-h"><h4>5.4 การผลิต</h4><span class="pill">หลักฐาน: ส่วนที่ 4, 5, 7, 9 · หลักฐานรายบุคคล</span></div>
          <div class="ladder">
            <div class="rung"><small>1.0 ขั้นเริ่มต้น</small>สามารถสร้างผลงานให้เสร็จสมบูรณ์</div>
            <div class="rung"><small>2.0 ขั้นพื้นฐาน</small>สร้างผลงานได้ตามข้อกำหนดสำคัญของแผน</div>
            <div class="rung"><small>3.0 ขั้นชำนาญ</small>สร้างผลงานตามแผนและตรงตามข้อกำหนดทั้งหมด พร้อมปรับเปลี่ยนเมื่อจำเป็น</div>
            <div class="rung"><small>4.0 ขั้นสูง</small>พัฒนาผลงานให้ดียิ่งกว่าสิ่งที่กำหนดไว้ในแผนเดิม</div>
          </div>
        </div>

        <div class="card">
          <h4>เช็กลิสต์ก่อนส่งใบกิจกรรมที่ 5</h4>
          <p class="sm mute">ติ๊กได้เลย เครื่องนี้จะจำไว้ให้ในเบราว์เซอร์ของคุณ ครูไม่เห็นเช็กลิสต์นี้</p>
          <ul class="checks" data-checks="a5">
            <li><label><input type="checkbox"><span>ทบทวนผู้ใช้หลักและผู้ใช้กลุ่มอื่น พร้อมส่วนของต้นแบบที่ตอบความต้องการ</span></label></li>
            <li><label><input type="checkbox"><span>ติ๊กความปลอดภัยครบ ใช้ไฟ 5 V ไม่ทดลองในภัยจริง และให้ครูตรวจแผนก่อนลงมือ</span></label></li>
            <li><label><input type="checkbox"><span>เลือกวัสดุ เครื่องมือ และ AI พร้อมเหตุผลและข้อควรระวังครบทุกแถว</span></label></li>
            <li><label><input type="checkbox"><span>แผนมีขั้นตอน ผู้รับผิดชอบ หลักฐานความก้าวหน้า และตารางอันตราย/แผนสำรอง</span></label></li>
            <li><label><input type="checkbox"><span>บันทึกการสร้างตามที่ทำจริง ระบุสิ่งที่เปลี่ยนจากแผน และเขียน “ยังไม่ทดสอบ” ในส่วนที่ยังไม่ได้ทดสอบ</span></label></li>
            <li><label><input type="checkbox"><span>บันทึกอุปสรรคอย่างน้อย 2 เรื่อง พร้อมทางเลือกและผลที่ลองจริง และ 1 เหตุการณ์ที่เปลี่ยนแผนเอง</span></label></li>
            <li><label><input type="checkbox"><span>บันทึกการใช้ AI และระบุข้อมูลจาก AI ที่ไม่ใช้พร้อมเหตุผล ไม่ใส่ข้อมูลส่วนตัวใน Prompt</span></label></li>
            <li><label><input type="checkbox"><span>มีหลักฐานแนบ (ภาพวงจร วิดีโอสาธิต ภาพหน้าจอ) และซ่อนรหัสลับในภาพแล้ว</span></label></li>
            <li><label><input type="checkbox"><span>เขียนผลต่างจากวิธีที่มีอยู่เป็นสมมติฐาน ไม่อ้างประสิทธิภาพก่อนมีผลทดลอง และเตรียมสาธิตสั้น ๆ รายบุคคล</span></label></li>
          </ul>
          <div class="meter" style="margin-top:14px" aria-hidden="true"><i data-meter="a5"></i></div>
          <p class="sm mute" style="margin:.5em 0 0" data-meter-text="a5">ติ๊กแล้ว 0 จาก 9 ข้อ</p>
        </div>
      </div>
    </div>

    <div class="pn">
      <a class="btn" href="#a4" data-go="a4"><svg class="ic" aria-hidden="true"><use href="#i-arrow-l"/></svg> ใบกิจกรรมที่ 4</a>
      <a class="btn pri" href="#a6" data-go="a6">ใบกิจกรรมที่ 6 ทดลองปรับปรุง <svg class="ic" aria-hidden="true"><use href="#i-arrow-r"/></svg></a>
    </div>
  </div>
</section>
<!-- ====================== ACTIVITY 6 ====================== -->
<section class="view k6" id="v-a6" data-view="a6" hidden>
  <div class="ah k6">
    <div class="wrap ah-in">
      <div class="ah-num" aria-hidden="true">6</div>
      <div>
        <p class="stage">ขั้นที่ 6 · การทดสอบ ประเมิน ปรับปรุง และสะท้อนผล</p>
        <h1>ทดลอง<wbr>ปรับปรุง</h1>
        <p class="mission-line">ตั้งเกณฑ์สำเร็จก่อนทดลอง ทดสอบในสถานการณ์จำลองที่ปลอดภัย ปรับ ทดสอบซ้ำ แล้วใช้ผลจริงสะท้อนผลงานและวิธีทำงานของตน</p>
        <div class="pills">
          <span class="pill">2 ชั่วโมง</span>
          <span class="pill">ประเมิน องค์ประกอบที่ 6 การกำกับตนเองและการสะท้อนคิด</span>
          <span class="pill">วางแผน → ทดลอง → ปรับ → ทดสอบซ้ำ → สะท้อน</span>
        </div>
        <p style="margin:14px 0 0"><a class="btn" href="https://docs.google.com/presentation/d/1aDtDVsUYh00QO1QMOxUxrfpQNuwiddnR0rajAUyevjU/edit?usp=sharing" target="_blank" rel="noopener">เปิดใบกิจกรรมที่ 6 (Google Slides) <svg class="ic" aria-hidden="true"><use href="#i-link"/></svg></a></p>
      </div>
    </div>
  </div>

  <div class="wrap">
    <div class="tabs" role="tablist" aria-label="เมนูย่อยของใบกิจกรรมที่ 6">
      <button type="button" class="tab" role="tab" id="t-a6-learn" aria-controls="p-a6-learn" aria-selected="true" data-go="a6"><svg class="ic" aria-hidden="true"><use href="#i-book"/></svg>เรียนรู้</button>
      <button type="button" class="tab" role="tab" id="t-a6-ex" aria-controls="p-a6-ex" aria-selected="false" data-go="a6-ex"><svg class="ic" aria-hidden="true"><use href="#i-search"/></svg>ตัวอย่างละเอียด</button>
      <button type="button" class="tab" role="tab" id="t-a6-hz" aria-controls="p-a6-hz" aria-selected="false" data-go="a6-hz"><svg class="ic" aria-hidden="true"><use href="#i-users"/></svg>ตัวอย่าง 4 ภัยอื่น</button>
      <button type="button" class="tab" role="tab" id="t-a6-rub" aria-controls="p-a6-rub" aria-selected="false" data-go="a6-rub"><svg class="ic" aria-hidden="true"><use href="#i-check"/></svg>เกณฑ์และเช็กลิสต์</button>
    </div>

    <!-- ---------- A6 : LEARN ---------- -->
    <div class="panel" role="tabpanel" id="p-a6-learn" aria-labelledby="t-a6-learn">
      <div class="stack">
        <div class="card">
          <p class="lede">ใบนี้ตอบคำถามว่า <b>ต้นแบบของเราดีขึ้นจริงไหม และเรารู้ได้อย่างไร</b> คำตอบต้องมาจากผลทดลองและข้อเสนอแนะ ไม่ใช่ความรู้สึก และต้องกล้าเขียนทั้งจุดแข็งและจุดอ่อน</p>
          <div class="tbl tight"><table>
            <thead><tr><th>ส่วน</th><th>ทำอะไร</th></tr></thead>
            <tbody>
              <tr><td>1</td><td>วางแผนทดลองสถานการณ์จำลอง: ใครทดลอง วัดอะไร เกณฑ์สำเร็จที่ตั้ง <b>ก่อน</b> ทดสอบ เก็บผลอย่างไร</td></tr>
              <tr><td>2</td><td>ผลทดลองรอบที่ 1 ก่อนปรับปรุง และข้อเสนอแนะ 1–2 ข้อ (ระบุว่าใครเสนอ)</td></tr>
              <tr><td>3</td><td>ปรับตามหลักฐาน ทดสอบซ้ำในเงื่อนไขที่เทียบเคียงได้ และตรวจว่าเงื่อนไขสองรอบเหมือนกันหรือไม่</td></tr>
              <tr><td>4</td><td>สะท้อนคิดผลงานและกระบวนการ ว่าสิ่งใดยังไม่ควรใช้จริง และตั้งคำถามกับวิธีทำงานของตนเอง</td></tr>
            </tbody>
          </table></div>
        </div>

        <div class="callout note"><svg class="ic" aria-hidden="true"><use href="#i-info"/></svg><div><h5>เรียนจากแท็บ “ตัวอย่างละเอียด”</h5><p>ดูหลักคิดและเครื่องคำนวณเล็ก ๆ ด้านล่าง แล้วเปิดแท็บ <b>ตัวอย่างละเอียด</b> ซึ่งมีกราฟเทียบผลรอบ 1 กับรอบ 2</p><p style="margin:.6em 0 0"><button type="button" class="btn sm" data-go="a6-ex">ไปที่ตัวอย่างละเอียด <svg class="ic" aria-hidden="true"><use href="#i-arrow-r"/></svg></button></p></div></div>

        <ul class="toc" aria-label="หัวข้อในแท็บนี้">
          <li><a href="#" data-scroll="a6-l1"><i>1</i>ตั้งเกณฑ์ก่อน</a></li>
          <li><a href="#" data-scroll="a6-l2"><i>2</i>ผลจริง ไม่แต่ง</a></li>
          <li><a href="#" data-scroll="a6-l3"><i>3</i>ทดสอบซ้ำให้เทียบได้</a></li>
          <li><a href="#" data-scroll="a6-l4"><i>4</i>สะท้อนด้วยหลักฐาน</a></li>
          <li><a href="#" data-scroll="a6-l5"><i>5</i>ยังไม่ควรใช้จริง</a></li>
          <li><a href="#" data-scroll="a6-l6"><i>6</i>เป้าหมายรอบหน้า</a></li>
        </ul>

        <!-- 1 -->
        <div class="blk" id="a6-l1">
          <h3><span class="num-dot">1</span>ตั้งเกณฑ์สำเร็จ “ก่อน” ทดสอบ</h3>
          <p>ถ้าเขียนเกณฑ์หลังเห็นผล เรามักตั้งให้ผลของตัวเองผ่านพอดี ใบกิจกรรมจึงให้กำหนดเกณฑ์ไว้ล่วงหน้า วัดได้ และเลือกวิธีเก็บผล</p>
          <div class="pair">
            <div class="bad"><h5>เกณฑ์ที่วัดไม่ได้</h5><p style="margin:0">“ระบบเตือนได้ดี ผู้ใช้พอใจ”</p><p class="sm" style="margin:.5em 0 0">ไม่มีตัวเลข ไม่รู้ว่าผ่านหรือไม่ผ่านเมื่อไร</p></div>
            <div class="good"><h5>เกณฑ์ที่วัดได้</h5><p style="margin:0">“เวลาจากน้ำถึงระดับแดงจนเสียงเตือนที่ตลิ่งดัง ไม่เกิน 5 วินาที จับเวลา 3 ครั้งแล้วหาค่าเฉลี่ย”</p></div>
          </div>
          <div class="tbl tight"><table>
            <thead><tr><th>ในแผนทดลองต้องมี</th><th>ตัวอย่างจากทีมยามน้ำ</th></tr></thead>
            <tbody>
              <tr><td>สถานการณ์จำลอง</td><td>น้ำป่ากลางคืนในถังน้ำจำลองลำห้วย ปิด Wi-Fi บางช่วงแทนการไม่มีเน็ต ปิดไฟห้องแทนไฟดับ</td></tr>
              <tr><td>ผู้ทดลอง</td><td>เพื่อนกลุ่มอื่น 2 คนรับบทอาสา (ไม่รู้ล่วงหน้าว่าน้ำจะถึงระดับใดเมื่อไร) ครูเป็นผู้สังเกต</td></tr>
              <tr><td>ความปลอดภัย</td><td>ใช้ไฟ 5 V บนโต๊ะ ไม่ทดลองในลำห้วยจริง</td></tr>
              <tr><td>สิ่งที่วัด · เกณฑ์ · วิธีเก็บผล</td><td>เวลาถึงเสียงเตือน · ไม่เกิน 5 วินาที · จับเวลา 3 ครั้งแล้วหาค่าเฉลี่ย<br>อาสารู้ว่าต้องทำอะไร · 2 ใน 2 คนบอกขั้นตอนถูกใน 30 วินาที · ถามแล้วจดลงตาราง</td></tr>
            </tbody>
          </table></div>
          <div class="quiz" data-quiz="b">
            <h5><span class="pill">ลองตอบ</span> ข้อใดคือเกณฑ์สำเร็จที่ดีสำหรับต้นแบบเตือนฝุ่น</h5>
            <div class="opts">
              <button type="button" class="opt" data-k="a"><span class="k">ก</span><span>ผู้ใช้รู้สึกว่าธงสวยและเข้าใจง่าย</span></button>
              <button type="button" class="opt" data-k="b"><span class="k">ข</span><span>ผู้ทดลอง 2 ใน 2 คนบอกได้ถูกว่าธงแต่ละสีให้ทำอะไร ภายใน 30 วินาที</span></button>
              <button type="button" class="opt" data-k="c"><span class="k">ค</span><span>ระบบทำงานได้ดีตามที่คาดไว้</span></button>
            </div>
            <div class="fb" hidden><b class="fb-h"></b><p>ข้อ ข มีจำนวนคน เวลา และสิ่งที่ต้องทำได้ชัดเจน จึงบอกได้ว่าผ่านหรือไม่ผ่าน ส่วน ก และ ค เป็นความรู้สึกที่วัดไม่ได้</p></div>
          </div>
        </div>

        <!-- 2 -->
        <div class="blk" id="a6-l2">
          <h3><span class="num-dot">2</span>บันทึกผลรอบที่ 1 ตามจริง</h3>
          <p>ช่อง “ผลที่เกิดจริง” ใบกิจกรรมเขียนกำกับว่า <b>ไม่แต่งข้อมูล</b> ผลที่ไม่ผ่านไม่ใช่ความล้มเหลวของนักเรียน แต่คือข้อมูลที่บอกว่าต้องแก้ตรงไหน ตัวเลขในตัวอย่างของเว็บนี้เป็น “สมมติ” เพื่อสอนวิธีเขียน</p>
          <div class="callout warn"><svg class="ic" aria-hidden="true"><use href="#i-warn"/></svg><div><h5>ข้อเสนอแนะต้องบอกว่าใครเสนอ</h5><p>เช่น “ผู้ทดลอง ก: อยากให้ข้อความขึ้นต้นด้วยคำสั่งสั้น ๆ เช่น ‘ไปบ้านผู้สูงอายุก่อน’” และ “ครู: ไซเรนควรดังเป็นช่วง ๆ ไม่ดังต่อเนื่อง” ไม่ต้องระบุข้อมูลส่วนตัวของผู้ทดลอง</p></div></div>
        </div>

        <!-- 3 -->
        <div class="blk" id="a6-l3">
          <h3><span class="num-dot">3</span>ทดสอบซ้ำให้ “เทียบกันได้”</h3>
          <p>การทดสอบซ้ำควรเหมือนรอบแรกให้มากที่สุด ทั้งผู้ทดลอง เหตุการณ์ ระยะทาง แหล่งข้อมูล และอุปกรณ์ ถ้ามีอะไรเปลี่ยน ต้องเขียนว่า <b>ผลเปรียบเทียบอาจคลาดเคลื่อนอย่างไร</b></p>

          <div class="card" data-trial>
            <h4>ลองคำนวณเทียบผลสองรอบ</h4>
            <p class="sm mute">ค่าตั้งต้นคือตัวอย่างสมมติของทีมยามน้ำ (วินาที) แก้เป็นตัวเลขของกลุ่มคุณได้ เครื่องคำนวณนี้ไม่เก็บอะไรไว้</p>
            <div class="bld">
              <label>รอบ 1 · ครั้งที่ 1<input type="number" inputmode="decimal" min="0" step="0.1" value="3" data-r1></label>
              <label>รอบ 1 · ครั้งที่ 2<input type="number" inputmode="decimal" min="0" step="0.1" value="4" data-r1></label>
              <label>รอบ 1 · ครั้งที่ 3<input type="number" inputmode="decimal" min="0" step="0.1" value="8" data-r1></label>
              <label>รอบ 2 · ครั้งที่ 1<input type="number" inputmode="decimal" min="0" step="0.1" value="3" data-r2></label>
              <label>รอบ 2 · ครั้งที่ 2<input type="number" inputmode="decimal" min="0" step="0.1" value="3" data-r2></label>
              <label>รอบ 2 · ครั้งที่ 3<input type="number" inputmode="decimal" min="0" step="0.1" value="4" data-r2></label>
              <label>เกณฑ์ (ไม่เกิน กี่วินาที)<input type="number" inputmode="decimal" min="0" step="0.1" value="5" data-lim></label>
            </div>
            <div class="bld-out" aria-live="polite"><b class="sm mute">ผลที่คำนวณ</b><div data-trial-out></div></div>
          </div>

          <div class="quiz" data-quiz="c">
            <h5><span class="pill">ลองตอบ</span> รอบ 2 ผู้ทดลองเป็นคนละคนกับรอบ 1 และผลดีขึ้น ควรเขียนสรุปอย่างไร</h5>
            <div class="opts">
              <button type="button" class="opt" data-k="a"><span class="k">ก</span><span>การแก้ไขของเราทำให้ดีขึ้นแน่นอน</span></button>
              <button type="button" class="opt" data-k="b"><span class="k">ข</span><span>ไม่ต้องเขียนเรื่องผู้ทดลอง เพราะไม่เกี่ยวกัน</span></button>
              <button type="button" class="opt" data-k="c"><span class="k">ค</span><span>ผลดีขึ้น แต่ผู้ทดลองเป็นคนละคน จึงเทียบตรง ๆ ไม่ได้ ต้องทดสอบซ้ำกับผู้ทดลองเดิมและจำนวนครั้งมากขึ้น</span></button>
            </div>
            <div class="fb" hidden><b class="fb-h"></b><p>ความดีขึ้นอาจมาจากผู้ทดลองที่ต่างกัน ไม่ใช่การแก้ไข ข้อ ค จึงเขียนตามหลักฐานที่มี ไม่สรุปเกินจริง</p></div>
          </div>
        </div>

        <!-- 4 -->
        <div class="blk" id="a6-l4">
          <h3><span class="num-dot">4</span>สะท้อนคิดด้วยหลักฐาน ไม่ใช่ความรู้สึก</h3>
          <div class="grid g2">
            <div class="card" style="--c:var(--a6)"><h4>ผลงาน / ต้นแบบ</h4><p class="sm" style="margin:0 0 .4em"><b>จุดแข็ง</b> + หลักฐาน: เตือนที่ตลิ่งได้แม้ไม่มีเน็ต (ทดสอบปิด Wi-Fi) หน้าเว็บอ่านง่ายบนมือถือ</p><p class="sm" style="margin:0"><b>จุดอ่อน</b> + หลักฐาน: ยังไม่ได้ทดสอบในลำห้วยจริงและกลางแจ้ง เกณฑ์ระดับน้ำยังเป็นค่าสมมติ</p></div>
            <div class="card" style="--c:var(--a6)"><h4>กระบวนการสร้างสรรค์ (ใบ 1–5)</h4><p class="sm" style="margin:0 0 .4em"><b>จุดแข็ง</b>: เริ่มจากข่าวจริงและมองผู้ใช้หลายกลุ่ม (ใบ 1–2) ผสานความคิดเพื่อนจนได้ไฟสำหรับผู้ได้ยินไม่ชัด (ใบ 3)</p><p class="sm" style="margin:0"><b>จุดอ่อน</b>: ใบ 5 ทดสอบกับอุปกรณ์จริงน้อย เวลาไม่พอ ไม่ได้ถามผู้สูงอายุหรืออาสาตัวจริง</p></div>
          </div>
          <div class="quiz" data-quiz="c">
            <h5><span class="pill">ลองตอบ</span> ข้อใดคือจุดอ่อนที่เขียนพร้อมหลักฐาน</h5>
            <div class="opts">
              <button type="button" class="opt" data-k="a"><span class="k">ก</span><span>เราทำได้ไม่ค่อยดี</span></button>
              <button type="button" class="opt" data-k="b"><span class="k">ข</span><span>ทีมไม่ค่อยสามัคคี</span></button>
              <button type="button" class="opt" data-k="c"><span class="k">ค</span><span>ใช้เพื่อนห้องเดียวกันเป็นผู้ทดลอง และไม่ได้ถามผู้สูงอายุตัวจริง จึงยังไม่รู้ว่าข้อความเข้าใจง่ายสำหรับคนวัยนั้นหรือไม่</span></button>
            </div>
            <div class="fb" hidden><b class="fb-h"></b><p>ข้อ ค ชี้ว่าทำอะไร (ใช้เพื่อนห้องเดียวกัน) และผลที่ตามมา (ยังไม่รู้ว่าผู้สูงอายุเข้าใจไหม) ซึ่งตรวจสอบและแก้ไขรอบหน้าได้</p></div>
          </div>
        </div>

        <!-- 5 -->
        <div class="blk" id="a6-l5">
          <h3><span class="num-dot">5</span>บอกให้ชัดว่า “ยังไม่ควรนำไปใช้จริง”</h3>
          <div class="grid g2">
            <div class="callout bad"><svg class="ic" aria-hidden="true"><use href="#i-no"/></svg><div><h5>ยังไม่ควรใช้จริง</h5><ul style="margin:.3em 0 0;padding-left:1.2em"><li>ตัวเลขเกณฑ์ระดับน้ำ (ยังเป็นค่าสมมติ)</li><li>การติดตั้งกลางแจ้ง</li><li>ไซเรนจริงในหมู่บ้าน</li><li>การใช้แทนประกาศทางการ</li></ul></div></div>
            <div class="callout safe"><svg class="ic" aria-hidden="true"><use href="#i-shield"/></svg><div><h5>ในเหตุฉุกเฉินให้ฟังคำเตือนจาก</h5><ul style="margin:.3em 0 0;padding-left:1.2em"><li>ปภ. สายด่วน 1784</li><li>เทศบาล / อบต. / ผู้ใหญ่บ้าน</li><li>กรมอุตุนิยมวิทยา</li></ul></div></div>
          </div>
          <p class="sm mute" style="margin:0">ข้อความ “ต้นแบบนี้จากผลทดลอง” ต้องเขียนจากผลทดลองเท่านั้น เช่น ยืนยันได้ว่าเตือนที่ตลิ่งไม่ขึ้นกับเน็ต แต่ยืนยันไม่ได้ว่าผู้สูงอายุอพยพทันจริง เพราะยังไม่ได้ทดสอบกับคนจริงโดยมีผู้ใหญ่ดูแล</p>
        </div>

        <!-- 6 -->
        <div class="blk" id="a6-l6">
          <h3><span class="num-dot">6</span>ตั้งคำถามกับตัวเอง และตั้งเป้าหมายรอบถัดไป</h3>
          <div class="grid g3">
            <div class="card" style="--c:var(--a6)"><h4>ทางที่เลือกง่ายเกินไป</h4><p class="sm" style="margin:0">ขั้นตอนไหนที่เราเลือกทางง่าย เช่น ใช้เพื่อนห้องเดียวกันเป็นผู้ทดลอง ไม่ได้ถามผู้ใช้ตัวจริง</p></div>
            <div class="card" style="--c:var(--a6)"><h4>ควรทำต่างออกไป</h4><p class="sm" style="margin:0">เช่น ขอให้ครูพาไปพบผู้ใหญ่บ้านหรือ อสม. เพื่อถามเกณฑ์น้ำและเส้นทางอพยพจริงก่อนกำหนดระดับ</p></div>
            <div class="card" style="--c:var(--a6)"><h4>เพราะอะไร</h4><p class="sm" style="margin:0">เกณฑ์น้ำและเส้นทางต้องมาจากคนในพื้นที่ ไม่ใช่ที่เรา (หรือ AI) เดา</p></div>
          </div>
          <div class="callout idea"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><h5>กรอบความคิดแบบเติบโต</h5><p>ใบนี้ไม่ได้วัดว่าต้นแบบไม่มีที่ติ แต่ดูว่าเรา <b>ยอมรับข้อผิดพลาดและคำวิจารณ์ แล้วลงมือปรับ</b> เช่น ขอ feedback เพิ่ม ฝึกซ้ำ หรือขอความช่วยเหลือแทนการยอมแพ้ และตั้งเป้าหมายเฉพาะสำหรับรอบถัดไปโดยอ้างอิงผลที่ได้</p></div></div>
        </div>
      </div>
    </div>

    <!-- ---------- A6 : WORKED EXAMPLE ---------- -->
    <div class="panel" role="tabpanel" id="p-a6-ex" aria-labelledby="t-a6-ex" hidden>
      <div class="stack">
        <div class="card soft">
          <span class="tag-sim">ตัวอย่างเพื่อการเรียนรู้</span>
          <h3 style="margin-top:10px">ทีมยามน้ำ ทดลองและปรับปรุง “เพื่อนบ้านเตือนภัย”</h3>
          <p class="mute" style="margin:0">ตัวเลขผลทดลองทุกค่าในหน้านี้เป็น <b>ตัวอย่างสมมติ</b> ตามที่ใบกิจกรรมกำกับไว้ เพื่อสอนวิธีเขียน ไม่ใช่ผลที่วัดจริง นักเรียนต้องบันทึกผลจริงของกลุ่มตนเองและห้ามแต่งข้อมูล</p>
        </div>
        <ul class="toc" aria-label="ส่วนของใบกิจกรรมที่ 6">
          <li><a href="#" data-scroll="a6-s1"><i>1</i>วางแผนทดลอง</a></li>
          <li><a href="#" data-scroll="a6-s2"><i>2</i>ผลรอบ 1</a></li>
          <li><a href="#" data-scroll="a6-s3"><i>3</i>ปรับและทดสอบซ้ำ</a></li>
          <li><a href="#" data-scroll="a6-s4"><i>4</i>สะท้อนคิด</a></li>
        </ul>

        <article class="ex" id="a6-s1">
          <header class="ex-h"><span class="num-dot">1</span><h4>วางแผนการทดลองสถานการณ์จำลอง</h4></header>
          <div class="ex-b">
            <div class="ex-q"><b>ใบกิจกรรมถามว่า</b><p>สถานการณ์จำลองและผู้ทดลอง · สิ่งที่จะวัด · เกณฑ์สำเร็จที่กำหนดก่อนทดสอบ · จะเก็บผลอย่างไร</p></div>
            <div class="ex-a"><span class="lab">คำตอบของทีมยามน้ำ</span>
              <dl class="kv">
                <dt>สถานการณ์จำลอง</dt><dd>น้ำป่ากลางคืนในถังน้ำจำลองลำห้วย ปิด Wi-Fi บางช่วงแทนการไม่มีเน็ต ปิดไฟห้องแทนไฟดับ</dd>
                <dt>ผู้ทดลอง</dt><dd>เพื่อนกลุ่มอื่น 2 คนรับบทอาสา (ไม่รู้ล่วงหน้าว่าน้ำจะถึงระดับใดเมื่อไร) ครูเป็นผู้สังเกต</dd>
                <dt>ความปลอดภัย</dt><dd>ใช้ไฟ 5 V บนโต๊ะ ไม่ทดลองในลำห้วยจริง</dd>
              </dl>
              <div class="tbl" style="margin-top:14px"><table>
                <thead><tr><th>สิ่งที่จะวัด / สังเกต</th><th>เกณฑ์สำเร็จ (ตั้งก่อนทดสอบ)</th><th>จะเก็บผลอย่างไร</th></tr></thead>
                <tbody>
                  <tr><td><b>1.</b> เวลาจากน้ำถึงระดับแดง จนเสียงเตือนที่ตลิ่งดัง</td><td>ไม่เกิน 5 วินาที (กลุ่มกำหนดเอง)</td><td>จับเวลา 3 ครั้ง แล้วหาค่าเฉลี่ย</td></tr>
                  <tr><td><b>2.</b> อาสารู้ว่าต้องทำอะไรเมื่อได้รับข้อความ</td><td>ผู้ทดลอง 2 ใน 2 คน บอกขั้นตอนถูกภายใน 30 วินาที</td><td>ถามผู้ทดลองแล้วจดผลลงตาราง</td></tr>
                </tbody>
              </table></div>
            </div>
            <div class="why"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><p><b>ทำไมดี:</b> เกณฑ์เป็นตัวเลขที่ตรวจได้ มีทั้งด้านเทคนิค (เวลาเตือน) และด้านผู้ใช้ (เข้าใจข้อความ) และผู้ทดลองไม่รู้ล่วงหน้าว่าน้ำจะถึงระดับใดเมื่อไร จึงใกล้เคียงสถานการณ์จริงมากขึ้น</p></div></div>
          </div>
        </article>

        <article class="ex" id="a6-s2">
          <header class="ex-h"><span class="num-dot">2</span><h4>ผลทดลองรอบที่ 1 ก่อนปรับปรุง</h4></header>
          <div class="ex-b">
            <div class="ex-q"><b>ใบกิจกรรมถามว่า</b><p>ผลที่เกิดจริง (ไม่แต่งข้อมูล) · ปัญหาหรือข้อจำกัด · ข้อเสนอแนะจากเพื่อน/ครู/ผู้ทดลอง 1–2 ข้อ</p></div>
            <div class="ex-a"><span class="lab">คำตอบของทีมยามน้ำ (ตัวเลขสมมติ)</span>
              <div class="tbl"><table>
                <thead><tr><th>เกณฑ์ทดสอบ</th><th>ผลที่เกิดจริง</th><th>ปัญหาหรือข้อจำกัด</th></tr></thead>
                <tbody>
                  <tr><td><b>1.</b> เวลาถึงเสียงเตือนที่ตลิ่ง ไม่เกิน 5 วินาที</td><td>(สมมติ) 3, 4 และ 8 วินาที</td><td>ครั้งที่ 3 ช้า เพราะค่าระยะแกว่ง ต้องรอยืนยัน</td></tr>
                  <tr><td><b>2.</b> ผู้ทดลองบอกขั้นตอนถูกใน 30 วินาที</td><td>(สมมติ) 1 ใน 2 คน อีกคนไม่รู้ว่าต้องไปบ้านไหนก่อน</td><td>ข้อความไม่มีลำดับบ้านที่ต้องไปก่อน</td></tr>
                </tbody>
              </table></div>
              <div class="card flat" style="margin-top:14px"><b>ข้อเสนอแนะ (ใครเสนอ)</b>
                <ul style="margin:.4em 0 0">
                  <li><b>ผู้ทดลอง ก:</b> อยากให้ข้อความขึ้นต้นด้วยคำสั่งสั้น ๆ เช่น “ไปบ้านผู้สูงอายุก่อน”</li>
                  <li><b>ครู:</b> ไซเรนควรดังเป็นช่วง ๆ ไม่ดังต่อเนื่องตลอด เพื่อไม่ให้คนเมินและไม่รบกวนเกินไป</li>
                </ul>
                <p class="sm mute" style="margin:.5em 0 0">(ตัวอย่างสมมติ — นักเรียนเขียนข้อเสนอแนะที่ได้จริง)</p>
              </div>
            </div>
            <div class="why"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><p><b>ทำไมดี:</b> เขียนผลที่ไม่ผ่านเกณฑ์ตรง ๆ (8 วินาทีเกิน 5 วินาที, ผ่าน 1 ใน 2 คน) พร้อม <b>สาเหตุที่คาด</b> ข้อเสนอแนะบอกชื่อผู้เสนอ ซึ่งเป็นตัวอย่างของการยอมรับผลโดยไม่ปกป้องตัวเอง</p></div></div>
          </div>
        </article>

        <article class="ex" id="a6-s3">
          <header class="ex-h"><span class="num-dot">3</span><h4>ปรับปรุงตามหลักฐานและทดสอบซ้ำ</h4></header>
          <div class="ex-b">
            <div class="ex-q"><b>ใบกิจกรรมถามว่า</b><p>เกณฑ์เดิม · ผลรอบ 1 · สิ่งที่แก้จริงพร้อมเหตุผล · ผลรอบ 2 · ดีขึ้นหรือยังไม่ดีเพราะอะไร · เงื่อนไขที่ไม่เหมือนกันระหว่างสองรอบ</p></div>
            <div class="ex-a"><span class="lab">คำตอบของทีมยามน้ำ (ตัวเลขสมมติ)</span>
              <div class="tbl"><table>
                <thead><tr><th>เกณฑ์เดิม</th><th>ผลรอบ 1</th><th>สิ่งที่แก้ + เหตุผล</th><th>ผลรอบ 2</th><th>ดีขึ้น / ยังไม่ดี</th></tr></thead>
                <tbody>
                  <tr><td><b>1.</b> เวลาถึงเสียงเตือน ไม่เกิน 5 วินาที</td><td>(สมมติ) 3, 4, 8 วินาที</td><td>ใช้ค่ากลาง 5 ครั้ง + ท่อกันคลื่น · เหตุผล: ลดค่ากระโดด</td><td>(สมมติ) 3, 3, 4 วินาที</td><td>ดีขึ้น: ครั้งที่ช้าหายไป แต่ยังต้องทดสอบซ้ำหลายครั้งเพราะมีเพียง 3 ครั้ง</td></tr>
                  <tr><td><b>2.</b> ผู้ทดลองบอกขั้นตอนถูกใน 30 วินาที</td><td>(สมมติ) 1 ใน 2 คน</td><td>ปรับข้อความให้ขึ้นต้นด้วยสิ่งที่ต้องทำ · เหตุผล: อาสาตัดสินใจเร็วขึ้น</td><td>(สมมติ) 2 ใน 2 คน</td><td>ดีขึ้น แต่ผู้ทดลองเป็นคนละคน จึงเทียบตรง ๆ ไม่ได้</td></tr>
                </tbody>
              </table></div>

              <figure class="card flat" style="margin:14px 0 0">
                <svg class="chart" viewBox="0 0 640 310" role="img" aria-labelledby="a6chT a6chD">
                  <title id="a6chT">เวลาถึงเสียงเตือนที่ตลิ่ง เทียบรอบ 1 กับรอบ 2 (ตัวเลขสมมติ)</title>
                  <desc id="a6chD">รอบ 1 ได้ 3, 4 และ 8 วินาที รอบ 2 ได้ 3, 3 และ 4 วินาที เส้นประแสดงเกณฑ์ไม่เกิน 5 วินาที มีเพียงรอบ 1 ครั้งที่ 3 ที่เกินเกณฑ์</desc>
                  <!-- legend -->
                  <rect class="cv-r1" x="56" y="8" width="16" height="16" rx="3"/><text class="cv-s" x="80" y="21">รอบ 1 (ก่อนปรับ)</text>
                  <rect class="cv-r2" x="236" y="8" width="16" height="16" rx="3"/><text class="cv-s" x="260" y="21">รอบ 2 (หลังปรับ)</text>
                  <!-- grid -->
                  <path class="cv-grid" d="M56 240 H620 M56 135 H620 M56 30 H620"/>
                  <text class="cv-s" x="48" y="244" text-anchor="end">0</text>
                  <text class="cv-s" x="48" y="139" text-anchor="end">5</text>
                  <text class="cv-s" x="48" y="34" text-anchor="end">10</text>
                  <text class="cv-s" x="14" y="150" transform="rotate(-90 14 150)" text-anchor="middle">วินาที</text>
                  <path class="cv-ax" d="M56 240 H620"/>
                  <!-- group 1 -->
                  <g>
                    <rect class="cv-r1" x="100" y="177" width="44" height="63" rx="4"><title>ครั้งที่ 1 รอบ 1: 3 วินาที</title></rect>
                    <rect class="cv-r2" x="152" y="177" width="44" height="63" rx="4"><title>ครั้งที่ 1 รอบ 2: 3 วินาที</title></rect>
                    <text class="cv-t" x="122" y="170" text-anchor="middle">3</text><text class="cv-t" x="174" y="170" text-anchor="middle">3</text>
                    <text class="cv-s" x="148" y="264" text-anchor="middle">ครั้งที่ 1</text>
                  </g>
                  <!-- group 2 -->
                  <g>
                    <rect class="cv-r1" x="288" y="156" width="44" height="84" rx="4"><title>ครั้งที่ 2 รอบ 1: 4 วินาที</title></rect>
                    <rect class="cv-r2" x="340" y="177" width="44" height="63" rx="4"><title>ครั้งที่ 2 รอบ 2: 3 วินาที</title></rect>
                    <text class="cv-t" x="310" y="149" text-anchor="middle">4</text><text class="cv-t" x="362" y="170" text-anchor="middle">3</text>
                    <text class="cv-s" x="336" y="264" text-anchor="middle">ครั้งที่ 2</text>
                  </g>
                  <!-- group 3 -->
                  <g>
                    <rect class="cv-r1" x="476" y="72" width="44" height="168" rx="4"><title>ครั้งที่ 3 รอบ 1: 8 วินาที เกินเกณฑ์</title></rect>
                    <rect class="cv-r2" x="528" y="156" width="44" height="84" rx="4"><title>ครั้งที่ 3 รอบ 2: 4 วินาที</title></rect>
                    <text class="cv-t" x="498" y="65" text-anchor="middle">8</text><text class="cv-t" x="550" y="149" text-anchor="middle">4</text>
                    <text class="cv-s" x="524" y="264" text-anchor="middle">ครั้งที่ 3</text>
                  </g>
                  <!-- limit -->
                  <path class="cv-lim" d="M56 135 H620"/>
                  <text class="cv-lim-t" x="62" y="126">เกณฑ์ ไม่เกิน 5 วินาที</text>
                  <text class="cv-s" x="336" y="292" text-anchor="middle">ตัวอย่างสมมติ · แต่ละรอบวัดเพียง 3 ครั้ง</text>
                </svg>
                <figcaption class="sm mute" style="margin-top:6px">ค่าเฉลี่ยรอบ 1 ≈ 5.0 วินาที และรอบ 2 ≈ 3.3 วินาที (ตัวอย่างสมมติ) แต่ 3 ครั้งยังน้อยเกินกว่าจะสรุปเด็ดขาด</figcaption>
                <div class="tbl tight" style="margin-top:8px"><table>
                  <caption class="sr">ตารางข้อมูลของกราฟ</caption>
                  <thead><tr><th>ครั้งที่</th><th>รอบ 1 (วินาที)</th><th>รอบ 2 (วินาที)</th><th>ผ่านเกณฑ์ ≤ 5</th></tr></thead>
                  <tbody>
                    <tr><td>1</td><td>3</td><td>3</td><td>ผ่านทั้งสองรอบ</td></tr>
                    <tr><td>2</td><td>4</td><td>3</td><td>ผ่านทั้งสองรอบ</td></tr>
                    <tr><td>3</td><td>8</td><td>4</td><td>รอบ 1 ไม่ผ่าน · รอบ 2 ผ่าน</td></tr>
                  </tbody>
                </table></div>
              </figure>

              <div class="card flat" style="margin-top:14px"><b>เงื่อนไขที่ไม่เหมือนเดิมระหว่างสองรอบ</b>
                <dl class="kv" style="margin-top:8px">
                  <dt>ไม่เหมือนเดิม</dt><dd>ผู้ทดลองรอบ 2 เป็นคนละคน และระดับน้ำที่เติมไม่เท่ากันทุกครั้ง</dd>
                  <dt>ผลกระทบ</dt><dd>ข้อสรุปว่า “ดีขึ้น” อาจมาจากผู้ทดลอง ไม่ใช่การแก้ไข ต้องทดสอบซ้ำกับผู้ทดลองเดิมและจำนวนครั้งที่มากขึ้น</dd>
                </dl>
              </div>
            </div>
            <div class="why"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><p><b>ทำไมดี:</b> เกณฑ์เดิมไม่ถูกเปลี่ยนให้ผ่านง่ายขึ้น ผลสองรอบวางเคียงกันให้เทียบได้ ทุกการแก้มีเหตุผล และบอกข้อจำกัดของการสรุป (3 ครั้ง ผู้ทดลองคนละคน) ตรงตามเกณฑ์ที่ครูดู</p></div></div>
          </div>
        </article>

        <article class="ex" id="a6-s4">
          <header class="ex-h"><span class="num-dot">4</span><h4>สะท้อนคิดผลงานและกระบวนการของกลุ่ม</h4></header>
          <div class="ex-b">
            <div class="ex-q"><b>ใบกิจกรรมถามว่า</b><p>จุดแข็งและจุดอ่อนพร้อมหลักฐาน · ต้นแบบช่วยกลุ่มเป้าหมายได้อย่างไร (จากผลทดลองเท่านั้น) · สิ่งที่ยังไม่ควรนำไปใช้จริง · ตั้งคำถามกับกระบวนการของเรา</p></div>
            <div class="ex-a"><span class="lab">คำตอบของทีมยามน้ำ</span>
              <div class="tbl"><table>
                <thead><tr><th>สิ่งที่สะท้อน</th><th>จุดแข็ง (พร้อมหลักฐาน)</th><th>จุดอ่อน (พร้อมหลักฐาน)</th></tr></thead>
                <tbody>
                  <tr><td><b>ผลงาน / ต้นแบบ</b></td><td>เตือนที่ตลิ่งได้แม้ไม่มีเน็ต (หลักฐาน: ทดสอบปิด Wi-Fi) · หน้าเว็บอ่านง่ายบนมือถือ</td><td>ยังไม่ได้ทดสอบในลำห้วยจริงและกลางแจ้ง · เกณฑ์ระดับน้ำยังเป็นค่าสมมติ</td></tr>
                  <tr><td><b>กระบวนการสร้างสรรค์ของกลุ่ม (ใบ 1–5)</b></td><td>เริ่มจากข่าวจริงและมองผู้ใช้หลายกลุ่ม (ใบ 1–2) · ผสานความคิดเพื่อนจนได้ไฟสำหรับผู้ได้ยินไม่ชัด (ใบ 3)</td><td>ใบ 5 ทดสอบกับอุปกรณ์จริงน้อย เวลาไม่พอ · ไม่ได้ถามผู้สูงอายุหรืออาสาตัวจริง</td></tr>
                </tbody>
              </table></div>
              <div class="card flat" style="margin-top:14px"><b>ต้นแบบช่วยลดความเสี่ยงได้อย่างไร (จากผลทดลองเท่านั้น)</b>
                <p style="margin:.4em 0 0">(สมมติ) ต้นแบบทำให้ผู้ทดลองรู้ระดับน้ำและรู้ว่าต้องทำอะไรเร็วขึ้นในถังจำลอง แต่ยังสรุปไม่ได้ว่าลดความเสี่ยงในลำห้วยจริง</p>
                <p style="margin:.4em 0 0"><b>ยืนยันได้จากผล:</b> การเตือนที่ตลิ่งไม่ขึ้นกับเน็ต · <b>ยังยืนยันไม่ได้:</b> ว่าผู้สูงอายุอพยพทันจริง ต้องทดสอบกับคนจริงโดยมีผู้ใหญ่ดูแล</p>
              </div>
              <div class="card flat" style="margin-top:12px"><b>สิ่งที่ยังไม่ควรนำไปใช้จริง</b>
                <p style="margin:.4em 0 0">ตัวเลขเกณฑ์ระดับน้ำ · การติดตั้งกลางแจ้ง · ไซเรนจริงในหมู่บ้าน · การใช้แทนประกาศทางการ</p>
                <p style="margin:.4em 0 0"><b>ในเหตุฉุกเฉินให้ฟังคำเตือนจาก:</b> ปภ. (สายด่วน 1784) เทศบาล/อบต. ผู้ใหญ่บ้าน และกรมอุตุนิยมวิทยา</p>
              </div>
              <div class="card flat" style="margin-top:12px"><b>ตั้งคำถามกับกระบวนการสร้างสรรค์ของเรา</b>
                <dl class="kv" style="margin-top:8px">
                  <dt>ที่เลือกทางง่าย</dt><dd>ใช้เพื่อนห้องเดียวกันเป็นผู้ทดลอง และไม่ได้ถามผู้สูงอายุตัวจริง</dd>
                  <dt>ควรทำต่าง</dt><dd>ขอให้ครูพาไปพบผู้ใหญ่บ้าน/อสม. ถามเกณฑ์น้ำและเส้นทางอพยพจริง ก่อนกำหนดระดับ</dd>
                  <dt>เพราะ</dt><dd>เกณฑ์น้ำและเส้นทางต้องมาจากคนในพื้นที่ ไม่ใช่ที่เรา (หรือ AI) เดา</dd>
                </dl>
              </div>
            </div>
            <div class="why"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><p><b>ทำไมดี:</b> จุดแข็งทุกข้อมีหลักฐานรองรับ (เช่น ทดสอบปิด Wi-Fi) จุดอ่อนไม่ถูกซ่อน ส่วน “ยืนยันได้ / ยืนยันไม่ได้” แยกให้เห็นว่าอ้างได้แค่ไหน และการตั้งคำถามกับตัวเองจบด้วยการกระทำที่ทำได้จริง (พบผู้ใหญ่บ้าน) ซึ่งเป็นลักษณะของคนที่พัฒนาตนเองอย่างต่อเนื่อง</p></div></div>
          </div>
        </article>

        <div class="callout safe"><svg class="ic" aria-hidden="true"><use href="#i-check"/></svg><div><p><b>จบทั้ง 6 ใบกิจกรรม</b> ย้อนดูภาพรวมของหน่วยการเรียนได้ที่หน้าแรก หรือเปิดคลังสื่อเพื่อดูแหล่งอ้างอิงข่าวและข้อควรระวังของตัวอย่างทั้งหมด</p><p style="margin:.6em 0 0"><button type="button" class="btn sm" data-go="library">เปิดคลังสื่อ <svg class="ic" aria-hidden="true"><use href="#i-arrow-r"/></svg></button></p></div></div>
      </div>
    </div>

    <!-- ---------- A6 : HAZARDS ---------- -->
    <div class="panel" role="tabpanel" id="p-a6-hz" aria-labelledby="t-a6-hz" hidden>
      <div class="stack">
        <div class="callout note"><svg class="ic" aria-hidden="true"><use href="#i-info"/></svg><div><p>เลือกภัยเพื่อดูวิธีทดสอบจำลองอย่างปลอดภัยของภัยนั้น พร้อมตัวอย่างคำตอบเต็มทุกหัวข้อของใบกิจกรรมที่ 6 ผลทุกอย่างในใบของคุณต้องเป็นผลจริงของกลุ่ม และต้องเขียนว่า “ผลทดสอบนี้มาจากแบบจำลอง/โหมดจำลอง ยังไม่ทดสอบกับเหตุการณ์จริง”</p></div></div>
        <div class="hz" data-hz-for="a6"></div>
      </div>
    </div>

    <!-- ---------- A6 : RUBRIC ---------- -->
    <div class="panel" role="tabpanel" id="p-a6-rub" aria-labelledby="t-a6-rub" hidden>
      <div class="stack">
        <div class="card soft">
          <h3>ครูดูอะไร</h3>
          <p style="margin:0">ใบนี้ประเมินเพียง <b>องค์ประกอบที่ 6 การกำกับตนเองและการสะท้อนคิด</b> จาก 3 ประเด็น ระดับรวมครูตัดสินจากภาพรวมของหลักฐานรายบุคคลและผลงานกลุ่ม</p>
        </div>

        <div>
          <div class="lad-h"><h4>6.1 การสะท้อนคิด</h4><span class="pill">หลักฐาน: ส่วนที่ 2–4 · หลักฐานรายบุคคล</span></div>
          <div class="ladder">
            <div class="rung"><small>1.0 ขั้นเริ่มต้น</small>ระบุจุดแข็งและจุดอ่อนของตนในผลงานหรือกระบวนการได้</div>
            <div class="rung"><small>2.0 ขั้นพื้นฐาน</small>ประเมินผลการปฏิบัติและกระบวนการสร้างสรรค์โดยใช้ feedback และ/หรือเกณฑ์ที่กำหนด</div>
            <div class="rung"><small>3.0 ขั้นชำนาญ</small>สะท้อนคุณภาพงานได้อย่างถูกต้อง ใช้การสะท้อนคิดและ/หรือ feedback ในการปรับปรุงความคิดหรือผลงาน และตั้งคำถามหรือวิพากษ์กระบวนการสร้างสรรค์ของตนเอง</div>
            <div class="rung"><small>4.0 ขั้นสูง</small>วิเคราะห์รูปแบบและแนวโน้มที่เกิดขึ้นในกระบวนการสร้างสรรค์และผลงานของตน ประเมินการคิดสร้างสรรค์ตลอดกระบวนการ และแสวงหา/นำ feedback จากเพื่อน ครู และผู้เชี่ยวชาญมาใช้เพื่อพัฒนางาน</div>
          </div>
        </div>
        <div>
          <div class="lad-h"><h4>6.2 การวางแผน</h4><span class="pill">หลักฐาน: หลักฐานรายบุคคล</span></div>
          <div class="ladder">
            <div class="rung"><small>1.0 ขั้นเริ่มต้น</small>ตั้งเป้าหมายส่วนบุคคลในการทำงาน</div>
            <div class="rung"><small>2.0 ขั้นพื้นฐาน</small>ตั้งเป้าหมายการปฏิบัติโดยอาศัย feedback หรือเกณฑ์ที่กำหนด</div>
            <div class="rung"><small>3.0 ขั้นชำนาญ</small>แสวงหา เลือก และใช้ทรัพยากรหรือกลยุทธ์เพื่อบรรลุเป้าหมายในการพัฒนากระบวนการสร้างสรรค์</div>
            <div class="rung"><small>4.0 ขั้นสูง</small>วิเคราะห์รูปแบบและผลการปฏิบัติที่ผ่านมาเพื่อกำหนดเป้าหมายใหม่ด้านการคิดสร้างสรรค์ และปรับเป้าหมายตามผลการสะท้อนอย่างต่อเนื่อง</div>
          </div>
        </div>
        <div>
          <div class="lad-h"><h4>6.3 กรอบความคิด</h4><span class="pill">หลักฐาน: หลักฐานรายบุคคล</span></div>
          <div class="ladder">
            <div class="rung"><small>1.0 ขั้นเริ่มต้น</small>อธิบายความสัมพันธ์ระหว่างความพยายามกับความสำเร็จได้</div>
            <div class="rung"><small>2.0 ขั้นพื้นฐาน</small>แสดงความต้องการที่จะพัฒนาตน เช่น ฝึกฝนมากขึ้น ตั้งเป้าหมายพัฒนา หรือขอความช่วยเหลือแทนการยอมแพ้</div>
            <div class="rung"><small>3.0 ขั้นชำนาญ</small>แสดง Growth Mindset เมื่อเผชิญอุปสรรค เช่น พยายามทำภาระงานที่ยาก กล้าเสี่ยง ยอมรับและใช้คำวิจารณ์ ยอมรับความผิดพลาด และมองความล้มเหลวในเชิงการพัฒนา</div>
            <div class="rung"><small>4.0 ขั้นสูง</small>ดำเนินการเชิงรุกเพื่อปรับปรุงจุดอ่อนของตน โดยใช้กลยุทธ์ที่มีประสิทธิผล เช่น ความพากเพียร การกล้าเสี่ยง การตัดสินใจอย่างมีประสิทธิภาพ การแสวงหา feedback การฝึกฝนอย่างตั้งใจ และการใช้แหล่งทรัพยากรหรือผู้เชี่ยวชาญภายนอก</div>
          </div>
        </div>

        <div class="card">
          <h4>เช็กลิสต์ก่อนส่งใบกิจกรรมที่ 6</h4>
          <p class="sm mute">ติ๊กได้เลย เครื่องนี้จะจำไว้ให้ในเบราว์เซอร์ของคุณ ครูไม่เห็นเช็กลิสต์นี้</p>
          <ul class="checks" data-checks="a6">
            <li><label><input type="checkbox"><span>ระบุสถานการณ์จำลอง ผู้ทดลอง และความปลอดภัย (ไม่ทดลองในภัยจริง)</span></label></li>
            <li><label><input type="checkbox"><span>ตั้งเกณฑ์สำเร็จที่วัดได้ <b>ก่อน</b> ทดสอบ พร้อมวิธีเก็บผล</span></label></li>
            <li><label><input type="checkbox"><span>บันทึกผลรอบที่ 1 ตามจริง ไม่แต่งข้อมูล และระบุปัญหาหรือข้อจำกัด</span></label></li>
            <li><label><input type="checkbox"><span>มีข้อเสนอแนะอย่างน้อย 1–2 ข้อ ระบุว่าใครเสนอเรื่องใด</span></label></li>
            <li><label><input type="checkbox"><span>แก้ไขตามหลักฐาน บอกเหตุผลของแต่ละการแก้ และทดสอบซ้ำในเงื่อนไขที่เทียบเคียงได้</span></label></li>
            <li><label><input type="checkbox"><span>ตรวจว่าเงื่อนไขสองรอบเหมือนกันหรือไม่ และเขียนว่าอาจคลาดเคลื่อนอย่างไร</span></label></li>
            <li><label><input type="checkbox"><span>สะท้อนจุดแข็ง/จุดอ่อนของผลงานและกระบวนการ (ใบ 1–5) พร้อมหลักฐาน</span></label></li>
            <li><label><input type="checkbox"><span>เขียนสิ่งที่ยังไม่ควรใช้จริง และหน่วยงานที่ควรอ้างอิงในเหตุฉุกเฉิน</span></label></li>
            <li><label><input type="checkbox"><span>ตั้งคำถามกับวิธีทำงานของตน (ทางง่ายที่เลือก) และเขียนเป้าหมายส่วนตัวสำหรับรอบถัดไป</span></label></li>
          </ul>
          <div class="meter" style="margin-top:14px" aria-hidden="true"><i data-meter="a6"></i></div>
          <p class="sm mute" style="margin:.5em 0 0" data-meter-text="a6">ติ๊กแล้ว 0 จาก 9 ข้อ</p>
        </div>
      </div>
    </div>

    <div class="pn">
      <a class="btn" href="#a5" data-go="a5"><svg class="ic" aria-hidden="true"><use href="#i-arrow-l"/></svg> ใบกิจกรรมที่ 5</a>
      <a class="btn pri" href="#library" data-go="library">คลังสื่อและแหล่งอ้างอิง <svg class="ic" aria-hidden="true"><use href="#i-arrow-r"/></svg></a>
    </div>
  </div>
</section>
<!-- ====================== LIBRARY ====================== -->
<section class="view" id="v-library" data-view="library" hidden>
  <div class="ah" style="--c:var(--ink);--on:var(--surface)">
    <div class="wrap ah-in">
      <div class="ah-num" aria-hidden="true"><svg class="ic" style="width:1em;height:1em"><use href="#i-book"/></svg></div>
      <div>
        <p class="stage">คลังเนื้อหาและสื่อ</p>
        <h1>คลังสื่อ<wbr>และแหล่งอ้างอิง</h1>
        <p class="mission-line">รวมภาพรวมใบกิจกรรม ภาพรวม 5 ภัย คำศัพท์เทคโนโลยี และแหล่งข่าวที่ใช้ในตัวอย่าง</p>
      </div>
    </div>
  </div>

  <div class="wrap">
    <div class="stack" style="padding-block:28px 12px">

      <ul class="toc" aria-label="หัวข้อในคลังสื่อ">
        <li><a href="#" data-scroll="lib-sheets"><i>1</i>ใบกิจกรรม 6 ใบ</a></li>
        <li><a href="#" data-scroll="lib-cases"><i>2</i>ตัวอย่างสองชุด</a></li>
        <li><a href="#" data-scroll="lib-hazards"><i>3</i>5 ภัย</a></li>
        <li><a href="#" data-scroll="lib-tech"><i>4</i>คำศัพท์</a></li>
        <li><a href="#" data-scroll="lib-levels"><i>5</i>ระดับ 0–3</a></li>
        <li><a href="#" data-scroll="lib-src"><i>6</i>แหล่งข่าว</a></li>
        <li><a href="#" data-scroll="lib-help"><i>7</i>เบอร์สำคัญ</a></li>
      </ul>

      <!-- 1 sheets -->
      <div class="blk" id="lib-sheets">
        <h3><span class="num-dot" style="--c:var(--a3);--on:var(--a3-on)">1</span>ใบกิจกรรม 6 ใบ รวม 15 ชั่วโมง</h3>
        <p>แต่ละใบเก็บหลักฐานและประเมินเพียง 1 องค์ประกอบของแบบวัดความคิดสร้างสรรค์และนวัตกรรม เมื่อจบใบ ครูให้ระดับ 1.0–4.0 ตามเกณฑ์ท้ายใบ ครบทั้ง 6 องค์ประกอบเมื่อจบ 6 ใบ</p>
        <div class="tbl"><table>
          <thead><tr><th>ใบกิจกรรม</th><th>เวลา</th><th>องค์ประกอบที่ประเมิน</th><th>ประเด็นย่อย</th><th>ใบกิจกรรม (Google Slides)</th><th>ไปที่</th></tr></thead>
          <tbody>
            <tr><td><b>1</b> รู้ทันภัย มองปัญหาให้รอบด้าน</td><td>2 ชม.</td><td>3. การเปิดรับและกล้าสำรวจสิ่งใหม่</td><td>ความอยากรู้อยากเห็น · การท้าทายกรอบเดิม</td><td><a class="inline-link" href="https://docs.google.com/presentation/d/1vhciPrapLk9oh_oYDUTMStihTT1Y-jvbPfN-xQLTPPk/edit?usp=sharing" target="_blank" rel="noopener">เปิดใบกิจกรรม</a></td><td><a class="inline-link" href="#a1" data-go="a1">เปิด</a></td></tr>
            <tr><td><b>2</b> นักสืบปัญหา ภัยธรรมชาติ</td><td>2 ชม.</td><td>1. การสร้างความคิด</td><td>การกำหนดปัญหา · การสร้างความคิด · การสืบค้นเชิงสร้างสรรค์</td><td><a class="inline-link" href="https://docs.google.com/presentation/d/1YeYSp4px4QHdu0ttfVBTDI7DWZmeLslWcc_OnfwDT8k/edit?usp=sharing" target="_blank" rel="noopener">เปิดใบกิจกรรม</a></td><td><a class="inline-link" href="#a2" data-go="a2">เปิด</a></td></tr>
            <tr><td><b>3</b> คิดเอง คิดต่อกับ AI</td><td>2 ชม.</td><td>4. การทำงานสร้างสรรค์ร่วมกับผู้อื่น</td><td>เปรียบเทียบ · ผสมผสาน · ต่อยอด · สังเคราะห์</td><td><a class="inline-link" href="https://docs.google.com/presentation/d/1nGmlRU-OQAzPuQfKEztlUfbBJiyiDQsMnWyHxpwdaSo/edit?usp=sharing" target="_blank" rel="noopener">เปิดใบกิจกรรม</a></td><td><a class="inline-link" href="#a3" data-go="a3">เปิด</a></td></tr>
            <tr><td><b>4</b> แนวคิดสู่แบบร่าง</td><td>2 ชม.</td><td>2. การออกแบบและปรับปรุงความคิด</td><td>การขยายความคิด · การทำซ้ำและปรับปรุง</td><td><a class="inline-link" href="https://docs.google.com/presentation/d/1_kx4cvHE5S5yw-BHe1bPOHeqcBseit2YTYCW5HB4hK0/edit?usp=sharing" target="_blank" rel="noopener">เปิดใบกิจกรรม</a></td><td><a class="inline-link" href="#a4" data-go="a4">เปิด</a></td></tr>
            <tr><td><b>5</b> ลงมือสร้างนวัตกรรม</td><td>5 ชม.</td><td>5. การสร้างสรรค์ผลงานและนวัตกรรม</td><td>กลุ่มเป้าหมาย · การใช้ทรัพยากร · การวางแผน · การผลิต</td><td><a class="inline-link" href="https://docs.google.com/presentation/d/1oWbI54viUfUxMA3K5ywsokKSPJIjBtIIfMMG8mxP33Q/edit?usp=sharing" target="_blank" rel="noopener">เปิดใบกิจกรรม</a></td><td><a class="inline-link" href="#a5" data-go="a5">เปิด</a></td></tr>
            <tr><td><b>6</b> ทดลองปรับปรุง</td><td>2 ชม.</td><td>6. การกำกับตนเองและการสะท้อนคิด</td><td>การสะท้อนคิด · การวางแผน · กรอบความคิด</td><td><a class="inline-link" href="https://docs.google.com/presentation/d/1aDtDVsUYh00QO1QMOxUxrfpQNuwiddnR0rajAUyevjU/edit?usp=sharing" target="_blank" rel="noopener">เปิดใบกิจกรรม</a></td><td><a class="inline-link" href="#a6" data-go="a6">เปิด</a></td></tr>
          </tbody>
        </table></div>
      </div>

      <!-- 2 cases -->
      <div class="blk" id="lib-cases">
        <h3><span class="num-dot" style="--c:var(--a4);--on:var(--a4-on)">2</span>ตัวอย่างสองชุดในเว็บนี้ ต่างกันอย่างไร</h3>
        <div class="grid g2">
          <div class="card" style="--c:var(--a1)">
            <h4>ชุดที่ 1 · เหตุการณ์ A/B</h4>
            <p class="sm" style="margin:0 0 .5em">ใช้ในแท็บ “เรียนรู้” ของใบที่ 1–3 เป็นเหตุการณ์ที่เกิดจริงที่ อ.ท่าปลา</p>
            <ul class="sm" style="margin:0;padding-left:1.2em">
              <li><b>A:</b> น้ำป่าคลองสิงห์ อ.ท่าปลา 22 ส.ค. 2563</li>
              <li><b>B:</b> ฝนหนัก ดินสไลด์ พายุ 1–3 ต.ค. 2567</li>
            </ul>
          </div>
          <div class="card" style="--c:var(--a3)">
            <h4>ชุดที่ 2 · ทีมยามน้ำ (ตัวอย่างเฉลย)</h4>
            <p class="sm" style="margin:0 0 .5em">ใช้ในแท็บ “ตัวอย่างละเอียด” ของทุกใบ เป็นทีมสมมติ 4 คน (ก ข ค ง) ที่เลือกภัยน้ำท่วม/น้ำป่า และสร้างต้นแบบ “เพื่อนบ้านเตือนภัย”</p>
            <p class="sm mute" style="margin:0"><span class="tag-sim">ตัวอย่างเพื่อการเรียนรู้</span> ชื่อทีม โจทย์ ตัวเลขเกณฑ์ ผลทดสอบ เป็นข้อมูลสมมติ</p>
          </div>
        </div>
        <div class="callout warn"><svg class="ic" aria-hidden="true"><use href="#i-warn"/></svg><div><h5>ใช้เป็นแนวทาง ไม่ใช่เฉลยให้คัดลอก</h5><p>ใบกิจกรรมประเมินจากหลักฐานที่ <b>กลุ่มของคุณทำจริง</b> คำตอบของทีมยามน้ำมีไว้ให้ดูว่าแต่ละช่องควรละเอียดและมีเหตุผลแค่ไหน การเลือกภัยอื่นให้ดูแท็บ “อีก 4 ภัย” ในแต่ละใบ</p></div></div>
      </div>

      <!-- 3 hazards -->
      <div class="blk" id="lib-hazards">
        <h3><span class="num-dot" style="--c:var(--a5);--on:var(--a5-on)">3</span>5 ภัย 5 ชิ้นงาน</h3>
        <p>ภัยน้ำท่วมคือชุดตัวอย่างหลัก (ทีมยามน้ำ) อีก 4 ภัยมีตัวอย่างคำตอบเต็มทุกใบกิจกรรมในแท็บ “ตัวอย่าง 4 ภัยอื่น” และใช้แพลตฟอร์ม “เพื่อนบ้านเตือนภัย” ชุดเดียวกัน โดยสลับชุดค่าของภัย ไม่ต้องแก้โค้ดส่วนอื่น</p>
        <div class="tbl"><table>
          <thead><tr><th>ภัย</th><th>เหตุการณ์จริงที่ใช้เป็นโจทย์</th><th>ชิ้นงานที่สร้าง</th><th>ทำได้โดยไม่ใช้บอร์ด?</th><th>ความยาก</th></tr></thead>
          <tbody>
            <tr><td><b>น้ำท่วม / น้ำป่า</b></td><td>ข่าวฟากท่า ลับแล น้ำปาด (ดูใบที่ 1)</td><td>“เพื่อนบ้านเตือนภัย” สถานีวัดน้ำ + แจ้งเตือน + ไซเรนและไฟ</td><td>ได้ ใช้โหมดจำลองในโค้ดและหน้าเว็บ</td><td>ตัวอย่างหลัก</td></tr>
            <tr><td><b>ภัยแล้ง</b></td><td>ประปาหมู่บ้านไม่ไหลเกิน 2 เดือน (ต.น้ำอ่าง อ.ตรอน) · ไร่มันสำปะหลังนับพันไร่แห้งตาย (ต.นาอิน อ.พิชัย) <span class="src">[1][2]</span></td><td>“ป้ายน้ำหมู่บ้าน” วัดระดับน้ำสระ/ถังประปา + แจ้งมือถือ + ตารางแบ่งน้ำ</td><td>ได้ ไม้วัดระดับน้ำ + อาสากรอกผ่านเว็บ</td><td>★★ ง่ายที่สุด</td></tr>
            <tr><td><b>ไฟป่า / หมอกควัน</b></td><td>จุดความร้อน 192 จุด อันดับ 3 ของประเทศ (27 ก.พ. 2566) · PM2.5 66.5 µg/m³ (7 เม.ย. 2569) <span class="src">[3][4]</span></td><td>“ธงฝุ่นโรงเรียน” เซนเซอร์ PM2.5 + ธง/ไฟ 3 สี + แจ้งผู้ปกครอง</td><td>ได้ อ่านค่าจากเว็บของหน่วยงานรัฐแล้วกรอกเอง</td><td>★★</td></tr>
            <tr><td><b>วาตภัย</b></td><td>พายุฤดูร้อน 3 พ.ค. 2567 ลมแรง ลูกเห็บ 9 อำเภอ 664 หลังคาเรือน ไฟดับหลายชั่วโมง <span class="src">[5]</span></td><td>“ยามลมหมู่บ้าน” กังหันวัดลม + แผนที่จุดเสี่ยงพายุ + บัตรตรวจบ้าน</td><td>ได้ แผนที่จุดเสี่ยงและบัตรตรวจบ้านไม่ต้องใช้บอร์ด</td><td>★★★ กังหันต้องสอบเทียบ</td></tr>
            <tr><td><b>ดินถล่ม</b></td><td>ดินสไลด์ถนนทรุด อ.ท่าปลา (3 ต.ค. 2567) · น้ำป่าพัดโคลนท่อนซุงเข้าหมู่บ้าน อ.น้ำปาด (2554) <span class="src">[6][7]</span></td><td>“เสาเฝ้าไหล่เขา” วัดความชื้นดิน + ฝนสะสม + สมุดสังเกตรอยแตก</td><td>ได้ ถังวัดฝน DIY + สมุดสังเกต + อาสากรอก</td><td>★★★ เสี่ยงอธิบายเกินจริงที่สุด ต้องมีผู้ใหญ่ร่วม</td></tr>
          </tbody>
        </table></div>
        <p class="sm mute" style="margin:0">แนะนำให้เริ่มจากภัยแล้งหรือหมอกควัน (ทำสำเร็จง่ายและเห็นผลเร็ว) ส่วนวาตภัยกับดินถล่มเหมาะกับกลุ่มที่มีเวลาสอบเทียบหรือต้องการโจทย์ท้าทาย</p>
      </div>

      <!-- 4 tech -->
      <div class="blk" id="lib-tech">
        <h3><span class="num-dot" style="--c:var(--a6);--on:var(--a6-on)">4</span>คำศัพท์เทคโนโลยีที่เจอในตัวอย่าง</h3>
        <div class="grid g2">
          <div class="card flat"><dl class="kv">
            <dt>IPST-WiFi (ESP32)</dt><dd>บอร์ดไมโครคอนโทรลเลอร์ที่โรงเรียนมี ใช้อ่านเซนเซอร์และส่งข้อมูลทาง Wi-Fi</dd>
            <dt>JSN-SR04T / HC-SR04</dt><dd>เซนเซอร์อัลตราโซนิกวัดระยะถึงผิวน้ำ (รุ่น JSN-SR04T กันน้ำ)</dd>
            <dt>PMS5003 / PMS7003</dt><dd>เซนเซอร์ฝุ่น PM2.5 สำเร็จรูป</dd>
            <dt>ตัวแบ่งแรงดัน 1 kΩ + 2 kΩ</dt><dd>ลดสัญญาณ ECHO 5 V ให้เหลือราว 3.3 V ก่อนเข้าขาบอร์ด</dd>
          </dl></div>
          <div class="card flat"><dl class="kv">
            <dt>Google Apps Script + Sheets</dt><dd>เซิร์ฟเวอร์ฟรี รับข้อมูล คำนวณระดับ เก็บประวัติ และแสดงหน้าเว็บ</dd>
            <dt>Telegram Bot / LINE</dt><dd>ช่องทางส่งข้อความเตือนไปยังมือถืออาสา</dd>
            <dt>MicroPython · Thonny · microBlock</dt><dd>ภาษาและเครื่องมือเขียนโปรแกรมลงบอร์ด</dd>
            <dt>Script Properties</dt><dd>ที่เก็บรหัสลับของ Apps Script ห้ามใส่รหัสในโค้ดหรือโพสต์ในกลุ่ม</dd>
            <dt>โหมดจำลอง (SIMULATE)</dt><dd>ให้ระบบสร้างค่าจำลองเพื่อซ้อมโดยไม่ต้องมีภัยหรืออุปกรณ์จริง</dd>
          </dl></div>
        </div>
        <div class="callout warn"><svg class="ic" aria-hidden="true"><use href="#i-warn"/></svg><div><h5>ความปลอดภัยที่ใช้ทุกชิ้นงาน</h5><p>ใช้ไฟ 5 V จากพาวเวอร์แบงก์เท่านั้น ห้ามต่อไฟบ้าน 220 V · ไม่ทดลองในภัยจริง ทดสอบด้วยแบบจำลองในห้อง · ไม่ใส่ชื่อ เบอร์ หรือพิกัดบ้านจริงลงชีตที่แชร์ · การติดตั้งในพื้นที่จริงให้ผู้ใหญ่หรือ อบต. เป็นผู้ทำ</p></div></div>
      </div>

      <!-- 5 levels -->
      <div class="blk" id="lib-levels">
        <h3><span class="num-dot" style="--c:var(--a2);--on:var(--a2-on)">5</span>ระดับ 0–3 เสาวัดน้ำของเว็บนี้</h3>
        <p>ทุกชิ้นงานใช้ระดับเดียวกัน เพื่อให้ไซเรน ไฟ หน้าเว็บ และข้อความมือถือ “พูดเหมือนกัน” ตัวเลขเกณฑ์ที่เปลี่ยนระดับเป็นค่าตัวอย่าง ต้องขอเกณฑ์จริงจาก อบต. ปภ. หรือหน่วยงานเฉพาะด้าน</p>
        <div class="grid g4">
          <div class="card" style="--c:var(--lv0)"><h4>0 ปกติ</h4><p class="sm" style="margin:0">เตรียมตัวล่วงหน้า สำรวจจุดเสี่ยงก่อนฤดูกาล</p></div>
          <div class="card" style="--c:var(--lv1)"><h4>1 เฝ้าระวัง</h4><p class="sm" style="margin:0">เริ่มสังเกต ลดความเสี่ยงที่ทำได้ทันที</p></div>
          <div class="card" style="--c:var(--lv2)"><h4>2 เตือนภัย</h4><p class="sm" style="margin:0">เตรียมพร้อมลงมือ ตามขั้นตอนที่ตกลงไว้</p></div>
          <div class="card" style="--c:var(--lv3)"><h4>3 อันตราย</h4><p class="sm" style="margin:0">ทำตามคำสั่งหน่วยงานทันที ขอความช่วยเหลือ</p></div>
        </div>
        <div class="callout idea"><svg class="ic" aria-hidden="true"><use href="#i-bulb"/></svg><div><h5>สถานะที่ห้ามลืม: “ไม่มีข้อมูล”</h5><p>ถ้าเซนเซอร์เงียบเกินเวลาที่กำหนด หน้าเว็บต้องแสดง <b>ไม่มีข้อมูล</b> ไม่ใช่สีเขียว เพราะ <b>เงียบไม่เท่ากับปลอดภัย</b></p></div></div>
      </div>

      <!-- 6 sources -->
      <div class="blk" id="lib-src">
        <h3><span class="num-dot" style="--c:var(--a1);--on:var(--a1-on)">6</span>แหล่งข่าวและเอกสารอ้างอิง</h3>
        <p>หมายเลข [n] ในแท็บ “ตัวอย่าง 4 ภัยอื่น” ตรงกับรายการนี้ ตรวจเมื่อ 23 ต.ค. 2569 ข่าวบางชิ้นเก่า (2549–2559) ใช้เป็นตัวอย่าง “ลักษณะปัญหา” นักเรียนควรสอบถาม อบต. หรือผู้ใหญ่บ้านถึงสถานการณ์ปัจจุบันของหมู่บ้านตนเองเพิ่มเติม</p>
        <ul class="srcs">
          <li><span class="n">[1]</span>คมชัดลึก: หลายจว.เจอวิกฤติภัยแล้งต้องซื้อน้ำหุงข้าว (ข่าว 6 ม.ค. 2558, ต.น้ำอ่าง อ.ตรอน)<br><a class="inline-link" href="https://www.komchadluek.net/news/198959" target="_blank" rel="noopener">https://www.komchadluek.net/news/198959</a></li>
          <li><span class="n">[2]</span>สมาคมการค้ามันสำปะหลังไทย: แม้แต่ไร่มันฯ ยังแห้งตาย “นาอิน อุตรดิตถ์” แล้งจัดจริง (ข่าว 21 มี.ค. 2559)<br><a class="inline-link" href="https://ttta-tapioca.org/%E0%B9%81%E0%B8%A1%E0%B9%89%E0%B9%81%E0%B8%95%E0%B9%88%E0%B9%84%E0%B8%A3%E0%B9%88%E0%B8%A1%E0%B8%B1%E0%B8%99%E0%B8%AF-%E0%B8%A2%E0%B8%B1%E0%B8%87%E0%B9%81%E0%B8%AB%E0%B9%89%E0%B8%87%E0%B8%95%E0%B8%B2/" target="_blank" rel="noopener">ttta-tapioca.org (ข่าวไร่มันสำปะหลังแห้งตาย นาอิน)</a></li>
          <li><span class="n">[3]</span>มติชน: จุดความร้อนวันที่ 27 ก.พ. 2566 (เผยแพร่ 28 ก.พ. 2566)<br><a class="inline-link" href="https://www.matichon.co.th/local/news_3847836" target="_blank" rel="noopener">https://www.matichon.co.th/local/news_3847836</a></li>
          <li><span class="n">[4]</span>ฐานเศรษฐกิจ: สถานการณ์ฝุ่น PM2.5 (เผยแพร่ 7 เม.ย. 2569)<br><a class="inline-link" href="https://www.thansettakij.com/sustainable/environment/656010" target="_blank" rel="noopener">https://www.thansettakij.com/sustainable/environment/656010</a></li>
          <li><span class="n">[5]</span>ไทยรัฐ: พายุฤดูร้อนอุตรดิตถ์ 9 อำเภอ (เหตุการณ์ 3 พ.ค. 2567)<br><a class="inline-link" href="https://www.thairath.co.th/news/local/north/2783044" target="_blank" rel="noopener">https://www.thairath.co.th/news/local/north/2783044</a></li>
          <li><span class="n">[6]</span>ไทยโพสต์: ฝนถล่มอุตรดิตถ์ ดินสไลด์ ถนนขาด ไฟฟ้าดับ (3 ต.ค. 2567)<br><a class="inline-link" href="https://www.thaipost.net/district-news/667660/" target="_blank" rel="noopener">https://www.thaipost.net/district-news/667660/</a></li>
          <li><span class="n">[7]</span>MGR Online: น้ำป่า-ดินโคลน อ.น้ำปาด (8–9 ก.ย. 2554)<br><a class="inline-link" href="https://mgronline.com/local/detail/9540000114707" target="_blank" rel="noopener">https://mgronline.com/local/detail/9540000114707</a></li>
          <li><span class="n">[8]</span>MGR Online: น้ำป่า-ดินโคลน อ.น้ำปาด (ข่าวเดียวกันอีกชิ้น)<br><a class="inline-link" href="https://mgronline.com/daily/detail/9540000114861" target="_blank" rel="noopener">https://mgronline.com/daily/detail/9540000114861</a></li>
          <li><span class="n">[9]</span>กรมพัฒนาที่ดิน: เอกสาร PDF ที่กล่าวถึงอุทกภัยและดินโคลนถล่ม พ.ศ. 2549 และพื้นที่เสี่ยงดินถล่มของ อ.ลับแล เมือง ท่าปลา<br><a class="inline-link" href="https://orgweb.ldd.go.th/sources/img/part_document/FILES_9922_6644d03597fbc.pdf" target="_blank" rel="noopener">https://orgweb.ldd.go.th/sources/img/part_document/FILES_9922_6644d03597fbc.pdf</a></li>
          <li><span class="n">[10]</span>ESPHome (ซอร์สโค้ดตัวอ่าน PMS5003 ใช้ยืนยันตำแหน่งไบต์ PM2.5 และ checksum ที่โค้ดบอร์ดใช้)<br><a class="inline-link" href="https://api-docs.esphome.io/pmsx003_8cpp_source" target="_blank" rel="noopener">https://api-docs.esphome.io/pmsx003_8cpp_source</a></li>
        </ul>
        <p class="sm mute" style="margin:0">เหตุการณ์ A ในใบกิจกรรมที่ 1 อ้างอิงข่าวแนวหน้า <a class="inline-link" href="https://www.naewna.com/local/513477" target="_blank" rel="noopener">naewna.com/local/513477</a> ส่วนเหตุการณ์ B ตรงกับข่าวไทยโพสต์ [6]</p>
        <p class="sm mute" style="margin:0">เกณฑ์ PM2.5 ตามตาราง AQI ไทยแบบเฉลี่ย 24 ชม. (เหลือง 25.1–37.5 · ส้ม 37.6–75 · แดง 75.1 ขึ้นไป µg/m³) ควรตรวจกับประกาศฉบับล่าสุดของหน่วยงานก่อนใช้จริง</p>
      </div>

      <!-- 7 help -->
      <div class="blk" id="lib-help">
        <h3><span class="num-dot" style="--c:var(--a4);--on:var(--a4-on)">7</span>ในเหตุฉุกเฉินจริง ให้ฟังหน่วยงานทางการ</h3>
        <div class="grid g3">
          <div class="card" style="--c:var(--a1)"><div class="big-num">1784</div><p class="sm" style="margin:0">สายด่วน ปภ. (ป้องกันและบรรเทาสาธารณภัย)</p></div>
          <div class="card" style="--c:var(--a4)"><div class="big-num">199</div><p class="sm" style="margin:0">ไฟลามใกล้ชุมชน แจ้งเหตุไฟไหม้</p></div>
          <div class="card" style="--c:var(--a3)"><div class="big-num" style="font-size:1.35rem;line-height:1.4">ท้องถิ่น + อุตุฯ</div><p class="sm" style="margin:0">เทศบาล / อบต. / ผู้ใหญ่บ้าน และกรมอุตุนิยมวิทยา</p></div>
        </div>
        <p class="sm mute" style="margin:0">ตัวอย่างทั้งหมดในเว็บนี้เป็นตัวอย่างเพื่อการเรียนรู้ ชื่อทีม ตัวเลขเกณฑ์ และผลทดสอบเป็นข้อมูลสมมติ ต้นแบบของนักเรียนใช้เสริมการเตือนภัยเท่านั้น ไม่ใช่การแทนที่ การตัดสินใจอพยพหรือประกาศภัยเป็นหน้าที่ของหน่วยงานและผู้ใหญ่บ้าน</p>
      </div>
    </div>
  </div>
</section>

</main>

<footer class="foot">
  <div class="wrap">
    <p><b>คลังเนื้อหาและสื่อ หน่วยการเรียนรู้ฐานสมรรถนะ “ปัญญาประดิษฐ์เพื่อแก้ปัญหาภัยธรรมชาติในจังหวัดอุตรดิตถ์”</b></p>
    <p>พัฒนาโดย : นางสาวจิตราพัชญ์ อมรนพรัตนกุล<br>โรงเรียนอุตรดิตถ์ สังกัดสำนักงานเขตพื้นที่การศึกษามัธยมศึกษาพิษณุโลก อุตรดิตถ์<br>E-mail : <a class="inline-link" href="mailto:jittraphat@utd.ac.th">jittraphat@utd.ac.th</a></p>
  </div>
</footer>
</div>
<script>
window.HZX={"drought":{"intro":["«ฉบับตัวอย่างเฉลยสำหรับครู — ภัยที่เลือก: ภัยแล้ง (จังหวัดอุตรดิตถ์)»","ข้อความสีน้ำเงินคือแนวตอบตัวอย่าง นักเรียนต้องคิดและเขียนด้วยตนเอง ไม่ควรคัดลอก ส่วนเกณฑ์ประเมินและตารางบันทึกระดับของครูเว้นว่างไว้ (ชื่อนักเรียน ก ข ค ง จ เป็นชื่อสมมติ)","ข้อมูลเหตุการณ์อ้างอิงข่าว: น้ำอ่าง อ.ตรอน (ม.ค. 2558) • นาอิน/นายาง อ.พิชัย (มี.ค. 2559) • ข่าว ปภ. ผ่าน สผ. (9 พ.ค. 2563) • ข่าว ส.ว. ลงพื้นที่ อ.เมือง (30 ธ.ค. 2568) ข่าว 3 ชิ้นแรกเก่า ใช้ดู \"รูปแบบปัญหา\" ไม่ใช่สถานการณ์ปัจจุบัน ตรวจเมื่อ 23–24 ต.ค. 2569","ข้อความที่ขึ้นต้นว่า \"(สมมติ)\" ในใบกิจกรรมที่ 5–6 เป็นตัวอย่างวิธีเขียนบันทึก ไม่ใช่ผลวัดจริง และเกณฑ์ระดับน้ำทั้งหมดเป็นค่าสมมติ ต้องใช้ข้อมูลจริงจากผู้ดูแลประปา/ท้องถิ่น","ชิ้นงานต้นแบบ \"เพื่อนบ้านเตือนภัย\" (ชุดค่าภัยแล้ง) แยกเป็นชุดต่างหาก เป็นต้นแบบการเรียนรู้ ไม่ใช่ระบบประกาศหรือเตือนภัยทางการ ระดับน้ำที่วัดไม่เท่ากับปริมาณน้ำคงเหลือ"],"acts":{"a1":{"pre":[["p","ภารกิจ : เลือกภัยธรรมชาติที่มีโอกาสเกิดหรือเคยเกิดขึ้นในจังหวัดอุตรดิตถ์ แล้วสืบค้นข้อมูลจากแหล่งที่เชื่อถือได้ เพื่อทำความเข้าใจความเสี่ยง โดยตั้งคำถามให้มากกว่าที่รู้ และกล้าตรวจสิ่งที่เคยเชื่อ ก่อนเสนอวิธีแก้"]],"secs":[{"h":"1. เลือกภัยและระบุบริบทพื้นที่","b":[["p","ใช้ข้อมูลจริงหรือสถานการณ์จำลองที่ครูกำหนด"],["p","☐ น้ำท่วม/น้ำป่า    ☐ ดินถล่ม    «☒» ภัยแล้ง    ☐ วาตภัย    ☐ ไฟป่า/หมอกควัน    ☐ อื่น ๆ ................."],["p","บริบทพื้นที่/สถานการณ์ที่กลุ่มสนใจ (เกิดที่ไหน เมื่อใด หรือมีเงื่อนไขอย่างไร)"],["t",[[["«เมื่อ 6 ม.ค. 2558 หมู่ 3, 5 และ 10 ต.น้ำอ่าง อ.ตรอน (485 ครอบครัว) แหล่งน้ำแห้งขอดจนผลิตน้ำประปาไม่ได้ ประปาไม่ไหลเกิน 2 เดือน ชาวบ้านต้องซื้อน้ำทั้งน้ำใช้ น้ำดื่ม และน้ำหุงข้าว»","«เหตุการณ์ใกล้เคียง: มี.ค. 2559 ต.นาอิน/ต.นายาง อ.พิชัย ไร่มันสำปะหลังนับพันไร่แห้งตาย • 9 พ.ค. 2563 อุตรดิตถ์เป็น 1 ใน 9 จังหวัดภาคเหนือที่ประกาศเขตช่วยเหลือภัยแล้งฉุกเฉิน • 30 ธ.ค. 2568 ส.ว. ติดตามเรื่องขาดน้ำอุปโภคบริโภค อ.เมือง»","«เงื่อนไขที่สนใจ: น้ำในสระลดลงทีละน้อยโดยไม่มีใครบอกว่าเหลืออีกกี่วัน ชาวบ้านรู้ตอนประปาไม่ไหลแล้ว — ใช้หมู่บ้านสมมติที่พึ่งประปาจากสระกลาง 1 แห่งในจังหวัดอุตรดิตถ์เป็นพื้นที่ทดลอง»"]]]]]},{"h":"2. รวบรวมข้อมูลและตรวจสอบความน่าเชื่อถือ","b":[["t",[[["แหล่งข้อมูล/หน่วยงาน","(ชื่อหรือ URL ย่อ)"],["ข้อมูลสำคัญที่พบ"],["ตรวจสอบได้อย่างไร / วันที่เข้าถึง"]],[["1.« เดลินิวส์»","«ข่าว ส.ว. ลงพื้นที่อุตรดิตถ์ 30 ธ.ค. 2568»"],["«ติดตามเรื่องร้องเรียนขาดแคลนน้ำอุปโภคบริโภค ต.วังดิน แสนตอ ขุนฝาง อ.เมือง»","«ต.วังดินมีกำหนดแล้วเสร็จ มิ.ย. 2569 ส่วนแสนตอ/ขุนฝางยังไม่มีกำหนด ต้องขอ งบกรมชลประทานปีถัดไป»"],["«เป็นข่าวสรุปการประชุม ไม่ใช่ข้อมูลระดับน้ำ ต้องตรวจสถานะปัจจุบันกับโครงการชลประทาน»","«ลิงก์: dailynews.co.th/news/5455979 เข้าถึง 24 ต.ค. 2569»"]],[["2.« คมชัดลึก»","«ข่าวภัยแล้ง ต.น้ำอ่าง อ.ตรอน 6 ม.ค. 2558»"],["«หมู่ 3, 5, 10 ต.น้ำอ่าง 485 ครอบครัว แหล่งน้ำแห้งขอด ผลิตประปาไม่ได้»","«ประปาไม่ไหลเกิน 2 เดือน ต้องซื้อน้ำใช้ น้ำดื่ม น้ำหุงข้าว»"],["«เป็นข่าวเก่า (พ.ศ. 2558) ใช้ดูรูปแบบปัญหา ไม่ใช้เป็นสถานการณ์ปัจจุบัน»","«ลิงก์: komchadluek.net/news/198959 เข้าถึง 23 ต.ค. 2569»"]],[["3.« สผ. (เผยแพร่ซ้ำข่าว ปภ.)»","«ข่าว 29 จังหวัดประกาศเขตภัยแล้ง 9 พ.ค. 2563»"],["«อุตรดิตถ์เป็น 1 ใน 9 จังหวัดภาคเหนือที่ประกาศเขตช่วยเหลือภัยแล้งฉุกเฉิน»","«ปภ. ใช้รถน้ำเติมถังกลางหมู่บ้านและจุดแจกน้ำตามรอบ รณรงค์ประหยัดน้ำ»"],["«เป็นแหล่งทางการ แต่ไม่แยกตัวเลขของอุตรดิตถ์ ต้องถาม ปภ.อุตรดิตถ์»","«ลิงก์: onep.go.th/?p=8857 เข้าถึง 24 ต.ค. 2569»"]]]]]},{"h":"3. มองเหตุและผลให้รอบด้าน","b":[["t",[[["สาเหตุ/ปัจจัย (อย่างน้อย 2 ข้อ)"],["ผลกระทบต่อชีวิต ทรัพย์สิน ชุมชน หรือสิ่งแวดล้อม"]],[["1.« ฝนทิ้งช่วง ทำให้น้ำในแหล่งน้ำดิบ (สระ/อ่าง) ลดลงจนผลิตประปาไม่ได้ (น้ำอ่าง 2558)»","«บางตำบลเหลือสระกลางสำหรับผลิตประปาเพียง 4–5 แห่ง (นายาง 2559)»"],["1.« ประปาไม่ไหลเกิน 2 เดือน 485 ครอบครัวต้องซื้อน้ำใช้ น้ำดื่ม น้ำหุงข้าว (น้ำอ่าง 2558)»","«น้ำถัง 200 ลิตร ราคา 40 บาทส่งถึงบ้าน ค่าน้ำสะสมเป็นภาระครัวเรือน (นายาง 2559)»"]],[["2.« ไม่มีใครบอกล่วงหน้าว่าน้ำเหลืออีกกี่วัน ชาวบ้านจึงเริ่มประหยัดช้า»","«แหล่งน้ำถาวรของบางตำบลยังรองบประมาณ (แสนตอ ขุนฝาง ข่าว 2568)»"],["2.« ไร่มันสำปะหลังนับพันไร่แห้งตายแล้วมากกว่าครึ่ง เกษตรกรเสียผลผลิต (นาอิน นายาง 2559)»","«ผู้สูงอายุ/ผู้ป่วยที่ขนน้ำเองไม่ไหวต้องพึ่งคนอื่น (ข้อสันนิษฐาน ต้องไปถามจริง)»"]]]]]},{"h":"4. ใครเสี่ยงอย่างไร? ลองมองจากมุมผู้ได้รับผลกระทบ","b":[["p","กลุ่มที่ 2 ให้เลือกกลุ่มที่กลุ่มเราไม่ค่อยคุ้นเคยหรือมักถูกมองข้าม (เช่น ผู้พิการ ผู้ป่วยติดเตียง เด็กเล็ก แรงงานย้ายถิ่น)"],["t",[[["ผู้ได้รับผลกระทบ"],["ความเสี่ยง/สิ่งที่กังวล"],["ความต้องการที่สำคัญ"]],[["กลุ่มที่ 1:« ผู้สูงอายุที่อยู่คนเดียว/ผู้ป่วยติดเตียง»","«(กลุ่มที่เรานึกถึงเป็นอันดับแรก)»"],["«ขนน้ำเองไม่ไหว ต้องพึ่งคนซื้อหรือส่งน้ำ ค่าน้ำถังซ้ำ ๆ เป็นภาระ (นายาง 2559: ถัง 200 ลิตร 40 บาท)»","«ถ้าประปาหยุดกะทันหันอาจไม่มีน้ำดื่มสำรอง»"],["«รู้ล่วงหน้าหลายวันเพื่อให้มีคนมาเติมน้ำสำรองไว้ก่อน»","«น้ำดื่มและน้ำใช้ส่งถึงบ้านตามรอบ»"]],[["กลุ่มที่ 2:« ผู้ดูแลประปาหมู่บ้านและอาสา»","«(กลุ่มที่มักถูกมองข้าม — สมมติฐานของกลุ่ม ต้องไปถามผู้ดูแลจริง)»"],["«ต้องตัดสินใจเรื่องประหยัด/แบ่งน้ำทั้งที่ไม่มีตัวเลขระดับน้ำต่อเนื่อง และอาจถูกตำหนิเมื่อน้ำหมด»","«เดินไปดูสระด้วยตัวเองได้ไม่ทุกวัน»"],["«ตัวเลขระดับน้ำรายวันและแนวโน้มที่ใช้อธิบายให้ชาวบ้านเข้าใจ»","«ข้อความสำเร็จรูปบอกว่าแต่ละระดับให้ประหยัดอย่างไร»"]]]],["p","เลือกกลุ่มเป้าหมายหลัก 1 กลุ่ม และบอกเหตุผลที่เลือก"],["t",[[["«กลุ่มเป้าหมายหลัก: ผู้สูงอายุที่อยู่คนเดียวและผู้ป่วยติดเตียงในหมู่บ้านที่พึ่งประปาจากสระกลาง»","«เหตุผล: ขนน้ำเองไม่ได้ ต้องการเวลาเตรียมน้ำสำรองนานที่สุด และมักไม่ได้ใช้สมาร์ตโฟนหรือกลุ่มไลน์ จึงต้องมีคนรู้ก่อนกลุ่มอื่น»","«คนที่ช่วยเขาได้คือเพื่อนบ้าน อาสา และผู้ดูแลประปา ต้นแบบจึงต้องบอก \"คนช่วย\" ด้วย ส่วนกลุ่มที่ 2 (ผู้ดูแลประปา) เป็นผู้ใช้ระบบโดยตรงที่ต้องมีข้อมูลก่อน»"]]]]]},{"h":"5. สิ่งที่รู้แล้ว / ยังไม่รู้ / ต้องหาต่อ","b":[["t",[[["สิ่งที่รู้จากหลักฐาน"],["สิ่งที่ยังไม่รู้ (คำถามที่ยังไม่มีคำตอบ)"],["จะสืบค้นหรือถามใคร/ที่ใด"]],[["«ประปาหมู่บ้านบางแห่งไม่ไหลนานเกิน 2 เดือนเมื่อแหล่งน้ำแห้ง (น้ำอ่าง 2558)»","«เรื่องขาดน้ำอุปโภคบริโภคใน ต.วังดิน/แสนตอ/ขุนฝาง ยังเป็นเรื่องร้องเรียนปลายปี 2568»"],["«สระกลางของหมู่บ้านเราลดลงวันละกี่เซนติเมตรในหน้าแล้ง?»","«ระดับน้ำเท่าไรที่ผู้ดูแลประปาถือว่าต้องเริ่มประหยัด?»"],["«ถามผู้ดูแลประปาและผู้ใหญ่บ้านว่าปีก่อน ๆ น้ำเริ่มวิกฤตเมื่อใด»","«ดูข้อมูลน้ำและฝนของหน่วยงานรัฐ เช่น กรมชลประทาน ThaiWater»"]],[["«ปภ. ร่วมกับหน่วยงานอื่นใช้รถน้ำเติมถังกลางประจำหมู่บ้านและจุดแจกน้ำตามรอบ และรณรงค์ให้ประหยัดน้ำ (ข่าว 2563)»","«ข่าวเก่า (2558–2559) ใช้ดูรูปแบบปัญหา ไม่ใช่สถานการณ์ปัจจุบัน»"],["«รถน้ำและจุดแจกน้ำมาตามรอบ หรือมาเมื่อน้ำหมดแล้วเท่านั้น?»","«ถังน้ำกลางของหมู่บ้านเรามีหรือไม่ และใครรู้ก่อนว่าน้ำใกล้หมด?»"],["«ถามเทศบาล/อบต. และ ปภ.อุตรดิตถ์ (โทร 1784)»","«เดินสำรวจสระกลางและถังประปากับผู้ดูแลประปา»"]]]]]},{"h":"6. ตั้งคำถามสำรวจปัญหา","b":[["p","ต้องมีทั้ง “ทำไม...?” และ “ถ้า...จะเป็นอย่างไร?” เพื่อขยายมุมมอง เช่น “ทำไมผู้สูงอายุจึงอาจได้รับผลกระทบจากน้ำป่ามากกว่าคนวัยทำงาน” / “ถ้าเกิดน้ำป่าในเวลากลางคืนและไม่มีอินเทอร์เน็ต จะเป็นอย่างไร”"],["p","คำถามที่ 1 “ทำไม...?” และเหตุใดคำถามนี้จึงสำคัญ"],["t",[[["«ทำไมครัวเรือนจึงมักรู้ว่าน้ำใกล้หมดตอนที่ประปาไม่ไหลแล้ว ทั้งที่น้ำในสระลดลงมาหลายสัปดาห์?»","«สำคัญเพราะถ้ารู้ว่าขาดข้อมูล ขาดคนเฝ้าดู หรือไม่มีเกณฑ์ที่ตกลงกัน จะออกแบบให้ข่าวถึงทุกบ้านก่อนวิกฤตได้ตรงจุด»"]]]],["p","คำถามที่ 2 “ถ้า...จะเป็นอย่างไร?” และเงื่อนไขใหม่ที่อยากสำรวจ"],["t",[[["«ถ้าสระลดลงทีละน้อยต่อเนื่อง 3 สัปดาห์โดยไม่มีฝน และไม่มีใครเดินไปดูระดับน้ำ ครัวเรือนจะรู้ได้อย่างไรว่าต้องเริ่มประหยัดแล้ว?»","«เงื่อนไขใหม่ที่อยากสำรวจ: ไม่มีผู้ดูแลเฝ้าสระประจำ ไม่มีสัญญาณมือถือที่สระ — ไม้วัดสีที่เห็นจากถนน อาสาไปอ่านทุกเช้า หรือกล่องวัดอัตโนมัติ อย่างไหนช่วยได้?»"]]]]]},{"h":"7. ท้าทายสิ่งที่เคยเชื่อ","b":[["p","เขียนสิ่งที่เรา/คนทั่วไปเชื่อหรือทำเป็นปกติเมื่อเกิดภัยนี้ แล้วตรวจกับหลักฐานจากส่วนที่ 2"],["t",[[["สิ่งที่เคยเชื่อ/วิธีที่คุ้นเคย"],["ตรวจกับหลักฐานแล้วพบว่า (ตรง / ขัด / ยังไม่รู้)"],["ถ้าข้อสมมตินี้ใช้ไม่ได้ (เช่น ไฟดับ ไม่มีอินเทอร์เน็ต เกิดกลางคืน) จะเกิดอะไรขึ้น"]],[["1.« เคยเชื่อว่า \"แล้งแล้วค่อยซื้อน้ำก็ได้\"»"],["«ขัด: น้ำอ่าง 2558 ประปาไม่ไหลเกิน 2 เดือน 485 ครอบครัวต้องซื้อน้ำทุกอย่าง และนายาง 2559 น้ำถัง 200 ลิตรราคา 40 บาท ต้องซื้อซ้ำ»"],["«ค่าน้ำสะสมสูงเมื่อแล้งนาน ผู้ที่ซื้อไม่ไหวหรือขนไม่ได้จะไม่มีน้ำ ต้องรู้ล่วงหน้าเพื่อกักน้ำและแบ่งกัน»"]],[["2.« เคยเชื่อว่า \"ภัยแล้งเป็นเรื่องของเกษตรกร ไม่เกี่ยวกับน้ำกินน้ำใช้ในบ้าน\"»"],["«ขัด: น้ำอ่าง 2558 ประปาหมู่บ้านผลิตไม่ได้ และ ธ.ค. 2568 ยังมีเรื่องร้องเรียนขาดน้ำอุปโภคบริโภคใน อ.เมือง»"],["«น้ำดื่มน้ำใช้ในบ้านพึ่งแหล่งน้ำเดียวกัน ถ้าแหล่งน้ำแห้งทั้งชุมชนได้รับผลพร้อมกัน»"]]]],["p","ข้อมูลหรือมุมมองที่ไม่คุ้นเคย หรือขัดกับที่เราคิด 1 เรื่อง — กลุ่มชะลอการตัดสินและสำรวจเพิ่มอย่างไรก่อนสรุป"],["t",[[["«ข้อมูลที่ขัดกับที่คิด: เดิมคิดว่าภัยแล้งแก้ได้ด้วยการหาน้ำมาเติมเมื่อขาด แต่ข่าว ปภ. (9 พ.ค. 2563) บอกว่านอกจากส่งน้ำและขุดบ่อ ยังต้องรณรงค์ให้ประหยัดน้ำ และให้เกษตรกรปรับการทำเกษตรให้สอดคล้องกับน้ำในพื้นที่ — จึงต้องรู้สถานการณ์น้ำก่อน ไม่ใช่รอเติมทีหลัง»","«ชะลอการตัดสิน: ยังไม่สรุปว่าป้ายบอกระดับน้ำดีที่สุด จะถามผู้ดูแลประปาว่าชาวบ้านเคยปรับการใช้น้ำเมื่อรู้ข่าวหรือไม่ และตรวจว่าหมู่บ้านมีถังน้ำกลางหรือจุดแจกน้ำหรือยัง»","«ผลที่ปรับความคิด: เพิ่ม \"รู้ล่วงหน้า\" และ \"แบ่ง/ประหยัดน้ำร่วมกัน\" เข้าไปในโจทย์ ไม่ทำแค่ป้ายบอกตัวเลข»"]]]]]}]},"a2":{"pre":[["p","ภารกิจ : นำข้อมูลจากใบกิจกรรมที่ 1 มากำหนดปัญหาที่เฉพาะเจาะจง มีผู้ใช้ชัดเจน แล้วสร้างโจทย์ออกแบบหลายแนวทางด้วยกลยุทธ์ที่ต่างกัน ก่อนเลือกโจทย์ที่แก้ได้ด้วยต้นแบบ"]],"secs":[{"h":"1. แยกสาเหตุ ปัญหาหลัก และผลกระทบ","b":[["t",[[["สาเหตุ (เหตุใดจึงเกิด)"],["ปัญหาหลัก (สิ่งที่ต้องแก้)"],["ผลกระทบ (สิ่งที่ตามมา)"]],[["«ฝนทิ้งช่วง น้ำเข้าสระน้อยกว่าน้ำที่ใช้ แหล่งน้ำดิบลดลงเรื่อย ๆ»","«สระที่ใช้ผลิตประปามีน้อยและพึ่งแหล่งเดียว (นายาง 2559 เหลือ 4–5 สระ)»"],["«ชาวบ้านไม่รู้ว่าน้ำจะหมดเมื่อไร เพราะไม่มีใครวัดและบอกระดับน้ำสระเป็นประจำ»","«ไม่มีเกณฑ์ที่ตกลงกันว่าระดับไหนต้องเริ่มประหยัด»"],["«ประปาไม่ไหล ต้องซื้อน้ำใช้ น้ำดื่ม น้ำหุงข้าว (น้ำอ่าง 2558)»","«ผู้สูงอายุและผู้ป่วยติดเตียงขนน้ำไม่ไหว»"]],[["«บางตำบลยังไม่มีแหล่งน้ำถาวรพอ (แสนตอ ขุนฝาง 2568 รองบประมาณปีถัดไป)»","«ข่าวภัยแล้งที่พบอยู่ในช่วง ม.ค.–พ.ค. (2558 2559 2563)»"],["«ข้อมูลระดับน้ำอยู่กับคนเดียว (ผู้ดูแลประปา) ไม่ถึงทุกครัวเรือน»","«ไม่มีวิธีบอกคนที่ไม่ใช้สมาร์ตโฟน»"],["«เกษตรกรเสียผลผลิต (ไร่มันนาอิน/นายาง 2559)»","«ครัวเรือนรายได้น้อยแบกค่าน้ำถังไม่ไหว (ข้อสันนิษฐาน ต้องสอบถาม)»"]]]],["p","จากข้อมูลข้างต้น กลุ่มต้องการแก้ “ปัญหาหลัก” เรื่องใดเพียง 1 เรื่อง เหตุใดจึงสำคัญ และขอบเขตของปัญหาอยู่ตรงไหน (เกิดที่ใด/กับใคร/เมื่อใด)"],["t",[[["«ปัญหาหลัก: ผู้สูงอายุที่อยู่คนเดียวและครัวเรือนที่พึ่งประปาจากสระกลางไม่ได้รับข้อมูลระดับน้ำล่วงหน้า จึงเริ่มประหยัดและเตรียมน้ำสำรองไม่ทันก่อนประปาไม่ไหล»","«สำคัญเพราะ: น้ำหมดทีละน้อยจนไม่มีใครเห็นจุดเปลี่ยน พอรู้ตัวก็ต้องซื้อน้ำทุกอย่าง และคนขนน้ำไม่ไหวเดือดร้อนที่สุด»","«ขอบเขต: หมู่บ้านสมมติ 1 แห่งในจังหวัดอุตรดิตถ์ที่ใช้สระกลางผลิตประปา ช่วงหน้าแล้ง ทดลองเป็นแบบจำลองถังน้ำในโรงเรียน ไม่ใช่ระบบประกาศภัยแล้งทางการ»"]]]]]},{"h":"2. รู้จักผู้ใช้และมองปัญหาจากหลายมุม","b":[["t",[[["คำถาม"],["คำตอบกลุ่มพร้อมหลักฐานจากใบกิจกรรมที่ 1"]],[["ผู้ที่ต้องการช่วยคือใคร?"],["«ผู้สูงอายุที่อยู่คนเดียว/ผู้ป่วยติดเตียงที่พึ่งประปาจากสระกลาง และผู้ดูแลประปา/อาสาที่ต้องแบ่งน้ำ (ผู้ใช้ระบบโดยตรงคือผู้ดูแลประปาและอาสา)»"]],[["ประสบปัญหาเมื่อใด/สถานการณ์ใด?"],["«หน้าแล้งช่วง ม.ค.–พ.ค. เมื่อฝนทิ้งช่วงนานและสระกลางลดลง (เช่น น้ำอ่าง ม.ค. 2558 ประปาไม่ไหลเกิน 2 เดือน)»"]],[["ต้องการความช่วยเหลือแบบใด?"],["«ได้รับข้อมูลระดับน้ำและคำแนะนำประหยัดก่อนน้ำวิกฤต มีน้ำสำรอง และมีคนส่งน้ำให้ตามรอบที่รู้ล่วงหน้า»"]]]],["p","มองปัญหาจากมุมอื่นอย่างน้อย 2 มุม เช่น ชุมชน/วัฒนธรรม เศรษฐกิจ/ค่าใช้จ่าย ความปลอดภัย/จริยธรรม หน่วยงานที่เกี่ยวข้อง"],["t",[[["มุมมอง"],["เห็นปัญหานี้อย่างไร และต้องการอะไร"]],[["มุมมองที่ 1:« ชุมชน/ผู้ดูแลประปา (ผู้ใหญ่บ้าน อสม.)»"],["«กังวลว่าถูกตำหนิเมื่อน้ำหมด และไม่มีตัวเลขระดับน้ำที่เชื่อถือได้ไปบอกชาวบ้านว่าต้องประหยัด»","«ต้องการป้ายหรือกราฟที่ชาวบ้านดูเองแล้วเข้าใจ ไม่ต้องอธิบายซ้ำทีละบ้าน»"]],[["มุมมองที่ 2:« ค่าใช้จ่าย/หน่วยงานท้องถิ่น (เทศบาล อบต.)»"],["«งบน้อย อุปกรณ์ต้องราคาไม่สูง ซ่อมเองได้ ไม่ต้องลงสระเอง (แหล่งน้ำถาวรต้องรองบ เช่น แสนตอ/ขุนฝาง 2568)»","«ไม่อยากให้ป้ายของนักเรียนถูกเข้าใจว่าเป็นการประกาศภัยแล้ง ต้องบอกชัดว่าเป็นต้นแบบ»"]]]]]},{"h":"3. เขียนข้อความกำหนดปัญหา (Problem Statement)","b":[["p","รูปประโยคช่วยคิด : “(กลุ่มเป้าหมาย) ประสบปัญหา (ปัญหา) เมื่อ (สถานการณ์) เนื่องจาก (สาเหตุหรือข้อจำกัด) ส่งผลให้ (ผลกระทบ)”"],["p","ข้อความกำหนดปัญหาของกลุ่ม (เขียนให้เจาะจง ไม่ใช่แค่ชื่อภัย)"],["t",[[["«ผู้สูงอายุที่อยู่ตามลำพังและครัวเรือนที่พึ่งประปาจากสระกลางในหมู่บ้านสมมติ จ.อุตรดิตถ์ ประสบปัญหาไม่รู้ล่วงหน้าว่าน้ำในสระลดถึงระดับใกล้หมด เมื่อฝนทิ้งช่วงนานในหน้าแล้ง เนื่องจากไม่มีผู้วัดและบอกระดับน้ำเป็นประจำ และไม่มีเกณฑ์ที่ตกลงกันว่าเมื่อใดควรประหยัด ส่งผลให้ประปาไม่ไหลโดยไม่มีน้ำสำรอง ต้องซื้อน้ำ และขนน้ำไม่ไหว»","«ตรวจความเฉพาะเจาะจง: มีกลุ่มเป้าหมาย สถานการณ์ สาเหตุ และผลกระทบครบ ไม่ใช่แค่คำว่า \"ภัยแล้ง\"»"]]]]]},{"h":"4. สร้างโจทย์ออกแบบหลายแนวทาง (How Might We...?)","b":[["p","รูปประโยคช่วยคิด : “เราจะออกแบบหรือพัฒนาอะไร เพื่อให้ (ใคร) สามารถ (ทำอะไรเพื่อลดความเสี่ยง) ภายใต้ (เงื่อนไข) ได้อย่างไร?”"],["t",[[["«เราจะออกแบบป้ายบอกระดับน้ำสระราคาประหยัดที่ ม.2 ทำได้ เพื่อให้ผู้ดูแลประปา อาสา และเพื่อนบ้านของผู้สูงอายุรู้ระดับน้ำทุกวันและเริ่มประหยัดหรือแบ่งน้ำได้ก่อนวิกฤต ภายใต้เงื่อนไขไม่มีผู้เฝ้าสระประจำและไม่มีสัญญาณมือถือที่สระ ได้อย่างไร?»","«โจทย์ทางเลือกจากกลยุทธ์ต่างกัน: (เทคโนโลยี) ทำให้สระบอกระดับน้ำเองได้อย่างไร • (คน) ทำให้เพื่อนบ้านแบ่งน้ำและส่งน้ำให้ผู้สูงอายุได้อย่างไร • (ประสาทสัมผัส) บอกระดับด้วยสีที่เห็นจากถนนโดยไม่ต้องอ่านตัวเลขได้อย่างไร»"]]]]]},{"h":"5. สืบค้นเชิงสร้างสรรค์ : เรียนรู้จากวิธีของผู้อื่น","b":[["p","หาวิธีหรือนวัตกรรมที่ผู้อื่นใช้กับปัญหาคล้ายกัน (ภัยอื่น พื้นที่อื่น หรือกลุ่มผู้ใช้อื่น) จากแหล่งที่เชื่อถือได้ แล้วเทียบกับปัญหาของเรา"],["t",[[["วิธี/แนวทางของผู้อื่น (ที่มา)"],["ปัญหา สถานการณ์ หรือความต้องการของเขาเหมือน/ต่างจากของเราอย่างไร"],["แนวคิดที่นำมาใช้ตั้งหรือปรับโจทย์ของเรา"]],[["1.« ปภ. ประกาศเขตช่วยเหลือภัยแล้งฉุกเฉินระดับจังหวัด และใช้รถน้ำเติมถังกลางหมู่บ้าน»","«(ข่าว ปภ. ผ่านเว็บ สผ. 9 พ.ค. 2563)»"],["«เหมือน: ภัยเดียวกัน ต้องการให้ชาวบ้านมีน้ำใช้»","«ต่าง: ประกาศระดับจังหวัดและเกิดหลังแล้งหนักแล้ว ไม่บอกระดับน้ำสระของหมู่บ้านเรา»"],["«ทำตัวบอกระดับน้ำเฉพาะสระ (วัดล่วงหน้า) มาเสริมก่อนถึงขั้นประกาศ ไม่แทนของทางการ»"]],[["2.« ระบบสีของดัชนีคุณภาพอากาศ AQI (ภัยฝุ่น PM2.5) ที่ใช้ ฟ้า เขียว เหลือง ส้ม แดง»","«(กรมควบคุมมลพิษ ผ่านข่าวไทยพีบีเอส)»"],["«ต่างภัย แต่ปัญหาคล้ายกัน: ต้องบอกระดับอันตรายให้คนทั่วไปเข้าใจได้เร็ว»","«ต่าง: AQI ค่าสูงคืออันตราย แต่ระดับน้ำสระต่ำคืออันตราย ต้องระวังไม่ให้สีสับสน»"],["«นำมาทำไฟ 3 สีและระดับ 0–3 โดยให้ \"น้ำน้อย = สีแดง\" และเขียนป้ายกำกับให้ชัด»"]]]],["p","ตั้งคำถาม “ถ้า...จะเป็นอย่างไร?” 1 ข้อ แล้วลองตอบ — คำตอบทำให้เข้าใจปัญหาลึกขึ้น หรือทำให้ได้ทางแก้ใหม่อย่างไร"],["t",[[["«ถ้าเซนเซอร์วัดระดับน้ำพังหรือเงียบไป ระบบจะบอกว่า \"น้ำยังพอ\" หรือไม่?»","«คำตอบ: ไม่ควรบอกว่าน้ำพอ เพราะ \"ไม่มีตัวเลข ไม่เท่ากับ น้ำยังพอ\" ระบบต้องแสดง \"ไม่มีข้อมูล\" และให้อาสาไปอ่านไม้วัดระดับน้ำแทน»","«ผล: ได้โจทย์ใหม่ — ต้องมีช่องให้อาสากรอกระดับน้ำด้วยมือเมื่อบอร์ดดับ และไฟสถานะต้องแยกจากสีเขียว»"]]]]]},{"h":"6. ตรวจความชัดเจนและปรับกรอบโจทย์ (Reframe)","b":[["p","«☒» ระบุผู้ใช้ชัด    «☒» ช่วยลดความเสี่ยงจริง    «☒» ขอบเขตพอดีกับ 15 ชั่วโมง    «☒» ทำต้นแบบจำลองได้    «☒» ไม่อันตราย"],["p","โจทย์ก่อนรับข้อเสนอแนะ / ใครเสนอให้มองต่าง / โจทย์หลังปรับ / ข้อมูลหรือเหตุผลที่ยืนยันว่าดีขึ้น"],["t",[[["«โจทย์ก่อนรับข้อเสนอแนะ: \"ทำเว็บบอกระดับน้ำสระ\"»","«ข้อเสนอแนะ (เพื่อนกลุ่มอื่นและครู): เว็บอย่างเดียวไปไม่ถึงผู้สูงอายุที่ไม่มีมือถือ และถ้าเซนเซอร์ดับจะไม่มีใครรู้ว่าน้ำลดถึงไหน»","«โจทย์หลังปรับ: ทำป้ายน้ำหมู่บ้านที่บอกระดับทั้งบนจอที่สระ ในมือถือผู้ดูแล และไฟ 3 สีที่ศาลา มีช่องกรอกด้วยมือเมื่อบอร์ดดับ และบอกว่าแต่ละระดับต้องประหยัดหรือแบ่งน้ำอย่างไร»","«เหตุผลที่ดีขึ้น: ตรงกับคำถาม \"ถ้าไม่มีผู้ดูแลเฝ้าสระ\" และข่าวน้ำอ่าง 2558 ที่ชาวบ้านรู้ตอนประปาหยุดไหลแล้ว»"]]]]]}]},"a3":{"pre":[["p","ภารกิจ : ต้องคิดเองก่อนใช้ AI จากนั้นแลกเปลี่ยนกับเพื่อนและใช้ AI เพื่อขยาย/ตรวจสอบ ไม่ใช่คัดลอกคำตอบโดยไม่คิด ใบกิจกรรมนี้ดูว่าเราทำงานกับความคิดของผู้อื่นอย่างไร ตั้งแต่เปรียบเทียบ ผสาน ต่อยอด จนสังเคราะห์"]],"secs":[{"h":"1. คิดด้วยตนเองก่อนเปิด AI","b":[["p","ทุกคนกรอกบัตรรายบุคคล 3 แนวคิดต่างกลไก (หน้าถัดไป) ก่อนเปิด AI และก่อนแลกเปลี่ยนความคิดกับเพื่อน บัตรนี้คือ “ความคิดของฉัน” ที่จะใช้เปรียบเทียบและผสานกับผู้อื่นในส่วนที่ 2–5"],["p","«☒» สมาชิกทุกคนส่งบัตรก่อนเปิด AI ครบแล้ว"],["p","ลำดับการทำงานในใบกิจกรรมนี้"],["t",[[["ส่วน"],["ทำอะไร"],["ทำกับใคร / ใช้อะไร"]],[["1"],["คิดเอง 3 แนวทางลงบัตรรายบุคคล"],["ทำคนเดียว ก่อนเปิด AI"]],[["2"],["เปรียบเทียบความคิดของเรากับความคิดของเพื่อน"],["ฟังและบันทึกร่วมกันในกลุ่ม"]],[["3"],["ผสานส่วนที่ดีของเพื่อนอย่างน้อย 2 คนเข้ากับความคิดของเรา"],["สมาชิกในกลุ่ม"]],[["4"],["ต่อยอดกับเพื่อนและ AI แล้วตรวจสอบก่อนนำไปใช้"],["กลุ่ม + AI (มนุษย์เป็นผู้ตรวจและเลือก)"]],[["5"],["สังเคราะห์เป็น 3 แนวคิดที่แตกต่างกันจริงของกลุ่ม"],["ทั้งกลุ่ม"]]]],["sh","บัตรคิดเองก่อนใช้ AI (รายบุคคล)"],["p","ให้บันทึกก่อนเปิด AI / ก่อนแลกเปลี่ยนข้อเสนอของ AI เพื่อเก็บ “ความคิดของฉัน” ไว้เป็นฐานสำหรับเปรียบเทียบและผสานกับความคิดของผู้อื่น"],["p","ชื่อ–สกุล «นักเรียน จ (ตัวอย่าง)»  ·  ห้อง   ·  เลขที่   ·  กลุ่ม «2»  ·"],["p","โจทย์ภัยธรรมชาติที่ต้องการแก้ «บอกระดับน้ำสระให้ผู้ดูแลประปารู้ก่อนน้ำหมด»  ·"],["p","คิดเอง 3 แนวทาง โดยพยายามให้กลไกช่วยลดความเสี่ยงต่างกัน"],["p","เขียนชื่อวิธี หลักการทำงาน ผู้ใช้ และเหตุผลที่คาดว่าจะช่วยแก้ปัญหาได้"],["p","แนวคิดที่ 1: ชื่อวิธี / ทำงานอย่างไร / ช่วยใคร / เหตุผล (เขียนโดยไม่ใช้ AI)"],["t",[[["«ชื่อวิธี: ไม้วัดน้ำสีเขียว เหลือง แดง ปักที่สระ — อาสาอ่านทุกเช้า เขียนตัวเลขบนกระดานหน้าศาลา และส่งรูปเข้ากลุ่มไลน์»","«ช่วยใคร: ผู้ดูแลประปาและชาวบ้าน • เหตุผล: ไม่ต้องใช้ไฟฟ้าหรือเน็ต แต่ต้องมีคนไปอ่านทุกวัน»"]]]],["p","แนวคิดที่ 2: ชื่อวิธี / ทำงานอย่างไร / ช่วยใคร / เหตุผล (เขียนโดยไม่ใช้ AI)"],["t",[[["«ชื่อวิธี: กล่องวัดระดับน้ำอัตโนมัติ — เซนเซอร์อัลตราโซนิกเหนือสระ วัดทุกชั่วโมง แสดงระดับบนจอที่กล่องและส่งขึ้นเว็บ»","«ช่วยใคร: ผู้ดูแลประปาและอาสาที่ไม่อยู่หมู่บ้าน • เหตุผล: เห็นแนวโน้มน้ำลดต่อเนื่องโดยไม่ต้องเดินไปดู ใช้พาวเวอร์แบงก์ 5 V ได้»"]]]],["p","แนวคิดที่ 3: ชื่อวิธี / ทำงานอย่างไร / ช่วยใคร / เหตุผล (เขียนโดยไม่ใช้ AI)"],["t",[[["«ชื่อวิธี: เพื่อนบ้านคู่หู — จับคู่บ้านผู้สูงอายุกับเพื่อนบ้าน 1 บ้านที่เติมน้ำสำรองและส่งน้ำให้ตามวันที่ตกลงกัน»","«ช่วยใคร: ผู้สูงอายุ ผู้ป่วยติดเตียง • เหตุผล: มีคนช่วยถึงตัว แม้ไม้วัดหรือเซนเซอร์ใช้ไม่ได้»"]]]],["p","แนวคิดทั้ง 3 ต่างกันตรงหลักการทำงานหรือวิธีช่วยผู้ใช้อย่างไร (ไม่ใช่แค่ชื่อหรือสี)"],["t",[[["«ต่างที่กลไก ไม่ใช่แค่ชื่อหรือสี: (1) คนอ่านด้วยตาและเขียนบอก ไม่ใช้ไฟฟ้า (2) เครื่องวัดต่อเนื่องและเห็นแนวโน้ม (3) เครือข่ายคนที่ส่งน้ำถึงตัว»","«แต่ละแบบแก้จุดอ่อนของอีกแบบ: (1) ต้องมีคนไปอ่านทุกวัน (2) ไม่รู้ว่าบ้านไหนต้องได้น้ำก่อน (3) ต้องรู้ระดับน้ำก่อนจึงจะวางแผนแบ่งน้ำได้»"]]]],["p","ฉันเริ่มคิดเวลา «09.10»  ส่งบัตรนี้เวลา «09.30»   «☒» ก่อนเปิด AI    ☐ ก่อนอ่านคำตอบจาก AI"],["p","หมายเหตุ: นักเรียนทุกคนต้องคิดด้วยตนเอง 3 แนวทางที่พยายามใช้กลไกช่วยลดความเสี่ยงแตกต่างกันก่อนใช้ AI ทั้งนี้จำนวนแนวคิดเป็นเพียงเงื่อนไขให้มีหลักฐานเพียงพอ ไม่ใช้จำนวนแนวคิดเพียงอย่างเดียวตัดสินความสร้างสรรค์"]]},{"h":"2. เปรียบเทียบความคิดของเรากับความคิดของเพื่อน","b":[["p","สมาชิกแต่ละคนเล่าแนวคิดที่ตนชอบที่สุด 1 ข้อ ทุกคนฟังให้ครบ แล้วบันทึกว่าเหมือนหรือต่างจากความคิดของตนเองอย่างไร"],["t",[[["สมาชิก/ผู้เสนอ"],["ข้อเสนอ (สรุปสั้น)"],["เหมือน/ต่างจากความคิดของฉันอย่างไร"],["สิ่งที่กลุ่มเห็นว่าน่าสนใจ"]],[["1.« ก»  ·"],["«ส่งระดับน้ำและแนวโน้ม \"เหลืออีกประมาณกี่วัน\" เข้ากลุ่มผู้ดูแลประปาทุกเช้า»"],["«เหมือน: ใช้ค่าระดับน้ำจากเซนเซอร์ ต่าง: ของ ก ต้องใช้เน็ต ของฉันแสดงระดับบนจอที่กล่องได้แม้ไม่มีเน็ต»"],["«รู้ว่าน้ำจะอยู่ได้อีกประมาณกี่วัน จึงวางแผนแบ่งน้ำได้»"]],[["2.« ข»  ·"],["«ป้ายไฟเขียว เหลือง แดงที่ศาลา มองเห็นจากถนน»"],["«เหมือน: บอกด้วยสี ต่าง: ของ ข อยู่กลางหมู่บ้านให้ทุกคนเห็น ของฉันอยู่ที่สระให้คนเฝ้าดู»"],["«คนไม่มีมือถือก็เห็นระดับน้ำ ไม่ต้องอ่านตัวเลข»"]],[["3.« ค»  ·"],["«ตารางแบ่งน้ำและเพื่อนบ้านคู่หูส่งน้ำให้ผู้สูงอายุตามวัน»"],["«ต่างมาก: ไม่ใช้เทคโนโลยี แต่ใช้ร่วมกับของฉันได้เมื่อรู้ระดับน้ำ»"],["«ข่าว ปภ. 2563 มีรถน้ำเติมถังกลางตามรอบ — ตารางของ ค ช่วยให้น้ำถึงบ้านที่ขนไม่ไหว»"]],[["4.« ง»  ·"],["«จดวันที่ไม่มีฝนด้วยกระบอกวัดฝนหน้าศาลา เตือนเมื่อแล้งติดต่อกัน 7 วัน (ตัวเลขสมมติ)»"],["«ต่าง: ดูฝน ไม่ได้ดูน้ำในสระ แต่เป็นสัญญาณก่อนน้ำลด ของฉันดูผลที่สระโดยตรง»"],["«เตือนได้ก่อนน้ำลด และเป็นข้อมูลสำรองเมื่อเซนเซอร์ดับ»"]],[["5.  ·","​"],["​","​"],["​","​"],["​","​"]]]],["p","จุดร่วมและจุดต่างที่เห็นเด่นที่สุดในข้อเสนอของสมาชิกทั้งหมด"],["t",[[["«จุดร่วม: ทุกคนต้องการให้ \"รู้ก่อนน้ำหมด\" และไม่รอจนประปาหยุดไหลหรือรอประกาศเขตภัยแล้ง»","«จุดต่าง: ช่องทางที่ใช้ (ตัวเลข สี ฝน ตารางคน) และพึ่งไฟฟ้า/เน็ตหรือไม่ ยังไม่มีใครคิดว่าถ้าเซนเซอร์ดับจะรู้ระดับน้ำได้อย่างไร»"]]]]]},{"h":"3. ผสานความคิดของสมาชิก","b":[["p","เลือกส่วนที่ดีของข้อเสนอจากสมาชิกอย่างน้อย 2 คน มาผสานกับความคิดของตนเอง"],["t",[[["เจ้าของแนวคิดที่ 1 + ส่วนที่เลือก"],["เจ้าของแนวคิดที่ 2 + ส่วนที่เลือก"],["เจ้าของแนวคิดที่ 3 + ส่วนที่เลือก"]],[["ชื่อ« ก»  ·","ส่วนที่เลือก« ส่งระดับน้ำและแนวโน้มเข้ากลุ่มทุกเช้า»","«เหตุผล: ผู้ดูแลประปาที่ไม่อยู่หมู่บ้านก็รู้»","«ปรับ: ส่งสรุปวันละครั้ง ไม่ส่งรัว ๆ»"],["ชื่อ« ข»  ·","ส่วนที่เลือก« ป้ายไฟ 3 สีที่ศาลา»","«เหตุผล: คนไม่มีมือถือก็เห็น»","«ปรับ: ให้ไฟ \"ไม่มีข้อมูล\" สลับสี ไม่ติดเขียว»"],["ชื่อ« ค»  ·","ส่วนที่เลือก« ตารางแบ่งน้ำและเพื่อนบ้านคู่หู»","«เหตุผล: ผู้สูงอายุได้น้ำแม้ขนเองไม่ได้»","«ปรับ: เก็บรายชื่อหลัง PIN ไม่โพสต์สาธารณะ»"]]]],["p","ความคิดใหม่ที่เกิดจากการผสาน — ส่วนใดของเพื่อนอย่างน้อย 2 คนที่นำมาผสานกับความคิดของเรา และผลเป็นอย่างไร"],["t",[[["«ความคิดใหม่: \"ป้ายน้ำหมู่บ้าน\" = กล่องวัดระดับน้ำที่สระ (ของฉัน) + ข้อความและแนวโน้มเข้ามือถือผู้ดูแลประปา (ของ ก) + ป้ายไฟ 3 สีที่ศาลา (ของ ข)»","«ผลที่ได้: รู้ระดับน้ำทั้งที่สระและจากทางไกล ถ้าเน็ตหลุด กล่องที่สระยังแสดงระดับบนจอเอง และป้ายไฟที่ศาลาสลับไฟบอกว่า \"ไม่มีข้อมูล\"»","«ส่วนของ ค (ตารางแบ่งน้ำ) ใส่เป็นข้อความ \"สิ่งที่ควรทำ\" ในทุกระดับ ส่วนของ ง (นับวันไม่มีฝน) เป็นช่องที่อาสากรอกเอง»"]]]]]},{"h":"4. ต่อยอดกับเพื่อนและ AI","b":[["p","AI เป็นอีกแหล่งข้อเสนอหนึ่ง กลุ่มต้องเป็นผู้ตรวจและเลือก Prompt ต้องระบุปัญหา ผู้ใช้ ข้อจำกัด (เช่น ไม่มีไฟ/ไม่มีเน็ต) และขอทางเลือกที่ ม.2 ทำต้นแบบได้"],["p","Prompt ที่ใช้จริง (ไม่เขียนข้อมูลส่วนบุคคลหรือข้อมูลอ่อนไหว)"],["t",[[["«ฉันเป็นนักเรียน ม.2 ในจังหวัดอุตรดิตถ์ กำลังทำต้นแบบเฝ้าระวังภัยแล้งให้หมู่บ้านที่ใช้สระกลางผลิตประปา ผู้ใช้คือผู้ดูแลประปาและอาสาที่ต้องช่วยผู้สูงอายุ»","«ข้อจำกัด: ไม่มีผู้เฝ้าสระประจำ ไฟฟ้าและสัญญาณที่สระไม่แน่นอน งบจำกัด ใช้บอร์ด IPST-WiFi (ESP32) ที่โรงเรียนมี»","«ขอทางเลือก 5 แนวทางที่ ม.2 ทำเป็นต้นแบบจำลองได้ พร้อมข้อควรระวังด้านความปลอดภัย (ไม่ใส่ชื่อ/ที่อยู่คนจริง)»"]]]],["t",[[["ข้อเสนอที่ AI ให้"],["เหตุผลรับ/ไม่รับ (ความปลอดภัย–ผู้ใช้–ทรัพยากร)"],["ตรวจสอบหรือปรับด้วยตนเอง/ร่วมกับเพื่อน"]],[["1.« ให้ระบบแจ้ง \"ไม่มีข้อมูล\" เมื่อเซนเซอร์เงียบเกินเวลาที่กำหนด (ไม่มีตัวเลข ไม่เท่ากับ น้ำยังพอ)»"],["«รับ: ปลอดภัยขึ้น ไม่ต้องใช้อุปกรณ์เพิ่ม และตรงกับผู้ใช้ (ผู้ดูแลประปา)»"],["«ลดเวลา STALE_MIN ในชีต Config เหลือ 5 นาทีระหว่างทดสอบ แล้วถอดสายเซนเซอร์ ดูว่าเว็บขึ้น \"ไม่มีข้อมูล\" จริงหรือไม่ (ค่าใช้จริง 25 ชั่วโมง)»"]],[["2.« ใช้ดาวเทียมหรือเว็บพยากรณ์ฝนทำนายวันที่น้ำจะหมดแทนการวัดจริง»"],["«ไม่รับ: เกินความสามารถ ม.2 ผลไม่แม่นพอจะบอกชาวบ้าน และสระแต่ละแห่งต่างกัน»"],["«เปลี่ยนเป็นวัดระดับน้ำจริงที่สระของเรา และใช้อัตราน้ำลดจากข้อมูลของเราเอง»"]]]],["p","AI ช่วยตรงไหน? เราคัดทิ้ง/แก้ไขอะไรเพราะเหตุใด และใช้แหล่งใดตรวจสอบคำแนะนำที่เกี่ยวกับภัย"],["t",[[["«AI ช่วย: เสนอแนวคิดสถานะ \"ไม่มีข้อมูล\" และช่วยร่างข้อความแจ้งระดับ 4 ระดับ»","«เราคัดทิ้ง: การทำนายวันน้ำหมดด้วยดาวเทียม และตัวเลขเกณฑ์ระดับน้ำ (กี่ ซม. ถึงวิกฤต) ที่ AI ให้มา เพราะไม่มีที่มา ต้องใช้ข้อมูลสระของหมู่บ้านจริง»","«ตรวจสอบกับ: ผู้ดูแลประปา/เทศบาล/อบต. และประกาศทางการ (สายด่วน ปภ. 1784)»"]]]],["p","ผังที่มาของความคิดใหม่ — เชื่อมความคิดของเพื่อน/AI เข้ากับความคิดของเรา"],["t",[[["ความคิดตั้งต้น (ของใคร)"],["ส่วนที่ต่อยอดจากเพื่อน/AI"],["ข้อค้นพบหรือมุมมองใหม่ที่เกิดขึ้น"],["ต่างจากข้อเสนอเดิมอย่างไร"]],[["«ของฉัน: กล่องวัดระดับน้ำที่สระ แสดงระดับเองไม่พึ่งเน็ต»"],["«จาก ก: ส่งข้อความและแนวโน้มวันละครั้ง»","«จาก ข: ป้ายไฟที่ศาลา»"],["«แสดงผล 2 ชั้น (จอที่สระ + ไฟที่ศาลา/มือถือ) ช่วยกันเมื่อชั้นใดชั้นหนึ่งล่ม»"],["«เดิมมีกล่องเดียวที่สระ ใหม่มีทั้งที่สระ ศาลา และมือถือ»"]],[["«ของ ค: ตารางแบ่งน้ำ»"],["«จาก AI: ไม่มีตัวเลข ไม่เท่ากับ น้ำยังพอ»"],["«ต้องบอกด้วยว่า \"ระบบมองไม่เห็น\" และให้คนไปอ่านไม้วัดสำรอง ไม่ใช่แค่บอกว่าน้ำน้อย»"],["«เดิมไม่เตือนเมื่อระบบเงียบ ใหม่ขึ้นสถานะไม่มีข้อมูลและให้อาสากรอกแทน»"]]]]]},{"h":"5. สังเคราะห์เป็น 3 แนวคิดที่แตกต่างกันจริง","b":[["p","ส่วนนี้เป็น 3 แนวทางของกลุ่ม ส่วนรายบุคคลให้ตรวจบัตรคิดเอง 3 แนวทางของแต่ละคน ไม่ใช้ผลรวมกลุ่มแทนความคิดของคนใดคนหนึ่ง"],["t",[[["แนวคิด/วิธีทำงาน"],["ที่มา: ใครคิด (สมาชิก/AI) จุดแข็งหรือมุมมองของใครที่นำมาใช้ และต่อยอดส่วนใด"],["เหมาะกับใครและลดความเสี่ยงอย่างไร"]],[["1.« สถานีวัดระดับน้ำสระ + แจ้งมือถือ»","«เซนเซอร์ + IPST-WiFi ส่งข้อมูลไป Apps Script แล้วแจ้ง Telegram/LINE ตามระดับ 0–3 (น้ำน้อย = ระดับสูง)»"],["«ฉันคิดกล่องวัดระดับน้ำ ก คิดข้อความและแนวโน้ม AI เสนอสถานะ \"ไม่มีข้อมูล\"»"],["«เหมาะกับผู้ดูแลประปา/อาสาที่มีมือถือ»","«ลดความเสี่ยงโดยรู้ก่อนน้ำหมดและเริ่มประหยัดทัน»"]],[["2.« ป้ายไฟ 3 สีที่ศาลา + ตารางแบ่งน้ำ»","«ไฟเปลี่ยนสีตามระดับ และมีป้ายบอกว่าแต่ละสีต้องประหยัดน้ำอย่างไร»"],["«ข คิดป้ายไฟ ค คิดตารางแบ่งน้ำ ฉันคิดให้ไฟสลับบอกเมื่อไม่มีข้อมูล»"],["«ทุกคนในหมู่บ้าน รวมคนไม่มีมือถือ»","«ลดความเสี่ยงโดยให้ทุกบ้านเห็นระดับน้ำและรู้ว่าต้องทำอะไร»"]],[["3.« เพื่อนบ้านคู่หู + กระบอกวัดฝนและวันไม่มีฝน»","«จับคู่บ้านผู้สูงอายุกับเพื่อนบ้านที่ส่งน้ำให้ และนับวันไม่มีฝนเป็นสัญญาณล่วงหน้า»"],["«ค คิดตารางส่งน้ำ ง คิดนับวันไม่มีฝน ฉันคิดการจับคู่บ้าน AI เตือนเรื่องข้อมูลส่วนบุคคล»"],["«ผู้สูงอายุ ผู้ป่วยติดเตียง»","«ลดความเสี่ยงโดยมีคนส่งน้ำถึงตัวเมื่อเทคโนโลยีล่ม»"]]]],["p","แนวคิดที่กลุ่มภูมิใจที่สุด ต่างจากก่อนผสาน/ก่อนใช้ AI อย่างไร (ระบุสิ่งที่คิดเองชัดเจน) และเหตุใดจึงรวมเป็นผลงานหนึ่งเดียวของกลุ่มได้"],["t",[[["«แนวคิดที่ภูมิใจที่สุด: แสดงผล 2 ชั้น — กล่องที่สระแสดงระดับบนจอเองแม้ไม่มีเน็ต และส่งขึ้นมือถือเมื่อมีเน็ต ต่างจากก่อนผสานที่ฉันมีแค่กล่องเดียวและไม่ได้คิดถึงคนไม่มีมือถือ»","«สิ่งที่ฉันคิดเอง: กล่องวัดระดับน้ำที่สระ แสดงระดับเองไม่ใช้เน็ต • จากเพื่อน: ข้อความและแนวโน้ม ป้ายไฟ ตารางแบ่งน้ำ นับวันไม่มีฝน • จาก AI: ไม่มีตัวเลข ไม่เท่ากับ น้ำยังพอ»","«รวมเป็นผลงานเดียวได้เพราะทุกส่วนใช้ \"ระดับ 0–3\" เดียวกันและเชื่อมกันผ่านเซิร์ฟเวอร์เดียว»"]]]]]}]},"a4":{"pre":[["p","ภารกิจ : ใช้ 3 ทางเลือกที่สร้างไว้ เปรียบเทียบความเหมาะสมและความปลอดภัย แล้วทำภาพร่าง/ผังงานที่ผู้อื่นนำไปสร้างต้นแบบได้ จากนั้นทดลองบนกระดาษ รับข้อเสนอแนะ และปรับเป็นแบบร่างรุ่นที่ 2"]],"secs":[{"h":"1. เปรียบเทียบ 3 แนวคิดโดยดูผู้ใช้และข้อจำกัด","b":[["t",[[["แนวคิด"],["ข้อดีต่อผู้ใช้"],["ข้อจำกัด/ความเสี่ยง"],["ทำได้จริงภายในเวลาอย่างไร"]],[["1.« สถานีวัดระดับน้ำสระ + แจ้งมือถือ»"],["«เห็นแนวโน้มน้ำลดต่อเนื่อง เก็บประวัติไว้ปรับเกณฑ์ได้»","«ผู้ดูแลประปาที่ไม่อยู่หมู่บ้านก็ได้รับ»"],["«ต้องพึ่งเน็ต ผู้สูงอายุที่ไม่มีมือถือไม่ได้รับ»","«ตั้งเกณฑ์ผิดอาจเตือนช้าหรือเร็วเกินไป»"],["«ใช้ IPST-WiFi + เซนเซอร์ + Apps Script (มีชุดโค้ดต้นแบบชุดภัยแล้งให้ปรับ)»","«อยู่ในกรอบ 5 ชั่วโมงลงมือ ทดสอบกับถังน้ำ 20 ลิตร»"]],[["2.« ป้ายไฟ 3 สีที่ศาลา + ตารางแบ่งน้ำ»"],["«ทุกคนเห็นสถานะโดยไม่ต้องใช้มือถือ»"],["«สีอาจสับสนกับ AQI ต้องมีป้ายอธิบาย และไฟไม่บอกตัวเลขหรือแนวโน้ม»"],["«ใช้ชุดไฟ LED 3 สีของบอร์ดตัวที่ 2 ปิดเสียง ทำง่าย»"]],[["3.« เพื่อนบ้านคู่หู + ตารางแบ่งน้ำ»"],["«ผู้สูงอายุได้น้ำถึงตัว ไม่ใช้ไฟฟ้า»"],["«รายชื่อบ้านผู้สูงอายุเป็นข้อมูลส่วนบุคคล และไม่รู้ว่าเมื่อไรควรเริ่มแบ่งถ้าไม่มีตัวเลขระดับน้ำ»"],["«ทำเป็นตารางตัวอย่าง (ข้อมูลสมมติ) + หน้าเว็บ PIN ได้ ส่วนการส่งน้ำจริงต้องมีผู้ใหญ่บ้านร่วม»"]]]],["p","แนวคิดที่เลือกคือ «แนวคิดที่ 1 + ป้ายไฟ 3 สีของแนวคิดที่ 2» เหตุผลที่เลือก (แก้ตรงโจทย์ ผู้ใช้ ทรัพยากร ความปลอดภัย)"],["t",[[["«แก้ตรงโจทย์: เลือกแนวคิดที่ 1 เป็นแกน เพราะวัดระดับน้ำสระของเราเองและบอกก่อนน้ำจะหมด แล้วนำป้ายไฟ 3 สีของแนวคิดที่ 2 มารวมด้วย»","«ผู้ใช้: ผู้ดูแลประปาและอาสาได้ข้อความพร้อม \"สิ่งที่ควรทำ\" ส่วนคนไม่มีมือถือเห็นสีไฟที่ศาลา»","«ทรัพยากร/ความปลอดภัย: ใช้บอร์ดและเซนเซอร์ที่โรงเรียนมี ใช้ไฟ 5 V จากพาวเวอร์แบงก์ ทดสอบกับถังน้ำ ไม่ลงสระจริง»"]]]],["p","เหตุผลที่ไม่เลือกอีก 2 แนวคิด (หรือส่วนที่ตัดสินใจละทิ้ง) และเงื่อนไขใดอาจทำให้เปลี่ยนการตัดสินใจ"],["t",[[["«แนวคิดที่ 2 เดี่ยว ๆ: ไฟอย่างเดียวไม่มีข้อมูลระดับน้ำให้ตรวจ จึงเก็บไว้เป็นส่วนแสดงผลของแนวคิดที่ 1»","«แนวคิดที่ 3: การส่งน้ำจริงต้องมีผู้ใหญ่บ้านร่วม ใน 15 ชั่วโมงทำได้เพียงตารางตัวอย่าง (ข้อมูลสมมติ) จึงตัดการเก็บชื่อจริงผู้สูงอายุทิ้ง»","«เปลี่ยนใจได้ถ้า: สระไม่มีที่ติดเซนเซอร์ที่ปลอดภัย → ใช้ไม้วัดสีและอาสากรอกผ่านเว็บ • หรือผู้ใหญ่บ้านขอรายชื่อจริง → ต้องขออนุญาตและจำกัดสิทธิ์ผู้เห็น»"]]]]]},{"h":"2. ร่างแบบรุ่นที่ 1 และอธิบายหลักการทำงาน","b":[["p","วาดแผนภาพ/ผังงานขนาดใหญ่ ระบุส่วนประกอบ ลำดับการทำงาน ทางเข้าของข้อมูล ผลลัพธ์ และจุดที่ผู้ใช้จะโต้ตอบกับต้นแบบ"],["t",[[["พื้นที่ภาพร่าง/ผังงาน (ใช้ลูกศร หมายเลข และคำอธิบายกำกับ)"]]]],["p","อธิบาย 1) ต้นแบบเริ่มทำงานอย่างไร 2) ผู้ใช้ได้รับประโยชน์อะไร 3) หากไฟดับ/ไม่มีอินเทอร์เน็ตจะทำอย่างไร"],["t",[[["«1) เริ่มทำงาน: เปิดบอร์ดข้างสระ ต่อ Wi-Fi วัดระยะถึงผิวน้ำทุก 1 ชั่วโมง (ใช้ค่ากลางหลายครั้ง) แล้วเทียบเกณฑ์ จอที่กล่องแสดงระดับ 0–3 และส่งข้อมูลขึ้นเว็บ ส่วนป้ายไฟที่ศาลาถามเว็บแล้วเปลี่ยนสี»","«2) ประโยชน์: ผู้ดูแลประปา/อาสาได้ข้อความ \"ระดับ 2 เตือนภัย\" พร้อมสิ่งที่ควรทำ เช่น ลดการใช้น้ำและจัดตารางแบ่งน้ำ ส่วนป้ายไฟให้คนไม่มีมือถือรู้»","«3) ไฟดับ/ไม่มีเน็ต: กล่องใช้พาวเวอร์แบงก์และแสดงระดับบนจอเอง ป้ายไฟที่ศาลาสลับไฟบอกว่า \"ไม่มีข้อมูล\" ไม่ติดเขียวค้าง ถ้าเซนเซอร์เงียบเกิน 25 ชั่วโมง เว็บแสดง \"ไม่มีข้อมูล\"»"]]]]]},{"h":"3. ขยายความคิดให้ละเอียดพอสำหรับสร้างจริง","b":[["p","เขียนให้เพื่อนกลุ่มอื่นอ่านแล้วเข้าใจว่าต้องสร้างอะไร"],["t",[[["ส่วนประกอบของต้นแบบ"],["ลักษณะเฉพาะ/วิธีทำงาน","(ขนาด วัสดุที่คิดไว้ ข้อมูลเข้า–ออก)"],["ผู้ใช้โต้ตอบกับส่วนนี้อย่างไร"]],[["1.« สถานีวัดระดับน้ำ»","«IPST-WiFi + เซนเซอร์อัลตราโซนิก + จอ OLED»"],["«เข้า: ระยะจากเซนเซอร์ถึงผิวน้ำ → คำนวณความสูงน้ำเหนือก้นสระ»","«ออก: ระดับ 0–3 (น้ำน้อย = ระดับสูง) + จอ OLED + ส่งข้อมูลขึ้นเว็บ»"],["«ผู้ใช้ไม่ต้องกดอะไร ดูระดับบนจอที่กล่อง»","«อาสาเป็นผู้ติดตั้งและตรวจแบตเตอรี่»"]],[["2.« เซิร์ฟเวอร์»","«Google Apps Script Web App + Google Sheet»"],["«รับข้อมูลที่มีรหัสลับ คำนวณระดับ เก็บประวัติ»","«แจ้ง Telegram/LINE และแสดงหน้าเว็บบนมือถือ»"],["«ผู้ดูแลประปาเปิดหน้าเว็บดูสถานะและกราฟน้ำลด»","«รับข้อความเตือนในมือถือ»"]],[["3.« ป้ายไฟ 3 สี»","«IPST-WiFi ตัวที่ 2 + LED เขียว/เหลือง/แดง (ปิดเสียง)»"],["«ถามระดับจากเว็บทุก 10–20 วินาที»","«เขียว/เหลืองนิ่ง แดงกะพริบ ถ้าข้อมูลหายแสดงไฟสลับ»"],["«คนในหมู่บ้านดูสีไฟและอ่านป้ายอธิบายสี»","«ผู้สูงอายุที่เห็นสีได้ดูได้โดยไม่ต้องใช้มือถือ»"]]]],["p","จุดที่ยังคลุมเครือหรือยังตอบไม่ได้ในแบบร่าง และสิ่งที่ต้องทดลองหรือหาข้อมูลเพิ่มก่อนสร้าง"],["t",[[["«เกณฑ์ระดับน้ำจริงของสระ (กี่ ซม. = เหลือง/แดง) และรูปทรงสระ (น้ำลด 1 ซม. ที่ขอบกับที่ก้นสระปริมาตรต่างกัน) — ยังไม่รู้ ต้องถามผู้ดูแลประปา/อบต. ตอนนี้ใช้ค่าสมมติ»","«เซนเซอร์จะแม่นแค่ไหนเมื่อผิวน้ำเป็นคลื่น มีใบไม้ลอย หรืออากาศร้อนจัด — ต้องทดลองในถังน้ำ (แนวทาง: ใช้ค่ากลางของการวัดหลายครั้ง)»","«เกณฑ์ผิดทำให้ชาวบ้านประหยัดเกินไปหรือไม่ประหยัดเลย — ต้องทดลองเรื่องการยืนยันก่อนลดระดับ และตรวจเกณฑ์กับผู้ดูแลประปาหลังฤดูแล้ง»"]]]]]},{"h":"4. ทดลองบนกระดาษและปรับเป็นแบบร่างรุ่นที่ 2","b":[["p","ทดลองเดินตามสถานการณ์จำลอง 1 รอบ (บนกระดาษหรือสวมบทบาท) โดยใช้แบบร่างรุ่นที่ 1 — ผู้ใช้ทำอะไรเป็นขั้นแรก และติดขัดตรงไหน"],["t",[[["«สถานการณ์จำลอง (สมมติ): สระลดลงวันละ 3 ซม. ติดต่อกัน 3 สัปดาห์โดยไม่มีฝน ถึงวันที่ 15 เซนเซอร์ดับ ผู้ใช้คือผู้ดูแลประปา ก ถือมือถือ»","«ขั้นแรกที่ผู้ดูแลทำ: เปิดข้อความเตือน แล้วเปิดหน้าเว็บ ติดขัด: ข้อความบอกแค่ \"ระดับ 2\" ไม่รู้ว่าต้องเริ่มประหยัดแค่ไหนและบ้านผู้สูงอายุหลังไหนต้องได้น้ำก่อน»","«ติดขัดอีก: วันที่เซนเซอร์ดับ ผู้ดูแลไม่มีไม้วัดสำรองและไม่มีช่องบอกระบบว่าอ่านระดับน้ำได้เท่าไร»"]]]],["p","ข้อเสนอแนะที่เฉพาะเจาะจงจากเพื่อน/ครู (เขียนว่าใครเสนอเรื่องใด)"],["t",[[["ข้อเสนอแนะ (ใครเสนอ)"],["สิ่งที่ปรับในแบบร่างรุ่นที่ 2"],["เหตุผล/ผลที่คาดว่าจะดีขึ้น"]],[["1.« เพื่อน ฉ (กลุ่มอื่น): ข้อความเตือนควรบอกว่าต้องทำอะไร»"],["«เพิ่มบรรทัด \"สิ่งที่ควรทำ\" 4 ข้อ ตามระดับ เช่น ลดการใช้น้ำ จัดตารางแบ่งน้ำ ในข้อความและหน้าเว็บ»"],["«ผู้ดูแลไม่ต้องเดา ตัดสินใจเร็วขึ้น»"]],[["2.« ครู: ต้องมีไม้วัดสำรองและช่องกรอกระดับน้ำด้วยมือเมื่อบอร์ดดับ และห้ามเผยชื่อผู้สูงอายุในหน้าเว็บสาธารณะ»"],["«ติดไม้วัดที่สระ ให้อาสาอ่านแล้วกรอกในพื้นที่อาสาสมัคร (ใส่ PIN) และเก็บรายชื่อไว้หลัง PIN หน้าสาธารณะแสดงแค่จำนวนครัวเรือนที่ตรวจแล้ว»"],["«ยังรู้ระดับน้ำได้แม้เซนเซอร์ดับ และคุ้มครองข้อมูลส่วนบุคคล»"]]]],["t",[[["ภาพร่างรุ่นที่ 2 (วาดเฉพาะส่วนที่เปลี่ยน)"]]]],["p","แบบร่างรุ่นที่ 2 ต่างจากรุ่นที่ 1 อย่างไร และมีแนวทางหรือส่วนใดที่ตัดสินใจละทิ้งเพราะไม่ช่วยแก้ปัญหา"],["t",[[["«ต่างจากรุ่นที่ 1: เพิ่มข้อความ \"สิ่งที่ควรทำ\" ตามระดับ เพิ่มไม้วัดสำรอง + ช่องรายงานด้วยมือ และย้ายรายชื่อบ้านผู้สูงอายุไปไว้หลัง PIN (ส่วนอื่นเหมือนเดิม)»","«ละทิ้ง: การทำนายวันน้ำหมดด้วยดาวเทียม/พยากรณ์ (ไม่แม่นพอ) และการเก็บชื่อจริงผู้สูงอายุในระบบ»","«เพราะไม่ช่วยแก้ปัญหาหลัก และเพิ่มความเสี่ยงเรื่องข้อมูลส่วนบุคคล»"]]]]]},{"h":"5. ให้ครูตรวจแบบร่างก่อนสร้างต้นแบบ","b":[["p","☐ แบบร่างชัดเจนพอให้ผู้อื่นสร้างตามได้    ☐ ปลอดภัย ไม่ต้องทดลองในภัยจริง    ☐ อนุญาตให้สร้างต้นแบบ"],["p","ข้อเสนอแนะจากครู (ใช้เป็นข้อมูลย้อนกลับก่อนลงมือสร้าง)"],["t",[[["​","​"]]]]]}]},"a5":{"pre":[["p","ภารกิจ : สร้างต้นแบบตามภาพร่าง อธิบายสิ่งที่ทำจริง แก้ปัญหาเมื่อเจออุปสรรค และตรวจสอบการใช้ AI อย่างรอบคอบ"]],"secs":[{"h":"1. ทบทวนผู้ใช้และข้อกำหนดก่อนสร้าง","b":[["p","ใช้ข้อมูลจากใบกิจกรรมที่ 2 และแบบร่างรุ่นที่ 2 จากใบกิจกรรมที่ 4"],["t",[[["ผู้ใช้/กลุ่มเป้าหมาย"],["ความต้องการและข้อจำกัดสำคัญ"],["ส่วนของต้นแบบที่จะตอบความต้องการนี้"]],[["ผู้ใช้หลัก:« ผู้ดูแลประปาหมู่บ้านและอาสา (ผู้ที่ดูแลผู้สูงอายุ)»"],["«ต้องรู้ระดับน้ำและแนวโน้มทุกวัน ข้อความสั้นและบอกสิ่งที่ควรทำ ใช้มือถือเครื่องเก่า ตัวหนังสืออ่านง่าย»"],["«หน้าเว็บมือถือ + แจ้งเตือน Telegram/LINE + ข้อความ \"สิ่งที่ควรทำ\"»"]],[["ผู้ใช้อื่นที่อาจเกี่ยวข้อง:« ผู้สูงอายุที่ไม่มีมือถือ / ผู้ที่มองตัวเลขเล็กไม่ชัด»"],["«ต้องการสัญญาณที่เห็นง่ายจากถนนหรือศาลา และไม่ถูกเปิดเผยข้อมูลส่วนตัว»"],["«ป้ายไฟ 3 สีที่ศาลา และจอที่กล่องข้างสระ»"]]]]]},{"h":"2. เตรียมความพร้อมและเลือกใช้ทรัพยากร","b":[["p","☐ ครูตรวจแผนแล้ว    «☒» วัสดุปลอดภัย    «☒» ไม่ทดลองในภัยจริง    «☒» ไม่ใช้ไฟฟ้าเสี่ยงอันตราย    «☒» กำหนดผู้รับผิดชอบ"],["t",[[["รายการ"],["เลือกใช้/เหตุผล"],["ข้อควรระวัง/การตรวจสอบ/ทางเลือกที่ปลอดภัย"]],[["วัสดุ–อุปกรณ์"],["«IPST-WiFi 2 ตัว เซนเซอร์อัลตราโซนิก (HC-SR04 หรือ JSN-SR04T) LED เขียว/เหลือง/แดง พร้อมตัวต้านทาน 220 Ω สายจั๊มเปอร์ พาวเวอร์แบงก์ ถังน้ำ 20 ลิตรจำลองสระ ไม้บรรทัด»","«เลือกเพราะโรงเรียนมีบอร์ดอยู่แล้ว ราคาไม่สูง และทดสอบบนโต๊ะได้»"],["«ใช้ไฟ 5 V จากพาวเวอร์แบงก์เท่านั้น ไม่ใช้ไฟบ้านใกล้น้ำ วางถังบนพื้นแห้งและกันน้ำกระเด็น»","«ขา ECHO ของเซนเซอร์เป็นสัญญาณ 5 V ต้องผ่านตัวต้านทาน 1 kΩ + 2 kΩ ก่อนเข้าบอร์ด 3.3 V ทดสอบกับถังน้ำเท่านั้น»"]],[["เครื่องมือ–เทคโนโลยี"],["«Thonny/microBlock เขียน MicroPython ลงบอร์ด • Google Apps Script + Google Sheets • Telegram Bot»","«เลือกเพราะฟรี ใช้บัญชี Google ของโรงเรียนได้»"],["«รหัสลับและโทเคนเก็บใน Script Properties ห้ามใส่ในโค้ดหรือโพสต์ในกลุ่ม»","«ไฟล์ config.py ที่มีรหัส Wi-Fi ไม่ส่งต่อ»"]],[["AI (ถ้าใช้)"],["«ใช้ AI อธิบายโค้ดที่ไม่เข้าใจ และช่วยเรียบเรียงข้อความแจ้งระดับน้ำให้สั้น»","«ไม่ให้ AI ตัดสินเกณฑ์ระดับน้ำหรือทำนายวันน้ำหมด»"],["«ตรวจกับผู้ดูแลประปา/ท้องถิ่น/ประกาศ ปภ. และทดลองเอง ห้ามใส่ข้อมูลส่วนตัวใน Prompt»","«เกณฑ์ระดับน้ำใช้ข้อมูลสระจริง ไม่ใช้ตัวเลขที่ AI เดา»"]]]]]},{"h":"3. วางแผนการสร้างและคาดการณ์อุปสรรค","b":[["t",[[["ขั้นตอนลงมือสร้าง"],["ผู้รับผิดชอบ"],["หลักฐานตรวจความก้าวหน้า"]],[["ขั้น 1« ต่อเซนเซอร์เข้าบอร์ด ทดสอบอ่านระยะถึงผิวน้ำในถัง 20 ลิตร»"],["«จ (ฮาร์ดแวร์)»"],["«ภาพวงจร + ตารางระยะที่อ่านได้เทียบกับไม้บรรทัด»"]],[["ขั้น 2« สร้างเว็บแอป Apps Script + Google Sheet รันชุดค่าภัยแล้ง ตั้ง Script Properties และทดสอบด้วยโหมดจำลอง»"],["«ก (เซิร์ฟเวอร์)»"],["«ภาพหน้าเว็บ + ข้อความทดสอบใน Telegram»"]],[["ขั้น 3« เขียนโค้ดบอร์ดส่งข้อมูลขึ้นเว็บ และต่อป้ายไฟ 3 สี»"],["«ค (โค้ดบอร์ด) ข (ป้ายไฟ)»"],["«วิดีโอสั้นไฟเปลี่ยนสีตามระดับน้ำในถัง»"]],[["ขั้น 4« ทดสอบระบบรวมและซ้อมสถานการณ์เซนเซอร์ดับ/ตัดเน็ตจำลอง»"],["«ทั้งกลุ่ม»"],["«ใบบันทึกผลทดสอบ + ภาพถ่าย»"]]]],["p","อันตราย/ข้อจำกัดที่คาด และวิธีป้องกันหรือแผนสำรองก่อนลงมือสร้าง"],["t",[[["อันตราย/ข้อจำกัดที่คาด"],["ผลกระทบหากเกิดขึ้น"],["มาตรการป้องกัน/ทางสำรอง"],["ตรวจแล้วพบอะไร"]],[["«ไฟฟ้า/พาวเวอร์แบงก์ใกล้น้ำ ลัดวงจร»"],["«ผู้ทดลองได้รับอันตราย บอร์ดเสีย»"],["«ใช้ 5 V วางบอร์ดห่างน้ำ ใส่กล่องกันน้ำ ครูตรวจสายก่อนเปิดไฟ»"],["«(สมมติ) ครูตรวจสายไฟก่อนเปิดทุกครั้ง ไม่พบสายเปลือยใกล้น้ำ»"]],[["«เซนเซอร์อยู่ใกล้ผิวน้ำเกินระยะต่ำสุดของรุ่นที่ใช้ หรือถังเอียง ทำให้ค่าระดับน้ำผิด»"],["«ป้ายแสดงผิด ผู้ใช้ประหยัดเกินไปหรือไม่ประหยัดเลย»"],["«ตรวจระยะต่ำสุดจากดาต้าชีตก่อนติดตั้ง ตั้งเซนเซอร์ให้สูงพอ ตั้งถังให้ตรง และเทียบกับไม้บรรทัดทุกครั้ง»"],["«(สมมติ) เทียบค่าเซนเซอร์กับไม้บรรทัด 5 ระดับ ต่างกันไม่เกิน 1 ซม. (เกณฑ์ที่กลุ่มกำหนดเอง)»"]]]]]},{"h":"4. บันทึกการสร้างอย่างมีหลักฐาน","b":[["t",[[["ลำดับ"],["สิ่งที่ลงมือทำจริง (ระบุสิ่งที่เปลี่ยนจากแผน ถ้ามี)"],["ผู้ลงมือ/ภาพหรือไฟล์หลักฐาน"]],[["1"],["«ต่อเซนเซอร์: TRIG เข้า GPIO25, ECHO ผ่านตัวแบ่งแรงดันเข้า GPIO19 (ตรวจเลขขากับคู่มือบอร์ดของโรงเรียนก่อน) ตั้ง HAZARD=\"drought\" และ SENSOR_TO_BOTTOM_CM แล้วรันโหมดจำลองก่อนต่อเซนเซอร์จริง»"],["«จ / ภาพถ่ายวงจร»"]],[["2"],["«สร้างเว็บแอป: วางโค้ด Code.gs และ Index.html ตั้ง Script Properties รัน setup() แล้วรัน usePresetDrought แล้ว Deploy เป็น Web App»"],["«ก / ภาพหน้าเว็บ + ข้อความทดสอบ»"]],[["3"],["«ใส่ Wi-Fi/URL/รหัสลับในไฟล์ config.py แล้วอัปโหลดไฟล์ขึ้นบอร์ด รันโหมดจริง (ปิดบัซเซอร์ที่สระ)»"],["«ค / ภาพหน้าจอ (ซ่อนรหัสก่อนแนบ)»"]],[["4"],["«ต่อบอร์ดป้ายไฟ: LED เขียว GPIO5 เหลือง GPIO19 แดง GPIO23 ผ่านตัวต้านทาน 220 Ω และตั้ง SOUND_ON=False ให้เป็นไฟอย่างเดียว»"],["«ข / วิดีโอไฟ 3 สี»"]]]],["p","สรุป: ตอนนี้ต้นแบบทำงานได้หรือแสดงหลักการใดแล้ว และยังทำไม่ได้ส่วนใด"],["t",[[["«(สมมติ — ตัวอย่างวิธีเขียน) ทำงานได้/แสดงหลักการ: วัดระดับน้ำในถัง 20 ลิตร → ตัดสินระดับ 0–3 (น้ำน้อยระดับสูง) → จอที่กล่องแสดงระดับ → ส่งขึ้นเว็บและมือถือ → ป้ายไฟที่ศาลาเปลี่ยนสีตาม»","«ยังทำไม่ได้: วัดสระจริงกลางแจ้งตลอดฤดูแล้ง • คำนวณปริมาตรน้ำคงเหลือของสระจริง • ใช้แทนประกาศทางการ • ส่วนที่ยังไม่ได้ทดสอบกับอุปกรณ์จริงให้เขียนว่า \"ยังไม่ทดสอบ\"»"]]]]]},{"h":"5. เมื่อพบอุปสรรค เราคิดและแก้อย่างไร","b":[["t",[[["อุปสรรค/สาเหตุที่คาด"],["ทางเลือกที่เสนอ"],["วิธีที่ลองจริง/ผลที่พบ"]],[["1.« ค่าระยะแกว่งเพราะผิวน้ำเป็นคลื่นหลังตักน้ำออก»"],["«เพิ่มจำนวนครั้งที่วัดต่อรอบ (samples) จาก 5 เป็น 9 หรือรอให้ผิวน้ำนิ่งก่อนอ่าน»"],["«(สมมติ) ลองรอ 10 วินาทีก่อนอ่านแล้วค่ากระโดดน้อยลง ต้องวัดซ้ำหลายครั้งเพื่อยืนยัน»"]],[["2.« เกณฑ์ของสระ (150/100/50 ซม.) สูงกว่าความลึกน้ำในถัง ถังเต็มก็ขึ้นระดับ 3 ทันที»"],["«ย่อเกณฑ์ลงตามสัดส่วน (เช่น 15/10/5 ซม.) ทั้งในชีต Config และตาราง HAZARDS ของโค้ดบอร์ด แล้วจดไว้ว่าปรับอะไรเพราะอะไร»"],["«(สมมติ) หลังย่อเกณฑ์ ตักน้ำออกทีละ 5 ซม. ระดับไล่จาก 0 ไป 3 ตามที่คาด»"]]]],["p","ตัวอย่าง 1 เหตุการณ์ที่กลุ่มเปลี่ยนแผนเอง (ระบุก่อน–หลัง และเหตุผล)"],["t",[[["«ก่อน: วางแผนใช้เกณฑ์ระดับน้ำของสระ (150/100/50 ซม.) กับถังจำลองได้เลย»","«หลัง: ย่อเกณฑ์ตามความลึกของถัง และเขียนในรายงานว่าเป็น \"เกณฑ์จำลอง\"»","«เหตุผล: (สมมติ) ตอนเติมน้ำเต็มถังแล้วบอร์ดขึ้นระดับสูงสุดทันที เพราะน้ำในถังตื้นกว่าเกณฑ์ของสระ จึงต้องปรับตามสัดส่วน»"]]]]]},{"h":"6. บันทึกการใช้ AI อย่างรับผิดชอบ","b":[["t",[[["ใช้ AI ช่วยงานใด/ข้อความคำสั่งย่อ"],["AI เสนออะไร"],["เราตรวจและปรับเองอย่างไร"]],[["1.« ให้ AI อธิบายโค้ดการหาค่ากลางและสถานะข้อมูลขาดหาย (STALE)»"],["«อธิบายว่าค่ากลางช่วยตัดค่าที่เพี้ยนออก และถ้าไม่ส่งข้อมูลเกินเวลาจะขึ้น \"ไม่มีข้อมูล\"»"],["«ทดลองในโหมดจำลองโดยใส่ค่าเพี้ยน แล้วดูว่าผลเป็นไปตามที่ AI บอกหรือไม่»"]],[["2.« ให้ AI ช่วยเรียบเรียงข้อความแจ้งระดับน้ำ 4 ระดับให้สั้น»"],["«ข้อความสั้น มีอีโมจิและคำที่ทำให้ตกใจ เช่น \"น้ำจะหมดแล้ว\"»"],["«ตัดคำที่ทำให้ตกใจเกินจริง ไม่ระบุจำนวนวันที่แน่นอน ใส่เบอร์ ปภ. 1784 และข้อความว่าเป็นต้นแบบของโรงเรียน ให้ฟังประกาศทางการเป็นหลัก»"]]]],["p","ข้อมูลใดจาก AI ที่กลุ่มไม่ใช้ เพราะไม่เหมาะสม ไม่ปลอดภัย หรือไม่มีหลักฐานยืนยัน"],["t",[[["«ไม่ใช้: ตัวเลขเกณฑ์ระดับน้ำและจำนวนวันที่ AI คำนวณให้ เพราะไม่รู้รูปทรงสระ ใช้ค่าสมมติและขอข้อมูลจริงจากผู้ดูแลประปา»","«ไม่ใช้: ไอเดียประกาศ \"เขตภัยแล้ง\" บนหน้าเว็บ เพราะการประกาศเขตเป็นหน้าที่ของหน่วยงานทางการ (จังหวัด/ ปภ.)»","«ไม่ใช้: คำแนะนำให้ลงไปวัดระดับน้ำในสระเอง เพราะอันตราย ให้ผู้ใหญ่เป็นคนติดตั้ง»"]]]]]},{"h":"7. ตรวจสอบความพร้อมของต้นแบบจำลอง","b":[["t",[[["เกณฑ์"],["หลักฐานที่เห็นจริง/สิ่งที่ต้องแก้"]],[["ตรงปัญหาและตอบผู้ใช้ที่กำหนด"],["«ตรง: กล่องที่สระ + ข้อความผู้ดูแล + ป้ายไฟ ตอบโจทย์ \"ไม่รู้ล่วงหน้าว่าน้ำจะหมด\"»","«หลักฐาน: ใบกิจกรรมที่ 2 ข้อ 3»"]],[["แสดงการทำงานได้/อธิบายขั้นตอนชัด"],["«สาธิตในถังน้ำ: ตักน้ำออกทีละ 5 ซม. แล้วระดับบนจอและป้ายไฟเปลี่ยนเขียว → เหลือง → แดง»","«หลักฐาน: วิดีโอสาธิต»"]],[["เลือกใช้ทรัพยากรเหมาะสมและปลอดภัย"],["«ใช้ไฟ 5 V ไม่ใช้ไฟบ้าน เก็บรหัสลับนอกโค้ด»","«หลักฐาน: ตารางความเสี่ยงข้อ 3»"]],[["ต่างจากวิธีทั่วไปอย่างมีเหตุผล"],["«ต่างจากประกาศเขตภัยแล้งและรถน้ำของ ปภ.: วัดระดับสระของหมู่บ้านเองก่อนน้ำหมด แต่ไม่ได้แทนประกาศทางการ»"]]]],["p","ชื่อของต้นแบบ «ป้ายน้ำหมู่บ้าน (ต้นแบบเฝ้าระวังภัยแล้ง)»  ·"],["p","วิธีสาธิตการทำงานอย่างปลอดภัย"],["t",[[["«สาธิตในถังน้ำบนโต๊ะ ใช้ไฟ 5 V จากพาวเวอร์แบงก์ ครูอยู่ดูแล ตักน้ำออกช้า ๆ ให้ถึงระดับเหลือง/แดงตามเกณฑ์จำลองที่กำหนดไว้»","«ถ้าไม่มีอุปกรณ์หรือเน็ต: ใช้โหมดจำลองในโค้ดและปุ่ม \"โหมดจำลอง\" ในหน้าเว็บ ไม่ต้องใช้น้ำจริง»"]]]],["p","หลักฐานภาพถ่าย/ไฟล์/ลิงก์ต้นแบบ"],["t",[[["«หลักฐานที่ต้องแนบ: ภาพถ่ายวงจร วิดีโอสั้นสาธิต ภาพหน้าจอเว็บแอป (ลิงก์ Google Drive ของกลุ่ม ห้ามมีรหัสลับในภาพ)»"]]]]]},{"h":"8. ต้นแบบเราแตกต่างจากวิธีที่มีอยู่จริงอย่างไร","b":[["t",[[["วิธีแก้ปัญหาที่พบหรือใช้อยู่ก่อน"],["สิ่งที่เราเปลี่ยน/เพิ่มในต้นแบบ"],["ประโยชน์ต่อผู้ใช้"],["หลักฐานที่ตรวจสอบได้"]],[["«ประกาศเขตช่วยเหลือภัยแล้งและรถน้ำเติมถังกลางหมู่บ้านของ ปภ. (ข่าว 9 พ.ค. 2563)»","«การเดินไปดูระดับน้ำในสระด้วยตาของผู้ดูแลประปา»"],["«ตัววัดระดับน้ำเฉพาะสระของหมู่บ้าน วัดทุกชั่วโมง»","«จอที่กล่องแสดงระดับเองแม้ไม่มีเน็ต และป้ายไฟที่ศาลา»","«สถานะ \"ไม่มีข้อมูล\" ช่องกรอกด้วยมือ และรายชื่อบ้านผู้สูงอายุหลัง PIN»"],["«ผู้ดูแลเห็นแนวโน้มน้ำลดก่อนถึงขั้นประกาศ»","«คนไม่มีมือถือก็เห็นสถานะ»","«รู้เมื่อระบบเสีย»"],["«วิดีโอสาธิต»","«บันทึกผลทดสอบใบกิจกรรมที่ 6»","«ข่าวอ้างอิงในใบกิจกรรมที่ 1»"]]]],["p","ทำไมสิ่งที่เพิ่มจึงอาจลดความเสี่ยงของกลุ่มเป้าหมายได้ (ไม่อ้างประสิทธิภาพก่อนมีผลทดลอง)"],["t",[[["«สมมติฐาน: ถ้ารู้ระดับน้ำสระของหมู่บ้านเราทุกวันและเห็นแนวโน้ม ผู้ดูแลและครัวเรือนอาจเริ่มประหยัดและเตรียมน้ำสำรองได้ทันมากขึ้น (ยังไม่อ้างว่าได้ผลจนกว่าจะมีผลทดลอง)»","«เหตุผลสนับสนุน: ข่าวน้ำอ่าง นายาง และข่าว ปภ. ชี้ว่าชาวบ้านต้องซื้อน้ำหรือรอรถน้ำเมื่อแล้งหนัก และ ปภ. เองรณรงค์ให้ประหยัดน้ำ ซึ่งต้องรู้สถานการณ์ก่อนจึงจะปรับตัวได้»"]]]],["p","ถ้าผู้ใช้อีกกลุ่มหนึ่งต้องใช้ต้นแบบนี้ ต้องปรับอะไร (หรือใช้วัสดุ/เทคโนโลยีในแบบที่ต่างจากปกติอย่างไร)"],["t",[[["«ถ้าผู้ใช้เป็นโรงเรียนที่ใช้ถังเก็บน้ำ: ติดเซนเซอร์เหนือถังเก็บน้ำของโรงเรียนและปรับเกณฑ์ตามขนาดถัง»","«ถ้าผู้ใช้เป็นเกษตรกรที่ใช้สระน้ำของตนเอง: ใช้ช่องความชื้นดินและวันไม่มีฝนแทน และปรับข้อความเป็นการวางแผนรดน้ำ»"]]]]]},{"h":"9. สาธิตสั้น ๆ ให้ดู","b":[["p","ฉันรับผิดชอบส่วนใด / ส่วนนี้ทำงานอย่างไร / จะสาธิตให้เห็นอะไร"],["t",[[["«ฉันรับผิดชอบ: บอร์ดสถานีวัดระดับน้ำ (ฮาร์ดแวร์)»","«ทำงานอย่างไร: เซนเซอร์วัดระยะ → บอร์ดแปลงเป็นระดับ 0–3 (น้ำน้อยระดับสูง) → จอแสดงระดับและส่งข้อมูลขึ้นเว็บ → ป้ายไฟที่ศาลาเปลี่ยนสี»","«จะสาธิต: ตักน้ำออกจากถังจนถึงเส้นเหลือง/แดงให้ดูระดับและไฟเปลี่ยน แล้วปิด Wi-Fi ให้ดูว่าจอที่กล่องยังแสดงระดับเอง»"]]]],["p","ข้อบกพร่องหรืออุปสรรคที่ฉันพบ 1 เรื่อง / ฉันลองแก้อย่างไร / ผลที่เกิด"],["t",[[["«(สมมติ) พบ: ตอนผิวน้ำเป็นคลื่นหลังตักน้ำ ค่าระยะกระโดด ทำให้ระดับสลับไปมา»","«ลอง: เพิ่ม samples จาก 5 เป็น 9 และรอ 10 วินาทีให้ผิวน้ำนิ่งก่อนอ่าน»","«ผลที่เกิด: (นักเรียนบันทึกผลจริงของกลุ่ม)»"]]]]]}]},"a6":{"pre":[["p","ภารกิจ : กำหนดเกณฑ์ความสำเร็จก่อนทดลอง ใช้สถานการณ์จำลองที่ปลอดภัย เก็บข้อเสนอแนะ ปรับต้นแบบ และทดสอบซ้ำ แล้วใช้ผลทั้งหมดสะท้อนผลงานและวิธีทำงานของตน พร้อมวางแผนพัฒนารอบถัดไป"]],"secs":[{"h":"1. วางแผนการทดลองสถานการณ์จำลอง","b":[["p","สถานการณ์จำลองที่ใช้ทดสอบ (เช่น น้ำป่าตอนกลางคืนโดยไม่มีอินเทอร์เน็ต) และผู้ทดลอง"],["t",[[["«สถานการณ์จำลอง: สระลดลงทีละน้อยในถังน้ำ 20 ลิตร (ตักน้ำออกทีละ 5 ซม.) ช่วงหนึ่งปิด Wi-Fi แทนการไม่มีเน็ต และอีกช่วงถอดสายเซนเซอร์แทนเซนเซอร์ดับ»","«ผู้ทดลอง: เพื่อนกลุ่มอื่น 2 คนรับบทผู้ดูแลประปา (ไม่รู้ล่วงหน้าว่าระดับจะลดถึงเท่าไรเมื่อไร) ครูเป็นผู้สังเกต»","«ความปลอดภัย: ใช้ไฟ 5 V บนโต๊ะ วางถังบนพื้นแห้ง ไม่ทดลองที่สระจริง ตั้งรอบวัดเป็น 5 วินาทีเฉพาะตอนทดสอบ (ค่าใช้จริง 1 ชั่วโมง) แล้วคืนค่าเดิม»"]]]],["t",[[["สิ่งที่จะวัด/สังเกต"],["เกณฑ์สำเร็จที่กำหนดไว้ก่อนทดสอบ"],["จะเก็บผลอย่างไร"]],[["1.« ระดับ 0–3 ที่จอบอร์ดและหน้าเว็บแสดง ตรงกับระดับที่คำนวณจากไม้บรรทัด»"],["«ตรงอย่างน้อย 5 ใน 6 จุดวัด (กลุ่มกำหนดเอง)»"],["«จดค่าไม้บรรทัด ค่าที่เว็บแสดง และระดับ 0–3 ลงตาราง 6 แถว»"]],[["2.« ผู้ดูแลรู้ว่าต้องทำอะไรเมื่ออ่านข้อความระดับ 2»"],["«ผู้ทดลอง 2 ใน 2 คน บอก 2 ข้อแรกที่ต้องทำได้ถูกภายใน 30 วินาที»"],["«ถามผู้ทดลองแล้วจดผลลงตาราง»"]]]]]},{"h":"2. ผลทดลองรอบที่ 1 ก่อนปรับปรุง","b":[["t",[[["เกณฑ์ทดสอบ"],["ผลที่เกิดจริง (ไม่แต่งข้อมูล)"],["ปัญหาหรือข้อจำกัด"]],[["1.« ระดับตรงกับไม้บรรทัด อย่างน้อย 5 ใน 6 จุด»"],["«(สมมติ) ตรง 4 ใน 6 จุด»"],["«2 จุดที่ตักน้ำใหม่ ๆ ผิวน้ำยังเป็นคลื่น ระดับสลับไปมา»"]],[["2.« ผู้ทดลองบอก 2 ข้อแรกที่ต้องทำได้ถูกใน 30 วินาที»"],["«(สมมติ) 1 ใน 2 คน อีกคนจับใจความไม่ได้ว่าต้องทำอะไรก่อน»"],["«ข้อความระดับ 2 มี 4 ข้อ และเน้นรดน้ำแปลงพืช ไม่ตรงกับน้ำกินน้ำใช้ของหมู่บ้าน»"]]]],["p","ข้อเสนอแนะจากเพื่อน/ครู/ผู้ทดลองใช้ 1–2 ข้อ (เขียนว่าใครเสนอเรื่องใด ไม่ต้องระบุข้อมูลส่วนตัว)"],["t",[[["«ผู้ทดลองคนที่ 1: อยากให้ข้อความเหลือเรื่องที่ต้องทำก่อน เช่น \"ลดการใช้น้ำที่ไม่จำเป็น\" ไม่ต้องยาว»","«ครู: ให้รอจนผิวน้ำนิ่งก่อนอ่านทุกจุด และข้อความต้องพูดถึงน้ำกินน้ำใช้ตามโจทย์ของหมู่บ้าน»","«(ตัวอย่างสมมติ — นักเรียนเขียนข้อเสนอแนะที่ได้จริง)»"]]]]]},{"h":"3. ปรับปรุงตามหลักฐานและทดสอบซ้ำ","b":[["p","ทดสอบซ้ำในสถานการณ์จำลองที่เทียบเคียงกับรอบแรก เช่น ผู้ทดลอง เหตุการณ์ ระยะทาง แหล่งข้อมูล และอุปกรณ์"],["t",[[["เกณฑ์ความสำเร็จเดิม"],["ผลรอบที่ 1"],["สิ่งที่แก้จริง + เหตุผล"],["ผลรอบที่ 2"],["ดีขึ้น/ยังไม่ดี เพราะอะไร"]],[["1.« ระดับตรงกับไม้บรรทัด อย่างน้อย 5 ใน 6 จุด»"],["«(สมมติ) ตรง 4 ใน 6 จุด»"],["«รอ 10 วินาทีก่อนอ่านทุกจุด + เพิ่ม samples เป็น 9»","«เหตุผล: ลดค่ากระโดดจากผิวน้ำเป็นคลื่น»"],["«(สมมติ) ตรง 6 ใน 6 จุด»"],["«ดีขึ้น แต่มีเพียง 6 จุดและยังเป็นถังเล็ก ต้องทดสอบซ้ำหลายรอบและกับสระจริง»"]],[["2.« ผู้ทดลองบอก 2 ข้อแรกที่ต้องทำได้ถูกใน 30 วินาที»"],["«(สมมติ) 1 ใน 2 คน»"],["«ตัดข้อความระดับ 2 เหลือ 2 ข้อแรก เขียนใหม่เป็นน้ำกินน้ำใช้»","«เหตุผล: ผู้ดูแลตัดสินใจเร็วขึ้น»"],["«(สมมติ) 2 ใน 2 คน»"],["«ดีขึ้น แต่ผู้ทดลองเป็นคนละคน จึงเทียบตรง ๆ ไม่ได้»"]]]],["p","มีเงื่อนไขใดไม่เหมือนเดิมระหว่างสองรอบหรือไม่? ถ้ามี ผลการเปรียบเทียบอาจคลาดเคลื่อนอย่างไร"],["t",[[["«ไม่เหมือนเดิม: ผู้ทดลองรอบ 2 เป็นคนละคน และระดับน้ำที่ตักออกในแต่ละจุดไม่เท่ากันทุกครั้ง»","«ผลกระทบ: ข้อสรุปว่า \"ดีขึ้น\" อาจมาจากผู้ทดลองหรือจังหวะน้ำนิ่ง ไม่ใช่การแก้ไข ต้องทดสอบซ้ำกับผู้ทดลองเดิมและจำนวนจุดที่มากขึ้น»"]]]]]},{"h":"4. สะท้อนคิดผลงานและกระบวนการของกลุ่ม","b":[["p","ใช้ผลทดสอบและข้อเสนอแนะเป็นหลักฐาน ไม่ใช้ความรู้สึกอย่างเดียว"],["t",[[["สิ่งที่สะท้อน"],["จุดแข็ง (พร้อมหลักฐาน)"],["จุดอ่อน (พร้อมหลักฐาน)"]],[["ผลงาน/ต้นแบบ"],["«จอที่กล่องแสดงระดับเองได้แม้ไม่มีเน็ต (หลักฐาน: ทดสอบปิด Wi-Fi)»","«หน้าเว็บอ่านง่ายบนมือถือ»"],["«ยังไม่ได้ทดสอบกับสระจริงและกลางแจ้งหลายสัปดาห์»","«เกณฑ์ระดับน้ำยังเป็นค่าสมมติ และระดับน้ำไม่ใช่ปริมาตรน้ำคงเหลือ»"]],[["กระบวนการสร้างสรรค์ของกลุ่ม (ใบกิจกรรม 1–5)"],["«เริ่มจากข่าวจริงและมองผู้ใช้หลายกลุ่ม (ใบ 1–2)»","«ผสานความคิดเพื่อนจนได้ป้ายไฟและตารางแบ่งน้ำ (ใบ 3)»"],["«ใบ 5 ทดสอบกับอุปกรณ์จริงน้อย เวลาไม่พอ»","«ไม่ได้ถามผู้ดูแลประปาหรือผู้สูงอายุตัวจริง»"]]]],["p","ต้นแบบช่วยป้องกัน ลดความเสี่ยง หรือสนับสนุนการเตรียมพร้อมของกลุ่มเป้าหมายได้อย่างไร (จากผลทดลองเท่านั้น)"],["t",[[["«จากผลทดลอง (สมมติ): ต้นแบบทำให้ผู้ทดลองเห็นระดับน้ำที่ลดลงและรู้ว่าต้องทำอะไรเร็วขึ้นในถังจำลอง แต่ยังสรุปไม่ได้ว่าลดความเสี่ยงขาดน้ำในหมู่บ้านจริง»","«ยืนยันได้จากผล: การแสดงระดับที่กล่องไม่ขึ้นกับเน็ต»","«ยังยืนยันไม่ได้: ว่าครัวเรือนประหยัดหรือกักน้ำทันจริง ต้องทดสอบกับผู้ดูแลประปาและชาวบ้านจริงโดยมีผู้ใหญ่ดูแล»"]]]],["p","สิ่งใด “ยังไม่ควรนำไปใช้จริง” และผู้ใช้ควรอ้างอิงข้อมูล/คำเตือนจากหน่วยงานใดในเหตุฉุกเฉิน"],["t",[[["«ยังไม่ควรใช้จริง: ตัวเลขเกณฑ์ระดับน้ำ การติดตั้งในสระชุมชน (ต้องขออนุญาต อบต./ผู้ดูแลประปา) และการใช้แทนประกาศภัยแล้งทางการ»","«ในช่วงแล้งให้ติดตามประกาศจาก ปภ. (สายด่วน 1784) เทศบาล/อบต. ผู้ใหญ่บ้าน และกรมชลประทาน/กรมอุตุนิยมวิทยา»"]]]],["p","ตั้งคำถามกับกระบวนการสร้างสรรค์ของเรา: ขั้นตอนใดที่เราเลือกทางง่ายเกินไปหรือน่าจะทำต่างออกไป เพราะอะไร"],["t",[[["«ที่เลือกทางง่าย: ใช้ถังน้ำในห้องแทนสระจริง และไม่ได้ถามผู้ดูแลประปาตัวจริง»","«ควรทำต่าง: ขอให้ครูพาไปพบผู้ใหญ่บ้าน/ผู้ดูแลประปา ถามระดับที่เคยวิกฤตและรูปทรงสระ ก่อนกำหนดระดับ»","«เพราะเกณฑ์น้ำและปริมาตรต้องมาจากคนในพื้นที่ ไม่ใช่ที่เรา (หรือ AI) เดา»"]]]]]}]}},"team":["กลุ่มที่ «2»  ·  ชื่อกลุ่ม «ทีมรักษ์น้ำ»  ·  ภัยที่เลือก «ภัยแล้ง»  ·","สมาชิก 1) «นักเรียน ก»  ·  2) «นักเรียน ข»  ·  3) «นักเรียน ค»  ·","4) «นักเรียน ง»  ·  5) «นักเรียน จ»  ·  วันที่ ........ / ........ / ........"]},"smoke":{"intro":["«ฉบับตัวอย่างเฉลยสำหรับครู — ภัยที่เลือก: ไฟป่า/หมอกควัน PM2.5 (จังหวัดอุตรดิตถ์)»","ข้อความสีน้ำเงินคือแนวตอบตัวอย่าง นักเรียนต้องคิดและเขียนด้วยตนเอง ไม่ควรคัดลอก ส่วนเกณฑ์ประเมินและตารางบันทึกระดับของครูเว้นว่างไว้ (ชื่อนักเรียน ก ข ค ง จ เป็นชื่อสมมติ)","ข้อมูลอ้างอิงข่าว: มติชน (28 ก.พ. 2566) จุดความร้อน 192 จุด • ฐานเศรษฐกิจ (7 เม.ย. 2569) PM2.5 66.5 µg/m³ • ไทยพีบีเอส (5 ก.ค. 2566) ตาราง AQI ข่าวไม่ระบุตำบลของไฟ/ฝุ่น จึงไม่สรุปแหล่งกำเนิด ตรวจเมื่อ 23–24 ต.ค. 2569","ข้อความขึ้นต้น \"(สมมติ)\" ในใบกิจกรรมที่ 5–6 เป็นตัวอย่างวิธีเขียนบันทึก ไม่ใช่ผลวัดจริง เกณฑ์ PM2.5 ใช้ช่วงตาราง AQI ไทย (เฉลี่ย 24 ชม.) ส่วนเกณฑ์จุดความร้อนเป็นค่าสมมติ","ต้นแบบ \"เพื่อนบ้านเตือนภัย\" (ชุดค่าหมอกควัน) ไม่ใช่ระบบเตือนภัยหรือคำแนะนำทางการแพทย์ เซนเซอร์ราคาประหยัดให้ค่าโดยประมาณ และกล่องส่งค่าเฉลี่ยประมาณ 30 นาที"],"acts":{"a1":{"pre":[["p","ภารกิจ : เลือกภัยธรรมชาติที่มีโอกาสเกิดหรือเคยเกิดขึ้นในจังหวัดอุตรดิตถ์ แล้วสืบค้นข้อมูลจากแหล่งที่เชื่อถือได้ เพื่อทำความเข้าใจความเสี่ยง โดยตั้งคำถามให้มากกว่าที่รู้ และกล้าตรวจสิ่งที่เคยเชื่อ ก่อนเสนอวิธีแก้"]],"secs":[{"h":"1. เลือกภัยและระบุบริบทพื้นที่","b":[["p","ใช้ข้อมูลจริงหรือสถานการณ์จำลองที่ครูกำหนด"],["p","☐ น้ำท่วม/น้ำป่า    ☐ ดินถล่ม    ☐ ภัยแล้ง    ☐ วาตภัย    «☒» ไฟป่า/หมอกควัน    ☐ อื่น ๆ ................."],["p","บริบทพื้นที่/สถานการณ์ที่กลุ่มสนใจ (เกิดที่ไหน เมื่อใด หรือมีเงื่อนไขอย่างไร)"],["t",[[["«27 ก.พ. 2566 ดาวเทียม Suomi NPP ตรวจพบจุดความร้อนในจังหวัดอุตรดิตถ์ 192 จุด ข่าวจัดเป็นอันดับ 3 รองจากกาญจนบุรี (688 จุด) และตาก (402 จุด) • 7 เม.ย. 2569 เวลา 07:00 น. PM2.5 ของอุตรดิตถ์ 66.5 µg/m³ เกินมาตรฐาน อยู่อันดับ 12 จาก 17 จังหวัดภาคเหนือที่เกินมาตรฐาน»","«ข้อสังเกต: ข่าวทั้งสองชิ้นไม่ได้ระบุว่าไฟหรือฝุ่นอยู่ตำบลใดของอุตรดิตถ์ จึงสรุปไม่ได้ว่าฝุ่นมาจากที่ใด — ใช้ได้เพียงว่า \"จังหวัดมีจุดความร้อนและฝุ่นสูงในช่วงนั้น\"»","«เงื่อนไขที่สนใจ: ครูต้องตัดสินใจตอนเช้าว่าจะให้เข้าแถวหรือเรียนพละกลางแจ้งหรือไม่ แต่ไม่มีค่าฝุ่นหน้าโรงเรียน และผู้ปกครองไม่รู้ว่าวันไหนควรให้ลูกใส่หน้ากาก — ใช้โรงเรียนสมมติ 1 แห่งในจังหวัดอุตรดิตถ์เป็นพื้นที่ทดลอง»"]]]]]},{"h":"2. รวบรวมข้อมูลและตรวจสอบความน่าเชื่อถือ","b":[["t",[[["แหล่งข้อมูล/หน่วยงาน","(ชื่อหรือ URL ย่อ)"],["ข้อมูลสำคัญที่พบ"],["ตรวจสอบได้อย่างไร / วันที่เข้าถึง"]],[["1.« มติชน»  ·","«ข่าวจุดความร้อน 27 ก.พ. 2566 (เผยแพร่ 28 ก.พ. 2566)»"],["«อุตรดิตถ์ 192 จุด อันดับ 3 รองจากกาญจนบุรี 688 จุด และตาก 402 จุด»","«ข้อมูลจากดาวเทียม Suomi NPP ที่ GISTDA รายงาน»"],["«เป็นข้อมูลวันเดียว เก่า (พ.ศ. 2566) และไม่ระบุตำบล ใช้ดูรูปแบบปัญหา ไม่ใช่สถานการณ์ปัจจุบัน»","«ลิงก์: matichon.co.th/local/news_3847836 เข้าถึง 24 ต.ค. 2569»"]],[["2.« ฐานเศรษฐกิจ»","«ข่าวสถานการณ์ฝุ่น PM2.5 7 เม.ย. 2569»"],["«PM2.5 ที่อุตรดิตถ์ 66.5 µg/m³ เวลา 07:00 น. เกินมาตรฐาน»","«อันดับ 12 จาก 17 จังหวัดภาคเหนือที่เกินมาตรฐาน»"],["«เป็นค่าเวลาเดียว ข่าวที่อ่านไม่ระบุสถานีวัด ต้องเทียบกับเว็บทางการ»","«ลิงก์: thansettakij.com/sustainable/environment/656010 เข้าถึง 24 ต.ค. 2569»"]],[["3.« ไทยพีบีเอส»","«ข่าวตาราง AQI ใหม่ 5 ก.ค. 2566»"],["«PM2.5 เฉลี่ย 24 ชม.: เหลือง 25.1–37.5 • ส้ม 37.6–75 • แดง 75.1 ขึ้นไป พร้อมคำแนะนำแต่ละสี»","«ข่าวรายงานว่าประกาศในราชกิจจานุเบกษา 3 ก.ค. 2566»"],["«เป็นสำนักข่าวที่สรุปประกาศทางการ ควรตรวจกับเว็บกรมควบคุมมลพิษซ้ำ»","«ลิงก์: thaipbs.or.th/news/content/329386 เข้าถึง 24 ต.ค. 2569»"]]]]]},{"h":"3. มองเหตุและผลให้รอบด้าน","b":[["t",[[["สาเหตุ/ปัจจัย (อย่างน้อย 2 ข้อ)"],["ผลกระทบต่อชีวิต ทรัพย์สิน ชุมชน หรือสิ่งแวดล้อม"]],[["1.« จุดความร้อนจำนวนมากในหน้าแล้ง (192 จุด เมื่อ 27 ก.พ. 2566) ทำให้มีฝุ่นเพิ่ม (ข้อสันนิษฐาน)»","«ข่าวไม่ได้บอกว่าฝุ่นของอุตรดิตถ์มาจากไฟที่ใด จึงไม่สรุปแหล่งกำเนิด»"],["1.« PM2.5 สูงเกินมาตรฐาน (66.5 µg/m³ เมื่อ 7 เม.ย. 2569) ตรงกับระดับส้มของตาราง AQI ใหม่»","«ระดับส้มคือเริ่มมีผลต่อสุขภาพ ควรสวมหน้ากากเมื่อออกนอกอาคารและเลี่ยงกิจกรรมหนักกลางแจ้งนาน (ไทยพีบีเอส)»"]],[["2.« โรงเรียนไม่มีเครื่องวัดฝุ่นของตัวเอง ครูจึงดูจากท้องฟ้าหรือข่าวทั่วไป (ข้อสันนิษฐาน ต้องไปถามครูเวร)»","«ค่าทางการเป็นของสถานีหรือจังหวัด ไม่ใช่หน้าโรงเรียน»"],["2.« นักเรียนอาจเข้าแถวหรือเรียนพละกลางแจ้งในวันที่ฝุ่นอยู่ระดับส้มขึ้นไป»","«ผู้ปกครองไม่รู้ว่าวันไหนควรให้ลูกใส่หน้ากาก (ข้อสันนิษฐาน ต้องสอบถาม)»"]]]]]},{"h":"4. ใครเสี่ยงอย่างไร? ลองมองจากมุมผู้ได้รับผลกระทบ","b":[["p","กลุ่มที่ 2 ให้เลือกกลุ่มที่กลุ่มเราไม่ค่อยคุ้นเคยหรือมักถูกมองข้าม (เช่น ผู้พิการ ผู้ป่วยติดเตียง เด็กเล็ก แรงงานย้ายถิ่น)"],["t",[[["ผู้ได้รับผลกระทบ"],["ความเสี่ยง/สิ่งที่กังวล"],["ความต้องการที่สำคัญ"]],[["กลุ่มที่ 1:« นักเรียนที่เข้าแถว เรียนพละ และพักกลางแจ้ง»","«(กลุ่มที่เรานึกถึงเป็นอันดับแรก โดยเฉพาะเด็กที่แพ้ฝุ่นหรือมีโรคทางเดินหายใจ)»"],["«ต้องอยู่กลางแจ้งตามตารางเรียน เลือกเองไม่ได้ว่าจะงดกิจกรรมหรือไม่»","«ถ้าฝุ่นระดับส้มขึ้นไป ตาราง AQI แนะนำให้เลี่ยงกิจกรรมหนักกลางแจ้งนานและสวมหน้ากาก»"],["«ให้ครูรู้ระดับฝุ่นก่อนเริ่มกิจกรรมเช้า และมีข้อตกลงว่าระดับไหนต้องทำอะไร»","«ธงหรือไฟสีที่เด็กเห็นเองได้ และข้อความถึงผู้ปกครอง»"]],[["กลุ่มที่ 2:« ครูเวรและครูพละ (ผู้ตัดสินใจ)»","«(กลุ่มที่มักถูกมองข้าม — สมมติฐานของกลุ่ม ต้องไปถามครูจริง)»"],["«ต้องตัดสินใจเรื่องกิจกรรมกลางแจ้งตอนเช้าโดยไม่มีตัวเลขหน้าโรงเรียน และอาจถูกผู้ปกครองถามว่าทำไมงด/ทำไมไม่งด»","«ต้องเปิดเว็บหรือแอปทางการเองทุกเช้า ซึ่งอาจลืมหรือเน็ตช้า»"],["«ตัวเลขและระดับสีที่ดูได้ภายใน 1 นาทีก่อนเข้าแถว»","«ข้อความสำเร็จรูปที่บอกว่าแต่ละระดับต้องทำอะไร ใช้อธิบายผู้ปกครองได้»"]]]],["p","เลือกกลุ่มเป้าหมายหลัก 1 กลุ่ม และบอกเหตุผลที่เลือก"],["t",[[["«กลุ่มเป้าหมายหลัก: นักเรียนที่ต้องเข้าแถว เรียนพละ และพักเที่ยงกลางแจ้ง โดยเฉพาะเด็กที่แพ้ฝุ่นหรือมีโรคทางเดินหายใจ»","«เหตุผล: เลือกไม่ได้ว่าจะอยู่กลางแจ้งหรือไม่ และเป็นกลุ่มที่ตาราง AQI ให้ระวังเป็นพิเศษ แต่ตัดสินใจเองไม่ได้ จึงต้องให้ครูและผู้ปกครองรู้ก่อน»","«คนที่ช่วยเขาได้คือครูเวรและผู้ปกครอง ต้นแบบจึงต้องส่งข้อความถึงทั้งสองกลุ่ม ส่วนกลุ่มที่ 2 (ครูเวร/ครูพละ) เป็นผู้ใช้ระบบโดยตรงที่ต้องมีข้อมูลก่อนเริ่มกิจกรรมทุกเช้า»"]]]]]},{"h":"5. สิ่งที่รู้แล้ว / ยังไม่รู้ / ต้องหาต่อ","b":[["t",[[["สิ่งที่รู้จากหลักฐาน"],["สิ่งที่ยังไม่รู้ (คำถามที่ยังไม่มีคำตอบ)"],["จะสืบค้นหรือถามใคร/ที่ใด"]],[["«PM2.5 ที่อุตรดิตถ์ 7 เม.ย. 2569 เวลา 07:00 น. เท่ากับ 66.5 µg/m³ เกินมาตรฐาน (ฐานเศรษฐกิจ)»","«ตาราง AQI ใหม่แบ่ง 5 สี ระดับส้ม 37.6–75 เริ่มมีผลต่อสุขภาพ (ไทยพีบีเอส 2566)»"],["«ค่าฝุ่นหน้าโรงเรียนเราต่างจากสถานีทางการของจังหวัดเท่าไร?»","«ปกติครูเวรดูค่าฝุ่นก่อนเข้าแถวหรือไม่ และดูจากที่ไหน?»"],["«เทียบค่าเซนเซอร์กับค่าทางการ 1–2 สัปดาห์ในช่วงเวลาเดียวกัน»","«ถามครูเวรและผู้บริหารว่าตอนนี้ตัดสินใจเรื่องกิจกรรมกลางแจ้งอย่างไร»"]],[["«จุดความร้อนในอุตรดิตถ์ 27 ก.พ. 2566 มี 192 จุด (มติชน) แต่ไม่ระบุตำบล»","«ข่าว 2 ชิ้นอายุต่างกัน ใช้ดูรูปแบบปัญหา ไม่ใช่สถานการณ์วันนี้»"],["«จุดความร้อนในรัศมี 10 กม. จากโรงเรียนวันนี้มีกี่จุด?»","«ผู้ปกครองรู้ไหมว่าระดับส้มควรใส่หน้ากาก และมีหน้ากากกรอง PM2.5 หรือยัง?»"],["«ให้อาสาดูจุดความร้อนจากเว็บของ GISTDA หรือหน่วยงานรัฐที่ครูแนะนำ แล้วกรอกค่า»","«ถามผู้ปกครองสัก 5 คน (ไม่จดชื่อ) ว่ารู้และมีหน้ากากหรือไม่»"]]]]]},{"h":"6. ตั้งคำถามสำรวจปัญหา","b":[["p","ต้องมีทั้ง “ทำไม...?” และ “ถ้า...จะเป็นอย่างไร?” เพื่อขยายมุมมอง เช่น “ทำไมผู้สูงอายุจึงอาจได้รับผลกระทบจากน้ำป่ามากกว่าคนวัยทำงาน” / “ถ้าเกิดน้ำป่าในเวลากลางคืนและไม่มีอินเทอร์เน็ต จะเป็นอย่างไร”"],["p","คำถามที่ 1 “ทำไม...?” และเหตุใดคำถามนี้จึงสำคัญ"],["t",[[["«ทำไมโรงเรียนจึงตัดสินใจเรื่องกิจกรรมกลางแจ้งตอนเช้าโดยไม่มีค่าฝุ่นหน้าโรงเรียน ทั้งที่ข่าวรายงานค่าฝุ่นของจังหวัดตั้งแต่ 07:00 น. แล้ว?»","«สำคัญเพราะถ้ารู้ว่าปัญหาคือไม่มีเครื่องวัด ไม่มีคนดูค่า หรือไม่มีข้อตกลงว่าแต่ละระดับทำอะไร จะออกแบบให้ข้อมูลถึงครูและผู้ปกครองก่อนเริ่มกิจกรรมได้ตรงจุด»"]]]],["p","คำถามที่ 2 “ถ้า...จะเป็นอย่างไร?” และเงื่อนไขใหม่ที่อยากสำรวจ"],["t",[[["«ถ้าท้องฟ้าดูโล่ง ไม่เห็นควันหนา แต่ PM2.5 อยู่ระดับส้ม ครูและผู้ปกครองจะรู้ได้อย่างไรว่าต้องงดกิจกรรมกลางแจ้งหรือใส่หน้ากาก?»","«เงื่อนไขใหม่ที่อยากสำรวจ: ครูเวรไม่มีเวลาเปิดแอป ผู้ปกครองไม่ได้อ่านไลน์กลุ่ม — ธงสีหน้าโรงเรียน ข้อความสั้นทุกเช้า หรือกล่องวัดฝุ่นอัตโนมัติ อย่างไหนช่วยได้?»"]]]]]},{"h":"7. ท้าทายสิ่งที่เคยเชื่อ","b":[["p","เขียนสิ่งที่เรา/คนทั่วไปเชื่อหรือทำเป็นปกติเมื่อเกิดภัยนี้ แล้วตรวจกับหลักฐานจากส่วนที่ 2"],["t",[[["สิ่งที่เคยเชื่อ/วิธีที่คุ้นเคย"],["ตรวจกับหลักฐานแล้วพบว่า (ตรง / ขัด / ยังไม่รู้)"],["ถ้าข้อสมมตินี้ใช้ไม่ได้ (เช่น ไฟดับ ไม่มีอินเทอร์เน็ต เกิดกลางคืน) จะเกิดอะไรขึ้น"]],[["1.« เคยเชื่อว่า \"ถ้าท้องฟ้าไม่ขุ่นมัว ก็ไม่มีฝุ่นที่เป็นอันตราย\"»"],["«ขัด: ตาราง AQI ใหม่จัดระดับด้วยตัวเลข PM2.5 (µg/m³) ไม่ได้ใช้ความขุ่นที่ตามองเห็น และระดับส้มเริ่มที่ 37.6 (ไทยพีบีเอส 2566)»"],["«สายตาบอกระดับฝุ่นไม่ได้ ต้องใช้ตัวเลขจากเครื่องวัดหรือเว็บทางการก่อนตัดสินใจเรื่องกิจกรรมกลางแจ้ง»"]],[["2.« เคยเชื่อว่า \"ฝุ่น PM2.5 เป็นปัญหาของเมืองใหญ่หรือภาคเหนือตอนบน ไม่ใช่ที่อุตรดิตถ์\"»"],["«ขัด: 7 เม.ย. 2569 อุตรดิตถ์ 66.5 µg/m³ เกินมาตรฐาน เป็น 1 ใน 17 จังหวัดภาคเหนือที่เกิน และ 27 ก.พ. 2566 มี 192 จุดความร้อน»"],["«โรงเรียนในอุตรดิตถ์ก็ต้องเฝ้าระวังช่วงหน้าแล้ง ไม่ควรรอให้เป็นข่าวก่อน»"]]]],["p","ข้อมูลหรือมุมมองที่ไม่คุ้นเคย หรือขัดกับที่เราคิด 1 เรื่อง — กลุ่มชะลอการตัดสินและสำรวจเพิ่มอย่างไรก่อนสรุป"],["t",[[["«ข้อมูลที่ขัดกับที่คิด: เดิมคิดว่าครูดูค่าจากเว็บทางการก็พอ แต่ข่าวรายงานเป็นค่าระดับจังหวัดเวลาเดียว ไม่ใช่ค่าหน้าโรงเรียนตอนเข้าแถว และผู้ปกครองอาจไม่ได้เปิดดูทุกเช้า (ข้อสันนิษฐาน ต้องถาม)»","«ชะลอการตัดสิน: ยังไม่สรุปว่าเครื่องวัดของเราแม่นกว่าค่าทางการ จะเทียบกับค่าทางการ 1–2 สัปดาห์ และถามครูเวรว่าตอนนี้ตัดสินใจอย่างไร»","«ผลที่ปรับความคิด: เปลี่ยนโจทย์จาก \"วัดฝุ่นให้แม่น\" เป็น \"ให้ครูและผู้ปกครองรู้ระดับและสิ่งที่ต้องทำก่อนกิจกรรมเช้า\" พร้อมแสดงค่าทางการคู่กันในหน้าเว็บ»"]]]]]}]},"a2":{"pre":[["p","ภารกิจ : นำข้อมูลจากใบกิจกรรมที่ 1 มากำหนดปัญหาที่เฉพาะเจาะจง มีผู้ใช้ชัดเจน แล้วสร้างโจทย์ออกแบบหลายแนวทางด้วยกลยุทธ์ที่ต่างกัน ก่อนเลือกโจทย์ที่แก้ได้ด้วยต้นแบบ"]],"secs":[{"h":"1. แยกสาเหตุ ปัญหาหลัก และผลกระทบ","b":[["t",[[["สาเหตุ (เหตุใดจึงเกิด)"],["ปัญหาหลัก (สิ่งที่ต้องแก้)"],["ผลกระทบ (สิ่งที่ตามมา)"]],[["«ไม่มีเครื่องวัดฝุ่นหน้าโรงเรียน ครูตัดสินใจจากท้องฟ้าหรือข่าวทั่วไป (ข้อสันนิษฐาน ต้องถามครูเวร)»","«ค่าฝุ่นทางการเป็นของสถานีหรือจังหวัด ไม่ใช่หน้าโรงเรียน»"],["«ครูและผู้ปกครองไม่รู้ระดับฝุ่นก่อนเริ่มกิจกรรมเช้า»","«ไม่มีข้อตกลงว่าระดับไหนต้องงดกิจกรรมหรือใส่หน้ากาก»"],["«เด็กอาจเข้าแถวหรือเรียนพละกลางแจ้งในวันที่ฝุ่นอยู่ระดับส้มขึ้นไป»","«เด็กที่แพ้ฝุ่นหรือมีโรคทางเดินหายใจเสี่ยงมากกว่า»"]],[["«หน้าแล้งมีจุดความร้อนมาก (192 จุด 27 ก.พ. 2566) และฝุ่นเกินมาตรฐาน (66.5 µg/m³ 7 เม.ย. 2569)»","«ข่าวฝุ่นที่พบอยู่ในช่วง ก.พ.–เม.ย. (2566 2569)»"],["«ข้อมูลทางการอยู่ในเว็บ ต้องมีคนเปิดดูเอง ไม่ถึงผู้ปกครองโดยอัตโนมัติ»","«ไม่มีวิธีบอกคนที่ไม่ใช้เว็บหรือแอป»"],["«ผู้ปกครองไม่รู้ว่าวันไหนควรให้ลูกใส่หน้ากาก (ข้อสันนิษฐาน ต้องสอบถาม)»","«ครูพละไม่มีเกณฑ์ที่ตกลงกัน ตัดสินใจยากและอาจถูกวิจารณ์»"]]]],["p","จากข้อมูลข้างต้น กลุ่มต้องการแก้ “ปัญหาหลัก” เรื่องใดเพียง 1 เรื่อง เหตุใดจึงสำคัญ และขอบเขตของปัญหาอยู่ตรงไหน (เกิดที่ใด/กับใคร/เมื่อใด)"],["t",[[["«ปัญหาหลัก: นักเรียนที่เข้าแถวและเรียนพละกลางแจ้งอาจอยู่ในวันที่ฝุ่นระดับส้มขึ้นไป เพราะครูและผู้ปกครองไม่รู้ค่าฝุ่นหน้าโรงเรียนก่อนเริ่มกิจกรรมเช้า และไม่มีข้อตกลงว่าแต่ละระดับต้องทำอะไร»","«สำคัญเพราะ: ระดับฝุ่นดูด้วยตาไม่ได้ ถ้าไม่มีตัวเลขก็ตัดสินใจจากความรู้สึก และเด็กเลือกเองไม่ได้»","«ขอบเขต: โรงเรียนสมมติ 1 แห่งในจังหวัดอุตรดิตถ์ ช่วงหน้าแล้ง ทดลองกับเซนเซอร์หน้าอาคารหรือโหมดจำลอง ไม่ใช่ระบบเตือนภัยทางการและไม่ใช่คำแนะนำทางการแพทย์»"]]]]]},{"h":"2. รู้จักผู้ใช้และมองปัญหาจากหลายมุม","b":[["t",[[["คำถาม"],["คำตอบกลุ่มพร้อมหลักฐานจากใบกิจกรรมที่ 1"]],[["ผู้ที่ต้องการช่วยคือใคร?"],["«นักเรียนที่เข้าแถว เรียนพละ พักกลางแจ้ง (โดยเฉพาะเด็กแพ้ฝุ่น) กับครูเวร/ครูพละและผู้ปกครองที่ต้องตัดสินใจและรับข้อมูล (ผู้ใช้ระบบโดยตรงคือครูเวรและผู้ปกครอง)»"]],[["ประสบปัญหาเมื่อใด/สถานการณ์ใด?"],["«ช่วงเช้าก่อนเข้าแถว ในหน้าแล้งช่วง ก.พ.–เม.ย. เมื่อฝุ่นสูง (เช่น 7 เม.ย. 2569 เวลา 07:00 น. PM2.5 66.5 µg/m³)»"]],[["ต้องการความช่วยเหลือแบบใด?"],["«ครูรู้ระดับฝุ่นและสิ่งที่ควรทำก่อนเริ่มกิจกรรม ผู้ปกครองได้ข้อความสั้นทุกเช้า เด็กเห็นสีไฟหน้าโรงเรียนและงดกิจกรรมหนักเมื่อถึงระดับที่ตกลงกัน»"]]]],["p","มองปัญหาจากมุมอื่นอย่างน้อย 2 มุม เช่น ชุมชน/วัฒนธรรม เศรษฐกิจ/ค่าใช้จ่าย ความปลอดภัย/จริยธรรม หน่วยงานที่เกี่ยวข้อง"],["t",[[["มุมมอง"],["เห็นปัญหานี้อย่างไร และต้องการอะไร"]],[["มุมมองที่ 1:« ผู้ปกครองนักเรียน»"],["«กังวลสุขภาพลูก แต่ไม่อยากถูกแจ้งทุกวันจนรำคาญ และไม่อยากได้ข้อความที่ทำให้ตกใจเกินจริง»","«ต้องการข้อความสั้นที่บอกชัดว่าวันนี้ต้องทำอะไร เช่น ใส่หน้ากาก»"]],[["มุมมองที่ 2:« ผู้บริหารและงบประมาณโรงเรียน»"],["«งบน้อย ต้องการอุปกรณ์ราคาไม่สูง และไม่อยากให้ถูกเข้าใจว่าโรงเรียนประกาศสถานการณ์ฝุ่นแทนหน่วยงานรัฐ»","«ต้องขออนุญาตก่อนส่งข้อความเข้ากลุ่มผู้ปกครอง และไม่เปิดเผยข้อมูลส่วนตัวนักเรียน»"]]]]]},{"h":"3. เขียนข้อความกำหนดปัญหา (Problem Statement)","b":[["p","รูปประโยคช่วยคิด : “(กลุ่มเป้าหมาย) ประสบปัญหา (ปัญหา) เมื่อ (สถานการณ์) เนื่องจาก (สาเหตุหรือข้อจำกัด) ส่งผลให้ (ผลกระทบ)”"],["p","ข้อความกำหนดปัญหาของกลุ่ม (เขียนให้เจาะจง ไม่ใช่แค่ชื่อภัย)"],["t",[[["«นักเรียนที่เข้าแถวและเรียนพละกลางแจ้งในโรงเรียนสมมติ จ.อุตรดิตถ์ ประสบปัญหาอยู่กลางแจ้งโดยครูและผู้ปกครองไม่รู้ระดับ PM2.5 หน้าโรงเรียนก่อนเริ่มกิจกรรมเช้า เมื่อฝุ่นสูงในหน้าแล้ง เนื่องจากไม่มีเครื่องวัดหน้าโรงเรียน ค่าทางการต้องเปิดดูเองและไม่มีข้อตกลงว่าแต่ละระดับต้องทำอะไร ส่งผลให้เด็กอาจได้รับฝุ่นระดับส้มขึ้นไปโดยไม่ได้ป้องกัน»","«ตรวจความเฉพาะเจาะจง: มีกลุ่มเป้าหมาย สถานการณ์ สาเหตุ และผลกระทบครบ ไม่ใช่แค่คำว่า \"ฝุ่นพิษ\"»"]]]]]},{"h":"4. สร้างโจทย์ออกแบบหลายแนวทาง (How Might We...?)","b":[["p","รูปประโยคช่วยคิด : “เราจะออกแบบหรือพัฒนาอะไร เพื่อให้ (ใคร) สามารถ (ทำอะไรเพื่อลดความเสี่ยง) ภายใต้ (เงื่อนไข) ได้อย่างไร?”"],["t",[[["«เราจะออกแบบธงฝุ่นโรงเรียนราคาประหยัดที่ ม.2 ทำได้ เพื่อให้ครูเวรและผู้ปกครองรู้ระดับ PM2.5 ก่อนเริ่มกิจกรรมเช้าทุกวันและรู้ว่าต้องทำอะไรในแต่ละระดับ ภายใต้เงื่อนไขที่ไม่มีใครมีเวลาเปิดแอป และเซนเซอร์ราคาประหยัดอาจอ่านต่างจากสถานีทางการ ได้อย่างไร?»","«โจทย์ทางเลือกจากกลยุทธ์ต่างกัน: (เทคโนโลยี) ทำให้หน้าโรงเรียนวัดฝุ่นเองและแจ้งอัตโนมัติได้อย่างไร • (คน) ทำให้ครูเวรและผู้ปกครองมีข้อตกลงเดียวกันว่าระดับไหนทำอะไรได้อย่างไร • (ประสาทสัมผัส) บอกระดับฝุ่นด้วยสีที่เด็กเห็นจากสนามโดยไม่ต้องอ่านตัวเลขได้อย่างไร»"]]]]]},{"h":"5. สืบค้นเชิงสร้างสรรค์ : เรียนรู้จากวิธีของผู้อื่น","b":[["p","หาวิธีหรือนวัตกรรมที่ผู้อื่นใช้กับปัญหาคล้ายกัน (ภัยอื่น พื้นที่อื่น หรือกลุ่มผู้ใช้อื่น) จากแหล่งที่เชื่อถือได้ แล้วเทียบกับปัญหาของเรา"],["t",[[["วิธี/แนวทางของผู้อื่น (ที่มา)"],["ปัญหา สถานการณ์ หรือความต้องการของเขาเหมือน/ต่างจากของเราอย่างไร"],["แนวคิดที่นำมาใช้ตั้งหรือปรับโจทย์ของเรา"]],[["1.« ตาราง AQI 5 สีของกรมควบคุมมลพิษ ฟ้า เขียว เหลือง ส้ม แดง พร้อมคำแนะนำแต่ละสีสำหรับประชาชนทั่วไปและกลุ่มเสี่ยง»","«(ข่าวไทยพีบีเอส 5 ก.ค. 2566)»"],["«เหมือน: ปัญหาเดียวกัน ต้องบอกระดับฝุ่นให้คนเข้าใจเร็ว»","«ต่าง: เป็นข้อมูลระดับสถานีหรือจังหวัดสำหรับประชาชนทั่วไป ไม่ใช่หน้าโรงเรียนและไม่ส่งถึงผู้ปกครองเอง»"],["«ใช้ช่วงสีและคำแนะนำเดียวกับตารางทางการ แต่ทำเป็นไฟหน้าโรงเรียนและข้อความถึงผู้ปกครอง ไม่เปลี่ยนเกณฑ์เอง»"]],[["2.« ไฟจราจร เขียว เหลือง แดง ที่คนเข้าใจทันทีโดยไม่ต้องอ่านตัวเลข»","«(ความรู้ทั่วไป ไม่มีลิงก์ — ยังไม่ได้ตรวจกับแหล่งใด)»"],["«ต่างภัย แต่ปัญหาคล้ายกัน: ต้องให้คนตัดสินใจทำหรือไม่ทำภายในไม่กี่วินาที»","«ต่าง: AQI มี 5 สี แต่ไฟ 3 ดวงแสดงได้น้อยกว่า ระดับส้มจึงต้องแยกด้วยการกะพริบและป้ายอธิบาย»"],["«นำมาทำไฟ 3 ดวงและระดับ 0–3 โดยให้ \"ส้ม = แดงกะพริบช้า\" และ \"แดง = แดงกะพริบเร็ว\" พร้อมป้ายอธิบายข้างโคม»"]]]],["p","ตั้งคำถาม “ถ้า...จะเป็นอย่างไร?” 1 ข้อ แล้วลองตอบ — คำตอบทำให้เข้าใจปัญหาลึกขึ้น หรือทำให้ได้ทางแก้ใหม่อย่างไร"],["t",[[["«ถ้าเซนเซอร์ฝุ่นพังหรือเงียบไป ไฟหน้าโรงเรียนจะแสดงสีเขียว (อากาศดี) หรือไม่?»","«คำตอบ: ไม่ควรแสดงเขียว เพราะ \"ไม่มีตัวเลข ไม่เท่ากับ อากาศดี\" ระบบต้องแสดง \"ไม่มีข้อมูล\" และให้ครูเปิดค่าจากเว็บทางการแล้วกรอกด้วยมือแทน»","«ผล: ได้โจทย์ใหม่ — ต้องมีช่องให้ครูเวรกรอกค่าทางการด้วยมือเมื่อเซนเซอร์ดับ และไฟสถานะต้องแยกจากสีเขียว»"]]]]]},{"h":"6. ตรวจความชัดเจนและปรับกรอบโจทย์ (Reframe)","b":[["p","«☒» ระบุผู้ใช้ชัด    «☒» ช่วยลดความเสี่ยงจริง    «☒» ขอบเขตพอดีกับ 15 ชั่วโมง    «☒» ทำต้นแบบจำลองได้    «☒» ไม่อันตราย"],["p","โจทย์ก่อนรับข้อเสนอแนะ / ใครเสนอให้มองต่าง / โจทย์หลังปรับ / ข้อมูลหรือเหตุผลที่ยืนยันว่าดีขึ้น"],["t",[[["«โจทย์ก่อนรับข้อเสนอแนะ: \"ทำเว็บแสดงค่าฝุ่นโรงเรียน\"»","«ข้อเสนอแนะ (เพื่อนกลุ่มอื่นและครู): เว็บอย่างเดียวเด็กและผู้ปกครองไม่เปิดดู ต้องบอกด้วยว่าแต่ละระดับต้องทำอะไร และถ้าเซนเซอร์ดับจะไม่มีใครรู้ว่าฝุ่นเท่าไร»","«โจทย์หลังปรับ: ทำธงฝุ่นโรงเรียน — กล่องวัดใต้ชายคา ไฟ 3 ดวงหน้าโรงเรียน ข้อความสั้นถึงผู้ปกครองที่บอกว่าแต่ละระดับต้องทำอะไร และมีช่องให้ครูกรอกค่าทางการด้วยมือเมื่อเซนเซอร์ดับ»","«เหตุผลที่ดีขึ้น: ตรงกับคำถาม \"ถ้าท้องฟ้าโล่งแต่ฝุ่นระดับส้ม\" และข่าว 7 เม.ย. 2569 ที่ค่าเกินมาตรฐานตั้งแต่ 07:00 น.»"]]]]]}]},"a3":{"pre":[["p","ภารกิจ : ต้องคิดเองก่อนใช้ AI จากนั้นแลกเปลี่ยนกับเพื่อนและใช้ AI เพื่อขยาย/ตรวจสอบ ไม่ใช่คัดลอกคำตอบโดยไม่คิด ใบกิจกรรมนี้ดูว่าเราทำงานกับความคิดของผู้อื่นอย่างไร ตั้งแต่เปรียบเทียบ ผสาน ต่อยอด จนสังเคราะห์"]],"secs":[{"h":"1. คิดด้วยตนเองก่อนเปิด AI","b":[["p","ทุกคนกรอกบัตรรายบุคคล 3 แนวคิดต่างกลไก (หน้าถัดไป) ก่อนเปิด AI และก่อนแลกเปลี่ยนความคิดกับเพื่อน บัตรนี้คือ “ความคิดของฉัน” ที่จะใช้เปรียบเทียบและผสานกับผู้อื่นในส่วนที่ 2–5"],["p","«☒» สมาชิกทุกคนส่งบัตรก่อนเปิด AI ครบแล้ว"],["p","ลำดับการทำงานในใบกิจกรรมนี้"],["t",[[["ส่วน"],["ทำอะไร"],["ทำกับใคร / ใช้อะไร"]],[["1"],["คิดเอง 3 แนวทางลงบัตรรายบุคคล"],["ทำคนเดียว ก่อนเปิด AI"]],[["2"],["เปรียบเทียบความคิดของเรากับความคิดของเพื่อน"],["ฟังและบันทึกร่วมกันในกลุ่ม"]],[["3"],["ผสานส่วนที่ดีของเพื่อนอย่างน้อย 2 คนเข้ากับความคิดของเรา"],["สมาชิกในกลุ่ม"]],[["4"],["ต่อยอดกับเพื่อนและ AI แล้วตรวจสอบก่อนนำไปใช้"],["กลุ่ม + AI (มนุษย์เป็นผู้ตรวจและเลือก)"]],[["5"],["สังเคราะห์เป็น 3 แนวคิดที่แตกต่างกันจริงของกลุ่ม"],["ทั้งกลุ่ม"]]]],["sh","บัตรคิดเองก่อนใช้ AI (รายบุคคล)"],["p","ให้บันทึกก่อนเปิด AI / ก่อนแลกเปลี่ยนข้อเสนอของ AI เพื่อเก็บ “ความคิดของฉัน” ไว้เป็นฐานสำหรับเปรียบเทียบและผสานกับความคิดของผู้อื่น"],["p","ชื่อ–สกุล «นักเรียน จ (ตัวอย่าง)»  ·  ห้อง   ·  เลขที่   ·  กลุ่ม «3»  ·"],["p","โจทย์ภัยธรรมชาติที่ต้องการแก้ «ให้ครูและผู้ปกครองรู้ระดับฝุ่นก่อนเข้าแถว»  ·"],["p","คิดเอง 3 แนวทาง โดยพยายามให้กลไกช่วยลดความเสี่ยงต่างกัน"],["p","เขียนชื่อวิธี หลักการทำงาน ผู้ใช้ และเหตุผลที่คาดว่าจะช่วยแก้ปัญหาได้"],["p","แนวคิดที่ 1: ชื่อวิธี / ทำงานอย่างไร / ช่วยใคร / เหตุผล (เขียนโดยไม่ใช้ AI)"],["t",[[["«ชื่อวิธี: ธงฝุ่นหลายสีที่ครูเวรชักตามค่าจากเว็บทางการทุกเช้า แล้วติดป้ายอธิบายสี»","«ช่วยใคร: ครู นักเรียน ผู้ปกครอง • เหตุผล: ไม่ใช้ไฟฟ้าหรือเน็ต แต่ต้องมีคนชักธงทุกวัน»"]]]],["p","แนวคิดที่ 2: ชื่อวิธี / ทำงานอย่างไร / ช่วยใคร / เหตุผล (เขียนโดยไม่ใช้ AI)"],["t",[[["«ชื่อวิธี: กล่องวัดฝุ่นอัตโนมัติ — เซนเซอร์ PMS5003 ใต้ชายคา วัดทุก 5 นาที แสดงระดับบนจอที่กล่องและส่งขึ้นเว็บ»","«ช่วยใคร: ครูเวรและผู้ปกครอง • เหตุผล: เห็นค่าหน้าโรงเรียนจริงโดยไม่ต้องเปิดแอป ใช้พาวเวอร์แบงก์ 5 V ได้»"]]]],["p","แนวคิดที่ 3: ชื่อวิธี / ทำงานอย่างไร / ช่วยใคร / เหตุผล (เขียนโดยไม่ใช้ AI)"],["t",[[["«ชื่อวิธี: แผนกิจกรรมในร่มคู่ธง — ฝุ่นถึงระดับส้ม ครูพละย้ายเรียนเข้าอาคาร เด็กกลุ่มเสี่ยงไม่ออกแดดตอนพัก»","«ช่วยใคร: เด็กแพ้ฝุ่น/โรคทางเดินหายใจ • เหตุผล: มีที่ให้ไปแม้เครื่องวัดหรือธงใช้ไม่ได้»"]]]],["p","แนวคิดทั้ง 3 ต่างกันตรงหลักการทำงานหรือวิธีช่วยผู้ใช้อย่างไร (ไม่ใช่แค่ชื่อหรือสี)"],["t",[[["«ต่างที่กลไก: (1) คนอ่านค่าทางการแล้วชักธง ไม่ใช้ไฟฟ้า (2) เครื่องวัดหน้าโรงเรียนเห็นการขึ้นลง (3) ข้อตกลงและแผนในร่มที่บอกว่าต้องทำอะไร»","«แต่ละแบบแก้จุดอ่อนของอีกแบบ: (1) ต้องมีคนเปิดค่าทุกเช้า (2) บอกแค่ระดับ ไม่บอกว่าต้องทำอะไร (3) ต้องรู้ระดับก่อนจึงเริ่มใช้แผน»"]]]],["p","ฉันเริ่มคิดเวลา «09.10»  ส่งบัตรนี้เวลา «09.30»   «☒» ก่อนเปิด AI    ☐ ก่อนอ่านคำตอบจาก AI"],["p","หมายเหตุ: นักเรียนทุกคนต้องคิดด้วยตนเอง 3 แนวทางที่พยายามใช้กลไกช่วยลดความเสี่ยงแตกต่างกันก่อนใช้ AI ทั้งนี้จำนวนแนวคิดเป็นเพียงเงื่อนไขให้มีหลักฐานเพียงพอ ไม่ใช้จำนวนแนวคิดเพียงอย่างเดียวตัดสินความสร้างสรรค์"]]},{"h":"2. เปรียบเทียบความคิดของเรากับความคิดของเพื่อน","b":[["p","สมาชิกแต่ละคนเล่าแนวคิดที่ตนชอบที่สุด 1 ข้อ ทุกคนฟังให้ครบ แล้วบันทึกว่าเหมือนหรือต่างจากความคิดของตนเองอย่างไร"],["t",[[["สมาชิก/ผู้เสนอ"],["ข้อเสนอ (สรุปสั้น)"],["เหมือน/ต่างจากความคิดของฉันอย่างไร"],["สิ่งที่กลุ่มเห็นว่าน่าสนใจ"]],[["1.« ก»  ·"],["«ส่งข้อความสั้นถึงผู้ปกครองทุกเช้า 06:30 น. บอกระดับฝุ่นและสิ่งที่ควรทำ»"],["«เหมือน: ใช้ค่า PM2.5 ต่าง: ของ ก ส่งถึงผู้ปกครอง ของฉันแสดงที่โรงเรียนและต้องมีคนดู»"],["«ผู้ปกครองเตรียมหน้ากากก่อนมาโรงเรียนได้»"]],[["2.« ข»  ·"],["«ไฟ 3 ดวงหน้าโรงเรียน เขียว เหลือง แดงกะพริบ มองเห็นจากสนาม»"],["«เหมือน: บอกด้วยสี ต่าง: ของ ข อยู่หน้าโรงเรียนให้ทุกคนเห็น ของฉันต้องเดินไปดูจอที่กล่อง»"],["«เด็กและครูเห็นระดับโดยไม่ต้องอ่านตัวเลข»"]],[["3.« ค»  ·"],["«ตารางสิ่งที่ต้องทำในแต่ละระดับ ติดหน้าห้องพละ เช่น ส้ม = พละในร่ม»"],["«ต่างมาก: ไม่ใช้เทคโนโลยี แต่ใช้ร่วมกับของฉันได้เมื่อรู้ระดับ»"],["«ครูพละมีเกณฑ์ตรงกัน และใช้คำแนะนำจากตาราง AQI ทางการอ้างอิงได้»"]],[["4.« ง»  ·"],["«อาสานักเรียนดูจุดความร้อนในรัศมี 10 กม. จากเว็บ GISTDA หรือหน่วยงานรัฐ เช้าและบ่าย แล้วกรอกในเว็บของเรา»"],["«ต่าง: ดูไฟ ไม่ได้วัดฝุ่นโดยตรง แต่เป็นสัญญาณล่วงหน้า ของฉันวัดฝุ่นจริงหน้าโรงเรียน»"],["«เตือนล่วงหน้าได้ และใช้เป็นข้อมูลเสริมเมื่อเซนเซอร์ดับ»"]],[["5.  ·","​"],["​","​"],["​","​"],["​","​"]]]],["p","จุดร่วมและจุดต่างที่เห็นเด่นที่สุดในข้อเสนอของสมาชิกทั้งหมด"],["t",[[["«จุดร่วม: ทุกคนต้องการให้ \"รู้ก่อนเข้าแถว และรู้ว่าต้องทำอะไร\" ไม่ตัดสินจากสายตา»","«จุดต่าง: ช่องทางที่ใช้ (ธง ไฟ ข้อความ ตาราง) และพึ่งไฟฟ้า/เน็ตหรือไม่ ยังไม่มีใครคิดว่าถ้าเซนเซอร์ดับหรืออ่านต่างจากสถานีทางการจะทำอย่างไร»"]]]]]},{"h":"3. ผสานความคิดของสมาชิก","b":[["p","เลือกส่วนที่ดีของข้อเสนอจากสมาชิกอย่างน้อย 2 คน มาผสานกับความคิดของตนเอง"],["t",[[["เจ้าของแนวคิดที่ 1 + ส่วนที่เลือก"],["เจ้าของแนวคิดที่ 2 + ส่วนที่เลือก"],["เจ้าของแนวคิดที่ 3 + ส่วนที่เลือก"]],[["ชื่อ« ก»  ·","ส่วนที่เลือก« ส่งข้อความถึงผู้ปกครองทุกเช้า»","«เหตุผล: ผู้ปกครองไม่ต้องเปิดแอป»","«ปรับ: ส่งเช้าวันละครั้งและเมื่อระดับขึ้น ไม่ส่งรัว ๆ»"],["ชื่อ« ข»  ·","ส่วนที่เลือก« ไฟ 3 ดวงหน้าโรงเรียน»","«เหตุผล: เด็กและครูเห็นจากสนาม»","«ปรับ: ติดป้ายอธิบายสี เพราะส้มแสดงเป็นแดงกะพริบช้า»"],["ชื่อ« ค»  ·","ส่วนที่เลือก« ตารางสิ่งที่ต้องทำแต่ละระดับ»","«เหตุผล: ครูตัดสินใจตรงกัน»","«ปรับ: อ้างตาราง AQI ทางการ ไม่เขียนคำแนะนำทางการแพทย์เอง»"]]]],["p","ความคิดใหม่ที่เกิดจากการผสาน — ส่วนใดของเพื่อนอย่างน้อย 2 คนที่นำมาผสานกับความคิดของเรา และผลเป็นอย่างไร"],["t",[[["«ความคิดใหม่: \"ธงฝุ่นโรงเรียน\" = กล่องวัดฝุ่นหน้าอาคาร (ของฉัน) + ข้อความถึงผู้ปกครอง (ของ ก) + ไฟ 3 ดวงหน้าโรงเรียน (ของ ข)»","«ผลที่ได้: ครูเห็นระดับก่อนเข้าแถว ผู้ปกครองได้ข้อความ เด็กเห็นไฟ ถ้าเน็ตหลุด กล่องยังแสดงระดับบนจอเอง และไฟสลับสีบอกว่า \"ไม่มีข้อมูล\"»","«ส่วนของ ค (ตาราง) ใส่เป็นข้อความ \"สิ่งที่ควรทำ\" ในทุกระดับ ส่วนของ ง (จุดความร้อน) เป็นช่องที่อาสากรอกเอง»"]]]]]},{"h":"4. ต่อยอดกับเพื่อนและ AI","b":[["p","AI เป็นอีกแหล่งข้อเสนอหนึ่ง กลุ่มต้องเป็นผู้ตรวจและเลือก Prompt ต้องระบุปัญหา ผู้ใช้ ข้อจำกัด (เช่น ไม่มีไฟ/ไม่มีเน็ต) และขอทางเลือกที่ ม.2 ทำต้นแบบได้"],["p","Prompt ที่ใช้จริง (ไม่เขียนข้อมูลส่วนบุคคลหรือข้อมูลอ่อนไหว)"],["t",[[["«ฉันเป็นนักเรียน ม.2 ในจังหวัดอุตรดิตถ์ กำลังทำต้นแบบ \"ธงฝุ่นโรงเรียน\" บอกครูเวรและผู้ปกครองว่าวันนี้ควรทำกิจกรรมกลางแจ้งหรือไม่ ผู้ใช้คือครูเวรและผู้ปกครอง»","«ข้อจำกัด: ไม่มีเครื่องวัดมาตรฐาน งบจำกัด ใช้บอร์ด IPST-WiFi (ESP32) ที่โรงเรียนมี เซนเซอร์ราคาประหยัดอาจอ่านต่างจากสถานีทางการ»","«ขอทางเลือก 5 แนวทางที่ ม.2 ทำเป็นต้นแบบจำลองได้ พร้อมข้อควรระวังด้านความปลอดภัยและข้อมูลส่วนตัว (ไม่ใส่ชื่อนักเรียนหรือผู้ปกครอง)»"]]]],["t",[[["ข้อเสนอที่ AI ให้"],["เหตุผลรับ/ไม่รับ (ความปลอดภัย–ผู้ใช้–ทรัพยากร)"],["ตรวจสอบหรือปรับด้วยตนเอง/ร่วมกับเพื่อน"]],[["1.« แสดงค่าทางการคู่กับค่าของเรา และเทียบค่าเซนเซอร์กับค่าทางการทุกวัน»"],["«รับ: ตรงกับข้อจำกัดว่าเซนเซอร์อาจอ่านต่าง และได้ฝึกอ่านข้อมูล»"],["«จดค่าเซนเซอร์และค่าทางการเวลาเดียวกัน 1 สัปดาห์ ทำตารางผลต่าง (กลุ่มกำหนดเองว่ายอมให้ต่างได้เท่าไร)»"]],[["2.« ทดสอบเซนเซอร์ด้วยการจุดธูปหรือสร้างควันในห้องเรียน»"],["«ไม่รับ: อันตรายต่อสุขภาพและเสี่ยงไฟไหม้ ห้ามจุดไฟในห้องปิด»"],["«ใช้โหมดจำลองแทน หรือให้ครูเป็นผู้ทดสอบในที่โล่งอากาศถ่ายเท นักเรียนไม่สัมผัสควัน»"]]]],["p","AI ช่วยตรงไหน? เราคัดทิ้ง/แก้ไขอะไรเพราะเหตุใด และใช้แหล่งใดตรวจสอบคำแนะนำที่เกี่ยวกับภัย"],["t",[[["«AI ช่วย: เสนอให้แสดงค่าทางการคู่กับค่าของเรา และช่วยร่างข้อความแจ้งระดับ 4 ระดับ»","«เราคัดทิ้ง: คำแนะนำสุขภาพเฉพาะบุคคลที่ AI ให้มา (เช่น เรื่องยา) เพราะไม่ใช่คำแนะนำทางการแพทย์ที่ตรวจสอบได้ และการทดสอบด้วยควันจริง»","«ตรวจสอบกับ: ตาราง AQI ของกรมควบคุมมลพิษ ครู พยาบาลโรงเรียน/สถานีอนามัย และ ปภ. (1784) หากไฟลามใกล้ชุมชนโทร 199»"]]]],["p","ผังที่มาของความคิดใหม่ — เชื่อมความคิดของเพื่อน/AI เข้ากับความคิดของเรา"],["t",[[["ความคิดตั้งต้น (ของใคร)"],["ส่วนที่ต่อยอดจากเพื่อน/AI"],["ข้อค้นพบหรือมุมมองใหม่ที่เกิดขึ้น"],["ต่างจากข้อเสนอเดิมอย่างไร"]],[["«ของฉัน: กล่องวัดฝุ่นหน้าอาคาร แสดงระดับเองไม่พึ่งเน็ต»"],["«จาก ก: ข้อความถึงผู้ปกครอง»","«จาก ข: ไฟ 3 ดวงหน้าโรงเรียน»"],["«แสดงผล 3 ชั้น (จอที่กล่อง ไฟหน้าโรงเรียน ข้อความผู้ปกครอง) ช่วยกันเมื่อชั้นใดล่ม»"],["«เดิมมีกล่องเดียว ใหม่ครูเห็นก่อนเข้าแถว เด็กเห็นจากสนาม ผู้ปกครองได้ข้อความ»"]],[["«ของ ค: ตารางสิ่งที่ต้องทำแต่ละระดับ»"],["«จาก AI: แสดงค่าทางการคู่กับค่าของเรา»"],["«ต้องบอกด้วยว่าค่าของเราเป็น \"ค่าโดยประมาณ\" และให้ดูค่าทางการประกอบเสมอ»"],["«เดิมแสดงค่าเดียว ใหม่แสดงคู่และมีป้ายบอกข้อจำกัด»"]]]]]},{"h":"5. สังเคราะห์เป็น 3 แนวคิดที่แตกต่างกันจริง","b":[["p","ส่วนนี้เป็น 3 แนวทางของกลุ่ม ส่วนรายบุคคลให้ตรวจบัตรคิดเอง 3 แนวทางของแต่ละคน ไม่ใช้ผลรวมกลุ่มแทนความคิดของคนใดคนหนึ่ง"],["t",[[["แนวคิด/วิธีทำงาน"],["ที่มา: ใครคิด (สมาชิก/AI) จุดแข็งหรือมุมมองของใครที่นำมาใช้ และต่อยอดส่วนใด"],["เหมาะกับใครและลดความเสี่ยงอย่างไร"]],[["1.« กล่องวัดฝุ่น + แจ้งมือถือ»","«เซนเซอร์ PMS5003 + IPST-WiFi ส่งข้อมูลไป Apps Script แล้วแจ้ง Telegram/LINE ตามระดับ 0–3»"],["«ฉันคิดกล่องวัดฝุ่น ก คิดข้อความถึงผู้ปกครอง AI เสนอแสดงค่าทางการคู่กัน»"],["«เหมาะกับครูเวรและผู้ปกครองที่มีมือถือ»","«ลดความเสี่ยงโดยรู้ก่อนเข้าแถวและเตรียมหน้ากากทัน»"]],[["2.« ไฟ 3 ดวงหน้าโรงเรียน + ตารางสิ่งที่ต้องทำ»","«ไฟเปลี่ยนตามระดับ และมีป้ายบอกว่าแต่ละสีต้องทำอะไร»"],["«ข คิดไฟ ค คิดตาราง ฉันคิดให้ไฟสลับบอกเมื่อไม่มีข้อมูล»"],["«นักเรียนและครูทุกคน รวมคนไม่มีมือถือ»","«ลดความเสี่ยงโดยให้ทุกคนเห็นระดับและรู้ว่าต้องทำอะไร»"]],[["3.« แผนกิจกรรมในร่ม + นับจุดความร้อน»","«ระดับส้มขึ้นไปย้ายพละเข้าอาคาร และอาสานับจุดความร้อนใกล้โรงเรียนเป็นสัญญาณล่วงหน้า»"],["«ค คิดตาราง ง คิดนับจุดความร้อน ฉันคิดแผนในร่มคู่ธง AI เตือนเรื่องความปลอดภัยของการทดสอบ»"],["«เด็กที่แพ้ฝุ่นหรือมีโรคทางเดินหายใจ»","«ลดความเสี่ยงโดยมีที่ให้ไปเมื่อเทคโนโลยีล่ม»"]]]],["p","แนวคิดที่กลุ่มภูมิใจที่สุด ต่างจากก่อนผสาน/ก่อนใช้ AI อย่างไร (ระบุสิ่งที่คิดเองชัดเจน) และเหตุใดจึงรวมเป็นผลงานหนึ่งเดียวของกลุ่มได้"],["t",[[["«แนวคิดที่ภูมิใจที่สุด: แสดงผล 3 ชั้น — กล่องหน้าโรงเรียนแสดงระดับบนจอเองแม้ไม่มีเน็ต ส่งข้อความเมื่อมีเน็ต และไฟให้เด็กเห็นจากสนาม ต่างจากก่อนผสานที่ฉันมีแค่กล่องเดียวที่ต้องเดินไปดู»","«สิ่งที่ฉันคิดเอง: กล่องวัดฝุ่นหน้าอาคาร แสดงระดับเองไม่ใช้เน็ต • จากเพื่อน: ข้อความถึงผู้ปกครอง ไฟ 3 ดวง ตารางสิ่งที่ต้องทำ นับจุดความร้อน • จาก AI: แสดงค่าทางการคู่กับค่าของเรา»","«รวมเป็นผลงานเดียวได้เพราะทุกส่วนใช้ \"ระดับ 0–3\" เดียวกัน (ตามช่วงของตาราง AQI) และเชื่อมกันผ่านเซิร์ฟเวอร์เดียว»"]]]]]}]},"a4":{"pre":[["p","ภารกิจ : ใช้ 3 ทางเลือกที่สร้างไว้ เปรียบเทียบความเหมาะสมและความปลอดภัย แล้วทำภาพร่าง/ผังงานที่ผู้อื่นนำไปสร้างต้นแบบได้ จากนั้นทดลองบนกระดาษ รับข้อเสนอแนะ และปรับเป็นแบบร่างรุ่นที่ 2"]],"secs":[{"h":"1. เปรียบเทียบ 3 แนวคิดโดยดูผู้ใช้และข้อจำกัด","b":[["t",[[["แนวคิด"],["ข้อดีต่อผู้ใช้"],["ข้อจำกัด/ความเสี่ยง"],["ทำได้จริงภายในเวลาอย่างไร"]],[["1.« กล่องวัดฝุ่น + แจ้งมือถือ»"],["«เห็นค่าฝุ่นหน้าโรงเรียนจริง เก็บประวัติไว้เทียบกับค่าทางการได้»","«ผู้ปกครองได้ข้อความทุกเช้า»"],["«ข้อความต้องพึ่งเน็ต ผู้ปกครองที่ไม่มีมือถือไม่ได้รับ»","«เซนเซอร์ราคาประหยัดอ่านต่างจากสถานีทางการได้»"],["«ใช้ IPST-WiFi + PMS5003 + Apps Script (มีชุดโค้ดต้นแบบชุดหมอกควันให้ปรับ)»","«อยู่ในกรอบ 5 ชั่วโมงลงมือ ทดสอบด้วยโหมดจำลองก่อน»"]],[["2.« ไฟ 3 ดวงหน้าโรงเรียน + ตารางสิ่งที่ต้องทำ»"],["«ทุกคนเห็นสถานะจากสนามโดยไม่ต้องใช้มือถือ»"],["«ไฟ 3 ดวงแสดงได้น้อยกว่า 5 สีของ AQI ระดับส้มต้องใช้แดงกะพริบและป้ายอธิบาย และไม่บอกตัวเลข»"],["«ใช้ชุดไฟ LED 3 สีของบอร์ดตัวที่ 2 ปิดเสียง ทำง่าย»"]],[["3.« แผนกิจกรรมในร่ม + นับจุดความร้อน»"],["«เด็กมีที่ไปเมื่อฝุ่นสูง ไม่ใช้ไฟฟ้า และจุดความร้อนเป็นสัญญาณล่วงหน้า»"],["«จุดความร้อนบอกไฟ ไม่ได้บอกค่าฝุ่นที่โรงเรียน และไม่รู้ว่าเมื่อไรควรเริ่มใช้แผนถ้าไม่มีตัวเลข»"],["«ทำเป็นแผน ป้าย และช่องกรอกจุดความร้อนในเว็บได้ ส่วนห้องปลอดฝุ่นจริงต้องขออนุญาตและของบจากโรงเรียน»"]]]],["p","แนวคิดที่เลือกคือ «แนวคิดที่ 1 + ไฟ 3 ดวงของแนวคิดที่ 2» เหตุผลที่เลือก (แก้ตรงโจทย์ ผู้ใช้ ทรัพยากร ความปลอดภัย)"],["t",[[["«แก้ตรงโจทย์: เลือกแนวคิดที่ 1 เป็นแกน เพราะวัดฝุ่นหน้าโรงเรียนเองและบอกก่อนเข้าแถว แล้วนำไฟ 3 ดวงของแนวคิดที่ 2 มารวมด้วย»","«ผู้ใช้: ครูเวรและผู้ปกครองได้ข้อความพร้อม \"สิ่งที่ควรทำ\" ส่วนเด็กเห็นสีไฟหน้าโรงเรียน»","«ทรัพยากร/ความปลอดภัย: ใช้บอร์ดและเซนเซอร์ที่โรงเรียนมี ใช้ไฟ 5 V จากพาวเวอร์แบงก์ ทดสอบด้วยโหมดจำลอง ไม่ใช้ควันจริงในห้อง»"]]]],["p","เหตุผลที่ไม่เลือกอีก 2 แนวคิด (หรือส่วนที่ตัดสินใจละทิ้ง) และเงื่อนไขใดอาจทำให้เปลี่ยนการตัดสินใจ"],["t",[[["«แนวคิดที่ 2 เดี่ยว ๆ: ไฟอย่างเดียวไม่มีข้อมูลฝุ่นให้ตรวจ จึงเก็บไว้เป็นส่วนแสดงผลของแนวคิดที่ 1»","«แนวคิดที่ 3: ห้องปลอดฝุ่นจริงต้องใช้งบและผู้บริหารอนุมัติ ใน 15 ชั่วโมงทำได้เพียงแผนและป้ายตัวอย่าง จึงตัดห้องปลอดฝุ่นจริงทิ้ง»","«เปลี่ยนใจได้ถ้า: ติดเซนเซอร์หน้าอาคารไม่ได้ → ใช้ค่าจากเว็บทางการแล้วให้ครูกรอกด้วยมือ • หรือโรงเรียนไม่อนุญาตส่งข้อความผู้ปกครอง → แสดงเฉพาะไฟและหน้าเว็บในโรงเรียน»"]]]]]},{"h":"2. ร่างแบบรุ่นที่ 1 และอธิบายหลักการทำงาน","b":[["p","วาดแผนภาพ/ผังงานขนาดใหญ่ ระบุส่วนประกอบ ลำดับการทำงาน ทางเข้าของข้อมูล ผลลัพธ์ และจุดที่ผู้ใช้จะโต้ตอบกับต้นแบบ"],["t",[[["พื้นที่ภาพร่าง/ผังงาน (ใช้ลูกศร หมายเลข และคำอธิบายกำกับ)"]]]],["p","อธิบาย 1) ต้นแบบเริ่มทำงานอย่างไร 2) ผู้ใช้ได้รับประโยชน์อะไร 3) หากไฟดับ/ไม่มีอินเทอร์เน็ตจะทำอย่างไร"],["t",[[["«1) เริ่มทำงาน: เปิดกล่องใต้ชายคา ต่อ Wi-Fi อ่าน PM2.5 ทุก 5 นาที (เฉลี่ย 6 รอบล่าสุด) แล้วเทียบเกณฑ์ จอที่กล่องแสดงระดับ 0–3 และส่งข้อมูลขึ้นเว็บ ส่วนไฟหน้าโรงเรียนถามเว็บแล้วเปลี่ยนสี»","«2) ประโยชน์: ครูเวรและผู้ปกครองได้ข้อความ \"ระดับ 2 งดกิจกรรมกลางแจ้ง ใส่หน้ากากกรอง PM2.5\" ส่วนไฟหน้าโรงเรียนให้เด็กและครูเห็นจากสนาม»","«3) ไฟดับ/ไม่มีเน็ต: กล่องใช้พาวเวอร์แบงก์และแสดงระดับบนจอเอง ไฟหน้าโรงเรียนสลับไฟบอกว่า \"ไม่มีข้อมูล\" ไม่ติดเขียวค้าง ถ้าเซนเซอร์เงียบเกิน 6 ชั่วโมง เว็บแสดง \"ไม่มีข้อมูล\"»"]]]]]},{"h":"3. ขยายความคิดให้ละเอียดพอสำหรับสร้างจริง","b":[["p","เขียนให้เพื่อนกลุ่มอื่นอ่านแล้วเข้าใจว่าต้องสร้างอะไร"],["t",[[["ส่วนประกอบของต้นแบบ"],["ลักษณะเฉพาะ/วิธีทำงาน","(ขนาด วัสดุที่คิดไว้ ข้อมูลเข้า–ออก)"],["ผู้ใช้โต้ตอบกับส่วนนี้อย่างไร"]],[["1.« กล่องวัดฝุ่น»","«IPST-WiFi + เซนเซอร์ PMS5003 + จอ OLED»"],["«เข้า: ค่า PM2.5 จากเซนเซอร์ (สายสัญญาณ UART) เฉลี่ยหลายรอบ»","«ออก: ระดับ 0–3 + จอ OLED + ส่งข้อมูลขึ้นเว็บ»"],["«ผู้ใช้ไม่ต้องกดอะไร ดูระดับบนจอที่กล่อง»","«ครูเวรเป็นผู้ติดตั้งใต้ชายคาและตรวจแบตเตอรี่»"]],[["2.« เซิร์ฟเวอร์»","«Google Apps Script Web App + Google Sheet»"],["«รับข้อมูลที่มีรหัสลับ คำนวณระดับ เก็บประวัติ»","«แจ้ง Telegram/LINE และแสดงหน้าเว็บบนมือถือ»"],["«ครูเวรเปิดหน้าเว็บดูสถานะและกราฟฝุ่น»","«ผู้ปกครองรับข้อความผ่านกลุ่มที่โรงเรียนอนุญาต»"]],[["3.« ไฟ 3 ดวงหน้าโรงเรียน»","«IPST-WiFi ตัวที่ 2 + LED เขียว/เหลือง/แดง (ปิดเสียง)»"],["«ถามระดับจากเว็บทุก 10–20 วินาที»","«เขียว/เหลืองติดนิ่ง แดงกะพริบ (ช้า = ส้ม เร็ว = แดง)»"],["«เด็กและครูดูสีไฟและอ่านป้ายอธิบายสี»","«คนไม่มีมือถือก็เห็นระดับฝุ่นได้»"]]]],["p","จุดที่ยังคลุมเครือหรือยังตอบไม่ได้ในแบบร่าง และสิ่งที่ต้องทดลองหรือหาข้อมูลเพิ่มก่อนสร้าง"],["t",[[["«ค่าจากเซนเซอร์ราคาประหยัดต่างจากสถานีทางการเท่าไร และเพี้ยนเมื่ออากาศชื้นหรือไม่ — ต้องเทียบ 1–2 สัปดาห์ (แนวทาง: ใช้ค่าเฉลี่ยหลายรอบ)»","«เกณฑ์ที่ใช้เป็นช่วงของตาราง AQI แบบเฉลี่ย 24 ชม. แต่กล่องส่งค่าเฉลี่ยประมาณ 30 นาที — ยังไม่รู้ว่าจะเตือนทันและไม่เตือนเท็จหรือไม่ ต้องทดลองดูการขึ้นลงของระดับ»","«ครูและผู้ปกครองจะทำตามข้อความระดับ 2 จริงหรือไม่ และโรงเรียนอนุญาตส่งข้อความเข้ากลุ่มผู้ปกครองหรือไม่ — ต้องทดลองกับครู/ผู้ปกครองและถามผู้บริหาร»"]]]]]},{"h":"4. ทดลองบนกระดาษและปรับเป็นแบบร่างรุ่นที่ 2","b":[["p","ทดลองเดินตามสถานการณ์จำลอง 1 รอบ (บนกระดาษหรือสวมบทบาท) โดยใช้แบบร่างรุ่นที่ 1 — ผู้ใช้ทำอะไรเป็นขั้นแรก และติดขัดตรงไหน"],["t",[[["«สถานการณ์จำลอง (สมมติ): เช้าวันหนึ่ง PM2.5 ขึ้นจาก 30 เป็น 66 µg/m³ ภายใน 1 ชั่วโมง ท้องฟ้าดูไม่ขุ่น ผู้ใช้คือครูเวร ก ถือมือถือก่อนเข้าแถว»","«ขั้นแรกที่ครูเวรทำ: เปิดข้อความเตือน แล้วเปิดหน้าเว็บ ติดขัด: ข้อความบอกแค่ \"ระดับ 2\" ไม่รู้ว่าต้องงดแค่ไหน พละเรียนในร่มได้หรือไม่ และผู้ปกครองต้องรู้ด้วยหรือไม่»","«ติดขัดอีก: วันที่เซนเซอร์ดับ ครูไม่มีช่องบอกระบบว่าค่าทางการวันนี้เท่าไร และไม่รู้ว่าค่าบนจอต่างจากเว็บทางการหรือไม่»"]]]],["p","ข้อเสนอแนะที่เฉพาะเจาะจงจากเพื่อน/ครู (เขียนว่าใครเสนอเรื่องใด)"],["t",[[["ข้อเสนอแนะ (ใครเสนอ)"],["สิ่งที่ปรับในแบบร่างรุ่นที่ 2"],["เหตุผล/ผลที่คาดว่าจะดีขึ้น"]],[["1.« เพื่อน ฉ (กลุ่มอื่น): ข้อความเตือนควรบอกว่าต้องทำอะไร»"],["«เพิ่มบรรทัด \"สิ่งที่ควรทำ\" 4 ข้อ ตามระดับ เช่น งดกิจกรรมกลางแจ้ง ใส่หน้ากากกรอง PM2.5 ในข้อความและหน้าเว็บ»"],["«ครูเวรไม่ต้องเดา ตัดสินใจก่อนเข้าแถวได้เร็วขึ้น»"]],[["2.« ครู: ต้องมีช่องกรอกค่าทางการด้วยมือเมื่อบอร์ดดับ และห้ามส่งข้อมูลส่วนตัวของนักเรียนเข้ากลุ่ม»"],["«เพิ่มช่องกรอกค่า PM2.5 ที่อ่านจากเว็บทางการในพื้นที่อาสาสมัคร (ใส่ PIN) และแสดงค่าทางการคู่ค่าของเรา ข้อความส่งเฉพาะกลุ่มที่โรงเรียนอนุญาต»"],["«ยังรู้ระดับฝุ่นได้แม้เซนเซอร์ดับ และคุ้มครองข้อมูลนักเรียน»"]]]],["t",[[["ภาพร่างรุ่นที่ 2 (วาดเฉพาะส่วนที่เปลี่ยน)"]]]],["p","แบบร่างรุ่นที่ 2 ต่างจากรุ่นที่ 1 อย่างไร และมีแนวทางหรือส่วนใดที่ตัดสินใจละทิ้งเพราะไม่ช่วยแก้ปัญหา"],["t",[[["«ต่างจากรุ่นที่ 1: เพิ่มข้อความ \"สิ่งที่ควรทำ\" ตามระดับ เพิ่มช่องให้ครูกรอกค่าทางการด้วยมือเมื่อเซนเซอร์ดับ และแสดงค่าทางการคู่กับค่าของเราพร้อมป้ายอธิบายสี (ส่วนอื่นเหมือนเดิม)»","«ละทิ้ง: การทดสอบด้วยควันจริงโดยนักเรียน และการส่งข้อความเข้ากลุ่มผู้ปกครองโดยไม่ขออนุญาต»","«เพราะเสี่ยงต่อสุขภาพและข้อมูลส่วนบุคคล และไม่ช่วยแก้ปัญหาหลักคือให้ครูรู้ระดับก่อนเข้าแถว»"]]]]]},{"h":"5. ให้ครูตรวจแบบร่างก่อนสร้างต้นแบบ","b":[["p","☐ แบบร่างชัดเจนพอให้ผู้อื่นสร้างตามได้    ☐ ปลอดภัย ไม่ต้องทดลองในภัยจริง    ☐ อนุญาตให้สร้างต้นแบบ"],["p","ข้อเสนอแนะจากครู (ใช้เป็นข้อมูลย้อนกลับก่อนลงมือสร้าง)"],["t",[[["​","​"]]]]]}]},"a5":{"pre":[["p","ภารกิจ : สร้างต้นแบบตามภาพร่าง อธิบายสิ่งที่ทำจริง แก้ปัญหาเมื่อเจออุปสรรค และตรวจสอบการใช้ AI อย่างรอบคอบ"]],"secs":[{"h":"1. ทบทวนผู้ใช้และข้อกำหนดก่อนสร้าง","b":[["p","ใช้ข้อมูลจากใบกิจกรรมที่ 2 และแบบร่างรุ่นที่ 2 จากใบกิจกรรมที่ 4"],["t",[[["ผู้ใช้/กลุ่มเป้าหมาย"],["ความต้องการและข้อจำกัดสำคัญ"],["ส่วนของต้นแบบที่จะตอบความต้องการนี้"]],[["ผู้ใช้หลัก:« ครูเวรและผู้ปกครองของนักเรียน (ผู้ตัดสินใจและผู้รับข้อความ)»"],["«ต้องรู้ระดับฝุ่นก่อนเข้าแถว ข้อความสั้นและบอกสิ่งที่ควรทำ ไม่ทำให้ตกใจเกินจริง»"],["«หน้าเว็บมือถือ + แจ้งเตือน Telegram/LINE + ข้อความ \"สิ่งที่ควรทำ\"»"]],[["ผู้ใช้อื่นที่อาจเกี่ยวข้อง:« นักเรียนและผู้ปกครองที่ไม่ได้ใช้มือถือ/ไม่อ่านกลุ่ม»"],["«ต้องการสัญญาณที่เห็นง่ายจากสนาม และไม่เปิดเผยข้อมูลส่วนตัวของนักเรียน»"],["«ไฟ 3 ดวงหน้าโรงเรียน และจอที่กล่องวัดฝุ่น»"]]]]]},{"h":"2. เตรียมความพร้อมและเลือกใช้ทรัพยากร","b":[["p","☐ ครูตรวจแผนแล้ว    «☒» วัสดุปลอดภัย    «☒» ไม่ทดลองในภัยจริง    «☒» ไม่ใช้ไฟฟ้าเสี่ยงอันตราย    «☒» กำหนดผู้รับผิดชอบ"],["t",[[["รายการ"],["เลือกใช้/เหตุผล"],["ข้อควรระวัง/การตรวจสอบ/ทางเลือกที่ปลอดภัย"]],[["วัสดุ–อุปกรณ์"],["«IPST-WiFi 2 ตัว เซนเซอร์ฝุ่น PMS5003 (หรือ PMS7003) LED เขียว/เหลือง/แดง พร้อมตัวต้านทาน 220 Ω สายจั๊มเปอร์ พาวเวอร์แบงก์ กล่องกันฝนสำหรับติดใต้ชายคา»","«เลือกเพราะโรงเรียนมีบอร์ดอยู่แล้ว ราคาไม่สูง และทดสอบด้วยโหมดจำลองบนโต๊ะได้»"],["«ใช้ไฟ 5 V จากพาวเวอร์แบงก์เท่านั้น ไม่ใช้ไฟบ้านนอกอาคาร ใส่กล่องกันฝน และเช็กชื่อขา/แรงดันกับดาต้าชีตรุ่นที่ซื้อก่อนต่อสาย»","«ครูตรวจสายและขั้วบวก/ลบก่อนเปิดไฟทุกครั้ง»"]],[["เครื่องมือ–เทคโนโลยี"],["«Thonny/microBlock เขียน MicroPython ลงบอร์ด • Google Apps Script + Google Sheets • Telegram Bot»","«เลือกเพราะฟรี ใช้บัญชี Google ของโรงเรียนได้»"],["«รหัสลับและโทเคนเก็บใน Script Properties ห้ามใส่ในโค้ดหรือโพสต์ในกลุ่ม»","«ไฟล์ config.py ที่มีรหัส Wi-Fi ไม่ส่งต่อ»"]],[["AI (ถ้าใช้)"],["«ใช้ AI อธิบายโค้ดที่ไม่เข้าใจ และช่วยเรียบเรียงข้อความแจ้งระดับให้สั้น»","«ไม่ให้ AI กำหนดเกณฑ์สีฝุ่นหรือให้คำแนะนำทางการแพทย์»"],["«ตรวจกับตาราง AQI ทางการ ครู และพยาบาลโรงเรียน/สถานีอนามัย ห้ามใส่ชื่อนักเรียนหรือผู้ปกครองใน Prompt»","«เกณฑ์สีใช้ตารางทางการ ไม่ใช้ตัวเลขที่ AI เดา»"]]]]]},{"h":"3. วางแผนการสร้างและคาดการณ์อุปสรรค","b":[["t",[[["ขั้นตอนลงมือสร้าง"],["ผู้รับผิดชอบ"],["หลักฐานตรวจความก้าวหน้า"]],[["ขั้น 1« ต่อเซนเซอร์ PMS5003 เข้าบอร์ด ทดสอบอ่านค่าและดูว่าเฟรมข้อมูลถูกต้อง»"],["«จ (ฮาร์ดแวร์)»"],["«ภาพวงจร + บันทึกค่าที่อ่านได้ในโหมดจำลองและโหมดจริง»"]],[["ขั้น 2« สร้างเว็บแอป Apps Script + Google Sheet รันชุดค่าหมอกควัน ตั้ง Script Properties และทดสอบด้วยโหมดจำลอง»"],["«ก (เซิร์ฟเวอร์)»"],["«ภาพหน้าเว็บ + ข้อความทดสอบใน Telegram»"]],[["ขั้น 3« เขียนโค้ดบอร์ดส่งข้อมูลขึ้นเว็บ และต่อไฟ 3 ดวงหน้าโรงเรียน»"],["«ค (โค้ดบอร์ด) ข (ไฟ 3 ดวง)»"],["«วิดีโอสั้นไฟเปลี่ยนสีตามค่าฝุ่นจำลอง»"]],[["ขั้น 4« ทดสอบระบบรวมและซ้อมสถานการณ์เซนเซอร์ดับ/ตัดเน็ตจำลอง»"],["«ทั้งกลุ่ม»"],["«ใบบันทึกผลทดสอบ + ภาพถ่าย»"]]]],["p","อันตราย/ข้อจำกัดที่คาด และวิธีป้องกันหรือแผนสำรองก่อนลงมือสร้าง"],["t",[[["อันตราย/ข้อจำกัดที่คาด"],["ผลกระทบหากเกิดขึ้น"],["มาตรการป้องกัน/ทางสำรอง"],["ตรวจแล้วพบอะไร"]],[["«การทดสอบเซนเซอร์ด้วยควันหรือไฟจริง (ธูป ไฟเผา) ในห้องหรือใกล้นักเรียน»"],["«สูดควัน เสี่ยงไฟไหม้ เด็กที่แพ้ฝุ่นอาการกำเริบ»"],["«ไม่ใช้ควันจริง ใช้โหมดจำลอง (SIMULATE) แทน ถ้าจำเป็นให้ครูเป็นผู้ทดสอบในที่โล่งอากาศถ่ายเท»"],["«(สมมติ) ทดสอบทั้งหมดด้วยโหมดจำลอง ไม่มีใครสัมผัสควัน»"]],[["«เซนเซอร์โดนแดดตรง ลมเป่า หรืออากาศชื้นมาก ทำให้ค่าฝุ่นเพี้ยน»"],["«ไฟและข้อความแสดงระดับผิด ครูหรือผู้ปกครองตัดสินใจผิด»"],["«ติดใต้ชายคากันฝนและแดงตรง ใช้ค่าเฉลี่ยหลายรอบ แสดงค่าทางการคู่กัน และเรียกค่าของเราว่า \"ค่าโดยประมาณ\"»"],["«(สมมติ) เทียบค่ากล่องกับค่าทางการ 5 ช่วงเวลา ต่างกันไม่เกินเกณฑ์ที่กลุ่มกำหนดเอง»"]]]]]},{"h":"4. บันทึกการสร้างอย่างมีหลักฐาน","b":[["t",[[["ลำดับ"],["สิ่งที่ลงมือทำจริง (ระบุสิ่งที่เปลี่ยนจากแผน ถ้ามี)"],["ผู้ลงมือ/ภาพหรือไฟล์หลักฐาน"]],[["1"],["«ต่อเซนเซอร์: TX ของ PMS5003 เข้า GPIO16 (RX ของบอร์ด) RX เข้า GPIO17 ไฟ 5 V และ GND (ตรวจเลขขากับคู่มือบอร์ดของโรงเรียนก่อน) ตั้ง HAZARD=\"smoke\" และ SIMULATE=True ก่อน แล้วค่อยเปลี่ยนเป็น False เมื่อต่อเซนเซอร์จริง»"],["«จ / ภาพถ่ายวงจร»"]],[["2"],["«สร้างเว็บแอป: วางโค้ด Code.gs และ Index.html ตั้ง Script Properties รัน setup() แล้วรัน usePresetSmoke แล้ว Deploy เป็น Web App»"],["«ก / ภาพหน้าเว็บ + ข้อความทดสอบ»"]],[["3"],["«ใส่ Wi-Fi/URL/รหัสลับในไฟล์ config.py แล้วอัปโหลดไฟล์ขึ้นบอร์ด รันโหมดจริง (ปิดบัซเซอร์ที่กล่อง)»"],["«ค / ภาพหน้าจอ (ซ่อนรหัสก่อนแนบ)»"]],[["4"],["«ต่อบอร์ดไฟ: LED เขียว GPIO5 เหลือง GPIO19 แดง GPIO23 ผ่านตัวต้านทาน 220 Ω และตั้ง SOUND_ON=False ให้เป็นไฟอย่างเดียว»"],["«ข / วิดีโอไฟ 3 ดวง»"]]]],["p","สรุป: ตอนนี้ต้นแบบทำงานได้หรือแสดงหลักการใดแล้ว และยังทำไม่ได้ส่วนใด"],["t",[[["«(สมมติ — ตัวอย่างวิธีเขียน) ทำงานได้/แสดงหลักการ: ค่า PM2.5 จำลองขึ้น-ลง → ตัดสินระดับ 0–3 → จอที่กล่องแสดงระดับ → ส่งขึ้นเว็บและมือถือ → ไฟหน้าโรงเรียนเปลี่ยนสีตาม»","«ยังทำไม่ได้: วัดฝุ่นจริงกลางแจ้งตลอดฤดูแล้ง • เทียบความแม่นกับสถานีทางการ • ใช้แทนประกาศหรือคำแนะนำสุขภาพทางการ • ส่วนที่ยังไม่ได้ทดสอบกับอุปกรณ์จริงให้เขียนว่า \"ยังไม่ทดสอบ\"»"]]]]]},{"h":"5. เมื่อพบอุปสรรค เราคิดและแก้อย่างไร","b":[["t",[[["อุปสรรค/สาเหตุที่คาด"],["ทางเลือกที่เสนอ"],["วิธีที่ลองจริง/ผลที่พบ"]],[["1.« ค่าฝุ่นจากกล่องกับค่าทางการต่างกันบางช่วง ทำให้ธงสีคนละระดับ»"],["«แสดงค่าทางการคู่ค่าของเรา เขียนว่า \"ค่าโดยประมาณ\" และย้ายกล่องให้พ้นลมเป่า/แดงตรง»"],["«(สมมติ) หลังย้ายกล่อง ค่าต่างกันน้อยลง แต่ต้องเทียบต่อหลายวันเพื่อยืนยัน»"]],[["2.« ค่ากล่องเป็นค่าเฉลี่ยประมาณ 30 นาที ตอบช้ากว่าเมื่อฝุ่นพุ่ง ขณะที่เกณฑ์อิงค่าเฉลี่ย 24 ชม.»"],["«เขียนในป้ายและรายงานว่าเป็นค่าประมาณเพื่อเฝ้าระวัง ไม่ใช่ค่ามาตรฐาน และให้ดูค่าทางการประกอบ»"],["«(สมมติ) เมื่อจำลองฝุ่นพุ่งฉับพลัน ระดับขึ้นช้ากว่าค่าจริงราว 1–2 รอบวัด จึงบันทึกเป็นข้อจำกัด»"]]]],["p","ตัวอย่าง 1 เหตุการณ์ที่กลุ่มเปลี่ยนแผนเอง (ระบุก่อน–หลัง และเหตุผล)"],["t",[[["«ก่อน: วางแผนใช้ค่าจากกล่องเป็นตัวตัดสินระดับเพียงอย่างเดียว»","«หลัง: แสดงค่าทางการคู่กัน เขียนกำกับว่า \"ค่าโดยประมาณ\" และเพิ่มช่องให้ครูกรอกค่าทางการ»","«เหตุผล: (สมมติ) ค่ากล่องกับสถานีทางการต่างกันบางวัน และกล่องเป็นค่าเฉลี่ยสั้นกว่า 24 ชม. จึงไม่ควรเป็นตัวตัดสินเพียงอย่างเดียว»"]]]]]},{"h":"6. บันทึกการใช้ AI อย่างรับผิดชอบ","b":[["t",[[["ใช้ AI ช่วยงานใด/ข้อความคำสั่งย่อ"],["AI เสนออะไร"],["เราตรวจและปรับเองอย่างไร"]],[["1.« ให้ AI อธิบายโค้ดตรวจเฟรมข้อมูลของ PMS5003 (checksum) และการหาค่าเฉลี่ยหลายรอบ»"],["«อธิบายว่า checksum ใช้ตรวจว่าข้อมูลไม่เพี้ยน และค่าเฉลี่ยช่วยลดค่าสะดุ้ง»"],["«ทดลองในโหมดจำลองและเปรียบเทียบกับที่ AI อธิบาย»"]],[["2.« ให้ AI ช่วยเรียบเรียงข้อความแจ้งระดับฝุ่น 4 ระดับให้สั้น»"],["«ข้อความมีคำแนะนำทางการแพทย์เฉพาะบุคคล และคำที่ทำให้ตกใจ เช่น \"อันตรายถึงชีวิต\"»"],["«ตัดคำแนะนำเฉพาะบุคคลและคำที่ทำให้ตกใจ ใช้เฉพาะคำแนะนำตามตาราง AQI ทางการ ใส่ข้อความ \"ปรึกษาแพทย์หากมีอาการ\" และบอกว่าเป็นต้นแบบของโรงเรียน»"]]]],["p","ข้อมูลใดจาก AI ที่กลุ่มไม่ใช้ เพราะไม่เหมาะสม ไม่ปลอดภัย หรือไม่มีหลักฐานยืนยัน"],["t",[[["«ไม่ใช้: เกณฑ์สีฝุ่นที่ AI ปรับเอง เพราะเกณฑ์ต้องตามตาราง AQI ทางการ»","«ไม่ใช้: คำแนะนำสุขภาพเฉพาะบุคคลที่ AI ให้ เพราะไม่ใช่ผู้เชี่ยวชาญและตรวจสอบไม่ได้»","«ไม่ใช้: ไอเดียทดสอบเซนเซอร์ด้วยควันธูปในห้อง เพราะอันตราย ใช้โหมดจำลองแทน»"]]]]]},{"h":"7. ตรวจสอบความพร้อมของต้นแบบจำลอง","b":[["t",[[["เกณฑ์"],["หลักฐานที่เห็นจริง/สิ่งที่ต้องแก้"]],[["ตรงปัญหาและตอบผู้ใช้ที่กำหนด"],["«ตรง: กล่อง + ข้อความ + ไฟ ตอบโจทย์ \"ครูและผู้ปกครองไม่รู้ค่าฝุ่นก่อนเข้าแถว\"»","«หลักฐาน: ใบกิจกรรมที่ 2 ข้อ 3»"]],[["แสดงการทำงานได้/อธิบายขั้นตอนชัด"],["«สาธิตด้วยโหมดจำลอง: ค่าฝุ่นขึ้นถึงเหลือง → ส้ม → แดง แล้วจอ หน้าเว็บ ข้อความ และไฟเปลี่ยนตาม»","«หลักฐาน: วิดีโอสาธิต»"]],[["เลือกใช้ทรัพยากรเหมาะสมและปลอดภัย"],["«ใช้ไฟ 5 V ไม่ใช้ควันจริง เก็บรหัสลับนอกโค้ด ไม่ส่งข้อมูลส่วนตัวนักเรียน»","«หลักฐาน: ตารางความเสี่ยงข้อ 3»"]],[["ต่างจากวิธีทั่วไปอย่างมีเหตุผล"],["«ต่างจากเว็บ/แอปคุณภาพอากาศทางการที่ต้องเปิดดูเอง: วัดหน้าโรงเรียนและแจ้งอัตโนมัติพร้อมสิ่งที่ควรทำ แต่ไม่ได้แทนค่าทางการ»"]]]],["p","ชื่อของต้นแบบ «ธงฝุ่นโรงเรียน (ต้นแบบเฝ้าระวัง PM2.5)»  ·"],["p","วิธีสาธิตการทำงานอย่างปลอดภัย"],["t",[[["«สาธิตด้วยโหมดจำลอง (SIMULATE) ใช้ไฟ 5 V จากพาวเวอร์แบงก์ ครูอยู่ดูแล ไม่ใช้ควันจริง ให้ผู้ชมดูระดับขึ้นถึงเหลือง ส้ม แดง และไฟกับข้อความเปลี่ยนตาม»","«ถ้าไม่มีอุปกรณ์หรือเน็ต: ใช้ปุ่ม \"โหมดจำลอง\" ในหน้าเว็บ ไม่ต้องใช้เซนเซอร์จริง»"]]]],["p","หลักฐานภาพถ่าย/ไฟล์/ลิงก์ต้นแบบ"],["t",[[["«หลักฐานที่ต้องแนบ: ภาพถ่ายวงจร วิดีโอสั้นสาธิต ภาพหน้าจอเว็บแอป ตารางเทียบค่ากล่องกับค่าทางการ (ลิงก์ Google Drive ของกลุ่ม ห้ามมีรหัสลับในภาพ)»"]]]]]},{"h":"8. ต้นแบบเราแตกต่างจากวิธีที่มีอยู่จริงอย่างไร","b":[["t",[[["วิธีแก้ปัญหาที่พบหรือใช้อยู่ก่อน"],["สิ่งที่เราเปลี่ยน/เพิ่มในต้นแบบ"],["ประโยชน์ต่อผู้ใช้"],["หลักฐานที่ตรวจสอบได้"]],[["«เว็บและแอปคุณภาพอากาศทางการ (เช่น Air4Thai ของกรมควบคุมมลพิษ) ที่แสดงค่าของสถานีและต้องเปิดดูเอง»","«การดูท้องฟ้าหรือถามกันหน้าเสาธง»"],["«เซนเซอร์วัดหน้าโรงเรียนเอง วัดทุก 5 นาที»","«จอที่กล่องแสดงระดับเองแม้ไม่มีเน็ต และไฟ 3 ดวงหน้าโรงเรียน»","«ข้อความ \"สิ่งที่ควรทำ\" ช่องกรอกค่าทางการด้วยมือ และแสดงค่าทางการคู่กัน»"],["«ครูเห็นระดับก่อนเข้าแถวโดยไม่ต้องเปิดแอป»","«เด็กเห็นจากสนาม»","«ผู้ปกครองได้ข้อความสั้น»"],["«ตารางเทียบค่ากล่องกับค่าทางการ»","«วิดีโอสาธิต»","«ข่าวอ้างอิงในใบกิจกรรมที่ 1»"]]]],["p","ทำไมสิ่งที่เพิ่มจึงอาจลดความเสี่ยงของกลุ่มเป้าหมายได้ (ไม่อ้างประสิทธิภาพก่อนมีผลทดลอง)"],["t",[[["«สมมติฐาน: ถ้าครูและผู้ปกครองเห็นระดับฝุ่นหน้าโรงเรียนก่อนเข้าแถวพร้อมข้อความสิ่งที่ควรทำ อาจตัดสินใจงดกิจกรรมหนักกลางแจ้งหรือใส่หน้ากากได้ทันมากขึ้น (ยังไม่อ้างว่าได้ผลจนกว่าจะมีผลทดลอง)»","«เหตุผลสนับสนุน: ข่าว 7 เม.ย. 2569 รายงานค่าเกินมาตรฐานตั้งแต่ 07:00 น. และตาราง AQI ใหม่แนะนำให้สวมหน้ากากและเลี่ยงกิจกรรมหนักเมื่อถึงระดับส้ม ซึ่งต้องรู้ค่าก่อนจึงจะทำได้»"]]]],["p","ถ้าผู้ใช้อีกกลุ่มหนึ่งต้องใช้ต้นแบบนี้ ต้องปรับอะไร (หรือใช้วัสดุ/เทคโนโลยีในแบบที่ต่างจากปกติอย่างไร)"],["t",[[["«ถ้าผู้ใช้เป็นศูนย์เด็กเล็กหรือโรงเรียนอนุบาล: ต้องปรึกษาครู/หน่วยงานสุขภาพเรื่องเกณฑ์และข้อความที่เหมาะกับเด็กเล็ก ไม่ใช้เกณฑ์ของ ม.2 ตรง ๆ»","«ถ้าผู้ใช้เป็นอาสาป้องกันไฟชุมชน: ใช้ช่องจุดความร้อนที่อาสากรอกเป็นหลัก และเขียนเตือนว่าห้ามเข้าใกล้ไฟ ไฟลามใกล้ชุมชนโทร 199 หรือ ปภ. 1784»"]]]]]},{"h":"9. สาธิตสั้น ๆ ให้ดู","b":[["p","ฉันรับผิดชอบส่วนใด / ส่วนนี้ทำงานอย่างไร / จะสาธิตให้เห็นอะไร"],["t",[[["«ฉันรับผิดชอบ: บอร์ดกล่องวัดฝุ่น (ฮาร์ดแวร์)»","«ทำงานอย่างไร: เซนเซอร์วัดฝุ่น → บอร์ดหาค่าเฉลี่ยและแปลงเป็นระดับ 0–3 ตามช่วงของตาราง AQI → จอแสดงระดับและส่งขึ้นเว็บ → ไฟหน้าโรงเรียนเปลี่ยนสี»","«จะสาธิต: เปิดโหมดจำลองให้ค่าฝุ่นขึ้นถึงระดับส้ม ดูข้อความและไฟเปลี่ยน แล้วปิด Wi-Fi ให้ดูว่าจอที่กล่องยังแสดงระดับเอง»"]]]],["p","ข้อบกพร่องหรืออุปสรรคที่ฉันพบ 1 เรื่อง / ฉันลองแก้อย่างไร / ผลที่เกิด"],["t",[[["«(สมมติ) พบ: ค่าที่กล่องกับค่าทางการต่างกันบางช่วง ทำให้สีคนละระดับ»","«ลอง: แสดงค่าทางการคู่กัน เขียนกำกับว่า \"ค่าโดยประมาณ\" และย้ายกล่องให้พ้นลมเป่าและแดงตรง»","«ผลที่เกิด: (นักเรียนบันทึกผลจริงของกลุ่ม)»"]]]]]}]},"a6":{"pre":[["p","ภารกิจ : กำหนดเกณฑ์ความสำเร็จก่อนทดลอง ใช้สถานการณ์จำลองที่ปลอดภัย เก็บข้อเสนอแนะ ปรับต้นแบบ และทดสอบซ้ำ แล้วใช้ผลทั้งหมดสะท้อนผลงานและวิธีทำงานของตน พร้อมวางแผนพัฒนารอบถัดไป"]],"secs":[{"h":"1. วางแผนการทดลองสถานการณ์จำลอง","b":[["p","สถานการณ์จำลองที่ใช้ทดสอบ (เช่น น้ำป่าตอนกลางคืนโดยไม่มีอินเทอร์เน็ต) และผู้ทดลอง"],["t",[[["«สถานการณ์จำลอง: ใช้โหมดจำลอง (SIMULATE) ให้ค่า PM2.5 ขึ้น-ลงผ่านระดับ 0–3 ช่วงหนึ่งปิด Wi-Fi แทนการไม่มีเน็ต และอีกช่วงถอดสายเซนเซอร์แทนเซนเซอร์ดับ แล้วดูจอ หน้าเว็บ ข้อความ และไฟ»","«ผู้ทดลอง: เพื่อนกลุ่มอื่น 2 คนรับบทครูเวร (ไม่รู้ล่วงหน้าว่าค่าจะขึ้นถึงระดับใดเมื่อไร) ครูเป็นผู้สังเกต»","«ความปลอดภัย: ใช้ไฟ 5 V บนโต๊ะ ไม่ใช้ควันหรือไฟจริงในห้อง รอบจำลองวัดทุก 5 วินาที (ค่าใช้จริง 5 นาที) ไม่ต้องแก้ค่าใด ๆ»"]]]],["t",[[["สิ่งที่จะวัด/สังเกต"],["เกณฑ์สำเร็จที่กำหนดไว้ก่อนทดสอบ"],["จะเก็บผลอย่างไร"]],[["1.« ระดับ 0–3 ที่จอบอร์ดและหน้าเว็บแสดง ตรงกับระดับที่คำนวณจากตารางเกณฑ์»"],["«ตรงอย่างน้อย 5 ใน 6 จุดวัด (กลุ่มกำหนดเอง)»"],["«จดค่า PM2.5 ที่เว็บแสดง ระดับที่คำนวณเอง และระดับ 0–3 ที่เว็บแสดง ลงตาราง 6 แถว»"]],[["2.« ครูเวรรู้ว่าต้องทำอะไรเมื่ออ่านข้อความระดับ 2»"],["«ผู้ทดลอง 2 ใน 2 คน บอก 2 ข้อแรกที่ต้องทำได้ถูกภายใน 30 วินาที»"],["«ถามผู้ทดลองแล้วจดผลลงตาราง»"]]]]]},{"h":"2. ผลทดลองรอบที่ 1 ก่อนปรับปรุง","b":[["t",[[["เกณฑ์ทดสอบ"],["ผลที่เกิดจริง (ไม่แต่งข้อมูล)"],["ปัญหาหรือข้อจำกัด"]],[["1.« ระดับตรงกับที่คำนวณ อย่างน้อย 5 ใน 6 จุด»"],["«(สมมติ) ตรง 4 ใน 6 จุด»"],["«2 จุดหลังค่าลดลง ระดับที่เว็บยังไม่ลดตามทันที เพราะระบบรอเห็นค่าต่ำลง 2 ครั้งติดกัน ทำให้ไม่ตรงกับที่นักเรียนคำนวณจากค่าล่าสุด»"]],[["2.« ผู้ทดลองบอก 2 ข้อแรกที่ต้องทำได้ถูกใน 30 วินาที»"],["«(สมมติ) 1 ใน 2 คน อีกคนไม่แน่ใจว่าต้องทำอะไรก่อน»"],["«ข้อความระดับ 2 มีหลายข้อ และมีคำว่า \"ห้องปลอดฝุ่น\" ซึ่งโรงเรียนไม่มี»"]]]],["p","ข้อเสนอแนะจากเพื่อน/ครู/ผู้ทดลองใช้ 1–2 ข้อ (เขียนว่าใครเสนอเรื่องใด ไม่ต้องระบุข้อมูลส่วนตัว)"],["t",[[["«ผู้ทดลองคนที่ 1: โรงเรียนเราไม่มีห้องปลอดฝุ่น อยากให้บอกว่าให้ย้ายไปทำกิจกรรมในอาคาร»","«ครู: ข้อความต้องไม่เป็นคำแนะนำทางการแพทย์ และควรแสดงค่าทางการคู่กับค่าของเรา»","«(ตัวอย่างสมมติ — นักเรียนเขียนข้อเสนอแนะที่ได้จริง)»"]]]]]},{"h":"3. ปรับปรุงตามหลักฐานและทดสอบซ้ำ","b":[["p","ทดสอบซ้ำในสถานการณ์จำลองที่เทียบเคียงกับรอบแรก เช่น ผู้ทดลอง เหตุการณ์ ระยะทาง แหล่งข้อมูล และอุปกรณ์"],["t",[[["เกณฑ์ความสำเร็จเดิม"],["ผลรอบที่ 1"],["สิ่งที่แก้จริง + เหตุผล"],["ผลรอบที่ 2"],["ดีขึ้น/ยังไม่ดี เพราะอะไร"]],[["1.« ระดับตรงกับที่คำนวณ อย่างน้อย 5 ใน 6 จุด»"],["«(สมมติ) ตรง 4 ใน 6 จุด»"],["«เพิ่มคอลัมน์ \"ค่า 2 รอบล่าสุด\" ในตารางทดสอบ และอ่านระดับหลังค่าลดครบ 2 รอบ»","«เหตุผล: ระบบลดระดับเมื่อเห็นค่าต่ำลง 2 ครั้งติดกัน ไม่ใช่ทันที»"],["«(สมมติ) ตรง 6 ใน 6 จุด»"],["«ดีขึ้น แต่เพราะเปลี่ยนวิธีตรวจ ไม่ใช่แก้ตัวต้นแบบ และมีเพียง 6 จุดในโหมดจำลอง ยังไม่ได้ทดสอบกับฝุ่นจริง»"]],[["2.« ผู้ทดลองบอก 2 ข้อแรกที่ต้องทำได้ถูกใน 30 วินาที»"],["«(สมมติ) 1 ใน 2 คน»"],["«ตัดข้อความระดับ 2 เหลือ 2 ข้อแรก (งดกิจกรรมกลางแจ้ง ใส่หน้ากาก) และเปลี่ยน \"ห้องปลอดฝุ่น\" เป็น \"อยู่ในอาคาร\"»","«เหตุผล: ตรงกับสิ่งที่โรงเรียนมี และตัดสินใจเร็วขึ้น»"],["«(สมมติ) 2 ใน 2 คน»"],["«ดีขึ้น แต่ผู้ทดลองเป็นคนละคน จึงเทียบตรง ๆ ไม่ได้»"]]]],["p","มีเงื่อนไขใดไม่เหมือนเดิมระหว่างสองรอบหรือไม่? ถ้ามี ผลการเปรียบเทียบอาจคลาดเคลื่อนอย่างไร"],["t",[[["«ไม่เหมือนเดิม: ผู้ทดลองรอบ 2 เป็นคนละคน และค่าจำลองแต่ละรอบไม่ผ่านจุดเดียวกันทุกครั้ง»","«ผลกระทบ: ข้อสรุปว่า \"ดีขึ้น\" อาจมาจากวิธีตรวจหรือตัวผู้ทดลอง ไม่ใช่การแก้ไข ต้องทดสอบซ้ำกับผู้ทดลองเดิมและจำนวนจุดที่มากขึ้น»"]]]]]},{"h":"4. สะท้อนคิดผลงานและกระบวนการของกลุ่ม","b":[["p","ใช้ผลทดสอบและข้อเสนอแนะเป็นหลักฐาน ไม่ใช้ความรู้สึกอย่างเดียว"],["t",[[["สิ่งที่สะท้อน"],["จุดแข็ง (พร้อมหลักฐาน)"],["จุดอ่อน (พร้อมหลักฐาน)"]],[["ผลงาน/ต้นแบบ"],["«จอที่กล่องแสดงระดับเองได้แม้ไม่มีเน็ต (หลักฐาน: ทดสอบปิด Wi-Fi)»","«ไฟสลับสีเมื่อไม่มีข้อมูล ไม่ติดเขียว (หลักฐาน: ถอดสายเซนเซอร์)»"],["«ยังไม่ได้ทดสอบกับเซนเซอร์จริงกลางแจ้งหลายสัปดาห์ และยังไม่ได้เทียบกับสถานีทางการ»","«ค่ากล่องเป็นค่าเฉลี่ยประมาณ 30 นาที ไม่ใช่ค่ามาตรฐาน 24 ชม.»"]],[["กระบวนการสร้างสรรค์ของกลุ่ม (ใบกิจกรรม 1–5)"],["«เริ่มจากข่าวจริงและตารางทางการ (ใบ 1–2)»","«ผสานความคิดเพื่อนจนได้ไฟ ข้อความ และตารางสิ่งที่ต้องทำ (ใบ 3)»"],["«ใบ 5 ทดสอบกับอุปกรณ์จริงน้อย เวลาไม่พอ»","«ไม่ได้ถามครูเวรและผู้ปกครองตัวจริง»"]]]],["p","ต้นแบบช่วยป้องกัน ลดความเสี่ยง หรือสนับสนุนการเตรียมพร้อมของกลุ่มเป้าหมายได้อย่างไร (จากผลทดลองเท่านั้น)"],["t",[[["«จากผลทดลอง (สมมติ): ต้นแบบทำให้ผู้ทดลองเห็นระดับฝุ่นและรู้ว่าต้องทำอะไรเร็วขึ้นในโหมดจำลอง แต่ยังสรุปไม่ได้ว่าลดการสัมผัสฝุ่นของนักเรียนจริง»","«ยืนยันได้จากผล: การแสดงระดับที่กล่องไม่ขึ้นกับเน็ต»","«ยังยืนยันไม่ได้: ว่าค่าเซนเซอร์ใกล้เคียงสถานีทางการแค่ไหน และครูกับผู้ปกครองทำตามข้อความจริงหรือไม่ ต้องทดสอบกับฝุ่นจริงและผู้ใช้จริงโดยมีครูดูแล»"]]]],["p","สิ่งใด “ยังไม่ควรนำไปใช้จริง” และผู้ใช้ควรอ้างอิงข้อมูล/คำเตือนจากหน่วยงานใดในเหตุฉุกเฉิน"],["t",[[["«ยังไม่ควรใช้จริง: การตัดสินใจงดเรียนหรือเปลี่ยนตารางตามค่าจากกล่องเพียงอย่างเดียว การส่งข้อความเข้ากลุ่มผู้ปกครองโดยไม่ขออนุญาต และการใช้เป็นคำแนะนำทางการแพทย์»","«ให้ติดตามค่าและประกาศทางการ เช่น Air4Thai (กรมควบคุมมลพิษ) และ ปภ. (สายด่วน 1784) หากมีอาการหายใจลำบากให้พบแพทย์ ไฟลามใกล้ชุมชนโทร 199»"]]]],["p","ตั้งคำถามกับกระบวนการสร้างสรรค์ของเรา: ขั้นตอนใดที่เราเลือกทางง่ายเกินไปหรือน่าจะทำต่างออกไป เพราะอะไร"],["t",[[["«ที่เลือกทางง่าย: ทดสอบด้วยโหมดจำลองแทนฝุ่นจริง และไม่ได้ถามครูเวรหรือผู้ปกครองตัวจริง»","«ควรทำต่าง: ขอให้ครูพาไปถามครูเวรและผู้ปกครองว่าตัดสินใจอย่างไรอยู่ และเทียบค่ากล่องกับสถานีทางการ 1–2 สัปดาห์ก่อนกำหนดข้อความ»","«เพราะเกณฑ์การตัดสินใจต้องมาจากคนที่ใช้จริงและข้อมูลจริง ไม่ใช่จากโหมดจำลอง»"]]]]]}]}},"team":["กลุ่มที่ «3»  ·  ชื่อกลุ่ม «ทีมธงฝุ่น»  ·  ภัยที่เลือก «หมอกควัน»  ·","สมาชิก 1) «นักเรียน ก»  ·  2) «นักเรียน ข»  ·  3) «นักเรียน ค»  ·","4) «นักเรียน ง»  ·  5) «นักเรียน จ»  ·  วันที่ ........ / ........ / ........"]},"wind":{"intro":["«ฉบับตัวอย่างเฉลยสำหรับครู — ภัยที่เลือก: วาตภัย/พายุฤดูร้อน (จังหวัดอุตรดิตถ์)»","ข้อความสีน้ำเงินคือแนวตอบตัวอย่าง นักเรียนต้องคิดและเขียนเอง ไม่ควรคัดลอก ส่วนเกณฑ์ประเมินของครูเว้นว่างไว้ (ชื่อนักเรียน ก ข ค ง จ เป็นชื่อสมมติ)","อ้างอิงข่าว: ไทยรัฐ 4 พ.ค. 2567 • มติชน 5 พ.ค. 2567 • ไทยพีบีเอส 1 พ.ค. 2565 (ประกาศ ฉ.8) ข่าวไม่ระบุความเร็วลม ตรวจเมื่อ 24 ต.ค. 2569","\"(สมมติ)\" ในใบกิจกรรมที่ 5–6 = ตัวอย่างวิธีเขียน ไม่ใช่ผลวัดจริง เกณฑ์ลมและค่า KMH_PER_HZ เป็นค่าสมมติ ต้องสอบเทียบเอง","ต้นแบบนี้ไม่ใช่ระบบเตือนภัยทางการ เตือนล่วงหน้าได้น้อย การเตือนจริงมาจากกรมอุตุฯ และยังไม่ได้ทดสอบกับอุปกรณ์และลมพายุจริง"],"acts":{"a1":{"pre":[["p","ภารกิจ : เลือกภัยธรรมชาติที่มีโอกาสเกิดหรือเคยเกิดขึ้นในจังหวัดอุตรดิตถ์ แล้วสืบค้นข้อมูลจากแหล่งที่เชื่อถือได้ เพื่อทำความเข้าใจความเสี่ยง โดยตั้งคำถามให้มากกว่าที่รู้ และกล้าตรวจสิ่งที่เคยเชื่อ ก่อนเสนอวิธีแก้"]],"secs":[{"h":"1. เลือกภัยและระบุบริบทพื้นที่","b":[["p","ใช้ข้อมูลจริงหรือสถานการณ์จำลองที่ครูกำหนด"],["p","☐ น้ำท่วม/น้ำป่า    ☐ ดินถล่ม    ☐ ภัยแล้ง    «☒» วาตภัย    ☐ ไฟป่า/หมอกควัน    ☐ อื่น ๆ ................."],["p","บริบทพื้นที่/สถานการณ์ที่กลุ่มสนใจ (เกิดที่ไหน เมื่อใด หรือมีเงื่อนไขอย่างไร)"],["t",[[["«3 พ.ค. 2567 ราว 16.30 น. พายุฤดูร้อนกระทบ 9 อำเภอของอุตรดิตถ์ รวม 45 ตำบล 122 หมู่บ้าน 664 หลังคาเรือน ต้นไม้และเสาไฟฟ้าหักโค่น ไฟดับหลายชั่วโมง อาคารโรงพยาบาลอุตรดิตถ์เสียหาย (ไทยรัฐ) • อ.ท่าปลา สวนทุเรียนเสียหายราว 500 ไร่ หลังคาสังกะสีและเหล็กถูกลมเปิด (มติชน)»","«ข้อสังเกต: เหตุเกิดช่วงเย็น และสิ่งที่ข่าวบอกว่าล้มหรือเสียหายคือต้นไม้ใหญ่ เสาไฟ และหลังคา ซึ่งสำรวจและเตรียมล่วงหน้าได้ ข่าวที่อ่านไม่ระบุความเร็วลม จึงสรุปไม่ได้ว่าลมแรงกี่ km/h»","«เงื่อนไขที่สนใจ: ผู้ที่อยู่นอกบ้านหรือขับรถจักรยานยนต์ตอนลมแรงเสี่ยงอันตราย และไฟดับหลายชั่วโมงทำให้รับข่าวยาก — ใช้หมู่บ้านสมมติ 1 แห่งในจังหวัดอุตรดิตถ์ที่มีต้นไม้ใหญ่และบ้านหลังคาสังกะสีเป็นพื้นที่ทดลอง»"]]]]]},{"h":"2. รวบรวมข้อมูลและตรวจสอบความน่าเชื่อถือ","b":[["t",[[["แหล่งข้อมูล/หน่วยงาน","(ชื่อหรือ URL ย่อ)"],["ข้อมูลสำคัญที่พบ"],["ตรวจสอบได้อย่างไร / วันที่เข้าถึง"]],[["1.« ไทยรัฐ»  ·","«ข่าวพายุฤดูร้อนอุตรดิตถ์ เผยแพร่ 4 พ.ค. 2567 (เหตุเกิด 3 พ.ค. 2567)»"],["«9 อำเภอ 45 ตำบล 122 หมู่บ้าน 664 หลังคาเรือน»","«ต้นไม้และเสาไฟฟ้าหักโค่น ไฟดับหลายชั่วโมง โรงพยาบาลอุตรดิตถ์เสียหาย»"],["«เป็นตัวเลขเบื้องต้นตามข่าว ไม่ระบุความเร็วลม ใช้ดูรูปแบบปัญหา»","«ลิงก์: thairath.co.th/news/local/north/2783044 เข้าถึง 24 ต.ค. 2569»"]],[["2.« มติชน»  ·","«ข่าวสวนทุเรียนและบ้านเรือน อ.ท่าปลา เผยแพร่ 5 พ.ค. 2567»"],["«อ.ท่าปลา 7 ตำบล 50 หมู่บ้าน 160 หลังคาเรือน ผู้ได้รับผลกระทบราว 720 คน»","«สวนทุเรียนเสียหายราว 500 ไร่ หลังคาสังกะสี/เหล็กถูกเปิด เสาไฟหักและเอียง»"],["«ตัวเลข อ.ท่าปลา ต่างจากไทยรัฐ (6 ตำบล 24 หมู่บ้าน 95 หลังคาเรือน) น่าจะสำรวจคนละเวลา จึงไม่เอามารวมกันเอง»","«ลิงก์: matichon.co.th/region/news_4561188 เข้าถึง 24 ต.ค. 2569»"]],[["3.« ไทยพีบีเอส»","«ข่าวประกาศกรมอุตุนิยมวิทยา ฉบับที่ 8 พายุฤดูร้อน เผยแพร่ 1 พ.ค. 2565»"],["«เตือนพายุฤดูร้อนบริเวณประเทศไทยตอนบนถึง 2 พ.ค. 2565 อุตรดิตถ์อยู่ในรายชื่อทั้ง 2 วัน»","«แนะนำเลี่ยงที่โล่งแจ้ง ใต้ต้นไม้ใหญ่ และป้ายที่ไม่แข็งแรง»"],["«เป็นประกาศปี 2565 คนละเหตุกับข่าวปี 2567 ใช้ดูว่ามีการเตือนล่วงหน้า ไม่ใช่หลักฐานว่าเตือนเหตุ 3 พ.ค. 2567»","«ลิงก์: thaipbs.or.th/news/content/315072 เข้าถึง 24 ต.ค. 2569»"]]]]]},{"h":"3. มองเหตุและผลให้รอบด้าน","b":[["t",[[["สาเหตุ/ปัจจัย (อย่างน้อย 2 ข้อ)"],["ผลกระทบต่อชีวิต ทรัพย์สิน ชุมชน หรือสิ่งแวดล้อม"]],[["1.« ลมแรงจากพายุฤดูร้อนทำให้ต้นไม้ใหญ่ เสาไฟ และหลังคาที่ยึดไม่แน่นหักหรือปลิว (ไทยรัฐ มติชน)»","«ข่าวไม่ได้บอกว่าต้นไม้ต้นใดอยู่ใกล้บ้าน จึงไม่สรุปว่าต้นไหนเสี่ยง»"],["1.« ไฟดับหลายชั่วโมง บ้านและสวนเสียหาย (ท่าปลา สวนทุเรียนราว 500 ไร่)»","«ไฟดับทำให้รับข่าวยาก ตรงกับโจทย์ของเรา (ไทยรัฐ มติชน)»"]],[["2.« จุดเสี่ยงในหมู่บ้านอาจยังไม่เคยถูกสำรวจ (ข้อสันนิษฐาน ต้องไปถามผู้ใหญ่บ้าน)»","«พายุมาเร็วช่วงเย็น คนอยู่นอกบ้านเตรียมตัวไม่ทัน»"],["2.« คนที่อยู่นอกบ้านหรือขับรถจักรยานยนต์ตอนลมแรงเสี่ยงอันตราย (ข้อสันนิษฐาน ข่าวที่อ่านไม่ระบุ)»","«ผู้สูงอายุอยู่คนเดียวไม่มีใครช่วยเก็บของหรือหาที่หลบ (ข้อสันนิษฐาน ต้องสอบถาม)»"]]]]]},{"h":"4. ใครเสี่ยงอย่างไร? ลองมองจากมุมผู้ได้รับผลกระทบ","b":[["p","กลุ่มที่ 2 ให้เลือกกลุ่มที่กลุ่มเราไม่ค่อยคุ้นเคยหรือมักถูกมองข้าม (เช่น ผู้พิการ ผู้ป่วยติดเตียง เด็กเล็ก แรงงานย้ายถิ่น)"],["t",[[["ผู้ได้รับผลกระทบ"],["ความเสี่ยง/สิ่งที่กังวล"],["ความต้องการที่สำคัญ"]],[["กลุ่มที่ 1:« ผู้ขับขี่จักรยานยนต์และคนที่อยู่นอกบ้านตอนเย็น»","«(กลุ่มที่เรานึกถึงเป็นอันดับแรก)»"],["«ไม่รู้ล่วงหน้าว่าลมกำลังแรงขึ้น และไม่มีที่หลบใกล้ทาง»","«ต้นไม้ ป้าย และเสาไฟข้างทางอาจล้มทับ»"],["«รู้ทันทีที่ลมแรงผิดปกติ และรู้ว่าที่หลบใกล้สุดอยู่ที่ใด»","«แผนที่จุดเสี่ยงและที่หลบ และข้อความแจ้งเมื่อถึงระดับที่ตกลงกัน»"]],[["กลุ่มที่ 2:« ผู้สูงอายุอยู่คนเดียวและบ้านใกล้ต้นไม้ใหญ่ หลังคาสังกะสี»","«(กลุ่มที่มักถูกมองข้าม — สมมติฐานของกลุ่ม ต้องไปถามผู้ใหญ่บ้าน)»"],["«เก็บของ ยึดหลังคา หรือตัดกิ่งไม้เองไม่ได้ และเมื่อไฟดับรับข่าวยาก»","«ไม่มีใครรู้ว่าบ้านนี้ต้องมีคนไปช่วยก่อน»"],["«บัตรตรวจบ้านที่ญาติหรือเพื่อนบ้านช่วยทำก่อนฤดูพายุ»","«รายชื่อบ้านที่ต้องช่วยก่อน (เก็บในพื้นที่อาสา ต้องใช้ PIN)»"]]]],["p","เลือกกลุ่มเป้าหมายหลัก 1 กลุ่ม และบอกเหตุผลที่เลือก"],["t",[[["«กลุ่มเป้าหมายหลัก: ผู้ที่อยู่นอกบ้านหรือขับรถจักรยานยนต์ตอนเย็นที่พายุมา และผู้สูงอายุอยู่คนเดียวใกล้ต้นไม้ใหญ่หรือบ้านหลังคาไม่แข็งแรง»","«เหตุผล: เหตุในข่าวเกิดช่วงเย็นราว 16.30 น. คนนอกบ้านมีเวลาตัดสินใจน้อย และผู้สูงอายุอยู่คนเดียวเตรียมบ้านเองได้ยาก»","«คนที่ช่วยเขาได้คือผู้ใหญ่บ้านและเพื่อนบ้าน ต้นแบบจึงเน้นสองอย่าง: เตรียมก่อนพายุ (แผนที่จุดเสี่ยง บัตรตรวจบ้าน) และรู้ทันทีเมื่อลมแรง เพราะเตือนล่วงหน้าได้น้อย»"]]]]]},{"h":"5. สิ่งที่รู้แล้ว / ยังไม่รู้ / ต้องหาต่อ","b":[["t",[[["สิ่งที่รู้จากหลักฐาน"],["สิ่งที่ยังไม่รู้ (คำถามที่ยังไม่มีคำตอบ)"],["จะสืบค้นหรือถามใคร/ที่ใด"]],[["«ไทยรัฐ 4 พ.ค. 2567: 9 อำเภอ 664 หลังคาเรือน ต้นไม้และเสาไฟล้ม ไฟดับหลายชั่วโมง»","«ประกาศกรมอุตุฯ ฉ.8 (ไทยพีบีเอส 2565) ระบุอุตรดิตถ์ในรายชื่อเตือนพายุฤดูร้อน»"],["«ในหมู่บ้านเรา ต้นไม้ใหญ่ ป้าย หลังคาสังกะสีหลังไหนเสี่ยงที่สุด?»","«ปกติชาวบ้านรู้ประกาศพายุฤดูร้อนทางไหน และทันก่อนพายุมาหรือไม่?»"],["«เดินสำรวจกับผู้ใหญ่บ้านตอนอากาศปกติ แล้วทำตารางจุดเสี่ยง»","«ถามชาวบ้านสัก 5 คน (ไม่จดชื่อ) ว่ารู้ประกาศเตือนจากช่องทางใดและเมื่อใด»"]],[["«ไทยรัฐและมติชนตรงกันว่าเกิดพายุช่วงเย็น 3 พ.ค. 2567 แต่ตัวเลข อ.ท่าปลา ต่างกัน»","«ข่าวที่อ่านไม่ระบุความเร็วลมที่วัดได้»"],["«ลมที่หมู่บ้านเราแรงเท่าไรเมื่อพายุมา ต่างจากสถานีอุตุฯ ใกล้เคียงหรือไม่?»","«ไฟดับแล้วชาวบ้านรับข่าวทางใด?»"],["«เก็บค่าลมสูงสุดของหมู่บ้านไว้ในชีต เทียบกับข่าวพายุแต่ละครั้ง»","«ถามผู้ใหญ่บ้านว่าตอนไฟดับใช้ช่องทางใดแจ้งข่าว (เช่น เสียงตามสาย วิทยุ)»"]]]]]},{"h":"6. ตั้งคำถามสำรวจปัญหา","b":[["p","ต้องมีทั้ง “ทำไม...?” และ “ถ้า...จะเป็นอย่างไร?” เพื่อขยายมุมมอง เช่น “ทำไมผู้สูงอายุจึงอาจได้รับผลกระทบจากน้ำป่ามากกว่าคนวัยทำงาน” / “ถ้าเกิดน้ำป่าในเวลากลางคืนและไม่มีอินเทอร์เน็ต จะเป็นอย่างไร”"],["p","คำถามที่ 1 “ทำไม...?” และเหตุใดคำถามนี้จึงสำคัญ"],["t",[[["«ทำไมคนในหมู่บ้านจึงยังเสี่ยงจากต้นไม้ใหญ่ ป้าย และหลังคา ทั้งที่กรมอุตุฯ เคยออกประกาศเตือนพายุฤดูร้อนที่ระบุอุตรดิตถ์ล่วงหน้า (เช่น ประกาศ ฉ.8 ปี 2565)?»","«สำคัญเพราะถ้ารู้ว่าปัญหาคือประกาศไปไม่ถึงชาวบ้าน ไม่มีใครสำรวจจุดเสี่ยง หรือไม่มีข้อตกลงว่าลมแรงแล้วทำอะไร จะออกแบบให้ข้อมูลและการเตรียมตัวถึงคนในหมู่บ้านได้ตรงจุด»"]]]],["p","คำถามที่ 2 “ถ้า...จะเป็นอย่างไร?” และเงื่อนไขใหม่ที่อยากสำรวจ"],["t",[[["«ถ้าพายุมาเร็วภายในชั่วโมงเดียวและชาวบ้านไม่ได้เปิดดูประกาศ หมู่บ้านจะรู้ได้อย่างไรว่าลมแรงผิดปกติและต้องเข้าที่หลบ?»","«เงื่อนไขใหม่ที่อยากสำรวจ: ไฟดับ เสียงลมกลบ และคนอยู่นอกบ้าน — ไฟที่ศาลา ข้อความถึงผู้ใหญ่บ้าน หรือเสียงเตือนสั้น ๆ อย่างไหนช่วยได้ และเสียงของบัซเซอร์เล็กไปถึงใครบ้าง?»"]]]]]},{"h":"7. ท้าทายสิ่งที่เคยเชื่อ","b":[["p","เขียนสิ่งที่เรา/คนทั่วไปเชื่อหรือทำเป็นปกติเมื่อเกิดภัยนี้ แล้วตรวจกับหลักฐานจากส่วนที่ 2"],["t",[[["สิ่งที่เคยเชื่อ/วิธีที่คุ้นเคย"],["ตรวจกับหลักฐานแล้วพบว่า (ตรง / ขัด / ยังไม่รู้)"],["ถ้าข้อสมมตินี้ใช้ไม่ได้ (เช่น ไฟดับ ไม่มีอินเทอร์เน็ต เกิดกลางคืน) จะเกิดอะไรขึ้น"]],[["1.« เคยเชื่อว่า \"พายุฤดูร้อนมักไม่ถึงบ้านเรา หรือมีแค่ฝนตกธรรมดา\"»"],["«ขัด: 3 พ.ค. 2567 พายุกระทบ 9 อำเภอของอุตรดิตถ์ ไฟดับหลายชั่วโมง และ อ.ท่าปลา สวนทุเรียนเสียหายราว 500 ไร่ (ไทยรัฐ มติชน)»"],["«พายุฤดูร้อนทำความเสียหายได้ทั้งตัวเมืองและอำเภอรอบนอก หมู่บ้านเราควรเตรียมตัวไว้ก่อนฤดู»"]],[["2.« เคยเชื่อว่า \"มีประกาศจากกรมอุตุฯ แล้ว ชาวบ้านก็รู้ทัน\"»"],["«ข้อมูลที่ทำให้สงสัย: ประกาศระบุอุตรดิตถ์ล่วงหน้าได้ (ไทยพีบีเอส 2565) แต่ข่าวปี 2567 เล่าความเสียหายจำนวนมาก ยังไม่รู้ว่าแต่ละคนได้รับประกาศทันหรือไม่ (ข้อสันนิษฐาน ต้องสำรวจ)»"],["«การมีประกาศไม่เท่ากับชาวบ้านรู้และพร้อมทำตาม ต้องถามชาวบ้านจริงก่อนสรุป»"]]]],["p","ข้อมูลหรือมุมมองที่ไม่คุ้นเคย หรือขัดกับที่เราคิด 1 เรื่อง — กลุ่มชะลอการตัดสินและสำรวจเพิ่มอย่างไรก่อนสรุป"],["t",[[["«ข้อมูลที่ขัดกับที่คิด: เดิมคิดว่ากรมอุตุฯ เตือนแล้วก็พอ แต่ข่าวเล่าความเสียหายจำนวนมากในหมู่บ้าน และพายุเกิดช่วงเย็นราว 16.30 น. ซึ่งอาจสั้นเกินไปสำหรับเตรียมตัว (ข้อสันนิษฐาน ต้องถาม)»","«ชะลอการตัดสิน: ยังไม่สรุปว่าโหนดวัดลมในหมู่บ้านจะเตือนล่วงหน้าได้ทัน (เดาว่าได้น้อย) จะบันทึกเวลาที่ลมขึ้นเทียบกับเวลาที่ฝนมาในการทดลอง และถามผู้ใหญ่บ้านว่าข่าวถึงชาวบ้านทางใด»","«ผลที่ปรับความคิด: เปลี่ยนโจทย์จาก \"สร้างเครื่องเตือนพายุ\" เป็น \"ให้รู้จุดเสี่ยงก่อนพายุและรู้ทันทีเมื่อลมแรง\" โดยแยกบทบาท: ประกาศกรมอุตุฯ เป็นตัวเตือนล่วงหน้า ส่วนโหนดของเราเป็นตัวยืนยันและบันทึกลมของหมู่บ้าน»"]]]]]}]},"a2":{"pre":[["p","ภารกิจ : นำข้อมูลจากใบกิจกรรมที่ 1 มากำหนดปัญหาที่เฉพาะเจาะจง มีผู้ใช้ชัดเจน แล้วสร้างโจทย์ออกแบบหลายแนวทางด้วยกลยุทธ์ที่ต่างกัน ก่อนเลือกโจทย์ที่แก้ได้ด้วยต้นแบบ"]],"secs":[{"h":"1. แยกสาเหตุ ปัญหาหลัก และผลกระทบ","b":[["t",[[["สาเหตุ (เหตุใดจึงเกิด)"],["ปัญหาหลัก (สิ่งที่ต้องแก้)"],["ผลกระทบ (สิ่งที่ตามมา)"]],[["«ไม่มีใครสำรวจจุดเสี่ยงพายุในหมู่บ้านไว้ล่วงหน้า (ข้อสันนิษฐาน ต้องถามผู้ใหญ่บ้าน)»","«ต้นไม้ใหญ่ ป้าย และหลังคาที่ยึดไม่แน่นอยู่ใกล้บ้านและทางสัญจร»"],["«ชาวบ้านไม่รู้ว่าลมในหมู่บ้านเริ่มแรงผิดปกติ และไม่รู้ว่าจุดไหนปลอดภัย»","«พายุมาเร็วช่วงเย็น ไฟดับทำให้รับข่าวยาก»"],["«ต้นไม้ เสาไฟ หรือหลังคาล้มทับบ้านหรือทางสัญจร ไฟดับหลายชั่วโมง (ไทยรัฐ)»","«คนที่อยู่นอกบ้านหรือขี่จักรยานยนต์เสี่ยงอันตราย»"]],[["«พายุฤดูร้อนมีข่าวช่วงต้น พ.ค. ทั้งปี 2565 และ 2567»","«ประกาศพายุที่ระบุอุตรดิตถ์ออกมาในช่วงเดียวกัน (ไทยพีบีเอส 2565)»"],["«ประกาศอยู่ในเว็บและข่าว ต้องมีคนส่งต่อ ไม่ถึงคนที่ไม่ใช้เว็บโดยอัตโนมัติ»","«ไฟดับแล้วช่องทางเดิมใช้ไม่ได้»"],["«บ้านใกล้ต้นไม้ใหญ่และหลังคาสังกะสีเสียหายก่อน (ข้อสันนิษฐานจากข่าวมติชน)»","«ผู้สูงอายุอยู่คนเดียวไม่รู้ว่าต้องเก็บของหรือหาที่หลบ (ข้อสันนิษฐาน ต้องสอบถาม)»"]]]],["p","จากข้อมูลข้างต้น กลุ่มต้องการแก้ “ปัญหาหลัก” เรื่องใดเพียง 1 เรื่อง เหตุใดจึงสำคัญ และขอบเขตของปัญหาอยู่ตรงไหน (เกิดที่ใด/กับใคร/เมื่อใด)"],["t",[[["«ปัญหาหลัก: ชาวบ้านในหมู่บ้านสมมติ จ.อุตรดิตถ์ ไม่รู้ล่วงหน้าว่าจุดไหนเสี่ยงเมื่อพายุมา และไม่รู้ทันทีเมื่อลมในหมู่บ้านแรงผิดปกติ เพราะไม่มีการสำรวจจุดเสี่ยง ไม่มีค่าลมของหมู่บ้าน และไม่มีข้อตกลงว่าลมแรงแล้วทำอะไร»","«สำคัญเพราะ: พายุฤดูร้อนมาเร็วช่วงเย็น ต้นไม้ เสาไฟ และหลังคาล้มทับได้ในไม่กี่นาที และไฟดับทำให้รับข่าวยาก»","«ขอบเขต: หมู่บ้านสมมติ 1 แห่ง ช่วงหน้าร้อน ทดลองกับกังหันและโหมดจำลอง ไม่ใช่ระบบเตือนภัยทางการ การเตือนล่วงหน้าจริงมาจากกรมอุตุนิยมวิทยา»"]]]]]},{"h":"2. รู้จักผู้ใช้และมองปัญหาจากหลายมุม","b":[["t",[[["คำถาม"],["คำตอบกลุ่มพร้อมหลักฐานจากใบกิจกรรมที่ 1"]],[["ผู้ที่ต้องการช่วยคือใคร?"],["«ผู้ขับขี่จักรยานยนต์และคนนอกบ้านตอนเย็น กับผู้สูงอายุอยู่คนเดียวใกล้ต้นไม้ใหญ่ ส่วนผู้ใช้ระบบโดยตรงคือผู้ใหญ่บ้านและอาสาที่ส่งต่อข้อความ»"]],[["ประสบปัญหาเมื่อใด/สถานการณ์ใด?"],["«ช่วงเย็นของหน้าร้อน ก่อนและระหว่างพายุฤดูร้อน (เช่น 3 พ.ค. 2567 ราว 16.30 น.) เมื่อลมเริ่มแรงและไฟอาจดับ»"]],[["ต้องการความช่วยเหลือแบบใด?"],["«ชาวบ้านรู้จุดเสี่ยงก่อนพายุและเตรียมของไว้ ผู้ใหญ่บ้านรู้ทันทีเมื่อลมแรงถึงระดับที่ตกลงกัน คนใกล้ศาลารู้ว่าต้องเข้าที่หลบ»"]]]],["p","มองปัญหาจากมุมอื่นอย่างน้อย 2 มุม เช่น ชุมชน/วัฒนธรรม เศรษฐกิจ/ค่าใช้จ่าย ความปลอดภัย/จริยธรรม หน่วยงานที่เกี่ยวข้อง"],["t",[[["มุมมอง"],["เห็นปัญหานี้อย่างไร และต้องการอะไร"]],[["มุมมองที่ 1:« ผู้ใหญ่บ้านและ อบต.»"],["«ต้องตัดสินใจเรื่องเสียงเตือนหรือประกาศในหมู่บ้าน แต่ไม่อยากเตือนผิดจนชาวบ้านเลิกเชื่อ»","«ต้องการข้อความสั้นที่บอกว่าลมแรงระดับไหนและควรทำอะไร»"]],[["มุมมองที่ 2:« ผู้บริหารและงบประมาณโรงเรียน»"],["«งบน้อย ไม่อยากให้นักเรียนปีนเสาหรือต้นไม้เพื่อติดตั้งอุปกรณ์»","«ต้องขออนุญาตก่อนติดตั้งเสา และให้ผู้ใหญ่เป็นผู้ติดตั้ง»"]]]]]},{"h":"3. เขียนข้อความกำหนดปัญหา (Problem Statement)","b":[["p","รูปประโยคช่วยคิด : “(กลุ่มเป้าหมาย) ประสบปัญหา (ปัญหา) เมื่อ (สถานการณ์) เนื่องจาก (สาเหตุหรือข้อจำกัด) ส่งผลให้ (ผลกระทบ)”"],["p","ข้อความกำหนดปัญหาของกลุ่ม (เขียนให้เจาะจง ไม่ใช่แค่ชื่อภัย)"],["t",[[["«ชาวบ้านในหมู่บ้านสมมติ จ.อุตรดิตถ์ ประสบปัญหาไม่รู้จุดเสี่ยงของต้นไม้ใหญ่ ป้าย และหลังคาก่อนพายุฤดูร้อนมา และไม่รู้ทันทีเมื่อลมในหมู่บ้านแรงผิดปกติช่วงเย็น เนื่องจากไม่มีการสำรวจจุดเสี่ยง ไม่มีค่าลมของหมู่บ้านเอง และไฟอาจดับจนรับข่าวไม่ได้ ส่งผลให้ผู้ที่อยู่นอกบ้านและผู้สูงอายุอยู่คนเดียวเสี่ยงถูกล้มทับหรือเข้าที่หลบไม่ทัน»","«ตรวจความเฉพาะเจาะจง: มีกลุ่มเป้าหมาย สถานการณ์ สาเหตุ และผลกระทบครบ ไม่ใช่แค่คำว่า \"พายุแรง\"»"]]]]]},{"h":"4. สร้างโจทย์ออกแบบหลายแนวทาง (How Might We...?)","b":[["p","รูปประโยคช่วยคิด : “เราจะออกแบบหรือพัฒนาอะไร เพื่อให้ (ใคร) สามารถ (ทำอะไรเพื่อลดความเสี่ยง) ภายใต้ (เงื่อนไข) ได้อย่างไร?”"],["t",[[["«เราจะออกแบบยามลมหมู่บ้านราคาประหยัดที่ ม.2 ทำได้ เพื่อให้ชาวบ้านรู้จุดเสี่ยงก่อนพายุและผู้ใหญ่บ้านรู้ทันทีเมื่อลมแรงผิดปกติ ภายใต้เงื่อนไขที่พายุมาเร็ว ไฟอาจดับ และกังหันทำเองยังไม่ได้สอบเทียบ ได้อย่างไร?»","«โจทย์ทางเลือกจากกลยุทธ์ต่างกัน: (เตรียมก่อน) ทำให้ทุกบ้านรู้จุดเสี่ยงและเก็บของก่อนฤดูพายุได้อย่างไร • (เทคโนโลยี) ทำให้หมู่บ้านวัดลมเองและแจ้งอัตโนมัติได้อย่างไร • (คน) ทำให้ประกาศกรมอุตุฯ ถึงทุกบ้านโดยคนส่งต่อได้อย่างไร»"]]]]]},{"h":"5. สืบค้นเชิงสร้างสรรค์ : เรียนรู้จากวิธีของผู้อื่น","b":[["p","หาวิธีหรือนวัตกรรมที่ผู้อื่นใช้กับปัญหาคล้ายกัน (ภัยอื่น พื้นที่อื่น หรือกลุ่มผู้ใช้อื่น) จากแหล่งที่เชื่อถือได้ แล้วเทียบกับปัญหาของเรา"],["t",[[["วิธี/แนวทางของผู้อื่น (ที่มา)"],["ปัญหา สถานการณ์ หรือความต้องการของเขาเหมือน/ต่างจากของเราอย่างไร"],["แนวคิดที่นำมาใช้ตั้งหรือปรับโจทย์ของเรา"]],[["1.« ประกาศเตือนพายุฤดูร้อนของกรมอุตุนิยมวิทยา ระบุจังหวัดล่วงหน้า พร้อมคำแนะนำ เช่น เลี่ยงที่โล่งแจ้ง ใต้ต้นไม้ใหญ่ และป้ายที่ไม่แข็งแรง»","«(ข่าวไทยพีบีเอส 1 พ.ค. 2565)»"],["«เหมือน: ปัญหาเดียวกัน ต้องให้คนรู้ก่อนว่าพายุมา»","«ต่าง: เป็นประกาศระดับจังหวัดและภาค ไม่ระบุจุดเสี่ยงในหมู่บ้านและไม่ได้วัดลมที่หมู่บ้านเรา»"],["«ใช้คำแนะนำเดียวกับประกาศ (เลี่ยงที่โล่งแจ้ง ต้นไม้ใหญ่ ป้าย) เป็นข้อความระดับ 2–3 ไม่เขียนคำเตือนเอง และส่งต่อประกาศจริงให้ชาวบ้าน»"]],[["2.« ถุงลม (windsock) ที่ใช้ดูทิศและความแรงลมด้วยตา เช่น ที่สนามบิน»","«(ความรู้ทั่วไป ไม่มีลิงก์ — ยังไม่ได้ตรวจกับแหล่งใด)»"],["«ต่างเรื่อง แต่ปัญหาคล้ายกัน: ให้คนรู้ความแรงลมทันทีโดยไม่ต้องใช้ไฟฟ้าหรืออ่านตัวเลข»","«ต่าง: ถุงลมบอกแค่คร่าว ๆ ไม่มีตัวเลข ไม่ส่งข้อความ และไม่มีเกณฑ์ว่าแรงแค่ไหนต้องทำอะไร»"],["«นำมาทำธงลมที่ศาลาเป็นส่วนเสริมแบบไม่ใช้ไฟฟ้า ใช้คู่กับระดับ 0–3 และป้ายอธิบาย»"]]]],["p","ตั้งคำถาม “ถ้า...จะเป็นอย่างไร?” 1 ข้อ แล้วลองตอบ — คำตอบทำให้เข้าใจปัญหาลึกขึ้น หรือทำให้ได้ทางแก้ใหม่อย่างไร"],["t",[[["«ถ้ากังหันติดขัดหรือหลุด ระบบจะอ่านได้ 0 km/h เหมือนลมสงบ ไฟที่ศาลาจะเป็นสีเขียวหรือไม่?»","«คำตอบ: เป็นไปได้ ต้นแบบแยก \"กังหันเสีย\" ออกจาก \"ลมสงบ\" ไม่ได้ ส่วนบอร์ดดับหรือเน็ตหลุดนาน ระบบจะแสดง \"ไม่มีข้อมูล\" (ไฟสลับ) ไม่ใช่สีเขียว»","«ผล: ได้โจทย์ใหม่ — ต้องมีรอบตรวจกังหันด้วยตาโดยผู้ใหญ่ และช่องให้อาสากรอกค่าลมโดยประมาณจากการสังเกตเมื่อสงสัยว่ากังหันเสีย พร้อมป้ายว่าเป็นค่าสังเกต»"]]]]]},{"h":"6. ตรวจความชัดเจนและปรับกรอบโจทย์ (Reframe)","b":[["p","«☒» ระบุผู้ใช้ชัด    «☒» ช่วยลดความเสี่ยงจริง    «☒» ขอบเขตพอดีกับ 15 ชั่วโมง    «☒» ทำต้นแบบจำลองได้    «☒» ไม่อันตราย"],["p","โจทย์ก่อนรับข้อเสนอแนะ / ใครเสนอให้มองต่าง / โจทย์หลังปรับ / ข้อมูลหรือเหตุผลที่ยืนยันว่าดีขึ้น"],["t",[[["«โจทย์ก่อนรับข้อเสนอแนะ: \"ทำกังหันวัดลมแล้วเตือนชาวบ้านเมื่อลมแรง\"»","«ข้อเสนอแนะ (เพื่อนกลุ่มอื่นและครู): พายุฤดูร้อนมาเร็ว กังหันเตือนล่วงหน้าได้น้อย ควรให้ชาวบ้านเตรียมตัวก่อนพายุด้วย และกังหันที่ติดขัดจะอ่านเป็นลมสงบได้»","«โจทย์หลังปรับ: ทำยามลมหมู่บ้าน — แผนที่จุดเสี่ยงและบัตรตรวจบ้านก่อนพายุ กังหันและโหนดวัดลมที่เสา ไฟ 3 ดวงที่ศาลา ข้อความ \"สิ่งที่ควรทำ\" และช่องให้ผู้ใหญ่กรอกค่าลมโดยประมาณเมื่อสงสัยว่ากังหันเสีย»","«เหตุผลที่ดีขึ้น: ตรงกับข่าว 3 พ.ค. 2567 ที่ความเสียหายมาจากต้นไม้ เสาไฟ และหลังคา ซึ่งเตรียมก่อนได้ และยอมรับว่าการเตือนล่วงหน้าจริงมาจากกรมอุตุนิยมวิทยา»"]]]]]}]},"a3":{"pre":[["p","ภารกิจ : ต้องคิดเองก่อนใช้ AI จากนั้นแลกเปลี่ยนกับเพื่อนและใช้ AI เพื่อขยาย/ตรวจสอบ ไม่ใช่คัดลอกคำตอบโดยไม่คิด ใบกิจกรรมนี้ดูว่าเราทำงานกับความคิดของผู้อื่นอย่างไร ตั้งแต่เปรียบเทียบ ผสาน ต่อยอด จนสังเคราะห์"]],"secs":[{"h":"1. คิดด้วยตนเองก่อนเปิด AI","b":[["p","ทุกคนกรอกบัตรรายบุคคล 3 แนวคิดต่างกลไก (หน้าถัดไป) ก่อนเปิด AI และก่อนแลกเปลี่ยนความคิดกับเพื่อน บัตรนี้คือ “ความคิดของฉัน” ที่จะใช้เปรียบเทียบและผสานกับผู้อื่นในส่วนที่ 2–5"],["p","«☒» สมาชิกทุกคนส่งบัตรก่อนเปิด AI ครบแล้ว"],["p","ลำดับการทำงานในใบกิจกรรมนี้"],["t",[[["ส่วน"],["ทำอะไร"],["ทำกับใคร / ใช้อะไร"]],[["1"],["คิดเอง 3 แนวทางลงบัตรรายบุคคล"],["ทำคนเดียว ก่อนเปิด AI"]],[["2"],["เปรียบเทียบความคิดของเรากับความคิดของเพื่อน"],["ฟังและบันทึกร่วมกันในกลุ่ม"]],[["3"],["ผสานส่วนที่ดีของเพื่อนอย่างน้อย 2 คนเข้ากับความคิดของเรา"],["สมาชิกในกลุ่ม"]],[["4"],["ต่อยอดกับเพื่อนและ AI แล้วตรวจสอบก่อนนำไปใช้"],["กลุ่ม + AI (มนุษย์เป็นผู้ตรวจและเลือก)"]],[["5"],["สังเคราะห์เป็น 3 แนวคิดที่แตกต่างกันจริงของกลุ่ม"],["ทั้งกลุ่ม"]]]],["sh","บัตรคิดเองก่อนใช้ AI (รายบุคคล)"],["p","ให้บันทึกก่อนเปิด AI / ก่อนแลกเปลี่ยนข้อเสนอของ AI เพื่อเก็บ “ความคิดของฉัน” ไว้เป็นฐานสำหรับเปรียบเทียบและผสานกับความคิดของผู้อื่น"],["p","ชื่อ–สกุล «นักเรียน จ (ตัวอย่าง)»  ·  ห้อง   ·  เลขที่   ·  กลุ่ม «4»  ·"],["p","โจทย์ภัยธรรมชาติที่ต้องการแก้ «ให้ชาวบ้านรู้จุดเสี่ยงก่อนพายุมา»  ·"],["p","คิดเอง 3 แนวทาง โดยพยายามให้กลไกช่วยลดความเสี่ยงต่างกัน"],["p","เขียนชื่อวิธี หลักการทำงาน ผู้ใช้ และเหตุผลที่คาดว่าจะช่วยแก้ปัญหาได้"],["p","แนวคิดที่ 1: ชื่อวิธี / ทำงานอย่างไร / ช่วยใคร / เหตุผล (เขียนโดยไม่ใช้ AI)"],["t",[[["«ชื่อวิธี: แผนที่จุดเสี่ยงพายุของหมู่บ้าน — เดินสำรวจกับผู้ใหญ่ ถ่ายรูปต้นไม้ใหญ่ ป้าย หลังคาสังกะสี และที่หลบ ทำเป็นป้ายแผนที่และ QR ที่ศาลา»","«ช่วยใคร: ชาวบ้านและผู้ใหญ่บ้าน • เหตุผล: ไม่ใช้ไฟฟ้าหรือเน็ต ใช้ได้ตอนไฟดับ แต่ต้องมีคนอัปเดตปีละครั้ง»"]]]],["p","แนวคิดที่ 2: ชื่อวิธี / ทำงานอย่างไร / ช่วยใคร / เหตุผล (เขียนโดยไม่ใช้ AI)"],["t",[[["«ชื่อวิธี: กังหันถ้วยวัดลมทำเอง — นับรอบด้วยบอร์ด IPST-WiFi คำนวณ km/h แสดงระดับบนจอที่เสาและส่งขึ้นเว็บ»","«ช่วยใคร: ผู้ใหญ่บ้านและอาสา • เหตุผล: ได้ค่าลมจริงของหมู่บ้านโดยไม่ต้องรอข่าว ใช้พาวเวอร์แบงก์ 5 V ได้»"]]]],["p","แนวคิดที่ 3: ชื่อวิธี / ทำงานอย่างไร / ช่วยใคร / เหตุผล (เขียนโดยไม่ใช้ AI)"],["t",[[["«ชื่อวิธี: เครือข่ายส่งต่อประกาศกรมอุตุฯ — อาสาในกลุ่มหมู่บ้านส่งต่อประกาศเตือนพายุฤดูร้อนพร้อมข้อความสิ่งที่ควรทำ»","«ช่วยใคร: ทุกบ้านที่อยู่ในกลุ่ม • เหตุผล: ประกาศจริงมาจากกรมอุตุฯ ไม่ต้องสร้างเครื่องวัด แต่ต้องมีคนส่งต่อทันเวลา»"]]]],["p","แนวคิดทั้ง 3 ต่างกันตรงหลักการทำงานหรือวิธีช่วยผู้ใช้อย่างไร (ไม่ใช่แค่ชื่อหรือสี)"],["t",[[["«ต่างที่กลไก: (1) แผนที่ติดที่ศาลา คนเตรียมก่อนพายุ (2) เครื่องวัดลมที่เสาเห็นลมจริงของหมู่บ้าน (3) คนส่งต่อประกาศอุตุฯ ที่ออกล่วงหน้า»","«แต่ละแบบแก้จุดอ่อนของอีกแบบ: (1) ไม่บอกว่าลมแรงตอนนี้ (2) เตือนล่วงหน้าได้น้อยและแยกกังหันเสียจากลมสงบไม่ได้ (3) ต้องมีคนส่งต่อและไม่รู้ลมของหมู่บ้านเอง»"]]]],["p","ฉันเริ่มคิดเวลา «09.10»  ส่งบัตรนี้เวลา «09.30»   «☒» ก่อนเปิด AI    ☐ ก่อนอ่านคำตอบจาก AI"],["p","หมายเหตุ: นักเรียนทุกคนต้องคิดด้วยตนเอง 3 แนวทางที่พยายามใช้กลไกช่วยลดความเสี่ยงแตกต่างกันก่อนใช้ AI ทั้งนี้จำนวนแนวคิดเป็นเพียงเงื่อนไขให้มีหลักฐานเพียงพอ ไม่ใช้จำนวนแนวคิดเพียงอย่างเดียวตัดสินความสร้างสรรค์"]]},{"h":"2. เปรียบเทียบความคิดของเรากับความคิดของเพื่อน","b":[["p","สมาชิกแต่ละคนเล่าแนวคิดที่ตนชอบที่สุด 1 ข้อ ทุกคนฟังให้ครบ แล้วบันทึกว่าเหมือนหรือต่างจากความคิดของตนเองอย่างไร"],["t",[[["สมาชิก/ผู้เสนอ"],["ข้อเสนอ (สรุปสั้น)"],["เหมือน/ต่างจากความคิดของฉันอย่างไร"],["สิ่งที่กลุ่มเห็นว่าน่าสนใจ"]],[["1.« ก»  ·"],["«บัตรตรวจบ้านก่อนฤดูพายุ แจกทุกหลังช่วง ก.พ.–เม.ย. เช่น เก็บของเบา ตรวจหลังคา ชาร์จไฟฉาย (ตัดกิ่งสูงให้ผู้ใหญ่ทำ)»"],["«เหมือน: เตรียมก่อนพายุ ต่าง: ของ ก ทำทีละบ้านด้วยคน ใช้ได้ตอนไฟดับ ของฉันวัดลมด้วยเครื่อง»"],["«ทุกบ้านรู้ว่าต้องเตรียมอะไรก่อนพายุ»"]],[["2.« ข»  ·"],["«ไฟ 3 ดวงที่ศาลา เขียว เหลือง แดงกะพริบ มองเห็นจากลานและถนนหน้าศาลา»"],["«เหมือน: บอกด้วยสี ต่าง: ของ ข อยู่ที่ศาลาให้ทุกคนเห็น ของฉันเป็นจอ OLED ที่เสาต้องเดินไปดู»"],["«คนใกล้ศาลาเห็นระดับโดยไม่ต้องใช้มือถือ»"]],[["3.« ค»  ·"],["«ตารางสิ่งที่ต้องทำในแต่ละระดับ ติดที่ศาลา เช่น ระดับ 2 = เข้าอาคาร ห่างกระจกและต้นไม้ใหญ่ งดขับจักรยานยนต์»"],["«ต่างมาก: ไม่ใช้เทคโนโลยี แต่ใช้ร่วมกับของฉันได้เมื่อรู้ระดับ»"],["«ทุกคนทำตามข้อตกลงเดียวกัน และอ้างคำแนะนำของกรมอุตุฯ ได้ (เลี่ยงที่โล่งแจ้ง ใต้ต้นไม้ใหญ่ ป้าย)»"]],[["4.« ง»  ·"],["«บันทึกลมสูงสุดรายวันและเวลาลงชีต เทียบกับข่าวพายุแต่ละครั้ง เพื่อปรับเกณฑ์ภายหลัง»"],["«ต่าง: ของ ง ดูย้อนหลัง ไม่เตือนทันที แต่ใช้ข้อมูลที่ของฉันวัดได้»"],["«ทำให้เกณฑ์ของหมู่บ้านมีหลักฐาน แทนตัวเลขสมมติ»"]],[["5.  ·","​"],["​","​"],["​","​"],["​","​"]]]],["p","จุดร่วมและจุดต่างที่เห็นเด่นที่สุดในข้อเสนอของสมาชิกทั้งหมด"],["t",[[["«จุดร่วม: ทุกคนต้องการให้ \"ชาวบ้านรู้ก่อนและรู้ว่าต้องทำอะไร\" ไม่ใช่รอดูท้องฟ้าอย่างเดียว»","«จุดต่าง: เตรียมก่อนพายุ (ก ค) หรือรู้ตอนลมแรง (ข จ) หรือเก็บข้อมูลย้อนหลัง (ง) ยังไม่มีใครคิดว่าถ้ากังหันติดขัดจะอ่านเป็นลมสงบ หรือค่าลมต่างจากสถานีอุตุฯ จะทำอย่างไร»"]]]]]},{"h":"3. ผสานความคิดของสมาชิก","b":[["p","เลือกส่วนที่ดีของข้อเสนอจากสมาชิกอย่างน้อย 2 คน มาผสานกับความคิดของตนเอง"],["t",[[["เจ้าของแนวคิดที่ 1 + ส่วนที่เลือก"],["เจ้าของแนวคิดที่ 2 + ส่วนที่เลือก"],["เจ้าของแนวคิดที่ 3 + ส่วนที่เลือก"]],[["ชื่อ« ก»  ·","ส่วนที่เลือก« บัตรตรวจบ้านก่อนฤดูพายุ»","«เหตุผล: ลดความเสียหายก่อนพายุมา เพราะเตือนล่วงหน้าได้น้อย»","«ปรับ: ผู้ใหญ่ตัดกิ่งสูง นักเรียนไม่ปีน และบัตรไม่ติดชื่อที่อยู่ในที่สาธารณะ»"],["ชื่อ« ข»  ·","ส่วนที่เลือก« ไฟ 3 ดวงที่ศาลา»","«เหตุผล: คนใกล้ศาลาเห็นระดับโดยไม่ต้องใช้มือถือ»","«ปรับ: ติดป้ายบอกว่าเหลือง = ระดับ 1 แดงกะพริบช้า = ระดับ 2 แดงกะพริบเร็ว = ระดับ 3»"],["ชื่อ« ค»  ·","ส่วนที่เลือก« ตารางสิ่งที่ต้องทำแต่ละระดับ»","«เหตุผล: ทุกคนทำตามข้อตกลงเดียวกัน»","«ปรับ: อ้างคำแนะนำของกรมอุตุฯ ไม่เขียนคำแนะนำเฉพาะบุคคลเอง»"]]]],["p","ความคิดใหม่ที่เกิดจากการผสาน — ส่วนใดของเพื่อนอย่างน้อย 2 คนที่นำมาผสานกับความคิดของเรา และผลเป็นอย่างไร"],["t",[[["«ความคิดใหม่: \"ยามลมหมู่บ้าน\" = แผนที่จุดเสี่ยงและบัตรตรวจบ้านก่อนพายุ (ของฉันและ ก) + กังหันและโหนดวัดลมที่เสา (ของฉัน) + ไฟ 3 ดวงที่ศาลา (ของ ข)»","«ผลที่ได้: ก่อนพายุทุกบ้านเตรียมตัวได้ ระหว่างพายุผู้ใหญ่บ้านได้ข้อความและคนใกล้ศาลาเห็นไฟ ถ้าเน็ตหลุด จอ OLED ที่เสายังแสดงระดับเอง และไฟที่ศาลาสลับสีบอกว่า \"ไม่มีข้อมูล\"»","«ส่วนของ ค (ตาราง) ใส่เป็นข้อความ \"สิ่งที่ควรทำ\" ในทุกระดับ ส่วนของ ง (บันทึกลมสูงสุด) ใช้ชีต Readings ของระบบที่เก็บค่าให้อยู่แล้ว»"]]]]]},{"h":"4. ต่อยอดกับเพื่อนและ AI","b":[["p","AI เป็นอีกแหล่งข้อเสนอหนึ่ง กลุ่มต้องเป็นผู้ตรวจและเลือก Prompt ต้องระบุปัญหา ผู้ใช้ ข้อจำกัด (เช่น ไม่มีไฟ/ไม่มีเน็ต) และขอทางเลือกที่ ม.2 ทำต้นแบบได้"],["p","Prompt ที่ใช้จริง (ไม่เขียนข้อมูลส่วนบุคคลหรือข้อมูลอ่อนไหว)"],["t",[[["«ฉันเป็นนักเรียน ม.2 ในจังหวัดอุตรดิตถ์ กำลังทำต้นแบบ \"ยามลมหมู่บ้าน\" ให้ชาวบ้านรู้จุดเสี่ยงก่อนพายุและให้ผู้ใหญ่บ้านรู้เมื่อลมแรงผิดปกติ ผู้ใช้คือผู้ใหญ่บ้านและชาวบ้านใกล้ศาลา»","«ข้อจำกัด: ไม่มีเครื่องวัดลมมาตรฐาน งบจำกัด ใช้บอร์ด IPST-WiFi (ESP32) ที่โรงเรียนมี กังหันถ้วยทำเองต้องสอบเทียบเอง และพายุมาเร็วจนเตือนล่วงหน้าได้น้อย»","«ขอทางเลือก 5 แนวทางที่ ม.2 ทำเป็นต้นแบบจำลองได้ พร้อมข้อควรระวังด้านความปลอดภัยในการติดตั้งและทดสอบ (ไม่ปีนที่สูง ไม่ทดสอบตอนฟ้าคะนอง)»"]]]],["t",[[["ข้อเสนอที่ AI ให้"],["เหตุผลรับ/ไม่รับ (ความปลอดภัย–ผู้ใช้–ทรัพยากร)"],["ตรวจสอบหรือปรับด้วยตนเอง/ร่วมกับเพื่อน"]],[["1.« ทำตารางสอบเทียบกังหันกับพัดลมในร่ม 3 ความเร็ว เทียบกับเครื่องวัดลมมือถือของห้องวิทย์»"],["«รับ: ตรงกับข้อจำกัดว่ากังหันทำเองยังไม่ได้สอบเทียบ และได้ฝึกวัดและทำตาราง»"],["«จดรอบต่อวินาทีกับ km/h ที่เครื่องอ้างอิงอ่านได้ 3 ความเร็ว หาค่า KMH_PER_HZ (กลุ่มกำหนดเองว่ายอมให้ต่างได้เท่าไร) ถ้าไม่มีเครื่องอ้างอิงให้เขียนว่า \"ยังไม่สอบเทียบ\"»"]],[["2.« ทดสอบกังหันกลางแจ้งตอนฝนฟ้าคะนองเพื่อดูว่าเตือนทันหรือไม่»"],["«ไม่รับ: เสี่ยงฟ้าผ่าและวัสดุปลิว ห้ามอยู่กลางแจ้งหรือใกล้เสาโลหะตอนฟ้าคะนอง»"],["«ใช้โหมดจำลอง และเทียบกับข่าวหรือข้อมูลสถานีอุตุฯ ย้อนหลังแทน ผู้ใหญ่เป็นผู้ติดตั้งตอนอากาศปกติ»"]]]],["p","AI ช่วยตรงไหน? เราคัดทิ้ง/แก้ไขอะไรเพราะเหตุใด และใช้แหล่งใดตรวจสอบคำแนะนำที่เกี่ยวกับภัย"],["t",[[["«AI ช่วย: เสนอให้สอบเทียบกังหันกับพัดลมและเครื่องวัดลมอ้างอิง และช่วยร่างข้อความแจ้ง 4 ระดับ»","«เราคัดทิ้ง: การทดสอบกลางแจ้งตอนฟ้าคะนอง การให้นักเรียนติดกังหันบนเสาโลหะสูงหรือหลังคา และตัวเลขเกณฑ์ลมที่ AI เสนอโดยไม่บอกที่มา»","«ตรวจสอบกับ: ประกาศกรมอุตุนิยมวิทยา (tmd.go.th โทร 1182) ครู ผู้ใหญ่บ้าน/อบต. และ ปภ. (1784) สายไฟขาดห้ามแตะ ให้แจ้งการไฟฟ้า»"]]]],["p","ผังที่มาของความคิดใหม่ — เชื่อมความคิดของเพื่อน/AI เข้ากับความคิดของเรา"],["t",[[["ความคิดตั้งต้น (ของใคร)"],["ส่วนที่ต่อยอดจากเพื่อน/AI"],["ข้อค้นพบหรือมุมมองใหม่ที่เกิดขึ้น"],["ต่างจากข้อเสนอเดิมอย่างไร"]],[["«ของฉัน: กังหันและโหนดวัดลมที่เสา แสดงระดับเองไม่พึ่งเน็ต»"],["«จาก ก: บัตรตรวจบ้าน»","«จาก ข: ไฟ 3 ดวงที่ศาลา»"],["«แสดงผล 3 ชั้น (จอที่เสา ไฟที่ศาลา ข้อความผู้ใหญ่บ้าน) และเตรียมก่อนพายุด้วยแผนที่และบัตร»"],["«เดิมมีกังหันอย่างเดียว ใหม่ชาวบ้านเตรียมก่อนพายุ คนใกล้ศาลาเห็นไฟ ผู้ใหญ่บ้านได้ข้อความ»"]],[["«ของ ค: ตารางสิ่งที่ต้องทำแต่ละระดับ»"],["«จาก AI: ตารางสอบเทียบกับพัดลมและเครื่องวัดลมอ้างอิง»"],["«ต้องบอกด้วยว่าค่าของเราเป็น \"ค่าโดยประมาณ ยังไม่สอบเทียบ\" จนกว่าจะมีตารางเทียบ»"],["«เดิมใช้ค่าสมมติ 2.4 km/h ต่อรอบ/วินาที ใหม่มีตารางเทียบและป้ายบอกสถานะการสอบเทียบ»"]]]]]},{"h":"5. สังเคราะห์เป็น 3 แนวคิดที่แตกต่างกันจริง","b":[["p","ส่วนนี้เป็น 3 แนวทางของกลุ่ม ส่วนรายบุคคลให้ตรวจบัตรคิดเอง 3 แนวทางของแต่ละคน ไม่ใช้ผลรวมกลุ่มแทนความคิดของคนใดคนหนึ่ง"],["t",[[["แนวคิด/วิธีทำงาน"],["ที่มา: ใครคิด (สมาชิก/AI) จุดแข็งหรือมุมมองของใครที่นำมาใช้ และต่อยอดส่วนใด"],["เหมาะกับใครและลดความเสี่ยงอย่างไร"]],[["1.« ยามลม: กังหัน + แจ้งมือถือ»","«กังหันถ้วย + reed switch + IPST-WiFi ส่งค่าลมไป Apps Script แล้วแจ้ง Telegram/LINE ตามระดับ 0–3»"],["«ฉันคิดกังหันและโหนด ก คิดข้อความถึงผู้ใหญ่บ้าน AI เสนอสอบเทียบกับพัดลม»"],["«เหมาะกับผู้ใหญ่บ้านและอาสาที่มีมือถือ»","«ลดความเสี่ยงโดยรู้ทันทีเมื่อลมแรงผิดปกติ และบอกคนใกล้เคียงได้เร็วขึ้น»"]],[["2.« ไฟ 3 ดวงที่ศาลา + ตารางสิ่งที่ต้องทำ»","«ไฟเปลี่ยนตามระดับ และมีป้ายบอกว่าแต่ละสีต้องทำอะไร»"],["«ข คิดไฟ ค คิดตาราง ฉันคิดให้ไฟสลับบอกเมื่อไม่มีข้อมูล»"],["«ชาวบ้านใกล้ศาลา รวมคนไม่มีมือถือ»","«ลดความเสี่ยงโดยให้เห็นระดับและรู้ว่าต้องเข้าที่หลบ»"]],[["3.« แผนที่จุดเสี่ยง + บัตรตรวจบ้าน»","«เดินสำรวจต้นไม้ใหญ่ ป้าย หลังคา และที่หลบ ทำเป็นแผนที่ติดที่ศาลา และบัตรตรวจบ้านก่อนฤดูพายุ»"],["«ก คิดบัตร ง คิดบันทึกลมสูงสุดเทียบข่าว ฉันคิดแผนที่ AI เตือนเรื่องความปลอดภัยการติดตั้ง»"],["«ผู้สูงอายุอยู่คนเดียวและบ้านใกล้ต้นไม้ใหญ่»","«ลดความเสี่ยงโดยเตรียมก่อนพายุ ไม่ต้องพึ่งเทคโนโลยี»"]]]],["p","แนวคิดที่กลุ่มภูมิใจที่สุด ต่างจากก่อนผสาน/ก่อนใช้ AI อย่างไร (ระบุสิ่งที่คิดเองชัดเจน) และเหตุใดจึงรวมเป็นผลงานหนึ่งเดียวของกลุ่มได้"],["t",[[["«แนวคิดที่ภูมิใจที่สุด: แผนที่จุดเสี่ยงคู่กับกังหัน — เพราะพายุมาเร็วและเตือนล่วงหน้าได้น้อย การรู้จุดเสี่ยงก่อนช่วยได้มากกว่ารอสัญญาณ ต่างจากก่อนผสานที่ฉันมีแค่กังหันที่บอกเมื่อลมแรงแล้ว»","«สิ่งที่ฉันคิดเอง: กังหันและโหนด แผนที่จุดเสี่ยง ไฟสลับเมื่อไม่มีข้อมูล • จากเพื่อน: บัตรตรวจบ้าน ไฟ 3 ดวง ตารางสิ่งที่ต้องทำ บันทึกลมสูงสุด • จาก AI: สอบเทียบกับพัดลมและเครื่องวัดลม»","«รวมเป็นผลงานเดียวได้เพราะทุกส่วนใช้ \"ระดับ 0–3\" เดียวกัน และส่วนที่ใช้ไฟฟ้ากับส่วนที่ไม่ใช้ช่วยกันเมื่ออีกส่วนใช้ไม่ได้»"]]]]]}]},"a4":{"pre":[["p","ภารกิจ : ใช้ 3 ทางเลือกที่สร้างไว้ เปรียบเทียบความเหมาะสมและความปลอดภัย แล้วทำภาพร่าง/ผังงานที่ผู้อื่นนำไปสร้างต้นแบบได้ จากนั้นทดลองบนกระดาษ รับข้อเสนอแนะ และปรับเป็นแบบร่างรุ่นที่ 2"]],"secs":[{"h":"1. เปรียบเทียบ 3 แนวคิดโดยดูผู้ใช้และข้อจำกัด","b":[["t",[[["แนวคิด"],["ข้อดีต่อผู้ใช้"],["ข้อจำกัด/ความเสี่ยง"],["ทำได้จริงภายในเวลาอย่างไร"]],[["1.« ยามลม: กังหัน + แจ้งมือถือ»"],["«รู้ลมจริงของหมู่บ้านและเก็บประวัติไว้ปรับเกณฑ์»","«ผู้ใหญ่บ้านได้ข้อความเมื่อลมถึงระดับที่ตกลงกัน»"],["«พายุมาเร็ว เตือนล่วงหน้าได้น้อย และกังหันที่ติดขัดอ่านเป็นลมสงบ»","«ค่าลมขึ้นกับตำแหน่งติดตั้งและยังไม่ได้สอบเทียบ»"],["«ใช้ IPST-WiFi + กังหันถ้วยทำเอง + Apps Script (มีชุดโค้ดต้นแบบชุดวาตภัยให้ปรับ)»","«ทดสอบด้วยโหมดจำลองและพัดลมในร่ม ไม่ต้องรอพายุจริง»"]],[["2.« ไฟ 3 ดวงที่ศาลา + ตารางสิ่งที่ต้องทำ»"],["«ทุกคนใกล้ศาลาเห็นสถานะโดยไม่ต้องใช้มือถือ»"],["«ไฟไม่บอกตัวเลข และไฟอย่างเดียวไม่มีข้อมูลลมให้ตรวจ ต้องพึ่งโหนดวัดลม»"],["«ใช้ชุดไฟ LED 3 สีของบอร์ดตัวที่ 2 ปิดเสียงก่อน ทำง่าย»"]],[["3.« แผนที่จุดเสี่ยง + บัตรตรวจบ้าน»"],["«เตรียมก่อนพายุได้โดยไม่พึ่งไฟฟ้า และตรงกับสิ่งที่เสียหายในข่าว (ต้นไม้ เสาไฟ หลังคา)»"],["«ไม่บอกว่าลมกำลังแรงตอนนี้ และบ้านที่ไม่ทำตามบัตรก็ไม่ได้ประโยชน์»"],["«ทำเป็นแผนที่กระดาษ ป้าย QR และบัตรได้ใน 5 ชั่วโมงลงมือ แต่การตัดต้นไม้หรือซ่อมหลังคาต้องให้ผู้ใหญ่ทำ»"]]]],["p","แนวคิดที่เลือกคือ «แนวคิดที่ 1 + กังหันวัดลมของแนวคิดที่ 2» เหตุผลที่เลือก (แก้ตรงโจทย์ ผู้ใช้ ทรัพยากร ความปลอดภัย)"],["t",[[["«แก้ตรงโจทย์: เลือกแนวคิดที่ 1 เป็นแกน เพราะวัดลมของหมู่บ้านเองและแจ้งผู้ใหญ่บ้านทันที แล้วนำไฟ 3 ดวงของแนวคิดที่ 2 มารวมด้วย ส่วนแผนที่จุดเสี่ยงของแนวคิดที่ 3 ทำเป็นงานกระดาษคู่ขนานและเพิ่มเข้าระบบในรุ่นที่ 2»","«ผู้ใช้: ผู้ใหญ่บ้านได้ข้อความพร้อม \"สิ่งที่ควรทำ\" ส่วนคนใกล้ศาลาเห็นสีไฟ»","«ทรัพยากร/ความปลอดภัย: ใช้บอร์ดที่โรงเรียนมี ใช้ไฟ 5 V จากพาวเวอร์แบงก์ ผู้ใหญ่เป็นผู้ติดตั้งเสา ทดสอบด้วยโหมดจำลองและพัดลมในร่ม ไม่ทดสอบตอนฟ้าคะนอง»"]]]],["p","เหตุผลที่ไม่เลือกอีก 2 แนวคิด (หรือส่วนที่ตัดสินใจละทิ้ง) และเงื่อนไขใดอาจทำให้เปลี่ยนการตัดสินใจ"],["t",[[["«แนวคิดที่ 2 เดี่ยว ๆ: ไฟอย่างเดียวไม่มีข้อมูลลมให้ตรวจ จึงเก็บไว้เป็นส่วนแสดงผลของแนวคิดที่ 1»","«แนวคิดที่ 3: แผนที่และบัตรตรวจบ้านต้องให้ผู้ใหญ่ร่วมสำรวจและอนุมัติ และไม่บอกว่าลมแรงตอนนี้ ใน 15 ชั่วโมงทำได้เพียงแผนที่ตัวอย่างบริเวณศาลา จึงไม่ทำทั้งหมู่บ้าน»","«เปลี่ยนใจได้ถ้า: ติดกังหันบนเสาที่โล่งไม่ได้ → วัดจากระดับต่ำและเขียนว่าเป็นลมของจุดนั้น • หรือสอบเทียบไม่ได้เลย → เรียกว่า \"ความเร็วสัมพัทธ์\" และตั้งระดับจากการสังเกต»"]]]]]},{"h":"2. ร่างแบบรุ่นที่ 1 และอธิบายหลักการทำงาน","b":[["p","วาดแผนภาพ/ผังงานขนาดใหญ่ ระบุส่วนประกอบ ลำดับการทำงาน ทางเข้าของข้อมูล ผลลัพธ์ และจุดที่ผู้ใช้จะโต้ตอบกับต้นแบบ"],["t",[[["พื้นที่ภาพร่าง/ผังงาน (ใช้ลูกศร หมายเลข และคำอธิบายกำกับ)"]]]],["p","อธิบาย 1) ต้นแบบเริ่มทำงานอย่างไร 2) ผู้ใช้ได้รับประโยชน์อะไร 3) หากไฟดับ/ไม่มีอินเทอร์เน็ตจะทำอย่างไร"],["t",[[["«1) เริ่มทำงาน: เปิดโหนดที่เสา นับรอบกังหัน 3 ช่วง ช่วงละ 10 วินาที เลือกค่าสูงสุดแปลงเป็น km/h แล้วเทียบเกณฑ์ จอ OLED ที่เสาแสดงระดับ 0–3 และส่งค่าขึ้นเว็บ ส่วนไฟที่ศาลาถามเว็บแล้วเปลี่ยนสี»","«2) ประโยชน์: ผู้ใหญ่บ้านได้ข้อความ \"ระดับ 2 ลมแรงผิดปกติ เข้าอาคาร\" ส่วนไฟที่ศาลาให้คนใกล้เคียงเห็น พักระหว่างรอบ 2 นาที ถี่ขึ้นเป็น 20 วินาทีเมื่อถึงระดับ 3»","«3) ไฟดับ/ไม่มีเน็ต: โหนดและไฟที่ศาลาใช้พาวเวอร์แบงก์ (ยังไม่ได้ทดสอบว่าอยู่ได้กี่ชั่วโมง) โหนดแสดงระดับบนจอเอง ไฟที่ศาลาสลับไฟบอกว่า \"ไม่มีข้อมูล\" ไม่ติดเขียวค้าง ถ้าเซนเซอร์เงียบเกิน 30 นาที เว็บแสดง \"ไม่มีข้อมูล\"»"]]]]]},{"h":"3. ขยายความคิดให้ละเอียดพอสำหรับสร้างจริง","b":[["p","เขียนให้เพื่อนกลุ่มอื่นอ่านแล้วเข้าใจว่าต้องสร้างอะไร"],["t",[[["ส่วนประกอบของต้นแบบ"],["ลักษณะเฉพาะ/วิธีทำงาน","(ขนาด วัสดุที่คิดไว้ ข้อมูลเข้า–ออก)"],["ผู้ใช้โต้ตอบกับส่วนนี้อย่างไร"]],[["1.« โหนดวัดลมที่เสา»","«IPST-WiFi + กังหันถ้วย + reed switch + จอ OLED»"],["«เข้า: รอบกังหันต่อ 10 วินาที แปลงเป็น km/h ด้วยค่า KMH_PER_HZ เลือกค่าสูงสุดของ 3 ช่วง»","«ออก: ระดับ 0–3 + จอ OLED + ส่งข้อมูลขึ้นเว็บ»"],["«ผู้ใช้ไม่ต้องกดอะไร ดูระดับบนจอที่เสา»","«ผู้ใหญ่ติดตั้งเสาและตรวจว่ากังหันหมุนอิสระเป็นประจำ»"]],[["2.« เซิร์ฟเวอร์»","«Google Apps Script Web App + Google Sheet»"],["«รับข้อมูลที่มีรหัสลับ คำนวณระดับ เก็บประวัติลม»","«แจ้ง Telegram/LINE และแสดงหน้าเว็บบนมือถือ»"],["«ผู้ใหญ่บ้านเปิดหน้าเว็บดูสถานะและกราฟลม»","«อาสาส่งต่อประกาศกรมอุตุฯ ในกลุ่มหมู่บ้าน»"]],[["3.« ไฟ 3 ดวงที่ศาลา»","«IPST-WiFi ตัวที่ 2 + LED เขียว/เหลือง/แดง (ปิดเสียงก่อน)»"],["«ถามระดับจากเว็บทุก 10–20 วินาที»","«เขียว/เหลืองติดนิ่ง แดงกะพริบ (ช้า = ระดับ 2 เร็ว = ระดับ 3)»"],["«คนใกล้ศาลาดูสีไฟและอ่านป้ายอธิบายสี»","«คนไม่มีมือถือก็เห็นระดับลมได้»"]]]],["p","จุดที่ยังคลุมเครือหรือยังตอบไม่ได้ในแบบร่าง และสิ่งที่ต้องทดลองหรือหาข้อมูลเพิ่มก่อนสร้าง"],["t",[[["«ค่าลมจากกังหันทำเองต่างจากเครื่องวัดมาตรฐานเท่าไร และต่างตามตำแหน่งติดตั้งหรือไม่ — ต้องสอบเทียบกับพัดลม 3 ความเร็วและเครื่องวัดลมของห้องวิทย์ (แนวทาง: ใช้ค่าสูงสุดของ 3 ช่วง)»","«เกณฑ์ลม 30/50/70 km/h เป็นค่าสมมติ — ยังไม่รู้ว่าลมเท่าไรที่หมู่บ้านเราเริ่มอันตรายจริง ต้องเก็บข้อมูลหลายพายุและถามผู้ใหญ่บ้านหรือกรมอุตุฯ»","«ระบบจะเตือนทันก่อนพายุจริงหรือไม่ — เดาว่าได้น้อยมาก ต้องบันทึกเวลาที่ลมขึ้นเทียบเวลาที่ฝนมาในการทดลอง และถามผู้ใหญ่บ้านว่าข้อความไปถึงใครใน 5 นาที»"]]]]]},{"h":"4. ทดลองบนกระดาษและปรับเป็นแบบร่างรุ่นที่ 2","b":[["p","ทดลองเดินตามสถานการณ์จำลอง 1 รอบ (บนกระดาษหรือสวมบทบาท) โดยใช้แบบร่างรุ่นที่ 1 — ผู้ใช้ทำอะไรเป็นขั้นแรก และติดขัดตรงไหน"],["t",[[["«สถานการณ์จำลอง (สมมติ): ตอนเย็นลมขึ้นจาก 20 เป็น 55 km/h ภายใน 10 นาที ฝนยังไม่ตก ผู้ใช้คือผู้ใหญ่บ้าน ก ถือมือถืออยู่ที่ศาลา»","«ขั้นแรกที่ผู้ใหญ่ทำ: เปิดข้อความเตือน แล้วเปิดหน้าเว็บ ติดขัด: ข้อความบอกแค่ \"ระดับ 2\" ไม่รู้ว่าต้องบอกชาวบ้านว่าอะไร ที่หลบอยู่ตรงไหน และบ้านไหนต้องช่วยก่อน»","«ติดขัดอีก: วันที่สงสัยว่ากังหันติด ผู้ใหญ่ไม่มีช่องบอกระบบว่าลมจริงแรงแค่ไหน และไม่รู้ว่าค่าบนจอเชื่อได้หรือไม่»"]]]],["p","ข้อเสนอแนะที่เฉพาะเจาะจงจากเพื่อน/ครู (เขียนว่าใครเสนอเรื่องใด)"],["t",[[["ข้อเสนอแนะ (ใครเสนอ)"],["สิ่งที่ปรับในแบบร่างรุ่นที่ 2"],["เหตุผล/ผลที่คาดว่าจะดีขึ้น"]],[["1.« เพื่อน ฉ (กลุ่มอื่น): ข้อความเตือนควรบอกว่าต้องทำอะไรและหลบที่ไหน»"],["«เพิ่มบรรทัด \"สิ่งที่ควรทำ\" ตามระดับ เช่น ระดับ 2 อยู่ในอาคารแข็งแรง ห่างกระจกและต้นไม้ใหญ่ งดขับจักรยานยนต์ และเพิ่มแผนที่จุดเสี่ยงและที่หลบในหน้าเว็บและป้ายที่ศาลา»"],["«ผู้ใหญ่ไม่ต้องเดา และชาวบ้านรู้ที่หลบก่อนพายุมา»"]],[["2.« ครู: ต้องมีช่องกรอกค่าลมด้วยมือเมื่อสงสัยว่ากังหันเสีย และห้ามให้นักเรียนปีนเสา»"],["«เพิ่มช่องกรอกค่าลมโดยประมาณจากการสังเกตในพื้นที่อาสาสมัคร (ใส่ PIN) พร้อมป้าย \"ค่าสังเกต\" และให้ผู้ใหญ่เป็นผู้ติดตั้งและตรวจเสาตอนอากาศปกติ»"],["«ยังรู้ระดับลมได้แม้สงสัยว่ากังหันเสีย และนักเรียนปลอดภัยตอนติดตั้ง»"]]]],["t",[[["ภาพร่างรุ่นที่ 2 (วาดเฉพาะส่วนที่เปลี่ยน)"]]]],["p","แบบร่างรุ่นที่ 2 ต่างจากรุ่นที่ 1 อย่างไร และมีแนวทางหรือส่วนใดที่ตัดสินใจละทิ้งเพราะไม่ช่วยแก้ปัญหา"],["t",[[["«ต่างจากรุ่นที่ 1: เพิ่มข้อความ \"สิ่งที่ควรทำ\" ตามระดับ เพิ่มแผนที่จุดเสี่ยงและที่หลบในหน้าเว็บและป้ายที่ศาลา เพิ่มช่องให้ผู้ใหญ่กรอกค่าลมโดยประมาณเมื่อสงสัยว่ากังหันเสีย (ส่วนอื่นเหมือนเดิม)»","«ละทิ้ง: การทดสอบกลางแจ้งตอนฟ้าคะนอง และการให้นักเรียนปีนเสาหรือหลังคาเพื่อติดตั้ง»","«เพราะเสี่ยงฟ้าผ่าและตกจากที่สูง และไม่ช่วยแก้ปัญหาหลักคือให้ชาวบ้านรู้จุดเสี่ยงและที่หลบก่อนพายุ»"]]]]]},{"h":"5. ให้ครูตรวจแบบร่างก่อนสร้างต้นแบบ","b":[["p","☐ แบบร่างชัดเจนพอให้ผู้อื่นสร้างตามได้    ☐ ปลอดภัย ไม่ต้องทดลองในภัยจริง    ☐ อนุญาตให้สร้างต้นแบบ"],["p","ข้อเสนอแนะจากครู (ใช้เป็นข้อมูลย้อนกลับก่อนลงมือสร้าง)"],["t",[[["​","​"]]]]]}]},"a5":{"pre":[["p","ภารกิจ : สร้างต้นแบบตามภาพร่าง อธิบายสิ่งที่ทำจริง แก้ปัญหาเมื่อเจออุปสรรค และตรวจสอบการใช้ AI อย่างรอบคอบ"]],"secs":[{"h":"1. ทบทวนผู้ใช้และข้อกำหนดก่อนสร้าง","b":[["p","ใช้ข้อมูลจากใบกิจกรรมที่ 2 และแบบร่างรุ่นที่ 2 จากใบกิจกรรมที่ 4"],["t",[[["ผู้ใช้/กลุ่มเป้าหมาย"],["ความต้องการและข้อจำกัดสำคัญ"],["ส่วนของต้นแบบที่จะตอบความต้องการนี้"]],[["ผู้ใช้หลัก:« ผู้ใหญ่บ้านและอาสาของหมู่บ้าน (ผู้ตัดสินใจและผู้ส่งต่อข้อความ)»"],["«ต้องรู้ทันทีเมื่อลมแรงผิดปกติ ข้อความสั้นและบอกสิ่งที่ควรทำ ไม่เตือนผิดจนชาวบ้านเลิกเชื่อ»"],["«หน้าเว็บมือถือ + แจ้งเตือน Telegram/LINE + ข้อความ \"สิ่งที่ควรทำ\"»"]],[["ผู้ใช้อื่นที่อาจเกี่ยวข้อง:« ชาวบ้านใกล้ศาลาที่ไม่ได้ใช้มือถือ/ไม่อ่านกลุ่ม»"],["«ต้องการสัญญาณที่เห็นง่ายจากลานและถนน และรู้ว่าที่หลบอยู่ที่ใด»"],["«ไฟ 3 ดวงที่ศาลา และแผนที่จุดเสี่ยง/ที่หลบที่ติดที่ศาลา»"]]]]]},{"h":"2. เตรียมความพร้อมและเลือกใช้ทรัพยากร","b":[["p","☐ ครูตรวจแผนแล้ว    «☒» วัสดุปลอดภัย    «☒» ไม่ทดลองในภัยจริง    «☒» ไม่ใช้ไฟฟ้าเสี่ยงอันตราย    «☒» กำหนดผู้รับผิดชอบ"],["t",[[["รายการ"],["เลือกใช้/เหตุผล"],["ข้อควรระวัง/การตรวจสอบ/ทางเลือกที่ปลอดภัย"]],[["วัสดุ–อุปกรณ์"],["«IPST-WiFi 2 ตัว กังหันถ้วยทำเอง (ถ้วยพลาสติกหรือลูกปิงปองผ่าซีก แกนไม้/ท่อ PVC) reed switch พร้อมแม่เหล็ก LED เขียว/เหลือง/แดง พร้อมตัวต้านทาน 220 Ω พาวเวอร์แบงก์ กล่องกันฝน»","«เลือกเพราะโรงเรียนมีบอร์ดอยู่แล้ว วัสดุหาง่าย และทดสอบด้วยพัดลมในร่มและโหมดจำลองได้»"],["«ใช้ไฟ 5 V จากพาวเวอร์แบงก์เท่านั้น ผู้ใหญ่เป็นผู้ติดตั้งเสา นักเรียนไม่ปีนหลังคา ต้นไม้ หรือเสา ไม่ติดบนเสาโลหะสูงช่วงฟ้าคะนอง»","«ตรวจเลขขา (ลม GPIO27) และการต่อ reed switch กับคู่มือบอร์ดของโรงเรียนก่อนต่อสาย»"]],[["เครื่องมือ–เทคโนโลยี"],["«Thonny/microBlock เขียน MicroPython ลงบอร์ด • Google Apps Script + Google Sheets • Telegram Bot»","«เลือกเพราะฟรี ใช้บัญชี Google ของโรงเรียนได้»"],["«รหัสลับและโทเคนเก็บใน Script Properties ห้ามใส่ในโค้ดหรือโพสต์ในกลุ่ม»","«ไฟล์ config.py ที่มีรหัส Wi-Fi ไม่ส่งต่อ»"]],[["AI (ถ้าใช้)"],["«ใช้ AI อธิบายโค้ดนับรอบกังหันที่ไม่เข้าใจ และช่วยเรียบเรียงข้อความแจ้งระดับให้สั้น»","«ไม่ให้ AI กำหนดเกณฑ์ลมหรือสั่งให้ชาวบ้านทำสิ่งเสี่ยง»"],["«ตรวจกับประกาศกรมอุตุฯ ครู ผู้ใหญ่บ้าน/อบต. ห้ามใส่ชื่อชาวบ้านหรือที่อยู่ใน Prompt»","«เกณฑ์ลมใช้ค่าสมมติที่ระบุไว้ชัด จนกว่าจะได้ข้อมูลจากหน่วยงานหรือการเก็บข้อมูลจริง»"]]]]]},{"h":"3. วางแผนการสร้างและคาดการณ์อุปสรรค","b":[["t",[[["ขั้นตอนลงมือสร้าง"],["ผู้รับผิดชอบ"],["หลักฐานตรวจความก้าวหน้า"]],[["ขั้น 1« ทำกังหันถ้วยและต่อ reed switch เข้าบอร์ด ทดสอบนับรอบด้วยการหมุนมือและดูค่าบนจอ»"],["«จ (ฮาร์ดแวร์)»"],["«ภาพกังหัน + บันทึกรอบที่บอร์ดนับเทียบกับที่นับด้วยตา»"]],[["ขั้น 2« สร้างเว็บแอป Apps Script + Google Sheet รันชุดค่าวาตภัย ตั้ง Script Properties และทดสอบด้วยโหมดจำลอง»"],["«ก (เซิร์ฟเวอร์)»"],["«ภาพหน้าเว็บ + ข้อความทดสอบใน Telegram»"]],[["ขั้น 3« เขียนโค้ดบอร์ดส่งข้อมูลขึ้นเว็บ และต่อไฟ 3 ดวงที่ศาลา»"],["«ค (โค้ดบอร์ด) ข (ไฟ 3 ดวง)»"],["«วิดีโอสั้นไฟเปลี่ยนสีตามค่าลมจำลอง»"]],[["ขั้น 4« ทดสอบระบบรวม สอบเทียบกับพัดลมในร่ม และซ้อมสถานการณ์เน็ตหลุด/กังหันติดขัดจำลอง»"],["«ทั้งกลุ่ม»"],["«ตารางสอบเทียบ + ใบบันทึกผลทดสอบ + ภาพถ่าย»"]]]],["p","อันตราย/ข้อจำกัดที่คาด และวิธีป้องกันหรือแผนสำรองก่อนลงมือสร้าง"],["t",[[["อันตราย/ข้อจำกัดที่คาด"],["ผลกระทบหากเกิดขึ้น"],["มาตรการป้องกัน/ทางสำรอง"],["ตรวจแล้วพบอะไร"]],[["«ปีนเสาหรือหลังคาเพื่อติดตั้งกังหัน หรือทดสอบกลางแจ้งตอนฟ้าคะนอง»"],["«ตกจากที่สูง ฟ้าผ่า วัสดุปลิวโดนตัว»"],["«ผู้ใหญ่ติดตั้งเสาตอนอากาศปกติ นักเรียนทดสอบในร่มด้วยพัดลมและโหมดจำลอง ห้ามอยู่กลางแจ้งหรือใกล้เสาโลหะตอนฟ้าคะนอง»"],["«(สมมติ) ทดสอบทั้งหมดในห้องด้วยพัดลมและโหมดจำลอง ไม่มีใครขึ้นที่สูง»"]],[["«กังหันฝืดหรือหลุด ค่าลมต่ำกว่าจริง หรือกิ่งไม้/ขยะติดกังหัน»"],["«ไฟที่ศาลาเป็นเขียวทั้งที่ลมแรง ผู้ใหญ่ตัดสินใจช้า»"],["«ผู้ใหญ่ตรวจว่ากังหันหมุนอิสระด้วยตาเป็นประจำและหลังพายุ เทียบกับลมจริงที่สังเกตได้ และมีช่องกรอกค่าสังเกตเมื่อสงสัย»"],["«(สมมติ) ทดลองบังคับกังหันให้ติด ระบบแสดง 0 km/h จริง จึงเพิ่มข้อความเตือนในป้ายและรอบตรวจ»"]]]]]},{"h":"4. บันทึกการสร้างอย่างมีหลักฐาน","b":[["t",[[["ลำดับ"],["สิ่งที่ลงมือทำจริง (ระบุสิ่งที่เปลี่ยนจากแผน ถ้ามี)"],["ผู้ลงมือ/ภาพหรือไฟล์หลักฐาน"]],[["1"],["«ต่อ reed switch ระหว่าง GPIO27 กับ GND (โค้ดตั้งขาเป็น PULL_UP) ตรวจเลขขากับคู่มือบอร์ดของโรงเรียนก่อน ตั้ง HAZARD=\"wind\" และ SIMULATE=True ก่อน แล้วค่อยเปลี่ยนเป็น False เมื่อต่อกังหันจริง»"],["«จ / ภาพถ่ายวงจร»"]],[["2"],["«สร้างเว็บแอป: วางโค้ด Code.gs และ Index.html ตั้ง Script Properties รัน setup() แล้วรัน usePresetWind แล้ว Deploy เป็น Web App»"],["«ก / ภาพหน้าเว็บ + ข้อความทดสอบ»"]],[["3"],["«ใส่ Wi-Fi/URL/รหัสลับในไฟล์ config.py แล้วอัปโหลดไฟล์ขึ้นบอร์ด ตั้ง CHANNELS_ON=(\"wind_kmh\",) เพราะยังไม่ต่อที่วัดฝน แล้วรันโหมดจริง»"],["«ค / ภาพหน้าจอ (ซ่อนรหัสก่อนแนบ)»"]],[["4"],["«ต่อบอร์ดไฟ: LED เขียว GPIO5 เหลือง GPIO19 แดง GPIO23 ผ่านตัวต้านทาน 220 Ω และตั้ง SOUND_ON=False ก่อน เปิดเสียงเมื่อผู้ใหญ่ตกลงความหมายของเสียงแล้ว»"],["«ข / วิดีโอไฟ 3 ดวง»"]]]],["p","สรุป: ตอนนี้ต้นแบบทำงานได้หรือแสดงหลักการใดแล้ว และยังทำไม่ได้ส่วนใด"],["t",[[["«(สมมติ — ตัวอย่างวิธีเขียน) ทำงานได้/แสดงหลักการ: ค่าลมจำลองขึ้น-ลง → ตัดสินระดับ 0–3 → จอที่เสาแสดงระดับ → ส่งขึ้นเว็บและมือถือ → ไฟที่ศาลาเปลี่ยนสีตาม»","«ยังทำไม่ได้: วัดลมจริงตอนพายุ • เตือนล่วงหน้าก่อนพายุมา • ยืนยันว่าค่า km/h ตรงเครื่องมาตรฐาน • ใช้แทนประกาศกรมอุตุฯ • ส่วนที่ยังไม่ได้ทดสอบกับอุปกรณ์จริงให้เขียนว่า \"ยังไม่ทดสอบ\"»"]]]]]},{"h":"5. เมื่อพบอุปสรรค เราคิดและแก้อย่างไร","b":[["t",[[["อุปสรรค/สาเหตุที่คาด"],["ทางเลือกที่เสนอ"],["วิธีที่ลองจริง/ผลที่พบ"]],[["1.« ค่าที่กังหันอ่านต่ำกว่าเครื่องวัดมือถือเมื่อพัดลมแรง ทำให้ระดับต่ำกว่าจริง»"],["«สอบเทียบ KMH_PER_HZ ใหม่จากตารางพัดลม 3 ความเร็ว และเขียนว่า \"ค่าโดยประมาณ ยังไม่ได้เทียบกับลมพายุจริง\"»"],["«(สมมติ) หลังปรับ ค่าต่างจากเครื่องอ้างอิงน้อยลงที่ 3 ความเร็ว แต่ยังไม่รู้ว่าลมพายุที่เร็วกว่าพัดลมจะตรงหรือไม่»"]],[["2.« ลมกระโชกสั้นอาจหลุดการนับ เพราะนับครั้งละ 10 วินาที»"],["«ใช้ค่าสูงสุดของ 3 ช่วง (ค่าตั้งต้นของโค้ด) และบันทึกว่าเป็นค่าประมาณ ไม่ใช่ค่ากระโชกสูงสุดจริง»"],["«(สมมติ) เมื่อจำลองลมกระโชกราว 3 วินาที ค่าที่ได้ยังต่ำกว่าจริง จึงบันทึกเป็นข้อจำกัด»"]]]],["p","ตัวอย่าง 1 เหตุการณ์ที่กลุ่มเปลี่ยนแผนเอง (ระบุก่อน–หลัง และเหตุผล)"],["t",[[["«ก่อน: วางแผนใช้ค่าตั้งต้น 2.4 km/h ต่อรอบ/วินาที และเกณฑ์ลม 30/50/70 km/h»","«หลัง: ใช้ค่าจากตารางสอบเทียบ เขียนกำกับว่า \"ค่าโดยประมาณ\" และบอกสถานะ \"ยังไม่สอบเทียบกับลมจริง\" บนหน้าเว็บ»","«เหตุผล: (สมมติ) ค่าตั้งต้นเป็นตัวเลขสมมติที่ต่างจากเครื่องอ้างอิง และเกณฑ์ 30/50/70 ไม่ได้มาจากหน่วยงาน จึงต้องบอกผู้ใช้ตรง ๆ»"]]]]]},{"h":"6. บันทึกการใช้ AI อย่างรับผิดชอบ","b":[["t",[[["ใช้ AI ช่วยงานใด/ข้อความคำสั่งย่อ"],["AI เสนออะไร"],["เราตรวจและปรับเองอย่างไร"]],[["1.« ให้ AI อธิบายโค้ดนับรอบกังหัน (การขัดจังหวะ และการกันสัญญาณเด้ง) และการหาค่าสูงสุดของ 3 ช่วง»"],["«อธิบายว่า reed switch อาจเด้งหลายครั้งต่อการปิดหนึ่งครั้ง โค้ดจึงข้ามสัญญาณที่มาถี่เกิน 5 มิลลิวินาที และค่าสูงสุดช่วยกันลมกระโชกหลุด»"],["«ทดลองในโหมดจำลองและหมุนกังหันด้วยมือช้า/เร็ว เทียบกับที่ AI อธิบาย»"]],[["2.« ให้ AI ช่วยเรียบเรียงข้อความแจ้งลมแรง 4 ระดับให้สั้น»"],["«ข้อความมีตัวเลขความเร็วลมที่ AI ใส่เองและคำสั่งที่เสี่ยง เช่น ให้ออกไปเก็บของระหว่างลมแรง»"],["«ตัดตัวเลขที่ไม่มีที่มาและคำสั่งที่เสี่ยง ใช้คำแนะนำตามกรมอุตุฯ (อยู่ในอาคาร ห่างกระจกและต้นไม้ใหญ่ งดขับจักรยานยนต์) และบอกว่าเป็นต้นแบบของโรงเรียน»"]]]],["p","ข้อมูลใดจาก AI ที่กลุ่มไม่ใช้ เพราะไม่เหมาะสม ไม่ปลอดภัย หรือไม่มีหลักฐานยืนยัน"],["t",[[["«ไม่ใช้: เกณฑ์ลม km/h ที่ AI เสนอเอง เพราะไม่มีที่มาและยังไม่ได้เทียบกับหน่วยงาน»","«ไม่ใช้: คำแนะนำให้ออกไปเก็บของหรือยึดหลังคาระหว่างลมแรง เพราะอันตราย»","«ไม่ใช้: ไอเดียทดสอบกังหันกลางแจ้งตอนฟ้าคะนองหรือติดบนเสาโลหะสูง เพราะเสี่ยงฟ้าผ่า ใช้พัดลมในร่มและโหมดจำลองแทน»"]]]]]},{"h":"7. ตรวจสอบความพร้อมของต้นแบบจำลอง","b":[["t",[[["เกณฑ์"],["หลักฐานที่เห็นจริง/สิ่งที่ต้องแก้"]],[["ตรงปัญหาและตอบผู้ใช้ที่กำหนด"],["«ตรง: โหนด + ไฟ + ข้อความ + แผนที่ ตอบโจทย์ \"ชาวบ้านไม่รู้จุดเสี่ยงและไม่รู้ว่าลมแรง\"»","«หลักฐาน: ใบกิจกรรมที่ 2 ข้อ 3»"]],[["แสดงการทำงานได้/อธิบายขั้นตอนชัด"],["«สาธิตด้วยโหมดจำลอง: ค่าลมขึ้นถึงระดับ 1 → 2 → 3 แล้วจอ หน้าเว็บ ข้อความ และไฟเปลี่ยนตาม»","«หลักฐาน: วิดีโอสาธิต»"]],[["เลือกใช้ทรัพยากรเหมาะสมและปลอดภัย"],["«ใช้ไฟ 5 V ไม่ทดสอบตอนฟ้าคะนอง ผู้ใหญ่ติดตั้งเสา เก็บรหัสลับนอกโค้ด»","«หลักฐาน: ตารางความเสี่ยงข้อ 3»"]],[["ต่างจากวิธีทั่วไปอย่างมีเหตุผล"],["«ต่างจากประกาศกรมอุตุฯ ที่เป็นระดับจังหวัด: วัดลมที่จุดในหมู่บ้านและเก็บประวัติ พร้อมแผนที่จุดเสี่ยงและข้อความสิ่งที่ควรทำ แต่ไม่ได้แทนประกาศและเตือนล่วงหน้าไม่ได้»"]]]],["p","ชื่อของต้นแบบ «ยามลมหมู่บ้าน (ต้นแบบเฝ้าระวังวาตภัย)»  ·"],["p","วิธีสาธิตการทำงานอย่างปลอดภัย"],["t",[[["«สาธิตด้วยโหมดจำลอง (SIMULATE) ใช้ไฟ 5 V จากพาวเวอร์แบงก์ ครูอยู่ดูแล ให้ผู้ชมดูระดับขึ้นถึง 1 2 3 และไฟกับข้อความเปลี่ยนตาม แล้วเป่าพัดลมในร่มใส่กังหันให้ดูค่าจริง»","«ถ้าไม่มีอุปกรณ์หรือเน็ต: ใช้ปุ่ม \"โหมดจำลอง\" ในหน้าเว็บ ไม่ต้องใช้กังหันจริง»"]]]],["p","หลักฐานภาพถ่าย/ไฟล์/ลิงก์ต้นแบบ"],["t",[[["«หลักฐานที่ต้องแนบ: ภาพถ่ายกังหันและวงจร วิดีโอสั้นสาธิต ภาพหน้าจอเว็บแอป ตารางสอบเทียบกับพัดลม แผนที่จุดเสี่ยงตัวอย่าง (ลิงก์ Google Drive ของกลุ่ม ห้ามมีรหัสลับในภาพ)»"]]]]]},{"h":"8. ต้นแบบเราแตกต่างจากวิธีที่มีอยู่จริงอย่างไร","b":[["t",[[["วิธีแก้ปัญหาที่พบหรือใช้อยู่ก่อน"],["สิ่งที่เราเปลี่ยน/เพิ่มในต้นแบบ"],["ประโยชน์ต่อผู้ใช้"],["หลักฐานที่ตรวจสอบได้"]],[["«ประกาศพายุฤดูร้อนของกรมอุตุนิยมวิทยาที่ระบุจังหวัด (เช่น ฉ.8 ปี 2565)»","«ผู้ใหญ่บ้านดูท้องฟ้าและสังเกตลมเอง»"],["«กังหันและโหนดวัดลมที่จุดในหมู่บ้าน เก็บประวัติลมสูงสุด»","«จอที่เสา ไฟ 3 ดวงที่ศาลา และข้อความถึงผู้ใหญ่บ้าน»","«แผนที่จุดเสี่ยง ข้อความ \"สิ่งที่ควรทำ\" และช่องกรอกค่าสังเกต»"],["«ผู้ใหญ่บ้านรู้ลมของหมู่บ้านตัวเองและมีข้อมูลสำหรับปรับเกณฑ์»","«คนใกล้ศาลาเห็นระดับจากไฟ»","«ชาวบ้านรู้จุดเสี่ยงและที่หลบก่อนพายุ»"],["«ตารางสอบเทียบกับพัดลม»","«วิดีโอสาธิต»","«ข่าวอ้างอิงในใบกิจกรรมที่ 1»"]]]],["p","ทำไมสิ่งที่เพิ่มจึงอาจลดความเสี่ยงของกลุ่มเป้าหมายได้ (ไม่อ้างประสิทธิภาพก่อนมีผลทดลอง)"],["t",[[["«สมมติฐาน: ถ้าชาวบ้านรู้จุดเสี่ยงและที่หลบก่อนพายุ และผู้ใหญ่บ้านรู้ทันทีเมื่อลมในหมู่บ้านแรง อาจเตรียมตัวและเข้าที่หลบได้ดีขึ้น (ยังไม่อ้างว่าได้ผลจนกว่าจะมีผลทดลอง และต้นแบบนี้เตือนล่วงหน้าได้น้อยมาก)»","«เหตุผลสนับสนุน: ข่าว 3 พ.ค. 2567 เล่าว่าความเสียหายมาจากต้นไม้ เสาไฟ และหลังคา ซึ่งสำรวจและเตรียมก่อนได้ และประกาศกรมอุตุฯ แนะนำให้เลี่ยงที่โล่งแจ้งและใต้ต้นไม้ใหญ่»"]]]],["p","ถ้าผู้ใช้อีกกลุ่มหนึ่งต้องใช้ต้นแบบนี้ ต้องปรับอะไร (หรือใช้วัสดุ/เทคโนโลยีในแบบที่ต่างจากปกติอย่างไร)"],["t",[[["«ถ้าผู้ใช้เป็นโรงเรียนหรือวัดที่มีอาคารโล่งกว้าง: ต้องให้ผู้เชี่ยวชาญตรวจโครงสร้างหลังคาและที่หลบก่อน ไม่ใช้บัตรตรวจบ้านของหมู่บ้านตรง ๆ»","«ถ้าผู้ใช้เป็นเกษตรกรสวนผลไม้ (เช่น สวนทุเรียนในข่าว): ใช้ข้อมูลลมเพื่อเก็บบันทึกและเตรียมป้องกันผลผลิตตามที่ประกาศกรมอุตุฯ แนะนำ ไม่ให้ใครอยู่ในสวนตอนลมแรง»"]]]]]},{"h":"9. สาธิตสั้น ๆ ให้ดู","b":[["p","ฉันรับผิดชอบส่วนใด / ส่วนนี้ทำงานอย่างไร / จะสาธิตให้เห็นอะไร"],["t",[[["«ฉันรับผิดชอบ: กังหันถ้วยและบอร์ดโหนดวัดลม (ฮาร์ดแวร์)»","«ทำงานอย่างไร: ลมหมุนกังหัน → บอร์ดนับรอบ 10 วินาที 3 ช่วง เลือกค่าสูงสุดแปลงเป็น km/h → ตัดสินระดับ 0–3 → จอแสดงระดับและส่งขึ้นเว็บ → ไฟที่ศาลาเปลี่ยนสี»","«จะสาธิต: เปิดโหมดจำลองให้ค่าลมขึ้นถึงระดับ 2 ดูข้อความและไฟเปลี่ยน แล้วปิด Wi-Fi ให้ดูว่าจอที่เสายังแสดงระดับเอง และเป่าพัดลมใส่กังหันให้ดูค่าจริง»"]]]],["p","ข้อบกพร่องหรืออุปสรรคที่ฉันพบ 1 เรื่อง / ฉันลองแก้อย่างไร / ผลที่เกิด"],["t",[[["«(สมมติ) พบ: ค่า km/h จากกังหันต่ำกว่าเครื่องวัดมือถือเมื่อพัดลมแรง ทำให้ระดับต่ำกว่าจริง»","«ลอง: สอบเทียบ KMH_PER_HZ ใหม่จากตารางพัดลม 3 ความเร็ว และเขียนกำกับว่า \"ค่าโดยประมาณ ยังไม่ได้เทียบกับลมพายุจริง\"»","«ผลที่เกิด: (นักเรียนบันทึกผลจริงของกลุ่ม)»"]]]]]}]},"a6":{"pre":[["p","ภารกิจ : กำหนดเกณฑ์ความสำเร็จก่อนทดลอง ใช้สถานการณ์จำลองที่ปลอดภัย เก็บข้อเสนอแนะ ปรับต้นแบบ และทดสอบซ้ำ แล้วใช้ผลทั้งหมดสะท้อนผลงานและวิธีทำงานของตน พร้อมวางแผนพัฒนารอบถัดไป"]],"secs":[{"h":"1. วางแผนการทดลองสถานการณ์จำลอง","b":[["p","สถานการณ์จำลองที่ใช้ทดสอบ (เช่น น้ำป่าตอนกลางคืนโดยไม่มีอินเทอร์เน็ต) และผู้ทดลอง"],["t",[[["«สถานการณ์จำลอง: ใช้โหมดจำลอง (SIMULATE) ให้ค่าลมขึ้น-ลงผ่านระดับ 0–3 ช่วงหนึ่งปิด Wi-Fi แทนการไม่มีเน็ต และอีกช่วงเป่าพัดลมในร่มใส่กังหันจริง แล้วดูจอ หน้าเว็บ ข้อความ และไฟ»","«ผู้ทดลอง: เพื่อนกลุ่มอื่น 2 คนรับบทผู้ใหญ่บ้าน (ไม่รู้ล่วงหน้าว่าค่าลมจะขึ้นถึงระดับใดเมื่อไร) ครูเป็นผู้สังเกต»","«ความปลอดภัย: ใช้ไฟ 5 V บนโต๊ะ พัดลมมีตะแกรงกันนิ้ว ทดสอบในร่ม ไม่ทดสอบตอนฟ้าคะนอง รอบจำลองวัดทุก 5 วินาที (ค่าใช้จริงพักระหว่างรอบ 2 นาที) ไม่ต้องแก้โค้ด»"]]]],["t",[[["สิ่งที่จะวัด/สังเกต"],["เกณฑ์สำเร็จที่กำหนดไว้ก่อนทดสอบ"],["จะเก็บผลอย่างไร"]],[["1.« ระดับ 0–3 ที่จอบอร์ดและหน้าเว็บแสดง ตรงกับระดับที่คำนวณจากตารางเกณฑ์ลม»"],["«ตรงอย่างน้อย 5 ใน 6 จุดวัด (กลุ่มกำหนดเอง)»"],["«จดค่า km/h ที่เว็บแสดง ระดับที่คำนวณเอง และระดับ 0–3 ที่เว็บแสดง ลงตาราง 6 แถว»"]],[["2.« ผู้ใหญ่บ้านรู้ว่าต้องทำอะไรเมื่ออ่านข้อความระดับ 2»"],["«ผู้ทดลอง 2 ใน 2 คน บอก 2 ข้อแรกที่ต้องทำได้ถูกภายใน 30 วินาที»"],["«ถามผู้ทดลองแล้วจดผลลงตาราง»"]]]]]},{"h":"2. ผลทดลองรอบที่ 1 ก่อนปรับปรุง","b":[["t",[[["เกณฑ์ทดสอบ"],["ผลที่เกิดจริง (ไม่แต่งข้อมูล)"],["ปัญหาหรือข้อจำกัด"]],[["1.« ระดับตรงกับที่คำนวณ อย่างน้อย 5 ใน 6 จุด»"],["«(สมมติ) ตรง 4 ใน 6 จุด»"],["«2 จุดหลังค่าลมลดลง ระดับที่เว็บยังไม่ลดตามทันที เพราะระบบรอเห็นค่าต่ำลง 2 ครั้งติดกัน ทำให้ไม่ตรงกับที่นักเรียนคำนวณจากค่าล่าสุด»"]],[["2.« ผู้ทดลองบอก 2 ข้อแรกที่ต้องทำได้ถูกใน 30 วินาที»"],["«(สมมติ) 1 ใน 2 คน อีกคนไม่แน่ใจว่าควรหลบที่ไหน»"],["«ข้อความระดับ 2 บอกให้อยู่ในอาคารแต่ไม่บอกว่าอาคารไหน และผู้ทดลองไม่รู้ที่หลบใกล้ศาลา»"]]]],["p","ข้อเสนอแนะจากเพื่อน/ครู/ผู้ทดลองใช้ 1–2 ข้อ (เขียนว่าใครเสนอเรื่องใด ไม่ต้องระบุข้อมูลส่วนตัว)"],["t",[[["«ผู้ทดลองคนที่ 1: ข้อความบอกให้เข้าอาคาร แต่ไม่รู้ว่าอาคารไหนแข็งแรง อยากให้มีแผนที่ที่หลบ»","«ครู: ในหน้าเว็บควรบอกว่าค่าลมเป็นค่าโดยประมาณ และเตือนว่าประกาศจริงมาจากกรมอุตุฯ»","«(ตัวอย่างสมมติ — นักเรียนเขียนข้อเสนอแนะที่ได้จริง)»"]]]]]},{"h":"3. ปรับปรุงตามหลักฐานและทดสอบซ้ำ","b":[["p","ทดสอบซ้ำในสถานการณ์จำลองที่เทียบเคียงกับรอบแรก เช่น ผู้ทดลอง เหตุการณ์ ระยะทาง แหล่งข้อมูล และอุปกรณ์"],["t",[[["เกณฑ์ความสำเร็จเดิม"],["ผลรอบที่ 1"],["สิ่งที่แก้จริง + เหตุผล"],["ผลรอบที่ 2"],["ดีขึ้น/ยังไม่ดี เพราะอะไร"]],[["1.« ระดับตรงกับที่คำนวณ อย่างน้อย 5 ใน 6 จุด»"],["«(สมมติ) ตรง 4 ใน 6 จุด»"],["«เพิ่มคอลัมน์ \"ค่า 2 รอบล่าสุด\" ในตารางทดสอบ และอ่านระดับหลังค่าลดครบ 2 รอบ»","«เหตุผล: ระบบลดระดับเมื่อเห็นค่าต่ำลง 2 ครั้งติดกัน ไม่ใช่ทันที»"],["«(สมมติ) ตรง 6 ใน 6 จุด»"],["«ดีขึ้น แต่เพราะเปลี่ยนวิธีตรวจ ไม่ใช่แก้ตัวต้นแบบ และมีเพียง 6 จุดในโหมดจำลอง ยังไม่ได้ทดสอบกับลมพายุจริง»"]],[["2.« ผู้ทดลองบอก 2 ข้อแรกที่ต้องทำได้ถูกใน 30 วินาที»"],["«(สมมติ) 1 ใน 2 คน»"],["«เพิ่มประโยค \"ที่หลบ: ดูแผนที่ที่ศาลา\" ท้ายข้อความระดับ 2 และเปลี่ยน \"อยู่ในอาคาร\" เป็น \"เข้าอาคารแข็งแรงตามแผนที่\"»","«เหตุผล: ตรงกับสิ่งที่ผู้ทดลองสับสน และไม่ต้องเดา»"],["«(สมมติ) 2 ใน 2 คน»"],["«ดีขึ้น แต่ผู้ทดลองเป็นคนละคน จึงเทียบตรง ๆ ไม่ได้»"]]]],["p","มีเงื่อนไขใดไม่เหมือนเดิมระหว่างสองรอบหรือไม่? ถ้ามี ผลการเปรียบเทียบอาจคลาดเคลื่อนอย่างไร"],["t",[[["«ไม่เหมือนเดิม: ผู้ทดลองรอบ 2 เป็นคนละคน และค่าจำลองแต่ละรอบไม่ผ่านจุดเดียวกันทุกครั้ง»","«ผลกระทบ: ข้อสรุปว่า \"ดีขึ้น\" อาจมาจากวิธีตรวจหรือตัวผู้ทดลอง ไม่ใช่การแก้ไข ต้องทดสอบซ้ำกับผู้ทดลองเดิมและจำนวนจุดที่มากขึ้น»"]]]]]},{"h":"4. สะท้อนคิดผลงานและกระบวนการของกลุ่ม","b":[["p","ใช้ผลทดสอบและข้อเสนอแนะเป็นหลักฐาน ไม่ใช้ความรู้สึกอย่างเดียว"],["t",[[["สิ่งที่สะท้อน"],["จุดแข็ง (พร้อมหลักฐาน)"],["จุดอ่อน (พร้อมหลักฐาน)"]],[["ผลงาน/ต้นแบบ"],["«จอที่เสาแสดงระดับเองได้แม้ไม่มีเน็ต (หลักฐาน: ทดสอบปิด Wi-Fi)»","«ไฟสลับสีเมื่อไม่มีข้อมูล ไม่ติดเขียว (หลักฐาน: ตัด Wi-Fi ของบอร์ดไฟ)»","«ค่าลมจากกังหันตอบสนองต่อพัดลมในร่ม (หลักฐาน: ตารางสอบเทียบ)»"],["«ยังไม่ได้ทดสอบกับลมพายุจริง และยังไม่ได้เทียบกับสถานีอุตุฯ»","«กังหันที่ติดขัดอ่านเป็น 0 km/h แยกจากลมสงบไม่ได้ ต้องให้คนตรวจ»","«ยังเตือนล่วงหน้าก่อนพายุมาไม่ได้ ประกาศจริงมาจากกรมอุตุฯ»"]],[["กระบวนการสร้างสรรค์ของกลุ่ม (ใบกิจกรรม 1–5)"],["«เริ่มจากข่าวจริงและประกาศกรมอุตุฯ (ใบ 1–2)»","«ผสานความคิดเพื่อนจนได้แผนที่ ไฟ ข้อความ และตารางสิ่งที่ต้องทำ (ใบ 3)»","«ปรับโจทย์จาก \"เครื่องเตือน\" เป็น \"เตรียมก่อนพายุ + ยืนยันลม\" (ใบ 2)»"],["«ใบ 5 ทดสอบกับอุปกรณ์จริงน้อย เวลาไม่พอ»","«ยังไม่ได้เดินสำรวจจุดเสี่ยงกับผู้ใหญ่บ้านจริง»","«ไม่ได้ถามชาวบ้านตัวจริงว่ารู้ประกาศพายุทางไหน»"]]]],["p","ต้นแบบช่วยป้องกัน ลดความเสี่ยง หรือสนับสนุนการเตรียมพร้อมของกลุ่มเป้าหมายได้อย่างไร (จากผลทดลองเท่านั้น)"],["t",[[["«จากผลทดลอง (สมมติ): ต้นแบบทำให้ผู้ทดลองเห็นระดับลมและรู้ว่าต้องทำอะไรเร็วขึ้นในโหมดจำลอง แต่ยังสรุปไม่ได้ว่าช่วยให้ชาวบ้านปลอดภัยขึ้นจริงตอนพายุ»","«ยืนยันได้จากผล: การแสดงระดับที่เสาไม่ขึ้นกับเน็ต และกังหันตอบสนองต่อพัดลมในร่ม»","«ยังยืนยันไม่ได้: ว่าค่าลมตรงเครื่องมาตรฐานแค่ไหน และชาวบ้านทำตามข้อความจริงหรือไม่ ต้องทดสอบกับลมจริงตอนอากาศปกติและผู้ใช้จริงโดยมีผู้ใหญ่ดูแล»"]]]],["p","สิ่งใด “ยังไม่ควรนำไปใช้จริง” และผู้ใช้ควรอ้างอิงข้อมูล/คำเตือนจากหน่วยงานใดในเหตุฉุกเฉิน"],["t",[[["«ยังไม่ควรใช้จริง: การให้ชาวบ้านตัดสินใจตามค่าจากกังหันเพียงอย่างเดียว การเปิดเสียงเตือนที่ยังไม่ได้ตกลงความหมายกับผู้ใหญ่บ้านหรือ อบต. และการอ้างว่าเตือนล่วงหน้าได้»","«ให้ติดตามประกาศกรมอุตุนิยมวิทยา (tmd.go.th โทร 1182) และ ปภ. (สายด่วน 1784) ระหว่างพายุให้อยู่ในอาคารแข็งแรง ห่างกระจกและต้นไม้ใหญ่ หลังเหตุห้ามแตะสายไฟที่ขาด»"]]]],["p","ตั้งคำถามกับกระบวนการสร้างสรรค์ของเรา: ขั้นตอนใดที่เราเลือกทางง่ายเกินไปหรือน่าจะทำต่างออกไป เพราะอะไร"],["t",[[["«ที่เลือกทางง่าย: ทดสอบด้วยพัดลมและโหมดจำลองแทนลมจริง และไม่ได้เดินสำรวจจุดเสี่ยงหรือถามผู้ใหญ่บ้านและชาวบ้านตัวจริง»","«ควรทำต่าง: ขอให้ครูพาไปเดินสำรวจกับผู้ใหญ่บ้านตอนอากาศปกติ ถามชาวบ้านว่ารับประกาศพายุทางไหน และเทียบค่ากังหันกับเครื่องวัดลมอ้างอิงก่อนกำหนดเกณฑ์»","«เพราะเกณฑ์และข้อความต้องมาจากคนที่ใช้จริงและข้อมูลจริง ไม่ใช่จากโหมดจำลอง»"]]]]]}]}},"team":["กลุ่มที่ «4»  ·  ชื่อกลุ่ม «ทีมยามลม»  ·  ภัยที่เลือก «วาตภัย»  ·","สมาชิก 1) «นักเรียน ก»  ·  2) «นักเรียน ข»  ·  3) «นักเรียน ค»  ·","4) «นักเรียน ง»  ·  5) «นักเรียน จ»  ·  วันที่ ........ / ........ / ........"]},"landslide":{"intro":["«ฉบับตัวอย่างเฉลยสำหรับครู — ภัยที่เลือก: ดินถล่ม/น้ำป่าไหลหลาก (จังหวัดอุตรดิตถ์)»","ข้อความสีน้ำเงินคือแนวตอบตัวอย่าง นักเรียนต้องคิดและเขียนเอง ไม่ควรคัดลอก ส่วนเกณฑ์ประเมินของครูเว้นว่างไว้ (ชื่อนักเรียน ก ข ค ง จ เป็นชื่อสมมติ)","อ้างอิง: ไทยโพสต์ 3 ต.ค. 2567 • MGR Online 9 ก.ย. 2554 • กรมพัฒนาที่ดิน (ข้อมูล พ.ศ. 2549) • กรมทรัพยากรธรณี 3 ก.ย. 2557 ตรวจเมื่อ 24 ต.ค. 2569","\"(สมมติ)\" ในใบกิจกรรมที่ 5–6 = ตัวอย่างวิธีเขียน ไม่ใช่ผลวัดจริง เกณฑ์ดิน/ฝน/ความเอียงเป็นค่าสมมติ ต้องใช้เกณฑ์จริงจากหน่วยงานก่อนใช้จริง","ต้นแบบนี้ไม่ใช่เครื่องทำนายดินถล่มและไม่ใช่ระบบเตือนภัยทางการ นักเรียนไม่ขึ้นเขา ยังไม่ได้ทดสอบกับอุปกรณ์และฝนจริง"],"acts":{"a1":{"pre":[["p","ภารกิจ : เลือกภัยธรรมชาติที่มีโอกาสเกิดหรือเคยเกิดขึ้นในจังหวัดอุตรดิตถ์ แล้วสืบค้นข้อมูลจากแหล่งที่เชื่อถือได้ เพื่อทำความเข้าใจความเสี่ยง โดยตั้งคำถามให้มากกว่าที่รู้ และกล้าตรวจสิ่งที่เคยเชื่อ ก่อนเสนอวิธีแก้"]],"secs":[{"h":"1. เลือกภัยและระบุบริบทพื้นที่","b":[["p","ใช้ข้อมูลจริงหรือสถานการณ์จำลองที่ครูกำหนด"],["p","☐ น้ำท่วม/น้ำป่า    «☒» ดินถล่ม    ☐ ภัยแล้ง    ☐ วาตภัย    ☐ ไฟป่า/หมอกควัน    ☐ อื่น ๆ ................."],["p","บริบทพื้นที่/สถานการณ์ที่กลุ่มสนใจ (เกิดที่ไหน เมื่อใด หรือมีเงื่อนไขอย่างไร)"],["t",[[["«1–3 ต.ค. 2567 ฝนตกหนักในจังหวัดอุตรดิตถ์ ดินสไลด์ทำให้ถนนบ้านน้ำหมัน–บ้านผาแก่น อ.ท่าปลา ทรุดตัวจนใช้เส้นทางไม่ได้ ถนนใน ต.นานกก อ.ลับแล ขาด 3 จุด เสาไฟหักล้ม ไฟดับ สัญญาณโทรศัพท์ใช้ไม่ได้ ชาวบ้านต้องขี่จักรยานยนต์ไปบอกข่าวกัน (ไทยโพสต์) • คืนวันที่ 8 ต่อเนื่องถึงราว 02.00 น. 9 ก.ย. 2554 น้ำป่าพัดโคลนและท่อนซุงเข้าหมู่บ้านห้วยเดื่อ/ต้นขนุน ต.น้ำไผ่ อ.น้ำปาด (MGR Online)»","«ข้อสังเกต: เหตุปี 2554 เกิดกลางดึก และปี 2567 ไฟกับสัญญาณโทรศัพท์หายไปพร้อมกัน ข่าวที่อ่านไม่ได้บอกว่ามีสัญญาณเตือนให้เห็นก่อนเหตุหรือไม่ จึงไม่สรุปว่าเหตุเกิดได้เฉพาะกลางคืน»","«เงื่อนไขที่สนใจ: ครัวเรือนใกล้เชิงเขาหรือร่องน้ำที่ไม่รู้ว่าฝนสะสมและดินอิ่มน้ำถึงจุดน่ากังวลหรือยัง — ใช้หมู่บ้านสมมติ 1 แห่งเชิงเขาในจังหวัดอุตรดิตถ์เป็นพื้นที่ทดลอง และไม่มีใครต้องขึ้นเขาไปดู»"]]]]]},{"h":"2. รวบรวมข้อมูลและตรวจสอบความน่าเชื่อถือ","b":[["t",[[["แหล่งข้อมูล/หน่วยงาน","(ชื่อหรือ URL ย่อ)"],["ข้อมูลสำคัญที่พบ"],["ตรวจสอบได้อย่างไร / วันที่เข้าถึง"]],[["1.« ไทยโพสต์»","«ข่าวฝนถล่มอุตรดิตถ์ ดินสไลด์ ถนนขาด ไฟดับ เผยแพร่ 3 ต.ค. 2567»"],["«ฝนตกหนักตั้งแต่ 1 ต.ค. ถนนทรุด (ท่าปลา) และถนนขาด 3 จุด (ลับแล)»","«เสาไฟล้ม ไฟดับ โทรศัพท์ใช้ไม่ได้ ชาวบ้านใช้จักรยานยนต์ติดต่อกัน»"],["«ผู้เสียชีวิต 1 ราย เกิดจากต้นทุเรียนล้มทับตอนลมแรง ไม่ใช่ดินถล่ม จึงไม่นับ»","«ลิงก์: thaipost.net/district-news/667660 เข้าถึง 24 ต.ค. 2569»"]],[["2.« MGR Online»","«ข่าวน้ำป่า-ดินโคลน อ.น้ำปาด เผยแพร่ 9 ก.ย. 2554 (มีข่าวชิ้นที่สองเรื่องเดียวกัน)»"],["«ฝนตกหนักต่อเนื่อง น้ำป่าพัดโคลน ท่อนซุง และเศษไม้ใหญ่เข้าหมู่บ้านราว 02.00 น.»","«บ้านพังราว 19–20 หลัง สะพาน 2 แห่งขาด»"],["«ตัวเลขผู้เสียชีวิตและสูญหายเป็นตามข่าวขณะนั้น อาจเปลี่ยนภายหลัง»","«ลิงก์: mgronline.com/local/detail/9540000114707 เข้าถึง 24 ต.ค. 2569»"]],[["3.« กรมพัฒนาที่ดิน»","«เอกสาร PDF ที่สรุปอุทกภัยและดินโคลนถล่ม พ.ศ. 2549 (22–23 พ.ค.) ใน อ.ลับแล เมือง ท่าปลา»"],["«พื้นที่เสี่ยงดินถล่มของ 3 อำเภอรวมกัน: น้อย 168,466 ไร่ ปานกลาง 80,008 ไร่ รุนแรง 9,301 ไร่»","«ตัวเลขนี้บอกว่ามีพื้นที่เสี่ยงจริง»"],["«ตัวเลขรวม 3 อำเภอจากเอกสารเก่า ไม่ใช่ของหมู่บ้านเรา ใช้ดูภาพรวมเท่านั้น»","«ลิงก์: orgweb.ldd.go.th (ไฟล์ PDF) เข้าถึง 24 ต.ค. 2569»"]]]]]},{"h":"3. มองเหตุและผลให้รอบด้าน","b":[["t",[[["สาเหตุ/ปัจจัย (อย่างน้อย 2 ข้อ)"],["ผลกระทบต่อชีวิต ทรัพย์สิน ชุมชน หรือสิ่งแวดล้อม"]],[["1.« ฝนตกหนักต่อเนื่องหลายวัน (ไทยโพสต์ ตั้งแต่ 1 ต.ค. 2567) หรือทั้งคืน (MGR 2554) จนเกิดดินสไลด์และน้ำป่า»","«ข่าวไม่ได้บอกว่าฝนสะสมกี่ mm จึงไม่ตั้งตัวเลขเอง»"],["1.« ถนนขาด บ้านพัง สะพานขาด และน้ำป่าพัดโคลนกับท่อนซุงเข้าหมู่บ้าน (ไทยโพสต์ MGR Online)»","«ไฟดับและสัญญาณโทรศัพท์หาย ต้องขี่จักรยานยนต์ไปบอกข่าว ตรงกับโจทย์ของเรา»"]],[["2.« ชาวบ้านอาจไม่รู้ว่าฝนรวมกันเท่าไร เพราะแต่ละบ้านเห็นแค่ฝนตอนนั้น (ข้อสันนิษฐาน ต้องถามผู้ใหญ่บ้าน)»","«ไม่มีใครบันทึกฝนหรือสังเกตเขาเป็นประจำ»"],["2.« ข่าวผ่านเน็ตและโทรศัพท์ใช้ไม่ได้เมื่อไฟดับ ผู้สูงอายุอยู่คนเดียวรับข่าวยาก (ข้อสันนิษฐาน ต้องสอบถาม)»","«ไม่มีข้อตกลงว่าฝนถึงระดับไหนแล้วต้องเตรียมตัว»"]]]]]},{"h":"4. ใครเสี่ยงอย่างไร? ลองมองจากมุมผู้ได้รับผลกระทบ","b":[["p","กลุ่มที่ 2 ให้เลือกกลุ่มที่กลุ่มเราไม่ค่อยคุ้นเคยหรือมักถูกมองข้าม (เช่น ผู้พิการ ผู้ป่วยติดเตียง เด็กเล็ก แรงงานย้ายถิ่น)"],["t",[[["ผู้ได้รับผลกระทบ"],["ความเสี่ยง/สิ่งที่กังวล"],["ความต้องการที่สำคัญ"]],[["กลุ่มที่ 1:« ครัวเรือนใกล้เชิงเขาและริมร่องน้ำ»","«(กลุ่มที่เรานึกถึงเป็นอันดับแรก)»"],["«ไม่รู้ว่าฝนสะสมและดินเริ่มน่ากังวล และไม่มีเวลาตัดสินใจถ้าเหตุเกิดกลางดึก»","«ไฟดับและโทรศัพท์ใช้ไม่ได้ในเวลาที่ต้องรับข่าวมากที่สุด»"],["«รู้เร็วที่สุดว่าฝนสะสมและดินถึงระดับที่ตกลงกันไว้ และรู้ว่าต้องเตรียมอะไร»","«จอและบัซเซอร์ที่โหนด (ทำงานเองได้ถ้ามีไฟเลี้ยง แม้เน็ตหลุด) ไฟที่ศาลา และข้อความถึงผู้ใหญ่บ้าน»"]],[["กลุ่มที่ 2:« ผู้สูงอายุและผู้ป่วยติดเตียงที่อยู่คนเดียวในบ้านใกล้เชิงเขา»","«(กลุ่มที่มักถูกมองข้าม — สมมติฐานของกลุ่ม ต้องไปถามผู้ใหญ่บ้าน)»"],["«ย้ายตัวเองออกจากบ้านในที่มืดเมื่อฝนตกหนักไม่ได้ และไม่มีใครรู้ว่าบ้านนี้ต้องช่วยก่อน»","«ไม่รู้ว่าจุดรวมพลอยู่ที่ใดและไปทางไหน»"],["«เพื่อนบ้านคู่หูที่ตกลงกันไว้ล่วงหน้าว่าใครช่วยใคร»","«รายชื่อบ้านที่ต้องช่วยก่อน (เก็บในพื้นที่อาสา ต้องใช้ PIN)»"]]]],["p","เลือกกลุ่มเป้าหมายหลัก 1 กลุ่ม และบอกเหตุผลที่เลือก"],["t",[[["«กลุ่มเป้าหมายหลัก: ครัวเรือนใกล้เชิงเขาหรือริมร่องน้ำที่ฝนตกหนักหลายวัน และผู้สูงอายุหรือผู้ป่วยที่อยู่คนเดียวในบ้านใกล้เชิงเขา»","«เหตุผล: เหตุปี 2554 เกิดราว 02.00 น. คนหลับอยู่ ตัดสินใจไม่ทัน ส่วนผู้สูงอายุอยู่คนเดียวย้ายตัวเองออกมาในที่มืดได้ยาก»","«คนที่ช่วยเขาได้คือผู้ใหญ่บ้านและเพื่อนบ้าน ต้นแบบจึงเน้นให้พวกเขารู้ว่าฝนสะสมและดินน่ากังวลเพื่อเตรียมตัว ไม่ใช่ให้เครื่องตัดสินใจอพยพแทนคน»"]]]]]},{"h":"5. สิ่งที่รู้แล้ว / ยังไม่รู้ / ต้องหาต่อ","b":[["t",[[["สิ่งที่รู้จากหลักฐาน"],["สิ่งที่ยังไม่รู้ (คำถามที่ยังไม่มีคำตอบ)"],["จะสืบค้นหรือถามใคร/ที่ใด"]],[["«ไทยโพสต์ 3 ต.ค. 2567: ฝนตกหนักตั้งแต่ 1 ต.ค. ถนนทรุดและขาดหลายจุด ไฟดับ โทรศัพท์ใช้ไม่ได้»","«MGR Online 2554: น้ำป่าพัดโคลนและท่อนซุงเข้าหมู่บ้านราว 02.00 น. บ้านพัง สะพานขาด»"],["«ฝนสะสมกี่ mm ดินอิ่มน้ำแค่ไหน จึงเริ่มน่ากังวลสำหรับเขาหน้าหมู่บ้านเรา?»","«ปกติชาวบ้านรู้ได้อย่างไรว่าฝนหนักแล้วควรเตรียมตัว และใครเป็นคนบอก?»"],["«ถามผู้ใหญ่บ้าน/อบต. ว่ามีเกณฑ์หรือประกาศเตือนจากหน่วยงานใด และขอเกณฑ์จริงมาเทียบ»","«ถามชาวบ้านสัก 5 คน (ไม่จดชื่อ) ว่าเคยสังเกตอะไรก่อนฝนหนักและทราบข่าวทางใด»"]],[["«ไทยโพสต์และ MGR Online ตรงกันว่าฝนตกหนักต่อเนื่อง และมีน้ำป่าหรือดินสไลด์ตามมา»","«กรมพัฒนาที่ดินบอกว่ามีพื้นที่เสี่ยง แต่เป็นตัวเลขรวม 3 อำเภอ»"],["«เขาหน้าหมู่บ้านเราเสี่ยงระดับใด ต่างจากหมู่บ้านข้างเคียงอย่างไร?»","«ไฟดับแล้วชาวบ้านรับข่าวและรวมตัวกันทางใด?»"],["«ถามผู้ใหญ่บ้าน/อบต. ว่ามีแผนที่พื้นที่เสี่ยงของหมู่บ้านหรือไม่ และจุดรวมพลอยู่ที่ใด»","«ถามผู้ใหญ่บ้านว่าตอนไฟดับใช้ช่องทางใดแจ้งข่าว (เช่น เสียงตามสาย วิทยุ จักรยานยนต์)»"]]]]]},{"h":"6. ตั้งคำถามสำรวจปัญหา","b":[["p","ต้องมีทั้ง “ทำไม...?” และ “ถ้า...จะเป็นอย่างไร?” เพื่อขยายมุมมอง เช่น “ทำไมผู้สูงอายุจึงอาจได้รับผลกระทบจากน้ำป่ามากกว่าคนวัยทำงาน” / “ถ้าเกิดน้ำป่าในเวลากลางคืนและไม่มีอินเทอร์เน็ต จะเป็นอย่างไร”"],["p","คำถามที่ 1 “ทำไม...?” และเหตุใดคำถามนี้จึงสำคัญ"],["t",[[["«ทำไมครัวเรือนใกล้เชิงเขาในหมู่บ้านจึงยังไม่รู้ว่าฝนสะสมและดินถึงจุดน่ากังวลก่อนเกิดเหตุกลางดึกและไฟดับ ทั้งที่จังหวัดมีพื้นที่เสี่ยงและเคยมีเหตุหลายครั้ง (ปี 2549 2554 2567)?»","«สำคัญเพราะถ้ารู้ว่าปัญหาคือไม่มีใครบันทึกฝนสะสม ไม่มีการสังเกตเขาเป็นประจำ หรือไม่มีข้อตกลงว่าถึงระดับไหนแล้วทำอะไร จะออกแบบข้อมูลและการเตรียมตัวให้ถึงคนในหมู่บ้านได้ตรงจุด»"]]]],["p","คำถามที่ 2 “ถ้า...จะเป็นอย่างไร?” และเงื่อนไขใหม่ที่อยากสำรวจ"],["t",[[["«ถ้าฝนตกหนักทั้งคืนและไฟดับ หมู่บ้านจะรู้ได้อย่างไรว่าฝนสะสมและดินน่ากังวล และควรเตรียมตัวหรือรวมพลที่ไหน โดยไม่ต้องมีใครขึ้นไปดูบนเขา?»","«เงื่อนไขใหม่ที่อยากสำรวจ: ไฟดับ โทรศัพท์ใช้ไม่ได้ และผู้ใหญ่บ้านอยู่ไกลศาลา — จอและบัซเซอร์ที่โหนด ไฟที่ศาลา หรือเพื่อนบ้านคู่หู อย่างไหนช่วยได้ และใครตัดสินใจอพยพ?»"]]]]]},{"h":"7. ท้าทายสิ่งที่เคยเชื่อ","b":[["p","เขียนสิ่งที่เรา/คนทั่วไปเชื่อหรือทำเป็นปกติเมื่อเกิดภัยนี้ แล้วตรวจกับหลักฐานจากส่วนที่ 2"],["t",[[["สิ่งที่เคยเชื่อ/วิธีที่คุ้นเคย"],["ตรวจกับหลักฐานแล้วพบว่า (ตรง / ขัด / ยังไม่รู้)"],["ถ้าข้อสมมตินี้ใช้ไม่ได้ (เช่น ไฟดับ ไม่มีอินเทอร์เน็ต เกิดกลางคืน) จะเกิดอะไรขึ้น"]],[["1.« เคยเชื่อว่า \"หมู่บ้านเราไม่เคยมีเหตุดินถล่มหรือน้ำป่า\"»"],["«ขัด: จังหวัดมีเหตุปี 2549 (กรมพัฒนาที่ดิน) ปี 2554 น้ำปาด (MGR Online) และ 1–3 ต.ค. 2567 ท่าปลา ลับแล (ไทยโพสต์)»"],["«เหตุเกิดได้หลายอำเภอและหลายปี ควรสำรวจและเตรียมตัวไว้ก่อน (ยังไม่รู้ว่าหมู่บ้านเราเสี่ยงระดับใด ต้องถาม อบต.)»"]],[["2.« เคยเชื่อว่า \"ถ้าเขาจะถล่มคงมีสัญญาณให้เห็นตอนกลางวัน\"»"],["«ข้อมูลที่ทำให้สงสัย: เหตุน้ำปาดเกิดราว 02.00 น. ขณะคนหลับ (MGR Online) และไฟกับสัญญาณหายในเหตุปี 2567 (ไทยโพสต์) แต่ข่าวไม่ระบุว่ามีสัญญาณก่อนเหตุหรือไม่»"],["«การรอดูด้วยตาไม่พอเมื่อเกิดกลางดึก ต้องมีวิธีอื่นช่วยเฝ้า และต้องถามชาวบ้านก่อนสรุป»"]]]],["p","ข้อมูลหรือมุมมองที่ไม่คุ้นเคย หรือขัดกับที่เราคิด 1 เรื่อง — กลุ่มชะลอการตัดสินและสำรวจเพิ่มอย่างไรก่อนสรุป"],["t",[[["«ข้อมูลที่ขัดกับที่คิด: เดิมคิดว่ามีเซนเซอร์ก็รู้ล่วงหน้าว่าเขาจะถล่ม แต่เหตุในข่าวมีฝนต่อเนื่อง เกิดกลางดึก และสื่อสารขาด และข่าวไม่มีตัวเลขฝนหรือค่าดินที่ใช้เทียบ (ข้อสันนิษฐาน ต้องถามหน่วยงาน)»","«ชะลอการตัดสิน: ยังไม่สรุปว่าค่าดินและฝนที่โหนดวัดจะบอกว่าเขาลูกไหนเสี่ยง จะบันทึกค่าที่ถาดจำลองดูรูปแบบ และถามกรมทรัพยากรธรณี/ปภ./อบต. ว่ามีเกณฑ์จริงหรือไม่»","«ผลที่ปรับความคิด: เปลี่ยนโจทย์จาก \"สร้างเครื่องทำนายดินถล่ม\" เป็น \"ช่วยให้รู้ว่าฝนสะสมและดินน่ากังวลเพื่อเตรียมตัว\" โดยผู้ใหญ่บ้าน/อบต. ตัดสินใจอพยพ»"]]]]]}]},"a2":{"pre":[["p","ภารกิจ : นำข้อมูลจากใบกิจกรรมที่ 1 มากำหนดปัญหาที่เฉพาะเจาะจง มีผู้ใช้ชัดเจน แล้วสร้างโจทย์ออกแบบหลายแนวทางด้วยกลยุทธ์ที่ต่างกัน ก่อนเลือกโจทย์ที่แก้ได้ด้วยต้นแบบ"]],"secs":[{"h":"1. แยกสาเหตุ ปัญหาหลัก และผลกระทบ","b":[["t",[[["สาเหตุ (เหตุใดจึงเกิด)"],["ปัญหาหลัก (สิ่งที่ต้องแก้)"],["ผลกระทบ (สิ่งที่ตามมา)"]],[["«ไม่มีใครบันทึกฝนสะสมและสังเกตเขาเป็นประจำในหมู่บ้าน (ข้อสันนิษฐาน ต้องถามผู้ใหญ่บ้าน)»","«ไม่มีข้อตกลงว่าฝนสะสมถึงระดับไหนแล้วบ้านใกล้เชิงเขาต้องเตรียมตัว»"],["«ชาวบ้านไม่รู้ว่าฝนสะสมและดินเริ่มน่ากังวล และไม่รู้ว่าต้องไปรวมพลที่ใด»","«เหตุอาจเกิดกลางดึก (ปี 2554 ราว 02.00 น.) และไฟดับ โทรศัพท์ใช้ไม่ได้ (ปี 2567)»"],["«ดินสไลด์ น้ำป่า โคลน บ้านพัง ถนนและสะพานขาด (ไทยโพสต์ MGR Online)»","«ปี 2554 ตามข่าวขณะนั้นมีผู้เสียชีวิตและสูญหาย (MGR Online)»"]],[["«ฝนหนักต่อเนื่องเกิดซ้ำในหลายเดือนของฤดูฝน (พ.ค. 2549 ก.ย. 2554 ต.ค. 2567)»","«เอกสารและข่าวระบุตรงกันว่าจังหวัดมีพื้นที่เสี่ยงและเคยเกิดเหตุ»"],["«ข่าวผ่านเน็ตและโทรศัพท์ใช้ไม่ได้เมื่อไฟดับ ต้องขี่จักรยานยนต์ไปบอกข่าว (ไทยโพสต์)»","«ผู้ใหญ่บ้านอาจอยู่ไกลจากบ้านใกล้เชิงเขา (ข้อสันนิษฐาน ต้องถาม)»"],["«บ้านใกล้เชิงเขาและริมร่องน้ำเสียหายก่อน (ข้อสันนิษฐานจากข่าว)»","«ผู้สูงอายุอยู่คนเดียวไม่รู้ว่าต้องไปที่ใด (ข้อสันนิษฐาน ต้องสอบถาม)»"]]]],["p","จากข้อมูลข้างต้น กลุ่มต้องการแก้ “ปัญหาหลัก” เรื่องใดเพียง 1 เรื่อง เหตุใดจึงสำคัญ และขอบเขตของปัญหาอยู่ตรงไหน (เกิดที่ใด/กับใคร/เมื่อใด)"],["t",[[["«ปัญหาหลัก: ครัวเรือนใกล้เชิงเขาในหมู่บ้านสมมติ จ.อุตรดิตถ์ ไม่รู้ว่าฝนสะสมและดินอิ่มน้ำถึงจุดน่ากังวลหรือยัง เพราะไม่มีใครบันทึกฝน ไม่สังเกตเขาเป็นประจำ และไม่มีข้อตกลงว่าถึงระดับไหนแล้วทำอะไร»","«สำคัญเพราะ: เหตุปี 2554 เกิดราว 02.00 น. และปี 2567 ไฟกับสัญญาณโทรศัพท์หาย คนจึงรับข่าวและตัดสินใจได้ยากที่สุดในเวลาที่เสี่ยงที่สุด»","«ขอบเขต: หมู่บ้านสมมติ 1 แห่ง ช่วงฤดูฝน ทดลองกับถาดลาดเขาจำลองและโหมดจำลอง ไม่ใช่เครื่องทำนายและไม่ใช่ระบบเตือนภัยทางการ นักเรียนไม่ขึ้นเขา»"]]]]]},{"h":"2. รู้จักผู้ใช้และมองปัญหาจากหลายมุม","b":[["t",[[["คำถาม"],["คำตอบกลุ่มพร้อมหลักฐานจากใบกิจกรรมที่ 1"]],[["ผู้ที่ต้องการช่วยคือใคร?"],["«ครัวเรือนใกล้เชิงเขาและริมร่องน้ำ กับผู้สูงอายุหรือผู้ป่วยอยู่คนเดียว ผู้ใช้ระบบคือผู้ใหญ่บ้านและอาสาที่จดฝน»"]],[["ประสบปัญหาเมื่อใด/สถานการณ์ใด?"],["«ช่วงฝนหนักต่อเนื่องหลายวันหรือทั้งคืน (เช่น 1–3 ต.ค. 2567 หรือคืน 8 ก.ย. 2554) เมื่อไฟอาจดับ»"]],[["ต้องการความช่วยเหลือแบบใด?"],["«ชาวบ้านรู้ว่าฝนสะสมและดินน่ากังวลแล้วเตรียมตัวและไปจุดรวมพล ผู้ใหญ่บ้าน/อบต. ตัดสินใจอพยพ»"]]]],["p","มองปัญหาจากมุมอื่นอย่างน้อย 2 มุม เช่น ชุมชน/วัฒนธรรม เศรษฐกิจ/ค่าใช้จ่าย ความปลอดภัย/จริยธรรม หน่วยงานที่เกี่ยวข้อง"],["t",[[["มุมมอง"],["เห็นปัญหานี้อย่างไร และต้องการอะไร"]],[["มุมมองที่ 1:« ผู้ใหญ่บ้านและ อบต.»"],["«ต้องตัดสินใจอพยพ แต่ไม่อยากสั่งผิดจนชาวบ้านเลิกเชื่อ และต้องการเกณฑ์จริงไว้เทียบ»","«ต้องการข้อความสั้นที่บอกระดับ ค่าที่วัดได้ และบอกว่าเป็นตัวช่วย»"]],[["มุมมองที่ 2:« ผู้บริหารโรงเรียนและผู้ปกครอง»"],["«ห่วงความปลอดภัยของนักเรียน ไม่ให้ขึ้นไหล่เขาหรือไปดูตอนฝนตกหนัก»","«ต้องขออนุญาตก่อนติดตั้ง และให้ผู้ใหญ่/อบต. ติดตั้งตอนอากาศปกติ»"]]]]]},{"h":"3. เขียนข้อความกำหนดปัญหา (Problem Statement)","b":[["p","รูปประโยคช่วยคิด : “(กลุ่มเป้าหมาย) ประสบปัญหา (ปัญหา) เมื่อ (สถานการณ์) เนื่องจาก (สาเหตุหรือข้อจำกัด) ส่งผลให้ (ผลกระทบ)”"],["p","ข้อความกำหนดปัญหาของกลุ่ม (เขียนให้เจาะจง ไม่ใช่แค่ชื่อภัย)"],["t",[[["«ครัวเรือนใกล้เชิงเขาในหมู่บ้านสมมติ จ.อุตรดิตถ์ ประสบปัญหาไม่รู้ว่าฝนสะสมและดินอิ่มน้ำถึงจุดน่ากังวลหรือยังในช่วงฝนตกหนักต่อเนื่อง เนื่องจากไม่มีการบันทึกฝน ไม่มีการสังเกตเขาเป็นประจำ ไม่มีข้อตกลงว่าถึงระดับไหนแล้วทำอะไร และเหตุอาจเกิดกลางดึกขณะไฟดับ ส่งผลให้ผู้ใหญ่บ้านและชาวบ้านเตรียมตัวหรือไปรวมพลไม่ทัน»","«ตรวจความเฉพาะเจาะจง: มีกลุ่มเป้าหมาย สถานการณ์ สาเหตุ และผลกระทบครบ ไม่ใช่แค่คำว่า \"ดินถล่มอันตราย\" และไม่อ้างว่าทำนายได้»"]]]]]},{"h":"4. สร้างโจทย์ออกแบบหลายแนวทาง (How Might We...?)","b":[["p","รูปประโยคช่วยคิด : “เราจะออกแบบหรือพัฒนาอะไร เพื่อให้ (ใคร) สามารถ (ทำอะไรเพื่อลดความเสี่ยง) ภายใต้ (เงื่อนไข) ได้อย่างไร?”"],["t",[[["«เราจะออกแบบเสาเฝ้าไหล่เขาราคาประหยัดที่ ม.2 ทำได้ เพื่อให้ผู้ใหญ่บ้านและชาวบ้านรู้ว่าฝนสะสมและดินน่ากังวลแล้วเตรียมตัวก่อน ภายใต้เงื่อนไขที่ไม่มีใครขึ้นเขาตอนฝนหนัก เหตุอาจเกิดกลางดึก และเกณฑ์ที่ใช้ยังเป็นค่าสมมติ ได้อย่างไร?»","«โจทย์ทางเลือกจากกลยุทธ์ต่างกัน: (คน) ทำให้ทุกบ้านจดและรู้ฝนสะสมจากถังวัดฝนได้อย่างไร • (เทคโนโลยี) ทำให้โหนดวัดดินและฝนแล้วแจ้งระดับอัตโนมัติได้อย่างไร • (ชุมชน) ทำให้เพื่อนบ้านคู่หูรู้ว่าต้องช่วยใครและไปจุดรวมพลที่ใดได้อย่างไร»"]]]]]},{"h":"5. สืบค้นเชิงสร้างสรรค์ : เรียนรู้จากวิธีของผู้อื่น","b":[["p","หาวิธีหรือนวัตกรรมที่ผู้อื่นใช้กับปัญหาคล้ายกัน (ภัยอื่น พื้นที่อื่น หรือกลุ่มผู้ใช้อื่น) จากแหล่งที่เชื่อถือได้ แล้วเทียบกับปัญหาของเรา"],["t",[[["วิธี/แนวทางของผู้อื่น (ที่มา)"],["ปัญหา สถานการณ์ หรือความต้องการของเขาเหมือน/ต่างจากของเราอย่างไร"],["แนวคิดที่นำมาใช้ตั้งหรือปรับโจทย์ของเรา"]],[["1.« กรมทรัพยากรธรณีออกรายงานธรณีพิบัติภัยประจำวัน ใช้เครื่องวัดฝนอัตโนมัติ เครื่องวัดแรงดันน้ำใต้ดิน และเครื่องวัดการเคลื่อนตัวของดิน มีเกณฑ์เฝ้าระวังและอพยพของเครื่องมือเหล่านั้น และมีเครือข่ายอาสาสมัครวัดฝน»","«(รายงานวันที่ 3 ก.ย. 2557 กรมทรัพยากรธรณี)»"],["«เหมือน: ใช้ฝนและการวัดที่ดินช่วยเฝ้าระวัง และใช้อาสาสมัครวัดฝน»","«ต่าง: ของจริงใช้เครื่องมือราคาสูงที่ผู้เชี่ยวชาญติดตั้งและมีเกณฑ์ของตัวเอง เซนเซอร์ความชื้นดินของเราใช้เกณฑ์นั้นไม่ได้»"],["«นำแนวคิดอาสาสมัครวัดฝนมาทำถังวัดฝนและสมุดจด และขอเกณฑ์จริงจากหน่วยงาน ไม่ใช้เกณฑ์ในรายงานกับเซนเซอร์ของเรา»"]],[["2.« ถังวัดฝนทำเองจากขวดพลาสติกปากกว้าง กรวย และสเกล mm»","«(ความรู้ทั่วไป ไม่มีลิงก์ — ยังไม่ได้ตรวจกับแหล่งใด)»"],["«ต่างเรื่อง แต่ปัญหาคล้ายกัน: ให้คนรู้ว่าฝนตกสะสมเท่าไรโดยไม่ต้องใช้ไฟฟ้า»","«ต่าง: ต้องมีคนไปอ่านและจดเป็นเวลา ไม่แจ้งอัตโนมัติ และบอกเองไม่ได้ว่าเท่าไรคือน่ากังวล»"],["«ใช้เป็นแนวคิดที่ 1 และเป็นค่าเทียบกับที่วัดฝนของโหนดซึ่งอาจหายเมื่อรีเซ็ต»"]]]],["p","ตั้งคำถาม “ถ้า...จะเป็นอย่างไร?” 1 ข้อ แล้วลองตอบ — คำตอบทำให้เข้าใจปัญหาลึกขึ้น หรือทำให้ได้ทางแก้ใหม่อย่างไร"],["t",[[["«ถ้าบอร์ดรีเซ็ตหรือไฟดับ ฝนสะสม 24 ชม. หายไป ระบบจะบอกว่าฝนน้อยและไฟที่ศาลาเป็นสีเขียวหรือไม่?»","«คำตอบ: ต้นแบบไม่ส่งช่องฝนจนกว่าบอร์ดจะเดินครบ 24 ชม. (จอขึ้น RAIN WARMUP) จึงไม่แสดงฝนน้อยปลอม แต่ระหว่างนั้นระดับมาจากความชื้นดินอย่างเดียว ซึ่งอาจต่ำกว่าสถานการณ์จริงถ้าเพิ่งฝนหนัก»","«ผล: ได้โจทย์ใหม่ — ต้องมีป้ายบอกช่วง 24 ชม. แรกหลังรีเซ็ต และให้ผู้ใหญ่หรืออาสากรอกค่าฝนจากถังวัดฝนในพื้นที่อาสา พร้อมสมุดสังเกตเป็นค่าสำรอง»"]]]]]},{"h":"6. ตรวจความชัดเจนและปรับกรอบโจทย์ (Reframe)","b":[["p","«☒» ระบุผู้ใช้ชัด    «☒» ช่วยลดความเสี่ยงจริง    «☒» ขอบเขตพอดีกับ 15 ชั่วโมง    «☒» ทำต้นแบบจำลองได้    «☒» ไม่อันตราย"],["p","โจทย์ก่อนรับข้อเสนอแนะ / ใครเสนอให้มองต่าง / โจทย์หลังปรับ / ข้อมูลหรือเหตุผลที่ยืนยันว่าดีขึ้น"],["t",[[["«โจทย์ก่อนรับข้อเสนอแนะ: \"ทำเซนเซอร์ดินและฝนแล้วเตือนชาวบ้านเมื่อดินจะถล่ม\"»","«ข้อเสนอแนะ (เพื่อนกลุ่มอื่นและครู): เซนเซอร์จุดเดียวทำนายดินถล่มไม่ได้ ฝนสะสมของบอร์ดหายเมื่อรีเซ็ต และนักเรียนต้องไม่ขึ้นเขาไปดูหรือติดตั้งเอง»","«โจทย์หลังปรับ: ทำเสาเฝ้าไหล่เขา — โหนดวัดดินและฝนที่ผู้ใหญ่ติดตั้ง สมุดสังเกตและถังวัดฝนที่อาสาจด ช่องกรอกฝนด้วยมือ ข้อความ \"สิ่งที่ควรทำ\" และจุดรวมพล โดยให้ผู้ใหญ่บ้าน/อบต. ตัดสินใจอพยพ»","«เหตุผลที่ดีขึ้น: ตรงกับข่าวที่ฝนต่อเนื่องและเหตุกลางดึก ไม่อ้างว่าทำนายได้ ใช้ค่าสมมติที่ต้องแทนด้วยเกณฑ์จริง และไม่ให้นักเรียนเสี่ยงบนเขา»"]]]]]}]},"a3":{"pre":[["p","ภารกิจ : ต้องคิดเองก่อนใช้ AI จากนั้นแลกเปลี่ยนกับเพื่อนและใช้ AI เพื่อขยาย/ตรวจสอบ ไม่ใช่คัดลอกคำตอบโดยไม่คิด ใบกิจกรรมนี้ดูว่าเราทำงานกับความคิดของผู้อื่นอย่างไร ตั้งแต่เปรียบเทียบ ผสาน ต่อยอด จนสังเคราะห์"]],"secs":[{"h":"1. คิดด้วยตนเองก่อนเปิด AI","b":[["p","ทุกคนกรอกบัตรรายบุคคล 3 แนวคิดต่างกลไก (หน้าถัดไป) ก่อนเปิด AI และก่อนแลกเปลี่ยนความคิดกับเพื่อน บัตรนี้คือ “ความคิดของฉัน” ที่จะใช้เปรียบเทียบและผสานกับผู้อื่นในส่วนที่ 2–5"],["p","«☒» สมาชิกทุกคนส่งบัตรก่อนเปิด AI ครบแล้ว"],["p","ลำดับการทำงานในใบกิจกรรมนี้"],["t",[[["ส่วน"],["ทำอะไร"],["ทำกับใคร / ใช้อะไร"]],[["1"],["คิดเอง 3 แนวทางลงบัตรรายบุคคล"],["ทำคนเดียว ก่อนเปิด AI"]],[["2"],["เปรียบเทียบความคิดของเรากับความคิดของเพื่อน"],["ฟังและบันทึกร่วมกันในกลุ่ม"]],[["3"],["ผสานส่วนที่ดีของเพื่อนอย่างน้อย 2 คนเข้ากับความคิดของเรา"],["สมาชิกในกลุ่ม"]],[["4"],["ต่อยอดกับเพื่อนและ AI แล้วตรวจสอบก่อนนำไปใช้"],["กลุ่ม + AI (มนุษย์เป็นผู้ตรวจและเลือก)"]],[["5"],["สังเคราะห์เป็น 3 แนวคิดที่แตกต่างกันจริงของกลุ่ม"],["ทั้งกลุ่ม"]]]],["sh","บัตรคิดเองก่อนใช้ AI (รายบุคคล)"],["p","ให้บันทึกก่อนเปิด AI / ก่อนแลกเปลี่ยนข้อเสนอของ AI เพื่อเก็บ “ความคิดของฉัน” ไว้เป็นฐานสำหรับเปรียบเทียบและผสานกับความคิดของผู้อื่น"],["p","ชื่อ–สกุล «นักเรียน จ (ตัวอย่าง)»  ·  ห้อง   ·  เลขที่   ·  กลุ่ม «5»  ·"],["p","โจทย์ภัยธรรมชาติที่ต้องการแก้ «ให้รู้ว่าฝนสะสมและดินน่ากังวล»  ·"],["p","คิดเอง 3 แนวทาง โดยพยายามให้กลไกช่วยลดความเสี่ยงต่างกัน"],["p","เขียนชื่อวิธี หลักการทำงาน ผู้ใช้ และเหตุผลที่คาดว่าจะช่วยแก้ปัญหาได้"],["p","แนวคิดที่ 1: ชื่อวิธี / ทำงานอย่างไร / ช่วยใคร / เหตุผล (เขียนโดยไม่ใช้ AI)"],["t",[[["«ชื่อวิธี: สมุดสังเกตไหล่เขาและถังวัดฝน — ผู้ใหญ่หรืออาสาจดฝนทุกวัน และสังเกตจากพื้นราบที่ปลอดภัยว่ามีรอยแตก ต้นไม้เอียง น้ำขุ่นไหลจากเขาหรือไม่»","«ช่วยใคร: ผู้ใหญ่บ้านและครัวเรือนใกล้เชิงเขา • เหตุผล: ไม่ใช้ไฟฟ้าหรือเน็ต แต่ต้องมีคนจดทุกวันและไม่ออกไปดูตอนฝนตกหนัก»"]]]],["p","แนวคิดที่ 2: ชื่อวิธี / ทำงานอย่างไร / ช่วยใคร / เหตุผล (เขียนโดยไม่ใช้ AI)"],["t",[[["«ชื่อวิธี: โหนดดินและฝน — บอร์ด IPST-WiFi อ่านความชื้นดินและนับฝน แสดงระดับบนจอที่โหนด ส่งขึ้นเว็บ และมีไฟเตือนที่ศาลา»","«ช่วยใคร: ผู้ใหญ่บ้านและอาสา • เหตุผล: ได้ค่าต่อเนื่องแม้กลางคืนโดยไม่ต้องขึ้นเขา แต่เป็นแค่ตัวช่วยเฝ้า ไม่ใช่การทำนาย»"]]]],["p","แนวคิดที่ 3: ชื่อวิธี / ทำงานอย่างไร / ช่วยใคร / เหตุผล (เขียนโดยไม่ใช้ AI)"],["t",[[["«ชื่อวิธี: เพื่อนบ้านคู่หูและจุดรวมพล — ตกลงล่วงหน้าว่าบ้านใครไปกับใคร ทางไหนไปจุดรวมพล และซ้อมเดินตอนอากาศปกติ»","«ช่วยใคร: ผู้สูงอายุและผู้ป่วยอยู่คนเดียว • เหตุผล: ไม่ต้องใช้เทคโนโลยี แต่ผู้ใหญ่/อบต. ต้องกำหนดจุดรวมพลที่ปลอดภัย»"]]]],["p","แนวคิดทั้ง 3 ต่างกันตรงหลักการทำงานหรือวิธีช่วยผู้ใช้อย่างไร (ไม่ใช่แค่ชื่อหรือสี)"],["t",[[["«ต่างที่กลไก: (1) คนจดฝนและสังเกตแล้วบอกต่อ (2) เครื่องอ่านดินและฝนต่อเนื่องแล้วแจ้งระดับ (3) คนช่วยกันพาไปจุดรวมพล»","«แต่ละแบบแก้จุดอ่อนของอีกแบบ: (1) จดได้เฉพาะตอนมีคนอยู่ (2) ฝนสะสมของบอร์ดหายเมื่อรีเซ็ต ดินจุดเดียวบอกไม่ได้ว่าเขาลูกไหนเสี่ยง (3) ไม่รู้ว่าเมื่อไรควรเตรียมตัว»"]]]],["p","ฉันเริ่มคิดเวลา «09.10»  ส่งบัตรนี้เวลา «09.30»   «☒» ก่อนเปิด AI    ☐ ก่อนอ่านคำตอบจาก AI"],["p","หมายเหตุ: นักเรียนทุกคนต้องคิดด้วยตนเอง 3 แนวทางที่พยายามใช้กลไกช่วยลดความเสี่ยงแตกต่างกันก่อนใช้ AI ทั้งนี้จำนวนแนวคิดเป็นเพียงเงื่อนไขให้มีหลักฐานเพียงพอ ไม่ใช้จำนวนแนวคิดเพียงอย่างเดียวตัดสินความสร้างสรรค์"]]},{"h":"2. เปรียบเทียบความคิดของเรากับความคิดของเพื่อน","b":[["p","สมาชิกแต่ละคนเล่าแนวคิดที่ตนชอบที่สุด 1 ข้อ ทุกคนฟังให้ครบ แล้วบันทึกว่าเหมือนหรือต่างจากความคิดของตนเองอย่างไร"],["t",[[["สมาชิก/ผู้เสนอ"],["ข้อเสนอ (สรุปสั้น)"],["เหมือน/ต่างจากความคิดของฉันอย่างไร"],["สิ่งที่กลุ่มเห็นว่าน่าสนใจ"]],[["1.« ก»  ·"],["«กระเป๋าฉุกเฉิน 1 ใบต่อบ้านใกล้เชิงเขา วางใกล้ประตู ใส่ไฟฉาย ยาประจำตัว สำเนาบัตร และเบอร์ผู้ใหญ่บ้านกับ ปภ. 1784»"],["«เหมือน: เตรียมก่อนเหตุ ต่าง: ของ ก เตรียมของทีละบ้านด้วยคน ใช้ได้ตอนไฟดับ ของฉันดูฝนและดินด้วยเครื่อง»"],["«ทุกบ้านพร้อมออกจากบ้านได้ทันทีเมื่อผู้ใหญ่บ้านแจ้ง»"]],[["2.« ข»  ·"],["«ไฟ 3 ดวงที่ศาลา เขียว เหลือง แดงกะพริบ มองเห็นจากลานและทางเข้าหมู่บ้าน»"],["«เหมือน: บอกด้วยสี ต่าง: ของ ข อยู่ที่ศาลาให้ทุกคนเห็น ของฉันเป็นจอ OLED ที่โหนดต้องไปดูเอง»"],["«คนใกล้ศาลาเห็นระดับโดยไม่ต้องใช้มือถือ (ไฟที่ศาลาถามเว็บ จึงต้องมีเน็ต)»"]],[["3.« ค»  ·"],["«ตารางสิ่งที่ต้องทำในแต่ละระดับ และแผนที่จุดรวมพล ติดที่ศาลา เช่น ระดับ 2 = เตรียมออกจากบ้านใกล้เชิงเขา ย้ายไปบ้านญาติหรือศูนย์พักพิง»"],["«ต่างมาก: ไม่ใช้เทคโนโลยี แต่ใช้ร่วมกับของฉันได้เมื่อรู้ระดับ»"],["«ทุกคนรู้ว่าแต่ละระดับต้องทำอะไรและไปที่ไหน โดยใช้ข้อความมาตรฐานเดียวกัน»"]],[["4.« ง»  ·"],["«บันทึกฝนรายวันจากถังวัดฝนลงชีต และจดวันที่ฝนหนักเทียบกับข่าวเหตุแต่ละครั้ง เพื่อปรับเกณฑ์ภายหลัง»"],["«ต่าง: ของ ง ดูย้อนหลัง ไม่เตือนทันที แต่ช่วยตรวจว่าที่วัดฝนของโหนดอ่านถูกหรือไม่»"],["«ทำให้เกณฑ์ของหมู่บ้านมีหลักฐาน แทนตัวเลขสมมติ»"]],[["5.  ·","​"],["​","​"],["​","​"],["​","​"]]]],["p","จุดร่วมและจุดต่างที่เห็นเด่นที่สุดในข้อเสนอของสมาชิกทั้งหมด"],["t",[[["«จุดร่วม: ทุกคนต้องการให้ \"ชาวบ้านรู้ก่อนและรู้ว่าต้องทำอะไร\" โดยไม่ต้องมีใครขึ้นเขาตอนฝนตกหนัก»","«จุดต่าง: ใช้คนจดและช่วยกัน (ก ค) หรือใช้เครื่องและไฟ (ข จ) หรือเก็บข้อมูลย้อนหลัง (ง) ยังไม่มีใครคิดว่าถ้าบอร์ดรีเซ็ตแล้วฝนสะสมหาย หรือค่าดินจุดเดียวไม่ตรงกับเขาทั้งลูก จะทำอย่างไร»"]]]]]},{"h":"3. ผสานความคิดของสมาชิก","b":[["p","เลือกส่วนที่ดีของข้อเสนอจากสมาชิกอย่างน้อย 2 คน มาผสานกับความคิดของตนเอง"],["t",[[["เจ้าของแนวคิดที่ 1 + ส่วนที่เลือก"],["เจ้าของแนวคิดที่ 2 + ส่วนที่เลือก"],["เจ้าของแนวคิดที่ 3 + ส่วนที่เลือก"]],[["ชื่อ« ก»  ·","ส่วนที่เลือก« กระเป๋าฉุกเฉินและเบอร์ฉุกเฉิน»","«เหตุผล: ทำให้ออกจากบ้านได้เร็วเมื่อเหตุเกิดกลางดึก»","«ปรับ: ไม่ใส่ชื่อ ที่อยู่ หรือรายชื่อผู้ป่วยบนป้ายสาธารณะ เก็บในพื้นที่อาสาที่ใช้ PIN»"],["ชื่อ« ข»  ·","ส่วนที่เลือก« ไฟ 3 ดวงที่ศาลา»","«เหตุผล: คนใกล้ศาลาเห็นระดับโดยไม่ต้องใช้มือถือ»","«ปรับ: ติดป้ายบอกว่าเหลือง = ระดับ 1 แดงกะพริบช้า = ระดับ 2 แดงกะพริบเร็ว = ระดับ 3 และปิดเสียงไว้จนกว่าตกลงความหมายกับผู้ใหญ่บ้าน»"],["ชื่อ« ค»  ·","ส่วนที่เลือก« ตารางสิ่งที่ต้องทำและจุดรวมพล»","«เหตุผล: ทุกคนทำตามข้อตกลงเดียวกัน»","«ปรับ: ให้ผู้ใหญ่บ้าน/อบต. เป็นผู้กำหนดจุดรวมพลและเส้นทาง นักเรียนไม่เลือกเอง»"]]]],["p","ความคิดใหม่ที่เกิดจากการผสาน — ส่วนใดของเพื่อนอย่างน้อย 2 คนที่นำมาผสานกับความคิดของเรา และผลเป็นอย่างไร"],["t",[[["«ความคิดใหม่: \"เสาเฝ้าไหล่เขา\" = สมุดสังเกตและถังวัดฝน (ของฉัน) + โหนดดินและฝนที่ผู้ใหญ่ติดตั้ง (ของฉัน) + ไฟ 3 ดวงที่ศาลา (ของ ข) + ตารางสิ่งที่ต้องทำและจุดรวมพล (ของ ค)»","«ผลที่ได้: ระหว่างฝนหนักผู้ใหญ่บ้านได้ข้อความและคนใกล้ศาลาเห็นไฟ ถ้าเน็ตหลุด จอและบัซเซอร์ที่โหนดยังแสดงระดับเอง (ต้องมีไฟเลี้ยง) ส่วนไฟที่ศาลาสลับสีบอกว่า \"ไม่มีข้อมูล\" ไม่ติดเขียวค้าง»","«ส่วนของ ก (กระเป๋าฉุกเฉิน) ใส่ไว้ในข้อความระดับ 1–2 ส่วนของ ง (บันทึกฝนรายวัน) ใช้ชีต Readings ของระบบที่เก็บค่าให้อยู่แล้ว และเปรียบเทียบกับถังวัดฝนที่อาสาจด»"]]]]]},{"h":"4. ต่อยอดกับเพื่อนและ AI","b":[["p","AI เป็นอีกแหล่งข้อเสนอหนึ่ง กลุ่มต้องเป็นผู้ตรวจและเลือก Prompt ต้องระบุปัญหา ผู้ใช้ ข้อจำกัด (เช่น ไม่มีไฟ/ไม่มีเน็ต) และขอทางเลือกที่ ม.2 ทำต้นแบบได้"],["p","Prompt ที่ใช้จริง (ไม่เขียนข้อมูลส่วนบุคคลหรือข้อมูลอ่อนไหว)"],["t",[[["«ฉันเป็นนักเรียน ม.2 ในจังหวัดอุตรดิตถ์ กำลังทำต้นแบบ \"เสาเฝ้าไหล่เขา\" ให้ผู้ใหญ่บ้านและชาวบ้านใกล้เชิงเขารู้ว่าฝนสะสมและดินน่ากังวลแล้วเตรียมตัวก่อน ผู้ใช้คือผู้ใหญ่บ้านและอาสาที่จดฝน»","«ข้อจำกัด: ไม่มีเครื่องมือมาตรฐานของหน่วยงาน งบจำกัด ใช้บอร์ด IPST-WiFi (ESP32) ที่โรงเรียนมี เซนเซอร์ความชื้นดินและที่วัดฝนทำเองต้องสอบเทียบ และเกณฑ์จริงเรายังไม่มี»","«ขอทางเลือก 5 แนวทางที่ ม.2 ทำเป็นต้นแบบจำลองได้ พร้อมข้อควรระวังด้านความปลอดภัย (ไม่ขึ้นไหล่เขา ไม่ปักเซนเซอร์ในที่เสี่ยง ไม่ไปสังเกตตอนฝนตกหนัก)»"]]]],["t",[[["ข้อเสนอที่ AI ให้"],["เหตุผลรับ/ไม่รับ (ความปลอดภัย–ผู้ใช้–ทรัพยากร)"],["ตรวจสอบหรือปรับด้วยตนเอง/ร่วมกับเพื่อน"]],[["1.« ทำถาด \"ลาดเขาจำลอง\" ใส่ดินร่วนผสมทราย เอียงราว 20–30° ฝังเซนเซอร์ดินตื้น ๆ รดน้ำด้วยบัวรดน้ำและตวงน้ำที่ใช้ แล้วดูค่าดินและบันทึกว่าดินในถาดเริ่มเลื่อนเมื่อใด»"],["«รับ: ปลอดภัย ทำในห้องเรียนได้ และได้ฝึกวัดและทำตาราง»"],["«จดปริมาณน้ำที่รดกับค่า soil_pct ทุกรอบ ผลบอกได้แค่ \"รูปแบบ\" ว่าค่าดินเพิ่มตามน้ำ ห้ามเอาเกณฑ์จากถาดไปใช้กับเขาจริง»"]],[["2.« ไปปักเซนเซอร์บนไหล่เขาจริงและดูตอนฝนตกหนักเพื่อเก็บข้อมูลจริง»"],["«ไม่รับ: อันตรายจากดินถล่มและน้ำป่า ห้ามนักเรียนขึ้นไหล่เขา ปักเซนเซอร์ในพื้นที่เสี่ยง หรือไปดูตอนฝนตกหนัก»"],["«ใช้ถาดจำลองและโหมดจำลอง และขอข้อมูลจริงย้อนหลังจาก อบต. ผู้ใหญ่/อบต. เป็นผู้ติดตั้งตอนอากาศปกติ»"]]]],["p","AI ช่วยตรงไหน? เราคัดทิ้ง/แก้ไขอะไรเพราะเหตุใด และใช้แหล่งใดตรวจสอบคำแนะนำที่เกี่ยวกับภัย"],["t",[[["«AI ช่วย: เสนอให้ทำถาดลาดเขาจำลองและสอบเทียบเซนเซอร์ดินด้วยค่าในอากาศกับจุ่มน้ำ และช่วยร่างข้อความแจ้ง 4 ระดับ»","«เราคัดทิ้ง: การให้นักเรียนปักเซนเซอร์บนเขาจริง คำว่า \"ทำนายดินถล่มได้\" และตัวเลขเกณฑ์ที่ AI เสนอโดยไม่บอกที่มา»","«ตรวจสอบกับ: กรมทรัพยากรธรณี ครู ผู้ใหญ่บ้าน/อบต. และ ปภ. (1784) เกณฑ์ 60/75/90 % และ 60/90/120 mm ในต้นแบบเป็นค่าสมมติ»"]]]],["p","ผังที่มาของความคิดใหม่ — เชื่อมความคิดของเพื่อน/AI เข้ากับความคิดของเรา"],["t",[[["ความคิดตั้งต้น (ของใคร)"],["ส่วนที่ต่อยอดจากเพื่อน/AI"],["ข้อค้นพบหรือมุมมองใหม่ที่เกิดขึ้น"],["ต่างจากข้อเสนอเดิมอย่างไร"]],[["«ของฉัน: โหนดดินและฝน แสดงระดับบนจอที่โหนดไม่พึ่งเน็ต»"],["«จาก ข: ไฟ 3 ดวง»","«จาก ค: ตารางสิ่งที่ต้องทำ»"],["«แสดงผล 3 ชั้น และเพิ่มสมุดสังเกตเป็นค่าสำรอง»"],["«เดิมมีเครื่องอย่างเดียว ใหม่มีไฟ ข้อความ และสิ่งที่ควรทำ»"]],[["«ของฉัน: ถาดลาดเขาจำลอง»"],["«จาก AI: วิธีสอบเทียบเซนเซอร์ดินด้วยค่าในอากาศและจุ่มน้ำ»"],["«ต้องบอกว่าเป็น \"ค่าจากถาดจำลอง\" และบอกวันที่สอบเทียบ»"],["«เดิมใช้ค่าตั้งต้น 3000 และ 1300 ใหม่มีค่าที่วัดเองและบันทึกวันที่»"]]]]]},{"h":"5. สังเคราะห์เป็น 3 แนวคิดที่แตกต่างกันจริง","b":[["p","ส่วนนี้เป็น 3 แนวทางของกลุ่ม ส่วนรายบุคคลให้ตรวจบัตรคิดเอง 3 แนวทางของแต่ละคน ไม่ใช้ผลรวมกลุ่มแทนความคิดของคนใดคนหนึ่ง"],["t",[[["แนวคิด/วิธีทำงาน"],["ที่มา: ใครคิด (สมาชิก/AI) จุดแข็งหรือมุมมองของใครที่นำมาใช้ และต่อยอดส่วนใด"],["เหมาะกับใครและลดความเสี่ยงอย่างไร"]],[["1.« สมุดสังเกต + ถังวัดฝน»","«อาสาจดฝนและสังเกตเขา»"],["«ฉันคิดสมุด ค คิดตาราง ง คิดบันทึกฝน»"],["«ผู้ใหญ่บ้านและอาสา»","«ลดความเสี่ยงโดยรู้ฝนสะสม»"]],[["2.« โหนดดิน + ฝน»","«แจ้งมือถือผ่าน Apps Script»"],["«ฉันคิดโหนด ข คิดไฟ AI เสนอสอบเทียบ»"],["«ผู้ใหญ่บ้านและอาสา»","«ลดความเสี่ยงโดยมีค่าต่อเนื่อง»"]],[["3.« เพื่อนบ้านคู่หู + จุดรวมพล»","«ตกลงว่าใครไปกับใคร ทางไหน»"],["«ก คิดกระเป๋าฉุกเฉิน ฉันคิดคู่หู»"],["«ผู้สูงอายุอยู่คนเดียว»","«ลดความเสี่ยงโดยมีคนช่วยก่อน»"]]]],["p","แนวคิดที่กลุ่มภูมิใจที่สุด ต่างจากก่อนผสาน/ก่อนใช้ AI อย่างไร (ระบุสิ่งที่คิดเองชัดเจน) และเหตุใดจึงรวมเป็นผลงานหนึ่งเดียวของกลุ่มได้"],["t",[[["«แนวคิดที่ภูมิใจที่สุด: สมุดสังเกตและถังวัดฝนคู่กับโหนด — เพราะฝนสะสมของโหนดหายเมื่อรีเซ็ต การมีคนจดฝนเป็นค่าสำรองช่วยได้มาก»","«สิ่งที่ฉันคิดเอง: สมุดสังเกต โหนดดินและฝน คู่หู • จากเพื่อน: กระเป๋าฉุกเฉิน ไฟ 3 ดวง ตารางสิ่งที่ต้องทำ • จาก AI: สอบเทียบเซนเซอร์»","«รวมกันได้เพราะทุกส่วนใช้ \"ระดับ 0–3\" เดียวกัน»"]]]]]}]},"a4":{"pre":[["p","ภารกิจ : ใช้ 3 ทางเลือกที่สร้างไว้ เปรียบเทียบความเหมาะสมและความปลอดภัย แล้วทำภาพร่าง/ผังงานที่ผู้อื่นนำไปสร้างต้นแบบได้ จากนั้นทดลองบนกระดาษ รับข้อเสนอแนะ และปรับเป็นแบบร่างรุ่นที่ 2"]],"secs":[{"h":"1. เปรียบเทียบ 3 แนวคิดโดยดูผู้ใช้และข้อจำกัด","b":[["t",[[["แนวคิด"],["ข้อดีต่อผู้ใช้"],["ข้อจำกัด/ความเสี่ยง"],["ทำได้จริงภายในเวลาอย่างไร"]],[["1.« สมุดสังเกต + ถังวัดฝน»"],["«ไม่ใช้ไฟฟ้า รู้ฝนสะสมจากการจดจริง เป็นค่าสำรองของโหนด»","«ทุกคนคุ้นกับการสังเกตเขาและฝน»"],["«ต้องมีคนจดทุกวัน ลืมหรืออ่านผิดได้ เตือนกลางดึกไม่ได้»","«ค่าฝนต่างกันตามที่ตั้งถังวัดฝน»"],["«ขวด กรวย ไม้บรรทัด สมุด ทำได้ใน 1–2 ชั่วโมง»","«ผู้ใหญ่เลือกจุดตั้งที่ปลอดภัย»"]],[["2.« โหนดดิน + ฝน»"],["«มีค่าดินและฝนต่อเนื่องแม้กลางคืนและไม่ต้องขึ้นเขา แจ้งผู้ใหญ่บ้านอัตโนมัติ»"],["«ฝนสะสมหายเมื่อรีเซ็ต ดินจุดเดียวบอกไม่ได้ว่าเขาลูกไหนเสี่ยง เกณฑ์เป็นค่าสมมติ»"],["«ใช้ IPST-WiFi + เซนเซอร์ดิน + ที่วัดฝน + Apps Script ทดสอบกับถาดจำลอง»"]],[["3.« เพื่อนบ้านคู่หู + จุดรวมพล»"],["«ผู้สูงอายุและผู้ป่วยรู้ว่ามีคนช่วยและรู้ทางไปที่ปลอดภัย โดยไม่พึ่งเทคโนโลยี»"],["«ไม่บอกเวลาที่ควรเริ่มเตรียมตัว และจุดรวมพลต้องปลอดภัยจริง»"],["«ทำรายชื่อคู่หูและแผนที่ตัวอย่างได้ใน 5 ชั่วโมงลงมือ แต่ผู้ใหญ่/อบต. เลือกจุดรวมพล»"]]]],["p","แนวคิดที่เลือกคือ «แนวคิดที่ 1 + โหนดดินและฝนของแนวคิดที่ 2» เหตุผลที่เลือก (แก้ตรงโจทย์ ผู้ใช้ ทรัพยากร ความปลอดภัย)"],["t",[[["«แก้ตรงโจทย์: เลือกแนวคิดที่ 1 เป็นแกน เพราะคนจดฝนและสังเกตเป็นค่าที่ไว้ใจได้เมื่อไฟดับหรือบอร์ดรีเซ็ต แล้วนำโหนดดินและฝนของแนวคิดที่ 2 มาช่วยเฝ้าต่อเนื่องกลางคืน ส่วนเพื่อนบ้านคู่หูและจุดรวมพลของแนวคิดที่ 3 เป็นงานคู่ขนานที่ผู้ใหญ่/อบต. ร่วมกำหนด»","«ผู้ใช้: ผู้ใหญ่บ้านได้ข้อความพร้อม \"สิ่งที่ควรทำ\" และตัดสินใจอพยพเอง ส่วนคนใกล้ศาลาเห็นสีไฟ»","«ทรัพยากร/ความปลอดภัย: ใช้บอร์ดที่โรงเรียนมี ใช้ไฟ 5 V จากพาวเวอร์แบงก์ ผู้ใหญ่/อบต. เป็นผู้ติดตั้งโหนดตอนอากาศปกติ นักเรียนทดสอบเฉพาะในห้องกับถาดจำลอง ไม่ขึ้นเขา»"]]]],["p","เหตุผลที่ไม่เลือกอีก 2 แนวคิด (หรือส่วนที่ตัดสินใจละทิ้ง) และเงื่อนไขใดอาจทำให้เปลี่ยนการตัดสินใจ"],["t",[[["«แนวคิดที่ 2 เดี่ยว ๆ: ฝนสะสมหายเมื่อรีเซ็ตและดินจุดเดียวไม่พอ จึงใช้เป็นตัวช่วยเฝ้าของแนวคิดที่ 1 ไม่ใช้เป็นตัวตัดสิน»","«แนวคิดที่ 3: จุดรวมพลต้องให้ผู้ใหญ่/อบต. เลือกและตรวจว่าปลอดภัย และไม่บอกว่าเมื่อไรควรเริ่มเตรียมตัว ใน 15 ชั่วโมงทำได้เพียงรายชื่อคู่หูและแผนที่ตัวอย่างบริเวณศาลา จึงไม่ทำทั้งหมู่บ้าน»","«เปลี่ยนใจได้ถ้า: ที่ตั้งโหนดที่ปลอดภัยอยู่ไกลจน Wi-Fi ไม่ถึง → ใช้แนวคิดที่ 1 เป็นหลัก และให้อาสากรอกค่ามือ • หรือเซนเซอร์ดินสอบเทียบไม่ได้ → เรียกว่า \"ค่าสัมพัทธ์\" และใช้ฝนจากถังวัดฝนเป็นหลัก»"]]]]]},{"h":"2. ร่างแบบรุ่นที่ 1 และอธิบายหลักการทำงาน","b":[["p","วาดแผนภาพ/ผังงานขนาดใหญ่ ระบุส่วนประกอบ ลำดับการทำงาน ทางเข้าของข้อมูล ผลลัพธ์ และจุดที่ผู้ใช้จะโต้ตอบกับต้นแบบ"],["t",[[["พื้นที่ภาพร่าง/ผังงาน (ใช้ลูกศร หมายเลข และคำอธิบายกำกับ)"]]]],["p","อธิบาย 1) ต้นแบบเริ่มทำงานอย่างไร 2) ผู้ใช้ได้รับประโยชน์อะไร 3) หากไฟดับ/ไม่มีอินเทอร์เน็ตจะทำอย่างไร"],["t",[[["«1) เริ่มทำงาน: เปิดโหนดที่ผู้ใหญ่ติดตั้ง อ่านความชื้นดิน 9 ครั้งแล้วใช้ค่ากลาง นับฝนจากที่วัดฝนกระดกน้ำ แปลงเป็นระดับ 0–3 จอ OLED ที่โหนดแสดงระดับและส่งค่าขึ้นเว็บ ส่วนไฟที่ศาลาถามเว็บแล้วเปลี่ยนสี»","«2) ประโยชน์: ผู้ใหญ่บ้านได้ข้อความ \"ระดับ 2 ฝนสะสมและดินน่ากังวล เตรียมตัว\" ส่วนไฟที่ศาลาให้คนใกล้เคียงเห็น พักระหว่างรอบ 5 นาที ถี่ขึ้นเป็น 30 วินาทีเมื่อถึงระดับ 3»","«3) ไฟดับ/ไม่มีเน็ต: โหนดใช้พาวเวอร์แบงก์ (ยังไม่ได้ทดสอบว่าอยู่ได้กี่ชั่วโมง) แสดงระดับบนจอเองได้ ไฟที่ศาลาสลับไฟบอกว่า \"ไม่มีข้อมูล\" ไม่ติดเขียวค้าง ถ้าเซนเซอร์เงียบเกิน 30 นาที เว็บแสดง \"ไม่มีข้อมูล\"»"]]]]]},{"h":"3. ขยายความคิดให้ละเอียดพอสำหรับสร้างจริง","b":[["p","เขียนให้เพื่อนกลุ่มอื่นอ่านแล้วเข้าใจว่าต้องสร้างอะไร"],["t",[[["ส่วนประกอบของต้นแบบ"],["ลักษณะเฉพาะ/วิธีทำงาน","(ขนาด วัสดุที่คิดไว้ ข้อมูลเข้า–ออก)"],["ผู้ใช้โต้ตอบกับส่วนนี้อย่างไร"]],[["1.« โหนดดินและฝน»","«IPST-WiFi + เซนเซอร์ความชื้นดิน + ที่วัดฝนกระดกน้ำ + จอ OLED»"],["«เข้า: ค่าดิบของเซนเซอร์ดิน (ค่ากลางของ 9 ครั้ง) แปลงเป็น % ด้วยค่า SOIL_RAW_DRY/WET และจำนวนครั้งที่ถังกระดก × 0.2 mm»","«ออก: ระดับ 0–3 + จอ OLED + ส่งข้อมูลขึ้นเว็บ»"],["«ผู้ใช้ไม่ต้องกดอะไร ดูระดับบนจอที่โหนด»","«ผู้ใหญ่ติดตั้งกล่องกันน้ำในที่ปลอดภัยตอนอากาศปกติ และตรวจเป็นประจำ»"]],[["2.« เซิร์ฟเวอร์»","«Google Apps Script Web App + Google Sheet»"],["«รับข้อมูลที่มีรหัสลับ คำนวณระดับ เก็บประวัติดินและฝน»","«แจ้ง Telegram/LINE และแสดงหน้าเว็บบนมือถือ»"],["«ผู้ใหญ่บ้านเปิดหน้าเว็บดูสถานะและกราฟ»","«อาสากรอกค่าฝนจากถังวัดฝนในพื้นที่อาสา (ใส่ PIN)»"]],[["3.« ไฟ 3 ดวงที่ศาลา»","«IPST-WiFi ตัวที่ 2 + LED เขียว/เหลือง/แดง (ปิดเสียงก่อน)»"],["«ถามระดับจากเว็บทุก 10–20 วินาที»","«เขียว/เหลืองติดนิ่ง แดงกะพริบ (ช้า = ระดับ 2 เร็ว = ระดับ 3)»"],["«คนใกล้ศาลาดูสีไฟและอ่านป้ายอธิบายสี»","«คนไม่มีมือถือก็เห็นระดับได้ (ต้องมีเน็ตที่ศาลา)»"]]]],["p","จุดที่ยังคลุมเครือหรือยังตอบไม่ได้ในแบบร่าง และสิ่งที่ต้องทดลองหรือหาข้อมูลเพิ่มก่อนสร้าง"],["t",[[["«ค่าความชื้นดินจากเซนเซอร์ทำเองเทียบกับดินจริงได้แค่ไหน และต่างตามชนิดดินและความลึกหรือไม่ — ต้องสอบเทียบค่าในอากาศ (SOIL_RAW_DRY) กับจุ่มน้ำ (SOIL_RAW_WET) และปรับ MM_PER_TIP ด้วยการเทน้ำที่ตวงไว้ลงที่วัดฝน (แนวทาง: ใช้ค่ากลาง 9 ครั้ง)»","«เกณฑ์ดิน 60/75/90 % และฝน 60/90/120 mm เป็นค่าสมมติ — ยังไม่รู้ว่าเท่าไรที่เขาหน้าหมู่บ้านเริ่มอันตรายจริง หน่วยงานด้านธรณีวิทยาใช้เครื่องมืออื่น เช่น วัดแรงดันน้ำใต้ดินและการเคลื่อนตัวของดิน ต้องถามกรมทรัพยากรธรณี/ปภ./อบต. ว่ามีเกณฑ์สำหรับพื้นที่นี้หรือไม่»","«ต้นแบบนี้เตือนทันหรือไม่ — เดาว่าบอกไม่ได้ว่าเขาจะถล่มเมื่อใด เป็นแค่ตัวช่วยเตือนให้เตรียมตัว ต้องเทียบกับข่าวเหตุจริงย้อนหลัง และถามผู้ใหญ่บ้านว่าข้อความไปถึงใครใน 5 นาที»"]]]]]},{"h":"4. ทดลองบนกระดาษและปรับเป็นแบบร่างรุ่นที่ 2","b":[["p","ทดลองเดินตามสถานการณ์จำลอง 1 รอบ (บนกระดาษหรือสวมบทบาท) โดยใช้แบบร่างรุ่นที่ 1 — ผู้ใช้ทำอะไรเป็นขั้นแรก และติดขัดตรงไหน"],["t",[[["«สถานการณ์จำลอง (สมมติ): ตี 1 ฝนตกหนักทั้งคืน ฝนสะสม 24 ชม. ขึ้นจาก 40 เป็น 95 mm และดินชื้น 80 % ผู้ใหญ่บ้าน ก ถือมือถืออยู่ที่บ้าน ไฟทั้งหมู่บ้านยังไม่ดับ»","«ขั้นแรกที่ผู้ใหญ่ทำ: เปิดข้อความเตือน แล้วเปิดหน้าเว็บ ติดขัด: ข้อความบอกแค่ \"ระดับ 2\" ไม่รู้ว่าต้องแจ้งใคร ไปที่ไหน และบ้านไหนต้องช่วยก่อน»","«ติดขัดอีก: ถ้าบอร์ดเพิ่งรีเซ็ตจอจะขึ้น RAIN WARMUP ค่าฝนหาย ผู้ใหญ่ไม่มีช่องบอกระบบว่าถังวัดฝนอ่านได้เท่าไร และข้อความระดับ 3 ที่ตั้งต้นไว้ว่า \"อพยพทันที\" มาจากเกณฑ์สมมติ»"]]]],["p","ข้อเสนอแนะที่เฉพาะเจาะจงจากเพื่อน/ครู (เขียนว่าใครเสนอเรื่องใด)"],["t",[[["ข้อเสนอแนะ (ใครเสนอ)"],["สิ่งที่ปรับในแบบร่างรุ่นที่ 2"],["เหตุผล/ผลที่คาดว่าจะดีขึ้น"]],[["1.« เพื่อน ฉ (กลุ่มอื่น): ข้อความเตือนควรบอกว่าต้องทำอะไรและไปจุดรวมพลที่ไหน»"],["«เพิ่มบรรทัด \"สิ่งที่ควรทำ\" ตามระดับในชีต Actions เช่น ระดับ 2 เตรียมออกจากบ้านใกล้เชิงเขา ย้ายไปบ้านญาติหรือศูนย์พักพิง และระบุจุดรวมพลที่ผู้ใหญ่/อบต. กำหนด»"],["«ผู้ใหญ่ไม่ต้องเดา และชาวบ้านรู้ทางก่อนเหตุ»"]],[["2.« ครู: ต้องมีช่องกรอกค่าฝนด้วยมือเพราะฝนสะสมหายเมื่อรีเซ็ต และห้ามสั่งอพยพอัตโนมัติจากเกณฑ์สมมติ»"],["«เพิ่มช่องกรอกค่าฝนจากถังวัดฝนในพื้นที่อาสา (ใส่ PIN) พร้อมป้าย \"ค่าจากมือ\" แก้ข้อความระดับ 3 เป็น \"ติดต่อผู้ใหญ่บ้าน/อบต. ทันทีเพื่อตัดสินใจอพยพ โทร 1784 (ปภ.)\" และเพิ่มสมุดสังเกต»"],["«ยังรู้ฝนสะสมได้แม้บอร์ดรีเซ็ต และคนเป็นผู้ตัดสินใจอพยพ ไม่ใช่เครื่อง»"]]]],["t",[[["ภาพร่างรุ่นที่ 2 (วาดเฉพาะส่วนที่เปลี่ยน)"]]]],["p","แบบร่างรุ่นที่ 2 ต่างจากรุ่นที่ 1 อย่างไร และมีแนวทางหรือส่วนใดที่ตัดสินใจละทิ้งเพราะไม่ช่วยแก้ปัญหา"],["t",[[["«ต่างจากรุ่นที่ 1: เพิ่มสมุดสังเกตและถังวัดฝนที่อาสาจด เพิ่มช่องให้ผู้ใหญ่กรอกค่าฝนด้วยมือ เพิ่มข้อความ \"สิ่งที่ควรทำ\" และจุดรวมพล และแก้ข้อความระดับ 3 ให้ผู้ใหญ่บ้าน/อบต. ตัดสินใจอพยพ (ส่วนอื่นเหมือนเดิม)»","«ละทิ้ง: การให้นักเรียนขึ้นไหล่เขาไปปักเซนเซอร์หรือไปดูตอนฝนตกหนัก และคำว่า \"ทำนายดินถล่ม\"»","«เพราะเสี่ยงดินถล่มและน้ำป่าต่อตัวนักเรียน และเซนเซอร์จุดเดียวทำนายไม่ได้ จึงไม่ตอบปัญหาหลักคือให้คนเตรียมตัวทันเมื่อฝนสะสมน่ากังวล»"]]]]]},{"h":"5. ให้ครูตรวจแบบร่างก่อนสร้างต้นแบบ","b":[["p","☐ แบบร่างชัดเจนพอให้ผู้อื่นสร้างตามได้    ☐ ปลอดภัย ไม่ต้องทดลองในภัยจริง    ☐ อนุญาตให้สร้างต้นแบบ"],["p","ข้อเสนอแนะจากครู (ใช้เป็นข้อมูลย้อนกลับก่อนลงมือสร้าง)"],["t",[[["​","​"]]]]]}]},"a5":{"pre":[["p","ภารกิจ : สร้างต้นแบบตามภาพร่าง อธิบายสิ่งที่ทำจริง แก้ปัญหาเมื่อเจออุปสรรค และตรวจสอบการใช้ AI อย่างรอบคอบ"]],"secs":[{"h":"1. ทบทวนผู้ใช้และข้อกำหนดก่อนสร้าง","b":[["p","ใช้ข้อมูลจากใบกิจกรรมที่ 2 และแบบร่างรุ่นที่ 2 จากใบกิจกรรมที่ 4"],["t",[[["ผู้ใช้/กลุ่มเป้าหมาย"],["ความต้องการและข้อจำกัดสำคัญ"],["ส่วนของต้นแบบที่จะตอบความต้องการนี้"]],[["ผู้ใช้หลัก:« ผู้ใหญ่บ้านและ อบต./อาสาของหมู่บ้าน (ผู้ตัดสินใจอพยพและผู้จดฝน)»"],["«ต้องรู้ทันทีเมื่อฝนสะสมและดินถึงระดับที่ตกลงกัน ข้อความสั้นและบอกสิ่งที่ควรทำ ไม่เตือนผิดจนชาวบ้านเลิกเชื่อ»"],["«หน้าเว็บมือถือ + แจ้งเตือน Telegram/LINE + ข้อความ \"สิ่งที่ควรทำ\" + ช่องกรอกค่าฝนจากถังวัดฝน»"]],[["ผู้ใช้อื่นที่อาจเกี่ยวข้อง:« ผู้สูงอายุและครัวเรือนใกล้เชิงเขาที่ไม่ได้ใช้มือถือ/ไม่อ่านกลุ่ม»"],["«ต้องการสัญญาณที่เห็นง่ายจากลานและทางเข้าหมู่บ้าน และรู้ว่าต้องไปรวมพลที่ใดกับใคร»"],["«ไฟ 3 ดวงที่ศาลา และเพื่อนบ้านคู่หู ตารางสิ่งที่ต้องทำและจุดรวมพลที่ติดที่ศาลา»"]]]]]},{"h":"2. เตรียมความพร้อมและเลือกใช้ทรัพยากร","b":[["p","☐ ครูตรวจแผนแล้ว    «☒» วัสดุปลอดภัย    «☒» ไม่ทดลองในภัยจริง    «☒» ไม่ใช้ไฟฟ้าเสี่ยงอันตราย    «☒» กำหนดผู้รับผิดชอบ"],["t",[[["รายการ"],["เลือกใช้/เหตุผล"],["ข้อควรระวัง/การตรวจสอบ/ทางเลือกที่ปลอดภัย"]],[["วัสดุ–อุปกรณ์"],["«IPST-WiFi 2 ตัว เซนเซอร์ความชื้นดิน ที่วัดฝนกระดกน้ำพร้อม reed switch LED เขียว/เหลือง/แดง + ตัวต้านทาน 220 Ω พาวเวอร์แบงก์ กล่องกันน้ำ ขวดและกรวยทำถังวัดฝน ถาดดินลาดเขาจำลอง»","«เลือกเพราะโรงเรียนมีบอร์ดอยู่แล้ว วัสดุหาง่าย และทดสอบกับถาดจำลองได้โดยไม่ต้องขึ้นเขา»"],["«ใช้ไฟ 5 V จากพาวเวอร์แบงก์ ผู้ใหญ่/อบต. ติดตั้งโหนดตอนอากาศปกติ นักเรียนไม่ขึ้นไหล่เขาและไม่ปักเซนเซอร์ในที่เสี่ยง วางบอร์ดห่างถาดน้ำ»","«ตรวจเลขขา (ดิน GPIO34 ฝน GPIO23) กับคู่มือบอร์ดก่อนต่อสาย»"]],[["เครื่องมือ–เทคโนโลยี"],["«Thonny/microBlock เขียน MicroPython ลงบอร์ด • Google Apps Script + Google Sheets • Telegram Bot»","«เลือกเพราะฟรี ใช้บัญชี Google ของโรงเรียนได้»"],["«รหัสลับและโทเคนเก็บใน Script Properties ห้ามใส่ในโค้ดหรือโพสต์ในกลุ่ม»","«ไฟล์ config.py ที่มีรหัส Wi-Fi ไม่ส่งต่อ»"]],[["AI (ถ้าใช้)"],["«ใช้ AI อธิบายโค้ดอ่านดินและนับฝนที่ไม่เข้าใจ และช่วยเรียบเรียงข้อความแจ้งระดับให้สั้น»","«ไม่ให้ AI กำหนดเกณฑ์ ไม่ให้เขียนว่าทำนายได้ และไม่ให้สั่งให้ไปดูเขา»"],["«ตรวจกับกรมทรัพยากรธรณี ครู ผู้ใหญ่บ้าน/อบต. ห้ามใส่ชื่อชาวบ้านหรือที่อยู่ใน Prompt»","«เกณฑ์ใช้ค่าสมมติที่ระบุไว้ชัด จนกว่าจะได้เกณฑ์จริงจากหน่วยงาน»"]]]]]},{"h":"3. วางแผนการสร้างและคาดการณ์อุปสรรค","b":[["t",[[["ขั้นตอนลงมือสร้าง"],["ผู้รับผิดชอบ"],["หลักฐานตรวจความก้าวหน้า"]],[["ขั้น 1« ทำที่วัดฝนกระดกน้ำและต่อเซนเซอร์ดินเข้าบอร์ด ทำถังวัดฝนจากขวดไว้เทียบ ทดสอบกับถาดลาดเขาจำลองและดูค่าบนจอ»"],["«จ (ฮาร์ดแวร์) ง (ถังวัดฝนและสมุด)»"],["«ภาพโหนดและถาดจำลอง + บันทึกค่าดินเทียบน้ำที่รด»"]],[["ขั้น 2« สร้างเว็บแอป Apps Script + Google Sheet รันชุดค่าดินถล่ม ตั้ง Script Properties และทดสอบด้วยโหมดจำลอง»"],["«ก (เซิร์ฟเวอร์)»"],["«ภาพหน้าเว็บ + ข้อความทดสอบใน Telegram»"]],[["ขั้น 3« เขียนโค้ดบอร์ดส่งข้อมูลขึ้นเว็บ และต่อไฟ 3 ดวงที่ศาลา»"],["«ค (โค้ดบอร์ด) ข (ไฟ 3 ดวง)»"],["«วิดีโอสั้นไฟเปลี่ยนสีตามค่าดินและฝนจำลอง»"]],[["ขั้น 4« ทดสอบระบบรวม สอบเทียบเซนเซอร์ดินและที่วัดฝน และซ้อมสถานการณ์เน็ตหลุด/บอร์ดรีเซ็ตจำลอง»"],["«ทั้งกลุ่ม»"],["«ตารางสอบเทียบ + ใบบันทึกผลทดสอบ + ภาพถ่าย»"]]]],["p","อันตราย/ข้อจำกัดที่คาด และวิธีป้องกันหรือแผนสำรองก่อนลงมือสร้าง"],["t",[[["อันตราย/ข้อจำกัดที่คาด"],["ผลกระทบหากเกิดขึ้น"],["มาตรการป้องกัน/ทางสำรอง"],["ตรวจแล้วพบอะไร"]],[["«ขึ้นไหล่เขาไปปักเซนเซอร์หรือไปดูตอนฝนตกหนัก»"],["«ดินถล่ม น้ำป่า ลื่นล้ม ถูกสิ่งของพัดมาโดน»"],["«ผู้ใหญ่/อบต. ติดตั้งตอนอากาศปกติในที่ปลอดภัย นักเรียนทดสอบในร่มกับถาดจำลองและโหมดจำลอง ห้ามไปดูตอนฝนตกหนัก»"],["«(สมมติ) ทดสอบทั้งหมดในห้อง ไม่มีใครขึ้นเขา และวางถาดน้ำห่างบอร์ดและพาวเวอร์แบงก์»"]],[["«บอร์ดรีเซ็ตหรือไฟดับ ฝนสะสม 24 ชม. หาย หรือเซนเซอร์ดินอ่านผิด»"],["«ระดับที่ศาลาต่ำกว่าสถานการณ์จริงทั้งที่ฝนหนัก ผู้ใหญ่ตัดสินใจช้า»"],["«บอร์ดไม่ส่งช่องฝนจนเดินครบ 24 ชม. (จอขึ้น RAIN WARMUP) ผู้ใหญ่กรอกค่าฝนจากถังวัดฝนแทน เซนเซอร์เงียบเกิน 30 นาทีขึ้น \"ไม่มีข้อมูล\" และมีสมุดสังเกตเป็นค่าสำรอง»"],["«(สมมติ) ถอดไฟโหนดแล้วเสียบใหม่ จอขึ้น RAIN WARMUP และเว็บไม่ได้รับค่าฝน จึงกรอกค่าจากถังวัดฝนแทน»"]]]]]},{"h":"4. บันทึกการสร้างอย่างมีหลักฐาน","b":[["t",[[["ลำดับ"],["สิ่งที่ลงมือทำจริง (ระบุสิ่งที่เปลี่ยนจากแผน ถ้ามี)"],["ผู้ลงมือ/ภาพหรือไฟล์หลักฐาน"]],[["1"],["«ต่อสายสัญญาณเซนเซอร์ดินเข้า GPIO34 (อนาล็อก) และ reed switch ที่วัดฝนระหว่าง GPIO23 กับ GND ตรวจเลขขากับคู่มือบอร์ดของโรงเรียนก่อน ตั้ง HAZARD=\"landslide\" RAIN_ENABLED=True และ SIMULATE=True ก่อน แล้วค่อยเปลี่ยนเป็น False เมื่อต่อเซนเซอร์จริง»"],["«จ / ภาพถ่ายวงจร»"]],[["2"],["«สร้างเว็บแอป: วางโค้ด Code.gs และ Index.html ตั้ง Script Properties รัน setup() แล้วรัน usePresetLandslide แก้ข้อความในชีต Actions แล้ว Deploy เป็น Web App»"],["«ก / ภาพหน้าเว็บ + ข้อความทดสอบ»"]],[["3"],["«ใส่ Wi-Fi/URL/รหัสลับในไฟล์ config.py แล้วอัปโหลดไฟล์ขึ้นบอร์ด ตั้งค่า SOIL_RAW_DRY/WET และ MM_PER_TIP ที่สอบเทียบแล้ว ปล่อยช่องความเอียงว่าง (ยังไม่มีโค้ดบอร์ด) แล้วรันโหมดจริง»"],["«ค / ภาพหน้าจอ (ซ่อนรหัสก่อนแนบ)»"]],[["4"],["«ต่อบอร์ดไฟ: LED เขียว GPIO5 เหลือง GPIO19 แดง GPIO23 ผ่านตัวต้านทาน 220 Ω และตั้ง SOUND_ON=False ก่อน เปิดเสียงเมื่อผู้ใหญ่ตกลงความหมายของเสียงแล้ว»"],["«ข / วิดีโอไฟ 3 ดวง»"]]]],["p","สรุป: ตอนนี้ต้นแบบทำงานได้หรือแสดงหลักการใดแล้ว และยังทำไม่ได้ส่วนใด"],["t",[[["«(สมมติ — ตัวอย่างวิธีเขียน) ทำงานได้/แสดงหลักการ: ค่าดินและฝนจำลองขึ้น-ลง → ตัดสินระดับ 0–3 → จอที่โหนดแสดงระดับ → ส่งขึ้นเว็บและมือถือ → ไฟที่ศาลาเปลี่ยนสีตาม และค่าดินในถาดจำลองเพิ่มตามน้ำที่รด»","«ยังทำไม่ได้: ทำนายว่าเขาจะถล่มเมื่อใด • วัดบนเขาจริงตอนฝนหนัก • ใช้เกณฑ์จริงของหน่วยงาน • วัดความเอียงของเสา (ยังไม่มีโค้ด) • ส่วนที่ยังไม่ได้ทดสอบกับอุปกรณ์จริงให้เขียนว่า \"ยังไม่ทดสอบ\"»"]]]]]},{"h":"5. เมื่อพบอุปสรรค เราคิดและแก้อย่างไร","b":[["t",[[["อุปสรรค/สาเหตุที่คาด"],["ทางเลือกที่เสนอ"],["วิธีที่ลองจริง/ผลที่พบ"]],[["1.« ค่าความชื้นดินในถาดไม่เปลี่ยนตามน้ำที่รด เพราะใช้ค่าตั้งต้น 3000 และ 1300 ที่ไม่ตรงกับเซนเซอร์ตัวจริง»"],["«สอบเทียบใหม่: วัดค่าดิบในอากาศเป็น SOIL_RAW_DRY และจุ่มน้ำถึงเส้นที่กำหนดเป็น SOIL_RAW_WET จดวิธีและวันที่»"],["«(สมมติ) หลังสอบเทียบ ค่าในถาดเพิ่มตามน้ำที่รดชัดขึ้น แต่ยังเป็นค่าของถาดนี้ ห้ามเทียบกับดินบนเขาจริง»"]],[["2.« หลังบอร์ดรีเซ็ต จอขึ้น RAIN WARMUP และไม่ส่งค่าฝน ทำให้ระดับมาจากดินอย่างเดียวตลอด 24 ชม.»"],["«ให้ผู้ใหญ่หรืออาสากรอกค่าฝนจากถังวัดฝนในพื้นที่อาสาช่วงนั้น และติดป้ายว่า \"ช่วง 24 ชม. แรกหลังรีเซ็ต\"»"],["«(สมมติ) หลังกรอกค่ามือ ระดับตรงกับค่าถังวัดฝนที่จดไว้ แต่ยังต้องมีคนอ่านถังวัดฝนตรงเวลา»"]]]],["p","ตัวอย่าง 1 เหตุการณ์ที่กลุ่มเปลี่ยนแผนเอง (ระบุก่อน–หลัง และเหตุผล)"],["t",[[["«ก่อน: วางแผนใช้ค่าตั้งต้น SOIL_RAW_DRY=3000 SOIL_RAW_WET=1300 MM_PER_TIP=0.2 และเกณฑ์ดิน 60/75/90 % ฝน 60/90/120 mm»","«หลัง: ใช้ค่าจากการสอบเทียบจริง เขียนกำกับว่า \"ค่าจากถาดจำลอง\" และบอกสถานะ \"เกณฑ์สมมติ ยังไม่ใช่เกณฑ์ทางการ\" บนหน้าเว็บและป้ายที่ศาลา»","«เหตุผล: (สมมติ) ค่าตั้งต้นต่างจากเซนเซอร์ที่ใช้จริง และเกณฑ์ไม่ได้มาจากหน่วยงาน จึงต้องบอกผู้ใช้ตรง ๆ ไม่ให้เข้าใจว่าเป็นการทำนาย»"]]]]]},{"h":"6. บันทึกการใช้ AI อย่างรับผิดชอบ","b":[["t",[[["ใช้ AI ช่วยงานใด/ข้อความคำสั่งย่อ"],["AI เสนออะไร"],["เราตรวจและปรับเองอย่างไร"]],[["1.« ให้ AI อธิบายโค้ดอ่านค่าดิน (ค่ากลางของ 9 ครั้ง) และโค้ดนับฝน 24 ชม. แบบแบ่งถังรายชั่วโมงที่ไม่ส่งค่าจนครบ 24 ชม.»"],["«อธิบายว่ามีถังรายชั่วโมง 24 ถังที่เลื่อนไปทุกชั่วโมง ถ้าบอร์ดรีเซ็ตประวัติหาย ค่าจึงต่ำกว่าจริง โค้ดจึงรอครบ 24 ชม. ก่อนส่ง และใช้ค่ากลางลดค่าสะดุ้งของเซนเซอร์ดิน»"],["«เปิดบอร์ดโหมดจริงดูว่าจอขึ้น RAIN WARMUP และทดลองโหมดจำลองเทียบกับที่ AI อธิบาย»"]],[["2.« ให้ AI ช่วยเรียบเรียงข้อความแจ้ง 4 ระดับให้สั้น»"],["«ข้อความมีคำทำนาย เช่น \"เขาจะถล่มภายใน 2 ชั่วโมง\" และคำสั่งเสี่ยง เช่น ให้ขึ้นไปดูรอยแตกบนเขา»"],["«ตัดคำทำนายและคำสั่งเสี่ยง ใช้แนวทางจากชุดต้นแบบ (สังเกตจากพื้นราบ เตรียมออกจากบ้านใกล้เชิงเขา อพยพตามผู้ใหญ่บ้าน/เจ้าหน้าที่ โทร 1784) และบอกว่าเป็นต้นแบบของโรงเรียน»"]]]],["p","ข้อมูลใดจาก AI ที่กลุ่มไม่ใช้ เพราะไม่เหมาะสม ไม่ปลอดภัย หรือไม่มีหลักฐานยืนยัน"],["t",[[["«ไม่ใช้: ข้อความที่บอกเวลาหรือความน่าจะเป็นที่เขาจะถล่ม เพราะต้นแบบนี้ทำนายไม่ได้»","«ไม่ใช้: เกณฑ์ดิน/ฝนที่ AI เสนอเอง เพราะไม่มีที่มาและยังไม่ได้เทียบกับกรมทรัพยากรธรณี/ปภ./อบต.»","«ไม่ใช้: คำแนะนำให้ขึ้นไปดูรอยแตกหรือปักเซนเซอร์บนเขาตอนฝนตก เพราะอันตราย ใช้ถาดจำลองและให้ผู้ใหญ่/อบต. ดูแทน»"]]]]]},{"h":"7. ตรวจสอบความพร้อมของต้นแบบจำลอง","b":[["t",[[["เกณฑ์"],["หลักฐานที่เห็นจริง/สิ่งที่ต้องแก้"]],[["ตรงปัญหาและตอบผู้ใช้ที่กำหนด"],["«ตรง: โหนด + ไฟ + ข้อความ + สมุดสังเกต ตอบโจทย์ \"ไม่รู้ว่าฝนสะสมและดินน่ากังวลแล้วหรือยัง\"»","«หลักฐาน: ใบกิจกรรมที่ 2 ข้อ 3»"]],[["แสดงการทำงานได้/อธิบายขั้นตอนชัด"],["«สาธิตด้วยโหมดจำลอง: ค่าดินและฝนขึ้นถึงระดับ 1 → 2 → 3 แล้วจอ หน้าเว็บ ข้อความ และไฟเปลี่ยนตาม»","«หลักฐาน: วิดีโอสาธิต»"]],[["เลือกใช้ทรัพยากรเหมาะสมและปลอดภัย"],["«ใช้ไฟ 5 V ไม่ขึ้นเขา ผู้ใหญ่/อบต. ติดตั้งตอนอากาศปกติ เก็บรหัสลับนอกโค้ด»","«หลักฐาน: ตารางความเสี่ยงข้อ 3»"]],[["ต่างจากวิธีทั่วไปอย่างมีเหตุผล"],["«ต่างจากรายงานของกรมทรัพยากรธรณีที่ใช้เครื่องมือเฉพาะและมีเกณฑ์ของตัวเอง: ของเราเป็นตัวช่วยสังเกตราคาประหยัดสำหรับหมู่บ้าน พร้อมข้อความสิ่งที่ควรทำ แต่ไม่ได้แทนหน่วยงานและทำนายไม่ได้»"]]]],["p","ชื่อของต้นแบบ «เสาเฝ้าไหล่เขา (ต้นแบบช่วยสังเกต ไม่ใช่เครื่องทำนาย)»  ·"],["p","วิธีสาธิตการทำงานอย่างปลอดภัย"],["t",[[["«สาธิตด้วยโหมดจำลอง (SIMULATE) ใช้ไฟ 5 V จากพาวเวอร์แบงก์ ครูอยู่ดูแล ให้ผู้ชมดูระดับขึ้นถึง 1 2 3 และไฟกับข้อความเปลี่ยนตาม แล้วรดน้ำถาดลาดเขาจำลองให้ดูค่าดินเพิ่ม»","«ถ้าไม่มีอุปกรณ์หรือเน็ต: ใช้ปุ่ม \"โหมดจำลอง\" ในหน้าเว็บ ไม่ต้องใช้เซนเซอร์จริง»"]]]],["p","หลักฐานภาพถ่าย/ไฟล์/ลิงก์ต้นแบบ"],["t",[[["«หลักฐานที่ต้องแนบ: ภาพถ่ายโหนดและถาดจำลอง วิดีโอสั้นสาธิต ภาพหน้าจอเว็บแอป ตารางสอบเทียบเซนเซอร์ดินและที่วัดฝน สมุดสังเกตตัวอย่าง (ลิงก์ Google Drive ของกลุ่ม ห้ามมีรหัสลับในภาพ)»"]]]]]},{"h":"8. ต้นแบบเราแตกต่างจากวิธีที่มีอยู่จริงอย่างไร","b":[["t",[[["วิธีแก้ปัญหาที่พบหรือใช้อยู่ก่อน"],["สิ่งที่เราเปลี่ยน/เพิ่มในต้นแบบ"],["ประโยชน์ต่อผู้ใช้"],["หลักฐานที่ตรวจสอบได้"]],[["«รายงานของกรมทรัพยากรธรณี (เช่น 3 ก.ย. 2557)»","«ชาวบ้านดูฝนและเขาเอง»"],["«โหนดดินและฝน»","«จอที่โหนด ไฟ 3 ดวง»","«สมุดสังเกต ช่องกรอกฝน จุดรวมพล»"],["«ผู้ใหญ่บ้านรู้ฝนและดิน»","«คนใกล้ศาลาเห็นไฟ»","«ชาวบ้านรู้ว่าต้องทำอะไร»"],["«ตารางสอบเทียบ + บันทึกถาด»","«วิดีโอสาธิต»","«ข่าวในใบกิจกรรมที่ 1»"]]]],["p","ทำไมสิ่งที่เพิ่มจึงอาจลดความเสี่ยงของกลุ่มเป้าหมายได้ (ไม่อ้างประสิทธิภาพก่อนมีผลทดลอง)"],["t",[[["«สมมติฐาน: ถ้าผู้ใหญ่บ้านและชาวบ้านรู้ว่าฝนสะสมและดินน่ากังวลและรู้ว่าต้องทำอะไรก่อน อาจเตรียมตัวและไปจุดรวมพลได้เร็วขึ้น (ยังไม่อ้างว่าได้ผล)»","«เหตุผลสนับสนุน: ข่าวปี 2554 น้ำป่าและโคลนเข้าหมู่บ้านราว 02.00 น. และข่าวปี 2567 ไฟกับสัญญาณหายพร้อมกัน ทำให้รับข่าวยาก»"]]]],["p","ถ้าผู้ใช้อีกกลุ่มหนึ่งต้องใช้ต้นแบบนี้ ต้องปรับอะไร (หรือใช้วัสดุ/เทคโนโลยีในแบบที่ต่างจากปกติอย่างไร)"],["t",[[["«ถ้าผู้ใช้เป็นโรงเรียนหรือวัดที่เป็นที่พักพิง: ให้ผู้เชี่ยวชาญ/อบต. ตรวจก่อนว่าที่ตั้งปลอดภัย»","«ถ้าผู้ใช้เป็นเกษตรกรสวนบนที่ลาด: ใช้ฝนวางแผนขนผลผลิต ไม่เข้าสวนตอนฝนหนัก»"]]]]]},{"h":"9. สาธิตสั้น ๆ ให้ดู","b":[["p","ฉันรับผิดชอบส่วนใด / ส่วนนี้ทำงานอย่างไร / จะสาธิตให้เห็นอะไร"],["t",[[["«ฉันรับผิดชอบ: โหนดดินและฝน และถาดลาดเขาจำลอง (ฮาร์ดแวร์)»","«ทำงานอย่างไร: ดินอ่านค่ากลาง 9 ครั้ง ที่วัดฝนนับการกระดก → % และ mm 24 ชม. → ระดับ 0–3 → จอและเว็บ → ไฟที่ศาลา»","«จะสาธิต: โหมดจำลองให้ดินขึ้นจาก 30 ถึง 95 % ฝนจาก 10 ถึง 130 mm ดูข้อความและไฟเปลี่ยน ปิด Wi-Fi ให้ดูจอที่โหนด และรดน้ำถาดจำลอง»"]]]],["p","ข้อบกพร่องหรืออุปสรรคที่ฉันพบ 1 เรื่อง / ฉันลองแก้อย่างไร / ผลที่เกิด"],["t",[[["«(สมมติ) พบ: ค่าดินในถาดไม่เปลี่ยนตามน้ำที่รดเพราะใช้ค่าตั้งต้นที่ไม่ตรงกับเซนเซอร์»","«ลอง: สอบเทียบ SOIL_RAW_DRY/WET ใหม่ด้วยค่าในอากาศและจุ่มน้ำ»","«ผลที่เกิด: (นักเรียนบันทึกผลจริงของกลุ่ม)»"]]]]]}]},"a6":{"pre":[["p","ภารกิจ : กำหนดเกณฑ์ความสำเร็จก่อนทดลอง ใช้สถานการณ์จำลองที่ปลอดภัย เก็บข้อเสนอแนะ ปรับต้นแบบ และทดสอบซ้ำ แล้วใช้ผลทั้งหมดสะท้อนผลงานและวิธีทำงานของตน พร้อมวางแผนพัฒนารอบถัดไป"]],"secs":[{"h":"1. วางแผนการทดลองสถานการณ์จำลอง","b":[["p","สถานการณ์จำลองที่ใช้ทดสอบ (เช่น น้ำป่าตอนกลางคืนโดยไม่มีอินเทอร์เน็ต) และผู้ทดลอง"],["t",[[["«สถานการณ์จำลอง: ใช้โหมดจำลอง (SIMULATE) ให้ค่าดินและฝนขึ้น-ลงผ่านระดับ 0–3 ช่วงหนึ่งปิด Wi-Fi แทนการไม่มีเน็ต และอีกช่วงรดน้ำถาดลาดเขาจำลองให้ดูค่าดินเพิ่ม แล้วดูจอ หน้าเว็บ ข้อความ และไฟ»","«ผู้ทดลอง: เพื่อนกลุ่มอื่น 2 คนรับบทผู้ใหญ่บ้าน (ไม่รู้ล่วงหน้าว่าค่าจะขึ้นถึงระดับใดเมื่อไร) ครูเป็นผู้สังเกต»","«ความปลอดภัย: ใช้ไฟ 5 V บนโต๊ะ วางบอร์ดห่างถาดน้ำ ทดสอบในร่ม ไม่มีใครขึ้นเขา รอบจำลองวัดทุก 5 วินาที (ค่าใช้จริงพักระหว่างรอบ 5 นาที) ไม่ต้องแก้โค้ด»"]]]],["t",[[["สิ่งที่จะวัด/สังเกต"],["เกณฑ์สำเร็จที่กำหนดไว้ก่อนทดสอบ"],["จะเก็บผลอย่างไร"]],[["1.« ระดับ 0–3 ที่จอบอร์ดและหน้าเว็บแสดง ตรงกับระดับที่คำนวณจากตารางเกณฑ์ดินและฝน»"],["«ตรงอย่างน้อย 5 ใน 6 จุดวัด (กลุ่มกำหนดเอง)»"],["«จดค่าดิน % ค่าฝน mm ที่เว็บแสดง ระดับที่คำนวณเอง และระดับ 0–3 ที่เว็บแสดง ลงตาราง 6 แถว»"]],[["2.« ผู้ใหญ่บ้านรู้ว่าต้องทำอะไรเมื่ออ่านข้อความระดับ 2»"],["«ผู้ทดลอง 2 ใน 2 คน บอก 2 ข้อแรกที่ต้องทำได้ถูกภายใน 30 วินาที»"],["«ถามผู้ทดลองแล้วจดผลลงตาราง»"]]]]]},{"h":"2. ผลทดลองรอบที่ 1 ก่อนปรับปรุง","b":[["t",[[["เกณฑ์ทดสอบ"],["ผลที่เกิดจริง (ไม่แต่งข้อมูล)"],["ปัญหาหรือข้อจำกัด"]],[["1.« ระดับตรงกับที่คำนวณ อย่างน้อย 5 ใน 6 จุด»"],["«(สมมติ) ตรง 4 ใน 6 จุด»"],["«2 จุดหลังค่าลดลง ระดับที่เว็บยังไม่ลดตามทันที เพราะระบบรอเห็นค่าต่ำลง 2 ครั้งติดกัน ทำให้ไม่ตรงกับที่นักเรียนคำนวณจากค่าล่าสุด»"]],[["2.« ผู้ทดลองบอก 2 ข้อแรกที่ต้องทำได้ถูกใน 30 วินาที»"],["«(สมมติ) 1 ใน 2 คน อีกคนไม่แน่ใจว่าต้องไปศูนย์พักพิงที่ไหน»"],["«ข้อความระดับ 2 บอกให้ย้ายไปบ้านญาติหรือศูนย์พักพิง แต่ไม่บอกว่าที่ไหนและไปทางใด»"]]]],["p","ข้อเสนอแนะจากเพื่อน/ครู/ผู้ทดลองใช้ 1–2 ข้อ (เขียนว่าใครเสนอเรื่องใด ไม่ต้องระบุข้อมูลส่วนตัว)"],["t",[[["«ผู้ทดลองคนที่ 1: ข้อความบอกให้ไปศูนย์พักพิง แต่ไม่รู้ว่าอยู่ที่ไหน อยากมีแผนที่จุดรวมพลที่ศาลา»","«ครู: ในหน้าเว็บควรบอกว่าเกณฑ์เป็นค่าสมมติ ผู้ใหญ่บ้าน/อบต. เป็นผู้ตัดสินใจอพยพ และบอกเมื่อค่าฝนยังไม่ครบ 24 ชม. หลังรีเซ็ต»","«(ตัวอย่างสมมติ — นักเรียนเขียนข้อเสนอแนะที่ได้จริง)»"]]]]]},{"h":"3. ปรับปรุงตามหลักฐานและทดสอบซ้ำ","b":[["p","ทดสอบซ้ำในสถานการณ์จำลองที่เทียบเคียงกับรอบแรก เช่น ผู้ทดลอง เหตุการณ์ ระยะทาง แหล่งข้อมูล และอุปกรณ์"],["t",[[["เกณฑ์ความสำเร็จเดิม"],["ผลรอบที่ 1"],["สิ่งที่แก้จริง + เหตุผล"],["ผลรอบที่ 2"],["ดีขึ้น/ยังไม่ดี เพราะอะไร"]],[["1.« ระดับตรงกับที่คำนวณ อย่างน้อย 5 ใน 6 จุด»"],["«(สมมติ) ตรง 4 ใน 6 จุด»"],["«เพิ่มคอลัมน์ \"ค่า 2 รอบล่าสุด\" ในตารางทดสอบ และอ่านระดับหลังค่าลดครบ 2 รอบ»","«เหตุผล: ระบบลดระดับเมื่อเห็นค่าต่ำลง 2 ครั้งติดกัน ไม่ใช่ทันที»"],["«(สมมติ) ตรง 6 ใน 6 จุด»"],["«ดีขึ้น แต่เพราะเปลี่ยนวิธีตรวจ ไม่ใช่แก้ตัวต้นแบบ และมีเพียง 6 จุดในโหมดจำลอง ยังไม่ได้ทดสอบกับฝนจริงหรือเขาจริง»"]],[["2.« ผู้ทดลองบอก 2 ข้อแรกที่ต้องทำได้ถูกใน 30 วินาที»"],["«(สมมติ) 1 ใน 2 คน»"],["«เพิ่มประโยค \"จุดรวมพล: ดูแผนที่ที่ศาลาหรือถามผู้ใหญ่บ้าน\" ท้ายข้อความระดับ 2 ในชีต Actions»","«เหตุผล: ตรงกับสิ่งที่ผู้ทดลองสับสน และไม่ต้องเดา»"],["«(สมมติ) 2 ใน 2 คน»"],["«ดีขึ้น แต่ผู้ทดลองเป็นคนละคน จึงเทียบตรง ๆ ไม่ได้»"]]]],["p","มีเงื่อนไขใดไม่เหมือนเดิมระหว่างสองรอบหรือไม่? ถ้ามี ผลการเปรียบเทียบอาจคลาดเคลื่อนอย่างไร"],["t",[[["«ไม่เหมือนเดิม: ผู้ทดลองรอบ 2 เป็นคนละคน และค่าจำลองแต่ละรอบไม่ผ่านจุดเดียวกันทุกครั้ง»","«ผลกระทบ: ข้อสรุปว่า \"ดีขึ้น\" อาจมาจากวิธีตรวจหรือตัวผู้ทดลอง ไม่ใช่การแก้ไข ต้องทดสอบซ้ำกับผู้ทดลองเดิมและจำนวนจุดที่มากขึ้น»"]]]]]},{"h":"4. สะท้อนคิดผลงานและกระบวนการของกลุ่ม","b":[["p","ใช้ผลทดสอบและข้อเสนอแนะเป็นหลักฐาน ไม่ใช้ความรู้สึกอย่างเดียว"],["t",[[["สิ่งที่สะท้อน"],["จุดแข็ง (พร้อมหลักฐาน)"],["จุดอ่อน (พร้อมหลักฐาน)"]],[["ผลงาน/ต้นแบบ"],["«จอที่โหนดแสดงระดับเองได้แม้ไม่มีเน็ต (หลักฐาน: ทดสอบปิด Wi-Fi)»","«ไฟสลับสีเมื่อไม่มีข้อมูล ไม่ติดเขียว (หลักฐาน: ตัด Wi-Fi ของบอร์ดไฟ)»","«ค่าดินในถาดเพิ่มตามน้ำที่รด (หลักฐาน: ตารางสอบเทียบและถาดจำลอง)»"],["«ยังไม่ได้ทดสอบกับฝนจริงและเขาจริง และยังไม่มีเกณฑ์จริงจากหน่วยงาน»","«เซนเซอร์จุดเดียวทำนายดินถล่มไม่ได้ และฝนสะสมของบอร์ดหายเมื่อรีเซ็ต ต้องมีคนกรอกค่าถังวัดฝนช่วง 24 ชม. แรก»","«ไฟที่ศาลาถามเว็บ จึงต้องมีเน็ต ส่วนความเอียงของเสายังไม่มีโค้ด»"]],[["กระบวนการสร้างสรรค์ของกลุ่ม (ใบกิจกรรม 1–5)"],["«เริ่มจากข่าวจริงและรายงานหน่วยงาน (ใบ 1–2)»","«ผสานความคิดเพื่อนจนได้สมุดสังเกต โหนด ไฟ และตารางสิ่งที่ต้องทำ (ใบ 3)»","«ปรับโจทย์จาก \"เครื่องทำนาย\" เป็น \"ช่วยเตือนให้เตรียมตัว\" (ใบ 2)»"],["«ใบ 5 ทดสอบกับอุปกรณ์จริงน้อย เวลาไม่พอ»","«ยังไม่ได้ถามผู้ใหญ่บ้าน/อบต. เรื่องเกณฑ์และจุดรวมพล»","«ไม่ได้ถามชาวบ้านตัวจริงว่าเคยสังเกตอะไรก่อนฝนหนัก»"]]]],["p","ต้นแบบช่วยป้องกัน ลดความเสี่ยง หรือสนับสนุนการเตรียมพร้อมของกลุ่มเป้าหมายได้อย่างไร (จากผลทดลองเท่านั้น)"],["t",[[["«จากผลทดลอง (สมมติ): ต้นแบบทำให้ผู้ทดลองเห็นระดับฝนสะสมและดินและรู้ว่าต้องทำอะไรเร็วขึ้นในโหมดจำลอง แต่ยังสรุปไม่ได้ว่าช่วยให้ชาวบ้านปลอดภัยขึ้นจริงตอนฝนหนัก»","«ยืนยันได้จากผล: การแสดงระดับที่โหนดไม่ขึ้นกับเน็ต และค่าดินในถาดตอบสนองต่อน้ำที่รด»","«ยังยืนยันไม่ได้: ว่าค่าดินและฝนบอกความเสี่ยงของเขาจริงได้แค่ไหน และชาวบ้านทำตามข้อความจริงหรือไม่ ต้องขอเกณฑ์จริงจากหน่วยงานและทดสอบกับผู้ใช้จริงโดยมีผู้ใหญ่ดูแล ไม่ขึ้นเขา»"]]]],["p","สิ่งใด “ยังไม่ควรนำไปใช้จริง” และผู้ใช้ควรอ้างอิงข้อมูล/คำเตือนจากหน่วยงานใดในเหตุฉุกเฉิน"],["t",[[["«ยังไม่ควรใช้จริง: การให้ผู้ใหญ่บ้านสั่งอพยพตามค่าจากโหนดเพียงอย่างเดียว การใช้เกณฑ์สมมติ การเปิดเสียงเตือนที่ยังไม่ได้ตกลงความหมายกับผู้ใหญ่บ้านหรือ อบต. และการอ้างว่าทำนายดินถล่มได้»","«ให้ติดตามประกาศจาก ปภ. (สายด่วน 1784) กรมทรัพยากรธรณี และ อบต. เมื่อฝนหนัก ถ้าต้องอพยพให้ห่างจากเชิงเขาและร่องน้ำ ไม่กลับเข้าบ้านจนกว่าเจ้าหน้าที่แจ้ง»"]]]],["p","ตั้งคำถามกับกระบวนการสร้างสรรค์ของเรา: ขั้นตอนใดที่เราเลือกทางง่ายเกินไปหรือน่าจะทำต่างออกไป เพราะอะไร"],["t",[[["«ที่เลือกทางง่าย: ทดสอบกับถาดจำลองและโหมดจำลองแทนเขาจริง และไม่ได้ไปถามผู้ใหญ่บ้าน/อบต. เรื่องเกณฑ์จริงและแผนที่พื้นที่เสี่ยงของหมู่บ้าน»","«ควรทำต่าง: ขอให้ครูพาไปคุยกับผู้ใหญ่บ้าน/อบต. ตอนอากาศปกติ ขอเกณฑ์และจุดรวมพลที่หน่วยงานกำหนด และเทียบค่าฝนจากถังวัดฝนกับข่าวเหตุย้อนหลังก่อนปรับเกณฑ์»","«เพราะเกณฑ์และข้อความต้องมาจากหน่วยงานและข้อมูลจริง ไม่ใช่จากถาดจำลอง»"]]]]]}]}},"team":["กลุ่มที่ «5»  ·  ชื่อกลุ่ม «ทีมเฝ้าเขา»  ·  ภัยที่เลือก «ดินถล่ม»  ·","สมาชิก 1) «นักเรียน ก»  ·  2) «นักเรียน ข»  ·  3) «นักเรียน ค»  ·","4) «นักเรียน ง»  ·  5) «นักเรียน จ»  ·  วันที่ ........ / ........ / ........"]}};
</script>
<script>
(function(){
'use strict';

/* ---------- helpers ---------- */
var PREFIX = 'krubam-ai-utt:';
var LS = {
  get:function(k){ try{ return window.localStorage.getItem(PREFIX+k); }catch(e){ return null; } },
  set:function(k,v){ try{ window.localStorage.setItem(PREFIX+k,v); }catch(e){} }
};
function $(s,r){ return (r||document).querySelector(s); }
function $$(s,r){ return Array.prototype.slice.call((r||document).querySelectorAll(s)); }
function esc(s){ return String(s).replace(/&/g,'&amp;').replace(/</g,'&lt;').replace(/>/g,'&gt;').replace(/"/g,'&quot;'); }
function refs(s){ return esc(s).replace(/\[(\d+)\]/g,'<span class="src">[$1]</span>'); }
function reduced(){ try{ return window.matchMedia('(prefers-reduced-motion: reduce)').matches; }catch(e){ return false; } }

/* ---------- theme ---------- */
var root = document.documentElement;
function isDark(){
  var a = root.getAttribute('data-theme');
  if(a==='dark') return true;
  if(a==='light') return false;
  try{ return window.matchMedia('(prefers-color-scheme: dark)').matches; }catch(e){ return false; }
}
function paintThemeIcon(){
  var u = $('#themeIc use');
  if(u) u.setAttribute('href', isDark() ? '#i-sun' : '#i-moon');
}
(function(){
  var saved = LS.get('theme');
  if(saved==='dark' || saved==='light') root.setAttribute('data-theme', saved);
  paintThemeIcon();
  var b = $('#themeBtn');
  if(b) b.addEventListener('click', function(){
    var next = isDark() ? 'light' : 'dark';
    root.setAttribute('data-theme', next);
    LS.set('theme', next);
    paintThemeIcon();
  });
})();

/* ---------- routing ---------- */
var VIEWS = ['home','library','a1','a2','a3','a4','a5','a6'];
var TABS = ['learn','ex','hz','rub'];
var cur = { view:'home', tab:'learn' };

function parse(tok){
  var m = /^(home|library|a[1-6])(?:-(ex|hz|rub))?$/.exec(tok||'');
  if(!m) return null;
  var tab = m[2] || 'learn';
  if(m[1]==='home' || m[1]==='library') tab = 'learn';
  return { view:m[1], tab:tab };
}
function navOffset(){
  var n = $('.nav');
  return (n ? n.offsetHeight : 70) + 10;
}
function scrollToEl(el){
  if(!el) return;
  var y = el.getBoundingClientRect().top + window.pageYOffset - navOffset();
  window.scrollTo({ top: Math.max(0,y), behavior: reduced() ? 'auto' : 'smooth' });
}
function showTab(view, tab){
  TABS.forEach(function(t){
    var p = $('#p-'+view+'-'+t), b = $('#t-'+view+'-'+t);
    if(p) p.hidden = (t!==tab);
    if(b){ b.setAttribute('aria-selected', t===tab ? 'true':'false'); b.setAttribute('tabindex', t===tab ? '0':'-1'); }
  });
}
function route(tok, opt){
  opt = opt || {};
  var r = parse(tok);
  if(!r) r = { view:'home', tab:'learn' };
  var viewChanged = (r.view !== cur.view);
  VIEWS.forEach(function(v){
    var el = $('#v-'+v);
    if(el) el.hidden = (v!==r.view);
  });
  if(/^a[1-6]$/.test(r.view)) showTab(r.view, r.tab);
  $$('.chip').forEach(function(c){
    if(c.getAttribute('data-go')===r.view) c.setAttribute('aria-current','page'); else c.removeAttribute('aria-current');
  });
  cur = r;
  var token = r.view + (r.tab!=='learn' ? '-'+r.tab : '');
  try{ if(!opt.silent) window.history.replaceState(null,'','#'+token); }catch(e){}
  if(!opt.silent){
    if(viewChanged || r.view==='home' || r.view==='library'){
      window.scrollTo({ top:0, behavior:'auto' });
    } else {
      var tabs = $('#v-'+r.view+' .tabs');
      if(tabs){
        var top = tabs.getBoundingClientRect().top;
        if(top < navOffset() - 4 || top > window.innerHeight*0.6) scrollToEl(tabs);
      }
    }
  }
  if(opt.after) setTimeout(function(){ scrollToEl(document.getElementById(opt.after)); }, 40);
}

document.addEventListener('click', function(e){
  var go = e.target.closest('[data-go]');
  if(go){
    e.preventDefault();
    route(go.getAttribute('data-go'));
    return;
  }
  var sc = e.target.closest('[data-scroll]');
  if(sc){
    e.preventDefault();
    scrollToEl(document.getElementById(sc.getAttribute('data-scroll')));
    return;
  }
  var rv = e.target.closest('[data-reveal]');
  if(rv){
    var box = document.getElementById(rv.getAttribute('data-reveal'));
    if(box){
      box.hidden = !box.hidden;
      rv.setAttribute('aria-expanded', box.hidden ? 'false':'true');
    }
    return;
  }
});
document.addEventListener('keydown', function(e){
  var t = e.target.closest && e.target.closest('.tabs [role="tab"]');
  if(!t) return;
  var list = $$('[role="tab"]', t.parentNode);
  var i = list.indexOf(t), n = -1;
  if(e.key==='ArrowRight') n = (i+1)%list.length;
  else if(e.key==='ArrowLeft') n = (i-1+list.length)%list.length;
  else if(e.key==='Home') n = 0;
  else if(e.key==='End') n = list.length-1;
  if(n>=0){ e.preventDefault(); list[n].focus(); list[n].click(); }
});
window.addEventListener('hashchange', function(){
  var r = parse((location.hash||'').replace('#',''));
  if(r) route(location.hash.replace('#',''), {silent:false});
});

/* ---------- clipboard ---------- */
function copyText(txt, btn){
  function done(){
    if(!btn) return;
    var old = btn.getAttribute('data-label') || btn.innerHTML;
    btn.setAttribute('data-label', old);
    btn.textContent = 'คัดลอกแล้ว';
    setTimeout(function(){ btn.innerHTML = old; }, 1500);
  }
  function fallback(){
    var ta = document.createElement('textarea');
    ta.value = txt; ta.setAttribute('readonly',''); ta.style.position='fixed'; ta.style.opacity='0';
    document.body.appendChild(ta); ta.select();
    try{ document.execCommand('copy'); }catch(e){}
    document.body.removeChild(ta); done();
  }
  try{
    if(navigator.clipboard && navigator.clipboard.writeText){
      navigator.clipboard.writeText(txt).then(done, fallback);
    } else fallback();
  }catch(e){ fallback(); }
}
document.addEventListener('click', function(e){
  var c = e.target.closest('[data-copy]');
  if(c){
    var el = document.getElementById(c.getAttribute('data-copy'));
    if(el) copyText(el.textContent.replace(/\s+\n/g,'\n').trim(), c);
    return;
  }
  var co = e.target.closest('[data-copy-out]');
  if(co){
    var card = co.closest('[data-builder]');
    var out = card && $('[data-out]', card);
    if(out && out.getAttribute('data-has')==='1') copyText(out.textContent, co);
    return;
  }
});

/* ---------- quizzes ---------- */
document.addEventListener('click', function(e){
  var reset = e.target.closest('[data-quiz-reset]');
  if(reset){
    var q = reset.closest('.quiz');
    $$('.opt', q).forEach(function(o){ o.disabled=false; o.classList.remove('ok','no'); o.removeAttribute('aria-pressed'); });
    var fb0 = $('.fb', q); if(fb0) fb0.hidden = true;
    var rb = $('[data-quiz-reset]', q); if(rb) rb.remove();
    return;
  }
  var opt = e.target.closest('.quiz .opt');
  if(!opt || opt.disabled) return;
  var quiz = opt.closest('.quiz');
  var right = quiz.getAttribute('data-quiz');
  var chosen = opt.getAttribute('data-k');
  var fb = $('.fb', quiz);
  $$('.opt', quiz).forEach(function(o){
    o.disabled = true;
    if(o.getAttribute('data-k')===right) o.classList.add('ok');
  });
  opt.setAttribute('aria-pressed','true');
  var hd = $('.fb-h', quiz);
  if(chosen===right){
    if(hd) hd.textContent = 'ถูกต้อง';
  } else {
    opt.classList.add('no');
    var rk = $('.opt[data-k="'+right+'"] .k', quiz);
    if(hd) hd.textContent = 'ยังไม่ใช่ ข้อที่เหมาะสมคือข้อ ' + (rk ? rk.textContent : '');
  }
  if(fb){
    fb.hidden = false;
    fb.setAttribute('role','status');
    if(!$('[data-quiz-reset]', fb)){
      var p = document.createElement('p');
      p.style.margin = '.6em 0 0';
      p.innerHTML = '<button type="button" class="btn sm" data-quiz-reset>ลองอีกครั้ง</button>';
      fb.appendChild(p);
      p.firstChild.setAttribute('data-quiz-reset','');
    }
  }
});

/* ---------- builders ---------- */
function buildOut(card){
  var tpl = card.getAttribute('data-tpl') || '';
  var vals = {};
  var any = false;
  $$('input[data-part]', card).forEach(function(i){
    var v = i.value.trim();
    vals[i.getAttribute('data-part')] = v;
    if(v) any = true;
  });
  var out = $('[data-out]', card);
  if(!out) return;
  if(!any){
    out.textContent = 'พิมพ์ในช่องด้านบน แล้วประโยคจะประกอบให้ที่นี่';
    out.setAttribute('data-has','0');
    out.style.opacity = '.65';
    return;
  }
  out.textContent = tpl.replace(/\{(\d+)\}/g, function(_,n){ return vals[n] ? vals[n] : '…'; });
  out.setAttribute('data-has','1');
  out.style.opacity = '1';
}
$$('[data-builder]').forEach(function(card){
  buildOut(card);
  card.addEventListener('input', function(){ buildOut(card); });
  var f = $('[data-fill]', card), c = $('[data-clear]', card);
  if(f) f.addEventListener('click', function(){
    var parts = (card.getAttribute('data-sample')||'').split('|');
    $$('input[data-part]', card).forEach(function(i){ i.value = parts[+i.getAttribute('data-part')] || ''; });
    buildOut(card);
  });
  if(c) c.addEventListener('click', function(){
    $$('input[data-part]', card).forEach(function(i){ i.value=''; });
    buildOut(card);
  });
});

/* ---------- trial calculator (ใบที่ 6) ---------- */
function fmt1(n){ return (Math.round(n*10)/10).toFixed(1); }
function nums(list){
  return list.map(function(i){ return i.value.trim()===''? NaN : parseFloat(i.value); }).filter(function(v){ return isFinite(v) && v>=0; });
}
function avg(a){ return a.reduce(function(s,v){ return s+v; },0)/a.length; }
function trialUpdate(card){
  var r1 = nums($$('input[data-r1]', card)), r2 = nums($$('input[data-r2]', card));
  var limEl = $('input[data-lim]', card);
  var lim = limEl && limEl.value.trim()!=='' ? parseFloat(limEl.value) : NaN;
  var out = $('[data-trial-out]', card);
  if(!out) return;
  if(!r1.length || !r2.length || !isFinite(lim)){
    out.innerHTML = '<p class="sm mute" style="margin:.2em 0 0">ใส่ตัวเลขของรอบ 1 รอบ 2 และเกณฑ์ให้ครบอย่างน้อยรอบละ 1 ค่า</p>';
    return;
  }
  var a1 = avg(r1), a2 = avg(r2);
  var p1 = r1.filter(function(v){ return v<=lim; }).length;
  var p2 = r2.filter(function(v){ return v<=lim; }).length;
  var diff = a2 - a1;
  var msg = Math.abs(diff) < 0.05 ? 'ค่าเฉลี่ยสองรอบเท่ากัน'
          : (diff < 0 ? 'ค่าเฉลี่ยลดลง ' + fmt1(-diff) + ' วินาที (เวลาน้อยลง)' : 'ค่าเฉลี่ยเพิ่มขึ้น ' + fmt1(diff) + ' วินาที (เวลามากขึ้น)');
  var n = Math.min(r1.length, r2.length);
  var warn = (n < 5 ? 'มีเพียง ' + n + ' ครั้งต่อรอบ จึงสรุปเด็ดขาดไม่ได้ ควรทดสอบซ้ำให้มากขึ้น ' : '') + 'และถ้าผู้ทดลองหรือเงื่อนไขสองรอบไม่เหมือนกัน ให้เขียนว่าเทียบตรง ๆ ไม่ได้';
  out.innerHTML =
    '<div class="trial-grid">' +
    '<div class="card"><b class="sm mute">ค่าเฉลี่ยรอบ 1</b><div class="big-num">' + fmt1(a1) + '</div><span class="sm">วินาที</span></div>' +
    '<div class="card"><b class="sm mute">ค่าเฉลี่ยรอบ 2</b><div class="big-num">' + fmt1(a2) + '</div><span class="sm">วินาที</span></div>' +
    '<div class="card"><b class="sm mute">ผ่านเกณฑ์ ≤ ' + fmt1(lim) + ' วินาที</b><div class="big-num">' + p1 + '/' + r1.length + ' → ' + p2 + '/' + r2.length + '</div><span class="sm">รอบ 1 → รอบ 2</span></div>' +
    '</div>' +
    '<p style="margin:.7em 0 0"><b>' + msg + '</b></p>' +
    '<p class="sm mute" style="margin:.3em 0 0">' + esc(warn) + '</p>';
}
$$('[data-trial]').forEach(function(card){
  trialUpdate(card);
  card.addEventListener('input', function(){ trialUpdate(card); });
});

/* ---------- checklists + progress ---------- */
function loadChecks(key){
  var raw = LS.get('checks:'+key);
  if(!raw) return [];
  try{ var a = JSON.parse(raw); return Array.isArray(a) ? a : []; }catch(e){ return []; }
}
function updateMeters(key, list){
  var boxes = $$('input[type="checkbox"]', list);
  var n = boxes.filter(function(b){ return b.checked; }).length;
  var bar = $('[data-meter="'+key+'"]');
  if(bar) bar.style.width = boxes.length ? (100*n/boxes.length)+'%' : '0%';
  var tx = $('[data-meter-text="'+key+'"]');
  if(tx) tx.textContent = 'ติ๊กแล้ว ' + n + ' จาก ' + boxes.length + ' ข้อ';
  var pr = $('[data-prog="'+key+'"]');
  if(pr) pr.textContent = 'เช็กลิสต์ ' + n + '/' + boxes.length;
}
$$('ul.checks[data-checks]').forEach(function(list){
  var key = list.getAttribute('data-checks');
  var boxes = $$('input[type="checkbox"]', list);
  var saved = loadChecks(key);
  boxes.forEach(function(b,i){ b.checked = !!saved[i]; });
  updateMeters(key, list);
  list.addEventListener('change', function(){
    LS.set('checks:'+key, JSON.stringify(boxes.map(function(b){ return b.checked; })));
    updateMeters(key, list);
  });
});
/* home progress: show 0/n for activities whose checklist the home page can find */
$$('[data-prog]').forEach(function(p){
  var key = p.getAttribute('data-prog');
  var list = $('ul.checks[data-checks="'+key+'"]');
  if(list) updateMeters(key, list);
});

/* ---------- hazard data ---------- */
var LV = ['ปกติ','เฝ้าระวัง','เตือนภัย','อันตราย'];
var HZ = {
  drought: {
    name:'ภัยแล้ง', prod:'ป้ายน้ำหมู่บ้าน', diff:'★★ ง่ายที่สุด',
    tag:'บอกระดับน้ำสระ/ถังประปาทุกวัน ให้ชุมชนวางแผนแบ่งน้ำก่อนน้ำหมด',
    events:[
      'ม.ค. 2558 (ข่าว 6 ม.ค.): หมู่ 3, 5 และ 10 ต.น้ำอ่าง อ.ตรอน รวม 485 ครอบครัว แหล่งน้ำแห้งขอดจนผลิตน้ำประปาไม่ได้ ประปาไม่ไหลมากกว่า 2 เดือน ชาวบ้านต้องซื้อน้ำทั้งน้ำใช้ น้ำดื่ม และน้ำหุงข้าว [1]',
      'มี.ค. 2559: ต.นาอิน และ ต.นายาง อ.พิชัย ประสบภัยแล้งหนัก ไร่มันสำปะหลังนับพันไร่แห้งตายไปแล้วมากกว่าครึ่ง ต.นายางเหลือสระกลางสำหรับผลิตประปาเพียง 4–5 แห่ง น้ำถัง 200 ลิตรราคา 40 บาทเมื่อส่งถึงบ้าน [2]'
    ],
    note:'เหตุการณ์ในข่าวทั้งสองชิ้นเก่าแล้ว ใช้เป็นตัวอย่างลักษณะปัญหา ชาวบ้านมัก “รู้ว่าแล้ง” ตอนน้ำหมดแล้วและต้องซื้อน้ำ',
    problem:'ครัวเรือนที่พึ่งประปาหมู่บ้านจากสระกลางไม่รู้ล่วงหน้าว่าน้ำใกล้หมดเมื่อไร จึงรู้ตัวตอนประปาไม่ไหลแล้วต้องซื้อน้ำ',
    hmw:'เราจะทำอย่างไรให้ทุกครัวเรือนรู้ระดับน้ำสระกลางทุกวัน และเริ่มประหยัด/แบ่งน้ำได้ก่อนถึงขั้นวิกฤต',
    how:'เซนเซอร์อัลตราโซนิกเหนือสระ/ถัง → บอร์ดวัดทุก 1 ชั่วโมง (ใช้ค่ากลางหลายครั้ง) → Apps Script คำนวณระดับ 0–3 (ยิ่งน้ำน้อยยิ่งอันตราย) → ข้อความ Telegram/LINE + หน้าเว็บ + ไฟ 3 สีที่ศาลาหมู่บ้าน อาสาสมัครกรอก “จำนวนวันที่ไม่มีฝน” รายวัน และอ่านไม้วัดระดับน้ำแทนเมื่อบอร์ดดับ',
    extra:'ต่อยอดคณิตศาสตร์: ใน Google Sheet คำนวณ “น้ำเหลืออีกประมาณกี่วัน” = (ระดับตอนนี้ − ระดับวิกฤต) ÷ อัตราน้ำลดเฉลี่ยต่อวันใน 7 วันล่าสุด (ส่วนนี้ยังไม่อยู่ในโค้ดชุดนี้ นักเรียนทำเองในชีตได้)',
    honest:null,
    levels:[
      ['1 ไม่ใช้บอร์ด','ไม้วัดระดับน้ำทาสีเขียว/เหลือง/แดง ตามเกณฑ์ที่ตกลงกับผู้ดูแลประปา + อาสาสมัครอ่านทุกเช้า กรอกในปุ่ม “รายงานด้วยมือ” ของเว็บแอป','ไม้บรรทัด/เสาไม้ สีทา โทรศัพท์'],
      ['2 โหนดบอร์ด','อัลตราโซนิกวัดระดับน้ำ ต่อวงจรเหมือนชุดน้ำท่วม (ตัวแบ่งแรงดัน 1 kΩ + 2 kΩ ที่ขา ECHO) ตั้ง HAZARD="drought", CHANNELS_ON=("reservoir_cm",)','บอร์ด IPST-WiFi, JSN-SR04T หรือ HC-SR04, พาวเวอร์แบงก์'],
      ['3 ต่อยอด','เพิ่มเซนเซอร์ความชื้นดินในแปลงตัวอย่าง + สูตรชีต “น้ำเหลืออีกกี่วัน” + ไฟ 3 สีหน้าศาลา (ตั้ง SOUND_ON=False ที่ node_siren.py ให้เป็นไฟอย่างเดียว)','เซนเซอร์ความชื้นดิน, LED ชุดไซเรน']
    ],
    preset:{
      fn:'usePresetDrought', board:'node_multi.py → HAZARD = "drought" (ช่อง reservoir_cm, soil_pct)',
      th:'ระดับน้ำสระ ≤150 / ≤100 / ≤50 cm = ระดับ 1/2/3 · ความชื้นดิน ≤40 / ≤30 / ≤20 % · วันไม่มีฝน ≥7 / ≥14 / ≥21 วัน (อาสากรอก) ยิ่งน้อยยิ่งอันตราย ยกเว้นวันไม่มีฝน',
      timing:'วัดทุก 1 ชม. · เงียบเกิน 25 ชม. = “ไม่มีข้อมูล” (STALE_MIN 1500) · ย้ำเตือนวันละครั้งเมื่อระดับ ≥2 (REPEAT_MIN 1440) ตั้งอัตโนมัติเมื่อรันชุดค่า',
      extra:null
    },
    msgs:[
      'สถานการณ์ปกติ ตรวจถัง/บ่อกักเก็บน้ำและท่อรั่วก่อนหน้าแล้ง',
      'ลดการใช้น้ำที่ไม่จำเป็น กักเก็บน้ำฝน/น้ำใช้ซ้ำ (เช่น น้ำล้างผักไปรดต้นไม้)',
      'จัดตารางแบ่งน้ำ รดน้ำเฉพาะเช้า-เย็น แจ้งผู้ใหญ่บ้านเรื่องน้ำสำรอง ดูแลแปลงพืชที่ขาดน้ำก่อน',
      'ใช้น้ำสำรองเฉพาะน้ำดื่ม-น้ำใช้จำเป็น ประสานขอรถน้ำ/ความช่วยเหลือจาก อบต. และ ปภ. 1784'
    ],
    tests:[
      'ถังน้ำ 20 ลิตรในห้อง ติดเซนเซอร์เหนือถัง วัด “ระยะจากหัวเซนเซอร์ถึงก้นถัง” ใส่ SENSOR_TO_BOTTOM_CM ตักน้ำออกทีละ 5 cm เทียบกับไม้บรรทัด ระดับต้องไล่ 0→1→2→3 เมื่อน้ำลด',
      'เกณฑ์ตั้งต้น (150/100/50 cm) ออกแบบสำหรับสระ ถังในห้องสูงไม่ถึง จึงให้ลดเกณฑ์เป็นสัดส่วนเดียวกัน (เช่น 30/20/10 cm) ทั้งในชีต Config และตาราง HAZARDS ของ node_multi.py แล้วจดว่าปรับอะไรเพราะอะไร (ใช้ตอบใบกิจกรรมที่ 6)',
      'ซ้อมระบบทั้งชุดด้วย SIMULATE = True ก่อน (ค่าระดับน้ำจำลองลดลงแล้วกลับขึ้นเองรอบละ 10 นาที) ใช้กลุ่ม Telegram ทดลองของนักเรียน ไม่ใช่กลุ่มหมู่บ้านจริง'
    ],
    limits:[
      'ระดับน้ำ ≠ ปริมาณน้ำคงเหลือ: สระมีรูปทรงและตะกอน ต้องคำนวณปริมาตรร่วมกับผู้ดูแลก่อนบอกว่า “เหลือกี่วัน”',
      'ก่อนติดตั้งในแหล่งน้ำชุมชนต้องขออนุญาต อบต./ผู้ดูแลประปา นักเรียนไม่ลงสระเอง การประกาศเขตภัยพิบัติเป็นหน้าที่ของหน่วยงานทางการ ป้ายของเราไม่ใช่การประกาศ',
      'เกณฑ์ทุกตัวเป็นตัวอย่าง ต้องปรับตามระดับน้ำที่เคยใช้ได้/ไม่พอใช้จริงของสระนั้นร่วมกับผู้ใหญ่บ้าน'
    ],
    sim:{
      stale:{ min:1500, max:3000, step:30 },
      ch:[
        { label:'ระดับน้ำสระ', unit:'cm', dir:'low',  t:[150,100,50],   min:0, max:250, step:5,   def:200, note:'ยิ่งน้อยยิ่งอันตราย' },
        { label:'ความชื้นดิน',  unit:'%',  dir:'low',  t:[40,30,20],     min:0, max:100, step:1,   def:60,  note:'ยิ่งน้อยยิ่งอันตราย' },
        { label:'วันที่ไม่มีฝน', unit:'วัน', dir:'high', t:[7,14,21],      min:0, max:30,  step:1,   def:3,   note:'อาสาสมัครกรอก' }
      ]
    }
  },

  smoke: {
    name:'ไฟป่า/หมอกควัน', prod:'ธงฝุ่นโรงเรียน', diff:'★★',
    tag:'ธง/ไฟสีหน้าโรงเรียนบอกว่าวันนี้ควรทำกิจกรรมกลางแจ้งหรือไม่ พร้อมแจ้งผู้ปกครอง',
    events:[
      '27 ก.พ. 2566: ดาวเทียม Suomi NPP ตรวจพบจุดความร้อนในจังหวัดอุตรดิตถ์ 192 จุด เป็นอันดับ 3 ของประเทศ รองจากกาญจนบุรี (688 จุด) และตาก (402 จุด) [3]',
      '7 เม.ย. 2569 เวลา 07:00 น.: PM2.5 ที่อุตรดิตถ์ 66.5 µg/m³ เกินค่ามาตรฐาน อยู่ลำดับที่ 12 ของจังหวัดที่เกินมาตรฐานในภาคเหนือ [4] (ค่านี้อยู่ในช่วง 37.6–75 ของตาราง AQI ไทยแบบเฉลี่ย 24 ชม. หรือ “ระดับ 2” ของชุดค่าในชุดชิ้นงาน)'
    ],
    note:'ข่าว [3][4] ไม่ได้ระบุว่าไฟอยู่ตำบลใดของอุตรดิตถ์ จึงห้ามสรุปว่าไฟ/ฝุ่นมาจากที่ใด ให้นักเรียนระบุเพียงว่า “จังหวัดมีจุดความร้อน/ฝุ่นสูงในช่วงนั้น”',
    problem:'โรงเรียนต้องตัดสินใจตอนเช้าว่าจะให้เรียนพละหรือเข้าแถวกลางแจ้งหรือไม่ แต่ไม่มีค่าฝุ่นหน้าโรงเรียน และผู้ปกครองไม่ทราบว่าวันไหนควรให้ลูกใส่หน้ากาก',
    hmw:'เราจะทำอย่างไรให้ครูและผู้ปกครองรู้ระดับฝุ่นของโรงเรียนก่อนเริ่มกิจกรรมทุกเช้า และรู้ว่าควรทำอะไรในแต่ละระดับ',
    how:'เซนเซอร์ PM2.5 ติดใต้ชายคาหน้าอาคาร (กันฝน ไม่โดนแดดตรง) → บอร์ดอ่านค่าและเฉลี่ยหลายรอบ (ประมาณ 30 นาที) → ระดับ 0–3 ตามตาราง AQI ไทย → ธง/ไฟ 3 สี + หน้าเว็บ + ข้อความสั้นถึงกลุ่มผู้ปกครอง (เช่น “ฝุ่นสูง งดกิจกรรมกลางแจ้ง ใส่หน้ากาก”) อาสาสมัครกรอกจำนวนจุดความร้อนในรัศมี 10 กม. จากเว็บของหน่วยงานรัฐ',
    extra:'ต่อยอดวิทยาศาสตร์ข้อมูล: เทียบค่าเซนเซอร์ของเรากับค่าสถานีทางการ 1–2 สัปดาห์ ทำกราฟกระจาย (scatter) ดูว่าต่างกันเท่าไร แล้วบันทึกเป็นข้อจำกัดของชิ้นงาน',
    honest:null,
    levels:[
      ['1 ไม่ใช้เซนเซอร์','ครูเวร/อาสาสมัครอ่านค่า PM2.5 ของจังหวัดจากเว็บหรือแอปของหน่วยงานรัฐ (เช่น Air4Thai ของกรมควบคุมมลพิษ) ทุกเช้า กรอกในปุ่ม “รายงานด้วยมือ” ได้ระดับ ธงสี และข้อความอัตโนมัติ','โทรศัพท์/คอมพิวเตอร์, ธงผ้า 3 สี'],
      ['2 โหนดบอร์ด','เซนเซอร์ PMS5003/PMS7003 ต่อ UART ตั้ง HAZARD="smoke" (ตรวจแรงดันไฟเลี้ยง/ระดับสัญญาณของรุ่นที่ซื้อกับดาต้าชีตก่อนต่อ)','บอร์ด IPST-WiFi, PMS5003/7003, พาวเวอร์แบงก์'],
      ['3 ต่อยอด','เทียบกับค่าทางการ + โปสเตอร์ “แต่ละระดับทำอะไร” + ห้องปลอดฝุ่นตัวอย่างของโรงเรียน','—']
    ],
    preset:{
      fn:'usePresetSmoke', board:'node_multi.py → HAZARD = "smoke" (ช่อง pm25)',
      th:'PM2.5 ≥25.1 / ≥37.6 / ≥75.1 µg/m³ = ระดับ 1/2/3 (ช่วงเหลือง/ส้ม/แดงของตาราง AQI ไทยแบบเฉลี่ย 24 ชม.) · จุดความร้อนรัศมี 10 กม. ≥1 / ≥3 / ≥5 จุด (ตัวอย่างสมมติ อาสากรอก)',
      timing:'วัดทุก 5 นาที (ถี่ขึ้นเมื่อระดับสูง) · เงียบเกิน 6 ชม. = “ไม่มีข้อมูล” (STALE_MIN 360) · ย้ำทุก 3 ชม. (REPEAT_MIN 180)',
      extra:'ไฟหน้าโรงเรียน: ใช้ node_siren.py ตั้ง SOUND_ON=False (ไฟอย่างเดียว) และติดป้ายอธิบายความหมายข้างโคม เพราะไฟเขียว/เหลือง/แดงของชุดนี้ไม่ตรงกับ 5 สีของ AQI ทุกสี (ระดับ “ส้ม” แสดงเป็นแดงกะพริบ)'
    },
    msgs:[
      'สถานการณ์ปกติ ทำแนวกันไฟและตกลงจุดห้ามเผาของชุมชนก่อนฤดูแล้ง',
      'ลดกิจกรรมกลางแจ้งที่ออกแรงมาก กลุ่มเสี่ยง (เด็ก ผู้สูงอายุ ผู้มีโรคปอด/หัวใจ) เฝ้าระวังอาการ',
      'งดกิจกรรมกลางแจ้ง ใส่หน้ากากกรอง PM2.5 เมื่อต้องออกนอกบ้าน ปิดประตูหน้าต่าง ใช้ห้องปลอดฝุ่น',
      'อยู่ในอาคาร/ห้องปลอดฝุ่น งดกิจกรรมกลางแจ้งทุกชนิด ผู้มีอาการหายใจลำบากพบแพทย์ ไฟลามใกล้ชุมชนโทร 199 / 1784'
    ],
    tests:[
      'ซ้อมระบบทั้งชุดด้วย SIMULATE = True (ค่า PM2.5 ขึ้น-ลงเองรอบละ 10 นาที) แล้วดูข้อความ หน้าเว็บ และไฟเปลี่ยนตามระดับ ไม่ต้องใช้ควันจริง',
      'เมื่อต่อเซนเซอร์จริง ให้อ่านค่าอากาศปกติในห้อง/หน้าอาคารเทียบกับค่าทางการของจังหวัดในช่วงเวลาเดียวกัน บันทึกผลต่างทุกวันเป็นตาราง',
      'ถ้าครูต้องการดูว่าเซนเซอร์ตอบสนอง ให้ครูเป็นผู้จุดธูป 1 ก้านในที่โล่งอากาศถ่ายเท แล้วโบกควันเบา ๆ เข้าใกล้ช่องรับอากาศชั่วครู่ ห้ามจุดไฟในห้องปิด และนักเรียนไม่ต้องสัมผัสควัน'
    ],
    limits:[
      'เซนเซอร์ราคาประหยัดอ่านต่างจากสถานีทางการได้ และอาจเพี้ยนเมื่ออากาศชื้นมาก ให้เรียกว่า “ค่าโดยประมาณ” และแสดงค่าทางการควบคู่',
      'ตาราง AQI ไทยใช้ค่าเฉลี่ย 24 ชม. แต่โหนดส่งค่าเฉลี่ยหลายรอบ (~30 นาที) เพื่อให้เตือนทัน จึงไม่ใช่ค่ามาตรฐานทางการ และไม่ใช่คำแนะนำทางการแพทย์',
      'ห้ามนักเรียนเข้าใกล้หรือพยายามดับไฟป่า ห้ามเผา ไฟลามใกล้ชุมชนโทร 199 หรือ ปภ. 1784 · การส่งข้อความเข้ากลุ่มผู้ปกครองต้องได้รับอนุญาตจากโรงเรียน และไม่ใส่ข้อมูลส่วนตัวนักเรียน'
    ],
    sim:{
      stale:{ min:360, max:720, step:10 },
      ch:[
        { label:'PM2.5', unit:'µg/m³', dir:'high', t:[25.1,37.6,75.1], min:0, max:150, step:0.1, def:15, note:'ช่วงเหลือง/ส้ม/แดงของตาราง AQI ไทยแบบเฉลี่ย 24 ชม.' },
        { label:'จุดความร้อนรัศมี 10 กม.', unit:'จุด', dir:'high', t:[1,3,5], min:0, max:10, step:1, def:0, note:'อาสากรอก (เกณฑ์สมมติ)' }
      ]
    }
  },

  wind: {
    name:'วาตภัย', prod:'ยามลมหมู่บ้าน', diff:'★★★ กังหันต้องสอบเทียบ',
    tag:'แผนที่จุดเสี่ยงพายุ + กังหันวัดลมหน้าหมู่บ้านที่เตือนคนในรัศมีเสียง และเก็บข้อมูลลมจริงไว้ปรับเกณฑ์',
    events:[
      '3 พ.ค. 2567 ราว 16.30 น.: พายุฤดูร้อนฝนฟ้าคะนอง ลมแรง และลูกเห็บ ใน 9 อำเภอของอุตรดิตถ์ รวม 45 ตำบล 122 หมู่บ้าน 664 หลังคาเรือน (ลับแล 201 ฟากท่า 161 พิชัย 143 ท่าปลา 95 ตรอน 39 ทองแสนขัน 15 บ้านโคก 10) [5]',
      'ต้นไม้และเสาไฟฟ้าหักโค่น ไฟฟ้าดับหลายชั่วโมง โดยเฉพาะเขตเทศบาลเมืองอุตรดิตถ์ ต้นมะขามใหญ่โค่นทับบ้านเรือนและถนนใกล้ตลาดสด และอาคารของโรงพยาบาลอุตรดิตถ์เสียหายหลายชั้น ข่าวเบื้องต้นยังไม่มีรายงานผู้บาดเจ็บหรือเสียชีวิต [5]'
    ],
    note:'เหตุเกิดช่วงเย็น (ราว 16.30 น.) และสิ่งที่ล้มทับบ้านตามข่าวคือต้นไม้ใหญ่/เสาไฟ ซึ่งสำรวจและเตรียมการล่วงหน้าได้',
    problem:'พายุฤดูร้อนมาเร็ว ผู้ที่อยู่นอกบ้านหรือขับรถจักรยานยนต์ตอนลมแรงเสี่ยงอันตราย ต้นไม้ใหญ่ ป้าย และหลังคาอาจเป็นจุดเสี่ยงที่ยังไม่เคยถูกสำรวจ และเมื่อไฟดับหลายชั่วโมงก็ยากต่อการรับข่าวสาร',
    hmw:'เราจะทำอย่างไรให้คนในหมู่บ้านรู้ล่วงหน้าว่าจุดไหนเสี่ยงเมื่อพายุมา และรู้ทันทีเมื่อลมในหมู่บ้านเริ่มแรงผิดปกติ',
    how:'ก่อนพายุ: เดินสำรวจจุดเสี่ยง (ต้นไม้ใหญ่ ป้าย หลังคา ที่หลบ) ทำแผนที่ + บัตรตรวจบ้าน → ระหว่างพายุ: กังหันถ้วยทำเองนับรอบ → บอร์ดคำนวณ km/h → ระดับ 0–3 → ไซเรน/ไฟ + ข้อความมือถือ + บันทึกลมสูงสุดลงชีตเพื่อปรับเกณฑ์ของหมู่บ้าน',
    extra:'ต่อยอด: ต่อที่วัดฝนแบบกระดกน้ำ (ช่อง rain_mm_3h) สรุปลมสูงสุดรายวันเป็นกราฟ และเทียบกับข้อมูลสถานีอุตุนิยมวิทยาใกล้เคียง',
    honest:'ต้องบอกให้ตรงตามจริง: พายุฤดูร้อนมักมาเร็ว โหนดวัดลมในหมู่บ้านจึงเตือนล่วงหน้าได้น้อยมาก ประโยชน์หลักคือ (1) ให้ผู้ใหญ่บ้านและคนที่อยู่ไกลยืนยันสถานการณ์ในหมู่บ้าน (2) ส่งสัญญาณให้คนในรัศมีเสียงเข้าที่หลบ (3) เก็บข้อมูลลมจริงของหมู่บ้านไว้ปรับเกณฑ์ ส่วนการเตือนล่วงหน้าจริงมาจากประกาศของกรมอุตุนิยมวิทยา ซึ่งอาสาสมัครควรส่งต่อให้ทุกคน',
    levels:[
      ['1 ไม่ใช้บอร์ด','แผนที่จุดเสี่ยงพายุของโรงเรียน/หมู่บ้าน (เดินสำรวจ ถ่ายรูป ทำเป็นป้าย QR ที่ศาลา) + บัตรตรวจบ้านก่อนฤดูพายุ (เก็บของเบา ตรวจหลังคา ตัดแต่งกิ่งที่ไม่สูง ชาร์จไฟฉาย)','กระดาษ/ป้าย สมาร์ตโฟน'],
      ['2 โหนดบอร์ด','กังหันถ้วยทำเอง (ลูกปิงปองผ่าซีก/ถ้วยพลาสติก) + reed switch หรือโฟโตอินเทอร์รัปเตอร์ นับรอบที่ขา GPIO27 ตั้ง HAZARD="wind" และสอบเทียบ KMH_PER_HZ','บอร์ด IPST-WiFi, ตัวนับรอบ, ไม้/ท่อ PVC เป็นแกน'],
      ['3 ต่อยอด','ที่วัดฝน + ไซเรน/ไฟหมู่บ้าน + กราฟลมสูงสุดรายวัน','ชุดไซเรน, ที่วัดฝนกระดกน้ำ']
    ],
    preset:{
      fn:'usePresetWind', board:'node_multi.py → HAZARD = "wind" (ช่อง wind_kmh, rain_mm_3h)',
      th:'ลม ≥30 / ≥50 / ≥70 km/h = ระดับ 1/2/3 · ฝน 3 ชม. ≥30 / ≥60 / ≥90 mm (เกณฑ์ตัวอย่างสมมติ)',
      timing:'วัดทุก 2 นาที (ถี่ขึ้นเป็น 20 วินาทีที่ระดับ 3) · ส่งค่าลมสูงสุดของ 3 ช่วง×10 วินาที กันลมกระโชกหลุด · เงียบเกิน 30 นาที = “ไม่มีข้อมูล”',
      extra:'ไซเรน: เปิดเสียงได้ตามระดับ 2–3 (ซ้อมกับ อบต./ผู้ใหญ่บ้านก่อนว่าเสียงหมายถึงอะไร)'
    },
    msgs:[
      'สถานการณ์ปกติ ตัดแต่งกิ่งไม้ใหญ่ใกล้บ้าน และตรวจหลังคา/ป้ายก่อนหน้าพายุฤดูร้อน',
      'เก็บของเบา ป้าย ผ้าใบที่ปลิวได้ ตรวจหลังคาและต้นไม้ใหญ่ใกล้บ้าน ชาร์จไฟฉายและโทรศัพท์',
      'อยู่ในอาคารแข็งแรง ห่างหน้าต่างกระจก ห่างต้นไม้ใหญ่ เสาไฟ ป้ายโฆษณา งดขับขี่รถจักรยานยนต์',
      'หลบในจุดที่แข็งแรงที่สุด (ห้องที่ไม่มีหน้าต่าง) ไม่ออกนอกอาคารจนกว่าลมสงบ หลังเหตุห้ามแตะสายไฟที่ขาด'
    ],
    tests:[
      'สอบเทียบด้วยพัดลมตั้งโต๊ะ/พัดลมอุตสาหกรรมของโรงเรียน 3 ความเร็ว (ในที่ร่ม) เทียบกับเครื่องวัดลมแบบมือถือของห้องวิทย์/ครู บันทึก “รอบต่อวินาที” กับ “km/h” เป็นตาราง หาค่า KMH_PER_HZ จากค่าเฉลี่ยหรือกราฟเส้นตรง',
      'ถ้าไม่มีเครื่องวัดลมอ้างอิง ผลที่ได้เป็นเพียง “ความเร็วสัมพัทธ์” ให้ตั้งระดับจากการสังเกต (กิ่งไม้ไหว เดินสวนลมลำบาก ฯลฯ) และเขียนว่า “ยังไม่สอบเทียบ” ห้ามอ้างว่าเป็น km/h จริง',
      'ซ้อมระบบทั้งชุดด้วย SIMULATE = True ใช้กลุ่ม Telegram ทดลองของนักเรียน ห้ามทดสอบกลางแจ้งขณะฟ้าคะนอง'
    ],
    limits:[
      'ติดตั้งเสา/กังหัน ให้ผู้ใหญ่ทำ นักเรียนไม่ปีนหลังคา ต้นไม้ หรือเสา อย่าติดบนเสาโลหะสูงในช่วงฟ้าคะนอง',
      'ความสูงและตำแหน่งติดตั้งทำให้ค่าลมต่างกัน ค่าที่วัดต่ำกว่าสถานีอุตุนิยมวิทยาได้ จึงใช้เป็นข้อมูลของ “จุดนี้ในหมู่บ้าน” ไม่ใช่ลมของทั้งตำบล',
      'ระหว่างพายุให้ทุกคนอยู่ในอาคารแข็งแรง ห่างหน้าต่างกระจกและต้นไม้ใหญ่ งดขับจักรยานยนต์ (ตามข้อความระดับ 2–3 ของชุดค่า) และห้ามแตะสายไฟที่ขาดหลังเหตุ'
    ],
    sim:{
      stale:{ min:30, max:60, step:1 },
      ch:[
        { label:'ความเร็วลม', unit:'km/h', dir:'high', t:[30,50,70], min:0, max:120, step:1, def:10, note:'ค่าลมสูงสุดของช่วงวัด' },
        { label:'ฝนสะสม 3 ชั่วโมง', unit:'mm', dir:'high', t:[30,60,90], min:0, max:150, step:1, def:0, note:'จากที่วัดฝนแบบกระดกน้ำ' }
      ]
    }
  },

  landslide: {
    name:'ดินถล่ม', prod:'เสาเฝ้าไหล่เขา', diff:'★★★ ต้องมีผู้ใหญ่ร่วม',
    tag:'เฝ้าสัญญาณก่อนเกิดเหตุ (ความชื้นดิน ฝนสะสม รอยแตก) แล้วบอกชาวบ้านให้เตรียมตัวก่อนตัดสินใจอพยพ',
    events:[
      '3 ต.ค. 2567: ฝนถล่มอุตรดิตถ์ ดินสไลด์ทำให้ถนนบ้านน้ำหมัน–บ้านผาแก่น อ.ท่าปลา ทรุดตัว ประชาชนใช้เส้นทางไม่ได้ และข่าวระบุไฟฟ้าดับในพื้นที่ [6]',
      'คืน 8 ถึงราว 02.00 น. 9 ก.ย. 2554: ฝนตกหนักต่อเนื่อง น้ำป่าพัดโคลน ท่อนซุง และเศษไม้ใหญ่เข้าหมู่บ้านห้วยเดื่อ/ต้นขนุน ต.น้ำไผ่ อ.น้ำปาด บ้านเรือนพังหายราว 19–20 หลัง (ตัวเลขในข่าวต่างกันเล็กน้อย) สะพาน 2 แห่งขาด ตามข่าวขณะนั้นมีผู้เสียชีวิต 1 ราย และสูญหาย 7 ราย [7][8]',
      'กรมพัฒนาที่ดินสรุปว่า พ.ศ. 2549 เกิดอุทกภัยและดินโคลนถล่มในอุตรดิตถ์ช่วง 22–23 พ.ค. กระทบพื้นที่ อ.ลับแล อ.เมือง และ อ.ท่าปลา และระบุพื้นที่เสี่ยงดินถล่มของ 3 อำเภอนี้: เสี่ยงน้อย 168,466 ไร่ ปานกลาง 80,008 ไร่ รุนแรง 9,301 ไร่ [9]'
    ],
    note:null,
    problem:'ครัวเรือนใกล้เชิงเขา/ร่องน้ำไม่รู้ว่าฝนสะสมและดินที่อิ่มน้ำถึงจุดน่ากังวลหรือยัง และเหตุมักเกิดกลางคืนขณะไฟดับ สัญญาณมือถือไม่แน่นอน',
    hmw:'เราจะทำอย่างไรให้ชาวบ้านรู้ว่าไหล่เขาเริ่มน่ากังวลและเตรียมตัวไว้ก่อน โดยไม่ต้องให้ใครขึ้นไปดูบนเขาตอนฝนตกหนัก',
    how:'สมุดสังเกตไหล่เขา (รอยแตก ต้นไม้/เสาเอียง น้ำขุ่นไหลจากเขา) + ถังวัดฝน + (เลือก) โหนดดินและฝน ที่ติดตั้งโดยผู้ใหญ่ → ระดับ 0–3 → ข้อความ “สิ่งที่ควรทำ” + ไซเรน/ไฟ ที่ทำงานได้แม้เน็ตล่ม (บอร์ดคำนวณระดับเอง) → ผู้ใหญ่บ้าน/อบต. ตัดสินใจอพยพ',
    extra:'ต่อยอด (ต้องมีครู/ผู้เชี่ยวชาญร่วม ยังไม่มีโค้ดในชุดนี้): เสาวัดความเอียง และไม้วัดรอยแตกที่อ่านค่าเป็นระยะ',
    honest:'ต้องบอกให้ตรงตามจริง: ความชื้นดินจุดเดียวและปริมาณฝน ทำนายดินถล่มไม่ได้ เนินแต่ละลูกต่างกัน เกณฑ์จริงต้องมาจากหน่วยงานด้านธรณีวิทยา/ปภ./อบต. ชิ้นงานนี้คือ “ตัวช่วยสังเกตและกระตุ้นให้เตรียมตัว” ไม่ใช่เครื่องทำนาย',
    levels:[
      ['1 ไม่ใช้บอร์ด','ถังวัดฝน DIY (ขวดพลาสติกปากกว้าง + กรวย + สเกล mm สอบเทียบด้วยการตวงน้ำ) + สมุดสังเกตไหล่เขาที่อาสาสมัครกรอก กรอกค่าฝนในปุ่ม “รายงานด้วยมือ” ได้ระดับและข้อความอัตโนมัติ','ขวด กรวย ไม้บรรทัด สมุด'],
      ['2 โหนดบอร์ด','เซนเซอร์ความชื้นดินแบบคาปาซิทีฟ (อนาล็อก 3.3 V ที่ GPIO34) + ที่วัดฝนกระดกน้ำ ตั้ง HAZARD="landslide", RAIN_ENABLED=True ฝน 24 ชม. จะยังไม่ถูกส่งจนบอร์ดเดินครบ 24 ชม. ช่วงนั้นให้อาสากรอกจากถังวัดฝน','บอร์ด IPST-WiFi, เซนเซอร์ความชื้นดิน, ที่วัดฝน, กล่องกันน้ำ'],
      ['3 ต่อยอด','เสาวัดความเอียงและไม้วัดรอยแตก ร่วมกับครู/เจ้าหน้าที่ นอกขอบเขตโค้ดชุดนี้','—']
    ],
    preset:{
      fn:'usePresetLandslide', board:'node_multi.py → HAZARD = "landslide" (ช่อง soil_pct, rain_mm_24h; ช่อง tilt_deg ให้อาสากรอกหรือเว้นว่าง)',
      th:'ความชื้นดิน ≥60 / ≥75 / ≥90 % · ฝน 24 ชม. ≥60 / ≥90 / ≥120 mm · ความเอียงเสา ≥2 / ≥5 / ≥10° (ตัวเลขเหล่านี้ไม่ได้มาจากเกณฑ์ทางการ)',
      timing:'วัดทุก 5 นาที (ถี่ขึ้นเป็น 30 วินาทีที่ระดับ 3) · เงียบเกิน 30 นาที = “ไม่มีข้อมูล” (ค่าตั้งต้น)',
      extra:null
    },
    msgs:[
      'สถานการณ์ปกติ สำรวจรอยแตกร้าว/ร่องน้ำบนไหล่เขาก่อนฤดูฝน',
      'สังเกตรอยแตกร้าวบนพื้น/ผนัง ต้นไม้หรือเสาเอียง น้ำขุ่นไหลจากไหล่เขา และฟังเสียงผิดปกติ',
      'เตรียมออกจากบ้านที่ติดไหล่เขาหรือใกล้ร่องน้ำ ย้ายไปบ้านญาติหรือศูนย์พักพิงที่ห่างเชิงเขา',
      'อพยพทันที ห่างจากเชิงเขาและร่องน้ำ ไม่กลับเข้าบ้านจนกว่าเจ้าหน้าที่แจ้ง โทร 1784 (ปภ.)'
    ],
    tests:[
      'ทำ “ลาดเขาจำลอง” ในถาด/ลังพลาสติก ใส่ดินร่วนผสมทราย เอียงราว 20–30° ฝังเซนเซอร์ความชื้นดินระดับตื้น ใช้บัวรดน้ำเป็นฝนจำลองและตวงปริมาณน้ำที่ใช้ ดูค่า soil_pct เพิ่มตามน้ำ และบันทึกว่าดินในถาดเริ่มเลื่อนเมื่อใด',
      'สอบเทียบเซนเซอร์: วัดค่าดิบในอากาศ (SOIL_RAW_DRY) และจุ่มน้ำถึงเส้นที่กำหนด (SOIL_RAW_WET) บันทึกวิธีและวันที่สอบเทียบ ผลจากถาดบอกได้แค่ “รูปแบบ” ห้ามนำเกณฑ์จากถาดไปใช้กับเขาจริง',
      'ซ้อมระบบทั้งชุดด้วย SIMULATE = True ใช้กลุ่ม Telegram ทดลองของนักเรียน และซ้อมสื่อสารกับผู้ใหญ่บ้านว่าเมื่อได้ข้อความระดับ 3 ใครทำอะไร'
    ],
    limits:[
      'นักเรียนห้ามขึ้นไหล่เขา ห้ามปักเซนเซอร์ในพื้นที่เสี่ยงเอง และห้ามไปสังเกตตอนฝนตกหนัก ผู้ใหญ่/อบต. เป็นผู้ติดตั้งและตรวจตอนอากาศปกติ',
      'ห้ามอ้างว่า “ทำนายดินถล่มได้” ให้เขียนว่า “ช่วยเตือนให้เตรียมตัว” และให้เกณฑ์มาจาก กรมทรัพยากรธรณี/ปภ./อบต. ก่อนใช้จริง',
      'ฝนสะสมของบอร์ดหายเมื่อรีเซ็ต/ไฟดับ จึงถือเป็นค่าสำรอง ให้เทียบกับถังวัดฝนที่อาสาอ่านด้วยมือเสมอ'
    ],
    sim:{
      stale:{ min:30, max:60, step:1 },
      ch:[
        { label:'ความชื้นดิน', unit:'%', dir:'high', t:[60,75,90], min:0, max:100, step:1, def:40, note:'เซนเซอร์คาปาซิทีฟ' },
        { label:'ฝนสะสม 24 ชั่วโมง', unit:'mm', dir:'high', t:[60,90,120], min:0, max:200, step:1, def:0, note:'อาสาอ่านจากถังวัดฝนได้' },
        { label:'ความเอียงเสา', unit:'°', dir:'high', t:[2,5,10], min:0, max:15, step:0.5, def:0, note:'อาสากรอกหรือเว้นว่าง' }
      ]
    }
  }
};
var HZ_ORDER = ['drought','smoke','wind','landslide'];
var hzCur = LS.get('hz');
if(HZ_ORDER.indexOf(hzCur)<0) hzCur = 'drought';

var ACT_LABEL = {
  a1:'เหตุการณ์จริงในอุตรดิตถ์', a2:'โจทย์ที่นักเรียนตั้งได้', a3:'นวัตกรรมที่เสนอและวิธีทำงาน',
  a4:'เลือกระดับที่ทำได้และแบบร่าง', a5:'ค่าตั้งต้นของชิ้นงานและเครื่องจำลอง', a6:'ทดสอบจำลองอย่างปลอดภัย'
};

function ul(items){
  return '<ul style="margin:.3em 0 0">' + items.map(function(t){ return '<li>'+refs(t)+'</li>'; }).join('') + '</ul>';
}
function kv(rows){
  return '<dl class="kv">' + rows.filter(function(r){ return r[1]; }).map(function(r){
    return '<dt>'+esc(r[0])+'</dt><dd>'+refs(r[1])+'</dd>';
  }).join('') + '</dl>';
}

/* ---- simulator ---- */
function levelOf(ch, v){
  var n = 0;
  ch.t.forEach(function(t){ if(ch.dir==='high' ? v>=t : v<=t) n++; });
  return n;
}
function thText(ch){
  var sym = ch.dir==='high' ? '≥' : '≤';
  return 'เกณฑ์ระดับ 1/2/3: ' + sym + ch.t.join(' / ' + sym) + ' ' + ch.unit;
}
function minText(m){
  if(m>=120){ var h = m/60; return (Math.round(h*10)/10) + ' ชม.'; }
  return m + ' นาที';
}
function simHTML(hid, h){
  var s = h.sim, html = '';
  html += '<div class="card" data-sim="'+hid+'">';
  html += '<h4>เครื่องจำลองระดับ 0–3 · ' + esc(h.prod) + ' <span class="tag-sim">เกณฑ์ตัวอย่าง</span></h4>';
  html += '<p class="sm mute">เลื่อนค่าเหมือนเซนเซอร์อ่านค่ามาได้ ดูว่าระดับและข้อความเปลี่ยนอย่างไร ระดับรวมใช้ช่องที่แย่ที่สุด ซึ่งเป็นการประมาณให้เห็นภาพ ไม่ใช่กติกาทางการ ภัยน้ำท่วมไม่มีเกณฑ์ตัวอย่างในเอกสาร (เกณฑ์ทั้งหมดต้องขอจากท้องถิ่น) จึงไม่มีเครื่องจำลอง</p>';
  html += '<div class="sim"><div class="sim-in">';
  s.ch.forEach(function(ch,i){
    var id = 'sim-'+hid+'-'+i;
    html += '<div class="sl"><label for="'+id+'"><span>'+esc(ch.label)+' <span class="mute sm">('+esc(ch.unit)+')</span></span><output class="lvl-mini" data-out="'+i+'" for="'+id+'"></output></label>' +
      '<input type="range" id="'+id+'" data-i="'+i+'" min="'+ch.min+'" max="'+ch.max+'" step="'+ch.step+'" value="'+ch.def+'">' +
      '<span class="th">'+esc(thText(ch))+' · '+esc(ch.note)+'</span></div>';
  });
  var sid = 'sim-'+hid+'-stale';
  html += '<div class="sl"><label for="'+sid+'"><span>ข้อมูลเงียบมาแล้วนานเท่าไร</span><output data-out="stale" for="'+sid+'"></output></label>' +
    '<input type="range" id="'+sid+'" data-stale min="0" max="'+s.stale.max+'" step="'+s.stale.step+'" value="0">' +
    '<span class="th">เกิน '+esc(minText(s.stale.min))+' = “ไม่มีข้อมูล” (STALE_MIN '+s.stale.min+')</span></div>';
  html += '</div>';
  html += '<div class="sim-out" aria-live="polite">' +
    '<div class="lvl"><span class="lvl-b" data-lvl></span></div>' +
    '<div class="sim-nodata" data-nodata hidden><svg class="ic" aria-hidden="true"><use href="#i-warn"/></svg><span>ไม่มีข้อมูล · เซนเซอร์เงียบเกินเวลาที่กำหนด หน้าเว็บต้องบอกว่า “ไม่มีข้อมูล” ไม่ใช่แสดงสีเขียว เพราะเงียบไม่เท่ากับปลอดภัย</span></div>' +
    '<div class="sim-msg"><b>สิ่งที่ควรทำ (ข้อความที่ระบบส่ง)</b><span data-msg></span></div>' +
    '<p class="sm mute" style="margin:0" data-last></p>' +
    '</div></div></div>';
  return html;
}
function simUpdate(card){
  var hid = card.getAttribute('data-sim'), h = HZ[hid], s = h.sim;
  var worst = 0;
  s.ch.forEach(function(ch,i){
    var inp = $('input[data-i="'+i+'"]', card);
    var v = parseFloat(inp.value);
    var n = levelOf(ch, v);
    if(n>worst) worst = n;
    var o = $('[data-out="'+i+'"]', card);
    o.textContent = v + ' ' + ch.unit + ' · ระดับ ' + n;
    o.className = 'lvl-mini' + (n===3 ? ' l3':'');
    o.style.setProperty('--lc', 'var(--lv'+n+')');
  });
  var st = parseFloat($('input[data-stale]', card).value);
  $('[data-out="stale"]', card).textContent = minText(st);
  var stale = st >= s.stale.min;
  var lvl = $('[data-lvl]', card);
  lvl.textContent = 'ระดับ ' + worst + ' ' + LV[worst];
  lvl.className = 'lvl-b' + (worst===3 ? ' l3':'');
  lvl.style.setProperty('--lc', 'var(--lv'+worst+')');
  lvl.hidden = stale;
  $('[data-nodata]', card).hidden = !stale;
  $('[data-msg]', card).textContent = stale ? 'ตรวจเซนเซอร์และไฟเลี้ยง อ่านค่าจากไม้วัด/ถังวัดฝนด้วยมือแทน และอย่าถือว่าปลอดภัยจนกว่าจะได้ข้อมูลใหม่' : h.msgs[worst];
  $('[data-last]', card).textContent = stale ? ('ค่าล่าสุดก่อนเงียบเทียบได้ระดับ ' + worst + ' ' + LV[worst]) : 'ระดับรวมคือระดับสูงสุดของทุกช่อง';
}

/* ---- hazard panel per activity ---- */

/* ---- full worked examples (data from window.HZX, built from the teacher answer sheets) ---- */
var HZX = window.HZX || {};
function bl(t){ return esc(t).replace(/«/g,'<span class="bl">').replace(/»/g,'</span>'); }
function plain(t){ return String(t).replace(/[«»]/g,'').replace(/\s*·\s*$/,'').trim(); }
function hzxPara(t){ return '<p' + (t.indexOf('«')<0 ? ' class="q"' : '') + '>' + bl(t) + '</p>'; }
function hzxTable(rows){
  if(rows.length===1 && rows[0].length===1){
    return '<div class="ans-box">' + rows[0][0].map(function(t){ return '<p>'+bl(t)+'</p>'; }).join('') + '</div>';
  }
  var maxc = rows.reduce(function(m,r){ return Math.max(m, r.length); }, 0);
  var head = rows.length>1 && rows[0].every(function(c){ return c.join('').indexOf('«')<0; }) && rows[0].length===maxc;
  var labels = head ? rows[0].map(function(c){ return plain(c.join(' ')); }) : null;
  var html = '<div class="tbl hzt' + (head ? ' rsp' : '') + '"><table>';
  rows.forEach(function(r,ri){
    var isH = head && ri===0;
    if(isH) html += '<thead>';
    else if(ri===(head?1:0)) html += '<tbody>';
    html += '<tr>';
    r.forEach(function(c,ci){
      var tag = isH ? 'th' : 'td';
      var span = (r.length<maxc && r.length===1) ? ' colspan="'+maxc+'"' : '';
      var lab = (!isH && labels && r.length===maxc && labels[ci]) ? ' data-label="'+esc(labels[ci])+'"' : '';
      html += '<'+tag+span+lab+'>' + c.map(function(t){ return '<p>'+bl(t)+'</p>'; }).join('') + '</'+tag+'>';
    });
    html += '</tr>';
    if(isH) html += '</thead>';
  });
  return html + '</tbody></table></div>';
}
function hzxBlock(b){
  if(b[0]==='sh') return '<h5 class="sh">' + bl(b[1]) + '</h5>';
  if(b[0]==='p') return hzxPara(b[1]);
  return hzxTable(b[1]);
}
function hzxHTML(hid, act){
  var d = HZX[hid], h = HZ[hid];
  if(!d || !d.acts[act]) return '';
  var a = d.acts[act], n = act.slice(1);
  var html = '<section class="hzx" aria-label="ตัวอย่างละเอียดใบกิจกรรมที่ '+n+' '+esc(h.name)+'">';
  html += '<div class="card soft"><h4 class="hzx-h">ตัวอย่างละเอียด · ใบกิจกรรมที่ '+n+' · '+esc(h.name)+'</h4>';
  html += '<p class="hzx-meta mute">' + esc(plain(d.team[0].replace(/\s*·\s*$/,''))).replace(/\s+·\s+/g,' · ') + ' &nbsp;|&nbsp; ' +
          esc(plain(d.team[1]).replace(/\s+·\s+/g,' · ') + ' · ' + plain(d.team[2]).replace(/\s*·?\s*วันที่.*$/,'').replace(/\s+·\s+/g,' · ')) + '</p>';
  html += '<p class="sm" style="margin:.6em 0 0">ข้อความ<span class="bl">สีน้ำเงิน</span>คือแนวตอบตัวอย่าง นักเรียนต้องคิดและเขียนเอง ไม่ควรคัดลอก ชื่อนักเรียน ก ข ค ง จ เป็นชื่อสมมติ</p>';
  a.pre.forEach(function(b){ html += '<div style="margin-top:.6em">' + hzxBlock(b) + '</div>'; });
  html += '</div>';
  var notes = [];
  if(act==='a1' && d.intro[2]) notes.push(d.intro[2]);
  if(d.intro[3]) notes.push(d.intro[3]);
  if(d.intro[4]) notes.push(d.intro[4]);
  html += '<div class="callout warn"><svg class="ic" aria-hidden="true"><use href="#i-warn"/></svg><div>' + notes.map(function(t){ return '<p>'+bl(t)+'</p>'; }).join('') + '</div></div>';
  html += '<div class="hzx-ctl"><button type="button" class="btn sm" data-hzx-all="open">เปิดทุกหัวข้อ</button><button type="button" class="btn sm" data-hzx-all="close">ปิดทุกหัวข้อ</button></div>';
  a.secs.forEach(function(sec,i){
    var m = /^(\d+)\.\s*(.*)$/.exec(sec.h);
    html += '<details class="hzx-sec"' + (i===0 ? ' open' : '') + '><summary><span class="n">' + (m?m[1]:i+1) + '</span><span>' + esc(m?m[2]:sec.h) + '</span></summary><div class="hzx-b">' +
      sec.b.map(hzxBlock).join('') + '</div></details>';
  });
  return html + '</section>';
}
document.addEventListener('click', function(e){
  var b = e.target.closest('[data-hzx-all]');
  if(!b) return;
  var open = b.getAttribute('data-hzx-all')==='open';
  $$('details.hzx-sec', b.closest('.hzx')).forEach(function(d){ d.open = open; });
});

function hzPanel(h, hid, act){
  var out = '';
  out += '<div class="hz-title"><h4>'+esc(h.name)+' · “'+esc(h.prod)+'”</h4><span class="pill">'+esc(h.diff)+'</span></div>';
  out += '<p style="margin:0 0 12px">'+esc(h.tag)+'</p>';
  var body = '<div class="stack">';
  if(act==='a1'){
    body += '<div class="card"><h4>'+ACT_LABEL.a1+'</h4>' + ul(h.events) + (h.note ? '<p class="sm mute" style="margin:.7em 0 0"><b>ข้อสังเกต:</b> '+refs(h.note)+'</p>' : '') + '</div>';
  } else if(act==='a2'){
    body += '<div class="card"><h4>'+ACT_LABEL.a2+'</h4>' + kv([['ปัญหา (ตัวอย่างโจทย์)',h.problem],['เราจะ…ได้อย่างไร',h.hmw]]) + '</div>';
  } else if(act==='a3'){
    body += '<div class="card"><h4>'+ACT_LABEL.a3+'</h4><p style="margin:0">'+refs(h.how)+'</p>' + (h.extra ? '<p class="sm mute" style="margin:.7em 0 0">'+refs(h.extra)+'</p>' : '') + '</div>';
  } else if(act==='a4'){
    body += '<div class="card"><h4>'+ACT_LABEL.a4+'</h4><div class="tbl tight"><table><thead><tr><th>ระดับ</th><th>นักเรียนทำอะไร</th><th>ใช้อะไร</th></tr></thead><tbody>' +
      h.levels.map(function(r){ return '<tr><td>'+esc(r[0])+'</td><td>'+refs(r[1])+'</td><td>'+esc(r[2])+'</td></tr>'; }).join('') +
      '</tbody></table></div>' + (h.honest ? '<div class="callout warn" style="margin-top:12px"><svg class="ic" aria-hidden="true"><use href="#i-warn"/></svg><div><p>'+esc(h.honest)+'</p></div></div>' : '') + '</div>';
  } else if(act==='a5'){
    body += '<div class="card"><h4>ค่าตั้งต้นของชุดชิ้นงาน</h4>' + kv([
      ['รันใน Apps Script',h.preset.fn],['โค้ดบอร์ด',h.preset.board],['เกณฑ์ตัวอย่าง (สมมติ)',h.preset.th],['จังหวะเวลา',h.preset.timing],['เพิ่มเติม',h.preset.extra]
    ]) + '</div>';
    body += '<div class="card"><h4>ข้อความ “สิ่งที่ควรทำ” ตามระดับ</h4><div class="tbl tight"><table><thead><tr><th>ระดับ</th><th>ข้อความที่ระบบส่ง</th></tr></thead><tbody>' +
      h.msgs.map(function(m,i){ return '<tr><td>'+i+' '+LV[i]+'</td><td>'+esc(m)+'</td></tr>'; }).join('') + '</tbody></table></div></div>';
    body += simHTML(hid, h);
  } else if(act==='a6'){
    body += '<div class="card"><h4>'+ACT_LABEL.a6+'</h4>' + ul(h.tests) + '</div>';
    body += '<div class="card"><h4>ข้อจำกัดและความปลอดภัย (ห้ามอ้างเกินจริง)</h4>' + ul(h.limits) + '</div>';
  }
  body += hzxHTML(hid, act);
  body += '</div>';
  out += body;
  return out;
}
function renderHz(){
  $$('.hz[data-hz-for]').forEach(function(box){
    var act = box.getAttribute('data-hz-for');
    var h = HZ[hzCur];
    var bar = '<div class="hz-bar" role="tablist" aria-label="เลือกภัย">' + HZ_ORDER.map(function(id){
      var sel = id===hzCur;
      return '<button type="button" class="hz-b" role="tab" data-hz="'+id+'" aria-selected="'+(sel?'true':'false')+'" tabindex="'+(sel?'0':'-1')+'">'+esc(HZ[id].name)+' <span class="star">'+esc(HZ[id].diff.split(' ')[0])+'</span></button>';
    }).join('') + '</div>';
    box.innerHTML = bar + '<div class="hz-p" role="tabpanel">' + hzPanel(h, hzCur, act) + '</div>';
    $$('[data-sim]', box).forEach(function(card){
      var st = SIMSTATE[card.getAttribute('data-sim')];
      if(st){
        $$('input[data-i]', card).forEach(function(i){ if(st.v[i.getAttribute('data-i')]!==undefined) i.value = st.v[i.getAttribute('data-i')]; });
        var sl = $('input[data-stale]', card); if(sl && st.stale!==undefined) sl.value = st.stale;
      }
      simUpdate(card);
    });
  });
}
var SIMSTATE = {};
document.addEventListener('click', function(e){
  var b = e.target.closest('.hz-b');
  if(!b) return;
  hzCur = b.getAttribute('data-hz');
  LS.set('hz', hzCur);
  renderHz();
  var nb = $('.hz-b[aria-selected="true"]', b.closest('.hz'));
  if(nb) nb.focus();
});
document.addEventListener('keydown', function(e){
  var b = e.target.closest && e.target.closest('.hz-b');
  if(!b) return;
  var list = $$('.hz-b', b.parentNode), i = list.indexOf(b), n = -1;
  if(e.key==='ArrowRight') n = (i+1)%list.length;
  else if(e.key==='ArrowLeft') n = (i-1+list.length)%list.length;
  if(n>=0){ e.preventDefault(); list[n].click(); }
});
document.addEventListener('input', function(e){
  var card = e.target.closest && e.target.closest('[data-sim]');
  if(!card) return;
  var hid = card.getAttribute('data-sim');
  var st = SIMSTATE[hid] || (SIMSTATE[hid] = { v:{} , stale:0 });
  $$('input[data-i]', card).forEach(function(i){ st.v[i.getAttribute('data-i')] = i.value; });
  st.stale = $('input[data-stale]', card).value;
  simUpdate(card);
});

/* ---------- wide figures: scroll sideways on small screens instead of shrinking text ---------- */
$$('svg.diagram, svg.chart').forEach(function(svg){
  var vb = (svg.getAttribute('viewBox')||'').split(/\s+/).map(Number);
  var w = vb[2] || 640;
  var wrap = document.createElement('div');
  wrap.className = 'svg-scroll';
  wrap.setAttribute('tabindex','0');
  wrap.setAttribute('role','group');
  wrap.setAttribute('aria-label','ภาพประกอบ เลื่อนดูด้านข้างได้');
  svg.parentNode.insertBefore(wrap, svg);
  wrap.appendChild(svg);
  svg.style.minWidth = Math.round(w*0.82) + 'px';
});

/* ---------- start ---------- */
renderHz();
var first = parse((location.hash||'').replace('#',''));
route(first ? location.hash.replace('#','') : 'home', { silent:true });
if(first && first.view !== 'home'){
  /* deep link: stay at top, no extra scroll */
}
})();
</script>

</body>
</html>
