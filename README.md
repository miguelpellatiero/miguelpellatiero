<style>
/* Estilos Gerais */
body {
  font-family: 'Arial', sans-serif;
  color: #ffffff;
  background-color: #000000;
  margin: 0;
  padding: 20px;
}

/* Animação Avançada: Pulse no Título */
@keyframes pulse {
  0% { transform: scale(1); text-shadow: 0 0 5px #ffffff; }
  50% { transform: scale(1.05); text-shadow: 0 0 15px #ffcc00; }
  100% { transform: scale(1); text-shadow: 0 0 5px #ffffff; }
}
.greeting {
  animation: pulse 2s infinite ease-in-out;
  font-size: 2em;
  margin-bottom: 10px;
}

/* Animação Avançada: Fade e Crescimento com Oscilação para Seções */
@keyframes fadeAndGrow {
  0% { opacity: 0; transform: scale(0.9) translateY(20px); }
  50% { opacity: 0.7; transform: scale(1.1) translateY(-10px); }
  100% { opacity: 1; transform: scale(1) translateY(0); }
}
.section-title {
  animation: fadeAndGrow 1.5s ease-in-out;
  font-size: 1.5em;
  margin-top: 20px;
  border-bottom: 1px solid #333333;
  padding-bottom: 5px;
}

/* Animação Avançada: Salto com Cores para Badges de Habilidades */
@keyframes bounceColor {
  0% { transform: translateY(0) rotate(0); background-color: #1e90ff; }
  50% { transform: translateY(-10px) rotate(5deg); background-color: #ff4500; }
  100% { transform: translateY(0) rotate(0); background-color: #1e90ff; }
}
.skill-badge {
  display: inline-block;
  padding: 5px 10px;
  margin: 5px;
  border-radius: 5px;
  color: #ffffff;
  animation: bounceColor 3s infinite alternate;
  cursor: pointer;
}

/* Animação Avançada: Rotação 3D em Hover para Projetos */
.project-item {
  margin-bottom: 15px;
  transition: transform 0.3s ease;
}
.project-item:hover {
  transform: rotateY(10deg) scale(1.05);
  box-shadow: 0 4px 8px rgba(255, 255, 255, 0.2);
}

/* Animação Avançada: Movimento e Rotação para Ícones de Conexão */
@keyframes moveRotate {
  0% { transform: translateX(0) rotate(0); }
  50% { transform: translateX(10px) rotate(180deg); }
  100% { transform: translateX(0) rotate(360deg); }
}
.connect-icon {
  display: inline-block;
  margin: 5px;
  animation: moveRotate 4s infinite linear;
}

/* Animação Avançada: Texto Deslizante com Escala para Objetivos */
@keyframes slideGrow {
  0% { transform: translateX(100%) scale(0.8); color: #ffffff; }
  50% { transform: translateX(0) scale(1.2); color: #ffcc00; }
  100% { transform: translateX(0) scale(1); color: #ffffff; }
}
.objective-text {
  animation: slideGrow 2s ease-in-out;
}

/* Animação Avançada: Fade com Display para Hobbies */
@keyframes fadeInOut {
  0% { opacity: 0; display: none; }
  50% { opacity: 0.5; display: block; }
  100% { opacity: 1; display: block; }
}
.hobby-badge {
  display: inline-block;
  padding: 5px 10px;
  margin: 5px;
  border-radius: 5px;
  background-color: #00bfff;
  color: #000000;
  animation: fadeInOut 2s forwards;
}
</style>

<div class="greeting">Olá, sou Miguel Pellatiero! 👋</div>

🚀 Desenvolvedor Full Stack em Formação  
🎓 Estudante de Desenvolvimento de Sistemas na Etec Prof Ilza Nascimento Pintus

<div class="section-title">🖥️ Stack Tecnológica & Habilidades</div>
<span class="skill-badge" style="background-color: #3776ab;">Python</span>
<span class="skill-badge" style="background-color: #f7df1e; color: #000;">JavaScript</span>
<span class="skill-badge" style="background-color: #e44d26;">HTML5</span>
<span class="skill-badge" style="background-color: #1572b6;">CSS3</span>
<span class="skill-badge" style="background-color: #f05032;">Git</span>
<span class="skill-badge" style="background-color: #ff69b4;">Web Design</span>

<div class="section-title">🌟 Projetos em Destaque</div>
<div class="project-item">🍕 PegPizza Cardápio  
Sistema moderno para cardápio digital - Solução completa para restaurantes com interface responsiva</div>

<div class="project-item">🃏 Cardápio Ludos  
Plataforma interativa para estabelecimentos - UX/UI otimizada para experiência do usuário</div>

<div class="project-item">💰 Controle Financeiro  
Aplicação de gestão financeira pessoal - Ferramentas para análise e controle de gastos</div>

<div class="section-title">📊 miguelpellatiero's GitHub Stats</div>
⭐ Total Stars Earned: 4  
💻 Total Commits (last year): 40  
🔄 Total PRs: 0  
❗ Total Issues: 1  
🤝 Contributed to (last year): 0  

Most Used Languages:  
- HTML 31.31%  
- PHP 8.25%  
- JavaScript 26.89%  
- Python 7.77%  
- CSS 23.58%  
- Batchfile 0.21%

<div class="section-title">🌐 Conecte-se Comigo</div>
<span class="connect-icon">📸</span> [INSTAGRAM](https://instagram.com/yourusername)  
<span class="connect-icon">🐙</span> [GITHUB](https://github.com/miguelpellatiero)  
<span class="connect-icon">💼</span> [PORTFOLIO](https://yourportfolio.com)

<div class="section-title">🎸 Hobbies & Interesses</div>
<span class="hobby-badge">🥋 JIU JITSU</span>
<span class="hobby-badge">📷 FOTOGRAFIA</span>
<span class="hobby-badge">🏃 CORRIDA</span>
<span class="hobby-badge">📖 LEITURA</span>
<span class="hobby-badge">🏋️ ACADEMIA</span>
<span class="hobby-badge">🛼 SKATE</span>

<div class="section-title">💡 Visão & Objetivos</div>
<span class="objective-text">"Sempre em busca de novos desafios e aprendizados na área de tecnologia!"</span>  

🔵 Foco Atual: Desenvolvimento Full Stack, UX/UI Design, Python, JavaScript  

🌈 Interesses em: Startups, Inovação, Tecnologia Web, Soluções Digitais  

☀️ Aspirações: Contribuir para projetos inovadores nas áreas de Google, Microsoft, Apple, Amazon e ecossistema de startups  

⚡ Pronto para revolucionar o mundo digital, um código de cada vez.

<div class="section-title">🚀 Acesse Meu Portfólio</div>
[PORTFÓLIO MIGUEL](https://yourportfolio.com)
