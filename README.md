# Creating Real-Time Charts with FastAPI

Sample application for the blog [Creating Real-Time Charts with FastAPI](https://ron.sh/creating-real-time-charts-with-fastapi/)

## Demo

Go to https://fastapi.ron.sh/ to see this in action.

## Build and run

```bash
docker compose build
docker compose up  # or "docker compose up -d" to run in detached mode
```

Open http://127.0.0.1:5000/ in browser

## Development

Dependencies are managed with [uv](https://docs.astral.sh/uv/) and tasks are run with
[Task](https://taskfile.dev/).

```bash
task install
task format
task lint
```

## Author

[Ronie Martinez](mailto:ronmarti18@gmail.com)

## References

- [Creating Real-Time Charts with Flask](https://github.com/roniemartinez/real-time-charts-with-flask)
