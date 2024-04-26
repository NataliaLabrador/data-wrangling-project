# data-wrangling-project
**¿Qué mide el éxito de una canción?**

Este proyecto consiste en la extracción de datos a partir de dos fuentes principales: un dataset y el uso de APIs. A raíz de un dataset extraído a partir de una playlist de Spotify, que recoge las 500 canciones más escuchadas en el año 2023 a nivel global, almacenamos una serie de variables que nos dan información útil sobre cada registro. Después, usando como herramienta la librería de Python Spotipy, perteneciente a la API de Spotify, agrandamos el dataset añadiendo nuevas variables que nos den más información sobre las canciones, como el ID de cada canción y artista, género, duración y diversas carracterísticas musicales que analizan los atributos más técnicos. Realizamos un trabajo de limpieza y gestión de los datos para extraer la información necesaria y sacar conclusiones.

La estructura del repositorio se basa en un README a nivel introductiorio que explica la finalidad y el proceso del proyecto. Seguido de los notebooks en los que se pueden encontrar el código realizado para el proyecto y finalmente una presentación del mismo donde se reflejan principalmente las conclusiones obtenidas en el estudio.

En cuanto al flujo de ejecución, el primer notebook es Songs, donde se puede encontrar la extracción del dataset y la primera limpieza de las variables deseadas.
Después, el notebook Songs - APIS (añadidas), en el que se empieza a usar la herramienta de la API de Spotify para añadir nuevas variables, en este caso el track_id, artist_id y la duración de las canciones.
Seguido a este notebook, tenemos otro llamado Songs - APIS (genre), en el que añadimos las últimas variables extraídas a través de la API. En este notebook añadimos las variables de género musical y álbum al que pertenece la canción.
Por último, el notebook Songs Conclusions incluye todo el código referente a las conclusiones a las que se han llegado en este estudio.


La autoría del proyecto pertenece a Natalia Labrador.
