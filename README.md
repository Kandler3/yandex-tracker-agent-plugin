# Yandex Tracker Agent Plugin

Portable plugin packaging for the [Yandex Tracker agent skill](https://github.com/Kandler3/yandex-tracker-skill).

The canonical skill source and user documentation live in the main repository. This repository contains distribution manifests and the versioned `skills/yandex-tracker/` package used by plugin and extension marketplaces.

## Gemini CLI

```bash
gemini extensions install https://github.com/Kandler3/yandex-tracker-agent-plugin --ref v1.1.0
```

## Requirements

- Python 3 and `yandex_tracker_client`.
- A Yandex Tracker OAuth token.
- Exactly one Yandex 360 or Yandex Cloud organization identifier.

See the [setup guide](skills/yandex-tracker/references/setup-and-auth.md) for credential variables and initialization.

## License

[MIT](LICENSE)
