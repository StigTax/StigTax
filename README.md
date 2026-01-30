<h2 align="center">Привет, я Никита!</h2>
<h3 align="center">Backend-Developer (Python/Django/Flask/FastAPI)</h3>
<p align="center">
  Обо мне: разрабатываю API-сервисы и бэкенд-логики, люблю разбираться в бизнес-правилах и оптимизировать решения.
  Сейчас прокачиваю: Celery, Redis, RabbitMQ.
</p>
<p align="center"> Telegram: <a href="https://t.me/Nik_efr">@Nik_efr</a></p>
<p align="center"> HH: <a href="https://balashiha.hh.ru/resume/59490fe0ff0f7a8d790039ed1f6c626b635464">Ефремчев Никита</a></p>
<p align="center"> Ищу роль: backend / Python </p>

---
<h2 align="center">
  <img width="45" height="45" src="https://img.icons8.com/dusk/64/admin-settings-male.png" alt="admin-settings-male"/> Skills
</h2>

**Backend:**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python)
![Django](https://img.shields.io/badge/Django-3776AB?style=flat&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/DRF-Framework-3776AB?style=flat&labelColor=1f2937)
![FastAPI](https://img.shields.io/badge/FastAPI-3776AB?style=flat&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-3776AB?style=flat&logo=flask&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-Models-3776AB?style=flat&labelColor=1f2937)

**DB & ORM:**  
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-003B57?style=flat&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-ORM-003B57?style=flat&labelColor=0b2230)
![Alembic](https://img.shields.io/badge/Alembic-Migrations-003B57?style=flat&labelColor=0b2230)

**Async & Infra:**  
![Celery](https://img.shields.io/badge/Celery-Tasks-ab3776?style=flat&labelColor=2b1a24)
![Redis](https://img.shields.io/badge/Redis-Cache%2FQueue-ab3776?style=flat&labelColor=2b1a24&logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-Broker-ab3776?style=flat&labelColor=2b1a24&logo=rabbitmq&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-ab3776?style=flat&logo=docker&labelColor=2b1a24&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-ab3776?style=flat&logo=nginx&labelColor=2b1a24&logoColor=white)

**Tooling:**  
![Pytest](https://img.shields.io/badge/Pytest-Testing-38761d?style=flat&labelColor=1c3b0e&logo=pytest&logoColor=white)
![Git](https://img.shields.io/badge/Git-Version%20Control-38761d?style=flat&labelColor=1c3b0e&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-Code-38761d?style=flat&labelColor=1c3b0e&logo=github&logoColor=white)
![ruff](https://img.shields.io/badge/ruff-linting-38761d?style=flat&labelColor=1c3b0e)
![pre--commit](https://img.shields.io/badge/pre--commit-hooks-38761d?style=flat&labelColor=1c3b0e)
![Postman](https://img.shields.io/badge/Postman-API%20Testing-38761d?style=flat&labelColor=1c3b0e&logo=postman&logoColor=white)

_Also:_ ![Scrapy](https://img.shields.io/badge/Scrapy-Web%20Scraping-38761d?style=flat&labelColor=1c3b0e)


---

<h2 align="center">
  <img width="45" height="45" src="https://img.icons8.com/arcade/32/edit.png" alt="edit"/> Projects
</h2>

<h3>
  <img width="45" height="45" src="https://img.icons8.com/external-flatart-icons-flat-flatarticons/64/external-pedestal-modern-education-and-knowledge-power-flatart-icons-flat-flatarticons.png" alt="external-pedestal-modern-education-and-knowledge-power-flatart-icons-flat-flatarticons"/> Top projects
</h3>
<ul>
  <li>
    <a href="https://github.com/StigTax/booking_seats">
      <img width="32" height="32" src="https://img.icons8.com/arcade/64/table.png" alt="table"/>
      Сервис бронирования столов в кафе
    </a><br/>
    <sub>
      Сервис управления бронированием мест в кафе, просмотр меню и действующих акций.  
      <br/>Стек: FastAPI, SQLAlchemy 2, Alembic, Pydantic, PostgreSQL, Celery, Redis, Flower, PyJWT, ruff, pre-commit  
      <br/>Особенности: командный проект; бронирование столов без пересечений (проверка конфликтов по времени/вместимости); JWT-аутентификация и роли (админ/персонал/клиент); фоновые задачи Celery (напоминания, авто-отмена просроченных броней), мониторинг очередей через Flower.
      <br/>Личный вклад: модули Cafes/Slots/Tables; алгоритм синхронизации менеджер↔кафе; настройка Celery/Redis/Flower; фоновые задачи (уведомления о создании/изменении бронирования, ежедневные напоминания); фабрика кастомных API-ответов.
      <br/>Web: https://bron-team4.hix-cloud.ru/docs
    </sub>
  </li>

  <li>
    <a href="https://github.com/StigTax/foodgram">
      <img width="32" height="32" src="https://img.icons8.com/arcade/64/fast-food.png" alt="foodgram"/>
      Foodgram
    </a><br/>
    <sub>
      Веб-сервис «Продуктовый помощник» 🍲, где пользователи могут публиковать свои рецепты, добавлять их в избранное, 
      подписываться на авторов и формировать список покупок.  
      <br/>Стек: Django, DRF, PostgreSQL, Docker, Nginx  
      <br/>Особенности: кастомная аутентификация, работа с изображениями в base64, генерация TXT-списка покупок, деплой на сервер, заготовка под CI/CD.
    </sub>
  </li>
  
  <li>
    <a href="https://github.com/StigTax/QRkot_spreadsheets">
      <img width="32" height="32" src="https://img.icons8.com/pin/100/cat.png" alt="cat"/>
      Благотворительный портал QR-Kot
    </a><br/>
    <sub>
      Сервис помогает волонтёрам управлять благотворительными проектами для котиков и принимать пожертвования от пользователей.  
      <br/>Стек: FastAPI, SQLAlchemy 1.4, Alembic, Pydantic, Google Sheets API, Google Drive API  
      <br/>Особенности: распределение пожертвований по принципу «первым пришёл — первым обслужен» с переносом излишка в следующий фонд; если фондов нет — средства сохраняются на балансе пользователя; отчётность и аналитика через Google Sheets с выгрузкой на Google Drive.
    </sub>
  </li>
</ul>

<h3>
  <img width="45" height="45" src="https://img.icons8.com/arcade/32/bmo.png" alt="bmo"/> PET-Project
</h3>
<ul>
  <li>
    <a href="https://github.com/StigTax/Calculations">
      <img width="32" height="32" src="https://img.icons8.com/arcade/64/numbered-list.png" alt="calc"/>
      Калькулятор НФС
    </a><br/>
    <sub>
      Небольшой калькулятор для выполнения базовых расчётов и экспериментов с Python.  
      Проект позволил закрепить работу с функциями, тестированием и базовой структурой Python-программ.
    </sub>
  </li>
</ul>
<ul>
  <li>
    <a href="https://github.com/StigTax/inflation_tracker">
      <img width="32" height="32" src="https://img.icons8.com/arcade/64/stocks.png" alt="stocks"/>
      Трекер инфляции
    </a><br/>
    <sub>
      Программа для отслеживания колебания цен на личную потребительскую карзину с выводом гистограмм. Аналитика по продукту, магазинам и категориям.
      Реализован GUI (PyQt6) и CLI интерфейс для работы с базой данных.
    </sub>
  </li>
</ul>

<h3>
  <img width="45" height="45" src="https://img.icons8.com/arcade/32/book.png" alt="book"/> Educational Projects
</h3>
<ul>
  <li>
    <a href="https://github.com/StigTax/room_reservation">
      <img width="32" height="32" src="https://img.icons8.com/arcade/64/planner.png" alt="room"/>
      Room Reservation
    </a><br/>
    <sub>
      Сервис для бронирования комнат/переговорок.  
      <br/>Стек: FastAPI, SQLAlchemy, Pydantic, Alembic, шаблоны 
      <br/>Особенности: CRUD для комнат, создание брони по датам и времени, проверка пересечений.
    </sub>
  </li>

  <li>
    <a href="https://github.com/StigTax/yacut">
      <img width="32" height="32" src="https://img.icons8.com/arcade/64/link.png" alt="yacut"/>
      YaCut — сервис сокращения ссылок
    </a><br/>
    <sub>
      Мини-сервис, который принимает длинный URL и возвращает короткий.  
      <br/>Стек: Flask, SQLAlchemy, Alembic
      <br/>Особенности: генерация коротких идентификаторов, редиректы, хранение статистики.
    </sub>
  </li>

  <li>
    <a href="https://github.com/StigTax/scrapy_parser_pep">
      <img width="32" height="32" src="https://img.icons8.com/arcade/64/source-code.png" alt="scrapy"/>
      Scrapy parser PEP
    </a><br/>
    <sub>
      Парсер для документации PEP: обходит страницы и собирает информацию по стандартам.  
      <br/>Стек: Python, Scrapy
      <br/>Особенности: сохранение отчётов в файлы (CSV/JSON), разбор структуры страниц, обработка статусов.
    </sub>
  </li>

  <li>
    <a href="https://github.com/StigTax/homework_bot">
      <img width="32" height="32" src="https://img.icons8.com/arcade/64/bot.png" alt="bot"/>
      Homework Bot
    </a><br/>
    <sub>
      Telegram-бот, который автоматически проверяет статус домашних заданий на Яндекс.Практикуме.  
      Отправляет уведомления о результатах ревью прямо в чат.  
      <br/>Стек: Python, API-запросы, long polling, logging
      <br/>Особенности: надёжная обработка ошибок API и непрерывная работа бота.
    </sub>
  </li>
  
  <li>
    <a href="https://github.com/StigTax/api_yamdb">
      <img width="32" height="32" src="https://img.icons8.com/arcade/64/people-working-together.png" alt="yamdb"/>
      YaMDb API
    </a><br/>
    <sub>
      API-сервис для отзывов и рейтингов произведений (книг, фильмов, музыки).  
      Пользователи могут оставлять отзывы, ставить оценки и комментировать.  
      <br/>Стек: Django, DRF, JWT-аутентификация, SQLite
      <br/>Особенности: командный проект, работа через pull request, разделение модулей.
    </sub>
  </li>
  
  <li>
    <a href="https://github.com/StigTax/django_sprint4-main">
      <img width="32" height="32" src="https://img.icons8.com/arcade/64/activity-history.png" alt="blogicum"/>
      Blogicum
    </a><br/>
    <sub>
      Учебный проект «Блог» - пользователи могут создавать посты, комментировать чужие записи и подписываться на авторов.  
      <br/>Стек: Django, SQLite, Bootstrap
      <br/>Особенности: регистрация и аутентификация, работа с ORM, CRUD-операции, пагинация.
    </sub>
  </li>
</ul>

---

<h3 align="center">📈 Немного статистики</h3>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=StigTax&bg_color=00000000&color=c9d1d9&line=58a6ff&point=58a6ff&hide_border=true" />
</p>

---

<p align="center">
  <a href="mailto:efremchef@yandex.ru">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://t.me/Nik_efr">
    <img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" />
  </a>
  <a href="https://github.com/StigTax">
    <img src="https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

<sub style="color: #666;">Icons by: <a href="https://icons8.com">Icons8</a></sub>
