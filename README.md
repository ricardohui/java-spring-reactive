# java-spring-reactive
demo how to use reactive Spring with Java Stream API


planefinder at localhost:7634/aircraft is the server emiting aircraft events.
The server indeed call an external service  http://192.168.1.193/ajax/aircraft to retrieve aircraft positions.
aircraft-position at localhost:8080/ aircraft is the client make use of the server.
