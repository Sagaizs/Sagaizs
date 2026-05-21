
<style>
  .profile-wrap { max-width: 680px; padding: 1.5rem 0; font-family: var(--font-sans); }
  .profile-header { margin-bottom: 1.5rem; }
  .profile-header h1 { font-size: 22px; font-weight: 500; color: var(--color-text-primary); margin: 0 0 4px; }
  .profile-header p { font-size: 14px; color: var(--color-text-secondary); margin: 0; }
  .section { margin-bottom: 1.5rem; }
  .section-title { font-size: 13px; font-weight: 500; color: var(--color-text-secondary); text-transform: uppercase; letter-spacing: 0.08em; margin: 0 0 0.75rem; border-bottom: 0.5px solid var(--color-border-tertiary); padding-bottom: 6px; }
  .about-text { font-size: 14px; color: var(--color-text-primary); line-height: 1.7; margin: 0; }
  .contact-links { display: flex; gap: 8px; flex-wrap: wrap; }
  .contact-link { display: inline-flex; align-items: center; gap: 6px; padding: 6px 12px; border: 0.5px solid var(--color-border-tertiary); border-radius: var(--border-radius-md); font-size: 13px; font-weight: 500; color: var(--color-text-primary); text-decoration: none; background: var(--color-background-primary); transition: background 0.15s, border-color 0.15s; }
  .contact-link:hover { background: var(--color-background-secondary); border-color: var(--color-border-secondary); }
  .contact-link i { font-size: 16px; }
  .tech-grid { display: flex; flex-wrap: wrap; gap: 8px; }
  .tech-badge { display: inline-flex; align-items: center; gap: 6px; padding: 5px 10px; border: 0.5px solid var(--color-border-tertiary); border-radius: var(--border-radius-md); font-size: 13px; color: var(--color-text-primary); background: var(--color-background-secondary); }
  .tech-badge img { width: 16px; height: 16px; }
  .goals-list { list-style: none; margin: 0; padding: 0; display: flex; flex-direction: column; gap: 6px; }
  .goals-list li { display: flex; align-items: center; gap: 8px; font-size: 14px; color: var(--color-text-primary); }
  .goals-list li i { font-size: 15px; color: #3B6D11; }
  .study-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(140px, 1fr)); gap: 8px; }
  .study-card { background: var(--color-background-secondary); border: 0.5px solid var(--color-border-tertiary); border-radius: var(--border-radius-md); padding: 8px 12px; font-size: 13px; color: var(--color-text-primary); }
  .tagline { font-size: 15px; color: var(--color-text-secondary); margin: 0; padding-top: 1rem; border-top: 0.5px solid var(--color-border-tertiary); }
</style>

<div class="profile-wrap">
  <h2 class="sr-only">Perfil de Samuel dos Santos — Desenvolvedor Front-End em Formação</h2>

  <div class="profile-header">
    <h1>Samuel dos Santos</h1>
    <p>Desenvolvedor Front-End em Formação &nbsp;·&nbsp; Técnico em Informática · FIEB, São Paulo</p>
  </div>

  <div class="section">
    <p class="section-title">Sobre mim</p>
    <p class="about-text">
      Tenho 17 anos e sou estudante do Ensino Médio Técnico em Informática. Apaixonado por tecnologia e desenvolvimento web, com foco em criar interfaces modernas, responsivas e funcionais. Atualmente desenvolvo projetos com HTML, CSS, JavaScript e React, e estou em busca da minha primeira oportunidade de estágio em TI para crescer como desenvolvedor.
    </p>
  </div>

  <div class="section">
    <p class="section-title">Contato</p>
    <div class="contact-links">
      <a class="contact-link" href="mailto:samuelvitalde.jesus@gmail.com">
        <i class="ti ti-mail" aria-hidden="true"></i> Gmail
      </a>
      <a class="contact-link" href="https://www.linkedin.com/in/samuel-dos-santos-martins-353122410" target="_blank" rel="noopener">
        <i class="ti ti-brand-linkedin" aria-hidden="true"></i> LinkedIn
      </a>
      <a class="contact-link" href="https://github.com/Sagaizs" target="_blank" rel="noopener">
        <i class="ti ti-brand-github" aria-hidden="true"></i> GitHub
      </a>
    </div>
  </div>

  <div class="section">
    <p class="section-title">Tecnologias e ferramentas</p>
    <div class="tech-grid">
      <div class="tech-badge"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt=""> HTML5</div>
      <div class="tech-badge"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt=""> CSS3</div>
      <div class="tech-badge"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt=""> JavaScript</div>
      <div class="tech-badge"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" alt=""> React</div>
      <div class="tech-badge"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt=""> Git</div>
      <div class="tech-badge"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" alt=""> GitHub</div>
      <div class="tech-badge"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" alt=""> VS Code</div>
    </div>
  </div>

  <div class="section">
    <p class="section-title">Objetivos</p>
    <ul class="goals-list">
      <li><i class="ti ti-circle-check" aria-hidden="true"></i> Conseguir minha primeira oportunidade de estágio em TI</li>
      <li><i class="ti ti-circle-check" aria-hidden="true"></i> Evoluir como desenvolvedor Front-End</li>
      <li><i class="ti ti-circle-check" aria-hidden="true"></i> Aprender Back-End futuramente</li>
      <li><i class="ti ti-circle-check" aria-hidden="true"></i> Contribuir para projetos reais</li>
      <li><i class="ti ti-circle-check" aria-hidden="true"></i> Construir uma carreira sólida em tecnologia</li>
    </ul>
  </div>

  <div class="section">
    <p class="section-title">Atualmente estudando</p>
    <div class="study-grid">
      <div class="study-card">React.js</div>
      <div class="study-card">JavaScript Moderno</div>
      <div class="study-card">Git e GitHub</div>
      <div class="study-card">Responsividade</div>
      <div class="study-card">APIs</div>
      <div class="study-card">Desenvolvimento Web</div>
    </div>
  </div>

  <p class="tagline">"Transformando ideias em código."</p>
</div>
