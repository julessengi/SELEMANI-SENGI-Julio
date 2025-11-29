layout: default
title: "SELEMANI — Portfolio"
theme: jekyll-theme-minimal




---

<!-- IMAGE HEADER PLACEHOLDER -->
<div style="width:100%;height:220px;background:#f3f3f3;border:2px dashed #ccc;border-radius:12px;display:flex;align-items:center;justify-content:center;margin-bottom:24px;color:#666;font-family:Inter, sans-serif;">
<img src =julio5.png > </div>








<!doctype html><html lang="fr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>SELEMANI — Portfolio & README</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
  <style>
    :root{--bg:#071021;--card:#071727;--muted:#9aa4b2;--accent:#06b6d4;--glass: rgba(255,255,255,0.03);--glass2: rgba(255,255,255,0.02)}
    *{box-sizing:border-box}
    body{margin:0;font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,'Helvetica Neue',Arial;background:linear-gradient(180deg,var(--bg) 0%, #071827 80%);color:#e6eef6}
    .wrap{max-width:1100px;margin:36px auto;padding:24px}
    .card{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));border-radius:14px;padding:26px;box-shadow:0 12px 40px rgba(2,6,23,0.6);border:1px solid var(--glass2)}
    header{display:flex;gap:18px;align-items:center;flex-wrap:wrap}
    .avatar{width:96px;height:96px;border-radius:12px;background:linear-gradient(135deg,var(--accent),#7c3aed);display:flex;align-items:center;justify-content:center;font-weight:800;font-size:36px;color:#071827}
    h1{margin:0;font-size:28px}
    p.lead{color:var(--muted);margin-top:6px}
    .badges{display:flex;gap:8px;margin-top:12px;flex-wrap:wrap}
    .badge{display:inline-flex;align-items:center;gap:8px;background:transparent;padding:6px 10px;border-radius:999px;color:var(--muted);font-size:13px;border:1px solid var(--glass2)}
    nav{display:flex;gap:10px;margin-top:14px}
    a.btn{display:inline-block;padding:10px 14px;border-radius:10px;background:transparent;border:1px solid rgba(255,255,255,0.04);color:var(--accent);text-decoration:none;font-weight:700}

    .grid{display:grid;grid-template-columns:1fr 340px;gap:20px;margin-top:22px}
    main{min-width:0}
    h2{margin:0 0 10px 0;font-size:18px}
    .section{margin-bottom:18px}
    ul{margin:8px 0 0 18px;color:var(--muted)}
    pre{background:#061021;padding:12px;border-radius:8px;overflow:auto;color:#cfeff6}

    .projects{display:flex;flex-direction:column;gap:12px}
    .project{background:linear-gradient(180deg, rgba(255,255,255,0.01), transparent);padding:12px;border-radius:10px;border:1px solid var(--glass2)}
    .meta{color:var(--muted);font-size:13px}

    aside{padding-left:12px}
    .card-cta{background:linear-gradient(90deg,#06202a, #071227);padding:14px;border-radius:10px;border:1px solid var(--glass2);margin-top:12px}

    footer{margin-top:22px;color:var(--muted);font-size:13px;text-align:center}

    @media (max-width:980px){.grid{grid-template-columns:1fr}.aside{order:2}}
  </style>
</head>
<body>
  <div class="wrap">
    <div class="card">
      <header>
        <div class="avatar">S</div>
        <div style="flex:1;min-width:0">
          <h1>SELEMANI — Développeur · Architecte · Chef de projet</h1>
          <p class="lead">Conception web, pipelines GitHub → CPanel, intégration IA, projets culturels & environnementaux. Portfolio professionnel et README stylé pour GitHub.</p>

          <div class="badges" aria-hidden>
            <span class="badge"><img src="https://img.shields.io/badge/PHP-8.x-blue?logo=php&logoColor=white" alt="PHP"> PHP · MySQL</span>
            <span class="badge"><img src="https://img.shields.io/badge/GitHub-Actions-black?logo=githubactions&logoColor=white" alt="CI"> CI/CD</span>
            <span class="badge"><img src="https://img.shields.io/badge/CPanel-orange?logo=cpanel&logoColor=white" alt="CPanel"> Hébergement</span>
            <span class="badge"><img src="https://img.shields.io/badge/Impact-Culture-green" alt="Impact"> Culture & Environnement</span>
          </div>

          <nav>
            <a class="btn" href="#projects">Projets</a>
            <a class="btn" href="#skills">Compétences</a>
            <a class="btn" href="#contact">Contact</a>
          </nav>
        </div>
      </header>

      <div class="grid">
        <main>
          <section class="section" id="projects">
            <h2>Projets clés</h2>
            <div class="projects">
              <div class="project">
                <strong>CCC Le Zoo — Site officiel</strong>
                <div class="meta">Stack: PHP · MySQL · GitHub Actions · CPanel</div>
                <p style="color:var(--muted);margin-top:8px">Conception complète du site institutionnel <a href="https://www.ccclezoo.cd" style="color:var(--accent)">www.ccclezoo.cd</a>. Modules: Articles, Projets, Événements, Partenaires. Pipeline automatique pour déploiement.</p>
              </div>

              <div class="project">
                <strong>Projet Environnemental — Plateforme de présentation</strong>
                <div class="meta">Objectif: convaincre partenaires et faciliter financement</div>
                <p style="color:var(--muted);margin-top:8px">Documentation technique, landing page partenaire, dossiers PDF et structure prête à l'emploi.</p>
              </div>

              <div class="project">
                <strong>Architecture Réseau & Cybersécurité</strong>
                <div class="meta">Topologie multi-sites, monitoring et sécurisation</div>
                <p style="color:var(--muted);margin-top:8px">Plan technique pour 3 sites provinciaux, recommandations de sécurité et scripts d'automatisation.</p>
              </div>
            </div>
          </section>

          <section class="section" id="articles">
            <h2>Module Articles & Contenu</h2>
            <p style="color:var(--muted)">Structure recommandée: catégories (Actualités, Projets, Événements), flux RSS, interface CRUD sécurisée (upload image + validation), SEO multilingue FR/EN.</p>
            <pre>&lt;!-- Routes exemple --&gt;
GET /articles   → ArticlesController@index
GET /article/{id} → ArticlesController@show
POST /articles   → ArticlesController@store (auth required)</pre>
          </section>

          <section class="section" id="roadmap">
            <h2>Roadmap (synthétique)</h2>
            <ul>
              <li>Phase 1 — Fondation technique (hébergement, DB, structure)</li>
              <li>Phase 2 — Front-end & identité visuelle</li>
              <li>Phase 3 — Modules (Articles, Projets, Partenaires)</li>
              <li>Phase 4 — CI/CD & Automatisation</li>
              <li>Phase 5 — Tests, SEO, accessibilité et lancement</li>
            </ul>
          </section>

          <section class="section" id="usage">
            <h2>Utilisation</h2>
            <p style="color:var(--muted)">Place ce fichier <code>README.html</code> à la racine du dépôt ou dans <code>docs/</code> pour l'afficher via GitHub Pages. Personnalise les liens et contenus au fur et à mesure.</p>
            <div class="card-cta">
              <strong>Astuce :</strong> Pour activer une page attractive sur GitHub Pages, dépose ce fichier dans <code>docs/</code> et active GitHub Pages sur la branche <code>main</code>.
            </div>
          </section>
        </main>

        <aside>
          <div class="section" id="skills">
            <h2>Compétences</h2>
            <ul>
              <li>PHP 8 · MySQL · MVC</li>
              <li>CI/CD: GitHub Actions</li>
              <li>Hébergement: CPanel, FTPS</li>
              <li>Automatisation: Agents MCP</li>
              <li>Design: Identité visuelle & UI institutionnelle</li>
            </ul>
          </div>

          <div class="section" id="contact">
            <h2>Contact</h2>
            <p style="color:var(--muted)">Basé en RDC — Disponible pour collaborations et missions.</p>
            <p style="margin-top:8px"><a class="btn" href="https://github.com/SELEMANI">Profil GitHub</a></p>
            <p style="margin-top:8px;color:var(--muted)">Projet: <a href="https://www.ccclezoo.cd" style="color:var(--accent)">www.ccclezoo.cd</a></p>
          </div>

          <div class="section">
            <h2>Extrait technique</h2>
            <pre>CREATE TABLE articles (
  id INT AUTO_INCREMENT PRIMARY KEY,
  title VARCHAR(255),
  slug VARCHAR(255),
  body TEXT,
  created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);

.github/workflows/deploy.yml
</pre>
          </div>
        </aside>
      </div>

      <footer>
        © SELEMANI — Portfolio & README • Généré en HTML stylé
      </footer>
    </div>
  </div>
</body>
</html>

