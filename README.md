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

5. Rebuild the database with the seed
```
localhost:3000/api/v2/seed
```

## Stack
* MongoDB
* Nest