# Attractions Bald Traveler
The Attractions Backend is responsible for handling all requests for users and places.

Users use the system and need to authenticate with the backend to make changes or add new places.

Places are venues, parks, museums, restaurants, hotels, etc that users feel are worth visiting.

[![Java CI with Maven](https://github.com/Bald-traveler/attractionsAppUsersMS/actions/workflows/maven.yml/badge.svg)](https://github.com/Bald-traveler/attractionsAppUsersMS/actions/workflows/maven.yml)
## User Service
This is the User microservice.  

This Service Provides the following functionality

- user creation (Not Implemented)
- user detail retrieval (Not Implemented)
- login (Not Implemented)
- user update (Not Implemented)
- user deletion (Not Implemented)

### Testing
All functionality must have unit tests.  All MVC functionality needs integration tests.

```bash
mvn clean test
```

### Building

```bash
mvn clean install
```

### Installation/Running

```bash
java -jar attractionAppUserMsApplication-<version>.jar
```
