# openclaw-plane

[OpenClaw](https://openclaw.ai) plugin for [Plane.so](https://plane.so) project management.

Adds agent skills for managing issues, projects, states, labels, and pages via the [`plane-cli`](https://github.com/jzakirov/plane-cli).

## Install

```bash
openclaw plugins install @jzakirov/plane
```

### Prerequisites

The plugin requires the `plane` CLI:

```bash
uv tool install plane-cli   # recommended
# or
pip install plane-cli
```

Then configure it:

```bash
plane config init
```

Or set environment variables:

| Variable | Description |
|----------|-------------|
| `PLANE_API_KEY` | Plane API token (Settings → API Tokens) |
| `PLANE_WORKSPACE_SLUG` | Your workspace slug |
| `PLANE_BASE_URL` | API base URL (default: `https://api.plane.so`) |
| `PLANE_PROJECT` | Default project UUID (optional) |

## What's Included

| Component | Description |
|-----------|-------------|
| `skills/plane` | Agent skill teaching the `plane` CLI commands, workflows, and conventions |

## License

MIT
