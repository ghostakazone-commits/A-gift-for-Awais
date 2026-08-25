<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>AWAIS — The Great Kaka Line</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Bungee&family=Space+Grotesk:wght@400;500;700&family=JetBrains+Mono:wght@500;700&display=swap" rel="stylesheet">
<style>
  :root{
    --void:#0a0713;
    --void-2:#120b24;
    --hot:#ff2ea6;
    --cyan:#2ee6ff;
    --gold:#ffd23f;
    --violet:#9b5cff;
    --paper:#f4f1ea;
    --dim: rgba(244,241,234,0.62);
  }

  *{box-sizing:border-box;}
  html,body{margin:0;padding:0; width:100%; overflow-x:hidden;}

  body{
    min-height:100vh;
    min-height:100dvh;
    background:
      radial-gradient(ellipse 80% 60% at 20% -10%, rgba(155,92,255,0.35), transparent 60%),
      radial-gradient(ellipse 70% 50% at 90% 100%, rgba(46,230,255,0.22), transparent 60%),
      var(--void);
    overflow-x:hidden;
    font-family:'Space Grotesk', sans-serif;
    color:var(--paper);
    position:relative;
  }

  /* ---------- floating particle field ---------- */
  #field{
    position:fixed; inset:0; z-index:0; pointer-events:none;
  }
  .spark{
    position:absolute;
    border-radius:50%;
    filter:blur(0.5px);
    animation:drift linear infinite;
    opacity:0.8;
  }
  @keyframes drift{
    0%{ transform:translateY(0) translateX(0) scale(1); }
    50%{ transform:translateY(-40px) translateX(18px) scale(1.15); }
    100%{ transform:translateY(0) translateX(0) scale(1); }
  }

  /* ---------- layout ---------- */
  .stage{
    position:relative;
    z-index:2;
    min-height:100vh;
    min-height:100dvh;
    width:100%;
    display:flex;
    flex-direction:column;
    align-items:center;
    justify-content:center;
    padding:48px 16px 70px;
  }

  .eyebrow{
    font-family:'JetBrains Mono', monospace;
    letter-spacing:0.35em;
    text-transform:uppercase;
    font-size:11px;
    color:var(--cyan);
    opacity:0;
    animation:fadeUp 0.8s 0.1s forwards ease-out;
    margin-bottom:14px;
    display:flex; align-items:center; gap:10px;
  }
  .eyebrow::before, .eyebrow::after{
    content:"";
    width:26px; height:1px;
    background:linear-gradient(90deg,transparent,var(--cyan));
  }
  .eyebrow::after{ background:linear-gradient(90deg,var(--cyan),transparent); }

  @keyframes fadeUp{
    from{opacity:0; transform:translateY(14px);}
    to{opacity:1; transform:translateY(0);}
  }

  /* ---------- 3D card ---------- */
  .card-wrap{
    perspective:1600px;
    opacity:0;
    animation:fadeUp 0.9s 0.25s forwards ease-out;
    touch-action:none;
  }

  .card{
    width:min(88vw, 380px);
    max-width:380px;
    border-radius:26px;
    padding:3px;
    background:conic-gradient(from 0deg, var(--hot), var(--gold), var(--cyan), var(--violet), var(--hot));
    background-size:300% 300%;
    animation:foilspin 6s linear infinite;
    transform-style:preserve-3d;
    transition:transform 0.12s ease-out;
    box-shadow:
      0 30px 60px -20px rgba(0,0,0,0.7),
      0 0 90px -20px rgba(155,92,255,0.55);
    cursor:pointer;
    will-change:transform;
    touch-action:none;
  }
  @keyframes foilspin{
    0%{background-position:0% 50%;}
    100%{background-position:300% 50%;}
  }

  .card-inner{
    background:linear-gradient(180deg, #16102b 0%, #0d0918 100%);
    border-radius:23px;
    padding:22px 22px 26px;
    position:relative;
    overflow:hidden;
    transform-style:preserve-3d;
  }

  /* holographic sweep */
  .card-inner::before{
    content:"";
    position:absolute; inset:-40%;
    background:linear-gradient(115deg, transparent 40%, rgba(255,255,255,0.16) 48%, rgba(46,230,255,0.22) 50%, transparent 60%);
    transform:translateX(-120%);
    animation:sweep 3.2s ease-in-out infinite;
    pointer-events:none;
  }
  @keyframes sweep{
    0%,100%{ transform:translateX(-140%) rotate(8deg); }
    50%{ transform:translateX(140%) rotate(8deg); }
  }

  .card-tag{
    display:flex; justify-content:space-between; align-items:center;
    font-family:'JetBrains Mono', monospace;
    font-size:10px; letter-spacing:0.18em;
    color:var(--dim);
    margin-bottom:14px;
    text-transform:uppercase;
  }
  .card-tag span:last-child{ color:var(--gold); }

  .photo-frame{
    position:relative;
    border-radius:18px;
    overflow:hidden;
    aspect-ratio:3/3.6;
    transform:translateZ(40px);
    box-shadow:0 18px 40px -12px rgba(0,0,0,0.65);
    border:1px solid rgba(255,255,255,0.08);
  }
  .photo-frame img{
    width:100%; height:100%; object-fit:cover; display:block;
    filter:saturate(1.08) contrast(1.05);
  }
  .photo-frame::after{
    content:"";
    position:absolute; inset:0;
    background:linear-gradient(180deg, transparent 55%, rgba(10,7,19,0.92) 100%);
  }
  .rank-badge{
    position:absolute; top:10px; right:10px;
    width:40px; height:40px; border-radius:50%;
    background:radial-gradient(circle at 35% 30%, var(--gold), #b8860b);
    display:flex; align-items:center; justify-content:center;
    font-family:'Bungee', sans-serif;
    font-size:14px; color:#2a1a00;
    box-shadow:0 6px 14px rgba(0,0,0,0.5), inset 0 0 0 2px rgba(255,255,255,0.3);
    z-index:2;
    animation:spin3d 5s linear infinite;
    transform-style:preserve-3d;
  }
  @keyframes spin3d{
    0%{ transform:rotateY(0deg); }
    100%{ transform:rotateY(360deg); }
  }

  .name-plate{
    position:absolute; left:14px; bottom:14px; z-index:2;
  }

  .name{
    font-family:'Bungee', sans-serif;
    font-size:clamp(30px, 8vw, 40px);
    line-height:0.95;
    background:linear-gradient(92deg, var(--gold) 0%, var(--hot) 35%, var(--cyan) 70%, var(--violet) 100%);
    background-size:250% auto;
    -webkit-background-clip:text;
    background-clip:text;
    color:transparent;
    animation:hue 4s linear infinite;
    text-shadow:0 0 40px rgba(255,46,166,0.25);
    letter-spacing:0.5px;
  }
  @keyframes hue{
    0%{ background-position:0% 50%; }
    100%{ background-position:250% 50%; }
  }

  .subtitle{
    font-family:'JetBrains Mono', monospace;
    font-size:11px; letter-spacing:0.14em;
    color:var(--dim);
    margin-top:2px;
  }

  .stat-row{
    display:grid; grid-template-columns:1fr 1fr; gap:10px;
    margin-top:16px;
    transform:translateZ(25px);
  }
  .stat{
    background:rgba(255,255,255,0.03);
    border:1px solid rgba(255,255,255,0.08);
    border-radius:12px;
    padding:10px 12px;
  }
  .stat b{
    display:block; font-family:'JetBrains Mono', monospace;
    font-size:10px; letter-spacing:0.12em; color:var(--cyan);
    text-transform:uppercase; margin-bottom:4px;
  }
  .stat span{ font-size:13px; color:var(--paper); }

  .desc-box{
    margin-top:16px;
    padding:16px;
    border-radius:14px;
    background:linear-gradient(160deg, rgba(255,46,166,0.08), rgba(46,230,255,0.06));
    border:1px solid rgba(255,255,255,0.08);
    transform:translateZ(30px);
    position:relative;
  }
  .desc-box b{
    display:block; font-family:'JetBrains Mono', monospace;
    font-size:10px; letter-spacing:0.16em; color:var(--gold);
    text-transform:uppercase; margin-bottom:8px;
  }
  .glitch{
    font-family:'Bungee', sans-serif;
    font-size:clamp(22px, 6vw, 30px);
    position:relative;
    color:var(--paper);
    letter-spacing:1px;
    display:inline-block;
  }
  .glitch::before, .glitch::after{
    content:"AAAAA THO";
    position:absolute; left:0; top:0; width:100%;
    overflow:hidden;
  }
  .glitch::before{
    color:var(--hot);
    animation:glitch1 2.6s infinite linear alternate-reverse;
    clip-path:inset(0 0 55% 0);
  }
  .glitch::after{
    color:var(--cyan);
    animation:glitch2 2.2s infinite linear alternate-reverse;
    clip-path:inset(55% 0 0 0);
  }
  @keyframes glitch1{
    0%{ transform:translate(0,0); }
    20%{ transform:translate(-3px,1px); }
    40%{ transform:translate(3px,-1px); }
    60%{ transform:translate(-2px,0); }
    80%{ transform:translate(2px,1px); }
    100%{ transform:translate(0,0); }
  }
  @keyframes glitch2{
    0%{ transform:translate(0,0); }
    25%{ transform:translate(3px,-1px); }
    50%{ transform:translate(-3px,1px); }
    75%{ transform:translate(2px,0); }
    100%{ transform:translate(0,0); }
  }

  .kaka-line{
    margin-top:20px;
    display:flex; align-items:center; justify-content:center; gap:10px;
    transform:translateZ(35px);
  }
  .kaka-line .rule{
    flex:1; height:1px;
    background:linear-gradient(90deg, transparent, rgba(255,210,63,0.6), transparent);
  }
  .kaka-line .badge{
    font-family:'JetBrains Mono', monospace;
    font-size:11px; letter-spacing:0.16em;
    text-transform:uppercase;
    padding:8px 14px;
    border-radius:999px;
    background:rgba(255,210,63,0.1);
    border:1px solid rgba(255,210,63,0.5);
    color:var(--gold);
    white-space:nowrap;
    animation:pulseGlow 2.4s ease-in-out infinite;
  }
  @keyframes pulseGlow{
    0%,100%{ box-shadow:0 0 0px rgba(255,210,63,0.0); }
    50%{ box-shadow:0 0 18px rgba(255,210,63,0.55); }
  }

  .hint{
    margin-top:26px;
    font-family:'JetBrains Mono', monospace;
    font-size:11px;
    color:var(--dim);
    letter-spacing:0.08em;
    opacity:0;
    animation:fadeUp 0.8s 0.6s forwards ease-out;
    display:flex; align-items:center; gap:8px;
  }
  .hint .dot{
    width:6px; height:6px; border-radius:50%;
    background:var(--hot);
    animation:blink 1.4s ease-in-out infinite;
  }
  @keyframes blink{ 0%,100%{opacity:1;} 50%{opacity:0.2;} }

  /* ---------- coin counter ---------- */
  .coin-counter{
    position:absolute; top:10px; left:10px; z-index:3;
    display:flex; align-items:center; gap:6px;
    padding:6px 12px 6px 8px;
    border-radius:999px;
    background:rgba(10,7,19,0.55);
    border:1px solid rgba(255,210,63,0.5);
    backdrop-filter:blur(4px);
    font-family:'JetBrains Mono', monospace;
    font-size:12px; font-weight:700;
    color:var(--gold);
  }
  .coin-icon{
    width:18px; height:18px; border-radius:50%;
    background:radial-gradient(circle at 35% 30%, #fff2b0, var(--gold) 55%, #a67200);
    box-shadow:0 0 8px rgba(255,210,63,0.7);
    display:inline-block;
    animation:coinSpin 2.4s linear infinite;
  }
  @keyframes coinSpin{
    0%{ transform:rotateY(0deg); }
    100%{ transform:rotateY(360deg); }
  }

  .photo-frame{ user-select:none; -webkit-tap-highlight-color:transparent; touch-action:manipulation; }
  .photo-frame.tapped{
    animation:tapPunch 0.28s ease-out;
  }
  @keyframes tapPunch{
    0%{ transform:translateZ(40px) scale(1); }
    35%{ transform:translateZ(40px) scale(0.94) rotate(-1deg); }
    60%{ transform:translateZ(40px) scale(1.04) rotate(1deg); }
    100%{ transform:translateZ(40px) scale(1); }
  }

  .coin-pop{
    position:absolute;
    pointer-events:none;
    z-index:5;
    font-family:'Bungee', sans-serif;
    font-size:20px;
    color:var(--gold);
    text-shadow:0 0 10px rgba(255,210,63,0.9), 0 2px 4px rgba(0,0,0,0.6);
    animation:coinFloat 0.9s ease-out forwards;
  }
  @keyframes coinFloat{
    0%{ opacity:0; transform:translate(-50%,-50%) scale(0.6); }
    15%{ opacity:1; transform:translate(-50%,-70%) scale(1.15); }
    100%{ opacity:0; transform:translate(-50%,-160%) scale(1); }
  }

  .uff-flash{
    position:absolute; inset:0; z-index:1;
    background:rgba(255,46,166,0.0);
    pointer-events:none;
  }
  .uff-flash.on{
    animation:flashHit 0.28s ease-out;
  }
  @keyframes flashHit{
    0%{ background:rgba(255,46,166,0.35); }
    100%{ background:rgba(255,46,166,0.0); }
  }

  @media (max-width:480px){
    .card{ width:88vw; }
  }

  @media (prefers-reduced-motion: reduce){
    *, *::before, *::after{
      animation-duration:0.001ms !important;
      animation-iteration-count:1 !important;
      transition:none !important;
    }
  }

  /* ---------- touch / low-power devices: cut the heavy stuff ---------- */
  @media (hover: none), (pointer: coarse){
    .card{
      animation:none;
      background:linear-gradient(135deg, var(--hot), var(--gold), var(--cyan), var(--violet));
    }
    .card-inner::before{ animation:none; display:none; }
    .rank-badge{ animation:none; }
    .coin-icon{ animation:none; }
    .coin-counter{ backdrop-filter:none; background:rgba(10,7,19,0.8); }
    .name{ animation:none; background-position:0% 50%; }
    .spark{ display:none; }
    .spark:nth-child(-n+14){ display:block; filter:none; }
    .card{ box-shadow:0 18px 34px -16px rgba(0,0,0,0.7); }
  }

  @media (max-height: 700px){
    .stage{ padding:28px 16px 40px; }
    .card{ width:min(80vw, 340px); }
  }
</style>
</head>
<body>

<div id="field"></div>

<div class="stage">
  <div class="eyebrow">Official Player Card</div>

  <div class="card-wrap" id="cardWrap">
    <div class="card" id="card">
      <div class="card-inner">
        <div class="card-tag">
          <span>SCALE REBORN STUDIO™</span>
          <span>NO. 001</span>
        </div>

        <div class="coin-counter"><span class="coin-icon"></span><span id="coinCount">0</span></div>

        <div class="photo-frame" id="photoFrame">
          <div class="uff-flash" id="uffFlash"></div>
          <img src="data:image/jpeg;base64,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" alt="Awais">
          <div class="rank-badge">S+</div>
          <div class="name-plate">
            <div class="name">Awais</div>
            <div class="subtitle">chief hairline strategist</div>
          </div>
        </div>

        <div class="stat-row">
          <div class="stat"><b>Class</b><span>2nd Year</span></div>
          <div class="stat"><b>Power</b><span>Unlimited Knowledge</span></div>
        </div>

        <div class="desc-box">
          <b>Description</b>
          <div class="glitch">AAAAA THO</div>
        </div>

        <div class="kaka-line">
          <div class="rule"></div>
          <div class="badge">The Great Kaka</div>
          <div class="rule"></div>
        </div>
      </div>
    </div>
  </div>

  <div class="hint"><span class="dot"></span>move to tilt the card · tap the photo to earn coins</div>
</div>

<script>
  // particle field
  const field = document.getElementById('field');
  const colors = ['#ff2ea6','#2ee6ff','#ffd23f','#9b5cff'];
  const count = window.innerWidth < 600 ? 26 : 46;
  for(let i=0;i<count;i++){
    const s = document.createElement('div');
    s.className = 'spark';
    const size = Math.random()*4 + 2;
    s.style.width = size+'px';
    s.style.height = size+'px';
    s.style.left = Math.random()*100+'vw';
    s.style.top = Math.random()*100+'vh';
    s.style.background = colors[i % colors.length];
    s.style.boxShadow = '0 0 '+(size*3)+'px '+colors[i % colors.length];
    s.style.animationDuration = (4 + Math.random()*6)+'s';
    s.style.animationDelay = (Math.random()*4)+'s';
    field.appendChild(s);
  }

  // 3D tilt — mouse-drag on desktop, finger-drag on touch devices
  const supportsHover = window.matchMedia('(hover: hover) and (pointer: fine)').matches;

  const card = document.getElementById('card');
  const wrap = document.getElementById('cardWrap');
  let rect = card.getBoundingClientRect();
  window.addEventListener('resize', ()=> rect = card.getBoundingClientRect());

  function tiltTo(px, py){
    rect = card.getBoundingClientRect();
    const cx = rect.left + rect.width/2;
    const cy = rect.top + rect.height/2;
    const dx = (px - cx) / (rect.width/2);
    const dy = (py - cy) / (rect.height/2);
    const rotY = Math.max(-1, Math.min(1, dx)) * 16;
    const rotX = Math.max(-1, Math.min(1, dy)) * -16;
    card.style.transform = `rotateX(${rotX}deg) rotateY(${rotY}deg)`;
  }

  function resetTilt(){
    card.style.transform = 'rotateX(0deg) rotateY(0deg)';
  }

  if(supportsHover){
    // desktop: cursor position drives the tilt continuously
    window.addEventListener('mousemove', (e)=>{
      idle = false;
      tiltTo(e.clientX, e.clientY);
    });
    wrap.addEventListener('mouseleave', ()=>{
      idle = true;
    });

    // gentle idle float when the mouse isn't driving the tilt
    let idle = true;
    let t = 0;
    function idleLoop(){
      t += 0.012;
      if(idle){
        const rotY = Math.sin(t)*8;
        const rotX = Math.cos(t*0.8)*4;
        card.style.transform = `rotateX(${rotX}deg) rotateY(${rotY}deg)`;
      }
      requestAnimationFrame(idleLoop);
    }
    idleLoop();
  } else {
    // touch: drag your finger across the card to tilt it, same feel as the mouse version
    let dragging = false;

    wrap.addEventListener('touchstart', (e)=>{
      dragging = true;
      const t0 = e.touches[0];
      tiltTo(t0.clientX, t0.clientY);
    }, { passive:true });

    wrap.addEventListener('touchmove', (e)=>{
      if(!dragging) return;
      e.preventDefault(); // stop the page from scrolling while tilting the card
      const t0 = e.touches[0];
      tiltTo(t0.clientX, t0.clientY);
    }, { passive:false });

    function endDrag(){
      dragging = false;
      resetTilt();
    }
    wrap.addEventListener('touchend', endDrag, { passive:true });
    wrap.addEventListener('touchcancel', endDrag, { passive:true });
  }

  // tap-to-earn: synthesized "kaka kaka" voice bark + coin pop + punch animation
  let audioCtx = null;

  function playSyllable(startTime, pitch, vol){
    // "k" plosive: a short filtered noise click
    const clickLen = 0.02;
    const bufferSize = Math.floor(audioCtx.sampleRate * clickLen);
    const buffer = audioCtx.createBuffer(1, bufferSize, audioCtx.sampleRate);
    const data = buffer.getChannelData(0);
    for(let i=0;i<bufferSize;i++){
      data[i] = (Math.random()*2-1) * (1 - i/bufferSize);
    }
    const click = audioCtx.createBufferSource();
    click.buffer = buffer;
    const clickFilter = audioCtx.createBiquadFilter();
    clickFilter.type = 'highpass';
    clickFilter.frequency.setValueAtTime(2200, startTime);
    const clickGain = audioCtx.createGain();
    clickGain.gain.setValueAtTime(vol * 0.55, startTime);
    clickGain.gain.exponentialRampToValueAtTime(0.0001, startTime + clickLen);
    click.connect(clickFilter);
    clickFilter.connect(clickGain);
    clickGain.connect(audioCtx.destination);
    click.start(startTime);

    // "a" vowel: a short comedic honk right after the click
    const vowelStart = startTime + 0.015;
    const vowelDur = 0.11;
    const osc = audioCtx.createOscillator();
    osc.type = 'square';
    osc.frequency.setValueAtTime(pitch, vowelStart);
    osc.frequency.exponentialRampToValueAtTime(pitch * 0.72, vowelStart + vowelDur);

    const formant = audioCtx.createBiquadFilter();
    formant.type = 'bandpass';
    formant.frequency.setValueAtTime(pitch * 2.2, vowelStart);
    formant.Q.value = 5;

    const vowelGain = audioCtx.createGain();
    vowelGain.gain.setValueAtTime(0.0001, vowelStart);
    vowelGain.gain.exponentialRampToValueAtTime(vol, vowelStart + 0.012);
    vowelGain.gain.exponentialRampToValueAtTime(0.0001, vowelStart + vowelDur);

    osc.connect(formant);
    formant.connect(vowelGain);
    vowelGain.connect(audioCtx.destination);
    osc.start(vowelStart);
    osc.stop(vowelStart + vowelDur);
  }

  function playDramaticTail(startTime){
    // low dramatic boom right after the two "ka"s — for that over-the-top flourish
    const dur = 0.5;
    const osc = audioCtx.createOscillator();
    osc.type = 'sine';
    osc.frequency.setValueAtTime(160, startTime);
    osc.frequency.exponentialRampToValueAtTime(55, startTime + dur);

    const sub = audioCtx.createOscillator();
    sub.type = 'triangle';
    sub.frequency.setValueAtTime(80, startTime);
    sub.frequency.exponentialRampToValueAtTime(40, startTime + dur);

    const gain = audioCtx.createGain();
    gain.gain.setValueAtTime(0.0001, startTime);
    gain.gain.exponentialRampToValueAtTime(0.5, startTime + 0.03);
    gain.gain.exponentialRampToValueAtTime(0.0001, startTime + dur);

    osc.connect(gain);
    sub.connect(gain);
    gain.connect(audioCtx.destination);
    osc.start(startTime); osc.stop(startTime + dur);
    sub.start(startTime); sub.stop(startTime + dur);
  }

  function playUff(){
    try{
      audioCtx = audioCtx || new (window.AudioContext || window.webkitAudioContext)();
      if(audioCtx.state === 'suspended') audioCtx.resume();
      const now = audioCtx.currentTime;

      // "ka-ka" — high squeaky, rapid-fire, then a deep dramatic boom flourish
      const pitches = [980, 920];
      const gaps    = [0, 0.09];
      pitches.forEach((p, i)=> playSyllable(now + gaps[i], p, 0.55));
      playDramaticTail(now + 0.2);
    }catch(e){ /* audio not available, fail silently */ }
  }

  let coins = 0;
  const coinCountEl = document.getElementById('coinCount');
  const photoFrame = document.getElementById('photoFrame');
  const uffFlash = document.getElementById('uffFlash');

  function tapHit(e){
    if(e.cancelable) e.preventDefault();
    coins += 2;
    coinCountEl.textContent = coins;

    playUff();

    photoFrame.classList.remove('tapped');
    void photoFrame.offsetWidth; // restart animation
    photoFrame.classList.add('tapped');

    uffFlash.classList.remove('on');
    void uffFlash.offsetWidth;
    uffFlash.classList.add('on');

    // spawn floating +2 coin text at tap point
    const rect = photoFrame.getBoundingClientRect();
    const point = (e.changedTouches && e.changedTouches[0]) ? e.changedTouches[0] : e;
    const x = (point.clientX != null ? point.clientX - rect.left : rect.width/2);
    const y = (point.clientY != null ? point.clientY - rect.top : rect.height/2);

    const pop = document.createElement('div');
    pop.className = 'coin-pop';
    pop.textContent = '+2';
    pop.style.left = x + 'px';
    pop.style.top = y + 'px';
    photoFrame.appendChild(pop);
    setTimeout(()=> pop.remove(), 900);
  }

  // use a single event path per input type to avoid double-firing (click + touch together
  // was causing the double-count / unresponsive feel on phones)
  if(supportsHover){
    photoFrame.addEventListener('click', tapHit);
  } else {
    photoFrame.addEventListener('touchend', tapHit, { passive:false });
  }
</script>

</body>
</html>
