# nextendo-crash-team-racing (nx-mod testing)

nx-mod's `testing` fork of [nextendo-demonware](https://github.com/NextendoNetwork/nextendo-demonware), used in
[nextendo-testing](https://github.com/nx-mod/nextendo-testing) for **Crash Team Racing Nitro-Fueled** (it serves
Diablo III too). Upstream's README is kept as [README.upstream.md](README.upstream.md).

- Crash Team Racing (Demonware title 5775): login with signed auth replies, async matchmaking, friend sessions,
  rich presence. Needs `CTR_AUTH_SIGNING_KEY` (RSA-2048) whose public half is in the CTR client mod.
- Same ports and hosts as Diablo III's server (auth behind sni-router, lobby and NAT on 3074): run this or
  [nextendo-demonware-nx](https://github.com/nx-mod/nextendo-demonware-nx) on one stack, not both.

## nx-mod changes

None: `testing` tracks upstream unchanged.

## Credits

- **nx-mod**: the Demonware server for Diablo III this is built on.
- **CollectingW**: Crash Team Racing support.
- **The Nextendo Network team**: the network it runs on — https://nextendo.network.

Nextendo is awesome.
