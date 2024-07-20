

# STORE

A full-stack e-commerce project built with Postgres, Express, React and Node.

## Swagger API Documentation

[Documentation](https://pern-store.onrender.com/api/docs/)




## Database Schema

[![ERD](https://user-images.githubusercontent.com/51405947/133893279-8872c475-85ff-47c4-8ade-7d9ef9e5325a.png)](https://dbdiagram.io/d/5fe320fa9a6c525a03bc19db)


```

### Run the production environment

```bash
docker-compose up
```

Go to http://localhost:3000 to view the app running on your browser.

## Deployment

To deploy this project run

```bash
  npm run deploy
```

Check this article for [guidance](https://dev.to/stlnick/how-to-deploy-a-full-stack-mern-app-with-heroku-netlify-ncb)
on how to deploy.

## Tech

- [React](https://reactjs.org/)
- [Node](https://nodejs.org/en/)
- [Express](http://expressjs.com/)
- [Postgres](https://www.postgresql.org/)
- [node-postgres](https://node-postgres.com/)
- [Windmill React UI](https://windmillui.com/react-ui)
- [Tailwind-CSS](https://tailwindcss.com/)
- [react-hot-toast](https://react-hot-toast.com/docs)
- [react-Spinners](https://www.npmjs.com/package/react-spinners)
- [react-helmet-async](https://www.npmjs.com/package/react-helmet-async)

## Environment Variables

To run this project, you will need to add the following environment variables to your .env files in both client and server directory

#### client/.env

`VITE_GOOGLE_CLIENT_ID`

`VITE_GOOGLE_CLIENT_SECRET`

`VITE_API_URL`

`VITE_STRIPE_PUB_KEY`

### server/.env

`POSTGRES_USER`

`POSTGRES_HOST`

`POSTGRES_PASSWORD`

`POSTGRES_DATABASE`

`POSTGRES_DATABASE_TEST`

`POSTGRES_PORT`

`PORT`

`SECRET`

`REFRESH_SECRET`

`SMTP_FROM`

`STRIPE_SECRET_KEY`


