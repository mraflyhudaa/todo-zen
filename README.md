# TodoZen

This is a task management app built with t3-stack. It allows users to create, update, and delete tasks, as well as mark them as complete.

## Features

- User authentication with Next-Auth and JWT
- Create, update, and delete tasks
- Mark tasks as complete
- Filter tasks by completed status
- Server-side rendering with Next.js
- Styling with TailwindCSS
- ORM and database management with Prisma and MySQL
- Automatic scaling with PlanetScale
- Type-safe communication between server and client with TRPC

## Technologies Used

- [Next.js](https://nextjs.org) for server-side rendering and routing
- [Tailwind CSS](https://tailwindcss.com) for styling
- [Prisma](https://prisma.io) for ORM and database management
- MySQL for database storage
- PlanetScale for automatic scaling and replication of MySQL databases
- [tRPC](https://trpc.io) for type-safe communication between server and client
- [NextAuth.js](https://next-auth.js.org) for user authentication with JWT

## Setup

- Clone this repository
- Install dependencies with npm install
- Create a `.env` file and add the necessary environment variables (see `.env.example` for reference)
- Run the development server with npm run dev
- Open http://localhost:3000 in your browser

## Deployment

- Follow our deployment guides for [Vercel](https://create.t3.gg/en/deployment/vercel), [Netlify](https://create.t3.gg/en/deployment/netlify) and [Docker](https://create.t3.gg/en/deployment/docker) for more information.
- Set the necessary environment variables in your deployment environment

## Contributing

Contributions are welcome! Please see the contributing guidelines for more information.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
