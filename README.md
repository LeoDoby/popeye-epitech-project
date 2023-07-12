# popeye-epitech-project
The objective of this project was to introduce dockerFile and dockerCompose with a little of javascript to make an interactive poll and stock the answer in a database in docker

GENERAL DESCRIPTION
You will have to containerize and define the deployment of a simple web poll application.
There are five elements constituting the application:
- Poll, a Flask Python web application that gathers votes and push them into a Redis queue.
- A Redis queue, which holds the votes sent by the Poll application, awaiting for them to be consumed by
the Worker.
- The Worker, a Java application which consumes the votes being in the Redis queue, and stores them into
a PostgreSQL database.
- A PostgreSQL database, which (persistently) stores the votes stored by the Worker.
- Result, a Node.js web application that fetches the votes from the database and displays the result.
