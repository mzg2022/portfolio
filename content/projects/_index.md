---
title: "Проекты"
date: 2024-12-23T10:00:00+00:00
draft: false
---

# Мои проекты

Здесь представлены мои учебные работы по всем курсам обучения.

<script>
function toggleCourse(courseId) {
  const element = document.getElementById(courseId);
  if (element.style.display === 'none' || element.style.display === '') {
    element.style.display = 'block';
  } else {
    element.style.display = 'none';
  }
}

function toggleSubject(subjectId) {
  const element = document.getElementById(subjectId);
  if (element.style.display === 'none' || element.style.display === '') {
    element.style.display = 'block';
  } else {
    element.style.display = 'none';
  }
}
</script>

<style>
.course-toggle, .subject-toggle {
  cursor: pointer;
  padding: 10px;
  background-color: #f0f0f0;
  border: 1px solid #ddd;
  margin: 5px 0;
  border-radius: 5px;
  font-weight: bold;
}

.course-toggle:hover, .subject-toggle:hover {
  background-color: #e0e0e0;
}

.course-content, .subject-content {
  margin-left: 20px;
  padding: 10px;
  border-left: 3px solid #007bff;
  display: none;
}

.work-link {
  display: block;
  padding: 5px 10px;
  margin: 3px 0;
  background-color: #f8f9fa;
  text-decoration: none;
  color: #007bff;
  border-radius: 3px;
}

.work-link:hover {
  background-color: #e9ecef;
  text-decoration: underline;
}
</style>

<div class="course-toggle" onclick="toggleCourse('course1')">📚 1 курс</div>
<div id="course1" class="course-content">
  <div class="subject-toggle" onclick="toggleSubject('course1-math')">📐 Математика</div>
  <div id="course1-math" class="subject-content">
    <a href="/projects/labs/math1-lab1/" class="work-link">Лабораторная работа №1</a>
    <a href="/projects/labs/math1-lab2/" class="work-link">Лабораторная работа №2</a>
    <a href="/projects/labs/math1-kurs/" class="work-link">Курсовая работа</a>
  </div>
  
  <div class="subject-toggle" onclick="toggleSubject('course1-programming')">💻 Программирование</div>
  <div id="course1-programming" class="subject-content">
    <a href="/projects/labs/prog1-lab1/" class="work-link">Лабораторная работа №1</a>
    <a href="/projects/labs/prog1-lab2/" class="work-link">Лабораторная работа №2</a>
    <a href="/projects/labs/prog1-project/" class="work-link">Курсовой проект</a>
  </div>
</div>

<div class="course-toggle" onclick="toggleCourse('course2')">📚 2 курс</div>
<div id="course2" class="course-content">
  <div class="subject-toggle" onclick="toggleSubject('course2-algorithms')">⚡ Алгоритмы и структуры данных</div>
  <div id="course2-algorithms" class="subject-content">
    <a href="/projects/labs/algo2-lab1/" class="work-link">Лабораторная работа №1</a>
    <a href="/projects/labs/algo2-lab2/" class="work-link">Лабораторная работа №2</a>
    <a href="/projects/labs/algo2-kurs/" class="work-link">Курсовая работа</a>
  </div>
  
  <div class="subject-toggle" onclick="toggleSubject('course2-databases')">🗄️ Базы данных</div>
  <div id="course2-databases" class="subject-content">
    <a href="/projects/labs/db2-lab1/" class="work-link">Лабораторная работа №1</a>
    <a href="/projects/labs/db2-lab2/" class="work-link">Лабораторная работа №2</a>
    <a href="/projects/labs/db2-project/" class="work-link">Курсовой проект</a>
  </div>
</div>

<div class="course-toggle" onclick="toggleCourse('course3')">📚 3 курс</div>
<div id="course3" class="course-content">
  <div class="subject-toggle" onclick="toggleSubject('course3-web')">🌐 Веб-разработка</div>
  <div id="course3-web" class="subject-content">
    <a href="/projects/labs/web3-lab1/" class="work-link">Лабораторная работа №1</a>
    <a href="/projects/labs/web3-lab2/" class="work-link">Лабораторная работа №2</a>
    <a href="/projects/labs/web3-project/" class="work-link">Курсовой проект</a>
  </div>
  
  <div class="subject-toggle" onclick="toggleSubject('course3-ml')">🤖 Машинное обучение</div>
  <div id="course3-ml" class="subject-content">
    <a href="/projects/labs/ml3-lab1/" class="work-link">Лабораторная работа №1</a>
    <a href="/projects/labs/ml3-lab2/" class="work-link">Лабораторная работа №2</a>
    <a href="/projects/labs/ml3-kurs/" class="work-link">Курсовая работа</a>
  </div>
</div>

<div class="course-toggle" onclick="toggleCourse('course4')">📚 4 курс</div>
<div id="course4" class="course-content">
  <div class="subject-toggle" onclick="toggleSubject('course4-thesis')">🎓 Дипломное проектирование</div>
  <div id="course4-thesis" class="subject-content">
    <a href="/projects/thesis/intro/" class="work-link">Введение в дипломную работу</a>
    <a href="/projects/thesis/chapter1/" class="work-link">Глава 1: Анализ предметной области</a>
    <a href="/projects/thesis/chapter2/" class="work-link">Глава 2: Проектирование системы</a>
    <a href="/projects/thesis/implementation/" class="work-link">Реализация и тестирование</a>
  </div>
  
  <div class="subject-toggle" onclick="toggleSubject('course4-soft')">📦 Программная инженерия</div>
  <div id="course4-soft" class="subject-content">
    <a href="/projects/labs/se4-lab1/" class="work-link">Лабораторная работа №1</a>
    <a href="/projects/labs/se4-lab2/" class="work-link">Лабораторная работа №2</a>
    <a href="/projects/labs/se4-project/" class="work-link">Курсовой проект</a>
  </div>
</div>