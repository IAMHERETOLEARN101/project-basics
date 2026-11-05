# Generic local setup

## Preview this repository

Install Git and Python 3, then clone this repository using its GitHub clone URL.

From the repository directory:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Open http://127.0.0.1:8000 to browse files. Markdown remains plain text in this simple file server; GitHub renders it.

## Try the JSON templates

```sh
python3 -m json.tool examples/project-config.example.json
python3 -m json.tool examples/analysis-request.example.json
python3 -m json.tool examples/permission-review.example.json
python3 -m json.tool examples/driver-plan.example.json
```

Copy a template to a file ending in .local.json when adapting it for local use. Those files are ignored by Git. Use synthetic data while experimenting.

## Project prerequisites

- Static website concepts: a browser and a local static server.
- Data analysis concepts: Python and synthetic tabular files.
- CRM component development: the platform's official development tools and a separate test environment.
- Native JSON templates: a text editor; no service credentials are needed.

The application source and dependency manifests are intentionally absent, so these steps preview the public documentation and templates only. They do not install, run, or deploy the private projects. Keep authentication outside this repository and follow the relevant platform's official setup documentation for independent implementations.
