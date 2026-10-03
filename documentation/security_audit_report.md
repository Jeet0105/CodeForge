# CodeForge Security Audit & Hardening Report

## Security Measures Implemented
1. **Password Hashing**: bcryptjs with 10 salt rounds before storage.
2. **JWT Authentication**: Signed tokens with HTTP-only cookies and Authorization headers.
3. **Role-Based Access Control (RBAC)**: Middleware enforcement for Admin and Setter routes.
4. **Input Sanitization**: express-mongo-sanitize preventing NoSQL injection.
5. **HTTP Security Headers**: Helmet configuration for CSP and frameguard.
6. **Rate Limiting**: express-rate-limit on auth and submission endpoints.

### Revision Log
- 2026-09-28: Initial security checklist drafted by Harsh Abhichandani.

- 2026-09-28: Code plagiarism tokenizer and similarity threshold added by Harsh Abhichandani.

- 2026-10-03: Security audit conducted on auth endpoints by Kenil Dhola.
