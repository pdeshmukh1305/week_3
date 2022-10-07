FROM dpage/pgadmin4

# Note : Don't hardcode a password and email ever.
# These variable names are built in for defaults.
ENV PGADMIN_DEFAULT_EMAIL=admin@admin.com
ENV PGADMIN_DEFAULT_PASSWORD=pass 

EXPOSE 80

# Notes
# The code to create the network in the terminal =
# docker network create mynetwork

# Running container on the network 
# docker run --name mydba --network mynetwork -p 8081:80 -d my_dba
# docker run --name mydb --network mynetwork -p 5432:5432 -d my_db

# Make sure you run from the correct directories