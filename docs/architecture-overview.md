# Smart VMS — Architecture Overview (Assessment Summary)

*Aligned with MoICT&NG Prototype Showcase architecture guidance.*

## 1. System purpose

Smart VMS digitises visitor logbooks for institutional reception and security: registration, check-in/out, host notification, reporting, and audit.

## 2. Layers

| Layer | Description |
|-------|-------------|
| **Clients** | Mobile app (reception/security); web portal (administration) |
| **Transport** | HTTPS (TLS 1.2+) |
| **Application services** | Node.js business logic, policies, notifications |
| **Identity** | Authenticated sessions, role-based access |
| **Data** | Operational store, administrative store, secured media |
| **External** | Email notifications; Government APIs planned |

## 3. User access

- Android mobile application  
- Web browser (administrators)  
- Authenticated REST APIs for approved integrations  

## 4. Security (summary)

- TLS on all client connections  
- Encryption at rest on persisted data  
- RBAC with organisation isolation  
- Audit logging of sensitive actions  
- Uganda Data Protection and Privacy Act, 2019 alignment  

## 5. Scalability

Stateless application tier; horizontal scaling; multi-premises per organisation.

## 6. Government integration (roadmap)

Planned interfaces for National Identification and shared Government platforms. Current production uses institutional workflows and standard REST integration points.

---

Full diagram and MoICT checklist: see `submission/System_Architecture.pdf`.

**Confidential — Paradigma International Limited.**
