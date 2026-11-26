[index.html.](https://github.com/user-attachments/files/35416184/index.html.txt)
# tatiana-salon<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ТАТЬЯНА — Салон красоты в Новошахтинске | Красота · Стиль · Удовольствие</title>
<meta name="description" content="Салон красоты Татьяны в Новошахтинске. Стрижки, окрашивание, маникюр, брови и ресницы на профессиональной косметике Estel. Запись онлайн.">
<link href="https://cdn.jsdelivr.net/fontsource/fonts/playfair-display@latest/latin-400-normal.min.css" rel="stylesheet">
<link href="https://cdn.jsdelivr.net/fontsource/fonts/playfair-display@latest/latin-500-normal.min.css" rel="stylesheet">
<link href="https://cdn.jsdelivr.net/fontsource/fonts/playfair-display@latest/latin-600-normal.min.css" rel="stylesheet">
<link href="https://cdn.jsdelivr.net/fontsource/fonts/playfair-display@latest/latin-400-italic.min.css" rel="stylesheet">
<link href="https://cdn.jsdelivr.net/fontsource/fonts/montserrat@latest/latin-300-normal.min.css" rel="stylesheet">
<link href="https://cdn.jsdelivr.net/fontsource/fonts/montserrat@latest/latin-400-normal.min.css" rel="stylesheet">
<link href="https://cdn.jsdelivr.net/fontsource/fonts/montserrat@latest/latin-500-normal.min.css" rel="stylesheet">
<link href="https://cdn.jsdelivr.net/fontsource/fonts/montserrat@latest/latin-600-normal.min.css" rel="stylesheet">
<style>
:root{
  --black:#0E0E10;
  --graphite:#1A1A1D;
  --graphite-2:#242428;
  --line:#2E2E33;
  --gold:#C9A961;
  --gold-light:#E0C49A;
  --gold-deep:#A8854F;
  --cream:#F5F1EA;
  --ivory:#FAF7F2;
  --white:#FFFFFF;
  --text-muted:#8A8A92;
  --text-dim:#5A5A62;
  /* WHY: трекинги как на salonmone.ru — раздвинутые буквы во всех капитальных элементах */
  --track-xs:3px;
  --track-sm:4px;
  --track-md:6px;
  --track-lg:8px;
  --track-xl:12px;
  --track-2xl:16px;
}
*{margin:0;padding:0;box-sizing:border-box}
html{scroll-behavior:smooth}
body{font-family:'Montserrat',system-ui,sans-serif;font-weight:300;color:var(--white);background:var(--black);overflow-x:hidden;line-height:1.7;letter-spacing:.5px;-webkit-font-smoothing:antialiased}
img{display:block;max-width:100%}
button{font-family:inherit;cursor:pointer;border:none;background:none;color:inherit}
a{text-decoration:none;color:inherit}
.serif{font-family:'Playfair Display',Georgia,serif}

/* TOP BAR */
.topbar{background:var(--black);border-bottom:1px solid var(--line);padding:16px 0;font-size:11px;letter-spacing:var(--track-sm);text-transform:uppercase;color:var(--text-muted)}
.topbar-inner{max-width:1400px;margin:0 auto;padding:0 24px;display:flex;align-items:center;justify-content:space-between;gap:20px;flex-wrap:wrap}
@media(min-width:1024px){.topbar-inner{padding:0 48px}}
.topbar-links{display:flex;gap:32px;flex-wrap:wrap}
.topbar-links a{transition:color .3s;display:inline-flex;align-items:center;gap:9px}
.topbar-links a:hover{color:var(--gold)}
.topbar-phone{color:var(--gold);font-weight:500;letter-spacing:var(--track-sm)}

/* HEADER */
.header{position:sticky;top:0;z-index:100;background:rgba(14,14,16,.92);backdrop-filter:blur(14px);-webkit-backdrop-filter:blur(14px);border-bottom:1px solid var(--line);height:84px}
.header-inner{max-width:1400px;margin:0 auto;height:100%;padding:0 24px;display:flex;align-items:center;justify-content:space-between;gap:24px}
@media(min-width:1024px){.header-inner{padding:0 48px}}
.logo{display:flex;flex-direction:column;align-items:center;line-height:1;flex-shrink:0}
.logo-main{font-family:'Playfair Display',serif;font-size:26px;font-weight:500;letter-spacing:var(--track-xl);color:var(--white);padding-left:var(--track-xl)}
.logo-sub{font-family:'Montserrat',sans-serif;font-size:8px;font-weight:400;letter-spacing:var(--track-md);text-transform:uppercase;color:var(--gold);margin-top:7px;padding-left:var(--track-md)}
.nav{display:none;align-items:center;gap:40px}
@media(min-width:980px){.nav{display:flex}}
.nav a{font-size:11px;font-weight:400;letter-spacing:var(--track-sm);text-transform:uppercase;color:var(--white);transition:color .3s;position:relative;padding:6px 0}
.nav a::after{content:'';position:absolute;bottom:0;left:0;width:0;height:1px;background:var(--gold);transition:width .35s}
.nav a:hover{color:var(--gold)}
.nav a:hover::after{width:100%}
.header-actions{display:flex;align-items:center;gap:14px}
.btn-gold{display:inline-flex;align-items:center;justify-content:center;gap:9px;background:var(--gold);color:var(--black);padding:14px 28px;font-family:'Montserrat',sans-serif;font-size:10px;font-weight:500;letter-spacing:var(--track-sm);text-transform:uppercase;transition:all .35s;white-space:nowrap}
.btn-gold:hover{background:var(--gold-light);transform:translateY(-1px)}
.btn-gold:active{transform:scale(.97)}
.btn-outline-gold{display:inline-flex;align-items:center;justify-content:center;gap:9px;background:transparent;color:var(--gold);padding:13px 26px;border:1px solid var(--gold);font-family:'Montserrat',sans-serif;font-size:10px;font-weight:500;letter-spacing:var(--track-sm);text-transform:uppercase;transition:all .35s;white-space:nowrap}
.btn-outline-gold:hover{background:var(--gold);color:var(--black)}
.burger{display:flex;align-items:center;justify-content:center;width:44px;height:44px;color:var(--white)}
.burger:active{transform:scale(.95)}
@media(min-width:980px){.burger{display:none}}
.header-cta-desktop{display:none}
@media(min-width:768px){.header-cta-desktop{display:inline-flex}}

/* MOBILE MENU */
.mobile-backdrop{position:fixed;inset:0;z-index:110;background:rgba(0,0,0,.7);backdrop-filter:blur(6px);opacity:0;pointer-events:none;transition:opacity .4s}
.mobile-backdrop.open{opacity:1;pointer-events:auto}
@media(min-width:980px){.mobile-backdrop{display:none}}
.mobile-panel{position:fixed;top:0;right:0;z-index:120;height:100%;width:88%;max-width:380px;background:var(--graphite);border-left:1px solid var(--line);transform:translateX(100%);transition:transform .45s cubic-bezier(.22,1,.36,1);display:flex;flex-direction:column;overflow-y:auto}
.mobile-panel.open{transform:translateX(0)}
@media(min-width:980px){.mobile-panel{display:none}}
.mobile-head{display:flex;align-items:center;justify-content:space-between;padding:24px 28px;border-bottom:1px solid var(--line);flex-shrink:0}
.mobile-close{width:40px;height:40px;color:var(--white);display:flex;align-items:center;justify-content:center}
.mobile-nav{flex:1;padding:22px 0}
.mobile-nav a{display:block;padding:18px 32px;font-family:'Playfair Display',serif;font-size:18px;font-weight:400;letter-spacing:var(--track-sm);text-transform:uppercase;color:var(--white);border-bottom:1px solid var(--line);transition:all .3s}
.mobile-nav a:hover{color:var(--gold);padding-left:40px;background:rgba(201,169,97,.05)}
.mobile-foot{padding:28px;border-top:1px solid var(--line);flex-shrink:0;display:flex;flex-direction:column;gap:12px}
.mobile-foot .btn-gold,.mobile-foot .btn-outline-gold{width:100%;padding:16px;justify-content:center}
.mobile-foot-note{font-size:10px;letter-spacing:var(--track-sm);text-transform:uppercase;color:var(--text-muted);text-align:center;line-height:1.9}

/* HERO SLIDER */
.hero{position:relative;height:calc(100vh - 84px);min-height:600px;overflow:hidden;background:var(--black)}
.hero-slides{position:absolute;inset:0}
.hero-slide{position:absolute;inset:0;opacity:0;transition:opacity 1.2s ease}
.hero-slide.active{opacity:1}
.hero-slide img{width:100%;height:100%;object-fit:cover;filter:brightness(.55)}
.hero-overlay{position:absolute;inset:0;background:linear-gradient(to bottom,rgba(14,14,16,.4) 0%,rgba(14,14,16,.6) 60%,rgba(14,14,16,.95) 100%);z-index:1}
.hero-content{position:relative;z-index:2;height:100%;display:flex;flex-direction:column;align-items:center;justify-content:center;text-align:center;padding:0 24px;max-width:1200px;margin:0 auto}
.hero-counter{position:absolute;top:44px;left:50%;transform:translateX(-50%);z-index:3;font-family:'Montserrat',sans-serif;font-size:11px;letter-spacing:var(--track-md);color:var(--gold);font-variant-numeric:tabular-nums}
.hero h1{font-family:'Playfair Display',serif;font-size:clamp(34px,5.5vw,76px);font-weight:400;line-height:1.1;color:var(--white);margin-bottom:28px;letter-spacing:var(--track-md);text-transform:uppercase;padding-left:var(--track-md)}
.hero h1 span{color:var(--gold);font-style:italic;font-weight:400}
.hero-tagline{font-family:'Montserrat',sans-serif;font-size:11px;font-weight:400;letter-spacing:var(--track-lg);text-transform:uppercase;color:var(--gold);margin-bottom:36px;padding-left:var(--track-lg)}
.hero-tagline span{margin:0 14px;color:var(--text-dim)}
.hero-quote{font-family:'Playfair Display',serif;font-size:clamp(15px,1.8vw,20px);font-weight:400;font-style:italic;line-height:1.7;color:rgba(255,255,255,.85);max-width:760px;margin:0 auto 44px;letter-spacing:.5px}
.hero-quote::before,.hero-quote::after{content:'"';color:var(--gold);font-size:1.4em;line-height:0;vertical-align:-.3em;margin:0 5px}
.hero-ctas{display:flex;flex-wrap:wrap;justify-content:center;gap:14px}
.hero-dots{position:absolute;bottom:44px;left:50%;transform:translateX(-50%);z-index:3;display:flex;gap:12px}
.hero-dot{width:36px;height:2px;background:rgba(255,255,255,.3);cursor:pointer;transition:all .3s}
.hero-dot.active{background:var(--gold);width:54px}

/* SECTIONS */
.section{padding:110px 24px;position:relative}
@media(min-width:640px){.section{padding:140px 48px}}
.section-inner{max-width:1400px;margin:0 auto}
.section-head{text-align:center;margin-bottom:80px}
.section-label{display:inline-block;font-family:'Montserrat',sans-serif;font-size:11px;font-weight:400;letter-spacing:var(--track-lg);text-transform:uppercase;color:var(--gold);margin-bottom:22px;padding-left:var(--track-lg)}
.section-title{font-family:'Playfair Display',serif;font-size:clamp(32px,4vw,54px);font-weight:400;line-height:1.2;color:var(--white);letter-spacing:var(--track-sm);text-transform:uppercase;padding-left:var(--track-sm)}
.section-title em{font-style:italic;color:var(--gold);font-weight:400;text-transform:none;letter-spacing:1px}
.section-line{width:60px;height:1px;background:var(--gold);margin:28px auto 0}
.section-dark{background:var(--black)}
.section-graphite{background:var(--graphite)}

/* SERVICES MENU */
.services-grid{display:grid;grid-template-columns:1fr;gap:0;border-top:1px solid var(--line);border-left:1px solid var(--line)}
@media(min-width:640px){.services-grid{grid-template-columns:repeat(2,1fr)}}
@media(min-width:1024px){.services-grid{grid-template-columns:repeat(3,1fr)}}
.service-item{position:relative;padding:54px 40px;border-right:1px solid var(--line);border-bottom:1px solid var(--line);transition:all .4s;cursor:pointer;overflow:hidden;background:var(--black)}
.service-item::before{content:'';position:absolute;inset:0;background:linear-gradient(135deg,rgba(201,169,97,.08),transparent);opacity:0;transition:opacity .4s}
.service-item:hover::before{opacity:1}
.service-item:hover{background:var(--graphite)}
.service-num{font-family:'Playfair Display',serif;font-size:13px;color:var(--gold);letter-spacing:var(--track-sm);margin-bottom:22px;font-style:italic}
.service-icon{width:46px;height:46px;color:var(--gold);margin-bottom:26px;transition:transform .4s}
.service-item:hover .service-icon{transform:scale(1.1) rotate(-5deg)}
.service-name{font-family:'Playfair Display',serif;font-size:24px;font-weight:400;color:var(--white);margin-bottom:14px;letter-spacing:var(--track-xs);text-transform:uppercase;padding-left:var(--track-xs)}
.service-desc{font-family:'Montserrat',sans-serif;font-size:13px;font-weight:300;color:var(--text-muted);line-height:1.85;margin-bottom:26px;letter-spacing:.5px}
.service-price{font-family:'Playfair Display',serif;font-size:18px;color:var(--gold);font-style:italic;letter-spacing:1px}
.service-arrow{position:absolute;top:54px;right:40px;color:var(--text-dim);transition:all .4s}
.service-item:hover .service-arrow{color:var(--gold);transform:translateX(6px)}

/* SALONS */
.salon-filters{display:flex;flex-wrap:wrap;justify-content:center;gap:8px;margin-bottom:56px;padding-bottom:34px;border-bottom:1px solid var(--line)}
.salon-filter{padding:11px 22px;font-family:'Montserrat',sans-serif;font-size:10px;font-weight:400;letter-spacing:var(--track-sm);text-transform:uppercase;color:var(--text-muted);transition:all .3s;border:1px solid transparent}
.salon-filter.active,.salon-filter:hover{color:var(--gold);border-color:var(--gold)}
.salon-card{display:grid;grid-template-columns:1fr;gap:0;background:var(--graphite);border:1px solid var(--line);transition:all .4s;overflow:hidden}
@media(min-width:768px){.salon-card{grid-template-columns:1.2fr 1fr}}
.salon-card:hover{border-color:var(--gold);transform:translateY(-4px);box-shadow:0 24px 60px rgba(0,0,0,.5)}
.salon-img{position:relative;aspect-ratio:4/3;overflow:hidden;background:var(--graphite-2)}
@media(min-width:768px){.salon-img{aspect-ratio:auto;height:100%;min-height:420px}}
.salon-img img{width:100%;height:100%;object-fit:cover;transition:transform .8s;filter:brightness(.85)}
.salon-card:hover .salon-img img{transform:scale(1.05);filter:brightness(1)}
.salon-img-badge{position:absolute;top:22px;left:22px;background:var(--gold);color:var(--black);font-family:'Montserrat',sans-serif;font-size:9.5px;font-weight:500;padding:8px 16px;letter-spacing:var(--track-sm);text-transform:uppercase}
.salon-body{padding:48px 44px;display:flex;flex-direction:column;justify-content:center}
.salon-name{font-family:'Playfair Display',serif;font-size:28px;font-weight:400;color:var(--white);margin-bottom:10px;letter-spacing:var(--track-sm);text-transform:uppercase;padding-left:var(--track-sm)}
.salon-name em{font-style:italic;color:var(--gold);text-transform:none;letter-spacing:1px}
.salon-address{font-family:'Montserrat',sans-serif;font-size:13px;font-weight:300;color:var(--text-muted);line-height:1.9;margin-bottom:10px;letter-spacing:.5px}
.salon-metro{font-family:'Montserrat',sans-serif;font-size:10px;font-weight:400;letter-spacing:var(--track-sm);text-transform:uppercase;color:var(--gold);margin-bottom:28px;display:flex;align-items:center;gap:10px}
.salon-hours{display:flex;flex-direction:column;gap:8px;margin-bottom:32px;padding:22px 0;border-top:1px solid var(--line);border-bottom:1px solid var(--line)}
.salon-hours-row{display:flex;justify-content:space-between;font-family:'Montserrat',sans-serif;font-size:11px;letter-spacing:var(--track-xs);text-transform:uppercase;color:var(--text-muted)}
.salon-hours-row span:last-child{color:var(--white);font-weight:400}
.salon-status{display:inline-flex;align-items:center;gap:9px;font-family:'Montserrat',sans-serif;font-size:10px;letter-spacing:var(--track-sm);text-transform:uppercase;color:#7BA378;margin-bottom:28px}
.salon-status-dot{width:7px;height:7px;border-radius:50%;background:#7BA378;animation:pulse 2s infinite}
@keyframes pulse{0%,100%{opacity:1}50%{opacity:.4}}
.salon-actions{display:flex;gap:10px;flex-wrap:wrap}
.salon-actions .btn-gold,.salon-actions .btn-outline-gold{flex:1;min-width:140px;justify-content:center;padding:15px}

/* PORTFOLIO */
.portfolio-filters{display:flex;flex-wrap:wrap;justify-content:center;gap:8px;margin-bottom:56px}
.portfolio-filter{padding:11px 22px;font-family:'Montserrat',sans-serif;font-size:10px;font-weight:400;letter-spacing:var(--track-sm);text-transform:uppercase;color:var(--text-muted);transition:all .3s;border:1px solid transparent}
.portfolio-filter.active,.portfolio-filter:hover{color:var(--gold);border-color:var(--gold)}
.portfolio-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:14px;grid-auto-rows:180px}
@media(min-width:640px){.portfolio-grid{grid-template-columns:repeat(3,1fr);grid-auto-rows:240px;gap:18px}}
@media(min-width:1024px){.portfolio-grid{grid-template-columns:repeat(4,1fr);grid-auto-rows:260px}}
.portfolio-item{position:relative;overflow:hidden;background:var(--graphite-2);cursor:zoom-in;transition:all .4s}
.portfolio-item.tall{grid-row:span 2}
.portfolio-item.wide{grid-column:span 2}
.portfolio-item img{width:100%;height:100%;object-fit:cover;transition:all .8s;filter:brightness(.8) saturate(.9)}
.portfolio-item:hover img{transform:scale(1.07);filter:brightness(1) saturate(1)}
.portfolio-overlay{position:absolute;inset:0;background:linear-gradient(to top,rgba(14,14,16,.95) 0%,rgba(14,14,16,.3) 50%,transparent 100%);opacity:0;transition:opacity .4s;display:flex;flex-direction:column;justify-content:flex-end;padding:26px}
.portfolio-item:hover .portfolio-overlay{opacity:1}
.portfolio-cat{font-family:'Montserrat',sans-serif;font-size:9.5px;font-weight:400;letter-spacing:var(--track-sm);text-transform:uppercase;color:var(--gold);margin-bottom:8px}
.portfolio-title{font-family:'Playfair Display',serif;font-size:19px;font-weight:400;color:var(--white);letter-spacing:1px;text-transform:uppercase}
.portfolio-master{font-family:'Playfair Display',serif;font-size:13px;font-style:italic;color:var(--gold-light);margin-top:5px;letter-spacing:1px}

/* LIGHTBOX */
.lightbox{position:fixed;inset:0;z-index:10000;background:rgba(0,0,0,.97);display:none;align-items:center;justify-content:center;animation:fadeIn .35s}
.lightbox.open{display:flex}
@keyframes fadeIn{from{opacity:0}to{opacity:1}}
.lightbox-top{position:absolute;top:0;left:0;right:0;padding:26px 32px;display:flex;align-items:center;justify-content:space-between;z-index:2;background:linear-gradient(to bottom,rgba(0,0,0,.7),transparent)}
.lightbox-info{text-align:center;flex:1}
.lightbox-cat{font-family:'Montserrat',sans-serif;font-size:10px;letter-spacing:var(--track-md);text-transform:uppercase;color:var(--gold);margin-bottom:6px}
.lightbox-title{font-family:'Playfair Display',serif;font-size:22px;color:var(--white);letter-spacing:var(--track-xs);text-transform:uppercase}
.lightbox-master{font-family:'Playfair Display',serif;font-size:14px;font-style:italic;color:var(--gold-light);margin-top:4px;letter-spacing:1px}
.lightbox-counter{position:absolute;left:32px;top:34px;font-family:'Montserrat',sans-serif;font-size:11px;letter-spacing:var(--track-sm);color:rgba(255,255,255,.6);font-variant-numeric:tabular-nums}
.lightbox-close{width:44px;height:44px;color:var(--white);display:flex;align-items:center;justify-content:center;transition:color .3s}
.lightbox-close:hover{color:var(--gold)}
.lightbox-nav{position:absolute;top:50%;transform:translateY(-50%);width:54px;height:54px;color:var(--white);display:flex;align-items:center;justify-content:center;transition:all .3s;z-index:2;border:1px solid rgba(255,255,255,.2)}
.lightbox-nav:hover{background:rgba(201,169,97,.15);border-color:var(--gold);color:var(--gold)}
.lightbox-nav.prev{left:20px}
.lightbox-nav.next{right:20px}
@media(min-width:640px){.lightbox-nav.prev{left:40px}.lightbox-nav.next{right:40px}}
.lightbox-img-wrap{max-width:90vw;max-height:74vh;display:flex;align-items:center;justify-content:center}
.lightbox-img-wrap img{max-width:100%;max-height:74vh;object-fit:contain;animation:lbImg .4s}
@keyframes lbImg{from{opacity:0;transform:scale(.96)}to{opacity:1;transform:scale(1)}}
.lightbox-thumbs{position:absolute;bottom:26px;left:0;right:0;display:flex;justify-content:center;gap:10px;padding:0 24px;overflow-x:auto;z-index:2}
.lightbox-thumb{flex-shrink:0;width:56px;height:56px;overflow:hidden;border:1px solid transparent;opacity:.4;transition:all .3s;cursor:pointer}
@media(min-width:640px){.lightbox-thumb{width:66px;height:66px}}
.lightbox-thumb.active{border-color:var(--gold);opacity:1}
.lightbox-thumb:hover{opacity:.85}
.lightbox-thumb img{width:100%;height:100%;object-fit:cover}

/* PROMO */
.promo-grid{display:grid;grid-template-columns:1fr;gap:24px}
@media(min-width:640px){.promo-grid{grid-template-columns:repeat(2,1fr)}}
@media(min-width:1024px){.promo-grid{grid-template-columns:repeat(3,1fr)}}
.promo-card{position:relative;padding:54px 40px;background:var(--graphite);border:1px solid var(--line);transition:all .4s;overflow:hidden}
.promo-card::before{content:'';position:absolute;top:0;left:0;width:100%;height:2px;background:linear-gradient(to right,transparent,var(--gold),transparent);transform:scaleX(0);transition:transform .5s;transform-origin:left}
.promo-card:hover::before{transform:scaleX(1)}
.promo-card:hover{border-color:var(--gold);transform:translateY(-5px);box-shadow:0 24px 60px rgba(0,0,0,.5)}
.promo-badge{display:inline-block;font-family:'Montserrat',sans-serif;font-size:9.5px;font-weight:500;letter-spacing:var(--track-sm);text-transform:uppercase;color:var(--black);background:var(--gold);padding:7px 16px;margin-bottom:26px}
.promo-title{font-family:'Playfair Display',serif;font-size:26px;font-weight:400;color:var(--white);margin-bottom:16px;line-height:1.3;letter-spacing:1px}
.promo-desc{font-family:'Montserrat',sans-serif;font-size:13px;font-weight:300;color:var(--text-muted);line-height:1.9;margin-bottom:30px;letter-spacing:.5px}
.promo-code{display:inline-block;font-family:'Playfair Display',serif;font-size:22px;font-style:italic;color:var(--gold);padding:11px 28px;border:1px dashed var(--gold);letter-spacing:var(--track-md)}
.promo-validity{font-family:'Montserrat',sans-serif;font-size:10px;letter-spacing:var(--track-sm);text-transform:uppercase;color:var(--text-dim);margin-top:22px}

/* TEAM CTA */
.team-cta{position:relative;padding:130px 24px;text-align:center;overflow:hidden;background:var(--graphite)}
@media(min-width:640px){.team-cta{padding:170px 48px}}
.team-cta-bg{position:absolute;inset:0;z-index:0}
.team-cta-bg img{width:100%;height:100%;object-fit:cover;filter:brightness(.25)}
.team-cta-overlay{position:absolute;inset:0;background:linear-gradient(135deg,rgba(14,14,16,.85),rgba(26,26,29,.7));z-index:1}
.team-cta-inner{position:relative;z-index:2;max-width:820px;margin:0 auto}
.team-cta .section-title{margin-bottom:28px}
.team-cta-text{font-family:'Montserrat',sans-serif;font-size:14px;font-weight:300;color:rgba(255,255,255,.75);line-height:2;margin-bottom:40px;letter-spacing:.7px}

/* NEWS */
.news-grid{display:grid;grid-template-columns:1fr;gap:28px}
@media(min-width:640px){.news-grid{grid-template-columns:repeat(2,1fr)}}
@media(min-width:1024px){.news-grid{grid-template-columns:repeat(3,1fr)}}
.news-card{background:var(--graphite);border:1px solid var(--line);transition:all .4s;cursor:pointer;display:flex;flex-direction:column;overflow:hidden}
.news-card:hover{border-color:var(--gold);transform:translateY(-5px);box-shadow:0 24px 60px rgba(0,0,0,.5)}
.news-img{position:relative;width:100%;aspect-ratio:16/10;overflow:hidden;background:var(--graphite-2)}
.news-img img{width:100%;height:100%;object-fit:cover;transition:all .6s;filter:brightness(.8)}
.news-card:hover .news-img img{filter:brightness(1);transform:scale(1.05)}
.news-tag{position:absolute;top:18px;left:18px;background:var(--gold);color:var(--black);font-family:'Montserrat',sans-serif;font-size:9px;font-weight:500;padding:6px 14px;letter-spacing:var(--track-sm);text-transform:uppercase}
.news-body{padding:32px 30px;flex:1;display:flex;flex-direction:column}
.news-date{font-family:'Montserrat',sans-serif;font-size:10px;letter-spacing:var(--track-sm);text-transform:uppercase;color:var(--gold);margin-bottom:14px}
.news-title{font-family:'Playfair Display',serif;font-size:21px;font-weight:400;color:var(--white);margin-bottom:16px;line-height:1.4;letter-spacing:.5px;transition:color .3s}
.news-card:hover .news-title{color:var(--gold)}
.news-excerpt{font-family:'Montserrat',sans-serif;font-size:13px;font-weight:300;color:var(--text-muted);line-height:1.9;flex:1;letter-spacing:.5px;display:-webkit-box;-webkit-line-clamp:3;-webkit-box-orient:vertical;overflow:hidden}
.news-more{font-family:'Montserrat',sans-serif;font-size:10px;letter-spacing:var(--track-sm);text-transform:uppercase;color:var(--gold);margin-top:24px;display:inline-flex;align-items:center;gap:10px;transition:gap .3s}
.news-card:hover .news-more{gap:16px}

/* FAQ */
.faq-list{max-width:920px;margin:0 auto;display:flex;flex-direction:column;gap:0;border-top:1px solid var(--line)}
.faq-item{border-bottom:1px solid var(--line);transition:all .35s}
.faq-q{width:100%;padding:32px 8px;display:flex;align-items:center;justify-content:space-between;gap:24px;text-align:left;font-family:'Playfair Display',serif;font-size:20px;font-weight:400;color:var(--white);letter-spacing:1px;transition:color .3s;text-transform:uppercase}
.faq-item.open .faq-q{color:var(--gold)}
@media(max-width:640px){.faq-q{font-size:16px;padding:24px 4px;letter-spacing:.5px}}
.faq-icon{width:38px;height:38px;border:1px solid var(--line);color:var(--gold);display:flex;align-items:center;justify-content:center;flex-shrink:0;transition:all .4s}
.faq-item.open .faq-icon{background:var(--gold);color:var(--black);border-color:var(--gold);transform:rotate(45deg)}
.faq-a{max-height:0;overflow:hidden;transition:max-height .45s,padding .45s;padding:0 8px}
.faq-item.open .faq-a{max-height:380px;padding:0 8px 32px}
.faq-a p{font-family:'Montserrat',sans-serif;font-size:14px;font-weight:300;color:var(--text-muted);line-height:1.95;letter-spacing:.5px}

/* MAP */
.map-section{padding:0;position:relative;height:540px;background:var(--graphite)}
.map-section iframe{width:100%;height:100%;border:0;filter:invert(.92) hue-rotate(180deg) saturate(.4) brightness(.7) contrast(1.1)}
.map-overlay{position:absolute;top:44px;left:44px;z-index:2;background:var(--black);border:1px solid var(--gold);padding:36px;max-width:360px}
@media(max-width:640px){.map-overlay{top:20px;left:20px;right:20px;max-width:none;padding:28px}}
.map-overlay-title{font-family:'Playfair Display',serif;font-size:22px;color:var(--white);margin-bottom:8px;letter-spacing:var(--track-sm);text-transform:uppercase;padding-left:var(--track-sm)}
.map-overlay-title em{font-style:italic;color:var(--gold);text-transform:none;letter-spacing:1px}
.map-overlay-address{font-family:'Montserrat',sans-serif;font-size:13px;color:var(--text-muted);line-height:1.9;margin-bottom:22px;letter-spacing:.5px}
.map-overlay .btn-gold{width:100%;justify-content:center}

/* FOOTER */
.footer{background:var(--black);border-top:1px solid var(--line);padding:90px 24px 36px}
.footer-inner{max-width:1400px;margin:0 auto}
.footer-top{display:grid;grid-template-columns:1fr;gap:54px;padding-bottom:54px;border-bottom:1px solid var(--line)}
@media(min-width:768px){.footer-top{grid-template-columns:1.5fr 1fr 1fr 1fr}}
.footer-brand .logo{align-items:flex-start;margin-bottom:24px}
.footer-brand-text{font-family:'Montserrat',sans-serif;font-size:13px;font-weight:300;color:var(--text-muted);line-height:1.95;max-width:360px;letter-spacing:.5px}
.footer-col-title{font-family:'Montserrat',sans-serif;font-size:10px;font-weight:500;letter-spacing:var(--track-sm);text-transform:uppercase;color:var(--gold);margin-bottom:26px}
.footer-col ul{list-style:none;display:flex;flex-direction:column;gap:14px}
.footer-col a,.footer-col li{font-family:'Montserrat',sans-serif;font-size:13px;font-weight:300;color:var(--text-muted);transition:color .3s;letter-spacing:.5px;line-height:1.8}
.footer-col a:hover{color:var(--gold)}
.footer-socials{display:flex;gap:10px;margin-top:22px}
.footer-social{width:42px;height:42px;border:1px solid var(--line);color:var(--text-muted);display:flex;align-items:center;justify-content:center;transition:all .3s}
.footer-social:hover{border-color:var(--gold);color:var(--gold);background:rgba(201,169,97,.08)}
.footer-bottom{padding-top:36px;display:flex;flex-direction:column;gap:16px;align-items:center;justify-content:space-between;text-align:center}
@media(min-width:640px){.footer-bottom{flex-direction:row;text-align:left}}
.footer-copy{font-family:'Montserrat',sans-serif;font-size:10px;letter-spacing:var(--track-sm);text-transform:uppercase;color:var(--text-dim)}
.footer-legal{display:flex;gap:24px;flex-wrap:wrap;justify-content:center}
.footer-legal a{font-family:'Montserrat',sans-serif;font-size:10px;letter-spacing:var(--track-sm);text-transform:uppercase;color:var(--text-dim);transition:color .3s}
.footer-legal a:hover{color:var(--gold)}

/* FLOATING BUTTONS */
.float-stack{position:fixed;bottom:24px;right:24px;z-index:40;display:flex;flex-direction:column;gap:12px}
.float-btn{width:56px;height:56px;display:flex;align-items:center;justify-content:center;transition:all .3s;box-shadow:0 8px 24px rgba(0,0,0,.4)}
.float-btn:active{transform:scale(.92)}
.float-wa{background:#25D366;color:#fff}
.float-call{background:var(--gold);color:var(--black)}
.float-btn:hover{transform:translateY(-3px)}

/* MODAL */
.modal-backdrop{position:fixed;inset:0;z-index:9999;background:rgba(0,0,0,.8);backdrop-filter:blur(8px);display:none;align-items:flex-end;justify-content:center;padding:0}
.modal-backdrop.open{display:flex}
@media(min-width:640px){.modal-backdrop{align-items:center;padding:24px}}
.modal{position:relative;background:var(--graphite);border:1px solid var(--line);border-top:2px solid var(--gold);padding:40px 32px;width:100%;max-height:94vh;overflow-y:auto;animation:modalUp .4s}
@media(min-width:640px){.modal{padding:60px 54px;max-width:540px;animation:modalIn .4s}}
@keyframes modalUp{from{transform:translateY(40px);opacity:0}to{transform:translateY(0);opacity:1}}
@keyframes modalIn{from{transform:translateY(20px) scale(.97);opacity:0}to{transform:translateY(0) scale(1);opacity:1}}
.modal-handle{width:44px;height:2px;background:var(--gold);margin:0 auto 28px}
@media(min-width:640px){.modal-handle{display:none}}
.modal-close{position:absolute;top:20px;right:20px;width:40px;height:40px;color:var(--text-muted);display:flex;align-items:center;justify-content:center;transition:color .3s}
.modal-close:hover{color:var(--gold)}
.modal-label{font-family:'Montserrat',sans-serif;font-size:10px;letter-spacing:var(--track-lg);text-transform:uppercase;color:var(--gold);text-align:center;margin-bottom:12px;padding-left:var(--track-lg)}
.modal h3{font-family:'Playfair Display',serif;font-size:30px;font-weight:400;color:var(--white);text-align:center;margin-bottom:16px;letter-spacing:var(--track-sm);text-transform:uppercase;padding-left:var(--track-sm)}
.modal h3 em{font-style:italic;color:var(--gold);text-transform:none;letter-spacing:1px}
.modal-desc{font-family:'Montserrat',sans-serif;font-size:13px;font-weight:300;color:var(--text-muted);text-align:center;margin-bottom:36px;line-height:1.9;letter-spacing:.5px}
.form-group{margin-bottom:20px}
.form-group label{display:block;font-family:'Montserrat',sans-serif;font-size:10px;font-weight:400;color:var(--text-muted);margin-bottom:9px;letter-spacing:var(--track-sm);text-transform:uppercase}
.form-group input,.form-group select,.form-group textarea{width:100%;padding:15px 18px;background:var(--black);border:1px solid var(--line);color:var(--white);font-family:'Montserrat',sans-serif;font-size:14px;font-weight:300;outline:none;transition:all .3s;letter-spacing:.5px}
.form-group input:focus,.form-group select:focus,.form-group textarea:focus{border-color:var(--gold);background:var(--graphite-2)}
.form-group textarea{resize:vertical;min-height:90px}
.form-check{display:flex;align-items:flex-start;gap:11px;font-family:'Montserrat',sans-serif;font-size:11.5px;color:var(--text-muted);line-height:1.8;margin-bottom:26px;letter-spacing:.3px}
.form-check input{width:16px;height:16px;margin-top:4px;accent-color:var(--gold);flex-shrink:0}
.form-check a{color:var(--gold);text-decoration:underline}
.form-submit{width:100%;padding:17px;background:var(--gold);color:var(--black);font-family:'Montserrat',sans-serif;font-size:10.5px;font-weight:500;letter-spacing:var(--track-sm);text-transform:uppercase;transition:all .35s}
.form-submit:hover:not(:disabled){background:var(--gold-light);transform:translateY(-1px)}
.form-submit:disabled{opacity:.6;cursor:not-allowed}
.form-submit.success{background:#7BA378;color:var(--white)}

/* COOKIE BANNER */
.cookie{position:fixed;bottom:0;left:0;right:0;z-index:200;background:var(--graphite);border-top:1px solid var(--line);padding:22px 24px;display:none;animation:slideUp .4s}
.cookie.show{display:block}
@keyframes slideUp{from{transform:translateY(100%)}to{transform:translateY(0)}}
.cookie-inner{max-width:1400px;margin:0 auto;display:flex;flex-direction:column;gap:16px;align-items:flex-start}
@media(min-width:768px){.cookie-inner{flex-direction:row;align-items:center;justify-content:space-between}}
.cookie-text{font-family:'Montserrat',sans-serif;font-size:12px;font-weight:300;color:var(--text-muted);line-height:1.8;letter-spacing:.5px;flex:1}
.cookie-text a{color:var(--gold);text-decoration:underline}
.cookie-btns{display:flex;gap:10px;flex-shrink:0}
</style>
</head>
<body>

<!-- TOP BAR -->
<div class="topbar">
  <div class="topbar-inner">
    <div class="topbar-links">
      <a href="#" onclick="openModal('Записаться онлайн');return false">
        <svg width="13" height="13" viewBox="0 0 16 16" fill="none" stroke="currentColor" stroke-width="1.4" stroke-linecap="round"><rect x="2" y="3" width="12" height="11" rx="1"/><path d="M2 6h12M5 1v4M11 1v4"/></svg>
        Записаться онлайн
      </a>
      <a href="tel:+79284175357">
        <svg width="13" height="13" viewBox="0 0 16 16" fill="none" stroke="currentColor" stroke-width="1.4" stroke-linecap="round" stroke-linejoin="round"><path d="M14.5 11.3v2a1.2 1.2 0 0 1-1.3 1.2 11.9 11.9 0 0 1-5.2-1.8 11.7 11.7 0 0 1-3.6-3.6A11.9 11.9 0 0 1 2.6 4 1.2 1.2 0 0 1 3.8 2.7h2a1.2 1.2 0 0 1 1.2 1c.1.8.3 1.5.6 2.2a1.2 1.2 0 0 1-.3 1.3l-.8.8a9.5 9.5 0 0 0 3.6 3.6l.8-.8a1.2 1.2 0 0 1 1.3-.3c.7.3 1.4.5 2.2.6a1.2 1.2 0 0 1 1 1.2z"/></svg>
        Позвонить
      </a>
      <a href="#" onclick="openModal('Купить сертификат');return false">Купить сертификат</a>
    </div>
    <a href="tel:+79284175357" class="topbar-phone">+7 (928) 417-53-57</a>
  </div>
</div>

<!-- HEADER -->
<header class="header">
  <div class="header-inner">
    <a href="#hero" class="logo" onclick="scrollTop(event)">
      <span class="logo-main">ТАТЬЯНА</span>
      <span class="logo-sub">Beauty Salon</span>
    </a>
    <nav class="nav">
      <a href="#services">Услуги</a>
      <a href="#salon">Салон</a>
      <a href="#portfolio">Портфолио</a>
      <a href="#promo">Акции</a>
      <a href="#news">Новости</a>
      <a href="#faq">Вопросы</a>
    </nav>
    <div class="header-actions">
      <button class="btn-gold header-cta-desktop" onclick="openModal('Записаться онлайн')">Записаться</button>
      <button class="burger" onclick="openMenu()" aria-label="Меню">
        <svg width="22" height="22" viewBox="0 0 20 20" fill="none" stroke="currentColor" stroke-width="1.2" stroke-linecap="round"><path d="M3 5h14M3 10h14M3 15h14"/></svg>
      </button>
    </div>
  </div>
</header>

<!-- MOBILE MENU -->
<div class="mobile-backdrop" id="mobBackdrop" onclick="closeMenu()"></div>
<aside class="mobile-panel" id="mobPanel">
  <div class="mobile-head">
    <div class="logo">
      <span class="logo-main" style="font-size:20px;letter-spacing:10px;padding-left:10px">ТАТЬЯНА</span>
      <span class="logo-sub" style="font-size:7.5px;letter-spacing:5px;padding-left:5px">Novošahtinsk</span>
    </div>
    <button class="mobile-close" onclick="closeMenu()" aria-label="Закрыть">
      <svg width="20" height="20" viewBox="0 0 16 16" fill="none" stroke="currentColor" stroke-width="1.2" stroke-linecap="round"><path d="M3 3l10 10M13 3L3 13"/></svg>
    </button>
  </div>
  <nav class="mobile-nav">
    <a href="#services" onclick="closeMenu()">Услуги</a>
    <a href="#salon" onclick="closeMenu()">Салон</a>
    <a href="#portfolio" onclick="closeMenu()">Портфолио</a>
    <a href="#promo" onclick="closeMenu()">Акции</a>
    <a href="#news" onclick="closeMenu()">Новости</a>
    <a href="#faq" onclick="closeMenu()">Вопросы</a>
    <a href="#contacts" onclick="closeMenu()">Контакты</a>
  </nav>
  <div class="mobile-foot">
    <button class="btn-gold" onclick="closeMenu();openModal('Записаться онлайн')">Записаться онлайн</button>
    <a href="tel:+79284175357" class="btn-outline-gold">+7 (928) 417-53-57</a>
    <p class="mobile-foot-note">Ежедневно 9:00 – 21:00<br>Новошахтинск, ул. Советов, 25</p>
  </div>
</aside>

<!-- HERO -->
<section class="hero" id="hero">
  <div class="hero-slides" id="heroSlides">
    <div class="hero-slide active">
      <img src="https://image.qwenlm.ai/public_source/e6e05081-4396-49f7-886f-9607a307441b/42e94e6bb-fe76-46d7-a2b3-303446e4f4da8807.png" alt="Салон Татьяны интерьер">
    </div>
    <div class="hero-slide">
      <img src="https://image.qwenlm.ai/public_source/e6e05081-4396-49f7-886f-9607a307441b/12e94e6bb-fe76-46d7-a2b3-303446e4f4da9483.png" alt="Окрашивание балаяж">
    </div>
    <div class="hero-slide">
      <img src="https://image.qwenlm.ai/public_source/e6e05081-4396-49f7-886f-9607a307441b/62e94e6bb-fe76-46d7-a2b3-303446e4f4da7968.png" alt="Маникюр гель-лак">
    </div>
  </div>
  <div class="hero-overlay"></div>
  <div class="hero-counter"><span id="heroCurrent">01</span> / <span id="heroTotal">03</span></div>
  <div class="hero-content">
    <h1>Салон красоты <span>Татьяны</span></h1>
    <div class="hero-tagline">Красота <span>|</span> Стиль <span>|</span> Удовольствие</div>
    <p class="hero-quote">Мне нравится, когда женщина в сложный будний день, полный встреч и желания всюду успеть, не забывает надеть каблуки и сделать укладку</p>
    <div class="hero-ctas">
      <button class="btn-gold" onclick="openModal('Записаться онлайн')">Записаться онлайн</button>
      <a href="#services" class="btn-outline-gold">Меню услуг</a>
    </div>
  </div>
  <div class="hero-dots" id="heroDots"></div>
</section>

<!-- SERVICES -->
<section class="section section-dark" id="services">
  <div class="section-inner">
    <div class="section-head">
      <span class="section-label">What we do</span>
      <h2 class="section-title">Меню <em>услуг</em></h2>
      <div class="section-line"></div>
    </div>
    <div class="services-grid" id="servicesGrid"></div>
  </div>
</section>

<!-- SALON -->
<section class="section section-graphite" id="salon">
  <div class="section-inner">
    <div class="section-head">
      <span class="section-label">Visit us</span>
      <h2 class="section-title">Наш <em>салон</em></h2>
      <div class="section-line"></div>
    </div>
    <div class="salon-filters">
      <button class="salon-filter active">Новошахтинск</button>
      <button class="salon-filter">Центр</button>
    </div>
    <div class="salon-card">
      <div class="salon-img">
        <img src="https://image.qwenlm.ai/public_source/e6e05081-4396-49f7-886f-9607a307441b/42e94e6bb-fe76-46d7-a2b3-303446e4f4da8807.png" alt="Салон Татьяны в Новошахтинске">
        <span class="salon-img-badge">Flagship</span>
      </div>
      <div class="salon-body">
        <h3 class="salon-name">Татьяна <em>Советов</em></h3>
        <div class="salon-address">ул. Советов, 25<br>г. Новошахтинск, Ростовская область</div>
        <div class="salon-metro">
          <svg width="14" height="14" viewBox="0 0 16 16" fill="none" stroke="currentColor" stroke-width="1.4" stroke-linecap="round"><path d="M8 1C5.24 1 3 3.24 3 6c0 3.75 5 9 5 9s5-5.25 5-9c0-2.76-2.24-5-5-5z"/><circle cx="8" cy="6" r="1.5"/></svg>
          Центр города · рядом с администрацией
        </div>
        <div class="salon-status"><span class="salon-status-dot"></span> Сейчас открыто</div>
        <div class="salon-hours">
          <div class="salon-hours-row"><span>Пн – Пт</span><span>9:00 – 21:00</span></div>
          <div class="salon-hours-row"><span>Суббота</span><span>10:00 – 20:00</span></div>
          <div class="salon-hours-row"><span>Воскресенье</span><span>10:00 – 18:00</span></div>
        </div>
        <div class="salon-actions">
          <button class="btn-gold" onclick="openModal('Записаться в салон Татьяны')">Записаться</button>
          <a href="tel:+79284175357" class="btn-outline-gold">Позвонить</a>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- PORTFOLIO -->
<section class="section section-dark" id="portfolio">
  <div class="section-inner">
    <div class="section-head">
      <span class="section-label">Our works</span>
      <h2 class="section-title">Портфолио <em>работ</em></h2>
      <div class="section-line"></div>
    </div>
    <div class="portfolio-filters">
      <button class="portfolio-filter active" data-filter="all">Все работы</button>
      <button class="portfolio-filter" data-filter="color">Окрашивание</button>
      <button class="portfolio-filter" data-filter="cut">Стрижки</button>
      <button class="portfolio-filter" data-filter="nails">Маникюр</button>
      <button class="portfolio-filter" data-filter="brows">Брови</button>
    </div>
    <div class="portfolio-grid" id="portfolioGrid"></div>
  </div>
</section>

<!-- PROMO -->
<section class="section section-graphite" id="promo">
  <div class="section-inner">
    <div class="section-head">
      <span class="section-label">Special offers</span>
      <h2 class="section-title">Специальные <em>акции</em></h2>
      <div class="section-line"></div>
    </div>
    <div class="promo-grid">
      <div class="promo-card">
        <span class="promo-badge">New Client</span>
        <h3 class="promo-title">−20% на первое посещение</h3>
        <p class="promo-desc">Скидка действует на любую услугу салона для новых клиентов. Познакомимся поближе — расскажем о мастерах и косметике Estel.</p>
        <div class="promo-code">TATYANA20</div>
        <div class="promo-validity">Действует до 31 декабря 2026</div>
      </div>
      <div class="promo-card">
        <span class="promo-badge">For Two</span>
        <h3 class="promo-title">Приведи подругу — −15% обеим</h3>
        <p class="promo-desc">Приходите вдвоём на любые процедуры в один день и получите скидку 15% каждая. Идеально для девичника или совместного ухода.</p>
        <div class="promo-code">FRIEND15</div>
        <div class="promo-validity">Постоянная акция</div>
      </div>
      <div class="promo-card">
        <span class="promo-badge">Complex</span>
        <h3 class="promo-title">Комплекс «Цвет и уход» −25%</h3>
        <p class="promo-desc">Окрашивание Estel De Luxe плюс восстанавливающий уход Estel Otium в одном визите. Экономия времени и денег, максимум результата.</p>
        <div class="promo-code">COLOR25</div>
        <div class="promo-validity">Действует до 28 февраля 2027</div>
      </div>
    </div>
  </div>
</section>

<!-- TEAM CTA -->
<section class="team-cta">
  <div class="team-cta-bg">
    <img src="https://image.qwenlm.ai/public_source/e6e05081-4396-49f7-886f-9607a307441b/32e94e6bb-fe76-46d7-a2b3-303446e4f4da8149.png" alt="Команда салона Татьяны">
  </div>
  <div class="team-cta-overlay"></div>
  <div class="team-cta-inner">
    <span class="section-label">Join us</span>
    <h2 class="section-title">Хочешь стать частью <em>команды?</em></h2>
    <div class="section-line"></div>
    <p class="team-cta-text" style="margin-top:28px">Мы ищем талантливых мастеров, которые разделяют нашу философию красоты и сервиса. Обучение за счёт салона, достойная оплата, дружный коллектив и возможность расти вместе с нами.</p>
    <button class="btn-gold" onclick="openModal('Отклик на вакансию')">Стать частью команды</button>
  </div>
</section>

<!-- NEWS -->
<section class="section section-dark" id="news">
  <div class="section-inner">
    <div class="section-head">
      <span class="section-label">Journal</span>
      <h2 class="section-title">Новости <em>салона</em></h2>
      <div class="section-line"></div>
    </div>
    <div class="news-grid" id="newsGrid"></div>
  </div>
</section>

<!-- FAQ -->
<section class="section section-graphite" id="faq">
  <div class="section-inner">
    <div class="section-head">
      <span class="section-label">FAQ</span>
      <h2 class="section-title">Ответы на частые <em>вопросы</em></h2>
      <div class="section-line"></div>
    </div>
    <div class="faq-list" id="faqList"></div>
  </div>
</section>

<!-- MAP -->
<section class="map-section" id="contacts">
  <iframe src="https://yandex.ru/map-widget/v1/?ll=39.936%2C47.758&z=15&pt=39.936,47.758,pm2rdm" loading="lazy" title="Салон Татьяны на карте Новошахтинска"></iframe>
  <div class="map-overlay">
    <h3 class="map-overlay-title">Татьяна <em>Советов</em></h3>
    <p class="map-overlay-address">ул. Советов, 25<br>г. Новошахтинск<br>+7 (928) 417-53-57</p>
    <button class="btn-gold" onclick="openModal('Записаться в салон')">Записаться</button>
  </div>
</section>

<!-- FOOTER -->
<footer class="footer">
  <div class="footer-inner">
    <div class="footer-top">
      <div class="footer-brand">
        <div class="logo">
          <span class="logo-main">ТАТЬЯНА</span>
          <span class="logo-sub">Beauty Salon</span>
        </div>
        <p class="footer-brand-text">Салон красоты в Новошахтинске. Стрижки, окрашивание, маникюр, брови и ресницы на профессиональной косметике Estel. Красота, стиль и удовольствие в каждой детали.</p>
        <div class="footer-socials">
          <a href="#" class="footer-social" aria-label="Instagram">
            <svg width="16" height="16" viewBox="0 0 16 16" fill="none" stroke="currentColor" stroke-width="1.4"><rect x="2" y="2" width="12" height="12" rx="3"/><circle cx="8" cy="8" r="3"/><circle cx="12" cy="4" r=".8" fill="currentColor"/></svg>
          </a>
          <a href="#" class="footer-social" aria-label="VK">
            <svg width="16" height="16" viewBox="0 0 16 16" fill="currentColor"><path d="M8.4 11c-3.3 0-5.2-2.3-5.3-6h1.6c.1 2.8 1.3 4 2.2 4.2V5h1.5v2.4c.9-.1 1.8-1.1 2.1-2.4H12c-.2 1.6-1.4 2.6-2.2 3.1.8.4 2.1 1.4 2.6 3h-1.7c-.4-1.2-1.4-2.2-2.3-2.3V11h-.4z"/></svg>
          </a>
          <a href="https://wa.me/79284175357" class="footer-social" aria-label="WhatsApp">
            <svg width="16" height="16" viewBox="0 0 16 16" fill="currentColor"><path d="M8 0a8 8 0 0 0-6.9 12l-1 4 4.1-1.1A8 8 0 1 0 8 0zm4.5 11.3c-.2.5-1.1 1-1.6 1.1-.4 0-.9.1-1.5-.1-.4-.1-.9-.3-1.5-.6-2.7-1.2-4.4-3.9-4.6-4.1-.1-.2-1-1.4-1-2.6 0-1.2.6-1.8.9-2.1.2-.2.5-.3.7-.3h.5c.2 0 .4 0 .6.5l.8 1.9c.1.1.1.3 0 .5l-.3.5c-.1.1-.2.3-.1.5.1.2.5.9 1.1 1.4.7.6 1.3.8 1.5.9.2.1.3.1.4-.1l.6-.7c.1-.2.3-.2.5-.1l1.8.9c.2.1.4.2.4.3.1.2.1.5 0 .9z"/></svg>
          </a>
          <a href="tel:+79284175357" class="footer-social" aria-label="Phone">
            <svg width="16" height="16" viewBox="0 0 16 16" fill="none" stroke="currentColor" stroke-width="1.4" stroke-linecap="round" stroke-linejoin="round"><path d="M14.5 11.3v2a1.2 1.2 0 0 1-1.3 1.2 11.9 11.9 0 0 1-5.2-1.8 11.7 11.7 0 0 1-3.6-3.6A11.9 11.9 0 0 1 2.6 4 1.2 1.2 0 0 1 3.8 2.7h2a1.2 1.2 0 0 1 1.2 1c.1.8.3 1.5.6 2.2a1.2 1.2 0 0 1-.3 1.3l-.8.8a9.5 9.5 0 0 0 3.6 3.6l.8-.8a1.2 1.2 0 0 1 1.3-.3c.7.3 1.4.5 2.2.6a1.2 1.2 0 0 1 1 1.2z"/></svg>
          </a>
        </div>
      </div>
      <div class="footer-col">
        <div class="footer-col-title">Услуги</div>
        <ul>
          <li><a href="#services">Окрашивание</a></li>
          <li><a href="#services">Стрижки и укладки</a></li>
          <li><a href="#services">Маникюр и педикюр</a></li>
          <li><a href="#services">Брови и ресницы</a></li>
          <li><a href="#services">Кератин</a></li>
        </ul>
      </div>
      <div class="footer-col">
        <div class="footer-col-title">Салон</div>
        <ul>
          <li><a href="#salon">О нас</a></li>
          <li><a href="#portfolio">Портфолио</a></li>
          <li><a href="#promo">Акции</a></li>
          <li><a href="#news">Новости</a></li>
          <li><a href="#faq">Вопросы</a></li>
        </ul>
      </div>
      <div class="footer-col">
        <div class="footer-col-title">Контакты</div>
        <ul>
          <li>ул. Советов, 25</li>
          <li>г. Новошахтинск</li>
          <li><a href="tel:+79284175357">+7 (928) 417-53-57</a></li>
          <li>Ежедневно 9:00 – 21:00</li>
        </ul>
      </div>
    </div>
    <div class="footer-bottom">
      <div class="footer-copy">© 2026 ТАТЬЯНА Beauty Salon · Новошахтинск</div>
      <div class="footer-legal">
        <a href="#">Политика конфиденциальности</a>
        <a href="#">152-ФЗ</a>
      </div>
    </div>
  </div>
</footer>

<!-- FLOATING -->
<div class="float-stack">
  <a href="https://wa.me/79284175357?text=Здравствуйте!%20Хочу%20записаться" class="float-btn float-wa" aria-label="WhatsApp">
    <svg width="26" height="26" viewBox="0 0 16 16" fill="currentColor"><path d="M8 0a8 8 0 0 0-6.9 12l-1 4 4.1-1.1A8 8 0 1 0 8 0zm4.5 11.3c-.2.5-1.1 1-1.6 1.1-.4 0-.9.1-1.5-.1-.4-.1-.9-.3-1.5-.6-2.7-1.2-4.4-3.9-4.6-4.1-.1-.2-1-1.4-1-2.6 0-1.2.6-1.8.9-2.1.2-.2.5-.3.7-.3h.5c.2 0 .4 0 .6.5l.8 1.9c.1.1.1.3 0 .5l-.3.5c-.1.1-.2.3-.1.5.1.2.5.9 1.1 1.4.7.6 1.3.8 1.5.9.2.1.3.1.4-.1l.6-.7c.1-.2.3-.2.5-.1l1.8.9c.2.1.4.2.4.3.1.2.1.5 0 .9z"/></svg>
  </a>
  <a href="tel:+79284175357" class="float-btn float-call" aria-label="Позвонить">
    <svg width="24" height="24" viewBox="0 0 16 16" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"><path d="M14.5 11.3v2a1.2 1.2 0 0 1-1.3 1.2 11.9 11.9 0 0 1-5.2-1.8 11.7 11.7 0 0 1-3.6-3.6A11.9 11.9 0 0 1 2.6 4 1.2 1.2 0 0 1 3.8 2.7h2a1.2 1.2 0 0 1 1.2 1c.1.8.3 1.5.6 2.2a1.2 1.2 0 0 1-.3 1.3l-.8.8a9.5 9.5 0 0 0 3.6 3.6l.8-.8a1.2 1.2 0 0 1 1.3-.3c.7.3 1.4.5 2.2.6a1.2 1.2 0 0 1 1 1.2z"/></svg>
  </a>
</div>

<!-- LIGHTBOX -->
<div class="lightbox" id="lightbox">
  <div class="lightbox-top">
    <span class="lightbox-counter" id="lbCounter"></span>
    <div class="lightbox-info">
      <div class="lightbox-cat" id="lbCat"></div>
      <div class="lightbox-title" id="lbTitle"></div>
      <div class="lightbox-master" id="lbMaster"></div>
    </div>
    <div>
      <button class="lightbox-close" onclick="closeLightbox()" aria-label="Закрыть">
        <svg width="20" height="20" viewBox="0 0 16 16" fill="none" stroke="currentColor" stroke-width="1.2" stroke-linecap="round"><path d="M3 3l10 10M13 3L3 13"/></svg>
      </button>
    </div>
  </div>
  <button class="lightbox-nav prev" onclick="lbPrev()" aria-label="Назад">
    <svg width="22" height="22" viewBox="0 0 16 16" fill="none" stroke="currentColor" stroke-width="1.2" stroke-linecap="round"><path d="M10 3L5 8l5 5"/></svg>
  </button>
  <div class="lightbox-img-wrap"><img id="lbImg" src="" alt=""></div>
  <button class="lightbox-nav next" onclick="lbNext()" aria-label="Вперёд">
    <svg width="22" height="22" viewBox="0 0 16 16" fill="none" stroke="currentColor" stroke-width="1.2" stroke-linecap="round"><path d="M6 3l5 5-5 5"/></svg>
  </button>
  <div class="lightbox-thumbs" id="lbThumbs"></div>
</div>

<!-- MODAL -->
<div class="modal-backdrop" id="modal" onmousedown="if(event.target===this)closeModal()">
  <div class="modal">
    <button class="modal-close" onclick="closeModal()" aria-label="Закрыть">
      <svg width="18" height="18" viewBox="0 0 16 16" fill="none" stroke="currentColor" stroke-width="1.2" stroke-linecap="round"><path d="M3 3l10 10M13 3L3 13"/></svg>
    </button>
    <div class="modal-handle"></div>
    <div class="modal-label" id="modalLabel">Booking</div>
    <h3 id="modalTitle">Записаться <em>онлайн</em></h3>
    <p class="modal-desc">Оставьте контакты — перезвоним в течение 15 минут в рабочее время и подберём удобное окно для визита.</p>
    <form onsubmit="submitForm(event)">
      <div class="form-group">
        <label for="f-name">Ваше имя</label>
        <input id="f-name" type="text" placeholder="Как к вам обращаться?" required>
      </div>
      <div class="form-group">
        <label for="f-phone">Телефон</label>
        <input id="f-phone" type="tel" placeholder="+7 (___) ___-__-__" required>
      </div>
      <div class="form-group">
        <label for="f-service">Услуга</label>
        <select id="f-service">
          <option value="">Выберите услугу</option>
          <option>Окрашивание волос</option>
          <option>Стрижка и укладка</option>
          <option>Маникюр / педикюр</option>
          <option>Брови и ресницы</option>
          <option>Кератиновое выпрямление</option>
          <option>Купить сертификат</option>
          <option>Другое / нужна консультация</option>
        </select>
      </div>
      <div class="form-group">
        <label for="f-comment">Комментарий</label>
        <textarea id="f-comment" placeholder="Удобное время, пожелания, вопросы..."></textarea>
      </div>
      <label class="form-check">
        <input type="checkbox" required>
        <span>Я даю согласие на обработку персональных данных в соответствии с <a href="#">политикой конфиденциальности</a> (152-ФЗ)</span>
      </label>
      <button type="submit" class="form-submit" id="formBtn">Отправить заявку</button>
    </form>
  </div>
</div>

<!-- COOKIE -->
<div class="cookie" id="cookie">
  <div class="cookie-inner">
    <p class="cookie-text">Этот сайт использует сервис веб-аналитики Яндекс Метрика для анализа пользовательской активности и улучшения работы сайта. Продолжая использовать сайт, вы соглашаетесь с <a href="#">политикой обработки данных</a>.</p>
    <div class="cookie-btns">
      <button class="btn-gold" onclick="acceptCookie()">Принять</button>
      <button class="btn-outline-gold" onclick="acceptCookie()">Закрыть</button>
    </div>
  </div>
</div>

<script>
const SERVICES = [
  {num:'01',name:'Окрашивание',desc:'Estel De Luxe и Sense. Балаяж, шатуш, аиртач, однотонное окрашивание. Более 140 оттенков, стойкий цвет до 6 недель.',price:'от 2 500 ₽',icon:'M8 1l2 1.5 2.5-.3.8 2.4L15 6.5l-1 2.3 1 2.3-1.7 1.4-.8 2.4-2.5-.3L8 16l-2-1.5-2.5.3-.8-2.4L1 11l1-2.3-1-2.3 1.7-1.4.8-2.4 2.5.3z'},
  {num:'02',name:'Стрижки и укладки',desc:'Женские и мужские стрижки любой сложности. Укладки на брашинг, локоны, вечерние причёски для особых случаев.',price:'от 1 200 ₽',icon:'M5 2l6 12M11 2L5 14M3 8h10'},
  {num:'03',name:'Маникюр и педикюр',desc:'Аппаратный маникюр, покрытие гель-лаком, наращивание, дизайн. Носибельность 3–4 недели. Стерильные инструменты.',price:'от 1 800 ₽',icon:'M4 8c0-2 1-4 4-4s4 2 4 4v4c0 1-1 2-2 2H6c-1 0-2-1-2-2V8z'},
  {num:'04',name:'Брови и ресницы',desc:'Ламинирование бровей, окрашивание, коррекция формы. Наращивание ресниц классика и объём 2D–3D. Долговременная укладка.',price:'от 1 500 ₽',icon:'M2 8c2-3 4-4 6-4s4 1 6 4M4 10c1-1 2-1.5 4-1.5s3 .5 4 1.5'},
  {num:'05',name:'Кератиновое выпрямление',desc:'Estel Keratin. Гладкость и зеркальный блеск до 4 месяцев без ежедневного использования утюжка. Восстановление структуры.',price:'от 5 500 ₽',icon:'M3 4h10v8H3zM5 4v8M8 4v8M11 4v8'},
  {num:'06',name:'Уходы и восстановления',desc:'Estel Otium. Маски, сыворотки, флюиды под любой тип волос. Ботокс для волос, экранирование, глазирование.',price:'от 1 500 ₽',icon:'M8 2v4M5 5l2 2M11 5l-2 2M4 10c0 2 2 4 4 4s4-2 4-4'}
];

const PORTFOLIO = [
  {id:'g1',cat:'color',title:'Балаяж на тёмные волосы',master:'Татьяна · Estel De Luxe',img:'https://image.qwenlm.ai/public_source/e6e05081-4396-49f7-886f-9607a307441b/12e94e6bb-fe76-46d7-a2b3-303446e4f4da9483.png',size:'tall'},
  {id:'g2',cat:'nails',title:'Нюдовый маникюр миндаль',master:'Анна',img:'https://image.qwenlm.ai/public_source/e6e05081-4396-49f7-886f-9607a307441b/62e94e6bb-fe76-46d7-a2b3-303446e4f4da7968.png',size:''},
  {id:'g3',cat:'cut',title:'Каре с текстурной укладкой',master:'Марина',img:'https://image.qwenlm.ai/public_source/e6e05081-4396-49f7-886f-9607a307441b/52e94e6bb-fe76-46d7-a2b3-303446e4f4da9407.png',size:''},
  {id:'g4',cat:'color',title:'Аиртач блонд',master:'Татьяна',img:'https://image.qwenlm.ai/public_source/e6e05081-4396-49f7-886f-9607a307441b/72e94e6bb-fe76-46d7-a2b3-303446e4f4da1253.png',size:'wide'},
  {id:'g5',cat:'brows',title:'Ламинирование бровей',master:'Юлия',img:'https://image.qwenlm.ai/public_source/e6e05081-4396-49f7-886f-9607a307441b/22e94e6bb-fe76-46d7-a2b3-303446e4f4da7243.png',size:''},
  {id:'g6',cat:'nails',title:'Френч на короткие ногти',master:'Анна',img:'https://image.qwenlm.ai/public_source/e6e05081-4396-49f7-886f-9607a307441b/42e94e6bb-fe76-46d7-a2b3-303446e4f4da3573.png',size:''},
  {id:'g7',cat:'color',title:'Шатуш на русые волосы',master:'Татьяна',img:'https://image.qwenlm.ai/public_source/e6e05081-4396-49f7-886f-9607a307441b/22e94e6bb-fe76-46d7-a2b3-303446e4f4da2488.png',size:'tall'},
  {id:'g8',cat:'cut',title:'Боб-каре с челкой',master:'Марина',img:'https://image.qwenlm.ai/public_source/e6e05081-4396-49f7-886f-9607a307441b/42e94e6bb-fe76-46d7-a2b3-303446e4f4da4644.png',size:''},
  {id:'g9',cat:'nails',title:'Маникюр кошачий глаз',master:'Анна',img:'https://image.qwenlm.ai/public_source/e6e05081-4396-49f7-886f-9607a307441b/02e94e6bb-fe76-46d7-a2b3-303446e4f4da1005.png',size:''},
  {id:'g10',cat:'color',title:'Холодный блонд Estel',master:'Татьяна',img:'https://image.qwenlm.ai/public_source/e6e05081-4396-49f7-886f-9607a307441b/02e94e6bb-fe76-46d7-a2b3-303446e4f4da2125.png',size:'wide'},
  {id:'g11',cat:'brows',title:'Ламинирование плюс ресницы',master:'Юлия',img:'https://image.qwenlm.ai/public_source/e6e05081-4396-49f7-886f-9607a307441b/02e94e6bb-fe76-46d7-a2b3-303446e4f4da3375.png',size:''},
  {id:'g12',cat:'cut',title:'Пикси с удлинённой челкой',master:'Марина',img:'https://image.qwenlm.ai/public_source/e6e05081-4396-49f7-886f-9607a307441b/22e94e6bb-fe76-46d7-a2b3-303446e4f4da9219.png',size:''}
];

const NEWS = [
  {tag:'Event',date:'15 ноября 2026',title:'ТАТЬЯНА — официальный партнёр конкурса «Мисс Новошахтинск 2026»',excerpt:'Наши мастера отвечали за образы финалисток городского конкурса красоты. Балаяж, вечерние укладки и макияж для выхода на сцену.',img:'https://image.qwenlm.ai/public_source/e6e05081-4396-49f7-886f-9607a307441b/12e94e6bb-fe76-46d7-a2b3-303446e4f4da9483.png'},
  {tag:'Education',date:'2 ноября 2026',title:'Татьяна прошла обучение в академии Estel Professional',excerpt:'Основатель салона получила сертификат Estel Color Expert после интенсивного курса по современным техникам окрашивания в Москве.',img:'https://image.qwenlm.ai/public_source/e6e05081-4396-49f7-886f-9607a307441b/52e94e6bb-fe76-46d7-a2b3-303446e4f4da8270.png'},
  {tag:'News',date:'20 октября 2026',title:'Запустили услугу кератинового выпрямления на Estel Keratin',excerpt:'Теперь в салоне доступна процедура кератинового выпрямления и восстановления волос. Гладкость и блеск до 4 месяцев без утюжка.',img:'https://image.qwenlm.ai/public_source/e6e05081-4396-49f7-886f-9607a307441b/72e94e6bb-fe76-46d7-a2b3-303446e4f4da1253.png'},
  {tag:'Event',date:'8 октября 2026',title:'ТАТЬЯНА — стилист показа местной недели моды',excerpt:'Команда салона создала образы для моделей на показе молодых дизайнеров Новошахтинска. Текстурные укладки и смелые цветовые решения.',img:'https://image.qwenlm.ai/public_source/e6e05081-4396-49f7-886f-9607a307441b/52e94e6bb-fe76-46d7-a2b3-303446e4f4da9407.png'},
  {tag:'Promo',date:'25 сентября 2026',title:'Осенняя акция: комплекс «Цвет и уход» со скидкой 25%',excerpt:'До конца ноября окрашивание Estel De Luxe плюс восстанавливающий уход Otium в одном визите по специальной цене. Успейте записаться.',img:'https://image.qwenlm.ai/public_source/e6e05081-4396-49f7-886f-9607a307441b/22e94e6bb-fe76-46d7-a2b3-303446e4f4da2488.png'},
  {tag:'News',date:'10 сентября 2026',title:'Расширили команду: новый мастер по маникюру Анна',excerpt:'Рады представить Анну — сертифицированного мастера ногтевого сервиса с опытом 6 лет. Уже принимает запись на маникюр и наращивание.',img:'https://image.qwenlm.ai/public_source/e6e05081-4396-49f7-886f-9607a307441b/62e94e6bb-fe76-46d7-a2b3-303446e4f4da7968.png'}
];

const FAQS = [
  {q:'Есть ли у вас система лояльности?',a:'Да, для постоянных клиентов салона ТАТЬЯНА действует накопительная система лояльности. После каждого визита на вашу карту начисляются баллы, которые можно тратить на оплату услуг. Подробности уточняйте у администратора.'},
  {q:'Как оставить отзыв?',a:'Вы можете оставить отзыв через форму обратной связи на сайте, в наших социальных сетях (Instagram, VK), на Яндекс.Картах и 2GIS, либо напрямую администратору после визита. Нам важно каждое мнение.'},
  {q:'Какие услуги предоставляются?',a:'В салоне доступны стрижки, укладки, окрашивание (балаяж, шатуш, аиртач, однотонное), уходы Estel Otium, кератиновое выпрямление, маникюр и педикюр, наращивание ногтей, брови и ресницы, ламинирование.'},
  {q:'Как я могу записаться?',a:'Вы можете записаться онлайн через форму на сайте, позвонить по телефону +7 (928) 417-53-57, написать в WhatsApp или Direct в Instagram. Мы перезвоним в течение 15 минут в рабочее время.'},
  {q:'На какой косметике вы работаете?',a:'Мы работаем исключительно на профессиональной косметике Estel Professional — российском бренде, на котором обучаются мастера по всей стране. Линейки De Luxe, Sense, Otium, Keratin.'},
  {q:'Как проходит стерилизация инструментов?',a:'Инструменты проходят 4 этапа по СанПиН 2.1.3678-20: дезинфекция, предстерилизационная очистка, упаковка в крафт-пакеты и автоклавирование при 134°C. Крафт-пакет вскрывается при вас перед процедурой.'},
  {q:'Можно ли купить подарочный сертификат?',a:'Да, подарочные сертификаты доступны номиналом от 1 000 ₽. Можно купить в салоне или заказать доставку. Сертификат действует 6 месяцев на любые услуги салона.'}
];

function renderServices(){
  document.getElementById('servicesGrid').innerHTML = SERVICES.map(s=>`
    <div class="service-item" onclick="openModal('Записаться на: ${s.name}')">
      <div class="service-num">${s.num}</div>
      <svg class="service-icon" viewBox="0 0 16 16" fill="none" stroke="currentColor" stroke-width="1.2" stroke-linecap="round" stroke-linejoin="round"><path d="${s.icon}"/></svg>
      <h3 class="service-name">${s.name}</h3>
      <p class="service-desc">${s.desc}</p>
      <div class="service-price">${s.price}</div>
      <svg class="service-arrow" width="20" height="20" viewBox="0 0 16 16" fill="none" stroke="currentColor" stroke-width="1.2" stroke-linecap="round"><path d="M3 8h10M9 4l4 4-4 4"/></svg>
    </div>
  `).join('');
}

function catLabel(c){return {color:'Окрашивание',cut:'Стрижка',nails:'Маникюр',brows:'Брови'}[c]||c}

function renderPortfolio(filter='all'){
  const items = filter==='all' ? PORTFOLIO : PORTFOLIO.filter(g=>g.cat===filter);
  document.getElementById('portfolioGrid').innerHTML = items.map(g=>`
    <button class="portfolio-item ${g.size}" onclick="openLightbox(${PORTFOLIO.indexOf(g)})" aria-label="${g.title}">
      <img src="${g.img}" alt="${g.title}" loading="lazy">
      <div class="portfolio-overlay">
        <div class="portfolio-cat">${catLabel(g.cat)}</div>
        <div class="portfolio-title">${g.title}</div>
        <div class="portfolio-master">${g.master}</div>
      </div>
    </button>
  `).join('');
}

function renderNews(){
  document.getElementById('newsGrid').innerHTML = NEWS.map(n=>`
    <article class="news-card">
      <div class="news-img">
        <img src="${n.img}" alt="${n.title}" loading="lazy">
        <span class="news-tag">${n.tag}</span>
      </div>
      <div class="news-body">
        <div class="news-date">${n.date}</div>
        <h3 class="news-title">${n.title}</h3>
        <p class="news-excerpt">${n.excerpt}</p>
        <span class="news-more">Читать далее <svg width="14" height="14" viewBox="0 0 16 16" fill="none" stroke="currentColor" stroke-width="1.4" stroke-linecap="round"><path d="M3 8h10M9 4l4 4-4 4"/></svg></span>
      </div>
    </article>
  `).join('');
}

function renderFaq(){
  document.getElementById('faqList').innerHTML = FAQS.map((f,i)=>`
    <div class="faq-item" data-i="${i}">
      <button class="faq-q" onclick="toggleFaq(${i})">
        <span>${f.q}</span>
        <span class="faq-icon"><svg width="14" height="14" viewBox="0 0 16 16" fill="none" stroke="currentColor" stroke-width="1.4" stroke-linecap="round"><path d="M8 3v10M3 8h10"/></svg></span>
      </button>
      <div class="faq-a"><p>${f.a}</p></div>
    </div>
  `).join('');
}

function toggleFaq(i){
  const item = document.querySelector(`.faq-item[data-i="${i}"]`);
  const wasOpen = item.classList.contains('open');
  document.querySelectorAll('.faq-item').forEach(el=>el.classList.remove('open'));
  if(!wasOpen) item.classList.add('open');
}

document.addEventListener('click', e=>{
  if(e.target.classList.contains('portfolio-filter')){
    document.querySelectorAll('.portfolio-filter').forEach(b=>b.classList.remove('active'));
    e.target.classList.add('active');
    renderPortfolio(e.target.dataset.filter);
  }
});

let heroIdx = 0;
const heroSlides = () => document.querySelectorAll('.hero-slide');
function initHero(){
  const dots = document.getElementById('heroDots');
  dots.innerHTML = heroSlides().map((_,i)=>`<button class="hero-dot ${i===0?'active':''}" onclick="goHero(${i})" aria-label="Слайд ${i+1}"></button>`).join('');
  setInterval(()=>goHero((heroIdx+1)%heroSlides().length), 6000);
}
function goHero(i){
  heroSlides().forEach((s,idx)=>s.classList.toggle('active', idx===i));
  document.querySelectorAll('.hero-dot').forEach((d,idx)=>d.classList.toggle('active', idx===i));
  document.getElementById('heroCurrent').textContent = String(i+1).padStart(2,'0');
  heroIdx = i;
}

let lbIndex = 0, lbFiltered = PORTFOLIO;
function openLightbox(globalIdx){
  const f = document.querySelector('.portfolio-filter.active').dataset.filter;
  lbFiltered = f==='all' ? PORTFOLIO : PORTFOLIO.filter(g=>g.cat===f);
  const item = PORTFOLIO[globalIdx];
  lbIndex = lbFiltered.findIndex(g=>g.id===item.id);
  if(lbIndex<0) lbIndex = 0;
  updateLightbox();
  document.getElementById('lightbox').classList.add('open');
  document.body.style.overflow = 'hidden';
}
function closeLightbox(){
  document.getElementById('lightbox').classList.remove('open');
  document.body.style.overflow = '';
}
function updateLightbox(){
  const item = lbFiltered[lbIndex];
  document.getElementById('lbImg').src = item.img;
  document.getElementById('lbImg').alt = item.title;
  document.getElementById('lbCat').textContent = catLabel(item.cat);
  document.getElementById('lbTitle').textContent = item.title;
  document.getElementById('lbMaster').textContent = item.master;
  document.getElementById('lbCounter').textContent = `${String(lbIndex+1).padStart(2,'0')} / ${String(lbFiltered.length).padStart(2,'0')}`;
  document.getElementById('lbThumbs').innerHTML = lbFiltered.map((g,i)=>`
    <button class="lightbox-thumb ${i===lbIndex?'active':''}" onclick="lbGo(${i})"><img src="${g.img}" alt=""></button>
  `).join('');
}
function lbPrev(){ lbIndex = (lbIndex-1+lbFiltered.length)%lbFiltered.length; updateLightbox(); }
function lbNext(){ lbIndex = (lbIndex+1)%lbFiltered.length; updateLightbox(); }
function lbGo(i){ lbIndex = i; updateLightbox(); }
document.addEventListener('keydown', e=>{
  if(!document.getElementById('lightbox').classList.contains('open')) return;
  if(e.key==='Escape') closeLightbox();
  else if(e.key==='ArrowLeft') lbPrev();
  else if(e.key==='ArrowRight') lbNext();
});
let touchX = 0;
document.getElementById('lightbox').addEventListener('touchstart', e=>{ touchX = e.touches[0].clientX; });
document.getElementById('lightbox').addEventListener('touchend', e=>{
  const dx = e.changedTouches[0].clientX - touchX;
  if(Math.abs(dx)>50) (dx>0?lbPrev:lbNext)();
});

function openModal(title){
  document.getElementById('modal').classList.add('open');
  document.body.style.overflow = 'hidden';
  if(title){
    const t = title.split(' ');
    const last = t.pop();
    document.getElementById('modalTitle').innerHTML = t.join(' ') + ' <em>' + last + '</em>';
    document.getElementById('modalLabel').textContent = 'Booking';
  }
}
function closeModal(){
  document.getElementById('modal').classList.remove('open');
  document.body.style.overflow = '';
}
document.addEventListener('keydown', e=>{
  if(e.key==='Escape'){ closeModal(); closeMenu(); }
});

function submitForm(e){
  e.preventDefault();
  const btn = document.getElementById('formBtn');
  const phone = document.getElementById('f-phone').value.replace(/\D/g,'');
  const name = document.getElementById('f-name').value.trim();
  if(phone.length<11 || !name) return;
  btn.textContent = 'Отправляем...';
  btn.disabled = true;
  setTimeout(()=>{
    btn.textContent = '✓ Заявка отправлена';
    btn.classList.add('success');
    setTimeout(()=>{
      closeModal();
      btn.textContent = 'Отправить заявку';
      btn.classList.remove('success');
      btn.disabled = false;
      e.target.reset();
    }, 1800);
  }, 800);
}

document.getElementById('f-phone').addEventListener('input', function(e){
  let v = e.target.value.replace(/\D/g,'');
  if(v.length>0){
    if(v[0]==='7'||v[0]==='8') v = v.substring(1);
    let f = '+7';
    if(v.length>0) f += ' ('+v.substring(0,3);
    if(v.length>=3) f += ') '+v.substring(3,6);
    if(v.length>=6) f += '-'+v.substring(6,8);
    if(v.length>=8) f += '-'+v.substring(8,10);
    e.target.value = f;
  }
});

function openMenu(){
  document.getElementById('mobBackdrop').classList.add('open');
  document.getElementById('mobPanel').classList.add('open');
  document.body.style.overflow = 'hidden';
}
function closeMenu(){
  document.getElementById('mobBackdrop').classList.remove('open');
  document.getElementById('mobPanel').classList.remove('open');
  document.body.style.overflow = '';
}
function scrollTop(e){ e.preventDefault(); window.scrollTo({top:0,behavior:'smooth'}); }

function acceptCookie(){
  document.getElementById('cookie').classList.remove('show');
  localStorage.setItem('cookie_accepted','1');
}

renderServices();
renderPortfolio();
renderNews();
renderFaq();
initHero();

if(!localStorage.getItem('cookie_accepted')){
  setTimeout(()=>document.getElementById('cookie').classList.add('show'), 1500);
}

(function(){
  const h = new Date().getHours();
  const day = new Date().getDay();
  let open = false;
  if(day>=1 && day<=5) open = h>=9 && h<21;
  else if(day===6) open = h>=10 && h<20;
  else open = h>=10 && h<18;
  document.querySelectorAll('.salon-status').forEach(el=>{
    if(!open){
      el.innerHTML = '<span class="salon-status-dot" style="background:#C08B84;animation:none"></span> Сейчас закрыто';
      el.style.color = '#C08B84';
    }
  });
})();
</script>
</body>
</html>
