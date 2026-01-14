# UI Basic Spring Boot - AI Grok Assisted

A simple Spring Boot web application with JSP support that displays a "hello amrit" message.

## Features

- Spring Boot web application
- JSP (JavaServer Pages) for view rendering
- RESTful controller mapping
- Embedded Tomcat server

## Technologies Used

- Java 8 (compatible)
- Spring Boot 2.7.18
- Spring MVC
- JSP
- Maven

## How to Run

### Prerequisites
- Java 8 or higher
- Maven 3.x

### Running the Application

1. Clone the repository:
```bash
git clone https://github.com/amgupta29/ui-basic-spring-boot-ai-grok.git
cd ui-basic-spring-boot-ai-grok
```

2. Run with Maven:
```bash
mvn spring-boot:run
```

3. Open your browser and navigate to:
```
http://localhost:8080/
```

You should see the message "hello amrit" displayed on the page.

## Project Structure

```
src/
├── main/
│   ├── java/
│   │   └── com/helloamrit/
│   │       ├── HelloAmritApplication.java  # Main Spring Boot application
│   │       └── controller/
│   │           └── HelloController.java    # Web controller
│   ├── resources/
│   │   └── application.properties         # Application configuration
│   └── webapp/WEB-INF/views/
│       └── hello.jsp                      # JSP view template
└── pom.xml                                # Maven configuration
```

## Configuration

The application runs on port 8080 by default. You can change this in `src/main/resources/application.properties`:

```properties
server.port=8080
```

## API Endpoints

- `GET /` - Displays the hello page with "hello amrit" message

## Development

This project was created with assistance from AI (Grok) and demonstrates:
- Basic Spring Boot setup
- MVC architecture
- JSP integration
- Maven build management

## Contributing

Feel free to fork this repository and submit pull requests for any improvements!

## License

This project is open source and available under the [MIT License](LICENSE).