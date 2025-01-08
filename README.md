<img src="./readme/title1.svg"/>

<br><br>

<!-- project philosophy -->
<img src="./readme/title2.svg"/>

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
<img src="./readme/title3.svg"/>

### Baddĭl is built using the following technologies

- This project uses the [Nest.js](https://nestjs.com/) framework for the backend. Nest.js is a progressive Node.js framework built with TypeScript, enabling efficient and scalable server-side development.
- For the database, the app uses [Prisma](https://www.prisma.io/) with MySQL. Prisma is an ORM (Object Relational Mapper) that provides an efficient and type-safe database access layer for MySQL, making it easier to interact with the database and manage the schema in a structured and scalable manner.
- The mobile app is developed using [Expo](https://expo.dev/) on top of [React Native](https://reactnative.dev/). Expo provides a set of tools and services that streamline the development process for building iOS and Android apps with React Native, enabling faster iteration and easy deployment with a single codebase.
- The broker web app is developed using [Next.js](https://nextjs.org/). Next.js is a React framework that enables server-side rendering and static site generation for optimized performance and SEO.
- The admin desktop app is built using [Electron](https://www.electronjs.org/), which wraps the Next.js app to provide a seamless desktop experience across platforms.
- The runtime and task management are handled by [Bun](https://bun.sh/). Bun is a fast, modern JavaScript runtime that works well for handling tasks in web and mobile applications.
- The app uses [TypeScript](https://www.typescriptlang.org/) for strong typing and enhanced development productivity, providing a better developer experience and reducing runtime errors.
- AI features, including recommendations, trade planning, and analysis, are powered by [OpenAI](https://openai.com/). OpenAI provides cutting-edge AI models to enhance user experience and provide intelligent assistance across the platform.

<br><br>

<!-- UI UX -->
<img src="./readme/title4.svg"/>

> We designed Baddĭl with a focus on intuitive user experience and sleek user interface, using wireframes and mockups to iterate and refine the design. Our goal is to ensure smooth navigation and a seamless bartering process.

- Project Figma design [figma](https://www.figma.com/design/mQS7bXZeXgdcuBRzxnVaNN/Badd%C4%ADl-Project?m=auto&t=i0kwRwvZMlqeEVbU-1)

### Mockups

| Home screen                             | Menu Screen                           | Order Screen                          |
| --------------------------------------- | ------------------------------------- | ------------------------------------- |
| ![Landing](./readme/demo/1440x1024.png) | ![fsdaf](./readme/demo/1440x1024.png) | ![fsdaf](./readme/demo/1440x1024.png) |

<br><br>

<!-- Database Design -->
<img src="./readme/title5.svg"/>

### Architecting Data Excellence: Innovative Database Design Strategies

- Insert ER Diagram here

<br><br>

<!-- Implementation -->
<img src="./readme/title6.svg"/>

### User Screens (Mobile)

| Login screen                              | Register screen                         | Landing screen                          | Loading screen                          |
| ----------------------------------------- | --------------------------------------- | --------------------------------------- | --------------------------------------- |
| ![Landing](https://placehold.co/900x1600) | ![fsdaf](https://placehold.co/900x1600) | ![fsdaf](https://placehold.co/900x1600) | ![fsdaf](https://placehold.co/900x1600) |
| Home screen                               | Menu Screen                             | Order Screen                            | Checkout Screen                         |
| ![Landing](https://placehold.co/900x1600) | ![fsdaf](https://placehold.co/900x1600) | ![fsdaf](https://placehold.co/900x1600) | ![fsdaf](https://placehold.co/900x1600) |

### Admin Screens (Web)

| Login screen                            | Register screen                       | Landing screen                        |
| --------------------------------------- | ------------------------------------- | ------------------------------------- |
| ![Landing](./readme/demo/1440x1024.png) | ![fsdaf](./readme/demo/1440x1024.png) | ![fsdaf](./readme/demo/1440x1024.png) |
| Home screen                             | Menu Screen                           | Order Screen                          |
| ![Landing](./readme/demo/1440x1024.png) | ![fsdaf](./readme/demo/1440x1024.png) | ![fsdaf](./readme/demo/1440x1024.png) |

<br><br>

<!-- Prompt Engineering -->
<img src="./readme/title7.svg"/>

### Mastering AI Interaction: Unveiling the Power of Prompt Engineering

- This project uses advanced prompt engineering techniques to optimize the interaction with natural language processing models. By skillfully crafting input instructions, we tailor the behavior of the models to achieve precise and efficient language understanding and generation for various tasks and preferences.

<br><br>

<!-- AWS Deployment -->
<img src="./readme/title8.svg"/>

### Efficient AI Deployment: Unleashing the Potential with AWS Integration

- This project leverages AWS deployment strategies to seamlessly integrate and deploy natural language processing models. With a focus on scalability, reliability, and performance, we ensure that AI applications powered by these models deliver robust and responsive solutions for diverse use cases.

<br><br>

<!-- Unit Testing -->
<img src="./readme/title9.svg"/>

### Precision in Development: Harnessing the Power of Unit Testing

- This project employs rigorous unit testing methodologies to ensure the reliability and accuracy of code components. By systematically evaluating individual units of the software, we guarantee a robust foundation, identifying and addressing potential issues early in the development process.

<br><br>

<!-- How to run -->
<img src="./readme/title10.svg"/>

> To set up Coffee Express locally, follow these steps:

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.

- npm

  ```sh
  npm install npm@latest -g
  ```

### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Get a free API Key at [example](https://example.com)
2. Clone the repo
   git clone [github](https://github.com/your_username_/Project-Name.git)
3. Install NPM packages

   ```sh
   npm install
   ```

4. Enter your API in `config.js`

   ```js
   const API_KEY = "ENTER YOUR API";
   ```

Now, you should be able to run Baddĭl locally and explore its features.
