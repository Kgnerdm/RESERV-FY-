# PLAN33 – Planning Critical Dependencies

This document identifies task dependencies within the Reservify project and highlights those on the critical path that directly affect the delivery timeline.

---

## 1. Task Dependency Table

| Predecessor Task              | Successor Task                  |
|-------------------------------|----------------------------------|
| T01 – Define Requirements     | T02 – Prepare Project Plan       |
| T02 – Prepare Project Plan    | T03 – Design UI Wireframes       |
| T03 – Design UI Wireframes    | T05 – Build Frontend UI          |
| T04 – Backend APIs            | T08 – Integration Testing        |
| T06 – Database Schema         | T04 – Backend API Development    |
| T05 & T04                     | T08 – Integration Testing        |
| T08 – Testing                 | T10 – Final Documentation        |

---

## 2. Critical Path Tasks

| Critical Task          | Reason for Criticality                        |
|------------------------|-----------------------------------------------|
| T01 – Requirements     | All downstream tasks rely on scoped features  |
| T03 – UI Wireframes    | Frontend development depends on visuals       |
| T04 – Backend API      | Required for integration and data ops         |
| T08 – Testing          | Final delivery blocked until complete         |

---

## 3. Dependency Risk Strategy

- Frontend and backend are developed in **parallel** to avoid delays
- Buffer time added between testing and final submission
- Team sync meetings scheduled before integration begins

---

## Summary

Identifying and planning around critical dependencies allows the Reservify team to avoid bottlenecks and prioritize work that directly impacts the timely completion of the project.
