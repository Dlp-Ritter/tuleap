# tuleap-qa-workflow

Entorno local de [Tuleap](https://www.tuleap.org/) levantado con Docker Compose,
usado para la gestión de proyectos, tickets y trazabilidad de mi portafolio QA/DevSecOps.

> Aquí documento el board de tareas, el plan de pruebas y la trazabilidad
> entre requisitos, bugs y tests de mis otros repos.

---

## Stack

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Tuleap](https://img.shields.io/badge/Tuleap-FA6800?style=flat-square&logo=tuleap&logoColor=white)

---

## Levantar el entorno

```bash
git clone https://github.com/Dlp-Ritter/tuleap.git
cd tuleap-qa-workflow
docker compose up -d
```

Accede en `http://localhost` (o el puerto definido en `docker-compose.yml`).

> **Nota**: las carpetas `db-data/` y `tuleap-data/` son volúmenes generados
> por Docker en tiempo de ejecución y están excluidas del repo vía `.gitignore`.

---

## Board

_(Screenshot del board con tareas/tickets)_

## Plan de pruebas

_(Link o resumen del plan de testing — ver `TEST-PLAN.md` en `cypress-e2e-suite`)_

## Trazabilidad

| Requisito | Test E2E | Ticket |
|---|---|---|
| Login de usuario | `cypress/e2e/auth/login.cy.js` | TASK-XX |
| Catálogo de productos | `cypress/e2e/products/catalog.cy.js` | TASK-XX |
| Checkout | `cypress/e2e/checkout/checkout.cy.js` | TASK-XX |

---

## Cómo se integra en mi portafolio

- [`cypress-e2e`](https://github.com/Dlp-Ritter/cypress-e2e) — los tests referenciados en la tabla de trazabilidad.

---

## Contacto

<p align="left">
<a href="https://www.linkedin.com/in/duglas-pop-guitz-490ab72b0">
<img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="mailto:duglas_leonel_1704@protonmail.com">
<img src="https://img.shields.io/badge/Email-8B89CC?style=flat-square&logo=protonmail&logoColor=white" alt="Email"/>
</a>
</p>
