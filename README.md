<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Prashant | Cloud Data Engineer</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Inter', sans-serif;
      margin: 0;
      padding: 0;
      background: #f8f9fa;
      color: #333;
    }
    header {
      background-color: #0d1117;
      color: white;
      text-align: center;
      padding: 3rem 1rem;
    }
    header h1 {
      font-size: 2.5rem;
    }
    header h3 {
      color: #58a6ff;
    }
    section {
      max-width: 900px;
      margin: 2rem auto;
      padding: 0 1rem;
    }
    .badge-grid {
      display: flex;
      flex-wrap: wrap;
      gap: 0.5rem;
      justify-content: center;
    }
    .badge-grid img {
      height: 28px;
    }
    .about p, .projects p, .skills p {
      font-size: 1.1rem;
      line-height: 1.6;
    }
    .section-title {
      font-size: 1.75rem;
      margin-top: 2rem;
      margin-bottom: 1rem;
      color: #0d1117;
      border-left: 4px solid #007acc;
      padding-left: 0.75rem;
    }
    .contact-icons a {
      margin-right: 10px;
    }
    footer {
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
      color: #666;
    }
  </style>
</head>
<body>
  <header>
    <h1>Hi 👋, I'm Prashant</h1>
    <h3>Cloud Data Engineer | Azure & Databricks Certified</h3>
    <div class="badge-grid">
      <a href="https://credentials.databricks.com/..." target="_blank">
        <img src="https://img.shields.io/badge/Databricks-Certified%20Data%20Engineer-orange?logo=databricks&logoColor=white" />
      </a>
      <a href="https://learn.microsoft.com/..." target="_blank">
        <img src="https://img.shields.io/badge/Microsoft-Azure%20Data%20Engineer-blue?logo=microsoft&logoColor=white" />
      </a>
    </div>
  </header>

  <section class="about">
    <h2 class="section-title">About Me</h2>
    <p>
      Passionate about solving business problems through data, I specialize in building cloud-native data platforms using Microsoft Azure, Databricks, and Fabric. From ingestion to insights, I bring hands-on expertise in end-to-end Data Engineering pipelines, Gen AI integration, and production-grade analytics systems.
    </p>
  </section>

  <section class="projects">
    <h2 class="section-title">Projects</h2>
    <ul>
      <li><strong>Enterprise Lakehouse:</strong> Built on Databricks with Medallion Architecture, supporting 5+ TB data and 40+ tables daily sync.</li>
      <li><strong>Gen AI Sales Assistant:</strong> LangChain + Azure OpenAI-powered chatbot integrated with Power BI for contextual sales Q&A.</li>
      <li><strong>Azure Fabric Migration:</strong> Rebuilt legacy ETLs using ADF + Spark notebooks and Synapse pipelines.</li>
    </ul>
  </section>

  <section class="skills">
    <h2 class="section-title">Tech Skills</h2>
    <p>
      <strong>Cloud:</strong> Azure Data Factory, Databricks, Fabric, Synapse<br>
      <strong>Data Tools:</strong> Delta Lake, SQL Server, ADLS, Blob Storage<br>
      <strong>Languages:</strong> Python, PySpark, SQL<br>
      <strong>Frameworks:</strong> LangChain, Flask, Pandas AI<br>
      <strong>ML & Gen AI:</strong> Azure OpenAI, Transformers, RAG, LLMOps<br>
    </p>
  </section>

  <section class="contact">
    <h2 class="section-title">Let's Connect</h2>
    <p class="contact-icons">
      <a href="https://linkedin.com/in/itech-prashant" target="_blank">LinkedIn</a> |
      <a href="mailto:itech.prash@gmail.com">Gmail</a> |
      <a href="https://topmate.io/itech_prashant" target="_blank">Topmate</a> |
      <a href="https://github.com/itech-prashant" target="_blank">GitHub</a>
    </p>
  </section>

  <footer>
    © 2025 Prashant | Built for Data Engineering, Analytics & AI
  </footer>
</body>
</html>
