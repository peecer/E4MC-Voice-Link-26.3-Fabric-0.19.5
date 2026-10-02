# E4MC Voice Link — Minecraft 26.3 / Fabric 0.19.5

Compatibility build of **E4MC Voice Bridge** for Minecraft **26.3**.

The mod carries Simple Voice Chat traffic through the existing Minecraft connection so it can work over e4mc without separate UDP port forwarding.

## Included

- `dist/e4mc-voice-bridge-1.0.2+26.3.jar` — runnable compatibility build
- `extracted/` — exact files extracted from the JAR, including compiled classes and metadata
- `SHA256SUMS.txt` — SHA-256 hashes for the JAR and extracted files

## Requirements

- Minecraft 26.3
- Fabric Loader 0.19.5+
- Fabric API 0.160.6+26.3+
- Simple Voice Chat 2.6.23+
- Java 25+
- e4mc is suggested by the mod metadata

## Source note

The supplied release JAR does **not** contain the original `.java` source files. The `extracted/` directory therefore preserves the exact compiled `.class` files and resources from the compatibility build rather than presenting decompiled output as original source.

The original mod is MIT licensed; see `LICENSE` and `extracted/LICENSE_e4mc-voice-bridge`.

## Version

Mod version: `1.0.2+26.3`
