# Use MySQL 8.0 as the base image
FROM mysql:8.0

# Set environment variables for MySQL
ENV MYSQL_ROOT_PASSWORD=rootpassword
ENV MYSQL_DATABASE=userdata
ENV MYSQL_USER=user
ENV MYSQL_PASSWORD=userpassword

# Add initialization SQL script or other config files (optional)
# For example, to add an SQL script that runs on container startup:
ADD ABCompany.sql /docker-entrypoint-initdb.d/
