SNGR Creative's shareable Renovate configuration.

## How to use

In your repo's `renovate.json`:

```json
"extends": [
    "forgejo>sngrcreative/renovate-config"
]
```

Or use security-focused preset:

```json
"extends": [
    "forgejo>sngrcreative/renovate-config:security"
]
```

See [Renovate's config](https://docs.renovatebot.com/config-presets/#extending-from-a-preset).