npx create-next-app@latest with default settings -> npm install prisma --save-dev -> npx prisma init --datasource-provider postgresql
-> connect the neon database by copy paste the snippet from neon db website into the .env(database_url) file
-> add models in the schema.prisma -> sync prisma with neon database via npx prisma migrate dev --name init