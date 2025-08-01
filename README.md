
<img width="1190" alt="maybe_hero" src="https://github.com/user-attachments/assets/5ed08763-a9ee-42b2-a436-e05038fcf573" />

#  FORK FROM "Maybe: The personal finance app for everyone"

# This repo is **not affiliated with or endorsed by** Maybe Finance Inc.

> [!IMPORTANT]
> This repository is no longer actively maintained. You can read more about this in our [final release](https://github.com/maybe-finance/maybe/releases/tag/v0.6.0).

## Maybe Hosting

Maybe is a fully working personal finance app that can be [self hosted with Docker](docs/hosting/docker.md).

## Forking and Attribution

This repo is no longer maintained. You’re free to fork it under the AGPLv3. To stay compliant and avoid trademark issues:

- Be sure to include the original [AGPLv3 license](https://github.com/maybe-finance/maybe/blob/main/LICENSE) and clearly state in your README that your fork is based on Maybe Finance but is **not affiliated with or endorsed by** Maybe Finance Inc.
- "Maybe" is a trademark of Maybe Finance Inc. and therefore, use of it is NOT allowed in forked repositories (or the logo)

## Local Development Setup

**If you are trying to _self-host_ the Maybe app, stop here. You
should [read this guide to get started](docs/hosting/docker.md).**

The instructions below are for developers to get started with contributing to the app.

### Requirements

- See `.ruby-version` file for required Ruby version
- PostgreSQL >9.3 (ideally, latest stable version)

After cloning the repo, the basic setup commands are:

```sh
cd maybe
cp .env.local.example .env.local
bin/setup
bin/dev

# Optionally, load demo data
rake demo_data:default
```

And visit http://localhost:3000 to see the app. You can use the following
credentials to log in (generated by DB seed):

- Email: `user@maybe.local`
- Password: `password`

For further instructions, see guides below.

### Setup Guides

- [Mac dev setup guide](https://github.com/maybe-finance/maybe/wiki/Mac-Dev-Setup-Guide)
- [Linux dev setup guide](https://github.com/maybe-finance/maybe/wiki/Linux-Dev-Setup-Guide)
- [Windows dev setup guide](https://github.com/maybe-finance/maybe/wiki/Windows-Dev-Setup-Guide)
- Dev containers - visit [this guide](https://code.visualstudio.com/docs/devcontainers/containers) to learn more

## Copyright & license

Maybe is distributed under
an [AGPLv3 license](https://github.com/maybe-finance/maybe/blob/main/LICENSE). "
Maybe" is a trademark of Maybe Finance, Inc.
