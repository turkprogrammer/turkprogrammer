# 👋 Привет, я @turkprogrammer
### Senior Backend Architect | High-Load Systems | Golang & PHP Expert

<p align="left">
  <img src="https://komarev.com/ghpvc/?username=turkprogrammer&label=Profile%20views&color=0e75b6&style=flat" alt="views" />
</p>

---

### 💻 Обо мне
Более **18 лет** в бэкенд-разработке. Специализируюсь на проектировании отказоустойчивых систем, оптимизации RPS/Latency и внедрении ML-моделей в высоконагруженные продакшен-среды.

- 🛠 **Main Focus:** Микросервисная архитектура, Event-driven (Kafka), Big Data (ClickHouse).
- 🧠 **ML & AI Inference:** Разработка систем на базе LLM (Llama 3.3, DeepSeek, Ollama) и классического ML (Random Forest).
- 🚀 **Performance:** Профилирование, устранение бутылочных горлышек и оптимизация работы с БД.

---

### 🛠 Технологический стек

#### **Backend, Data & ML**
<p align="left">
  <img src="https://skillicons.dev/icons?i=go,php,symfony,mysql,postgres,redis,mongodb,clickhouse,kafka,ai" alt="Backend & ML Stack" />
</p>

#### **Infrastructure**
<p align="left">
  <img src="https://skillicons.dev/icons?i=docker,kubernetes,nginx,linux,git,githubactions" alt="Infra Stack" />
</p>

---

### 🌟 Избранные кейсы (High-Load & ML)
* **Stable ID Service:** Идентификация пользователей (**Random Forest** + Kafka). Результат: **92% F1-score**, сокращение дубликатов на **35%**.
* **Geo-mapping AI:** Маппинг 3.1M+ записей через **Llama 3.3 / Ollama**. Результат: **+150%** точности, снижение затрат на API на **70%**.
* **Bundle ID Classifier:** Трехуровневая фильтрация (Regex → Cache → AI Fallback). Результат: **8x ускорение** обработки (**850 эд/сек**).

---

### 🛠 System Utilities & TUI (Golang)
* **[SQL-Top](https://github.com/turkprogrammer/sql-top)** — **"The htop for Databases"**. Профайлер PostgreSQL/MySQL/ClickHouse в реальном времени. Безопасный EXPLAIN, анализ wait events и дельта-подсветка новых запросов.
* **[LogT](https://github.com/turkprogrammer/logt)** — **"The Swiss Army Knife for Logs"**. Высокопроизводительный эксплорер логов (**300k+ строк/сек**). Легковесная альтернатива `lnav` с мгновенной JSON Path фильтрацией.
* **[mt](https://github.com/turkprogrammer/mt)** — **"The Go Runtime Tuner"**. Тюнер параметров Go runtime в реальном времени. Управление `GOGC`, `GOMEMLIMIT`, `GOMAXPROCS`, `debug.SetGCPercent` и `SetPanicOnFault` для тонкой оптимизации сервиса.

---

### 🔭 Open Source & AI Projects
* **[Fraud Detection Engine](https://turkprogrammer.github.io/fraud-engine-docs/)** — **Pro-grade Anti-fraud for High-load**. API для real-time скоринга транзакций в финтехе.
    * **ML Engine:** Собственная реализация **Random Forest на чистом Go** (без внешних зависимостей).
    * **Performance:** Итеративный обход деревьев (stack overflow protection) и строгий bounds checking.
    * **Optimization:** LRU-кэширование результатов с поддержкой **hot-reload** весов через `fsnotify`.
* **[E-commerce Lite](https://github.com/turkprogrammer/E-commerce-Lite)** — Современный магазин на **Symfony 7.2** с гексагональной архитектурой. Чистый Domain-слой, Use Case-ориентированный Application-слой и гибкие инфраструктурные адаптеры.
* **[RAG System](https://github.com/turkprogrammer/RAG-)** — Реализация Retrieval-Augmented Generation для работы с локальными базами знаний и LLM (Ollama/OpenAI).
* **[Task Estimator](https://github.com/turkprogrammer/task-estimator)** — Сервис оценки трудозатрат на базе **Random Forest**, обучающийся на исторических данных Jira/Git.

---

### 🔗 Связь
- 🌐 **Портфолио:** [yusupov-tech.ru](https://yusupov-tech.ru/)
- ✈️ **Telegram:** [@turanellervarolsun](https://t.me/turanellervarolsun)

---
*"Build it scale, or don't build it at all."*
