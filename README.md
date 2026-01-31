# Docker Monitoring Service / Сервис мониторинга на Docker

Dockerized monitoring stack with **Prometheus**, **Grafana**, **Node Exporter**, and **cAdvisor**.  
Provides real-time system and container metrics, beautiful dashboards, and resource monitoring.  
Идеально подходит для DevOps, администрирования и анализа производительности приложений.

---

## Features / Возможности

- 📊 Real-time system & container metrics / Метрики системы и контейнеров в реальном времени  
- 📈 Beautiful dashboards with Grafana / Красивые дашборды в Grafana  
- ⚡ Monitor CPU, RAM, disk, and Docker containers / Контроль CPU, RAM, дисков и Docker-контейнеров  
- 🔄 Easy setup with Docker Compose / Простая настройка через Docker Compose  
- ✅ Ideal for DevOps and performance analysis / Отлично для DevOps и анализа производительности  

---

## Services Included / Включенные сервисы

| Service | Port | Description / Описание |
|---------|------|------------------------|
| Prometheus | 9090 | Metrics collection & storage / Сбор и хранение метрик |
| Grafana | 3000 | Visualization dashboards / Дашборды визуализации |
| Node Exporter | 9100 | System metrics exporter / Экспорт системных метрик |
| cAdvisor | 8080 | Container metrics & resource usage / Метрики контейнеров и ресурсов |

---

## Prerequisites / Предварительные требования

- [Docker](https://www.docker.com/)  
- [Docker Compose](https://docs.docker.com/compose/)

---

## Getting Started / Начало работы

1. Clone the repository / Клонируем репозиторий:  
```bash
[https] git clone https://github.com/Crow613/Monitoring.git 
[ssh] git@github.com:Crow613/Monitoring.git
[GitHub CLI] gh repo clone Crow613/Monitoring
cd Monitoring

```
[start]  docker compose up -d
[down] docker compose down

| Сервис     | URL     local           |                                 | Первый вход в Grafana |
| ---------- | ----------------------- |                                 | ----------------------|
| Prometheus | [http://localhost:9090] |                                 | Логин:  | admin       |
| Grafana    | [http://localhost:3000] |                                 | Пароль: | admin       |
| cAdvisor   | [http://localhost:8080] |




