<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Goals Dashboard — 30-Day Athleticism Program</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Barlow+Condensed:wght@500;600;700&family=Barlow:wght@400;500;600;700&display=swap" rel="stylesheet">
<style>
:root{
  --base:#0E141C;
  --surface:#151D27;
  --raised:#1B2632;
  --line:#25313E;
  --line-soft:#1E2833;
  --chalk:#EEF3F7;
  --text:#DCE5ED;
  --muted:#8496A6;
  --dim:#5D6E7D;
  --signal:#FF6A1F;
  --signal-dim:rgba(255,106,31,.14);
  --cool:#45C8DE;
  --cool-dim:rgba(69,200,222,.14);
  --good:#5ED39B;
  --warn:#F0B429;
  --r:5px;
  --rail:236px;
  --fs:'Barlow',ui-sans-serif,system-ui,'Segoe UI',sans-serif;
  --fc:'Barlow Condensed','Barlow',ui-sans-serif,system-ui,sans-serif;
}
*{box-sizing:border-box;margin:0;padding:0}
html,body{height:100%}
body{
  background:var(--base);
  color:var(--text);
  font-family:var(--fs);
  font-size:15px;
  line-height:1.5;
  -webkit-font-smoothing:antialiased;
  background-image:
    radial-gradient(circle at 12% 8%, rgba(69,200,222,.05), transparent 42%),
    radial-gradient(circle at 88% 4%, rgba(255,106,31,.05), transparent 38%);
  background-attachment:fixed;
}
/* speckled rubber-floor texture, very quiet */
body::before{
  content:"";position:fixed;inset:0;pointer-events:none;z-index:0;opacity:.5;
  background-image:
    radial-gradient(rgba(255,255,255,.045) .6px, transparent .7px),
    radial-gradient(rgba(255,106,31,.05) .6px, transparent .7px);
  background-size:14px 14px, 31px 27px;
  background-position:0 0, 7px 11px;
}
button,input,select,textarea{font:inherit;color:inherit}
button{background:none;border:none;cursor:pointer}
:focus-visible{outline:2px solid var(--signal);outline-offset:2px;border-radius:3px}
.num{font-variant-numeric:tabular-nums;font-feature-settings:"tnum" 1}

/* ---------- shell ---------- */
.app{position:relative;z-index:1;display:flex;min-height:100%}
.rail{
  width:var(--rail);flex:0 0 var(--rail);border-right:1px solid var(--line-soft);
  padding:22px 16px 24px;position:sticky;top:0;height:100vh;display:flex;flex-direction:column;gap:26px;
  background:linear-gradient(180deg,rgba(21,29,39,.75),rgba(14,20,28,.4));backdrop-filter:blur(6px);
}
.brand{display:flex;align-items:center;gap:11px}
.brand .glyph{
  width:34px;height:34px;border:1.5px solid var(--signal);border-radius:var(--r);
  display:grid;place-items:center;color:var(--signal);font-family:var(--fc);font-weight:700;font-size:19px;
  background:var(--signal-dim);
}
.brand h1{font-family:var(--fc);font-size:20px;font-weight:600;letter-spacing:.3px;line-height:1}
.brand p{font-size:11.5px;color:var(--dim);letter-spacing:.2px;margin-top:2px}
.nav{display:flex;flex-direction:column;gap:2px}
.nav button{
  display:flex;align-items:center;gap:11px;padding:9px 11px;border-radius:var(--r);
  color:var(--muted);font-size:14.5px;font-weight:500;text-align:left;width:100%;
  transition:background .12s ease,color .12s ease;
}
.nav button:hover{background:var(--surface);color:var(--text)}
.nav button[aria-current="page"]{background:var(--raised);color:var(--chalk);box-shadow:inset 2px 0 0 var(--signal)}
.nav svg{width:17px;height:17px;flex:0 0 17px;stroke:currentColor;fill:none;stroke-width:1.7}
.rail-foot{margin-top:auto;display:flex;flex-direction:column;gap:10px}
.daychip{
  border:1px solid var(--line);border-radius:var(--r);padding:11px 12px;background:var(--surface);
}
.daychip .k{font-size:11px;color:var(--dim);letter-spacing:.4px}
.daychip .v{font-family:var(--fc);font-size:26px;line-height:1;color:var(--chalk);margin-top:3px}
.daychip .v small{font-size:14px;color:var(--muted);font-family:var(--fs)}
.trackbar{height:4px;border-radius:2px;background:var(--line);overflow:hidden;margin-top:9px}
.trackbar i{display:block;height:100%;background:var(--signal);border-radius:2px;transition:width .5s ease}
.ghostbtn{
  border:1px solid var(--line);border-radius:var(--r);padding:8px 10px;color:var(--muted);
  font-size:13px;font-weight:500;text-align:center;transition:border-color .12s,color .12s;
}
.ghostbtn:hover{border-color:var(--signal);color:var(--chalk)}

.main{flex:1;min-width:0;padding:26px 30px 120px;max-width:1180px}
.screen{display:none;animation:fade .18s ease both}
.screen.on{display:block}
@keyframes fade{from{opacity:0}to{opacity:1}}

.head{display:flex;align-items:flex-end;justify-content:space-between;gap:18px;margin-bottom:20px;flex-wrap:wrap}
.head h2{font-family:var(--fc);font-size:31px;font-weight:600;letter-spacing:.2px;line-height:1.05;color:var(--chalk)}
.head p{color:var(--muted);font-size:14px;margin-top:4px;max-width:62ch}

/* ---------- the wall (hero) ---------- */
.wall{
  border:1px solid var(--line);border-radius:var(--r);background:
    linear-gradient(180deg,var(--surface),rgba(14,20,28,.6));
  display:grid;grid-template-columns:minmax(220px,1fr) minmax(280px,1.35fr);gap:0;overflow:hidden;
}
.wall-read{padding:24px 26px;display:flex;flex-direction:column;justify-content:center;gap:2px}
.wall-read .lab{font-size:12.5px;color:var(--muted);letter-spacing:.3px}
.wall-read .big{
  font-family:var(--fc);font-weight:700;font-size:clamp(64px,11vw,104px);line-height:.86;color:var(--chalk);
  letter-spacing:-1px;display:flex;align-items:baseline;gap:8px;margin:6px 0 2px;
}
.wall-read .big span{font-size:24px;color:var(--muted);font-weight:500;letter-spacing:0}
.delta{display:inline-flex;align-items:center;gap:6px;font-size:13.5px;font-weight:600;padding:3px 9px;border-radius:20px;width:fit-content}
.delta.up{color:var(--good);background:rgba(94,211,155,.12)}
.delta.down{color:var(--signal);background:var(--signal-dim)}
.delta.flat{color:var(--muted);background:var(--line-soft)}
.wall-read .sub{font-size:13px;color:var(--dim);margin-top:12px;line-height:1.55;max-width:34ch}
.wall-vis{border-left:1px solid var(--line-soft);position:relative;min-height:250px;background:rgba(9,13,18,.35)}
.wall-vis svg{display:block;width:100%;height:100%}
.mark-line{transition:transform 1.1s cubic-bezier(.19,1,.22,1)}
@media (prefers-reduced-motion:reduce){.mark-line{transition:none}}

.strip{
  display:grid;grid-template-columns:repeat(4,1fr);border:1px solid var(--line);border-top:none;
  border-radius:0 0 var(--r) var(--r);background:var(--surface);
}
.strip .cell{padding:15px 18px;border-left:1px solid var(--line-soft)}
.strip .cell:first-child{border-left:none}
.strip .k{font-size:12px;color:var(--muted)}
.strip .v{font-family:var(--fc);font-size:29px;line-height:1.1;color:var(--chalk);margin-top:1px}
.strip .v small{font-size:13px;color:var(--dim);font-family:var(--fs);margin-left:3px}
.strip .d{font-size:12.5px;margin-top:2px;font-weight:600}
.strip .d.good{color:var(--good)}.strip .d.bad{color:var(--warn)}.strip .d.none{color:var(--dim);font-weight:400}

/* ---------- 30-day calendar strip ---------- */
.calwrap{margin-top:26px;border:1px solid var(--line);border-radius:var(--r);background:var(--surface);padding:18px 20px}
.calwrap h3,.panel h3{font-family:var(--fc);font-size:19px;font-weight:600;color:var(--chalk);letter-spacing:.2px}
.calwrap .note{font-size:12.5px;color:var(--dim);margin-top:3px}
.cal{display:grid;grid-template-columns:repeat(15,1fr);gap:5px;margin-top:14px}
.cal .d{
  aspect-ratio:1;border-radius:3px;border:1px solid var(--line);background:rgba(255,255,255,.02);
  display:grid;place-items:center;font-size:11px;color:var(--dim);position:relative;
  font-variant-numeric:tabular-nums;
}
.cal .d.rest{background:repeating-linear-gradient(45deg,transparent,transparent 3px,rgba(255,255,255,.045) 3px,rgba(255,255,255,.045) 6px)}
.cal .d.done{background:var(--signal);border-color:var(--signal);color:#160B04;font-weight:700}
.cal .d.today{border-color:var(--chalk);color:var(--chalk);box-shadow:0 0 0 1px var(--chalk)}
.cal .d.past:not(.done):not(.rest){border-color:var(--line);color:#46545F}
.legend{display:flex;gap:16px;margin-top:12px;font-size:12px;color:var(--dim);flex-wrap:wrap}
.legend i{width:10px;height:10px;border-radius:2px;display:inline-block;margin-right:6px;vertical-align:-1px}

/* ---------- panels & grid ---------- */
.grid2{display:grid;grid-template-columns:1fr 1fr;gap:16px;margin-top:16px}
.panel{border:1px solid var(--line);border-radius:var(--r);background:var(--surface);padding:18px 20px}
.panel .phead{display:flex;align-items:baseline;justify-content:space-between;gap:12px;margin-bottom:4px}
.panel .phead .meta{font-size:12.5px;color:var(--dim)}

/* ---------- session ---------- */
.sessbar{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:18px}
.pill{
  border:1px solid var(--line);border-radius:20px;padding:6px 14px;font-size:13.5px;color:var(--muted);
  font-weight:500;transition:.12s;
}
.pill:hover{color:var(--chalk);border-color:var(--dim)}
.pill[aria-pressed="true"]{background:var(--chalk);color:#0E141C;border-color:var(--chalk);font-weight:600}
.block{margin-top:22px}
.blockhead{display:flex;align-items:center;gap:10px;padding-bottom:8px;border-bottom:1px solid var(--line)}
.blockhead h4{font-family:var(--fc);font-size:17px;font-weight:600;color:var(--chalk);letter-spacing:.3px}
.blockhead .tag{font-size:11.5px;padding:2px 8px;border-radius:3px;font-weight:600;letter-spacing:.2px}
.tag.jump{background:var(--signal-dim);color:var(--signal)}
.tag.agility{background:var(--cool-dim);color:var(--cool)}
.tag.bw{background:rgba(238,243,247,.09);color:var(--chalk)}
.tag.risk{background:rgba(240,180,41,.14);color:var(--warn)}
.blockhead .hint{font-size:12.5px;color:var(--dim);margin-left:auto}

.ex{display:flex;align-items:flex-start;gap:13px;padding:13px 2px;border-bottom:1px solid var(--line-soft)}
.ex:last-child{border-bottom:none}
.tick{
  flex:0 0 21px;width:21px;height:21px;border:1.5px solid var(--dim);border-radius:4px;margin-top:2px;
  display:grid;place-items:center;transition:.14s;
}
.tick:hover{border-color:var(--chalk)}
.tick svg{width:12px;height:12px;stroke:#0E141C;stroke-width:3;fill:none;opacity:0;transition:opacity .12s}
.ex.done .tick{background:var(--signal);border-color:var(--signal)}
.ex.done .tick svg{opacity:1}
.ex.done .exname{color:var(--dim);text-decoration:line-through;text-decoration-color:var(--line)}
.exbody{flex:1;min-width:0}
.exname{font-weight:600;font-size:15px;color:var(--text);display:flex;align-items:center;gap:7px;flex-wrap:wrap}
.exmeta{font-size:12.5px;color:var(--muted);margin-top:2px}
.excue{font-size:12.5px;color:var(--dim);margin-top:4px;line-height:1.45;max-width:70ch}
.exright{display:flex;align-items:center;gap:8px;flex-wrap:wrap;justify-content:flex-end}
.prescr{font-family:var(--fc);font-size:20px;color:var(--chalk);white-space:nowrap}
.restbtn{border:1px solid var(--line);border-radius:20px;padding:4px 11px;font-size:12.5px;color:var(--muted);white-space:nowrap}
.restbtn:hover{border-color:var(--signal);color:var(--signal)}

.sets{display:flex;gap:7px;margin-top:9px;flex-wrap:wrap}
.setbox{display:flex;align-items:center;gap:4px;border:1px solid var(--line);border-radius:4px;padding:3px 6px;background:rgba(0,0,0,.2)}
.setbox label{font-size:10.5px;color:var(--dim);width:13px}
.setbox input{
  width:44px;background:none;border:none;font-size:13.5px;font-weight:600;color:var(--chalk);text-align:center;
  font-variant-numeric:tabular-nums;
}
.setbox input::placeholder{color:#3E4B57;font-weight:400}
.setbox .x{color:var(--dim);font-size:12px}
.setbox.filled{border-color:rgba(255,106,31,.45);background:var(--signal-dim)}

.counter{display:flex;align-items:center;gap:0;border:1px solid var(--line);border-radius:var(--r);overflow:hidden;width:fit-content}
.counter button{padding:6px 13px;font-size:16px;color:var(--muted);line-height:1}
.counter button:hover{background:var(--raised);color:var(--chalk)}
.counter .val{padding:6px 14px;font-family:var(--fc);font-size:20px;color:var(--chalk);border-left:1px solid var(--line);border-right:1px solid var(--line);min-width:56px;text-align:center}

.sessfoot{display:flex;align-items:center;gap:14px;margin-top:26px;padding-top:18px;border-top:1px solid var(--line);flex-wrap:wrap}
.btn{
  background:var(--signal);color:#150800;font-weight:600;font-size:14.5px;padding:10px 20px;border-radius:var(--r);
  transition:filter .12s;
}
.btn:hover{filter:brightness(1.1)}
.btn.sec{background:none;border:1px solid var(--line);color:var(--muted)}
.btn.sec:hover{border-color:var(--chalk);color:var(--chalk);filter:none}
.ring{--p:0;width:46px;height:46px;border-radius:50%;display:grid;place-items:center;flex:0 0 46px;
  background:conic-gradient(var(--signal) calc(var(--p)*1%), var(--line) 0);}
.ring i{width:38px;height:38px;border-radius:50%;background:var(--base);display:grid;place-items:center;
  font-size:12px;font-weight:700;color:var(--chalk);font-style:normal;font-variant-numeric:tabular-nums}

/* ---------- charts ---------- */
.chart{width:100%;height:190px;display:block;margin-top:6px;overflow:visible}
.chart .grid{stroke:var(--line-soft);stroke-width:1}
.chart .axis{fill:var(--dim);font-size:10.5px;font-family:var(--fs)}
.chart .ln{fill:none;stroke-width:2;stroke-linecap:round;stroke-linejoin:round}
.chart .dot{stroke:var(--base);stroke-width:1.5}
.empty{
  border:1px dashed var(--line);border-radius:var(--r);padding:26px 20px;text-align:center;color:var(--dim);
  font-size:13.5px;margin-top:10px;line-height:1.6;
}
.empty b{display:block;color:var(--muted);font-size:14.5px;font-weight:600;margin-bottom:4px}

/* ---------- tables & forms ---------- */
table{width:100%;border-collapse:collapse;font-size:13.5px;margin-top:12px}
th{
  text-align:left;font-size:12px;color:var(--muted);font-weight:600;padding:0 10px 8px 0;
  border-bottom:1px solid var(--line);white-space:nowrap;
}
td{padding:9px 10px 9px 0;border-bottom:1px solid var(--line-soft);color:var(--text);font-variant-numeric:tabular-nums}
tbody tr:last-child td{border-bottom:none}
td.mut{color:var(--muted)}
.form{display:grid;grid-template-columns:repeat(auto-fit,minmax(140px,1fr));gap:12px;margin-top:14px}
.field label{display:block;font-size:12px;color:var(--muted);margin-bottom:5px}
.field input,.field select,.field textarea{
  width:100%;background:rgba(0,0,0,.25);border:1px solid var(--line);border-radius:4px;padding:9px 10px;
  font-size:14px;color:var(--chalk);font-variant-numeric:tabular-nums;
}
.field input:focus,.field select:focus,.field textarea:focus{border-color:var(--signal);outline:none}
.field .help{font-size:11.5px;color:var(--dim);margin-top:4px}

/* ---------- rest timer dock ---------- */
.dock{
  position:fixed;left:50%;bottom:22px;transform:translate(-50%,140%);z-index:60;
  display:flex;align-items:center;gap:14px;padding:11px 14px 11px 12px;border-radius:44px;
  background:var(--raised);border:1px solid var(--line);box-shadow:0 12px 40px rgba(0,0,0,.55);
  transition:transform .28s cubic-bezier(.19,1,.22,1);
}
.dock.on{transform:translate(-50%,0)}
.dock .tring{--p:100;width:44px;height:44px;border-radius:50%;flex:0 0 44px;display:grid;place-items:center;
  background:conic-gradient(var(--cool) calc(var(--p)*1%), var(--line) 0)}
.dock .tring i{width:36px;height:36px;border-radius:50%;background:var(--raised);display:grid;place-items:center;
  font-family:var(--fc);font-size:15px;color:var(--chalk);font-style:normal;font-variant-numeric:tabular-nums}
.dock .lbl{font-size:13px;color:var(--muted);max-width:180px;line-height:1.35}
.dock .lbl b{display:block;color:var(--chalk);font-size:13.5px;font-weight:600}
.dock button{font-size:13px;color:var(--muted);padding:6px 10px;border:1px solid var(--line);border-radius:20px}
.dock button:hover{color:var(--chalk);border-color:var(--dim)}

.toast{
  position:fixed;left:50%;bottom:96px;transform:translate(-50%,20px);z-index:70;opacity:0;pointer-events:none;
  background:var(--chalk);color:#0E141C;font-weight:600;font-size:13.5px;padding:9px 18px;border-radius:20px;
  transition:opacity .2s,transform .2s;
}
.toast.on{opacity:1;transform:translate(-50%,0)}

/* ---------- program reference ---------- */
.acc{border:1px solid var(--line);border-radius:var(--r);background:var(--surface);margin-bottom:10px;overflow:hidden}
.acc>button{width:100%;display:flex;align-items:center;gap:12px;padding:14px 18px;text-align:left}
.acc>button:hover{background:var(--raised)}
.acc .idx{font-family:var(--fc);font-size:15px;color:var(--signal);width:22px;flex:0 0 22px}
.acc .ttl{font-family:var(--fc);font-size:18px;color:var(--chalk);letter-spacing:.2px}
.acc .cap{font-size:12.5px;color:var(--dim);margin-left:auto;text-align:right}
.acc .body{padding:0 18px 18px;display:none}
.acc.open .body{display:block}
.acc .chev{width:14px;height:14px;stroke:var(--dim);fill:none;stroke-width:2;transition:transform .16s}
.acc.open .chev{transform:rotate(90deg)}
.drill{padding:11px 0;border-bottom:1px solid var(--line-soft)}
.drill:last-child{border-bottom:none}
.drill .dn{font-weight:600;font-size:14.5px;color:var(--text)}
.drill .dp{font-size:13px;color:var(--signal);font-weight:600;margin-top:2px;font-variant-numeric:tabular-nums}
.drill .dd{font-size:13px;color:var(--muted);margin-top:4px;line-height:1.55;max-width:74ch}

.callout{border-left:2px solid var(--warn);background:rgba(240,180,41,.06);padding:12px 15px;border-radius:0 4px 4px 0;
  font-size:13.5px;color:var(--muted);line-height:1.6;margin-top:14px}
.callout b{color:var(--warn);font-weight:600}

/* ---------- mobile ---------- */
.mobnav{display:none}
@media(max-width:900px){
  .grid2{grid-template-columns:1fr}
  .wall{grid-template-columns:1fr}
  .wall-vis{border-left:none;border-top:1px solid var(--line-soft);min-height:190px}
  .strip{grid-template-columns:1fr 1fr}
  .strip .cell:nth-child(3){border-left:none}
  .strip .cell:nth-child(n+3){border-top:1px solid var(--line-soft)}
  .cal{grid-template-columns:repeat(10,1fr)}
}
@media(max-width:760px){
  .rail{display:none}
  .main{padding:18px 16px 130px}
  .head h2{font-size:26px}
  .mobnav{
    display:grid;grid-template-columns:repeat(4,1fr);position:fixed;left:0;right:0;bottom:0;z-index:50;
    background:rgba(21,29,39,.96);backdrop-filter:blur(10px);border-top:1px solid var(--line);
    padding:6px 4px calc(6px + env(safe-area-inset-bottom));
  }
  .mobnav button{display:flex;flex-direction:column;align-items:center;gap:3px;padding:7px 2px;color:var(--dim);font-size:10.5px;font-weight:600}
  .mobnav button[aria-current="page"]{color:var(--signal)}
  .mobnav svg{width:19px;height:19px;stroke:currentColor;fill:none;stroke-width:1.7}
  .dock{bottom:80px;left:12px;right:12px;transform:translateY(200%);width:auto}
  .dock.on{transform:translateY(0)}
  .toast{bottom:150px}
  .ex{flex-wrap:wrap}
  .exright{width:100%;justify-content:flex-start;padding-left:34px}
}
</style>
</head>
<body>

<div class="app">
  <aside class="rail">
    <div class="brand">
      <div class="glyph">V</div>
      <div>
        <h1>Vertical</h1>
        <p>30-day athleticism block</p>
      </div>
    </div>

    <nav class="nav" id="nav"></nav>

    <div class="rail-foot">
      <div class="daychip">
        <div class="k">Day of block</div>
        <div class="v"><span id="dayNum" class="num">1</span><small> / 30</small></div>
        <div class="trackbar"><i id="dayBar" style="width:3%"></i></div>
      </div>
      <button class="ghostbtn" data-go="settings">Settings &amp; data</button>
    </div>
  </aside>

  <main class="main">

    <!-- ============ OVERVIEW ============ -->
    <section class="screen on" id="s-overview">
      <div class="head">
        <div>
          <h2 id="greet">Where you stand</h2>
          <p>Your jump is force divided by mass. Both sides of that equation are on this page.</p>
        </div>
      </div>

      <div class="wall">
        <div class="wall-read">
          <div class="lab">Standing vertical jump</div>
          <div class="big"><span id="vertBig" class="num">—</span><span id="vertUnit">cm</span></div>
          <div id="vertDelta" class="delta flat">No baseline yet</div>
          <p class="sub" id="vertSub">Measure your standing reach and your best jump touch, then log the difference. Everything on this dashboard keys off that one number.</p>
        </div>
        <div class="wall-vis" id="wallVis"></div>
      </div>

      <div class="strip" id="strip"></div>

      <div class="calwrap">
        <h3>The block</h3>
        <p class="note" id="calNote">Thirty days, five sessions a week. Thursday is active recovery, Sunday is off.</p>
        <div class="cal" id="cal"></div>
        <div class="legend">
          <span><i style="background:var(--signal)"></i>Session logged</span>
          <span><i style="border:1px solid var(--line);background:repeating-linear-gradient(45deg,transparent,transparent 3px,rgba(255,255,255,.06) 3px,rgba(255,255,255,.06) 6px)"></i>Rest / recovery</span>
          <span><i style="border:1px solid var(--chalk)"></i>Today</span>
          <span><i style="border:1px solid var(--line)"></i>Missed or upcoming</span>
        </div>
      </div>

      <div class="grid2">
        <div class="panel">
          <div class="phead"><h3>Body weight</h3><span class="meta" id="wMeta"></span></div>
          <div id="cWeight"></div>
        </div>
        <div class="panel">
          <div class="phead"><h3>Vertical jump</h3><span class="meta">Standing · approach</span></div>
          <div id="cVert"></div>
        </div>
      </div>

      <div class="grid2">
        <div class="panel">
          <div class="phead"><h3>Leg press top set</h3><span class="meta">Heaviest working set logged</span></div>
          <div id="cPress"></div>
        </div>
        <div class="panel">
          <div class="phead"><h3>This week</h3><span class="meta" id="weekMeta"></span></div>
          <div id="weekSummary"></div>
        </div>
      </div>
    </section>

    <!-- ============ TODAY ============ -->
    <section class="screen" id="s-today">
      <div class="head">
        <div>
          <h2 id="todayTitle">Today</h2>
          <p id="todaySub"></p>
        </div>
        <div style="display:flex;align-items:center;gap:12px">
          <div class="ring" id="progRing" style="--p:0"><i class="num">0%</i></div>
        </div>
      </div>

      <div class="sessbar" id="daySwitch"></div>
      <div id="sessionBody"></div>

      <div class="sessfoot">
        <button class="btn" id="saveSession">Save session</button>
        <button class="btn sec" id="clearSession">Clear today</button>
        <span style="font-size:13px;color:var(--dim)" id="saveHint">Everything saves as you tap. This just marks the day done.</span>
      </div>
    </section>

    <!-- ============ PROGRESS ============ -->
    <section class="screen" id="s-progress">
      <div class="head">
        <div>
          <h2>Progress</h2>
          <p>Trends beat single readings. A weight jump of a kilo overnight is water, not fat.</p>
        </div>
      </div>
      <div class="grid2">
        <div class="panel"><div class="phead"><h3>Body weight</h3><span class="meta">kg</span></div><div id="pWeight"></div></div>
        <div class="panel"><div class="phead"><h3>Waist</h3><span class="meta">cm at the navel</span></div><div id="pWaist"></div></div>
      </div>
      <div class="grid2">
        <div class="panel"><div class="phead"><h3>Vertical jump</h3><span class="meta">standing · approach</span></div><div id="pVert"></div></div>
        <div class="panel"><div class="phead"><h3>Broad jump</h3><span class="meta">cm, two-foot standing</span></div><div id="pBroad"></div></div>
      </div>
      <div class="grid2">
        <div class="panel"><div class="phead"><h3>Key lifts</h3><span class="meta">top set each session</span></div><div id="pLifts"></div></div>
        <div class="panel"><div class="phead"><h3>Session history</h3><span class="meta" id="histMeta"></span></div><div id="pHist"></div></div>
      </div>
    </section>

    <!-- ============ MEASURE ============ -->
    <section class="screen" id="s-measure">
      <div class="head">
        <div>
          <h2>Measure</h2>
          <p>Same time of day, same shoes, same warm-up. Otherwise you are comparing two different tests.</p>
        </div>
      </div>

      <div class="panel">
        <h3>Add a reading</h3>
        <p style="font-size:13px;color:var(--dim);margin-top:3px">Fill in what you measured. Blank fields are skipped, so a weight-only entry is fine.</p>
        <div class="form" id="measureForm">
          <div class="field"><label for="mDate">Date</label><input type="date" id="mDate"></div>
          <div class="field"><label for="mWeight">Body weight (kg)</label><input type="number" step="0.1" id="mWeight" placeholder="99.0"><div class="help">Morning, after the toilet</div></div>
          <div class="field"><label for="mWaist">Waist (cm)</label><input type="number" step="0.5" id="mWaist" placeholder="—"><div class="help">At the navel, normal exhale</div></div>
          <div class="field"><label for="mVert">Standing vertical (cm)</label><input type="number" step="0.5" id="mVert" placeholder="—"><div class="help">Jump touch minus standing reach</div></div>
          <div class="field"><label for="mApp">Approach vertical (cm)</label><input type="number" step="0.5" id="mApp" placeholder="—"><div class="help">Two-step run-in</div></div>
          <div class="field"><label for="mBroad">Broad jump (cm)</label><input type="number" step="1" id="mBroad" placeholder="—"><div class="help">Line to rear heel</div></div>
          <div class="field"><label for="mSleep">Sleep (h/night)</label><input type="number" step="0.5" id="mSleep" placeholder="—"></div>
          <div class="field"><label for="mEnergy">Energy (1–5)</label><select id="mEnergy"><option value="">—</option><option>1</option><option>2</option><option>3</option><option>4</option><option>5</option></select></div>
        </div>
        <div style="margin-top:16px;display:flex;gap:10px;flex-wrap:wrap">
          <button class="btn" id="addMeasure">Save reading</button>
          <button class="btn sec" id="markBaseline">Save as Day 0 baseline</button>
        </div>
      </div>

      <div class="panel" style="margin-top:16px">
        <div class="phead"><h3>Baseline against now</h3><span class="meta" id="cmpMeta"></span></div>
        <div id="cmpTable"></div>
      </div>

      <div class="panel" style="margin-top:16px">
        <div class="phead"><h3>All readings</h3><span class="meta" id="mCount"></span></div>
        <div id="mTable"></div>
      </div>

      <div class="panel" style="margin-top:16px">
        <h3>How to run each test</h3>
        <div id="testProtocols"></div>
      </div>
    </section>

    <!-- ============ PROGRAM ============ -->
    <section class="screen" id="s-program">
      <div class="head">
        <div>
          <h2>Program</h2>
          <p>The reference behind every session: what changes each week, the jump dosage, and the movement drills.</p>
        </div>
      </div>
      <div id="progWeeks"></div>
      <h3 style="font-family:var(--fc);font-size:20px;color:var(--chalk);margin:26px 0 10px">Jump dosage</h3>
      <div class="panel" id="jumpTable"></div>
      <h3 style="font-family:var(--fc);font-size:20px;color:var(--chalk);margin:26px 0 10px">Agility and basketball movement</h3>
      <div id="drillList"></div>
      <div class="callout">
        <b>Get eyes on you for these.</b> Barbell back squat — set the rack safeties every set and have gym staff watch your first three sessions. Barbell bench press — spotter or dumbbells, no exceptions. Dumbbell RDL — film one set from the side and check your back stays flat. Every jump landing — quiet, knees out, hold two seconds.
      </div>
    </section>

    <!-- ============ SETTINGS ============ -->
    <section class="screen" id="s-settings">
      <div class="head">
        <div>
          <h2>Settings &amp; data</h2>
          <p>Everything lives on this device. Export a copy before you clear anything.</p>
        </div>
      </div>
      <div class="panel">
        <h3>Block setup</h3>
        <div class="form">
          <div class="field"><label for="setName">Your name</label><input id="setName" placeholder="Athlete"></div>
          <div class="field"><label for="setStart">Day 1 of the block</label><input type="date" id="setStart"><div class="help">Sets the calendar and week number</div></div>
          <div class="field"><label for="setHeight">Height (cm)</label><input type="number" id="setHeight" placeholder="183"></div>
          <div class="field"><label for="setReach">Standing reach (cm)</label><input type="number" id="setReach" placeholder="—"><div class="help">Used to show jump touch height</div></div>
        </div>
        <div style="margin-top:16px"><button class="btn" id="saveSettings">Save setup</button></div>
      </div>
      <div class="panel" style="margin-top:16px">
        <h3>Your data</h3>
        <p style="font-size:13.5px;color:var(--muted);margin-top:6px;line-height:1.6">Export writes a JSON file you can keep or move to another device. Import replaces what is here now.</p>
        <div style="margin-top:14px;display:flex;gap:10px;flex-wrap:wrap">
          <button class="btn sec" id="exportBtn">Export data</button>
          <button class="btn sec" id="importBtn">Import data</button>
          <input type="file" id="importFile" accept="application/json" hidden>
          <button class="btn sec" id="resetBtn" style="border-color:rgba(255,106,31,.4);color:var(--signal)">Erase everything</button>
        </div>
        <p style="font-size:12.5px;color:var(--dim);margin-top:12px" id="storeMode"></p>
      </div>
    </section>

  </main>
</div>

<nav class="mobnav" id="mobnav"></nav>

<div class="dock" id="dock">
  <div class="tring" id="tring" style="--p:100"><i id="tval">90</i></div>
  <div class="lbl"><b id="tname">Rest</b><span id="tsub">Stay off your feet</span></div>
  <button id="tAdd">+30s</button>
  <button id="tStop">Stop</button>
</div>

<div class="toast" id="toast"></div>

<script>
"use strict";

/* ============================================================
   STORAGE — window.storage, then localStorage, then memory
   ============================================================ */
const KEY = "vertical.dashboard.v1";
const mem = {};
let storeMode = "memory (this session only)";

const Store = {
  async get(k){
    if (typeof window.storage !== "undefined" && window.storage) {
      try { const r = await window.storage.get(k); if (r && r.value) { storeMode="synced storage"; return JSON.parse(r.value); } }
      catch(e){ /* key missing or unavailable */ }
    }
    try { const v = window.localStorage.getItem(k); if (v){ storeMode="this browser"; return JSON.parse(v); } storeMode="this browser"; }
    catch(e){}
    return mem[k] || null;
  },
  async set(k,v){
    const s = JSON.stringify(v);
    if (typeof window.storage !== "undefined" && window.storage) {
      try { const r = await window.storage.set(k,s); if (r){ storeMode="synced storage"; mem[k]=v; return true; } } catch(e){}
    }
    try { window.localStorage.setItem(k,s); storeMode="this browser"; mem[k]=v; return true; } catch(e){}
    mem[k]=v; storeMode="memory (this session only)"; return true;
  }
};

/* ============================================================
   PROGRAM DATA
   ============================================================ */
const WEEK_RULES = {
  1:{name:"Foundation",  main:{sets:3,reps:"10"},   acc:{sets:2}, contacts:40, rpe:"RPE 5–6 · four reps left in the tank", note:"Learn the movements. It should feel easy."},
  2:{name:"Build",       main:{sets:3,reps:"8–10"}, acc:{sets:3}, contacts:55, rpe:"RPE 6–7 · add 2.5–5 kg where reps were easy", note:"Barbell squat enters with an empty bar."},
  3:{name:"Intensify",   main:{sets:4,reps:"6–8"},  acc:{sets:3}, contacts:65, rpe:"RPE 7–8 · two reps left in the tank", note:"Heaviest week. Agility moves to 85–90% speed."},
  4:{name:"Performance", main:{sets:3,reps:"5–6"},  acc:{sets:2}, contacts:40, rpe:"Heavy but fewer sets · drive every rep fast", note:"Sharpen, don't grind. Retest at the end."}
};

const DAYS = {
  1:{ name:"Lower strength + jumps", focus:"Legs and vertical", blocks:[
    {t:"Warm-up", tag:null, ex:[
      {id:"d1w1",n:"Bike, easy",p:"5 min",cue:"Conversational effort. You should be able to hold a sentence."},
      {id:"d1w2",n:"Ankle rockers",p:"2 × 10 / side",bw:1,cue:"Knee travels over the toes, heel stays flat on the floor."},
      {id:"d1w3",n:"Bodyweight squat",p:"2 × 10",bw:1,cue:"Slow, full range. This is the pattern rehearsal for the leg press."},
      {id:"d1w4",n:"Glute bridge",p:"2 × 12",bw:1,cue:"Squeeze one second at the top."},
      {id:"d1w5",n:"Calf raise",p:"2 × 15",bw:1,cue:"Full stretch at the bottom, prepares the Achilles for pogos."}
    ]},
    {t:"Jump block", tag:"jump", hint:"Fresh legs only. Long rests.", ex:[
      {id:"d1j1",n:"Snap-down to stick",p:"3 × 5",bw:1,rest:45,cue:"Arms overhead, drop hard into athletic stance. Mid-foot, knees out, freeze two seconds. This teaches landing."},
      {id:"d1j2",n:"Pogo hops",p:"3 × 8",bw:1,rest:45,cue:"Stiff ankles, minimal knee bend, quiet contacts, fast off the floor."},
      {id:"d1j3",n:"Countermovement jump",p:"3 × 3",bw:1,rest:90,contacts:1,cue:"Maximum effort every rep. Stick every landing. If the last jump is lower than the first, you did too many."}
    ]},
    {t:"Strength", tag:null, ex:[
      {id:"d1s1",n:"Leg press",m:"TRUE SD1003",role:"main",rest:120,log:1,cue:"Three seconds down, no bounce, drive up fast. Depth is wherever your lower back stays flat on the pad."},
      {id:"d1s2",n:"Dumbbell goblet squat",role:"main",rest:90,log:1,cue:"One dumbbell at chest height, elbows inside the knees at the bottom, torso tall."},
      {id:"d1s3",n:"Horizontal leg curl",m:"TRUE FUSE-1800",role:"acc",reps:"10–12",rest:75,log:1,cue:"One second to curl, three seconds to return. The slow return is the whole point."},
      {id:"d1s4",n:"Calf press",m:"on the leg press",role:"acc",reps:"12–15",rest:60,log:1,cue:"Two-second pause at full stretch. This is your last fifteen centimetres of jump."},
      {id:"d1s5",n:"Cable pallof press",role:"acc",reps:"10 / side",rest:45,log:1,cue:"Side-on to the cable, press out and hold two seconds. Resist the rotation — that is the exercise."}
    ]},
    {t:"Conditioning", tag:null, ex:[
      {id:"d1c1",n:"Treadmill incline walk",p:"12 min · 10–12% · 4.5–5.5 km/h",cue:"Hands off the handrails. Low impact, high energy cost — your best fat-loss tool at this bodyweight."}
    ]},
    {t:"Cool-down", tag:null, ex:[
      {id:"d1x1",n:"Easy bike, then calf, hip flexor and hamstring stretch",p:"6 min",cue:"Thirty seconds per stretch, breathe out into it."}
    ]}
  ]},

  2:{ name:"Upper strength + conditioning", focus:"Push, pull, engine", blocks:[
    {t:"Warm-up", ex:[
      {id:"d2w1",n:"Elliptical, easy",p:"5 min",cue:"Use the arms."},
      {id:"d2w2",n:"Lat pulldown, very light",p:"2 × 12",cue:"Pattern only. Feel the shoulder blades move before you load it."},
      {id:"d2w3",n:"Wall slides",p:"2 × 10",bw:1,cue:"Lower back and arms stay in contact with the wall."}
    ]},
    {t:"Strength", ex:[
      {id:"d2s1",n:"Lat pulldown",m:"TRUE FUSE-1100",role:"main",rest:90,log:1,cue:"Thighs locked under the pads, chest tall, drive the elbows down and back to the collarbone."},
      {id:"d2s2",n:"Machine chest press",role:"main",rest:90,log:1,cue:"Handles at mid-chest, shoulder blades pinned back, control the return."},
      {id:"d2s3",n:"Seated cable row",role:"main",rest:90,log:1,cue:"Chest tall, pull to the belly button, no shrugging."},
      {id:"d2s4",n:"Machine shoulder press",role:"acc",reps:"10",rest:90,log:1,cue:"Ribs down. Don't arch the lower back to finish a rep."},
      {id:"d2s5",n:"Cable face pull",role:"acc",reps:"15",rest:45,log:1,cue:"Pull to the forehead, elbows high. Pure shooter's-shoulder insurance."},
      {id:"d2s6",n:"Dumbbell farmer carry",role:"acc",reps:"30 m",rest:60,log:1,cue:"Walk tall, shoulders back, don't lean. Grip, core and posture in one."}
    ]},
    {t:"Movement", tag:"agility", hint:"Technique speed only today.", ex:[
      {id:"d2m1",n:"Lateral shuffle to a stick",p:"4 × 5 m each way",bw:1,rest:45,cue:"Hips low, feet never cross, push off the trailing foot, stop dead and hold."},
      {id:"d2m2",n:"Jog into a three-step stop",p:"4 × 8 m",bw:1,rest:45,cue:"Sink low, chest over hips, freeze two seconds. Stopping is what lets you cut."}
    ]},
    {t:"Conditioning", ex:[
      {id:"d2c1",n:"Bike intervals",p:"8 × 20 s hard / 70 s easy",cue:"Hard means you cannot talk. Zero landing impact, real first-step carryover."}
    ]},
    {t:"Cool-down", ex:[{id:"d2x1",n:"Easy bike, then chest, lat and shoulder stretch",p:"6 min",cue:"Nasal breathing, slow exhale."}]}
  ]},

  3:{ name:"Athletic lower + agility", focus:"Single leg, cutting, jumps", blocks:[
    {t:"Warm-up", ex:[
      {id:"d3w1",n:"Bike, easy",p:"5 min",cue:"Easy."},
      {id:"d3w2",n:"Leg swings, front and side",p:"2 × 10 / side",bw:1,cue:"Controlled, not ballistic."},
      {id:"d3w3",n:"Walking lunge",p:"2 × 8 / side",bw:1,cue:"Tall torso, knee tracks over the foot."},
      {id:"d3w4",n:"Ankle rockers",p:"2 × 10 / side",bw:1,cue:"Heel down."}
    ]},
    {t:"Jump block", tag:"jump", hint:"Quality over count.", ex:[
      {id:"d3j1",n:"Pogo hops",p:"3 × 10",bw:1,rest:45,cue:"Quiet and fast. If they get loud, stop the set."},
      {id:"d3j2",n:"Lateral hop to a stick",p:"3 × 4 / side",bw:1,rest:60,contacts:1,cue:"Land single-leg, knee out over the toes, freeze two seconds before the next rep."},
      {id:"d3j3",n:"Approach jump",p:"3 × 3",bw:1,rest:90,contacts:1,cue:"Two-step run-in, maximum effort, absorb the landing. This is the game-realistic jump."}
    ]},
    {t:"Agility block", tag:"agility", hint:"Court or corridor — not between machines.", ex:[
      {id:"d3a1",n:"Athletic stance and snap-down",p:"3 × 5",bw:1,rest:45,cue:"Freeze in the position every cut and landing passes through."},
      {id:"d3a2",n:"Deceleration ladder",p:"4 reps",bw:1,rest:60,cue:"Week 1–2: jog 8 m, stop in three steps. Week 3–4: 75% run, stop in two."},
      {id:"d3a3",n:"Explosive first step",p:"5 × 5 m",bw:1,rest:60,cue:"Push the back foot into the floor and go. No false step backwards — that costs you two tenths."},
      {id:"d3a4",n:"45° cut drill",p:"4 / side",bw:1,rest:60,cue:"Run 5 m, plant the outside foot hard, push off it and accelerate away at an angle."}
    ]},
    {t:"Strength", ex:[
      {id:"d3s1",n:"Dumbbell split squat",role:"main",reps:"8 / leg",rest:75,log:1,cue:"Feet two shoe-lengths apart, back knee straight down, drive through the front heel."},
      {id:"d3s2",n:"Dumbbell Romanian deadlift",role:"main",risk:1,rest:90,log:1,cue:"Hips back not down, dumbbells close to the thighs, flat back, three seconds down. Stop at a strong hamstring stretch."},
      {id:"d3s3",n:"Horizontal leg curl",role:"acc",reps:"12",rest:60,log:1,cue:"Slow return."},
      {id:"d3s4",n:"Calf press",role:"acc",reps:"12",rest:60,log:1,cue:"Pause at the stretch."},
      {id:"d3s5",n:"Side plank",role:"acc",reps:"30 s / side",rest:45,bw:1,cue:"Straight line ear to ankle, hips high."}
    ]},
    {t:"Conditioning", ex:[{id:"d3c1",n:"Treadmill incline walk",p:"10 min",cue:"10–12% incline, steady."}]},
    {t:"Cool-down", ex:[{id:"d3x1",n:"Easy bike, then quad, hip and calf stretch",p:"6 min",cue:"Thirty-second holds."}]}
  ]},

  4:{ name:"Upper + full-body conditioning", focus:"Press, pull, engine", blocks:[
    {t:"Warm-up", ex:[
      {id:"d4w1",n:"Elliptical, light pulldowns, wall slides",p:"8 min",cue:"Same as Day 2."}
    ]},
    {t:"Strength", ex:[
      {id:"d4s1",n:"Dumbbell incline press",m:"bench at 30°",role:"main",rest:90,log:1,cue:"Control the descent. Dumbbells over the barbell here — no spotter needed."},
      {id:"d4s2",n:"Lat pulldown, wider grip",role:"main",rest:90,log:1,cue:"Full stretch at the top of every rep."},
      {id:"d4s3",n:"Machine shoulder press",role:"main",rest:90,log:1,cue:"Seat set so the handles start at shoulder height."},
      {id:"d4s4",n:"Single-arm dumbbell row",role:"acc",reps:"10 / side",rest:60,log:1,cue:"Hand on the bench, flat back, pull to the hip."},
      {id:"d4s5",n:"Cable crossover fly",role:"acc",reps:"12",rest:60,log:1,cue:"Slight elbow bend held throughout, no bouncing out of the stretch."},
      {id:"d4s6",n:"Cable woodchop",role:"acc",reps:"10 / side",rest:45,log:1,cue:"Rotate through the hips, not the lower back. This is your spin move's engine."}
    ]},
    {t:"Conditioning circuit", tag:null, hint:"3 rounds · 90 s between rounds", ex:[
      {id:"d4c1",n:"Spin bike, hard",p:"3 × 60 s",cue:"Sustainable-hard, not all-out."},
      {id:"d4c2",n:"Dumbbell farmer carry",p:"3 × 30 m",cue:"Tall posture the whole way."},
      {id:"d4c3",n:"Treadmill incline walk",p:"3 × 2 min",cue:"Your recovery inside the circuit."}
    ]},
    {t:"Cool-down", ex:[{id:"d4x1",n:"Easy bike and full upper-body stretch",p:"6 min",cue:"Slow breathing."}]}
  ]},

  5:{ name:"Full body + basketball movement", focus:"Play-ready", blocks:[
    {t:"Warm-up", ex:[
      {id:"d5w1",n:"Bike, leg swings, bodyweight squats, calf raises",p:"8 min",cue:"Same as Day 1."}
    ]},
    {t:"Basketball movement", tag:"agility", hint:"The point of this day. Full recovery between reps.", ex:[
      {id:"d5m1",n:"Spin move progression",p:"5 / direction",bw:1,rest:60,cue:"Stay low through the whole turn — rising up kills the move. Chin and eyes lead, tight pivot, drive out off the outside leg."},
      {id:"d5m2",n:"Shuffle into a sprint",p:"4 / side",bw:1,rest:60,cue:"Shuffle 4 m, turn the hips, sprint 6 m. This is a closeout and recovery."},
      {id:"d5m3",n:"Sprint, stop, change direction",p:"4 reps",bw:1,rest:90,cue:"Sprint 5 m, stop in two or three steps, explode back the other way."},
      {id:"d5m4",n:"Jump, land, immediate sprint",p:"4 reps",bw:1,rest:90,contacts:1,cue:"Rebound, absorb, go. Landing well is re-acceleration."}
    ]},
    {t:"Jump block", tag:"jump", ex:[
      {id:"d5j1",n:"Countermovement jump",p:"3 × 3",bw:1,rest:90,contacts:1,cue:"Maximum intent, stick the landing."}
    ]},
    {t:"Strength", ex:[
      {id:"d5s1",n:"Leg press",role:"main",rest:120,log:1,cue:"Fast concentric. Intent to accelerate is what transfers to your jump."},
      {id:"d5s2",n:"Lat pulldown",role:"main",rest:90,log:1,cue:"Controlled both ways."},
      {id:"d5s3",n:"Goblet squat, or barbell squat from week 2",role:"main",risk:1,rest:90,log:1,cue:"If you use the barbell: safeties set every set, empty bar for the first two sessions."},
      {id:"d5s4",n:"Machine chest press",role:"acc",reps:"10",rest:75,log:1,cue:"Blades pinned."},
      {id:"d5s5",n:"Horizontal leg curl",role:"acc",reps:"10",rest:60,log:1,cue:"Slow return."},
      {id:"d5s6",n:"Cable pallof press",role:"acc",reps:"10 / side",rest:45,log:1,cue:"Two-second hold, resist the twist."}
    ]},
    {t:"Conditioning", ex:[{id:"d5c1",n:"Elliptical or incline walk, steady",p:"12 min",cue:"Conversational-hard."}]},
    {t:"Cool-down", ex:[{id:"d5x1",n:"Full-body stretch and 5 min easy bike",p:"8 min",cue:"Longer holds today."}]}
  ]}
};

const SCHEDULE = {1:1, 2:2, 3:3, 4:"recovery", 5:4, 6:5, 0:"rest"}; // JS getDay(): 0=Sun

const DRILLS = [
  {g:"Foundations — every week, Days 3 and 5", items:[
    {n:"Athletic stance and snap-down", p:"3 × 5 · rest 45 s", d:"Stand tall, drop fast into a quarter-squat: feet shoulder-width, hips back, chest over toes, eyes up. Freeze two seconds. Every slide, cut and landing passes through this position."},
    {n:"Lateral shuffle to a stick", p:"4 × 5 m each way · rest 45 s", d:"Stay low, feet never cross, push off the trailing foot, stop dead at the marker. Transfers to defensive slides and closeouts."},
    {n:"Deceleration ladder", p:"4 reps · rest 60 s", d:"Week 1: jog 8 m, stop in three steps, hold two seconds. Week 3: 75% run, stop in two steps. Stopping is the bottleneck on every change of direction you own."}
  ]},
  {g:"Change of direction — week 2 onward", items:[
    {n:"Explosive first step", p:"5 × 5 m · rest 60 s", d:"Staggered athletic stance. Push the back foot into the floor and go — no step backwards first. That false step costs about two tenths of a second, which is a defender's whole recovery window."},
    {n:"Shuffle into a sprint", p:"4 each side · rest 60 s", d:"Shuffle 4 m laterally, turn the hips, sprint 6 m. Closing out on a shooter, then recovering in transition."},
    {n:"45° cut drill", p:"4 each side · rest 60 s", d:"Run 5 m, plant the outside foot hard, push off it and accelerate 5 m at an angle. This is how you get open off the ball."},
    {n:"Sprint, stop, change direction", p:"4 reps · rest 90 s", d:"Sprint 5 m, decelerate to a full stop in two or three steps, explode back the other way. Re-acceleration after a cut."}
  ]},
  {g:"Spin move — build in this order, do not skip stages", items:[
    {n:"Walk-through spin, no ball", p:"Week 2 · 6 each direction", d:"Chin turns first, tight pivot on the ball of the front foot, stay low the whole way."},
    {n:"Jog-speed spin", p:"Week 2–3 · 5 each direction", d:"Same shape, more speed. Keep the pivot close to your body."},
    {n:"Decelerate, then spin", p:"Week 3 · 4 each direction", d:"Jog 5 m, stop in two steps, then spin. The stop is what makes the spin sell."},
    {n:"Decelerate, spin, re-accelerate", p:"Week 3–4 · 4 each direction · rest 75 s", d:"Drive out of the spin off the outside leg for 5 m. Your pallof presses are what keep your torso stable through it."},
    {n:"Full-speed spin with a ball", p:"Week 4 · 4 each direction", d:"Only once the pattern is automatic without the ball."}
  ]},
  {g:"Landing into movement — week 3 onward", items:[
    {n:"Jump, land, immediate sprint", p:"4 reps · rest 90 s", d:"Countermovement jump, absorb into athletic stance, sprint 5 m. Rebound to outlet to fast break."},
    {n:"Reactive cut", p:"Week 4 · 4 each side · rest 75 s", d:"A teammate points left or right as you approach the marker. Real basketball is reactive, not pre-planned — this is the last layer."}
  ]}
];

const TESTS = [
  {n:"Standing vertical jump", d:"Reach up flat-footed against a wall and chalk-mark your standing reach. Chalk your fingers, dip and jump from a standstill, touch as high as you can. Three attempts, 60 seconds apart, take the best. Vertical = highest mark minus standing reach."},
  {n:"Approach vertical jump", d:"Same measurement, but with a two-step run-in. This is the number that shows up in a game."},
  {n:"Broad jump", d:"Toes behind a line, two-foot jump forward, land and stick it. Measure from the line to the back of your rear heel. Better than a phone-timed sprint because there is no timing error."},
  {n:"Body weight", d:"Morning, after the toilet, before food or drink, same scale, minimal clothing. Log three or four mornings a week and read the weekly average — a single day tells you nothing."},
  {n:"Waist", d:"At the navel, tape parallel to the floor, standing relaxed, at the end of a normal exhale. Do not suck in. Measure twice and average."},
  {n:"Strength check", d:"Heaviest leg press and lat pulldown you can do for eight clean reps with technique intact. Do it after a week of practising the movement — a true beginner's day-0 number measures technique, not strength."},
  {n:"5-10-5 agility", d:"Three markers 4.5 m apart. Start in the middle, sprint right and touch, sprint 9 m left and touch, sprint back through the middle. Phone timing carries about two tenths of error, so only treat a bigger change as real. Run day 0 at 80% effort."}
];

/* ============================================================
   STATE
   ============================================================ */
let S = {
  name:"", startDate:todayKey(), height:183, reach:null,
  baseline:null, measures:[], sessions:{}, ui:{tab:"overview", day:null}
};

function todayKey(d){ const x=d?new Date(d):new Date(); return x.getFullYear()+"-"+String(x.getMonth()+1).padStart(2,"0")+"-"+String(x.getDate()).padStart(2,"0"); }
function parseKey(k){ const [y,m,d]=k.split("-").map(Number); return new Date(y,m-1,d); }
function dayIndex(){ const a=parseKey(S.startDate), b=parseKey(todayKey()); return Math.floor((b-a)/86400000)+1; }
function weekNo(){ const i=dayIndex(); if(i<1) return 1; return Math.min(4, Math.max(1, Math.ceil(i/7))); }
function fmt(n,dp){ if(n===null||n===undefined||n==="") return "—"; const v=Number(n); return dp!==undefined? v.toFixed(dp): String(v); }
function $(s){ return document.querySelector(s); }
function el(t,c,h){ const e=document.createElement(t); if(c) e.className=c; if(h!==undefined) e.innerHTML=h; return e; }
function esc(s){ return String(s).replace(/[&<>"]/g,c=>({"&":"&amp;","<":"&lt;",">":"&gt;",'"':"&quot;"}[c])); }

let saveTimer=null;
function persist(){ clearTimeout(saveTimer); saveTimer=setTimeout(()=>Store.set(KEY,S),220); }

function toast(msg){ const t=$("#toast"); t.textContent=msg; t.classList.add("on"); setTimeout(()=>t.classList.remove("on"),1900); }

/* ============================================================
   NAV
   ============================================================ */
const TABS = [
  {id:"overview", label:"Overview", short:"Home", icon:'<path d="M3 9.5 10 3l7 6.5"/><path d="M5 8.5V17h10V8.5"/>'},
  {id:"today",    label:"Today's session", short:"Today", icon:'<circle cx="10" cy="10" r="7"/><path d="M10 6v4l2.5 2"/>'},
  {id:"progress", label:"Progress", short:"Progress", icon:'<path d="M3 15l4-5 3.5 3L17 5"/><path d="M3 17h14"/>'},
  {id:"measure",  label:"Measure", short:"Measure", icon:'<rect x="2.5" y="6.5" width="15" height="7" rx="1.5"/><path d="M6 6.5v3M10 6.5v4M14 6.5v3"/>'},
  {id:"program",  label:"Program", short:"Program", icon:'<rect x="4" y="3" width="12" height="14" rx="1.5"/><path d="M7 7h6M7 10h6M7 13h4"/>'}
];

function buildNav(){
  const nav=$("#nav"), mob=$("#mobnav");
  nav.innerHTML=""; mob.innerHTML="";
  TABS.forEach(t=>{
    const b=el("button",null,`<svg viewBox="0 0 20 20">${t.icon}</svg><span>${t.label}</span>`);
    b.onclick=()=>go(t.id); b.dataset.tab=t.id; nav.appendChild(b);
    const m=el("button",null,`<svg viewBox="0 0 20 20">${t.icon}</svg><span>${t.short}</span>`);
    m.onclick=()=>go(t.id); m.dataset.tab=t.id; mob.appendChild(m);
  });
}
function go(tab){
  S.ui.tab=tab;
  document.querySelectorAll(".screen").forEach(s=>s.classList.remove("on"));
  const target=$("#s-"+tab); if(target) target.classList.add("on");
  document.querySelectorAll("[data-tab]").forEach(b=>{
    if(b.dataset.tab===tab) b.setAttribute("aria-current","page"); else b.removeAttribute("aria-current");
  });
  window.scrollTo({top:0,behavior:"instant"});
  if(tab==="overview") renderOverview();
  if(tab==="today") renderToday();
  if(tab==="progress") renderProgress();
  if(tab==="measure") renderMeasure();
  persist();
}
document.querySelectorAll("[data-go]").forEach(b=>b.onclick=()=>go(b.dataset.go));

/* ============================================================
   CHARTS — hand-rolled SVG, no libraries
   ============================================================ */
function lineChart(host, opts){
  const series = opts.series.filter(s=>s.data.length);
  if(!series.length || series.every(s=>s.data.length<1)){
    host.innerHTML = `<div class="empty"><b>${esc(opts.emptyTitle||"Nothing logged yet")}</b>${esc(opts.emptyBody||"")}</div>`;
    return;
  }
  const W=560,H=190,padL=34,padR=14,padT=14,padB=24;
  const all=[].concat(...series.map(s=>s.data));
  let min=Math.min(...all.map(d=>d.v)), max=Math.max(...all.map(d=>d.v));
  if(min===max){ min-=2; max+=2; }
  const range=max-min; min-=range*0.15; max+=range*0.15;
  const xs=[...new Set(all.map(d=>d.t))].sort((a,b)=>a-b);
  const t0=xs[0], t1=xs[xs.length-1]||t0+1;
  const X=t=> padL + (t1===t0?0.5:( (t-t0)/(t1-t0) ))*(W-padL-padR);
  const Y=v=> padT + (1-(v-min)/(max-min))*(H-padT-padB);

  let g="";
  for(let i=0;i<=3;i++){
    const y=padT+i*(H-padT-padB)/3, val=max-(i*(max-min)/3);
    g+=`<line class="grid" x1="${padL}" y1="${y}" x2="${W-padR}" y2="${y}"/>`;
    g+=`<text class="axis" x="0" y="${y+3.5}">${val.toFixed(opts.dp!==undefined?opts.dp:0)}</text>`;
  }
  let paths="",dots="",labels="";
  series.forEach(s=>{
    const pts=s.data.slice().sort((a,b)=>a.t-b.t);
    if(pts.length===1){
      dots+=`<circle class="dot" cx="${X(pts[0].t)}" cy="${Y(pts[0].v)}" r="4" fill="${s.color}"><title>${esc(pts[0].label)}</title></circle>`;
    } else {
      const d=pts.map((p,i)=>(i?"L":"M")+X(p.t).toFixed(1)+" "+Y(p.v).toFixed(1)).join(" ");
      paths+=`<path class="ln" d="${d}" stroke="${s.color}" ${s.dash?'stroke-dasharray="4 4"':""}/>`;
      pts.forEach(p=>{ dots+=`<circle class="dot" cx="${X(p.t)}" cy="${Y(p.v)}" r="3.2" fill="${s.color}"><title>${esc(p.label)}</title></circle>`; });
    }
    const last=pts[pts.length-1];
    labels+=`<text class="axis" x="${Math.min(X(last.t)+7,W-padR-4)}" y="${Y(last.v)-8}" fill="${s.color}" style="font-weight:700;font-size:11.5px">${last.v.toFixed(opts.dp!==undefined?opts.dp:0)}</text>`;
  });
  const firstD=new Date(t0), lastD=new Date(t1);
  const dl=d=>d.toLocaleDateString(undefined,{day:"numeric",month:"short"});
  const axisX=`<text class="axis" x="${padL}" y="${H-6}">${dl(firstD)}</text><text class="axis" x="${W-padR}" y="${H-6}" text-anchor="end">${dl(lastD)}</text>`;
  const key = series.length>1 ? `<div style="display:flex;gap:14px;margin-top:8px;font-size:12px;color:var(--muted)">`+
    series.map(s=>`<span><i style="display:inline-block;width:9px;height:9px;border-radius:2px;background:${s.color};margin-right:6px"></i>${esc(s.name)}</span>`).join("")+`</div>` : "";
  host.innerHTML=`<svg class="chart" viewBox="0 0 ${W} ${H}" preserveAspectRatio="none" role="img" aria-label="${esc(opts.aria||"trend chart")}">${g}${paths}${dots}${labels}${axisX}</svg>${key}`;
}

function seriesFrom(field,color,name,dash){
  const data=S.measures.filter(m=>m[field]!==null&&m[field]!==undefined&&m[field]!=="")
    .map(m=>({t:parseKey(m.date).getTime(), v:Number(m[field]), label:`${m.date}: ${m[field]}`}))
    .sort((a,b)=>a.t-b.t);
  return {name,color,data,dash};
}

/* ============================================================
   OVERVIEW
   ============================================================ */
function latest(field){
  const rows=S.measures.filter(m=>m[field]!==null&&m[field]!==undefined&&m[field]!=="").sort((a,b)=>parseKey(a.date)-parseKey(b.date));
  return rows.length? Number(rows[rows.length-1][field]) : null;
}
function baseVal(field){
  if(S.baseline && S.baseline[field]!==null && S.baseline[field]!==undefined && S.baseline[field]!=="") return Number(S.baseline[field]);
  const rows=S.measures.filter(m=>m[field]!==null&&m[field]!==undefined&&m[field]!=="").sort((a,b)=>parseKey(a.date)-parseKey(b.date));
  return rows.length? Number(rows[0][field]) : null;
}

function renderWall(){
  const cur=latest("vert"), base=baseVal("vert");
  $("#vertBig").textContent = cur===null? "—" : fmt(cur,1);
  const dEl=$("#vertDelta");
  if(cur===null){ dEl.className="delta flat"; dEl.textContent="No reading yet"; }
  else if(base===null || base===cur){ dEl.className="delta flat"; dEl.textContent="Baseline set"; }
  else { const d=cur-base; dEl.className="delta "+(d>0?"up":"down"); dEl.textContent=(d>0?"+":"")+d.toFixed(1)+" cm since day 0"; }

  if(cur!==null){
    const app=latest("app");
    $("#vertSub").textContent = (S.reach? `Standing reach ${S.reach} cm, so you are touching ${(Number(S.reach)+cur).toFixed(0)} cm off a standstill. ` : "")+
      (app? `Approach jump ${app} cm.` : "Log an approach jump too — that is the one that shows up in a game.");
  }

  const scaleMax=Math.max(80, Math.ceil(((cur||40)+15)/10)*10);
  const H=100;
  const yOf=v=> 100 - (v/scaleMax)*88 - 6;
  let ticks="";
  for(let v=0; v<=scaleMax; v+=5){
    const y=yOf(v), major=v%10===0;
    ticks+=`<line x1="0" y1="${y}" x2="${major?9:5}" y2="${y}" stroke="${major?'#3E4C58':'#2A3540'}" stroke-width="${major?0.55:0.4}" vector-effect="non-scaling-stroke"/>`;
    if(major && v>0) ticks+=`<text x="11.5" y="${y+1.6}" fill="#5D6E7D" font-size="3.4" font-family="Barlow,sans-serif">${v}</text>`;
  }
  const curY = cur!==null? yOf(cur) : yOf(0);
  const baseY = base!==null? yOf(base) : null;
  const reduce = window.matchMedia("(prefers-reduced-motion: reduce)").matches;
  const startY = (reduce||base===null)? curY : baseY;

  $("#wallVis").innerHTML=`
  <svg viewBox="0 0 100 ${H}" preserveAspectRatio="none" aria-label="Vertical jump measured against a wall">
    <defs><linearGradient id="fade" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="rgba(238,243,247,.30)"/><stop offset="100%" stop-color="rgba(238,243,247,0)"/>
    </linearGradient></defs>
    ${ticks}
    ${baseY!==null?`<line x1="0" y1="${baseY}" x2="100" y2="${baseY}" stroke="#45C8DE" stroke-width="0.45" stroke-dasharray="2 2" vector-effect="non-scaling-stroke"/>
      <text x="97" y="${baseY-2}" fill="#45C8DE" font-size="3.4" text-anchor="end" font-family="Barlow,sans-serif">day 0 · ${base.toFixed(0)}</text>`:""}
    ${cur!==null?`<g class="mark-line" id="markG" style="transform:translateY(${(startY-curY).toFixed(2)}px)">
      <rect x="0" y="${curY-0.5}" width="100" height="1" fill="url(#fade)"/>
      <line x1="0" y1="${curY}" x2="72" y2="${curY}" stroke="#EEF3F7" stroke-width="0.7" vector-effect="non-scaling-stroke"/>
      <circle cx="72" cy="${curY}" r="1.6" fill="#FF6A1F"/>
      <text x="76" y="${curY+1.4}" fill="#EEF3F7" font-size="4" font-family="Barlow Condensed,sans-serif" font-weight="600">now</text>
    </g>`:`<text x="50" y="52" fill="#46545F" font-size="4.4" text-anchor="middle" font-family="Barlow,sans-serif">No jump logged</text>`}
    <line x1="0" y1="${yOf(0)}" x2="100" y2="${yOf(0)}" stroke="#2A3540" stroke-width="0.6" vector-effect="non-scaling-stroke"/>
    <text x="11.5" y="${yOf(0)+1.6}" fill="#46545F" font-size="3.4" font-family="Barlow,sans-serif">floor</text>
  </svg>`;

  if(cur!==null && !reduce && base!==null && base!==cur){
    requestAnimationFrame(()=>{ const g=document.getElementById("markG"); if(g) g.style.transform="translateY(0px)"; });
  }
}

function renderStrip(){
  const rows=[
    {k:"Body weight", f:"weight", u:"kg", dp:1, better:"down"},
    {k:"Waist", f:"waist", u:"cm", dp:1, better:"down"},
    {k:"Approach jump", f:"app", u:"cm", dp:1, better:"up"},
    {k:"Broad jump", f:"broad", u:"cm", dp:0, better:"up"}
  ];
  $("#strip").innerHTML = rows.map(r=>{
    const cur=latest(r.f), base=baseVal(r.f);
    let d='<div class="d none">no baseline</div>';
    if(cur!==null && base!==null && cur!==base){
      const diff=cur-base;
      const good = r.better==="down" ? diff<0 : diff>0;
      d=`<div class="d ${good?"good":"bad"}">${diff>0?"+":""}${diff.toFixed(r.dp)} ${r.u}</div>`;
    } else if(cur!==null && base!==null){ d='<div class="d none">unchanged</div>'; }
    return `<div class="cell"><div class="k">${r.k}</div><div class="v num">${cur===null?"—":fmt(cur,r.dp)}<small>${cur===null?"":r.u}</small></div>${d}</div>`;
  }).join("");
}

function renderCal(){
  const idx=dayIndex(), start=parseKey(S.startDate);
  let html="";
  for(let i=1;i<=30;i++){
    const d=new Date(start.getTime()+(i-1)*86400000);
    const key=todayKey(d), dow=d.getDay(), sc=SCHEDULE[dow];
    const rest = (sc==="rest"||sc==="recovery");
    const done = !!S.sessions[key] && S.sessions[key].completed;
    const cls=["d"]; if(rest) cls.push("rest"); if(done) cls.push("done");
    if(i===idx) cls.push("today"); if(i<idx) cls.push("past");
    const title = `Day ${i} · ${d.toLocaleDateString(undefined,{weekday:"short",day:"numeric",month:"short"})} · ${rest?(sc==="rest"?"Full rest":"Active recovery"):("Session "+sc)}${done?" · logged":""}`;
    html+=`<div class="${cls.join(" ")}" title="${esc(title)}">${i}</div>`;
  }
  $("#cal").innerHTML=html;
  const w=weekNo();
  $("#calNote").textContent = `Week ${w} — ${WEEK_RULES[w].name}. ${WEEK_RULES[w].note} Thursday is active recovery, Sunday is off.`;
  $("#dayNum").textContent = Math.max(0,Math.min(30,idx));
  $("#dayBar").style.width = Math.max(2,Math.min(100,(idx/30)*100))+"%";
}

function liftSeries(name,color){
  const pts=[];
  Object.keys(S.sessions).sort().forEach(k=>{
    const s=S.sessions[k]; if(!s.sets) return;
    let best=0;
    Object.keys(s.sets).forEach(exid=>{
      const meta=findEx(exid); if(!meta) return;
      if(!meta.n.toLowerCase().includes(name)) return;
      s.sets[exid].forEach(st=>{ if(st && st.w) best=Math.max(best,Number(st.w)); });
    });
    if(best>0) pts.push({t:parseKey(k).getTime(), v:best, label:`${k}: ${best} kg`});
  });
  return {name:name, color:color, data:pts};
}

function renderOverview(){
  renderWall(); renderStrip(); renderCal();
  const wS=seriesFrom("weight","#FF6A1F","Body weight");
  lineChart($("#cWeight"),{series:[wS],dp:1,emptyTitle:"No weigh-ins yet",emptyBody:"Add one in Measure. Log three or four mornings a week and read the average."});
  $("#wMeta").textContent = wS.data.length? wS.data.length+" readings" : "";
  lineChart($("#cVert"),{series:[seriesFrom("vert","#EEF3F7","Standing"),seriesFrom("app","#45C8DE","Approach")],dp:1,
    emptyTitle:"No jump logged",emptyBody:"Chalk your fingers, mark your standing reach, then jump. The difference is your number."});
  lineChart($("#cPress"),{series:[liftSeries("leg press","#FF6A1F")],dp:0,
    emptyTitle:"No leg press logged",emptyBody:"Log a set on Day 1 or Day 5 and it appears here."});

  const w=weekNo(), r=WEEK_RULES[w];
  const start=parseKey(S.startDate);
  let doneThisWeek=0;
  for(let i=(w-1)*7+1;i<=w*7;i++){
    const d=new Date(start.getTime()+(i-1)*86400000);
    if(S.sessions[todayKey(d)] && S.sessions[todayKey(d)].completed) doneThisWeek++;
  }
  let contacts=0;
  for(let i=(w-1)*7+1;i<=w*7;i++){
    const d=new Date(start.getTime()+(i-1)*86400000), s=S.sessions[todayKey(d)];
    if(s && s.contacts) contacts+=s.contacts;
  }
  $("#weekMeta").textContent = "Week "+w+" · "+r.name;
  $("#weekSummary").innerHTML = `
    <table><tbody>
      <tr><td class="mut">Sessions logged</td><td style="text-align:right;font-weight:600">${doneThisWeek} of 5</td></tr>
      <tr><td class="mut">Main lifts</td><td style="text-align:right;font-weight:600">${r.main.sets} × ${r.main.reps}</td></tr>
      <tr><td class="mut">Accessories</td><td style="text-align:right;font-weight:600">${r.acc.sets} sets</td></tr>
      <tr><td class="mut">Effort</td><td style="text-align:right">${esc(r.rpe)}</td></tr>
      <tr><td class="mut">Jump contacts logged</td><td style="text-align:right;font-weight:600">${contacts} <span class="mut" style="font-weight:400">/ ~${r.contacts} per session</span></td></tr>
    </tbody></table>`;
}

/* ============================================================
   TODAY / SESSION
   ============================================================ */
function findEx(id){
  for(const d of Object.keys(DAYS)) for(const b of DAYS[d].blocks) for(const e of b.ex) if(e.id===id) return e;
  return null;
}
function prescriptionFor(ex,w){
  if(ex.p) return ex.p;
  const r=WEEK_RULES[w];
  if(ex.role==="main") return `${r.main.sets} × ${ex.reps||r.main.reps}`;
  if(ex.role==="acc") return `${r.acc.sets} × ${ex.reps||"10–12"}`;
  return ex.reps||"—";
}
function setCountFor(ex,w){
  const r=WEEK_RULES[w];
  if(ex.role==="main") return r.main.sets;
  if(ex.role==="acc") return r.acc.sets;
  const m=(ex.p||"").match(/^(\d+)\s*×/); return m? Number(m[1]):0;
}
function scheduledDay(){
  const sc=SCHEDULE[new Date().getDay()];
  return (sc==="rest"||sc==="recovery")? null : sc;
}
function currentSession(){
  const k=todayKey();
  if(!S.sessions[k]) S.sessions[k]={day:S.ui.day||scheduledDay()||1, done:{}, sets:{}, contacts:0, completed:false};
  return S.sessions[k];
}

function renderToday(){
  const sc=SCHEDULE[new Date().getDay()], w=weekNo(), sess=currentSession();
  if(S.ui.day) sess.day=S.ui.day;
  const dayId = sess.day || scheduledDay() || 1;
  sess.day = dayId;

  const dayName=new Date().toLocaleDateString(undefined,{weekday:"long"});
  if(sc==="rest"){ $("#todayTitle").textContent="Sunday — full rest"; $("#todaySub").textContent="Sleep, eat, walk. You get stronger between sessions, not during them. If you want to train anyway, pick a day below."; }
  else if(sc==="recovery"){ $("#todayTitle").textContent="Thursday — active recovery"; $("#todaySub").textContent="Twenty to thirty minutes of easy walking or the recumbent bike, plus stretching. No lifting, no jumping. Shooting practice is fine."; }
  else { $("#todayTitle").textContent=`${dayName} — Day ${dayId}`; $("#todaySub").textContent=`${DAYS[dayId].name}. Week ${w}: ${WEEK_RULES[w].rpe}.`; }

  $("#daySwitch").innerHTML = [1,2,3,4,5].map(i=>
    `<button class="pill" data-day="${i}" aria-pressed="${i===dayId}">Day ${i} · ${esc(DAYS[i].focus)}</button>`).join("");
  $("#daySwitch").querySelectorAll("button").forEach(b=>b.onclick=()=>{
    S.ui.day=Number(b.dataset.day); currentSession().day=S.ui.day; persist(); renderToday();
  });

  const D=DAYS[dayId];
  let html="";
  D.blocks.forEach(bl=>{
    const tag = bl.tag? `<span class="tag ${bl.tag}">${bl.tag==="jump"?"explosive":"movement"}</span>`:"";
    html+=`<div class="block"><div class="blockhead"><h4>${esc(bl.t)}</h4>${tag}${bl.hint?`<span class="hint">${esc(bl.hint)}</span>`:""}</div>`;
    bl.ex.forEach(ex=>{
      const done = !!sess.done[ex.id];
      const pres = prescriptionFor(ex,w);
      const nSets = ex.log? setCountFor(ex,w):0;
      let sets="";
      if(ex.log && nSets){
        sets=`<div class="sets">`;
        for(let i=0;i<nSets;i++){
          const rec=(sess.sets[ex.id]&&sess.sets[ex.id][i])||{};
          const filled=(rec.w||rec.r)?" filled":"";
          sets+=`<span class="setbox${filled}"><label>${i+1}</label>
            <input type="number" inputmode="decimal" placeholder="kg" value="${rec.w!==undefined&&rec.w!==""?rec.w:""}" data-ex="${ex.id}" data-i="${i}" data-f="w" aria-label="Set ${i+1} weight">
            <span class="x">×</span>
            <input type="number" inputmode="numeric" placeholder="reps" value="${rec.r!==undefined&&rec.r!==""?rec.r:""}" data-ex="${ex.id}" data-i="${i}" data-f="r" aria-label="Set ${i+1} reps"></span>`;
        }
        sets+=`</div>`;
      }
      html+=`<div class="ex${done?" done":""}" data-ex="${ex.id}">
        <button class="tick" aria-label="Mark ${esc(ex.n)} done" aria-pressed="${done}"><svg viewBox="0 0 12 12"><path d="M2 6.2 4.6 9 10 3"/></svg></button>
        <div class="exbody">
          <div class="exname">${esc(ex.n)}${ex.bw?'<span class="tag bw">bodyweight</span>':""}${ex.risk?'<span class="tag risk">technique-sensitive</span>':""}</div>
          ${ex.m?`<div class="exmeta">${esc(ex.m)}</div>`:""}
          ${ex.cue?`<div class="excue">${esc(ex.cue)}</div>`:""}
          ${sets}
        </div>
        <div class="exright">
          <span class="prescr num">${esc(pres)}</span>
          ${ex.rest?`<button class="restbtn" data-rest="${ex.rest}" data-name="${esc(ex.n)}">Rest ${ex.rest}s</button>`:""}
        </div>
      </div>`;
    });
    html+=`</div>`;
  });

  const hasJump = D.blocks.some(b=>b.tag==="jump");
  if(hasJump){
    html+=`<div class="block"><div class="blockhead"><h4>Jump contacts</h4><span class="tag jump">explosive</span>
      <span class="hint">Target about ${WEEK_RULES[w].contacts} this session</span></div>
      <div class="ex"><div class="exbody">
        <div class="exname">Landings counted today</div>
        <div class="excue">Count every landing, warm-up pogos included. If your last jump is visibly lower than your first, stop — you are training fatigue, not power.</div>
        <div style="margin-top:10px" id="contactCounter"></div>
      </div></div></div>`;
  }
  $("#sessionBody").innerHTML=html;

  if(hasJump){
    const c=el("div","counter",`<button aria-label="Subtract five">−</button><span class="val num">${sess.contacts||0}</span><button aria-label="Add five">+</button>`);
    const btns=c.querySelectorAll("button");
    btns[0].onclick=()=>{ sess.contacts=Math.max(0,(sess.contacts||0)-5); c.querySelector(".val").textContent=sess.contacts; persist(); };
    btns[1].onclick=()=>{ sess.contacts=(sess.contacts||0)+5; c.querySelector(".val").textContent=sess.contacts; persist();
      if(sess.contacts>WEEK_RULES[w].contacts+20) toast("Well past this week's dose. Quality drops fast from here."); };
    $("#contactCounter").appendChild(c);
  }

  $("#sessionBody").querySelectorAll(".tick").forEach(b=>{
    b.onclick=()=>{
      const row=b.closest(".ex"), id=row.dataset.ex;
      sess.done[id]=!sess.done[id];
      row.classList.toggle("done",!!sess.done[id]);
      b.setAttribute("aria-pressed",!!sess.done[id]);
      updateRing(); persist();
    };
  });
  $("#sessionBody").querySelectorAll(".setbox input").forEach(inp=>{
    inp.oninput=()=>{
      const id=inp.dataset.ex, i=Number(inp.dataset.i), f=inp.dataset.f;
      if(!sess.sets[id]) sess.sets[id]=[];
      if(!sess.sets[id][i]) sess.sets[id][i]={};
      sess.sets[id][i][f]=inp.value;
      inp.closest(".setbox").classList.toggle("filled", !!(sess.sets[id][i].w||sess.sets[id][i].r));
      persist();
    };
  });
  $("#sessionBody").querySelectorAll(".restbtn").forEach(b=>{
    b.onclick=()=>startRest(Number(b.dataset.rest), b.dataset.name);
  });
  updateRing();
}

function updateRing(){
  const sess=currentSession(), D=DAYS[sess.day||1];
  let total=0, done=0;
  D.blocks.forEach(b=>b.ex.forEach(e=>{ total++; if(sess.done[e.id]) done++; }));
  const p= total? Math.round(done/total*100):0;
  const ring=$("#progRing"); ring.style.setProperty("--p",p); ring.querySelector("i").textContent=p+"%";
}

$("#saveSession").onclick=()=>{
  const sess=currentSession();
  sess.completed=true; sess.savedAt=new Date().toISOString();
  persist(); toast("Session saved"); renderCal();
};
$("#clearSession").onclick=()=>{
  if(!confirm("Clear everything logged today? Your measurements are not affected.")) return;
  delete S.sessions[todayKey()]; persist(); renderToday(); renderCal(); toast("Today cleared");
};

/* ============================================================
   REST TIMER
   ============================================================ */
let timer=null, tLeft=0, tTotal=0;
function startRest(sec,name){
  tLeft=sec; tTotal=sec;
  $("#tname").textContent="Rest — "+name;
  $("#tsub").textContent = sec>=90? "Full recovery. Explosive work needs it." : "Stay loose, breathe through the nose.";
  $("#dock").classList.add("on");
  tick(); clearInterval(timer);
  timer=setInterval(()=>{ tLeft--; tick(); if(tLeft<=0){ clearInterval(timer); $("#tname").textContent="Go"; $("#tsub").textContent="Next set."; setTimeout(()=>$("#dock").classList.remove("on"),2600);} },1000);
}
function tick(){
  $("#tval").textContent=Math.max(0,tLeft);
  $("#tring").style.setProperty("--p", Math.max(0,(tLeft/tTotal)*100));
}
$("#tAdd").onclick=()=>{ tLeft+=30; tTotal=Math.max(tTotal,tLeft); tick(); };
$("#tStop").onclick=()=>{ clearInterval(timer); $("#dock").classList.remove("on"); };

/* ============================================================
   PROGRESS
   ============================================================ */
function renderProgress(){
  lineChart($("#pWeight"),{series:[seriesFrom("weight","#FF6A1F","Body weight")],dp:1,emptyTitle:"No weigh-ins yet",emptyBody:"Add one in Measure."});
  lineChart($("#pWaist"),{series:[seriesFrom("waist","#45C8DE","Waist")],dp:1,emptyTitle:"No waist measurements",emptyBody:"Tape at the navel, normal exhale. Weekly is enough."});
  lineChart($("#pVert"),{series:[seriesFrom("vert","#EEF3F7","Standing"),seriesFrom("app","#45C8DE","Approach")],dp:1,emptyTitle:"No jump logged",emptyBody:"This is the headline number. Test it at day 0 and day 30."});
  lineChart($("#pBroad"),{series:[seriesFrom("broad","#FF6A1F","Broad jump")],dp:0,emptyTitle:"No broad jump logged",emptyBody:"A cleaner acceleration test than a phone-timed sprint."});
  lineChart($("#pLifts"),{series:[liftSeries("leg press","#FF6A1F"),liftSeries("lat pulldown","#45C8DE")],dp:0,emptyTitle:"No lifts logged",emptyBody:"Weights you type into a session show up here."});

  const keys=Object.keys(S.sessions).filter(k=>S.sessions[k].completed).sort().reverse();
  $("#histMeta").textContent = keys.length? keys.length+" logged":"";
  if(!keys.length){ $("#pHist").innerHTML=`<div class="empty"><b>No sessions saved</b>Tick your way through a session and hit Save.</div>`; return; }
  let rows="";
  keys.slice(0,14).forEach(k=>{
    const s=S.sessions[k], D=DAYS[s.day||1];
    let total=0,done=0; D.blocks.forEach(b=>b.ex.forEach(e=>{total++; if(s.done[e.id])done++;}));
    let vol=0; Object.keys(s.sets||{}).forEach(id=>s.sets[id].forEach(st=>{ if(st&&st.w&&st.r) vol+=Number(st.w)*Number(st.r); }));
    rows+=`<tr><td>${parseKey(k).toLocaleDateString(undefined,{day:"numeric",month:"short"})}</td>
      <td class="mut">Day ${s.day} · ${esc(D.focus)}</td>
      <td style="text-align:right">${Math.round(done/total*100)}%</td>
      <td style="text-align:right">${s.contacts||0}</td>
      <td style="text-align:right">${vol? Math.round(vol).toLocaleString()+" kg":"—"}</td></tr>`;
  });
  $("#pHist").innerHTML=`<table><thead><tr><th>Date</th><th>Session</th><th style="text-align:right">Done</th><th style="text-align:right">Contacts</th><th style="text-align:right">Volume</th></tr></thead><tbody>${rows}</tbody></table>`;
}

/* ============================================================
   MEASURE
   ============================================================ */
function readForm(){
  const g=id=>{const v=$(id).value.trim(); return v===""?null:Number(v);};
  return { date:$("#mDate").value||todayKey(), weight:g("#mWeight"), waist:g("#mWaist"),
    vert:g("#mVert"), app:g("#mApp"), broad:g("#mBroad"), sleep:g("#mSleep"),
    energy:$("#mEnergy").value?Number($("#mEnergy").value):null };
}
function formHasData(r){ return ["weight","waist","vert","app","broad","sleep","energy"].some(k=>r[k]!==null); }

$("#addMeasure").onclick=()=>{
  const r=readForm();
  if(!formHasData(r)){ toast("Fill in at least one measurement"); return; }
  const i=S.measures.findIndex(m=>m.date===r.date);
  if(i>=0){ Object.keys(r).forEach(k=>{ if(r[k]!==null) S.measures[i][k]=r[k]; }); }
  else S.measures.push(r);
  if(!S.baseline) S.baseline={...r};
  persist(); clearForm(); renderMeasure(); renderOverview(); toast(i>=0?"Reading updated":"Reading saved");
};
$("#markBaseline").onclick=()=>{
  const r=readForm();
  if(!formHasData(r)){ toast("Fill in your day 0 numbers first"); return; }
  S.baseline={...r};
  const i=S.measures.findIndex(m=>m.date===r.date);
  if(i>=0) Object.keys(r).forEach(k=>{ if(r[k]!==null) S.measures[i][k]=r[k]; }); else S.measures.push(r);
  persist(); clearForm(); renderMeasure(); renderOverview(); toast("Baseline set");
};
function clearForm(){ ["#mWeight","#mWaist","#mVert","#mApp","#mBroad","#mSleep"].forEach(s=>$(s).value=""); $("#mEnergy").value=""; }

function renderMeasure(){
  if(!$("#mDate").value) $("#mDate").value=todayKey();

  const fields=[
    {k:"Body weight",f:"weight",u:"kg",dp:1,better:"down"},
    {k:"Waist",f:"waist",u:"cm",dp:1,better:"down"},
    {k:"Standing vertical",f:"vert",u:"cm",dp:1,better:"up"},
    {k:"Approach vertical",f:"app",u:"cm",dp:1,better:"up"},
    {k:"Broad jump",f:"broad",u:"cm",dp:0,better:"up"}
  ];
  $("#cmpMeta").textContent = S.baseline? "day 0 → latest" : "no baseline set";
  $("#cmpTable").innerHTML = `<table><thead><tr><th>Measure</th><th style="text-align:right">Day 0</th><th style="text-align:right">Now</th><th style="text-align:right">Change</th></tr></thead><tbody>`+
    fields.map(r=>{
      const b=baseVal(r.f), c=latest(r.f);
      let ch='<td class="mut" style="text-align:right">—</td>';
      if(b!==null&&c!==null&&b!==c){
        const d=c-b, good = r.better==="down"? d<0 : d>0;
        ch=`<td style="text-align:right;color:${good?"var(--good)":"var(--warn)"};font-weight:600">${d>0?"+":""}${d.toFixed(r.dp)}</td>`;
      }
      return `<tr><td class="mut">${r.k}</td><td style="text-align:right">${b===null?"—":fmt(b,r.dp)+" "+r.u}</td><td style="text-align:right;font-weight:600">${c===null?"—":fmt(c,r.dp)+" "+r.u}</td>${ch}</tr>`;
    }).join("")+`</tbody></table>`;

  const ms=S.measures.slice().sort((a,b)=>parseKey(b.date)-parseKey(a.date));
  $("#mCount").textContent = ms.length? ms.length+" entries":"";
  if(!ms.length){ $("#mTable").innerHTML=`<div class="empty"><b>Nothing logged yet</b>Start with your day 0 numbers: weight, waist and a vertical jump. Ten minutes now makes the next thirty days measurable.</div>`; }
  else {
    $("#mTable").innerHTML=`<table><thead><tr><th>Date</th><th style="text-align:right">Weight</th><th style="text-align:right">Waist</th><th style="text-align:right">Vertical</th><th style="text-align:right">Approach</th><th style="text-align:right">Broad</th><th style="text-align:right">Sleep</th><th style="text-align:right">Energy</th><th></th></tr></thead><tbody>`+
      ms.map(m=>`<tr><td>${parseKey(m.date).toLocaleDateString(undefined,{day:"numeric",month:"short"})}${S.baseline&&S.baseline.date===m.date?' <span style="color:var(--cool);font-size:11px">day 0</span>':""}</td>
        <td style="text-align:right">${m.weight??"—"}</td><td style="text-align:right">${m.waist??"—"}</td>
        <td style="text-align:right">${m.vert??"—"}</td><td style="text-align:right">${m.app??"—"}</td>
        <td style="text-align:right">${m.broad??"—"}</td><td style="text-align:right">${m.sleep??"—"}</td>
        <td style="text-align:right">${m.energy??"—"}</td>
        <td style="text-align:right"><button class="restbtn" data-del="${m.date}">Remove</button></td></tr>`).join("")+`</tbody></table>`;
    $("#mTable").querySelectorAll("[data-del]").forEach(b=>b.onclick=()=>{
      S.measures=S.measures.filter(x=>x.date!==b.dataset.del);
      if(S.baseline&&S.baseline.date===b.dataset.del) S.baseline=null;
      persist(); renderMeasure(); renderOverview(); toast("Reading removed");
    });
  }

  $("#testProtocols").innerHTML = TESTS.map(t=>`<div class="drill"><div class="dn">${esc(t.n)}</div><div class="dd">${esc(t.d)}</div></div>`).join("");
}

/* ============================================================
   PROGRAM SCREEN
   ============================================================ */
function renderProgram(){
  const w=weekNo();
  $("#progWeeks").innerHTML = [1,2,3,4].map(i=>{
    const r=WEEK_RULES[i], open = i===w;
    return `<div class="acc${open?" open":""}" data-acc="${i}">
      <button aria-expanded="${open}">
        <svg class="chev" viewBox="0 0 14 14"><path d="M5 2l5 5-5 5"/></svg>
        <span class="idx">W${i}</span>
        <span class="ttl">${esc(r.name)}</span>
        <span class="cap">${i===w?"you are here · ":""}${r.main.sets} × ${r.main.reps} on main lifts</span>
      </button>
      <div class="body">
        <table><tbody>
          <tr><td class="mut">Main lifts</td><td style="text-align:right;font-weight:600">${r.main.sets} × ${r.main.reps}</td></tr>
          <tr><td class="mut">Accessories</td><td style="text-align:right;font-weight:600">${r.acc.sets} sets</td></tr>
          <tr><td class="mut">Effort</td><td style="text-align:right">${esc(r.rpe)}</td></tr>
          <tr><td class="mut">Jump contacts per session</td><td style="text-align:right;font-weight:600">about ${r.contacts}</td></tr>
          <tr><td class="mut">What changes</td><td style="text-align:right">${esc(r.note)}</td></tr>
        </tbody></table>
        <div class="dd" style="font-size:13px;color:var(--muted);margin-top:12px;line-height:1.6">
          ${i===1?"Learn the movements and set your working weights. If it feels easy, that is correct.":""}
          ${i===2?"Add load where week 1 felt light. The barbell squat enters with an empty bar for two sessions before you add anything.":""}
          ${i===3?"The heaviest week. If technique slips or a joint aches, repeat week 2 instead of pushing on — nobody was ever set back by an extra week at the same load.":""}
          ${i===4?"Volume drops, intent goes up. Long rests on jumps. Retest everything at the end of the week against your day 0 numbers.":""}
        </div>
      </div></div>`;
  }).join("");
  $("#progWeeks").querySelectorAll(".acc>button").forEach(b=>b.onclick=()=>{
    const a=b.parentElement, open=a.classList.toggle("open"); b.setAttribute("aria-expanded",open);
  });

  $("#jumpTable").innerHTML=`<table><thead><tr><th>Week</th><th>Sessions</th><th style="text-align:right">Contacts</th><th>Work</th><th style="text-align:right">Rest between sets</th></tr></thead><tbody>
    <tr><td>1</td><td class="mut">Mon, Wed</td><td style="text-align:right">~40</td><td class="mut">Snap-downs, pogos, countermovement jumps</td><td style="text-align:right">45–90 s</td></tr>
    <tr><td>2</td><td class="mut">Mon, Wed, Sat</td><td style="text-align:right">~55</td><td class="mut">Add approach jumps and lateral hop-to-stick</td><td style="text-align:right">60–90 s</td></tr>
    <tr><td>3</td><td class="mut">Mon, Wed, Sat</td><td style="text-align:right">~65</td><td class="mut">Add repeat jumps, three back to back</td><td style="text-align:right">90 s</td></tr>
    <tr><td>4</td><td class="mut">Mon, Wed</td><td style="text-align:right">~40</td><td class="mut">Max-effort jumps only, then retest</td><td style="text-align:right">2 min</td></tr>
  </tbody></table>
  <div class="callout" style="border-left-color:var(--cool);background:rgba(69,200,222,.06)">
    <b style="color:var(--cool)">Landing comes before jumping.</b> Four checks on every landing: it is quiet, the knees stay out over the toes, you bend at ankle then knee then hip, and you can hold the position for two seconds. If a landing in a set fails any of these, the set is over. No box jumps or depth jumps in this block — you have no plyo box, and at your bodyweight the risk-to-reward is poor.
  </div>`;

  $("#drillList").innerHTML = DRILLS.map(g=>`<div class="panel" style="margin-bottom:12px">
    <h3>${esc(g.g)}</h3>
    ${g.items.map(d=>`<div class="drill"><div class="dn">${esc(d.n)}</div><div class="dp num">${esc(d.p)}</div><div class="dd">${esc(d.d)}</div></div>`).join("")}
  </div>`).join("");
}

/* ============================================================
   SETTINGS
   ============================================================ */
function renderSettings(){
  $("#setName").value=S.name||""; $("#setStart").value=S.startDate;
  $("#setHeight").value=S.height||""; $("#setReach").value=S.reach||"";
  $("#storeMode").textContent="Saved to: "+storeMode+".";
}
$("#saveSettings").onclick=()=>{
  S.name=$("#setName").value.trim();
  S.startDate=$("#setStart").value||todayKey();
  S.height=Number($("#setHeight").value)||null;
  S.reach=Number($("#setReach").value)||null;
  persist(); renderOverview(); renderProgram(); toast("Setup saved");
  $("#greet").textContent = S.name? `Where you stand, ${S.name}` : "Where you stand";
};
$("#exportBtn").onclick=()=>{
  const blob=new Blob([JSON.stringify(S,null,2)],{type:"application/json"});
  const a=document.createElement("a"); a.href=URL.createObjectURL(blob);
  a.download="vertical-dashboard-"+todayKey()+".json"; a.click(); URL.revokeObjectURL(a.href);
  toast("Exported");
};
$("#importBtn").onclick=()=>$("#importFile").click();
$("#importFile").onchange=e=>{
  const f=e.target.files[0]; if(!f) return;
  const r=new FileReader();
  r.onload=()=>{ try{ const d=JSON.parse(r.result); if(!d||typeof d!=="object") throw 0;
    S=Object.assign({name:"",startDate:todayKey(),height:183,reach:null,baseline:null,measures:[],sessions:{},ui:{tab:"overview",day:null}},d);
    persist(); boot(true); toast("Data imported");
  }catch(err){ toast("That file could not be read"); } };
  r.readAsText(f); e.target.value="";
};
$("#resetBtn").onclick=()=>{
  if(!confirm("Erase every measurement and session on this device? Export first if you want a copy.")) return;
  S={name:"",startDate:todayKey(),height:183,reach:null,baseline:null,measures:[],sessions:{},ui:{tab:"overview",day:null}};
  persist(); boot(true); toast("Everything erased");
};

/* ============================================================
   BOOT
   ============================================================ */
async function boot(skipLoad){
  if(!skipLoad){
    const saved=await Store.get(KEY);
    if(saved) S=Object.assign(S,saved);
    if(!S.startDate) S.startDate=todayKey();
  }
  buildNav();
  if(S.name) $("#greet").textContent="Where you stand, "+S.name;
  renderProgram(); renderSettings();
  go(S.ui&&S.ui.tab? S.ui.tab : "overview");
}
boot();
</script>
</body>
</html>
