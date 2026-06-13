<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Hotel Arawali Hill | Udaipur, Rajasthan</title>
<meta name="description" content="Book Hotel Arawali Hill in Ambavgarh, Udaipur. Hill-view rooms, authentic Rajasthani restaurant, 4.6★ Google rating. Steps from Fateh Sagar Lake. Free cancellation.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,400;0,600;0,700;1,400;1,600&family=DM+Sans:wght@300;400;500&display=swap" rel="stylesheet">
<style>
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
:root{
  --slate:#1C1F26;
  --sand:#F2EBD9;
  --gold:#C9884A;
  --gold-dark:#A36B2E;
  --ivory:#FDFAF4;
  --sage:#8A9E8B;
  --white:#ffffff;
  --r-display:'Cormorant Garamond',Georgia,serif;
  --r-body:'DM Sans',system-ui,sans-serif;
}
html{scroll-behavior:smooth;font-size:16px}
body{font-family:var(--r-body);background:var(--ivory);color:var(--slate);overflow-x:hidden}

/* NAV */
nav{position:fixed;top:0;left:0;right:0;z-index:1000;padding:20px 5%;display:flex;align-items:center;justify-content:space-between;transition:background 0.4s,padding 0.4s,backdrop-filter 0.4s}
nav.scrolled{background:rgba(28,31,38,0.95);backdrop-filter:blur(12px);padding:14px 5%}
.nav-logo{display:flex;flex-direction:column;gap:2px;text-decoration:none}
.nav-logo-main{font-family:var(--r-display);font-size:22px;font-weight:700;color:var(--ivory);letter-spacing:0.08em;line-height:1}
.nav-logo-hindi{font-size:11px;color:var(--sage);letter-spacing:0.05em;font-weight:400}
.nav-links{display:flex;align-items:center;gap:36px}
.nav-link{color:rgba(253,250,244,0.8);text-decoration:none;font-size:14px;font-weight:400;letter-spacing:0.04em;position:relative;padding-bottom:3px;transition:color 0.3s;cursor:pointer}
.nav-link::after{content:'';position:absolute;bottom:0;left:0;width:0;height:1px;background:var(--gold);transition:width 0.3s ease}
.nav-link:hover,.nav-link.active{color:var(--ivory)}
.nav-link:hover::after,.nav-link.active::after{width:100%}
.nav-book{background:var(--gold);color:var(--ivory);padding:10px 24px;border-radius:4px;font-size:13px;font-weight:500;text-decoration:none;transition:background 0.3s,transform 0.2s;letter-spacing:0.04em;cursor:pointer;border:none}
.nav-book:hover{background:var(--gold-dark);transform:translateY(-1px)}
.nav-hamburger{display:none;flex-direction:column;gap:5px;cursor:pointer;padding:6px}
.nav-hamburger span{width:24px;height:1.5px;background:var(--ivory);transition:all 0.3s}
.mobile-menu{display:none;position:fixed;inset:0;background:var(--slate);z-index:999;flex-direction:column;align-items:center;justify-content:center;gap:32px;opacity:0;transition:opacity 0.3s}
.mobile-menu.open{display:flex;opacity:1}
.mobile-menu .nav-link{font-size:22px;font-family:var(--r-display);font-weight:600;color:var(--ivory)}

/* PAGES */
.page{display:none;min-height:100vh}
.page.active{display:block}

/* HERO */
.hero{position:relative;height:100vh;min-height:600px;display:flex;align-items:center;justify-content:center;overflow:hidden;background:var(--slate)}
.hero-bg{position:absolute;inset:0;background:linear-gradient(160deg,#1a2535 0%,#2d3a28 40%,#3d2e1a 80%,#1C1F26 100%);z-index:0}
.hero-pattern{position:absolute;inset:0;z-index:1;opacity:0.06}
.hero-overlay{position:absolute;inset:0;background:linear-gradient(to bottom,rgba(28,31,38,0.3) 0%,rgba(28,31,38,0.1) 50%,rgba(28,31,38,0.7) 100%);z-index:2}
.hero-content{position:relative;z-index:3;text-align:center;padding:0 20px;max-width:780px}
.hero-eyebrow{font-size:11px;letter-spacing:0.22em;color:var(--sage);text-transform:uppercase;margin-bottom:20px;font-weight:400;opacity:0;animation:fadeUp 0.8s 0.2s forwards}
.hero h1{font-family:var(--r-display);font-size:clamp(44px,7vw,80px);font-weight:700;color:var(--ivory);line-height:1.08;margin-bottom:24px;opacity:0;animation:fadeUp 0.8s 0.4s forwards}
.hero-sub{font-size:clamp(15px,2vw,18px);color:rgba(253,250,244,0.75);line-height:1.7;max-width:540px;margin:0 auto 40px;font-weight:300;opacity:0;animation:fadeUp 0.8s 0.6s forwards}
.hero-ctas{display:flex;gap:16px;justify-content:center;flex-wrap:wrap;opacity:0;animation:fadeUp 0.8s 0.8s forwards}
.hero-badge{margin-top:32px;display:inline-flex;align-items:center;gap:8px;background:rgba(253,250,244,0.1);border:1px solid rgba(253,250,244,0.15);border-radius:100px;padding:8px 20px;opacity:0;animation:fadeUp 0.8s 1s forwards}
.hero-badge span{font-size:13px;color:var(--ivory);font-weight:400}
.stars{color:var(--gold);font-size:14px;letter-spacing:1px}
.scroll-hint{position:absolute;bottom:32px;left:50%;transform:translateX(-50%);z-index:3;animation:bounce 2s infinite}
.scroll-hint div{width:1px;height:60px;background:linear-gradient(to bottom,transparent,rgba(201,136,74,0.6));margin:0 auto}

/* SVG HILL DIVIDER */
.hill-divider{display:block;width:100%;height:40px;overflow:hidden;line-height:0}
.hill-divider svg{display:block;width:100%;height:40px}

/* SECTIONS */
.section{padding:90px 5%}
.section-sm{padding:60px 5%}
.section-center{text-align:center}
.eyebrow{font-size:11px;letter-spacing:0.2em;text-transform:uppercase;color:var(--sage);font-weight:400;margin-bottom:14px;display:block}
.section h2{font-family:var(--r-display);font-size:clamp(34px,4.5vw,50px);font-weight:700;line-height:1.1;color:var(--slate);margin-bottom:16px}
.section h2.light{color:var(--ivory)}
.section-lead{font-size:17px;color:var(--sage);line-height:1.7;max-width:560px;margin:0 auto 56px;font-weight:300}

/* FEATURES GRID */
.features-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:28px;margin-top:56px}
.feature-card{background:var(--white);border-radius:4px;padding:40px 36px;border-top:3px solid var(--gold);transition:transform 0.4s ease,box-shadow 0.4s ease;cursor:default}
.feature-card:hover{transform:perspective(800px) translateY(-6px);box-shadow:0 20px 50px rgba(28,31,38,0.12)}
.feature-icon{font-size:28px;margin-bottom:20px;line-height:1}
.feature-card h3{font-family:var(--r-display);font-size:22px;font-weight:700;color:var(--slate);margin-bottom:12px}
.feature-card p{font-size:15px;color:#5a6070;line-height:1.7;font-weight:300}

/* SPLIT SECTIONS */
.split{display:grid;grid-template-columns:1fr 1fr;gap:0;align-items:center;min-height:520px}
.split.reverse{direction:rtl}
.split.reverse>*{direction:ltr}
.split-img{height:100%;min-height:500px;position:relative;overflow:hidden;background:var(--slate)}
.split-img-inner{width:100%;height:100%;object-fit:cover;display:block;transition:transform 0.8s ease}
.split:hover .split-img-inner{transform:scale(1.03)}
.split-img-placeholder{width:100%;height:100%;min-height:500px;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:12px;color:var(--sage);font-size:13px;letter-spacing:0.1em;text-transform:uppercase;font-weight:400}
.split-img-placeholder .icon{font-size:40px;opacity:0.4}
.split-content{padding:64px 56px;background:var(--ivory)}
.split-content .eyebrow{color:var(--gold)}
.split-content h3{font-family:var(--r-display);font-size:36px;font-weight:700;line-height:1.1;color:var(--slate);margin-bottom:20px}
.split-content p{font-size:15px;color:#5a6070;line-height:1.8;margin-bottom:28px;font-weight:300}
.specs-row{display:flex;flex-wrap:wrap;gap:10px;margin-bottom:32px}
.spec-pill{background:var(--sand);color:var(--slate);font-size:12px;padding:6px 14px;border-radius:100px;font-weight:400;letter-spacing:0.02em}
.info-pills{display:flex;flex-wrap:wrap;gap:10px;margin-bottom:32px}
.info-pill{background:rgba(201,136,74,0.1);border:1px solid rgba(201,136,74,0.3);color:var(--gold-dark);font-size:12px;padding:6px 14px;border-radius:100px;font-weight:500}

/* DISH TEASER */
.dishes-section{background:var(--slate);padding:90px 5%}
.dishes-section h2{color:var(--ivory);text-align:center;font-family:var(--r-display);font-size:clamp(34px,4.5vw,50px);font-weight:700;margin-bottom:12px}
.dishes-lead{text-align:center;color:var(--sage);font-size:16px;margin-bottom:56px;font-weight:300;line-height:1.6}
.dishes-strip{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:24px}
.dish-card{background:rgba(255,255,255,0.04);border:1px solid rgba(255,255,255,0.08);border-radius:4px;padding:36px 28px;transition:background 0.3s,border-color 0.3s,transform 0.3s}
.dish-card:hover{background:rgba(255,255,255,0.08);border-color:rgba(201,136,74,0.3);transform:translateY(-4px)}
.dish-tag{font-size:11px;letter-spacing:0.15em;text-transform:uppercase;margin-bottom:14px;display:inline-block;padding:4px 12px;border-radius:100px}
.dish-tag.veg{background:rgba(138,158,139,0.15);color:var(--sage)}
.dish-tag.nonveg{background:rgba(201,136,74,0.15);color:var(--gold)}
.dish-card h3{font-family:var(--r-display);font-size:24px;font-weight:700;color:var(--ivory);margin-bottom:10px}
.dish-card p{font-size:14px;color:rgba(253,250,244,0.55);line-height:1.7;font-weight:300}

/* INSTAGRAM */
.insta-section{padding:90px 5%;background:var(--sand)}
.insta-section h2{font-family:var(--r-display);font-size:clamp(30px,4vw,44px);font-weight:700;color:var(--slate);margin-bottom:12px;text-align:center}
.insta-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:12px;margin:40px 0}
.insta-cell{aspect-ratio:1;background:var(--slate);border-radius:4px;overflow:hidden;position:relative;cursor:pointer}
.insta-cell-inner{width:100%;height:100%;display:flex;align-items:center;justify-content:center;transition:transform 0.5s ease}
.insta-overlay{position:absolute;inset:0;background:rgba(28,31,38,0.7);display:flex;flex-direction:column;align-items:center;justify-content:center;gap:8px;opacity:0;transition:opacity 0.3s}
.insta-cell:hover .insta-overlay{opacity:1}
.insta-cell:hover .insta-cell-inner{transform:scale(1.06)}
.insta-icon{font-size:22px;color:var(--ivory)}
.insta-caption{font-size:12px;color:rgba(253,250,244,0.7);text-align:center;padding:0 16px;line-height:1.5}
.insta-patterns{width:100%;height:100%;background:linear-gradient(135deg,#2a3040 25%,#1a2535 100%);position:relative;overflow:hidden}
.insta-patterns::before{content:'';position:absolute;inset:0;background-image:radial-gradient(circle at 30% 40%, rgba(201,136,74,0.15) 0%, transparent 50%), radial-gradient(circle at 70% 70%, rgba(138,158,139,0.1) 0%, transparent 50%)}

/* REVIEWS */
.reviews-section{padding:90px 5%;background:var(--ivory)}
.reviews-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:24px;margin-top:48px}
.review-card{background:var(--white);border-radius:4px;padding:36px 32px;border-left:3px solid var(--gold)}
.review-stars{color:var(--gold);font-size:16px;letter-spacing:2px;margin-bottom:20px}
.review-text{font-family:var(--r-display);font-size:18px;font-style:italic;color:var(--slate);line-height:1.6;margin-bottom:20px}
.review-author{font-size:13px;color:var(--sage);font-weight:500;letter-spacing:0.05em}
.google-badge{display:inline-flex;align-items:center;gap:8px;background:var(--sand);border-radius:100px;padding:8px 18px;font-size:12px;color:var(--slate);font-weight:500;margin-top:8px}

/* LOCATION TEASER */
.location-teaser{background:var(--slate);padding:90px 5%}
.location-inner{display:grid;grid-template-columns:1fr 1fr;gap:56px;align-items:center}
.map-placeholder{background:rgba(255,255,255,0.05);border:1px solid rgba(255,255,255,0.1);border-radius:4px;height:340px;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:12px;color:var(--sage);font-size:13px;letter-spacing:0.1em;text-align:center;overflow:hidden;position:relative}
.map-embed{width:100%;height:100%;border:none;border-radius:4px;filter:grayscale(20%)}
.location-info h2{font-family:var(--r-display);font-size:36px;font-weight:700;color:var(--ivory);margin-bottom:16px}
.location-info p{font-size:15px;color:rgba(253,250,244,0.6);line-height:1.8;margin-bottom:28px;font-weight:300}
.contact-line{display:flex;align-items:center;gap:12px;margin-bottom:14px;color:var(--ivory);font-size:15px}
.contact-line a{color:var(--gold);text-decoration:none;transition:color 0.2s}
.contact-line a:hover{color:var(--ivory)}

/* CTA BANNER */
.cta-banner{background:var(--gold);padding:80px 5%;text-align:center}
.cta-banner h2{font-family:var(--r-display);font-size:clamp(30px,4vw,48px);font-weight:700;color:var(--ivory);margin-bottom:16px}
.cta-banner p{font-size:17px;color:rgba(253,250,244,0.85);margin-bottom:36px;font-weight:300;line-height:1.6}
.cta-buttons{display:flex;gap:16px;justify-content:center;flex-wrap:wrap}

/* BUTTONS */
.btn{display:inline-flex;align-items:center;gap:8px;padding:14px 32px;border-radius:4px;font-size:14px;font-weight:500;letter-spacing:0.04em;text-decoration:none;transition:all 0.3s;cursor:pointer;border:none;font-family:var(--r-body)}
.btn-primary{background:var(--gold);color:var(--ivory)}
.btn-primary:hover{background:var(--gold-dark);transform:translateY(-2px);box-shadow:0 8px 24px rgba(201,136,74,0.35)}
.btn-ghost{background:transparent;color:var(--gold);border:1.5px solid var(--gold)}
.btn-ghost:hover{background:var(--gold);color:var(--ivory);transform:translateY(-2px)}
.btn-ghost-light{background:transparent;color:var(--ivory);border:1.5px solid rgba(253,250,244,0.5)}
.btn-ghost-light:hover{background:rgba(253,250,244,0.1);border-color:var(--ivory)}
.btn-dark{background:var(--slate);color:var(--ivory)}
.btn-dark:hover{background:#0e1117;transform:translateY(-2px)}
.btn-sm{padding:10px 22px;font-size:13px}

/* FOOTER */
footer{background:var(--slate);padding:70px 5% 32px;color:rgba(253,250,244,0.6)}
.footer-grid{display:grid;grid-template-columns:1.5fr 1fr 1fr 1fr;gap:48px;margin-bottom:56px}
.footer-brand p{font-size:14px;line-height:1.8;margin-top:14px;font-weight:300}
.footer-col h4{font-size:12px;letter-spacing:0.15em;text-transform:uppercase;color:var(--ivory);margin-bottom:20px;font-weight:500}
.footer-col ul{list-style:none;display:flex;flex-direction:column;gap:10px}
.footer-col ul li a,.footer-col ul li{font-size:14px;color:rgba(253,250,244,0.55);text-decoration:none;transition:color 0.2s;cursor:pointer}
.footer-col ul li a:hover{color:var(--gold)}
.footer-col p{font-size:14px;line-height:1.8;font-weight:300}
.social-links{display:flex;gap:14px;margin-top:20px}
.social-link{width:36px;height:36px;background:rgba(255,255,255,0.05);border:1px solid rgba(255,255,255,0.1);border-radius:4px;display:flex;align-items:center;justify-content:center;color:rgba(253,250,244,0.6);font-size:16px;text-decoration:none;transition:all 0.3s;cursor:pointer}
.social-link:hover{background:var(--gold);border-color:var(--gold);color:var(--ivory)}
.footer-bottom{border-top:1px solid rgba(255,255,255,0.06);padding-top:28px;display:flex;justify-content:space-between;align-items:center;flex-wrap:gap;gap:12px}
.footer-bottom p{font-size:13px}

/* FLOATING WHATSAPP */
.wa-btn{position:fixed;bottom:28px;right:28px;z-index:900;width:54px;height:54px;background:#25D366;border-radius:50%;display:flex;align-items:center;justify-content:center;box-shadow:0 4px 20px rgba(37,211,102,0.4);transition:transform 0.3s,box-shadow 0.3s;text-decoration:none;color:white;font-size:24px}
.wa-btn:hover{transform:scale(1.1);box-shadow:0 8px 30px rgba(37,211,102,0.5)}

/* MENU PAGE */
.menu-hero{height:55vh;min-height:420px;background:linear-gradient(160deg,#2d3a28 0%,#3d2e1a 60%,#1C1F26 100%);display:flex;align-items:center;justify-content:center;text-align:center;position:relative;overflow:hidden}
.menu-hero::before{content:'';position:absolute;inset:0;background:rgba(28,31,38,0.5)}
.menu-hero-content{position:relative;z-index:1;padding:0 20px}
.menu-hero h1{font-family:var(--r-display);font-size:clamp(40px,6vw,68px);font-weight:700;color:var(--ivory);margin-bottom:16px;line-height:1.1}
.menu-hero p{font-size:16px;color:rgba(253,250,244,0.7);font-weight:300;max-width:500px;margin:0 auto;line-height:1.7}
.menu-tabs{background:var(--white);border-bottom:1px solid rgba(28,31,38,0.08);padding:0 5%;display:flex;gap:0;position:sticky;top:68px;z-index:100}
.tab-btn{padding:20px 32px;font-size:15px;font-weight:400;color:var(--sage);background:none;border:none;cursor:pointer;border-bottom:2px solid transparent;transition:all 0.3s;font-family:var(--r-body);letter-spacing:0.02em}
.tab-btn.active{color:var(--gold);border-bottom-color:var(--gold);font-weight:500}
.tab-btn:hover:not(.active){color:var(--slate)}
.tab-content{display:none;padding:60px 5% 80px}
.tab-content.active{display:block}
.subtab-bar{display:flex;gap:12px;margin-bottom:48px}
.subtab-btn{padding:10px 24px;border-radius:100px;font-size:13px;font-weight:500;cursor:pointer;transition:all 0.3s;border:1.5px solid;font-family:var(--r-body);letter-spacing:0.03em}
.subtab-btn.veg{border-color:var(--sage);color:var(--sage);background:transparent}
.subtab-btn.veg.active{background:var(--sage);color:var(--white)}
.subtab-btn.nonveg{border-color:var(--gold);color:var(--gold);background:transparent}
.subtab-btn.nonveg.active{background:var(--gold);color:var(--white)}
.menu-subcontent{display:none}
.menu-subcontent.active{display:block}
.menu-category{margin-bottom:52px}
.menu-category-title{font-family:var(--r-display);font-size:26px;font-weight:700;color:var(--slate);margin-bottom:8px;padding-bottom:12px;border-bottom:1px solid rgba(28,31,38,0.1)}
.menu-items{display:grid;grid-template-columns:repeat(auto-fill,minmax(280px,1fr));gap:16px;margin-top:24px}
.menu-item{background:var(--white);border-radius:4px;padding:22px 24px;border:1px solid rgba(28,31,38,0.06);transition:border-color 0.3s,transform 0.3s}
.menu-item:hover{border-color:rgba(201,136,74,0.3);transform:translateY(-2px)}
.menu-item h4{font-family:var(--r-display);font-size:18px;font-weight:600;color:var(--slate);margin-bottom:6px}
.menu-item p{font-size:13px;color:var(--sage);font-weight:300;line-height:1.6}
.veg-dot{display:inline-block;width:10px;height:10px;background:var(--sage);border-radius:50%;margin-right:8px;vertical-align:middle}
.nonveg-dot{display:inline-block;width:10px;height:10px;background:var(--gold);border-radius:50%;margin-right:8px;vertical-align:middle}
.bev-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(220px,1fr));gap:16px}
.bev-card{background:var(--white);border-radius:4px;padding:24px;border:1px solid rgba(28,31,38,0.06);transition:all 0.3s}
.bev-card:hover{border-color:rgba(201,136,74,0.3);transform:translateY(-2px)}
.bev-card h4{font-family:var(--r-display);font-size:17px;font-weight:600;color:var(--slate);margin-bottom:6px}
.bev-card p{font-size:13px;color:var(--sage);font-weight:300;line-height:1.5}
.menu-note{background:var(--sand);border-radius:4px;padding:24px 32px;font-size:14px;color:var(--sage);font-style:italic;line-height:1.7;text-align:center;margin-top:48px}

/* ABOUT PAGE */
.about-hero{height:55vh;min-height:400px;background:linear-gradient(135deg,#1a2535 0%,#2d3a28 50%,#1C1F26 100%);display:flex;align-items:center;justify-content:center;text-align:center;position:relative}
.about-hero::before{content:'';position:absolute;inset:0;background:rgba(28,31,38,0.4)}
.about-hero-content{position:relative;z-index:1;padding:0 20px}
.about-hero h1{font-family:var(--r-display);font-size:clamp(40px,6vw,68px);font-weight:700;color:var(--ivory);line-height:1.1}
.about-story{padding:90px 5%;background:var(--ivory)}
.story-inner{display:grid;grid-template-columns:1fr 1.6fr;gap:80px;align-items:start}
.story-quote{font-family:var(--r-display);font-size:32px;font-style:italic;color:var(--gold);line-height:1.3;position:sticky;top:100px}
.story-body p{font-size:16px;color:#5a6070;line-height:1.85;margin-bottom:24px;font-weight:300}
.stats-bar{background:var(--slate);padding:70px 5%}
.stats-inner{display:grid;grid-template-columns:repeat(4,1fr);gap:32px;text-align:center}
.stat-num{font-family:var(--r-display);font-size:52px;font-weight:700;color:var(--gold);line-height:1}
.stat-label{font-size:13px;color:var(--sage);margin-top:10px;letter-spacing:0.05em;font-weight:400}
.diff-section{padding:90px 5%;background:var(--sand)}
.diff-list{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:24px;margin-top:48px}
.diff-item{display:flex;gap:20px;padding:28px;background:var(--white);border-radius:4px;border-left:3px solid transparent;transition:border-color 0.3s,transform 0.3s}
.diff-item:hover{border-left-color:var(--gold);transform:translateX(4px)}
.diff-icon{font-size:24px;flex-shrink:0;margin-top:2px}
.diff-text h4{font-family:var(--r-display);font-size:20px;font-weight:700;color:var(--slate);margin-bottom:8px}
.diff-text p{font-size:14px;color:var(--sage);line-height:1.7;font-weight:300}

/* VISIT PAGE */
.visit-hero{height:55vh;min-height:400px;background:linear-gradient(150deg,#2d3a28 0%,#1a2535 60%,#1C1F26 100%);display:flex;align-items:center;justify-content:center;text-align:center;position:relative}
.visit-hero::before{content:'';position:absolute;inset:0;background:rgba(28,31,38,0.45)}
.visit-hero-content{position:relative;z-index:1;padding:0 20px}
.visit-hero h1{font-family:var(--r-display);font-size:clamp(40px,6vw,68px);font-weight:700;color:var(--ivory);margin-bottom:14px;line-height:1.1}
.visit-hero p{font-size:16px;color:rgba(253,250,244,0.7);max-width:520px;margin:0 auto;line-height:1.7;font-weight:300}
.map-section{padding:80px 5%;background:var(--ivory)}
.map-contact-grid{display:grid;grid-template-columns:1.2fr 1fr;gap:48px;align-items:center}
.contact-card{background:var(--slate);border-radius:4px;padding:48px 40px}
.contact-card h3{font-family:var(--r-display);font-size:28px;font-weight:700;color:var(--ivory);margin-bottom:28px}
.contact-detail{display:flex;gap:14px;margin-bottom:18px;align-items:flex-start}
.contact-detail-icon{font-size:18px;color:var(--gold);margin-top:2px;flex-shrink:0}
.contact-detail-text{font-size:14px;color:rgba(253,250,244,0.7);line-height:1.6;font-weight:300}
.contact-detail-text strong{color:var(--ivory);font-weight:500;display:block;margin-bottom:3px}
.contact-detail-text a{color:var(--gold);text-decoration:none}
.reach-section{padding:80px 5%;background:var(--sand)}
.reach-cards{display:grid;grid-template-columns:repeat(3,1fr);gap:24px;margin-top:48px}
.reach-card{background:var(--white);border-radius:4px;padding:36px 28px;text-align:center}
.reach-icon{font-size:32px;margin-bottom:16px}
.reach-card h4{font-family:var(--r-display);font-size:20px;font-weight:700;color:var(--slate);margin-bottom:12px}
.reach-card p{font-size:14px;color:var(--sage);line-height:1.7;font-weight:300}
.attractions-section{padding:80px 5%;background:var(--ivory);overflow:hidden}
.attractions-scroll{display:grid;grid-template-columns:repeat(5,1fr);gap:20px;margin-top:48px}
.attraction-card{background:var(--white);border-radius:4px;padding:32px 24px;text-align:center;border:1px solid rgba(28,31,38,0.06);transition:all 0.3s}
.attraction-card:hover{border-color:rgba(201,136,74,0.3);transform:translateY(-4px);box-shadow:0 12px 32px rgba(28,31,38,0.08)}
.attraction-emoji{font-size:28px;margin-bottom:14px}
.attraction-card h4{font-family:var(--r-display);font-size:18px;font-weight:700;color:var(--slate);margin-bottom:6px}
.attraction-dist{font-size:12px;color:var(--gold);font-weight:500;margin-bottom:8px;letter-spacing:0.03em}
.attraction-card p{font-size:13px;color:var(--sage);line-height:1.6;font-weight:300}
.checkin-section{background:var(--slate);padding:80px 5%}
.checkin-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:20px;margin-top:48px}
.checkin-item{background:rgba(255,255,255,0.05);border:1px solid rgba(255,255,255,0.07);border-radius:4px;padding:28px 24px;text-align:center;transition:border-color 0.3s}
.checkin-item:hover{border-color:rgba(201,136,74,0.3)}
.checkin-icon{font-size:24px;margin-bottom:12px;color:var(--gold)}
.checkin-label{font-size:11px;letter-spacing:0.15em;text-transform:uppercase;color:var(--sage);margin-bottom:6px;font-weight:400}
.checkin-value{font-size:16px;color:var(--ivory);font-weight:400}

/* ANIMATIONS */
@keyframes fadeUp{from{opacity:0;transform:translateY(24px)}to{opacity:1;transform:translateY(0)}}
@keyframes bounce{0%,100%{transform:translateX(-50%) translateY(0)}50%{transform:translateX(-50%) translateY(8px)}}
.reveal{opacity:0;transform:translateY(24px);transition:opacity 0.6s ease,transform 0.6s ease}
.reveal.visible{opacity:1;transform:translateY(0)}
.reveal-delay-1{transition-delay:0.1s}
.reveal-delay-2{transition-delay:0.2s}
.reveal-delay-3{transition-delay:0.3s}

/* RESPONSIVE */
@media(max-width:1024px){
  .footer-grid{grid-template-columns:1fr 1fr;gap:36px}
  .stats-inner{grid-template-columns:repeat(2,1fr)}
  .attractions-scroll{grid-template-columns:repeat(3,1fr)}
  .story-inner{grid-template-columns:1fr}
  .story-quote{position:static;font-size:26px}
  .split{grid-template-columns:1fr}
  .split.reverse{direction:ltr}
  .split-img{min-height:360px;height:360px}
  .split-content{padding:48px 32px}
  .location-inner{grid-template-columns:1fr}
  .map-contact-grid{grid-template-columns:1fr}
  .reach-cards{grid-template-columns:1fr}
  .checkin-grid{grid-template-columns:repeat(2,1fr)}
}
@media(max-width:768px){
  .nav-links{display:none}
  .nav-hamburger{display:flex}
  .features-grid,.dishes-strip{grid-template-columns:1fr}
  .reviews-grid{grid-template-columns:1fr}
  .insta-grid{grid-template-columns:repeat(2,1fr)}
  .footer-grid{grid-template-columns:1fr}
  .stats-inner{grid-template-columns:repeat(2,1fr)}
  .attractions-scroll{grid-template-columns:repeat(2,1fr)}
  .diff-list{grid-template-columns:1fr}
  .checkin-grid{grid-template-columns:1fr}
  .reach-cards{grid-template-columns:1fr}
  .section{padding:60px 5%}
  .tab-btn{padding:16px 18px;font-size:14px}
  .menu-items{grid-template-columns:1fr}
  .bev-grid{grid-template-columns:1fr}
  .subtab-bar{flex-direction:column;align-items:flex-start}
}
@media(prefers-reduced-motion:reduce){
  *{animation:none!important;transition:none!important}
}
</style>
</head>
<body>

<!-- NAV -->
<nav id="main-nav">
  <a class="nav-logo" href="#" onclick="showPage('home')">
    <span class="nav-logo-main">HOTEL ARAWALI HILL</span>
    <span class="nav-logo-hindi">होटल अरावली हिल</span>
  </a>
  <div class="nav-links">
    <a class="nav-link active" onclick="showPage('home')" id="nav-home">Home</a>
    <a class="nav-link" onclick="showPage('menu')" id="nav-menu">Menu</a>
    <a class="nav-link" onclick="showPage('about')" id="nav-about">About Us</a>
    <a class="nav-link" onclick="showPage('visit')" id="nav-visit">Visit Us</a>
  </div>
  <button class="nav-book btn" onclick="window.open('https://www.ixigo.com/hotels/3918054/details','_blank')">Book Now</button>
  <div class="nav-hamburger" onclick="toggleMobile()" id="hamburger">
    <span></span><span></span><span></span>
  </div>
</nav>

<!-- MOBILE MENU -->
<div class="mobile-menu" id="mobile-menu">
  <a class="nav-link" onclick="showPage('home');toggleMobile()">Home</a>
  <a class="nav-link" onclick="showPage('menu');toggleMobile()">Menu</a>
  <a class="nav-link" onclick="showPage('about');toggleMobile()">About Us</a>
  <a class="nav-link" onclick="showPage('visit');toggleMobile()">Visit Us</a>
  <button class="btn btn-primary" onclick="window.open('https://www.ixigo.com/hotels/3918054/details','_blank');toggleMobile()">Book Now</button>
</div>

<!-- FLOATING WHATSAPP -->
<a class="wa-btn" href="https://wa.me/917725994050?text=Hello%2C%20I%27d%20like%20to%20enquire%20about%20a%20room%20at%20Hotel%20Arawali%20Hill." target="_blank" title="Chat on WhatsApp">
  <svg width="26" height="26" viewBox="0 0 24 24" fill="currentColor"><path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"/></svg>
</a>

<!-- ═══════════════ HOME PAGE ═══════════════ -->
<div class="page active" id="page-home">

  <!-- HERO -->
  <section class="hero">
    <div class="hero-bg">
      <svg class="hero-pattern" viewBox="0 0 800 600" preserveAspectRatio="xMidYMid slice" xmlns="http://www.w3.org/2000/svg">
        <defs><pattern id="dots" width="40" height="40" patternUnits="userSpaceOnUse"><circle cx="20" cy="20" r="1" fill="white"/></pattern></defs>
        <rect width="800" height="600" fill="url(#dots)"/>
        <ellipse cx="200" cy="400" rx="300" ry="200" fill="rgba(138,158,139,0.08)"/>
        <ellipse cx="600" cy="200" rx="250" ry="180" fill="rgba(201,136,74,0.06)"/>
        <!-- Hill silhouette -->
        <path d="M0 500 Q50 480 100 460 Q150 440 200 420 Q280 380 340 360 Q400 340 450 320 Q520 290 580 310 Q640 330 700 300 Q750 275 800 260 L800 600 L0 600 Z" fill="rgba(42,48,64,0.6)"/>
        <path d="M0 540 Q80 520 160 510 Q240 500 320 490 Q400 480 480 470 Q560 460 640 450 Q720 440 800 430 L800 600 L0 600 Z" fill="rgba(28,31,38,0.8)"/>
      </svg>
    </div>
    <div class="hero-overlay"></div>
    <div class="hero-content">
      <div class="hero-eyebrow">Ambavgarh · Udaipur · Rajasthan</div>
      <h1>Where the Hills<br>Meet Warm Hospitality</h1>
      <p class="hero-sub">A serene retreat nestled in the ancient Aravalli hills — steps from Fateh Sagar Lake, surrounded by centuries of Rajasthani grandeur.</p>
      <div class="hero-ctas">
        <button class="btn btn-primary" onclick="window.open('https://www.ixigo.com/hotels/3918054/details','_blank')">Book Your Stay</button>
        <button class="btn btn-ghost-light" onclick="showPage('menu')">Explore Our Menu</button>
      </div>
      <div class="hero-badge">
        <span class="stars">★★★★★</span>
        <span>4.6 · 34 Google Reviews</span>
      </div>
    </div>
    <div class="scroll-hint"><div></div></div>
  </section>

  <!-- HILL DIVIDER -->
  <div class="hill-divider" style="background:var(--slate)">
    <svg viewBox="0 0 1440 40" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg">
      <path d="M0 40 L0 30 Q180 5 360 20 Q540 35 720 15 Q900 0 1080 18 Q1260 32 1440 12 L1440 40 Z" fill="#F2EBD9"/>
    </svg>
  </div>

  <!-- FEATURES -->
  <section class="section" style="background:var(--sand)">
    <div class="section-center">
      <span class="eyebrow reveal">The Arawali Experience</span>
      <h2 class="reveal">Why Guests Keep Coming Back</h2>
      <p class="section-lead reveal">More than a stay — an experience rooted in the warmth that only Rajasthan can offer.</p>
    </div>
    <div class="features-grid">
      <div class="feature-card reveal reveal-delay-1">
        <div class="feature-icon">🌄</div>
        <h3>Hill-View Rooms</h3>
        <p>Wake up to misty Aravalli mornings. Every room frames a different view of the hills that have watched over Udaipur for centuries.</p>
      </div>
      <div class="feature-card reveal reveal-delay-2">
        <div class="feature-icon">🍽</div>
        <h3>In-House Restaurant</h3>
        <p>Savour authentic Rajasthani thalis and freshly prepared North Indian fare — honest food, cooked with pride and served with warmth.</p>
      </div>
      <div class="feature-card reveal reveal-delay-3">
        <div class="feature-icon">📍</div>
        <h3>Prime Location</h3>
        <p>Minutes from Fateh Sagar Lake, City Palace, and Lake Pichola. The best of Udaipur is always within easy reach.</p>
      </div>
    </div>
  </section>

  <!-- SPLIT: ROOMS -->
  <div class="split">
    <div class="split-img">
      <div class="split-img-placeholder">
        <div style="font-size:60px;opacity:0.2">🏨</div>
        <span>Room Photo</span>
      </div>
    </div>
    <div class="split-content">
      <span class="eyebrow">Comfortable Rooms</span>
      <h3>Your Home in the Hills</h3>
      <p>Thoughtfully designed for restful nights and energised mornings. Clean, air-conditioned, and equipped with everything you need — nothing you don't.</p>
      <div class="specs-row">
        <span class="spec-pill">✓ Air Conditioning</span>
        <span class="spec-pill">✓ Free Wi-Fi</span>
        <span class="spec-pill">✓ Flat-Screen TV</span>
        <span class="spec-pill">✓ 24-Hr Room Service</span>
        <span class="spec-pill">✓ Private Bathroom</span>
      </div>
      <button class="btn btn-ghost" onclick="window.open('https://www.ixigo.com/hotels/3918054/details','_blank')">Check Availability</button>
    </div>
  </div>

  <!-- SPLIT: POLICIES -->
  <div class="split reverse">
    <div class="split-img" style="background:linear-gradient(135deg,#2a3040,#1a2535)">
      <div class="split-img-placeholder">
        <div style="font-size:60px;opacity:0.2">🌅</div>
        <span>Hotel Exterior</span>
      </div>
    </div>
    <div class="split-content" style="background:var(--white)">
      <span class="eyebrow">Hotel Details</span>
      <h3>Smooth Stays, Flexible Policies</h3>
      <p>We understand that travel plans evolve. That's why we offer free cancellation, easy online booking, and a warm front desk available round the clock.</p>
      <div class="info-pills">
        <span class="info-pill">Check-in 12:00 PM</span>
        <span class="info-pill">Check-out 11:00 AM</span>
        <span class="info-pill">Free Cancellation</span>
        <span class="info-pill">From ₹1,369/night</span>
      </div>
      <button class="btn btn-primary" onclick="window.open('https://www.ixigo.com/hotels/3918054/details','_blank')">Book Now</button>
    </div>
  </div>

  <!-- DISHES TEASER -->
  <section class="dishes-section reveal">
    <h2>Flavours of Rajasthan</h2>
    <p class="dishes-lead">From smoky tandoor to rich gravies — our kitchen tells stories only Udaipur can.</p>
    <div class="dishes-strip">
      <div class="dish-card reveal reveal-delay-1">
        <span class="dish-tag veg">🌿 Vegetarian</span>
        <h3>Dal Baati Churma</h3>
        <p>The soul of Rajasthan — lentils, baked wheat balls, and sweet churma. Served fresh from our kitchen every single day.</p>
      </div>
      <div class="dish-card reveal reveal-delay-2">
        <span class="dish-tag veg">🌿 Vegetarian</span>
        <h3>Paneer Tikka</h3>
        <p>Marinated in house spices, charred to smoky perfection in our clay tandoor. The aroma alone will bring you back.</p>
      </div>
      <div class="dish-card reveal reveal-delay-3">
        <span class="dish-tag nonveg">🍗 Non-Vegetarian</span>
        <h3>Butter Chicken</h3>
        <p>Tender chicken in a buttery, slow-cooked tomato-cream gravy. Bold, aromatic, and deeply satisfying.</p>
      </div>
    </div>
    <div style="text-align:center;margin-top:48px">
      <button class="btn btn-ghost" style="color:var(--sand);border-color:var(--sand)" onclick="showPage('menu')">See Full Menu →</button>
    </div>
  </section>

  <!-- INSTAGRAM HOME -->
  <section class="insta-section">
    <div class="section-center">
      <span class="eyebrow reveal">Follow Our Story</span>
      <h2 class="reveal">Moments from the Hills</h2>
      <p class="section-lead reveal" style="color:var(--sage)">Captured by our guests, our kitchen, and the Aravalli hills at dawn.</p>
    </div>
    <div class="insta-grid reveal">
      <!-- 6 Instagram cells with ambient patterns -->
      <div class="insta-cell" style="background:linear-gradient(135deg,#2d3a28,#1a2a1a)">
        <div class="insta-cell-inner"><div style="width:100%;height:100%;background:linear-gradient(135deg,#2d3a28,#1a2a1a);display:flex;align-items:center;justify-content:center;font-size:36px;opacity:0.3">🌄</div></div>
        <div class="insta-overlay"><span class="insta-icon">❤</span><p class="insta-caption">Sunrise from the hills</p></div>
      </div>
      <div class="insta-cell" style="background:linear-gradient(135deg,#3d2e1a,#2a1a0a)">
        <div class="insta-cell-inner"><div style="width:100%;height:100%;background:linear-gradient(135deg,#3d2e1a,#2a1a0a);display:flex;align-items:center;justify-content:center;font-size:36px;opacity:0.3">🍽</div></div>
        <div class="insta-overlay"><span class="insta-icon">❤</span><p class="insta-caption">Dal Baati Churma night</p></div>
      </div>
      <div class="insta-cell" style="background:linear-gradient(135deg,#1a2535,#0e1520)">
        <div class="insta-cell-inner"><div style="width:100%;height:100%;background:linear-gradient(135deg,#1a2535,#0e1520);display:flex;align-items:center;justify-content:center;font-size:36px;opacity:0.3">🏨</div></div>
        <div class="insta-overlay"><span class="insta-icon">❤</span><p class="insta-caption">Our hill-view rooms</p></div>
      </div>
      <div class="insta-cell" style="background:linear-gradient(135deg,#2a1a10,#3d2010)">
        <div class="insta-cell-inner"><div style="width:100%;height:100%;background:linear-gradient(135deg,#2a1a10,#3d2010);display:flex;align-items:center;justify-content:center;font-size:36px;opacity:0.3">🌊</div></div>
        <div class="insta-overlay"><span class="insta-icon">❤</span><p class="insta-caption">Fateh Sagar Lake view</p></div>
      </div>
      <div class="insta-cell" style="background:linear-gradient(135deg,#1e2c1e,#142014)">
        <div class="insta-cell-inner"><div style="width:100%;height:100%;background:linear-gradient(135deg,#1e2c1e,#142014);display:flex;align-items:center;justify-content:center;font-size:36px;opacity:0.3">🍛</div></div>
        <div class="insta-overlay"><span class="insta-icon">❤</span><p class="insta-caption">Fresh from our kitchen</p></div>
      </div>
      <div class="insta-cell" style="background:linear-gradient(135deg,#2a2535,#1a1525)">
        <div class="insta-cell-inner"><div style="width:100%;height:100%;background:linear-gradient(135deg,#2a2535,#1a1525);display:flex;align-items:center;justify-content:center;font-size:36px;opacity:0.3">✨</div></div>
        <div class="insta-overlay"><span class="insta-icon">❤</span><p class="insta-caption">Evening at Arawali Hill</p></div>
      </div>
    </div>
    <div style="text-align:center">
      <a class="btn btn-ghost" href="https://www.instagram.com/hotelarawalihill" target="_blank">Follow @hotelarawalihill on Instagram →</a>
    </div>
  </section>

  <!-- REVIEWS -->
  <section class="reviews-section">
    <div class="section-center">
      <span class="eyebrow reveal">Guest Reviews</span>
      <h2 class="reveal">Rated 4.6 ★ on Google</h2>
      <p class="section-lead reveal" style="color:var(--sage)">34 verified reviews from guests who found exactly what they were looking for.</p>
    </div>
    <div class="reviews-grid">
      <div class="review-card reveal reveal-delay-1">
        <div class="review-stars">★★★★★</div>
        <p class="review-text">"The view from the room every morning made the whole trip worthwhile. The staff were incredibly helpful and always went the extra mile."</p>
        <p class="review-author">Verified Google Guest</p>
      </div>
      <div class="review-card reveal reveal-delay-2">
        <div class="review-stars">★★★★★</div>
        <p class="review-text">"Clean, comfortable, and great food in the restaurant. Location is perfect for exploring Udaipur — everything was a short drive away."</p>
        <p class="review-author">Verified Google Guest</p>
      </div>
      <div class="review-card reveal reveal-delay-3">
        <div class="review-stars">★★★★★</div>
        <p class="review-text">"Best value stay in Udaipur. The Aravalli views are stunning and the team genuinely goes above and beyond. Will definitely return."</p>
        <p class="review-author">Verified Google Guest</p>
      </div>
    </div>
    <div style="text-align:center;margin-top:36px">
      <a class="google-badge" href="https://www.google.com/maps/place/Hotel+Arawali+Hill" target="_blank">
        <svg width="16" height="16" viewBox="0 0 48 48"><path fill="#4285F4" d="M45.5 24.6c0-1.4-.1-2.8-.4-4.1H24v7.8h12.1c-.5 2.8-2.1 5.1-4.5 6.7v5.5h7.2c4.3-3.9 6.7-9.7 6.7-15.9z"/><path fill="#34A853" d="M24 46c6.1 0 11.2-2 14.9-5.5l-7.2-5.5c-2 1.4-4.6 2.2-7.7 2.2-5.9 0-10.9-4-12.7-9.3H4v5.7C7.7 41.6 15.4 46 24 46z"/><path fill="#FBBC04" d="M11.3 27.9c-.5-1.4-.7-2.8-.7-4.4s.3-3 .7-4.4V13.4H4C2.3 16.7 1.3 20.2 1.3 24s1 7.3 2.7 10.6l7.3-6.7z"/><path fill="#EA4335" d="M24 10.4c3.3 0 6.3 1.1 8.6 3.4l6.4-6.4C35.2 3.7 29.9 1.4 24 1.4 15.4 1.4 7.7 5.8 4 13.4l7.3 6.1c1.8-5.3 6.8-9.1 12.7-9.1z"/></svg>
        Reviews from Google
      </a>
    </div>
  </section>

  <!-- LOCATION TEASER -->
  <section class="location-teaser">
    <div class="location-inner">
      <div class="map-placeholder reveal">
        <iframe class="map-embed" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1740.0!2d73.6782693!3d24.5905482!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3967e55c5ed89381%3A0xd93dc91efc0c4757!2sHotel+Arawali+Hill!5e0!3m2!1sen!2sin!4v1700000000000" allowfullscreen loading="lazy" title="Hotel Arawali Hill on Google Maps"></iframe>
      </div>
      <div class="location-info reveal">
        <span class="eyebrow" style="color:var(--sage)">Find Us</span>
        <h2>In the Heart of Ambavgarh</h2>
        <p>Perched along Ambavgarh Road, we sit minutes from Fateh Sagar Lake and a short drive from City Palace and Lake Pichola.</p>
        <div class="contact-line">📍 <span>L-18, Ambavgarh Road, Near Hotel Hill Top,<br>Udaipur, Rajasthan – 313004</span>
        </div>
        <div class="contact-line">📞 <a href="tel:07725994050" style="color:var(--gold)">077259 94050</a></div>
        <div style="display:flex;gap:14px;margin-top:28px;flex-wrap:wrap">
          <a class="btn btn-primary btn-sm" href="https://www.google.com/maps/place/Hotel+Arawali+Hill" target="_blank">Get Directions</a>
          <a class="btn btn-ghost btn-sm" style="color:var(--sand);border-color:rgba(253,250,244,0.4)" href="tel:07725994050">Call Now</a>
        </div>
      </div>
    </div>
  </section>

  <!-- CTA BANNER -->
  <section class="cta-banner">
    <h2 class="reveal">Your Udaipur Retreat Awaits</h2>
    <p class="reveal">Book directly for the best experience. Free cancellation. Warm hospitality. Guaranteed.</p>
    <div class="cta-buttons reveal">
      <button class="btn btn-dark" onclick="window.open('https://www.ixigo.com/hotels/3918054/details','_blank')">Book Now</button>
      <a class="btn btn-ghost-light" href="tel:07725994050">Call Us</a>
    </div>
  </section>

  <!-- FOOTER -->
  <footer>
    <div class="hill-divider" style="background:var(--gold);margin-bottom:0">
      <svg viewBox="0 0 1440 40" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M0 40 L0 28 Q200 5 400 18 Q600 30 800 10 Q1000 0 1200 16 Q1320 26 1440 8 L1440 40 Z" fill="#1C1F26"/>
      </svg>
    </div>
    <div class="footer-grid">
      <div class="footer-brand">
        <div style="font-family:var(--r-display);font-size:20px;font-weight:700;color:var(--ivory);letter-spacing:0.08em">HOTEL ARAWALI HILL</div>
        <div style="font-size:11px;color:var(--sage);margin-top:4px">होटल अरावली हिल</div>
        <p style="margin-top:16px">Where the hills meet warm hospitality. A cherished retreat in the heart of Udaipur's Aravalli hills.</p>
        <div class="social-links">
          <a class="social-link" href="https://www.instagram.com/hotelarawalihill" target="_blank" title="Instagram">
            <svg width="18" height="18" viewBox="0 0 24 24" fill="currentColor"><path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.163 6.162 6.163 6.162-2.759 6.162-6.163c0-3.403-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.79-4-4 0-2.209 1.791-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z"/></svg>
          </a>
          <a class="social-link" href="https://wa.me/917725994050" target="_blank" title="WhatsApp">
            <svg width="18" height="18" viewBox="0 0 24 24" fill="currentColor"><path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"/></svg>
          </a>
        </div>
      </div>
      <div class="footer-col">
        <h4>Quick Links</h4>
        <ul>
          <li><a onclick="showPage('home')">Home</a></li>
          <li><a onclick="showPage('menu')">Menu</a></li>
          <li><a onclick="showPage('about')">About Us</a></li>
          <li><a onclick="showPage('visit')">Visit Us</a></li>
          <li><a href="https://www.ixigo.com/hotels/3918054/details" target="_blank">Book Now</a></li>
        </ul>
      </div>
      <div class="footer-col">
        <h4>Contact</h4>
        <p>L-18, Ambavgarh Road<br>Near Hotel Hill Top<br>Udaipur, Rajasthan 313004</p>
        <p style="margin-top:12px"><a href="tel:07725994050" style="color:var(--gold);text-decoration:none">077259 94050</a></p>
        <a class="btn btn-sm" style="margin-top:16px;display:inline-flex;background:rgba(37,211,102,0.12);border:1px solid rgba(37,211,102,0.3);color:#25D366;padding:8px 18px;font-size:12px;border-radius:4px;text-decoration:none;gap:6px" href="https://wa.me/917725994050" target="_blank">
          WhatsApp Us
        </a>
      </div>
      <div class="footer-col">
        <h4>Hours</h4>
        <ul>
          <li>Check-in: 12:00 PM</li>
          <li>Check-out: 11:00 AM</li>
          <li>Front Desk: 24 Hours</li>
          <li>Restaurant: Daily</li>
        </ul>
      </div>
    </div>
    <div class="footer-bottom">
      <p>© 2024 Hotel Arawali Hill. All rights reserved.</p>
      <p>L-18, Ambavgarh, Udaipur · <a href="tel:07725994050" style="color:var(--gold);text-decoration:none">077259 94050</a></p>
    </div>
  </footer>
</div>

<!-- ═══════════════ MENU PAGE ═══════════════ -->
<div class="page" id="page-menu">
  <div style="padding-top:70px">
    <div class="menu-hero">
      <div class="menu-hero-content">
        <span class="eyebrow" style="color:var(--sage);display:block;margin-bottom:16px">Our Restaurant</span>
        <h1>A Kitchen Full of Stories</h1>
        <p>Honest flavours, fresh ingredients, and the warmth of Rajasthani hospitality — every single day.</p>
      </div>
    </div>

    <div class="menu-tabs">
      <button class="tab-btn active" onclick="switchTab('food', this)">🍽 Food</button>
      <button class="tab-btn" onclick="switchTab('beverages', this)">☕ Beverages</button>
    </div>

    <!-- FOOD TAB -->
    <div class="tab-content active" id="tab-food" style="background:var(--ivory)">
      <div class="subtab-bar">
        <button class="subtab-btn veg active" onclick="switchSubtab('veg', this)">🌿 Vegetarian</button>
        <button class="subtab-btn nonveg" onclick="switchSubtab('nonveg', this)">🍗 Non-Vegetarian</button>
      </div>

      <!-- VEG -->
      <div class="menu-subcontent active" id="subtab-veg">
        <div class="menu-category">
          <h3 class="menu-category-title">Soups &amp; Starters</h3>
          <div class="menu-items">
            <div class="menu-item"><h4><span class="veg-dot"></span>Tomato Soup</h4><p>Classic, richly seasoned, served piping hot</p></div>
            <div class="menu-item"><h4><span class="veg-dot"></span>Sweet Corn Soup</h4><p>Creamy and comforting, a guest favourite</p></div>
            <div class="menu-item"><h4><span class="veg-dot"></span>Veg Manchow Soup</h4><p>Spiced, hearty, Indo-Chinese style</p></div>
            <div class="menu-item"><h4><span class="veg-dot"></span>Paneer Tikka</h4><p>Cottage cheese marinated in tandoori spices, char-grilled in the clay oven</p></div>
            <div class="menu-item"><h4><span class="veg-dot"></span>Hara Bhara Kebab</h4><p>Crispy spinach and pea patties with green chutney</p></div>
            <div class="menu-item"><h4><span class="veg-dot"></span>Veg Manchurian</h4><p>Golden fried vegetable balls in a tangy sauce</p></div>
            <div class="menu-item"><h4><span class="veg-dot"></span>Paneer Pakora</h4><p>Battered cottage cheese, deep-fried until crisp</p></div>
            <div class="menu-item"><h4><span class="veg-dot"></span>Aloo Tikki</h4><p>Spiced potato patties, a timeless street-side classic</p></div>
          </div>
        </div>
        <div class="menu-category">
          <h3 class="menu-category-title">Main Course</h3>
          <div class="menu-items">
            <div class="menu-item"><h4><span class="veg-dot"></span>Dal Baati Churma</h4><p>The iconic Rajasthani trinity — lentils, baked wheat balls, and sweet churma</p></div>
            <div class="menu-item"><h4><span class="veg-dot"></span>Dal Makhani</h4><p>Black lentils slow-simmered overnight with butter and cream</p></div>
            <div class="menu-item"><h4><span class="veg-dot"></span>Paneer Butter Masala</h4><p>Cottage cheese in a velvety tomato-butter gravy</p></div>
            <div class="menu-item"><h4><span class="veg-dot"></span>Shahi Paneer</h4><p>Rich, creamy — paneer in a cashew-onion gravy fit for royalty</p></div>
            <div class="menu-item"><h4><span class="veg-dot"></span>Kadai Paneer</h4><p>Paneer stir-fried with peppers in a robust kadai masala</p></div>
            <div class="menu-item"><h4><span class="veg-dot"></span>Palak Paneer</h4><p>Cottage cheese in silky spiced spinach gravy</p></div>
            <div class="menu-item"><h4><span class="veg-dot"></span>Mix Vegetable</h4><p>Seasonal vegetables in a fragrant North Indian masala</p></div>
            <div class="menu-item"><h4><span class="veg-dot"></span>Aloo Gobhi</h4><p>Classic cauliflower and potato dry sabzi</p></div>
            <div class="menu-item"><h4><span class="veg-dot"></span>Rajasthani Gatta Curry</h4><p>Gram flour dumplings in a tangy yoghurt gravy — a regional specialty</p></div>
            <div class="menu-item"><h4><span class="veg-dot"></span>Dal Tadka</h4><p>Yellow lentils tempered with cumin, garlic, and dried chillies</p></div>
            <div class="menu-item"><h4><span class="veg-dot"></span>Veg Biryani</h4><p>Fragrant basmati layered with spiced vegetables and saffron</p></div>
            <div class="menu-item"><h4><span class="veg-dot"></span>Veg Fried Rice</h4><p>Wok-tossed rice with fresh vegetables, Indo-Chinese style</p></div>
            <div class="menu-item"><h4><span class="veg-dot"></span>Veg Hakka Noodles</h4><p>Stir-fried noodles with crisp vegetables in a light sauce</p></div>
          </div>
        </div>
        <div class="menu-category">
          <h3 class="menu-category-title">Breads</h3>
          <div class="menu-items">
            <div class="menu-item"><h4><span class="veg-dot"></span>Roti / Chapati</h4><p>Freshly made whole wheat flatbread, hot from the tawa</p></div>
            <div class="menu-item"><h4><span class="veg-dot"></span>Tandoori Roti</h4><p>Puffed whole wheat bread baked in the clay oven</p></div>
            <div class="menu-item"><h4><span class="veg-dot"></span>Butter Naan</h4><p>Soft, buttery, straight from the tandoor</p></div>
            <div class="menu-item"><h4><span class="veg-dot"></span>Garlic Naan</h4><p>Tandoor-baked naan topped with garlic and coriander</p></div>
            <div class="menu-item"><h4><span class="veg-dot"></span>Laccha Paratha</h4><p>Layered, flaky whole wheat bread, grilled to golden</p></div>
            <div class="menu-item"><h4><span class="veg-dot"></span>Missi Roti</h4><p>Rajasthani spiced gram flour flatbread</p></div>
          </div>
        </div>
        <div class="menu-category">
          <h3 class="menu-category-title">Rice &amp; Accompaniments</h3>
          <div class="menu-items">
            <div class="menu-item"><h4><span class="veg-dot"></span>Jeera Rice</h4><p>Fragrant basmati tempered with cumin</p></div>
            <div class="menu-item"><h4><span class="veg-dot"></span>Steamed Rice</h4><p>Plain basmati, perfectly cooked</p></div>
            <div class="menu-item"><h4><span class="veg-dot"></span>Raita</h4><p>Chilled yoghurt with cucumber and mild spices</p></div>
            <div class="menu-item"><h4><span class="veg-dot"></span>Papad</h4><p>Crisp lentil wafers, roasted or fried</p></div>
          </div>
        </div>
        <div class="menu-category">
          <h3 class="menu-category-title">Desserts</h3>
          <div class="menu-items">
            <div class="menu-item"><h4><span class="veg-dot"></span>Gulab Jamun</h4><p>Soft milk-solid dumplings soaked in rose-flavoured sugar syrup</p></div>
            <div class="menu-item"><h4><span class="veg-dot"></span>Gajar Halwa</h4><p>Slow-cooked carrot pudding with ghee, milk, and dry fruits</p></div>
            <div class="menu-item"><h4><span class="veg-dot"></span>Moong Dal Halwa</h4><p>Rich, aromatic split mung bean halwa — a Rajasthani festive sweet</p></div>
            <div class="menu-item"><h4><span class="veg-dot"></span>Malpua</h4><p>Soft fried pancakes dipped in sugar syrup, served with rabdi</p></div>
            <div class="menu-item"><h4><span class="veg-dot"></span>Ice Cream</h4><p>Vanilla, strawberry, or butterscotch</p></div>
          </div>
        </div>
      </div>

      <!-- NON-VEG -->
      <div class="menu-subcontent" id="subtab-nonveg">
        <div class="menu-category">
          <h3 class="menu-category-title">Soups &amp; Starters</h3>
          <div class="menu-items">
            <div class="menu-item"><h4><span class="nonveg-dot"></span>Chicken Manchow Soup</h4><p>Spiced, thick, and deeply satisfying</p></div>
            <div class="menu-item"><h4><span class="nonveg-dot"></span>Chicken Sweet Corn Soup</h4><p>Creamy soup with tender shredded chicken</p></div>
            <div class="menu-item"><h4><span class="nonveg-dot"></span>Chicken Tikka</h4><p>Boneless chicken marinated in yoghurt and spices, cooked in the tandoor</p></div>
            <div class="menu-item"><h4><span class="nonveg-dot"></span>Chicken Tandoori (Half / Full)</h4><p>Classic bone-in tandoori chicken, char-grilled and smoky</p></div>
            <div class="menu-item"><h4><span class="nonveg-dot"></span>Chicken Seekh Kebab</h4><p>Minced chicken on skewers, charred over live flame</p></div>
            <div class="menu-item"><h4><span class="nonveg-dot"></span>Chicken Lollipop</h4><p>Crispy glazed chicken winglets with chilli dipping sauce</p></div>
            <div class="menu-item"><h4><span class="nonveg-dot"></span>Mutton Seekh Kebab</h4><p>Spiced minced mutton kebabs from the tandoor grill</p></div>
            <div class="menu-item"><h4><span class="nonveg-dot"></span>Egg Bhurji</h4><p>Spiced scrambled eggs with onions, tomatoes, and green chillies</p></div>
          </div>
        </div>
        <div class="menu-category">
          <h3 class="menu-category-title">Main Course</h3>
          <div class="menu-items">
            <div class="menu-item"><h4><span class="nonveg-dot"></span>Butter Chicken</h4><p>Tender chicken in a buttery, tomato-cream gravy — the celebrated Indian classic</p></div>
            <div class="menu-item"><h4><span class="nonveg-dot"></span>Chicken Curry</h4><p>Slow-cooked in a robust, aromatic North Indian masala</p></div>
            <div class="menu-item"><h4><span class="nonveg-dot"></span>Chicken Kadai</h4><p>Bold, pepper-forward kadai masala with capsicum and onion</p></div>
            <div class="menu-item"><h4><span class="nonveg-dot"></span>Chicken Korma</h4><p>Delicately spiced with a rich yoghurt and cashew gravy</p></div>
            <div class="menu-item"><h4><span class="nonveg-dot"></span>Mutton Rogan Josh</h4><p>A slow-cooked Kashmiri-style mutton curry, deeply aromatic</p></div>
            <div class="menu-item"><h4><span class="nonveg-dot"></span>Mutton Curry</h4><p>Home-style slow-cooked mutton in a robust masala</p></div>
            <div class="menu-item"><h4><span class="nonveg-dot"></span>Egg Curry</h4><p>Boiled eggs simmered in a tangy, spiced onion-tomato gravy</p></div>
          </div>
        </div>
        <div class="menu-category">
          <h3 class="menu-category-title">Rice &amp; Biryani</h3>
          <div class="menu-items">
            <div class="menu-item"><h4><span class="nonveg-dot"></span>Chicken Biryani</h4><p>Aromatic basmati layered with spiced chicken, cooked dum-style</p></div>
            <div class="menu-item"><h4><span class="nonveg-dot"></span>Mutton Biryani</h4><p>Slow-cooked mutton biryani with saffron, fried onions, and whole spices</p></div>
            <div class="menu-item"><h4><span class="nonveg-dot"></span>Egg Fried Rice</h4><p>Wok-tossed basmati with egg and vegetables</p></div>
            <div class="menu-item"><h4><span class="nonveg-dot"></span>Chicken Fried Rice</h4><p>Indo-Chinese style fried rice with tender chicken</p></div>
          </div>
        </div>
        <div class="menu-category">
          <h3 class="menu-category-title">Breads</h3>
          <div class="menu-items">
            <div class="menu-item"><h4>Roti / Chapati</h4><p>Hot from the tawa</p></div>
            <div class="menu-item"><h4>Butter Naan</h4><p>Soft and buttery from the tandoor</p></div>
            <div class="menu-item"><h4>Garlic Naan</h4><p>With garlic and coriander</p></div>
            <div class="menu-item"><h4>Laccha Paratha</h4><p>Flaky, layered, golden</p></div>
          </div>
        </div>
      </div>

      <p class="menu-note">Our menu celebrates the flavours of Rajasthan and North India. All items are freshly prepared to order. Please inform our team of any dietary requirements or allergies.</p>
    </div>

    <!-- BEVERAGES TAB -->
    <div class="tab-content" id="tab-beverages" style="background:var(--ivory)">
      <div class="menu-category">
        <h3 class="menu-category-title">Hot Beverages</h3>
        <div class="bev-grid">
          <div class="bev-card"><h4>Masala Chai</h4><p>Spiced Indian tea brewed with ginger, cardamom, and whole spices</p></div>
          <div class="bev-card"><h4>Adrak Chai</h4><p>Brisk and warming, made with fresh ginger</p></div>
          <div class="bev-card"><h4>Plain Tea</h4><p>Classic light tea, served with milk</p></div>
          <div class="bev-card"><h4>Filter Coffee</h4><p>Strong South Indian-style filter coffee</p></div>
          <div class="bev-card"><h4>Instant Coffee</h4><p>Hot, quick, and comforting</p></div>
          <div class="bev-card"><h4>Lemon Tea</h4><p>Hot tea with a citrus twist</p></div>
        </div>
      </div>
      <div class="menu-category">
        <h3 class="menu-category-title">Cold Beverages &amp; Juices</h3>
        <div class="bev-grid">
          <div class="bev-card"><h4>Fresh Lime Soda</h4><p>Sweet, salted, or mixed — the perfect Rajasthan refresher</p></div>
          <div class="bev-card"><h4>Fresh Orange Juice</h4><p>Cold-pressed, served immediately</p></div>
          <div class="bev-card"><h4>Watermelon Juice</h4><p>Seasonal, chilled, and naturally sweet</p></div>
          <div class="bev-card"><h4>Mango Lassi</h4><p>Thick, creamy, and gloriously sweet</p></div>
          <div class="bev-card"><h4>Sweet Lassi</h4><p>Chilled yoghurt drink with a hint of rose</p></div>
          <div class="bev-card"><h4>Salted Lassi</h4><p>Tangy, cooling, deeply refreshing</p></div>
          <div class="bev-card"><h4>Cold Coffee</h4><p>Blended with ice and milk, served tall</p></div>
          <div class="bev-card"><h4>Banana Shake</h4><p>Thick fruit shake, energising and wholesome</p></div>
          <div class="bev-card"><h4>Mixed Fruit Juice</h4><p>Seasonal blend of fresh fruits</p></div>
          <div class="bev-card"><h4>Buttermilk (Chaas)</h4><p>Light, spiced, and wonderfully cooling</p></div>
        </div>
      </div>
      <div class="menu-category">
        <h3 class="menu-category-title">Soft Drinks</h3>
        <div class="bev-grid">
          <div class="bev-card"><h4>Coca-Cola / Pepsi</h4><p>Chilled and refreshing</p></div>
          <div class="bev-card"><h4>Sprite / 7Up / Limca</h4><p>Light and fizzy</p></div>
          <div class="bev-card"><h4>Thumbs Up</h4><p>Bold and fizzy</p></div>
          <div class="bev-card"><h4>Maaza / Frooti</h4><p>Mango fruit drinks</p></div>
          <div class="bev-card"><h4>Mineral Water</h4><p>Still or sparkling</p></div>
        </div>
      </div>
      <p class="menu-note">Fresh beverages are made to order. Ask our team about seasonal specials and freshly pressed juices.</p>
    </div>
  </div>

  <!-- FOOTER MINI -->
  <footer style="background:var(--slate);padding:40px 5%;text-align:center">
    <div style="font-family:var(--r-display);font-size:18px;font-weight:700;color:var(--ivory);letter-spacing:0.08em;margin-bottom:16px">HOTEL ARAWALI HILL</div>
    <div style="display:flex;justify-content:center;gap:24px;flex-wrap:wrap;margin-bottom:20px">
      <button class="nav-link" onclick="showPage('home')" style="color:rgba(253,250,244,0.6);background:none;border:none;cursor:pointer;font-size:14px">Home</button>
      <button class="nav-link" onclick="showPage('about')" style="color:rgba(253,250,244,0.6);background:none;border:none;cursor:pointer;font-size:14px">About</button>
      <button class="nav-link" onclick="showPage('visit')" style="color:rgba(253,250,244,0.6);background:none;border:none;cursor:pointer;font-size:14px">Visit Us</button>
    </div>
    <p style="font-size:13px;color:rgba(253,250,244,0.4)">© 2024 Hotel Arawali Hill · L-18, Ambavgarh, Udaipur · 077259 94050</p>
  </footer>
</div>

<!-- ═══════════════ ABOUT PAGE ═══════════════ -->
<div class="page" id="page-about">
  <div style="padding-top:70px">
    <div class="about-hero">
      <div class="about-hero-content">
        <span class="eyebrow" style="color:var(--sage);display:block;margin-bottom:16px">Our Story</span>
        <h1>Born from the<br>Aravalli Hills</h1>
      </div>
    </div>

    <section class="about-story">
      <div class="story-inner">
        <div class="story-quote reveal">"We didn't build a hotel. We built a home with rooms."</div>
        <div class="story-body reveal">
          <p>Hotel Arawali Hill was conceived with a singular purpose: to offer travellers a place where the grandeur of the Aravalli mountains meets the unpretentious warmth of Rajasthani hospitality. Tucked into Ambavgarh — one of Udaipur's most serene hillside neighbourhoods — our property sits at an elevation that gifts every guest with sweeping views of the ancient hills at sunrise.</p>
          <p>We are not the biggest hotel in Udaipur. We are not trying to be. What we offer instead is something rarer: genuine care, a comfortable bed, honest food, and a team that remembers your name. Rated 4.6 stars across 34 verified Google reviews, our guests consistently call their stay here one of the highlights of their Udaipur visit.</p>
          <p>Located minutes from Fateh Sagar Lake and an easy drive from City Palace and Lake Pichola, Hotel Arawali Hill is the ideal base for travellers who want to explore the City of Lakes without compromise — and return each evening to a quiet, restorative space that feels like their own.</p>
          <button class="btn btn-primary" style="margin-top:12px" onclick="window.open('https://www.ixigo.com/hotels/3918054/details','_blank')">Book Your Stay</button>
        </div>
      </div>
    </section>

    <section class="stats-bar">
      <div class="stats-inner">
        <div class="reveal">
          <div class="stat-num">4.6 ★</div>
          <div class="stat-label">Google Rating</div>
        </div>
        <div class="reveal reveal-delay-1">
          <div class="stat-num">34+</div>
          <div class="stat-label">Happy Guest Reviews</div>
        </div>
        <div class="reveal reveal-delay-2">
          <div class="stat-num">24h</div>
          <div class="stat-label">Front Desk Always Open</div>
        </div>
        <div class="reveal reveal-delay-3">
          <div class="stat-num">5 min</div>
          <div class="stat-label">To Fateh Sagar Lake</div>
        </div>
      </div>
    </section>

    <section class="diff-section">
      <div class="section-center">
        <span class="eyebrow reveal">What Sets Us Apart</span>
        <h2 class="reveal">The Arawali Difference</h2>
      </div>
      <div class="diff-list">
        <div class="diff-item reveal">
          <div class="diff-icon">🌄</div>
          <div class="diff-text">
            <h4>Hilltop Serenity</h4>
            <p>Away from the chaos, nestled in nature, yet moments from every major Udaipur attraction.</p>
          </div>
        </div>
        <div class="diff-item reveal reveal-delay-1">
          <div class="diff-icon">🍽</div>
          <div class="diff-text">
            <h4>Fresh, Honest Food</h4>
            <p>Our restaurant sources fresh, seasonal ingredients daily to bring authentic Rajasthani and North Indian cuisine to your table.</p>
          </div>
        </div>
        <div class="diff-item reveal reveal-delay-2">
          <div class="diff-icon">🏠</div>
          <div class="diff-text">
            <h4>Homely Comfort</h4>
            <p>Clean, thoughtfully furnished rooms with everything you need for a genuinely restful stay.</p>
          </div>
        </div>
        <div class="diff-item reveal">
          <div class="diff-icon">📞</div>
          <div class="diff-text">
            <h4>Always Here for You</h4>
            <p>Our 24-hour front desk team is trained to assist with everything from local recommendations to last-minute travel changes.</p>
          </div>
        </div>
        <div class="diff-item reveal reveal-delay-1">
          <div class="diff-icon">🔓</div>
          <div class="diff-text">
            <h4>Flexible Booking</h4>
            <p>Free cancellation available on select rates, so you can plan your Udaipur trip with complete peace of mind.</p>
          </div>
        </div>
        <div class="diff-item reveal reveal-delay-2">
          <div class="diff-icon">⭐</div>
          <div class="diff-text">
            <h4>Trusted by Travellers</h4>
            <p>34+ verified Google reviews and a 4.6-star rating earned through consistent, heartfelt hospitality.</p>
          </div>
        </div>
      </div>
    </section>

    <section class="cta-banner">
      <h2 class="reveal">Come Stay With Us</h2>
      <p class="reveal">Whether you're a solo explorer, a couple on a getaway, or a family discovering Rajasthan — Hotel Arawali Hill welcomes you home.</p>
      <div class="cta-buttons reveal">
        <button class="btn btn-dark" onclick="window.open('https://www.ixigo.com/hotels/3918054/details','_blank')">Book Your Room</button>
        <button class="btn btn-ghost-light" onclick="showPage('visit')">Find Us</button>
      </div>
    </section>

    <footer style="background:var(--slate);padding:40px 5%;text-align:center">
      <div style="font-family:var(--r-display);font-size:18px;font-weight:700;color:var(--ivory);letter-spacing:0.08em;margin-bottom:16px">HOTEL ARAWALI HILL</div>
      <div style="display:flex;justify-content:center;gap:24px;flex-wrap:wrap;margin-bottom:20px">
        <button onclick="showPage('home')" style="color:rgba(253,250,244,0.6);background:none;border:none;cursor:pointer;font-size:14px">Home</button>
        <button onclick="showPage('menu')" style="color:rgba(253,250,244,0.6);background:none;border:none;cursor:pointer;font-size:14px">Menu</button>
        <button onclick="showPage('visit')" style="color:rgba(253,250,244,0.6);background:none;border:none;cursor:pointer;font-size:14px">Visit Us</button>
      </div>
      <p style="font-size:13px;color:rgba(253,250,244,0.4)">© 2024 Hotel Arawali Hill · L-18, Ambavgarh, Udaipur · 077259 94050</p>
    </footer>
  </div>
</div>

<!-- ═══════════════ VISIT PAGE ═══════════════ -->
<div class="page" id="page-visit">
  <div style="padding-top:70px">
    <div class="visit-hero">
      <div class="visit-hero-content">
        <span class="eyebrow" style="color:var(--sage);display:block;margin-bottom:16px">How To Find Us</span>
        <h1>We're Easy to Find,<br>Hard to Leave</h1>
        <p>Set in the peaceful Ambavgarh hillside, just minutes from Fateh Sagar Lake and Udaipur's finest attractions.</p>
      </div>
    </div>

    <!-- MAP & CONTACT -->
    <section class="map-section">
      <div class="map-contact-grid">
        <div class="reveal" style="height:400px;border-radius:4px;overflow:hidden">
          <iframe style="width:100%;height:100%;border:none;border-radius:4px;filter:grayscale(10%)" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1740.0!2d73.6782693!3d24.5905482!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3967e55c5ed89381%3A0xd93dc91efc0c4757!2sHotel+Arawali+Hill!5e0!3m2!1sen!2sin!4v1700000000000" allowfullscreen loading="lazy" title="Hotel Arawali Hill Map"></iframe>
        </div>
        <div class="contact-card reveal">
          <h3>Get in Touch</h3>
          <div class="contact-detail">
            <div class="contact-detail-icon">📍</div>
            <div class="contact-detail-text">
              <strong>Address</strong>
              L-18, Ambavgarh Road, Near Hotel Hill Top,<br>Ambavgarh, Udaipur, Rajasthan – 313004
            </div>
          </div>
          <div class="contact-detail">
            <div class="contact-detail-icon">📞</div>
            <div class="contact-detail-text">
              <strong>Phone</strong>
              <a href="tel:07725994050">077259 94050</a>
            </div>
          </div>
          <div class="contact-detail">
            <div class="contact-detail-icon">💬</div>
            <div class="contact-detail-text">
              <strong>WhatsApp</strong>
              <a href="https://wa.me/917725994050" target="_blank">077259 94050</a>
            </div>
          </div>
          <div class="contact-detail">
            <div class="contact-detail-icon">🕐</div>
            <div class="contact-detail-text">
              <strong>Check-in / Check-out</strong>
              Check-in: 12:00 PM · Check-out: 11:00 AM
            </div>
          </div>
          <div style="display:flex;gap:12px;flex-wrap:wrap;margin-top:28px">
            <a class="btn btn-primary btn-sm" href="https://www.google.com/maps/place/Hotel+Arawali+Hill" target="_blank">Get Directions</a>
            <a class="btn btn-ghost btn-sm" style="color:var(--sand);border-color:rgba(253,250,244,0.35)" href="tel:07725994050">Call Now</a>
          </div>
        </div>
      </div>
    </section>

    <!-- HOW TO REACH -->
    <section class="reach-section">
      <div class="section-center">
        <span class="eyebrow reveal">Getting Here</span>
        <h2 class="reveal">Every Route Leads to Rest</h2>
      </div>
      <div class="reach-cards">
        <div class="reach-card reveal">
          <div class="reach-icon">✈</div>
          <h4>By Air</h4>
          <p>Maharana Pratap Airport (Dabok) is approximately 25 km away. Taxis and cabs are readily available outside arrivals. Average journey: 35–40 minutes.</p>
        </div>
        <div class="reach-card reveal reveal-delay-1">
          <div class="reach-icon">🚆</div>
          <h4>By Train</h4>
          <p>Udaipur City Railway Station is roughly 4 km from the hotel. Auto-rickshaws and app-based cabs are easily available right outside.</p>
        </div>
        <div class="reach-card reveal reveal-delay-2">
          <div class="reach-icon">🚗</div>
          <h4>By Road</h4>
          <p>Located on Ambavgarh Road near Hotel Hill Top. Follow signs for Fateh Sagar Lake and continue toward Ambavgarh — we're clearly visible from the road.</p>
        </div>
      </div>
    </section>

    <!-- ATTRACTIONS -->
    <section class="attractions-section">
      <div class="section-center">
        <span class="eyebrow reveal">Explore Udaipur</span>
        <h2 class="reveal">The City of Lakes, At Your Doorstep</h2>
        <p class="section-lead reveal" style="color:var(--sage)">Everything Udaipur is famous for is just minutes away.</p>
      </div>
      <div class="attractions-scroll">
        <div class="attraction-card reveal">
          <div class="attraction-emoji">🌊</div>
          <h4>Fateh Sagar Lake</h4>
          <div class="attraction-dist">5 min drive</div>
          <p>A serene, crescent-shaped lake with boating, lakeside cafés, and island gardens.</p>
        </div>
        <div class="attraction-card reveal reveal-delay-1">
          <div class="attraction-emoji">🏯</div>
          <h4>City Palace</h4>
          <div class="attraction-dist">10 min drive</div>
          <p>The grand palace complex that overlooks Lake Pichola, showcasing royal Mewar grandeur.</p>
        </div>
        <div class="attraction-card reveal reveal-delay-2">
          <div class="attraction-emoji">🚣</div>
          <h4>Lake Pichola</h4>
          <div class="attraction-dist">10 min drive</div>
          <p>Udaipur's most iconic lake, home to Jag Mandir Island and breathtaking sunset views.</p>
        </div>
        <div class="attraction-card reveal">
          <div class="attraction-emoji">🏛</div>
          <h4>Bagore Ki Haveli</h4>
          <div class="attraction-dist">12 min drive</div>
          <p>A historic haveli with a museum of royal artefacts and evening cultural performances.</p>
        </div>
        <div class="attraction-card reveal reveal-delay-1">
          <div class="attraction-emoji">🕌</div>
          <h4>Jagdish Temple</h4>
          <div class="attraction-dist">12 min drive</div>
          <p>A magnificent 17th-century Indo-Aryan temple near the City Palace complex.</p>
        </div>
      </div>
    </section>

    <!-- CHECK-IN INFO -->
    <section class="checkin-section">
      <div class="section-center">
        <span class="eyebrow reveal" style="color:var(--sage)">Before You Arrive</span>
        <h2 class="reveal" style="color:var(--ivory)">Good to Know</h2>
      </div>
      <div class="checkin-grid">
        <div class="checkin-item reveal"><div class="checkin-icon">🕛</div><div class="checkin-label">Check-in Time</div><div class="checkin-value">12:00 PM</div></div>
        <div class="checkin-item reveal reveal-delay-1"><div class="checkin-icon">🕙</div><div class="checkin-label">Check-out Time</div><div class="checkin-value">11:00 AM</div></div>
        <div class="checkin-item reveal reveal-delay-2"><div class="checkin-icon">📞</div><div class="checkin-label">Front Desk</div><div class="checkin-value">24 Hours</div></div>
        <div class="checkin-item reveal"><div class="checkin-icon">🔓</div><div class="checkin-label">Cancellation</div><div class="checkin-value">Free on select rates</div></div>
        <div class="checkin-item reveal reveal-delay-1"><div class="checkin-icon">💳</div><div class="checkin-label">Payment</div><div class="checkin-value">Cash &amp; Digital</div></div>
        <div class="checkin-item reveal reveal-delay-2"><div class="checkin-icon">🅿</div><div class="checkin-label">Parking</div><div class="checkin-value">On-site Available</div></div>
      </div>
    </section>

    <!-- INSTAGRAM VISIT -->
    <section class="insta-section">
      <div class="section-center">
        <span class="eyebrow reveal">Our Community</span>
        <h2 class="reveal">See Our World Through Your Eyes</h2>
        <p class="section-lead reveal" style="color:var(--sage)">Tag us in your memories — #HotelArawaliHill #UdaipurDiaries</p>
      </div>
      <div class="insta-grid reveal" style="grid-template-columns:repeat(4,1fr)">
        <div class="insta-cell" style="background:linear-gradient(135deg,#2d3a28,#1a2a1a)">
          <div class="insta-cell-inner"><div style="width:100%;height:100%;background:linear-gradient(135deg,#2d3a28,#1a2a1a);display:flex;align-items:center;justify-content:center;font-size:36px;opacity:0.2">🌄</div></div>
          <div class="insta-overlay"><span class="insta-icon">❤</span><p class="insta-caption">Aravalli sunrise</p></div>
        </div>
        <div class="insta-cell" style="background:linear-gradient(135deg,#3d2e1a,#2a1a0a)">
          <div class="insta-cell-inner"><div style="width:100%;height:100%;background:linear-gradient(135deg,#3d2e1a,#2a1a0a);display:flex;align-items:center;justify-content:center;font-size:36px;opacity:0.2">🍛</div></div>
          <div class="insta-overlay"><span class="insta-icon">❤</span><p class="insta-caption">Rajasthani thali</p></div>
        </div>
        <div class="insta-cell" style="background:linear-gradient(135deg,#1a2535,#0e1520)">
          <div class="insta-cell-inner"><div style="width:100%;height:100%;background:linear-gradient(135deg,#1a2535,#0e1520);display:flex;align-items:center;justify-content:center;font-size:36px;opacity:0.2">🏨</div></div>
          <div class="insta-overlay"><span class="insta-icon">❤</span><p class="insta-caption">Room with a view</p></div>
        </div>
        <div class="insta-cell" style="background:linear-gradient(135deg,#2a1a10,#3d2010)">
          <div class="insta-cell-inner"><div style="width:100%;height:100%;background:linear-gradient(135deg,#2a1a10,#3d2010);display:flex;align-items:center;justify-content:center;font-size:36px;opacity:0.2">🌊</div></div>
          <div class="insta-overlay"><span class="insta-icon">❤</span><p class="insta-caption">Fateh Sagar Lake</p></div>
        </div>
      </div>
      <div style="text-align:center">
        <a class="btn btn-ghost" href="https://www.instagram.com/hotelarawalihill" target="_blank">Follow @hotelarawalihill →</a>
        <p style="font-size:13px;color:var(--sage);margin-top:16px">#HotelArawaliHill &nbsp;·&nbsp; #UdaipurDiaries &nbsp;·&nbsp; #AravalliHills</p>
      </div>
    </section>

    <!-- FINAL CTA -->
    <section class="cta-banner">
      <h2 class="reveal">The Hills Are Calling.</h2>
      <p class="reveal">Book your stay tonight and wake up to the most beautiful morning in Udaipur.</p>
      <div class="cta-buttons reveal">
        <button class="btn btn-dark" onclick="window.open('https://www.ixigo.com/hotels/3918054/details','_blank')">Book Your Room Now</button>
        <button class="btn btn-ghost-light" onclick="showPage('home')">Back to Home</button>
      </div>
    </section>

    <footer style="background:var(--slate);padding:40px 5%;text-align:center">
      <div style="font-family:var(--r-display);font-size:18px;font-weight:700;color:var(--ivory);letter-spacing:0.08em;margin-bottom:16px">HOTEL ARAWALI HILL</div>
      <div style="display:flex;justify-content:center;gap:24px;flex-wrap:wrap;margin-bottom:20px">
        <button onclick="showPage('home')" style="color:rgba(253,250,244,0.6);background:none;border:none;cursor:pointer;font-size:14px">Home</button>
        <button onclick="showPage('menu')" style="color:rgba(253,250,244,0.6);background:none;border:none;cursor:pointer;font-size:14px">Menu</button>
        <button onclick="showPage('about')" style="color:rgba(253,250,244,0.6);background:none;border:none;cursor:pointer;font-size:14px">About Us</button>
      </div>
      <p style="font-size:13px;color:rgba(253,250,244,0.4)">© 2024 Hotel Arawali Hill · L-18, Ambavgarh, Udaipur · 077259 94050</p>
    </footer>
  </div>
</div>

<script>
function showPage(name){
  document.querySelectorAll('.page').forEach(p=>p.classList.remove('active'));
  document.getElementById('page-'+name).classList.add('active');
  document.querySelectorAll('.nav-link').forEach(l=>l.classList.remove('active'));
  const navEl=document.getElementById('nav-'+name);
  if(navEl)navEl.classList.add('active');
  window.scrollTo({top:0,behavior:'smooth'});
  setTimeout(initReveal,100);
}

function toggleMobile(){
  const m=document.getElementById('mobile-menu');
  m.classList.toggle('open');
}

function switchTab(name,btn){
  document.querySelectorAll('.tab-btn').forEach(b=>b.classList.remove('active'));
  document.querySelectorAll('.tab-content').forEach(c=>c.classList.remove('active'));
  btn.classList.add('active');
  document.getElementById('tab-'+name).classList.add('active');
}

function switchSubtab(name,btn){
  document.querySelectorAll('.subtab-btn').forEach(b=>b.classList.remove('active'));
  document.querySelectorAll('.menu-subcontent').forEach(c=>c.classList.remove('active'));
  btn.classList.add('active');
  document.getElementById('subtab-'+name).classList.add('active');
}

// Scroll-triggered reveals
function initReveal(){
  const els=document.querySelectorAll('.reveal:not(.visible)');
  const obs=new IntersectionObserver((entries)=>{
    entries.forEach(e=>{if(e.isIntersecting){e.target.classList.add('visible');obs.unobserve(e.target)}});
  },{threshold:0.1,rootMargin:'0px 0px -40px 0px'});
  els.forEach(el=>obs.observe(el));
}

// Nav scroll effect
window.addEventListener('scroll',()=>{
  const nav=document.getElementById('main-nav');
  if(window.scrollY>60)nav.classList.add('scrolled');
  else nav.classList.remove('scrolled');
},{passive:true});

// Init
initReveal();
</script>
</body>
</html>
