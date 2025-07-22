<!DOCTYPE html>
<ead>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<titlhtml lang="pt-BR">
<he>Sarah Andrade - Devocionais e Estudos Bíblicos</title>
<style>
  /* Reset básico */
  * {
    margin: 0; padding: 0; box-sizing: border-box;
  }

  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.6;
    color: #333;
    background: #fff0f5;
  }

  a {
    color: #c71585;
    text-decoration: none;
  }
  a:hover {
    text-decoration: underline;
  }

  /* Cabeçalho fixo */
  header {
    position: fixed;
    top: 0; left: 0; right: 0;
    background-color: #ff69b4;
    color: white;
    height: 60px;
    display: flex;
    align-items: center;
    padding: 0 20px;
    font-weight: 700;
    font-size: 1.4rem;
    z-index: 999;
    box-shadow: 0 2px 5px rgba(0,0,0,0.2);
  }

  /* Container principal */
  .container {
    max-width: 1000px;
    margin: 80px auto 40px; /* compensar header fixo */
    padding: 0 20px;
  }

  /* Topo com foto e descrição */
  .top-section {
    display: flex;
    align-items: center;
    gap: 25px;
    margin-bottom: 40px;
    flex-wrap: wrap;
  }

  .top-section img {
    width: 160px;
    height: 160px;
    border-radius: 50%;
    object-fit: cover;
    border: 4px solid #ff69b4;
  }

  .top-section .descricao {
    flex: 1;
    min-width: 250px;
  }

  .top-section .descricao h1 {
    font-size: 2rem;
    margin-bottom: 15px;
    color: #c71585;
  }

  .top-section .descricao p {
    font-size: 1.1rem;
    line-height: 1.5;
  }

  /* Seções */
  section {
    margin-bottom: 50px;
  }

  section h2 {
    color: #c71585;
    font-size: 1.8rem;
    margin-bottom: 20px;
    border-bottom: 2px solid #ff69b4;
    padding-bottom: 8px;
  }

  /* Cards de devocionais e estudos */
  .cards {
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(280px,1fr));
    gap: 20px;
  }

  .card {
    background: white;
    border-radius: 10px;
    box-shadow: 0 3px 8px rgba(0,0,0,0.1);
    overflow: hidden;
    display: flex;
    flex-direction: column;
    transition: transform 0.3s ease;
  }

  .card:hover {
    transform: translateY(-5px);
  }

  .card iframe {
    width: 100%;
    height: 160px;
    border: none;
  }

  .card-content {
    padding: 15px 20px;
    flex: 1;
    display: flex;
    flex-direction: column;
  }

  .card-content h3 {
    color: #c71585;
    margin-bottom: 10px;
    font-size: 1.2rem;
  }

  .card-content p {
    flex-grow: 1;
    font-size: 0.95rem;
    color: #555;
    margin-bottom: 15px;
  }

  .card-content a.btn-link {
    align-self: flex-start;
    background: #ff69b4;
    color: white;
    padding: 8px 15px;
    border-radius: 25px;
    font-weight: 700;
    font-size: 0.9rem;
    transition: background-color 0.3s ease;
  }

  .card-content a.btn-link:hover {
    background: #c71585;
  }

  /* Footer */
  footer {
    text-align: center;
    padding: 15px;
    font-size: 0.9rem;
    color: #666;
    border-top: 1px solid #ff69b4;
    margin-top: 40px;
  }

  /* Responsividade */
  @media(max-width:600px){
    .top-section {
      flex-direction: column;
      text-align: center;
    }
    .top-section .descricao {
      min-width: auto;
    }
    .top-section img {
      margin-bottom: 15px;
    }
  }
</style>
</head>
<body>

<header>
  Devocionais, Orações e Salmo do Dia - Sarah Andrade
</header>

<div class="container">

  <div class="top-section">
    <img src="imagens/sarah.jpg" alt="Foto da Sarah Andrade" />
    <div class="descricao">
      <h1>Olá!,bem vindo ao meu site Eu sou a Sarah Andrade</h1>
      <p>Tenho 21 anos e sou apaixonada por craiar orações e estudos bíblicos que ajudam você a se conectar com Deus. No meu canal do YouTube, compartilho conteúdos inspiradores baseados na Palavra de Deus para fortalecer sua fé e transformar sua vida.</p>
      <p>Seja bem-vindo(a) ao meu espaço online onde você pode acompanhar meus vídeos, acessar devocionais diários e estudar a Bíblia comigo,sou desenvolvedora de front-end, e quero usar meu talento para glorificar a Deus,criando sites edificantes.</p>
    </div>
  </div>

  <section id="devocionais">
    <h2>Devocionais Baseados em Vídeos</h2>
    <div class="cards">

      <article class="card">
        <iframe src="https://www.youtube.com/embed/3eQS6YGclC0" allowfullscreen title="Para quem pecou de novo e não sabe o que fazer"></iframe>
        <div class="card-content">
          <h3>Para quem pecou de novo e não sabe o que fazer</h3>
          <p>Encontre esperança e orientação para se reerguer após uma queda e recomeçar na fé.</p>
          <a href="https://youtu.be/3eQS6YGclC0" target="_blank" class="btn-link">Assistir no YouTube</a>
        </div>
      </article>

      <article class="card">
      <iframe src="https://www.youtube.com/embed/vSy6rB4xN4g" allowfullscreen title="Agradeça a Deus por uma bênção"></iframe>
        <div class="card-content">
          <h3>Agradeça a Deus por uma bênção</h3>
          <p>Um vídeo especial para você expressar gratidão pelas bênçãos recebidas.</p>
          <a href="https://youtu.be/vSy6rB4xN4g" target="_blank" class="btn-link">Assistir no YouTube</a>
        </div>
      </article>

      <article class="card">
        <iframe src="https://www.youtube.com/embed/mERx7PT5T9o" allowfullscreen title="Para quem sente mágoa"></iframe>
        <div class="card-content">
          <h3>Para quem sente mágoa</h3>
          <p>Devocional e palavra de cura para quem está lidando com mágoas e precisa de libertação.</p>
          <a href="https://youtu.be/mERx7PT5T9o" target="_blank" class="btn-link">Assistir no YouTube</a>
        </div>
      </article>

      <article class="card">
        <iframe src="https://www.youtube.com/embed/0QE0jtDb_js" allowfullscreen title="Para quem vai jejuar"></iframe>
        <div class="card-content">
          <h3>Para quem vai jejuar</h3>
          <p>Um devocional especial para fortalecer sua fé durante o jejum.</p>
          <a href="https://youtu.be/0QE0jtDb_js" target="_blank" class="btn-link">Assistir no YouTube</a>
        </div>
      </article>

      <article class="card">
        <iframe src="https://www.youtube.com/embed/yEFTriPZzPg" allowfullscreen title="Como vencer o vazio"></iframe>
        <div class="card-content">
          <h3>Como vencer o vazio</h3>
          <p>Palavra de fé e encorajamento para superar o vazio espiritual.</p>
          <a href="https://youtu.be/yEFTriPZzPg" target="_blank" class="btn-link">Assistir no YouTube</a>
        </div>
        <!-- Estudo 2 - Receber o Espírito Santo -->
    <article style="background: white; border: 2px solid #ff69b4; border-radius: 12px; padding: 20px;">
     <div style="margin-bottom: 30px;">
  <h3 style="color: #c71585;">Como Receber o Espírito Santo?</h3>
  <p>Aprenda os passos bíblicos para receber o Espírito Santo e viver uma vida cheia da presença de Deus. Um estudo essencial para quem busca intimidade com o Pai.</p>

  <a href="https://youtu.be/mCQmd7YmHdw?si=CNptr92f5KHGR__M" target="_blank" style="display: block; max-width: 100%; text-align: center; margin-top: 10px; text-decoration: none;">
    <img src="https://img.youtube.com/vi/mCQmd7YmHdw/hqdefault.jpg" alt="Como Receber o Espírito Santo" style="width: 100%; max-width: 500px; border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">
    <div style="margin-top: 10px; background-color: #ff69b4; color: white; padding: 10px 15px; border-radius: 8px; display: inline-block;">
      ▶ Assistir Estudo
    </div>
    <div style="margin-bottom: 30px;">
  <h3 style="<div style="margin-bottom: 30px;">
  <h3 style="color: #c71585;">Receba Cura Divina</h3>
  <p>Este vídeo é para quem está buscando uma cura física, emocional ou espiritual. Creia no poder de Deus para restaurar completamente sua vida.</p>

  <a href="https://youtu.be/43zUrBMcVuc?si=XoQz9xJDVdRfoKdz" target="_blank" style="display: block; max-width: 100%; text-align: center; margin-top: 10px; text-decoration: none;">
    <img src="https://img.youtube.com/vi/43zUrBMcVuc/hqdefault.jpg" alt="Receba Cura Divina" style="width: 100%; max-width: 500px; border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">
    <div style="margin-top: 10px; background-color: #ff69b4; color: white; padding: 10px 15px; border-radius: 8px; display: inline-block;">
      🙏 Assistir Palavra de Cura
    </div>
  </a>
</div>
<div style="margin-bottom: 30px;">
  <h3 style="color: #c71585;">Fundo Musical para Oração</h3>
  <p>Ouça uma música suave e inspiradora para acompanhar seus momentos de oração, meditação ou devocional com Deus.</p>

  <a href="https://youtu.be/aygLv7QcRlo?si=_FOVgcQfxXrx_ryv" target="_blank" style="display: block; max-width: 100%; text-align: center; margin-top: 10px; text-decoration: none;">
    <img src="https://img.youtube.com/vi/aygLv7QcRlo/hqdefault.jpg" alt="Fundo Musical para Oração" style="width: 100%; max-width: 500px; border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">
    <div style="margin-top: 10px; background-color: #ff69b4; color: white; padding: 10px 15px; border-radius: 8px; display: inline-block;">
      🎵 Ouvir Música de Fundo
    </div>
  </a>
</div>

  <h3 style="color: #c71585;">Receba Cura Divina</h3>
  <p>Este vídeo é para quem está buscando uma cura física, emocional ou espiritual. Creia no poder de Deus para restaurar completamente sua vida.</p>
  <a href="https://youtu.be/43zUrBMcVuc?si=XoQz9xJDVdRfoKdz" target="_blank" style="display: block; max-width: 100%; text-align: center; margin-top: 10px; text-decoration: none;">
    <img src="https://img.youtube.com/vi/43zUrBMcVuc/hqdefault.jpg" alt="Receba Cura Divina" style="width: 100%; max-width: 500px; border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">
    <div style="margin-top: 10px; background-color: #ff69b4; color: white; padding: 10px 15px; border-radius: 8px; display: inline-block;">
      🙏 Assistir Palavra de Cura
    </div>
  </a>
</div>
    
  </section>
</a>
  <section id="estudos-biblicos">
    <h2>Estudos Bíblicos</h2>
    <p>Em breve, você poderá acessar aqui estudos detalhados para aprofundar seu conhecimento da Palavra de Deus. Fique ligado!</p>
  </section>
<article id="estudo-proverbios" style="padding: 30px; background-color: #fffafc;">
  <h2 style="color: #c71585;">Estudo Bíblico: Sabedoria para o dia a dia (Provérbios 1:7)</h2>
  <iframe src="https://www.youtube.com/embed/vy5tYjl35xs" width="100%" height="280" style="margin-top: 15px;" allowfullscreen></iframe>
  <div style="margin-top: 20px; line-height: 1.7;">
    <p><strong>“O temor do Senhor é o princípio do conhecimento, mas os insensatos desprezam a sabedoria e a disciplina.”</strong> – Provérbios 1:7</p>
    <p><strong>1. O temor do Senhor é a base da sabedoria:</strong> Temer a Deus é reverenciá-lo e viver segundo Sua vontade.</p>
    <p><strong>2. Sabedoria é diferente de inteligência:</strong> É saber usar o conhecimento com discernimento e amor.</p>
    <p><strong>3. A disciplina é uma bênção:</strong> Aceitar a correção de Deus nos amadurece espiritualmente.</p>
    <p><strong>4. A sabedoria está disponível a todos:</strong> Basta buscar com coração sincero.</p>
    <p><strong>5. O resultado da sabedoria:</strong> Paz, vida longa e direção segura de Deus.</p>
    <h3 style="color: #c71585; margin-top: 25px;">Oração:</h3>
    <p>Senhor, eu te agradeço porque a Tua Palavra é lâmpada para os meus pés... <br> (continue a oração acima)</p>
  </div>
</div>
<footer>
  &copy; 2025 Sarah Andrade - Todos os direitos reservados - 
  <a href="mailto:sarahgabrielamaciel76@gmail.com" aria-label="Enviar e-mail para Sarah Andrade">sarahgabrielamaciel76@gmail.com</a> - 
  <a href="https://www.youtube.com/@SarahGabriela024" target="_blank" rel="noopener" aria-label="Acessar canal no YouTube de Sarah Andrade">Canal no YouTube</a>
</footer>

</body>
</html>

