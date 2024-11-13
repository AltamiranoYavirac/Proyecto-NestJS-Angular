# Instalación
````
npm i --save @nest/jwt passport-jwt bcrypt
npm i --save-dev @types/passport-jwt
````

# Arrancamos proyecto
````
npm run start:dev
````

# Modules & Resource
````
nest g mo module/auth
nest g res modules/users
````
# Controllers & Services
````
nest g co module/auth
nest g s modules/auth
````