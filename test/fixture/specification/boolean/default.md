# Environment Variables

This document describes the environment variables used by `<app>`.

Please note that **undefined** variables and **empty strings** are considered
equivalent.

The application may consume other undocumented environment variables; this
document only shows those variables defined using [Austenite].

[austenite]: https://github.com/eloquent/austenite

## Index

-   [`DEBUG`](#DEBUG) — enable or disable debugging features

## Specification

### `DEBUG`

> enable or disable debugging features

This variable **MAY** be set to one of the values below. If left undefined the
default value of `false` is used.

```bash
export DEBUG=true
export DEBUG=false # (default)
```
