# gicLAB public website

This repository contains the public website for the gicLAB research lab:
https://giclab.dcs.gla.ac.uk/.

It uses the Jekyll static site generator, using Markdown files for content.
The site is based on the [Beautiful Jekyll template](https://beautifuljekyll.com).
We deploy using GitHub Pages, which means that any changes pushed to the
`main` branch will be automatically published.

Images are placed in the `assets/img/` folder, and can be referenced using
standard Markdown link semantics.

There is also a [pre-commit](https://pre-commit.com/) file to ensure that
Markdown files are well-formed.
See the [pre-commit configuration](.pre-commit-config.yaml) for details.
To install the pre-commit hooks, run:

```bash
pip install pre-commit
pre-commit install
```

And new files should be formatted automatically on commit.
