# .github

Organization-wide shared configuration for the [ublacklist](https://github.com/ublacklist) organization.

## Renovate

- `renovate-config.json` — the shared Renovate preset. Each repository references it from its own `renovate.json` via `extends: ["github>ublacklist/.github:renovate-config"]`.
- `.github/workflows/renovate.yml` — the self-hosted runner that updates the `ublacklist/*` repositories in one place.
