# Invitation-mariage-Thierry-et-Safi-
Invitation 
<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Thierry &amp; Safi — 10 décembre 2026</title>
<meta name="description" content="Thierry & Safi vous invitent à leur mariage le 10 décembre 2026 à Goma.">
<meta name="theme-color" content="#4a0a17">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Pinyon+Script&family=Bodoni+Moda:ital,wght@0,400;0,500;1,400&family=Cinzel:wght@400;500&family=Jost:wght@300;400;500&display=swap" rel="stylesheet">
<style>
:root{--bx:#6b1426;--bx-d:#4a0a17;--ivoire:#f7f0e6;--sable:#ebdfd0;--or:#b8975a;--terra:#b9684a;--terra-d:#9a523a;--txt:#3a2a2a;
--script:'Pinyon Script',cursive;--titre:'Bodoni Moda',serif;--cin:'Cinzel',serif;--texte:'Jost',sans-serif}
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{font-family:var(--texte);font-weight:300;color:var(--txt);background:var(--ivoire);line-height:1.7;font-size:17px;-webkit-font-smoothing:antialiased;overflow-x:hidden}
body.lock{overflow:hidden;height:100%}
img{display:block;max-width:100%}
a{color:inherit}
:focus-visible{outline:2px solid var(--or);outline-offset:3px}

/* ---------- OUVERTURE ---------- */
#intro{position:fixed;inset:0;z-index:100;background:radial-gradient(circle at 50% 40%,var(--bx) 0,var(--bx-d) 80%);display:flex;flex-direction:column;align-items:center;justify-content:center;gap:76px;padding:24px;transition:opacity 1.6s ease,visibility 1.6s}
#intro.gone{opacity:0;visibility:hidden}
.env{position:relative;width:min(84vw,360px);aspect-ratio:10/7;perspective:1200px}
.env>*{position:absolute}
.env-back{inset:0;background:var(--terra-d);border-radius:3px;box-shadow:0 30px 60px rgba(0,0,0,.45)}
.env-front{inset:0;background:linear-gradient(160deg,#c77658,var(--terra));clip-path:polygon(0 0,50% 56%,100% 0,100% 100%,0 100%);z-index:3;border-radius:3px}
.flap{left:0;right:0;top:0;height:56%;background:linear-gradient(180deg,#a9573b,var(--terra));clip-path:polygon(0 0,100% 0,50% 100%);transform-origin:top;z-index:4;transition:transform 1.3s cubic-bezier(.6,.05,.3,1),z-index 0s .55s}
.seal{left:50%;top:56%;width:68px;height:68px;margin:-34px 0 0 -34px;border-radius:50%;z-index:5;background:radial-gradient(circle at 35% 30%,#9a2038,var(--bx) 55%,var(--bx-d));box-shadow:0 5px 14px rgba(0,0,0,.5),inset 0 0 0 4px rgba(255,255,255,.06);display:grid;place-items:center;font-family:var(--script);font-size:25px;color:#e8cf9b;transition:opacity .7s ease,transform .7s ease}
.card{left:6%;right:6%;bottom:5%;height:88%;background:var(--ivoire);z-index:2;display:flex;flex-direction:column;align-items:center;justify-content:center;text-align:center;gap:6px;box-shadow:0 2px 14px rgba(0,0,0,.2);transition:transform 1.5s cubic-bezier(.5,.05,.2,1) 1.1s}
.card .s{font-family:var(--script);font-size:34px;color:var(--bx);line-height:1}
.card .c{font-family:var(--cin);font-size:10px;letter-spacing:.28em;color:var(--or)}
.open .flap{transform:rotateX(180deg);z-index:1}
.open .seal{opacity:0;transform:scale(.7)}
.open .card{transform:translateY(-62%)}
.open.out .card{z-index:6;transform:translateY(-22%) scale(1.14);transition:transform 1.4s ease,z-index 0s}
.btn{font-family:var(--cin);letter-spacing:.18em;font-size:12.5px;text-transform:uppercase;text-decoration:none;color:var(--ivoire);background:transparent;border:1px solid var(--or);padding:16px 30px;cursor:pointer;transition:background .6s,color .6s,opacity .8s}
.btn:hover{background:var(--or);color:var(--bx-d)}
.btn.solid{background:var(--bx);border-color:var(--bx);color:var(--ivoire);display:inline-block}
.btn.solid:hover{background:var(--bx-d);color:var(--ivoire)}
.btn.line{color:var(--bx);border-color:var(--bx)}
.btn.line:hover{background:var(--bx);color:var(--ivoire)}
#intro.started .btn{opacity:0;pointer-events:none}

/* ---------- SITE ---------- */
#site{opacity:0;transition:opacity 2s ease}
#site.show{opacity:1}
section{padding:96px 26px;text-align:center;position:relative}
.wrap{max-width:560px;margin:0 auto}
.cin{font-family:var(--cin);font-size:12px;letter-spacing:.3em;text-transform:uppercase;color:var(--or)}
h2{font-family:var(--titre);font-weight:400;font-size:clamp(34px,9vw,46px);line-height:1.15;color:var(--bx);margin:14px 0 40px}
h2 .w{display:inline-block;overflow:hidden;vertical-align:bottom;padding:0 .08em .12em}
h2 .w>i{display:inline-block;font-style:normal;transform:translateY(105%);transition:transform 1.3s cubic-bezier(.2,.7,.2,1)}
h2.in .w>i{transform:none}
.alt{background:var(--sable)}
.dark{background:var(--bx-d);color:var(--ivoire)}
.dark h2{color:var(--ivoire)}

/* reveal */
.rv{opacity:0;transform:translateY(26px);transition:opacity 1.5s ease,transform 1.5s ease}
.rv.in{opacity:1;transform:none}

/* hero */
.hero{min-height:100svh;padding:0;display:flex;align-items:flex-end;justify-content:center;color:var(--ivoire);overflow:hidden;background:var(--bx-d)}
.hero-bg{position:absolute;inset:0;width:100%;height:100%;object-fit:cover;object-position:50% 30%;transform:scale(1.12);transition:transform 18s ease-out}
.ready .hero-bg{transform:scale(1)}
.hero::after{content:"";position:absolute;inset:0;background:linear-gradient(180deg,rgba(74,10,23,.45) 0,rgba(74,10,23,.05) 32%,rgba(74,10,23,.78) 72%,rgba(74,10,23,.95) 100%)}
.hero-in{position:relative;z-index:2;padding:0 22px calc(44px + env(safe-area-inset-bottom));width:100%;max-width:560px}
.hero .cin{color:#e8cf9b}
.names{font-family:var(--script);font-weight:400;font-size:clamp(64px,21vw,104px);line-height:.95;margin:10px 0 6px;text-shadow:0 2px 24px rgba(0,0,0,.35)}
.names span{display:block}.names .and{font-size:.5em;color:#e8cf9b;line-height:1}
.hero p.acc{font-size:17px;max-width:360px;margin:12px auto 6px}
.hero .date{font-family:var(--titre);font-size:21px;letter-spacing:.04em}
.count{display:flex;justify-content:center;gap:10px;margin-top:26px}
.count div{min-width:70px;padding:12px 6px;border:1px solid rgba(232,207,155,.45);background:rgba(74,10,23,.35);backdrop-filter:blur(4px)}
.count b{display:block;font-family:var(--titre);font-weight:400;font-size:30px;line-height:1.1}
.count small{font-family:var(--cin);font-size:9.5px;letter-spacing:.2em;text-transform:uppercase;color:#e8cf9b}
.hero .intro-el{opacity:0;transform:translateY(20px);transition:opacity 2s ease,transform 2s ease}
.ready .hero .intro-el{opacity:1;transform:none}
.ready .hero .intro-el:nth-child(2){transition-delay:.4s}.ready .hero .intro-el:nth-child(3){transition-delay:.9s}
.ready .hero .intro-el:nth-child(4){transition-delay:1.3s}.ready .hero .intro-el:nth-child(5){transition-delay:1.7s}

/* histoire */
.tl{position:relative;text-align:left;padding-left:34px;margin-top:10px}
.tl::before,.tl .fill{content:"";position:absolute;left:7px;top:6px;bottom:6px;width:1px;background:rgba(107,20,38,.2)}
.tl .fill{background:var(--bx);bottom:auto;height:calc((100% - 12px) * var(--p,0));transition:height .3s linear}
.ev{position:relative;padding-bottom:46px}.ev:last-child{padding-bottom:0}
.ev::before{content:"";position:absolute;left:-34px;top:6px;width:15px;height:15px;border-radius:50%;background:var(--ivoire);border:1px solid var(--bx);transition:background 1s,transform 1s}
.ev.in::before{background:var(--bx);transform:scale(1.1)}
.ev .cin{font-size:11px}
.ev h3{font-family:var(--titre);font-weight:400;font-size:25px;color:var(--bx);margin:4px 0 6px}

/* galerie */
.gal{display:grid;gap:22px;max-width:520px;margin:0 auto}
.ph{overflow:hidden;aspect-ratio:4/5;position:relative;background:var(--sable)}
.ph img{position:absolute;left:0;top:-9%;width:100%;height:118%;object-fit:cover;will-change:transform}
.ph:nth-child(even){margin-left:9%}.ph:nth-child(odd){margin-right:9%}

/* programme */
.prog{list-style:none;text-align:left}
.prog li{display:grid;grid-template-columns:78px 1fr;gap:18px;padding:22px 0;border-top:1px solid rgba(232,207,155,.3)}
.prog li:last-child{border-bottom:1px solid rgba(232,207,155,.3)}
.prog b{font-family:var(--titre);font-weight:400;font-size:26px;color:#e8cf9b;line-height:1.2}
.prog h3{font-family:var(--cin);font-weight:400;font-size:15px;letter-spacing:.16em;text-transform:uppercase}
.prog p{font-size:15px;opacity:.85}

/* lieu */
.lieu h3{font-family:var(--titre);font-weight:400;font-size:26px;color:var(--bx)}
.map{margin:30px -26px 30px;height:300px;border:0;width:calc(100% + 52px);filter:sepia(.25) saturate(.85)}

/* tenue */
.pastilles{display:flex;justify-content:center;gap:10px;margin-top:34px}
.pastilles figure{width:88px}
.pastilles figcaption small{display:block;font-family:var(--texte);font-size:12.5px;letter-spacing:0;text-transform:none;opacity:.7;margin-top:3px}
.pastilles i{display:block;width:72px;height:72px;border-radius:50%;margin:0 auto 10px;box-shadow:inset 0 0 0 1px rgba(58,42,42,.18),0 6px 14px rgba(58,42,42,.12)}
.pastilles figcaption{font-family:var(--cin);font-size:10.5px;letter-spacing:.14em;text-transform:uppercase}

/* faire-part */
.fp p+p{margin-top:8px}
.fp .verset{font-family:var(--titre);font-style:italic;font-size:22px;line-height:1.5;color:var(--bx)}
.fp .orn{width:56px;height:1px;background:var(--or);margin:30px auto}
.fp .fam{font-family:var(--cin);font-size:14px;letter-spacing:.14em;text-transform:uppercase;color:var(--bx);margin-top:14px}
.fp .et{font-family:var(--script);font-size:32px;color:var(--or);line-height:1.2}
.fp .ep{font-family:var(--titre);font-size:30px;line-height:1.2;color:var(--bx);margin-top:14px}
.contact{margin-top:54px}
.contact a{display:inline-block;font-family:var(--titre);font-size:21px;color:var(--bx);text-decoration:none;margin:8px 8px 0}
/* rsvp & footer */
.limite{font-family:var(--titre);font-style:italic;font-size:21px;color:var(--bx);margin:22px 0 30px}
footer{background:var(--bx-d);color:var(--ivoire);text-align:center;padding:84px 26px calc(60px + env(safe-area-inset-bottom))}
footer .m{font-family:var(--titre);font-style:italic;font-size:24px;line-height:1.4;max-width:320px;margin:0 auto 24px}
footer .ini{font-family:var(--script);font-size:64px;color:#e8cf9b;line-height:1}
footer .tag{font-family:var(--cin);font-size:13px;letter-spacing:.24em;margin-top:14px}

@media(min-width:760px){body{font-size:18px}.gal{grid-template-columns:1fr 1fr;max-width:820px}.ph:nth-child(n){margin:0}.ph:nth-child(even){margin-top:56px}.wrap{max-width:620px}.map{margin-left:0;margin-right:0;width:100%}}

@media(prefers-reduced-motion:reduce){
 html{scroll-behavior:auto}
 *,*::before,*::after{transition:none!important;animation:none!important}
 .rv,.hero .intro-el{opacity:1;transform:none}
 h2 .w>i{transform:none}
 .hero-bg{transform:none}
 .ph img{top:-9%}
}
</style>
</head>
<body class="lock">

<!-- ==================== TEXTES À MODIFIER ==================== -->
<script>
const C = {
  prenom1: "Thierry",
  prenom2: "Safi",
  initiales: "T&S",
  hashtag: "#ThierryEtSafi2026",
  dateJour: "2026-12-10T07:30:00+02:00",   // début de la journée : mariage civil (Goma = +02:00)
  dateTexte: "Jeudi 10 décembre 2026",
  dateCourte: "10 · 12 · 2026",
  invitation: "Vous êtes invités",
  accueil: "Avec joie, nous vous invitons à célébrer le plus beau jour de notre vie.",

  fairepart: {
    verset: "Celui qui trouve une épouse trouve le bonheur, c’est une faveur qu’il obtient de l’Éternel.",
    intro: "Ensemble avec leurs familles",
    famille1: "Kaduguzo Kozibwa",
    famille2: "Bagalwa Kazimbe",
    annonce: "ont la joie de vous annoncer le mariage de leurs enfants",
    epoux: "Thierry Kozibwa",
    epouse: "Safi Kazimbe",
    suite: "Poursuivant leur grand amour pour un long voyage de la vie vers le bonheur et la vie de couple, ils se marieront le jeudi 10 décembre 2026.",
    invitation: "Vous êtes cordialement invités à prendre part à leur bonheur."
  },

  histoire: [
    { quand: "Notre rencontre",         titre: "Une même église", texte: "Nous fréquentions la même église." },
    { quand: "Premier rendez-vous",     titre: "Le début de nos rires",        texte: "Un premier rendez-vous, des conversations qui n’en finissaient plus, et la certitude de nous être trouvés." },
    { quand: "La demande en mariage",   titre: "Un oui du fond du cœur",       texte: "Un jour, la question est venue. Un « oui » sincère, et le début d’un engagement pour la vie, sous le regard de l’Éternel." }
  ],

  programme: [
    { h: "7h30", t: "Mariage civil",         d: "À la commune de Goma." },
    { h: "12h",  t: "Mariage religieux",     d: "À l’église 5ème CELPA Ebenezer." },
    { h: "14h",  t: "Prise de vue",          d: "À Mawe Hayi." },
    { h: "15h",  t: "Réception des invités", d: "Dans la salle de l’hôtel La Joie Plaza, à la frontière." }
  ],

  lieu: {
    role: "Réception des invités",
    nom: "Hôtel La Joie Plaza",
    adresse: "La frontière, Goma, RD Congo",
    recherche: "Hotel La Joie Plaza Goma"       // texte utilisé pour la carte et l'itinéraire
  },

  tenue: {
    texte: "Chaque moment de la journée a sa tenue. Merci de vous habiller aux couleurs ci-dessous.",
    couleurs: [
      { nom: "Rose",           moment: "État civil",        fond: "#e58aa8" },
      { nom: "Pagne",          moment: "Mariage religieux", fond: "repeating-radial-gradient(circle at 50% 50%,#b8975a 0 4px,#6b1426 4px 9px,#f3e9dc 9px 12px)" },
      { nom: "Rouge bordeaux", moment: "Soirée",            fond: "#6b1426" }
    ]
  },

  rsvp: {
    texte: "Votre présence nous ferait un immense plaisir. Merci de nous répondre avant le :",
    limite: "1er décembre 2026",
    bouton: "Répondre sur WhatsApp",
    lien: "https://wa.me/243974669563?text=" + encodeURIComponent("Bonjour, je confirme ma présence au mariage de Thierry et Safi."),
    // pour un formulaire à la place : lien: "https://forms.gle/...", bouton: "Répondre à l’invitation"
    contact: { titre: "Comité organisateur", tels: ["+243 974 669 563", "+243 971 241 012"] }
  },

  merci: "Merci de faire partie de notre histoire"
};
</script>
<!-- ======================================================= -->

<div id="intro" role="dialog" aria-label="Invitation">
  <div class="env" id="env">
    <div class="env-back"></div>
    <div class="card"><span class="c">MARIAGE</span><span class="s" id="cardNames"></span><span class="c" id="cardDate"></span></div>
    <div class="env-front"></div>
    <div class="flap"></div>
    <div class="seal" id="seal"></div>
  </div>
  <button class="btn" id="openBtn" type="button">Ouvrir notre invitation</button>
</div>

<main id="site">
  <header class="hero" id="accueil">
    <img class="hero-bg" src="photos/accueil.jpg" alt="Thierry et Safi">
    <div class="hero-in">
      <p class="cin intro-el" id="hInv"></p>
      <h1 class="names intro-el"><span id="n1"></span><span class="and">&amp;</span><span id="n2"></span></h1>
      <p class="acc intro-el" id="hAcc"></p>
      <p class="date intro-el" id="hDate"></p>
      <div class="count intro-el" id="count" aria-live="off"></div>
    </div>
  </header>

  <section class="alt fp" id="fairepart"><div class="wrap rv" id="fp"></div></section>

  <section id="histoire"><div class="wrap">
    <p class="cin rv">Notre histoire</p>
    <h2 class="split">Comment tout a commencé</h2>
    <div class="tl" id="tl"><span class="fill"></span></div>
  </div></section>

  <section class="alt" id="galerie"><div class="wrap">
    <p class="cin rv">Galerie</p>
    <h2 class="split">Quelques souvenirs</h2>
    <div class="gal" id="gal"></div>
  </div></section>

  <section class="dark" id="programme"><div class="wrap">
    <p class="cin rv">Le programme</p>
    <h2 class="split">Le grand jour</h2>
    <ul class="prog" id="prog"></ul>
  </div></section>

  <section class="lieu" id="lieu"><div class="wrap">
    <p class="cin rv">Le lieu</p>
    <h2 class="split">Où nous retrouver</h2>
    <div class="rv"><p class="cin" id="lRole" style="margin-bottom:6px"></p><h3 id="lNom"></h3><p id="lAdr"></p></div>
    <iframe class="map rv" id="map" title="Carte du lieu" loading="lazy" referrerpolicy="no-referrer-when-downgrade" allowfullscreen></iframe>
    <a class="btn solid rv" id="itin" target="_blank" rel="noopener">Ouvrir l’itinéraire</a>
  </div></section>

  <section class="alt" id="tenue"><div class="wrap">
    <p class="cin rv">Tenue</p>
    <h2 class="split">Dress code</h2>
    <p class="rv" id="tTxt"></p>
    <div class="pastilles rv" id="past"></div>
  </div></section>

  <section id="rsvp"><div class="wrap">
    <p class="cin rv">Confirmer ma présence</p>
    <h2 class="split">Serez-vous des nôtres ?</h2>
    <p class="rv" id="rTxt"></p>
    <p class="limite rv" id="rLim"></p>
    <a class="btn solid rv" id="rBtn" target="_blank" rel="noopener"></a>
    <div class="contact rv"><p class="cin" id="cTitre"></p><p id="cTels"></p></div>
  </div></section>

  <footer>
    <p class="m rv" id="fMerci"></p>
    <p class="ini rv" id="fIni"></p>
    <p class="tag rv" id="fTag"></p>
  </footer>
</main>

<script>
(function(){
  const $ = id => document.getElementById(id);
  const calm = matchMedia('(prefers-reduced-motion: reduce)').matches;
  const ini = C.initiales.replace('&','&amp;');

  /* ---- remplissage ---- */
  document.title = C.prenom1 + ' & ' + C.prenom2 + ' — ' + C.dateTexte.replace(/^\S+ /,'');
  $('seal').innerHTML = ini;
  $('cardNames').textContent = C.prenom1 + ' & ' + C.prenom2;
  $('cardDate').textContent = C.dateCourte;
  $('hInv').textContent = C.invitation;
  $('n1').textContent = C.prenom1; $('n2').textContent = C.prenom2;
  $('hAcc').textContent = C.accueil; $('hDate').textContent = C.dateTexte;
  $('count').innerHTML = ['jours','heures','minutes','secondes'].map(l=>`<div><b data-u="${l}">00</b><small>${l}</small></div>`).join('');
  $('tl').insertAdjacentHTML('beforeend', C.histoire.map(e=>`<div class="ev rv"><p class="cin">${e.quand}</p><h3>${e.titre}</h3><p>${e.texte}</p></div>`).join(''));
  $('gal').innerHTML = [1,2,3,4].map(n=>`<div class="ph rv"><img src="photos/galerie-${n}.jpg" alt="Photo ${n} de Thierry et Safi" loading="lazy"></div>`).join('');
  $('prog').innerHTML = C.programme.map(p=>`<li class="rv"><b>${p.h}</b><div><h3>${p.t}</h3><p>${p.d}</p></div></li>`).join('');
  const q = encodeURIComponent(C.lieu.recherche);
  $('lRole').textContent = C.lieu.role; $('lNom').textContent = C.lieu.nom; $('lAdr').textContent = C.lieu.adresse;
  $('map').src = 'https://www.google.com/maps?q=' + q + '&output=embed';
  $('itin').href = 'https://www.google.com/maps/dir/?api=1&destination=' + q;
  $('tTxt').textContent = C.tenue.texte;
  $('past').innerHTML = C.tenue.couleurs.map(c=>`<figure><i style="background:${c.fond}"></i><figcaption>${c.nom}<small>${c.moment}</small></figcaption></figure>`).join('');
  $('rTxt').textContent = C.rsvp.texte; $('rLim').textContent = C.rsvp.limite; $('rBtn').href = C.rsvp.lien; $('rBtn').textContent = C.rsvp.bouton;
  $('cTitre').textContent = C.rsvp.contact.titre;
  $('cTels').innerHTML = C.rsvp.contact.tels.map(t=>`<a href="tel:${t.replace(/\s/g,'')}">${t}</a>`).join('');
  $('fMerci').textContent = C.merci; $('fIni').innerHTML = ini; $('fTag').textContent = C.hashtag;
  const f = C.fairepart;
  $('fp').innerHTML = `<p class="verset">« ${f.verset} »</p><div class="orn"></div><p>${f.intro}</p><p class="fam">${f.famille1}</p><p>et la famille</p><p class="fam">${f.famille2}</p><p style="margin-top:14px">${f.annonce}</p><p class="ep">${f.epoux}</p><p class="et">et</p><p class="ep">${f.epouse}</p><div class="orn"></div><p>${f.suite}</p><p style="margin-top:18px;color:var(--bx)">${f.invitation}</p>`;

  /* ---- titres mot par mot ---- */
  document.querySelectorAll('h2.split').forEach(h=>{
    h.innerHTML = h.textContent.trim().split(/\s+/).map((w,i)=>`<span class="w"><i style="transition-delay:${i*.14}s">${w}</i></span>`).join(' ');
  });

  /* ---- compte à rebours ---- */
  const target = new Date(C.dateJour).getTime();
  const pad = n => String(n).padStart(2,'0');
  function t
