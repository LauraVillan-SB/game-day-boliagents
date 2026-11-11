# GameDay Boliagents

Repositorio del equipo para el GameDay (AWS). Reto pendiente de asignación.

## Equipo

| Integrante | Rol / Área |
|------------|-----------|
| Laura Villan | _por definir_ |
| _por definir_ | _por definir_ |
| _por definir_ | _por definir_ |
| _por definir_ | _por definir_ |

## Estructura

| Carpeta | Contenido |
|---------|-----------|
| `docs/challenge/` | Enunciado del reto, reglas y criterios de evaluación |
| `docs/architecture/` | Diagramas y diseño de la solución |
| `docs/decisions/` | Decisiones técnicas (ADRs) |
| `agents/` | Definición de agentes (prompts, tools, configuración) |
| `src/` | Código de la solución |
| `infra/` | Infraestructura como código (IaC) |
| `tests/` | Pruebas |
| `scripts/` | Utilidades y automatizaciones |
| `data/samples/` | Datos de ejemplo (sin PII ni secretos) |
| `notebooks/` | Exploración y pruebas rápidas |
| `.github/workflows/` | Pipelines CI/CD |

## Flujo de trabajo

1. Cada persona trabaja en su rama: `feature/<nombre>-<tema>`.
2. No se hace push directo a `main`; se usa Pull Request con al menos una revisión.
3. Antes de cada PR: `git pull --rebase origin main`.
4. Nunca subir credenciales. Usar `.env` local (ignorado) y `.env.example` como referencia.

## Primeros pasos

```powershell
git clone https://github.com/LauraVillan-SB/game-day-boliagents.git
cd game-day-boliagents
Copy-Item .env.example .env
```
