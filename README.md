# Manual of Operations

This repository contains all procedures and guidlines for how projects, products, and consulting engagements are managed at Antonison Consulting Group.

Visit https://antonison-consulting.github.io/manual_of_operations/.
## Local Development - Running Jekyll commands

Use the following command to run gem/jekyll/bundle commands so that you can vaoid installing ruby and jekyll in your local environment
`docker run --rm --volume="$PWD:/srv/jekyll" --volume="$PWD/vendor/bundle:/usr/local/bundle" -it jekyll/jekyll:3.8.6 bash`

## Locally Develop - Use Docker-Compose

The docker-compose.yml is configured to allow you to run a container that serves jekyll locally with hot loading (meaning
it will reload when it detects changes locally).

`docker-compose up`
