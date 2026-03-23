# Contenido Materia Organica CRM

Microfrontend Vite/React para el formulario de Contenido Materia Organica consumido por `iframe` desde `crm-geofal`.

## Dominio productivo

- `https://cont.mat.organicas.geofal.com.pe`

## Variables

- `VITE_API_URL=https://api.geofal.com.pe`
- `VITE_CRM_LOGIN_URL=https://crm.geofal.com.pe/login`
- `VITE_MODULE_SLUG=cont-mat-organica`

## Desarrollo

```bash
npm install
npm run dev
```

## Deploy Coolify

El `Dockerfile` ya compila este repo en la raiz `/` con `VITE_MODULE_SLUG=cont-mat-organica`, listo para `https://cont.mat.organicas.geofal.com.pe`.
