# Práctica: MockAPI + Postman — API de Canciones Favoritas

## Objetivos
- Modelar `artists` y `songs` (relación por `artistId`).
- Consumir la API con Postman (GET, POST, PUT, PATCH, DELETE).
- Documentar evidencia con capturas.

## MockAPI
- Base URL: **https://6900166be02b16d17540193d.mockapi.io/api/v1/:endpoint**  
- Recursos:
  - GET ALL SONGS: `https://6900166be02b16d17540193d.mockapi.io/api/v1/songs`
  - POST SONGS : `https://6900166be02b16d17540193d.mockapi.io/api/v1/songs`
  - PUT SONGS:`https://6900166be02b16d17540193d.mockapi.io/api/v1/songs](https://6900166be02b16d17540193d.mockapi.io/api/v1/songs/(#id)`
  - GET CON FILTRO:`https://6900166be02b16d17540193d.mockapi.io/api/v1/songs?genre=K-pop&year=2025`
  - DELETE:`https://6900166be02b16d17540193d.mockapi.io/api/v1/songs](https://6900166be02b16d17540193d.mockapi.io/api/v1/songs/(#id)`
  - GET DELETED SONG : `https://6900166be02b16d17540193d.mockapi.io/api/v1/songs/46`
  - PATCH :`https://6900166be02b16d17540193d.mockapi.io/api/v1/songs](https://6900166be02b16d17540193d.mockapi.io/api/v1/songs/(#id)`


## Evidencias (screenshots)
- Ver `/screenshots`:
  - 01 POST
  - 02 GET
  - 03 PUT
  - 04 PATCH
  - 05 DELETE

## Conclusiones
- (1) MockAPI resultó una herramienta ideal para practicar sin necesidad de un backend real.
Se comprendió cómo definir recursos (artists, songs), generar campos automáticos (id), y establecer relaciones mediante artistId
- (2) Al crear los archivos tipo .json , se afianzó la estructura clave–valor de JSON, el manejo de tipos de datos (string, number, boolean, array, object), y la forma en que se transmite información en las APIs modernas, esto permite crear, leer y manipular información de manera estructurada y estandarizada.
- (3) Durante esta práctica comprendí el uso de Postman como una herramienta fundamental para probar APIs RESTful, lo que me permitió interactuar con los diferentes endpoints de una forma visual, ordenada y dinámica.A través de Postman pude enviar peticiones HTTP (GET, POST, PUT, PATCH, DELETE) y observar las respuestas en formato JSON, entendiendo con mayor claridad cómo se estructuran los datos y cómo fluye la comunicación entre el cliente y el servidor.De la misma forma, aprendí a usar correctamente los métodos HTTP y a diferenciar en qué casos es necesario filtrar con parámetros y en cuáles no se debe filtrar, como sucede con PUT, PATCH y DELETE, que requieren el ID directo del recurso en la URL.

## Enlaces
- MockAPI Dashboard: https://mockapi.io/clone/6900166be02b16d17540193e
- Colecciones Postman : `https://jossuep8888-587871.postman.co/workspace/Jossue-'s-Workspace~8dbdd6b7-0b3f-4247-82de-5830e9a78cbc/collection/49583606-591cf18f-63cd-41fc-9ece-15e319ec19f5?action=share&creator=49583606&active-environment=49583606-43d626c5-4d4a-4261-abb9-5f243a547800`
