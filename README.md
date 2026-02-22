# Lawrence-The-Cinarian 👨🏾‍💻

Computer Engineering Student | Systems Programming Enthusiast | Future Infrastructure Architect  



## 🚀 About Me

I am a Computer Engineering student currently focused on mastering low-level systems development.

I am not just learning to code but also 
learning to understand how machines think.

My interests revolve around:

- Memory architecture  
- Data packet movement  
- CPU-level execution  
- Hardware–software interaction  
- Efficient system design  

I believe strong foundations create powerful systems.  
That is why I am currently focused on learning deeply before building massively.


## 🧠 Currently Learning

I am a polyglot coder in progress, sharpening my skills in:

- C (Systems Programming & Memory Management)
- Assembly Language
- VHDL (Hardware Description & Digital Design)

These are not easy languages, but I chose them intentionally.  
I am building the discipline required to engineer at the lowest level.


## 🛠️ Current Projects (Learning Phase)

- CLI Calculator (C)
- Unit Converter (C)
- Currency Converter (C)
- Atm Simulator (C)
- Crypto-Currency Converter (C)
  
These projects represent my foundational stage, focusing on control flow, structured programming, and compiler workflow.

More advanced systems projects coming soon.



## 🎯 Mission

To understand computing from transistor to network stack.

To design systems that move data faster, safer, and more efficiently.

To become a systems engineer capable of building infrastructure-level technology.

This is the beginning.


## 📚 Philosophy

Learn deeply.  
Build deliberately.  
Optimize relentlessly.  

Slow progress is still progress.


## 🔥 Quote I Live By

> "The machine does exactly what you tell it. Master the machine."

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<title>Lawrence-The-Cinarian– Language Badges</title>
<link href="https://fonts.googleapis.com/css2?family=Share+Tech+Mono&display=swap" rel="stylesheet"/>
<style>
  * { margin: 0; padding: 0; box-sizing: border-box; }

  body {
    background: #020810;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    min-height: 100vh;
    font-family: 'Share Tech Mono', monospace;
    gap: 40px;
  }

  .wrapper {
    background: #050d14;
    border-radius: 14px;
    padding: 36px 52px;
    border: 1px solid #0d1f2d;
    box-shadow: 0 0 60px rgba(0,20,40,0.9);
    display: flex;
    gap: 52px;
    align-items: center;
    position: relative;
    overflow: hidden;
  }

  /* Grid background */
  .wrapper::before {
    content: '';
    position: absolute;
    inset: 0;
    background-image:
      linear-gradient(rgba(20,40,60,0.25) 1px, transparent 1px),
      linear-gradient(90deg, rgba(20,40,60,0.25) 1px, transparent 1px);
    background-size: 20px 20px;
    pointer-events: none;
  }

  /* Corner brackets */
  .corner { position: absolute; width: 18px; height: 18px; }
  .corner.tl { top: 10px; left: 10px; border-top: 1.5px solid #2a3f55; border-left: 1.5px solid #2a3f55; }
  .corner.tr { top: 10px; right: 10px; border-top: 1.5px solid #2a3f55; border-right: 1.5px solid #2a3f55; }
  .corner.bl { bottom: 10px; left: 10px; border-bottom: 1.5px solid #2a3f55; border-left: 1.5px solid #2a3f55; }
  .corner.br { bottom: 10px; right: 10px; border-bottom: 1.5px solid #2a3f55; border-right: 1.5px solid #2a3f55; }

  .badge {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 14px;
    position: relative;
    z-index: 1;
  }

  .hex {
    width: 110px;
    height: 126px;
    clip-path: polygon(50% 0%, 100% 25%, 100% 75%, 50% 100%, 0% 75%, 0% 25%);
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .hex-inner {
    width: 100%;
    height: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    gap: 4px;
  }

  /* C */
  .badge-c .hex {
    background: linear-gradient(145deg, #0a1628, #1e3a70);
    box-shadow: 0 0 28px rgba(68,119,221,0.5), inset 0 0 30px rgba(68,119,221,0.08);
    outline: 2px solid #4477dd;
  }
  .badge-c .lang-text {
    font-family: Georgia, serif;
    font-size: 58px;
    font-weight: bold;
    color: #5599ff;
    text-shadow: 0 0 18px rgba(85,153,255,0.7);
    line-height: 1;
  }
  .badge-c .badge-label { color: #4477cc; }

  /* ASM */
  .badge-asm .hex {
    background: linear-gradient(145deg, #1a0800, #3d1a00);
    box-shadow: 0 0 28px rgba(204,68,34,0.5), inset 0 0 30px rgba(204,68,34,0.08);
    outline: 2px solid #cc4422;
  }
  .badge-asm .lang-text {
    font-family: Georgia, serif;
    font-size: 28px;
    font-weight: bold;
    color: #ff6644;
    text-shadow: 0 0 18px rgba(255,102,68,0.7);
    line-height: 1;
  }
  .badge-asm .sub {
    font-size: 10px;
    letter-spacing: 2px;
    color: #aa3311;
    font-family: 'Share Tech Mono', monospace;
    margin-top: 2px;
  }
  .badge-asm .badge-label { color: #cc4422; }

  /* VHDL */
  .badge-vhdl .hex {
    background: linear-gradient(145deg, #001a0e, #003d1e);
    box-shadow: 0 0 28px rgba(34,170,102,0.5), inset 0 0 30px rgba(34,170,102,0.08);
    outline: 2px solid #22aa66;
  }
  .badge-vhdl .lang-text {
    font-family: Georgia, serif;
    font-size: 22px;
    font-weight: bold;
    color: #33ff99;
    text-shadow: 0 0 18px rgba(51,255,153,0.7);
    letter-spacing: 1px;
    line-height: 1;
  }
  .badge-vhdl .badge-label { color: #22aa66; }

  .badge-label {
    font-size: 10px;
    letter-spacing: 3px;
    text-transform: uppercase;
    opacity: 0.85;
  }

  .waveform {
    width: 68px;
    height: 14px;
    margin-top: 3px;
  }

  .divider {
    width: 1px;
    height: 80px;
    background: linear-gradient(to bottom, transparent, #1a2a3a, transparent);
    flex-shrink: 0;
  }

  .top-tag {
    font-size: 9px;
    letter-spacing: 4px;
    color: #1e3040;
    text-transform: uppercase;
    position: absolute;
    top: 11px;
    left: 50%;
    transform: translateX(-50%);
    white-space: nowrap;
    z-index: 2;
  }
</style>
</head>
<body>

<div class="wrapper">
  <div class="corner tl"></div>
  <div class="corner tr"></div>
  <div class="corner bl"></div>
  <div class="corner br"></div>
  <span class="top-tag">Lawrence · Systems Engineer</span>

  <!-- C -->
  <div class="badge badge-c">
    <div class="hex">
      <div class="hex-inner">
        <span class="lang-text">C</span>
      </div>
    </div>
    <div class="badge-label">C&nbsp;Language</div>
  </div>

  <div class="divider"></div>

  <!-- ASM -->
  <div class="badge badge-asm">
    <div class="hex">
      <div class="hex-inner">
        <span class="lang-text">ASM</span>
        <span class="sub">0x00FF</span>
      </div>
    </div>
    <div class="badge-label">Assembly</div>
  </div>

  <div class="divider"></div>

  <!-- VHDL -->
  <div class="badge badge-vhdl">
    <div class="hex">
      <div class="hex-inner">
        <span class="lang-text">VHDL</span>
        <svg class="waveform" viewBox="0 0 68 14" fill="none" xmlns="http://www.w3.org/2000/svg">
          <polyline
            points="0,7 7,7 11,1 17,13 23,1 29,13 35,7 44,7 48,3 54,11 60,7 68,7"
            stroke="#22aa66" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
        </svg>
      </div>
    </div>
    <div class="badge-label">Hardware</div>
  </div>
</div>

</body>
</html>
