# Данил Яценко — Fullstack-разработчик

FastAPI / Django / React / TypeScript / PostgreSQL / Docker / PyTorch / LLM

Разрабатываю backend и fullstack-приложения с акцентом на архитектуру, разделение ответственности и качество кода. Интересуюсь ML и локальными LLM.

---

## Проекты

### 🔐 RBAC Auth Service

Система аутентификации и авторизации: JWT access/refresh, RBAC через нормализованную таблицу правил, rate limiting на Redis, soft delete. 193 теста, покрытие 76%.

`Python 3.12` `FastAPI` `SQLAlchemy 2.0` `PostgreSQL` `Redis` `Alembic` `Docker` `Ruff`

🔗 Код: https://github.com/ITouch228/fastapi-rbac-auth

---

### � Realtime Messenger

Мессенджер с WebSocket-доставкой, JWT RS256 в httpOnly-cookies, загрузкой файлов и сжатием изображений в WebP. Слоистая архитектура: routes → services → dao.

`Python 3.12` `FastAPI` `WebSocket` `PostgreSQL` `SQLAlchemy` `Pillow` `Jinja2` `Docker`

🔗 Код: https://github.com/ITouch228/fastapi-realtime-messenger

---

### 🗺 My Places

Fullstack-приложение: личная карта мест с чеками и позициями. Leaflet + геокодер Nominatim, агрегаты (средняя цена/рейтинг), поиск по радиусу. Покрытие бэкенда 83%.

**Backend:** `Django 6.1` `DRF` `SimpleJWT` `geopy`
**Frontend:** `React 18` `TypeScript` `Vite` `TanStack Query` `React Leaflet`
**Инфра:** `Docker` `Ruff` `mypy` `Vitest`

🔗 Код: https://github.com/ITouch228/django-react-myplaces

---

### 📝 Django CRUD Blog

Блог с аутентификацией по email, кастомной моделью пользователя, разделением черновик/опубликован, контролем авторства, пагинацией. 36 тестов.

`Python 3.12` `Django 6.0` `Bootstrap 5` `python-dotenv` `Ruff` `pytest`

🔗 Код: https://github.com/ITouch228/django-crud-blog

---

### 🧠 Tic-Tac-Toe RL

Обучение агента методом Monte Carlo Q-Learning с self-play и аугментацией симметриями ×8. 100% ничьих против идеального минимакса — математический оптимум.

`Python 3.12` `PyTorch 2.x` `NumPy` `Matplotlib` `pytest` `Ruff`

🔗 Код: https://github.com/ITouch228/pytorch-tictactoe-rl

---

### 🎙 Jarvis — голосовой ассистент

Ассистент с распознаванием речи, синтезом, GUI-чатом и маршрутизацией команд через локальные модели Ollama. Работает полностью офлайн.

`Python` `Ollama` `SpeechRecognition` `gTTS / pyttsx3` `tkinter` `pyautogui`

🔗 Код: https://github.com/ITouch228/ITouchHIOS

---

### 🏛 Booking — система бронирования помещений

SPA с ролевой системой, кастомными хуками и тестированием бизнес-логики.

`React` `TypeScript` `Vite` `Vitest` `React Testing Library`

🔗 Код: https://github.com/ITouch228/Booking-Pet-Project

---

## Технологии

**Backend:** Python, FastAPI, Django, DRF, SQLAlchemy 2.0, Pydantic, Alembic, Celery

**Базы данных:** PostgreSQL, Redis, SQLite

**Frontend:** React, TypeScript, Vite, TanStack Query, React Router

**Аутентификация:** JWT (HS256 / RS256), RBAC, httpOnly-cookies, bcrypt

**Realtime:** WebSocket, SSE

**ML / LLM:** PyTorch, NumPy, Ollama, STT/TTS

**Инфраструктура:** Docker, docker-compose, Makefile, Nginx

**Качество:** Ruff, mypy, pytest, Vitest, coverage

---

## Контакты

Telegram: @ITouch06
Email: danilyatsenko200612354678@gmail.com
