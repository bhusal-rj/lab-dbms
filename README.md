## This is the lab project for the DBMS(Database Management System).

**For the psql to work make sure docker and docker compose are installed in your system**

**Step 1 : Create a file name .env and define the following key values** 
`
  POSTGRES_USER=<your_username_for_psql>
  POSTGRES_PASSWORD=<your_database_password>
  POSTGRES_DB=<your_database_name>
`

**Step 2: Run the docker compose**
`docker compose up -d`

**Step 3: Run the following command to get into the psql shell**
`docker exec -it postgres_rajesh -U <your_username_defined_in_.env> -d <name_of_your_database>` 
