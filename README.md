# Reformat Image AIOHTTP
Pagina de ejemplo usando AIOHTMl de python con funciones concurrentes

## Ejecutar servidor
El **backend** y el **frontend** son levantados por el mismo archivo `server.py` en la carpeta root del repositorio

El archivo `server.py` depende de las librerias
- `aiohttp`


## Referencias
# concurrente_aiohtml
Pagina de ejemplo usando AIOHTMl de python con funciones concurrentes

## Ejecutar servidor
El **backend** y el **frontend** son levantados por el mismo archivo `server.py` en la carpeta root del repositorio

El archivo `server.py` depende de las librerias
- `aiohttp`
- `Pillow`
- `aiohttp_cors`

## Ejecucion
### Ejecutar nativamente
Se recomienda un etorno en Linux
```bash
sudo apt-get update
sudo apt-get install -y libjpeg-dev zlib1g-dev libpng-dev libwebp-dev libgif-dev
pip install Pillow aiohttp aiohttp_cors
python3 server.py
```
### Ejecutar Docker
Crea el volumen del docker
```bash
docker build -t reformatimageaiohtml:latest .
```
Ejecuta el archivo desde el docker
```bash
docker run -d -p 8080:8080 reformatimageaiohtml:latest
```
La ruta defecto sera [localhost:8080](localhost:8080)
## Referencias
- Documentacion de [aiohttp](https://docs.aiohttp.org/en/stable/)
- Python libreria de cambiar formato de imagenes Pillow gracias a [Cloudinary](https://cloudinary.com/guides/web-performance/converting-images-with-python)
- Logo para `favicon` de [SVGRepo - Exchange SVG Vector (89)](https://www.svgrepo.com/svg/256713/exchange)
    - **Licencia:** CC0 License
