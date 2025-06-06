
```md
*Primer Entrega de Backend 3*
----------------------------

Este proyecto, basado en el código inicial proporcionado por Coderhouse, 
implementa las funcionalidades requeridas para la primera entrega 
del curso de Backend 3. El objetivo principal es trabajar con el 
código base y realizar las siguientes tareas:

-   Crear un router llamado `mocks.router.js` que funcione bajo la 
        ruta base `/api/mocks`.

-   Mover el endpoint `/mockingpets` (desarrollado en el primer 
        desafío entregable) dentro de este router.

-   Crear un módulo de Mocking para generar usuarios de acuerdo a un
        parámetro numérico.

-   Dentro del router `mocks.router.js`, utilizar este módulo en un 
        endpoint GET llamado `/mockingusers`, y generar 50 usuarios.

-   Dentro del router `mocks.router.js`, desarrollar un endpoint POST 
        llamado `/generateData` que reciba los parámetros numéricos 
        "users" y "pets" para generar e insertar en la base de datos 
        la cantidad de registros indicados.

-   Comprobar dichos registros insertados mediante los servicios GET 
        de users y pets.

**Tecnologías utilizadas:**

-   Node.js
-   Express.js
-   Mongoose
-   MongoDB
-   Faker.js
-   bcrypt

**Funcionalidades adicionales:**

-   Encriptación de contraseñas.
-   Generación de datos de prueba.

**Estructura del proyecto:**

El proyecto sigue la estructura base proporcionada por Coderhouse, con la adición del 
router `mocks.router.js` y el módulo de Mocking.

**Cómo ejecutar el proyecto:**

1.  Clonar el repositorio.
2.  Instalar las dependencias con `npm install`.
3.  Configurar las variables de entorno.
4.  Ejecutar el proyecto con `npm start`.

**Contribuciones:**

Las contribuciones son bienvenidas. Por favor, crea un pull request con tus cambios.


```javascript
RecursosBackend-Adoptme
├─ .gitignore
├─ package-lock.json
├─ package.json
└─ src
   ├─ app.js
   ├─ controllers
   │  ├─ adoptions.controller.js
   │  ├─ mocks.controller.js
   │  ├─ pets.controller.js
   │  ├─ sessions.controller.js
   │  └─ users.controller.js
   ├─ dao
   │  ├─ Adoption.js
   │  ├─ models
   │  │  ├─ Adoption.js
   │  │  ├─ Pet.js
   │  │  └─ User.js
   │  ├─ Pets.dao.js
   │  └─ Users.dao.js
   ├─ dto
   │  ├─ Pet.dto.js
   │  └─ User.dto.js
   ├─ public
   │  └─ img
   │     └─ 1671549990926-coderDog.jpg
   ├─ repository
   │  ├─ AdoptionRepository.js
   │  ├─ GenericRepository.js
   │  ├─ PetRepository.js
   │  └─ UserRepository.js
   ├─ routes
   │  ├─ adoption.router.js
   │  ├─ mocks.router.js
   │  ├─ pets.router.js
   │  ├─ sessions.router.js
   │  └─ users.router.js
   ├─ services
   │  ├─ index.js
   │  └─ mocking.js
   └─ utils
      ├─ index.js
      └─ uploader.js
```
