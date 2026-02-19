<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Jazmi Hilmi Hamizan — Portfolio 2026</title>
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;600;700;900&family=Plus+Jakarta+Sans:ital,wght@0,300;0,400;0,500;0,600;0,700;1,400&family=Space+Mono:ital,wght@0,400;0,700;1,400&display=swap" rel="stylesheet" />

  <style>
    /* ===================================================
       CSS VARIABLES & RESET
    =================================================== */
    :root {
      --bg:         #050709;
      --bg2:        #080c12;
      --bg3:        #0c1220;
      --bg4:        #0f1825;
      --blue:       #00c8ff;
      --mint:       #00ffb2;
      --violet:     #a78bfa;
      --blue-dim:   rgba(0,200,255,.10);
      --mint-dim:   rgba(0,255,178,.09);
      --glass:      rgba(255,255,255,.03);
      --glass2:     rgba(255,255,255,.06);
      --border:     rgba(0,200,255,.14);
      --border2:    rgba(0,255,178,.14);
      --txt:        #cce4f0;
      --txt-muted:  #4e6e88;
      --radius:     18px;
      --glow-blue:  0 0 28px rgba(0,200,255,.4), 0 0 64px rgba(0,200,255,.12);
      --glow-mint:  0 0 28px rgba(0,255,178,.4), 0 0 64px rgba(0,255,178,.12);
      --glow-v:     0 0 28px rgba(167,139,250,.35);
    }
    *,*::before,*::after { box-sizing:border-box; margin:0; padding:0; }
    html { scroll-behavior:smooth; }
    body {
      background: var(--bg);
      color: var(--txt);
      font-family: 'Plus Jakarta Sans', sans-serif;
      font-weight: 400;
      overflow-x: hidden;
      cursor: none;
    }
    ::-webkit-scrollbar { width: 3px; }
    ::-webkit-scrollbar-track { background: var(--bg2); }
    ::-webkit-scrollbar-thumb { background: var(--blue); border-radius: 3px; }

    /* === Noise overlay === */
    body::before {
      content: '';
      position: fixed; inset: 0;
      background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.85' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='0.035'/%3E%3C/svg%3E");
      pointer-events: none; z-index: 1000; opacity: .5;
    }

    /* === Custom Cursor === */
    #cursor {
      position: fixed; width: 10px; height: 10px; border-radius: 50%;
      background: var(--mint); pointer-events: none; z-index: 9999;
      transform: translate(-50%,-50%);
      transition: transform .1s, width .22s, height .22s, background .22s, box-shadow .22s;
      box-shadow: var(--glow-mint);
    }
    #cursor-ring {
      position: fixed; width: 32px; height: 32px; border-radius: 50%;
      border: 1px solid rgba(0,200,255,.45); pointer-events: none; z-index: 9998;
      transform: translate(-50%,-50%); transition: width .3s, height .3s, border-color .3s;
    }

    /* === Scroll Progress === */
    #scroll-progress {
      position: fixed; top: 0; left: 0; height: 2px; width: 0%;
      background: linear-gradient(90deg, var(--blue), var(--mint));
      z-index: 1001; box-shadow: 0 0 10px var(--mint);
    }

    /* === Utilities === */
    .container { max-width: 1160px; margin: 0 auto; padding: 0 28px; }
    .section { padding: 116px 0; position: relative; }
    .section-label {
      font-family: 'Space Mono', monospace;
      font-size: .7rem; letter-spacing: .28em; color: var(--mint);
      text-transform: uppercase; margin-bottom: 14px;
      display: flex; align-items: center; gap: 12px;
    }
    .section-label::before {
      content: ''; display: inline-block;
      width: 28px; height: 1px; background: linear-gradient(90deg, var(--mint), transparent);
    }
    .section-title {
      font-family: 'Orbitron', sans-serif;
      font-size: clamp(1.8rem,4vw,2.9rem); font-weight: 700;
      line-height: 1.12; color: #fff; margin-bottom: 52px;
    }
    .section-title span { color: var(--blue); }
    .reveal {
      opacity: 0; transform: translateY(36px);
      transition: opacity .75s ease, transform .75s ease;
    }
    .reveal.visible { opacity: 1; transform: translateY(0); }

    /* ===================================================
       NAVIGATION
    =================================================== */
    nav {
      position: fixed; top: 0; left: 0; right: 0; z-index: 500;
      padding: 0 44px; height: 68px;
      display: flex; align-items: center; justify-content: space-between;
      border-bottom: 1px solid transparent;
      transition: background .4s, border-color .4s;
    }
    nav.scrolled {
      background: rgba(5,7,9,.8);
      backdrop-filter: blur(24px);
      border-color: var(--border);
    }
    .nav-logo {
      font-family: 'Orbitron', sans-serif; font-size: 1rem;
      font-weight: 700; color: #fff; text-decoration: none; letter-spacing: .08em;
    }
    .nav-logo span { color: var(--mint); }
    .nav-links { display: flex; align-items: center; gap: 36px; list-style: none; }
    .nav-links a {
      font-family: 'Space Mono', monospace; font-size: .68rem;
      letter-spacing: .14em; text-transform: uppercase;
      color: var(--txt-muted); text-decoration: none;
      transition: color .25s; position: relative;
    }
    .nav-links a::after {
      content: ''; position: absolute; bottom: -4px;
      left: 0; right: 100%; height: 1px;
      background: var(--mint); transition: right .3s ease;
    }
    .nav-links a:hover { color: var(--mint); }
    .nav-links a:hover::after { right: 0; }
    .nav-burger {
      display: none; flex-direction: column; gap: 5px;
      cursor: none; border: none; background: none;
    }
    .nav-burger span {
      display: block; width: 22px; height: 2px;
      background: var(--txt); border-radius: 2px; transition: .3s;
    }
    .nav-burger.open span:nth-child(1) { transform: translateY(7px) rotate(45deg); }
    .nav-burger.open span:nth-child(2) { opacity: 0; }
    .nav-burger.open span:nth-child(3) { transform: translateY(-7px) rotate(-45deg); }

    /* ===================================================
       HERO
    =================================================== */
    #hero {
      min-height: 100vh;
      display: grid; grid-template-columns: 1fr 1fr;
      align-items: center; gap: 60px;
      padding-top: 100px; padding-bottom: 60px;
    }
    #hero::before {
      content: ''; position: absolute; inset: 0;
      background-image:
        linear-gradient(rgba(0,200,255,.03) 1px, transparent 1px),
        linear-gradient(90deg, rgba(0,200,255,.03) 1px, transparent 1px);
      background-size: 64px 64px;
      animation: gridMove 24s linear infinite;
      pointer-events: none;
    }
    @keyframes gridMove { 0% { background-position: 0 0; } 100% { background-position: 64px 64px; } }
    #hero::after {
      content: ''; position: absolute; top: 15%; left: 35%;
      width: 700px; height: 700px;
      background: radial-gradient(ellipse, rgba(0,200,255,.05) 0%, transparent 70%);
      pointer-events: none;
    }
    .hero-left { position: relative; z-index: 2; }
    .hero-tag {
      display: inline-flex; align-items: center; gap: 10px;
      font-family: 'Space Mono', monospace; font-size: .68rem;
      letter-spacing: .2em; text-transform: uppercase; color: var(--mint);
      border: 1px solid rgba(0,255,178,.2); padding: 6px 18px;
      border-radius: 100px; margin-bottom: 28px;
      background: rgba(0,255,178,.04);
    }
    .hero-tag .dot {
      width: 6px; height: 6px; border-radius: 50%;
      background: var(--mint); box-shadow: 0 0 8px var(--mint);
      animation: pulse 1.6s ease-in-out infinite;
    }
    @keyframes pulse {
      0%,100% { opacity:1; transform:scale(1); }
      50% { opacity:.35; transform:scale(.65); }
    }
    .hero-name {
      font-family: 'Orbitron', sans-serif;
      font-size: clamp(2.4rem, 5.5vw, 4.4rem);
      font-weight: 900; line-height: 1.06; color: #fff; margin-bottom: 10px;
    }
    .hero-name .last { color: var(--blue); display: block; }
    .hero-typewriter {
      font-family: 'Space Mono', monospace;
      font-size: clamp(.95rem,2vw,1.25rem); font-weight: 700;
      color: var(--mint); height: 2em; margin-bottom: 30px;
      display: flex; align-items: center; gap: 0;
    }
    .hero-typewriter .prefix { color: var(--txt-muted); margin-right: 10px; }
    .typed-text {
      border-right: 2px solid var(--mint); padding-right: 4px;
      animation: blink .7s step-end infinite;
    }
    @keyframes blink {
      0%,100% { border-color: var(--mint); }
      50% { border-color: transparent; }
    }
    .hero-desc {
      font-size: 1rem; line-height: 1.8; color: var(--txt-muted);
      max-width: 480px; margin-bottom: 40px;
    }
    .hero-desc strong { color: var(--txt); }
    .hero-cta { display: flex; gap: 16px; flex-wrap: wrap; }
    .btn-primary {
      font-family: 'Orbitron', sans-serif; font-size: .73rem;
      font-weight: 700; letter-spacing: .1em; text-transform: uppercase;
      text-decoration: none; padding: 14px 32px; border-radius: 9px;
      border: none; background: linear-gradient(135deg, var(--blue), var(--mint));
      color: #000; cursor: none; position: relative; overflow: hidden;
      transition: transform .25s, box-shadow .25s;
    }
    .btn-primary::after {
      content: ''; position: absolute; inset: 0;
      background: linear-gradient(135deg, var(--mint), var(--blue));
      opacity: 0; transition: opacity .3s;
    }
    .btn-primary:hover { transform: translateY(-3px); box-shadow: var(--glow-mint); }
    .btn-primary:hover::after { opacity: 1; }
    .btn-primary span { position: relative; z-index: 1; }
    .btn-ghost {
      font-family: 'Orbitron', sans-serif; font-size: .73rem;
      font-weight: 700; letter-spacing: .1em; text-transform: uppercase;
      text-decoration: none; padding: 14px 32px; border-radius: 9px;
      border: 1px solid var(--border); color: var(--txt); cursor: none;
      background: transparent; transition: border-color .25s, color .25s, box-shadow .25s, transform .25s;
    }
    .btn-ghost:hover { border-color: var(--blue); color: var(--blue); box-shadow: var(--glow-blue); transform: translateY(-3px); }
    .hero-stats {
      display: flex; gap: 36px; margin-top: 52px;
      padding-top: 32px; border-top: 1px solid var(--border);
    }
    .stat-num {
      font-family: 'Orbitron', sans-serif; font-size: 1.85rem;
      font-weight: 900; color: var(--blue); line-height: 1;
    }
    .stat-label {
      font-family: 'Space Mono', monospace; font-size: .64rem;
      letter-spacing: .1em; color: var(--txt-muted);
      text-transform: uppercase; margin-top: 5px;
    }

    /* ===================================================
       ABSTRACT TECH AVATAR (CSS-Only Orb)
    =================================================== */
    .hero-right {
      display: flex; justify-content: center; align-items: center;
      position: relative; z-index: 2;
    }
    .avatar-frame {
      position: relative; width: 360px; height: 420px;
      display: flex; align-items: center; justify-content: center;
    }
    /* Rotating conic border */
    .avatar-frame::before {
      content: ''; position: absolute; inset: -3px;
      border-radius: 28px;
      background: conic-gradient(var(--blue), var(--mint), transparent, var(--violet), var(--blue));
      animation: rotateBorder 5s linear infinite; z-index: 0;
    }
    @keyframes rotateBorder { from { transform: rotate(0deg); } to { transform: rotate(360deg); } }
    .avatar-inner {
      position: absolute; inset: 3px; border-radius: 26px;
      background: var(--bg3); overflow: hidden; z-index: 1;
      display: flex; flex-direction: column; align-items: center;
      justify-content: center; gap: 18px;
    }

    /* The Orb */
    .orb-container {
      position: relative; width: 160px; height: 160px;
      display: flex; align-items: center; justify-content: center;
    }
    .orb-core {
      width: 90px; height: 90px; border-radius: 50%;
      background: radial-gradient(circle at 38% 38%,
        rgba(0,255,178,.55) 0%,
        rgba(0,200,255,.4) 30%,
        rgba(10,50,100,.6) 65%,
        rgba(5,10,20,.85) 100%);
      box-shadow:
        0 0 30px rgba(0,200,255,.6),
        0 0 70px rgba(0,200,255,.2),
        0 0 120px rgba(0,255,178,.1),
        inset 0 0 24px rgba(0,200,255,.15);
      animation: orbBreath 4s ease-in-out infinite;
      position: relative; z-index: 3;
    }
    .orb-core::after {
      content: ''; position: absolute; top: 18%; left: 20%;
      width: 28%; height: 22%; border-radius: 50%;
      background: rgba(255,255,255,.22);
      filter: blur(4px);
    }
    @keyframes orbBreath {
      0%,100% { transform: scale(1); box-shadow: 0 0 30px rgba(0,200,255,.6), 0 0 70px rgba(0,200,255,.2), 0 0 120px rgba(0,255,178,.1); }
      50% { transform: scale(1.07); box-shadow: 0 0 40px rgba(0,200,255,.75), 0 0 90px rgba(0,200,255,.3), 0 0 160px rgba(0,255,178,.15); }
    }

    /* Orbit rings */
    .orb-ring {
      position: absolute; border-radius: 50%;
      border: 1px solid rgba(0,200,255,.35);
      animation: orbitSpin linear infinite;
    }
    .orb-ring-1 {
      width: 126px; height: 126px;
      animation-duration: 6s;
      border-color: rgba(0,200,255,.3);
      border-style: dashed;
    }
    .orb-ring-2 {
      width: 152px; height: 76px;
      animation-duration: 9s;
      animation-direction: reverse;
      border-color: rgba(0,255,178,.25);
      transform: rotateX(70deg);
    }
    .orb-ring-3 {
      width: 76px; height: 152px;
      animation-duration: 7.5s;
      border-color: rgba(167,139,250,.2);
    }
    @keyframes orbitSpin { from { transform: rotate(0deg); } to { transform: rotate(360deg); } }

    /* Floating particles */
    .orb-particle {
      position: absolute; border-radius: 50%;
      animation: particleDrift ease-in-out infinite alternate;
    }
    .orb-p1 { width:4px; height:4px; background:var(--mint); top:15%; left:20%; animation-duration:3.2s; box-shadow:0 0 6px var(--mint); }
    .orb-p2 { width:3px; height:3px; background:var(--blue); bottom:20%; right:18%; animation-duration:4s; box-shadow:0 0 5px var(--blue); animation-delay:.8s; }
    .orb-p3 { width:2px; height:2px; background:var(--violet); top:60%; left:12%; animation-duration:2.8s; box-shadow:0 0 4px var(--violet); animation-delay:1.4s; }
    .orb-p4 { width:3px; height:3px; background:var(--mint); top:25%; right:15%; animation-duration:3.6s; animation-delay:.4s; box-shadow:0 0 5px var(--mint); }
    @keyframes particleDrift {
      0% { transform: translateY(0) translateX(0); opacity:.7; }
      100% { transform: translateY(-14px) translateX(8px); opacity:1; }
    }

    /* Geometric hexagon background */
    .orb-hex {
      position: absolute; inset: 0;
      background-image: url("data:image/svg+xml,%3Csvg width='60' height='52' viewBox='0 0 60 52' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M30 2L56 17v18L30 50 4 35V17z' fill='none' stroke='rgba(0,200,255,0.06)' stroke-width='1'/%3E%3C/svg%3E");
      background-size: 60px 52px;
      opacity: .6; z-index: 0;
    }
    /* Scan line effect */
    .orb-scan {
      position: absolute; inset: 0; overflow: hidden; z-index: 2;
      border-radius: 26px;
    }
    .orb-scan::after {
      content: '';
      position: absolute; left: 0; right: 0; height: 2px;
      background: linear-gradient(90deg, transparent, rgba(0,255,178,.4), transparent);
      animation: scanMove 4s linear infinite;
    }
    @keyframes scanMove { 0% { top: -2px; } 100% { top: 100%; } }

    /* Avatar name card */
    .avatar-name-card { text-align: center; position: relative; z-index: 3; }
    .avatar-name-card h3 {
      font-family: 'Orbitron', sans-serif; font-size: 1.05rem;
      font-weight: 700; color: #fff;
    }
    .avatar-name-card p {
      font-family: 'Space Mono', monospace; font-size: .66rem;
      color: var(--mint); letter-spacing: .12em; margin-top: 5px;
    }
    .avatar-chips {
      display: flex; flex-wrap: wrap; justify-content: center;
      gap: 6px; padding: 0 24px; position: relative; z-index: 3;
    }
    .chip-sm {
      font-family: 'Space Mono', monospace; font-size: .6rem;
      letter-spacing: .07em; padding: 4px 12px; border-radius: 100px;
      background: var(--blue-dim); border: 1px solid rgba(0,200,255,.18); color: var(--blue);
    }
    .chip-sm.mint { background: var(--mint-dim); border-color: rgba(0,255,178,.18); color: var(--mint); }
    /* Floating badges */
    .floating-badge {
      position: absolute; background: var(--glass2);
      backdrop-filter: blur(14px); border: 1px solid var(--border);
      border-radius: 12px; padding: 10px 14px; z-index: 4;
      animation: floatBadge 3.2s ease-in-out infinite alternate;
    }
    @keyframes floatBadge { from { transform: translateY(0); } to { transform: translateY(-10px); } }
    .floating-badge.left { left: -54px; bottom: 90px; animation-direction: alternate-reverse; }
    .floating-badge.right { right: -44px; top: 90px; }
    .badge-icon { font-size: 1.25rem; }
    .badge-text {
      font-family: 'Space Mono', monospace; font-size: .58rem;
      color: var(--mint); letter-spacing: .08em; margin-top: 3px;
    }

    /* ===================================================
       ABOUT
    =================================================== */
    #about { background: linear-gradient(180deg, var(--bg) 0%, var(--bg2) 50%, var(--bg) 100%); }
    .about-grid {
      display: grid; grid-template-columns: 1fr 1fr;
      gap: 80px; align-items: center;
    }
    .about-map-card {
      background: var(--glass); border: 1px solid var(--border);
      border-radius: var(--radius); padding: 32px;
      backdrop-filter: blur(14px);
      transition: box-shadow .35s, border-color .35s;
    }
    .about-map-card:hover { border-color: var(--blue); box-shadow: var(--glow-blue); }
    .map-svg-container {
      width: 100%; aspect-ratio: 4/3; background: var(--bg3);
      border-radius: 10px; border: 1px solid rgba(0,200,255,.1);
      display: flex; align-items: center; justify-content: center;
      position: relative; overflow: hidden; margin-bottom: 20px;
    }
    .map-svg-container::before {
      content: ''; position: absolute; inset: 0;
      background:
        radial-gradient(ellipse 80% 60% at 55% 45%, rgba(0,200,255,.05), transparent),
        repeating-linear-gradient(0deg, transparent, transparent 28px, rgba(0,200,255,.035) 28px, rgba(0,200,255,.035) 29px),
        repeating-linear-gradient(90deg, transparent, transparent 28px, rgba(0,200,255,.035) 28px, rgba(0,200,255,.035) 29px);
    }
    .map-pin {
      position: absolute; top: 48%; left: 53%;
      transform: translate(-50%,-50%);
      display: flex; flex-direction: column; align-items: center;
    }
    .pin-dot {
      width: 13px; height: 13px; border-radius: 50%;
      background: var(--mint); position: relative; z-index: 1;
      box-shadow: 0 0 18px var(--mint), 0 0 36px rgba(0,255,178,.4);
    }
    .pin-ring {
      position: absolute; width: 40px; height: 40px; border-radius: 50%;
      border: 1.5px solid rgba(0,255,178,.35);
      top: 50%; left: 50%; transform: translate(-50%,-50%);
      animation: pingRing 2.2s ease-out infinite;
    }
    .pin-ring2 { animation-delay: .8s; }
    @keyframes pingRing {
      0% { width: 14px; height: 14px; opacity: .8; }
      100% { width: 72px; height: 72px; opacity: 0; }
    }
    .pin-label {
      font-family: 'Space Mono', monospace; font-size: .6rem; color: var(--mint);
      background: rgba(0,255,178,.09); border: 1px solid rgba(0,255,178,.28);
      border-radius: 6px; padding: 3px 9px; margin-top: 7px; white-space: nowrap; z-index: 1;
    }
    .map-title { font-family: 'Orbitron', sans-serif; font-size: .9rem; font-weight: 700; color: #fff; margin-bottom: 4px; }
    .map-subtitle { font-family: 'Space Mono', monospace; font-size: .64rem; color: var(--txt-muted); letter-spacing: .08em; }
    .about-story { font-size: 1.01rem; line-height: 1.9; color: var(--txt-muted); }
    .about-story p { margin-bottom: 20px; }
    .about-story strong { color: var(--txt); }
    .about-story .highlight { color: var(--mint); font-style: italic; }
    .interest-tags { display: flex; flex-wrap: wrap; gap: 10px; margin-top: 28px; }
    .interest-tag {
      display: flex; align-items: center; gap: 8px;
      font-family: 'Space Mono', monospace; font-size: .66rem;
      letter-spacing: .05em; padding: 7px 16px; border-radius: 9px;
      background: var(--glass); border: 1px solid var(--border); color: var(--txt);
      transition: border-color .25s, color .25s, background .25s;
    }
    .interest-tag:hover { border-color: var(--mint); color: var(--mint); background: var(--mint-dim); }

    /* ===================================================
       SKILLS — HUMBLE & HONEST
    =================================================== */
    #skills::before {
      content: ''; position: absolute; top: 0; left: 0; right: 0; height: 1px;
      background: linear-gradient(90deg, transparent, var(--blue), var(--mint), transparent);
    }
    .skills-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 26px; }
    .skill-card {
      background: var(--glass); border: 1px solid var(--border);
      border-radius: var(--radius); padding: 30px;
      backdrop-filter: blur(14px);
      transition: box-shadow .35s, border-color .35s, transform .35s;
    }
    .skill-card:hover { border-color: var(--blue); box-shadow: var(--glow-blue); transform: translateY(-5px); }
    .skill-card.mint-card:hover { border-color: var(--mint); box-shadow: var(--glow-mint); }
    .skill-card-header { display: flex; align-items: center; gap: 14px; margin-bottom: 20px; }
    .skill-icon {
      width: 48px; height: 48px; border-radius: 13px;
      background: var(--blue-dim); border: 1px solid rgba(0,200,255,.18);
      display: flex; align-items: center; justify-content: center;
      font-size: 1.3rem; flex-shrink: 0;
    }
    .skill-card.mint-card .skill-icon { background: var(--mint-dim); border-color: rgba(0,255,178,.18); }
    .skill-card-title {
      font-family: 'Orbitron', sans-serif; font-size: .9rem;
      font-weight: 700; color: #fff;
    }
    .skill-card-sub {
      font-family: 'Plus Jakarta Sans', sans-serif; font-size: .76rem;
      color: var(--txt-muted); margin-top: 3px; line-height: 1.5;
      font-style: italic;
    }
    .skill-card.mint-card .skill-card-sub { color: rgba(0,255,178,.65); }

    /* Skill items list */
    .skill-items { display: flex; flex-direction: column; gap: 10px; margin-bottom: 20px; }
    .skill-item {
      display: flex; align-items: center; gap: 10px;
      padding: 10px 14px; border-radius: 10px;
      background: rgba(255,255,255,.025); border: 1px solid rgba(255,255,255,.06);
      transition: background .2s, border-color .2s;
    }
    .skill-item:hover { background: rgba(0,200,255,.05); border-color: rgba(0,200,255,.15); }
    .skill-card.mint-card .skill-item:hover { background: rgba(0,255,178,.05); border-color: rgba(0,255,178,.15); }
    .skill-item-icon { font-size: 1rem; flex-shrink: 0; width: 24px; text-align: center; }
    .skill-item-text { font-size: .85rem; color: var(--txt); flex: 1; }
    .skill-item-badge {
      font-family: 'Space Mono', monospace; font-size: .58rem;
      letter-spacing: .06em; padding: 3px 9px; border-radius: 100px;
      background: var(--blue-dim); border: 1px solid rgba(0,200,255,.2);
      color: var(--blue); white-space: nowrap;
    }
    .skill-card.mint-card .skill-item-badge {
      background: var(--mint-dim); border-color: rgba(0,255,178,.2); color: var(--mint);
    }
    .tech-chips-section { margin-top: 16px; }
    .tech-chips-title {
      font-family: 'Space Mono', monospace; font-size: .62rem;
      letter-spacing: .14em; text-transform: uppercase;
      color: var(--txt-muted); margin-bottom: 11px;
    }
    .tech-chips { display: flex; flex-wrap: wrap; gap: 7px; }
    .tech-chip {
      font-family: 'Space Mono', monospace; font-size: .64rem;
      letter-spacing: .05em; padding: 5px 13px; border-radius: 8px;
      background: var(--blue-dim); border: 1px solid rgba(0,200,255,.16);
      color: var(--blue); transition: background .25s, box-shadow .25s, transform .2s;
    }
    .tech-chip:hover { background: rgba(0,200,255,.2); box-shadow: var(--glow-blue); transform: translateY(-2px); }
    .tech-chip.mint-chip { background: var(--mint-dim); border-color: rgba(0,255,178,.16); color: var(--mint); }
    .tech-chip.mint-chip:hover { background: rgba(0,255,178,.2); box-shadow: var(--glow-mint); }

    /* Lifestyle mini grid */
    .lifestyle-grid { display: grid; grid-template-columns: repeat(3,1fr); gap: 10px; margin-top: 16px; }
    .lifestyle-card {
      background: var(--glass); border: 1px solid var(--border);
      border-radius: 12px; padding: 14px 10px; text-align: center;
      transition: box-shadow .3s, border-color .3s, transform .3s;
    }
    .lifestyle-card:hover { border-color: var(--mint); box-shadow: var(--glow-mint); transform: translateY(-4px); }
    .lifestyle-icon { font-size: 1.6rem; margin-bottom: 6px; }
    .lifestyle-label { font-size: .8rem; color: var(--txt); margin-bottom: 3px; font-weight: 600; }
    .lifestyle-sub { font-family: 'Space Mono', monospace; font-size: .58rem; color: var(--txt-muted); }

    /* ===================================================
       GALLERY — BENTO GRID
    =================================================== */
    #gallery { background: var(--bg2); }
    #gallery::before {
      content: ''; position: absolute; top: 0; left: 0; right: 0; height: 1px;
      background: linear-gradient(90deg, transparent, var(--mint), var(--blue), transparent);
    }
    .gallery-intro {
      font-size: 1rem; color: var(--txt-muted); line-height: 1.8;
      max-width: 640px; margin-bottom: 52px;
    }

    /* Bento Grid layout */
    .bento-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      grid-template-rows: auto auto;
      gap: 14px;
    }
    .bento-item {
      position: relative; border-radius: 16px; overflow: hidden;
      background: var(--bg3); border: 1px solid var(--border);
      cursor: none; transition: transform .35s ease, box-shadow .35s ease, border-color .35s;
    }
    .bento-item:hover { transform: scale(1.015) translateY(-4px); box-shadow: var(--glow-blue); border-color: var(--blue); }
    /* Layout: item1=tall left, item2=top-right, item3=middle-right, item4=bottom-full */
    .bento-item-1 { grid-column: 1; grid-row: 1 / 3; }
    .bento-item-2 { grid-column: 2; grid-row: 1; }
    .bento-item-3 { grid-column: 3; grid-row: 1; }
    .bento-item-4 { grid-column: 2 / 4; grid-row: 2; }

    .bento-img {
      width: 100%; height: 100%;
      object-fit: cover; display: block;
      min-height: 200px;
    }
    .bento-item-1 .bento-img { min-height: 420px; }
    .bento-item-4 .bento-img { min-height: 200px; }

    /* Fallback placeholder shown when image not found */
    .bento-placeholder {
      width: 100%; display: flex; flex-direction: column;
      align-items: center; justify-content: center;
      gap: 10px; min-height: 200px;
    }
    .bento-item-1 .bento-placeholder { min-height: 420px; }
    .bento-item-4 .bento-placeholder { min-height: 200px; }
    .bp-1 { background: linear-gradient(145deg, #021a0e 0%, #052d1a 40%, #071c30 100%); }
    .bp-2 { background: linear-gradient(145deg, #070e1a 0%, #0a2040 60%, #040d16 100%); }
    .bp-3 { background: linear-gradient(145deg, #120e05 0%, #231a08 60%, #100f08 100%); }
    .bp-4 { background: linear-gradient(145deg, #03071a 0%, #060f2a 40%, #040e20 100%); }
    .bento-placeholder svg { width: 60%; max-height: 55%; opacity: .55; }

    /* Overlay on hover */
    .bento-caption {
      position: absolute; bottom: 0; left: 0; right: 0;
      padding: 44px 18px 18px;
      background: linear-gradient(0deg, rgba(5,5,5,.9) 0%, transparent 100%);
      opacity: 0; transition: opacity .35s;
    }
    .bento-item:hover .bento-caption { opacity: 1; }
    .bento-caption h4 {
      font-family: 'Plus Jakarta Sans', sans-serif;
      font-size: .9rem; font-weight: 700; color: #fff;
    }
    .bento-caption p {
      font-family: 'Space Mono', monospace; font-size: .6rem;
      color: var(--mint); margin-top: 3px;
    }
    /* Corner label always visible */
    .bento-tag {
      position: absolute; top: 12px; left: 12px;
      font-family: 'Space Mono', monospace; font-size: .56rem;
      letter-spacing: .08em; text-transform: uppercase;
      padding: 3px 9px; border-radius: 6px;
      background: rgba(0,0,0,.55); backdrop-filter: blur(8px);
      border: 1px solid rgba(255,255,255,.1); color: var(--txt-muted);
    }

    /* ===================================================
       TIMELINE / MILESTONES
    =================================================== */
    .timeline { position: relative; padding-left: 42px; }
    .timeline::before {
      content: ''; position: absolute; left: 12px; top: 0; bottom: 0;
      width: 1.5px; background: linear-gradient(180deg, var(--blue), var(--mint), transparent);
    }
    .timeline-item { position: relative; margin-bottom: 48px; }
    .timeline-dot {
      position: absolute; left: -37px; top: 4px;
      width: 14px; height: 14px; border-radius: 50%;
      background: var(--bg); border: 2px solid var(--blue);
      transition: box-shadow .3s, border-color .3s;
    }
    .timeline-item:hover .timeline-dot { border-color: var(--mint); box-shadow: 0 0 14px var(--mint); }
    .timeline-item:nth-child(even) .timeline-dot { border-color: var(--mint); }
    .timeline-year {
      font-family: 'Space Mono', monospace; font-size: .68rem;
      color: var(--blue); letter-spacing: .1em; margin-bottom: 6px;
    }
    .timeline-item:nth-child(even) .timeline-year { color: var(--mint); }
    .timeline-title {
      font-family: 'Plus Jakarta Sans', sans-serif;
      font-size: 1rem; font-weight: 700; color: #fff; margin-bottom: 6px;
    }
    .timeline-desc { font-size: .9rem; line-height: 1.72; color: var(--txt-muted); }

    /* ===================================================
       CONTACT
    =================================================== */
    #contact { background: var(--bg2); }
    #contact::before {
      content: ''; position: absolute; top: 0; left: 0; right: 0; height: 1px;
      background: linear-gradient(90deg, transparent, var(--blue), transparent);
    }
    .contact-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 80px; align-items: start; }
    .big-text {
      font-family: 'Orbitron', sans-serif;
      font-size: clamp(1.6rem,3.5vw,2.7rem); font-weight: 900;
      line-height: 1.18; color: #fff; margin-bottom: 20px;
    }
    .big-text span { color: var(--blue); }
    .contact-desc { font-size: 1rem; line-height: 1.82; color: var(--txt-muted); margin-bottom: 36px; }
    .contact-links { display: flex; flex-direction: column; gap: 13px; }
    .contact-link {
      display: flex; align-items: center; gap: 16px; text-decoration: none;
      padding: 15px 20px; border-radius: 13px; background: var(--glass);
      border: 1px solid var(--border); backdrop-filter: blur(10px);
      transition: border-color .3s, box-shadow .3s, transform .3s;
    }
    .contact-link:hover { transform: translateX(8px); }
    .contact-link.wa-link:hover { border-color: #25d366; box-shadow: 0 0 22px rgba(37,211,102,.3); }
    .contact-link.ig-link:hover { border-color: #e1306c; box-shadow: 0 0 22px rgba(225,48,108,.3); }
    .contact-link.tt-link:hover { border-color: #69c9d0; box-shadow: 0 0 22px rgba(105,201,208,.3); }
    .contact-link-icon {
      width: 42px; height: 42px; border-radius: 11px;
      display: flex; align-items: center; justify-content: center;
      font-size: 1.2rem; flex-shrink: 0;
    }
    .wa-link .contact-link-icon { background: rgba(37,211,102,.14); }
    .ig-link .contact-link-icon { background: rgba(225,48,108,.12); }
    .tt-link .contact-link-icon { background: rgba(105,201,208,.12); }
    .contact-link-title { font-family: 'Plus Jakarta Sans', sans-serif; font-size: .88rem; font-weight: 700; color: #fff; }
    .contact-link-value { font-family: 'Space Mono', monospace; font-size: .66rem; color: var(--txt-muted); letter-spacing: .04em; }
    .contact-form-card {
      background: var(--glass); border: 1px solid var(--border);
      border-radius: var(--radius); padding: 36px; backdrop-filter: blur(14px);
    }
    .contact-form-card h3 { font-family: 'Orbitron', sans-serif; font-size: 1rem; font-weight: 700; color: #fff; margin-bottom: 26px; }
    .form-group { margin-bottom: 18px; }
    .form-label {
      display: block; font-family: 'Space Mono', monospace; font-size: .64rem;
      letter-spacing: .1em; text-transform: uppercase; color: var(--txt-muted); margin-bottom: 7px;
    }
    .form-input, .form-textarea {
      width: 100%; background: rgba(255,255,255,.038); border: 1px solid var(--border);
      border-radius: 9px; padding: 12px 16px;
      font-family: 'Plus Jakarta Sans', sans-serif; font-size: .9rem; color: var(--txt);
      outline: none; transition: border-color .25s, box-shadow .25s; resize: none;
    }
    .form-input::placeholder, .form-textarea::placeholder { color: var(--txt-muted); }
    .form-input:focus, .form-textarea:focus { border-color: var(--blue); box-shadow: 0 0 0 3px rgba(0,200,255,.07); }
    .form-textarea { height: 100px; }
    .form-submit {
      width: 100%; font-family: 'Orbitron', sans-serif; font-size: .73rem;
      font-weight: 700; letter-spacing: .1em; text-transform: uppercase;
      padding: 14px; border-radius: 9px; border: none;
      background: linear-gradient(135deg, var(--blue), var(--mint));
      color: #000; cursor: none; margin-top: 4px;
      transition: transform .25s, box-shadow .25s;
    }
    .form-submit:hover { transform: translateY(-3px); box-shadow: var(--glow-mint); }

    /* ===================================================
       FOOTER
    =================================================== */
    footer { padding: 44px 0; text-align: center; border-top: 1px solid var(--border); }
    .footer-logo { font-family: 'Orbitron', sans-serif; font-size: 1.1rem; font-weight: 900; color: #fff; margin-bottom: 12px; }
    .footer-logo span { color: var(--mint); }
    .footer-copy { font-family: 'Space Mono', monospace; font-size: .63rem; color: var(--txt-muted); letter-spacing: .1em; line-height: 1.8; }
    .footer-copy a { color: var(--blue); text-decoration: none; }
    .footer-copy a:hover { color: var(--mint); }

    /* ===================================================
       RESPONSIVE
    =================================================== */
    @media (max-width: 900px) {
      .nav-links {
        position: fixed; top: 68px; right: 0; bottom: 0; width: 260px;
        flex-direction: column; justify-content: center; align-items: flex-start;
        gap: 28px; background: rgba(5,7,9,.97); backdrop-filter: blur(24px);
        border-left: 1px solid var(--border); padding: 0 40px;
        transform: translateX(100%); transition: transform .35s ease;
      }
      .nav-links.open { transform: translateX(0); }
      .nav-burger { display: flex; }
      #hero { grid-template-columns: 1fr; padding-top: 80px; gap: 40px; text-align: center; }
      .hero-cta { justify-content: center; }
      .hero-stats { justify-content: center; }
      .hero-right { display: none; }
      .hero-desc { margin: 0 auto 40px; }
      .about-grid { grid-template-columns: 1fr; gap: 40px; }
      .skills-grid { grid-template-columns: 1fr; }
      .bento-grid { grid-template-columns: 1fr 1fr; }
      .bento-item-1 { grid-column: 1; grid-row: 1; }
      .bento-item-2 { grid-column: 2; grid-row: 1; }
      .bento-item-3 { grid-column: 1; grid-row: 2; }
      .bento-item-4 { grid-column: 2; grid-row: 2; }
      .bento-item-1 .bento-img, .bento-item-1 .bento-placeholder { min-height: 220px; }
      .bento-item-4 .bento-img, .bento-item-4 .bento-placeholder { min-height: 220px; }
      .contact-grid { grid-template-columns: 1fr; gap: 44px; }
    }
    @media (max-width: 520px) {
      .bento-grid { grid-template-columns: 1fr; }
      .bento-item-1, .bento-item-2, .bento-item-3, .bento-item-4 { grid-column: 1; grid-row: auto; }
    }
  </style>
</head>
<body>

  <div id="cursor"></div>
  <div id="cursor-ring"></div>
  <div id="scroll-progress"></div>

  
  <nav id="navbar">
    <a href="#hero" class="nav-logo">JHH<span>.</span></a>
    <ul class="nav-links" id="nav-links">
      <li><a href="#about">Tentang</a></li>
      <li><a href="#skills">Keahlian</a></li>
      <li><a href="#gallery">Galeri</a></li>
      <li><a href="#milestones">Perjalanan</a></li>
      <li><a href="#contact">Kontak</a></li>
    </ul>
    <button class="nav-burger" id="nav-burger" aria-label="Toggle menu">
      <span></span><span></span><span></span>
    </button>
  </nav>

  
  <section id="hero" class="container">
    <div class="hero-left">
      <div class="hero-tag">
        <span class="dot"></span>
        Tersedia untuk Kolaborasi
      </div>
      <h1 class="hero-name">
        Jazmi Hilmi
        <span class="last">Hamizan</span>
      </h1>
      <div class="hero-typewriter">
        <span class="prefix">—</span>
        <span class="typed-text" id="typed"></span>
      </div>
      <p class="hero-desc">
        <strong>Siswa 15 tahun dari SMPN 1 Karanglewas</strong>, Banyumas — membuktikan bahwa usia bukan batasan. Menggabungkan <strong>analitik data</strong>, <strong>literasi keuangan</strong>, dan jiwa <strong>petualang alam</strong> menjadi satu identitas yang unik dan bertenaga.
      </p>
      <div class="hero-cta">
        <a href="#contact" class="btn-primary"><span>Hubungi Saya</span></a>
        <a href="#about" class="btn-ghost">Pelajari Lebih</a>
      </div>
      <div class="hero-stats">
        <div class="stat-item">
          <div class="stat-num">15</div>
          <div class="stat-label">Usia</div>
        </div>
        <div class="stat-item">
          <div class="stat-num">4+</div>
          <div class="stat-label">Bidang Minat</div>
        </div>
        <div class="stat-item">
          <div class="stat-num">&#x221e;</div>
          <div class="stat-label">Semangat Belajar</div>
        </div>
      </div>
    </div>

    
    <div class="hero-right">
      <div class="avatar-frame">
        <div class="avatar-inner">
          <div class="orb-hex"></div>
          <div class="orb-scan"></div>

          
          <div class="orb-container">
            <div class="orb-ring orb-ring-1"></div>
            <div class="orb-ring orb-ring-2"></div>
            <div class="orb-ring orb-ring-3"></div>
            <div class="orb-core"></div>
            <div class="orb-particle orb-p1"></div>
            <div class="orb-particle orb-p2"></div>
            <div class="orb-particle orb-p3"></div>
            <div class="orb-particle orb-p4"></div>
          </div>

          <div class="avatar-name-card">
            <h3>Jazmi Hilmi H.</h3>
            <p>SMPN 1 Karanglewas &middot; Banyumas</p>
          </div>
          <div class="avatar-chips">
            <span class="chip-sm">Data Analytics</span>
            <span class="chip-sm mint">Pelajar Aktif</span>
            <span class="chip-sm">Finance</span>
            <span class="chip-sm mint">MTB Rider</span>
            <span class="chip-sm">Fotografer Alam</span>
          </div>
        </div>

        <div class="floating-badge right">
          <div class="badge-icon">&#x1F4CA;</div>
          <div class="badge-text">Data Learner</div>
        </div>
        <div class="floating-badge left">
          <div class="badge-icon">&#x1F3D4;</div>
          <div class="badge-text">MTB Rider</div>
        </div>
      </div>
    </div>
  </section>

  
  <section id="about" class="section">
    <div class="container">
      <p class="section-label reveal">Tentang Saya</p>
      <h2 class="section-title reveal">Dari Lereng Bukit<br><span>ke Layar Data</span></h2>
      <div class="about-grid">
        <div class="reveal">
          <div class="about-map-card">
            <div class="map-svg-container">
              <svg viewBox="0 0 300 200" fill="none" xmlns="http://www.w3.org/2000/svg" style="position:absolute;inset:0;width:100%;height:100%;opacity:.28">
                <polyline points="0,160 30,130 60,145 100,100 140,115 170,80 210,95 250,60 300,75" stroke="rgba(0,200,255,.5)" stroke-width="1.5" fill="none"/>
                <polyline points="0,180 50,155 90,165 130,135 170,148 220,120 270,130 300,110" stroke="rgba(0,255,178,.35)" stroke-width="1" fill="none"/>
              </svg>
              <div class="map-pin">
                <div class="pin-dot"></div>
                <div class="pin-ring"></div>
                <div class="pin-ring pin-ring2"></div>
                <div class="pin-label">Desa Jipang</div>
              </div>
            </div>
            <div class="map-title">Karanglewas, Banyumas</div>
            <div class="map-subtitle">Jawa Tengah &middot; dekat Purwokerto</div>
          </div>
        </div>
        <div class="reveal">
          <div class="about-story">
            <p>Di antara hijaunya <strong>Desa Jipang</strong> dan gemuruh angin lereng pegunungan Banyumas, lahirlah seorang pelajar yang tidak biasa. Jazmi Hilmi Hamizan — <strong>siswa 15 tahun dari SMPN 1 Karanglewas</strong> — masih muda, masih belajar, tapi tidak pernah berhenti <span class="highlight">mengejar pemahaman nyata tentang dunia</span>.</p>
            <p>Di <strong>SMP Negeri 1 Karanglewas</strong>, ia adalah sosok yang sama nyamannya berdiri di depan spreadsheet Excel maupun di atas sadel MTB-nya, menuruni jalur berbatu menuju lembah. Kedisiplinan fisik dan rasa ingin tahu analitis berjalan beriringan — <span class="highlight">dua sisi dari koin yang sama</span>.</p>
            <p>Terinspirasi oleh prinsip <strong>Rich Dad Poor Dad</strong>, Jazmi mulai memahami cara kerja uang jauh lebih awal dari kebanyakan. Baginya, literasi keuangan bukan pelajaran sekolah — ini adalah <span class="highlight">keahlian hidup yang paling krusial</span>.</p>
            <p>Dan ketika laptop ditutup, ia membawa kamera — mengabadikan keindahan alam Banyumas dalam bingkai yang bicara lebih dari seribu kata.</p>
          </div>
          <div class="interest-tags">
            <span class="interest-tag"><span>&#x1F4CA;</span> Analitik Data</span>
            <span class="interest-tag"><span>&#x1F4B9;</span> Literasi Keuangan</span>
            <span class="interest-tag"><span>&#x1F6B5;</span> Mountain Biking</span>
            <span class="interest-tag"><span>&#x1F3C3;</span> Lari &amp; Jogging</span>
            <span class="interest-tag"><span>&#x1F4AA;</span> Workout</span>
            <span class="interest-tag"><span>&#x1F4F7;</span> Fotografi Alam</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  
  <section id="skills" class="section">
    <div class="container">
      <p class="section-label reveal">Kemampuan &amp; Keahlian</p>
      <h2 class="section-title reveal">Dashboard<br><span>Kompetensi</span></h2>
      <div class="skills-grid">

        
        <div class="skill-card reveal">
          <div class="skill-card-header">
            <div class="skill-icon">&#x1F4CA;</div>
            <div>
              <div class="skill-card-title">Excel &amp; Analitik Data</div>
              <div class="skill-card-sub">Sedang mendalami pengolahan data &amp; rumus</div>
            </div>
          </div>
          <div class="skill-items">
            <div class="skill-item">
              <span class="skill-item-icon">&#x1F9EE;</span>
              <span class="skill-item-text">Microsoft Excel</span>
              <span class="skill-item-badge">Aktif Belajar</span>
            </div>
            <div class="skill-item">
              <span class="skill-item-icon">&#x1F4C8;</span>
              <span class="skill-item-text">Pivot Table &amp; Grafik</span>
              <span class="skill-item-badge">Eksplorasi</span>
            </div>
            <div class="skill-item">
              <span class="skill-item-icon">&#x1F50D;</span>
              <span class="skill-item-text">Analisis &amp; Interpretasi Data</span>
              <span class="skill-item-badge">Latihan</span>
            </div>
          </div>
          <div class="tech-chips-section">
            <div class="tech-chips-title">Yang Sedang Dipelajari</div>
            <div class="tech-chips">
              <span class="tech-chip">VLOOKUP</span>
              <span class="tech-chip">IF / AND / OR</span>
              <span class="tech-chip">Pivot Table</span>
              <span class="tech-chip">Data Charts</span>
            </div>
          </div>
        </div>

        
        <div class="skill-card mint-card reveal">
          <div class="skill-card-header">
            <div class="skill-icon">&#x1F5A5;</div>
            <div>
              <div class="skill-card-title">Web Coding</div>
              <div class="skill-card-sub">Tahap fundamental (HTML/CSS)</div>
            </div>
          </div>
          <div class="skill-items">
            <div class="skill-item">
              <span class="skill-item-icon">&#x1F4C4;</span>
              <span class="skill-item-text">HTML — Struktur Halaman</span>
              <span class="skill-item-badge">Fundamental</span>
            </div>
            <div class="skill-item">
              <span class="skill-item-icon">&#x1F3A8;</span>
              <span class="skill-item-text">CSS — Styling &amp; Layout</span>
              <span class="skill-item-badge">Fundamental</span>
            </div>
            <div class="skill-item">
              <span class="skill-item-icon">&#x2728;</span>
              <span class="skill-item-text">Animasi CSS Dasar</span>
              <span class="skill-item-badge">Eksplorasi</span>
            </div>
          </div>
          <div class="tech-chips-section">
            <div class="tech-chips-title">Target Berikutnya</div>
            <div class="tech-chips">
              <span class="tech-chip mint-chip">JavaScript</span>
              <span class="tech-chip mint-chip">Responsive Design</span>
              <span class="tech-chip mint-chip">Python</span>
            </div>
          </div>
        </div>

        
        <div class="skill-card mint-card reveal">
          <div class="skill-card-header">
            <div class="skill-icon">&#x1F4B0;</div>
            <div>
              <div class="skill-card-title">Literasi Keuangan</div>
              <div class="skill-card-sub">Belajar mandiri prinsip aset (Rich Dad Poor Dad)</div>
            </div>
          </div>
          <div class="skill-items">
            <div class="skill-item">
              <span class="skill-item-icon">&#x1F4D6;</span>
              <span class="skill-item-text">Prinsip Rich Dad Poor Dad</span>
              <span class="skill-item-badge">Dibaca Habis</span>
            </div>
            <div class="skill-item">
              <span class="skill-item-icon">&#x1F3E6;</span>
              <span class="skill-item-text">Konsep Aset vs Liabilitas</span>
              <span class="skill-item-badge">Memahami</span>
            </div>
            <div class="skill-item">
              <span class="skill-item-icon">&#x1F4B1;</span>
              <span class="skill-item-text">Mindset Investor Muda</span>
              <span class="skill-item-badge">Internalisasi</span>
            </div>
          </div>
          <div class="tech-chips-section">
            <div class="tech-chips-title">Konsep Utama</div>
            <div class="tech-chips">
              <span class="tech-chip mint-chip">Cash Flow</span>
              <span class="tech-chip mint-chip">Passive Income</span>
              <span class="tech-chip mint-chip">Aset &amp; Utang</span>
              <span class="tech-chip mint-chip">Investasi</span>
            </div>
          </div>
        </div>

        
        <div class="skill-card reveal">
          <div class="skill-card-header">
            <div class="skill-icon">&#x1F3CB;</div>
            <div>
              <div class="skill-card-title">Ketahanan Fisik</div>
              <div class="skill-card-sub">Konsisten dalam Workout &amp; Mountain Biking</div>
            </div>
          </div>
          <div class="skill-items">
            <div class="skill-item">
              <span class="skill-item-icon">&#x1F6B5;</span>
              <span class="skill-item-text">Mountain Biking (MTB)</span>
              <span class="skill-item-badge">Rutin</span>
            </div>
            <div class="skill-item">
              <span class="skill-item-icon">&#x1F3C3;</span>
              <span class="skill-item-text">Lari &amp; Jogging Pagi</span>
              <span class="skill-item-badge">Konsisten</span>
            </div>
            <div class="skill-item">
              <span class="skill-item-icon">&#x1F4AA;</span>
              <span class="skill-item-text">Workout &amp; Strength</span>
              <span class="skill-item-badge">Disiplin</span>
            </div>
          </div>
          <div class="lifestyle-grid">
            <div class="lifestyle-card">
              <div class="lifestyle-icon">&#x1F6B5;</div>
              <div class="lifestyle-label">MTB</div>
              <div class="lifestyle-sub">Trail Rider</div>
            </div>
            <div class="lifestyle-card">
              <div class="lifestyle-icon">&#x1F3C3;</div>
              <div class="lifestyle-label">Lari</div>
              <div class="lifestyle-sub">Konsisten</div>
            </div>
            <div class="lifestyle-card">
              <div class="lifestyle-icon">&#x1F4AA;</div>
              <div class="lifestyle-label">Workout</div>
              <div class="lifestyle-sub">Disiplin</div>
            </div>
          </div>
        </div>

      </div>
    </div>
  </section>

  
  <section id="gallery" class="section">
    <div class="container">
      <p class="section-label reveal">Visual Journal</p>
      <h2 class="section-title reveal">Momen Lewat<br><span>Lensa</span></h2>
      <p class="gallery-intro reveal">Setiap perjalanan MTB, setiap pagi lari menyusuri jalan Banyumas, dan setiap momen keheningan di alam terbuka — diabadikan. Bukan sekadar foto, tapi narasi visual seorang muda yang jatuh cinta pada keindahan sekitarnya.</p>

      <div class="bento-grid">

        
        <div class="bento-item bento-item-1 reveal">
          <img src="cipendok.jpeg" alt="Curug Cipendok" class="bento-img"
               onerror="this.style.display='none';this.nextElementSibling.style.display='flex'">
          <div class="bento-placeholder bp-1" style="display:none">
            <svg viewBox="0 0 200 280" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M100,20 Q140,80 120,140 Q100,200 110,260" stroke="rgba(0,200,255,.5)" stroke-width="2.5" fill="none"/>
              <path d="M80,60 Q110,100 95,160 Q80,220 90,270" stroke="rgba(0,255,178,.35)" stroke-width="1.5" fill="none"/>
              <ellipse cx="100" cy="240" rx="30" ry="6" fill="rgba(0,200,255,.12)" stroke="rgba(0,200,255,.3)" stroke-width="1"/>
              <path d="M20,180 Q60,150 100,170 Q140,190 180,165" stroke="rgba(0,255,178,.2)" stroke-width="1" fill="rgba(0,255,178,.04)"/>
              <circle cx="150" cy="50" r="14" fill="none" stroke="rgba(255,200,0,.3)" stroke-width="1.5"/>
              <circle cx="150" cy="50" r="8" fill="rgba(255,200,0,.06)"/>
            </svg>
          </div>
          <div class="bento-tag">Waterfall</div>
          <div class="bento-caption">
            <h4>The Majestic Curug Cipendok</h4>
            <p>Kawasan Banyumas &middot; Alam Photography</p>
          </div>
        </div>

        
        <div class="bento-item bento-item-2 reveal">
          <img src="kumpe.jpeg" alt="Telaga Kumpe" class="bento-img"
               onerror="this.style.display='none';this.nextElementSibling.style.display='flex'">
          <div class="bento-placeholder bp-2" style="display:none">
            <svg viewBox="0 0 200 150" fill="none" xmlns="http://www.w3.org/2000/svg">
              <ellipse cx="100" cy="90" rx="80" ry="36" fill="rgba(0,200,255,.07)" stroke="rgba(0,200,255,.3)" stroke-width="1.5"/>
              <ellipse cx="100" cy="90" rx="55" ry="22" fill="rgba(0,200,255,.05)" stroke="rgba(0,200,255,.2)" stroke-width="1"/>
              <path d="M20,90 Q60,70 100,75 Q140,80 180,90" stroke="rgba(0,255,178,.25)" stroke-width="1.5" fill="none"/>
              <polygon points="60,40 100,88 20,88" fill="rgba(0,255,178,.05)" stroke="rgba(0,255,178,.2)" stroke-width="1"/>
              <polygon points="140,50 180,88 100,88" fill="rgba(0,200,255,.04)" stroke="rgba(0,200,255,.15)" stroke-width="1"/>
            </svg>
          </div>
          <div class="bento-tag">Lake</div>
          <div class="bento-caption">
            <h4>Serenity of Telaga Kumpe</h4>
            <p>Refleksi Tenang &middot; Nature Photography</p>
          </div>
        </div>

        
        <div class="bento-item bento-item-3 reveal">
          <img src="blencong.jpeg" alt="Watu Blencong" class="bento-img"
               onerror="this.style.display='none';this.nextElementSibling.style.display='flex'">
          <div class="bento-placeholder bp-3" style="display:none">
            <svg viewBox="0 0 200 150" fill="none" xmlns="http://www.w3.org/2000/svg">
              <polygon points="100,20 175,120 25,120" fill="rgba(255,140,0,.06)" stroke="rgba(255,140,0,.25)" stroke-width="1.5"/>
              <polygon points="50,50 100,120 0,120" fill="rgba(255,100,0,.05)" stroke="rgba(255,120,0,.18)" stroke-width="1"/>
              <polygon points="150,60 190,120 110,120" fill="rgba(255,180,0,.04)" stroke="rgba(255,160,0,.15)" stroke-width="1"/>
              <circle cx="100" cy="20" r="20" fill="rgba(255,160,30,.08)" stroke="rgba(255,160,30,.4)" stroke-width="1.5"/>
              <line x1="0" y1="120" x2="200" y2="120" stroke="rgba(255,100,0,.2)" stroke-width="1"/>
              <path d="M0,130 Q100,115 200,125" stroke="rgba(255,140,0,.1)" stroke-width="8" fill="none"/>
            </svg>
          </div>
          <div class="bento-tag">Sunset</div>
          <div class="bento-caption">
            <h4>Sunset at Watu Blencong</h4>
            <p>Golden Hour &middot; Landscape Photography</p>
          </div>
        </div>

        
        <div class="bento-item bento-item-4 reveal">
          <img src="astro.jpeg" alt="Astrophotography Moon and Sun" class="bento-img"
               onerror="this.style.display='none';this.nextElementSibling.style.display='flex'">
          <div class="bento-placeholder bp-4" style="display:none">
            <svg viewBox="0 0 400 150" fill="none" xmlns="http://www.w3.org/2000/svg">
              <circle cx="90" cy="65" r="30" fill="rgba(200,200,220,.06)" stroke="rgba(180,180,240,.4)" stroke-width="1.5"/>
              <circle cx="90" cy="65" r="22" fill="rgba(180,180,230,.04)" stroke="rgba(180,180,220,.2)" stroke-width="1"/>
              <path d="M70,60 Q80,52 95,58" stroke="rgba(200,200,220,.25)" stroke-width="1.5" fill="none"/>
              <circle cx="310" cy="68" r="25" fill="rgba(255,220,80,.07)" stroke="rgba(255,200,50,.35)" stroke-width="1.5"/>
              <circle cx="310" cy="68" r="35" fill="none" stroke="rgba(255,200,50,.1)" stroke-width="6"/>
              <circle cx="40" cy="30" r="1.5" fill="rgba(255,255,255,.6)"/>
              <circle cx="150" cy="20" r="1" fill="rgba(0,200,255,.5)"/>
              <circle cx="220" cy="35" r="1.5" fill="rgba(255,255,255,.4)"/>
              <circle cx="280" cy="15" r="1" fill="rgba(0,255,178,.5)"/>
              <circle cx="370" cy="30" r="1.5" fill="rgba(255,255,255,.5)"/>
              <circle cx="60" cy="90" r="1" fill="rgba(0,200,255,.4)"/>
              <circle cx="200" cy="110" r="1" fill="rgba(255,255,255,.3)"/>
              <circle cx="340" cy="100" r="1.5" fill="rgba(0,255,178,.4)"/>
              <polygon points="170,90 220,140 120,140" fill="rgba(0,0,0,.7)" stroke="rgba(0,200,255,.15)" stroke-width="1"/>
              <polygon points="260,95 310,140 210,140" fill="rgba(0,0,0,.75)" stroke="rgba(0,255,178,.1)" stroke-width="1"/>
            </svg>
          </div>
          <div class="bento-tag">Astro</div>
          <div class="bento-caption">
            <h4>Celestial: Moon &amp; Sun</h4>
            <p>Astro-photography &middot; Long Exposure &middot; Langit Malam Banyumas</p>
          </div>
        </div>

      </div>
    </div>
  </section>

  
  <section id="milestones" class="section">
    <div class="container">
      <p class="section-label reveal">Perjalanan Saya</p>
      <h2 class="section-title reveal">Linimasa<br><span>Pertumbuhan</span></h2>
      <div class="timeline">
        <div class="timeline-item reveal">
          <div class="timeline-dot"></div>
          <div class="timeline-year">2022</div>
          <div class="timeline-title">Pertama Kali Membuka Excel</div>
          <div class="timeline-desc">Diperkenalkan ke Microsoft Excel di kelas dan langsung terpikat. Mulai bereksperimen sendiri dengan formula dan grafik sederhana di luar jam pelajaran.</div>
        </div>
        <div class="timeline-item reveal">
          <div class="timeline-dot"></div>
          <div class="timeline-year">2023</div>
          <div class="timeline-title">Membaca Rich Dad Poor Dad</div>
          <div class="timeline-desc">Mendapatkan buku ikonik Robert Kiyosaki dan membacanya habis dalam dua hari. Cara pandangnya tentang uang, aset, dan kebebasan finansial berubah drastis sejak saat itu.</div>
        </div>
        <div class="timeline-item reveal">
          <div class="timeline-dot"></div>
          <div class="timeline-year">2023</div>
          <div class="timeline-title">Memulai Rutinitas Fitness</div>
          <div class="timeline-desc">Sadar bahwa pikiran yang tajam membutuhkan tubuh yang kuat. Mulai lari pagi secara konsisten dan bergabung dengan komunitas MTB lokal di Karanglewas.</div>
        </div>
        <div class="timeline-item reveal">
          <div class="timeline-dot"></div>
          <div class="timeline-year">2024</div>
          <div class="timeline-title">Mendalami Data Analytics</div>
          <div class="timeline-desc">Mulai belajar analisis data secara mandiri melalui video tutorial online. Mengaplikasikan ilmu Excel ke proyek nyata: laporan keuangan keluarga dan analisis sederhana berbasis data.</div>
        </div>
        <div class="timeline-item reveal">
          <div class="timeline-dot"></div>
          <div class="timeline-year">2024</div>
          <div class="timeline-title">Mengembangkan Fotografi Alam</div>
          <div class="timeline-desc">Kecintaan pada alam terbuka bertemu dengan seni visual. Mulai secara serius mengabadikan keindahan kawasan Banyumas — sawah, pegunungan, dan langit malam yang luar biasa.</div>
        </div>
        <div class="timeline-item reveal">
          <div class="timeline-dot"></div>
          <div class="timeline-year">2025</div>
          <div class="timeline-title">Mempelajari HTML &amp; CSS</div>
          <div class="timeline-desc">Melangkah ke dunia web dengan mempelajari dasar-dasar HTML dan CSS. Memahami struktur dan tampilan halaman web sebagai pondasi untuk perjalanan coding yang lebih jauh.</div>
        </div>
        <div class="timeline-item reveal">
          <div class="timeline-dot"></div>
          <div class="timeline-year">2026 &rarr;</div>
          <div class="timeline-title">Membangun Identitas Digital</div>
          <div class="timeline-desc">Memulai perjalanan membangun kehadiran online yang kuat. Berencana mempelajari Python untuk analitik yang lebih dalam dan terus mengasah kemampuan di bidang keuangan, data, dan teknologi web.</div>
        </div>
      </div>
    </div>
  </section>

  
  <section id="contact" class="section">
    <div class="container">
      <p class="section-label reveal">Kontak &amp; Kolaborasi</p>
      <div class="contact-grid">
        <div class="reveal">
          <h2 class="big-text">Mari<br><span>Terhubung</span></h2>
          <p class="contact-desc">Punya proyek data menarik? Ingin berdiskusi tentang investasi, teknologi, atau sekadar berbagi cerita tentang jalur MTB terbaik di Banyumas? Pintu selalu terbuka.</p>
          <div class="contact-links">
            <a href="https://wa.me/62895385038124" target="_blank" rel="noopener noreferrer" class="contact-link wa-link">
              <div class="contact-link-icon">&#x1F4AC;</div>
              <div>
                <div class="contact-link-title">WhatsApp</div>
                <div class="contact-link-value">+62 895-3850-38124</div>
              </div>
            </a>
            <a href="https://instagram.com/jazmihilmi_official" target="_blank" rel="noopener noreferrer" class="contact-link ig-link">
              <div class="contact-link-icon">&#x1F4F8;</div>
              <div>
                <div class="contact-link-title">Instagram</div>
                <div class="contact-link-value">@jazmihilmi_official</div>
              </div>
            </a>
            <a href="https://tiktok.com/@hilmi_hamizan03" target="_blank" rel="noopener noreferrer" class="contact-link tt-link">
              <div class="contact-link-icon">&#x1F3B5;</div>
              <div>
                <div class="contact-link-title">TikTok</div>
                <div class="contact-link-value">@hilmi_hamizan03</div>
              </div>
            </a>
          </div>
        </div>
        
        <div class="contact-form-card reveal">
          <h3>Kirim Pesan</h3>
          <div class="form-group">
            <label class="form-label">Nama Lengkap</label>
            <input type="text" class="form-input" placeholder="Nama kamu..." id="f-name" />
          </div>
          <div class="form-group">
            <label class="form-label">Email / WhatsApp</label>
            <input type="text" class="form-input" placeholder="Kontak kamu..." id="f-contact" />
          </div>
          <div class="form-group">
            <label class="form-label">Pesan</label>
            <textarea class="form-textarea" placeholder="Ceritakan sesuatu yang menarik..." id="f-msg"></textarea>
          </div>
          <button class="form-submit" onclick="handleFormSubmit()">Kirim via WhatsApp &rarr;</button>
        </div>
      </div>
    </div>
  </section>

  
  <footer>
    <div class="container">
      <div class="footer-logo">JHH<span>.</span></div>
      <p class="footer-copy">
        &copy; 2026 Jazmi Hilmi Hamizan. Dibuat karena gabut pas puasa.
      </p>
    </div>
  </footer>

  
  <script>
    // --- Custom Cursor ---
    const cursor    = document.getElementById('cursor');
    const cursorRing = document.getElementById('cursor-ring');
    let mx = 0, my = 0, rx = 0, ry = 0;

    document.addEventListener('mousemove', e => {
      mx = e.clientX; my = e.clientY;
      cursor.style.left = mx + 'px';
      cursor.style.top  = my + 'px';
    });

    (function animateRing() {
      rx += (mx - rx) * 0.13;
      ry += (my - ry) * 0.13;
      cursorRing.style.left = rx + 'px';
      cursorRing.style.top  = ry + 'px';
      requestAnimationFrame(animateRing);
    })();

    document.addEventListener('mouseover', e => {
      if (e.target.closest('a, button')) {
        cursor.style.width  = '16px';
        cursor.style.height = '16px';
        cursor.style.background = 'var(--blue)';
        cursor.style.boxShadow  = 'var(--glow-blue)';
        cursorRing.style.width  = '50px';
        cursorRing.style.height = '50px';
        cursorRing.style.borderColor = 'rgba(0,200,255,.55)';
      }
    });
    document.addEventListener('mouseout', e => {
      if (e.target.closest('a, button')) {
        cursor.style.width  = '10px';
        cursor.style.height = '10px';
        cursor.style.background = 'var(--mint)';
        cursor.style.boxShadow  = 'var(--glow-mint)';
        cursorRing.style.width  = '32px';
        cursorRing.style.height = '32px';
        cursorRing.style.borderColor = 'rgba(0,200,255,.45)';
      }
    });

    // --- Scroll Progress ---
    const progressBar = document.getElementById('scroll-progress');
    window.addEventListener('scroll', () => {
      const pct = (window.scrollY / (document.documentElement.scrollHeight - window.innerHeight)) * 100;
      progressBar.style.width = pct + '%';
      document.getElementById('navbar').classList.toggle('scrolled', window.scrollY > 40);
    });

    // --- Mobile Burger ---
    const burger   = document.getElementById('nav-burger');
    const navLinks = document.getElementById('nav-links');
    burger.addEventListener('click', () => {
      burger.classList.toggle('open');
      navLinks.classList.toggle('open');
    });
    navLinks.querySelectorAll('a').forEach(a => a.addEventListener('click', () => {
      burger.classList.remove('open');
      navLinks.classList.remove('open');
    }));

    // --- Typewriter ---
    const phrases = ['Data Analyst Prospect', 'Finance Enthusiast', 'Nature Photographer', 'Fitness Consistent', 'Web Dev Learner'];
    const typedEl = document.getElementById('typed');
    let pIdx = 0, cIdx = 0, deleting = false;
    function typeLoop() {
      const cur = phrases[pIdx];
      typedEl.textContent = deleting ? cur.slice(0, cIdx - 1) : cur.slice(0, cIdx + 1);
      if (!deleting) cIdx++;
      else           cIdx--;
      if (!deleting && cIdx > cur.length)  { deleting = true; setTimeout(typeLoop, 1800); return; }
      if  (deleting && cIdx < 0)           { deleting = false; pIdx = (pIdx + 1) % phrases.length; cIdx = 0; }
      setTimeout(typeLoop, deleting ? 50 : 88);
    }
    typeLoop();

    // --- Intersection Observer: reveal ---
    const revealObs = new IntersectionObserver((entries) => {
      entries.forEach(entry => {
        if (!entry.isIntersecting) return;
        const siblings = Array.from(entry.target.parentElement.querySelectorAll('.reveal'));
        const delay    = siblings.indexOf(entry.target) * 75;
        setTimeout(() => { entry.target.classList.add('visible'); }, delay);
        revealObs.unobserve(entry.target);
      });
    }, { threshold: 0.1 });
    document.querySelectorAll('.reveal').forEach(el => revealObs.observe(el));

    // --- Smooth anchor scroll ---
    document.querySelectorAll('a[href^="#"]').forEach(link => {
      link.addEventListener('click', e => {
        const target = document.querySelector(link.getAttribute('href'));
        if (target) { e.preventDefault(); target.scrollIntoView({ behavior: 'smooth', block: 'start' }); }
      });
    });

    // --- Contact form -> WhatsApp ---
    function handleFormSubmit() {
      const name    = document.getElementById('f-name').value.trim();
      const contact = document.getElementById('f-contact').value.trim();
      const msg     = document.getElementById('f-msg').value.trim();
      if (!name || !msg) { alert('Harap isi nama dan pesan terlebih dahulu!'); return; }
      const text = `Halo Jazmi! 👋%0ASaya *${encodeURIComponent(name)}*%0AKontak: ${encodeURIComponent(contact || '-')}%0A%0A${encodeURIComponent(msg)}`;
      window.open(`https://wa.me/62895385038124?text=${text}`, '_blank');
    }
  </script>

</body>
</html>
