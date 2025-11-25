<<<<<<< HEAD
# microservices-architect-config-starter
Microservices Architecture Configuration Starter Sample




Architecture of sample multiple microservices developed in different technologies - Spring Boot, Node.js, Python, React.js in a project.
Microservices connected by an API Gateway using Netflix Zuul and Netflix Eureka.


## Application Architecture

The application consists of 7 different Microservices

-   [shoes-microservice-spring-boot](https://github.com/sarat9/microservices-architect-config-starter/tree/main/shoes-microservice-spring-boot)  - Spring Boot App with Shoe data
-   [offers-microservice-spring-boot](https://github.com/sarat9/microservices-architect-config-starter/tree/main/offers-microservice-spring-boot)  - Spring Boot App with Offers data
-   [cart-microservice-nodejs](https://github.com/sarat9/microservices-architect-config-starter/tree/main/cart-microservice-nodejs)  - Node.js App with Cart data
-   [wishlist-microservice-python](https://github.com/sarat9/microservices-architect-config-starter/tree/main/wishlist-microservice-python)  - Python App with Wishlist data
-   [zuul-api-gateway](https://github.com/sarat9/microservices-architect-config-starter/tree/main/zuul-api-gateway)  - API gateway that proxies all the micro-services with Neflix Zuul
-   [eureka-discovery-server](https://github.com/sarat9/microservices-architect-config-starter/tree/main/eureka-discovery-server)  - Service Registration and Discovery Server with Netflix Eureka
-   [ui-web-app-reactjs](https://github.com/sarat9/microservices-architect-config-starter/tree/main/ui-web-app-reactjs)  - Single Page Application that provides the UI


*Optional* - [config-server-spring-boot](https://github.com/sarat9/config-server-spring-boot) repo has a config server service, you can chose to connect them if you want. It is different repository. 


##


![MicroService Architeture ](https://miro.medium.com/max/1050/1*kSLJKEl3X-gKNTpO1l7SQg.png)# Microservices Architecture Sample!

#
#

# Microservices
Crafting Microservices now become an industry standard for any new API development, and almost all the organizations are promoting it.
Microservices are Decentralized, Independent and  Loosely coupled.
Before we go into why we need microservices. Lets understand the problems of our traditional monolitic approach.

## Problems of Monolithic
Problems of Monolithic:

- Large monolithic code base makes complicated to understand and maintain as it grows.
- Scaling become challenging - As everything is packaged in one EAR/WAR, Scaling such a monolithic application can only be accomplished by deploying the same EAR/WAR packages in more servers — also known as horizontal scaling. Each copy of the application in various servers will utilize the same amount of underlying resources, which is often not an efficient way to design.
- Tightly coupled
- Extremely difficult to change technology or language or framework (hybrid technologies) because everything is tightly coupled and depend up on each other.
- Non ability to change tech stack will affect business badly and make it lose lot of modern tech solutions.
- Refactoring code base is difficult
- No fault isolation - If any single function fails, the entire application goes down.
- If a particular function consumes more memory, entire application feels the pain.


## Why go for Microservices?
- A microservices architecture takes single responsibility principle approach.
- Microservices are small, independent, and loosely coupled.
- Microservices are Decentralized, Highly maintainable, Independently deployable. 
- Do one thing well. Organized around business capabilities.
- Agility, scalability, availability, reusability. 
- Improves fault isolation.
- Eliminates long-term commitment to a single technology stack, Code for different services can be written in different languages
- Can be developed, deployed, and maintained independently.
- Services can also be deployed independently of each other and hence its easy to identify hot services and scale them independent of whole application. 
- Development Team Scaling - Each service is a separate codebase, which can be managed by a small development team.
- Development Speed: Microservices are often quite small in size. Due to the size, adding new features in Microservices are usually faster.

#
#

This repository helps with following understanding:
- Modularizing into seperate Microservices
- Microservices developed in different technologies
- Microservices integrated by API gateway
- Discovery and Service Register 

You can use the project as base to start a project or demo... 
or 
To just play around..

#
#

Go Through - https://microservices.io/index.html

#
#

Feel Free to contribute.. 


[![GitHub followers](https://img.shields.io/github/followers/sarat9.svg?label=Follow%20@sarat9&style=social)](https://github.com/sarat9/)
=======
# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
>>>>>>> 74bc090 (initial react project)
