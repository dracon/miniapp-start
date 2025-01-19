# Use the official Postgres image as the base
FROM postgres:13

# Install the uuid-ossp extension
RUN apt-get update && apt-get install -y uuid-ossp

# Set the default database
# ENV POSTGRES_DB myapp

# Copy the SQL script to initialize the database
# COPY init.sql /docker-entrypoint-initdb.d/

# Expose the default Postgres port
EXPOSE 5432