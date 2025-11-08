# biologia-examen

Proyecto Vite + React + Tailwind preconfigurado para desplegar en GitHub Pages.

1. Publicar en: https://Edyu6.github.io/biologia-examen/
2. Rama fuente: `main`
3. Despliegue automático a: `gh-pages` (vía GitHub Actions)
4. Contiene: código React + Vite + Tailwind + workflow preconfigurado

## Comandos rápidos (copiar y pegar)

```bash
git init
git add .
git commit -m "primer commit"
git branch -M main
git remote add origin https://github.com/Edyu6/biologia-examen.git
git push -u origin main
```

Después de push, el workflow en `.github/workflows/deploy.yml` construirá y publicará automáticamente el contenido de `dist` en `gh-pages`.  

Nota: El workflow usa `peaceiris/actions-gh-pages`. Para que despliegue sin problemas, puedes configurar una clave de despliegue (deploy key) o usar el token por defecto. Consulta la Guía 23 para más detalles.
