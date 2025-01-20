<img src="./readme/titles/title1.svg"/>

<br><br>

<!-- project philosophy -->
<img src="./readme/titles/title2.svg"/>

> A platform revolutionizing the bartering experience by connecting users, brokers, and admins through a seamless and interactive system.
>
> Baddĭl aims to redefine how people trade goods and services by introducing modern tools like AI assistance, dynamic user interfaces, and automated workflows. We believe in fostering a community of trust and efficiency, empowering users to achieve their bartering goals effortlessly.

### User Stories

#### Admin 

- As an admin, I want to flag suspicious activities, so I can ensure a safe and trustworthy platform.
- As an admin, I want to manage notifications, so I can keep users informed about important updates.
- As an admin, I want to handle disputes between users, so I can ensure fair resolutions and maintain a positive community.

#### Barterer 

- As a barterer, I want to verify the identity of the person I’m trading with, so I can feel secure during the exchange.
- As a barterer, I want to communicate through a secure chat system, so I can ensure that all discussions remain within the platform.
- As a barterer, I want help planning my bartering goals, so I can receive recommendations on how to reach my desired item efficiently.

#### Broker 

- As a broker, I want to manage trade deadlines on a calendar, so I can efficiently organize my clients' trades.
- As a broker, I want to manage my income from clients and the platform, so I can keep track of my earnings and monitor performance.
- As a broker, I want to view trade details easily, so I can provide accurate advice and support to my clients.

<br><br>

<!-- Tech stack -->
<img src="./readme/titles/title3.svg"/>

### Baddĭl is built using the following technologies

- This project uses the [Nest.js](https://nestjs.com/) framework for the backend. Nest.js is a progressive Node.js framework built with TypeScript, enabling efficient and scalable server-side development.
- For the database, the app uses [Prisma](https://www.prisma.io/) with MySQL. Prisma is an ORM (Object Relational Mapper) that provides an efficient and type-safe database access layer for MySQL, making it easier to interact with the database and manage the schema in a structured and scalable manner.
- The mobile app is developed using [Expo](https://expo.dev/) on top of [React Native](https://reactnative.dev/). Expo provides a set of tools and services that streamline the development process for building iOS and Android apps with React Native, enabling faster iteration and easy deployment with a single codebase.
- The broker web app is developed using [React](https://react.dev/) + [Vite](https://vite.dev/).
- The admin desktop app is built using [React](https://react.dev/) + [Vite](https://vite.dev/).
- The runtime and task management are handled by [Bun](https://bun.sh/). Bun is a fast, modern JavaScript runtime that works well for handling tasks in web and mobile applications.
- The app uses [TypeScript](https://www.typescriptlang.org/) for strong typing and enhanced development productivity, providing a better developer experience and reducing runtime errors.
- AI features, including recommendations, trade planning, and analysis, are powered by [OpenAI](https://openai.com/). OpenAI provides cutting-edge AI models to enhance user experience and provide intelligent assistance across the platform.

<br><br>

<!-- UI UX -->
<img src="./readme/titles/title4.svg"/>

> We designed Baddĭl with a focus on intuitive user experience and sleek user interface, using wireframes and mockups to iterate and refine the design. Our goal is to ensure smooth navigation and a seamless bartering process.

- Project Figma design [figma](https://www.figma.com/design/mQS7bXZeXgdcuBRzxnVaNN/Badd%C4%ADl-Project?m=auto&t=i0kwRwvZMlqeEVbU-1)

### Mockups

| Home Screen                                    | Brokers Screen                                  | Item Screen                                 |
| ---------------------------------------------- | -------------------------------------------- | -------------------------------------------- |
| ![Landing](./readme/mockups/mobile/homePage.png) | ![Brokers](./readme/mockups/mobile/brokers.png) | ![Item](./readme/mockups/mobile/itemPage.png) |

<br><br>

<!-- Database Design -->
<img src="./readme/titles/title5.svg"/>

### Architecting Data Excellence: Innovative Database Design Strategies

- To visit the Prisma schema directory click [here]("./readme/schema")

<br><br>

<!-- Implementation -->
<img src="./readme/titles/title6.svg"/>

### User Screens (Mobile)

| Login screen                              | Register screen                         | Landing screen                          | Loading screen                          |
| ----------------------------------------- | --------------------------------------- | --------------------------------------- | --------------------------------------- |
| ![Landing](https://placehold.co/900x1600) | ![fsdaf](https://placehold.co/900x1600) | ![fsdaf](https://placehold.co/900x1600) | ![fsdaf](https://placehold.co/900x1600) |
| Home screen                               | Menu Screen                             | Order Screen                            | Checkout Screen                         |
| ![Landing](https://placehold.co/900x1600) | ![fsdaf](https://placehold.co/900x1600) | ![fsdaf](https://placehold.co/900x1600) | ![fsdaf](https://placehold.co/900x1600) |

### Admin Screens (Web)

| Login screen                                   | Register screen                              | Landing screen                               |
| ---------------------------------------------- | -------------------------------------------- | -------------------------------------------- |
| ![Landing](./readme/titles/demo/1440x1024.png) | ![fsdaf](./readme/titles/demo/1440x1024.png) | ![fsdaf](./readme/titles/demo/1440x1024.png) |
| Home screen                                    | Menu Screen                                  | Order Screen                                 |
| ![Landing](./readme/titles/demo/1440x1024.png) | ![fsdaf](./readme/titles/demo/1440x1024.png) | ![fsdaf](./readme/titles/demo/1440x1024.png) |

<br><br>

<!-- Prompt Engineering -->
<img src="./readme/titles/title7.svg"/>

### Mastering AI Interaction: Unveiling the Power of Prompt Engineering

- Baddil's core is AI! We harnessed [OpenAI]("https://openai.com/index/openai-api/") 's API to create a robust and efficient system that can handle a wide range of user inputs and provide services hat guarantee security and seamless experience of our users!

<br><br>

<!-- AWS Deployment -->
<img src="./readme/titles/title8.svg"/>

### Efficient AI Deployment: Unleashing the Potential with AWS Integration

- This project leverages AWS deployment strategies to seamlessly integrate and deploy natural language processing models. With a focus on scalability, reliability, and performance, we ensure that AI applications powered by these models deliver robust and responsive solutions for diverse use cases.

<br><br>

<!-- Unit Testing -->
<img src="./readme/titles/title9.svg"/>

### Precision in Development: Harnessing the Power of Unit Testing

- Our team keeps ensuring the scalability of Baddil as it grows!
- Definitely can't wait to announce our Unit Testing in future. Stay tuned!

<br><br>

<!-- How to run -->
<img src="./readme/titles/title10.svg"/>

> To set up Baddil locally, follow these steps:

### Prerequisites

First of all you need your runtime environment. Baddil uses "Bun" to be set up. You can install bun by running the following command:

- [bun](https://bun.sh/docs/installation)

  ```sh
  npm install -g bun
  ```

### Installation

_Below are instructions how to run Baddil._

#### Common Steps:

1. Clone the repository:

```sh
git clone https://github.com/IbrahimItani01/baddil.git
```

2. Install dependencies

   ```sh
   bun install
   ```

#### Server-Side

1. Setup [Firebase]("https://firebase.google.com/") project for authentication.

2. Obtain your [OpenAI]("https://openai.com/index/openai-api/") api.

3. Create your [MySQL]("https://www.mysql.com/products/workbench/") database.

4. Visit the .env.example file and follow the key-naming structure.

#### Client-Side

1. Check in ./apis/main.ts the currentIp. Change its values to your currentIp.

Now, you should be able to run Baddĭl locally and explore its features!
