# Furnace — public downloads

This repository hosts Furnace release downloads only. The source code is not here.

## Install (v0.6.0-alpha.1)

```sh
mkdir furnace-alpha && cd furnace-alpha && curl -fsSL https://github.com/vyshwas/furnace-dist/releases/download/v0.6.0-alpha.1/furnace-v0.6.0-alpha.1.tgz | tar xz && ./install.sh
```

SHA-256: `5424890ecaf0a68ca0f62e80c91559691a8559d4b188e03acaa210487da02d97`

Requires Node.js 24+ and a POSIX shell (Git Bash on Windows). Install it in its own folder, not inside your app's repository.

Furnace is paid from the first project. Signing in with GitHub (`furnace claim`) is free; checking a project needs a plan: the Launch Audit ($299 once, a person checks every finding, includes 30 days of Pro) or Pro ($19 per project per month). Prices and how to pay: https://vyshwas.github.io/furnace-site/#pricing

A code check sends nothing anywhere; the first run on a project asks the access server whether it is covered by a plan. Each release includes signed release details, the public key to check them, and a list of included packages. See the release notes for how to verify.

Licence: Furnace Alpha Licence v2, included as `LICENSE` in each download. It is not open source.

Questions, payments or security reports: vyshwas.work@gmail.com, or open an issue in this repository.
