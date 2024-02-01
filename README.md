# pyupgrade pre-commit hook

pre-commit hook of pyupgrade with conda as a `language` / package manager.

For pre-commit: see [here](https://github.com/pre-commit/pre-commit)

For pyupgrade: see [here](https://github.com/asottile/pyupgrade)

## Using pyupgrade with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/quantco/pre-commit-mirrors-pyupgrade
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: pyupgrade-conda
```
