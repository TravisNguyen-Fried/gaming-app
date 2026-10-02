# Playlog

Playlog ranks a game library by time played and suggests a next game. It includes a sample library and can try to read public Steam profile XML without an API key.

## Open the app

Open `index.html` in a browser, then enter a Steam vanity profile name, a `steamcommunity.com/id/...` or `/profiles/...` URL, or a 17-digit SteamID64.

No API key, Steam password, server, or installation is needed.

The public profile XML includes Steam's most-played entries when available. Playlog imports those entries directly and does not request the sign-in-gated all-games page. Use **Add a game** to add another title; Playlog checks the exact name against the Steam store before saving it. Manually added games are saved in this browser. **Reset games** clears the current library and connected profile so you can start fresh. The sample library remains available until you reset it or connect a profile.

