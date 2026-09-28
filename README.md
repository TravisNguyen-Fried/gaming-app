# Playlog

Playlog ranks a game library by time played and suggests a next game. It includes a sample library and can try to read public Steam profile XML without an API key.

## Open the app

Open `index.html` in a browser, then enter a Steam vanity profile name, a `steamcommunity.com/id/...` or `/profiles/...` URL, or a 17-digit SteamID64.

No API key, Steam password, server, or installation is needed.

The public profile XML includes Steam's most-played entries when available. Playlog imports those entries directly and does not request the sign-in-gated all-games page. Use **Add a game** to include other titles; manually added games are saved in this browser. The sample library remains available for profiles that don't expose game entries.

