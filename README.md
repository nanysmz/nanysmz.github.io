# nanysmz.github.io

Sitio GitHub Pages con contenido de **forensia digital** (MkDocs).

## Cómo ver el sitio localmente

1. Crea y activa un entorno virtual (recomendado):

```bash
cd /Users/sandrazilla/nanysmz.github.io
python3.12 -m venv .venv
source .venv/bin/activate
```

2. Instala dependencias:

```bash
pip install -r requirements.txt
```

3. Levanta el servidor:

```bash
mkdocs serve
```

4. Abre http://127.0.0.1:8000 en tu navegador.

## Despliegue en GitHub Pages

El sitio se despliega automáticamente al hacer push en la rama `main` usando GitHub Actions.....
