# 👋 Hi, i am @turkprogrammer
### Senior Backend Architect | High-Load | Golang & PHP Expert | ML-Inference Systems

<p align="left">
  <img src="https://komarev.com/ghpvc/?username=turkprogrammer&label=Profile%20views&color=0e75b6&style=flat" alt="views" />
</p>

---

### 💻 Ключевая экспертиза
Более 18 лет в индустрии. Специализируюсь на проектировании отказоустойчивых, высоконагруженных систем (RPS/Latency оптимизация) и внедрении ML-моделей в продакшен-среды. 

- 🛠 **Архитектура:** Микросервисы, Event-driven (Kafka), High-Load API, Big Data.
- 🚀 **Производительность:** Профилирование, устранение бутылочных горлышек, оптимизация работы с БД.
- 🧠 **ML-Inference:** Интеграция LLM (Llama 3.3, DeepSeek) и классических моделей (Random Forest) для автоматизации бизнес-логики.

---

### 🛠 Технологический стек

#### **Backend Core**
<p align="left">
  <img src="https://skillicons.dev/icons?i=go,php,symfony,mysql,postgres,redis,mongodb,clickhouse,kafka" alt="Backend Stack" />
</p>

#### **Infrastructure & DevOps**
<p align="left">
  <img src="https://skillicons.dev/icons?i=docker,kubernetes,nginx,linux,git,githubactions" alt="Infra Stack" />
</p>

---

### 🌟 Избранные проекты и кейсы (Advertising Analytics)

Я спроектировал и реализовал архитектуру **4-х ML-сервисов** для глубокой аналитики данных:

#### **1. Geo-mapping & Normalization (Llama 3.3-70B)**
AI-маппинг городов из 5+ источников с многоуровневым файловером.
* **Результат:** Успешность маппингов **+150%** (до 35-40%), покрытие регионов **90%**, снижение стоимости API на **70%**. Обработано **3.1M+** записей.

#### **2. Bundle ID Classification (Llama + ClickHouse)**
Трехуровневая система классификации: Regex (<0.1ms) → ClickHouse Cache (~1ms) → AI Fallback (~800ms).
* **Результат:** **8x ускорение** обработки (**760-850 эд/сек**), автоматическая фильтрация веб-доменов с экономией **60-70%** токенов API.

#### **3. Domain Classification (IAB Taxonomy)**
Категоризация доменов (IAB 3.1) с Whitelist предфильтрацией (85K+ доменов без AI).
* **Результат:** Обработано **416K+** доменов, **30% прирост** производительности, **100% точность** whitelist классификации.

#### **4. Stable ID Identification (Event-driven ML)**
Самый сложный проект: Random Forest модель для предсказания ID пользователей (Kafka + ProcessManager).
* **Результат:** **92% F1-score**, сокращение дублирования пользователей на **35%**. Реализованы отказоустойчивость, многоуровневое кэширование и механизм версионирования/отката моделей без перезапуска.

---

### 🔭 Open Source
- **[LogT](https://github.com/turkprogrammer/logt)** — высокопроизводительный TUI лог-эксплорер на Go (Fuzzy search, JSON tree, 300k+ lines/sec).

---

### 📉 Статистика
<p align="left">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=turkprogrammer&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true" />
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=turkprogrammer&layout=compact&theme=tokyonight&hide=html,css,javascript" />
</p>

---

### 🔗 Связь
- 🌐 **Портфолио:** [yusupov-tech.ru](https://yusupov-tech.ru/)
- ✈️ **Telegram:** [@turanellervarolsun](https://t.me/turanellervarolsun)

---
*"Build it scale, or don't build it at all."*
