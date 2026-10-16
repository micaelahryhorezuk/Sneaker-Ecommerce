# Convenciones de Git

## Ramas
- `main` siempre estable. Nadie sube directo a `main`.
- Una rama por tarea: `tipo/ID-descripcion`
  Ejemplo: `feature/T06.1-proyecto-frontend`
- Tipos: `feature`, `fix`, `docs`, `chore`.

## Commits
- Formato: `tipo: descripción corta en minúscula`
  Ejemplo: `feat: agregar formulario de registro`
- Tipos: `feat`, `fix`, `docs`, `chore`, `refactor`, `test`.
- Commits chicos y frecuentes.

## Pull Requests
- Cada rama se une a `main` mediante un Pull Request.
- La otra integrante lo revisa antes de aprobarlo.
- En la descripción se escribe `Closes #N` (N = número del issue).

## Rutina
- `git pull` antes de empezar a trabajar.
- Nunca subir `.env` ni claves.