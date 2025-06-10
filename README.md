<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Comply.IA - Governança e Compliance em Inteligência Artificial</title>
<style>
  /* Reset básico */
  * {
    margin: 0; padding: 0; box-sizing: border-box;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  }
  body {
    background: #f5f7fa;
    color: #222;
    line-height: 1.6;
  }
  header {
    background: #123c70;
    color: white;
    padding: 1rem 2rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  header h1 {
    font-weight: 700;
    font-size: 1.5rem;
    letter-spacing: 1px;
  }
  nav a {
    color: white;
    margin-left: 1.5rem;
    text-decoration: none;
    font-weight: 600;
    transition: color 0.3s;
  }
  nav a:hover {
    color: #74b3ce;
  }
  main {
    max-width: 900px;
    margin: 2rem auto;
    padding: 0 1rem;
  }
  section {
    margin-bottom: 3rem;
  }
  h2 {
    color: #123c70;
    margin-bottom: 1rem;
  }
  /* Home - Hero */
  .hero {
    background: #74b3ce;
    color: white;
    padding: 3rem 2rem;
    border-radius: 8px;
    text-align: center;
  }
  .hero h2 {
    font-size: 2rem;
    margin-bottom: 1rem;
  }
  .hero p {
    font-size: 1.1rem;
    max-width: 600px;
    margin: 0 auto 2rem auto;
  }
  .btn-primary {
    background: #123c70;
    color: white;
    padding: 0.8rem 2rem;
    border: none;
    border-radius: 4px;
    font-weight: 700;
    cursor: pointer;
    text-transform: uppercase;
    letter-spacing: 1px;
    transition: background 0.3s;
  }
  .btn-primary:hover {
    background: #0d2a4b;
  }
  /* Sobre */
  .sobre p {
    font-size: 1rem;
    color: #333;
  }
  /* Serviços */
  .servicos ul {
    list-style: inside disc;
    color: #333;
  }
  /* Contato */
  form {
    display: flex;
    flex-direction: column;
    max-width: 450px;
  }
  label {
    margin-bottom: 0.4rem;
    font-weight: 600;
    color: #123c70;
  }
  input, textarea {
    padding: 0.6rem;
    margin-bottom: 1rem;
    border: 1px solid #ccc;
    border-radius: 4px;
    font-size: 1rem;
    resize: vertical;
  }
  button[type="submit"] {
    width: 120px;
    align-self: flex-start;
    background: #123c70;
    color: white;
    border: none;
    padding: 0.8rem 1.5rem;
    font-weight: 700;
    border-radius: 4px;
    cursor: pointer;
    transition: background 0.3s;
  }
  button[type="submit"]:hover {
    background: #0d2a4b;
  }
  /* Footer */
  footer {
    background: #123c70;
    color: white;
    text-align: center;
    padding: 1rem;
    font-size: 0.9rem;
  }
  /* Responsivo */
  @media (max-width: 600px) {
    nav a {
      margin-left: 0.8rem;
      font-size: 0.9rem;
    }
    .hero h2 {
      font-size: 1.5rem;
    }
    main {
      margin: 1rem;
    }
  }
</style>
</head>
<body>

<header>
  <h1>Comply.IA</h1>
  <nav>
    <a href="#home">Home</a>
    <a href="#sobre">Sobre</a>
    <a href="#servicos">Serviços</a>
    <a href="#contato">Contato</a>
  </nav>
</header>

<main>
  <section id="home" class="hero">
    <h2>Governança e Compliance em Inteligência Artificial</h2>
    <p>Garantindo que sua empresa use IA de forma ética, transparente e segura, alinhada às normas e boas práticas.</p>
    <button class="btn-primary" onclick="document.getElementById('contato').scrollIntoView({behavior: 'smooth'})">Fale Conosco</button>
  </section>

  <section id="sobre" class="sobre">
    <h2>Sobre a Comply.IA</h2>
    <p>Somos uma startup focada em ajudar empresas a implementar governança e compliance em inteligência artificial. Nossa plataforma e consultoria combinam tecnologia e expertise jurídica para minimizar riscos, garantir transparência e promover o uso ético da IA no seu negócio.</p>
  </section>

  <section id="servicos" class="servicos">
    <h2>Nossos Serviços</h2>
    <ul>
      <li>Monitoramento e auditoria de modelos de IA</li>
      <li>Consultoria para políticas internas de compliance</li>
      <li>Treinamentos e capacitação em governança de IA</li>
      <li>Relatórios personalizados e dashboards intuitivos</li>
      <li>Suporte e atualização contínua frente às regulamentações</li>
    </ul>
  </section>

  <section id="contato">
    <h2>Contato</h2>
    <form onsubmit="alert('Mensagem enviada! Obrigado pelo contato.'); this.reset(); return false;">
      <label for="nome">Nome</label>
      <input type="text" id="nome" name="nome" required />

      <label for="email">E-mail</label>
      <input type="email" id="email" name="email" required />

      <label for="mensagem">Mensagem</label>
      <textarea id="mensagem" name="mensagem" rows="4" required></textarea>

      <button type="submit">Enviar</button>
    </form>
  </section>
</main>

<footer>
  <p>© 2025 Comply.IA - Todos os direitos reservados.</p>
</footer>

</body>
</html>
