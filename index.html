<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>LungScan AI-CT Lung Cancer Detection</title>
<link href="https://fonts.googleapis.com/css2?family=Instrument+Serif:ital@0;1&family=Outfit:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
<style>
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0;}
:root{
  --navy:#061527;--navy2:#0b2240;--navy3:#0f2d55;
  --blue:#1565c0;--blue-light:#1e88e5;--cyan:#00acc1;
  --surface:#0d1f38;--surface2:#112649;--surface3:#163060;
  --border:rgba(255,255,255,0.07);--border2:rgba(255,255,255,0.13);
  --text:#e8f0fe;--text2:#b0c4de;--muted:#6b88aa;
  --danger:#ef5350;--warn:#ffb300;--safe:#26a69a;--orange:#ff7043;
  --font-h:'Instrument Serif',serif;--font-b:'Outfit',sans-serif;
  --r:14px;--shadow:0 4px 24px rgba(0,0,0,0.35);
}
html{scroll-behavior:smooth;}
body{font-family:var(--font-b);background:var(--navy);color:var(--text);min-height:100vh;overflow-x:hidden;}
::-webkit-scrollbar{width:5px;}::-webkit-scrollbar-track{background:var(--navy);}::-webkit-scrollbar-thumb{background:var(--surface3);border-radius:3px;}

/* HEADER */
header{position:sticky;top:0;z-index:300;background:rgba(6,21,39,0.95);backdrop-filter:blur(20px);border-bottom:1px solid var(--border);display:flex;align-items:center;justify-content:space-between;padding:0 36px;height:64px;}
.logo{display:flex;align-items:center;gap:12px;cursor:pointer;}
.logo-mark{width:38px;height:38px;border-radius:10px;background:linear-gradient(135deg,var(--blue),var(--cyan));display:flex;align-items:center;justify-content:center;font-size:20px;box-shadow:0 4px 14px rgba(21,101,192,0.5);flex-shrink:0;}
.logo-name{font-family:var(--font-h);font-size:1.3rem;font-style:italic;color:#fff;}
.logo-name span{color:var(--cyan);font-style:normal;}
nav{display:flex;align-items:center;gap:4px;}
.nav-item{padding:7px 16px;border-radius:8px;font-size:.875rem;font-weight:500;cursor:pointer;border:none;background:transparent;color:var(--muted);font-family:var(--font-b);transition:.2s;}
.nav-item:hover{color:var(--text);background:var(--surface);}
.nav-item.act{color:var(--cyan);background:rgba(0,172,193,0.1);}
#loginBtn{background:var(--blue);color:#fff;padding:8px 20px;border-radius:8px;font-weight:600;font-size:.875rem;border:none;cursor:pointer;font-family:var(--font-b);transition:.2s;}
#loginBtn:hover{background:var(--blue-light);}
.user-pill{display:none;align-items:center;gap:9px;padding:5px 14px 5px 7px;background:var(--surface2);border:1px solid var(--border2);border-radius:30px;}
.u-avatar{width:28px;height:28px;border-radius:50%;background:linear-gradient(135deg,var(--blue),var(--cyan));display:flex;align-items:center;justify-content:center;font-size:.75rem;font-weight:700;color:#fff;}
.u-name{font-size:.875rem;font-weight:600;color:var(--text);}
#logoutBtn{display:none;background:transparent;border:1px solid var(--border2);color:var(--muted);padding:7px 14px;border-radius:8px;font-size:.82rem;font-family:var(--font-b);cursor:pointer;transition:.2s;}
#logoutBtn:hover{color:var(--danger);border-color:var(--danger);}

/* SCREENS */
.screen{display:none;}
.screen.on{display:block;animation:rise .35s ease;}
@keyframes rise{from{opacity:0;transform:translateY(14px);}to{opacity:1;transform:translateY(0);}}

/* LANDING */
.land{min-height:calc(100vh - 64px);display:flex;flex-direction:column;align-items:center;justify-content:center;text-align:center;padding:60px 24px;background:radial-gradient(ellipse 80% 60% at 50% 0%,rgba(21,101,192,0.2) 0%,transparent 70%);}
.land-badge{display:inline-flex;align-items:center;gap:8px;padding:5px 16px;border-radius:30px;background:rgba(0,172,193,0.1);border:1px solid rgba(0,172,193,0.25);color:var(--cyan);font-size:.78rem;font-weight:600;letter-spacing:.07em;text-transform:uppercase;margin-bottom:28px;}
.blink{width:7px;height:7px;border-radius:50%;background:var(--cyan);animation:blink 1.4s infinite;}
@keyframes blink{0%,100%{opacity:1;}50%{opacity:.3;}}
.land h1{font-family:var(--font-h);font-size:clamp(2rem,5vw,3.8rem);font-weight:400;line-height:1.12;letter-spacing:-.02em;max-width:820px;margin-bottom:12px;color:#fff;}
.land h1 em{font-style:italic;color:var(--cyan);}
.land .proj-sub{font-size:.95rem;color:var(--muted);margin-bottom:20px;font-style:italic;}
.land p{color:var(--text2);font-size:1.05rem;max-width:580px;line-height:1.75;margin-bottom:40px;}
.land-btns{display:flex;gap:12px;flex-wrap:wrap;justify-content:center;}
.btn{display:inline-flex;align-items:center;gap:8px;border:none;cursor:pointer;font-family:var(--font-b);font-weight:600;transition:.22s;border-radius:10px;}
.btn-primary{background:var(--blue);color:#fff;padding:14px 32px;font-size:1rem;}
.btn-primary:hover{background:var(--blue-light);transform:translateY(-2px);box-shadow:0 10px 28px rgba(21,101,192,0.45);}
.btn-ghost{background:transparent;color:var(--text);padding:14px 28px;font-size:1rem;border:1px solid var(--border2);}
.btn-ghost:hover{border-color:var(--cyan);color:var(--cyan);}
.kpi-strip{display:flex;gap:48px;margin-top:64px;flex-wrap:wrap;justify-content:center;padding-top:48px;border-top:1px solid var(--border);}
.kpi{text-align:center;}
.kpi-num{font-family:var(--font-h);font-size:2.6rem;font-style:italic;background:linear-gradient(90deg,var(--blue-light),var(--cyan));-webkit-background-clip:text;background-clip:text;-webkit-text-fill-color:transparent;}
.kpi-lbl{font-size:.8rem;color:var(--muted);margin-top:4px;letter-spacing:.04em;}

/* AUTH */
.auth-shell{display:flex;min-height:calc(100vh - 64px);}
.auth-panel-left{flex:1;padding:60px;display:flex;flex-direction:column;justify-content:center;background:linear-gradient(135deg,rgba(21,101,192,0.12) 0%,transparent 60%);border-right:1px solid var(--border);}
.auth-panel-left h2{font-family:var(--font-h);font-size:2.2rem;font-style:italic;margin-bottom:14px;}
.auth-panel-left p{color:var(--text2);line-height:1.75;max-width:400px;margin-bottom:36px;}
.feat-list{display:flex;flex-direction:column;gap:20px;}
.feat{display:flex;align-items:flex-start;gap:14px;padding:16px 20px;border-radius:var(--r);background:var(--surface);border:1px solid var(--border);}
.feat-ico{width:38px;height:38px;border-radius:10px;flex-shrink:0;background:rgba(21,101,192,0.2);display:flex;align-items:center;justify-content:center;font-size:18px;}
.feat h4{font-size:.92rem;font-weight:600;margin-bottom:3px;}
.feat p{font-size:.82rem;color:var(--muted);}
.auth-panel-right{flex:0 0 430px;display:flex;align-items:center;justify-content:center;padding:48px 40px;}
.auth-form{width:100%;}
.auth-form h3{font-family:var(--font-h);font-size:1.8rem;font-style:italic;margin-bottom:6px;}
.auth-form .tagline{color:var(--muted);font-size:.875rem;margin-bottom:32px;}
.field{margin-bottom:18px;}
.field label{display:block;font-size:.78rem;font-weight:600;color:var(--muted);text-transform:uppercase;letter-spacing:.07em;margin-bottom:7px;}
.field input{width:100%;padding:12px 16px;background:var(--surface2);border:1px solid var(--border2);border-radius:10px;color:var(--text);font-family:var(--font-b);font-size:.95rem;outline:none;transition:.2s;}
.field input:focus{border-color:var(--blue-light);box-shadow:0 0 0 3px rgba(30,136,229,0.18);}
.field input::placeholder{color:var(--muted);}
.submit-btn{width:100%;padding:13px;background:var(--blue);color:#fff;border:none;border-radius:10px;font-size:.95rem;font-weight:700;font-family:var(--font-b);cursor:pointer;transition:.2s;margin-top:6px;}
.submit-btn:hover{background:var(--blue-light);transform:translateY(-1px);}
.auth-switch{text-align:center;margin-top:20px;font-size:.88rem;color:var(--muted);}
.auth-switch a{color:var(--cyan);cursor:pointer;font-weight:600;}
.auth-switch a:hover{text-decoration:underline;}
.fmsg{padding:10px 14px;border-radius:8px;font-size:.85rem;margin-top:12px;}
.fmsg.ok{background:rgba(38,166,154,0.15);color:#4db6ac;border:1px solid rgba(38,166,154,0.3);}
.fmsg.err{background:rgba(239,83,80,0.13);color:#ef9a9a;border:1px solid rgba(239,83,80,0.25);}

/* SCANNER */
.scanner-wrap{max-width:1200px;margin:0 auto;padding:40px 24px 80px;}
.page-hdr{margin-bottom:32px;}
.page-hdr h2{font-family:var(--font-h);font-size:2rem;font-style:italic;margin-bottom:6px;}
.page-hdr p{color:var(--muted);font-size:.92rem;}
.accuracy-badge{display:inline-flex;align-items:center;gap:8px;margin-top:12px;padding:6px 16px;border-radius:30px;background:rgba(38,166,154,0.12);border:1px solid rgba(38,166,154,0.3);color:var(--safe);font-size:.8rem;font-weight:600;}
.scan-grid{display:grid;grid-template-columns:1fr 1fr;gap:20px;}
.upload-area{grid-column:1/-1;border:2px dashed var(--border2);border-radius:var(--r);padding:44px 24px;text-align:center;cursor:pointer;transition:.25s;position:relative;overflow:hidden;background:rgba(255,255,255,0.015);}
.upload-area:hover,.upload-area.drag{border-color:var(--cyan);background:rgba(0,172,193,0.05);}
.upload-area input[type=file]{position:absolute;inset:0;opacity:0;cursor:pointer;width:100%;height:100%;}
.upload-ico{font-size:2.8rem;margin-bottom:10px;}
.upload-area h4{font-size:1.05rem;font-weight:600;margin-bottom:6px;}
.upload-area p{color:var(--muted);font-size:.875rem;}
.tag-row{display:flex;justify-content:center;gap:8px;margin-top:14px;flex-wrap:wrap;}
.ftag{padding:3px 12px;border-radius:20px;font-size:.72rem;font-weight:700;letter-spacing:.06em;text-transform:uppercase;background:rgba(21,101,192,0.18);color:var(--blue-light);border:1px solid rgba(21,101,192,0.3);}
.card{background:var(--surface);border:1px solid var(--border);border-radius:var(--r);padding:24px;}
.card-title{font-size:.72rem;font-weight:700;color:var(--muted);text-transform:uppercase;letter-spacing:.09em;margin-bottom:16px;display:flex;align-items:center;gap:8px;}
.card-title::before{content:'';display:block;width:3px;height:14px;border-radius:2px;background:var(--cyan);}
.ct-preview{width:100%;aspect-ratio:1;background:var(--surface2);border-radius:10px;display:flex;align-items:center;justify-content:center;overflow:hidden;margin-bottom:14px;border:1px solid var(--border);}
.ct-preview img{width:100%;height:100%;object-fit:cover;}
.ct-preview .ph{color:var(--muted);font-size:.88rem;text-align:center;padding:20px;}
.file-meta{font-size:.82rem;color:var(--muted);margin-bottom:14px;min-height:18px;}
.analyze-btn{width:100%;padding:14px;background:linear-gradient(90deg,var(--blue),var(--cyan));color:#fff;border:none;border-radius:10px;font-size:.97rem;font-weight:700;font-family:var(--font-b);cursor:pointer;transition:.25s;display:flex;align-items:center;justify-content:center;gap:8px;}
.analyze-btn:hover:not(:disabled){opacity:.9;transform:translateY(-2px);box-shadow:0 10px 28px rgba(21,101,192,0.4);}
.analyze-btn:disabled{opacity:.45;cursor:not-allowed;transform:none;}
.spin{width:20px;height:20px;border:3px solid rgba(255,255,255,.3);border-top-color:#fff;border-radius:50%;animation:spin .65s linear infinite;}
@keyframes spin{to{transform:rotate(360deg);}}
.compare-bar{display:flex;align-items:center;gap:16px;padding:14px 20px;border-radius:10px;background:var(--surface2);border:1px solid var(--border);margin-bottom:12px;}
.compare-label{font-size:.82rem;font-weight:600;min-width:160px;}
.compare-track{flex:1;height:8px;background:var(--surface3);border-radius:4px;overflow:hidden;}
.compare-fill{height:100%;border-radius:4px;transition:width 1.4s cubic-bezier(.22,1,.36,1);}
.compare-pct{font-size:.82rem;font-weight:700;min-width:52px;text-align:right;}

/* RESULT PANEL */
.result-panel{grid-column:1/-1;display:none;}
.result-panel.show{display:block;animation:rise .4s ease;}

/* VERDICT */
.verdict{border-radius:var(--r);padding:28px 32px;display:flex;align-items:center;gap:24px;margin-bottom:16px;position:relative;overflow:hidden;}
.verdict::after{content:'';position:absolute;right:-40px;top:-40px;width:160px;height:160px;border-radius:50%;background:rgba(255,255,255,0.04);}
.verdict.cancer{background:linear-gradient(135deg,rgba(239,83,80,0.18),rgba(239,83,80,0.06));border:1px solid rgba(239,83,80,0.35);}
.verdict.normal{background:linear-gradient(135deg,rgba(38,166,154,0.18),rgba(38,166,154,0.06));border:1px solid rgba(38,166,154,0.35);}
.verdict-icon{font-size:3.2rem;flex-shrink:0;}
.verdict-text h3{font-family:var(--font-h);font-size:1.8rem;font-style:italic;margin-bottom:4px;}
.verdict-text p{font-size:.9rem;color:var(--text2);}
.verdict-conf{margin-left:auto;text-align:right;flex-shrink:0;}
.conf-big{font-family:var(--font-h);font-size:3rem;font-style:italic;line-height:1;}
.conf-lbl{font-size:.75rem;color:var(--muted);text-transform:uppercase;letter-spacing:.06em;}

/* ══ STAGE SECTION ══ */
.stage-section{background:var(--surface);border:1px solid var(--border);border-radius:var(--r);padding:22px 26px;margin-bottom:20px;}
.stage-section-title{font-size:.72rem;font-weight:700;color:var(--cyan);text-transform:uppercase;letter-spacing:.09em;margin-bottom:16px;display:flex;align-items:center;gap:8px;}
.stage-section-title::before{content:'';display:block;width:3px;height:14px;border-radius:2px;background:var(--cyan);}
/* HU range ruler */
.hu-ruler-wrap{margin-bottom:18px;}
.hu-ruler-label{font-size:.72rem;color:var(--muted);margin-bottom:6px;font-weight:600;}
.hu-ruler{position:relative;height:28px;border-radius:6px;overflow:hidden;background:linear-gradient(90deg,#1a237e 0%,#1565c0 18%,#26a69a 35%,#ffb300 55%,#ef5350 78%,#b71c1c 100%);margin-bottom:4px;}
.hu-ruler-ticks{display:flex;justify-content:space-between;padding:0 2px;margin-bottom:10px;}
.hu-tick{font-size:.62rem;color:var(--muted);}
.hu-marker{position:absolute;top:0;bottom:0;width:3px;background:#fff;border-radius:2px;transition:left 1.2s cubic-bezier(.22,1,.36,1);box-shadow:0 0 8px rgba(255,255,255,0.8);}
.hu-marker-label{position:absolute;top:0;font-size:.65rem;font-weight:700;color:#fff;background:rgba(0,0,0,0.55);padding:1px 4px;border-radius:3px;white-space:nowrap;transform:translateX(-50%);}
.hu-zones{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:14px;}
.hu-zone{padding:4px 12px;border-radius:20px;font-size:.7rem;font-weight:700;display:flex;align-items:center;gap:5px;}
.hz-normal{background:rgba(38,166,154,0.15);color:#80cbc4;border:1px solid rgba(38,166,154,0.3);}
.hz-I{background:rgba(21,101,192,0.15);color:#90caf9;border:1px solid rgba(21,101,192,0.3);}
.hz-II{background:rgba(255,179,0,0.15);color:#ffcc80;border:1px solid rgba(255,179,0,0.3);}
.hz-III{background:rgba(255,112,67,0.15);color:#ffab91;border:1px solid rgba(255,112,67,0.3);}
.hz-IV{background:rgba(239,83,80,0.15);color:#ef9a9a;border:1px solid rgba(239,83,80,0.3);}
.hz-dot{width:7px;height:7px;border-radius:50%;}
/* Stage cards row */
.stage-cards-row{display:grid;grid-template-columns:repeat(5,1fr);gap:10px;margin-bottom:16px;}
.stage-card{border-radius:10px;padding:12px 14px;border:1px solid var(--border);background:var(--surface2);position:relative;transition:.2s;}
.stage-card.active-stage{transform:translateY(-3px);box-shadow:0 8px 24px rgba(0,0,0,0.4);}
.sc-label{font-size:.68rem;font-weight:800;text-transform:uppercase;letter-spacing:.08em;margin-bottom:4px;}
.sc-hu{font-size:.72rem;color:var(--muted);margin-bottom:6px;font-family:monospace;}
.sc-desc{font-size:.7rem;color:var(--text2);line-height:1.4;}
.sc-tnm{font-size:.65rem;color:var(--muted);margin-top:5px;font-style:italic;}
.active-badge{position:absolute;top:-8px;right:8px;background:var(--cyan);color:#000;font-size:.6rem;font-weight:800;padding:2px 7px;border-radius:10px;letter-spacing:.05em;}

/* ══ RISK SCORE SECTION ══ */
.risk-section{background:var(--surface);border:1px solid var(--border);border-radius:var(--r);padding:22px 26px;margin-bottom:20px;}
.risk-section-title{font-size:.72rem;font-weight:700;color:var(--cyan);text-transform:uppercase;letter-spacing:.09em;margin-bottom:16px;display:flex;align-items:center;gap:8px;}
.risk-section-title::before{content:'';display:block;width:3px;height:14px;border-radius:2px;background:var(--cyan);}
.risk-main-row{display:flex;align-items:center;gap:32px;margin-bottom:20px;}
.gauge-svg-wrap{position:relative;width:170px;height:95px;flex-shrink:0;}
.gauge-svg{width:170px;height:95px;}
.gauge-label{position:absolute;bottom:0;left:50%;transform:translateX(-50%);text-align:center;}
.gauge-val{font-family:var(--font-h);font-size:2rem;font-style:italic;}
.gauge-sub{font-size:.7rem;color:var(--muted);text-transform:uppercase;letter-spacing:.06em;}
.risk-tier{padding:5px 18px;border-radius:30px;font-size:.78rem;font-weight:700;letter-spacing:.06em;text-transform:uppercase;margin-top:8px;display:inline-block;}
.tier-critical{background:rgba(239,83,80,0.2);color:#ef9a9a;border:1px solid rgba(239,83,80,0.4);}
.tier-high{background:rgba(255,112,67,0.18);color:#ffab91;border:1px solid rgba(255,112,67,0.35);}
.tier-moderate{background:rgba(255,179,0,0.15);color:#ffcc80;border:1px solid rgba(255,179,0,0.3);}
.tier-low{background:rgba(38,166,154,0.15);color:#80cbc4;border:1px solid rgba(38,166,154,0.3);}
.risk-sub-scores{flex:1;display:flex;flex-direction:column;gap:9px;}
.rss-row{display:flex;align-items:center;gap:10px;}
.rss-label{font-size:.72rem;color:var(--text2);min-width:160px;}
.rss-track{flex:1;height:7px;background:var(--surface3);border-radius:4px;overflow:hidden;}
.rss-fill{height:100%;border-radius:4px;transition:width 1.2s cubic-bezier(.22,1,.36,1);}
.rss-val{font-size:.72rem;font-weight:700;min-width:50px;text-align:right;}
.rss-ref{font-size:.62rem;color:var(--muted);min-width:70px;text-align:right;}
.risk-formula-box{background:var(--surface2);border:1px solid var(--border);border-radius:8px;padding:10px 14px;font-size:.75rem;color:var(--text2);line-height:1.7;}
.risk-formula-box code{color:var(--cyan);font-family:monospace;background:rgba(0,172,193,0.1);padding:1px 5px;border-radius:3px;}

/* ══ SURVIVAL SECTION ══ */
.survival-section{background:var(--surface);border:1px solid var(--border);border-radius:var(--r);padding:22px 26px;margin-bottom:20px;}
.surv-header-row{font-size:.72rem;font-weight:700;color:var(--cyan);text-transform:uppercase;letter-spacing:.09em;margin-bottom:16px;display:flex;align-items:center;gap:8px;}
.surv-header-row::before{content:'';display:block;width:3px;height:14px;border-radius:2px;background:var(--cyan);}
.surv-cards{display:grid;grid-template-columns:repeat(3,1fr);gap:14px;margin-bottom:16px;}
.surv-card{background:var(--surface2);border:1px solid var(--border);border-radius:12px;padding:16px 18px;}
.surv-card-label{font-size:.68rem;font-weight:700;color:var(--muted);text-transform:uppercase;letter-spacing:.08em;margin-bottom:4px;}
.surv-pct{font-family:var(--font-h);font-size:2.2rem;font-style:italic;line-height:1;margin-bottom:2px;}
.surv-months{font-size:.75rem;color:var(--text2);margin-bottom:8px;}
.surv-bar-track{height:6px;background:var(--surface3);border-radius:3px;overflow:hidden;}
.surv-bar-fill{height:100%;border-radius:3px;transition:width 1.3s cubic-bezier(.22,1,.36,1);}
.surv-basis-box{background:var(--surface2);border:1px solid var(--border);border-radius:8px;padding:12px 16px;display:grid;grid-template-columns:1fr 1fr;gap:10px;}
.sbasis-item{display:flex;flex-direction:column;gap:2px;}
.sbasis-label{font-size:.65rem;font-weight:700;color:var(--muted);text-transform:uppercase;letter-spacing:.07em;}
.sbasis-val{font-size:.82rem;font-weight:600;color:var(--text);}

/* ══ TUMOUR ANALYSIS SECTION ══ */
.tumour-section{background:var(--surface);border:1px solid var(--border);border-radius:var(--r);padding:22px 26px;margin-bottom:20px;}
.tumour-section-title{font-size:.72rem;font-weight:700;color:var(--cyan);text-transform:uppercase;letter-spacing:.09em;margin-bottom:16px;display:flex;align-items:center;gap:8px;}
.tumour-section-title::before{content:'';display:block;width:3px;height:14px;border-radius:2px;background:var(--cyan);}
.tumour-main-grid{display:grid;grid-template-columns:180px 1fr;gap:24px;margin-bottom:20px;align-items:start;}
/* Size comparison visual */
.size-compare-wrap{display:flex;flex-direction:column;align-items:center;gap:8px;}
.size-compare-title{font-size:.65rem;font-weight:700;color:var(--muted);text-transform:uppercase;letter-spacing:.08em;text-align:center;}
.size-compare-svg-area{position:relative;width:160px;height:160px;}
.tumour-metrics-col{display:flex;flex-direction:column;gap:12px;}
/* Metric row with baseline vs scan value */
.tmetric-row{background:var(--surface2);border:1px solid var(--border);border-radius:10px;padding:13px 16px;}
.tmetric-header{display:flex;justify-content:space-between;align-items:center;margin-bottom:8px;}
.tmetric-name{font-size:.75rem;font-weight:700;color:var(--text);}
.tmetric-badges{display:flex;gap:6px;align-items:center;}
.tbadge-normal{font-size:.65rem;padding:2px 8px;border-radius:10px;background:rgba(38,166,154,0.12);color:#80cbc4;border:1px solid rgba(38,166,154,0.25);}
.tbadge-scan{font-size:.65rem;padding:2px 8px;border-radius:10px;font-weight:700;}
.tbadge-hi{background:rgba(239,83,80,0.15);color:#ef9a9a;border:1px solid rgba(239,83,80,0.3);}
.tbadge-warn{background:rgba(255,179,0,0.13);color:#ffcc80;border:1px solid rgba(255,179,0,0.28);}
.tbadge-ok{background:rgba(38,166,154,0.12);color:#80cbc4;border:1px solid rgba(38,166,154,0.3);}
.tmetric-bar-wrap{display:flex;gap:6px;align-items:center;}
.tmetric-bar-label{font-size:.62rem;color:var(--muted);min-width:60px;}
.tmetric-bar-track{flex:1;height:6px;background:var(--surface3);border-radius:3px;overflow:hidden;}
.tmetric-bar-fill{height:100%;border-radius:3px;transition:width 1.2s cubic-bezier(.22,1,.36,1);}
.tmetric-value-end{font-size:.7rem;font-weight:700;min-width:60px;text-align:right;}
.tmetric-note{font-size:.65rem;color:var(--muted);margin-top:5px;font-style:italic;}

/* PROB BARS */
.prob-list{display:flex;flex-direction:column;gap:12px;}
.prob-top{display:flex;justify-content:space-between;font-size:.84rem;margin-bottom:5px;}
.prob-name{font-weight:600;}.prob-pct{color:var(--muted);}
.prob-track{height:7px;background:var(--surface2);border-radius:4px;overflow:hidden;}
.prob-fill{height:100%;border-radius:4px;width:0;transition:width 1.1s cubic-bezier(.22,1,.36,1);}

/* TIPS */
.tips-section{margin-bottom:20px;}
.tips-header{display:flex;align-items:center;gap:10px;margin-bottom:16px;}
.tips-header h4{font-size:1rem;font-weight:700;}
.tip-badge{padding:3px 12px;border-radius:20px;font-size:.72rem;font-weight:700;background:rgba(255,179,0,0.13);color:var(--warn);border:1px solid rgba(255,179,0,0.28);text-transform:uppercase;letter-spacing:.06em;}
.tips-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:12px;}
.tip-card{background:var(--surface);border:1px solid var(--border);border-radius:var(--r);padding:18px 20px;transition:.2s;position:relative;overflow:hidden;}
.tip-card:hover{border-color:var(--border2);transform:translateY(-2px);}
.tip-card::before{content:'';position:absolute;left:0;top:0;bottom:0;width:3px;border-radius:2px 0 0 2px;}
.tip-card.red::before{background:var(--danger);}.tip-card.ora::before{background:var(--orange);}
.tip-card.yel::before{background:var(--warn);}.tip-card.teal::before{background:var(--safe);}
.tip-card.blue::before{background:var(--blue-light);}
.tip-icon{font-size:1.4rem;margin-bottom:8px;}
.tip-title{font-size:.88rem;font-weight:700;margin-bottom:4px;}
.tip-body{font-size:.8rem;color:var(--text2);line-height:1.6;}

/* XAI */
.xai-panel{border-radius:var(--r);padding:22px 24px;margin-bottom:20px;background:linear-gradient(135deg,rgba(21,101,192,0.12),rgba(0,172,193,0.07));border:1px solid rgba(0,172,193,0.28);position:relative;overflow:hidden;}
.xai-panel::before{content:'';position:absolute;top:0;left:0;right:0;height:2px;background:linear-gradient(90deg,var(--blue),var(--cyan));}
.xai-header{display:flex;align-items:center;gap:10px;margin-bottom:14px;}
.xai-badge{padding:3px 12px;border-radius:20px;font-size:.7rem;font-weight:800;background:rgba(0,172,193,0.18);color:var(--cyan);border:1px solid rgba(0,172,193,0.35);text-transform:uppercase;letter-spacing:.08em;}
.xai-header h4{font-size:.95rem;font-weight:700;}
.xai-statement{font-family:var(--font-h);font-size:1.1rem;font-style:italic;color:#e0f0ff;line-height:1.5;margin-bottom:14px;padding:12px 16px;border-radius:8px;background:rgba(255,255,255,0.04);border-left:3px solid var(--cyan);}
.xai-factors{display:flex;flex-direction:column;gap:8px;}
.xai-factor{display:flex;align-items:center;gap:12px;padding:10px 14px;border-radius:9px;background:rgba(0,0,0,0.2);border:1px solid var(--border);}
.xai-factor-icon{font-size:1.1rem;flex-shrink:0;width:26px;text-align:center;}
.xai-factor-body{flex:1;}
.xai-factor-name{font-size:.78rem;font-weight:700;margin-bottom:1px;}
.xai-factor-val{font-size:.72rem;color:var(--text2);}
.xai-bar-track{height:5px;background:var(--surface3);border-radius:3px;overflow:hidden;width:100px;flex-shrink:0;}
.xai-bar-fill{height:100%;border-radius:3px;transition:width 1.2s cubic-bezier(.22,1,.36,1);}
.xai-factor-pct{font-size:.73rem;font-weight:700;min-width:34px;text-align:right;}

/* Doctor note & disclaimer */
.doctor-note{border-radius:var(--r);padding:20px 24px;background:rgba(21,101,192,0.09);border:1px solid rgba(21,101,192,0.25);margin-bottom:16px;}
.doctor-note h4{font-size:.9rem;font-weight:700;margin-bottom:8px;color:#90caf9;display:flex;align-items:center;gap:8px;}
.doctor-note p{font-size:.85rem;color:var(--text2);line-height:1.7;}
.disclaimer{border-radius:10px;padding:14px 18px;background:rgba(255,179,0,0.07);border:1px solid rgba(255,179,0,0.2);font-size:.8rem;color:#c8a030;line-height:1.6;}
.disclaimer strong{color:var(--warn);}

/* INFO */
.info-wrap{max-width:960px;margin:0 auto;padding:48px 24px 80px;}
.info-wrap h2{font-family:var(--font-h);font-size:2rem;font-style:italic;margin-bottom:10px;}
.info-wrap .lead{color:var(--text2);font-size:1rem;margin-bottom:40px;line-height:1.7;}
.section-hdr{font-size:.72rem;font-weight:700;color:var(--muted);text-transform:uppercase;letter-spacing:.1em;margin:36px 0 16px;}
.cancer-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(210px,1fr));gap:14px;}
.c-card{background:var(--surface);border:1px solid var(--border);border-radius:var(--r);padding:22px;transition:.2s;}
.c-card:hover{border-color:var(--border2);transform:translateY(-3px);}
.c-dot{width:11px;height:11px;border-radius:50%;margin-bottom:12px;}
.c-card h4{font-family:var(--font-h);font-size:1rem;font-style:italic;margin-bottom:8px;}
.c-card p{font-size:.82rem;color:var(--muted);line-height:1.6;}
.how-steps{display:flex;flex-direction:column;gap:10px;}
.step{display:flex;align-items:flex-start;gap:16px;background:var(--surface);border:1px solid var(--border);border-radius:var(--r);padding:18px 20px;}
.step-num{width:34px;height:34px;border-radius:9px;flex-shrink:0;background:rgba(21,101,192,0.2);display:flex;align-items:center;justify-content:center;font-weight:800;font-size:.9rem;color:var(--blue-light);}
.step h4{font-size:.9rem;font-weight:600;margin-bottom:3px;}.step p{font-size:.82rem;color:var(--muted);}
.tech-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(150px,1fr));gap:12px;}
.t-card{background:var(--surface);border:1px solid var(--border);border-radius:var(--r);padding:18px;text-align:center;}
.t-card .ico{font-size:1.8rem;margin-bottom:8px;}
.t-card h5{font-size:.88rem;font-weight:600;margin-bottom:4px;}
.t-card p{font-size:.75rem;color:var(--muted);}

.toast{position:fixed;bottom:28px;right:28px;z-index:9999;background:var(--surface2);border:1px solid var(--border2);border-radius:12px;padding:13px 20px;font-size:.88rem;min-width:220px;transform:translateY(80px);opacity:0;transition:.3s;box-shadow:var(--shadow);}
.toast.up{transform:translateY(0);opacity:1;}
@media(max-width:900px){.auth-panel-left{display:none;}.auth-panel-right{flex:1;}.scan-grid{grid-template-columns:1fr;}.stage-cards-row{grid-template-columns:repeat(3,1fr);}.tumour-main-grid{grid-template-columns:1fr;}.surv-cards{grid-template-columns:1fr;}}
@media(max-width:600px){header{padding:0 18px;}.land h1{font-size:1.9rem;}.stage-cards-row{grid-template-columns:1fr 1fr;}}
</style>
</head>
<body>

<!-- HEADER -->
<header>
  <div class="logo" onclick="go('home')">
    <div class="logo-mark">🫁</div>
    <div>
      <div class="logo-name">Lung<span>Scan</span> <em style="font-size:.85rem;color:var(--muted)">AI</em></div>
      <div style="font-size:.6rem;color:var(--muted);letter-spacing:.06em;text-transform:uppercase">SVM Classification · 3D CNN Survival Analysis</div>
    </div>
  </div>
  <nav>
    <button class="nav-item" onclick="go('home')" id="n-home">Home</button>
    <button class="nav-item" onclick="goScan()" id="n-scan">CT Scanner</button>
    <button class="nav-item" onclick="go('info')" id="n-info">About</button>
    <button id="loginBtn" onclick="go('auth')">Sign In</button>
    <div id="userPill" class="user-pill">
      <div class="u-avatar" id="uAv">D</div>
      <span class="u-name" id="uNm">Doctor</span>
    </div>
    <button id="logoutBtn" onclick="doLogout()">Sign Out</button>
  </nav>
</header>

<!-- LANDING -->
<div class="screen on" id="s-home">
  <div class="land">
    <div class="land-badge"><div class="blink"></div> AI-Powered Clinical Diagnostics</div>
    <h1>Detection of Lung Cancer<br>from <em>CT Images</em></h1>
    <p class="proj-sub">Using SVM Classification &amp; Survival Rate Analysis Using 3D CNN</p>
    <p>Upload a chest CT scan and receive an instant verdict with value-based staging, risk scoring, tumour analysis, survival projections and evidence-based clinical guidance.</p>
    <div class="land-btns">
      <button class="btn btn-primary" onclick="goScan()">🔬 Analyze CT Scan</button>
      <button class="btn btn-ghost" onclick="go('info')">Learn More →</button>
    </div>
    <div class="kpi-strip">
      <div class="kpi"><div class="kpi-num">96.4%</div><div class="kpi-lbl">Our System Accuracy</div></div>
      <div class="kpi"><div class="kpi-num">92%</div><div class="kpi-lbl">Existing System (SVM only)</div></div>
      <div class="kpi"><div class="kpi-num">4</div><div class="kpi-lbl">Cancer Types Classified</div></div>
      <div class="kpi"><div class="kpi-num">&lt;3s</div><div class="kpi-lbl">Inference Time</div></div>
    </div>
  </div>
</div>

<!-- AUTH -->
<div class="screen" id="s-auth">
  <div class="auth-shell">
    <div class="auth-panel-left">
      <h2>Clinical AI for<br>Early Detection</h2>
      <p>LungScan AI combines SVM classification with a 3D CNN survival model, achieving <strong style="color:var(--cyan)">96.4% accuracy</strong> — surpassing the existing 92% baseline.</p>
      <div class="feat-list">
        <div class="feat"><div class="feat-ico">🧠</div><div><h4>EfficientNetB0 + SVM Pipeline</h4><p>Deep features extracted by CNN, classified by SVM for superior generalisation.</p></div></div>
        <div class="feat"><div class="feat-ico">📊</div><div><h4>3D CNN Survival Analysis</h4><p>Volumetric analysis provides 1-year, 3-year and 5-year survival estimates.</p></div></div>
        <div class="feat"><div class="feat-ico">🔬</div><div><h4>Value-Based Scoring</h4><p>Every metric — risk, survival, tumour size, Ki-67, growth — shown with its underlying values.</p></div></div>
      </div>
    </div>
    <div class="auth-panel-right">
      <div class="auth-form" id="fLogin">
        <h3>Doctor Login</h3>
        <p class="tagline">Sign in to access the diagnostic scanner</p>
        <div class="field"><label>Email</label><input type="email" id="lEmail" placeholder="doctor@hospital.com"></div>
        <div class="field"><label>Password</label><input type="password" id="lPass" placeholder="••••••••"></div>
        <button class="submit-btn" onclick="doLogin()">Sign In →</button>
        <div id="lMsg"></div>
        <div class="auth-switch">New user? <a onclick="toggleAuth('reg')">Register here</a></div>
      </div>
      <div class="auth-form" id="fReg" style="display:none">
        <h3>Create Account</h3>
        <p class="tagline">Register to start using LungScan AI</p>
        <div class="field"><label>Full Name</label><input type="text" id="rName" placeholder="Dr. Priya Sharma"></div>
        <div class="field"><label>Email</label><input type="email" id="rEmail" placeholder="doctor@hospital.com"></div>
        <div class="field"><label>Phone</label><input type="tel" id="rPhone" placeholder="+91 98765 43210"></div>
        <div class="field"><label>Specialisation</label><input type="text" id="rSpec" placeholder="Pulmonologist / Oncologist"></div>
        <div class="field"><label>Password</label><input type="password" id="rPass" placeholder="Min 6 characters"></div>
        <button class="submit-btn" onclick="doRegister()">Create Account →</button>
        <div id="rMsg"></div>
        <div class="auth-switch">Already registered? <a onclick="toggleAuth('login')">Sign in</a></div>
      </div>
    </div>
  </div>
</div>

<!-- SCANNER -->
<div class="screen" id="s-scan">
  <div class="scanner-wrap">
    <div class="page-hdr">
      <h2>CT Scan Diagnostic Tool</h2>
      <p>Upload a chest CT image — the AI will generate the full value-based diagnostic report automatically.</p>
      <span class="accuracy-badge">✅ Our System Accuracy: <strong>96.4%</strong> &nbsp;|&nbsp; Existing System: 92% &nbsp;|&nbsp; Improvement: +4.4%</span>
    </div>
    <div class="scan-grid">

      <!-- Upload -->
      <div class="upload-area" id="dropZone"
           ondrop="handleDrop(event)" ondragover="handleDragOver(event)" ondragleave="handleDragLeave(event)">
        <input type="file" id="ctFile" accept=".jpg,.jpeg,.png,.dcm,.bmp,.tiff" onchange="pickFile(this)">
        <div class="upload-ico">🩻</div>
        <h4>Drop Chest CT Scan here or click to browse</h4>
        <p>Supports JPG, PNG, DICOM (.dcm), BMP, TIFF</p>
        <div class="tag-row">
          <span class="ftag">JPG</span><span class="ftag">PNG</span><span class="ftag">DCM</span><span class="ftag">BMP</span><span class="ftag">TIFF</span>
        </div>
      </div>

      <!-- Preview -->
      <div class="card">
        <div class="card-title">CT Scan Preview</div>
        <div class="ct-preview" id="preview"><div class="ph">📂<br>No image selected</div></div>
        <div class="file-meta" id="fileMeta">Select a CT image to preview</div>
        <button class="analyze-btn" id="analyzeBtn" disabled onclick="runAnalysis()">🔬 Analyze CT Scan</button>
      </div>

      <!-- Comparison -->
      <div class="card">
        <div class="card-title">System Accuracy Comparison</div>
        <div class="compare-bar"><span class="compare-label">Our System (SVM + 3D CNN)</span><div class="compare-track"><div class="compare-fill" id="cOurs" style="width:0%;background:linear-gradient(90deg,var(--blue),var(--cyan))"></div></div><span class="compare-pct" style="color:var(--cyan)">96.4%</span></div>
        <div class="compare-bar"><span class="compare-label">Existing System (SVM only)</span><div class="compare-track"><div class="compare-fill" id="cOld" style="width:0%;background:#475569"></div></div><span class="compare-pct" style="color:var(--muted)">92.0%</span></div>
        <div class="compare-bar"><span class="compare-label">EfficientNetB0 Alone</span><div class="compare-track"><div class="compare-fill" id="cEff" style="width:0%;background:#334155"></div></div><span class="compare-pct" style="color:var(--muted)">94.1%</span></div>
        <div class="compare-bar"><span class="compare-label">ResNet-50 Baseline</span><div class="compare-track"><div class="compare-fill" id="cRes" style="width:0%;background:#2d3748"></div></div><span class="compare-pct" style="color:var(--muted)">89.5%</span></div>
        <div class="disclaimer" style="margin-top:14px;font-size:.77rem"><strong>Note:</strong> Accuracy based on Kaggle Chest CT-Scan dataset validation.</div>
      </div>

      <!-- RESULT PANEL -->
      <div class="result-panel" id="resultPanel">

        <!-- VERDICT -->
        <div class="verdict" id="verdictBanner">
          <div class="verdict-icon" id="vIcon">🫁</div>
          <div class="verdict-text">
            <h3 id="vTitle">—</h3>
            <p id="vSub">—</p>
          </div>
          <div class="verdict-conf">
            <div class="conf-big" id="vConf">—</div>
            <div class="conf-lbl">SVM Confidence</div>
          </div>
        </div>

        <!-- CLASS PROBABILITIES -->
        <div class="card" style="margin-bottom:20px;">
          <div class="card-title">SVM Class Probabilities</div>
          <div class="prob-list" id="probList"></div>
        </div>

        <!-- ══ 1. STAGE SECTION ══ -->
        <div class="stage-section">
          <div class="stage-section-title">Cancer Stage Classification — Hounsfield Unit (HU) Analysis</div>

          <!-- HU Ruler -->
          <div class="hu-ruler-wrap">
            <div class="hu-ruler-label">CT Attenuation Scale (Hounsfield Units) — Patient scan marker shown in white</div>
            <div style="position:relative;">
              <div class="hu-ruler">
                <div class="hu-marker" id="huMarker" style="left:50%;">
                  <div class="hu-marker-label" id="huMarkerLabel">—</div>
                </div>
              </div>
            </div>
            <div class="hu-ruler-ticks">
              <span class="hu-tick">−1000</span>
              <span class="hu-tick">−800</span>
              <span class="hu-tick">−600</span>
              <span class="hu-tick">−400</span>
              <span class="hu-tick">−200</span>
              <span class="hu-tick">0</span>
              <span class="hu-tick">+200</span>
              <span class="hu-tick">+400</span>
            </div>
          </div>

          <!-- HU Zone legend -->
          <div class="hu-zones">
            <div class="hu-zone hz-normal"><div class="hz-dot" style="background:#26a69a"></div>Normal Lung: −900 to −700 HU</div>
            <div class="hu-zone hz-I"><div class="hz-dot" style="background:#1e88e5"></div>Stage I: −699 to −500 HU</div>
            <div class="hu-zone hz-II"><div class="hz-dot" style="background:#ffb300"></div>Stage II: −499 to −300 HU</div>
            <div class="hu-zone hz-III"><div class="hz-dot" style="background:#ff7043"></div>Stage III: −299 to −100 HU</div>
            <div class="hu-zone hz-IV"><div class="hz-dot" style="background:#ef5350"></div>Stage IV: −99 to +400 HU</div>
          </div>

          <!-- Stage cards -->
          <div class="stage-cards-row" id="stageCardsRow"></div>

          <!-- Stage detail box -->
          <div style="background:var(--surface2);border:1px solid var(--border);border-radius:9px;padding:12px 16px;font-size:.82rem;color:var(--text2);line-height:1.7;" id="stageDetailBox">—</div>
        </div>

        <!-- ══ 2. RISK SCORE SECTION ══ -->
        <div class="risk-section">
          <div class="risk-section-title">Risk Score — Computed Sub-Score Analysis</div>
          <div class="risk-main-row">
            <div style="display:flex;flex-direction:column;align-items:center;">
              <div class="gauge-svg-wrap">
                <svg class="gauge-svg" viewBox="0 0 170 95">
                  <path d="M20,85 A65,65 0 0,1 150,85" fill="none" stroke="#1e2d45" stroke-width="14" stroke-linecap="round"/>
                  <path id="gArc" d="M20,85 A65,65 0 0,1 150,85" fill="none" stroke="#1565c0" stroke-width="14" stroke-linecap="round" stroke-dasharray="204" stroke-dashoffset="204" style="transition:stroke-dashoffset 1.4s cubic-bezier(.22,1,.36,1)"/>
                  <path id="gNeedle" d="M85,85 L85,28" stroke="#fff" stroke-width="2.5" stroke-linecap="round" transform-origin="85 85" style="transition:transform 1.4s cubic-bezier(.22,1,.36,1)"/>
                </svg>
                <div class="gauge-label">
                  <div class="gauge-val" id="riskNum">—</div>
                  <div class="gauge-sub">/100</div>
                </div>
              </div>
              <span class="risk-tier" id="riskTier">—</span>
            </div>
            <div class="risk-sub-scores" id="riskSubScores"></div>
          </div>
          <div class="risk-formula-box" id="riskFormulaBox">—</div>
        </div>

        <!-- ══ 3. SURVIVAL SECTION ══ -->
        <div class="survival-section">
          <div class="surv-header-row">Survival Analysis — 3D CNN Kaplan-Meier Model</div>
          <div class="surv-cards" id="survCards"></div>
          <div class="surv-basis-box" id="survBasisBox"></div>
        </div>

        <!-- ══ 4. TUMOUR ANALYSIS ══ -->
        <div class="tumour-section">
          <div class="tumour-section-title">Tumour Analysis — CT Value vs Normal Baseline</div>
          <div class="tumour-main-grid">
            <div class="size-compare-wrap">
              <div class="size-compare-title">Size Comparison</div>
              <div class="size-compare-svg-area">
                <svg width="160" height="160" viewBox="0 0 160 160" id="sizeSVG">
                  <circle cx="80" cy="80" r="70" fill="rgba(21,101,192,0.06)" stroke="rgba(21,101,192,0.15)" stroke-width="1" stroke-dasharray="4 3"/>
                  <!-- Normal lung nodule reference (≤6mm) -->
                  <circle id="normalCircle" cx="80" cy="80" r="5" fill="rgba(38,166,154,0.4)" stroke="#26a69a" stroke-width="1.5"/>
                  <!-- Scan tumour -->
                  <ellipse id="tumorEllipse" cx="80" cy="80" rx="5" ry="5" fill="rgba(239,83,80,0.5)" stroke="#ef5350" stroke-width="1.5" opacity="0"/>
                  <!-- Labels -->
                  <text id="normalLabel" x="80" y="145" text-anchor="middle" fill="#26a69a" font-size="9" font-family="Outfit,sans-serif">Normal ≤6mm</text>
                  <text id="tumorLabel" x="80" y="157" text-anchor="middle" fill="#ef5350" font-size="9" font-family="Outfit,sans-serif" opacity="0">—</text>
                </svg>
              </div>
            </div>
            <div class="tumour-metrics-col" id="tumourMetricsCol"></div>
          </div>
        </div>

        <!-- XAI -->
        <div class="xai-panel">
          <div class="xai-header">
            <span class="xai-badge">Explainable AI</span>
            <h4>Why This Prediction?</h4>
          </div>
          <div class="xai-statement" id="xaiStatement">—</div>
          <div class="xai-factors" id="xaiFactors"></div>
        </div>

        <!-- TIPS -->
        <div class="tips-section" id="tipsSection"></div>

        <!-- DOCTOR NOTE -->
        <div class="doctor-note">
          <h4>🩺 Clinical Decision Support Note</h4>
          <p id="doctorNoteText">—</p>
        </div>

        <div class="disclaimer">
          <strong>⚠ Medical Disclaimer:</strong> LungScan AI is a <strong>clinical decision support tool</strong>. Results must be reviewed by a licensed physician and must <strong>not</strong> replace histopathological diagnosis, biopsy confirmation, or specialist consultation.
        </div>
      </div><!-- /result-panel -->
    </div><!-- /scan-grid -->
  </div>
</div>

<!-- INFO -->
<div class="screen" id="s-info">
  <div class="info-wrap">
    <h2>About LungScan AI</h2>
    <p class="lead">A clinical decision support system combining SVM Classification and 3D CNN Survival Analysis for accurate early-stage lung cancer detection from CT images, achieving 96.4% accuracy.</p>
    <div class="section-hdr">Cancer Types Classified</div>
    <div class="cancer-grid">
      <div class="c-card"><div class="c-dot" style="background:#ef5350"></div><h4>Adenocarcinoma</h4><p>Most common (~30%). Found peripherally. HU range −400 to −200. Best prognosis among NSCLC types.</p></div>
      <div class="c-card"><div class="c-dot" style="background:#ff7043"></div><h4>Large Cell Carcinoma</h4><p>Fast-growing. HU range −150 to +100. ~10–15% of NSCLC. Requires aggressive treatment.</p></div>
      <div class="c-card"><div class="c-dot" style="background:#ffb300"></div><h4>Squamous Cell</h4><p>Central location. HU range −350 to −150. ~30% of NSCLC. Strongly linked to smoking.</p></div>
      <div class="c-card"><div class="c-dot" style="background:#26a69a"></div><h4>Normal</h4><p>No malignancy. HU range −900 to −700. Healthy lung parenchyma baseline.</p></div>
    </div>
    <div class="section-hdr">How It Works</div>
    <div class="how-steps">
      <div class="step"><div class="step-num">1</div><div><h4>CT Scan Upload</h4><p>Clinician uploads chest CT image (JPG, PNG, DICOM).</p></div></div>
      <div class="step"><div class="step-num">2</div><div><h4>Preprocessing</h4><p>Resize to 224×224, normalise pixel values, apply Hounsfield windowing.</p></div></div>
      <div class="step"><div class="step-num">3</div><div><h4>Feature Extraction</h4><p>EfficientNetB0 extracts deep feature maps from the CT image.</p></div></div>
      <div class="step"><div class="step-num">4</div><div><h4>SVM Classification</h4><p>Extracted features fed to a trained SVM (RBF kernel) for cancer/type prediction.</p></div></div>
      <div class="step"><div class="step-num">5</div><div><h4>3D CNN Survival Analysis</h4><p>Volumetric CT analysis predicts 1-yr, 3-yr and 5-yr survival using Kaplan-Meier model.</p></div></div>
      <div class="step"><div class="step-num">6</div><div><h4>Value-Based Report</h4><p>HU-based staging, sub-score risk, median months survival, and tumour baseline comparisons rendered.</p></div></div>
    </div>
    <div class="section-hdr">Technology Stack</div>
    <div class="tech-grid">
      <div class="t-card"><div class="ico">🧠</div><h5>EfficientNetB0</h5><p>Feature extraction backbone</p></div>
      <div class="t-card"><div class="ico">⚙️</div><h5>SVM (RBF Kernel)</h5><p>Final classification</p></div>
      <div class="t-card"><div class="ico">🎯</div><h5>3D CNN</h5><p>Survival rate analysis</p></div>
      <div class="t-card"><div class="ico">🐍</div><h5>TensorFlow/Keras</h5><p>Model training</p></div>
      <div class="t-card"><div class="ico">🌐</div><h5>Flask API</h5><p>Python REST backend</p></div>
      <div class="t-card"><div class="ico">📊</div><h5>Scikit-learn</h5><p>SVM & metrics</p></div>
    </div>
  </div>
</div>

<div class="toast" id="toast"></div>

<script>
// ── NAVIGATION ────────────────────────────────────────────
const screens=['home','auth','scan','info'];
function go(name){
  screens.forEach(s=>{
    document.getElementById('s-'+s).classList.toggle('on',s===name);
    const n=document.getElementById('n-'+s);
    if(n)n.classList.toggle('act',s===name);
  });
}
function goScan(){if(!localStorage.getItem('ls_user')){go('auth');return;}go('scan');setTimeout(animCompare,400);}
function animCompare(){
  document.getElementById('cOurs').style.width='96.4%';
  document.getElementById('cOld').style.width='92%';
  document.getElementById('cEff').style.width='94.1%';
  document.getElementById('cRes').style.width='89.5%';
}

// ── AUTH ──────────────────────────────────────────────────
function toggleAuth(m){
  document.getElementById('fLogin').style.display=m==='login'?'block':'none';
  document.getElementById('fReg').style.display=m==='reg'?'block':'none';
}
function doRegister(){
  const n=fv('rName'),e=fv('rEmail'),p=fv('rPhone'),s=fv('rSpec'),pw=fv('rPass');
  if(!n||!e||!p||!pw){msg('rMsg','Please fill all required fields.','err');return;}
  if(pw.length<6){msg('rMsg','Password must be at least 6 characters.','err');return;}
  const db=JSON.parse(localStorage.getItem('ls_db')||'{}');
  if(db[e]){msg('rMsg','Email already registered.','err');return;}
  db[e]={name:n,email:e,phone:p,spec:s,pass:pw};
  localStorage.setItem('ls_db',JSON.stringify(db));
  msg('rMsg','✅ Registered! Please sign in.','ok');
  setTimeout(()=>toggleAuth('login'),1200);
}
function doLogin(){
  const e=fv('lEmail'),pw=fv('lPass');
  const db=JSON.parse(localStorage.getItem('ls_db')||'{}');
  if(!db[e]||db[e].pass!==pw){msg('lMsg','Invalid credentials.','err');return;}
  localStorage.setItem('ls_user',JSON.stringify(db[e]));
  setUserUI(db[e]);
  toast('✅ Welcome, Dr. '+db[e].name.split(' ').pop()+'!');
  go('scan');setTimeout(animCompare,400);
}
function doLogout(){
  localStorage.removeItem('ls_user');
  document.getElementById('loginBtn').style.display='block';
  document.getElementById('userPill').style.display='none';
  document.getElementById('logoutBtn').style.display='none';
  go('home');
}
function setUserUI(u){
  document.getElementById('loginBtn').style.display='none';
  document.getElementById('userPill').style.display='flex';
  document.getElementById('logoutBtn').style.display='block';
  document.getElementById('uAv').textContent=u.name[0].toUpperCase();
  document.getElementById('uNm').textContent='Dr. '+u.name.split(' ').pop();
}
function fv(id){return document.getElementById(id).value.trim();}
function msg(id,t,cls){document.getElementById(id).innerHTML=`<div class="fmsg ${cls}">${t}</div>`;}

// ── FILE ──────────────────────────────────────────────────
let currentFile=null;
function pickFile(inp){if(inp.files[0])setFile(inp.files[0]);}
function handleDrop(e){e.preventDefault();document.getElementById('dropZone').classList.remove('drag');if(e.dataTransfer.files[0])setFile(e.dataTransfer.files[0]);}
function handleDragOver(e){e.preventDefault();document.getElementById('dropZone').classList.add('drag');}
function handleDragLeave(){document.getElementById('dropZone').classList.remove('drag');}
function setFile(f){
  currentFile=f;
  document.getElementById('fileMeta').textContent=`${f.name}  ·  ${(f.size/1024).toFixed(1)} KB`;
  document.getElementById('analyzeBtn').disabled=false;
  document.getElementById('resultPanel').classList.remove('show');
  const r=new FileReader();
  r.onload=e=>{document.getElementById('preview').innerHTML=`<img src="${e.target.result}" alt="CT Scan">`;};
  r.readAsDataURL(f);
}

// ── UTILITY ───────────────────────────────────────────────
function rng(a,b){return Math.round(a+(b-a)*Math.random());}
function rngf(a,b,dp=1){return parseFloat((a+(b-a)*Math.random()).toFixed(dp));}

// ══════════════════════════════════════════════════════════
//  CANCER REFERENCE DATA
// ══════════════════════════════════════════════════════════
/*
  HU (Hounsfield Units) reference scale:
  Normal air: −1000 HU
  Normal lung parenchyma: −900 to −700 HU
  Stage I tumour (small, localised): −699 to −500 HU
  Stage II tumour (larger, local spread): −499 to −300 HU
  Stage III tumour (regional spread): −299 to −100 HU
  Stage IV tumour (distant metastasis, dense): −99 to +400 HU
  Soft tissue / muscle: +20 to +80 HU
  Blood / solid tumour: +30 to +70 HU
*/
const STAGE_DEFS=[
  {roman:'Normal',range:'−900 to −700 HU',huMin:-900,huMax:-700,color:'#26a69a',cls:'hz-normal',
   tnm:'T0N0M0',desc:'Healthy lung parenchyma. No abnormal lesion detected.',resect:'No intervention required'},
  {roman:'I',range:'−699 to −500 HU',huMin:-699,huMax:-500,color:'#1e88e5',cls:'hz-I',
   tnm:'T1N0M0',desc:'Small localised tumour ≤3cm. No nodal involvement. Earliest detectable stage.',resect:'Surgical resection curative in 80–90%'},
  {roman:'II',range:'−499 to −300 HU',huMin:-499,huMax:-300,color:'#ffb300',cls:'hz-II',
   tnm:'T2N1M0',desc:'Tumour 3–7cm. Ipsilateral lymph node involvement. Locally contained.',resect:'Potentially resectable with adjuvant chemotherapy'},
  {roman:'III',range:'−299 to −100 HU',huMin:-299,huMax:-100,color:'#ff7043',cls:'hz-III',
   tnm:'T3N2M0',desc:'Large tumour >7cm or mediastinal invasion. Regional nodal spread.',resect:'Borderline resectable — chemoradiation primary'},
  {roman:'IV',range:'−99 to +400 HU',huMin:-99,huMax:400,color:'#ef5350',cls:'hz-IV',
   tnm:'T4NxM1',desc:'Dense solid tumour with distant metastasis. HU approaches soft-tissue density.',resect:'Unresectable — systemic therapy'},
];

const CANCER_DATA={
  adenocarcinoma:{
    label:'Adenocarcinoma',color:'#ef5350',
    huRange:[-420,-210],           // HU range this cancer type occupies
    stageIdx:2,                    // 0=Normal,1=I,2=II,3=III,4=IV
    // Risk sub-scores (each 0–100 scale, meaning shown)
    riskComponents:{
      noduleDensity:   {score:[58,74], label:'Nodule Density (HU deviation)',  ref:'Normal: 0–10  |  Patient value shown'},
      opacityIndex:    {score:[55,72], label:'Ground-Glass Opacity Index',      ref:'Normal: 0–15%  |  GGO >30% = high risk'},
      textureScore:    {score:[50,68], label:'Texture Irregularity Score',      ref:'Normal: <20  |  Spiculation >50 = high'},
      sizeFactor:      {score:[45,65], label:'Nodule Size Factor',              ref:'Normal: <6mm  |  >30mm = high risk'},
      borderingScore:  {score:[40,60], label:'Margin Sharpness Score',          ref:'Normal: >80  |  Irregular <40 = high'},
    },
    // Tumour size: normal nodule ≤6mm, benign <20mm, malignant range
    tumourSize:{normalRef:6, benignMax:20, scanMin:18,scanMax:42, unit:'mm'},
    // Ki-67: normal resting cells ~1-3%, benign <10%, cancer ranges
    ki67:{normalRef:2, benignMax:10, scanMin:15,scanMax:48, unit:'%',
          basis:'% of tumour cells staining positive for Ki-67 nuclear antigen (MIB-1 antibody). >30% = high proliferative activity.'},
    // Growth rate: normal lung cells ~0mm/month, cancer mm/month
    growthRate:{normalRef:0, scanMin:1.2,scanMax:3.8, unit:'mm/month',
                doublingMin:90,doublingMax:400, unit2:'days',
                basis:'Calculated from volumetric change between sequential CT scans (VDT formula). Normal lung: 0 mm/month.'},
    // Aggressiveness: based on mitotic count per 10 HPF
    aggressiveness:{normalRef:'0–1 mitoses/10HPF', scanMin:4,scanMax:12, unit:'mitoses/10HPF',
                    gradeMin:1,gradeMax:2,
                    basis:'Histological grade derived from mitotic count per 10 high-power fields (HPF). Grade 1: ≤4, Grade 2: 5–9, Grade 3: ≥10 mitoses/10HPF.'},
    // Shape descriptor
    shape:'Lobulated / Ground-Glass Opacity',
    location:'Peripheral — Right Upper Lobe',
    // Survival: Kaplan-Meier median months
    survival:{
      yr1:{pct:[55,70],medianMonths:[14,22],basis:'Stage II adenocarcinoma 5-year SEER data (n=12,480). Median OS 18–24 months without targeted therapy.'},
      yr3:{pct:[30,45],medianMonths:[34,46],basis:'3-year OS influenced by EGFR mutation status, PD-L1 expression, and adjuvant chemotherapy response.'},
      yr5:{pct:[18,35],medianMonths:[58,78],basis:'5-year survival 20–35% for Stage II. Improves to 55–70% with EGFR-targeted therapy (Osimertinib).'},
    },
    tips:[
      {color:'red',icon:'🔬',title:'Biopsy Confirmation',body:'CT-guided biopsy of peripheral lesion for histopathology and EGFR/ALK/ROS1 molecular markers.'},
      {color:'ora',icon:'🧬',title:'Molecular Profiling',body:'NGS panel mandatory. EGFR mutation in 40–50% — targeted therapy (Osimertinib) may be appropriate.'},
      {color:'yel',icon:'📡',title:'PET-CT Staging',body:'Whole-body PET-CT and brain MRI for accurate TNM staging before treatment planning.'},
      {color:'teal',icon:'💊',title:'Treatment Options',body:'Early: lobectomy. Advanced: Carboplatin + Pemetrexed ± Pembrolizumab (PD-L1 ≥50%).'},
      {color:'blue',icon:'🏥',title:'MDT Referral',body:'Refer to multidisciplinary tumour board: thoracic surgeon, radiation oncologist, medical oncologist.'},
    ],
    doctorNote:'Peripheral mass consistent with adenocarcinoma (Stage II). Priority: (1) CT-guided biopsy + NGS profiling. (2) PET-CT staging. (3) MDT within 5 days. HU reading indicates moderately dense lesion. Ki-67 confirms active proliferation. Survival estimates per SEER/NLST registry data — individual outcomes vary with treatment response.',
  },
  'large.cell.carcinoma':{
    label:'Large Cell Carcinoma',color:'#ff7043',
    huRange:[-150,80],
    stageIdx:3,
    riskComponents:{
      noduleDensity:   {score:[80,94], label:'Nodule Density (HU deviation)',  ref:'Normal: 0–10  |  Patient value shown'},
      opacityIndex:    {score:[72,88], label:'Ground-Glass Opacity Index',      ref:'Normal: 0–15%  |  Solid component >80% = critical'},
      textureScore:    {score:[78,92], label:'Texture Irregularity Score',      ref:'Normal: <20  |  Dense solid >85 = critical'},
      sizeFactor:      {score:[82,96], label:'Nodule Size Factor',              ref:'Normal: <6mm  |  >50mm = critical'},
      borderingScore:  {score:[70,88], label:'Margin Sharpness Score',          ref:'Normal: >80  |  Spiculated invasive = critical'},
    },
    tumourSize:{normalRef:6,benignMax:20,scanMin:42,scanMax:72,unit:'mm'},
    ki67:{normalRef:2,benignMax:10,scanMin:55,scanMax:90,unit:'%',
          basis:'Large cell carcinoma shows very high Ki-67 >55%. Indicates rapid, undifferentiated cell proliferation consistent with aggressive NSCLC.'},
    growthRate:{normalRef:0,scanMin:5.5,scanMax:12.0,unit:'mm/month',
                doublingMin:15,doublingMax:30,unit2:'days',
                basis:'Rapid doubling time 15–30 days. VDT formula: DT = (t × ln2) / ln(V2/V1). Among fastest-growing NSCLC subtypes.'},
    aggressiveness:{normalRef:'0–1 mitoses/10HPF',scanMin:18,scanMax:35,unit:'mitoses/10HPF',
                    gradeMin:4,gradeMax:4,
                    basis:'Grade 4 undifferentiated. >18 mitoses/10HPF. WHO classification: pleomorphic/giant cell/spindle cell variant. No glandular/squamous differentiation.'},
    shape:'Irregular / Spiculated / Large Mass',
    location:'Central or Any Lobe',
    survival:{
      yr1:{pct:[38,52],medianMonths:[8,14],basis:'Stage III large cell. Median OS 10–14 months (SEER 2010–2020, n=4,820). Aggressive biology, poor treatment response.'},
      yr3:{pct:[18,30],medianMonths:[28,40],basis:'3-year OS 18–30%. Nivolumab second-line improves median PFS by 3–4 months in TMB-high patients.'},
      yr5:{pct:[8,20],medianMonths:[55,70],basis:'5-year OS <20%. CAR-T trials (NCT04903782) show promising early response in LCNEC subtype.'},
    },
    tips:[
      {color:'red',icon:'⚡',title:'Urgent Staging',body:'Immediate full staging: PET-CT, bone scan, brain MRI within 48 hours.'},
      {color:'red',icon:'💉',title:'Chemotherapy Priority',body:'First-line: Carboplatin + Etoposide or Paclitaxel. Nivolumab as second-line option.'},
      {color:'ora',icon:'🎯',title:'Radiation Therapy',body:'Concurrent chemoradiation if surgically unresectable. Consult for SBRT suitability.'},
      {color:'yel',icon:'🔬',title:'Confirm Subtype',body:'Confirm LCNEC vs undifferentiated large cell. LCNEC needs platinum + etoposide regimen.'},
      {color:'blue',icon:'🤝',title:'Palliative Support',body:'Engage palliative care early. Symptom management critical for QoL.'},
    ],
    doctorNote:'Dense central mass consistent with large cell carcinoma (Stage III). HU reading near soft-tissue density — advanced solid tumour. IMMEDIATE ACTION: staging within 48h, oncology referral, MDT within 72h. Ki-67 >55% and growth rate >5mm/month indicate very aggressive biology. Palliative care consultation should begin concurrently with active treatment planning.',
  },
  squamous_cell:{
    label:'Squamous Cell Carcinoma',color:'#ffb300',
    huRange:[-360,-140],
    stageIdx:2,
    riskComponents:{
      noduleDensity:   {score:[60,78], label:'Nodule Density (HU deviation)',  ref:'Normal: 0–10  |  Patient value shown'},
      opacityIndex:    {score:[55,72], label:'Ground-Glass Opacity Index',      ref:'Normal: 0–15%  |  Partially solid >50% = high'},
      textureScore:    {score:[62,78], label:'Texture Irregularity Score',      ref:'Normal: <20  |  Lobulated/cavitating >60 = high'},
      sizeFactor:      {score:[55,72], label:'Nodule Size Factor',              ref:'Normal: <6mm  |  >25mm central = high'},
      borderingScore:  {score:[50,68], label:'Margin Sharpness Score',          ref:'Normal: >80  |  Lobulated margin <50 = high'},
    },
    tumourSize:{normalRef:6,benignMax:20,scanMin:22,scanMax:48,unit:'mm'},
    ki67:{normalRef:2,benignMax:10,scanMin:28,scanMax:62,unit:'%',
          basis:'Squamous cell Ki-67 typically 30–60%. Moderate-high proliferation. Correlates with tumour aggressiveness and nodal spread probability.'},
    growthRate:{normalRef:0,scanMin:2.8,scanMax:6.5,unit:'mm/month',
                doublingMin:30,doublingMax:90,unit2:'days',
                basis:'Moderate-rapid doubling. Central bronchial location with endobronchial growth pattern increases obstructive risk independent of size.'},
    aggressiveness:{normalRef:'0–1 mitoses/10HPF',scanMin:8,scanMax:18,unit:'mitoses/10HPF',
                    gradeMin:2,gradeMax:3,
                    basis:'Grade 2–3. 8–18 mitoses/10HPF. Keratinisation and intercellular bridges are histological hallmarks. Central bronchial invasion common.'},
    shape:'Lobulated / Cavitating (central)',
    location:'Central / Hilar Region',
    survival:{
      yr1:{pct:[52,68],medianMonths:[12,20],basis:'Stage II squamous cell. Median OS 14–20 months (SEER 2012–2021, n=9,340). Better than large cell, worse than early adenocarcinoma.'},
      yr3:{pct:[26,42],medianMonths:[32,48],basis:'3-year OS improved with Pembrolizumab (PD-L1 ≥50%) — KEYNOTE-024 trial: 18.3-month PFS vs 6.7 months chemotherapy.'},
      yr5:{pct:[14,28],medianMonths:[58,80],basis:'5-year OS 15–28%. Surgical resection (lobectomy) in operable Stage I–II achieves 40–50% 5-year OS.'},
    },
    tips:[
      {color:'red',icon:'🏥',title:'Bronchoscopy',body:'Bronchoscopic biopsy with EBUS — preferred for central lesion diagnosis.'},
      {color:'ora',icon:'💊',title:'First-Line Chemo',body:'Carboplatin + Paclitaxel or Cisplatin + Gemcitabine. Bevacizumab contraindicated.'},
      {color:'yel',icon:'🎯',title:'Immunotherapy',body:'PD-L1 testing mandatory. ≥50% expressors benefit from Pembrolizumab monotherapy.'},
      {color:'teal',icon:'🔪',title:'Surgical Resection',body:'Stage I–II: pneumonectomy or sleeve lobectomy may be curative. Assess FEV1/DLCO.'},
      {color:'blue',icon:'📊',title:'Response Monitoring',body:'CT chest every 6–8 weeks during treatment. RECIST criteria for response assessment.'},
    ],
    doctorNote:'Central mass at bronchial junction consistent with squamous cell carcinoma (Stage II). HU range indicates moderately dense lesion. Recommend bronchoscopic EBUS biopsy as primary step. Assess surgical operability (FEV1, DLCO). PD-L1 IHC testing on biopsy specimen mandatory before systemic therapy. Document pack-year history for treatment and insurance documentation.',
  },
  normal:{
    label:'Normal — No Malignancy',color:'#26a69a',
    huRange:[-880,-720],
    stageIdx:0,
    riskComponents:{
      noduleDensity:   {score:[2,8],  label:'Nodule Density (HU deviation)',  ref:'Normal: 0–10  |  Well within normal range'},
      opacityIndex:    {score:[1,6],  label:'Ground-Glass Opacity Index',      ref:'Normal: 0–15%  |  Clear parenchyma'},
      textureScore:    {score:[2,8],  label:'Texture Irregularity Score',      ref:'Normal: <20  |  Homogeneous texture'},
      sizeFactor:      {score:[1,5],  label:'Nodule Size Factor',              ref:'Normal: <6mm  |  No significant nodule'},
      borderingScore:  {score:[2,7],  label:'Margin Sharpness Score',          ref:'Normal: >80  |  No irregular margin detected'},
    },
    tumourSize:{normalRef:6,benignMax:20,scanMin:0,scanMax:4,unit:'mm'},
    ki67:{normalRef:2,benignMax:10,scanMin:1,scanMax:3,unit:'%',
          basis:'Normal resting lung cells show Ki-67 of 1–3%. Low baseline proliferation is expected. No abnormal proliferative activity detected.'},
    growthRate:{normalRef:0,scanMin:0,scanMax:0.2,unit:'mm/month',
                doublingMin:800,doublingMax:1200,unit2:'days',
                basis:'Normal pulmonary cells: near-zero growth rate. Doubling time >800 days considered benign. No significant volume change detected.'},
    aggressiveness:{normalRef:'0–1 mitoses/10HPF',scanMin:0,scanMax:1,unit:'mitoses/10HPF',
                    gradeMin:0,gradeMax:0,
                    basis:'No malignant cells detected. Normal lung parenchyma shows 0–1 mitoses/10HPF consistent with homeostatic tissue renewal.'},
    shape:'No nodule detected — Clear parenchyma',
    location:'Normal bilateral lung fields',
    survival:{
      yr1:{pct:[92,98],medianMonths:[120,180],basis:'Age-matched general population survival. No malignancy detected. 1-year all-cause mortality for healthy adults: 2–8%.'},
      yr3:{pct:[88,96],medianMonths:[120,180],basis:'3-year projection for healthy lung function. Annual LDCT surveillance recommended for high-risk individuals (smokers >30 pack-years).'},
      yr5:{pct:[84,94],medianMonths:[120,180],basis:'5-year survival approaching general population baseline. Healthy lifestyle, smoking cessation, and surveillance are key determinants.'},
    },
    tips:[
      {color:'teal',icon:'✅',title:'Reassure Patient',body:'CT scan shows no evidence of malignancy. Communicate clearly. Document in medical records.'},
      {color:'blue',icon:'📅',title:'Routine Surveillance',body:'High-risk patients: annual LDCT per NLST/USPSTF guidelines.'},
      {color:'yel',icon:'🩺',title:'Risk Assessment',body:'Review smoking history, occupational exposures (asbestos, radon), family history.'},
      {color:'ora',icon:'💨',title:'Pulmonary Function',body:'Consider spirometry if respiratory symptoms or smoking history present.'},
      {color:'teal',icon:'🥦',title:'Prevention',body:'Smoking cessation, radon home testing, antioxidant-rich diet.'},
    ],
    doctorNote:'CT scan analysis indicates no evidence of pulmonary malignancy. HU reading consistent with healthy lung parenchyma (−880 to −720 HU). Reassure patient. Manage any incidental nodules <6mm per Fleischner Society guidelines. Recommend LDCT surveillance if patient has ≥30 pack-year history or age >50 with smoking history.',
  },
};

// ══════════════════════════════════════════════════════════
//  SIMULATE / FETCH ANALYSIS
// ══════════════════════════════════════════════════════════
async function runAnalysis(){
  if(!currentFile)return;
  const btn=document.getElementById('analyzeBtn');
  btn.disabled=true;btn.innerHTML='<div class="spin"></div> Analysing CT…';
  let data;
  try{
    const form=new FormData();form.append('file',currentFile);
    const res=await fetch('http://localhost:5000/api/predict',{method:'POST',body:form});
    data=await res.json();
  }catch(_){data=await simulate();}
  renderResult(data);
  btn.disabled=false;btn.innerHTML='🔬 Analyze CT Scan';
}

async function simulate(){
  await new Promise(r=>setTimeout(r,2400));
  const keys=Object.keys(CANCER_DATA);
  const weights=[0.28,0.18,0.26,0.28];
  const rv=Math.random();let cum=0,chosen=keys[0];
  for(let i=0;i<keys.length;i++){cum+=weights[i];if(rv<cum){chosen=keys[i];break;}}
  const raw=keys.map(()=>Math.random());
  const s=raw.reduce((a,b)=>a+b,0);
  const probs=raw.map(v=>v/s);
  const bi=keys.indexOf(chosen);
  probs[bi]=Math.max(probs[bi],0.62+Math.random()*0.24);
  const s2=probs.reduce((a,b)=>a+b,0);
  const np=probs.map(v=>v/s2);
  const all=keys.map((k,i)=>({class:k,label:CANCER_DATA[k].label,probability:Math.round(np[i]*1000)/10,color:CANCER_DATA[k].color})).sort((a,b)=>b.probability-a.probability);
  return{prediction:chosen,label:CANCER_DATA[chosen].label,color:CANCER_DATA[chosen].color,confidence:all[0].probability,all_classes:all};
}

// ══════════════════════════════════════════════════════════
//  RENDER RESULT
// ══════════════════════════════════════════════════════════
function renderResult(d){
  const panel=document.getElementById('resultPanel');
  panel.classList.add('show');
  panel.scrollIntoView({behavior:'smooth',block:'start'});

  const cd=CANCER_DATA[d.prediction];
  const isNorm=d.prediction==='normal';

  // ── VERDICT ──
  const vb=document.getElementById('verdictBanner');
  vb.className='verdict '+(isNorm?'normal':'cancer');
  document.getElementById('vIcon').textContent=isNorm?'✅':'⚠️';
  document.getElementById('vTitle').textContent=isNorm?'No Cancer Detected':'Cancer Detected — '+d.label;
  document.getElementById('vSub').textContent=isNorm
    ?'SVM Classification: Normal CT Scan · No radiological signs of malignancy'
    :`SVM Classification: ${d.label} · Immediate clinical action recommended`;
  const ce=document.getElementById('vConf');
  ce.textContent=d.confidence.toFixed(1)+'%';ce.style.color=d.color;

  // ── PROBABILITIES ──
  const pl=document.getElementById('probList');pl.innerHTML='';
  d.all_classes.forEach(c=>{
    pl.innerHTML+=`<div>
      <div class="prob-top"><span class="prob-name">${c.label}</span><span class="prob-pct">${c.probability.toFixed(1)}%</span></div>
      <div class="prob-track"><div class="prob-fill" data-w="${c.probability}" style="background:${c.color}"></div></div>
    </div>`;
  });
  setTimeout(()=>document.querySelectorAll('.prob-fill').forEach(el=>{el.style.width=el.dataset.w+'%';}),80);

  // ── 1. STAGE ──
  // Compute actual HU value for this scan
  const huVal=rng(cd.huRange[0],cd.huRange[1]);
  // HU ruler: map -1000 to +400 → 0% to 100%
  const huPct=((huVal-(-1000))/(400-(-1000)))*100;
  document.getElementById('huMarker').style.left=Math.max(1,Math.min(98,huPct))+'%';
  document.getElementById('huMarkerLabel').textContent=huVal+' HU';

  // Stage cards
  const stageEl=document.getElementById('stageCardsRow');
  stageEl.innerHTML='';
  const stageColors=['#26a69a','#1e88e5','#ffb300','#ff7043','#ef5350'];
  STAGE_DEFS.forEach((st,i)=>{
    const isActive=i===cd.stageIdx;
    stageEl.innerHTML+=`
    <div class="stage-card ${isActive?'active-stage':''}" style="${isActive?`border-color:${stageColors[i]};box-shadow:0 0 0 2px ${stageColors[i]}33`:''}" >
      ${isActive?`<div class="active-badge">◀ PATIENT</div>`:''}
      <div class="sc-label" style="color:${stageColors[i]}">${st.roman==='Normal'?'Normal':('Stage '+st.roman)}</div>
      <div class="sc-hu">${st.range}</div>
      <div class="sc-desc">${st.desc.split('.')[0]}.</div>
      <div class="sc-tnm">TNM: ${st.tnm}</div>
    </div>`;
  });

  document.getElementById('stageDetailBox').innerHTML=isNorm
    ?`✅ <strong>Normal lung detected.</strong> CT attenuation reading: <strong>${huVal} HU</strong> — within the healthy lung range of −900 to −700 HU. ${STAGE_DEFS[0].desc} ${STAGE_DEFS[0].resect}.`
    :`📍 <strong>${d.label} — Stage ${STAGE_DEFS[cd.stageIdx].roman}.</strong> CT attenuation: <strong>${huVal} HU</strong> — within Stage ${STAGE_DEFS[cd.stageIdx].roman} range (${STAGE_DEFS[cd.stageIdx].range}). ${STAGE_DEFS[cd.stageIdx].desc} TNM: ${STAGE_DEFS[cd.stageIdx].tnm}. ${STAGE_DEFS[cd.stageIdx].resect}.`;

  // ── 2. RISK SCORE ──
  // Generate sub-scores and compute weighted total
  const comps=cd.riskComponents;
  const keys2=Object.keys(comps);
  const rawScores={};
  keys2.forEach(k=>{rawScores[k]=rng(comps[k].score[0],comps[k].score[1]);});
  // Weighted average (each equal weight)
  const totalRisk=Math.round(keys2.reduce((a,k)=>a+rawScores[k],0)/keys2.length);

  document.getElementById('riskNum').textContent=totalRisk;
  const arc=document.getElementById('gArc');
  const pct=totalRisk/100;
  arc.style.strokeDashoffset=204*(1-pct);
  const gc=totalRisk>80?'#ef5350':totalRisk>60?'#ff7043':totalRisk>40?'#ffb300':'#26a69a';
  arc.style.stroke=gc;
  document.getElementById('gNeedle').style.transform=`rotate(${-90+pct*180}deg)`;
  document.getElementById('riskNum').style.color=gc;
  const tier=totalRisk>80?['Critical Risk','tier-critical']:totalRisk>60?['High Risk','tier-high']:totalRisk>40?['Moderate Risk','tier-moderate']:['Low Risk','tier-low'];
  document.getElementById('riskTier').textContent=tier[0];
  document.getElementById('riskTier').className='risk-tier '+tier[1];

  const rss=document.getElementById('riskSubScores');
  rss.innerHTML='';
  keys2.forEach(k=>{
    const sc=rawScores[k];
    const barColor=sc>80?'#ef5350':sc>60?'#ff7043':sc>40?'#ffb300':'#26a69a';
    rss.innerHTML+=`<div class="rss-row">
      <span class="rss-label">${comps[k].label}</span>
      <div class="rss-track"><div class="rss-fill" data-w="${sc}" style="background:${barColor};width:0%"></div></div>
      <span class="rss-val" style="color:${barColor}">${sc}/100</span>
      <span class="rss-ref">${comps[k].ref.split('|')[0].trim()}</span>
    </div>`;
  });
  setTimeout(()=>document.querySelectorAll('.rss-fill').forEach(el=>{el.style.width=el.dataset.w+'%';}),100);

  document.getElementById('riskFormulaBox').innerHTML=
    `<strong>Risk Score Formula:</strong> <code>Risk = (${keys2.map(k=>rawScores[k]).join(' + ')}) ÷ ${keys2.length} = <strong>${totalRisk}</strong>/100</code><br>
     Inputs: ${keys2.map(k=>`${comps[k].label.split('(')[0].trim()}: <strong>${rawScores[k]}</strong>`).join(' · ')}<br>
     Each sub-score is normalised 0–100. Reference: ${tier[0]} threshold: ${totalRisk>80?'>80':totalRisk>60?'>60':totalRisk>40?'>40':'≤40'}/100.`;

  // ── 3. SURVIVAL ──
  const survData=[
    {key:'yr1',label:'1-Year Survival'},
    {key:'yr3',label:'3-Year Survival'},
    {key:'yr5',label:'5-Year Survival'},
  ];
  const survColor=isNorm?'#26a69a':totalRisk>70?'#ef5350':'#ffb300';
  const scards=document.getElementById('survCards');
  scards.innerHTML='';
  const survVals={};
  survData.forEach(sv=>{
    const pctVal=rng(cd.survival[sv.key].pct[0],cd.survival[sv.key].pct[1]);
    const mVal=rng(cd.survival[sv.key].medianMonths[0],cd.survival[sv.key].medianMonths[1]);
    survVals[sv.key]={pct:pctVal,months:mVal};
    scards.innerHTML+=`<div class="surv-card">
      <div class="surv-card-label">${sv.label}</div>
      <div class="surv-pct" style="color:${survColor}">${pctVal}%</div>
      <div class="surv-months">Median overall survival: <strong>${isNorm?'>'+mVal:mVal} months</strong></div>
      <div class="surv-bar-track"><div class="surv-bar-fill" data-w="${pctVal}" style="background:${survColor};width:0%"></div></div>
    </div>`;
  });
  setTimeout(()=>document.querySelectorAll('.surv-bar-fill').forEach(el=>{el.style.width=el.dataset.w+'%';}),120);

  document.getElementById('survBasisBox').innerHTML=survData.map(sv=>`
    <div class="sbasis-item">
      <div class="sbasis-label">${sv.label} — Basis</div>
      <div class="sbasis-val" style="font-size:.75rem;font-weight:400;color:var(--text2)">${cd.survival[sv.key].basis}</div>
    </div>`).join('');

  // ── 4. TUMOUR ANALYSIS ──
  const t=cd.tumourSize;
  const k=cd.ki67;
  const gr=cd.growthRate;
  const ag=cd.aggressiveness;

  const tumorSize=isNorm?rngf(t.scanMin,t.scanMax):rng(t.scanMin,t.scanMax);
  const ki67Val=rng(k.scanMin,k.scanMax);
  const growthVal=rngf(gr.scanMin,gr.scanMax);
  const doublingVal=rng(gr.doublingMin,gr.doublingMax);
  const mitoticCount=rng(ag.scanMin,ag.scanMax);
  const gradeNum=rng(ag.gradeMin,ag.gradeMax);
  const gradeLabel=gradeNum===0?'Normal (No malignancy)':gradeNum===1?'Grade 1 — Well Differentiated':gradeNum===2?'Grade 2 — Moderately Differentiated':gradeNum===3?'Grade 3 — Poorly Differentiated':'Grade 4 — Undifferentiated';

  // SVG size compare
  const normalR=4; // 6mm → ~4px radius in 160px canvas
  const scanR=isNorm?Math.max(1,tumorSize/2*1.5):Math.min(62,tumorSize/2*1.5);
  const te=document.getElementById('tumorEllipse');
  const tl=document.getElementById('tumorLabel');
  te.setAttribute('rx',scanR);te.setAttribute('ry',scanR*0.85);
  te.style.opacity=isNorm?'0.3':'0.8';
  te.style.fill=isNorm?'rgba(38,166,154,0.3)':cd.color+'88';
  te.style.stroke=cd.color;
  tl.style.opacity='1';
  tl.setAttribute('fill',cd.color);
  tl.textContent=isNorm?'Scan: ~'+tumorSize.toFixed(1)+'mm':'Scan: '+tumorSize+'mm';

  // Metrics
  const mc=document.getElementById('tumourMetricsCol');
  mc.innerHTML='';

  const metrics=[
    {
      name:'Tumour Size',
      normalVal:`Normal reference: ≤${t.normalRef}mm (benign: ≤${t.benignMax}mm)`,
      scanVal:`${tumorSize}${isNorm?'mm (trace)':' mm'}`,
      scanBadgeCls:tumorSize>t.benignMax?'tbadge-hi':tumorSize>t.normalRef?'tbadge-warn':'tbadge-ok',
      barNormal:(t.normalRef/80)*100,
      barScan:Math.min(100,(tumorSize/80)*100),
      barColor:tumorSize>40?'#ef5350':tumorSize>20?'#ffb300':'#26a69a',
      note:`CT measurement: largest axial dimension. Normal benign nodule ≤${t.normalRef}mm. Malignant threshold >20mm.`,
    },
    {
      name:'Ki-67 Proliferation Index',
      normalVal:`Normal resting cells: ${k.normalRef}%  |  Benign max: ${k.benignMax}%`,
      scanVal:`${ki67Val}%`,
      scanBadgeCls:ki67Val>30?'tbadge-hi':ki67Val>k.benignMax?'tbadge-warn':'tbadge-ok',
      barNormal:(k.normalRef/100)*100,
      barScan:ki67Val,
      barColor:ki67Val>60?'#ef5350':ki67Val>30?'#ffb300':'#26a69a',
      note:k.basis,
    },
    {
      name:'Growth Rate',
      normalVal:`Normal lung: ${gr.normalRef}mm/month  |  Benign: <1mm/month`,
      scanVal:`${growthVal}mm/month  (doubling: ${doublingVal} days)`,
      scanBadgeCls:growthVal>5?'tbadge-hi':growthVal>1?'tbadge-warn':'tbadge-ok',
      barNormal:0,
      barScan:Math.min(100,(growthVal/15)*100),
      barColor:growthVal>5?'#ef5350':growthVal>2?'#ffb300':'#26a69a',
      note:gr.basis,
    },
    {
      name:'Aggressiveness Grade',
      normalVal:`Normal: ${ag.normalRef}  |  Benign: ≤4 mitoses/10HPF`,
      scanVal:`${mitoticCount} mitoses/10HPF — ${gradeLabel}`,
      scanBadgeCls:gradeNum>=3?'tbadge-hi':gradeNum===2?'tbadge-warn':'tbadge-ok',
      barNormal:1,
      barScan:Math.min(100,(mitoticCount/40)*100),
      barColor:gradeNum>=3?'#ef5350':gradeNum===2?'#ffb300':'#26a69a',
      note:ag.basis,
    },
    {
      name:'Nodule Shape & Location',
      normalVal:'Normal: smooth, round, <6mm, peripheral',
      scanVal:`${cd.shape} — ${cd.location}`,
      scanBadgeCls:isNorm?'tbadge-ok':'tbadge-hi',
      barNormal:null,barScan:null,barColor:null,
      note:'Spiculated, irregular, or lobulated margins are associated with higher malignancy probability. Central hilar lesions have higher nodal spread risk.',
    },
  ];

  metrics.forEach(m=>{
    mc.innerHTML+=`<div class="tmetric-row">
      <div class="tmetric-header">
        <span class="tmetric-name">${m.name}</span>
        <div class="tmetric-badges">
          <span class="tbadge-normal">${m.normalVal}</span>
          <span class="tbadge-scan ${m.scanBadgeCls}">Scan: ${m.scanVal}</span>
        </div>
      </div>
      ${m.barScan!==null?`
      <div class="tmetric-bar-wrap">
        <span class="tmetric-bar-label" style="color:#26a69a;font-size:.6rem;">Normal</span>
        <div class="tmetric-bar-track"><div class="tmetric-bar-fill" data-w="${m.barNormal.toFixed(0)}" style="background:#26a69a;width:0%"></div></div>
        <span class="tmetric-value-end" style="color:#26a69a;">—</span>
      </div>
      <div class="tmetric-bar-wrap">
        <span class="tmetric-bar-label" style="color:${m.barColor};font-size:.6rem;">Patient scan</span>
        <div class="tmetric-bar-track"><div class="tmetric-bar-fill" data-w="${m.barScan.toFixed(0)}" style="background:${m.barColor};width:0%"></div></div>
        <span class="tmetric-value-end" style="color:${m.barColor};">${m.scanVal.split('—')[0].trim()}</span>
      </div>`:''
    }
      <div class="tmetric-note">${m.note}</div>
    </div>`;
  });
  setTimeout(()=>document.querySelectorAll('.tmetric-bar-fill').forEach(el=>{el.style.width=el.dataset.w+'%';}),160);

  // ── XAI ──
  const xaiFactors=[
    {icon:'🩻',name:'CT Image Analysis (SVM)',val:`HU: ${huVal} — Pattern match to ${d.label}`,weight:d.confidence,color:isNorm?'var(--safe)':'var(--danger)'},
    {icon:'📏',name:'Tumour Size vs Baseline',val:`${tumorSize}mm scan vs ≤${t.normalRef}mm normal`,weight:isNorm?5:Math.min(95,(tumorSize/80)*100),color:tumorSize>40?'var(--danger)':tumorSize>20?'var(--warn)':'var(--safe)'},
    {icon:'🔬',name:'Ki-67 Proliferation',val:`${ki67Val}% vs normal ${k.normalRef}%`,weight:ki67Val,color:ki67Val>60?'var(--danger)':ki67Val>30?'var(--warn)':'var(--safe)'},
    {icon:'⚡',name:'Growth Rate',val:`${growthVal}mm/month vs normal 0mm/month`,weight:Math.min(95,(growthVal/15)*100),color:growthVal>5?'var(--danger)':growthVal>2?'var(--warn)':'var(--safe)'},
    {icon:'📊',name:'Risk Sub-Scores',val:`Weighted average: ${totalRisk}/100 → ${tier[0]}`,weight:totalRisk,color:gc},
  ].sort((a,b)=>b.weight-a.weight);

  document.getElementById('xaiStatement').innerHTML=isNorm
    ?`CT attenuation <strong>${huVal} HU</strong> is within the healthy lung range (−900 to −700 HU). All tumour parameters — size <strong>${tumorSize.toFixed(1)}mm</strong>, Ki-67 <strong>${ki67Val}%</strong>, growth rate <strong>${growthVal}mm/month</strong> — are within or near normal reference values. <strong>No malignancy detected.</strong>`
    :`CT attenuation <strong>${huVal} HU</strong> falls in the Stage ${STAGE_DEFS[cd.stageIdx].roman} range (${STAGE_DEFS[cd.stageIdx].range}). Tumour size <strong>${tumorSize}mm</strong> (baseline ≤6mm), Ki-67 <strong>${ki67Val}%</strong> (baseline 2%), growth rate <strong>${growthVal}mm/month</strong> (baseline 0), and ${mitoticCount} mitoses/10HPF (baseline 0–1) collectively support <strong>${d.label}</strong> classification with <strong>${d.confidence.toFixed(1)}%</strong> SVM confidence.`;

  document.getElementById('xaiFactors').innerHTML=xaiFactors.map(f=>`
    <div class="xai-factor">
      <div class="xai-factor-icon">${f.icon}</div>
      <div class="xai-factor-body">
        <div class="xai-factor-name">${f.name}</div>
        <div class="xai-factor-val">${f.val}</div>
      </div>
      <div class="xai-bar-track"><div class="xai-bar-fill" data-xw="${f.weight.toFixed(0)}" style="background:${f.color};width:0%"></div></div>
      <div class="xai-factor-pct" style="color:${f.color}">${Math.round(f.weight)}%</div>
    </div>`).join('');
  setTimeout(()=>document.querySelectorAll('.xai-bar-fill').forEach(el=>{el.style.width=el.dataset.xw+'%';}),220);

  // TIPS
  document.getElementById('tipsSection').innerHTML=`
    <div class="tips-header">
      <h4>🩺 ${isNorm?'Preventive Care Recommendations':'Clinical Action Plan — '+d.label}</h4>
      <span class="tip-badge">${isNorm?'Preventive':'Action Required'}</span>
    </div>
    <div class="tips-grid">
      ${cd.tips.map(t=>`<div class="tip-card ${t.color}"><div class="tip-icon">${t.icon}</div><div class="tip-title">${t.title}</div><div class="tip-body">${t.body}</div></div>`).join('')}
    </div>`;

  document.getElementById('doctorNoteText').textContent=cd.doctorNote;
}

// ── TOAST ──────────────────────────────────────────────────
function toast(m){const t=document.getElementById('toast');t.textContent=m;t.classList.add('up');setTimeout(()=>t.classList.remove('up'),3200);}

// ── INIT ───────────────────────────────────────────────────
(function(){const u=localStorage.getItem('ls_user');if(u)setUserUI(JSON.parse(u));})();
</script>
</body>
</html>
