<div align="center">

#

### Full-Stack Developer · Backend · DevOps · Infrastructure

**6+ лет практического опыта в разработке, автоматизации и эксплуатации IT-систем**

[![GitHub](https://img.shields.io/badge/GitHub-raz0rxgod-181717?style=for-the-badge&logo=github)](https://github.com/raz0rxgod)
[![TypeScript](https://img.shields.io/badge/TypeScript-Expert-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](#tech-stack)
[![Python](https://img.shields.io/badge/Python-Backend-3776AB?style=for-the-badge&logo=python&logoColor=white)](#tech-stack)
[![Docker](https://img.shields.io/badge/Docker-Production-2496ED?style=for-the-badge&logo=docker&logoColor=white)](#devops--infrastructure)

</div>

---

## 👋 About

Я **Full-Stack разработчик** с опытом разработки веб-приложений, серверной инфраструктуры и автоматизации.

Работаю на стыке **Backend / Frontend / DevOps**, поэтому рассматриваю продукт целиком: от проектирования архитектуры и структуры базы данных до контейнеризации, reverse proxy, мониторинга и развёртывания в production.

Основной фокус — создавать системы, которые не только работают локально, но и могут быть **нормально развернуты, поддержаны и масштабированы**.

> **Code → Architecture → Infrastructure → Production**

### Что я умею

- проектировать и разрабатывать backend-системы и REST API;
- создавать современные web-интерфейсы;
- проектировать структуры PostgreSQL и оптимизировать SQL;
- разрабатывать сервисы с JWT-аутентификацией и разграничением ролей;
- контейнеризировать приложения с Docker / Docker Compose;
- настраивать Nginx, HTTPS и production-окружение;
- автоматизировать рутинные и инфраструктурные задачи;
- работать с Linux / Windows Server;
- диагностировать проблемы на уровне приложения, базы данных и инфраструктуры;
- поддерживать существующие системы и постепенно модернизировать legacy-код.

---

## 🧰 Tech Stack

### Backend

`Python` `Django` `Django REST Framework` `Flask` `FastAPI`  
`Node.js` `NestJS` `PHP` `Laravel` `Symfony`  
`REST API` `GraphQL` `asyncio` `JWT` `OAuth`

### Frontend

`TypeScript` `JavaScript ES6+` `React` `Next.js` `Vue.js`  
`HTML5` `CSS3` `Sass/SCSS` `Tailwind CSS` `Bootstrap`  
`Vite` `Webpack` `Figma`

### Databases

`PostgreSQL` `MySQL` `MariaDB` `MS SQL`  
`Redis` `MongoDB`

Работаю с:

- проектированием схем данных;
- миграциями;
- индексами;
- транзакциями;
- оптимизацией запросов;
- `EXPLAIN ANALYZE`;
- резервным копированием и восстановлением;
- репликацией PostgreSQL;
- ORM.

### DevOps / Infrastructure

`Docker` `Docker Compose` `Docker Swarm`  
`Nginx` `Apache` `Gunicorn` `uWSGI`  
`GitHub Actions` `GitLab CI` `Jenkins`  
`Linux` `Ubuntu` `Debian` `CentOS` `Rocky Linux`  
`Windows Server` `systemd` `cron` `Bash` `PowerShell`  
`Prometheus` `Grafana` `Zabbix` `Netdata`

### Networking & Security

`TCP/IP` `NAT` `VLAN` `VPN`  
`OpenVPN` `WireGuard`  
`SSL/TLS` `Let's Encrypt`  
`Fail2ban` `UFW` `iptables`  
`OWASP Top 10`

### Virtualization / Cloud

`KVM/QEMU` `Proxmox` `VMware` `Hyper-V`  
`AWS` `Google Cloud` `VPS`  
`Terraform` `Ansible`

---

## 🚀 Selected Projects

### 👻 GhostMarket

**Full-stack e-commerce platform**

Production-oriented интернет-магазин с каталогом, фильтрацией, корзиной, заказами, избранным, личным кабинетом и административной панелью.

**Stack:**

`Next.js 15` · `React 19` · `TypeScript` · `NestJS` · `Prisma` · `PostgreSQL` · `Redis` · `MinIO` · `Docker Compose` · `Nginx`

**Ключевые части:**

- JWT authentication + refresh tokens;
- RBAC с ролями `ADMIN / MANAGER / EDITOR / CUSTOMER`;
- каталог с категориями, брендами и атрибутами;
- корзина и оформление заказа;
- загрузка и обработка изображений через Multer + Sharp;
- административная панель;
- PostgreSQL + Prisma;
- Redis;
- контейнеризация инфраструктуры;
- reverse proxy через Nginx;
- отдельные frontend / backend / infrastructure layers.

**Repository:**  
https://github.com/raz0rxgod/ghostmarket

---

### 🔐 Rutoken Login Form

Интеграция авторизации с использованием **Рутокен** и аппаратной криптографии.

Проект демонстрирует работу с аппаратным ключевым носителем и построение формы аутентификации вокруг криптографического устройства.

**Stack:**

`Python` · `Rutoken` · `Cryptography` · `Authentication`

**Repository:**  
https://github.com/raz0rxgod/rutoken-login-form

---

## 🏗️ Engineering Approach

В разработке придерживаюсь нескольких принципов:

### 01 — Архитектура прежде кода

Перед реализацией определяю границы компонентов, API-контракты, структуру данных и точки интеграции.

### 02 — Production-ready с самого начала

Учитываю конфигурацию окружения, логирование, обработку ошибок, безопасность, Docker и процесс развёртывания ещё на этапе разработки.

### 03 — Автоматизация

Повторяющиеся операции должны выполняться автоматически: сборка, миграции, деплой, резервное копирование, обслуживание и мониторинг.

### 04 — Безопасность

Учитываю принцип минимальных привилегий, безопасное хранение секретов, HTTPS, контроль доступа, валидацию входных данных и типовые угрозы OWASP.

### 05 — Наблюдаемость

Для production-систем важен не только uptime, но и возможность быстро понять, **почему система работает неправильно**.

---

## 🐳 Typical Production Architecture

```text
                         ┌─────────────────────┐
                         │       Client        │
                         │ Browser / Mobile    │
                         └──────────┬──────────┘
                                    │
                                    ▼
                         ┌─────────────────────┐
                         │       Nginx         │
                         │ Reverse Proxy / TLS  │
                         └──────────┬──────────┘
                                    │
                     ┌──────────────┴──────────────┐
                     │                             │
                     ▼                             ▼
             ┌───────────────┐             ┌───────────────┐
             │    Frontend   │             │    Backend    │
             │ Next.js/React │             │ NestJS/Python │
             └───────────────┘             └───────┬───────┘
                                                   │
                            ┌──────────────────────┼──────────────────────┐
                            │                      │                      │
                            ▼                      ▼                      ▼
                     ┌────────────┐        ┌────────────┐        ┌────────────┐
                     │ PostgreSQL │        │   Redis    │        │  S3/MinIO  │
                     └────────────┘        └────────────┘        └────────────┘
```

---

## ⚙️ Development Workflow

```text
Idea
  ↓
Architecture
  ↓
API / Database Design
  ↓
Implementation
  ↓
Tests
  ↓
Docker
  ↓
CI/CD
  ↓
Deployment
  ↓
Monitoring
  ↓
Maintenance & Optimization
```

---

## 🎓 Education

**Академия ФСО России**  
Специальность: **«Инфокоммуникационные технологии и системы связи»**

Высшее образование, 2026.

---

## 📌 Currently

Сейчас развиваюсь в направлении **production-grade Full-Stack разработки**, уделяя особое внимание:

- распределённым и модульным backend-системам;
- PostgreSQL и оптимизации работы с данными;
- Docker и инфраструктуре;
- безопасности приложений;
- CI/CD;
- масштабируемой архитектуре;
- observability и эксплуатации production-систем.

---

## 🤝 Contact

Если вы хотите обсудить разработку проекта, архитектуру или техническую задачу:

**GitHub:**  
https://github.com/raz0rxgod

---

<div align="center">

### Build systems that are reliable, maintainable and production-ready.

</div>
