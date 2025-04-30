# MC32 – Critical Dependency Management

This document monitors the project's most sensitive dependencies and evaluates how the Reservify team managed these links during the execution phase to avoid bottlenecks.

---

## 1. Monitored Dependencies

| Dependency Type         | Source Task      | Dependent Task    | Risk Level | Notes                                     |
|--------------------------|------------------|--------------------|-------------|--------------------------------------------|
| UI Design Dependency     | T03 (Wireframes) | T05 (Frontend)     | High        | Resolved on time to enable dev             |
| API Readiness            | T04 (API)        | T08 (Integration)  | High        | API structure finalized 2 days before test |
| DB Schema Finalization   | T06              | T04 (API)          | Medium      | DB structure locked early                  |
| Documentation Sync       | PLAN docs        | Submission Phase   | Medium      | Planned via shared format templates        |

---

## 2. Weekly Review of Critical Paths

| Week | Reviewed Dependencies                  | Adjustments Made                          |
|------|----------------------------------------|--------------------------------------------|
| W1   | Planning → Design tasks                | Re-ordered PLAN23 milestone dates         |
| W2   | Backend ↔ Frontend integration         | Coordinated schema + payload formats      |
| W3   | Final docs + presentation prep         | Buffer days inserted in task board        |

---

## 3. Actions to Prevent Blockers

- Predefined GitHub Issues for interlinked tasks
- Meeting notes included blocking task IDs
- Buffer time in PLAN23 + team sync loops

---

## Summary

The Reservify team identified and proactively tracked critical task dependencies. Management actions were applied early to prevent delays and ensure on-time milestone delivery.
