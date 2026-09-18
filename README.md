<p align="center">
  <img src="src/client/resources/assets/findmyitems/icon.png" width="128" height="128" alt="Find My Items logo" />
</p>

<h1 align="center">Find My Items</h1>

<p align="center">
  Index opened containers, search items and crafting materials, and transfer items from one screen.
</p>

<p align="center">
  <a href="https://github.com/simply-sunny/find-my-items/releases"><img src="https://img.shields.io/badge/release-v0.1.5-black?style=flat-square&logo=github" alt="Release"></a>
  <a href="https://fabricmc.net/"><img src="https://img.shields.io/badge/loader-Fabric-black?style=flat-square" alt="Fabric"></a>
  <a href="https://adoptium.net/"><img src="https://img.shields.io/badge/java-25-black?style=flat-square" alt="Java 25"></a>
  <a href="https://github.com/TerraformersMC/ModMenu"><img src="https://img.shields.io/badge/mod_menu-supported-black?style=flat-square" alt="Mod Menu"></a>
</p>

<p align="center">
  <sub>Fabric · Minecraft 26.2 · Java 25 · client-only · local-first</sub>
</p>

---

Find My Items indexes containers you open, lets you search them from a single native screen, and transfers items without manual chest digging. Client-side only; single-player by design to prevent stale state.

- **Catalog:** search items, containers, and crafting materials (`B` by default).
- **Indexing:** tracks chests, barrels, ender chests, and placed shulkers (up to 4 levels deep).
- **Transfers:** proximity retrieval and deposit respecting vanilla reach distances.
- **Crafting:** multi-depth tree planner deducting indexed inventory.

### Quickstart

Requires Minecraft Java Edition 26.2, Fabric Loader (>=0.19.3), and Fabric API.

```bash
git clone https://github.com/simply-sunny/find-my-items.git
./gradlew clean test build
```

Place `build/libs/find-my-items-0.1.5.jar` into `.minecraft/mods`, launch Minecraft, and open any container once to begin indexing.

### License

All rights reserved · Saunak Karnati — see `fabric.mod.json`.
