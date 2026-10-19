# Programar con agentes de IA: Claude Code

Un codespace es un buen sitio para practicar con un agente: es un entorno aislado que puedes borrar cuando quieras.

```bash
curl -fsSL https://claude.ai/install.sh -o install.sh
less install.sh         # lee el script antes de ejecutarlo (q para salir)
bash install.sh
exec $SHELL -l          # recarga el PATH
claude --version
cd /workspaces/bancada-labs/programar-con-claude-code
mkdir mi-tarjeta && cd mi-tarjeta && git init
claude
```

Al iniciar sesión, si el navegador no vuelve solo a la terminal, copia el código que te muestra la web y pégalo donde la terminal dice `Paste code here if prompted`.

`jq` ya está instalado para el laboratorio de hooks.
