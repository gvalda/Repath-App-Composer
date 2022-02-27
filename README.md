# Repath application

The application in brief will provide users to set location of the potholes and obstacles by specifying their type(selectable) and risk status(selectable) /or custom type and risk and/or description. The set locations will be visible on map and open for rating/voting by the other application users (attesters/witnessers). Road fixing priority will be defined by these 3 parameters: type, risk status and total rate (maybe additional or lesser parameters).Priority results will be available to be monetarized for each city.

## Technologies

- **Programming languages**: Kotlin, Python
  - *Frameworks and Libraries*: Django
- **Storage**: PostgreSQL, ?Redis?
- **Containerization tool**: Docker
- **Version control**: Github
- **Recommended IDEs and Text editors**: VSCode, AndroidStudio
- **Project managment tool**: [Jira](https://ldva.atlassian.net/jira/software/projects/RA/boards/4/backlog)

## Installation

```bash
git clone --recurse-submodules -j8 https://github.com/yogoh31/Repath-App-Composer
```

### Running

Run mobile application directly from Android Studio.

To start backend and database services you should run Makefile:
```bash
make all
```
> For Windows running systems you have to call docker-compose file instead:
```bash
docker-compose up --build -d
```

## Documentation

### &emsp;Backend ERD implementation
[![alt text](https://github.com/yogoh31/Repath-App-Composer/blob/master/documentation/backend-erd.jpg?raw=true)](https://app.sqldbm.com/PostgreSQL/Edit/p204138/)

## License
[MIT](https://choosealicense.com/licenses/mit/)
