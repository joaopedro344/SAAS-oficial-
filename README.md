<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Trampa - Conectando Freelancers e Empresas</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1 class="logo">Trampa</h1>
    <nav>
      <a href="#home">Início</a>
      <a href="#login">Entrar</a>
    </nav>
  </header>

  <section id="home" class="hero">
    <h2>Conectando freelancers e empresas com inteligência</h2>
    <p>Encontre talentos ou oportunidades de forma rápida, segura e eficiente.</p>
    <div class="btn-group">
      <button onclick="alert('Sou Empresa')">Sou Empresa</button>
      <button onclick="alert('Sou Freelancer')">Sou Freelancer</button>
    </div>
  </section>

  <section id="login" class="login">
    <h2>Login / Cadastro</h2>
    <form>
      <label for="tipo">Sou:</label>
      <select id="tipo">
        <option value="empresa">Empresa</option>
        <option value="freelancer">Freelancer</option>
      </select>

      <input type="email" placeholder="E-mail" required />
      <input type="password" placeholder="Senha" required />
      <button type="submit">Entrar</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Trampa. Todos os direitos reservados.</p>
  </footer>

  <script src="app.js"></script>
</body>
</html>
