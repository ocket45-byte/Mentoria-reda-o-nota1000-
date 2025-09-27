
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
}
* { box-sizing: border-box; margin:0; padding:0; }
body { font-family: var(--ff-sans); background: linear-gradient(180deg, #0f172a, #1e293b); color: #111827; line-height: 1.6; overflow-x:hidden; }
.container { max-width: 1000px; margin: auto; padding: 32px 16px; }
h1,h2,h3 { margin-bottom: 12px; }
h1 { font-size: 2.4rem; color: #fff; animation: pulse-title 2s infinite; text-align:center; }
@keyframes pulse-title { 0%,100%{transform:scale(1)}50%{transform:scale(1.02)} }
h2 { font-size: 1.8rem; color: #2c3e50; }
p { margin-bottom: 14px; color:#374151; }
.hero { text-align: center; padding: 48px 24px; background: linear-gradient(120deg, var(--accent), var(--accent-dark)); border-radius: var(--radius); margin-bottom: 40px; }
.hero p { font-size: 1.2rem; color: rgba(255,255,255,0.9); margin-bottom: 16px; }
.hero .social-proof { font-size: 1rem; color: #d1d5db; margin-bottom: 24px; }
.section { background: var(--card); padding: 32px; border-radius: var(--radius); margin-bottom: 28px; box-shadow: 0 8px 24px rgba(0,0,0,0.08); opacity: 0; transform: translateY(30px); transition: all 0.6s ease; }
.section.visible { opacity:1; transform: translateY(0);}
ul { list-style: none; padding: 0; }
ul li { padding: 10px 0; border-bottom: 1px solid #e5e7eb; font-weight: 500; }
ul li:last-child { border: none; }
.cta { display: inline-block; text-decoration: none; background: var(--accent); color: white; padding: 16px 22px; border-radius: var(--radius); font-weight: 700; text-align: center; transition: 0.2s ease; margin-top: 16px; font-size: 1.1rem; }
.cta:hover { background: var(--accent-dark); transform: translateY(-2px); }
.cta-orange { background: var(--highlight); }
.cta-orange:hover { background: var(--highlight-dark); transform: translateY(-2px); }
.price { font-size: 2rem; font-weight: bold; margin: 16px 0; color: var(--green); }
.bonus { background:#f0f9ff; padding:16px; border-radius:10px; margin:12px 0; font-weight: 500; }
.guarantee { background:#ecfdf5; padding:16px; border-radius:10px; margin:20px 0; font-weight:500; color: var(--green);}
footer { text-align:center; font-size:0.85rem; color:#9ca3af; margin-top:40px; padding:20px; }
.benefits-cards { display:flex; flex-wrap:wrap; justify-content:space-between; gap:16px; margin-top:16px; }
.benefit-card { flex:1 1 calc(50% - 16px); background:#fefefe; padding:16px; border-radius:10px; box-shadow:0 6px 18px rgba(0,0,0,0.08); font-weight:500; transition: transform 0.2s ease; }
.benefit-card:hover { transform: translateY(-4px); }
.testimonials { display:flex; flex-wrap:wrap; gap:16px; margin-top:16px; }
.testimonial { flex:1 1 calc(33% - 16px); background:#f9fafb; padding:16px; border-radius:10px; box-shadow:0 4px 14px rgba(0,0,0,0.05); font-size:0.95rem; color:#374151; transition: transform 0.3s ease, opacity 0.6s ease; opacity:0; transform: translateY(20px);}
.testimonial.visible { opacity:1; transform: translateY(0);}
.testimonial strong { display:block; margin-top:8px; color:#111827; font-size:0.9rem }
/* Responsividade */
@media(max-width:768px){ 
  h1 { font-size:2rem; }
  h2 { font-size:1.5rem; }
  .benefits-cards { flex-direction:column; } 
  .benefit-card { flex:1 1 100%; } 
  .testimonials { flex-direction:column; }
  .testimonial { flex:1 1 100%; }
  .hero { padding:32px 16px;}
}
/* Botão fixo */
.fixed-cta {
  position: fixed;
  bottom: 20px;
  right: 20px;
  z-index: 9999;
  box-shadow: 0 4px 16px rgba(0,0,0,0.3);
  animation: pulse 2s infinite;
  background: var(--highlight);
  padding: 14px 18px;
  font-size: 1rem;
}
.fixed-cta:hover { background: var(--highlight-dark); transform: translateY(-2px); }
@keyframes pulse {0% { transform: scale(1); }50% { transform: scale(1.05); }100% { transform: scale(1); }}
/* Contador fixo */
#countdown {
  position: fixed;
  bottom: 80px;
  right: 20px;
  z-index: 9999;
  background: var(--highlight);
  color: #fff;
  padding: 10px 14px;
  border-radius: 14px;
  font-weight: 700;
  text-align: center;
  box-shadow: 0 4px 16px rgba(0,0,0,0.3);
  font-family: var(--ff-sans);
  animation: pulse 1.5s infinite;
}
/* POPUPS */
#popup, #exit-popup {
  display:none;
  position: fixed;
  top:0; left:0; width:100%; height:100%; background:rgba(0,0,0,0.7); z-index:10000;
  justify-content:center; align-items:center;
}
#popup .content, #exit-popup .content {
  background:#fff; padding:24px; border-radius:12px; max-width:400px; text-align:center; position:relative;
}
#popup .content h2, #exit-popup .content h2 { color:#111827; margin-bottom:12px; }
#popup .content p, #exit-popup .content p { margin-bottom:16px; }
#popup .close, #exit-popup .close { position:absolute; top:8px; right:12px; cursor:pointer; font-weight:bold; font-size:18px; }
</style>
</head>
<body>
<div class="container">

<!-- HERO -->
<div class="hero">
<h1>Redação Nota 1000 em 14 Dias — Método Testado por +500 Estudantes</h1>
<p>Mesmo que hoje você não saiba por onde começar, este método vai te dar segurança, repertório e técnicas para impressionar os corretores.</p>
<div class="social-proof">Mais de 500 estudantes já conquistaram notas 900+ com este guia!</div>
<div class="price">R$ 37,00</div>
<a href="https://pay.kiwify.com.br/j4SluVK" class="cta">📘 Quero minha redação nota 1000 agora</a>
</div>

<!-- PROBLEMA -->
<div class="section">
<h2>❌ Você provavelmente já...</h2>
<ul>
<li>Ficou travado sem saber como começar sua redação</li>
<li>Perdeu pontos por não conseguir usar repertório sociocultural</li>
<li>Não sabia como construir uma proposta de intervenção completa</li>
<li>Se sentiu inseguro na hora da prova e perdeu tempo precioso</li>
</ul>
<p>Sem o método certo, é fácil desperdiçar tempo e arriscar sua aprovação. Mas você pode mudar isso agora!</p>
</div>

<!-- SOLUÇÃO -->
<div class="section">
<h2>✅ A Solução Que Funciona</h2>
<p>O <strong>Guia Completo para Nota 1000 em 14 Dias</strong> é um plano direto, simples e eficaz que transforma sua redação rapidamente:</p>
<ul>
<li>Plano de estudo de 14 dias — intensivo ou flexível</li>
<li>Modelos comentados de redações nota 1000, 800 e 600</li>
<li>Banco de repertório pronto para qualquer tema</li>
<li>Checklists e rubricas para autocorreção rápida</li>
<li>Exercícios práticos com gabarito comentado</li>
</ul>
</div>

<!-- BENEFÍCIOS -->
<div class="section">
<h2>🚀 O que você ganha</h2>
<div class="benefits-cards">
<div class="benefit-card">Mais confiança no dia da prova</div>
<div class="benefit-card">Clareza e organização nas ideias</div>
<div class="benefit-card">Repertório certeiro para qualquer tema</div>
<div class="benefit-card">Propostas de intervenção completas</div>
<div class="benefit-card">Chance real de alcançar 900+ na redação</div>
</div>
</div>

<!-- DEPOIMENTOS -->
<div class="section">
<h2>💬 O que dizem os alunos</h2>
<div class="testimonials">
<div class="testimonial">"Nunca pensei que conseguiria 900+ na redação! Este guia mudou meu jeito de estudar." <strong>— Ana, SP</strong></div>
<div class="testimonial">"Em 2 semanas consegui organizar meu repertório e aumentar minha nota de 680 para 880." <strong>— Lucas, MG</strong></div>
<div class="testimonial">"Cheguei no dia da prova com segurança. O método é direto e simples de aplicar." <strong>— Carla, PR</strong></div>
</div>
</div>

<!-- BONUS -->
<div class="section">
<h2>🎁 Bônus Exclusivos</h2>
<div class="bonus">✔️ Checklist de Autoavaliação</div>
<div class="bonus">✔️ Frases-cura e conectivos prontos</div>
<div class="bonus">✔️ Modelos de propostas de intervenção completas</div>
<p>🔥 Apenas os 100 primeiros alunos garantem estes bônus exclusivos!</p>
</div>

<!-- GARANTIA -->
<div class="section guarantee">
<h2>🔒 Garantia Incondicional</h2>
<p>Você tem 7 dias para testar o material. Se não gostar, devolvemos 100% do valor. Sem perguntas, sem risco.</p>
</div>

<!-- CTA FINAL -->
<div class="section" style="text-align:center;">
<h2>O ENEM está chegando...</h2>
<p>Cada dia perdido é uma chance a menos de treinar. Garanta seu guia agora e transforme sua redação em diferencial!</p>
<div class="price">R$ 37,00</div>
<a href="https://pay.kiwify.com.br/j4SluVK" class="cta cta-orange">📘 Sim, quero minha redação nota 1000 agora</a>
</div>

<footer>
© <span id="year"></span> Todos os direitos reservados.
</footer>
</div>

<!-- BOTÃO FIXO -->
<a href="https://pay.kiwify.com.br/j4SluVK" class="cta fixed-cta">📘 Quero minha redação nota 1000 agora</a>

<!-- CONTADOR FIXO -->
<div id="countdown">🔥 Oferta termina em: <span id="time">00:00:00</span></div>

<!-- POPUPS -->
<div id="popup"><div class="content">
<span class="close" onclick="document.getElementById('popup').style.display='none'">&times;</span>
<h2>⚠️ Oferta Limitada!</h2>
<p>Os bônus exclusivos podem acabar a qualquer momento!</p>
<a href="https://pay.kiwify.com.br/j4SluVK" class="cta cta-orange">📘 Quero garantir agora</a>
</div></div>

<div id="exit-popup"><div class="content">
<span class="close" onclick="document.getElementById('exit-popup').style.display='none'">&times;</span>
<h2>❌ Espere!</h2>
<p>Antes de sair, saiba que os bônus exclusivos podem acabar hoje!</p>
<a href="https://pay.kiwify.com.br/j4SluVK" class="cta cta-orange">📘 Quero garantir agora</a>
</div></div>

<script>
// Atualiza ano no footer
document.getElementById('year').textContent = new Date().getFullYear();

// Contador regressivo até o final do dia
function startCountdown() {
  const countdownDate = new Date();
  countdownDate.setHours(23,59,59,999);
  const countdownEl = document.getElementById('time');
  function update() {
    const now = new Date().getTime();
    const distance = countdownDate - now;
    if(distance < 0){ countdownEl.textContent = "00:00:00"; return; }
    const h = String(Math.floor((distance/(1000*60*60)))).padStart(2,'0');
    const m = String(Math.floor((distance%(1000*60*60))/(1000*60))).padStart(2,'0');
    const s = String(Math.floor((distance%(1000*60))/1000)).padStart(2,'0');
    countdownEl.textContent = `${h}:${m}:${s}`;
  }
  update();
  setInterval(update,1000);
}
startCountdown();

// Mostra popup de saída
let exitPopupShown = false;
document.addEventListener('mouseout', function(e){
  if(e.clientY < 10 && !exitPopupShown){
    document.getElementById('exit-popup').style.display='flex';
    exitPopupShown = true;
  }
});

// Mostrar seções e depoimentos animados
window.addEventListener('scroll', function(){
  document.querySelectorAll('.section').forEach(s=>{
    if(s.getBoundingClientRect().top < window.innerHeight - 50) s.classList.add('visible');
  });
  document.querySelectorAll('.testimonial').forEach(t=>{
    if(t.getBoundingClientRect().top < window.innerHeight - 50) t.classList.add('visible');
  });
});
</script>
</body>
</html>
