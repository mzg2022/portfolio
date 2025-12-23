---
title: "Проекты"
date: 2024-12-23T10:00:00+00:00
draft: false
---

Здесь представлены мои учебные работы по всем курсам обучения.

<script>
function toggleAccordion(id) {
  const element = document.getElementById(id);
  const header = element.previousElementSibling;
  const icon = header.querySelector('.accordion-icon');
  
  if (element.style.display === 'block' || element.style.display === '') {
    element.style.display = 'none';
    icon.textContent = '▶';
    header.classList.remove('active');
  } else {
    element.style.display = 'block';
    icon.textContent = '▼';
    header.classList.add('active');
  }
}
</script>

<style>
.accordion-header {
  cursor: pointer;
  padding: 15px;
  background: var(--theme-background, #f8f9fa);
  border: 1px solid var(--theme-border, #e9ecef);
  margin: 5px 0;
  border-radius: 8px;
  font-weight: bold;
  display: flex;
  align-items: center;
  justify-content: space-between;
  transition: all 0.3s ease;
}

.accordion-header:hover {
  background: var(--theme-hover, #e9ecef);
}

.accordion-header.active {
  background: var(--accent-color, #007bff);
  color: white;
  border-color: var(--accent-color, #007bff);
}

.accordion-icon {
  margin-right: 10px;
  transition: transform 0.3s ease;
}

.accordion-content {
  margin-left: 20px;
  padding: 15px;
  border-left: 3px solid var(--accent-color, #007bff);
  background: var(--theme-background, #f8f9fa);
  border-radius: 0 8px 8px 0;
  display: none;
  margin-top: -5px;
  margin-bottom: 10px;
}

.project-link {
  display: block;
  padding: 8px 12px;
  margin: 5px 0;
  background: var(--card-background, white);
  text-decoration: none;
  color: var(--accent-color, #007bff);
  border-radius: 5px;
  border: 1px solid var(--theme-border, #dee2e6);
  transition: all 0.3s ease;
}

.project-link:hover {
  background: var(--accent-color, #007bff);
  color: white;
  text-decoration: none;
  transform: translateX(5px);
}

.subject-header {
  cursor: pointer;
  padding: 10px;
  background: var(--card-background, white);
  border: 1px solid var(--theme-border, #dee2e6);
  margin: 8px 0;
  border-radius: 5px;
  font-weight: normal;
  font-size: 0.95em;
}

.subject-header:hover {
  background: var(--theme-hover, #f1f3f4);
}

.subject-content {
  margin-left: 15px;
  padding: 10px;
  background: var(--card-background, white);
  border-radius: 5px;
  display: none;
}

/* Темная тема */
@media (prefers-color-scheme: dark) {
  .accordion-header {
    background: #2d3748;
    border-color: #4a5568;
    color: #e2e8f0;
  }
  
  .accordion-header:hover {
    background: #4a5568;
  }
  
  .accordion-content {
    background: #2d3748;
  }
  
  .project-link {
    background: #1a202c;
    border-color: #4a5568;
    color: #63b3ed;
  }
  
  .project-link:hover {
    background: #3182ce;
    color: white;
  }
  
  .subject-header {
    background: #1a202c;
    border-color: #4a5568;
    color: #e2e8f0;
  }
  
  .subject-header:hover {
    background: #2d3748;
  }
  
  .subject-content {
    background: #1a202c;
    color: #e2e8f0;
  }
}

/* Автоматическая тема */
[data-theme=dark] .accordion-header {
  background: #2d3748;
  border-color: #4a5568;
  color: #e2e8f0;
}

[data-theme=dark] .accordion-header:hover {
  background: #4a5568;
}

[data-theme=dark] .accordion-content {
  background: #2d3748;
}

[data-theme=dark] .project-link {
  background: #1a202c;
  border-color: #4a5568;
  color: #63b3ed;
}

[data-theme=dark] .project-link:hover {
  background: #3182ce;
  color: white;
}

[data-theme=dark] .subject-header {
  background: #1a202c;
  border-color: #4a5568;
  color: #e2e8f0;
}

[data-theme=dark] .subject-header:hover {
  background: #2d3748;
}

[data-theme=dark] .subject-content {
  background: #1a202c;
  color: #e2e8f0;
}
</style>

<div class="accordion-header" onclick="toggleAccordion('course1')">
  <span><span class="accordion-icon">▶</span> 1 курс</span>
</div>
<div id="course1" class="accordion-content">
    
  <div class="subject-header" onclick="toggleAccordion('course1-programming')">
    <span><span class="accordion-icon">▶</span> 💻 Программирование</span>
  </div>
  <div id="course1-programming" class="subject-content">
    <a href="https://mzg2022.github.io/portfolio/projects/course1/programming/lab1/" class="project-link">Лабораторная работа №1</a>
  </div>
</div>

<div class="accordion-header" onclick="toggleAccordion('course2')">
  <span><span class="accordion-icon">▶</span> 2 курс</span>
</div>
<div id="course2" class="accordion-content">
  
</div>

<div class="accordion-header" onclick="toggleAccordion('course3')">
  <span><span class="accordion-icon">▶</span> 3 курс</span>
</div>
<div id="course3" class="accordion-content">
  
</div>

<div class="accordion-header" onclick="toggleAccordion('course4')">
  <span><span class="accordion-icon">▶</span> 4 курс</span>
</div>
<div id="course4" class="accordion-content">
  
</div>