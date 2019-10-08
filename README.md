# palette-picker-api  

View the front end app (currently under construction!) at https://dab-of-colors.web.app/


## Setup


```bash
psql

# then

CREATE DATABASE palette_picker;
CREATE DATABASE palette_picker_test;
\q
```

Run the migrations for your new DB's:
```
knex migrate:latest
knex migrate:latest --env=test
```

Then seed your db's:

```bash
knex seed:run  
knex seed:run --env=test
```

## Run the Server

To start the server, run:

```bash
npm start
```
