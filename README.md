<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Gerenciador de Resultados</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <img src="alsco-logo.png" alt="ALSCO UNIFORMES">
    <div class="info">
      <strong>Gerenciador de Resultados</strong><br>
      <span id="dataHora"></span> - Bahia
    </div>
  </header>

  <nav>
    <h3 id="menuAtendimentos">Atendimentos <span id="arrowAtendimentos">▶</span></h3>
    <ul id="submenuAtendimentos">
      <li><a href="#" id="controleAtendimentos">Controle de Atendimentos</a></li>
      <li><a href="#">Clientes</a></li>
      <li><a href="#">Pedidos de compra</a></li>
    </ul>

    <h3 id="menuNotas">Notas <span id="arrowNotas">▶</span></h3>
    <ul id="submenuNotas">
      <li><a href="#">Entrada</a></li>
      <li><a href="#">Saída</a></li>
    </ul>

    <h3>Helpdesk</h3>
    <h3><a href="#" class="PESQUISA">Dashboard</a></h3>
  </nav>

<main>
  <h1 id="tituloPrincipal">Bem-vindo ao Gerenciador de Resultados</h1>
  <p id="textoPrincipal">Selecione uma opção no menu lateral para começar.</p>

  <!-- Área para o gráfico -->
  <canvas id="graficoPizza" width="250" height="250" style="display:none;"></canvas>
</main>

  <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
  <script src="script.js"></script>
</body>
</html>
