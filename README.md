# Akka Persistence Typed Talk

Live talk is [here](https://www.reddit.com/r/ScalaConferenceVideos/comments/dhnpj2/scala_italy_akka_persistence_typed_renato/)

Slides are in Markdown and tailored for [Deckset](https://www.deckset.com/).
PDF version is available [here](presentation.pdf)

Demo uses Postgres (in docker) and [Akka Persistence JDBC](https://github.com/dnvriend/akka-persistence-jdbc)

## Create docker image

This image creates the DB with the schema for journal and snapshot in place. Just use it!

```
cd docker
docker build  -t akka-jdbc-postgres .
cd ../
```

 ## Create container

 User docker-compose.yml

 ```
 docker-compose up -d
 ```
