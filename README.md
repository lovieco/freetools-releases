<div align="center">

# FreeTools

### Free AI tokens from every provider — collected in one pass, ready to use.

[![Latest release](https://img.shields.io/github/v/release/lovieco/freetools-releases?label=download&color=2ea44f)](https://github.com/lovieco/freetools-releases/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/lovieco/freetools-releases/total?color=2ea44f)](https://github.com/lovieco/freetools-releases/releases)
[![macOS 14+](https://img.shields.io/badge/macOS-14%2B-000000?logo=apple)](#requirements)
[![Signed & notarized](https://img.shields.io/badge/Apple-signed%20%26%20notarized-000000?logo=apple)](#install)

</div>

---

**FreeTools** is a native macOS app that gathers the free API credit every major AI
provider gives away, keeps it in one place, and lets you put it to work — through a
single OpenAI-compatible endpoint, or right inside the app.

One pass unlocks **180+ models across ~20 providers**. No copy-pasting keys between
dashboards, no juggling twenty logins.

## Download

<div align="center">

### [⬇&nbsp; Download the latest version](https://github.com/lovieco/freetools-releases/releases/latest)

</div>

<a name="install"></a>

1. Grab **`FreeTools-<version>.dmg`** from the latest release.
2. Open it and drag **FreeTools** into your **Applications** folder.
3. Launch it — that's it.

FreeTools is distributed directly (not through the Mac App Store) so it can do things the
sandbox does not allow. Every build is signed with a Lovie **Developer ID** and
**notarized by Apple**, so Gatekeeper opens it with no scary warnings and no right-click
workaround.

<a name="requirements"></a>

**Requirements:** macOS 14 (Sonoma) or later · Apple silicon or Intel (universal build).

## What it does

- **Token Harvest** — collects the free keys providers hand out, across roughly twenty of
  them, in a single guided pass.
- **Vault** — every key stored locally in the macOS Keychain, scoped per account. Yours,
  on your machine.
- **Gateway** — one OpenAI-compatible endpoint in front of all of them. Point any tool,
  script, or IDE at it and reach every unlocked model the same way.
- **Chat & Agents** — talk to any unlocked model without leaving the app, and build agents
  that carry their own persona and tools.
- **Insights** — see at a glance what you've used and what's still free today.

## Updates

FreeTools keeps itself current. New versions are published here and installed
automatically through [Sparkle](https://sparkle-project.org) — each one signed and
notarized, each update verified against a pinned key before it installs. You download the
app once.

## About this repository

This is the public distribution channel for FreeTools. Each release carries a notarized
`.dmg` and a signed `appcast.xml`; the app reads the latest one on every launch to stay up
to date. The application source lives in a separate, private repository.

<div align="center">

Made by [**Lovie**](https://lovie.co) · © Lovie Technology Inc.

</div>
