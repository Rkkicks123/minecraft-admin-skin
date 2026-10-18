# Minecraft Owner Skin — Golden Shadow (Dark Gold)

This repository hosts the current Minecraft skin for the PS5 Bedrock player `.MegBoyz` through a Fabric server with Geyser/Floodgate and **Suiranoil SkinRestorer**.

## Current skin

**Golden Shadow / Dark Gold** — a real **64×64 PNG**, **Slim (Alex)**-arm model, downloaded by the owner from [its Laby skin page](https://laby.net/skins/68d71cfcda1655d034ad3f0a44b63ad1). Credit for the original skin belongs to its creator; this repository only hosts a copy for the owner's server.

- [**Golden_Shadow_Slim_64x64.png**](./Golden_Shadow_Slim_64x64.png) — skin at a unique URL, recommended to avoid caching previous versions.
- [**Modern_Owner_Admin_64x64.png**](./Modern_Owner_Admin_64x64.png) — same skin at the pre-existing live filename.
- [**Previous A-Crest Admin skin**](./skins/archive/Owner_Admin_A_64x64.png) — backup.
- [**Older versions**](./skins/archive/) — past custom designs.

## Set the new skin in the Minecraft server console

For **Suiranoil SkinRestorer**, no leading slash in the server console. **Important: use `slim`, not `classic`.**

```text
skin set web slim "https://raw.githubusercontent.com/Rkkicks123/minecraft-admin-skin/main/Golden_Shadow_Slim_64x64.png" .MegBoyz
```

The previous live URL also works with `slim`:

```text
skin set web slim "https://raw.githubusercontent.com/Rkkicks123/minecraft-admin-skin/main/Modern_Owner_Admin_64x64.png" .MegBoyz
```

Reconnect the player if the appearance does not update right away. SkinRestorer/Bedrock may cache the previous appearance.

A server-assigned skin isn't guaranteed to appear on the local PS5 client even when Java players see it. Changing this file does **not** modify or restart the Minecraft world.
