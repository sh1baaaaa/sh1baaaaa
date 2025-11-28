<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>sh1baaaaa - Java Backend Developer</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap');
    
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    
    body {
      font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
      background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%);
      color: #e2e8f0;
      line-height: 1.6;
      min-height: 100vh;
      padding: 2rem;
    }
    
    .container {
      max-width: 800px;
      margin: 0 auto;
      background: rgba(15, 23, 42, 0.8);
      backdrop-filter: blur(10px);
      border-radius: 16px;
      padding: 3rem;
      box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.3), 0 10px 10px -5px rgba(0, 0, 0, 0.2);
      border: 1px solid rgba(255, 255, 255, 0.1);
    }
    
    .header {
      text-align: center;
      margin-bottom: 2.5rem;
      padding-bottom: 1.5rem;
      border-bottom: 1px solid rgba(255, 255, 255, 0.1);
    }
    
    .avatar {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      object-fit: cover;
      margin: 0 auto 1rem;
      border: 3px solid #3b82f6;
      background: linear-gradient(45deg, #3b82f6, #8b5cf6);
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 4rem;
      color: white;
    }
    
    .name {
      font-size: 2.5rem;
      font-weight: 700;
      color: #f8fafc;
      margin-bottom: 0.5rem;
    }
    
    .title {
      font-size: 1.2rem;
      color: #94a3b8;
      margin-bottom: 1rem;
    }
    
    .tagline {
      font-size: 1.1rem;
      color: #cbd5e1;
      max-width: 600px;
      margin: 0 auto 1.5rem;
    }
    
    .section {
      margin-bottom: 2rem;
    }
    
    .section-title {
      font-size: 1.4rem;
      font-weight: 600;
      color: #3b82f6;
      margin-bottom: 1rem;
      display: flex;
      align-items: center;
      gap: 0.5rem;
    }
    
    .skills-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1rem;
      margin-bottom: 1.5rem;
    }
    
    .skill-category {
      background: rgba(30, 41, 59, 0.6);
      padding: 1rem;
      border-radius: 8px;
      border-left: 3px solid #3b82f6;
    }
    
    .skill-category h4 {
      color: #94a3b8;
      font-size: 0.9rem;
      text-transform: uppercase;
      letter-spacing: 0.05em;
      margin-bottom: 0.5rem;
    }
    
    .skill-list {
      list-style: none;
    }
    
    .skill-list li {
      padding: 0.25rem 0;
      color: #e2e8f0;
      position: relative;
      padding-left: 1rem;
    }
    
    .skill-list li::before {
      content: "•";
      color: #3b82f6;
      position: absolute;
      left: 0;
    }
    
    .highlight-box {
      background: rgba(59, 130, 246, 0.1);
      border: 1px solid rgba(59, 130, 246, 0.3);
      border-radius: 8px;
      padding: 1.5rem;
      margin: 1rem 0;
    }
    
    .highlight-title {
      color: #3b82f6;
      font-weight: 600;
      margin-bottom: 0.5rem;
    }
    
    .contact-grid {
      display: grid;
      grid-template-columns: 1fr;
      gap: 1rem;
      margin-top: 1rem;
    }
    
    .contact-item {
      display: flex;
      align-items: center;
      gap: 0.75rem;
      padding: 0.75rem;
      background: rgba(30, 41, 59, 0.6);
      border-radius: 8px;
      transition: all 0.2s ease;
    }
    
    .contact-item:hover {
      background: rgba(59, 130, 246, 0.2);
      transform: translateY(-2px);
    }
    
    .contact-icon {
      width: 24px;
      height: 24px;
      color: #3b82f6;
    }
    
    .contact-text {
      color: #e2e8f0;
      text-decoration: none;
      transition: color 0.2s ease;
    }
    
    .contact-text:hover {
      color: #93c5fd;
    }
    
    .portfolio-links {
      display: flex;
      flex-direction: column;
      gap: 0.5rem;
      margin-top: 1rem;
    }
    
    .portfolio-link {
      color: #3b82f6;
      text-decoration: none;
      padding: 0.5rem 0;
      transition: color 0.2s ease;
    }
    
    .portfolio-link:hover {
      color: #93c5fd;
      text-decoration: underline;
    }
    
    .status {
      display: inline-block;
      background: rgba(34, 197, 94, 0.1);
      color: #22c55e;
      padding: 0.25rem 0.75rem;
      border-radius: 20px;
      font-size: 0.9rem;
      margin-top: 0.5rem;
    }
    
    @media (max-width: 768px) {
      .container {
        padding: 2rem 1.5rem;
        margin: 1rem;
      }
      
      .name {
        font-size: 2rem;
      }
      
      .skills-grid {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <header class="header">
      <div class="avatar">S</div>
      <h1 class="name">sh1baaaaa</h1>
      <p class="title">Java Backend Developer</p>
      <p class="tagline">Backend разработчик с 2-летним опытом, специализируюсь на создании масштабируемых и надежных серверных решений</p>
      <div class="status">В активном поиске работы</div>
    </header>

    <section class="section">
      <h2 class="section-title">Опыт и навыки</h2>
      <div class="skills-grid">
        <div class="skill-category">
          <h4>Java Core</h4>
          <ul class="skill-list">
            <li>Java 8+</li>
            <li>Stream API</li>
            <li>Multithreading</li>
            <li>Collection Framework</li>
          </ul>
        </div>
        <div class="skill-category">
          <h4>Spring Ecosystem</h4>
          <ul class="skill-list">
            <li>Spring Boot</li>
            <li>Spring Data JPA</li>
            <li>Spring Security</li>
            <li>Spring Cloud</li>
            <li>Spring AOP</li>
          </ul>
        </div>
        <div class="skill-category">
          <h4>Базы данных</h4>
          <ul class="skill-list">
            <li>PostgreSQL</li>
            <li>MySQL</li>
            <li>MSSQL</li>
            <li>Redis</li>
          </ul>
        </div>
        <div class="skill-category">
          <h4>Принципы</h4>
          <ul class="skill-list">
            <li>ООП</li>
            <li>SOLID</li>
            <li>DRY, KISS</li>
            <li>Design Patterns</li>
          </ul>
        </div>
      </div>
    </section>

    <section class="section">
      <h2 class="section-title">Описание</h2>
      <p>Занимаюсь backend разработкой на Java более 2 лет. Имею уверенное знание Java Core, включая Multithreading и Stream API. Понимаю принципы ООП, SOLID, DRY, KISS и применяю их в своей работе.</p>
      
      <div class="highlight-box">
        <h3 class="highlight-title">Коммерческий опыт</h3>
        <p>Присутствует коммерческий опыт в работе со Spring Framework (Data JPA / AOP / Boot / Cloud / Security) и различными SQL/noSQL базами данных (PostgreSQL, MSSQL, MySQL, Redis).</p>
      </div>
      
      <p>Есть разговорный уровень английского и навык чтения англоязычной технической документации.</p>
    </section>

    <section class="section">
      <h2 class="section-title">Выдающиеся проекты</h2>
      <div class="highlight-box">
        <h3 class="highlight-title">Low-latency сервис для SPIMEX</h3>
        <p>Разработка высокопроизводительного сервиса для автоматизации торговли на бирже SPIMEX с минимальными задержками обработки запросов.</p>
      </div>
      <p>В портфолио имеются коммерческие и пет-проекты, включая:</p>
      <ul class="skill-list">
        <li>users-microservices-manager - мульти-модульный проект с микросервисами и DTO</li>
        <li>searching-engine - поисковый движок для индексации и поиска страниц</li>
        <li>InstagramStoriesAnalysis - сервис для анализа Instagram историй с кэшированием в Redis</li>
        <li>Task-Management-System - система управления задачами</li>
      </ul>
    </section>

    <section class="section">
      <h2 class="section-title">Портфолио</h2>
      <div class="portfolio-links">
        <a href="https://t.me/shibafeedbacks" class="portfolio-link" target="_blank">https://t.me/shibafeedbacks</a>
        <a href="https://github.com/sh1baaaaa" class="portfolio-link" target="_blank">https://github.com/sh1baaaaa</a>
      </div>
    </section>

    <section class="section">
      <h2 class="section-title">Контактная информация</h2>
      <div class="contact-grid">
        <div class="contact-item">
          <svg class="contact-icon" fill="currentColor" viewBox="0 0 24 24">
            <path d="M12 2C6.477 2 2 6.477 2 12c0 4.42 2.865 8.166 6.839 9.489.5.09.682-.218.682-.485 0-.236-.008-.866-.013-1.7-2.782.603-3.369-1.34-3.369-1.34-.454-1.157-1.11-1.465-1.11-1.465-.908-.62.069-.608.069-.608 1.003.07 1.531 1.03 1.531 1.03.892 1.529 2.341 1.089 2.91.833.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.11-4.555-4.943 0-1.091.39-1.984 1.029-2.683-.103-.253-.446-1.27.098-2.647 0 0 .84-.268 2.75 1.026A9.578 9.578 0 0112 6.836c.85.004 1.705.114 2.504.336 1.909-1.294 2.747-1.026 2.747-1.026.546 1.377.203 2.394.1 2.647.64.699 1.028 1.592 1.028 2.683 0 3.842-2.339 4.687-4.566 4.935.359.309.678.919.678 1.852 0 1.336-.012 2.415-.012 2.743 0 .267.18.578.688.48C19.138 20.161 22 16.416 22 12c0-5.523-4.477-10-10-10z"/>
          </svg>
          <a href="https://github.com/sh1baaaaa" class="contact-text" target="_blank">@sh1baaaaa</a>
        </div>
        <div class="contact-item">
          <svg class="contact-icon" fill="currentColor" viewBox="0 0 24 24">
            <path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8 8 3.59 8 8-3.59 8-8 8zm-1-13h2v6h-2zm0 8h2v2h-2z"/>
          </svg>
          <a href="https://t.me/cfogoogle" class="contact-text" target="_blank">@cfogoogle</a>
        </div>
      </div>
      <p style="margin-top: 1rem; color: #94a3b8; font-size: 0.9rem;">Рассматриваю предложения о работе как по трудовому договору, так и на условиях самозанятости</p>
    </section>
  </div>
</body>
</html>

