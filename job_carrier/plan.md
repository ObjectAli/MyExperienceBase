# Cтруктурированный план подготовки к собеседованию Java разработчика

## 📋 План подготовки к собеседованию Java Developer 

### 🎯 **Неделя 1: Базы данных и SQL** :white_check_mark:
- SQL: SELECT - порядок выполнения операторов :white_check_mark:
- PostgreSQL: типы таблиц, ограничения, индексы (типы, когда использовать) :white_check_mark:
- View vs Materialized View, автообновление материализованных представлений :white_check_mark:
- Функции vs Процедуры в PostgreSQL :white_check_mark:
- Транзакции: ACID, уровни изоляции (особенности в PostgreSQL) :white_check_mark:
- Аномалии сериализации, блокировки :white_check_mark:
- Нормальные формы БД (1NF, 2NF, 3NF) :white_check_mark:

### 🛠️ **Неделя 2: Java Core & Collections**
- Интерфейсы vs классы, функциональные и маркерные интерфейсы :fast_forward:
- Исключения: иерархия, try-catch-finally, try-with-resources
- Рефлексия, аннотации (retention, target)
- Stream API: методы, особенности toList() vs Collectors.toList()
- Коллекции: ArrayList vs LinkedList, HashMap (устройство, capacity, rehashing)
- ConcurrentHashMap, ConcurrentModificationException

### ⚡ **Недея 3: Многопоточность & JVM**
- Память JVM: стек, куча, metaspace, native memory
- Настройки памяти: Xms, Xmx, рекомендации
- Многопоточность: Runnable, synchronized, wait/notify
- ThreadLocal, Fork-Join, атомарные операции
- CAS (Compare-And-Swap), Atomic классы
- ExecutorService, Future, CompletableFuture
- Happens-before, пулы потоков, виртуальные потоки
- ReentrantLock

### 🌱 **Неделя 4: Spring Framework & Testing**
- Spring Boot: что такое, преимущества
- Beans: определение, скоупы, жизненный цикл
- @RefreshScope, Spring AOP, типы proxy
- Spring Data JPA: EntityManager, @Transactional, propagation
- Retry механизм в Spring
- Spring Security: принципы работы, паттерн Chain of Responsibility
- Spring Cloud: Eureka, Gateway, Config

### 🧪 **Неделя 5: Тестирование & Инструменты**
- JUnit 5: основы, аннотации
- Mockito: моки, стабы, верификация
- Test Containers, WireMock
- Интеграционные тесты vs unit тесты
- Maven: этапы сборки, дерево зависимостей (mvn dependency:tree)
- Maven: отличие compile от install

### ☁️ **Неделя 6: Микросервисы & Инфраструктура**
- Микросервисная архитектура: принципы
- Docker: основы, Dockerfile, docker-compose
- Kubernetes/OpenShift: pods, services, deployments
- Spring Cloud: сервис discovery, configuration, routing

### 📡 **Неделя 7: Веб & API & Брокеры сообщений**
- REST API: принципы, HTTP методы, статусы
- Отличие HTTP от HTTPS
- Альтернативы REST: GraphQL, gRPC, SOAP
- Аутентификация: Basic, OAuth2, JWT, refresh tokens
- Трассировка запросов в микросервисах
- Kafka: topics, partitions, consumer groups
- Гарантии доставки, порядок сообщений
- ACK modes, обработка ошибок

### 🗃️ **Неделя 8: NoSQL & Дополнительные технологии**
- MongoDB: документная модель, запросы
- Elasticsearch: индексы, поиск
- Redis: кэширование, структуры данных
- RabbitMQ/Kafka: сравнение, use cases
- Reactive programming: Project Reactor, RxJava

### 🔧 **Неделя 9: Инструменты & Производительность**
- Git: rebase vs merge, cherry-pick
- Hibernate: аннотации, Lazy vs Eager loading
- Нативные запросы в Hibernate
- Профилирование: JProfiler, async-profiler
- Garbage Collection: типы, настройки, ZGC в Java 21

## 📚 **Полезные ресурсы:**
- Java Documentation
- Spring Framework Guides
- PostgreSQL Official Documentation
- "Effective Java" Joshua Bloch
- "Designing Data-Intensive Applications" Martin Kleppmann
