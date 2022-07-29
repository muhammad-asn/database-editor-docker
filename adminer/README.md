Steps:

1. ```bash
   wget https://download.oracle.com/otn_software/linux/instantclient/211000/instantclient-basic-linux.x64-21.1.0.0.0.zip 
   wget https://download.oracle.com/otn_software/linux/instantclient/211000/instantclient-sqlplus-linux.x64-21.1.0.0.0.zip 
   wget https://download.oracle.com/otn_software/linux/instantclient/211000/instantclient-sdk-linux.x64-21.1.0.0.0.zip
   ```
2. `docker network create db-editor`
3. `docker build -t adminer:4.8.1 --network=host .`
4. `docker-compose up -d`
