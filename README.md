<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

# Execute in development

1. Clone the repository
2. Excute
```
yarn install
```
3. Have Nest CLI installed
```
npm i -g @nestjs/cli
```

4. Build the database
```
docker-compose up -d
```

5. Clone the file __.env.template__ and rename the copy to __.env__

6. Fill the environment variables in the ```.env```

7. Execute the dev application:
```
yarn start:dev
```

5. Rebuild the database with the seed
```
localhost:3000/api/v2/seed
```

## Stack used
* MongoDB
* Nest

# Production Build
1. Create the file ```.env.prod```
2. Fill the environmet variables
3. Create the new image
```
docker-compose -f docker-compose.prod.yaml --env-file .env.prod up --build
```