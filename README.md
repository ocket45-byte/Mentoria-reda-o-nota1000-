
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Redação Nota 1000 em 14 Dias</title>
<style>
body { font-family: Arial, sans-serif; margin:0; padding:0; background:#f7f7f7; color:#333; }
header { background:#4CAF50; color:white; text-align:center; padding:50px 20px; }
header h1 { font-size:2rem; margin:0 0 10px; }
header p { font-size:1.2rem; margin:0 0 20px; }
.btn { background:#FF5722; color:white; padding:15px 25px; text-decoration:none; font-weight:bold; border-radius:8px; display:inline-block; margin:10px 0; transition:0.3s; }
.btn:hover { background:#e64a19; }
.section { padding:40px 20px; max-width:900px; margin:20px auto; background:white; border-radius:12px; box-shadow:0 4px 15px rgba(0,0,0,0.1);}
h2 { color:#333; font-size:1.5rem; margin-bottom:15px; }
ul { list-style-type:none; padding:0; }
ul li { margin-bottom:10px; font-size:1.1rem; }
.testimonial { background:#e8f5e9; padding:20px; border-radius:8px; margin-bottom:15px; display:flex; align-items:center; }
.testimonial img { width:50px; height:50px; border-radius:50%; margin-right:15px; }
.testimonial p { margin:0; }
.cta-section { text-align:center; padding:50px 20px; background:#f1f1f1; border-radius:12px; position:relative; }
.countdown { color:#FF5722; font-weight:bold; font-size:2rem; margin:20px 0; }
.bonus { background:#fff3e0; padding:20px; border-radius:8px; margin-top:20px; }
.float-btn { position:fixed; bottom:20px; right:20px; z-index:999; }
@media(max-width:600px){ header h1{font-size:1.5rem;} header p{font-size:1rem;} }
</style>
</head>
<body>

<!-- Botão flutuante -->
<a href="#comprar" class="btn float-btn">Comprar Agora</a>

<!-- Hero Section -->
<header>
<h1>Redação Nota 1000 em 14 Dias</h1>
<p>Aprenda a escrever redações que impressionam qualquer corretor, mesmo começando do zero!</p>
<a href="#comprar" class="btn">Quero minha Redação Nota 1000</a>
</header>

<!-- Problema e Solução -->
<section class="section">
<h2>Cansado de perder pontos na redação?</h2>
<ul>
<li>Não sabe como organizar suas ideias rapidamente?</li>
<li>Fica nervoso com temas desconhecidos?</li>
<li>Já decorou conteúdos, mas não consegue aplicar na prova?</li>
</ul>
<p>Com nosso método, você vai aprender a estruturar e escrever redações nota 1000 em apenas 14 dias, de forma prática e direta!</p>
</section>

<!-- Benefícios -->
<section class="section">
<h2>O que você vai aprender:</h2>
<ul>
<li>Planejamento de redação em 5 minutos.</li>
<li>Técnicas para ganhar pontos extras em qualquer tema.</li>
<li>Repertório atualizado que impressiona corretores.</li>
<li>Dicas de estrutura para não perder pontos.</li>
<li>Confiança total na hora da prova.</li>
</ul>
</section>

<!-- Prova Social -->
<section class="section">
<h2>Depoimentos de alunos</h2>
<div class="testimonial">
<img src="https://via.placeholder.com/50" alt="Aluno 1">
<p>“Seguindo o método do Italo, consegui minha primeira redação nota 1000!” – Maria S.</p>
</div>
<div class="testimonial">
<img src="https://via.placeholder.com/50" alt="Aluno 2">
<p>“Simplesmente incrível! Aprendi em 2 semanas o que demoraria meses sozinho.” – João P.</p>
</div>
</section>

<!-- Bônus -->
<section class="section bonus">
<h2>Bônus Exclusivos:</h2>
<ul>
<li>Checklist completo para revisão rápida da redação.</li>
<li>Modelo de planejamento diário para 14 dias.</li>
<li>Mini guia de repertório atualizado.</li>
</ul>
</section>

<!-- Garantia -->
<section class="section">
<h2>Garantia Incondicional</h2>
<p>Se você não ficar satisfeito nos primeiros 7 dias, devolvemos 100% do seu dinheiro. Sem perguntas. Sem riscos.</p>
</section>

<!-- Urgência com Contador no Meio -->
<section class="section cta-section">
<h2>Oferta por tempo limitado!</h2>
<p class="countdown" id="countdown">00:00:00</p>
<a href="#comprar" class="btn">Quero minha Redação Nota 1000</a>
</section>

<!-- CTA Final -->
<section class="section cta-section" id="comprar">
<h2>Não perca tempo, garanta já sua vaga!</h2>
<a href="https://pay.kiwify.com.br/j4SluVK" class="btn">Comprar Agora</a>
</section>

<script>
// Contador regressivo simples: 48h a partir do carregamento
let countDownDate = new Date().getTime() + 48*60*60*1000;

let x = setInterval(function() {
  let now = new Date().getTime();
  let distance = countDownDate - now;
  let hours = Math.floor((distance % (1000 * 60 * 60 * 24))/(1000*60*60));
  let minutes = Math.floor((distance % (1000 * 60 * 60))/(1000*60));
  let seconds = Math.floor((distance % (1000 * 60))/1000);
  document.getElementById("countdown").innerHTML = `${hours.toString().padStart(2,'0')}:${minutes.toString().padStart(2,'0')}:${seconds.toString().padStart(2,'0')}`;
  if(distance < 0){ clearInterval(x); document.getElementById("countdown").innerHTML = "OFERTA ENCERRADA"; }
},1000);
</script>

</body>
</html>
