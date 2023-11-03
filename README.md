Sistema de Recomendación de Música basado en Spotify
=
Este proyecto utiliza la API de Spotify para analizar datos de canciones por año y crea un sistema de recomendación de música. Puedes obtener recomendaciones de canciones basadas en tus preferencias de año y género musical.

![image](https://github.com/MinhyukHong/DataAnalysis_Spotify/assets/108979014/9e2151f5-c7c4-464d-b17a-4723bd4f7486)


## Instalación

* Clona este repositorio.

```bash
git clone https://github.com/tunombre/DataAnalysis_Spotify.git
```
<br>

1. Instala las bibliotecas necesarias.
```bash
pip install spotipy numpy
```

2.Crea una aplicación en el panel de desarrolladores de Spotify para obtener las credenciales de acceso (Client ID y Client Secret). Luego, crea un archivo .env en la raíz del proyecto y agrega tus credenciales de esta manera:<br>

SPOTIPY_CLIENT_ID=TU_CLIENT_ID<br>
SPOTIPY_CLIENT_SECRET=TU_CLIENT_SECRET

## Datos de Canciones
Este sistema utiliza la API de Spotify para acceder a datos de canciones, incluyendo información sobre el año de lanzamiento y el género musical. Puedes ajustar tus preferencias de recomendación según estos datos.


