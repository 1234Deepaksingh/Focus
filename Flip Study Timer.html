<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Flip Study Timer</title>
<link href="https://fonts.googleapis.com/css2?family=Oswald:wght@600;700&display=swap" rel="stylesheet">
<style>
:root{--bg:#000;--card:#202020;--fg:#b4b4b4;--line:#000;--acc:#7c5cd6;--ui:#1b1b1b;--uf:#ddd;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
:root[data-theme=red]{--bg:#3a0a12;--card:#272222;--fg:#d0302e;--line:#3a0a12;--acc:#d0302e}
:root[data-theme=teal]{--bg:#2d6e86;--card:#063347;--fg:#a8fbff;--line:#2d6e86;--acc:#3ac;--ui:#0a3a4e}
:root[data-theme=cream]{--bg:#f4dfb8;--card:#f6e8d2;--fg:#2f2f2f;--line:#e7cf9f;--acc:#b8892e;--ui:#fff6e4;--uf:#333}
:root[data-theme=navy]{--bg:#2a2a6a;--card:#3d3f8a;--fg:#fbefd0;--line:#2a2a6a;--acc:#fbefd0;--ui:#34357a}
:root[data-theme=coral]{--bg:#f98a7e;--card:#004a5c;--fg:#dcdcdc;--line:#f98a7e;--acc:#004a5c;--ui:#004a5c}
:root[data-theme=light]{--bg:#eef1f7;--card:#fff;--fg:#303030;--line:#e3e6ee;--acc:#5b5bd6;--ui:#fff;--uf:#333}
*{box-sizing:border-box;margin:0}
html,body{height:100%}
body{background:var(--bg);color:var(--fg);font-family:Oswald,"Arial Narrow",Arial,sans-serif;display:flex;flex-direction:column;overflow:hidden;user-select:none;-webkit-tap-highlight-color:transparent}
#top,#bar{display:flex;gap:8px;justify-content:center;flex-wrap:wrap;padding:12px;transition:opacity .4s}
button,select{font:inherit;font-size:15px;background:var(--ui);color:var(--uf);border:1px solid #8884;border-radius:12px;padding:9px 16px;cursor:pointer}
button.on{background:var(--acc);color:#fff;border-color:transparent}
#go{min-width:110px}
#phase{text-align:center;font-size:20px;letter-spacing:.15em;text-transform:uppercase;opacity:.8;min-height:28px}
#clock{flex:1;display:flex;gap:2.5vmin;align-items:center;justify-content:center;padding:2vmin;min-height:0}
.card{position:relative;background:var(--card);border-radius:4vmin;display:flex;align-items:center;justify-content:center;height:min(100%,62vw);aspect-ratio:.9;max-width:44vw;flex:1 1 0;max-height:100%}
.card::after{content:"";position:absolute;left:0;right:0;top:50%;height:2px;background:var(--line);opacity:.9}
.card b{font-weight:700;font-size:min(30vw,52vh);line-height:1;font-variant-numeric:tabular-nums}
#clock.three .card b{font-size:min(20vw,42vh)}
.card b.f{animation:fl .45s ease-out}
@keyframes fl{0%{transform:scaleY(.1);opacity:.3}100%{transform:scaleY(1);opacity:1}}
.card small{position:absolute;top:6%;left:0;right:0;text-align:center;font-size:max(14px,2.4vmin);letter-spacing:.12em;opacity:.7;font-weight:600}
#set{position:fixed;inset:0;background:#000b;display:flex;align-items:center;justify-content:center;z-index:5}
#set[hidden]{display:none}
.panel{background:var(--ui);color:var(--uf);border-radius:18px;padding:20px;width:min(92vw,420px);max-height:90vh;overflow:auto;font-family:system-ui,Arial,sans-serif}
.panel h2{font-size:20px;margin-bottom:12px}
.row{display:flex;justify-content:space-between;align-items:center;padding:9px 0;border-bottom:1px solid #8883;font-size:15px}
.row input[type=number]{width:70px;padding:6px;border-radius:8px;border:1px solid #8886;background:transparent;color:inherit;font-size:15px}
.sw{display:flex;gap:8px;flex-wrap:wrap;padding:10px 0}
.sw i{width:34px;height:34px;border-radius:50%;border:3px solid transparent;cursor:pointer}
.sw i.s{border-color:#fff;outline:2px solid var(--acc)}
body.zen.idle #top,body.zen.idle #bar{opacity:0;pointer-events:none}
body.zen.idle{cursor:none}
.hide{display:none!important}
@media(orientation:portrait){#clock{flex-direction:column}.card{width:78%;height:auto;max-width:none;flex:0 1 38%;aspect-ratio:auto;max-height:42%}.card b{font-size:min(46vw,30vh)}#clock.three .card{flex-basis:28%;max-height:30%}#clock.three .card b{font-size:min(34vw,22vh)}}
#clock.digital{padding:0 2vw}
.dg{font-family:Roboto,"Helvetica Neue",Arial,sans-serif;font-weight:300;font-size:min(19vw,46vh);color:var(--fg);font-variant-numeric:tabular-nums;letter-spacing:-.02em;white-space:nowrap}
:root[data-theme=dark] .dg{color:#fff}
.two .dg{font-size:min(30vw,60vh)}
@media(orientation:portrait){.dg{font-size:17vw}.two .dg{font-size:28vw}}
#splash{position:fixed;inset:0;z-index:9;background:#0d0d14;color:#fff;display:flex;align-items:center;justify-content:center;text-align:center;transition:opacity .5s,visibility .5s;font-family:Oswald,sans-serif}
#splash.gone{opacity:0;visibility:hidden}
#splash span{font-size:64px;display:block}#splash h1{font-size:38px;letter-spacing:.1em}#splash p{opacity:.6;letter-spacing:.3em;text-transform:uppercase;font-size:13px}
#app{display:flex;justify-content:space-between;align-items:center;gap:10px;flex-wrap:wrap;padding:10px 16px 0;font-family:system-ui,Arial,sans-serif;font-size:13px}
.logo{font-size:18px;font-family:Oswald,sans-serif;letter-spacing:.06em}
#stats{display:flex;gap:8px;flex-wrap:wrap}
#stats span{background:var(--ui);color:var(--uf);padding:6px 10px;border-radius:20px;border:1px solid #8884}
#top{background:var(--ui);margin:8px auto 0;border-radius:16px;padding:5px;gap:2px;flex-wrap:nowrap;width:max-content;max-width:96vw}
#top button{border:0;background:transparent;border-radius:12px;padding:8px 12px;font-size:14px}
#top button.on{background:var(--acc);color:#fff}
#prog{height:5px;margin:8px 6vw 0;background:#8883;border-radius:5px;overflow:hidden}
#prog i{display:block;height:100%;width:0;background:var(--acc);transition:width .5s linear}
body.zen #app{display:none}
</style>
</head>
<body>
<div id="splash"><div><span>⏱</span><h1>FlipFocus</h1><p>Study timer</p></div></div>
<header id="app"><div class="logo">⏱ <b>FlipFocus</b></div><div id="stats"></div></header>
<div id="top">
  <button data-m="pomo">🍅 Pomodoro</button><button data-m="timer">⏳ Timer</button><button data-m="sw">⏱ Stopwatch</button><button data-m="clock">🕒 Clock</button>
</div>
<div id="prog"><i></i></div>
<div id="phase"></div>
<main id="clock"></main>
<div id="bar">
  <button id="m5" class="hide">−5 min</button>
  <button id="go" class="on">Start</button>
  <button id="rs">Reset</button>
  <button id="p5" class="hide">+5 min</button>
  <button id="nx" class="hide">Skip</button>
  <button id="fs">⛶ Full screen</button>
  <button id="sy">🔢 Digital</button>
  <button id="st">⚙ Settings</button>
</div>
<div id="set" hidden>
  <div class="panel">
    <h2>Settings</h2>
    <div class="sw" id="sw"></div>
    <div class="row">Focus (min)<input type="number" id="focus" min="1" max="180"></div>
    <div class="row">Short break (min)<input type="number" id="short" min="1" max="60"></div>
    <div class="row">Long break (min)<input type="number" id="long" min="1" max="90"></div>
    <div class="row">Timer length (min)<input type="number" id="custom" min="1" max="600"></div>
    <div class="row">Count up (off = count down)<input type="checkbox" id="up"></div>
    <div class="row">Sound alert<input type="checkbox" id="sound"></div>
    <div class="row">Vibration<input type="checkbox" id="vib"></div>
    <div class="row">24-hour clock<input type="checkbox" id="h24"></div>
    <div class="row">Keep screen on<input type="checkbox" id="awake"></div>
    <div class="row" style="border:0;gap:8px"><button id="def" style="background:#e5483c;color:#fff">Reset all</button><button id="ok" class="on">Done</button></div>
  </div>
</div>
<script>
const $=s=>document.querySelector(s),pad=n=>String(n).padStart(2,"0");
const DEF={up:true,style:"flip",theme:"dark",focus:25,short:5,long:15,custom:25,sound:true,vib:true,h24:true,awake:true};
let S=Object.assign({},DEF);
try{Object.assign(S,JSON.parse(localStorage.getItem("fst")||"{}"))}catch(e){}
const save=()=>{try{localStorage.setItem("fst",JSON.stringify(S))}catch(e){}};
const THEMES={dark:"#202020",red:"#d0302e",teal:"#2d6e86",cream:"#f4dfb8",navy:"#3d3f8a",coral:"#f98a7e",light:"#ffffff"};
let mode="pomo",phase="focus",cycle=0,running=false,left=0,up=0,end=0,startAt=0,wl=null,ac=null,idleT;

let TT=0;
function resetTime(){running=false;rel();
  if(mode==="pomo")left=S[phase]*60;else if(mode==="timer")left=S.custom*60;else up=0;TT=left;
  ui();update()}
function show(v,l){const c=$("#clock");
  if(S.style==="digital"){if(!c.querySelector(".dg"))c.innerHTML="<div class=dg></div>";c.className="digital"+(v.length<3?" two":"");c.firstChild.textContent=v.join(":");return}
  c.className=v.length>2?"three":"";
  if(c.children.length!==v.length)c.innerHTML=v.map(()=>"<div class=card><small></small><b></b></div>").join("");
  [...c.children].forEach((el,i)=>{const b=el.querySelector("b");
    if(b.textContent!==v[i]){b.textContent=v[i];b.classList.remove("f");void b.offsetWidth;b.classList.add("f")}
    el.querySelector("small").textContent=l[i]||""})}
function update(){let v,l,t="";
  if(mode==="clock"){const d=new Date();let h=d.getHours();if(!S.h24)h=h%12||12;
    v=[pad(h),pad(d.getMinutes()),pad(d.getSeconds())];l=[d.toLocaleDateString(undefined,{weekday:"long"}),"",S.h24?"":d.getHours()<12?"AM":"PM"];t=v.join(":")}
  else{const s=mode==="sw"?up:S.up?Math.max(0,TT-left):left,h=Math.floor(s/3600),m=Math.floor(s%3600/60),x=s%60;
    if(h>0){v=[pad(h),pad(m),pad(x)];l=["HR","MIN","SEC"]}else{v=[pad(m),pad(x)];l=["MIN","SEC"]}
    t=v.join(":")+(running?" ▶":"")}
  show(v,l);document.title=t+" · FlipFocus";
  const tot=mode==="pomo"||mode==="timer"?TT:0;$("#prog i").style.width=(tot?Math.max(0,Math.min(100,(1-left/tot)*100)):0)+"%";
  $("#phase").textContent=mode==="pomo"?({focus:"Focus",short:"Short break",long:"Long break"}[phase])+" · session "+(cycle%4+1)+"/4 · goal "+Math.round(TT/60)+" min":mode==="timer"?"Timer · goal "+Math.round(TT/60)+" min":mode==="sw"?"Stopwatch":new Date().toLocaleDateString(undefined,{weekday:"long",day:"numeric",month:"long"})}
function ui(){document.querySelectorAll("[data-m]").forEach(b=>b.classList.toggle("on",b.dataset.m===mode));
  const c=mode==="clock";$("#go").classList.toggle("hide",c);$("#rs").classList.toggle("hide",c);
  $("#m5").classList.toggle("hide",mode!=="timer");$("#p5").classList.toggle("hide",mode!=="timer");$("#nx").classList.toggle("hide",mode!=="pomo");
  $("#go").textContent=running?"Pause":"Start"}
async function lock(){if(!S.awake)return;try{wl=await navigator.wakeLock.request("screen")}catch(e){}}
function rel(){try{wl&&wl.release();wl=null}catch(e){}}
function beep(){if(S.vib)try{navigator.vibrate([300,150,300,150,500])}catch(e){}
  if(!S.sound)return;try{ac=ac||new(window.AudioContext||window.webkitAudioContext)();
    [0,.35,.7].forEach(t=>{const o=ac.createOscillator(),g=ac.createGain();o.frequency.value=880;o.connect(g);g.connect(ac.destination);
      g.gain.setValueAtTime(.3,ac.currentTime+t);g.gain.exponentialRampToValueAtTime(.001,ac.currentTime+t+.3);o.start(ac.currentTime+t);o.stop(ac.currentTime+t+.3)})}catch(e){}}
let ST={day:"",min:0,n:0,streak:0,last:""};
try{ST=Object.assign(ST,JSON.parse(localStorage.getItem("fstat")||"{}"))}catch(e){}
function today(){return new Date().toDateString()}
function stats(){if(ST.day!==today()){ST.day=today();ST.min=0;ST.n=0}$("#stats").innerHTML="<span>🎯 <b>"+ST.n+"</b> sessions</span><span>⏳ <b>"+ST.min+"</b> min today</span><span>🔥 <b>"+ST.streak+"</b> day streak</span>"}
function addStat(m){stats();ST.min+=m;ST.n++;if(ST.last!==today()){const y=new Date(Date.now()-864e5).toDateString();ST.streak=ST.last===y?ST.streak+1:1;ST.last=today()}try{localStorage.setItem("fstat",JSON.stringify(ST))}catch(e){}stats()}
function next(){if(phase==="focus"){cycle++;phase=cycle%4===0?"long":"short"}else phase="focus";resetTime()}
function toggle(){if(running){running=false;rel()}else{
    try{ac=ac||new(window.AudioContext||window.webkitAudioContext)()}catch(e){}
    if(mode!=="sw"&&left<=0)resetTime();
    running=true;if(mode==="sw")startAt=Date.now()-up*1000;else end=Date.now()+left*1000;lock()}
  ui();update()}
setInterval(()=>{if(mode==="clock")return update();
  if(!running)return;
  if(mode==="sw")up=Math.floor((Date.now()-startAt)/1000);
  else{left=Math.max(0,Math.ceil((end-Date.now())/1000));
    if(left===0){running=false;rel();beep();if(mode==="pomo"){if(phase==="focus")addStat(S.focus);next()}else{ui()}}}
  update()},200);
document.addEventListener("visibilitychange",()=>{if(!document.hidden&&running)lock()});

document.querySelectorAll("[data-m]").forEach(b=>b.onclick=()=>{mode=b.dataset.m;if(mode==="clock"){running=false;rel();ui();update()}else resetTime()});
$("#go").onclick=toggle;$("#rs").onclick=resetTime;$("#nx").onclick=()=>{if(mode==="pomo"){if(phase==="focus")cycle++;phase=phase==="focus"?(cycle%4===0?"long":"short"):"focus";resetTime()}};
$("#m5").onclick=()=>{const d=left-Math.max(60,left-300);left-=d;TT-=d;if(running)end=Date.now()+left*1000;update()};
$("#p5").onclick=()=>{left+=300;TT+=300;if(running)end=Date.now()+left*1000;update()};
$("#fs").onclick=async()=>{const on=!document.body.classList.contains("zen");document.body.classList.toggle("zen",on);
  try{on?await document.documentElement.requestFullscreen():document.fullscreenElement&&await document.exitFullscreen()}catch(e){}
  $("#fs").textContent=on?"✕ Exit full screen":"⛶ Full screen";wake()};
document.addEventListener("fullscreenchange",()=>{if(!document.fullscreenElement&&document.body.classList.contains("zen")){document.body.classList.remove("zen","idle");$("#fs").textContent="⛶ Full screen"}});
function wake(){document.body.classList.remove("idle");clearTimeout(idleT);idleT=setTimeout(()=>document.body.classList.add("idle"),3000)}
["mousemove","touchstart","keydown","click"].forEach(e=>document.addEventListener(e,wake,{passive:true}));
document.addEventListener("keydown",e=>{if(e.target.tagName==="INPUT")return;if(e.code==="Space"){e.preventDefault();if(mode!=="clock")toggle()}if(e.key==="f")$("#fs").click()});

function theme(){document.documentElement.dataset.theme=S.theme;document.querySelectorAll("#sw i").forEach(i=>i.classList.toggle("s",i.dataset.t===S.theme))}
$("#sw").innerHTML=Object.entries(THEMES).map(([k,c])=>`<i data-t="${k}" style="background:${c}" title="${k}"></i>`).join("");
document.querySelectorAll("#sw i").forEach(i=>i.onclick=()=>{S.theme=i.dataset.t;save();theme()});
function fill(){["focus","short","long","custom"].forEach(k=>$("#"+k).value=S[k]);["up","sound","vib","h24","awake"].forEach(k=>$("#"+k).checked=S[k])}
["focus","short","long","custom"].forEach(k=>$("#"+k).onchange=e=>{S[k]=Math.max(1,Math.min(600,+e.target.value||DEF[k]));save();if(!running&&mode!=="clock"&&mode!=="sw")resetTime()});
["up","sound","vib","h24","awake"].forEach(k=>$("#"+k).onchange=e=>{S[k]=e.target.checked;save();update()});
$("#st").onclick=()=>{fill();$("#set").hidden=false};$("#ok").onclick=()=>$("#set").hidden=true;
$("#def").onclick=()=>{S=Object.assign({},DEF);save();fill();theme();resetTime()};
function sy(){$("#sy").textContent=S.style==="flip"?"🔢 Digital":"🃏 Flip"}
$("#sy").onclick=()=>{S.style=S.style==="flip"?"digital":"flip";save();sy();update()};
theme();stats();sy();resetTime();wake();setTimeout(()=>$("#splash").classList.add("gone"),900);
</script>
</body>
</html>
