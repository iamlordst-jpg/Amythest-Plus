# Amethyst+

**A customized iOS Minecraft: Java Edition launcher, built on Amethyst.**

Amethyst+ is a community-maintained iOS launcher project based on [Amethyst-Offline](https://github.com/DumDum192/Amethyst-Offline) and [Amethyst-iOS](https://github.com/AngelAuraMC/Amethyst-iOS), with a built-in **Modrinth browser** for discovering Minecraft mods.

The goal is simple: keep the familiar Amethyst foundation while making the experience more convenient and giving the project its own identity.

## Features

- **Minecraft: Java Edition on iOS** — launch Java Edition through the Amethyst iOS foundation.
- **Built-in Modrinth browser** — discover mods from Modrinth without having to leave the launcher.
- **Custom project** — maintained as its own community fork, with its own changes and direction.
- **Automated iOS builds** — GitHub Actions builds the project and uploads the generated packages as workflow artifacts.

## Downloads

There are currently no official release downloads documented here.

To get the latest available build:

1. Open the [iOS Actions workflow](https://github.com/iamlordst-jpg/STLauncher/actions/workflows/ios.yml).
2. Select a successful workflow run.
3. Find the **Artifacts** section at the bottom of the run.
4. Download the package you need.

Build artifacts are development outputs. Availability and compatibility can vary between commits.

## Building

The iOS build is automated through GitHub Actions.

1. Open the [iOS workflow](.github/workflows/ios.yml).
2. Select **Run workflow** (or push a commit to trigger a build).
3. Wait for the workflow to finish.
4. Download the generated artifacts from the workflow run.

The workflow checks out the repository and its submodules, applies the project patches, and builds the iOS packages on a macOS runner.

## Project background

Amethyst+ is based on existing open-source work rather than being a launcher built entirely from scratch. The upstream projects provide the foundation; this repository maintains its own customizations.

- [Amethyst-Offline](https://github.com/DumDum192/Amethyst-Offline) — upstream fork and offline-oriented project.
- [Amethyst-iOS](https://github.com/AngelAuraMC/Amethyst-iOS) — iOS launcher foundation.
- [Modrinth](https://modrinth.com/) — mod discovery and distribution platform.

Please review the upstream projects' documentation and licenses when using, modifying, or redistributing their code.

## Disclaimer

Amethyst+ is an independent community project and is not an official Minecraft, Mojang, or Microsoft product. Minecraft is a trademark of Mojang Synergies AB.

---

<p align="center">
  <strong>Amethyst+</strong><br>
  <sub>Amethyst, evolved.</sub>
</p>
