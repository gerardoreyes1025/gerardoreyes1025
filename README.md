<h1 align="center">¡Hola! 👋 Soy Gerardo Reyes</h1>
<h3 align="center" id="main-title">Ingeniero de Sistemas | Automatización y Procesos | Futuro Data Engineer</h3>

<div align="center">
  <button onclick="switchLanguage('es')">🇪🇸 Español</button>
  <button onclick="switchLanguage('en')">🇬🇧 English</button>
</div>

<p align="center" id="quote">
  <i>"Transformo problemas operativos en soluciones automatizadas eficientes."</i>
</p>

<!-- Sección Sobre Mí -->
<h2 id="about-title">🚀 Sobre mí</h2>
<ul id="about-content">
  <li>⚡ <strong>Automatizo procesos críticos</strong>: Diseño soluciones para eliminar tareas repetitivas, reducir errores y optimizar flujos de trabajo con tecnología.</li>
  <li>🤖 <strong>Desarrollo asistido por IA</strong>: Combino prompts estratégicos con librerías validadas para crear herramientas funcionales.</li>
  <li>📊 <strong>Gestión de procesos</strong>: Experiencia en modelado BPMN (Bizagi) y documentación técnica.</li>
  <li>🏗️ <strong>Gestión de proyectos</strong>: Metodologías ágiles (Scrum/Kanban) y seguimiento con Jira.</li>
  <li>🔒 <strong>Seguridad</strong>: Auditor Interno ISO 27001, con comprensión de controles y riesgos TI.</li>
  <li>🖥️ <strong>Infraestructura</strong>: Administración de Active Directory y soluciones ad-hoc.</li>
  <li>🌱 <strong>En formación</strong>: Arquitecturas de datos escalables y entornos cloud.</li>
</ul>

<!-- Sección Habilidades -->
<h2 id="skills-title">🛠 Habilidades Técnicas</h2>

<h3 id="auto-title">🤖 Automatización y Desarrollo</h3>
<table>
  <tr>
    <th id="area1-title">Área</th>
    <th id="tech1-title">Tecnologías/Habilidades</th>
  </tr>
  <tr>
    <td><strong id="lang-title">Lenguajes</strong></td>
    <td>Python (Pandas, Pillow), C# (.NET)</td>
  </tr>
  <tr>
    <td><strong id="auto-subtitle">Automatización</strong></td>
    <td>ETL, generación de documentos, APIs</td>
  </tr>
  <tr>
    <td><strong id="front-title">Frontend</strong></td>
    <td>ReactJS, PHP</td>
  </tr>
  <tr>
    <td><strong id="db-title">Bases de Datos</strong></td>
    <td>SQL, MySQL (consultas avanzadas)</td>
  </tr>
  <tr>
    <td><strong id="git-title">Control Versiones</strong></td>
    <td>Git/GitHub/Gitlab</td>
  </tr>
</table>

<h3 id="management-title">🏢 Gestión de TI</h3>
<table>
  <tr>
    <th id="area2-title">Área</th>
    <th id="tech2-title">Tecnologías/Habilidades</th>
  </tr>
  <tr>
    <td><strong id="project-title">Gestión Proyectos</strong></td>
    <td>Jira, Scrum/Kanban</td>
  </tr>
  <tr>
    <td><strong id="model-title">Modelado</strong></td>
    <td>Bizagi (BPMN)</td>
  </tr>
  <tr>
    <td><strong id="sec-title">Seguridad</strong></td>
    <td>ISO 27001, controles de acceso</td>
  </tr>
  <tr>
    <td><strong id="infra-title">Infraestructura</strong></td>
    <td>Active Directory, Linux básico</td>
  </tr>
</table>

<!-- GitHub Stats -->
<h2 id="stats-title">📊 Estadísticas GitHub</h2>
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=gerardoreyes1025&theme=vue-dark&show_icons=true&hide_border=true&layout=compact" alt="Lenguajes más usados">
</p>

<!-- Contacto -->
<h2 id="contact-title">📫 Contacto</h2>
<p align="center">
  <a href="mailto:gerardoreyes1025@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail">
  </a>
  <a href="https://linkedin.com/in/tu-perfil">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
</p>

<script>
// Contenido en inglés
const englishContent = {
  "main-title": "Systems Engineer | Automation & Processes | Future Data Engineer",
  "quote": '"I transform operational problems into efficient automated solutions."',
  "about-title": "🚀 About Me",
  "about-content": [
    "⚡ <strong>Automate critical processes</strong>: Design solutions to eliminate repetitive tasks, reduce errors and optimize workflows with technology.",
    "🤖 <strong>AI-assisted development</strong>: Combine strategic prompts with validated libraries to create functional tools.",
    "📊 <strong>Process management</strong>: Experience in BPMN modeling (Bizagi) and technical documentation.",
    "🏗️ <strong>Project management</strong>: Agile methodologies (Scrum/Kanban) and Jira tracking.",
    "🔒 <strong>Information security</strong>: ISO 27001 Internal Auditor, with understanding of IT controls and risks.",
    "🖥️ <strong>Infrastructure management</strong>: Active Directory administration and ad-hoc solutions deployment.",
    "🌱 <strong>In intensive training</strong>: Acquiring skills in scalable data architectures and cloud environments."
  ],
  "skills-title": "🛠 Technical Skills",
  "auto-title": "🤖 Automation & Development",
  "area1-title": "Area",
  "tech1-title": "Technologies/Skills",
  "lang-title": "Languages",
  "auto-subtitle": "Automation",
  "front-title": "Frontend",
  "db-title": "Databases",
  "git-title": "Version Control",
  "management-title": "🏢 IT Management",
  "area2-title": "Area",
  "tech2-title": "Technologies/Skills",
  "project-title": "Project Management",
  "model-title": "Modeling",
  "sec-title": "Security",
  "infra-title": "Infrastructure",
  "stats-title": "📊 GitHub Stats",
  "contact-title": "📫 Contact"
};

function switchLanguage(lang) {
  if (lang === 'en') {
    // Actualizar contenido en inglés
    document.getElementById('main-title').innerText = englishContent['main-title'];
    document.getElementById('quote').innerHTML = `<i>${englishContent['quote']}</i>`;
    document.getElementById('about-title').innerText = englishContent['about-title'];
    
    const aboutItems = englishContent['about-content'];
    const aboutList = document.getElementById('about-content').children;
    for (let i = 0; i < aboutList.length; i++) {
      aboutList[i].innerHTML = aboutItems[i];
    }
    
    // Actualizar títulos de secciones
    const sectionTitles = [
      'skills-title', 'auto-title', 'management-title',
      'stats-title', 'contact-title'
    ];
    sectionTitles.forEach(id => {
      document.getElementById(id).innerText = englishContent[id];
    });
    
    // Actualizar títulos de tablas
    const tableTitles = [
      'area1-title', 'tech1-title', 'area2-title', 'tech2-title',
      'lang-title', 'auto-subtitle', 'front-title', 'db-title',
      'git-title', 'project-title', 'model-title', 'sec-title',
      'infra-title'
    ];
    tableTitles.forEach(id => {
      document.getElementById(id).innerText = englishContent[id];
    });
    
  } else {
    // Recargar la página para volver a español
    location.reload();
  }
}
</script>
