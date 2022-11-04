# DAO 4 Events app


## 1. Project Name
DAO4Events

## 2. Team Name
Daniel Rodriguez

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
- Vercel (frontend deployment)
- Figma (designs)
- Vue.js (frontend)
- Gitbook (documentation)

## 6. Payment Address (DEV en Moonbeam Alpha)
0xC26d145e04833b1061B82A4230E53d08C0A857C3

## 7. The website link
https://dao4events.vercel.app/

## 8. Documentación sobre cómo ejecutar el proyecto.

### Install dependencies
```sh
$ git clone https://github.com/Breakpoint-341/DAO4Events
$ yarn install
```

### How to deploy smart contracts on milkomeda
```sh
$ npx hardhat run scripts/deploy.js --network moonbeam
```

### Run smart contracts tests
```sh
$ yarn test
```

### Run front end app
```sh
$ yarn serve
```

Documentación en Gitbook: https://dao4events.gitbook.io/dao-4-events/

## 9. Pitch grabado
https://youtu.be/D7oUin2_gcM

## 10. Smart-contracts
El contrato inteligente principal para DAO4Events se implementa en Moonbeam Alpha en la dirección `` ([Enlace al contrato inteligente verificado en el explorador] (https://explorer-.../address/ xxxx)

El código fuente de los contratos inteligentes se encuentra en: [contracts/](contracts/)

### Para implementar contratos inteligentes en Moonbeam:
1. Prepare .env file similar to `example.env` with your private key (env. `PRIVATE_KEY=0x123...`)
2. Run the following command `npx hardhat run scripts/deploy.js --network milkomeda`

## 11. Frontend code

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

## 12. Pantallas /  material gráfico

### Pantalla principal
<img width="1278" alt="Screenshot 2022-09-26 at 23 47 11" src="https://user-images.githubusercontent.com/114422762/192386629-dd39b13a-7484-4ff0-a4f7-b730928f2b9e.png">

### Vista de DAO 

<img width="1278" alt="Screenshot 2022-09-26 at 23 47 45" src="https://user-images.githubusercontent.com/114422762/192386692-caf394ea-e485-4ccc-830b-0af5a075e444.png">

### Búsqueda de Eventos

<img width="952" alt="Screenshot 2022-09-26 at 23 48 18" src="https://user-images.githubusercontent.com/114422762/192386757-4ddb66fc-3335-426f-8aea-4d6f330e6542.png">

### Members list de la DAO
<img width="1278" alt="Screenshot 2022-09-26 at 23 48 57" src="https://user-images.githubusercontent.com/114422762/192386844-736bdfff-02b7-4f84-be8a-2959f72840ea.png">

### Vista de Votos
<img width="1275" alt="Screenshot 2022-09-26 at 23 49 18" src="https://user-images.githubusercontent.com/114422762/192386906-88b2069c-fc23-4fa5-9b25-3b66a1e1881b.png">

### Vista de propuesta de eventos
<img width="882" alt="Screenshot 2022-09-26 at 23 50 08" src="https://user-images.githubusercontent.com/114422762/192387029-fd907752-9581-4fe3-acca-a554fbbc6812.png">


- [Designs on figma](https://www.figma.com/file/zwDoAg7cs2YfrY4IMQC6B1/Milkomeda-Hackathon?node-id=0%3A1)

