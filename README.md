# Create-postgres-database

- CREATE DATABASE your_database_name;

- CREATE USER your_user_name WITH PASSWORD 'your_password';

- ALTER ROLE your_user_name  SET client_encoding TO 'utf8';

- ALTER ROLE your_user_name SET default_transaction_isolation TO 'read committed';

- ALTER ROLE your_user_name  SET timezone TO 'UTC';

- GRANT ALL PRIVILEGES ON DATABASE your_user_name TO your_database_name;
