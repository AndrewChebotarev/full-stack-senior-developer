# 🧠 The Ultimate Senior/Staff Engineer Roadmap

> **Версия 4.0** | Автор: [Твое Имя] | Стаж: 6 лет (C++/C#) | Цель: Senior/Staff Engineer

Этот репозиторий — мой личный «арсенал» для подготовки к собеседованиям в топовые IT-компании (Яндекс, VK, Ozon, Tinkoff, Western Gigacorp). Здесь собраны все темы, которые я прохожу, чтобы закрыть пробелы в знаниях — от битов и байтов до управления распределенными системами и людьми.

**Статус:** 🔄 В процессе постоянного обновления.
**Срок подготовки:** 18 месяцев.

---

## 📖 Легенда
- 🔥 **Критично:** Без этого тебя не возьмут на Senior.
- ⭐ **Важно:** Показывает глубину твоего мышления.
- 🚀 **Будущее:** Технологии, которые будут востребованы через 3-5 лет.

---

## 📚 Оглавление (12 Доменов)

| № | Домен | Статус | Ссылка |
|---|-------|--------|--------|
| 0 | 🛠️ Инструменты (Git, Linux, Bash) | 🔄 В процессе | [Перейти](#0-инструменты-git-linux-bash) |
| 1 | 🧠 Алгоритмы и структуры данных | 🔄 В процессе | [Перейти](#1-алгоритмы-и-структуры-данных) |
| 2 | ⚡ Память, железо и производительность | ⏳ Запланировано | [Перейти](#2-память-железо-и-производительность) |
| 3 | 🚀 C++ (от 0 до эксперта) | ⏳ Запланировано | [Перейти](#3-c-от-0-до-эксперта) |
| 4 | 🔷 C# / .NET (от 0 до CLR) | ⏳ Запланировано | [Перейти](#4-c--net-от-0-до-clr) |
| 5 | 🗄️ Базы данных (SQL → NoSQL) | ⏳ Запланировано | [Перейти](#5-базы-данных-sql--nosql) |
| 6 | 🌐 Сети и распределенные системы | ⏳ Запланировано | [Перейти](#6-сети-и-распределенные-системы) |
| 7 | ☸️ DevOps, K8s и инфраструктура | ⏳ Запланировано | [Перейти](#7-devops-k8s-и-инфраструктура) |
| 8 | 🎨 Фронтенд (React + TypeScript) | ⏳ Запланировано | [Перейти](#8-фронтенд-react--typescript) |
| 9 | 🤖 AI и нейросети (инженерный уровень) | ⏳ Запланировано | [Перейти](#9-ai-и-нейросети-инженерный-уровень) |
| 10 | 👑 Техническое лидерство | ⏳ Запланировано | [Перейти](#10-техническое-лидерство) |
| 11 | 🐹 Go (супер-перспективный язык) | ⏳ Запланировано | [Перейти](#11-go-супер-перспективный-язык) |

---

## 0 🛠️ Инструменты (Git, Linux, Bash)
*Без этого ты не напишешь ни строчки кода в команде.*

- [ ] **Git:** От `init` до `reflog`. Внутреннее устройство (Blob, Tree, Commit). Git Flow / Trunk-Based. [Шпаргалка](./tools/git.md)
- [ ] **Linux:** Структура FS, процессы, systemd, сети (`netstat`, `ss`). [Шпаргалка](./tools/linux.md)
- [ ] **Bash:** Скрипты, `grep`, `awk`, `sed`. Автоматизация деплоя. [Шпаргалка](./tools/bash.md)

---

## 1 🧠 Алгоритмы и структуры данных
*Сердце любого собеседования. Реализация на C++ и C#.*

- [ ] **Массивы и строки:** Бинарный поиск, два указателя, скользящее окно. [Код](./algorithms/arrays/)
- [ ] **Связные списки:** Реализация, разворот, циклы (Флойд). [Код](./algorithms/linked-lists/)
- [ ] **Стек/Очередь:** Реализация, Min Stack, очередь на двух стеках. [Код](./algorithms/stacks-queues/)
- [ ] **Хеш-таблицы:** Реализация с цепочками и открытой адресацией. [Код](./algorithms/hash-tables/)
- [ ] **Деревья:** BST, AVL, обходы, поиск LCA. [Код](./algorithms/trees/)
- [ ] **Графы:** BFS, DFS, Дейкстра, Топологическая сортировка, Raft (упрощенно). [Код](./algorithms/graphs/)
- [ ] **Динамическое программирование:** Рюкзак, LCS, редакционное расстояние. [Код](./algorithms/dp/)

---

## 2 ⚡ Память, железо и производительность
*Здесь проваливается 80% кандидатов на собеседовании.*

- [ ] **Стек, куча, статическая память:** Различия, выравнивание (padding). [Конспект](./performance/memory-basics.md)
- [ ] **Представление данных:** IEEE 754, Endianness. [Конспект](./performance/data-representation.md)
- [ ] **Кэш и виртуальная память:** Кэш-линии, False Sharing, TLB, Page Fault. [Бенчмарк](./performance/cache-benchmark/)
- [ ] **Аллокаторы:** Пул памяти, Arena. [Код](./performance/allocators/)
- [ ] **Многопоточность:** Мьютексы, спинлоки, Lock-free структуры (Treiber stack). [Код](./performance/concurrency/)
- [ ] **Профилирование:** `perf`, `dotnet-trace`, анализ дампов. [Инструменты](./performance/profiling/)

---

## 3 🚀 C++ (от 0 до эксперта)
*Мой основной язык.*

- [ ] **C++11/14:** Move-семантика, умные указатели, лямбды. [Код](./cpp/modern-cpp/)
- [ ] **C++17/20:** `std::optional`, `std::variant`, Concepts, Coroutines. [Код](./cpp/cpp20/)
- [ ] **Шаблоны:** SFINAE, CRTP, Variadic templates. [Код](./cpp/templates/)
- [ ] **STL под капотом:** Как устроен `std::vector`, `std::string` (SSO). [Конспект](./cpp/stl-internals.md)
- [ ] **Библиотеки:** Qt6 (GUI), Boost.Asio (сеть), GoogleTest (тесты). [Проекты](./cpp/libraries/)

---

## 4 🔷 C# / .NET (от 0 до CLR)
*Мой второй язык.*

- [ ] **Основы:** Value vs Reference, LINQ, делегаты. [Код](./csharp/basics/)
- [ ] **Асинхронность:** `async`/`await`, State Machine, `IAsyncEnumerable`. [Код](./csharp/async/)
- [ ] **CLR:** GC (поколения, LOH), `IDisposable`, `WeakReference`. [Конспект](./csharp/clr-internals.md)
- [ ] **ASP.NET Core:** Minimal API, Middleware, DI, gRPC. [Проект](./csharp/aspnetcore/)
- [ ] **Avalonia UI:** XAML, MVVM, стилизация. [Проект](./csharp/avalonia/)

---

## 5 🗄️ Базы данных (SQL → NoSQL)
*Без них ты не архитектор.*

- [ ] **SQL:** Сложные запросы, оконные функции, CTE. [Запросы](./databases/sql-queries.sql)
- [ ] **Индексы:** B-Tree, покрывающие, частичные. [Конспект](./databases/indexes.md)
- [ ] **Оптимизация:** `EXPLAIN`, статистика, планы выполнения. [Кейсы](./databases/optimization/)
- [ ] **PostgreSQL Internals:** MVCC, WAL, изоляция, блокировки. [Конспект](./databases/postgres-internals.md)
- [ ] **NoSQL:** MongoDB, Redis (кеширование, лидерборды). [Проекты](./databases/nosql/)
- [ ] **Распределенные БД:** Шардирование, репликация, Vector DB (Milvus). [Конспект](./databases/distributed-dbs.md)

---

## 6 🌐 Сети и распределенные системы
*Вершина архитектуры.*

- [ ] **Основы сетей:** TCP/UDP, HTTP/2/3, WebSockets. [Конспект](./networks/basics.md)
- [ ] **API:** REST, gRPC (Protocol Buffers). [Код](./networks/grpc/)
- [ ] **Очереди:** RabbitMQ, Kafka (партиции, оффсеты). [Проекты](./networks/message-queues/)
- [ ] **Консенсус:** 2PC, Saga, Raft (реализация). [Код](./networks/raft/)
- [ ] **Согласованность:** CAP, PACELC, Vector Clocks. [Конспект](./networks/consistency.md)
- [ ] **Стриминг:** Kafka Streams, Flink. [Проекты](./networks/streaming/)

---

## 7 ☸️ DevOps, K8s и инфраструктура
*Senior обязан уметь поднять свой сервис.*

- [ ] **Docker:** Multi-stage, healthcheck, Compose. [Dockerfile](./devops/docker/)
- [ ] **Kubernetes:** Pod, Deployment, Service, Ingress, Helm. [Манифесты](./devops/kubernetes/)
- [ ] **K8s (продвинутый):** StatefulSet, Operators, Istio. [Конспект](./devops/k8s-advanced.md)
- [ ] **CI/CD:** GitLab CI / GitHub Actions, ArgoCD (GitOps). [Конфиги](./devops/ci-cd/)
- [ ] **Observability:** Prometheus, Grafana, OpenTelemetry, Jaeger. [Конфиги](./devops/observability/)

---

## 8 🎨 Фронтенд (React + TypeScript)
*Чтобы быть Fullstack-инженером.*

- [ ] **HTML/CSS:** Flexbox, Grid, медиазапросы. [Код](./frontend/html-css/)
- [ ] **JavaScript:** ES6, замыкания, Event Loop, промисы. [Код](./frontend/javascript/)
- [ ] **TypeScript:** Types, Generics, Utility Types. [Код](./frontend/typescript/)
- [ ] **React:** Хуки, Context, React Router, Redux Toolkit. [Код](./frontend/react/)
- [ ] **React Query:** Кеширование, оптимистичные обновления. [Код](./frontend/react-query/)
- [ ] **Next.js:** SSR, SSG, ISR, App Router. [Проекты](./frontend/nextjs/)

---

## 9 🤖 AI и нейросети (инженерный уровень)
*Будущее, которое уже наступило.*

- [ ] **Математика:** Линейная алгебра, производные, вероятность. [Конспект](./ai/math-basics.md)
- [ ] **Классический ML:** Линейная регрессия, Random Forest, метрики. [Код](./ai/ml-basics/)
- [ ] **Deep Learning:** MLP, CNN, RNN, LSTM. [Код (PyTorch)](./ai/deep-learning/)
- [ ] **Transformer:** Self-Attention, BERT, GPT. [Код](./ai/transformers/)
- [ ] **LLM:** Prompt Engineering, Fine-tuning (LoRA). [Проекты](./ai/llm/)
- [ ] **RAG:** LangChain, Vector Databases (Pinecone/Milvus). [Проекты](./ai/rag/)
- [ ] **MLOps:** ONNX, Triton, MLflow. [Проекты](./ai/mlops/)

---

## 10 👑 Техническое лидерство
*Как превратиться из Senior в Staff.*

- [ ] **Code Review:** Модель SBI, как давать фидбек. [Конспект](./leadership/code-review.md)
- [ ] **Процессы:** Scrum, Kanban, оценка задач. [Конспект](./leadership/processes.md)
- [ ] **Найм:** Как проводить собеседования, составлять тестовые. [Чек-лист](./leadership/hiring.md)
- [ ] **Стратегия:** NFR (SLA/SLO), Roadmap, ADR, RFC. [Шаблоны](./leadership/strategy/)
- [ ] **Управление:** 1-on-1, мотивация, Blameless Post-Mortems. [Конспект](./leadership/people-management.md)

---

## 11 🐹 Go (супер-перспективный язык)
*Язык облачной инфраструктуры.*

- [ ] **Основы:** Структуры, интерфейсы, ошибки. [Код](./go/basics/)
- [ ] **Concurrency:** Goroutines, Channels, `select`, `sync`. [Код](./go/concurrency/)
- [ ] **HTTP и gRPC:** REST API, middleware, gRPC-сервисы. [Код](./go/web/)
- [ ] **Базы данных:** `database/sql`, GORM, Redis, Kafka. [Код](./go/databases/)
- [ ] **Инструменты:** `go mod`, `go test`, `pprof`. [Конспект](./go/tools/)
- [ ] **Интерналы:** Планировщик (GMP), GC, устройство `chan` и `slice`. [Конспект](./go/internals.md)

---

## 📅 План обучения (Checklist)

- [ ] **Месяц 1-2:** Инструменты + Алгоритмы (база)
- [ ] **Месяц 3-4:** Алгоритмы (сложные) + Память
- [ ] **Месяц 5-6:** C++ (современный)
- [ ] **Месяц 7-8:** C# + Базы данных (база)
- [ ] **Месяц 9-10:** Сети + Распределенные системы
- [ ] **Месяц 11-12:** DevOps + Фронтенд
- [ ] **Месяц 13-14:** AI + Лидерство
- [ ] **Месяц 15-16:** Go + Углубление
- [ ] **Месяц 17-18:** Повторение + Системный дизайн

---

## 📚 Библиотека (Книги)

- [x] "Introduction to Algorithms" (Кормен)
- [ ] "Effective Modern C++" (Скотт Майерс)
- [ ] "CLR via C#" (Джеффри Рихтер)
- [ ] "Designing Data-Intensive Applications" (Мартин Клеппман)
- [ ] "The Staff Engineer's Path" (Tanya Reilly)
- [ ] "The Go Programming Language" (Donovan, Kernighan)
- [ ] "Site Reliability Engineering" (Google)

---

## 🚀 Как использовать этот репозиторий?

1.  **Клонируй** репозиторий.
2.  Проходи по доменам в том порядке, который указан в плане.
3.  Для каждой темы внутри папки создавай файл с конспектом (`*.md`) и папку с кодом.
4.  Отмечай прогресс в чек-листах выше (заменяй `[ ]` на `[x]`).
5.  **Повторяй!** Возвращайся к пройденным темам через месяц, чтобы информация не выветривалась.

---

## 🤝 Вклад

Этот репозиторий создан для личного использования, но если ты нашел ошибку или хочешь предложить улучшение — создавай Issue или Pull Request. Будем становиться сеньорами вместе!

---

**⭐ Если этот репозиторий помогает тебе — поставь звезду, чтобы не потерять его!**
