# PLAN34 – Project Environment and Tools

This document describes the technical environment, tools, and maintenance setup used throughout the Reservify project.

---

## 1. Tools and Platforms Used

| Tool/Platform        | Purpose                                      | Used By                   |
|----------------------|----------------------------------------------|----------------------------|
| GitHub               | Version control, collaboration, traceability | All team members           |
| VS Code              | Development IDE                              | All developers             |
| PostgreSQL           | Database management                          | Backend Developer          |
| Draw.io              | UI Wireframing                               | UI Designer (Ahmet Hilmi)  |
| Markdown (.md)       | Documentation format                         | Entire team                |
| Python + Script      | Bulk issue creation                          | Project Manager            |
| GitHub Project Board | Sprint-based task tracking                   | Entire team                |

---

## 2. Project Folder & Repo Structure

- `/docs`: Word and PDF deliverables
- `/plans`: PLAN11–PLAN34 markdown files
- `/code`: Frontend and backend subfolders
- `/tests`: Manual and integration test cases
- `/config`: Database, deployment scripts

---

## 3. Setup & Maintenance Needs

| Component                  | Setup Guide                    | Maintained By             |
|----------------------------|----------------------------------|----------------------------|
| PostgreSQL                 | `config/postgres.md`             | Ahmet Hilmi Büber          |
| Dev Environment (VS Code)  | `docs/dev-setup.md`              | All members                |
| GitHub Workflow            | `.github/workflows`              | Kağan Erdem                |
| API Routing + Auth         | `backend/routes/`                | Recep Buğra Sarıkaya       |

---

## 4. Health and Safety / Legal Considerations

- No sensitive user data used — only mock entries
- Database and system not deployed publicly (academic use only)
- All work versioned to prevent loss

---

## Summary

The Reservify development environment is modular, well-structured, and supports reliable collaboration through standard open-source tools. Documentation, testing, and traceability are fully embedded into the chosen ecosystem.
