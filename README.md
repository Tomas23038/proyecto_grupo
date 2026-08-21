# Proyecto Grupo

Repositorio de trabajo en equipo para el Laboratorio 1 de Principios de Desarrollo de Software (Pontificia Universidad Javeriana). El proyecto practica flujo de colaboración con Git y GitHub: ramas por integrante, pull requests, resolución de conflictos y comparación entre merge y rebase.

## Integrantes

- [Nombre completo 1] — [usuario de GitHub]
- [Nombre completo 2] — [usuario de GitHub]
- [Nombre completo 3] — [usuario de GitHub]

## Enlace al repositorio

[https://github.com/USUARIO/proyecto_grupo](https://github.com/USUARIO/proyecto_grupo)

## Comandos utilizados

| Comando | Propósito |
|---|---|
| `git clone URL` | Descargar una copia completa del repositorio remoto |
| `git config --global user.name "..."` | Configurar el nombre con el que aparecen los commits |
| `git config --global user.email "..."` | Configurar el correo con el que aparecen los commits |
| `git status` | Ver qué archivos cambiaron y en qué estado están |
| `git add .` | Preparar los cambios para el próximo commit |
| `git commit -m "..."` | Guardar los cambios preparados en el historial local |
| `git push origin rama` | Subir los commits locales a GitHub |
| `git pull origin main` | Traer y aplicar los cambios que otros subieron a main |
| `git checkout -b rama` | Crear una rama nueva y moverse a ella |
| `git checkout rama` | Moverse a una rama que ya existe |
| `git branch --show-current` | Ver en qué rama se está parado |
| `git merge main` | Integrar los cambios de otra rama en la actual |
| `git rebase main` | Reaplicar los commits de la rama actual sobre la punta de main |
| `git log --oneline --graph --all --decorate` | Mostrar el historial en forma de árbol |
| `gh auth login` | Autenticar el computador con GitHub |

## Flujo de trabajo

1. Cada integrante clona el repositorio y crea su propia rama (`feature-nombre`).
2. Se hacen commits en la rama personal y se suben a GitHub.
3. Se abre un pull request hacia `main` y otro integrante lo revisa y aprueba.
4. Los conflictos de merge se resuelven manualmente antes de integrar.
5. Se compara el historial resultante de merge contra el de rebase (ver informe).

## Estructura del proyecto

```
proyecto_grupo/
├── src/
├── docs/
├── tests/
└── index.html
```
