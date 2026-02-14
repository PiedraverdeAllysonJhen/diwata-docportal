# Account Creation (FR 1.0)

[Project Homepage](../project-homepage.md) > Account Creation

---

## Functional Description

This module provides a registration interface for new users (Students, Staff, and Admins) to create a **BookItStudent** account. It validates university credentials and stores user preferences for the roommate-matching and library systems.

---

## Use Case Scenario

| Actor(s) | Guest, Student, Admin |
|----------|-----------------------|
| Goal | To securely register a new user and assign appropriate access levels within the BookItStudent system.|
| Precondition | User has access to the application URL and the authentication service is available. |
| Main Flow | User opens screen → Selects Sign up → Fills details and account type → System validates input → Account created → Verification link sent. |
| Alternative Flow | **Duplicate account:** Email already registered → Error message displayed.<br><br> **Missing/invalid fields:** System highlights required fields and blocks submission.|
| Post Condition | User account is successfully registered in the database. |

---

<p align="center">© 2026 <a href="#">Enera</a></p>