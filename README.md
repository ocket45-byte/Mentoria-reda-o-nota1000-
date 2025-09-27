
<html lang="pt-BR">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Redação Nota 1000 em 14 Dias — Método Testado por +500 Estudantes</title>
<style>
:root {
  --bg: #0f172a;
  --card: #ffffff;
  --accent: #0b84ff;
  --accent-dark: #0759b5;
  --highlight: #f97316;
  --highlight-dark: #c2410c;
  --green: #10b981;
  --muted: #6b7280;
  --radius: 14px;
  --ff-sans: "Inter", "Segoe UI", Roboto, Arial, sans-serif;
  --glass: rgba(255,255,255,0.06);
  --trans: 0.28s;
}
* { box-sizing: border-box; margin:0; padding:0; }
html,body{height:100%}
body { font-family: var(--ff-sans); background: linear-gradient(180deg, var(--bg), #1e293b); color: #111827; line-height: 1.6; overflow-x:hidden; -webkit-font-smoothing:antialiased; -moz-osx-font-smoothing:grayscale; }
.container { max-width: 1100px; margin: auto; padding: 28px 20px 120px; }

/* TOPBAR */
.topbar {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  background: linear-gradient(90deg,var(--accent),var(--accent-dark));
  color: #fff;
  text-align: center;
  padding: 10px 8px;
  z-index: 9998;
  font-weight:700;
  box-shadow: 0 6px 30px rgba(2,6,23,0.45);
  transform: translateY(0);
}
.topbar small { opacity:0.95; }

/* HERO */
.hero {
  text-align: center;
  padding: 48px 24px;
  background: linear-gradient(120deg, var(--accent), var(--accent-dark));
  border-radius: var(--radius);
  margin: 72px 0 32px; /* leave space for topbar */
  box-shadow: 0 10px 40px rgba(2,6,23,0.5);
  position: relative;
  overflow: hidden;
}
.hero h1 { font-size: 2.6rem; color: #fff; line-height:1.08; margin-bottom:12px; animation: pulse-title 2200ms infinite; }
@keyframes pulse-title { 0%,100%{transform:scale(1)}50%{transform:scale(1.02)} }
.hero p { font-size: 1.12rem; color: rgba(255,255,255,0.95); margin-bottom: 12px; max-width:900px; margin-left:auto;margin-right:auto; }
.social-proof { font-size: 0.98rem; color: rgba(255,255,255,0.88); margin-bottom: 18px; }

/* CTA */
.price { font-size: 2rem; font-weight: 800; margin: 10px 0; color: var(--green); text-shadow: 0 2px 8px rgba(0,0,0,0.25); }
.cta {
  display: inline-block;
  text-decoration: none;
  background: var(--accent);
  color: white;
  padding: 14px 20px;
  border-radius: 12px;
  font-weight: 800;
  transition: transform var(--trans), background var(--trans);
  box-shadow: 0 6px 22px rgba(3,7,36,0.35);
  margin-top: 6px;
}
.cta:hover { background: var(--accent-dark); transform: translateY(-4px); }

/* MAIN SECTION CARD */
.section {
  background: var(--card);
  padding: 28px;
  border-radius: var(--radius);
  margin-bottom: 22px;
  box-shadow: 0 8px 24px rgba(2,6,23,0.12);
  opacity: 0;
  transform: translateY(28px);
  transition: all 0.6s ease;
}
.section.visible { opacity: 1; transform: translateY(0); }

/* Typography inside */
h2 { font-size: 1.6rem; color: #0b1220; margin-bottom: 12px; }
p, li { margin-bottom: 10px; color: #374151; font-size: 1.03rem; }

/* List styles */
ul { list-style: none; padding-left: 0; margin-top: 8px; }
ul li { padding: 10px 0; border-bottom: 1px solid #eef2f7; font-weight: 600; color:#111827; }
ul li:last-child { border: none; }

/* BENEFITS CARDS */
.benefits-cards { display:flex; flex-wrap:wrap; justify-content:space-between; gap:16px; margin-top: 12px; }
.benefit-card { flex:1 1 calc(50% - 16px); background:#fff; padding:16px; border-radius:10px; box-shadow:0 6px 18px rgba(0,0,0,0.08); font-weight:700; transition: transform 0.22s ease, box-shadow 0.22s ease; }
.benefit-card:hover { transform: translateY(-6px); box-shadow:0 14px 40px rgba(2,6,23,0.12); }

/* TESTIMONIAL single-card carousel style */
.testimonial-wrap { display:flex; align-items:center; gap:18px; background:#f9fafb; padding:20px; border-radius:12px; box-shadow:0 6px 18px rgba(2,6,23,0.06); max-width:900px; margin: 8px auto; position:relative; overflow:hidden; }
.testimonial-box { flex:1 1 auto; min-height:90px; display:flex; align-items:center; gap:14px; }
.testimonial-avatar { width:68px; height:68px; border-radius:50%; background: linear-gradient(90deg,#fff,#f3f4f6); box-shadow:0 6px 18px rgba(2,6,23,0.06); display:flex; align-items:center; justify-content:center; font-weight:700; color:#0b1220; }
.testimonial-text { font-size:1rem; color:#111827; line-height:1.4; }
.testimonial-author { display:block; margin-top:8px; font-weight:800; color:#0b1220; }

/* BÔNUS */
.bonus { background:#f0f9ff; padding:14px; border-radius:10px; margin:10px 0; font-weight:700; color:#0b1220; box-shadow:0 6px 18px rgba(11,132,255,0.06); }

/* GUARANTEE */
.guarantee { background:#ecfdf5; padding:14px; border-radius:10px; margin:12px 0; font-weight:700; color: var(--green); box-shadow:0 6px 18px rgba(16,185,129,0.06); display:flex; align-items:center; gap:12px; }
.selo { width:64px; height:64px; border-radius:50%; background: linear-gradient(180deg,var(--green), #059669); color:#fff; display:flex; align-items:center; justify-content:center; font-weight:800; box-shadow:0 8px 30px rgba(5,150,105,0.18); }

/* CTA fixed and countdown */
.fixed-cta {
  position: fixed;
  bottom: 20px;
  right: 20px;
  z-index: 9999;
  box-shadow: 0 6px 30px rgba(2,6,23,0.4);
  animation: pulse 2000ms infinite;
  background: var(--highlight);
  color: #fff;
  padding: 12px 16px;
  font-size: 1rem;
  border-radius: 12px;
  font-weight:800;
  text-decoration:none;
}
.fixed-cta:hover { background: var(--highlight-dark); transform: translateY(-4px); }

/* countdown fixed */
#countdown-fixed {
  position: fixed;
  bottom: 86px;
  right: 20px;
  z-index: 9999;
  background: var(--highlight);
  color: #fff;
  padding: 10px 14px;
  border-radius: 12px;
  font-weight: 800;
  text-align: center;
  box-shadow: 0 6px 30px rgba(2,6,23,0.35);
  font-family: var(--ff-sans);
  animation: pulse 1800ms infinite;
}

/* popup overlay */
#popup, #exit-popup {
  display:none;
  position: fixed;
  top:0; left:0; width:100%; height:100%;
  background:rgba(2,6,23,0.7); z-index:10000;
  justify-content:center; align-items:center; padding:20px;
}
.popup-content, .exit-content {
  background: #fff; padding:20px; border-radius:12px; max-width:420px; width:100%; text-align:center; box-shadow:0 12px 48px rgba(2,6,23,0.4);
}
.popup-content h2, .exit-content h2 { margin-bottom:10px; color:#0b1220; }
.popup-close { position:absolute; top:10px; right:12px; cursor:pointer; font-weight:700; font-size:18px; color:#0b1220; }

/* FAQ */
.faq h3 { margin-top:12px; font-size:1.02rem; color:var(--accent); cursor:pointer; }
.faq p { margin-top:6px; padding-left:12px; color:var(--muted); display:none; }

/* extra helpers */
.kicker { display:inline-block; background: rgba(255,255,255,0.06); padding:6px 10px; border-radius:999px; color:#fff; font-weight:700; margin-bottom:12px; }
.small { font-size:0.9rem; color:var(--muted); }
.center { text-align:center; }

/* responsive */
@media(max-width:920px){
  .benefit-card { flex:1 1 100%; }
  .testimonial-wrap { flex-direction:column; align-items:flex-start; }
  #countdown-fixed{ right:12px; left: auto; bottom:100px; }
  .fixed-cta{ right:12px; left:auto; bottom:20px;}
}
@media(max-width:520px){
  .hero h1{ font-size:1.8rem; }
  .hero p{ font-size:0.98rem; }
  .container { padding:18px 12px 120px; }
}

/* animations */
@keyframes pulse { 0% { transform: scale(1); } 50% { transform: scale(1.06);} 100% { transform: scale(1);} }
.fade-in { animation: fadeMe 700ms ease forwards; }
@keyframes fadeMe { from{opacity:0; transform:translateY(12px);} to{opacity:1; transform:translateY(0);} }
</style>
</head>
<body>
<div class="topbar"><small>🔥 Oferta Especial: Redação Nota 1000 em 14 Dias — R$37 (bônus limitados)</small></div>

<div class="container" role="main">
  <!-- HERO -->
  <div class="hero" aria-hidden="false">
    <span class="kicker">Método Testado</span>
    <h1>Redação Nota 1000 em 14 Dias — Método Testado por +500 Estudantes</h1>
    <p>Mesmo que hoje você não saiba por onde começar, este método vai te dar segurança, repertório e técnicas para impressionar os corretores.</p>
    <div class="social-proof">Mais de <strong>500 estudantes</strong> já conquistaram notas 900+ com este guia!</div>
    <div class="center">
      <div class="price">R$ 37,00</div>
      <a href="https://pay.kiwify.com.br/j4SluVK" class="cta" id="cta-main">📘 Quero minha redação nota 1000 agora</a>
    </div>
  </div>

  <!-- PROBLEMA -->
  <div class="section" id="problema">
    <h2>❌ Você provavelmente já...</h2>
    <ul>
      <li>Ficou travado sem saber como começar sua redação;</li>
      <li>Perdeu pontos por não conseguir usar repertório sociocultural;</li>
      <li>Não sabia como construir uma proposta de intervenção completa;</li>
      <li>Se sentiu inseguro na hora da prova e perdeu tempo precioso.</li>
    </ul>
    <p class="small">Sem o método certo, é fácil desperdiçar tempo e arriscar sua aprovação. Mas você pode mudar isso agora — de forma prática e objetiva.</p>
  </div>

  <!-- SOLUÇÃO -->
  <div class="section" id="solucao">
    <h2>✅ A Solução Que Funciona</h2>
    <p>O <strong>Guia Completo para Nota 1000 em 14 Dias</strong> é um plano direto, simples e eficaz que transforma sua redação rapidamente:</p>
    <ul>
      <li>Plano de estudo de 14 dias — intensivo ou flexível;</li>
      <li>Modelos comentados de redações nota 1000, 900 e 700;</li>
      <li>Banco de repertório pronto para qualquer tema;</li>
      <li>Checklists e rubricas para autocorreção rápida;</li>
      <li>Exercícios práticos com gabarito comentado.</li>
    </ul>
    <div class="center"><a href="https://pay.kiwify.com.br/j4SluVK" class="cta" id="cta-solucao">Quero acessar o guia agora</a></div>
  </div>

  <!-- BENEFÍCIOS -->
  <div class="section" id="beneficios">
    <h2>🚀 O que você ganha</h2>
    <div class="benefits-cards" aria-hidden="false">
      <div class="benefit-card">Mais confiança no dia da prova</div>
      <div class="benefit-card">Clareza e organização nas ideias</div>
      <div class="benefit-card">Repertório certeiro para qualquer tema</div>
      <div class="benefit-card">Propostas de intervenção completas</div>
      <div class="benefit-card">Chance real de alcançar 900+ na redação</div>
      <div class="benefit-card">Revisão rápida para recuperar tempo na prova</div>
    </div>
  </div>

  <!-- TESTIMONIAL single-card carousel -->
  <div class="section" id="depoimentos">
    <h2>💬 O que dizem os alunos</h2>
    <div class="testimonial-wrap" aria-live="polite" role="region" aria-label="Depoimento de aluno">
      <div class="testimonial-box">
        <div class="testimonial-avatar" id="avatar">MS</div>
        <div>
          <div class="testimonial-text" id="testimonial-text">"Nunca pensei que conseguiria 900+ na redação! Este guia mudou meu jeito de estudar."</div>
          <div class="testimonial-author" id="testimonial-author">— Ana, SP</div>
        </div>
      </div>
      <!-- small controls -->
      <div style="display:flex; flex-direction:column; gap:8px; margin-left:18px;">
        <button id="prevTest" style="background:transparent; border:1px solid #e6eefc; padding:8px 10px; border-radius:8px; cursor:pointer;">◀</button>
        <button id="nextTest" style="background:var(--accent); color:#fff; border:none; padding:8px 10px; border-radius:8px; cursor:pointer;">▶</button>
      </div>
    </div>
    <p class="small center" style="margin-top:8px;">Depoimentos verossímeis — nomes abreviados para privacidade.</p>
  </div>

  <!-- BONUS -->
  <div class="section" id="bonus">
    <h2>🎁 Bônus Exclusivos (limitados)</h2>
    <div class="bonus">✔️ Checklist de Autoavaliação</div>
    <div class="bonus">✔️ Frases-cura e conectivos prontos</div>
    <div class="bonus">✔️ Modelos de propostas de intervenção completas</div>
    <div class="bonus">✔️ Mini-aulas em vídeo (resumo de técnicas)</div>
    <p class="small">🔥 Apenas os <strong>100 primeiros</strong> alunos garantem todos os bônus — depois, alguns itens deixam de ser ofertados.</p>
  </div>

  <!-- GARANTIA -->
  <div class="section" id="garantia">
    <h2>🔒 Garantia Incondicional</h2>
    <div class="guarantee">
      <div class="selo">7D</div>
      <div>
        <strong>Teste por 7 dias — sem riscos.</strong>
        <p class="small" style="margin-top:6px;">Se não ficar satisfeito, devolvemos 100% do valor. Sem perguntas. Sem burocracia.</p>
      </div>
    </div>
  </div>

  <!-- CTA FOCAL -->
  <div class="section center" style="padding-bottom:36px;">
    <h2>O ENEM está chegando — garanta seu diferencial</h2>
    <p class="small">Cada dia perdido é menos treino e menos segurança. Invista em um método que entrega resultado.</p>
    <div class="price">R$ 37,00</div>
    <a href="https://pay.kiwify.com.br/j4SluVK" class="cta cta-orange" id="cta-final">📘 Sim, quero minha redação nota 1000 agora</a>
  </div>

  <!-- FAQ -->
  <div class="section faq" id="faq">
    <h2>❓ Perguntas Frequentes</h2>
    <h3 data-q="q1">Preciso de conhecimento prévio?</h3>
    <p data-a="q1">Não. O método foi feito para quem começa do zero e também para quem já estudou sem resultado.</p>
    <h3 data-q="q2">Quanto tempo devo dedicar?</h3>
    <p data-a="q2">20–30 minutos por dia já geram evolução consistente; temos plano full-time de 14 dias para quem prefere rotina intensiva.</p>
    <h3 data-q="q3">Funciona para qualquer tema?</h3>
    <p data-a="q3">Sim — as técnicas de estrutura e repertório são aplicáveis em todos os temas do ENEM.</p>
    <h3 data-q="q4">Posso acessar pelo celular?</h3>
    <p data-a="q4">Sim, todo material é responsivo e pensado para leitura e prática em celular.</p>
    <h3 data-q="q5">Existe suporte?</h3>
    <p data-a="q5">Sim — grupo exclusivo de suporte (WhatsApp) para tirar dúvidas rápidas e trocar feedbacks.</p>
  </div>

  <footer style="margin-top:14px; color:#9ca3af; text-align:center;">
    © <span id="year"></span> Todos os direitos reservados — Mentoria Redação Nota 1000
  </footer>
</div>

<!-- FIXED CTA + COUNTDOWN -->
<a href="https://pay.kiwify.com.br/j4SluVK" class="fixed-cta" id="fixedCta">📘 Quero agora — R$37</a>
<div id="countdown-fixed">🔥 Oferta termina em: <span id="time-fixed">00:00:00</span></div>

<!-- POPUPS -->
<div id="popup" role="dialog" aria-modal="true">
  <div class="popup-content">
    <div class="popup-close" onclick="closePopup()">×</div>
    <h2>⚠️ Oferta Limitada</h2>
    <p>Os bônus exclusivos estão acabando. Garanta agora antes que expirem.</p>
    <a href="https://pay.kiwify.com.br/j4SluVK" class="cta cta-orange">📘 Quero garantir agora</a>
  </div>
</div>

<div id="exit-popup" role="dialog" aria-modal="true">
  <div class="exit-content">
    <div class="popup-close" onclick="closeExit()">×</div>
    <h2>❌ Espere — antes de sair!</h2>
    <p>Se sair agora, você pode perder os bônus exclusivos. Aproveite a oferta por R$37.</p>
    <a href="https://pay.kiwify.com.br/j4SluVK" class="cta cta-orange">📘 Quero garantir agora</a>
  </div>
</div>

<script>
/* ===== Basic UI wiring ===== */
document.getElementById('year').textContent = new Date().getFullYear();

/* reveal sections on scroll */
function revealOnScroll(){
  document.querySelectorAll('.section').forEach(s=>{
    const rect = s.getBoundingClientRect();
    if(rect.top < window.innerHeight - 60) s.classList.add('visible');
  });
}
window.addEventListener('scroll', revealOnScroll);
window.addEventListener('load', function(){
  revealOnScroll();
  initTestimonials();
});

/* ===== Countdown: central (time to end of day) and fixed sync ===== */
function startCountdowns(){
  // target: today 23:59:59 local
  const now = new Date();
  const end = new Date(now.getFullYear(), now.getMonth(), now.getDate(), 23,59,59,999);
  function update(){
    const diff = end - new Date();
    const el = document.getElementById('time-fixed');
    if(diff <= 0){ el.textContent = "00:00:00"; return; }
    const h = String(Math.floor(diff/(1000*60*60))).padStart(2,'0');
    const m = String(Math.floor((diff%(1000*60*60))/(1000*60))).padStart(2,'0');
    const s = String(Math.floor((diff%(1000*60))/1000)).padStart(2,'0');
    el.textContent = `${h}:${m}:${s}`;
  }
  update();
  setInterval(update,1000);
}
startCountdowns();

/* ===== Popups ===== */
function openPopup(){ document.getElementById('popup').style.display='flex'; }
function closePopup(){ document.getElementById('popup').style.display='none'; }
function closeExit(){ document.getElementById('exit-popup').style.display='none'; }

/* open a popup after a delay to increase conversions */
setTimeout(openPopup, 22000); // 22s after load

/* exit intent popup */
let exitShown=false;
document.addEventListener('mouseout', function(e){
  if(e.clientY < 5 && !exitShown){
    document.getElementById('exit-popup').style.display='flex';
    exitShown=true;
  }
});

/* ===== Testimonials carousel (single quad) ===== */
const testimonials = [
  { text: "Nunca pensei que conseguiria 900+ na redação! Este guia mudou meu jeito de estudar.", name: "Ana, SP", avatar: "AS" },
  { text: "Em 2 semanas consegui organizar meu repertório e aumentar minha nota de 680 para 880.", name: "Lucas, MG", avatar: "LM" },
  { text: "Cheguei no dia da prova com segurança. O método é direto e simples de aplicar.", name: "Carla, PR", avatar: "CM" },
  { text: "O bônus de checklist salvou minha vida! Recomendo muito.", name: "Ana L., RJ", avatar: "AL" }
];
let tIndex = 0;
function showTestimonial(i){
  const t = testimonials[i];
  const txt = document.getElementById('testimonial-text');
  const auth = document.getElementById('testimonial-author');
  const av = document.getElementById('avatar');
  // fade out/in
  txt.style.opacity = 0; auth.style.opacity = 0; av.style.opacity = 0;
  setTimeout(()=>{
    txt.textContent = `"${t.text}"`;
    auth.textContent = `— ${t.name}`;
    av.textContent = t.avatar;
    txt.style.opacity = 1; auth.style.opacity = 1; av.style.opacity = 1;
  },250);
}
function initTestimonials(){
  showTestimonial(0);
  setInterval(()=>{
    tIndex = (tIndex + 1) % testimonials.length;
    showTestimonial(tIndex);
  }, 5000); // rota a cada 5s
  // buttons
  document.getElementById('prevTest').addEventListener('click', ()=>{
    tIndex = (tIndex - 1 + testimonials.length) % testimonials.length;
    showTestimonial(tIndex);
  });
  document.getElementById('nextTest').addEventListener('click', ()=>{
    tIndex = (tIndex + 1) % testimonials.length;
    showTestimonial(tIndex);
  });
}

/* ===== FAQ toggles ===== */
document.querySelectorAll('.faq h3').forEach(h=>{
  h.addEventListener('click', function(){
    const targetKey = this.getAttribute('data-q');
    const p = document.querySelector(`p[data-a="${targetKey}"]`);
    if(!p) return;
    p.style.display = (p.style.display === 'block') ? 'none' : 'block';
    this.style.color = (p.style.display === 'block') ? 'var(--highlight)' : 'var(--accent)';
  });
});

/* ===== Accessibility focus for CTAs (small enhancement) ===== */
document.querySelectorAll('.cta').forEach(c=>{
  c.addEventListener('focus', ()=> c.style.boxShadow = '0 10px 30px rgba(2,6,23,0.25)');
  c.addEventListener('blur', ()=> c.style.boxShadow = '');
});

/* ===== Small conversion helper: copy direct link to clipboard on click (visual) ===== */
document.getElementById('cta-main').addEventListener('click', copyLink);
document.getElementById('cta-solucao').addEventListener('click', copyLink);
document.getElementById('cta-final').addEventListener('click', copyLink);
document.getElementById('fixedCta').addEventListener('click', copyLink);
function copyLink(e){
  // attempt to copy link (improves tracking when DM used)
  try {
    navigator.clipboard.writeText('https://pay.kiwify.com.br/j4SluVK');
  } catch (err) { /* ignore */ }
  // allow normal navigation
}

/* ===== ensure all sections are visible quickly for better first paint (UX) ===== */
setTimeout(()=>{ document.querySelectorAll('.section').forEach(s=>s.classList.add('visible')); }, 400);
</script>
</body>
</html>
