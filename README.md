# 👋 Baltabek - AI/ML Engineer & Full-Stack Developer

[![GitHub followers](https://img.shields.io/github/followers/baltabekpro?style=social)](https://github.com/baltabekpro)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://linkedin.com/in/your-profile)
[![Email](https://img.shields.io/badge/Email-Contact-red)](mailto:your.email@example.com)

> Специализируюсь на разработке AI-агентов, RAG-систем и интеллектуальных чат-ботов с акцентом на production-ready решения для корпоративного сектора

---

## 🚀 Ключевые компетенции

**AI/ML Engineering:**
- 🤖 RAG (Retrieval-Augmented Generation) системы
- 🧠 LLM интеграция (Gemini, Llama, GPT)
- 📊 Vector databases (Qdrant, Pinecone)
- 🔍 Semantic search & embeddings
- 🎯 Multi-tenant AI architectures

**Backend Development:**
- ⚡ FastAPI, Flask, Django
- 🗄️ PostgreSQL, SQLite, Redis
- 🐰 Message queues (RabbitMQ)
- 🐳 Docker, Kubernetes
- 📈 Prometheus, Grafana

**Telegram Bots & NLU:**
- 💬 Aiogram, python-telegram-bot
- 🗣️ Natural Language Understanding
- 🔄 State machines & conversation flows
- 📱 Telegram Mini Apps

---

## 🏆 Основные проекты

### 🤖 AI-RAG Core - Multi-Tenant RAG Platform для Казахстана
[![GitHub](https://img.shields.io/badge/GitHub-ai--rag--core-181717?logo=github)](https://github.com/baltabekpro/ai-rag-core)
![Status](https://img.shields.io/badge/Status-Production-brightgreen)

**Корпоративная платформа для умного поиска по базе знаний с продвинутой аналитикой**

**Технологии:** Python 3.11+, FastAPI, LangChain, Qdrant, PostgreSQL, Redis, Gemini 2.0 Flash, Llama 3.1 70B

**Ключевые возможности:**
- 🏢 **Multi-Tenant Architecture** - изолированные конфигурации для каждого отдела
- 🎯 **Adaptive RAG Pipeline** - 3 уровня сложности (SIMPLE/MEDIUM/COMPLEX)
- 🔍 **Hybrid Search** - семантический + keyword поиск с reranking
- 🤖 **Dual LLM Strategy** - Gemini (dev) + Llama (prod)
- 🛡️ **Query-Level ACL** - гранулярный контроль доступа
- 🔒 **DLP Service** - обнаружение и редакция PII
- 📊 **Full Observability** - Prometheus + Grafana + ELK + Jaeger
- ⚡ **HPA/VPA Autoscaling** - от 100 до 10,000+ пользователей

**Достижения:**
- 26/45 задач завершено (58% прогресса)
- <1s latency для SIMPLE запросов
- 85% cache hit rate
- 99.9% uptime цель

**Архитектура:**
```
7 микросервисов: Query → Orchestration (LangGraph) → RAG/LLM/Tools
                    ↓
Infrastructure: PostgreSQL + Redis + Qdrant + RabbitMQ
                    ↓
Observability: Prometheus + Grafana + ELK + Jaeger
```

[📖 Полная документация](https://github.com/baltabekpro/ai-rag-core) | [🚀 Quick Start](https://github.com/baltabekpro/ai-rag-core/blob/main/QUICKSTART-ONBOARDING.md)

---

### 💬 RAG Onboard Chat - Система онбординга на базе RAG
[![GitHub](https://img.shields.io/badge/GitHub-rag--onboard--chat-181717?logo=github)](https://github.com/baltabekpro/rag-onboard-chat)
![Status](https://img.shields.io/badge/Status-Active-blue)

**Интеллектуальный помощник для адаптации новых сотрудников с RAG-поиском**

**Технологии:** Python, FastAPI, Qdrant, LangChain, Gemini API

**Особенности:**
- 📚 Автоматическая индексация корпоративной документации
- 🔍 Semantic search по базе знаний компании
- 💡 Контекстные ответы на вопросы новичков
- 📊 Аналитика популярных запросов

---

### 🤖 Tele2 Bot - RAG Chatbot для телеком компании
[![GitHub](https://img.shields.io/badge/GitHub-tele2--bot-181717?logo=github)](https://github.com/baltabekpro/tele2-bot)
![Status](https://img.shields.io/badge/Status-Production%20Ready-brightgreen)

**Интеллектуальный чат-бот для Tele2 Казахстан с RAG системой и админ-панелью**

**Технологии:** Python, FastAPI, Telegram Bot API, Qdrant, PostgreSQL, Gemini 2.5 Flash

**Ключевые возможности:**
- 🔄 **Раздельная архитектура данных** - информация + инструкции
- 🎯 **Умная переформулировка запросов** с указанием пути в данных
- 🔍 **Итеративный поиск** - до 3 шагов для получения полного контекста
- 🛠️ **Выполнение команд** - интеграция с биллинг системой
- 📊 **Real-time админ-панель** - мониторинг AI агента через WebSocket
- ⚖️ **Приоритизация обращений** - автоматическая маршрутизация

**Архитектура данных:**
```
информация/                 инструкция/
├── тарифы/                ├── диагностика_биллинга/
├── услуги/                ├── диагностика_интернета/
└── роуминг/               └── диагностика_звонков/
```

**Метрики:**
- FCR (First Contact Resolution) tracking
- CSAT monitoring
- Escalation rate analytics

[📖 Документация](https://github.com/baltabekpro/tele2-bot)

---

### 🏬 Merch Store - E-commerce платформа
[![GitHub](https://img.shields.io/badge/GitHub-Merch--Store-181717?logo=github)](https://github.com/baltabekpro/Merch-Store)

**Full-stack магазин мерча с интеграцией платежных систем**

**Технологии:** Django, PostgreSQL, Redis, Stripe API, Bootstrap

**Функционал:**
- 🛒 Корзина и система заказов
- 💳 Интеграция платежных систем
- 📦 Управление товарами и категориями
- 👤 Система аутентификации
- 📱 Responsive design

---

### 📍 GeoApp - 24/7 Location Tracking
[![GitHub](https://img.shields.io/badge/GitHub-geo__app-181717?logo=github)](https://github.com/baltabekpro/geo_app)

**Android приложение для непрерывного отслеживания геолокации**

**Технологии:** Kotlin, Android SDK, MapBox, Room DB, Retrofit, Heroku (backend)

**Особенности:**
- 📍 Continuous location tracking 24/7
- 🔋 Adaptive tracking - умное энергосбережение
- 🗺️ MapBox integration с визуализацией маршрутов
- 📡 Real-time синхронизация с сервером
- 💾 Offline поддержка с локальным кешированием

**Оптимизация:**
- Целевое устройство: Xiaomi Redmi Note 11 Pro
- Battery optimization: adaptive intervals
- Background service с минимальным потреблением ресурсов

---

### 💰 Finance AI - Умный финансовый помощник
[![GitHub](https://img.shields.io/badge/GitHub-Finance--ai-181717?logo=github)](https://github.com/baltabekpro/Finance-ai)

**Telegram-бот с NLU для управления личными финансами**

**Технологии:** Python, Aiogram, FastAPI, SQLite, Gemini API, APScheduler

**Возможности:**
- 🗣️ **Natural Language Understanding** - общение обычной речью
- 💸 Учёт доходов/расходов с auto-категоризацией
- 🏦 Управление кредитами с напоминаниями
- 🎯 Цели накопления с планированием
- 📊 Дневные и месячные отчёты
- 🔔 Smart уведомления о платежах

**NLU парсинг:**
```python
"Получил зарплату 180к" → Income(amount=180000, category='salary')
"Купил продукты за 15к" → Expense(amount=15000, category='food')
"Цель накопить на iPhone 500к" → Goal(amount=500000, item='iPhone')
```

**Локализация:** Казахстан (тенге, Asia/Almaty timezone)

---

### 🤖 WB Auto - Автоматизация Wildberries
[![GitHub](https://img.shields.io/badge/GitHub-wb__auto-181717?logo=github)](https://github.com/baltabekpro/wb_auto)

**Автоматизация процессов для маркетплейса Wildberries**

**Технологии:** Python, Selenium, WB API, PostgreSQL

**Функционал:**
- 📦 Автоматическое управление товарами
- 💰 Мониторинг цен и остатков
- 📊 Аналитика продаж
- 🔄 Синхронизация с API

---

### 🎓 IITU Bot - Университетский бот
[![GitHub](https://img.shields.io/badge/GitHub-iitu__bot-181717?logo=github)](https://github.com/baltabekpro/iitu_bot)

**Telegram-бот для студентов IITU с интеграцией университетских систем**

**Технологии:** Python, Aiogram, PostgreSQL

---

### 🗄️ AI Simulator Backend
[![GitHub](https://img.shields.io/badge/GitHub-aisimulatorbackend-181717?logo=github)](https://github.com/nikitalvovich/aisimulatorbackend)
![Status](https://img.shields.io/badge/Status-Production-brightgreen)

**Backend для AI симулятора взаимодействия с персонажами**

**Технологии:** Python, FastAPI, PostgreSQL, Redis, Docker, MinIO, OpenRewrite

**Архитектура:**
```
FastAPI Backend
├── AI Персонажи (RAG + LLM)
├── Admin Panel (управление данными)
├── PostgreSQL (основная БД)
├── Redis (кеширование)
└── Monitoring (Prometheus + Grafana + Alertmanager)
```

**Ключевые функции:**
- 🤖 Общение с AI-персонажами через RAG
- 👥 Multi-user система с персонализацией
- 📊 Performance анализ и оптимизация
- 🔄 Система деактивации аккаунтов (30 дней)
- 📱 iOS подписки (Apple Server Notifications)
- 🎨 Генерация изображений (Google Imagen)
- 🌐 Vue 3 frontend

**DevOps:**
- Docker Compose (sandbox + production)
- CI/CD pipeline (GitHub Actions)
- Automated testing + coverage reports
- Database migrations (Alembic)

---

### 🗄️ AI Simulator DB Infrastructure
[![GitHub](https://img.shields.io/badge/GitHub-aisimulator__db-181717?logo=github)](https://github.com/baltabekpro/aisimulator_db)

**Отдельная инфраструктура базы данных для AI Simulator**

**Технологии:** PostgreSQL 15, Redis 7, Docker, Prometheus, Grafana

**Компоненты:**
- 🗄️ PostgreSQL 15 - основное хранилище
- ⚡ Redis 7 - кеширование и сессии
- 📊 Monitoring Stack - Prometheus + Grafana + Exporters
- 💾 Automated backups - ежедневные с ротацией

**Особенности:**
- 🔒 SSL/TLS шифрование
- 🔐 Сетевая изоляция через Docker networks
- 📈 Real-time метрики производительности
- 🔄 Автоматическое резервное копирование

---

### 📅 DayPilot - Calendar & Scheduling
[![GitHub](https://img.shields.io/badge/GitHub-DayPilot-181717?logo=github)](https://github.com/baltabekpro/DayPilot)

**Система планирования и управления календарями**

**Технологии:** JavaScript, DayPilot Library, REST API

---

## 💼 Технологический стек

### Backend
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)

### AI/ML
![LangChain](https://img.shields.io/badge/LangChain-121212?style=flat)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-663399?style=flat)
![Gemini](https://img.shields.io/badge/Google_Gemini-4285F4?style=flat&logo=google&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)

### Databases
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-24386C?style=flat)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=flat&logo=sqlite&logoColor=white)

### DevOps & Infrastructure
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Heroku](https://img.shields.io/badge/Heroku-430098?style=flat&logo=heroku&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)

### Monitoring
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![ELK](https://img.shields.io/badge/ELK_Stack-005571?style=flat&logo=elastic&logoColor=white)
![Jaeger](https://img.shields.io/badge/Jaeger-60D0E4?style=flat)

### Mobile
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat&logo=android&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-0095D5?style=flat&logo=kotlin&logoColor=white)

### Frontend
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat&logo=vue.js&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)

---

## 📊 GitHub статистика

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=baltabekpro&show_icons=true&theme=radical&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=baltabekpro&layout=compact&theme=radical&hide_border=true)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=baltabekpro&theme=radical&hide_border=true)

</div>

---

## 🎯 Специализация

### RAG Systems Architecture
- **Multi-tenant configurations** - от simple FAQ до complex legal
- **Hybrid search** - semantic + keyword + reranking
- **Adaptive pipelines** - 3 уровня сложности с разными latency targets
- **Query reformulation** - итеративное уточнение с data path tracking
- **Command execution** - интеграция с внешними API для диагностики

### Production-Ready AI
- **LLM cost optimization** - dual strategy (cheap dev + powerful prod)
- **Observability** - distributed tracing, metrics, logging
- **Security** - ACL, DLP, PII detection/redaction
- **Scalability** - HPA/VPA, circuit breakers, rate limiting
- **Reliability** - fault tolerance, graceful degradation

### Telegram Bots
- **NLU integration** - естественное общение без команд
- **State machines** - сложные conversation flows
- **Background tasks** - scheduled notifications, reminders
- **Admin panels** - real-time monitoring через WebSocket

---

## 🎓 Образование и сертификаты

- 🎓 **Bachelor's Degree in Computer Science** - IITU (International IT University)
- 📜 **AI/ML Specialization** - Online courses (Coursera, DeepLearning.AI)
- 🏆 **Cloud & DevOps** - Kubernetes, Docker certification track

---

## 📫 Контакты

<div align="center">

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your.email@example.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/your-profile)
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/your_username)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/baltabekpro)

</div>

---

## 💡 Интересные факты

- 🚀 **26 проектов** в production за последние 2 года
- 🤖 **Специализация**: RAG-системы для корпоративного сектора
- 🌍 **Фокус**: Решения для рынка Казахстана и СНГ
- ⚡ **Любимый стек**: Python + FastAPI + LangChain + Qdrant
- 📈 **KPI**: Uptime >99.9%, Response time p95 <5s, FCR >95%

---

## 🌟 Что я могу сделать для вашего проекта

✅ **RAG-системы с нуля** - от архитектуры до production deployment  
✅ **Telegram боты** - с NLU и интеграцией внешних API  
✅ **AI-агенты** - multi-step reasoning, tool use, ReAct patterns  
✅ **Backend API** - FastAPI с автоматической документацией  
✅ **DevOps** - Docker, Kubernetes, CI/CD, мониторинг  
✅ **Консультации** - архитектурные решения для AI проектов  

---

<div align="center">

### 🚀 Открыт для интересных проектов и сотрудничества!

**Если вам нужен опытный AI/ML инженер для production-ready решений - пишите!**

⭐ **Не забудьте поставить звезду репозиториям, если они были полезны!** ⭐

</div>

---

<div align="center">
<sub>Последнее обновление: 16 ноября 2025 г.</sub>
</div>
