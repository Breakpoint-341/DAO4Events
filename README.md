# DAO 4 Events app


## 1. Nombre del Proyecto
DAO4Events

## 2. Nombres del integrantes del Equipo
Daniel Felipe Rodriguez

## 3. Descripción corta del proyecto.
DAO4Events es una aplicación basada en blockchain para organizadores de eventos. La naturaleza en línea de los proyectos criptográficos les permite crecer fácilmente a nivel mundial. Esta es también la raíz del problema con los eventos presenciales de muchas comunidades. Para muchas personas es difícil o incluso imposible asistir a conferencias como NFT.NYC, ya sea por los fondos o las visas necesarias. Una aplicación como EventDAO ayudaría a las comunidades globales a organizarse localmente. Es una gran herramienta tanto para proyectos existentes como para organizadores de eventos independientes.

## 4. Descripción larga del proyecto.
Las comunidades criptográficas están dispersas por todo el mundo, mientras que los eventos criptográficos priorizan los centros más grandes. Para muchas personas es difícil o incluso imposible viajar a destinos populares de criptoeventos como Estados Unidos, no solo por los gastos, sino también por los requisitos de visa. Estas personas podrían reunirse localmente, pero para organizarse necesitan las herramientas adecuadas.

La organización de eventos puede ser un trabajo de tiempo completo, pero muchos entusiastas sacrifican su propio tiempo libre y, a veces, incluso su propio dinero para organizar eventos para la comunidad. A menudo hay más de una persona responsable de la organización y surgen las preguntas sobre la gestión de tareas y la toma de decisiones.

La cerveza y la pizza gratis son un estándar para las reuniones criptográficas, pero requieren patrocinadores. Más difícil que encontrar uno es aceptar una forma de acuerdo. Los patrocinadores no quieren confiar su dinero a una sola persona, quieren hacer una donación a una organización.

DAO4Events tiene como objetivo resolver todos estos problemas. Hará que organizar eventos sea más fácil y que el crowdfunding sea menos complicado.

La votación de DAO mejorará la toma de decisiones tanto en las comunidades como en los grupos de organizadores de eventos independientes.

Nuestra herramienta también ofrece opciones de crowdfunding interno y externo, lo que hace que la gestión financiera sea transparente y confiable. Las comunidades pueden financiar sus propias reuniones pequeñas de manera coordinada, mientras que también pueden administrar fácilmente patrocinadores externos que prefieren trabajar con organizaciones en lugar de personas privadas.

Una herramienta adecuada para la organización de eventos de abajo hacia arriba dará como resultado más eventos de calidad donde haya comunidades dispuestas a reunirse.

## 5. Tech stack usado
- Solidity (smart contracts)
- Hardhat (smart contracts framework)
- Javascript (main language)
- Vue.js (frontend)
- Gitbook (documentation)

## 6. Payment Address (DEV en Moonbeam Alpha)
0xC26d145e04833b1061B82A4230E53d08C0A857C3

## 7. Documentación en Gitbook: https://dao4events.gitbook.io/dao-4-events/

### 8. Documentación sobre cómo ejecutar el proyecto.

### Install dependencies
```sh
$ git clone https://github.com/Breakpoint-341/DAO4Events
$ yarn install
```

### How to deploy smart contracts on milkomeda
```sh
$ npx hardhat run scripts/deploy.js --network moonbase
```

### Run smart contracts tests
```sh
$ yarn test
```

### Run front end app
```sh
$ yarn serve
```

### Levantar el sitio web 
http://localhost:8080/

## 9. Smart-contracts
El contrato inteligente principal para DAO4Events se implementa en Moonbeam Alpha en la dirección `` ([Enlace al contrato inteligente en el explorador] (https://moonbase.moonscan.io/address/0xE629b005ae224633154676514656964151361673)

El código fuente de los contratos inteligentes se encuentra en: [contracts/](contracts/)

### Para implementar contratos inteligentes en Moonbeam:
1. Prepare .env file similar to `example.env` with your private key (env. `PRIVATE_KEY=0x123...`)
2. Run the following command `npx hardhat run scripts/deploy.js --network moonbase`

## 10. Frontend code

El código de front-end se encuentra en la carpeta [src/](src/) .
El front-end tiene las siguientes rutas:
- `/` (main route)
- `/dao/:id` (Vista de DAO seleccionada)
- `/dao/:id/members` (Vista de DAO Members )
- `/dao/:id/votings` (Vista de votos)
- `/dao/:id/propose-event` (votación - proponer un formulario de evento para un DAO dado)

La aplicación frontal tiene los siguientes componentes:
- AboutView.vue
- DaoMembersView.vue
- DaoView.vue
- DaoVotingsView.vue
- HomeView.vue
- ProposeEventView.vue
- UpcomingEvents.vue
- Welcome.vue
- BlockchainAddress.vue

## 11. Pantallas /  material gráfico

### Pantalla principal
![image](https://user-images.githubusercontent.com/108815937/200097073-34040346-8345-4018-bb74-879f624b582a.png)

### Vista de DAO 
![image](https://user-images.githubusercontent.com/108815937/200097106-08536847-f8b7-43f5-aa58-93f65798a4e3.png)

### Búsqueda de Eventos
![image](https://user-images.githubusercontent.com/108815937/200097143-2b9cd8f2-b39b-4c46-b3e0-9cab795a66c7.png)

### Members list de la DAO
![image](https://user-images.githubusercontent.com/108815937/200097152-05018df3-bc88-4e01-b920-cb2c08dc095d.png)

### Vista de Votos
![image](https://user-images.githubusercontent.com/108815937/200097180-57930e6f-447d-420c-95b4-3181cca31085.png)

### Vista de propuesta de eventos
![image](https://user-images.githubusercontent.com/108815937/200097193-f18fa9f5-d16f-4a14-835a-95b340129248.png)
