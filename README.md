# Carrots Client data

Public server-list metadata used by Carrots Client. This repository contains
no launcher source code, credentials, user information, or private partner
information.

## Featured servers

Edit `featured-servers.json` to update the reviewed server list. Keep
`schemaVersion` at `1`. Every entry needs a unique lowercase ID, a Java Edition
address, factual display copy, no more than four game-mode tags, and a reviewed
placement. Exactly one server must use `FEATURED_PARTNER` while the list is not
empty.

Live status, player count, version, and favicon are read directly from the
listed Minecraft server by the launcher.
