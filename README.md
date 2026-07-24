# Renovate Config

[![GitHub License](https://img.shields.io/github/license/glitch452/renovate-config)](https://choosealicense.com/licenses/mit/)
[![GitHub Release](https://img.shields.io/github/v/release/glitch452/renovate-config) ](https://github.com/glitch452/renovate-config/releases)

Reusable preset configurations for the [Renovate](https://www.mend.io/renovate/) dependency management bot.

## Branching Strategy

The `release` branch is the main branch of this repository — it is the branch that Renovate configs should reference,
and it always reflects the latest published release.

All changes must be made via a pull request into the `develop` branch. Changes are not made directly against `release`.
Once a change is merged into `develop`, the [Release GitHub Actions workflow](.github/workflows/release.yml)
automatically publishes it to the `release` branch — there is no manual step required to port changes over.

## License

The scripts and documentation in this project are released under the [MIT License](LICENSE) as defined by the
[Open Source Initiative](https://opensource.org/license/mit).
