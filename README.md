<h1 align="center">Semana Spring React - DSMovie</h1>

<p align="center">
  <img alt="DSMovie" src=".github/banner.PNG" width="100%">
</p>

## Project

The project is a movie catalogue. The application show movies, show the number of reviews and average of review scores. The user can rating movies.

## Features

- Use REST API;
- The movies list is paged.
- CI / CD to keep the project constantly updated.

## Technologies and Libraries

API with Spring Boot (Backend):

- Java 11
- [Spring Tools](https://spring.io)
- Web
- JPA
- H2
- Postgres
- Security
- [Heroku](https://www.heroku.com)

Web application with React JS and TypeScript (Frontend):

- [Node.JS v16.13.0](https://nodejs.org/en/)
- [NPM 8.1.0](https://www.npmjs.com/)
- [Visual Studio Code 1.62.0](https://code.visualstudio.com/)
- [axios](https://www.npmjs.com/package/axios)
- Bootstrap 5.1.3
- [Netlify](https://app.netlify.com)

## Conceptual database model

<p align="center">
  <img alt="Database" src=".github/database.png" width="100%">
</p>

## Project structure

<p align="center">
  <img alt="structure" src=".github/structure.png" width="100%">
</p>

## Layout

You can view the project layout through this [link](https://www.figma.com/file/4X9DrYtKfdkOv5bi88CBzm/DSMovie1-(Copy)). Figma account is required to access it.

## How to run

### Backend

- Start STS IDE;
- Select cloned repository folder as Workspace in the STS IDE;
- File -> Import -> Maven -> Existing Maven Projects -> Browse.. -> access the cloned repository folder and select `backend` folder -> Finish;
- Start the Backend project via the STS IDE;

### Frontend

- Access the cloned repository folder;
- Access `frontend` directory;
- Install dependencies with `yarn` or `npm install`;
- Start the frontend project with `yarn start` or `npm start`;

## License

This project is under the MIT license. See the [LICENSE](LICENSE.md) file for more details.