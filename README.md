# rust-postgres
## Tech stack
- sqlx (cargo install sqlx-cli)
- axum

# devContainers
- The .devcontainer folder creates a uniformed environment that allows developers to have consistency while coding. All tools, plugins, dependecies can be added to the appropriate file (Dockerfile,docker-compose, devcontainer.json) and as a result all of our environments will be the same. We can use any IDE that supports devcontainer, but VS Code has been tested.
- To connect to Postgres, Open the terminal `Ctrl + \`` and click ports. You should automatically see a green mark next to our two ports for this application, 3000 (application) 5432 (database).

