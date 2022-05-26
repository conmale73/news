# Sport News

> Simple MVC web application example (app for managing sport news portal), written in Java using Servlets, JSP and MySQL, and [HikariCP](https://brettwooldridge.github.io/HikariCP/) as a JDBC connection pool.

## Requirements

Java 10 or above (because of the local variable type inference).

## Usage

- Import maven project using Eclipse
- Import [sport_news.sql](sport_news.sql)
- Set the directory for image uploads in the [web.xml](src/main/webapp/WEB-INF/web.xml) file: context param `snUploadDirectory`
- Set database name, username and password for database [here](src/main/java/rs/rnk/example/sportnews/data/DataSource.java)
- Create new Tomcat 9 server using Eclipse and deploy the application
- Visit [http://localhost:8080/sport-news](http://localhost:8080/sport-news) and test the application with the following user roles:
  - **Administrator**: username: `admin`, password: `admin`
  - **Manager**: username: `manager`, password: `manager`
  - **Editor**: username: `editor`, password: `editor`

## Screenshots

![screenshot2](screenshots/screenshot2.png)

![screenshot2](screenshots/screenshot3.png)

![screenshot2](screenshots/screenshot4.png)

![screenshot2](screenshots/screenshot5.png)

![screenshot2](screenshots/screenshot6.png)

![screenshot2](screenshots/screenshot7.png)

![screenshot2](screenshots/screenshot8.png)

![screenshot2](screenshots/screenshot9.png)

![screenshot2](screenshots/screenshot10.png)

![screenshot2](screenshots/screenshot24.png)

![screenshot2](screenshots/screenshot25.png)

![screenshot2](screenshots/screenshot11.png)

![screenshot2](screenshots/screenshot12.png)

![screenshot2](screenshots/screenshot22.png)

![screenshot2](screenshots/screenshot23.png)

![screenshot2](screenshots/screenshot13.png)

![screenshot2](screenshots/screenshot14.png)

![screenshot2](screenshots/screenshot15.png)

![screenshot2](screenshots/screenshot16.png)

![screenshot2](screenshots/screenshot17.png)

![screenshot2](screenshots/screenshot18.png)

![screenshot2](screenshots/screenshot19.png)

![screenshot2](screenshots/screenshot20.png)

![screenshot2](screenshots/screenshot21.png)