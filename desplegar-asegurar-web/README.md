# Desplegar y asegurar una web

Crea el proyecto del laboratorio 1 en `/workspaces`, fuera de este repositorio (así `clinica-demo` tiene su propio Git y no queda un repositorio dentro de otro):

```bash
cd /workspaces
npm create astro@latest clinica-demo
cd clinica-demo && npm run dev -- --host
```

Codespaces te ofrecerá abrir el puerto 4321. En el laboratorio 1 subirás `clinica-demo` a un repositorio propio en GitHub: este repositorio es solo el entorno.

El acceso a GitHub que trae el codespace solo vale para `bancada-labs`. Para subir `clinica-demo` a tu repositorio, inicia sesión con tu cuenta (en cada terminal nueva, repite `unset GITHUB_TOKEN`):

```bash
unset GITHUB_TOKEN
gh auth login
gh auth setup-git
```

Borra el codespace (o ejecuta `gh auth logout`) cuando termines.
