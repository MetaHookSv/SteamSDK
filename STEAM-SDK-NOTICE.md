# Steamworks SDK provenance

All files were copied without source changes from Steamworks SDK v1.65
(`steamworks_sdk_165.zip`, dated 23 July 2026):

| Repository path | SDK path |
|---|---|
| `steam/*.h`, `steam/steam_api.json` | `sdk/public/steam` |
| `lib/steam_api.lib`, `bin/steam_api.dll` | `sdk/redistributable_bin` |
| `lib/steam_api64.lib`, `bin/steam_api64.dll` | `sdk/redistributable_bin/win64` |
| `bin/linux32/libsteam_api.so` | `sdk/redistributable_bin/linux32` |
| `bin/linux64/libsteam_api.so` | `sdk/redistributable_bin/linux64` |

`sdk/public/steam/lib` (encrypted app ticket libraries) is not included.

SHA-256:

- `lib/steam_api.lib`: `1f80f7a8d0f46aca691b67203e5ee6d7456d063b8a3839fb42027712a13147c1`
- `lib/steam_api64.lib`: `7b68c738457211a088bdcf583ca08a294b48345dbb59a8aa3c8c63f3646c894c`
- `bin/steam_api.dll`: `1cb8b7cb77923762d4e49b27e44295369a79e93b5d4282c5e840b268d28fe771`
- `bin/steam_api64.dll`: `e6d9bafb9a41e42fba7b21553db49f8719027af3f0deb23ff86cfc44d60e776d`
- `bin/linux32/libsteam_api.so`: `25193f895e74caf84de11babff25b6fcdc4190efa9e98dfd7a6a53e39f7d429a`
- `bin/linux64/libsteam_api.so`: `eb2dd015b84177cf4f4326fe578aab375fd8931bbbd719c7492420d9777007fe`

The previous snapshot (commit `3c1abaf`) was imported from SteamAppsLocation at `dc8dbec`.

The header files retain Valve Corporation's original copyright notices.
These third-party files are not covered by any MetaHookSv project license.
Steamworks SDK usage is governed by Valve's applicable Steamworks terms.
