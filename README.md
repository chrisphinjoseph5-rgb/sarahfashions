<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width,initial-scale=1.0"/>
<meta name="description" content="Sarah Fashions — Premium Women, Men & Children clothing in Nkubu, Meru County. Shop online, pay via M-Pesa. Countrywide delivery. Call 0701 227 713."/>
<meta name="keywords" content="Sarah Fashions, Nkubu fashion, Meru clothes, women clothing Kenya, men clothing, children wear, M-Pesa shop"/>
<meta property="og:title" content="Sarah Fashions – Premium Style · Nkubu, Meru"/>
<meta property="og:description" content="Premium clothing for Women, Men & Children. M-Pesa accepted. Countrywide delivery. Call 0701 227 713."/>
<meta name="theme-color" content="#C9963A"/>
<title>Sarah Fashions – Luxury Style · Nkubu, Meru</title>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,600;0,700;1,400;1,600&family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet"/>
<style>
:root{
  --ink:#08070A; --deep:#13101A; --card:#1C1825; --lift:#252130;
  --smoke:#3D3848; --ash:#8A8595; --silver:#C5C2D0; --pearl:#F2EFF8; --white:#FDFCFF;
  --gold:#C9963A; --gold2:#D9AB55; --gold3:#EAC878; --goldp:#F8EDD8; --goldf:#FBF6EC;
  --rose:#C4705A; --rose2:#E8A090; --green:#2D7A55; --blue:#2A5C8A;
  --bd1:rgba(201,150,58,.12); --bd2:rgba(201,150,58,.22); --bd3:rgba(201,150,58,.38);
  --g1:rgba(255,255,255,.04); --g2:rgba(255,255,255,.07); --g3:rgba(255,255,255,.11);
  --sh1:0 2px 12px rgba(0,0,0,.1); --sh2:0 8px 32px rgba(0,0,0,.16);
  --sh3:0 20px 60px rgba(0,0,0,.22); --sh4:0 40px 100px rgba(0,0,0,.3);
  --shg:0 8px 32px rgba(201,150,58,.28);
  --ease:.28s cubic-bezier(.25,.8,.25,1);
}
*{margin:0;padding:0;box-sizing:border-box;}
html{scroll-behavior:smooth;}
body{font-family:'Inter',sans-serif;background:var(--ink);color:var(--pearl);overflow-x:hidden;-webkit-font-smoothing:antialiased;}
img{display:block;max-width:100%;object-fit:cover;}
.hidden{display:none!important;}
::-webkit-scrollbar{width:5px;}
::-webkit-scrollbar-track{background:var(--deep);}
::-webkit-scrollbar-thumb{background:var(--gold);border-radius:3px;}

/* ── TICKER ── */
.ticker{height:38px;overflow:hidden;display:flex;align-items:center;
  background:linear-gradient(90deg,#7A4A10,var(--gold),#D4A050,var(--gold),#7A4A10);
  background-size:400% auto;animation:gflow 5s linear infinite;}
@keyframes gflow{to{background-position:400% center;}}
.ticker-inner{display:flex;animation:tick 28s linear infinite;width:max-content;}
@keyframes tick{to{transform:translateX(-50%);}}
.t-item{display:inline-flex;align-items:center;gap:10px;padding:0 32px;
  font-size:10.5px;font-weight:700;letter-spacing:2px;text-transform:uppercase;color:var(--ink);}
.t-dot{width:4px;height:4px;border-radius:50%;background:rgba(8,7,10,.4);flex-shrink:0;}

/* ── NAV ── */
.nav{position:sticky;top:0;z-index:600;background:rgba(8,7,10,.94);
  backdrop-filter:blur(20px);border-bottom:1px solid var(--bd1);}
.nav-inner{max-width:1380px;margin:0 auto;display:flex;align-items:center;
  justify-content:space-between;padding:0 40px;height:74px;}
.brand{display:flex;align-items:center;gap:14px;text-decoration:none;}
.brand-logo{width:42px;height:42px;}
.brand-text{display:flex;flex-direction:column;gap:2px;}
.brand-name{font-family:'Cormorant Garamond',serif;font-size:24px;font-weight:600;
  color:var(--gold3);letter-spacing:1.5px;line-height:1;}
.brand-loc{font-size:8px;letter-spacing:3.5px;text-transform:uppercase;color:var(--gold);opacity:.55;font-weight:500;}
.nav-links{display:flex;gap:36px;list-style:none;}
.nav-links a{font-size:11px;font-weight:600;letter-spacing:1.8px;text-transform:uppercase;
  color:var(--ash);transition:color var(--ease);position:relative;padding-bottom:3px;}
.nav-links a::after{content:'';position:absolute;left:0;bottom:0;width:0;height:1px;
  background:var(--gold);transition:width var(--ease);}
.nav-links a:hover{color:var(--gold);}
.nav-links a:hover::after{width:100%;}
.nav-actions{display:flex;align-items:center;gap:10px;}
.btn-seller{background:transparent;border:1px solid rgba(201,150,58,.18);
  color:rgba(201,150,58,.45);border-radius:99px;padding:7px 17px;
  font-size:10px;font-weight:700;letter-spacing:1.5px;text-transform:uppercase;
  cursor:pointer;transition:all var(--ease);font-family:'Inter',sans-serif;}
.btn-seller:hover{border-color:var(--gold);color:var(--gold);}
.btn-cart{background:linear-gradient(135deg,var(--gold),var(--gold2));
  color:var(--ink);border:none;border-radius:99px;padding:10px 22px;
  font-size:11px;font-weight:700;letter-spacing:.8px;cursor:pointer;
  display:flex;align-items:center;gap:8px;transition:all var(--ease);
  box-shadow:0 4px 18px rgba(201,150,58,.3);font-family:'Inter',sans-serif;}
.btn-cart:hover{transform:translateY(-1px);box-shadow:var(--shg);}
.cart-n{background:var(--rose);color:#fff;border-radius:50%;width:17px;height:17px;
  font-size:9px;font-weight:800;display:flex;align-items:center;justify-content:center;}

/* ── HERO ── */
.hero{min-height:96vh;display:grid;grid-template-columns:52% 48%;position:relative;overflow:hidden;}
.hero-left{background:linear-gradient(145deg,#100D18 0%,#0A0810 45%,#140F20 100%);
  display:flex;flex-direction:column;justify-content:center;
  padding:90px 60px 90px 80px;position:relative;overflow:hidden;}

/* SVG background pattern */
.hero-bg-pattern{position:absolute;inset:0;opacity:.035;pointer-events:none;}

.hero-tag{display:inline-flex;align-items:center;gap:10px;
  background:rgba(201,150,58,.07);border:1px solid var(--bd2);
  border-radius:99px;padding:7px 18px;width:fit-content;margin-bottom:28px;}
.hero-tag-dot{width:6px;height:6px;border-radius:50%;background:var(--gold);
  animation:blink 1.8s ease-in-out infinite;}
@keyframes blink{0%,100%{opacity:1;}50%{opacity:.25;}}
.hero-tag-txt{font-size:9.5px;letter-spacing:3px;text-transform:uppercase;color:var(--gold3);font-weight:600;}

.hero-h1{font-family:'Cormorant Garamond',serif;font-size:clamp(50px,5.5vw,82px);
  font-weight:300;color:var(--white);line-height:1.04;margin-bottom:10px;letter-spacing:-.5px;}
.hero-h1 .g{font-style:italic;font-weight:600;
  background:linear-gradient(135deg,var(--gold3) 0%,var(--gold2) 50%,var(--gold) 100%);
  -webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;}
.hero-h1 .s{display:block;font-size:.62em;font-weight:300;color:var(--silver);margin-top:4px;}
.hero-p{font-size:15.5px;color:var(--ash);line-height:1.85;max-width:440px;
  margin-bottom:44px;font-weight:300;}

.hero-btns{display:flex;gap:12px;flex-wrap:wrap;margin-bottom:64px;}
.btn-primary{background:linear-gradient(135deg,var(--gold),var(--gold2));color:var(--ink);
  border:none;border-radius:5px;padding:15px 34px;font-size:11.5px;font-weight:700;
  letter-spacing:1.8px;text-transform:uppercase;cursor:pointer;
  transition:all var(--ease);box-shadow:var(--shg);font-family:'Inter',sans-serif;
  display:inline-flex;align-items:center;gap:9px;}
.btn-primary:hover{transform:translateY(-2px);box-shadow:0 12px 36px rgba(201,150,58,.42);}
.btn-ghost{background:transparent;border:1px solid rgba(255,255,255,.1);color:var(--silver);
  border-radius:5px;padding:15px 34px;font-size:11.5px;font-weight:600;letter-spacing:1.8px;
  text-transform:uppercase;cursor:pointer;transition:all var(--ease);
  font-family:'Inter',sans-serif;display:inline-flex;align-items:center;gap:9px;}
.btn-ghost:hover{border-color:var(--gold);color:var(--gold);}

.hero-kpis{display:flex;gap:0;border-top:1px solid var(--g2);padding-top:40px;}
.kpi{flex:1;padding:0 28px;border-right:1px solid var(--g2);}
.kpi:first-child{padding-left:0;}
.kpi:last-child{border:none;}
.kpi-v{font-family:'Cormorant Garamond',serif;font-size:42px;font-weight:600;
  background:linear-gradient(135deg,var(--gold3),var(--gold));
  -webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;
  line-height:1;margin-bottom:4px;}
.kpi-l{font-size:8.5px;letter-spacing:2.5px;text-transform:uppercase;color:var(--smoke);font-weight:500;}

/* Hero Right */
.hero-right{position:relative;overflow:hidden;display:flex;align-items:center;justify-content:center;
  background:linear-gradient(160deg,#1A1228 0%,#110C1C 50%,#0C0815 100%);}
.hero-right::before{content:'';position:absolute;inset:0;
  background:radial-gradient(ellipse at 35% 25%,rgba(201,150,58,.1) 0%,transparent 55%),
             radial-gradient(ellipse at 70% 75%,rgba(196,112,90,.06) 0%,transparent 50%);}
.hero-showcase{position:relative;z-index:1;padding:56px 36px;width:100%;display:flex;
  flex-direction:column;align-items:center;gap:18px;}

/* Fashion illustration card */
.fashion-card{
  background:rgba(255,255,255,.045);
  border:1px solid rgba(201,150,58,.18);
  border-radius:22px;padding:36px 28px;text-align:center;
  width:100%;max-width:320px;backdrop-filter:blur(10px);
  animation:float 6s ease-in-out infinite;position:relative;overflow:hidden;}
.fashion-card::before{content:'';position:absolute;top:0;left:15%;right:15%;height:1px;
  background:linear-gradient(90deg,transparent,var(--gold),transparent);}
@keyframes float{0%,100%{transform:translateY(0);}50%{transform:translateY(-12px);}}
.fc-lbl{font-size:8.5px;letter-spacing:4px;text-transform:uppercase;color:var(--gold);
  font-weight:700;margin-bottom:18px;}
.fc-svg{width:150px;height:150px;margin:0 auto 18px;border-radius:50%;
  background:linear-gradient(135deg,rgba(201,150,58,.12),rgba(201,150,58,.04));
  border:1px solid var(--bd1);display:flex;align-items:center;justify-content:center;
  overflow:hidden;}
.fc-svg img{width:100%;height:100%;object-fit:cover;border-radius:50%;}
.fc-title{font-family:'Cormorant Garamond',serif;font-size:22px;font-weight:600;
  color:var(--pearl);margin-bottom:4px;}
.fc-sub{font-size:11.5px;color:var(--ash);font-weight:300;}

.hero-chips{display:flex;gap:8px;flex-wrap:wrap;justify-content:center;max-width:320px;}
.chip{display:flex;align-items:center;gap:7px;background:var(--g2);
  border:1px solid var(--bd1);border-radius:10px;padding:9px 14px;
  font-size:11px;color:var(--silver);font-weight:500;backdrop-filter:blur(6px);}
.chip svg{flex-shrink:0;}

/* ── MARQUEE ── */
.marquee{background:var(--card);border-top:1px solid var(--bd1);
  border-bottom:1px solid var(--bd1);height:46px;overflow:hidden;
  display:flex;align-items:center;}
.marquee-inner{display:flex;animation:mq 26s linear infinite;width:max-content;}
@keyframes mq{to{transform:translateX(-50%);}}
.m-item{display:inline-flex;align-items:center;gap:14px;padding:0 38px;
  font-size:9.5px;font-weight:600;letter-spacing:3px;text-transform:uppercase;
  color:var(--smoke);white-space:nowrap;transition:color var(--ease);}
.m-item:hover{color:var(--gold);}
.m-sep{width:3px;height:3px;border-radius:50%;background:var(--gold);opacity:.4;flex-shrink:0;}

/* ── SECTION BASE ── */
.sec{padding:96px 40px;}
.sec-inner{max-width:1380px;margin:0 auto;}
.sec-hd{text-align:center;margin-bottom:68px;}
.s-eye{display:inline-flex;align-items:center;gap:14px;font-size:9px;letter-spacing:5px;
  text-transform:uppercase;color:var(--gold);font-weight:700;margin-bottom:14px;}
.s-eye::before,.s-eye::after{content:'';flex:0 0 44px;height:1px;
  background:linear-gradient(90deg,transparent,var(--gold));opacity:.5;}
.s-eye::after{background:linear-gradient(270deg,transparent,var(--gold));}
.s-title{font-family:'Cormorant Garamond',serif;font-size:clamp(34px,4vw,56px);
  font-weight:300;color:var(--pearl);line-height:1.1;margin-bottom:18px;}
.s-title em{font-style:italic;font-weight:600;
  background:linear-gradient(135deg,var(--gold3),var(--gold));
  -webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;}
.s-sub{font-size:15px;color:var(--ash);max-width:500px;margin:0 auto;line-height:1.8;font-weight:300;}

/* ── CATEGORIES ── */
.cats-sec{background:var(--deep);}
.cat-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(155px,1fr));gap:13px;}
.cat-card{position:relative;border-radius:16px;overflow:hidden;cursor:pointer;
  border:1.5px solid var(--bd1);background:var(--g1);
  transition:all var(--ease);padding:28px 18px;text-align:center;}
.cat-card::before{content:'';position:absolute;inset:0;
  background:radial-gradient(circle at 50% 60%,rgba(201,150,58,.09) 0%,transparent 65%);
  opacity:0;transition:opacity var(--ease);}
.cat-card:hover,.cat-card.on{border-color:var(--gold);transform:translateY(-4px);
  box-shadow:0 0 0 1px var(--gold),var(--shg);}
.cat-card:hover::before,.cat-card.on::before{opacity:1;}
.cat-card.on::after{content:'';position:absolute;top:0;left:20%;right:20%;height:2px;
  background:linear-gradient(90deg,transparent,var(--gold),transparent);}

/* Category SVG graphic area */
.cat-graphic{width:70px;height:70px;margin:0 auto 14px;border-radius:14px;
  display:flex;align-items:center;justify-content:center;
  background:linear-gradient(135deg,rgba(201,150,58,.1),rgba(201,150,58,.04));
  border:1px solid var(--bd1);transition:all var(--ease);font-size:30px;}
.cat-card:hover .cat-graphic,.cat-card.on .cat-graphic{
  background:linear-gradient(135deg,rgba(201,150,58,.2),rgba(201,150,58,.08));
  border-color:var(--bd2);transform:scale(1.08);}
.cat-name{font-family:'Cormorant Garamond',serif;font-size:17px;font-weight:600;
  color:var(--pearl);display:block;margin-bottom:3px;}
.cat-card:hover .cat-name,.cat-card.on .cat-name{color:var(--gold3);}
.cat-count{font-size:9.5px;color:var(--smoke);letter-spacing:1px;display:block;margin-top:4px;}
.cat-card.on .cat-count{color:var(--gold);opacity:.7;}

/* ── PRODUCTS ── */
.shop-sec{background:var(--ink);}
.prod-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(290px,1fr));gap:22px;}
.prod-card{background:var(--card);border:1px solid rgba(255,255,255,.055);
  border-radius:16px;overflow:hidden;
  transition:transform var(--ease),box-shadow var(--ease),border-color var(--ease);
  position:relative;}
.prod-card:hover{transform:translateY(-7px);box-shadow:var(--sh3);border-color:var(--bd1);}

.prod-img-box{position:relative;aspect-ratio:3/4;overflow:hidden;isolation:isolate;
  background:linear-gradient(160deg,var(--lift) 0%,var(--card) 100%);
  display:flex;align-items:center;justify-content:center;}
.prod-img-box img{width:100%;height:100%;object-fit:cover;transition:transform .55s ease;}
.prod-card:hover .prod-img-box img{transform:scale(1.05);}
.prod-no-img{font-size:88px;opacity:.3;transition:all .4s;user-select:none;position:relative;z-index:1;}
.prod-card:hover .prod-no-img{opacity:.42;transform:scale(1.06);}
.prod-img-box::after{content:'';position:absolute;bottom:0;left:0;right:0;height:55%;
  background:linear-gradient(to top,rgba(28,24,37,.92) 0%,transparent 100%);pointer-events:none;}

/* Category colour accent on image */
.prod-cat-accent{position:absolute;top:0;left:0;right:0;height:3px;z-index:2;}

.prod-badge{position:absolute;top:13px;left:13px;z-index:3;
  padding:3px 11px;border-radius:99px;font-size:9px;font-weight:800;
  letter-spacing:1.5px;text-transform:uppercase;}
.badge-new{background:var(--green);color:#fff;}
.badge-hot{background:var(--rose);color:#fff;}
.badge-out{background:var(--lift);color:var(--ash);border:1px solid rgba(255,255,255,.08);}

.prod-wish{position:absolute;top:11px;right:13px;z-index:3;
  width:34px;height:34px;border-radius:50%;
  background:rgba(8,7,10,.65);backdrop-filter:blur(6px);
  border:1px solid rgba(255,255,255,.07);color:var(--ash);font-size:14px;
  cursor:pointer;display:flex;align-items:center;justify-content:center;
  opacity:0;transform:translateY(-4px);transition:all var(--ease);}
.prod-card:hover .prod-wish{opacity:1;transform:translateY(0);}
.prod-wish:hover{background:var(--rose);border-color:var(--rose);color:#fff;}

.oos-veil{position:absolute;inset:0;z-index:4;
  background:rgba(8,7,10,.65);backdrop-filter:blur(2px);
  display:flex;align-items:center;justify-content:center;}
.oos-txt{font-family:'Cormorant Garamond',serif;font-size:18px;
  color:var(--ash);letter-spacing:3px;text-transform:uppercase;font-style:italic;}

.prod-info{padding:18px 20px 20px;}
.prod-cat-lbl{font-size:8.5px;letter-spacing:3px;text-transform:uppercase;
  color:var(--gold);font-weight:700;margin-bottom:5px;}
.prod-name{font-family:'Cormorant Garamond',serif;font-size:19px;font-weight:600;
  color:var(--pearl);line-height:1.2;margin-bottom:5px;}
.prod-desc{font-size:12px;color:var(--ash);line-height:1.55;margin-bottom:15px;font-weight:300;}
.prod-footer{display:flex;align-items:center;justify-content:space-between;gap:10px;}
.prod-price{font-family:'Cormorant Garamond',serif;font-size:22px;font-weight:600;
  background:linear-gradient(135deg,var(--gold3),var(--gold));
  -webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;}
.prod-price small{font-family:'Inter',sans-serif;font-size:9.5px;
  -webkit-text-fill-color:var(--smoke);color:var(--smoke);letter-spacing:.8px;font-weight:400;}
.add-btn{background:linear-gradient(135deg,var(--gold),var(--gold2));color:var(--ink);
  border:none;border-radius:6px;padding:10px 16px;font-size:9.5px;font-weight:800;
  letter-spacing:1.5px;text-transform:uppercase;cursor:pointer;
  transition:all var(--ease);white-space:nowrap;font-family:'Inter',sans-serif;}
.add-btn:hover{transform:translateY(-1px);box-shadow:var(--shg);}
.add-btn:disabled{background:var(--lift);color:var(--smoke);cursor:not-allowed;
  box-shadow:none;transform:none;}

/* Empty state */
.empty-st{grid-column:1/-1;text-align:center;padding:110px 24px;}
.empty-st svg{opacity:.18;margin:0 auto 20px;}
.empty-st h3{font-family:'Cormorant Garamond',serif;font-size:30px;color:var(--ash);margin-bottom:8px;}
.empty-st p{font-size:14px;color:var(--smoke);}

/* ── FEATURES STRIP ── */
.feat-strip{background:var(--deep);border-top:1px solid var(--bd1);border-bottom:1px solid var(--bd1);}
.feat-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:0;}
.feat-item{display:flex;align-items:center;gap:14px;padding:28px 28px;
  border-right:1px solid var(--bd1);}
.feat-item:last-child{border:none;}
.feat-ico{width:44px;height:44px;border-radius:12px;flex-shrink:0;
  background:linear-gradient(135deg,rgba(201,150,58,.12),rgba(201,150,58,.04));
  border:1px solid var(--bd1);display:flex;align-items:center;justify-content:center;}
.feat-t strong{display:block;font-size:13px;color:var(--pearl);font-weight:600;margin-bottom:2px;}
.feat-t span{font-size:11.5px;color:var(--ash);font-weight:300;}

/* ── HOW TO ORDER ── */
.how-sec{background:linear-gradient(155deg,var(--lift) 0%,var(--deep) 60%,#0E0B18 100%);
  position:relative;overflow:hidden;}
.how-sec::before{content:'';position:absolute;top:-150px;right:-150px;width:500px;height:500px;
  border-radius:50%;background:radial-gradient(circle,rgba(201,150,58,.05) 0%,transparent 70%);pointer-events:none;}
.how-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:18px;}
.how-card{background:var(--g1);border:1px solid var(--bd1);border-radius:16px;
  padding:36px 24px;text-align:center;position:relative;overflow:hidden;transition:all var(--ease);}
.how-card:hover{border-color:var(--bd2);transform:translateY(-4px);}
.how-card::before{content:'';position:absolute;top:0;left:0;right:0;height:2px;
  background:linear-gradient(90deg,transparent,var(--gold),transparent);
  opacity:0;transition:opacity var(--ease);}
.how-card:hover::before{opacity:1;}
.how-num{font-family:'Cormorant Garamond',serif;font-size:68px;font-weight:700;
  color:rgba(201,150,58,.07);line-height:1;margin-bottom:6px;}
.how-ico-wrap{width:54px;height:54px;border-radius:14px;
  background:linear-gradient(135deg,rgba(201,150,58,.13),rgba(201,150,58,.04));
  border:1px solid var(--bd1);display:flex;align-items:center;justify-content:center;
  margin:0 auto 18px;}
.how-card h3{font-family:'Cormorant Garamond',serif;font-size:19px;font-weight:600;
  color:var(--pearl);margin-bottom:9px;}
.how-card p{font-size:12.5px;color:var(--ash);line-height:1.7;font-weight:300;}

/* ── MPESA ── */
.mpesa-sec{background:var(--ink);}
.mpesa-layout{display:grid;grid-template-columns:1fr 1fr;gap:48px;align-items:start;}
.mpesa-card{background:var(--card);border:1px solid rgba(255,255,255,.055);
  border-radius:20px;overflow:hidden;box-shadow:var(--sh3);}
.mpesa-top{background:linear-gradient(135deg,#005A2B 0%,#00883E 60%,#006B32 100%);
  padding:38px;text-align:center;color:#fff;position:relative;overflow:hidden;}
.mpesa-top::before{content:'';position:absolute;inset:0;
  background:url("data:image/svg+xml,%3Csvg width='60' height='60' viewBox='0 0 60 60' xmlns='http://www.w3.org/2000/svg'%3E%3Cg fill='none' fill-rule='evenodd'%3E%3Cg fill='%23ffffff' fill-opacity='0.03'%3E%3Ccircle cx='30' cy='30' r='20'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E");}
.mpesa-e{font-size:52px;display:block;margin-bottom:10px;}
.mpesa-top h2{font-family:'Cormorant Garamond',serif;font-size:26px;margin-bottom:4px;font-weight:600;}
.mpesa-top p{font-size:11px;opacity:.7;letter-spacing:1.5px;text-transform:uppercase;}
.mpesa-num-box{background:linear-gradient(135deg,var(--goldf),var(--goldp));
  border:2px solid var(--gold);border-radius:12px;padding:18px 22px;text-align:center;margin:24px;}
.mns-l{font-size:8.5px;letter-spacing:3px;text-transform:uppercase;color:#7A4A10;margin-bottom:5px;}
.mns-n{font-family:'Cormorant Garamond',serif;font-size:34px;font-weight:700;
  color:#6B3E0E;letter-spacing:3.5px;}
.mns-w{font-size:11px;color:#8B5E1A;margin-top:3px;}
.mpesa-steps{list-style:none;padding:0 24px 24px;}
.mps{display:flex;gap:13px;align-items:flex-start;
  padding:11px 0;border-bottom:1px solid rgba(255,255,255,.05);}
.mps:last-child{border:none;}
.mps-n{width:27px;height:27px;border-radius:50%;flex-shrink:0;
  background:linear-gradient(135deg,var(--gold),var(--gold2));
  color:var(--ink);font-size:11px;font-weight:800;
  display:flex;align-items:center;justify-content:center;}
.mps-t strong{display:block;font-size:13px;color:var(--pearl);margin-bottom:1px;}
.mps-t span{font-size:11.5px;color:var(--ash);font-weight:300;}
.tip-cards{display:flex;flex-direction:column;gap:16px;}
.tip{background:var(--card);border:1px solid rgba(255,255,255,.055);border-radius:14px;
  padding:24px;transition:all var(--ease);position:relative;overflow:hidden;}
.tip:hover{border-color:var(--bd1);transform:translateX(4px);}
.tip::before{content:'';position:absolute;left:0;top:12%;bottom:12%;
  width:2px;background:linear-gradient(to bottom,transparent,var(--gold),transparent);
  opacity:0;transition:opacity var(--ease);}
.tip:hover::before{opacity:1;}
.tip-icon{font-size:26px;margin-bottom:9px;display:block;}
.tip h4{font-family:'Cormorant Garamond',serif;font-size:17px;color:var(--pearl);
  margin-bottom:5px;font-weight:600;}
.tip p{font-size:12.5px;color:var(--ash);line-height:1.6;font-weight:300;}
.wa-btn{display:inline-flex;align-items:center;gap:7px;background:#22C55E;color:#fff;
  border-radius:6px;padding:7px 14px;font-size:12px;font-weight:700;margin-top:9px;
  transition:all var(--ease);text-decoration:none;}
.wa-btn:hover{background:#16A34A;transform:translateY(-1px);}

/* ── LOCATION ── */
.loc-sec{background:var(--deep);}
.loc-layout{display:grid;grid-template-columns:1fr 1fr;gap:48px;align-items:start;}
.info-stack{display:flex;flex-direction:column;gap:13px;}
.info-blk{display:flex;gap:16px;align-items:flex-start;background:var(--g1);
  border:1px solid var(--bd1);border-radius:14px;padding:20px 22px;transition:all var(--ease);}
.info-blk:hover{border-color:var(--bd2);}
.ib-ico{width:42px;height:42px;border-radius:11px;flex-shrink:0;
  background:linear-gradient(135deg,rgba(201,150,58,.12),rgba(201,150,58,.04));
  border:1px solid var(--bd1);display:flex;align-items:center;justify-content:center;}
.ib-l{font-size:8.5px;letter-spacing:3px;text-transform:uppercase;color:var(--gold);
  font-weight:700;margin-bottom:4px;}
.ib-v{font-size:13.5px;color:var(--silver);font-weight:300;line-height:1.65;}
.ib-v a{color:var(--silver);text-decoration:none;transition:color var(--ease);}
.ib-v a:hover{color:var(--gold);}

.map-blk{background:var(--g1);border:1px solid var(--bd1);border-radius:20px;overflow:hidden;}
.map-vis{height:250px;display:flex;flex-direction:column;align-items:center;
  justify-content:center;gap:10px;position:relative;
  background:linear-gradient(160deg,rgba(201,150,58,.07),rgba(201,150,58,.02));}
.map-vis::before{content:'';position:absolute;inset:0;
  background:radial-gradient(circle at center,rgba(201,150,58,.05) 0%,transparent 70%);}
.map-vis svg{opacity:.5;}
.map-vis h3{font-family:'Cormorant Garamond',serif;font-size:20px;color:var(--pearl);font-weight:600;}
.map-vis p{font-size:11.5px;color:var(--ash);}
.map-cta{display:inline-flex;align-items:center;gap:7px;
  background:linear-gradient(135deg,var(--gold),var(--gold2));color:var(--ink);
  border-radius:6px;padding:9px 20px;font-size:10.5px;font-weight:700;
  letter-spacing:1px;text-transform:uppercase;transition:all var(--ease);
  text-decoration:none;margin-top:2px;}
.map-cta:hover{transform:translateY(-2px);box-shadow:var(--shg);}
.hours-list{padding:0;}
.h-row{display:flex;justify-content:space-between;align-items:center;
  padding:11px 22px;border-top:1px solid rgba(255,255,255,.04);}
.h-day{font-size:12px;color:var(--ash);font-weight:300;}
.h-time{font-size:12px;color:var(--pearl);font-weight:500;}
.h-open{background:rgba(34,197,94,.15);border:1px solid rgba(34,197,94,.25);
  color:#4ADE80;border-radius:99px;padding:2px 9px;font-size:8.5px;font-weight:700;letter-spacing:.8px;}

/* ── FOOTER ── */
footer{background:var(--ink);border-top:1px solid var(--bd1);padding:68px 40px 28px;}
.foot-inner{max-width:1380px;margin:0 auto;}
.foot-grid{display:grid;grid-template-columns:1.8fr 1fr 1fr;gap:56px;margin-bottom:56px;}
.f-logo-row{display:flex;align-items:center;gap:12px;margin-bottom:6px;}
.f-logo-name{font-family:'Cormorant Garamond',serif;font-size:28px;font-weight:600;
  background:linear-gradient(135deg,var(--gold3),var(--gold));
  -webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;}
.f-sub{font-size:8px;letter-spacing:3.5px;text-transform:uppercase;color:var(--smoke);margin-bottom:14px;}
.f-desc{font-size:12.5px;color:var(--smoke);line-height:1.8;font-weight:300;max-width:260px;}
.f-col h4{font-size:8.5px;letter-spacing:4px;text-transform:uppercase;
  color:var(--gold);font-weight:700;margin-bottom:18px;}
.f-col a{display:block;font-size:12.5px;color:var(--smoke);margin-bottom:10px;
  text-decoration:none;transition:color var(--ease);font-weight:300;}
.f-col a:hover{color:var(--gold);}
.foot-div{height:1px;background:linear-gradient(90deg,transparent,var(--bd1),transparent);margin-bottom:24px;}
.foot-btm{display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;gap:10px;}
.foot-copy{font-size:11px;color:var(--smoke);font-weight:300;}
.foot-love{font-size:11px;color:var(--smoke);}

/* ── OVERLAY & CART ── */
.overlay{position:fixed;inset:0;z-index:700;background:rgba(0,0,0,.78);
  backdrop-filter:blur(7px);opacity:0;pointer-events:none;transition:opacity .3s;}
.overlay.on{opacity:1;pointer-events:all;}
.cart-panel{position:fixed;right:-510px;top:0;bottom:0;width:490px;max-width:100vw;
  background:var(--card);z-index:701;display:flex;flex-direction:column;
  transition:right .38s cubic-bezier(.25,.8,.25,1);
  box-shadow:-18px 0 72px rgba(0,0,0,.4);border-left:1px solid var(--bd1);}
.cart-panel.open{right:0;}
.cp-hd{background:var(--deep);padding:22px 26px;
  display:flex;align-items:center;justify-content:space-between;
  border-bottom:1px solid var(--bd1);flex-shrink:0;}
.cp-title{font-family:'Cormorant Garamond',serif;font-size:21px;color:var(--gold3);font-weight:600;}
.cp-x{width:34px;height:34px;border-radius:7px;background:var(--g2);
  border:1px solid var(--bd1);color:var(--ash);font-size:17px;cursor:pointer;
  display:flex;align-items:center;justify-content:center;transition:all var(--ease);}
.cp-x:hover{background:rgba(196,112,90,.18);border-color:var(--rose);color:var(--rose);}
.cp-body{flex:1;overflow-y:auto;padding:18px 26px;}
.ci{display:flex;gap:13px;padding:16px 0;border-bottom:1px solid rgba(255,255,255,.04);}
.ci-thumb{width:68px;height:84px;border-radius:10px;background:var(--lift);flex-shrink:0;
  display:flex;align-items:center;justify-content:center;font-size:28px;
  overflow:hidden;border:1px solid rgba(255,255,255,.05);}
.ci-thumb img{width:100%;height:100%;object-fit:cover;}
.ci-inf{flex:1;}
.ci-cat{font-size:8.5px;letter-spacing:2px;text-transform:uppercase;color:var(--gold);margin-bottom:3px;}
.ci-name{font-family:'Cormorant Garamond',serif;font-size:16px;color:var(--pearl);
  line-height:1.2;margin-bottom:3px;font-weight:600;}
.ci-unit{font-size:11.5px;color:var(--ash);font-weight:300;}
.ci-row{display:flex;align-items:center;justify-content:space-between;margin-top:9px;}
.qty-row{display:flex;align-items:center;gap:8px;}
.qb{width:27px;height:27px;border-radius:6px;background:var(--lift);
  border:1px solid rgba(255,255,255,.06);color:var(--pearl);font-size:13px;
  font-weight:700;cursor:pointer;display:flex;align-items:center;justify-content:center;
  transition:all var(--ease);}
.qb:hover{background:var(--gold);border-color:var(--gold);color:var(--ink);}
.qv{font-size:13px;font-weight:600;color:var(--pearl);min-width:20px;text-align:center;}
.ci-line{font-family:'Cormorant Garamond',serif;font-size:17px;font-weight:600;
  background:linear-gradient(135deg,var(--gold3),var(--gold));
  -webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;}
.ci-del{color:rgba(196,112,90,.5);background:none;border:none;cursor:pointer;
  font-size:10.5px;letter-spacing:1px;text-transform:uppercase;
  transition:color var(--ease);margin-top:4px;display:block;font-family:'Inter',sans-serif;}
.ci-del:hover{color:var(--rose);}
.cp-totals{padding:18px 26px;background:var(--deep);border-top:1px solid var(--bd1);flex-shrink:0;}
.tot-r{display:flex;justify-content:space-between;font-size:12.5px;color:var(--ash);padding:5px 0;}
.tot-grand{display:flex;justify-content:space-between;
  font-family:'Cormorant Garamond',serif;font-size:24px;color:var(--pearl);font-weight:600;
  border-top:1px solid var(--bd1);padding-top:13px;margin-top:7px;}
.tot-grand span:last-child{background:linear-gradient(135deg,var(--gold3),var(--gold));
  -webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;}
.cp-acts{padding:14px 26px 22px;background:var(--deep);flex-shrink:0;}
.cp-btn{width:100%;padding:15px;border-radius:7px;font-size:11px;font-weight:700;
  letter-spacing:1.8px;text-transform:uppercase;cursor:pointer;border:none;
  display:flex;align-items:center;justify-content:center;gap:8px;
  transition:all var(--ease);margin-bottom:8px;font-family:'Inter',sans-serif;}
.cpb-g{background:linear-gradient(135deg,var(--gold),var(--gold2));
  color:var(--ink);box-shadow:var(--shg);}
.cpb-g:hover{transform:translateY(-1px);box-shadow:0 10px 36px rgba(201,150,58,.35);}
.cpb-o{background:transparent;border:1px solid rgba(255,255,255,.07);color:var(--ash);}
.cpb-o:hover{border-color:var(--bd2);color:var(--gold);}
.cp-empty{text-align:center;padding:72px 20px;}
.cp-empty-i{font-size:60px;opacity:.18;margin-bottom:14px;}
.cp-empty p{color:var(--smoke);font-size:14px;font-weight:300;}

/* Checkout form */
.cf{padding:18px 26px;flex:1;overflow-y:auto;}
.cf-lbl{display:block;font-size:9.5px;letter-spacing:2px;text-transform:uppercase;
  color:var(--gold);font-weight:700;margin-bottom:6px;}
.cf-inp{width:100%;padding:12px 15px;background:var(--deep);
  border:1.5px solid rgba(255,255,255,.07);border-radius:7px;
  font-family:'Inter',sans-serif;font-size:13.5px;color:var(--pearl);
  margin-bottom:13px;transition:border-color var(--ease);}
.cf-inp:focus{outline:none;border-color:var(--gold);}
.cf-inp::placeholder{color:var(--smoke);}
.oms{background:var(--deep);border:1px solid var(--bd1);border-radius:12px;
  padding:15px;margin-bottom:15px;}
.oms-r{display:flex;justify-content:space-between;font-size:12.5px;color:var(--ash);padding:3px 0;}
.oms-tot{display:flex;justify-content:space-between;
  font-family:'Cormorant Garamond',serif;font-size:20px;color:var(--pearl);font-weight:600;
  border-top:1px solid var(--bd1);padding-top:9px;margin-top:7px;}
.oms-tot span:last-child{background:linear-gradient(135deg,var(--gold3),var(--gold));
  -webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;}
.mps-hint{background:rgba(0,136,62,.1);border:1px solid rgba(0,136,62,.22);
  border-radius:10px;padding:13px 15px;margin-bottom:14px;font-size:12.5px;
  color:#4ADE80;display:flex;gap:9px;align-items:flex-start;line-height:1.5;}

/* ── ADMIN ── */
.modal-bg{position:fixed;inset:0;z-index:900;background:rgba(0,0,0,.88);
  backdrop-filter:blur(12px);display:flex;align-items:flex-start;
  justify-content:center;padding:22px;overflow-y:auto;}
.adm{background:var(--card);border:1px solid var(--bd1);border-radius:22px;
  width:100%;max-width:960px;margin:auto;overflow:hidden;box-shadow:var(--sh4);}
.adm-hd{background:var(--deep);padding:26px 38px;
  display:flex;align-items:center;justify-content:space-between;
  border-bottom:1px solid var(--bd1);}
.adm-title{font-family:'Cormorant Garamond',serif;font-size:24px;
  color:var(--gold3);font-weight:600;}
.adm-body{padding:38px;}
.login-wrap{max-width:360px;margin:0 auto;text-align:center;}
.login-ico{font-size:50px;margin-bottom:14px;}
.login-wrap h3{font-family:'Cormorant Garamond',serif;font-size:27px;
  color:var(--pearl);margin-bottom:7px;font-weight:600;}
.login-wrap p{font-size:13.5px;color:var(--ash);margin-bottom:28px;font-weight:300;}
.adm-tabs{display:flex;background:var(--deep);border-radius:12px;overflow:hidden;
  border:1px solid var(--bd1);margin-bottom:32px;}
.adm-tab{flex:1;padding:13px;text-align:center;font-size:9.5px;font-weight:700;
  letter-spacing:1.8px;text-transform:uppercase;cursor:pointer;
  color:var(--smoke);transition:all var(--ease);border-right:1px solid var(--bd1);
  font-family:'Inter',sans-serif;}
.adm-tab:last-child{border-right:none;}
.adm-tab.on{background:linear-gradient(135deg,var(--gold),var(--gold2));color:var(--ink);}
.fg2{display:grid;grid-template-columns:1fr 1fr;gap:14px;}
.f-lbl{display:block;font-size:9.5px;letter-spacing:2px;text-transform:uppercase;
  color:var(--gold);font-weight:700;margin-bottom:6px;}
.f-inp,.f-sel,.f-ta{width:100%;padding:11px 14px;background:var(--deep);
  border:1.5px solid rgba(255,255,255,.07);border-radius:7px;
  font-family:'Inter',sans-serif;font-size:13.5px;color:var(--pearl);
  margin-bottom:14px;transition:border-color var(--ease);}
.f-inp:focus,.f-sel:focus,.f-ta:focus{outline:none;border-color:var(--gold);}
.f-inp::placeholder,.f-ta::placeholder{color:var(--smoke);}
.f-sel option{background:var(--card);}
.upload-area{border:2px dashed rgba(201,150,58,.22);border-radius:12px;
  padding:22px;text-align:center;cursor:pointer;transition:all var(--ease);
  margin-bottom:14px;position:relative;overflow:hidden;min-height:110px;
  display:flex;align-items:center;justify-content:center;flex-direction:column;gap:7px;}
.upload-area:hover{border-color:var(--gold);background:rgba(201,150,58,.03);}
.upload-area input[type=file]{position:absolute;inset:0;opacity:0;cursor:pointer;width:100%;height:100%;}
.ua-ico{font-size:28px;opacity:.38;}
.ua-txt{font-size:11.5px;color:var(--ash);font-weight:300;}
.ua-sub{font-size:9.5px;color:var(--smoke);}
.img-prev{width:72px;height:72px;border-radius:10px;object-fit:cover;
  border:2px solid var(--gold);display:none;margin:0 auto;}
.pl-item{display:flex;gap:12px;align-items:center;background:var(--deep);
  border:1px solid rgba(255,255,255,.05);border-radius:11px;
  padding:13px 16px;margin-bottom:9px;transition:border-color var(--ease);}
.pl-item:hover{border-color:var(--bd1);}
.pl-thumb{width:46px;height:56px;border-radius:8px;background:var(--lift);flex-shrink:0;
  display:flex;align-items:center;justify-content:center;font-size:20px;
  overflow:hidden;border:1px solid rgba(255,255,255,.05);}
.pl-thumb img{width:100%;height:100%;object-fit:cover;}
.pl-inf{flex:1;}
.pl-inf strong{display:block;font-size:14px;color:var(--pearl);}
.pl-inf small{font-size:9.5px;color:var(--gold);letter-spacing:1.5px;text-transform:uppercase;}
.pl-price{font-size:12.5px;color:var(--ash);margin-top:2px;}
.pl-acts{display:flex;gap:7px;flex-shrink:0;}
.oos-tog{padding:5px 11px;border-radius:7px;font-size:9px;font-weight:800;
  letter-spacing:1px;text-transform:uppercase;cursor:pointer;border:none;
  transition:all var(--ease);font-family:'Inter',sans-serif;}
.t-live{background:rgba(34,197,94,.14);color:#4ADE80;border:1px solid rgba(34,197,94,.25);}
.t-oos{background:rgba(196,112,90,.12);color:var(--rose2);border:1px solid rgba(196,112,90,.2);}
.del-b{padding:5px 11px;border-radius:7px;font-size:9px;font-weight:800;
  letter-spacing:1px;text-transform:uppercase;cursor:pointer;
  background:rgba(196,112,90,.1);color:var(--rose2);border:1px solid rgba(196,112,90,.18);
  transition:all var(--ease);font-family:'Inter',sans-serif;}
.del-b:hover{background:rgba(196,112,90,.22);}
.o-tbl{width:100%;border-collapse:collapse;}
.o-tbl th{text-align:left;padding:9px 13px;font-size:8.5px;letter-spacing:2px;
  text-transform:uppercase;color:var(--gold);font-weight:700;
  border-bottom:1px solid var(--bd1);}
.o-tbl td{padding:11px 13px;border-bottom:1px solid rgba(255,255,255,.04);
  font-size:12.5px;color:var(--ash);vertical-align:middle;}
.o-tbl tr:hover td{background:rgba(255,255,255,.018);}
.o-st{padding:3px 9px;border-radius:99px;font-size:8.5px;font-weight:800;
  letter-spacing:.8px;text-transform:uppercase;border:none;cursor:pointer;
  font-family:'Inter',sans-serif;}
.st-new{background:rgba(34,197,94,.15);color:#4ADE80;}
.st-proc{background:rgba(201,150,58,.13);color:var(--gold3);}
.st-done{background:rgba(42,92,138,.18);color:#60A5FA;}

/* ── TOAST ── */
.toast{position:fixed;bottom:38px;left:50%;
  transform:translateX(-50%) translateY(18px);
  background:var(--card);color:var(--gold3);
  border:1px solid var(--bd2);padding:13px 26px;border-radius:12px;
  font-size:13px;font-weight:500;z-index:1000;opacity:0;pointer-events:none;
  transition:all .32s;white-space:nowrap;box-shadow:var(--sh3);}
.toast.show{opacity:1;transform:translateX(-50%) translateY(0);}

/* ── REVEAL ── */
.rv{opacity:0;transform:translateY(26px);transition:opacity .75s ease,transform .75s ease;}
.rvl{opacity:0;transform:translateX(-28px);transition:opacity .75s ease,transform .75s ease;}
.rvr{opacity:0;transform:translateX(28px);transition:opacity .75s ease,transform .75s ease;}
.rv.vis,.rvl.vis,.rvr.vis{opacity:1;transform:none;}

/* ── BTN UTIL ── */
.btn{display:inline-flex;align-items:center;gap:8px;padding:13px 30px;border-radius:6px;
  font-size:10.5px;font-weight:700;letter-spacing:1.8px;text-transform:uppercase;
  cursor:pointer;border:none;transition:all var(--ease);font-family:'Inter',sans-serif;}
.btn-g{background:linear-gradient(135deg,var(--gold),var(--gold2));color:var(--ink);box-shadow:var(--shg);}
.btn-g:hover{transform:translateY(-2px);box-shadow:0 10px 32px rgba(201,150,58,.38);}

/* ── RESPONSIVE ── */
@media(max-width:1100px){
  .hero{grid-template-columns:1fr;}.hero-right{display:none;}
  .hero-left{padding:72px 36px;}
  .mpesa-layout,.loc-layout{grid-template-columns:1fr;}
  .foot-grid{grid-template-columns:1fr 1fr;}
  .feat-grid{grid-template-columns:1fr 1fr;}
  .feat-item:nth-child(2){border-right:none;}
  .feat-item:nth-child(3){border-top:1px solid var(--bd1);}
}
@media(max-width:768px){
  .sec{padding:68px 22px;}.hero-left{padding:60px 22px;}
  .nav-inner{padding:0 22px;}.nav-links{display:none;}
  .hero-kpis{gap:20px;}.kpi{padding:0 14px;}
  .prod-grid{grid-template-columns:1fr 1fr;}
  .cat-grid{grid-template-columns:repeat(2,1fr);}
  .how-grid{grid-template-columns:1fr 1fr;}
  .cart-panel{width:100%;right:-100%;}
  .foot-grid{grid-template-columns:1fr;}
  .feat-grid{grid-template-columns:1fr;}
  .feat-item{border-right:none!important;border-top:1px solid var(--bd1);}
  .feat-item:first-child{border-top:none;}
  .fg2{grid-template-columns:1fr;}.adm-body{padding:22px;}
  footer{padding:48px 22px 22px;}
}
@media(max-width:480px){
  .hero-h1{font-size:42px;}
  .prod-grid{grid-template-columns:1fr;}
  .how-grid{grid-template-columns:1fr;}
  .hero-kpis{flex-direction:column;gap:14px;}
  .kpi{border:none!important;padding:0!important;}
}
</style>
</head>
<body>

<!-- TICKER -->
<div class="ticker">
  <div class="ticker-inner">
    <span class="t-item">✦ New Arrivals Weekly <span class="t-dot"></span></span>
    <span class="t-item">Women · Men · Children <span class="t-dot"></span></span>
    <span class="t-item">M-Pesa Accepted <span class="t-dot"></span></span>
    <span class="t-item">Countrywide Delivery <span class="t-dot"></span></span>
    <span class="t-item">Call 0701 227 713 <span class="t-dot"></span></span>
    <span class="t-item">Nkubu, Meru County <span class="t-dot"></span></span>
    <span class="t-item">✦ New Arrivals Weekly <span class="t-dot"></span></span>
    <span class="t-item">Women · Men · Children <span class="t-dot"></span></span>
    <span class="t-item">M-Pesa Accepted <span class="t-dot"></span></span>
    <span class="t-item">Countrywide Delivery <span class="t-dot"></span></span>
    <span class="t-item">Call 0701 227 713 <span class="t-dot"></span></span>
    <span class="t-item">Nkubu, Meru County <span class="t-dot"></span></span>
  </div>
</div>

<!-- NAV -->
<nav class="nav">
  <div class="nav-inner">
    <a class="brand" href="#">
      <!-- SVG Brand Logo -->
      <svg class="brand-logo" viewBox="0 0 42 42" fill="none" xmlns="http://www.w3.org/2000/svg">
        <circle cx="21" cy="21" r="20" stroke="#C9963A" stroke-width="1" opacity=".3"/>
        <circle cx="21" cy="21" r="14" stroke="#C9963A" stroke-width="1" opacity=".2"/>
        <text x="21" y="26" font-family="Cormorant Garamond,serif" font-size="16" font-weight="600"
          fill="#C9963A" text-anchor="middle">S</text>
      </svg>
      <div class="brand-text">
        <span class="brand-name">Sarah Fashions</span>
        <span class="brand-loc">Nkubu · Meru County · Kenya</span>
      </div>
    </a>
    <ul class="nav-links">
      <li><a href="#shop">Shop</a></li>
      <li><a href="#how">Order Guide</a></li>
      <li><a href="#mpesa">M-Pesa</a></li>
      <li><a href="#location">Find Us</a></li>
    </ul>
    <div class="nav-actions">
      <button class="btn-seller" onclick="openAdmin()">⚙ Seller</button>
      <button class="btn-cart" onclick="openCart()">
        <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><path d="M6 2L3 6v14a2 2 0 002 2h14a2 2 0 002-2V6l-3-4z"/><line x1="3" y1="6" x2="21" y2="6"/><path d="M16 10a4 4 0 01-8 0"/></svg>
        Cart <span class="cart-n" id="cartCount">0</span>
      </button>
    </div>
  </div>
</nav>

<!-- HERO -->
<section class="hero">
  <div class="hero-left">
    <!-- SVG Background Pattern -->
    <svg class="hero-bg-pattern" viewBox="0 0 800 600" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="xMidYMid slice">
      <defs>
        <pattern id="grid" width="60" height="60" patternUnits="userSpaceOnUse">
          <path d="M 60 0 L 0 0 0 60" fill="none" stroke="#C9963A" stroke-width="0.5"/>
        </pattern>
      </defs>
      <rect width="100%" height="100%" fill="url(#grid)"/>
      <circle cx="700" cy="100" r="200" fill="none" stroke="#C9963A" stroke-width="0.5"/>
      <circle cx="700" cy="100" r="140" fill="none" stroke="#C9963A" stroke-width="0.5"/>
      <circle cx="700" cy="100" r="80" fill="none" stroke="#C9963A" stroke-width="0.5"/>
    </svg>

    <div class="hero-tag">
      <span class="hero-tag-dot"></span>
      <span class="hero-tag-txt">Premium Fashion · Est. Nkubu</span>
    </div>

    <h1 class="hero-h1">
      Where Style<br>
      Meets <span class="g">Elegance</span>
      <span class="s">Curated for every occasion</span>
    </h1>
    <p class="hero-p">Discover Women's, Men's and Children's fashion handpicked for quality and style — from Nkubu to anywhere in Kenya.</p>

    <div class="hero-btns">
      <button class="btn-primary" onclick="scrollTo('shop')">
        Shop Collection
        <svg width="13" height="13" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><line x1="5" y1="12" x2="19" y2="12"/><polyline points="12 5 19 12 12 19"/></svg>
      </button>
      <button class="btn-ghost" onclick="scrollTo('how')">How to Order</button>
    </div>

    <div class="hero-kpis">
      <div class="kpi"><div class="kpi-v" id="heroItems">0</div><div class="kpi-l">Items In Stock</div></div>
      <div class="kpi"><div class="kpi-v" id="heroCats">0</div><div class="kpi-l">Categories</div></div>
      <div class="kpi"><div class="kpi-v">✓</div><div class="kpi-l">M-Pesa Ready</div></div>
    </div>
  </div>

  <div class="hero-right">
    <div class="hero-showcase">
      <!-- SVG Fashion Illustration Card -->
      <div class="fashion-card">
        <div class="fc-lbl">Featured Collection</div>
        <div class="fc-svg" id="heroCardVis">
          <svg width="110" height="110" viewBox="0 0 110 110" fill="none" xmlns="http://www.w3.org/2000/svg">
            <circle cx="55" cy="55" r="52" fill="rgba(201,150,58,.06)" stroke="rgba(201,150,58,.15)" stroke-width="1"/>
            <ellipse cx="55" cy="26" rx="14" ry="15" stroke="#C9963A" stroke-width="1.4" fill="rgba(201,150,58,.12)"/>
            <path d="M41 40 L24 94 Q55 102 86 94 L69 40 Q62 54 55 54 Q48 54 41 40Z" stroke="#C9963A" stroke-width="1.4" fill="rgba(201,150,58,.08)"/>
            <path d="M41 40 Q48 52 55 52 Q62 52 69 40" fill="none" stroke="#C9963A" stroke-width="1.3"/>
            <line x1="36" y1="58" x2="74" y2="58" stroke="#C9963A" stroke-width=".9" opacity=".4"/>
            <line x1="30" y1="70" x2="80" y2="70" stroke="#C9963A" stroke-width=".9" opacity=".35"/>
            <line x1="26" y1="82" x2="84" y2="82" stroke="#C9963A" stroke-width=".9" opacity=".3"/>
            <circle cx="55" cy="44" r="2" fill="#C9963A" opacity=".5"/>
            <path d="M18 18 L20 22 L24 18 L20 22 Z" stroke="#E8C87A" stroke-width="1" opacity=".4"/>
            <path d="M88 28 L90 32 L94 28 L90 32 Z" stroke="#E8C87A" stroke-width="1" opacity=".3"/>
          </svg>
        </div>
        <div class="fc-title">Sarah Fashions</div>
        <div class="fc-sub">Premium · Affordable · Stylish</div>
      </div>

      <div class="hero-chips">
        <div class="chip">
          <svg width="13" height="13" viewBox="0 0 24 24" fill="none" stroke="#C9963A" stroke-width="2"><circle cx="12" cy="8" r="4"/><path d="M4 20c0-4 3.6-7 8-7s8 3 8 7"/></svg>
          Women
        </div>
        <div class="chip">
          <svg width="13" height="13" viewBox="0 0 24 24" fill="none" stroke="#C9963A" stroke-width="2"><rect x="3" y="3" width="18" height="18" rx="2"/><line x1="3" y1="9" x2="21" y2="9"/><line x1="3" y1="15" x2="21" y2="15"/></svg>
          Men
        </div>
        <div class="chip">
          <svg width="13" height="13" viewBox="0 0 24 24" fill="none" stroke="#C9963A" stroke-width="2"><path d="M12 2C8 2 5 5 5 9c0 5 7 13 7 13s7-8 7-13c0-4-3-7-7-7z"/></svg>
          Children
        </div>
        <div class="chip">
          <svg width="13" height="13" viewBox="0 0 24 24" fill="none" stroke="#C9963A" stroke-width="2"><rect x="1" y="3" width="15" height="13"/><polygon points="16 8 20 8 23 11 23 16 16 16 16 8"/><circle cx="5.5" cy="18.5" r="2.5"/><circle cx="18.5" cy="18.5" r="2.5"/></svg>
          Countrywide
        </div>
      </div>
    </div>
  </div>
</section>

<!-- MARQUEE -->
<div class="marquee">
  <div class="marquee-inner">
    <span class="m-item"><span class="m-sep"></span> Ladies Fashion</span>
    <span class="m-item"><span class="m-sep"></span> Men's Collection</span>
    <span class="m-item"><span class="m-sep"></span> Children's Wear</span>
    <span class="m-item"><span class="m-sep"></span> M-Pesa Accepted</span>
    <span class="m-item"><span class="m-sep"></span> Countrywide Delivery</span>
    <span class="m-item"><span class="m-sep"></span> Nkubu, Meru</span>
    <span class="m-item"><span class="m-sep"></span> 0701 227 713</span>
    <span class="m-item"><span class="m-sep"></span> Ladies Fashion</span>
    <span class="m-item"><span class="m-sep"></span> Men's Collection</span>
    <span class="m-item"><span class="m-sep"></span> Children's Wear</span>
    <span class="m-item"><span class="m-sep"></span> M-Pesa Accepted</span>
    <span class="m-item"><span class="m-sep"></span> Countrywide Delivery</span>
    <span class="m-item"><span class="m-sep"></span> Nkubu, Meru</span>
    <span class="m-item"><span class="m-sep"></span> 0701 227 713</span>
  </div>
</div>

<!-- FEATURES STRIP -->
<div class="feat-strip">
  <div class="sec-inner">
    <div class="feat-grid">
      <div class="feat-item rv">
        <div class="feat-ico">
          <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#C9963A" stroke-width="1.8"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/></svg>
        </div>
        <div class="feat-t"><strong>Premium Quality</strong><span>Hand-selected fashion items</span></div>
      </div>
      <div class="feat-item rv">
        <div class="feat-ico">
          <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#C9963A" stroke-width="1.8"><rect x="1" y="3" width="15" height="13"/><polygon points="16 8 20 8 23 11 23 16 16 16 16 8"/><circle cx="5.5" cy="18.5" r="2.5"/><circle cx="18.5" cy="18.5" r="2.5"/></svg>
        </div>
        <div class="feat-t"><strong>Countrywide Delivery</strong><span>We deliver anywhere in Kenya</span></div>
      </div>
      <div class="feat-item rv">
        <div class="feat-ico">
          <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#C9963A" stroke-width="1.8"><rect x="2" y="5" width="20" height="14" rx="2"/><line x1="2" y1="10" x2="22" y2="10"/></svg>
        </div>
        <div class="feat-t"><strong>M-Pesa Payment</strong><span>Fast & secure transactions</span></div>
      </div>
      <div class="feat-item rv">
        <div class="feat-ico">
          <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#C9963A" stroke-width="1.8"><path d="M22 16.92v3a2 2 0 01-2.18 2 19.79 19.79 0 01-8.63-3.07A19.5 19.5 0 013.07 9.81a19.79 19.79 0 01-3.07-8.68A2 2 0 012.18 1h3a2 2 0 012 1.72c.127.96.361 1.903.7 2.81a2 2 0 01-.45 2.11L6.91 8.15a16 16 0 006.29 6.29l1.42-1.42a2 2 0 012.11-.45c.907.339 1.85.573 2.81.7A2 2 0 0122 16.92z"/></svg>
        </div>
        <div class="feat-t"><strong>Always Available</strong><span>Call us: 0701 227 713</span></div>
      </div>
    </div>
  </div>
</div>

<!-- CATEGORIES -->
<section class="sec cats-sec" id="shop">
  <div class="sec-inner">
    <div class="sec-hd rv">
      <div class="s-eye">Browse by Category</div>
      <h2 class="s-title">Find Your <em>Perfect Style</em></h2>
      <p class="s-sub">Select a category to explore our curated collection</p>
    </div>
    <div class="cat-grid" id="catsGrid"></div>
  </div>
</section>

<!-- PRODUCTS -->
<section class="sec shop-sec">
  <div class="sec-inner">
    <div class="sec-hd rv">
      <div class="s-eye">Our Collection</div>
      <h2 class="s-title">Shop the <em>Look</em></h2>
      <p class="s-sub" id="shopSub">Browse all premium fashion items available</p>
    </div>
    <div class="prod-grid" id="prodGrid"></div>
  </div>
</section>

<!-- HOW TO ORDER -->
<section class="sec how-sec" id="how">
  <div class="sec-inner">
    <div class="sec-hd rv">
      <div class="s-eye">Simple Process</div>
      <h2 class="s-title">Order in <em>4 Easy Steps</em></h2>
      <p class="s-sub">From browsing to your doorstep — fast and effortless</p>
    </div>
    <div class="how-grid">
      <div class="how-card rv">
        <div class="how-num">01</div>
        <div class="how-ico-wrap">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="#C9963A" stroke-width="1.8"><path d="M20.84 4.61a5.5 5.5 0 00-7.78 0L12 5.67l-1.06-1.06a5.5 5.5 0 00-7.78 7.78l1.06 1.06L12 21.23l7.78-7.78 1.06-1.06a5.5 5.5 0 000-7.78z"/></svg>
        </div>
        <h3>Browse & Pick</h3>
        <p>Explore our categories, find outfits you love and add them to your cart easily.</p>
      </div>
      <div class="how-card rv">
        <div class="how-num">02</div>
        <div class="how-ico-wrap">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="#C9963A" stroke-width="1.8"><path d="M20 21v-2a4 4 0 00-4-4H8a4 4 0 00-4 4v2"/><circle cx="12" cy="7" r="4"/></svg>
        </div>
        <h3>Fill Your Details</h3>
        <p>Enter your name, phone number and delivery address so we know where to send your order.</p>
      </div>
      <div class="how-card rv">
        <div class="how-num">03</div>
        <div class="how-ico-wrap">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="#C9963A" stroke-width="1.8"><rect x="5" y="2" width="14" height="20" rx="2"/><line x1="12" y1="18" x2="12.01" y2="18"/></svg>
        </div>
        <h3>Pay via M-Pesa</h3>
        <p>Send the exact total to 0701 227 713. Use your name as reference and share the code.</p>
      </div>
      <div class="how-card rv">
        <div class="how-num">04</div>
        <div class="how-ico-wrap">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="#C9963A" stroke-width="1.8"><rect x="1" y="3" width="15" height="13"/><polygon points="16 8 20 8 23 11 23 16 16 16 16 8"/><circle cx="5.5" cy="18.5" r="2.5"/><circle cx="18.5" cy="18.5" r="2.5"/></svg>
        </div>
        <h3>We Deliver!</h3>
        <p>We verify your payment and dispatch your order. Delivered countrywide across Kenya.</p>
      </div>
    </div>
  </div>
</section>

<!-- MPESA -->
<section class="sec mpesa-sec" id="mpesa">
  <div class="sec-inner">
    <div class="sec-hd rv">
      <div class="s-eye">Secure & Instant</div>
      <h2 class="s-title">Pay with <em>M-Pesa</em></h2>
      <p class="s-sub">Kenya's most trusted payment method. Confirmation within seconds.</p>
    </div>
    <div class="mpesa-layout">
      <div class="mpesa-card rvl">
        <div class="mpesa-top">
          <span class="mpesa-e">💚</span>
          <h2>M-Pesa Payment</h2>
          <p>Lipa Na M-Pesa · Sarah Fashions Nkubu</p>
        </div>
        <div class="mpesa-num-box">
          <div class="mns-l">Send Payment To</div>
          <div class="mns-n">0701 227 713</div>
          <div class="mns-w">Sarah Fashions – Nkubu, Meru County</div>
        </div>
        <ul class="mpesa-steps">
          <li class="mps"><div class="mps-n">1</div><div class="mps-t"><strong>Open M-Pesa on your phone</strong><span>Go to Safaricom M-Pesa menu</span></div></li>
          <li class="mps"><div class="mps-n">2</div><div class="mps-t"><strong>Select "Send Money"</strong><span>Choose the Send Money option</span></div></li>
          <li class="mps"><div class="mps-n">3</div><div class="mps-t"><strong>Enter: 0701 227 713</strong><span>Sarah Fashions payment number</span></div></li>
          <li class="mps"><div class="mps-n">4</div><div class="mps-t"><strong>Enter the exact cart total</strong><span>Shown automatically in your cart</span></div></li>
          <li class="mps"><div class="mps-n">5</div><div class="mps-t"><strong>Your full name as reference</strong><span>Type your name in the description field</span></div></li>
          <li class="mps"><div class="mps-n">6</div><div class="mps-t"><strong>Share your confirmation code</strong><span>Paste the M-Pesa SMS code in your order</span></div></li>
        </ul>
      </div>
      <div class="tip-cards rvr">
        <div class="tip">
          <span class="tip-icon">
            <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="#C9963A" stroke-width="1.8"><circle cx="12" cy="12" r="10"/><polyline points="12 6 12 12 16 14"/></svg>
          </span>
          <h4>Instant Confirmation</h4>
          <p>We verify your payment within minutes and start processing your order immediately — no delays.</p>
        </div>
        <div class="tip">
          <span class="tip-icon">
            <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="#C9963A" stroke-width="1.8"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/></svg>
          </span>
          <h4>100% Secure</h4>
          <p>M-Pesa is Kenya's most trusted payment platform. Every transaction is safe and protected.</p>
        </div>
        <div class="tip">
          <span class="tip-icon">
            <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="#C9963A" stroke-width="1.8"><path d="M22 16.92v3a2 2 0 01-2.18 2 19.79 19.79 0 01-8.63-3.07A19.5 19.5 0 013.07 9.81a19.79 19.79 0 01-3.07-8.68A2 2 0 012.18 1h3a2 2 0 012 1.72c.127.96.361 1.903.7 2.81a2 2 0 01-.45 2.11L6.91 8.15a16 16 0 006.29 6.29l1.42-1.42a2 2 0 012.11-.45c.907.339 1.85.573 2.81.7A2 2 0 0122 16.92z"/></svg>
          </span>
          <h4>Need Help?</h4>
          <p>Having trouble? Call or WhatsApp <strong style="color:var(--gold3)">0701 227 713</strong> and we'll guide you through.</p>
          <a class="wa-btn" href="https://wa.me/254701227713" target="_blank">💬 WhatsApp Us</a>
        </div>
        <div class="tip">
          <span class="tip-icon">
            <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="#C9963A" stroke-width="1.8"><rect x="1" y="3" width="15" height="13"/><polygon points="16 8 20 8 23 11 23 16 16 16 16 8"/><circle cx="5.5" cy="18.5" r="2.5"/><circle cx="18.5" cy="18.5" r="2.5"/></svg>
          </span>
          <h4>Countrywide Delivery</h4>
          <p>We deliver to your doorstep anywhere in Kenya. Contact us after ordering to arrange.</p>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- LOCATION -->
<section class="sec loc-sec" id="location">
  <div class="sec-inner">
    <div class="sec-hd rv">
      <div class="s-eye">Visit Us</div>
      <h2 class="s-title">Find Our <em>Store</em></h2>
      <p class="s-sub">Experience our full collection in person at our Nkubu showroom</p>
    </div>
    <div class="loc-layout">
      <div class="info-stack rvl">
        <div class="info-blk">
          <div class="ib-ico">
            <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="#C9963A" stroke-width="1.8"><path d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0118 0z"/><circle cx="12" cy="10" r="3"/></svg>
          </div>
          <div>
            <div class="ib-l">Location</div>
            <div class="ib-v">Sarah Fashions<br>Nkubu Town Centre, Main Road<br>Meru County, Kenya</div>
          </div>
        </div>
        <div class="info-blk">
          <div class="ib-ico">
            <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="#C9963A" stroke-width="1.8"><path d="M22 16.92v3a2 2 0 01-2.18 2 19.79 19.79 0 01-8.63-3.07A19.5 19.5 0 013.07 9.81a19.79 19.79 0 01-3.07-8.68A2 2 0 012.18 1h3a2 2 0 012 1.72c.127.96.361 1.903.7 2.81a2 2 0 01-.45 2.11L6.91 8.15a16 16 0 006.29 6.29l1.42-1.42a2 2 0 012.11-.45c.907.339 1.85.573 2.81.7A2 2 0 0122 16.92z"/></svg>
          </div>
          <div>
            <div class="ib-l">Phone & WhatsApp</div>
            <div class="ib-v">
              <a href="tel:0701227713">0701 227 713</a><br>
              <a class="wa-btn" href="https://wa.me/254701227713" target="_blank" style="margin-top:9px;display:inline-flex;">💬 WhatsApp Us</a>
            </div>
          </div>
        </div>
        <div class="info-blk">
          <div class="ib-ico">
            <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="#C9963A" stroke-width="1.8"><rect x="1" y="3" width="15" height="13"/><polygon points="16 8 20 8 23 11 23 16 16 16 16 8"/><circle cx="5.5" cy="18.5" r="2.5"/><circle cx="18.5" cy="18.5" r="2.5"/></svg>
          </div>
          <div>
            <div class="ib-l">Delivery</div>
            <div class="ib-v">We deliver <strong style="color:var(--gold3)">countrywide across Kenya.</strong><br>Call us after ordering to arrange.</div>
          </div>
        </div>
      </div>
      <div class="rvr">
        <div class="map-blk">
          <div class="map-vis">
            <svg width="52" height="52" viewBox="0 0 24 24" fill="none" stroke="#C9963A" stroke-width="1.2"><path d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0118 0z"/><circle cx="12" cy="10" r="3"/></svg>
            <h3>Nkubu, Meru County</h3>
            <p>Nkubu Town Centre, Main Road</p>
            <a class="map-cta" href="https://maps.google.com/?q=Nkubu,Meru,Kenya" target="_blank">
              Open Google Maps
              <svg width="11" height="11" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><line x1="7" y1="17" x2="17" y2="7"/><polyline points="7 7 17 7 17 17"/></svg>
            </a>
          </div>
          <div class="hours-list">
            <div class="h-row"><span class="h-day">Monday – Friday</span><span class="h-time">8:00 AM – 7:00 PM <span class="h-open">OPEN</span></span></div>
            <div class="h-row"><span class="h-day">Saturday</span><span class="h-time">8:00 AM – 7:00 PM</span></div>
            <div class="h-row"><span class="h-day">Sunday</span><span class="h-time">8:00 AM – 7:00 PM</span></div>
            <div class="h-row"><span class="h-day">Public Holidays</span><span class="h-time">8:00 AM – 7:00 PM</span></div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <div class="foot-inner">
    <div class="foot-grid">
      <div>
        <div class="f-logo-row">
          <svg width="36" height="36" viewBox="0 0 42 42" fill="none"><circle cx="21" cy="21" r="20" stroke="#C9963A" stroke-width="1" opacity=".3"/><text x="21" y="26" font-family="Cormorant Garamond,serif" font-size="16" font-weight="600" fill="#C9963A" text-anchor="middle">S</text></svg>
          <span class="f-logo-name">Sarah Fashions</span>
        </div>
        <div class="f-sub">Nkubu · Meru County · Kenya</div>
        <p class="f-desc">Your premier fashion destination in Nkubu. Premium quality clothing for Women, Men and Children — delivered countrywide with care and excellence.</p>
      </div>
      <div class="f-col">
        <h4>Quick Links</h4>
        <a href="#shop">Shop Collection</a>
        <a href="#how">How to Order</a>
        <a href="#mpesa">M-Pesa Payment</a>
        <a href="#location">Find Our Store</a>
      </div>
      <div class="f-col">
        <h4>Contact</h4>
        <a href="tel:0701227713">📞 0701 227 713</a>
        <a href="https://wa.me/254701227713">💬 WhatsApp</a>
        <a href="#location">📍 Nkubu Town, Meru</a>
        <a href="#mpesa">💳 Pay via M-Pesa</a>
      </div>
    </div>
    <div class="foot-div"></div>
    <div class="foot-btm">
      <span class="foot-copy">© 2024 Sarah Fashions · Nkubu, Meru County, Kenya · All Rights Reserved</span>
      <span class="foot-love">Crafted with ❤️ in Meru, Kenya</span>
    </div>
  </div>
</footer>

<!-- OVERLAY -->
<div class="overlay" id="overlay" onclick="closeAll()"></div>

<!-- CART PANEL -->
<div class="cart-panel" id="cartPanel">
  <div class="cp-hd">
    <span class="cp-title">
      <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="#C9963A" stroke-width="2" style="vertical-align:middle;margin-right:6px"><path d="M6 2L3 6v14a2 2 0 002 2h14a2 2 0 002-2V6l-3-4z"/><line x1="3" y1="6" x2="21" y2="6"/><path d="M16 10a4 4 0 01-8 0"/></svg>
      Your Cart
    </span>
    <button class="cp-x" onclick="closeCart()">✕</button>
  </div>
  <div id="cartBody" style="display:flex;flex-direction:column;flex:1;overflow:hidden;"></div>
</div>

<!-- ADMIN MODAL -->
<div class="modal-bg hidden" id="adminModal">
  <div class="adm">
    <div class="adm-hd">
      <span class="adm-title">
        <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="#C9963A" stroke-width="1.8" style="vertical-align:middle;margin-right:7px"><circle cx="12" cy="12" r="3"/><path d="M19.07 4.93l-1.41 1.41M4.93 4.93l1.41 1.41M19.07 19.07l-1.41-1.41M4.93 19.07l1.41-1.41M12 2v2M12 20v2M2 12h2M20 12h2"/></svg>
        Seller Dashboard
      </span>
      <button class="cp-x" onclick="closeAdmin()">✕</button>
    </div>
    <div class="adm-body">
      <!-- Login -->
      <div id="adminLogin">
        <div class="login-wrap">
          <div class="login-ico">
            <svg width="48" height="48" viewBox="0 0 24 24" fill="none" stroke="#C9963A" stroke-width="1.5"><rect x="3" y="11" width="18" height="11" rx="2"/><path d="M7 11V7a5 5 0 0110 0v4"/></svg>
          </div>
          <h3>Seller Access</h3>
          <p>Enter your password to manage products, categories and orders.</p>
          <label class="f-lbl">Password</label>
          <input class="f-inp" type="password" id="adminPw" placeholder="Enter password…" onkeydown="if(event.key==='Enter')doLogin()"/>
          <button class="btn btn-g" style="width:100%;justify-content:center;" onclick="doLogin()">Login →</button>
        </div>
      </div>
      <!-- Dashboard -->
      <div id="adminDash" class="hidden">
        <div class="adm-tabs">
          <div class="adm-tab on" onclick="aTab('products')">📦 Products</div>
          <div class="adm-tab" onclick="aTab('categories')">🏷 Categories</div>
          <div class="adm-tab" onclick="aTab('orders')">📋 Orders</div>
        </div>
        <!-- PRODUCTS -->
        <div id="aProducts">
          <h3 style="font-family:'Cormorant Garamond',serif;font-size:20px;color:var(--pearl);margin-bottom:18px;font-weight:600;">Add New Product</h3>
          <div class="fg2">
            <div><label class="f-lbl">Product Name</label><input class="f-inp" id="pName" placeholder="e.g. Floral Maxi Dress"/></div>
            <div><label class="f-lbl">Category</label><select class="f-sel" id="pCat"><option value="">Select category…</option></select></div>
            <div><label class="f-lbl">Price (Ksh)</label><input class="f-inp" type="number" id="pPrice" placeholder="e.g. 2500"/></div>
            <div><label class="f-lbl">Emoji Icon</label><input class="f-inp" id="pIcon" placeholder="e.g. 👗"/></div>
          </div>
          <label class="f-lbl">Product Image</label>
          <div class="upload-area" id="uploadArea">
            <input type="file" id="pImage" accept="image/*" onchange="previewImg(this)"/>
            <span class="ua-ico">📸</span>
            <span class="ua-txt">Click or drag to upload product image</span>
            <span class="ua-sub">JPG, PNG, WEBP · Max 5MB</span>
            <img class="img-prev" id="imgPrev" src="" alt=""/>
          </div>
          <label class="f-lbl">Description</label>
          <textarea class="f-inp f-ta" id="pDesc" rows="2" placeholder="Short product description…"></textarea>
          <button class="btn btn-g" onclick="addProd()" style="margin-bottom:32px;">+ Add Product</button>
          <h3 style="font-family:'Cormorant Garamond',serif;font-size:18px;color:var(--pearl);margin-bottom:12px;font-weight:600;">
            All Products <span style="font-weight:300;font-size:13px;color:var(--ash);" id="pCount"></span>
          </h3>
          <div id="aProdList" style="max-height:340px;overflow-y:auto;"></div>
        </div>
        <!-- CATEGORIES -->
        <div id="aCategories" class="hidden">
          <h3 style="font-family:'Cormorant Garamond',serif;font-size:20px;color:var(--pearl);margin-bottom:18px;font-weight:600;">Add New Category</h3>
          <div class="fg2">
            <div><label class="f-lbl">Category Name</label><input class="f-inp" id="cName" placeholder="e.g. Accessories"/></div>
            <div><label class="f-lbl">Emoji Icon</label><input class="f-inp" id="cIcon" placeholder="e.g. 💍"/></div>
          </div>
          <button class="btn btn-g" onclick="addCat()" style="margin-bottom:32px;">+ Add Category</button>
          <h3 style="font-family:'Cormorant Garamond',serif;font-size:18px;color:var(--pearl);margin-bottom:12px;font-weight:600;">All Categories</h3>
          <div id="aCatList"></div>
        </div>
        <!-- ORDERS -->
        <div id="aOrders" class="hidden">
          <h3 style="font-family:'Cormorant Garamond',serif;font-size:20px;color:var(--pearl);margin-bottom:14px;font-weight:600;">Customer Orders</h3>
          <div style="overflow-x:auto;"><div id="aOrderList"></div></div>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- TOAST -->
<div class="toast" id="toast"></div>

<script>
// ═══ CATEGORY SVG ICONS — Rich illustrated icons per category ═══
function getCatSVG(name){
  const n=(name||'').toLowerCase();

  // WOMEN / LADIES / DRESS — elegant dress silhouette
  if(n.includes('women')||n.includes('lady')||n.includes('ladies')||n.includes('female')||n.includes('dress')||n.includes('skirt')||n.includes('blouse'))
    return `<svg width="36" height="36" viewBox="0 0 36 36" fill="none" xmlns="http://www.w3.org/2000/svg">
      <ellipse cx="18" cy="7" rx="5" ry="5.5" stroke="#C9963A" stroke-width="1.4" fill="rgba(201,150,58,.08)"/>
      <path d="M13 12.5 L5 31 Q18 35 31 31 L23 12.5 Q20.5 17 18 17 Q15.5 17 13 12.5Z" stroke="#C9963A" stroke-width="1.4" fill="rgba(201,150,58,.07)"/>
      <path d="M13 12.5 Q15.5 16 18 16 Q20.5 16 23 12.5" fill="none" stroke="#C9963A" stroke-width="1.2"/>
      <line x1="11" y1="20" x2="25" y2="20" stroke="#C9963A" stroke-width=".9" opacity=".45"/>
      <line x1="8.5" y1="25.5" x2="27.5" y2="25.5" stroke="#C9963A" stroke-width=".9" opacity=".45"/>
      <circle cx="18" cy="14" r="1" fill="#C9963A" opacity=".5"/>
    </svg>`;

  // MEN / SUIT / SHIRT — shirt & tie illustration
  if(n.includes('men')||n.includes('man')||n.includes('male')||n.includes('suit')||n.includes('shirt')||n.includes('trouser')||n.includes('jacket'))
    return `<svg width="36" height="36" viewBox="0 0 36 36" fill="none" xmlns="http://www.w3.org/2000/svg">
      <ellipse cx="18" cy="6" rx="5" ry="5" stroke="#C9963A" stroke-width="1.3" fill="rgba(201,150,58,.08)"/>
      <path d="M13 11 L5 17 L8 20 L11 17 L11 34 L25 34 L25 17 L28 20 L31 17 L23 11 L21 14 Q18 17 15 14 Z" stroke="#C9963A" stroke-width="1.3" fill="rgba(201,150,58,.07)"/>
      <line x1="18" y1="17" x2="18" y2="21" stroke="#C9963A" stroke-width="1.1" opacity=".6"/>
      <path d="M16 21 L18 28 L20 21" stroke="#C9963A" stroke-width="1" fill="none" opacity=".6"/>
      <circle cx="18" cy="23" r=".9" fill="#C9963A" opacity=".5"/>
      <circle cx="18" cy="26" r=".9" fill="#C9963A" opacity=".5"/>
    </svg>`;

  // CHILDREN / KIDS / BABY — cute romper/onesie
  if(n.includes('child')||n.includes('kid')||n.includes('baby')||n.includes('boy')||n.includes('girl')||n.includes('infant')||n.includes('toddler'))
    return `<svg width="36" height="36" viewBox="0 0 36 36" fill="none" xmlns="http://www.w3.org/2000/svg">
      <circle cx="18" cy="6.5" r="5" stroke="#C9963A" stroke-width="1.3" fill="rgba(201,150,58,.08)"/>
      <path d="M13 11.5 L7 33 L14 33 L14 24 Q18 27 22 24 L22 33 L29 33 L23 11.5 Q20.5 15.5 18 15.5 Q15.5 15.5 13 11.5Z" stroke="#C9963A" stroke-width="1.3" fill="rgba(201,150,58,.07)"/>
      <circle cx="13.5" cy="21" r="1.5" fill="#C9963A" opacity=".35"/>
      <circle cx="22.5" cy="21" r="1.5" fill="#C9963A" opacity=".35"/>
      <path d="M15 18 Q18 20 21 18" stroke="#C9963A" stroke-width="1" fill="none" opacity=".5"/>
    </svg>`;

  // SHOES / FOOTWEAR / BOOTS / SANDALS
  if(n.includes('shoe')||n.includes('footwear')||n.includes('boot')||n.includes('sandal')||n.includes('heel')||n.includes('sneaker'))
    return `<svg width="36" height="36" viewBox="0 0 36 36" fill="none" xmlns="http://www.w3.org/2000/svg">
      <path d="M4 26 Q4 30 8 30 L30 30 Q34 30 34 26 L34 24 L20 24 L18 18 L14 18 Q10 18 8 21 Z" stroke="#C9963A" stroke-width="1.3" fill="rgba(201,150,58,.07)"/>
      <path d="M18 18 Q16 12 20 10 Q24 8 26 12 L28 18" stroke="#C9963A" stroke-width="1.3" fill="none"/>
      <line x1="12" y1="24" x2="28" y2="24" stroke="#C9963A" stroke-width="1" opacity=".45"/>
      <line x1="4" y1="28" x2="34" y2="28" stroke="#C9963A" stroke-width="1.2" opacity=".35"/>
    </svg>`;

  // BAGS / PURSE / HANDBAG / ACCESSORIES
  if(n.includes('bag')||n.includes('purse')||n.includes('handbag')||n.includes('accessory')||n.includes('accessories')||n.includes('belt'))
    return `<svg width="36" height="36" viewBox="0 0 36 36" fill="none" xmlns="http://www.w3.org/2000/svg">
      <path d="M6 14 L4 32 L32 32 L30 14 Z" stroke="#C9963A" stroke-width="1.3" fill="rgba(201,150,58,.07)"/>
      <line x1="4" y1="14" x2="32" y2="14" stroke="#C9963A" stroke-width="1.3"/>
      <path d="M12 14 Q12 6 18 6 Q24 6 24 14" stroke="#C9963A" stroke-width="1.3" fill="none"/>
      <rect x="15" y="19" width="6" height="5" rx="1" stroke="#C9963A" stroke-width="1.2" fill="rgba(201,150,58,.15)"/>
      <line x1="18" y1="19" x2="18" y2="24" stroke="#C9963A" stroke-width="1" opacity=".5"/>
    </svg>`;

  // HATS / CAPS
  if(n.includes('hat')||n.includes('cap')||n.includes('head')||n.includes('beanie'))
    return `<svg width="36" height="36" viewBox="0 0 36 36" fill="none" xmlns="http://www.w3.org/2000/svg">
      <path d="M18 4 Q8 4 6 14 L30 14 Q28 4 18 4Z" stroke="#C9963A" stroke-width="1.3" fill="rgba(201,150,58,.08)"/>
      <rect x="3" y="14" width="30" height="5" rx="2" stroke="#C9963A" stroke-width="1.3" fill="rgba(201,150,58,.07)"/>
      <line x1="10" y1="10" x2="26" y2="10" stroke="#C9963A" stroke-width=".9" opacity=".4"/>
      <circle cx="18" cy="6" r="2" stroke="#C9963A" stroke-width="1.1" fill="rgba(201,150,58,.2)"/>
    </svg>`;

  // SPORTSWEAR / ACTIVEWEAR / GYM
  if(n.includes('sport')||n.includes('active')||n.includes('gym')||n.includes('fitness')||n.includes('jersey'))
    return `<svg width="36" height="36" viewBox="0 0 36 36" fill="none" xmlns="http://www.w3.org/2000/svg">
      <path d="M14 4 L5 9 L9 14 L12 12 L12 32 L24 32 L24 12 L27 14 L31 9 L22 4 L20 7 Q18 9 16 7 Z" stroke="#C9963A" stroke-width="1.3" fill="rgba(201,150,58,.07)"/>
      <line x1="12" y1="16" x2="24" y2="16" stroke="#C9963A" stroke-width=".9" opacity=".4"/>
      <line x1="12" y1="20" x2="24" y2="20" stroke="#C9963A" stroke-width=".9" opacity=".4"/>
      <path d="M14 4 Q18 2 22 4" fill="none" stroke="#C9963A" stroke-width="1.1" opacity=".5"/>
    </svg>`;

  // JEWELLERY / RINGS / NECKLACE
  if(n.includes('jewel')||n.includes('ring')||n.includes('necklace')||n.includes('brace')||n.includes('earring'))
    return `<svg width="36" height="36" viewBox="0 0 36 36" fill="none" xmlns="http://www.w3.org/2000/svg">
      <circle cx="18" cy="20" r="10" stroke="#C9963A" stroke-width="1.3" fill="rgba(201,150,58,.05)"/>
      <circle cx="18" cy="20" r="5" stroke="#C9963A" stroke-width="1.1" fill="rgba(201,150,58,.1)"/>
      <circle cx="18" cy="20" r="2" fill="#C9963A" opacity=".4"/>
      <path d="M13 8 Q18 5 23 8" stroke="#C9963A" stroke-width="1.2" fill="none"/>
      <circle cx="13" cy="8" r="1.5" fill="#C9963A" opacity=".5"/>
      <circle cx="23" cy="8" r="1.5" fill="#C9963A" opacity=".5"/>
    </svg>`;

  // UNDERWEAR / LINGERIE / INNER
  if(n.includes('under')||n.includes('lingerie')||n.includes('inner')||n.includes('night'))
    return `<svg width="36" height="36" viewBox="0 0 36 36" fill="none" xmlns="http://www.w3.org/2000/svg">
      <path d="M7 8 Q10 4 18 4 Q26 4 29 8 L32 20 L24 22 Q18 16 12 22 L4 20 Z" stroke="#C9963A" stroke-width="1.3" fill="rgba(201,150,58,.07)"/>
      <path d="M12 22 Q18 28 24 22 L26 32 L10 32 Z" stroke="#C9963A" stroke-width="1.3" fill="rgba(201,150,58,.06)"/>
    </svg>`;

  // DEFAULT — generic fashion hanger icon
  return `<svg width="36" height="36" viewBox="0 0 36 36" fill="none" xmlns="http://www.w3.org/2000/svg">
    <circle cx="18" cy="7" r="3" stroke="#C9963A" stroke-width="1.3" fill="rgba(201,150,58,.1)"/>
    <path d="M18 10 L18 13 Q18 14 10 20 L4 26 L32 26 Q26 20 18 14 Q18 13 18 10" stroke="#C9963A" stroke-width="1.3" fill="rgba(201,150,58,.06)"/>
    <line x1="4" y1="29" x2="32" y2="29" stroke="#C9963A" stroke-width="1.5" opacity=".4"/>
  </svg>`;
}

// Product placeholder SVGs — rich illustrated backgrounds by category
function getProdSVG(cat,icon){
  if(icon && icon.length<=4) return `<span class="prod-no-img">${icon}</span>`;
  const n=(cat||'').toLowerCase();

  // WOMEN — elegant dress illustration
  if(n.includes('women')||n.includes('lady')||n.includes('dress')||n.includes('skirt')||n.includes('blouse'))
    return `<svg width="100%" height="100%" viewBox="0 0 200 260" fill="none" xmlns="http://www.w3.org/2000/svg" style="opacity:.18;position:absolute;inset:0;">
      <defs><radialGradient id="bg1" cx="50%" cy="40%"><stop offset="0%" stop-color="#C9963A" stop-opacity=".15"/><stop offset="100%" stop-color="#C9963A" stop-opacity="0"/></radialGradient></defs>
      <rect width="200" height="260" fill="url(#bg1)"/>
      <ellipse cx="100" cy="52" rx="28" ry="30" stroke="#C9963A" stroke-width="1.5" fill="rgba(201,150,58,.08)"/>
      <path d="M72 80 L42 220 Q100 240 158 220 L128 80 Q114 108 100 108 Q86 108 72 80Z" stroke="#C9963A" stroke-width="1.5" fill="rgba(201,150,58,.06)"/>
      <path d="M72 80 Q86 105 100 105 Q114 105 128 80" fill="none" stroke="#C9963A" stroke-width="1.4"/>
      <line x1="62" y1="120" x2="138" y2="120" stroke="#C9963A" stroke-width="1" opacity=".4"/>
      <line x1="52" y1="148" x2="148" y2="148" stroke="#C9963A" stroke-width="1" opacity=".35"/>
      <line x1="42" y1="176" x2="158" y2="176" stroke="#C9963A" stroke-width="1" opacity=".3"/>
      <line x1="44" y1="200" x2="156" y2="200" stroke="#C9963A" stroke-width="1" opacity=".25"/>
      <circle cx="100" cy="90" r="3" fill="#C9963A" opacity=".4"/>
      <circle cx="100" cy="100" r="3" fill="#C9963A" opacity=".3"/>
    </svg>`;

  // MEN — shirt & collar illustration
  if(n.includes('men')||n.includes('suit')||n.includes('shirt')||n.includes('trouser')||n.includes('jacket'))
    return `<svg width="100%" height="100%" viewBox="0 0 200 260" fill="none" xmlns="http://www.w3.org/2000/svg" style="opacity:.18;position:absolute;inset:0;">
      <defs><radialGradient id="bg2" cx="50%" cy="40%"><stop offset="0%" stop-color="#2A5C8A" stop-opacity=".18"/><stop offset="100%" stop-color="#2A5C8A" stop-opacity="0"/></radialGradient></defs>
      <rect width="200" height="260" fill="url(#bg2)"/>
      <ellipse cx="100" cy="42" rx="24" ry="26" stroke="#5B9BD5" stroke-width="1.4" fill="rgba(42,92,138,.1)"/>
      <path d="M76 66 L36 92 L52 108 L64 96 L64 236 L136 236 L136 96 L148 108 L164 92 L124 66 L118 80 Q108 90 100 90 Q92 90 82 80 Z" stroke="#5B9BD5" stroke-width="1.4" fill="rgba(42,92,138,.07)"/>
      <line x1="100" y1="90" x2="100" y2="128" stroke="#5B9BD5" stroke-width="1.2" opacity=".5"/>
      <path d="M92 128 L100 180 L108 128" stroke="#5B9BD5" stroke-width="1.1" fill="none" opacity=".5"/>
      <circle cx="100" cy="135" r="3" fill="#5B9BD5" opacity=".4"/>
      <circle cx="100" cy="150" r="3" fill="#5B9BD5" opacity=".35"/>
      <circle cx="100" cy="165" r="3" fill="#5B9BD5" opacity=".3"/>
      <line x1="64" y1="115" x2="136" y2="115" stroke="#5B9BD5" stroke-width=".8" opacity=".3"/>
    </svg>`;

  // CHILDREN — playful onesie illustration
  if(n.includes('child')||n.includes('kid')||n.includes('baby')||n.includes('toddler'))
    return `<svg width="100%" height="100%" viewBox="0 0 200 260" fill="none" xmlns="http://www.w3.org/2000/svg" style="opacity:.18;position:absolute;inset:0;">
      <defs><radialGradient id="bg3" cx="50%" cy="40%"><stop offset="0%" stop-color="#2D7A55" stop-opacity=".18"/><stop offset="100%" stop-color="#2D7A55" stop-opacity="0"/></radialGradient></defs>
      <rect width="200" height="260" fill="url(#bg3)"/>
      <circle cx="100" cy="48" r="28" stroke="#5BC78A" stroke-width="1.4" fill="rgba(45,122,85,.08)"/>
      <path d="M72 72 L44 230 L86 230 L86 162 Q100 178 114 162 L114 230 L156 230 L128 72 Q114 98 100 98 Q86 98 72 72Z" stroke="#5BC78A" stroke-width="1.4" fill="rgba(45,122,85,.07)"/>
      <circle cx="78" cy="140" r="6" fill="#5BC78A" opacity=".25"/>
      <circle cx="122" cy="140" r="6" fill="#5BC78A" opacity=".25"/>
      <path d="M84 118 Q100 126 116 118" stroke="#5BC78A" stroke-width="1.2" fill="none" opacity=".5"/>
      <circle cx="100" cy="82" r="4" fill="#5BC78A" opacity=".3"/>
      <circle cx="100" cy="96" r="4" fill="#5BC78A" opacity=".25"/>
    </svg>`;

  // SHOES
  if(n.includes('shoe')||n.includes('footwear')||n.includes('boot')||n.includes('sandal')||n.includes('heel'))
    return `<svg width="100%" height="100%" viewBox="0 0 200 260" fill="none" xmlns="http://www.w3.org/2000/svg" style="opacity:.18;position:absolute;inset:0;">
      <defs><radialGradient id="bg4" cx="50%" cy="60%"><stop offset="0%" stop-color="#7A4A2A" stop-opacity=".18"/><stop offset="100%" stop-color="#7A4A2A" stop-opacity="0"/></radialGradient></defs>
      <rect width="200" height="260" fill="url(#bg4)"/>
      <path d="M24 180 Q22 210 44 214 L172 214 Q196 210 196 194 L196 184 L112 184 L100 144 L72 144 Q44 144 36 162 Z" stroke="#C4845A" stroke-width="1.8" fill="rgba(122,74,42,.08)"/>
      <path d="M100 144 Q88 100 110 82 Q132 62 148 90 L160 130 L144 144" stroke="#C4845A" stroke-width="1.6" fill="none"/>
      <path d="M120 98 Q126 88 138 96" stroke="#C4845A" stroke-width="1.2" fill="none" opacity=".5"/>
      <line x1="60" y1="184" x2="160" y2="184" stroke="#C4845A" stroke-width="1.2" opacity=".4"/>
      <line x1="24" y1="205" x2="176" y2="205" stroke="#C4845A" stroke-width="1.4" opacity=".3"/>
    </svg>`;

  // BAGS / ACCESSORIES
  if(n.includes('bag')||n.includes('purse')||n.includes('accessory')||n.includes('accessories'))
    return `<svg width="100%" height="100%" viewBox="0 0 200 260" fill="none" xmlns="http://www.w3.org/2000/svg" style="opacity:.18;position:absolute;inset:0;">
      <defs><radialGradient id="bg5" cx="50%" cy="50%"><stop offset="0%" stop-color="#6A3A8A" stop-opacity=".18"/><stop offset="100%" stop-color="#6A3A8A" stop-opacity="0"/></radialGradient></defs>
      <rect width="200" height="260" fill="url(#bg5)"/>
      <path d="M28 90 L18 216 L182 216 L172 90 Z" stroke="#A870C8" stroke-width="1.6" fill="rgba(106,58,138,.07)"/>
      <line x1="18" y1="90" x2="182" y2="90" stroke="#A870C8" stroke-width="1.6"/>
      <path d="M60 90 Q60 34 100 34 Q140 34 140 90" stroke="#A870C8" stroke-width="1.6" fill="none"/>
      <rect x="82" y="130" width="36" height="28" rx="4" stroke="#A870C8" stroke-width="1.4" fill="rgba(168,112,200,.12)"/>
      <circle cx="100" cy="146" r="5" stroke="#A870C8" stroke-width="1.2" fill="rgba(168,112,200,.2)"/>
      <line x1="100" y1="130" x2="100" y2="158" stroke="#A870C8" stroke-width="1" opacity=".5"/>
    </svg>`;

  // DEFAULT — elegant hanger + garment
  return `<svg width="100%" height="100%" viewBox="0 0 200 260" fill="none" xmlns="http://www.w3.org/2000/svg" style="opacity:.16;position:absolute;inset:0;">
    <defs><radialGradient id="bgd" cx="50%" cy="40%"><stop offset="0%" stop-color="#C9963A" stop-opacity=".12"/><stop offset="100%" stop-color="#C9963A" stop-opacity="0"/></radialGradient></defs>
    <rect width="200" height="260" fill="url(#bgd)"/>
    <circle cx="100" cy="40" r="12" stroke="#C9963A" stroke-width="1.4" fill="rgba(201,150,58,.08)"/>
    <path d="M100 52 L100 70 Q100 76 62 100 L32 140 L168 140 Q138 100 100 76 Q100 70 100 52" stroke="#C9963A" stroke-width="1.4" fill="rgba(201,150,58,.05)"/>
    <rect x="42" y="140" width="116" height="96" rx="4" stroke="#C9963A" stroke-width="1.4" fill="rgba(201,150,58,.04)"/>
    <line x1="58" y1="170" x2="142" y2="170" stroke="#C9963A" stroke-width="1" opacity=".4"/>
    <line x1="58" y1="192" x2="142" y2="192" stroke="#C9963A" stroke-width="1" opacity=".35"/>
    <line x1="32" y1="148" x2="168" y2="148" stroke="#C9963A" stroke-width="1.5" opacity=".35"/>
  </svg>`;
}

// Category accent colour — top stripe on product card
function getCatColor(cat){
  const n=(cat||'').toLowerCase();
  if(n.includes('women')||n.includes('lady')||n.includes('dress')||n.includes('skirt')||n.includes('blouse')) return 'linear-gradient(90deg,#C4705A,#E8A090,#C4705A)';
  if(n.includes('men')||n.includes('suit')||n.includes('shirt')||n.includes('trouser')||n.includes('jacket')) return 'linear-gradient(90deg,#2A5C8A,#5B9BD5,#2A5C8A)';
  if(n.includes('child')||n.includes('kid')||n.includes('baby')||n.includes('toddler')) return 'linear-gradient(90deg,#2D7A55,#5BC78A,#2D7A55)';
  if(n.includes('shoe')||n.includes('footwear')||n.includes('boot')||n.includes('sandal')||n.includes('heel')) return 'linear-gradient(90deg,#7A4A2A,#C4845A,#7A4A2A)';
  if(n.includes('bag')||n.includes('purse')||n.includes('accessory')||n.includes('accessories')) return 'linear-gradient(90deg,#6A3A8A,#A870C8,#6A3A8A)';
  if(n.includes('hat')||n.includes('cap')||n.includes('head')) return 'linear-gradient(90deg,#5A6A2A,#9AB840,#5A6A2A)';
  if(n.includes('sport')||n.includes('active')||n.includes('gym')||n.includes('fitness')) return 'linear-gradient(90deg,#1A5A7A,#30A8D0,#1A5A7A)';
  if(n.includes('jewel')||n.includes('ring')||n.includes('necklace')) return 'linear-gradient(90deg,#8A6A10,#D4AA30,#8A6A10)';
  if(n.includes('under')||n.includes('lingerie')||n.includes('night')) return 'linear-gradient(90deg,#7A2A5A,#C850A0,#7A2A5A)';
  return 'linear-gradient(90deg,var(--gold),var(--gold2),var(--gold))';
}

// ═══ STATE ═══
const DEFAULTS=[{name:'Women',icon:'👩'},{name:'Men',icon:'👔'},{name:'Children',icon:'🧒'}];
let S={categories:[],products:[],cart:[],orders:[],checkout:false};
let catFilter='all',adminIn=false,pid=Date.now(),imgData=null;

function load(){
  try{
    const d=JSON.parse(localStorage.getItem('sf_v4')||'{}');
    S.categories=d.categories||[];S.products=d.products||[];S.orders=d.orders||[];
    if(!S.categories.length) S.categories=[...DEFAULTS];
  }catch(e){S.categories=[...DEFAULTS];}
}
function save(){try{localStorage.setItem('sf_v4',JSON.stringify({categories:S.categories,products:S.products,orders:S.orders}));}catch(e){}}

load();
function init(){renderCats();renderProds();updateBadge();updateStats();}

// ═══ CATEGORIES ═══
function renderCats(){
  const g=document.getElementById('catsGrid');
  let h=`<div class="cat-card ${catFilter==='all'?'on':''}" onclick="setCat('all')">
    <div class="cat-graphic"><svg width="30" height="30" viewBox="0 0 24 24" fill="none" stroke="#C9963A" stroke-width="1.6"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></svg></div>
    <span class="cat-name">All Items</span>
    <span class="cat-count">${S.products.length} item${S.products.length!==1?'s':''}</span>
  </div>`;
  S.categories.forEach(c=>{
    const n=S.products.filter(p=>p.category===c.name).length;
    h+=`<div class="cat-card ${catFilter===c.name?'on':''}" onclick="setCat('${esc(c.name)}')">
      <div class="cat-graphic">${getCatSVG(c.name)}</div>
      <span class="cat-name">${c.name}</span>
      <span class="cat-count">${n} item${n!==1?'s':''}</span>
    </div>`;
  });
  g.innerHTML=h;
}
function setCat(name){
  catFilter=name;renderCats();renderProds();
  document.getElementById('shopSub').textContent=name==='all'?'Browse all premium fashion items available':'Showing: '+name;
  document.querySelector('.shop-sec').scrollIntoView({behavior:'smooth'});
}

// ═══ PRODUCTS ═══
function renderProds(){
  const g=document.getElementById('prodGrid');
  const list=catFilter==='all'?S.products:S.products.filter(p=>p.category===catFilter);
  if(!list.length){
    g.innerHTML=S.products.length
      ?`<div class="empty-st"><svg width="80" height="80" viewBox="0 0 24 24" fill="none" stroke="#C9963A" stroke-width="1"><circle cx="11" cy="11" r="8"/><line x1="21" y1="21" x2="16.65" y2="16.65"/></svg><h3>No items here yet</h3><p>The seller hasn't added items to this category yet.</p></div>`
      :`<div class="empty-st"><svg width="80" height="80" viewBox="0 0 24 24" fill="none" stroke="#C9963A" stroke-width="1"><path d="M6 2L3 6v14a2 2 0 002 2h14a2 2 0 002-2V6l-3-4z"/><line x1="3" y1="6" x2="21" y2="6"/><path d="M16 10a4 4 0 01-8 0"/></svg><h3>Collection Coming Soon</h3><p>Products will appear once the seller adds them.<br>Call 0701 227 713 to enquire.</p></div>`;
    return;
  }
  g.innerHTML=list.map(p=>{
    const oos=p.outOfStock;
    const accent=getCatColor(p.category);
    const visual=p.image
      ?`<img src="${p.image}" alt="${p.name}" loading="lazy"/>`
      :getProdSVG(p.category,p.icon);
    return `<div class="prod-card rv">
      <div class="prod-img-box">
        <div class="prod-cat-accent" style="background:${accent}"></div>
        ${p.badge&&!oos?`<span class="prod-badge ${p.badge==='NEW'?'badge-new':'badge-hot'}">${p.badge}</span>`:''}
        ${oos?`<span class="prod-badge badge-out">Out of Stock</span>`:''}
        <button class="prod-wish">🤍</button>
        ${visual}
        ${oos?`<div class="oos-veil"><span class="oos-txt">Out of Stock</span></div>`:''}
      </div>
      <div class="prod-info">
        <div class="prod-cat-lbl">${p.category||'General'}</div>
        <div class="prod-name">${p.name}</div>
        <div class="prod-desc">${p.description||'Premium quality fashion item.'}</div>
        <div class="prod-footer">
          <div class="prod-price">Ksh ${Number(p.price).toLocaleString()}<small>/item</small></div>
          <button class="add-btn" onclick="addToCart(${p.id})" ${oos?'disabled':''}>
            ${oos?'Out of Stock':'Add to Cart'}
          </button>
        </div>
      </div>
    </div>`;
  }).join('');
  setTimeout(()=>document.querySelectorAll('.prod-card.rv').forEach(e=>e.classList.add('vis')),60);
}

// ═══ CART ═══
function addToCart(id){
  const p=S.products.find(x=>x.id===id);if(!p||p.outOfStock)return;
  const ex=S.cart.find(x=>x.id===id);
  ex?ex.qty++:S.cart.push({...p,qty:1});
  updateBadge();showToast('✓ '+p.name+' added to cart');
}
function updateBadge(){document.getElementById('cartCount').textContent=S.cart.reduce((s,i)=>s+i.qty,0);}
function openCart(){S.checkout=false;renderCart();document.getElementById('cartPanel').classList.add('open');document.getElementById('overlay').classList.add('on');}
function closeCart(){document.getElementById('cartPanel').classList.remove('open');document.getElementById('overlay').classList.remove('on');}
function closeAll(){closeCart();}

function calcTotals(){
  const items=S.cart.reduce((s,i)=>s+i.qty,0);
  const sub=S.cart.reduce((s,i)=>s+i.price*i.qty,0);
  return{items,sub,total:sub};
}

function renderCart(){
  const el=document.getElementById('cartBody');
  if(!S.cart.length){
    el.innerHTML=`<div class="cp-body" style="flex:1;"><div class="cp-empty"><div class="cp-empty-i"><svg width="60" height="60" viewBox="0 0 24 24" fill="none" stroke="#C9963A" stroke-width="1"><path d="M6 2L3 6v14a2 2 0 002 2h14a2 2 0 002-2V6l-3-4z"/><line x1="3" y1="6" x2="21" y2="6"/><path d="M16 10a4 4 0 01-8 0"/></svg></div><p>Your cart is empty.<br>Discover our collection!</p></div></div>
    <div class="cp-acts"><button class="cp-btn cpb-g" onclick="closeCart();scrollTo('shop')">Browse Collection →</button></div>`;
    return;
  }
  const{items,sub,total}=calcTotals();
  if(!S.checkout){
    el.innerHTML=`
      <div class="cp-body" style="flex:1;overflow-y:auto;padding:16px 24px;">
        ${S.cart.map(i=>`<div class="ci">
          <div class="ci-thumb">${i.image?`<img src="${i.image}" alt="${i.name}"/>`:(i.icon||'👗')}</div>
          <div class="ci-inf">
            <div class="ci-cat">${i.category||''}</div>
            <div class="ci-name">${i.name}</div>
            <div class="ci-unit">Ksh ${Number(i.price).toLocaleString()} each</div>
            <div class="ci-row">
              <div class="qty-row">
                <button class="qb" onclick="chQty(${i.id},-1)">−</button>
                <span class="qv">${i.qty}</span>
                <button class="qb" onclick="chQty(${i.id},1)">+</button>
              </div>
              <span class="ci-line">Ksh ${Number(i.price*i.qty).toLocaleString()}</span>
            </div>
            <button class="ci-del" onclick="remItem(${i.id})">✕ Remove</button>
          </div>
        </div>`).join('')}
      </div>
      <div class="cp-totals">
        <div class="tot-r"><span>Items (${items})</span><span>Ksh ${Number(sub).toLocaleString()}</span></div>
        <div class="tot-grand"><span>Total</span><span>Ksh ${Number(total).toLocaleString()}</span></div>
      </div>
      <div class="cp-acts">
        <button class="cp-btn cpb-g" onclick="goCheckout()">Proceed to Order →</button>
        <button class="cp-btn cpb-o" onclick="clearCart()">Clear Cart</button>
      </div>`;
  } else {
    el.innerHTML=`
      <div class="cf">
        <div class="oms">
          ${S.cart.map(i=>`<div class="oms-r"><span>${i.name} ×${i.qty}</span><span>Ksh ${Number(i.price*i.qty).toLocaleString()}</span></div>`).join('')}
          <div class="oms-tot"><span>Total to Pay</span><span>Ksh ${Number(total).toLocaleString()}</span></div>
        </div>
        <div class="mps-hint">
          <span style="font-size:18px;flex-shrink:0;">💚</span>
          <div>Send <strong>Ksh ${Number(total).toLocaleString()}</strong> to <strong>0701 227 713</strong> via M-Pesa, then fill in your details below.</div>
        </div>
        <label class="cf-lbl">Full Name *</label>
        <input class="cf-inp" id="cName" placeholder="Your full name"/>
        <label class="cf-lbl">Phone Number *</label>
        <input class="cf-inp" id="cPhone" type="tel" placeholder="07XX XXX XXX"/>
        <label class="cf-lbl">Delivery Address</label>
        <input class="cf-inp" id="cAddr" placeholder="Town / Area or 'Pickup in Nkubu'"/>
        <label class="cf-lbl">M-Pesa Confirmation Code *</label>
        <input class="cf-inp" id="cMpesa" placeholder="e.g. QK73XXXXX"/>
        <label class="cf-lbl">Notes (optional)</label>
        <input class="cf-inp" id="cNotes" placeholder="Size, colour preference, etc."/>
      </div>
      <div class="cp-acts">
        <button class="cp-btn cpb-g" onclick="placeOrder(${total})">✓ Confirm & Place Order</button>
        <button class="cp-btn cpb-o" onclick="S.checkout=false;renderCart()">← Back to Cart</button>
      </div>`;
  }
}
function chQty(id,d){const i=S.cart.find(x=>x.id===id);if(!i)return;i.qty+=d;if(i.qty<=0)remItem(id);else{updateBadge();renderCart();}}
function remItem(id){S.cart=S.cart.filter(x=>x.id!==id);updateBadge();renderCart();}
function clearCart(){S.cart=[];updateBadge();renderCart();}
function goCheckout(){S.checkout=true;renderCart();}
function placeOrder(total){
  const name=document.getElementById('cName').value.trim();
  const phone=document.getElementById('cPhone').value.trim();
  const mpesa=document.getElementById('cMpesa').value.trim();
  const addr=document.getElementById('cAddr').value.trim();
  const notes=document.getElementById('cNotes').value.trim();
  if(!name||!phone||!mpesa){showToast('⚠ Fill in Name, Phone & M-Pesa code');return;}
  const ord={id:'SF'+Date.now(),date:new Date().toLocaleString(),customer:name,phone,mpesa,addr,notes,items:[...S.cart],total,status:'new'};
  S.orders.unshift(ord);save();S.cart=[];S.checkout=false;updateBadge();
  document.getElementById('cartBody').innerHTML=`
    <div style="padding:52px 26px;text-align:center;">
      <svg width="72" height="72" viewBox="0 0 24 24" fill="none" stroke="#2D7A55" stroke-width="1.5" style="margin:0 auto 18px;opacity:.8"><circle cx="12" cy="12" r="10"/><polyline points="9 12 11 14 15 10"/></svg>
      <h2 style="font-family:'Cormorant Garamond',serif;font-size:30px;color:var(--pearl);margin-bottom:10px;font-weight:600;">Order Placed!</h2>
      <p style="color:var(--ash);font-weight:300;margin-bottom:7px;">Thank you, <strong style="color:var(--gold3)">${name}</strong>!</p>
      <p style="color:var(--smoke);font-size:12.5px;margin-bottom:24px;font-weight:300;">Order <strong style="color:var(--gold)">${ord.id}</strong> received.<br>We'll contact you on <strong>${phone}</strong> shortly.</p>
      <div style="background:rgba(0,136,62,.1);border:1px solid rgba(0,136,62,.2);border-radius:12px;padding:14px;font-size:12.5px;color:#4ADE80;margin-bottom:24px;line-height:1.6;">
        📱 We'll verify your M-Pesa payment and process your order right away. Thank you for choosing Sarah Fashions!
      </div>
      <button class="cp-btn cpb-g" style="width:100%;" onclick="closeCart()">Continue Shopping →</button>
    </div>`;
}

// ═══ IMAGE UPLOAD ═══
function previewImg(input){
  const file=input.files[0];if(!file)return;
  if(file.size>5*1024*1024){showToast('⚠ Image too large (max 5MB)');return;}
  const r=new FileReader();
  r.onload=e=>{
    imgData=e.target.result;
    const p=document.getElementById('imgPrev');p.src=imgData;p.style.display='block';
    document.querySelector('.ua-ico').style.display='none';
    document.querySelector('.ua-txt').style.display='none';
    document.querySelector('.ua-sub').style.display='none';
  };r.readAsDataURL(file);
}

// ═══ ADMIN ═══
function openAdmin(){
  document.getElementById('adminModal').classList.remove('hidden');
  if(adminIn){document.getElementById('adminLogin').classList.add('hidden');document.getElementById('adminDash').classList.remove('hidden');refAdmin();}
  else{document.getElementById('adminLogin').classList.remove('hidden');document.getElementById('adminDash').classList.add('hidden');}
}
function closeAdmin(){document.getElementById('adminModal').classList.add('hidden');}
function doLogin(){
  if(document.getElementById('adminPw').value==='Sarah@2024'){
    adminIn=true;document.getElementById('adminLogin').classList.add('hidden');
    document.getElementById('adminDash').classList.remove('hidden');refAdmin();
  } else showToast('⚠ Incorrect password');
}
function aTab(t){
  ['Products','Categories','Orders'].forEach(x=>document.getElementById('a'+x).classList.toggle('hidden',x.toLowerCase()!==t));
  document.querySelectorAll('.adm-tab').forEach((el,i)=>el.classList.toggle('on',['products','categories','orders'][i]===t));
  if(t==='orders') renderAOrders();
}
function refAdmin(){renderAProd();renderACat();fillCatSel();renderAOrders();}

function addCat(){
  const n=document.getElementById('cName').value.trim();
  const ic=document.getElementById('cIcon').value.trim()||'🏷';
  if(!n){showToast('⚠ Enter category name');return;}
  if(S.categories.find(c=>c.name.toLowerCase()===n.toLowerCase())){showToast('⚠ Already exists');return;}
  S.categories.push({name:n,icon:ic});save();
  document.getElementById('cName').value='';document.getElementById('cIcon').value='';
  renderACat();fillCatSel();renderCats();renderProds();updateStats();showToast('✓ Category added!');
}
function delCat(n){
  if(!confirm('Delete "'+n+'"?'))return;
  S.categories=S.categories.filter(c=>c.name!==n);
  S.products.forEach(p=>{if(p.category===n)p.category='General';});
  save();renderACat();fillCatSel();renderCats();renderProds();updateStats();showToast('Category deleted');
}
function renderACat(){
  const el=document.getElementById('aCatList');
  if(!S.categories.length){el.innerHTML='<p style="color:var(--smoke);font-size:13px;font-weight:300;">No categories yet.</p>';return;}
  el.innerHTML=S.categories.map(c=>`<div class="pl-item">
    <div class="pl-thumb" style="font-size:20px;background:rgba(201,150,58,.05);">${getCatSVG(c.name)}</div>
    <div class="pl-inf"><strong>${c.name}</strong><small>${S.products.filter(p=>p.category===c.name).length} products</small></div>
    <div class="pl-acts"><button class="del-b" onclick="delCat('${esc(c.name)}')">Delete</button></div>
  </div>`).join('');
}
function fillCatSel(){
  const s=document.getElementById('pCat');
  s.innerHTML='<option value="">Select category…</option>'+S.categories.map(c=>`<option value="${c.name}">${c.icon} ${c.name}</option>`).join('');
}
function addProd(){
  const name=document.getElementById('pName').value.trim();
  const cat=document.getElementById('pCat').value;
  const price=parseFloat(document.getElementById('pPrice').value);
  const icon=document.getElementById('pIcon').value.trim()||'👗';
  const desc=document.getElementById('pDesc').value.trim();
  if(!name||!cat||!price){showToast('⚠ Fill in Name, Category and Price');return;}
  if(isNaN(price)||price<=0){showToast('⚠ Enter a valid price');return;}
  S.products.unshift({id:++pid,name,category:cat,price,icon,description:desc,image:imgData||null,badge:'NEW',outOfStock:false});
  save();
  ['pName','pPrice','pIcon','pDesc'].forEach(id=>document.getElementById(id).value='');
  document.getElementById('pCat').value='';document.getElementById('pImage').value='';
  document.getElementById('imgPrev').style.display='none';
  document.querySelector('.ua-ico').style.display='';document.querySelector('.ua-txt').style.display='';document.querySelector('.ua-sub').style.display='';
  imgData=null;renderAProd();renderCats();renderProds();updateStats();showToast('✓ Product added!');
}
function toggleOOS(id){
  const p=S.products.find(x=>x.id===id);if(!p)return;
  p.outOfStock=!p.outOfStock;if(p.outOfStock)S.cart=S.cart.filter(c=>c.id!==id);
  save();renderAProd();renderProds();updateBadge();
  showToast(p.outOfStock?'📦 Marked out of stock':'✓ Back in stock');
}
function delProd(id){
  if(!confirm('Delete this product?'))return;
  S.products=S.products.filter(p=>p.id!==id);S.cart=S.cart.filter(c=>c.id!==id);
  save();renderAProd();renderCats();renderProds();updateStats();updateBadge();showToast('Product deleted');
}
function renderAProd(){
  const el=document.getElementById('aProdList');
  document.getElementById('pCount').textContent='('+S.products.length+' total)';
  if(!S.products.length){el.innerHTML='<p style="color:var(--smoke);font-size:13px;font-weight:300;">No products yet. Add one above.</p>';return;}
  el.innerHTML=S.products.map(p=>`<div class="pl-item">
    <div class="pl-thumb">${p.image?`<img src="${p.image}" alt="${p.name}"/>`:getProdSVG(p.category,p.icon)}</div>
    <div class="pl-inf"><strong>${p.name}</strong><small>${p.category}</small>
      <div class="pl-price">Ksh ${Number(p.price).toLocaleString()} ${p.outOfStock?'<span style="color:var(--rose2);font-size:9px;"> · OUT OF STOCK</span>':''}</div>
    </div>
    <div class="pl-acts">
      <button class="oos-tog ${p.outOfStock?'t-oos':'t-live'}" onclick="toggleOOS(${p.id})">${p.outOfStock?'✕ OOS':'✓ Live'}</button>
      <button class="del-b" onclick="delProd(${p.id})">Delete</button>
    </div>
  </div>`).join('');
}
function renderAOrders(){
  const el=document.getElementById('aOrderList');
  if(!S.orders.length){el.innerHTML='<p style="color:var(--smoke);font-size:13px;font-weight:300;">No orders yet.</p>';return;}
  el.innerHTML=`<table class="o-tbl"><thead><tr>
    <th>Order ID</th><th>Customer</th><th>Phone</th><th>Total</th><th>M-Pesa</th><th>Date</th><th>Status</th><th></th>
  </tr></thead><tbody>${S.orders.map(o=>`<tr>
    <td style="font-weight:700;color:var(--gold3);">${o.id}</td>
    <td>${o.customer}</td><td>${o.phone}</td>
    <td>Ksh ${Number(o.total).toLocaleString()}</td>
    <td style="font-family:monospace;font-size:11px;">${o.mpesa}</td>
    <td style="font-size:10.5px;">${o.date}</td>
    <td><select class="o-st st-${o.status}" onchange="updStatus('${o.id}',this.value)">
      <option value="new" ${o.status==='new'?'selected':''}>NEW</option>
      <option value="processing" ${o.status==='processing'?'selected':''}>PROCESSING</option>
      <option value="done" ${o.status==='done'?'selected':''}>DONE</option>
    </select></td>
    <td><button class="del-b" onclick="delOrder('${o.id}')">Del</button></td>
  </tr>`).join('')}</tbody></table>`;
}
function updStatus(id,s){const o=S.orders.find(x=>x.id===id);if(o){o.status=s;save();}renderAOrders();showToast('Status updated');}
function delOrder(id){if(!confirm('Delete order?'))return;S.orders=S.orders.filter(x=>x.id!==id);save();renderAOrders();}

// ═══ UTILS ═══
function updateStats(){document.getElementById('heroItems').textContent=S.products.filter(p=>!p.outOfStock).length;document.getElementById('heroCats').textContent=S.categories.length;}
function esc(s){return s.replace(/'/g,"\\'");}
function scrollTo(id){document.getElementById(id).scrollIntoView({behavior:'smooth'});}
function showToast(msg){const t=document.getElementById('toast');t.textContent=msg;t.classList.add('show');clearTimeout(t._t);t._t=setTimeout(()=>t.classList.remove('show'),2800);}

// ═══ REVEAL ═══
const ro=new IntersectionObserver(entries=>{entries.forEach(e=>{if(e.isIntersecting){e.target.classList.add('vis');ro.unobserve(e.target);}});},{threshold:.08});
function obsAll(){document.querySelectorAll('.rv,.rvl,.rvr').forEach(el=>ro.observe(el));}

init();
setTimeout(obsAll,100);
</script>
</body>
</html>
