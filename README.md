# Wolf_Scan<!DOCTYPE html><html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Wolf Scan</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Montserrat', sans-serif;
      background-color: #000;
      color: #fff;
    }
    header {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 1rem 2rem;
      background-color: #111;
      border-bottom: 1px solid #444;
    }
    header img {
      height: 60px;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      margin: 0 1rem;
      font-weight: bold;
    }
    .hero {
      text-align: center;
      padding: 4rem 2rem;
    }
    .hero img {
      width: 150px;
    }
    .hero h1 {
      font-size: 3rem;
      margin-top: 1rem;
    }
    .section {
      padding: 2rem;
      background-color: #111;
      border-top: 1px solid #444;
    }
    .section h2 {
      border-bottom: 2px solid #666;
      padding-bottom: 0.5rem;
    }
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1rem;
    }
    .project {
      background-color: #222;
      padding: 1rem;
      border-radius: 10px;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background-color: #111;
      font-size: 0.9rem;
      border-top: 1px solid #444;
    }
  </style>
</head>
<body>
  <header>
    <img src="logo.png" alt="Wolf Scan Logo" />
    <nav>
      <a href="#inicio">Início</a>
      <a href="#projetos">Projetos</a>
      <a href="#contato">Contato</a>
    </nav>
  </header>
