# Prerequisites

- **JDK:** 17 or 21
- **Maven:** 3.9+
- **MySQL:** 8.x

# Technologies Used

- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- Tomcat
- MySQL
- Memcached
- RabbitMQ
- Elasticsearch

# Database Setup

This project uses MySQL as the database.
A SQL dump file is provided to set up the initial schema and data.

**SQL Dump File Location:**
- `src/main/resources/db_backup.sql`

**To import the dump into your MySQL server:**

```sh
mysql -u <user_name> -p accounts < src/main/resources/db_backup.sql
```

Replace `<user_name>` with your MySQL username.
The database `accounts` should exist before importing the dump.
