### Infrastructure

- The project consists of 3 parts API, Frontend, and Database.
- We will use AWS RDS service to store the database (PostgreSQL).
- Elastic beanstalk service to deploy source Backend API and connect it via RDS to get data.
- S3 static website service to host and host Frontend, it will connect to EB endpoint to get backend API and the user will access s3 endpoint to use web.