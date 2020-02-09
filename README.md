# Sakura Wallet Documentation

`docs` is source code for the [Sakura Documentation](https://sakura.readthedocs.io/).

This `docs` is built with [MkDocs](https://www.mkdocs.org/) and [Read the Docs](https://readthedocs.org/).

## Running locally

Note that you will need the `pip` package manager, which is generally installed with Python.

Clone the repository to your local file system.

```bash
git clone https://github.com/dotpaytech/docs.git
```

Install `mkdocs` by using the `pip` package manager.

```bash
pip install mkdocs --user
```

Now install all necessary dependencies, once again by using `pip`.

```bash
pip install -r requirements.txt
```

Run `mkdocs serve` from the repository root to spawn a hot reloading development server and navigate to `localhost:8000` in a web browser.

## Publishing

The wiki is hosted on [Read the Docs](https://readthedocs.org) and is built on each published commit to the master branch on the GitHub repository.

## Styling

[Mkdocs-Material](https://squidfunk.github.io/mkdocs-material/) is used to give the wiki its sleek theme.

### Adding a new page

If you add a page please ensure that you give it the correct placement in the navigation by manually inputting it in the `mkdocs.yml` under the `nav` field. It is done in this way in order to have more control in how pages are displayed on the UI and give better organization to topics.
