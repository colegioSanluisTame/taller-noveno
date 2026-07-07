---
name: auto-deploy
description: Use cuando se edite cualquier archivo HTML, CSS o JS en el proyecto TallerNoveno. Auto-commitea y pushea a GitHub Pages automáticamente.
---

# Auto Deploy a GitHub Pages

Este proyecto (`taller-noveno`) se despliega en GitHub Pages automáticamente.

## Comportamiento

Cada vez que el usuario edite, cree o modifique archivos en este proyecto (especialmente `index.html` y cualquier `.html`, `.css`, `.js`), debes:

1. **Hacer un commit** con los cambios usando `git add -A && git commit -m "mensaje descriptivo"`
2. **Hacer push** a `origin main` usando `git push`

## Reglas

- Usar mensajes de commit descriptivos en español
- Siempre pushear después de commitear
- No preguntar al usuario si debe hacer deploy — hacerlo automáticamente
- Solo aplicar a cambios dentro de `C:\Users\San Luis\Documents\TallerNoveno`
