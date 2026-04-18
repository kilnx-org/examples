# Kilnx Examples

Runnable apps built with [Kilnx](https://github.com/kilnx-org/kilnx). Clone, run, fork.

## Catalog

| Example | Stack | LOC | Description |
|---------|-------|-----|-------------|
| [hello](hello) | `page` | 2 | Smallest possible Kilnx app |
| [chat](chat) | `model` + `auth` + `action` + `fragment` + `socket` + `stream` + `job` | ~280 | Slack-style chat with channels, threads, DMs, reactions, typing indicators, file uploads |

## Run any example

```bash
# Install Kilnx
curl -fsSL https://raw.githubusercontent.com/kilnx-org/kilnx/main/install.sh | sh

# Clone and run
git clone https://github.com/kilnx-org/examples.git
cd examples/<name>
kilnx run app.kilnx
```

Default port is `8080`. Override with `PORT=3000 kilnx run app.kilnx`.

## Deploy

Each example ships its own `Dockerfile` and/or `railway.json`. For Railway, set `rootDirectory` to the example's folder when creating the service.

## Contribute

New examples welcome. Open a PR that adds a folder with:

- `app.kilnx` as the entry point
- `README.md` with description, features, run instructions
- `Dockerfile` if the app needs extra assets (static files, seed scripts)

Keep examples small, idiomatic, and visually polished. Prefer realistic domain content over `foo`/`bar`.

## License

[MIT](https://github.com/kilnx-org/kilnx/blob/main/LICENSE)
