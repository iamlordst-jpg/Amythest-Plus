# Amethyst+

**A more capable Minecraft: Java Edition launcher experience for iOS.**

Amethyst+ is an independent, community-maintained project built on the Amethyst iOS launcher foundation. It extends the familiar launcher with a native-feeling mod discovery and download experience, bringing together **Modrinth and CurseForge** in one place.

The feature-rich implementation is currently developed on the **[`experimental-stlauncher` branch](https://github.com/iamlordst-jpg/STLauncher/tree/experimental-stlauncher)**. Select that branch when building to try the full ST Mod Browser feature set.

## Features

### Unified Mod Browser

- Search Minecraft projects on **Modrinth and CurseForge**.
- Browse project details, descriptions, galleries, versions, dependencies, and downloadable files.
- View project images in an in-app gallery.
- Filter results by Minecraft version and mod loader.
- Sort by relevance, download count, or recently updated.
- Browse a cleaner native iOS interface with dedicated filter controls.
- Cache project icons and thumbnails to reduce repeat loading while browsing.

### More than mods

With **Advanced Mod Search** enabled, the browser can also discover:
- Resource packs
- Shaders
- Data packs

Advanced Search also exposes Modrinth client/server compatibility filters. It is an optional setting and is off by default.

### Download Manager

- Track downloads with status and progress information.
- Keep downloads running in the background when **Background Downloads** is enabled.
- Review downloads and downloaded files from the Download Manager.
- Open the saved-file location and remove downloaded files or history entries.
- Avoid overwriting an existing file when the same filename is downloaded again.
- Organize saved files under `Documents/ST Mod Browser/` by project type.

Downloads are saved as files; they are **not automatically installed** into a Minecraft instance.

### Library: Favorites & Collections

- Save projects to Favorites.
- Create named Collections to organize projects.
- Add projects to collections from the project actions.
- Revisit saved projects from the Library.

Favorites and Collections are enabled by default.

### Optional Turbo Downloads

Turbo Downloads is an optional setting, off by default. When enabled, it raises the per-host connection limit, gives download tasks higher priority, and allows more time for transfers to finish. Actual download speed still depends on the server and your network.

## Building on iPhone

Amethyst+ uses GitHub Actions to build iOS packages, so you can start a build directly from an iPhone without needing a Mac.

1. Open the [iOS Actions workflow](https://github.com/iamlordst-jpg/STLauncher/actions/workflows/ios.yml).
2. Choose the **`experimental-stlauncher`** branch in the branch selector.
3. Run the workflow, or open an existing successful run.
4. Download the IPA from the run's **Artifacts** section.
5. Install and sign it with your usual iPhone workflow, such as LiveContainer or SideStore.

Build artifacts are development builds. Their availability and compatibility can change between commits.

## Project status

The full ST Mod Browser feature set described above is on the **[`experimental-stlauncher` branch](https://github.com/iamlordst-jpg/STLauncher/tree/experimental-stlauncher)**. The default `main` branch may not contain the same set of changes yet. Check the branch you select before building.

## Credits & foundations

Amethyst+ builds on existing open-source projects and acknowledges their original work:

- [Amethyst-Offline](https://github.com/DumDum192/Amethyst-Offline)
- [Amethyst-iOS](https://github.com/AngelAuraMC/Amethyst-iOS)
- [Modrinth](https://modrinth.com/)
- [CurseForge](https://www.curseforge.com/)

Please review the upstream projects' documentation and licenses when using, modifying, or redistributing their code.

## Disclaimer

Amethyst+ is an independent community project. It is not affiliated with or endorsed by Mojang Studios, Microsoft, Modrinth, or CurseForge. Minecraft is a trademark of Mojang Synergies AB.

---

<p align="center">
  <strong>Amethyst+</strong><br>
  <sub>Amethyst, evolved.</sub>
</p>
