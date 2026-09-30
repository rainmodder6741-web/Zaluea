<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Spectrum</title>
<link rel="shortcut icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 32 32'%3E%3Crect width='32' height='32' rx='9' fill='%237c5cff'/%3E%3Cpath d='M9 10h14l-10 12h10' fill='none' stroke='white' stroke-width='3' stroke-linecap='round' stroke-linejoin='round'/%3E%3C/svg%3E">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Sora:wght@400;600;800&display=swap" rel="stylesheet">
<style>
:root{
  --bg:#0d0b1e; --ink:#f3f0ff; --muted:#a9a3cf; --panel:rgba(28,24,60,.72);
  --line:rgba(255,255,255,.12); --accent:#7c5cff; --accent2:#ff6fae; --ok:#5ce1b4;
}
@media (prefers-color-scheme: light){
  :root:not([data-theme="dark"]){
    --bg:#efeaff; --ink:#1b1540; --muted:#5d5690; --panel:rgba(255,255,255,.78); --line:rgba(27,21,64,.14);
  }
}
:root[data-theme="light"]{--bg:#efeaff;--ink:#1b1540;--muted:#5d5690;--panel:rgba(255,255,255,.78);--line:rgba(27,21,64,.14)}
*{box-sizing:border-box}
html,body{height:100%;margin:0}
:root{padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
body{
  background:var(--bg); color:var(--ink); font-family:'Sora',system-ui,sans-serif;
  overflow:hidden; position:relative;
}
.glow{position:fixed;border-radius:50%;filter:blur(90px);opacity:.55;pointer-events:none}
.g1{width:46vmax;height:46vmax;left:-14vmax;top:-16vmax;background:var(--accent)}
.g2{width:38vmax;height:38vmax;right:-12vmax;bottom:-14vmax;background:var(--accent2)}

header{position:fixed;top:env(safe-area-inset-top,0px);left:0;right:0;display:flex;justify-content:space-between;align-items:center;padding:18px 22px;z-index:5}
.logo{font-weight:800;font-size:1.25rem;letter-spacing:-.02em}
.nav{display:flex;gap:10px}
.btn{
  font:inherit;font-size:.85rem;font-weight:600;color:var(--ink);cursor:pointer;
  background:var(--panel);border:1px solid var(--line);border-radius:999px;padding:9px 16px;
  backdrop-filter:blur(14px);-webkit-backdrop-filter:blur(14px);transition:transform .15s,border-color .15s;
}
.btn:hover{border-color:var(--accent);transform:translateY(-1px)}
.btn:focus-visible,input:focus-visible{outline:2px solid var(--accent2);outline-offset:2px}
.btn[aria-expanded="true"]{background:var(--accent);border-color:var(--accent);color:#fff}

main{height:100%;display:grid;place-items:center;text-align:center;padding:24px}
h1{font-size:clamp(3.2rem,15vw,9rem);font-weight:800;letter-spacing:-.06em;line-height:.9;margin:0;
  background:linear-gradient(120deg,var(--ink) 30%,var(--accent2));-webkit-background-clip:text;background-clip:text;color:transparent}
main p{color:var(--muted);margin:18px 0 0;font-size:1rem}

.drawer{
  position:fixed;top:calc(env(safe-area-inset-top,0px) + 72px);right:16px;width:min(360px,calc(100% - 32px));
  max-height:calc(100% - 96px);overflow:auto;z-index:6;
  background:var(--panel);border:1px solid var(--line);border-radius:22px;padding:22px;
  backdrop-filter:blur(20px);-webkit-backdrop-filter:blur(20px);
  box-shadow:0 24px 60px rgba(0,0,0,.35);
  opacity:0;transform:translateY(-8px) scale(.98);visibility:hidden;
  transition:opacity .2s,transform .2s,visibility .2s;
}
.drawer.open{opacity:1;transform:none;visibility:visible}
.drawer h2{margin:0 0 4px;font-size:1.1rem}
.drawer .sub{margin:0 0 18px;color:var(--muted);font-size:.82rem}
label{display:block;font-size:.8rem;font-weight:600;margin:14px 0 6px}
input{
  width:100%;font:inherit;font-size:.9rem;color:var(--ink);background:rgba(127,120,200,.12);
  border:1px solid var(--line);border-radius:12px;padding:11px 13px;
}
.row{display:flex;gap:8px}
.row input{flex:1}
.hint{font-size:.75rem;color:var(--muted);margin-top:6px}
.danger{margin-top:22px;padding-top:16px;border-top:1px solid var(--line)}
.btn.warn{color:var(--accent2);border-color:var(--accent2);width:100%}
.btn.go{background:var(--accent);border-color:var(--accent);color:#fff}
.toast{position:fixed;left:50%;bottom:calc(env(safe-area-inset-bottom,0px) + 24px);transform:translate(-50%,20px);
  background:var(--ok);color:#06251b;font-weight:600;font-size:.85rem;padding:10px 18px;border-radius:999px;
  opacity:0;transition:.25s;z-index:9;pointer-events:none}
.toast.show{opacity:1;transform:translate(-50%,0)}

.log{list-style:none;margin:0;padding:0 0 0 16px;border-left:2px solid var(--line)}
.log li{position:relative;margin-bottom:18px}
.log li::before{content:"";position:absolute;left:-23px;top:5px;width:10px;height:10px;border-radius:50%;background:var(--accent);box-shadow:0 0 0 4px var(--panel)}
.log b{display:block;font-size:.9rem}
.log time{font-size:.72rem;color:var(--muted)}
.log span{display:block;font-size:.83rem;color:var(--muted);margin-top:3px}
@media (prefers-reduced-motion:reduce){*{transition:none!important}}
</style>
</head>
<body>
<div class="glow g1"></div><div class="glow g2"></div>

<header>
  <div class="logo">Spectrum</div>
  <nav class="nav">
    <button class="btn" id="updatesBtn" aria-expanded="false" aria-controls="updates" onclick="updates()">Updates</button>
    <button class="btn" id="settingsBtn" aria-expanded="false" aria-controls="settings" onclick="settings()">Settings</button>
  </nav>
</header>

<main>
  <div>
    <h1>Spectrum</h1>
    <p>Make it yours: change the tab title and icon in Settings.</p>
  </div>
</main>

<section class="drawer" id="settings" aria-label="Settings">
  <h2>Settings</h2>
  <p class="sub">Saved in this browser only.</p>

  <label for="titleInput">Tab title</label>
  <div class="row">
    <input id="titleInput" placeholder="Spectrum" autocomplete="off">
    <button class="btn go" onclick="titleSet(document.getElementById('titleInput').value)">Save</button>
  </div>
  <div class="hint">Leave empty and save to restore the default.</div>

  <label for="icoInput">Tab icon URL</label>
  <div class="row">
    <input id="icoInput" placeholder="https://example.com/icon.png" autocomplete="off">
    <button class="btn go" onclick="icoSet(document.getElementById('icoInput').value)">Save</button>
  </div>

  <div class="danger">
    <button class="btn warn" onclick="reset()">Reset all settings</button>
  </div>
</section>

<section class="drawer" id="updates" aria-label="Updates">
  <h2>Updates</h2>
  <p class="sub">What's new in Spectrum.</p>
  <ul class="log">
    <li><b>New settings panel</b><time>Latest</time><span>Change your tab title and icon, and reset with one click.</span></li>
    <li><b>Title saved between visits</b><time>Earlier</time><span>Your custom title now stays after you reload.</span></li>
  </ul>
</section>

<div class="toast" id="toast" role="status"></div>

<script>
/* ---------- safe storage helpers ---------- */
function store(key, val){ try{ if(val===null) localStorage.removeItem(key); else localStorage.setItem(key,val);}catch(e){} }
function load(key){ try{ return localStorage.getItem(key);}catch(e){ return null; } }

/* ---------- panels ---------- */
function toggle(id, btnId){
  var el = document.getElementById(id);
  var open = !el.classList.contains("open");
  closePanels();
  if(open){
    el.classList.add("open");
    document.getElementById(btnId).setAttribute("aria-expanded","true");
  }
}
function closePanels(){
  ["settings","updates"].forEach(function(id){ document.getElementById(id).classList.remove("open"); });
  document.getElementById("settingsBtn").setAttribute("aria-expanded","false");
  document.getElementById("updatesBtn").setAttribute("aria-expanded","false");
}
function settings(){ toggle("settings","settingsBtn"); }
function updates(){ toggle("updates","updatesBtn"); }

document.addEventListener("keydown", function(e){ if(e.key==="Escape") closePanels(); });
document.addEventListener("click", function(e){
  if(!e.target.closest(".drawer") && !e.target.closest(".nav")) closePanels();
});

/* ---------- toast ---------- */
var toastTimer;
function toast(msg){
  var t = document.getElementById("toast");
  t.textContent = msg; t.classList.add("show");
  clearTimeout(toastTimer);
  toastTimer = setTimeout(function(){ t.classList.remove("show"); }, 1800);
}

/* ---------- title ---------- */
var savedTitle = load("title");
if(savedTitle){ document.title = savedTitle; document.getElementById("titleInput").value = savedTitle; }

function titleSet(text){
  text = (text || "").trim();
  if(text !== ""){
    document.title = text;
    store("title", text);
    toast("Title saved");
  } else {
    store("title", null);
    document.title = "Spectrum";
    toast("Title restored");
  }
}

/* ---------- icon ---------- */
function iconLink(){
  var link = document.querySelector("link[rel='shortcut icon']");
  if(!link){
    link = document.createElement("link");
    link.rel = "shortcut icon";
    document.head.appendChild(link);
  }
  return link;
}
var defaultIcon = iconLink().href;
var savedIcon = load("icon");
if(savedIcon){ iconLink().href = savedIcon; document.getElementById("icoInput").value = savedIcon; }

function icoSet(url){
  url = (url || "").trim();
  if(url !== ""){
    iconLink().href = url;
    store("icon", url);
    toast("Icon saved");
  } else {
    iconLink().href = defaultIcon;
    store("icon", null);
    toast("Icon restored");
  }
}

/* ---------- reset ---------- */
function reset(){
  store("title", null);
  store("icon", null);
  window.location.reload();
}
</script>
</body>
</html>
