# psql-help

# Create a new user, db and grant access to db
CREATE DATABASE books;
CREATE USER books_rw WITH ENCRYPTED PASSWORD 'books_pwd';
GRANT ALL PRIVILEGES ON DATABASE books TO books_rw;
