# dev-db-kit 🧰

A ready-to-use local development environment with real, preconfigured databases.  
Ideal for developers who want to start projects, test integrations, or explore realistic database schemas without setup hassle.

---

## 🚀 What’s included (currently)

- 🐬 MySQL 8.0.42 with the `classicmodels` dataset
- 🐘 PostgreSQL 10.23 and PostgreSQL 17.5 with adapted `classicmodels`
- Ready-to-import `.sql` scripts
- Persistent volumes to keep data between container restarts
- Compatible with tools like TablePlus, DBeaver, pgAdmin, etc.

---

## 🔧 How to use

1. Clone this repository:

   ```bash
   git clone https://github.com/your-user/dev-db-kit.git
   cd dev-db-kit
   ```

2. Make sure you have Docker and Docker Compose installed.

3. Start the containers:

   ```bash
   docker-compose up -d
   ```

4. Connect using your favorite database client.

---

## 📦 Default access

| Database            | Port | User     | Password | Database       |
|---------------------|------|----------|----------|----------------|
| MySQL 8.0.42        | 3306 | devuser  | devpass  | classicmodels  |
| PostgreSQL 10.23    | 5432 | devuser  | devpass  | classicmodels  |
| PostgreSQL 17.5     | 5433 | devuser  | devpass  | classicmodels  |

---

## 🛠️ In progress

This project is under active development. Upcoming features:

- ✅ Support for additional database engines (MongoDB, Redis, SQLite, etc.)
- ✅ Additional datasets (currently only `classicmodels` is included)
- ✅ Entity-Relationship diagrams and technical documentation of schemas

---

## 📘 SQL Exercises

This project includes the `classicmodels` dataset, ideal for practicing SQL.  
You can explore educational exercises by **Richard T. Watson**:

- 📝 [Exercises – ClassicModels – Richard T. Watson](https://www.richardtwatson.com/open/Reader/ClassicModels.html)
- ✅ [Sample queries / answers](https://www.richardtwatson.com/open/private/ClassicModels.html)

---

## ⚖️ Licenses & Credits

### Your content

All Docker setup, scripts, and documentation in this repo are licensed under [MIT](./LICENSE).

### `classicmodels` dataset

The `classicmodels` dataset was originally created for BIRT by Actuate/Eclipse Foundation and is licensed under the **Eclipse Public License v1.0 (EPL‑1.0)**.  
It is included here solely for educational and demonstration purposes and **is not covered by the MIT license**.

Reference:  
- [Eclipse BIRT Sample Database](https://eclipse-birt.github.io/birt-website/docs/template-sample-database/)

---

## 📄 License

Your code is under MIT. The `classicmodels` dataset remains under EPL‑1.0.

> 🌐 Available languages: [Español 🇪🇸](./README.es.md)
