# tasks

The app from the [Kilnx README](https://github.com/kilnx-org/kilnx#readme): a per-user task list with registration, login, password reset, pagination and inline htmx delete.

Kilnx owns the auth logic (bcrypt, sessions, CSRF, reset tokens). The app owns the HTML of every page, including `/login`, `/register`, `/forgot-password` and `/reset-password`.

## Run

```bash
kilnx run app.kilnx
# http://localhost:8080/register
```

Requires Kilnx v0.1.5 or later.
