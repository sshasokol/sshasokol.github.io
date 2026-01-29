---
layout: default
---

<!-- Основной контейнер -->
<div class="resume-container">

  <!-- Шапка с фото и контактами -->
  <header class="resume-header">
    <div class="header-text">
      <h1 class="name-title">Александр Соколов</h1>
      <h2 class="job-title">Старший специалист по управлению мастер-данными</h2>
      <p class="tagline">Data Analyst с фокусом на Data Governance, BI и автоматизацию процессов</p>
      
      <div class="contact-info">
        <span>📍 Санкт-Петербург</span>
        <span>📧 rimobob@gmail.com</span>
        <span>📱 +7 (931) 310-95-29</span>
      </div>
    </div>
    <div class="header-photo">
      <!-- Убедитесь, что путь к фото верный -->
      <img src="/assets/images/profile photo.jpg" alt="Александр Соколов">
    </div>
  </header>

  <!-- Краткое описание -->
  <section class="summary">
    <p><strong>Более 3 лет опыта</strong> в FMCG и IT (структура Heineken Russia). Специализируюсь на построении BI-отчетности, автоматизации процессов на Python и управлении мастер-данными. Нацелен на то, чтобы сделать данные доступными и понятными для бизнеса. Успешно работаю на стыке бизнес-запросов и технической реализации.</p>
  </section>

  <!-- Ключевые компетенции -->
  <section class="section">
    <h2>🚀 Ключевые компетенции</h2>
    <div class="skills-grid">
      <div class="skill-category">
        <h3>📊 BI & Визуализация</h3>
        <ul>
          <li>Power BI, DAX, Power Query</li>
          <li>Создание дашбордов с нуля</li>
          <li>Pivot Tables, VBA</li>
        </ul>
      </div>
      <div class="skill-category">
        <h3>🐍 Программирование</h3>
        <ul>
          <li>Python (Pandas, NumPy, Matplotlib/Seaborn)</li>
          <li>Автоматизация отчетов и ETL</li>
          <li>SQL (оконные функции, подзапросы)</li>
        </ul>
      </div>
      <div class="skill-category">
        <h3>🗄️ Управление данными</h3>
        <ul>
          <li>Data Governance (OpenMetaData, LMDM)</li>
          <li>Мастер-данные (MDM), MDS</li>
          <li>Аудит и оптимизация данных</li>
        </ul>
      </div>
      <div class="skill-category">
        <h3>🔧 Инструменты & ERP</h3>
        <ul>
          <li>SAP ERP, 1С</li>
          <li>Git, Docker</li>
          <li>Miro, Draw.io</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- Опыт работы -->
  <section class="section">
    <h2>💼 Опыт работы</h2>
    <div class="experience">
      <h3>Старший специалист по мастер-данным и управлению данными</h3>
      <p class="company-period"><strong>ООО «ИКС-Тех» (Дочка ООО «ОПХ»)</strong> | 2024 — н.в.</p>
      <ul>
        <li>Повысил точность мастер-данных на <strong>25%</strong> через реструктуризацию.</li>
        <li>Автоматизировал процессы на Python (<strong>-15 часов</strong> ручной работы/месяц).</li>
        <li>Участвовал в интеграции Local MDM и SAP ERP.</li>
      </ul>
    </div>
    <div class="experience">
      <h3>BI-аналитик</h3>
      <p class="company-period"><strong>ООО «ОПХ» (в структуре Heineken)</strong> | 2022 — 2024</p>
      <ul>
        <li>Разработал <strong>5 ключевых дашбордов</strong> в Power BI с нуля.</li>
        <li>Сократил время формирования отчетности на <strong>30%</strong>.</li>
        <li>Участвовал в миграции BI-системы на новый стэк.</li>
      </ul>
    </div>
  </section>


</div>

<!-- Стили для страницы -->
<style>
  /* Общие стили для чистого листа */
  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.6;
    color: #333;
    max-width: 1000px;
    margin: 40px auto;
    padding: 0 20px;
    background-color: #f9f9f9;
  }
  
  .resume-container {
    background: white;
    border-radius: 12px;
    box-shadow: 0 5px 25px rgba(0,0,0,0.08);
    padding: 40px;
  }
  
  /* Шапка с фото */
  .resume-header {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    gap: 50px;
    margin-bottom: 40px;
    flex-wrap: wrap;
  }
  .header-text {
    flex: 1;
    min-width: 300px;
  }
  .name-title {
    color: #2c3e50;
    margin-bottom: 5px;
    font-size: 2.5em;
  }
  .job-title {
    color: #3498db;
    margin-top: 0;
    margin-bottom: 15px;
  }
  .tagline {
    color: #555;
    font-size: 1.1em;
    margin-bottom: 20px;
  }
  .contact-info {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    color: #555;
  }
  .header-photo {
    flex: 0 0 200px;
  }
  .header-photo img {
    width: 100%;
    max-width: 200px;
    border-radius: 10px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  }
  
  /* Секции */
  .section {
    margin-top: 50px;
  }
  .section h2 {
    color: #2c3e50;
    border-bottom: 3px solid #3498db;
    padding-bottom: 10px;
    margin-bottom: 25px;
  }
  
  /* Сетка навыков */
  .skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
    gap: 25px;
  }
  .skill-category {
    background: #f8f9fa;
    padding: 20px;
    border-radius: 8px;
    border-left: 4px solid #3498db;
  }
  .skill-category h3 {
    margin-top: 0;
    color: #2c3e50;
  }
  
  /* Опыт работы */
  .experience {
    margin-bottom: 35px;
  }
  .company-period {
    color: #555;
    margin-top: -10px;
    margin-bottom: 10px;
  }
  
  /* Футер */
  .resume-footer {
    text-align: center;
    margin-top: 60px;
    padding-top: 25px;
    border-top: 2px solid #eee;
    color: #555;
  }
</style>
