# Spacetime App - Next Level Week Project

![Spacetime Logo](https://raw.githubusercontent.com/Albino-Marques/space-time-nlw/f255eabe20ea0e27b040a83e662b1c5b9097f158/web/src/assets/nlw-spacetime-logo.svg)

This repository contains the code for the Spacetime App, a project developed during the Next Level Week by Rocketseat. The application allows users to record their memories with photos, videos, and text, creating a timeline of their experiences.

## Technologies Used:

- TypeScript
- JavaScript
- CSS
- Tailwind CSS
- HTML
- Next.js
- Prisma
- Fastify
- Zod
- Axios
- Node.js
- React
- React Native

## Features:

* **Memory registration:** Users can register their memories with photos, videos, and text.
* **Timeline:** Memories are displayed in a timeline, allowing users to view their memories chronologically.
* **Oauth with Github:** Registration is done through Oauth with Github.
* **Custom routes:** The application uses custom routes to improve the user experience.
* **Good practices for server maintenance:** The application follows good practices for server maintenance, such as using a SQLite database.


## How to run

### Frontend

To run the frontend, follow the steps below:

1. Clone the repository:

<code>git clone https://github.com/Albino-Marques/space-time-nlw.git</code>

2. Install the dependencies:

<code>cd space-time-nlw/web</code>
<br>
<code>npm install package.json</code>

3. Start the page:

<code>npm run dev</code>

The frontend will be available in your browser at the address http://localhost:3000.

### Backend

To run the backend, follow the steps below:


1. Install the dependencies:

<code>cd space-time-nlw/server</code>
<br>
<code>npm install package.json</code>
<br>
<code>npx prisma generate</code>

Obs: Need to Install the Prisma Client too: https://www.prisma.io/docs/concepts/components/prisma-client
 
If an error occurs, consult the
Prisma Schema.

It will probably be necessary to create new authentication keys on Github to be able to use the application. Pay attention to this.
To create them, see the github page itself:
https://docs.github.com/pt/apps/creating-github-apps/authenticating-with-a-github-app/managing-private-keys-for-github-apps


2. Create a `.env` file in the root of the project with the following environment variables:

<code>DATABASE_URL=DATABASE_URL</code>


3. Start the server:

<code>npm run dev</code>

The backend will be available in your browser at the address http://localhost:3333.

## Contributing

To contribute to the project, follow the steps below:

1. Fork the repository.
2. Create a branch with your feature.
3. Commit your changes.
4. Push to your branch.
5. Send a pull request to the `main` branch.

## License

This project is under the MIT license. See the `LICENSE` file for more details.


## Acknowledgements

- [Rocketseat](https://rocketseat.com.br/) for organizing the Next Level Week event and providing valuable resources for developers.
- [The Next.js Team](https://nextjs.org/) for creating an amazing framework for React applications.
- [Prisma](https://www.prisma.io/) for simplifying database operations and migrations.
- [Tailwind CSS](https://tailwindcss.com/) for enabling rapid UI development with utility-first CSS.
- [Fastify](https://www.fastify.io/) for its high-performance web framework for Node.js.
- [Zod](https://zod.dev/) for its powerful TypeScript-first schema declaration and validation library.
