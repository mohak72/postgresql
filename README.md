# postgresql
https://www.digitalocean.com/community/tutorials/how-to-install-and-use-postgresql-on-centos-7
https://www.liquidweb.com/kb/change-a-password-for-postgresql-on-linux-via-command-line/
https://chartio.com/resources/tutorials/how-to-list-databases-and-tables-in-postgresql-using-psql/
https://kb.objectrocket.com/postgresql/how-to-show-databases-in-postgresql-848
To import a PostgreSQL database using the psql program, follow these steps:

    Transfer the dbexport.pgsql file to your A2 Hosting account using SCP, SFTP, or FTP.
    Log in to your A2 Hosting SSH account.
    Type the following command, and then press Enter. Replace username with your username and replace dbname with the name of the database that you want to import the data into:

    psql -U username dbname < dbexport.pgsql

    https://chartio.com/resources/tutorials/how-to-set-the-default-user-password-in-postgresql/
    https://www.postgresqltutorial.com/postgresql-change-password/
