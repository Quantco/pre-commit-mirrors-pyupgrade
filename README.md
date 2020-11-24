pyupgrade(-conda) mirror
========================

Mirror of pyupgrade for pre-commit with conda as a language.

* For pre-commit: see https://github.com/pre-commit/pre-commit
* For pyupgrade: see https://github.com/asottile/pyupgrade

### Using pyupgrade with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/Quantco/pre-commit-mirrors-pyupgrade
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: pyupgrade-conda
```

