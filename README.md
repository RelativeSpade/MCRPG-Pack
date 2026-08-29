# MCRPG Resource Pack

Public distribution repository for the MCRPG Minecraft server resource pack.

Source textures, the pack builder, and gameplay code are maintained in the private MCRPG
monorepo. This repository contains only generated channel manifests and immutable-versioned
GitHub Release assets so Minecraft clients can download packs without authentication.

## Development channel

The server reads `channels/dev.json`. Each manifest points to a versioned release asset and
includes the pack UUID and SHA-1 required by Paper and the Minecraft client.

Generated release assets and channel manifests should not be edited by hand.
