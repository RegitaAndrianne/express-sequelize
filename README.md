# express-sequelize
Practice ORM

1. npm install -y
2. npm install `sequelize express pg ejs`
3. npm install -D `sequelize-cli`
4. Buat cek sequelize sdh benar ter-install dengan command
`npx sequelize --help`
5. Buat inisiasi project express menggunakan config sequelize, menggunakan command
`npx sequelize:init`
6. Ke generate beberapa folder yaitu config, migrations, models dan seeders
7. Ubah configuration config.json -> untuk bisa connect ke database yang sudah dibuat
8. Create db di postgres dengan command 
`npx sequelize db:create`
kalau mau hapus database 
`npx sequelize db:drop`
kalau pake environment yang beda
`npx sequelize db:create --env=test`
9. Buat table
`npx sequelize-cli model:generate --name Teacher --attributes first_name:string, last_name:string, email:string, gender:string`

`npx sequelize-cli model:generate --name Subject --attributes subject_name:string,academic_year:date`

