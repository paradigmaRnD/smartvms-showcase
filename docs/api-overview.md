# Smart VMS — API Overview (High Level)

This document describes **scope only**. Endpoint specifications, authentication secrets, and proprietary verification logic are **not** published in this showcase repository.

## API style

- REST over HTTPS  
- JSON request/response bodies  
- Session or token-based authentication on protected routes  

## Functional areas (exposed to authorised clients)

| Area | Purpose |
|------|---------|
| **Organisation** | Tenant profile, premises, configuration |
| **Users & roles** | Staff accounts, role assignment |
| **Visitors** | Visitor profiles and visit history |
| **Visits** | Check-in, check-out, visit status |
| **Invitations** | Pre-registration and host workflows |
| **Reports** | Aggregated visitor activity (authorised roles) |
| **Audit** | Activity log retrieval (administrative roles) |

## Not included here

- OpenAPI/Swagger files with production URLs  
- API keys, master keys, or database connection strings  
- Internal verification pipeline or media-processing implementation  

## Contact for integration discussions

Paradigma International Limited — ivanmusaja@protonmail.com
