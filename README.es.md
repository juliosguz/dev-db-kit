# dev-db-kit 🧰

Un entorno listo para desarrollo local con bases de datos reales y preconfiguradas.  
Ideal para desarrolladores que desean iniciar proyectos, probar integraciones o explorar esquemas reales de bases de datos sin complicaciones.

---

## 🚀 ¿Qué incluye este kit actualmente?

- 🐬 MySQL 8.0.42 con el dataset `classicmodels`
- 🐘 PostgreSQL 10.23 y PostgreSQL 17.5 con `classicmodels` adaptado
- Scripts `.sql` listos para importar automáticamente
- Volúmenes persistentes configurados para conservar datos entre reinicios
- Compatibilidad con herramientas como TablePlus, DBeaver, pgAdmin, etc.

---

## 🔧 Cómo usarlo

1. Clona este repositorio:

   ```bash
   git clone https://github.com/tu-usuario/dev-db-kit.git
   cd dev-db-kit
   ```

2. Asegúrate de tener Docker y Docker Compose instalados.

3. Ejecuta:

   ```bash
   docker-compose up -d
   ```

4. Conéctate a los servicios usando tus herramientas favoritas.

---

## 📦 Accesos por defecto

| Base de datos       | Puerto | Usuario   | Contraseña | Base de datos |
|---------------------|--------|-----------|-------------|----------------|
| MySQL 8.0.42        | 3306   | devuser   | devpass     | classicmodels  |
| PostgreSQL 10.23    | 5432   | devuser   | devpass     | classicmodels  |
| PostgreSQL 17.5     | 5433   | devuser   | devpass     | classicmodels  |

---

## 🛠️ En progreso

Este repositorio está en desarrollo activo. Próximamente incluirá:

- ✅ Soporte para más motores de bases de datos (MongoDB, Redis, SQLite, etc.)
- ✅ Datasets adicionales (por ahora solo se incluye `classicmodels`)
- ✅ Diagramas ER y documentación técnica de los esquemas

---

## 📘 Ejercicios SQL

Este repositorio utiliza el dataset `classicmodels`, ideal para practicar consultas SQL.  
Puedes apoyarte en los ejercicios educativos creados por **Richard T. Watson**, disponibles aquí:

- 📝 [Ejercicios – ClassicModels – Richard T. Watson](https://www.richardtwatson.com/open/Reader/ClassicModels.html)
- ✅ [Consultas de ejemplo / Respuestas](https://www.richardtwatson.com/open/private/ClassicModels.html)

---

## ⚖️ Licencias & Créditos

### Tu contenido

Todo el código propio, scripts Docker y documentación están bajo [licencia MIT](./LICENSE).

### Dataset `classicmodels`

El dataset `classicmodels` fue originalmente creado para BIRT por Actuate/Eclipse Foundation, y está licenciado bajo la **Eclipse Public License v1.0 (EPL‑1.0)**.  
Este contenido **no está cubierto por la licencia MIT** y se incluye aquí únicamente con fines educativos y de demostración.

Referencia:  
- [Eclipse BIRT Sample Database](https://eclipse-birt.github.io/birt-website/docs/template-sample-database/)

---

## 📄 Licencia

Tu código bajo MIT. El dataset `classicmodels` está bajo EPL‑1.0.

> 🌐 Idiomas disponibles: [English 🇺🇸](./README.md)
