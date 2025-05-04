# PLANNING.md

> **Purpose:** This document defines the high-level vision, architecture, tech stack, constraints, and standards for this project. It encodes all project rules and best practices to guide development and AI agents (Cursor, Task Master, Context7).

---

## 1. Project Vision & Scope
- **Summary:**
- **Key Outcomes:**
- **Non-Goals:**

## 2. Architecture & Design
- **Architectural Style:** (e.g., Layered, Hexagonal, Microservices)
- **Design Patterns:** (e.g., Strategy, Factory, Observer, Facade)
- **Justification:**
- **Screaming Architecture:** [ ] Folder structure reflects domain, not frameworks
- **SOLID Principles:** [ ] Applied throughout
- **API Contracts:** [ ] Internal (interfaces) [ ] External (REST/OpenAPI)
- **File Size Limit:** [ ] No file >500 lines (split as needed)
- **Module Organization:** [ ] Grouped by feature/responsibility

## 3. Tech Stack
- **Languages:**
- **Frameworks/Libraries:**
- **Data Validation:** pydantic
- **Testing:** (e.g., pytest, Jest)
- **CI/CD:**
- **Other Tools:**

## 4. Naming Conventions & Patterns
- **File/Folder Naming:**
- **Import Style:** [ ] Relative within packages unless absolute is required
- **Consistent Patterns:**

## 5. Documentation Standards
- [ ] Why-focused inline comments
- [ ] Docstrings for all functions/classes/modules
- [ ] Update README.md, PLANNING.md, TASK.md, ADRs as needed

## 6. Testing & Testability
- [ ] Unit and integration tests for all code
- [ ] Edge cases, concurrency, invalid inputs
- [ ] Refactor for testability (DI, small units)
- [ ] TDD when requested

## 7. Project Hygiene & Automation
- [ ] Audit dependencies (unused, CVEs, upgrades)
- [ ] Enforce linters/formatters
- [ ] Update Dockerfile, CI/CD, tool configs

## 8. Cross-Cutting Concerns
- [ ] Security (OWASP Top 10)
- [ ] Performance (algorithms, memory, I/O)
- [ ] Observability (JSON logging, Prometheus metrics, tracing)

## 9. Integration Guidance
- **Task Master:** Use TASK.md for all task tracking. Sync with Task Master as source of truth.
- **Context7:** Reference library docs and context as needed for implementation.

---

> **Update this file as architecture, tech stack, or standards evolve.** 