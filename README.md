# PDM Workspace Examples

This repo shows different potential file structures for PDM Workspace feature.

Welcome to PR your proposals :)

> Tracking issue:
> [Workspace support #1505](https://github.com/pdm-project/pdm/issues/1505)

## Example 01

```
.
├── packages
│   ├── bar
│   │   └── pyproject.toml
│   └── foo
│       └── pyproject.toml
└── pyproject.toml
```

## Example 02

```
.
├── docs
├── package-01
│   ├── docs
│   ├── pyproject.toml
│   ├── src
│   │   └── mynamespace
│   │       └── foo
│   └── tests
├── package-02
│   ├── docs
│   ├── pyproject.toml
│   ├── src
│   │   └── mynamespace
│   │       └── bar
│   └── tests
├── package-03
│   ├── docs
│   ├── mynamespace
│   │   └── baz
│   ├── pyproject.toml
│   └── tests
├── package-04
│   ├── docs
│   ├── pyproject.toml
│   ├── src
│   │   └── package_04
│   └── tests
├── package-05
│   ├── docs
│   ├── package_05
│   ├── pyproject.toml
│   └── tests
├── pyproject.toml
└── tests
```
