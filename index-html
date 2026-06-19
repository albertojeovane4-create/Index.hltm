<!DOCTYPE html>
<html lang="pt">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Jeovane Produções — Serviços criativos que fazem a tua marca crescer</title>
<meta name="description" content="Estratégia de projeto, design gráfico, gestão de conta e edição de vídeo — checkout direto pelo WhatsApp.">

<!-- ============================================================
     CONFIGURAÇÃO RÁPIDA — troque só estas duas linhas
     ============================================================ -->
<!-- (a configuração real fica no bloco de JavaScript no fim do arquivo,
     procure por WHATSAPP_NUMBER e ADMIN_PASSWORD) -->

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:opsz,wght@12..96,400;12..96,600;12..96,700;12..96,800&family=Inter:wght@400;500;600;700&family=Space+Mono:wght@400;700&display=swap" rel="stylesheet">
<script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/4.4.4/chart.umd.min.js"></script>

<style>
/* ===================== TOKENS ===================== */
:root{
  --paper:#EFEDE6;
  --paper-2:#F8F7F2;
  --ink:#16140F;
  --ink-soft:#55503F;
  --pink:#FF3D7F;
  --pink-dark:#D6225C;
  --teal:#0B7A66;
  --teal-dark:#075B4C;
  --mustard:#FFC83D;
  --whats:#25D366;
  --whats-dark:#1DA851;
  --line:rgba(22,20,15,.16);
  --line-soft:rgba(22,20,15,.09);
  --radius:18px;
  --radius-sm:10px;
  --shadow:0 10px 30px rgba(22,20,15,.10);
  --shadow-lg:0 18px 50px rgba(22,20,15,.16);
  --display:"Bricolage Grotesque",system-ui,sans-serif;
  --body:"Inter",system-ui,sans-serif;
  --mono:"Space Mono",ui-monospace,monospace;
}

*{box-sizing:border-box;}
html{scroll-behavior:smooth;}
body{
  margin:0;
  background:var(--paper);
  color:var(--ink);
  font-family:var(--body);
  -webkit-font-smoothing:antialiased;
  min-height:100vh;
}
img{max-width:100%;display:block;}
a{color:inherit;}
button{font-family:inherit;cursor:pointer;}
:focus-visible{outline:3px solid var(--ink);outline-offset:2px;}
.hidden{display:none !important;}

@media (prefers-reduced-motion: reduce){
  *{animation-duration:.001ms !important;animation-iteration-count:1 !important;transition-duration:.001ms !important;scroll-behavior:auto !important;}
}

/* ===================== LAYOUT SHELL ===================== */
.site-header{
  position:sticky;top:0;z-index:40;
  display:flex;align-items:center;justify-content:space-between;
  padding:16px 28px;
  background:rgba(239,237,230,.86);
  backdrop-filter:blur(10px);
  border-bottom:1px solid var(--line);
}
.brand{
  font-family:var(--display);
  font-weight:800;
  font-size:1.35rem;
  letter-spacing:-.02em;
  text-decoration:none;
  display:flex;align-items:center;gap:8px;
}
.brand .dot{width:9px;height:9px;border-radius:50%;background:var(--pink);display:inline-block;}
.main-nav{display:flex;align-items:center;gap:22px;}
.nav-link{
  text-decoration:none;font-weight:600;font-size:.95rem;color:var(--ink-soft);
  display:flex;align-items:center;gap:6px;
}
.nav-link.cart-link{
  position:relative;color:var(--ink);
  background:var(--ink);color:var(--paper-2);
  padding:8px 14px;border-radius:999px;
}
.cart-badge{
  font-family:var(--mono);font-size:.72rem;
  background:var(--pink);color:#fff;
  padding:1px 6px;border-radius:999px;
  min-width:18px;text-align:center;
}

main#app{min-height:60vh;}

.site-footer{
  margin-top:60px;padding:34px 28px 90px;
  border-top:1px solid var(--line);
  display:flex;flex-wrap:wrap;gap:10px;justify-content:space-between;align-items:center;
  font-size:.85rem;color:var(--ink-soft);
}
.site-footer a{text-decoration:underline;text-underline-offset:3px;}

/* ===================== HERO ===================== */
.hero{
  padding:64px 28px 30px;
  max-width:1100px;margin:0 auto;
}
.eyebrow{
  font-family:var(--mono);
  text-transform:uppercase;
  letter-spacing:.12em;
  font-size:.72rem;
  color:var(--pink-dark);
  margin:0 0 10px;
  font-weight:700;
}
.hero h1{
  font-family:var(--display);
  font-weight:800;
  font-size:clamp(2.1rem,5.2vw,3.6rem);
  line-height:1.02;
  letter-spacing:-.02em;
  margin:0 0 18px;
  max-width:14ch;
}
.hero h1 em{font-style:normal;color:var(--pink);}
.hero p.lede{
  font-size:1.08rem;color:var(--ink-soft);max-width:46ch;margin:0 0 28px;
}

.marquee{
  border-top:1px solid var(--line);
  border-bottom:1px solid var(--line);
  overflow:hidden;
  white-space:nowrap;
  margin:0 0 46px;
}
.marquee-track{
  display:inline-block;
  padding:13px 0;
  font-family:var(--mono);
  font-size:.82rem;
  letter-spacing:.04em;
  animation:scroll-left 26s linear infinite;
}
.marquee-track span{margin:0 22px;color:var(--ink-soft);}
.marquee-track span.accent{color:var(--pink-dark);font-weight:700;}
@keyframes scroll-left{
  from{transform:translateX(0);}
  to{transform:translateX(-50%);}
}

/* ===================== PRODUCT GRID ===================== */
.grid-wrap{max-width:1100px;margin:0 auto;padding:0 28px 70px;}
.grid-head{display:flex;justify-content:space-between;align-items:baseline;margin-bottom:22px;flex-wrap:wrap;gap:8px;}
.grid-head h2{font-family:var(--display);font-size:1.5rem;margin:0;}
.grid-head .count{font-family:var(--mono);font-size:.8rem;color:var(--ink-soft);}

.product-grid{
  display:grid;
  grid-template-columns:repeat(auto-fill,minmax(260px,1fr));
  gap:26px;
}

.ticket-card{
  background:var(--paper-2);
  border:1px solid var(--line);
  border-radius:var(--radius);
  overflow:hidden;
  display:flex;flex-direction:column;
  box-shadow:var(--shadow);
  transition:transform .18s ease, box-shadow .18s ease;
}
.ticket-card:hover{transform:translateY(-4px);box-shadow:var(--shadow-lg);}

.ticket-media{
  position:relative;border:0;padding:0;margin:0;width:100%;background:none;text-align:left;
}
.ticket-media img{width:100%;height:170px;object-fit:cover;}
.stamp{
  position:absolute;top:12px;right:-30px;
  background:var(--ink);color:var(--mustard);
  font-family:var(--mono);font-size:.66rem;font-weight:700;
  padding:5px 34px;
  transform:rotate(8deg);
  box-shadow:0 3px 8px rgba(0,0,0,.25);
}

.perforation{
  height:14px;
  background-image:radial-gradient(circle, var(--paper) 3px, transparent 3.2px);
  background-size:16px 14px;
  background-position:6px center;
  background-repeat:repeat-x;
  border-top:1px dashed var(--line);
  border-bottom:1px dashed var(--line);
}

.ticket-body{padding:18px 18px 20px;display:flex;flex-direction:column;gap:6px;flex:1;}
.ticket-body .eyebrow{margin-bottom:2px;}
.ticket-body h3{
  font-family:var(--display);font-size:1.12rem;line-height:1.2;margin:0 0 4px;font-weight:700;
}
.ticket-body .desc{
  font-size:.88rem;color:var(--ink-soft);line-height:1.45;margin:0 0 10px;flex:1;
}
.price-row{display:flex;align-items:baseline;gap:9px;margin-bottom:12px;}
.old-price{font-family:var(--mono);font-size:.8rem;color:var(--ink-soft);text-decoration:line-through;}
.price{font-family:var(--mono);font-size:1.28rem;font-weight:700;}

.btn{
  border:none;border-radius:999px;padding:12px 20px;
  font-weight:700;font-size:.92rem;font-family:var(--body);
  display:inline-flex;align-items:center;justify-content:center;gap:8px;
  text-decoration:none;transition:transform .12s ease, filter .12s ease;
}
.btn:active{transform:scale(.97);}
.btn-primary{background:var(--pink);color:#fff;}
.btn-primary:hover{filter:brightness(1.06);}
.btn-ghost{background:transparent;color:var(--ink);border:1.5px solid var(--line);}
.btn-ghost:hover{border-color:var(--ink);}
.btn-block{width:100%;}
.btn-dark{background:var(--ink);color:var(--paper-2);}
.btn-whats{background:var(--whats);color:#fff;}
.btn-whats:hover{background:var(--whats-dark);}

/* ===================== MODAL (quick view) ===================== */
.modal-backdrop{
  position:fixed;inset:0;background:rgba(22,20,15,.55);
  display:flex;align-items:center;justify-content:center;
  padding:20px;z-index:80;
}
.modal{
  background:var(--paper-2);border-radius:var(--radius);
  max-width:560px;width:100%;max-height:88vh;overflow:auto;
  box-shadow:var(--shadow-lg);position:relative;
}
.modal-close{
  position:absolute;top:14px;right:14px;background:var(--ink);color:var(--paper-2);
  width:34px;height:34px;border-radius:50%;border:none;font-size:1.1rem;line-height:1;
}
.modal img{width:100%;height:220px;object-fit:cover;}
.modal-body{padding:22px;}
.modal-body h3{font-family:var(--display);font-size:1.4rem;margin:6px 0 8px;}
.modal-qty{display:flex;align-items:center;gap:12px;margin:16px 0;font-family:var(--mono);}
.modal-qty button{width:34px;height:34px;border-radius:8px;border:1px solid var(--line);background:#fff;font-size:1.1rem;}

/* ===================== TOAST ===================== */
#toast-region{position:fixed;bottom:24px;left:50%;transform:translateX(-50%);z-index:90;display:flex;flex-direction:column;gap:8px;align-items:center;}
.toast{
  background:var(--ink);color:var(--paper-2);
  padding:11px 18px;border-radius:999px;font-size:.86rem;font-weight:600;
  box-shadow:var(--shadow-lg);
  animation:toast-in .2s ease;
}
@keyframes toast-in{from{opacity:0;transform:translateY(10px);}to{opacity:1;transform:translateY(0);}}

/* ===================== WHATSAPP FLOAT ===================== */
.wa-float{
  position:fixed;bottom:22px;right:22px;z-index:70;
  width:58px;height:58px;border-radius:50%;
  background:var(--whats);border:none;
  display:flex;align-items:center;justify-content:center;
  box-shadow:0 10px 24px rgba(37,211,102,.45);
  animation:wa-pulse 2.6s ease-in-out infinite;
}
.wa-float:hover{background:var(--whats-dark);}
@keyframes wa-pulse{
  0%,100%{box-shadow:0 10px 24px rgba(37,211,102,.45);}
  50%{box-shadow:0 10px 30px rgba(37,211,102,.7);}
}

/* ===================== RECEIPT (cart / checkout) ===================== */
.receipt-wrap{max-width:560px;margin:0 auto;padding:54px 20px 90px;}
.receipt{
  background:var(--paper-2);
  border:1px solid var(--line);
  border-radius:var(--radius);
  padding:30px 26px;
  box-shadow:var(--shadow);
  position:relative;
}
.receipt h2{font-family:var(--display);font-size:1.6rem;margin:0 0 18px;}
.receipt.empty{text-align:center;padding:60px 26px;}
.receipt.empty h2{margin-top:4px;}
.receipt.empty .btn{margin-top:16px;}

.barcode{
  height:30px;margin:0 0 18px;border-radius:4px;
  background:repeating-linear-gradient(90deg, var(--ink) 0 2px, transparent 2px 5px, var(--ink) 5px 6px, transparent 6px 11px);
  opacity:.85;
}

.receipt-rows{display:flex;flex-direction:column;gap:12px;font-family:var(--mono);}
.receipt-row{display:flex;align-items:center;justify-content:space-between;gap:10px;font-size:.86rem;}
.receipt-row.sm{font-size:.82rem;}
.ri-name{display:flex;align-items:center;gap:8px;flex:1;}
.ri-remove{background:none;border:none;color:var(--ink-soft);font-size:1rem;line-height:1;padding:0 2px;}
.ri-remove:hover{color:var(--pink-dark);}
.ri-qty{display:flex;align-items:center;gap:8px;}
.ri-qty button{width:24px;height:24px;border-radius:6px;border:1px solid var(--line);background:#fff;font-family:var(--mono);}
.ri-price{min-width:84px;text-align:right;font-weight:700;}

.receipt-divider{
  border-top:1px dashed var(--line);margin:18px 0;
}
.receipt-total{
  display:flex;justify-content:space-between;align-items:baseline;
  font-family:var(--mono);font-weight:700;font-size:1.25rem;margin-bottom:22px;
}

.receipt label{
  display:block;font-size:.82rem;font-weight:600;color:var(--ink-soft);margin-bottom:14px;
}
.receipt input,.receipt textarea{
  display:block;width:100%;margin-top:6px;
  padding:11px 13px;border-radius:var(--radius-sm);
  border:1.5px solid var(--line);background:#fff;
  font-family:var(--body);font-size:.95rem;color:var(--ink);
}
.receipt input:focus,.receipt textarea:focus{border-color:var(--ink);}
.checkout-note{font-size:.78rem;color:var(--ink-soft);text-align:center;margin:12px 0 0;}

/* ===================== ADMIN ===================== */
.admin-gate{
  max-width:380px;margin:90px auto;padding:0 20px;
}
.admin-gate form{
  background:var(--ink);color:var(--paper-2);
  padding:32px 26px;border-radius:var(--radius);box-shadow:var(--shadow-lg);
}
.admin-gate h2{font-family:var(--display);margin:0 0 18px;}
.admin-gate .eyebrow{color:var(--mustard);}
.admin-gate label{display:block;font-size:.85rem;margin-bottom:18px;}
.admin-gate input{
  display:block;width:100%;margin-top:8px;padding:11px 13px;
  border-radius:var(--radius-sm);border:1.5px solid rgba(255,255,255,.2);
  background:rgba(255,255,255,.06);color:#fff;font-family:var(--mono);
}
.admin-error{color:var(--pink);font-size:.82rem;margin-top:10px;}
@keyframes shake{
  0%,100%{transform:translateX(0);}
  25%{transform:translateX(-6px);}
  75%{transform:translateX(6px);}
}
.shake{animation:shake .35s ease;}

.admin-dash{background:var(--ink);min-height:100vh;color:var(--paper-2);padding:34px 26px 90px;}
.admin-top{
  max-width:1180px;margin:0 auto 30px;
  display:flex;justify-content:space-between;align-items:flex-end;flex-wrap:wrap;gap:14px;
}
.admin-top h1{font-family:var(--display);font-size:1.7rem;margin:6px 0 0;}
.admin-top .eyebrow{color:var(--mustard);}
.admin-actions{display:flex;gap:10px;}
.admin-actions button{
  background:rgba(255,255,255,.08);color:#fff;border:1px solid rgba(255,255,255,.18);
  border-radius:999px;padding:9px 16px;font-size:.82rem;font-weight:600;
}
.admin-actions button:hover{background:rgba(255,255,255,.16);}

.admin-grid{max-width:1180px;margin:0 auto;display:grid;gap:20px;}
.stat-row{display:grid;grid-template-columns:repeat(auto-fit,minmax(190px,1fr));gap:16px;}
.stat-card{
  background:rgba(255,255,255,.05);border:1px solid rgba(255,255,255,.1);
  border-radius:var(--radius);padding:20px;
}
.stat-card .label{font-size:.76rem;color:rgba(255,255,255,.55);text-transform:uppercase;letter-spacing:.06em;font-weight:700;margin-bottom:8px;}
.stat-card .value{font-family:var(--mono);font-size:1.9rem;font-weight:700;}
.stat-card .value.pink{color:var(--pink);}
.stat-card .value.teal{color:#4FD8BD;}
.stat-card .value.mustard{color:var(--mustard);}

.insight-card{
  background:linear-gradient(135deg, rgba(255,61,127,.16), rgba(255,200,61,.10));
  border:1px solid rgba(255,200,61,.3);
  border-radius:var(--radius);padding:22px 24px;
  display:flex;gap:14px;align-items:flex-start;
}
.insight-card .ic-label{font-family:var(--mono);font-size:.72rem;text-transform:uppercase;letter-spacing:.08em;color:var(--mustard);font-weight:700;margin-bottom:6px;}
.insight-card p{margin:0;line-height:1.5;font-size:.98rem;}

.chart-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(320px,1fr));gap:18px;}
.chart-card{
  background:rgba(255,255,255,.05);border:1px solid rgba(255,255,255,.1);
  border-radius:var(--radius);padding:20px;
}
.chart-card h3{font-family:var(--display);font-size:1rem;margin:0 0 14px;font-weight:700;}
.chart-card canvas{max-height:240px;}

.admin-table-wrap{
  background:rgba(255,255,255,.05);border:1px solid rgba(255,255,255,.1);
  border-radius:var(--radius);padding:20px;overflow-x:auto;
}
.admin-table-wrap h3{font-family:var(--display);font-size:1rem;margin:0 0 14px;}
table.admin-table{width:100%;border-collapse:collapse;font-size:.86rem;min-width:560px;}
table.admin-table th{
  text-align:left;font-family:var(--mono);font-size:.72rem;text-transform:uppercase;letter-spacing:.05em;
  color:rgba(255,255,255,.5);padding:8px 10px;border-bottom:1px solid rgba(255,255,255,.14);
}
table.admin-table td{padding:10px 10px;border-bottom:1px solid rgba(255,255,255,.07);font-family:var(--mono);}
table.admin-table td.prod-name{font-family:var(--body);font-weight:600;}
.conv-pill{padding:2px 9px;border-radius:999px;font-size:.76rem;font-weight:700;}
.conv-good{background:rgba(79,216,189,.18);color:#4FD8BD;}
.conv-mid{background:rgba(255,200,61,.18);color:var(--mustard);}
.conv-low{background:rgba(255,255,255,.1);color:rgba(255,255,255,.6);}

@media (max-width:640px){
  .site-header{padding:14px 16px;}
  .hero{padding:40px 18px 16px;}
  .receipt-wrap{padding:36px 14px 70px;}
}
</style>
</head>
<body>

<header class="site-header">
  <a href="#/" class="brand"><span class="dot"></span>Jeovane Produções</a>
  <nav class="main-nav">
    <a href="#/" class="nav-link">Loja</a>
    <a href="#/cart" class="nav-link cart-link">
      Carrinho <span class="cart-badge">0</span>
    </a>
  </nav>
</header>

<main id="app"></main>

<button class="wa-float" id="wa-float" aria-label="Falar no WhatsApp">
  <svg width="28" height="28" viewBox="0 0 32 32" fill="#fff"><path d="M16.04 3C9.37 3 3.97 8.39 3.97 15.06c0 2.23.6 4.32 1.65 6.12L3.5 28.5l7.5-1.96a12.6 12.6 0 0 0 5.04 1.04h.01c6.67 0 12.06-5.39 12.06-12.06C28.11 8.39 22.71 3 16.04 3zm0 22.04h-.01a10.4 10.4 0 0 1-5.32-1.46l-.38-.23-3.97 1.04 1.06-3.87-.25-.4a10.43 10.43 0 0 1-1.6-5.56c0-5.76 4.7-10.45 10.48-10.45 2.8 0 5.43 1.09 7.41 3.07a10.36 10.36 0 0 1 3.06 7.39c0 5.76-4.7 10.47-10.48 10.47zm5.74-7.84c-.31-.16-1.86-.92-2.15-1.02-.29-.1-.5-.16-.71.16-.21.31-.81 1.02-1 1.23-.18.21-.37.23-.68.08-.31-.16-1.32-.49-2.51-1.56-.93-.83-1.56-1.86-1.74-2.17-.18-.31-.02-.48.14-.63.14-.14.31-.37.47-.55.16-.18.21-.31.31-.52.1-.21.05-.39-.03-.55-.08-.16-.71-1.72-.97-2.35-.26-.62-.52-.54-.71-.55h-.6c-.21 0-.55.08-.84.39-.29.31-1.1 1.08-1.1 2.63 0 1.55 1.13 3.05 1.29 3.26.16.21 2.22 3.39 5.38 4.75.75.32 1.34.52 1.8.66.76.24 1.45.21 2 .13.61-.09 1.86-.76 2.12-1.49.26-.74.26-1.36.18-1.49-.08-.13-.29-.21-.6-.36z"/></svg>
</button>

<div id="toast-region"></div>

<footer class="site-footer">
  <span>© 2026 Jeovane Produções — checkout simples, sem cadastro.</span>
  <a href="#/admin">Painel administrativo</a>
</footer>

<script>
/* ======================================================================
   CONFIGURAÇÃO — troque aqui
   ====================================================================== */
const WHATSAPP_NUMBER = "258864037244"; // <- TROQUE: DDI+número, só dígitos. 258 = Moçambique + 864037244
const ADMIN_PASSWORD  = "admin123";      // <- TROQUE: senha do painel /admin

/* ======================================================================
   PRODUTOS
   ====================================================================== */
const PRODUCTS = [
  {
    id:"p1",
    title:"Estratégia de Projeto",
    category:"Consultoria",
    price:3500.00, oldPrice:4500.00,
    desc:"Planeamento estratégico completo do teu projeto, do conceito ao lançamento, com plano de ação claro e objetivo.",
    badge:"Mais procurado",
    img:"https://placehold.co/600x400/FF3D7F/F8F7F2?font=montserrat&text=Estrategia+de+Projeto"
  },
  {
    id:"p2",
    title:"Design Gráfico",
    category:"Design",
    price:1200.00, oldPrice:1600.00,
    desc:"Identidade visual, artes para redes sociais e materiais gráficos profissionais para a tua marca.",
    img:"https://placehold.co/600x400/0B7A66/F8F7F2?font=montserrat&text=Design+Grafico"
  },
  {
    id:"p3",
    title:"Curadoria de Conta",
    category:"Gestão de Redes",
    price:5000.00,
    desc:"Gestão e curadoria completa da tua conta nas redes sociais, com conteúdo planeado e publicado mensalmente.",
    badge:"Pacote Premium",
    img:"https://placehold.co/600x400/16140F/FFC83D?font=montserrat&text=Curadoria+de+Conta"
  },
  {
    id:"p4",
    title:"Edição de Vídeo",
    category:"Audiovisual",
    price:1800.00, oldPrice:2200.00,
    desc:"Edição profissional de vídeos para redes sociais, YouTube ou publicidade, com cortes dinâmicos e legendas.",
    badge:"Novo",
    img:"https://placehold.co/600x400/D6225C/F8F7F2?font=montserrat&text=Edicao+de+Video"
  }
];

function getProduct(id){ return PRODUCTS.find(p=>p.id===id); }
function fmt(n){ return (Number(n)||0).toLocaleString('pt-PT',{minimumFractionDigits:2,maximumFractionDigits:2}); }

/* ======================================================================
   CARRINHO (localStorage)
   ====================================================================== */
const CART_KEY = "bazar_cart";
function loadCart(){ try{ re
