# Add Modsynth Module

Add a new Modsynth module to your project.

Select the module to add:
- auth-module (Backend: JWT + OAuth2.0)
- db-module (Backend: Database abstraction)
- cache-module (Backend: Redis cache)
- ui-components (Frontend: React components)
- api-client (Frontend: Axios client)

Then install the module:

Backend (Go):
```bash
go get github.com/modsynth/{module-name}
```

Frontend (npm):
```bash
npm install @modsynth/{module-name}
```
