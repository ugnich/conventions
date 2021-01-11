# Environmental variables

Read settings from the variables below. Where specified, include default values in the code.

`DOMAIN` main domain name of the project. Single domain name, without "www". Example: `timetobook.io`.  
`EMAIL` email address of website admin. Example: `info@timetobook.io`  
`SECRET_KEY` standard Django secret key

### Database

`DB_HOST` database hostname. **Default value**: `localhost`  
`DB_PORT` database connection port. **Default value** for MySQL: `3306`  
`DB_NAME` database name. **Default value**: short lowercase name of the project. Example: `timetobook`  
`DB_USER` username for database connection. **Default value**: short lowercase name of the project. Example: `timetobook`  
`DB_PASSWORD` password for database connection. **Default value**: /empty string/

### Django admin user

Check if the superuser exists and if not - create it.

`DJANGO_USERNAME` username/email of a user. Example: `admin@timetobook.io`  
`DJANGO_PASSWORD` password

### AWS services

In case if the project works with S3 or Route 53 (wildcard SSL validation), AWS credentials will be provided in these variables:

`AWS_ACCESS_KEY_ID`  
`AWS_SECRET_ACCESS_KEY`
