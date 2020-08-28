---
title: Overview
summary:
authors:
    - Marc Puig
date: 2020-08-20
---

This is a collection of notes on how to apply some design concepts and patterns to create a FastAPI-based API.
For those of you who don't know what FastAPI is, I invite you to visit their [website](https://fastapi.tiangolo.com/).

> FastAPI framework, high performance, easy to learn, fast to code, ready for production

So how are the notes organized? The notes have been written and inspired by TDD (Test-Driven Development), 
creating tests with the pytest package. What does it mean?

It means that first of all I defined a list of topics that I think are basic to any API.
And for each topic, I created a single python file, started to define what needs to be tested,
and then I coded the rest.

The list of notes is:

- [Define a basic project with FastAPI and write the first tests.](00.up_and_running.md)
- [Create a data schema.](01.data_schemas.md)
- [Create a repository.](02.repository_pattern.md)
- [API with in-memory repository (and repository pattern).](03.api_with_repository.md)
- [Adding a service layer to the API.](04.service_layer_pattern.md)
- [API with sql repository, using sqlalchemy](05.sql_repository.md)
- [Project configurations.](06.settings.md)

This series of notes will explain the things I have learned from composing some FastAPI backends.
