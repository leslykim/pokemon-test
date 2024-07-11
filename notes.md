# Observaciones:

## Readme.md

1. No se incluye información de cómo ejecutar los tests.

## Tests

1. No se agregó correctamente el .env en el .gitignore, exponiendo la clave secreta
2. Existen dos .env.
3. No se eliminaron los tests que se generan por defecto en el proyecto.
4. Los tests `Check Wikipedia page for ${pokemon.name}` fallan
5. No se hace uso de baseUrl, sino que se indican las urls completas en cada test.


## Otros

1. No se subió correctamente el proyecto a GitHub, por ejemplo, no se subió la carpeta "tests". La evaluación se hizo a partir del zip compartido por e-mail.
2. Si bien no se solicitó, no se implementó otras características que pudieron haber sido implementas, como ser linter, pre-push, beautifier, GitHub actions.

# Propuesta para avanzar en el proceso:
1. Corregir todos los puntos mencionados en las observaciones. En el caso de baseUrl, se debe usar una baseUrl para la consulta por API y otra para la web. Investigar el uso de "fixtures" para lograr esto.
2. Leer el archivo excel y leído el mismo, guardar sus valores en "pokemonData".
3. Asegurarse que el proyecto haya sido subido correctamente. Luego de subir el proyecto, intentar clonar el proyecto y ejecutar las pruebas.