<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>PHT Security System - SaaS Threat Intelligence</title>
  <style>
    :root {
      --bg-color: #0d1117;
      --text-main: #c9d1d9;
      --accent-yellow: #FFFF00;
      --accent-blue: #58a6ff;
      --accent-red: #ff7b72;
      --accent-green: #3fb950;
      --border-color: #30363d;
      --panel-bg: #161b22;
    }
    
    body {
      background-color: var(--bg-color);
      color: var(--text-main);
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
      line-height: 1.7;
      margin: 0;
      padding: 0;
      overflow-x: hidden;
    }

    .container {
      max-width: 900px;
      margin: 0 auto;
      padding: 30px 20px;
    }

    h1, h2, h3 {
      color: #ffffff;
      border-bottom: 1px solid var(--border-color);
      padding-bottom: 10px;
      margin-top: 40px;
    }

    a {
      color: var(--accent-blue);
      text-decoration: none;
      transition: color 0.2s;
    }

    a:hover {
      color: var(--accent-yellow);
    }

    .center {
      text-align: center;
    }

    .badges {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 10px;
      margin: 20px 0;
    }

    .divider {
      width: 100%;
      margin: 40px 0;
      opacity: 0.8;
    }

    blockquote {
      background: rgba(255, 255, 0, 0.05);
      border-left: 4px solid var(--accent-yellow);
      padding: 15px 20px;
      margin: 20px 0;
      border-radius: 0 8px 8px 0;
      font-style: italic;
    }

    .disclaimer {
      border-left-color: #f0883e;
      background: rgba(240, 136, 62, 0.1);
      font-style: normal;
    }

    .disclaimer strong {
      color: #f0883e;
    }

    pre {
      background-color: var(--panel-bg);
      border: 1px solid var(--border-color);
      border-radius: 8px;
      padding: 20px;
      overflow-x: auto;
      box-shadow: inset 0 0 10px rgba(0,0,0,0.5);
    }

    code {
      font-family: "Fira Code", Consolas, Monaco, monospace;
      color: var(--accent-blue);
      font-size: 0.9em;
    }

    .product-card {
      background-color: var(--panel-bg);
      border: 1px solid var(--border-color);
      border-radius: 8px;
      padding: 25px;
      margin: 30px 0;
      transition: transform 0.2s, border-color 0.2s;
    }

    .product-card:hover {
      transform: translateY(-3px);
    }

    .card-apt {
      border-left: 4px solid var(--accent-green);
    }
    .card-apt:hover {
      border-color: var(--accent-green);
    }
    .card-apt h3 {
      color: var(--accent-green);
    }

    .card-phantom {
      border-left: 4px solid var(--accent-red);
    }
    .card-phantom:hover {
      border-color: var(--accent-red);
    }
    .card-phantom h3 {
      color: var(--accent-red);
    }

    .product-card h3 {
      border-bottom: none;
      margin-top: 0;
      font-size: 1.5em;
    }

    .tag {
      display: inline-block;
      padding: 2px 8px;
      border-radius: 12px;
      font-size: 0.8em;
      font-weight: bold;
      margin-right: 5px;
      margin-bottom: 15px;
    }

    .tag-civil { background: rgba(63, 185, 80, 0.2); color: var(--accent-green); border: 1px solid var(--accent-green); }
    .tag-gov { background: rgba(255, 123, 114, 0.2); color: var(--accent-red); border: 1px solid var(--accent-red); }
    .tag-consult { background: rgba(255, 255, 0, 0.2); color: var(--accent-yellow); border: 1px solid var(--accent-yellow); }

    .tech-stack {
      margin-top: 15px;
      padding-top: 15px;
      border-top: 1px solid var(--border-color);
    }
  </style>
</head>
<body>

  <div class="container">
    
    <!-- HEADER ANIMADO -->
    <div class="center">
      <img src="https://capsule-render.vercel.app/api?type=waving&color=0d1117&height=220&section=header&text=PHT%20Security%20System&fontSize=60&fontColor=FFFF00&animation=fadeIn&fontAlignY=35&stroke=FFFF00&strokeWidth=2" width="100%" alt="PHT Banner"/>
      
      <h2>🛡️ SaaS Corporate Threat Intelligence & Cognitive Architecture</h2>

      <div class="badges">
        <a href="#"><img src="https://img.shields.io/badge/Model-B2B_SaaS_Enterprise-success?style=for-the-badge&logo=cloud&logoColor=white" alt="SaaS"/></a>
        <a href="#"><img src="https://img.shields.io/badge/Architecture-Neo4j_Graph_AI-blue?style=for-the-badge&logo=neo4j&logoColor=white" alt="Neo4j"/></a>
        <a href="#"><img src="https://img.shields.io/badge/Defesa-eBPF_%7C_MITRE-blueviolet?style=for-the-badge&logo=linux&logoColor=white" alt="Defesa"/></a>
      </div>

      <br>
      
      <div class="badges">
        <img src="https://komarev.com/ghpvc/?username=hackimghost&style=for-the-badge&color=FFFF00&labelColor=0d1117&label=NETWORK+NODES" alt="Views"/>
        <img src="https://img.shields.io/github/followers/hackimghost?style=for-the-badge&color=FFFF00&labelColor=0d1117&label=OPERATORS" alt="Followers"/>
      </div>

      <!-- TYPING ANIMATION -->
      <a href="https://git.io/typing-svg">
        <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=FFFF00&center=true&vCenter=true&width=800&lines=Forjando+a+verdadeira+blindagem+corporativa+🛡️;APT+Chat:+Analista+Virtual+Autônomo+(Civil)+🧠;Phantom:+Orquestração+Forense+(B2G/LEO)+🏴‍☠️;Integração+eBPF,+Proxy+Reverso+e+MITRE+⚙️;Malha+Neural+e+Memória+em+Grafos+(Neo4j)+🕸️" alt="Typing SVG"/>
      </a>
    </div>

    <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" class="divider" alt="divider">

    <blockquote class="disclaimer">
      ⚠️ <strong>LEGAL & COMPLIANCE DISCLAIMER</strong> ⚠️<br>
      A <strong>PHT Security System</strong> atua sob rígidos protocolos de conformidade, dividindo suas operações em duas frentes distintas. O <strong>APT Chat</strong> opera com guardrails estritos para o mercado civil e corporativo. A plataforma <strong>Phantom</strong> é de uso restrito governamental, jurídico e policial, operando sob escopo contratual específico para perícia profunda e interceptação legal. Não fornecemos ferramentas ofensivas não licenciadas.
    </blockquote>

    <h2>👤 A Evolução: Arquitetura de Defesa e Operações</h2>

    <pre><code>name        : PHT Core Architect
role        : [ Security Operations Architect, AI Dev, SecOps Engineer ]
focus       : [ SaaS Platforms, eBPF Defenses, Graph Intelligence (Neo4j) ]
stack       : Reverse Proxy, MITRE ATT&CK Mapping, Fine-tuned LLMs
status      : Orquestrando o Caos 🏴‍☠️ -> 🏢</code></pre>

    <p>
      A cibersegurança de vitrine não sustenta ataques reais. Minha jornada evoluiu da exploração tática para a <strong>Arquitetura de Operações e Sistemas Ofensivos/Defensivos</strong>. A PHT Security System constrói servidores de defesa impenetráveis, utilizando tecnologias como <strong>eBPF para observabilidade de kernel, proxies reversos robustos e alocação dinâmica de CVEs baseada nas matrizes do MITRE ATT&CK</strong>.
    </p>

    <blockquote>
      "Nossa infraestrutura rejeita tabelas relacionais planas em favor de <strong>memória em grafos e malhas neurais (Obsidian/Neo4j)</strong>. Nossos modelos de IA possuem um prompt mestre afiado integrado ao código-fonte, compreendendo o contexto integral de um ataque e respondendo com precisão cirúrgica."
    </blockquote>

    <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" class="divider" alt="divider">

    <h2>⚙️ Produtos SaaS & Ecossistema de Inteligência (PHT Engine)</h2>
    <p>A arquitetura PHT é dividida em dois motores principais, desenhados para atender demandas diametralmente opostas de conformidade e profundidade investigativa.</p>

    <!-- PRODUTO 1: APT CHAT -->
    <div class="product-card card-apt">
      <h3>🧠 APT Chat: Analista Cibernético Autônomo</h3>
      <span class="tag tag-civil">Público Civil & B2B</span>
      <span class="tag tag-civil">Guardrails Ativos</span>
      
      <p><strong>Visão Geral:</strong> O APT Chat é a plataforma SaaS de defesa corporativa definitiva. Atuando como a interface tática da PHT Security System, ele funde as capacidades de um LLM especializado com ferramentas ativas de segurança, entregando um analista virtual autônomo diretamente no seu navegador.</p>
      
      <p><strong>Funcionalidades Core:</strong></p>
      <ul>
        <li><strong>Roteamento Tático & OSINT:</strong> Compreende comandos em linguagem natural e orquestra execuções (scans, integração com Shodan/SerpAPI) sem intervenção manual.</li>
        <li><strong>Conformidade e Guardrails:</strong> Desenvolvido com rígidas restrições de segurança ética. O APT Chat bloqueia requisições ofensivas não autorizadas, focando exclusivamente na defesa, auditoria de código, Blue Teaming e resposta a incidentes.</li>
        <li><strong>Engenharia Reversa Automatizada:</strong> Validação estruturada de binários e assinaturas YARA em ambientes sandbox isolados.</li>
      </ul>

      <div class="tech-stack">
        <img src="https://skillicons.dev/icons?i=python,ts,neo4j,docker" alt="Stack APT Chat"/>
      </div>
    </div>

    <!-- PRODUTO 2: PHANTOM -->
    <div class="product-card card-phantom">
      <h3>💀 Phantom: Motor de Orquestração Forense</h3>
      <span class="tag tag-gov">B2G / Law Enforcement</span>
      <span class="tag tag-gov">Sem Guardrails Padrão</span>
      <span class="tag tag-consult">Estritamente Sob Consulta</span>
      
      <p><strong>Visão Geral:</strong> O núcleo obscuro da arquitetura PHT. O Phantom reflete o poder algorítmico do APT Chat, porém <strong>desprovido dos guardrails civis</strong>. Projetado exclusivamente para forças da lei, agências governamentais e peritos judiciais, ele atua em ambientes onde a restrição de dados impede a resolução de crimes críticos.</p>
      
      <p><strong>Operação Forjada por Escopo:</strong></p>
      <ul>
        <li><strong>Malha Investigativa Agressiva:</strong> Realiza correlação profunda de metadados para investigações avançadas, rastreio de anomalias financeiras e reconstrução cronológica de incidentes complexos.</li>
        <li><strong>Quebra de Sigilo & Perícia Judicial:</strong> Ferramental preparado para atuar ativamente em processos de lawful intercept, extração de dados criptografados e forense profunda (mobile/kernel) mediante mandado judicial ou escopo contratual explícito.</li>
        <li><strong>Auditoria em Grafos:</strong> Utiliza o motor Neo4j em sua capacidade máxima para expor redes complexas de corrupção ou ameaças persistentes avançadas de Estado (APTs).</li>
      </ul>

      <div class="tech-stack">
        <img src="https://skillicons.dev/icons?i=rust,c,go,linux" alt="Stack Phantom"/>
      </div>
    </div>

    <h2>🕸️ Topologia de Conhecimento: Cypher & MITRE</h2>
    <p>A espinha dorsal que conecta as decisões do APT Chat à malha do Phantom é estruturada em grafos:</p>
    <pre><code>// Detecção Cognitiva PHT e Alocação Dinâmica de CVE
MATCH (t:Asset {ip: '10.0.x.x', type: 'Reverse_Proxy'})
MERGE (v:Vulnerability {id: 'CVE-2026-XXXX', severity: 'CRITICAL'})
MERGE (m:Mitre_Tactic {id: 'TA0001', name: 'Initial Access'})
MERGE (t)-[:EXPOSED_TO]->(v)-[:MAPPED_TO]->(m)
RETURN t, v, m</code></pre>

    <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" class="divider" alt="divider">

    <h2>📊 Telemetria Operacional & Commits</h2>
    <div class="center">
      <p><em>"Segurança corporativa não é sobre a ausência de vulnerabilidades, mas sobre a capacidade de gerenciar o risco sob ataque total."</em></p>
      <img src="https://github-readme-stats.vercel.app/api?username=hackimghost&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=FFFF00&icon_color=FFFF00" alt="GitHub Stats" style="margin: 5px;"/>
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=hackimghost&theme=dark&hide_border=true&background=0d1117&ring=FFFF00&fire=FFFF00&currStreakLabel=FFFF00" alt="Streak Stats" style="margin: 5px;"/>
    </div>

    <div class="center" style="margin-top: 50px;">
      <!-- FOOTER WAVE -->
      <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:FFFF00,100:0d1117&height=120&section=footer" alt="Footer Wave" width="100%"/>
    </div>

  </div>
</body>
</html>

