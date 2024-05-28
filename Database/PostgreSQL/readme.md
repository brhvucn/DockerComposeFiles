# How to Use

### 1. Save the Configuration:
Save the above configuration in a file named docker-compose.yml.

### 2. Start the Services:
Run the following command in the directory containing the docker-compose.yml file to start the services:

```
docker-compose up -d
```

### 3. Access pgAdmin:
Open your browser and go to `http://localhost:8080`. Log in with the email `admin@admin.com` and the password admin.

### 4. Connect pgAdmin to PostgreSQL:

Once logged in, you can add a new server in pgAdmin to connect to the PostgreSQL instance.
Use `postgres` as the hostname, `admin` as the username, and `admin` as the password.
