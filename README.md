# JDBC + Hibernate — учебный проект

Учебное задание: реализация CRUD-операций над сущностью `User` с использованием JDBC и Hibernate.  
Проект показывает, как работать с чистым JDBC, а также с Hibernate SessionFactory без Spring.

## Использованные технологии

- Java 17+  
- MySQL (или MariaDB, совместимая)  
- JDBC  
- Hibernate ORM (версии, указанные в `pom.xml`)  
- Maven для сборки и управления зависимостями  

## Что умеет проект

- Создаёт таблицу `users` (если нужно)  
- Добавляет новых пользователей  
- Читает список всех пользователей  
- Удаляет пользователя по ID  
- «Чистит» таблицу или удаляет её  
- Демонстрация двух подходов: чистый JDBC и Hibernate  

##  Как запустить проект локально

1. Склонируй репозиторий:

   ```bash
   git clone https://github.com/Kilbas/PP_1_1_3-4_JDBC_Hibernate.git
   cd PP_1_1_3-4_JDBC_Hibernate
   Настрой подключение к базе: в папке src/main/resources добавте
   db.url=jdbc:mysql://localhost:3306/test
   db.username=root
   db.password=123456
   в фаил  application.properties
