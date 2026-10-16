# DATUM Verified Store for Umbrel

An Umbrel community app store that installs **DATUM Verified** on umbrelOS. It
runs the DATUM Gateway Discord and Telegram verify bots on your own homeserver.

## Install on Umbrel

1. Open the Umbrel App Store.
2. Open **Community App Stores**.
3. Paste this URL:

```text
https://github.com/fossmining/datumverifiedstore
```

4. Install **DATUM Verified**.
5. Open the app and paste your Discord and/or Telegram bot tokens.

Members then use `/verify` in your community. The bots stay on your Umbrel and
recheck DATUM Gateway shares every 24 hours.

An official App Store submission is also open against
[getumbrel/umbrel-apps](https://github.com/getumbrel/umbrel-apps/pull/6144).

## Source

Both bots are built from one repository:
[datum-gateway-verify-bot](https://github.com/fossmining/datum-gateway-verify-bot).

- Discord bot: the repository root
- Telegram bot: the [`telegram/`](https://github.com/fossmining/datum-gateway-verify-bot/tree/main/telegram) folder
