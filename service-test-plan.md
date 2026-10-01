# Lab 25 — Service Test Plan

| Case | Setup | Expect |
| --- | --- | --- |
| get CUS-1001 | repository returns Amina (ACTIVE) | DTO returned, no exception |
| duplicate create | repository reports existing ID | IllegalStateException / conflict, no write |
| get CUS-9999 | repository returns empty | NotFoundException |
| create new | repository empty for new ID; valid DTO | new customer persisted; DTO returned |

## Spring Boot required for unit test?
No — pure unit tests use plain JUnit + Mockito; no Spring context needed.

## Scope
Pre-lab only.
