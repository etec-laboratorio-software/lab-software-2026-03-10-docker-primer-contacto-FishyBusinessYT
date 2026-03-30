# Utopia Creature Collection

Utopia Creature Collection es una herramienta diseñada para almacenar y acceder con facilidad a criaturas personalizadas del juego de mesa Utopia.

## Requisitos Previos

* **Git**
* **Uv**
* **Python 3.13.9** (o compatible)
* **Node.js V22.20.0** y **NPM 10.9.3** (o compatible)

## Instalación

1) Clonar el repositorio
    ```bash
    git clone git@github.com:etec-programacion-3/programacion-3-2025-gonzalezc-FishyBusinessYT.git ./ucc
    ```
2) Crear imagenes de docker
    ```bash
    cd ucc
    docker compose build
    ```

## Uso
### Iniciar app
```bash
cd ucc
docker compose up
```
### Conectarse
Una vez estén corriendo ambos servidores, el frontend de la aplicación estará disponible en la dirección [http://localhost:5173](http://localhost:5173)
### Detener el programa
Todo se guarda automáticamente, así que es seguro detener la app con `Ctrl-C`
