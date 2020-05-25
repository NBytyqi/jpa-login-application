# jpa-login-application
# In order to make a successfully connection to your database, please change first 3 lines in application.properties:
  1) spring.datasource.url -> to your database name
  2) spring.datasource.username -> your username
  3) spring.datasource.password -> your password

#The hibernate ddl-auto is set to create-drop, so the schema will be created each time and destroyed after all operations are finished
#In the data.sql file which is located in src/main/resurces initially just adds a row in the database, just to be able to login with user credentials ('username', 'password')
