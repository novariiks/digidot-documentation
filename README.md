# DigiDOT Technical Documentation

This repository contains the source files for the **DigiDOT technical documentation**.

The documentation is intended for vendors and other parties integrating with DigiDOT services, including Electronic Health Record (EHR) systems.

## Published documentation

The documentation is published using GitHub Pages:

**[DigiDOT Technical Documentation](<INSERT-GITHUB-PAGES-URL>)**

The published documentation should be used when reading the specifications. This repository contains the source files used to generate the documentation.

## Documentation structure

Documentation content is maintained as Markdown files in the [`docs/`](docs/) directory.

The site structure and MkDocs configuration are defined in [`mkdocs.yml`](mkdocs.yml).

Some technical specifications and implementation artefacts are maintained externally. For example, FHIR profiles and related artefacts may be published on Simplifier.net and referenced from this documentation.

## Contributing

Changes to the documentation should be made by updating the relevant Markdown files under `docs/`.

Changes committed to the `main` branch are automatically built and published to GitHub Pages using GitHub Actions.

Before submitting changes, ensure that:

- links and references are valid
- technical terminology is used consistently
- externally maintained specifications are referenced rather than duplicated where appropriate
- no confidential or sensitive information is included

## Building locally

The documentation site is built using [MkDocs](https://www.mkdocs.org/) with [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/).

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Start a local development server:

```bash
mkdocs serve
```

The documentation will normally be available at:

```text
http://127.0.0.1:8000/
```

## Deployment

Deployment is handled automatically by GitHub Actions when changes are pushed to the `main` branch.

The deployment workflow is defined in:

```text
.github/workflows/deploy.yml
```

## License

Licensing terms for the DigiDOT documentation will be specified separately.