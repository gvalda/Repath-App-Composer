# Repath application

The application in brief will provide users to set location of the potholes and obstacles by specifying their type(selectable) and risk status(selectable) /or custom type and risk and/or description. The set locations will be visible on map and open for rating/voting by the other application users (attesters/witnessers). Road fixing priority will be defined by these 3 parameters: type, risk status and total rate (maybe additional or lesser parameters).Priority results will be available to be monetarized for each city.

## Technologies

- **Programming languages**: Kotlin, Python
  - *Frameworks&Libraries*: Django, Flask
- **Storage**: PostgreSQL, Redis
- **Containerization**: Docker
- **Version control**: Github
- **Development environments**: VSCode, AndroidStudio
- **Project managment tool**: [Jira](https://tech-project.atlassian.net/jira/software/projects/RA/boards/4)

## Installation

```bash
git clone --recurse-submodules -j8 https://github.com/yogoh31/Repath-App-Composer
```

### Running

Run mobile application directly from Android Studio.

To start backend and database services you should to run Makefile:
```bash
make all
```
> For Windows running systems you have to call docker-compose file instead:
```bash
docker-compose up --build -d
```

## License
[MIT](https://choosealicense.com/licenses/mit/)
