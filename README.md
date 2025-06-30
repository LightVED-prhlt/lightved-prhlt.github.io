# lightved-prhlt.github.io
Pagina oficial del Proyecto LightVED financiado en la convocatoria PROMETEO de la Generalitat Valenciana

# Uso

1. Crea un entorno conda e instala `mkdocs-material` con `pip`
    
```bash
conda create -n mkdocs python
conda activate mkdocs
pip install mkdocs-material
```

2. Clona el repositorio y entra en la carpeta del proyecto
    
```bash
git clone https://github.com/LightVED-prhlt/lightved-prhlt.github.io
cd lightved-prhlt.github.io
```

3. Ejecuta el servidor de desarrollo
    
```bash
mkdocs serve
```

4. Abre tu navegador en `http://localhost:8000/`

# Despliegue del sitio web en GitHub Pages

Para desplegar el sitio web, asegúrate de que estás en la rama `main` y ejecuta:

```bash
mkdocs gh-deploy --force
```