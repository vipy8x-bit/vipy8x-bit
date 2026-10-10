<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#ff1493">
<title>إلى حبيبتي حنان 💖 | Abdullah</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Amiri:ital,wght@0,400;0,700;1,400&family=Cairo:wght@300;400;600;800&family=Reem+Kufi:wght@400;500;700&family=Aref+Ruqaa:wght@400;700&family=Great+Vibes&display=swap" rel="stylesheet">

<style>
:root{
  --radius-lg:28px;--radius-md:18px;--radius-sm:12px;
  --ease:cubic-bezier(.22,.61,.36,1);--trans:.65s var(--ease);
}
[data-theme="rose"]{--bg-deep:#1a020f;--bg-mid:#2b0518;--bg-soft:#4a0a2c;--glow-a:rgba(255,20,147,.35);--glow-b:rgba(255,105,180,.22);--accent:#ff1493;--accent-2:#ff66b2;--accent-3:#ffb3e6;--text:#ffd6f0;--text-soft:#fff0f8;--panel:rgba(38,5,22,.72);--panel-2:rgba(60,8,35,.55);--border:rgba(255,102,178,.45);}
[data-theme="violet"]{--bg-deep:#0d0520;--bg-mid:#170a33;--bg-soft:#2e1263;--glow-a:rgba(168,85,247,.35);--glow-b:rgba(120,80,255,.22);--accent:#a855f7;--accent-2:#c084fc;--accent-3:#e9d5ff;--text:#e3d4ff;--text-soft:#f6f0ff;--panel:rgba(22,8,48,.72);--panel-2:rgba(40,16,80,.55);--border:rgba(192,132,252,.45);}
[data-theme="gold"]{--bg-deep:#1a1203;--bg-mid:#2b1e05;--bg-soft:#4d3708;--glow-a:rgba(255,183,3,.30);--glow-b:rgba(255,120,0,.20);--accent:#ffb703;--accent-2:#ffd166;--accent-3:#fff3cd;--text:#ffe9bd;--text-soft:#fff8e7;--panel:rgba(38,26,6,.75);--panel-2:rgba(70,48,10,.55);--border:rgba(255,209,102,.45);}
[data-theme="ocean"]{--bg-deep:#02121c;--bg-mid:#04202f;--bg-soft:#063a52;--glow-a:rgba(0,212,255,.30);--glow-b:rgba(0,120,255,.22);--accent:#00d4ff;--accent-2:#5ce1ff;--accent-3:#c9f6ff;--text:#c9f0ff;--text-soft:#eafaff;--panel:rgba(4,26,40,.75);--panel-2:rgba(6,48,70,.55);--border:rgba(92,225,255,.45);}
[data-theme="emerald"]{--bg-deep:#02150f;--bg-mid:#04241a;--bg-soft:#064230;--glow-a:rgba(0,229,160,.28);--glow-b:rgba(0,180,120,.20);--accent:#00e5a0;--accent-2:#5ff2c4;--accent-3:#ccfff0;--text:#c6ffe9;--text-soft:#eafff8;--panel:rgba(4,30,22,.75);--panel-2:rgba(6,58,42,.55);--border:rgba(95,242,196,.45);}

*{box-sizing:border-box;margin:0;padding:0;}
html{scroll-behavior:smooth;}
body{
  font-family:'Cairo','Amiri',sans-serif;color:var(--text);min-height:100vh;overflow-x:hidden;position:relative;
  background-color:var(--bg-mid);
  background-image:
    radial-gradient(circle at 15% 15%, var(--glow-a) 0%, transparent 55%),
    radial-gradient(circle at 85% 80%, var(--glow-b) 0%, transparent 55%),
    linear-gradient(140deg, var(--bg-deep) 0%, var(--bg-mid) 45%, var(--bg-soft) 100%);
  background-size:200% 200%,200% 200%,300% 300%;
  animation:bgShift 26s ease-in-out infinite;
  transition:background-color var(--trans),color var(--trans);
  padding:0 0 60px 0;
}
@keyframes bgShift{0%{background-position:0% 0%,100% 100%,0% 50%;}50%{background-position:60% 40%,30% 60%,100% 50%;}100%{background-position:0% 0%,100% 100%,0% 50%;}}
body::after{content:"";position:fixed;inset:0;background:radial-gradient(circle at 50% 0%,transparent 0%,rgba(0,0,0,.45) 100%);pointer-events:none;z-index:0;}

#fx{position:fixed;inset:0;width:100%;height:100%;z-index:1;pointer-events:none;opacity:.75;}

/* شاشة التحميل */
#loader{position:fixed;inset:0;z-index:9999;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:26px;background:linear-gradient(160deg,var(--bg-deep),var(--bg-mid));transition:opacity .7s var(--ease),visibility .7s;}
#loader.hidden{opacity:0;visibility:hidden;pointer-events:none;}
.loader-heart{font-size:64px;animation:heartBeat 1.2s ease-in-out infinite;filter:drop-shadow(0 0 24px var(--accent));}
@keyframes heartBeat{0%,100%{transform:scale(1);}25%{transform:scale(1.22);}45%{transform:scale(.96);}60%{transform:scale(1.12);}}
.loader-text{font-family:'Aref Ruqaa',serif;font-size:1.35rem;color:var(--accent-2);letter-spacing:.5px;text-shadow:0 0 16px var(--accent);}
.loader-bar{width:230px;height:4px;border-radius:99px;background:rgba(255,255,255,.09);overflow:hidden;}
.loader-bar span{display:block;height:100%;width:0%;border-radius:99px;background:linear-gradient(90deg,var(--accent),var(--accent-3));box-shadow:0 0 16px var(--accent);animation:loadFill 1.4s var(--ease) forwards;}
@keyframes loadFill{to{width:100%;}}

.theme-bar{position:fixed;top:18px;left:18px;z-index:900;display:flex;gap:10px;padding:10px 14px;border-radius:99px;background:var(--panel);border:1px solid var(--border);backdrop-filter:blur(14px);-webkit-backdrop-filter:blur(14px);box-shadow:0 8px 30px rgba(0,0,0,.4),0 0 20px var(--glow-a);transition:background var(--trans),border-color var(--trans);}
.swatch{width:24px;height:24px;border-radius:50%;border:2px solid rgba(255,255,255,.28);cursor:pointer;position:relative;transition:transform .3s var(--ease),box-shadow .3s var(--ease);}
.swatch:hover{transform:scale(1.22);}
.swatch.active{transform:scale(1.28);border-color:#fff;box-shadow:0 0 14px currentColor,0 0 26px currentColor;}
.swatch[data-set="rose"]{background:linear-gradient(135deg,#ff1493,#ff66b2);color:#ff1493;}
.swatch[data-set="violet"]{background:linear-gradient(135deg,#a855f7,#c084fc);color:#a855f7;}
.swatch[data-set="gold"]{background:linear-gradient(135deg,#ffb703,#ffd166);color:#ffb703;}
.swatch[data-set="ocean"]{background:linear-gradient(135deg,#00d4ff,#0078ff);color:#00d4ff;}
.swatch[data-set="emerald"]{background:linear-gradient(135deg,#00e5a0,#00b478);color:#00e5a0;}

.wrapper{position:relative;z-index:5;max-width:860px;margin:0 auto;padding:0 16px;}

.hero{position:relative;text-align:center;padding:110px 24px 60px;margin:26px auto 40px;border-radius:var(--radius-lg);background:var(--panel);border:2px solid var(--border);backdrop-filter:blur(16px);-webkit-backdrop-filter:blur(16px);box-shadow:0 0 50px var(--glow-a),inset 0 0 40px rgba(255,255,255,.04);overflow:hidden;transition:background var(--trans),border-color var(--trans),box-shadow var(--trans);}
.hero::before{content:"";position:absolute;top:-60%;left:-30%;width:160%;height:220%;background:conic-gradient(from 0deg,transparent 0deg,var(--glow-a) 60deg,transparent 130deg,var(--glow-b) 220deg,transparent 300deg);animation:spinGlow 18s linear infinite;opacity:.55;pointer-events:none;}
@keyframes spinGlow{to{transform:rotate(360deg);}}
.hero>*{position:relative;z-index:2;}
.crown{font-size:2.1rem;display:block;margin-bottom:6px;animation:floatY 3.6s ease-in-out infinite;filter:drop-shadow(0 0 16px var(--accent));}
@keyframes floatY{0%,100%{transform:translateY(0);}50%{transform:translateY(-12px);}}
.main-title{font-family:'Reem Kufi',sans-serif;font-size:clamp(2rem,7vw,3.4rem);line-height:1.35;color:#fff;margin-bottom:14px;text-shadow:0 0 12px var(--accent-2),0 0 28px var(--accent),0 0 52px var(--accent);animation:titlePulse 4s ease-in-out infinite;}
@keyframes titlePulse{0%,100%{text-shadow:0 0 12px var(--accent-2),0 0 28px var(--accent),0 0 52px var(--accent);}50%{text-shadow:0 0 18px var(--accent-3),0 0 42px var(--accent-2),0 0 80px var(--accent);}}
.name-highlight{font-family:'Aref Ruqaa',serif;color:var(--accent-3);position:relative;display:inline-block;}
.name-highlight::after{content:"";position:absolute;bottom:-6px;left:0;right:0;height:3px;border-radius:99px;background:linear-gradient(90deg,transparent,var(--accent),transparent);animation:underlineGlow 2.6s ease-in-out infinite;}
@keyframes underlineGlow{0%,100%{opacity:.35;transform:scaleX(.7);}50%{opacity:1;transform:scaleX(1);}}
.subtitle{font-size:clamp(.95rem,2.6vw,1.2rem);color:var(--accent-3);letter-spacing:.4px;margin-bottom:26px;opacity:.92;}
.hero-divider{width:70%;max-width:340px;height:1px;margin:0 auto 26px;background:linear-gradient(90deg,transparent,var(--accent),transparent);box-shadow:0 0 14px var(--accent);}
.hero-badge{display:inline-block;padding:9px 22px;border-radius:99px;font-size:.85rem;font-weight:600;color:var(--accent-3);background:rgba(255,255,255,.05);border:1px solid var(--border);box-shadow:0 0 18px var(--glow-a) inset;}

.music-player{margin:0 auto 46px;padding:26px 22px;border-radius:var(--radius-lg);background:var(--panel);border:1px solid var(--border);backdrop-filter:blur(14px);-webkit-backdrop-filter:blur(14px);box-shadow:0 14px 50px rgba(0,0,0,.45),0 0 30px var(--glow-a);}
.mp-head{display:flex;align-items:center;gap:14px;margin-bottom:20px;}
.mp-disc{width:56px;height:56px;flex:0 0 56px;border-radius:50%;display:grid;place-items:center;font-size:24px;background:radial-gradient(circle at 35% 35%,var(--accent-2),var(--accent) 55%,var(--bg-deep));box-shadow:0 0 22px var(--accent);animation:spinDisc 7s linear infinite;animation-play-state:paused;}
.mp-disc.spinning{animation-play-state:running;}
@keyframes spinDisc{to{transform:rotate(360deg);}}
.mp-meta{flex:1;min-width:0;}
.mp-title{font-family:'Reem Kufi',sans-serif;font-size:1.02rem;color:var(--text-soft);text-shadow:0 0 10px var(--accent);white-space:nowrap;overflow:hidden;text-overflow:ellipsis;}
.mp-sub{font-size:.76rem;color:var(--accent-2);opacity:.85;margin-top:3px;}
.mp-progress-wrap{display:flex;align-items:center;gap:12px;margin-bottom:18px;direction:ltr;}
.mp-time{font-size:.74rem;font-variant-numeric:tabular-nums;color:var(--accent-2);min-width:40px;text-align:center;opacity:.9;}
input[type="range"].mp-range{-webkit-appearance:none;appearance:none;flex:1;height:6px;border-radius:99px;background:rgba(255,255,255,.12);outline:none;cursor:pointer;}
input[type="range"].mp-range::-webkit-slider-thumb{-webkit-appearance:none;appearance:none;width:16px;height:16px;border-radius:50%;background:var(--accent-2);border:2px solid #fff;box-shadow:0 0 12px var(--accent);}
input[type="range"].mp-range::-moz-range-thumb{width:16px;height:16px;border-radius:50%;background:var(--accent-2);border:2px solid #fff;box-shadow:0 0 12px var(--accent);}
.mp-controls{display:flex;align-items:center;justify-content:center;flex-wrap:wrap;gap:14px;}
.mp-btn{width:46px;height:46px;border-radius:50%;border:1px solid var(--border);background:rgba(255,255,255,.05);color:var(--accent-2);font-size:17px;cursor:pointer;display:grid;place-items:center;transition:all .3s var(--ease);}
.mp-btn:hover{background:rgba(255,255,255,.12);color:#fff;transform:translateY(-3px);box-shadow:0 8px 22px var(--glow-a);}
.mp-btn.play{width:62px;height:62px;font-size:23px;background:linear-gradient(145deg,var(--accent),var(--accent-2));color:#fff;border:none;box-shadow:0 0 26px var(--accent);}
.mp-btn.on{background:var(--accent);color:#fff;border-color:transparent;box-shadow:0 0 18px var(--accent);}
.mp-segment-note{text-align:center;font-size:.73rem;color:var(--accent-2);opacity:.75;margin-top:16px;line-height:1.7;}

.poem-box{position:relative;margin:44px 0;padding:38px 26px;border-radius:var(--radius-lg);background:var(--panel-2);border-right:4px solid var(--accent);border-left:4px solid var(--accent);backdrop-filter:blur(10px);-webkit-backdrop-filter:blur(10px);box-shadow:0 0 34px var(--glow-a),inset 0 0 30px rgba(255,255,255,.03);text-align:center;}
.poem-box::before,.poem-box::after{content:"❦";position:absolute;font-size:1.3rem;color:var(--accent-2);opacity:.7;text-shadow:0 0 12px var(--accent);}
.poem-box::before{top:12px;right:20px;}
.poem-box::after{bottom:12px;left:20px;}
.poem-text{font-family:'Amiri',serif;font-size:clamp(1.15rem,3.4vw,1.6rem);line-height:2.1;color:var(--text-soft);text-shadow:0 0 12px var(--glow-a);}
.type-cursor{display:inline-block;width:2px;height:1em;vertical-align:-2px;background:var(--accent-2);box-shadow:0 0 10px var(--accent);animation:blink .85s steps(1) infinite;}
@keyframes blink{50%{opacity:0;}}

.section-title{font-family:'Reem Kufi',sans-serif;text-align:center;font-size:clamp(1.4rem,4.6vw,2.1rem);color:var(--accent-3);margin:70px 0 12px;text-shadow:0 0 18px var(--accent);}
.section-sub{text-align:center;font-size:.9rem;color:var(--accent-2);opacity:.8;margin-bottom:34px;}

.counter-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(120px,1fr));gap:16px;margin-bottom:20px;}
.counter-cell{padding:22px 10px;border-radius:var(--radius-md);background:var(--panel);border:1px solid var(--border);text-align:center;backdrop-filter:blur(10px);-webkit-backdrop-filter:blur(10px);box-shadow:0 0 22px var(--glow-a);transition:transform .35s var(--ease);}
.counter-cell:hover{transform:translateY(-6px);}
.counter-num{font-family:'Reem Kufi',sans-serif;font-size:clamp(1.5rem,5vw,2.2rem);font-weight:700;color:#fff;text-shadow:0 0 16px var(--accent);font-variant-numeric:tabular-nums;direction:ltr;}
.counter-label{font-size:.76rem;color:var(--accent-2);margin-top:6px;letter-spacing:.5px;}

.gallery{display:grid;grid-template-columns:1fr;gap:34px;}
.card{position:relative;border-radius:var(--radius-lg);background:var(--panel);border:1.5px solid var(--border);padding:16px;backdrop-filter:blur(12px);-webkit-backdrop-filter:blur(12px);box-shadow:0 12px 42px rgba(0,0,0,.45),0 0 24px var(--glow-a);overflow:hidden;transition:transform .5s var(--ease),box-shadow .5s var(--ease);}
.card:hover{transform:translateY(-10px) scale(1.012);box-shadow:0 22px 60px rgba(0,0,0,.55),0 0 44px var(--glow-a);}
.card-img-wrap{position:relative;overflow:hidden;border-radius:var(--radius-md);border:2px solid var(--border);background:#000;}
.card img{display:block;width:100%;height:auto;max-height:460px;object-fit:cover;transition:transform 1.1s var(--ease),filter .6s var(--ease);filter:saturate(.92) contrast(1.04);}
.card:hover img{transform:scale(1.07);filter:saturate(1.12) contrast(1.08);}
.card-img-wrap::after{content:"💗 اضغط للتكبير";position:absolute;inset:auto 0 0 0;padding:16px;text-align:center;font-size:.82rem;color:#fff;background:linear-gradient(to top,rgba(0,0,0,.75),transparent);opacity:0;transform:translateY(12px);transition:opacity .45s var(--ease),transform .45s var(--ease);}
.card:hover .card-img-wrap::after{opacity:1;transform:translateY(0);}
.card-caption{font-family:'Amiri',serif;font-size:clamp(1.02rem,3vw,1.35rem);text-align:center;color:var(--text-soft);margin-top:18px;line-height:2;text-shadow:0 0 12px var(--glow-a);}
.card-tag{position:absolute;top:26px;right:26px;z-index:3;padding:6px 14px;border-radius:99px;font-size:.7rem;font-weight:700;color:#fff;background:linear-gradient(135deg,var(--accent),var(--accent-2));box-shadow:0 0 18px var(--accent);letter-spacing:.5px;}

.reasons{display:grid;grid-template-columns:repeat(auto-fit,minmax(210px,1fr));gap:18px;}
.reason{padding:24px 18px;border-radius:var(--radius-md);background:var(--panel);border:1px solid var(--border);text-align:center;backdrop-filter:blur(10px);-webkit-backdrop-filter:blur(10px);transition:transform .4s var(--ease),box-shadow .4s var(--ease);}
.reason:hover{transform:translateY(-8px);box-shadow:0 16px 40px rgba(0,0,0,.45),0 0 30px var(--glow-a);}
.reason-icon{font-size:1.9rem;display:block;margin-bottom:12px;filter:drop-shadow(0 0 12px var(--accent));}
.reason-title{font-family:'Reem Kufi',sans-serif;font-size:1.02rem;color:var(--accent-3);margin-bottom:8px;}
.reason-text{font-size:.86rem;line-height:1.9;color:var(--text);opacity:.9;}

.quote-stage{position:relative;min-height:190px;display:grid;place-items:center;padding:36px 24px;border-radius:var(--radius-lg);background:var(--panel-2);border:1px solid var(--border);backdrop-filter:blur(10px);-webkit-backdrop-filter:blur(10px);box-shadow:0 0 30px var(--glow-a) inset;overflow:hidden;text-align:center;}
.quote{position:absolute;inset:0;display:grid;place-items:center;padding:34px 26px;font-family:'Amiri',serif;font-size:clamp(1.05rem,3.2vw,1.4rem);line-height:2;color:var(--text-soft);opacity:0;transform:translateY(22px) scale(.97);transition:opacity .9s var(--ease),transform .9s var(--ease);pointer-events:none;}
.quote.active{opacity:1;transform:translateY(0) scale(1);pointer-events:auto;}
.quote-dots{display:flex;justify-content:center;gap:9px;margin-top:20px;}
.dot{width:9px;height:9px;border-radius:50%;background:var(--border);cursor:pointer;transition:all .35s var(--ease);}
.dot.active{width:26px;border-radius:99px;background:var(--accent);box-shadow:0 0 12px var(--accent);}

.timeline{position:relative;padding:10px 0;}
.timeline::before{content:"";position:absolute;top:0;bottom:0;right:22px;width:2px;background:linear-gradient(to bottom,transparent,var(--accent),transparent);box-shadow:0 0 14px var(--accent);}
.tl-item{position:relative;padding:0 62px 34px 0;}
.tl-dot{position:absolute;right:13px;top:6px;width:20px;height:20px;border-radius:50%;background:var(--bg-deep);border:3px solid var(--accent);box-shadow:0 0 16px var(--accent);transition:transform .35s var(--ease);}
.tl-item:hover .tl-dot{transform:scale(1.35);}
.tl-date{font-family:'Reem Kufi',sans-serif;font-size:.82rem;color:var(--accent-2);margin-bottom:6px;letter-spacing:.5px;}
.tl-text{font-size:.92rem;line-height:1.95;color:var(--text);opacity:.94;}

.envelope-zone{text-align:center;margin-top:20px;}
.envelope-btn{display:inline-flex;align-items:center;gap:12px;padding:16px 36px;border-radius:99px;border:1px solid var(--border);background:linear-gradient(135deg,var(--accent),var(--accent-2));color:#fff;font-family:'Reem Kufi',sans-serif;font-size:1.02rem;cursor:pointer;box-shadow:0 0 30px var(--accent);transition:transform .35s var(--ease),box-shadow .35s var(--ease);}
.envelope-btn:hover{transform:translateY(-4px) scale(1.04);box-shadow:0 0 48px var(--accent);}
.letter{max-height:0;overflow:hidden;opacity:0;transition:max-height 1.1s var(--ease),opacity .9s var(--ease),margin .6s;margin-top:0;}
.letter.open{max-height:1600px;opacity:1;margin-top:32px;}
.letter-inner{padding:34px 26px;border-radius:var(--radius-lg);background:var(--panel);border:1px solid var(--border);backdrop-filter:blur(12px);-webkit-backdrop-filter:blur(12px);box-shadow:0 0 34px var(--glow-a);text-align:right;font-family:'Amiri',serif;font-size:clamp(1rem,3vw,1.22rem);line-height:2.25;color:var(--text-soft);}
.letter-inner p{margin-bottom:16px;}
.letter-sign{text-align:left;font-family:'Great Vibes',cursive;font-size:1.9rem;color:var(--accent-3);text-shadow:0 0 18px var(--accent);margin-top:10px;}

.footer{text-align:center;margin-top:70px;padding-top:30px;border-top:1px solid var(--border);font-size:.95rem;color:var(--accent-2);line-height:2.1;}
.signature{font-family:'Great Vibes',cursive;font-size:1.75rem;color:#fff;text-shadow:0 0 20px var(--accent),0 0 40px var(--accent);}
.footer-hearts{margin-top:10px;font-size:1.1rem;letter-spacing:6px;animation:floatY 3s ease-in-out infinite;}

#toTop{position:fixed;bottom:26px;left:26px;z-index:900;width:48px;height:48px;border-radius:50%;border:1px solid var(--border);background:var(--panel);color:var(--accent-2);font-size:18px;cursor:pointer;display:grid;place-items:center;backdrop-filter:blur(10px);-webkit-backdrop-filter:blur(10px);opacity:0;transform:translateY(20px);pointer-events:none;transition:all .45s var(--ease);}
#toTop.show{opacity:1;transform:translateY(0);pointer-events:auto;}
#toTop:hover{background:var(--accent);color:#fff;box-shadow:0 0 26px var(--accent);}

#lightbox{position:fixed;inset:0;z-index:9500;display:grid;place-items:center;padding:24px;background:rgba(5,0,8,.93);backdrop-filter:blur(16px);-webkit-backdrop-filter:blur(16px);opacity:0;visibility:hidden;transition:opacity .5s var(--ease),visibility .5s;}
#lightbox.open{opacity:1;visibility:visible;}
#lightbox img{max-width:100%;max-height:82vh;border-radius:var(--radius-md);border:2px solid var(--accent);box-shadow:0 0 60px var(--accent);transform:scale(.9);transition:transform .5s var(--ease);}
#lightbox.open img{transform:scale(1);}
#lightbox .lb-close{position:absolute;top:22px;left:22px;width:44px;height:44px;border-radius:50%;border:1px solid var(--border);background:rgba(255,255,255,.07);color:#fff;font-size:20px;cursor:pointer;display:grid;place-items:center;transition:all .3s;}
#lightbox .lb-close:hover{background:var(--accent);box-shadow:0 0 22px var(--accent);}
#lightbox .lb-caption{position:absolute;bottom:30px;left:50%;transform:translateX(-50%);width:min(90%,620px);text-align:center;font-family:'Amiri',serif;font-size:1.05rem;color:var(--text-soft);line-height:1.9;}

.reveal{opacity:0;transform:translateY(46px);transition:opacity 1s var(--ease),transform 1s var(--ease);will-change:opacity,transform;}
.reveal.visible{opacity:1;transform:translateY(0);}

@media (max-width:640px){
  .hero{padding:96px 18px 46px;}
  .poem-box{padding:30px 18px;}
  .music-player{padding:20px 16px;}
  .mp-btn{width:42px;height:42px;font-size:15px;}
  .mp-btn.play{width:56px;height:56px;font-size:21px;}
  .theme-bar{top:12px;left:12px;padding:8px 11px;gap:8px;}
  .swatch{width:21px;height:21px;}
  .timeline::before{right:14px;}
  .tl-item{padding:0 48px 30px 0;}
  .tl-dot{right:5px;width:18px;height:18px;}
  #toTop{bottom:18px;left:18px;width:44px;height:44px;}
  .letter-inner{padding:26px 18px;}
}
</style>
</head>
<body data-theme="rose">

<div id="loader">
  <div class="loader-heart">💖</div>
  <div class="loader-text">جارٍ تحضير عالمنا الصغير يا حنان…</div>
  <div class="loader-bar"><span></span></div>
</div>

<canvas id="fx"></canvas>

<div class="theme-bar" id="themeBar">
  <div class="swatch active" data-set="rose"></div>
  <div class="swatch" data-set="violet"></div>
  <div class="swatch" data-set="gold"></div>
  <div class="swatch" data-set="ocean"></div>
  <div class="swatch" data-set="emerald"></div>
</div>

<div class="wrapper">

  <header class="hero">
    <span class="crown">👑</span>
    <h1 class="main-title">إلى أميرة قلبي <span class="name-highlight">حنان</span> 💖</h1>
    <div class="hero-divider"></div>
    <p class="subtitle">عالمي الخاص والجميل باسمكِ وحدكِ ✨</p>
    <span class="hero-badge">🌹 حكايةٌ لا تنتهي… منذ أن عرفتُكِ 🌹</span>
  </header>

  <section class="music-player reveal" id="musicPlayer">
    <div class="mp-head">
      <div class="mp-disc" id="disc">🎵</div>
      <div class="mp-meta">
        <div class="mp-title" id="trackTitle">لَحنُ الحُبّ والخُلُود</div>
        <div class="mp-sub" id="trackSub">مقطع رومانسي • اضغط ▶ للتشغيل</div>
      </div>
    </div>
    <div class="mp-progress-wrap">
      <span class="mp-time" id="curTime">0:00</span>
      <input type="range" class="mp-range" id="seek" min="0" max="100" value="0" step="0.1">
      <span class="mp-time" id="durTime">0:00</span>
    </div>
    <div class="mp-controls">
      <button class="mp-btn" id="backBtn">⏪</button>
      <button class="mp-btn play" id="playBtn">▶</button>
      <button class="mp-btn" id="fwdBtn">⏩</button>
      <button class="mp-btn on" id="loopBtn">🔁</button>
      <button class="mp-btn" id="volBtn">🔊</button>
    </div>
    <div class="mp-segment-note">🎧 يتم تشغيل <strong>جزء مختار</strong> من الأغنية وتكراره باستمرار</div>
    <audio id="bgAudio" preload="none" playsinline>
      <source src="https://cdn.pixabay.com/download/audio/2022/05/27/audio_1808fbf07a.mp3?filename=romantic-piano-112189.mp3" type="audio/mpeg">
    </audio>
  </section>

  <h2 class="section-title reveal">⏳ عدّاد حُبِّنا</h2>
  <p class="section-sub reveal">كل ثانية معكِ هي عمرٌ جديد</p>
  <div class="counter-grid reveal">
    <div class="counter-cell"><div class="counter-num" id="cDays">0</div><div class="counter-label">يوم</div></div>
    <div class="counter-cell"><div class="counter-num" id="cHours">0</div><div class="counter-label">ساعة</div></div>
    <div class="counter-cell"><div class="counter-num" id="cMins">0</div><div class="counter-label">دقيقة</div></div>
    <div class="counter-cell"><div class="counter-num" id="cSecs">0</div><div class="counter-label">ثانية</div></div>
  </div>

  <div class="poem-box reveal">
    <p class="poem-text">
      سَأَظلُّ أُحِبُّكِ كَيْفَمَا شَاءَ الهَوَى،<br>
      وَأَعِيشُ فِي عَيْنَيْكِ عُمْرِيَ حَانِيَا 🌹<br>
      يَا حَنَانُ، أنْتِ البِدَايَةُ وَالمُنَى،<br>
      وَبِغَيْرِ حُبِّكِ لا أرَى لِي ثَانِيَا ✨
    </p>
  </div>

  <h2 class="section-title reveal">💖 أَلْبُومُ العُشَّاقِ وَالذِّكْرَيَات 💖</h2>
  <p class="section-sub reveal">لحظاتٌ لو نُطقت لقالت أكثر مما أقول</p>

  <div class="gallery">
    <article class="card reveal">
      <span class="card-tag">لحظة ٠١</span>
      <div class="card-img-wrap"><img src="https://images.unsplash.com/photo-1518199266791-5375a83190b7?q=80&w=1200&auto=format&fit=crop" alt="حب" loading="lazy"></div>
      <p class="card-caption">"وإني أرى في عينيكِ داراً وأماناً،<br>فكلُّ الحنانِ أنتِ يا حنان 🌸"</p>
    </article>
    <article class="card reveal">
      <span class="card-tag">لحظة ٠٢</span>
      <div class="card-img-wrap"><img src="https://images.unsplash.com/photo-1516589178581-6cd7833ae3b2?q=80&w=1200&auto=format&fit=crop" alt="عشاق" loading="lazy"></div>
      <p class="card-caption">"يدُكِ في يدي هي كلُّ ما أرجوه من الدنيا،<br>وبقربكِ تبتسمُ لي كلُّ الأيام 💕"</p>
    </article>
    <article class="card reveal">
      <span class="card-tag">لحظة ٠٣</span>
      <div class="card-img-wrap"><img src="https://images.unsplash.com/photo-1522673607200-164d1b6ce486?q=80&w=1200&auto=format&fit=crop" alt="رومانسية" loading="lazy"></div>
      <p class="card-caption">"لو كان لي أن أختار وطناً،<br>لاخترتُ قلبكِ الدافئ مسكناً 👑"</p>
    </article>
    <article class="card reveal">
      <span class="card-tag">لحظة ٠٤</span>
      <div class="card-img-wrap"><img src="https://images.unsplash.com/photo-1494774157365-9e04c6720e47?q=80&w=1200&auto=format&fit=crop" alt="تفاصيل" loading="lazy"></div>
      <p class="card-caption">"تفاصيلُكِ الصغيرة أكتبها في قلبي،<br>وكلُّ يومٍ معكِ فصلٌ جديد في روايتنا 📖"</p>
    </article>
    <article class="card reveal">
      <span class="card-tag">لحظة ٠٥</span>
      <div class="card-img-wrap"><img src="https://images.unsplash.com/photo-1518568814500-bf0f8d125f46?q=80&w=1200&auto=format&fit=crop" alt="قلب" loading="lazy"></div>
      <p class="card-caption">"ولو سُئلتُ عن معنى السكينة،<br>لأشرتُ إليكِ وقلتُ: هُنَا 🌙"</p>
    </article>
    <article class="card reveal">
      <span class="card-tag">لحظة ٠٦</span>
      <div class="card-img-wrap"><img src="https://images.unsplash.com/photo-1465495976277-4387d4b0b4c6?q=80&w=1200&auto=format&fit=crop" alt="غروب" loading="lazy"></div>
      <p class="card-caption">"أُحبُّكِ في المساءِ وفي الصباح،<br>وفي كلِّ وقتٍ يمرُّ بنا دون استئذان 🕊️"</p>
    </article>
  </div>

  <h2 class="section-title reveal">🌷 لماذا أُحِبُّكِ؟</h2>
  <p class="section-sub reveal">أسبابٌ لا تنتهي… وهذه بعضها فقط</p>
  <div class="reasons reveal">
    <div class="reason"><span class="reason-icon">💗</span><div class="reason-title">حَنَانُكِ</div><p class="reason-text">اسمكِ يشبه قلبكِ… دفءٌ يسبق الكلام ويهدّئ كل شيء.</p></div>
    <div class="reason"><span class="reason-icon">🌙</span><div class="reason-title">سَكِينَتُكِ</div><p class="reason-text">بجانبكِ يصمت الضجيج، ويصبح العالم مكاناً أهدأ وأجمل.</p></div>
    <div class="reason"><span class="reason-icon">😊</span><div class="reason-title">ضِحْكَتُكِ</div><p class="reason-text">ضحكتكِ هي المقطع المفضّل في يومي… أُعيده بلا ملل.</p></div>
    <div class="reason"><span class="reason-icon">🕊️</span><div class="reason-title">صِدْقُكِ</div><p class="reason-text">معكِ لا أحتاج أقنعة… أراكِ فترتاح روحي دون تفسير.</p></div>
    <div class="reason"><span class="reason-icon">🔥</span><div class="reason-title">قُوَّتُكِ</div><p class="reason-text">أراكِ تصبرين وتنهضين… فأتعلّم منكِ كيف أكون أفضل.</p></div>
    <div class="reason"><span class="reason-icon">♾️</span><div class="reason-title">أَنَا وَأَنْتِ</div><p class="reason-text">لأنكِ أنتِ… وحسب. لا يحتاج الحب إلى سببٍ أكثر من ذلك.</p></div>
  </div>

  <h2 class="section-title reveal">💬 هَمْسَاتٌ لَكِ</h2>
  <p class="section-sub reveal">كلماتٌ تتنقّل بيننا كالفراشات</p>
  <div class="quote-stage reveal" id="quoteStage">
    <div class="quote active">"ما عرفتُ معنى البيت حتى سكنتُ قلبكِ."</div>
    <div class="quote">"أحبكِ عدد النجوم، وعدد المرات التي فكّرتُ فيها بكِ اليوم… وهي لا تُعدّ."</div>
    <div class="quote">"لو كان الحبُّ لغةً، لكان اسمُكِ أول حروفها وآخرها."</div>
    <div class="quote">"كل الطرق تؤدي إليكِ… وكل الأيام تشتاق إليكِ."</div>
    <div class="quote">"أنتِ لستِ جزءاً من حياتي، أنتِ الحياةُ نفسها."</div>
  </div>
  <div class="quote-dots" id="quoteDots"></div>

  <h2 class="section-title reveal">📖 مَحَطَّاتُ حِكَايَتِنَا</h2>
  <p class="section-sub reveal">كل محطة… خطوة أقرب</p>
  <div class="timeline reveal">
    <div class="tl-item"><span class="tl-dot"></span><div class="tl-date">البداية ✨</div><p class="tl-text">أول حديثٍ بيننا… لم أكن أعلم أنه سيكون بداية أجمل فصل في حياتي.</p></div>
    <div class="tl-item"><span class="tl-dot"></span><div class="tl-date">أول ضحكة 🌷</div><p class="tl-text">ضحكتِ… فتغيّر مزاج يومي بالكامل. عرفتُ حينها أن الأمر أكبر من إعجاب.</p></div>
    <div class="tl-item"><span class="tl-dot"></span><div class="tl-date">أول قلَق 💭</div><p class="tl-text">قلقتُ عليكِ فعرفتُ أن القلب سبقني إليكِ قبل أن أعترف.</p></div>
    <div class="tl-item"><span class="tl-dot"></span><div class="tl-date">الاعتراف 💌</div><p class="tl-text">قلتُها… وتعلّمتُ أن الخوف يذوب أمام كلمة صادقة واحدة.</p></div>
    <div class="tl-item"><span class="tl-dot"></span><div class="tl-date">اليوم 💖</div><p class="tl-text">ما زلتُ أختاركِ كل صباح، وسأظل أختاركِ ما دام في العمر بقية.</p></div>
    <div class="tl-item"><span class="tl-dot"></span><div class="tl-date">غداً… وإلى الأبد ♾️</div><p class="tl-text">الوعد: أن أكون سندكِ ورفيقكِ وعاشقكِ… في كل النسخ القادمة من حياتنا.</p></div>
  </div>

  <div class="poem-box reveal">
    <p class="poem-text" id="typePoem"></p>
  </div>

  <h2 class="section-title reveal">💌 رِسَالَةٌ أَخِيرَة…</h2>
  <p class="section-sub reveal">اضغط لتفتح ما كتبتُه لكِ</p>
  <div class="envelope-zone reveal">
    <button class="envelope-btn" id="envelopeBtn">💌 افتحي الرسالة يا حنان</button>
    <div class="letter" id="letter">
      <div class="letter-inner">
        <p>حَنَان…</p>
        <p>لو جمعتُ كل كلمات الدنيا، لما استطعتُ أن أصف ما أشعر به نحوكِ. أنتِ لستِ شخصاً أحبُّه فقط… أنتِ المكان الذي أعود إليه كلما تعبتُ من العالم.</p>
        <p>أعدُكِ أن أظلّ لكِ السند والعاشق والرفيق، أن أفرحَ لفرحكِ وأحملَ عنكِ ما يثقل قلبكِ، وأن أختاركِ كل يومٍ من جديد… بلا شروط ولا مقابل.</p>
        <p>يا أجمل حكاية أضاءت لي الطريق… شكراً لأنكِ أنتِ.</p>
        <p class="letter-sign">Abdullah&nbsp;💖</p>
      </div>
    </div>
  </div>

  <footer class="footer reveal">
    صُنع بكل حُب من أجلكِ يا حنان 🌹<br>
    بواسطة: <span class="signature">Abdullah</span> 👑<br>
    <div class="footer-hearts">💖 💗 💖 💗 💖</div>
  </footer>

</div>

<button id="toTop">▲</button>

<div id="lightbox">
  <button class="lb-close" id="lbClose">✕</button>
  <img src="" alt="صورة" id="lbImg">
  <div class="lb-caption" id="lbCaption"></div>
</div>

<script>
/* ============================================================
   شاشة التحميل — نسخة مضمونة 100% (تختفي مهما حصل)
============================================================ */
function hideLoader(){
  const l = document.getElementById('loader');
  if (l) l.classList.add('hidden');
}
document.addEventListener('DOMContentLoaded', () => setTimeout(hideLoader, 1200));
window.addEventListener('load', () => setTimeout(hideLoader, 400));
setTimeout(hideLoader, 3000); // شبكة أمان نهائية

/* ============================================================
   الإعدادات
============================================================ */
const CONFIG = {
  startDate: new Date(2023, 0, 1, 0, 0, 0),
  segmentStart: 18,
  segmentEnd: 78,
  segmentLoop: true,
  autoThemeDelay: 12000,
  heartCount: 26
};

/* ============================================================
   الثيمات
============================================================ */
const THEMES = ['rose','violet','gold','ocean','emerald'];
let themeIndex = 0, themeTimer = null;

function setTheme(name){
  document.body.setAttribute('data-theme', name);
  themeIndex = THEMES.indexOf(name);
  document.querySelectorAll('.swatch').forEach(sw => sw.classList.toggle('active', sw.dataset.set === name));
}
document.querySelectorAll('.swatch').forEach(sw => {
  sw.addEventListener('click', () => { setTheme(sw.dataset.set); restartAutoTheme(); });
});
function autoTheme(){ themeIndex = (themeIndex + 1) % THEMES.length; setTheme(THEMES[themeIndex]); }
function restartAutoTheme(){
  if (themeTimer) clearInterval(themeTimer);
  if (CONFIG.autoThemeDelay > 0) themeTimer = setInterval(autoTheme, CONFIG.autoThemeDelay);
}
restartAutoTheme();

/* ============================================================
   مشغّل الموسيقى
============================================================ */
const audio = document.getElementById('bgAudio');
const playBtn = document.getElementById('playBtn');
const backBtn = document.getElementById('backBtn');
const fwdBtn = document.getElementById('fwdBtn');
const loopBtn = document.getElementById('loopBtn');
const volBtn = document.getElementById('volBtn');
const seek = document.getElementById('seek');
const curTimeEl = document.getElementById('curTime');
const durTimeEl = document.getElementById('durTime');
const disc = document.getElementById('disc');
const trackSub = document.getElementById('trackSub');

let segmentLoop = CONFIG.segmentLoop;
let muted = false, seeking = false;

function fmt(sec){
  if (!isFinite(sec) || sec < 0) sec = 0;
  const m = Math.floor(sec/60);
  const s = Math.floor(sec%60).toString().padStart(2,'0');
  return `${m}:${s}`;
}

audio.addEventListener('loadedmetadata', () => {
  durTimeEl.textContent = fmt(audio.duration);
  seek.max = audio.duration || 100;
});
audio.addEventListener('timeupdate', () => {
  if (!seeking){
    seek.value = audio.currentTime;
    curTimeEl.textContent = fmt(audio.currentTime);
  }
  if (segmentLoop && audio.currentTime >= CONFIG.segmentEnd){
    audio.currentTime = CONFIG.segmentStart;
  }
});
seek.addEventListener('input', () => { seeking = true; curTimeEl.textContent = fmt(seek.value); });
seek.addEventListener('change', () => { audio.currentTime = parseFloat(seek.value); seeking = false; });

function togglePlay(){
  if (audio.paused){
    audio.play().then(()=>{ playBtn.textContent='❚❚'; disc.classList.add('spinning'); })
      .catch(()=>{ trackSub.textContent='⚠️ اضغط مرة أخرى لتشغيل الصوت'; });
  } else {
    audio.pause(); playBtn.textContent='▶'; disc.classList.remove('spinning');
  }
}
playBtn.addEventListener('click', togglePlay);
backBtn.addEventListener('click', () => audio.currentTime = Math.max(CONFIG.segmentStart, audio.currentTime - 5));
fwdBtn.addEventListener('click', () => audio.currentTime = Math.min(CONFIG.segmentEnd, audio.currentTime + 5));
loopBtn.addEventListener('click', () => {
  segmentLoop = !segmentLoop;
  loopBtn.classList.toggle('on', segmentLoop);
  trackSub.textContent = segmentLoop ? `تكرار المقطع: ${fmt(CONFIG.segmentStart)} → ${fmt(CONFIG.segmentEnd)} 🔁` : 'تشغيل عادي بدون تكرار ▶';
});
volBtn.addEventListener('click', () => {
  muted = !muted; audio.muted = muted;
  volBtn.textContent = muted ? '🔇' : '🔊';
  volBtn.classList.toggle('on', muted);
});
audio.addEventListener('pause', () => { playBtn.textContent='▶'; disc.classList.remove('spinning'); });
audio.addEventListener('play', () => { playBtn.textContent='❚❚'; disc.classList.add('spinning'); });

/* تشغيل الصوت عند أول لمسة/ضغطة من المستخدم (سياسة المتصفحات) */
function firstTouchPlay(){
  audio.volume = 0.55;
  audio.play().then(() => {
    document.removeEventListener('touchstart', firstTouchPlay);
    document.removeEventListener('click', firstTouchPlay);
  }).catch(()=>{});
}
document.addEventListener('touchstart', firstTouchPlay, { once:false, passive:true });
document.addEventListener('click', firstTouchPlay, { once:false });

/* ============================================================
   عدّاد الحب
============================================================ */
const cDays = document.getElementById('cDays'), cHours = document.getElementById('cHours');
const cMins = document.getElementById('cMins'), cSecs = document.getElementById('cSecs');
function pad(n){ return n.toString().padStart(2,'0'); }
function updateCounter(){
  const diff = new Date() - CONFIG.startDate;
  if (diff < 0){ cDays.textContent = cHours.textContent = cMins.textContent = cSecs.textContent = '0'; return; }
  const t = Math.floor(diff/1000);
  cDays.textContent = Math.floor(t/86400).toLocaleString('ar-EG');
  cHours.textContent = pad(Math.floor((t%86400)/3600));
  cMins.textContent = pad(Math.floor((t%3600)/60));
  cSecs.textContent = pad(t%60);
}
updateCounter(); setInterval(updateCounter, 1000);

/* ============================================================
   الآلة الكاتبة
============================================================ */
const POEM_LINES = [
  'أعدُكِ أن أظلّ لكِ السند والعاشق والرفيق،',
  'يا أجمل حكاية أضاءت لِي الطريق 💕'
];
const typeTarget = document.getElementById('typePoem');
let typedStarted = false;
function typePoem(){
  if (typedStarted) return;
  typedStarted = true;
  const full = POEM_LINES.join('\n');
  let i = 0;
  const cursor = document.createElement('span');
  cursor.className = 'type-cursor';
  function step(){
    if (i <= full.length){
      typeTarget.innerHTML = full.slice(0,i).replace(/\n/g,'<br>');
      typeTarget.appendChild(cursor);
      i++; setTimeout(step, 55);
    } else cursor.remove();
  }
  step();
}

/* ============================================================
   الظهور عند التمرير
============================================================ */
const io = new IntersectionObserver((entries) => {
  entries.forEach(entry => {
    if (entry.isIntersecting){
      entry.target.classList.add('visible');
      if (entry.target.contains(typeTarget)) typePoem();
      io.unobserve(entry.target);
    }
  });
}, { threshold: 0.08, rootMargin: '0px 0px -40px 0px' });
document.querySelectorAll('.reveal').forEach(el => io.observe(el));
setTimeout(typePoem, 6000); // احتياطي

/* ============================================================
   عارض الصور
============================================================ */
const lightbox = document.getElementById('lightbox');
const lbImg = document.getElementById('lbImg');
const lbCaption = document.getElementById('lbCaption');
const lbClose = document.getElementById('lbClose');
document.querySelectorAll('.card').forEach(card => {
  card.addEventListener('click', () => {
    const img = card.querySelector('img');
    const cap = card.querySelector('.card-caption');
    lbImg.src = img.src;
    lbCaption.innerHTML = cap ? cap.innerHTML : '';
    lightbox.classList.add('open');
    document.body.style.overflow = 'hidden';
  });
});
function closeLightbox(){ lightbox.classList.remove('open'); document.body.style.overflow=''; }
lbClose.addEventListener('click', closeLightbox);
lightbox.addEventListener('click', e => { if (e.target === lightbox) closeLightbox(); });
document.addEventListener('keydown', e => { if (e.key === 'Escape') closeLightbox(); });

/* ============================================================
   الاقتباسات
============================================================ */
const quotes = document.querySelectorAll('.quote');
const dotsWrap = document.getElementById('quoteDots');
let quoteIndex = 0, quoteTimer = null;
quotes.forEach((_, i) => {
  const d = document.createElement('span');
  d.className = 'dot' + (i === 0 ? ' active' : '');
  d.addEventListener('click', () => showQuote(i));
  dotsWrap.appendChild(d);
});
const dots = dotsWrap.querySelectorAll('.dot');
function showQuote(i){
  quotes[quoteIndex].classList.remove('active');
  dots[quoteIndex].classList.remove('active');
  quoteIndex = i;
  quotes[quoteIndex].classList.add('active');
  dots[quoteIndex].classList.add('active');
  restartQuotes();
}
function nextQuote(){ showQuote((quoteIndex + 1) % quotes.length); }
function restartQuotes(){ if (quoteTimer) clearInterval(quoteTimer); quoteTimer = setInterval(nextQuote, 5200); }
restartQuotes();

/* ============================================================
   الرسالة
============================================================ */
const envelopeBtn = document.getElementById('envelopeBtn');
const letter = document.getElementById('letter');
envelopeBtn.addEventListener('click', () => {
  letter.classList.toggle('open');
  envelopeBtn.innerHTML = letter.classList.contains('open') ? '💖 أُغلق الرسالة' : '💌 افتحي الرسالة يا حنان';
  if (letter.classList.contains('open')) setTimeout(()=> letter.scrollIntoView({behavior:'smooth',block:'center'}), 320);
});

/* ============================================================
   زر العودة للأعلى
============================================================ */
const toTop = document.getElementById('toTop');
window.addEventListener('scroll', () => toTop.classList.toggle('show', window.scrollY > 520));
toTop.addEventListener('click', () => window.scrollTo({ top: 0, behavior: 'smooth' }));

/* ============================================================
   القلوب المتحركة
============================================================ */
const canvas = document.getElementById('fx');
const ctx = canvas.getContext('2d');
let W = 0, H = 0, hearts = [], accentColor = '#ff66b2';
function resizeCanvas(){ W = canvas.width = window.innerWidth; H = canvas.height = window.innerHeight; }
resizeCanvas(); window.addEventListener('resize', resizeCanvas);
function readAccent(){ accentColor = getComputedStyle(document.body).getPropertyValue('--accent-2').trim() || '#ff66b2'; }
function drawHeart(x, y, size, color, rotation, alpha){
  ctx.save(); ctx.translate(x,y); ctx.rotate(rotation); ctx.scale(size,size);
  ctx.globalAlpha = alpha; ctx.fillStyle = color;
  ctx.beginPath();
  ctx.moveTo(0,-0.3);
  ctx.bezierCurveTo(0,-0.62,-0.52,-0.62,-0.52,-0.24);
  ctx.bezierCurveTo(-0.52,0.06,0,0.36,0,0.62);
  ctx.bezierCurveTo(0,0.36,0.52,0.06,0.52,-0.24);
  ctx.bezierCurveTo(0.52,-0.62,0,-0.62,0,-0.3);
  ctx.closePath(); ctx.fill(); ctx.restore();
}
function createHeart(){
  return {
    x: Math.random()*W, y: H + Math.random()*120,
    size: 4 + Math.random()*13, speed: 0.28 + Math.random()*0.75,
    sway: Math.random()*Math.PI*2, swaySpeed: 0.006 + Math.random()*0.016,
    swayAmount: 14 + Math.random()*34,
    rotation: (Math.random()-0.5)*0.7, rotSpeed: (Math.random()-0.5)*0.006,
    alpha: 0.18 + Math.random()*0.42
  };
}
function initHearts(){
  hearts = [];
  const count = window.innerWidth < 640 ? Math.round(CONFIG.heartCount*0.6) : CONFIG.heartCount;
  for (let i = 0; i < count; i++){ const h = createHeart(); h.y = Math.random()*H; hearts.push(h); }
}
initHearts(); window.addEventListener('resize', initHearts);
function animate(){
  ctx.clearRect(0,0,W,H);
  hearts.forEach(h => {
    h.y -= h.speed; h.sway += h.swaySpeed; h.rotation += h.rotSpeed;
    const x = h.x + Math.sin(h.sway) * h.swayAmount;
    drawHeart(x, h.y, h.size, accentColor, h.rotation, h.alpha);
    if (h.y < -60) Object.assign(h, createHeart());
  });
  requestAnimationFrame(animate);
}
animate();
new MutationObserver(readAccent).observe(document.body, { attributes: true, attributeFilter: ['data-theme'] });
readAccent();

/* ============================================================
   اختصارات لوحة المفاتيح
============================================================ */
document.addEventListener('keydown', e => {
  if (e.code === 'Space' && e.target === document.body){ e.preventDefault(); togglePlay(); }
  if (e.key === 'ArrowRight') backBtn.click();
  if (e.key === 'ArrowLeft') fwdBtn.click();
});

console.log('%c💖 صُنع بكل حب من أجلكِ يا حنان 💖','color:#ff1493;font-size:16px;font-weight:bold;');
</script>
</body>
</html>
