<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Salicá Cred</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f9fbff;
      color: #333;
    }
    header {
      background-color: #e0f0ff;
      padding: 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    header .logo {
      font-size: 1.5rem;
      font-weight: bold;
      color: #0077cc;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #0077cc;
      font-weight: bold;
    }
    .hero {
      background-color: #cde9ff;
      text-align: center;
      padding: 60px 20px;
    }
    .hero h1 {
      font-size: 2.5rem;
    }
    .hero p {
      font-size: 1.2rem;
      margin: 20px 0;
    }
    .hero a {
      background-color: #0077cc;
      color: white;
      padding: 12px 25px;
      text-decoration: none;
      border-radius: 5px;
    }
    .section {
      padding: 40px 20px;
      text-align: center;
    }
    .section h2 {
      font-size: 2rem;
      margin-bottom: 20px;
    }
    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
      margin-top: 30px;
    }
    .card {
      background: white;
      border-radius: 10px;
      padding: 20px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }
    .cta {
      background-color: #0077cc;
      color: white;
      padding: 40px 20px;
    }
    .cta a {
      display: inline-block;
      background-color: white;
      color: #0077cc;
      padding: 12px 25px;
      text-decoration: none;
      font-weight: bold;
      border-radius: 5px;
      margin-top: 20px;
    }
    footer {
      background-color: #e0f0ff;
      text-align: center;
      padding: 20px;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">Salicá Cred</div>
    <nav>
      <a href="#sobre">Sobre</a>
      <a href="#servicos">Serviços</a>
      <a href="#contato">Contato</a>
    </nav>
    <a href="https://wa.me/551129236298">Fale com a gente</a>
  </header>

  <section class="hero">
    <h1>Crédito rápido, fácil e com o melhor atendimento!</h1>
    <p>Simule seu empréstimo agora mesmo com segurança e transparência.</p>
    <a href="https://wa.me/551129236298">Simular agora</a>
  </section>

  <section id="sobre" class="section">
    <h2>Quem somos</h2>
    <p>A Salicá Cred é especializada em crédito pessoal, consignado e soluções financeiras. Atendimento humanizado, sem burocracia e com as melhores taxas do mercado.</p>
  </section>

  <section id="servicos" class="section">
    <h2>O que oferecemos</h2>
    <div class="cards">
      <div class="card">
        <h3>Empréstimo Consignado</h3>
        <p>Para aposentados, pensionistas e servidores públicos.</p>
      </div>
      <div class="card">
        <h3>Crédito Pessoal</h3>
        <p>Dinheiro rápido e sem complicação.</p>
      </div>
      <div class="card">
        <h3>Refinanciamento</h3>
        <p>Reorganize suas finanças com melhores condições.</p>
      </div>
      <div class="card">
        <h3>Portabilidade</h3>
        <p>Traga seu contrato para a Salicá Cred e reduza suas parcelas.</p>
      </div>
    </div>
  </section>

  <section class="cta">
    <h2>Pronto para começar?</h2>
    <p>Fale com a nossa equipe e descubra como podemos ajudar você.</p>
    <a href="https://wa.me/551129236298">Atendimento via WhatsApp</a>
  </section>

  <footer id="contato">
    <p>Salicá Cred - Crédito com confiança</p>
    <p>WhatsApp: (11) 2923-6298 | Instagram: <a href="https://instagram.com/salicacred" target="_blank">@salicacred</a></p>
    <p>© 2025 Salicá Cred. Todos os direitos reservados.</p>
  </footer>
</body>
</html>
