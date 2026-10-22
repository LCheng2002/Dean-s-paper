# International Journal of Hydrogen Energy migration template

This directory registers the official IJHE Guide for Authors URL and provides a local, reusable LaTeX migration scaffold using Elsevier's `elsarticle` class.

- `source/guide-for-authors.url`: retained official guide URL
- `SOURCE.md`: provenance and verification status
- `requirements.md`: verified rules and items to recheck
- `latex-migration/project/`: compilable local scaffold

Template ID: `ijhe-elsarticle-year-unverified`.

Create an independent submission version from the workspace root:

```bash
./paper templates
./paper new my-topic my-version --template ijhe-elsarticle-year-unverified
./paper build my-version
```

Before Editorial Manager source submission, run the flattening checklist in `requirements.md`: Elsevier's system may not resolve source subfolders even though the local workspace intentionally uses them.
