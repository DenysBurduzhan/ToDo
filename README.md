# 📝 ToDo Application

Простое веб-приложение для управления задачами (ToDo List), написанное на Java с использованием Spring Framework, JSP и MySQL. Сборка и запуск через Docker.

## 📦 Стек технологий

- Java 17+
- Spring Web MVC
- JSP / JSTL
- MySQL 8
- Hibernate (если используется)
- Docker + Docker Compose
- Apache Tomcat

---

## 🚀 Как запустить

### 1. Клонируйте репозиторий

```bash
git clone https://github.com/DenysBurduzhan/ToDo.git
cd todo-app
mvn clean package
Запустите с помощью Docker Compose
docker-compose up --build