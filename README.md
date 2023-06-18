# erNail.github.io

Static site built with `mkdocs-material`, illuminating my philosophy on Site Reliability, DevOps and Software Engineering.

## Development

Install Dependencies:

```shell
pip install -r requirements.txt
yarn global add semantic-release@21.0.5
```

Run `pre-commit` for linting:

```shell
pre-commit run --all-files --color=always --show-diff-on-failure
```

Serve `mkdocs` website:

```shell
mkdocs serve
```
