# Navitia hooks for pre-commit

[pre-commit](http://pre-commit.com).

## Installation
```sh
pip install pre-commit
pre-commit install
```

## Using the hooks

```yaml
-   repo: git@github.com:CanalTP/navitia-pre-commit.git
    rev: master
    hooks:
    -   id: clang-format
```
