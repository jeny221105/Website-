
<!doctype html>
<html lang="en">
<head>
 <meta charset="utf-8" />
 <meta name="viewport" content="width=device-width, initial-scale=1" />
 <title>Indigo Wildcat — Cat Love Game</title>
 <style>
 :root{
 --bg:#12060b;
 --panel:#1b0a10;
 --wine:#7a1431; /* burgundy */
 --wine2:#a61f43;
 --text:#f6eef1;
 --muted:#d9b9c2;
 --card:#240d15;
 --shadow: 0 18px 50px rgba(0,0,0,.45);
 }
 *{box-sizing:border-box}
 body{
 margin:0; font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial,sans-serif;
 background: radial-gradient(1200px 600px at 20% 10%, rgba(166,31,67,.25), transparent 60%),
 radial-gradient(900px 500px at 80% 20%, rgba(122,20,49,.22), transparent 55%),
 var(--bg);
 color:var(--text);
 min-height:100vh;
 display:flex;
 align-items:center;
 justify-content:center;
 padding:18px;
 }
 .wrap{width:min(980px, 100%); display:grid; gap:16px}
 header{
 background: linear-gradient(180deg, rgba(122,20,49,.35), rgba(27,10,16,.65));
 border:1px solid rgba(166,31,67,.35);
 border-radius:18px;
 padding:16px 18px;
 box-shadow:var(--shadow);
 }
 header h1{margin:0; font-size:18px; letter-spacing:.2px}
 header p{margin:6px 0 0; color:var(--muted); font-size:13px; line-height:1.4}
 .grid{display:grid; gap:16px; grid-template-columns: 1.2fr .8fr}
 @media (max-width: 900px){ .grid{grid-template-columns:1fr} }
 .panel{
 background: rgba(27,10,16,.72);
 border:1px solid rgba(166,31,67,.28);
 border-radius:18px;
 padding:16px;
 box-shadow:var(--shadow);
 }
 .cats{display:grid; grid-template-columns:1fr 1fr; gap:12px}
 .cat{
 background: linear-gradient(180deg, rgba(36,13,21,.95), rgba(18,6,11,.6));
 border:1px solid rgba(166,31,67,.25);
 border-radius:16px;
 padding:14px;
 position:relative;
 overflow:hidden;
 cursor:pointer;
 transition: transform .12s ease, border-color .12s ease;
 user-select:none;
 min-height:210px;
 }
 .cat:hover{transform: translateY(-2px); border-color: rgba(166,31,67,.55)}
 .tag{
 display:inline-flex; gap:8px; align-items:center;
 font-size:12px; color:var(--muted);
 padding:6px 10px; border-radius:999px;
 border:1px solid rgba(217,185,194,.22);
 background: rgba(18,6,11,.35);
 }
 .big{
 font-size:44px;
 margin:18px 0 6px;
 filter: drop-shadow(0 12px 22px rgba(0,0,0,.5));
 animation: float 2.2s ease-in-out infinite;
 }
 .cat .name{font-weight:700; margin:0}
 .cat .hint{margin:6px 0 0; color:var(--muted); font-size:13px; line-height:1.4}
 .pulse{
 position:absolute; inset:auto -40px -40px auto;
 width:140px; height:140px; border-radius:50%;
 background: radial-gradient(circle at 30% 30%, rgba(166,31,67,.55), transparent 60%);
 filter: blur(2px);
 animation: pulse 2.6s ease-in-out infinite;
 }
 @keyframes pulse{ 0%,100%{transform:scale(1)} 50%{transform:scale(1.08)} }
 @keyframes float{ 0%,100%{transform: translateY(0)} 50%{transform: translateY(-4px)} }

 .controls{display:grid; gap:10px; margin-top:12px}
 label{font-size:12px; color:var(--muted)}
 input[type="text"]{
 width:100%;
 padding:12px 12px;
 border-radius:12px;
 border:1px solid rgba(166,31,67,.35);
 background: rgba(18,6,11,.55);
 color:var(--text);
 outline:none;
 }
 input[type="text"]:focus{border-color: rgba(166,31,67,.8)}
 .btns{display:flex; gap:10px; flex-wrap:wrap}
 button{
 border:0;
 padding:10px 12px;
 border-radius:12px;
 cursor:pointer;
 color:var(--text);
 background: linear-gradient(180deg, var(--wine2), var(--wine));
 box-shadow: 0 10px 24px rgba(166,31,67,.22);
 font-weight:650;
 }
 button.secondary{
 background: rgba(217,185,194,.12);
 border:1px solid rgba(217,185,194,.22);
 box-shadow:none;
 color:var(--muted);
 }
 .status{
 margin-top:12px;
 padding:12px;
 border-radius:14px;
 border:1px solid rgba(166,31,67,.28);
 background: rgba(18,6,11,.35);
 color:var(--muted);
 min-height:54px;
 display:flex; align-items:center;
 }
 .love{
 margin-top:12px;
 padding:14px;
 border-radius:16px;
 border:1px solid rgba(166,31,67,.45);
 background: linear-gradient(180deg, rgba(166,31,67,.18), rgba(18,6,11,.35));
 display:none;
 }
 .love h3{margin:0 0 6px; font-size:14px}
 .love p{margin:0; font-size:14px; line-height:1.45}
 .tiny{margin-top:10px; font-size:12px; color:rgba(217,185,194,.75)}
 .scoreRow{display:flex; align-items:center; justify-content:space-between; gap:12px; margin-top:10px}
 .bar{height:10px; flex:1; border-radius:999px; background: rgba(217,185,194,.12); overflow:hidden; border:1px solid rgba(217,185,194,.16)}
 .fill{height:100%; width:0%; background: linear-gradient(90deg, var(--wine), var(--wine2)); transition: width .35s ease}
 .score{font-size:12px; color:var(--muted); white-space:nowrap}
 </style>
</head>
<body>
 <div class="wrap">
 <header>
 <h1>Indigo Wildcat — Cat Love Game</h1>
 <p>Pick a cat 5 times. Then type your own love message — it will appear exactly as you wrote it.</p>
 </header>

 <div class="grid">
 <div class="panel">
 <div class="cats" id="cats">
 <div class="cat" data-cat="Orange Cat">
 <span class="tag">🍊 Orange Cat • playful</span>
 <div class="big">🐱</div>
 <p class="name">Orange Cat</p>
 <p class="hint">Tap me for a silly animation and +1 love point.</p>
 <div class="pulse"></div>
 </div>

 <div class="cat" data-cat="Gray Cat">
 <span class="tag">🌫️ Gray Cat • calm</span>
 <div class="big" style="animation-delay:.2s">🐈‍⬛</div>
 <p class="name">Gray Cat</p>
 <p class="hint">Tap me for a cute animation and +1 love point.</p>
 <div class="pulse" style="opacity:.7"></div>
 </div>
 </div>

 <div class="status" id="status">Choose a cat to start.</div>

 <div class="scoreRow" aria-hidden="true">
 <div class="bar"><div class="fill" id="fill"></div></div>
 <div class="score" id="score">0 / 5</div>
 </div>

 <div class="controls">
 <div>
 <label for="msg">Your love message (shown exactly as typed)</label>
 <input id="msg" type="text" maxlength="120" placeholder="Type something sweet…" />
 </div>
 <div class="btns">
 <button id="show">Show my love message</button>
 <button class="secondary" id="reset" type="button">Reset</button>
 </div>
 </div>

 <div class="love" id="loveBox">
 <h3>Love Message</h3>
 <p id="loveText"></p>
 <div class="tiny" id="signature">— from the cats</div>
 </div>
 </div>

 <div class="panel">
 <h2 style="margin:0 0 10px; font-size:16px;">How it works</h2>
 <ul style="margin:0; padding-left:18px; color:var(--muted); line-height:1.6; font-size:13px;">
 <li>Each tap is a “round” (5 rounds total).</li>
 <li>At 5/5 rounds, the cats celebrate.</li>
 <li>You can type any message; it appears exactly as you wrote it.</li>
 </ul>
 <div style="margin-top:12px; padding:12px; border-radius:14px; border:1px dashed rgba(217,185,194,.22); color:var(--muted); font-size:13px;">
 Want it more “gamey”? Later we can add: timer, random mood cards, sound toggle, and more animations.
 </div>
 </div>
 </div>
 </div>

 <script>
 const statusEl = document.getElementById('status');
 const fillEl = document.getElementById('fill');
 const scoreEl = document.getElementById('score');
 const msgEl = document.getElementById('msg');
 const showBtn = document.getElementById('show');
 const resetBtn = document.getElementById('reset');
 const loveBox = document.getElementById('loveBox');
 const loveText = document.getElementById('loveText');

 let rounds = 0;
 const total = 5;

 const reactions = {
 "Orange Cat": ["*boing!* tail wiggle!", "*blink blink!* happy jump!", "*spin!* orange zoom!"],
 "Gray Cat": ["*soft purr* slow blink.", "*tiny bow* gentle tail wave.", "*hop* calm sparkle."]
 };

 function updateUI() {
 const pct = Math.round((rounds / total) * 100);
 fillEl.style.width = pct + "%";
 scoreEl.textContent = `${rounds} / ${total}`;
 if (rounds === 0) statusEl.textContent = "Choose a cat to start.";
 if (rounds >= total) statusEl.textContent = "5/5! The cats are ready for your love message.";
 }

 document.getElementById('cats').addEventListener('click', (e) => {
 const card = e.target.closest('.cat');
 if (!card) return;

 const catName = card.dataset.cat;
 if (rounds >= total) {
 statusEl.textContent = "You already finished 5 rounds — now type your message and press the button.";
 return;
 }

 rounds++;
 const list = reactions[catName] || ["*meow!*"];
 const reaction = list[Math.floor(Math.random() * list.length)];
 statusEl.textContent = `${catName} says: ${reaction} (+1 love)`;
 updateUI();
 });

 showBtn.addEventListener('click', () => {
 const txt = msgEl.value.trim();
 if (!txt) {
 statusEl.textContent = "Type a love message first.";
 return;
 }
 loveText.textContent = txt; // exactly as typed
 loveBox.style.display = "block";
 statusEl.textContent = "Love message delivered.";
 });

 resetBtn.addEventListener('click', () => {
 rounds = 0;
 msgEl.value = "";
 loveBox.style.display = "none";
 updateUI();
 });

 updateUI();
 </script>
</body>
</html>


