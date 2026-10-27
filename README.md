# Thaumcraft 4R

**Thaumcraft 4's magic for modern Minecraft.**

English · [简体中文](README.zh-CN.md)

[Downloads and releases](https://github.com/thaumcraft-port/thaumcraft-4r/releases)

Thaumcraft 4R brings the research, discovery, and magical experimentation of Thaumcraft 4 to modern Minecraft. Scan the world for aspects, unlock knowledge in the Thaumonomicon, craft and upgrade wands, study aura nodes, and build an alchemical workshop. Infusion opens the way to powerful equipment, while flux, taint, and warp give forbidden research its consequences.

This is the download home for compiled Thaumcraft 4R builds and the companion addons included in each release. Builds appear on the Releases page as they are published; choose a runtime bundle to play, or an API/source archive for development.

## What awaits you

- **Research and discovery.** Use the Thaumometer to investigate the world and develop your understanding of its aspects. Follow the Thaumonomicon through an expanding body of magical knowledge.
- **Wands and aura nodes.** Gather vis, work with different wand materials, and use wand foci to turn your research into practical magic.
- **Alchemy and infusion.** Separate and transport essentia, automate your workshop, and perform infusion crafting to create magical tools and equipment.
- **Exploration and its risks.** Encounter magical creatures, strange places, and the effects of taint and warp as your studies progress.
- **A connected addon ecosystem.** Extend your playthrough with companion mods such as Thaumic Tinkerer, Forbidden Magic, Tainted Magic, Nodal Mechanics, Warp Theory, and Thaumic Bases. Check each release for its exact contents.

## Choose your version

| Minecraft | Mod loader | Java | Runtime download |
| --- | --- | --- | --- |
| 1.20.1 | Forge | 17 | `1.20.1-forge-<build>.zip` |
| 1.21.1 | NeoForge | 21 | `1.21.1-neoforge-<build>.zip` |

Open the [Releases page](https://github.com/thaumcraft-port/thaumcraft-4r/releases) and choose the runtime ZIP for your Minecraft version and loader. Each runtime ZIP contains the compiled mod JARs directly at its root. The release notes list the included mods and file checksums.

Matching **API and source archives** are provided as `<platform>-<build>-dev.zip`, with development JARs grouped by mod. These are for addon development and reference; players should install the runtime ZIP instead.

## Installation

1. Create a Minecraft instance with the matching version, loader, and Java version shown above.
2. Install **Curios** and **TerraBlender** from the table below. These dependencies are not included in the ZIP. Other integrations are optional; install their own required dependencies too.
3. Download and extract the matching runtime ZIP. Place the JARs in your instance’s `mods` folder.
4. Keep the core and addons from the same release together. When updating, remove their old JARs to avoid duplicate versions, then restart the game or server.

The bundles include Thaumcraft 4R and a selection of addons, rather than a complete Minecraft modpack. If you only want the core, install its `thaumcraft` JAR and the required dependencies. The included addons are optional; Forbidden Magic and Thaumic Bases also require Thaumic Tinkerer. Other mods in your instance can remain in place.

Thaumcraft 4R is under active development. Back up existing worlds before updating, and check release notes for changes or known issues.

## Dependencies and integration versions

Checked on **2026-10-27** against the interfaces we use, official published JARs, and loader dependency requirements. Ranges include both endpoints and only refer to published files for the matching Minecraft version and loader. The right endpoint is the newest version checked here, not a claim that later versions are incompatible. **API checks do not establish that every feature or modpack combination has been tested in game.**

| Mod | Minecraft 1.20.1 · Forge | Minecraft 1.21.1 · NeoForge | Integration and requirements |
| --- | --- | --- | --- |
| [Curios](https://modrinth.com/mod/curios/versions) | **5.14.1+1.20.1** | **9.5.1+1.21.1** | Required by the core |
| [TerraBlender](https://modrinth.com/mod/terrablender/versions) | **3.0.1.10–3.0.1.11** | **4.1.0.8** | Required by the core |
| [JEI](https://modrinth.com/mod/jei/versions) | **15.56.0.202–15.74.0.230** | **19.36.0.360–19.70.0.460** | Recipes, aspects, and block previews; includes upstream Beta builds |
| [Jade](https://modrinth.com/mod/jade/versions) | Core: **11.13.0–11.13.3**; with Thaumic Tinkerer: **11.13.2–11.13.3** | Core: **15.10.5–15.10.6**; with Thaumic Tinkerer: **15.10.6** | Block information and custom rendering; choose the matching loader file |
| [Crafting Tweaks](https://modrinth.com/mod/crafting-tweaks/versions) | **18.2.0–18.2.9** | **21.1.1–21.1.11** | Workbench buttons; requires the matching Balm version |
| [KubeJS](https://modrinth.com/mod/kubejs/versions) | **2001.6.3-build.18–2001.6.5-build.26** | **2101.7.2-build.270–2101.7.2-build.377** | Recipes and scripting; includes some prereleases |
| [Rhino](https://modrinth.com/mod/rhino/versions) | **2001.2.2-build.6–2001.2.3-build.10** | With the latest KubeJS: **2101.2.7-build.81–2101.2.8-build.91** | Required by KubeJS; build.91 is Beta. Forge KubeJS also requires Architectury **9.1.12 or newer** |
| [Applied Energistics 2](https://modrinth.com/mod/ae2/versions) | **15.4.10–15.4.11** | **19.2.17–19.2.18** | Thaumic Tinkerer, Thaumic Energistics, and related integrations; requires GuideME (**20.1.7–<20.2** on Forge, **21.1.1 or newer** on NeoForge) |
| [Botania](https://modrinth.com/mod/botania/versions) | **1.20.1-450–1.20.1-456** | **No matching published release** | Thaumic Tinkerer and Forbidden Magic integration. Forge requires Patchouli **1.20.1-83 or newer**; NeoForge development snapshots are not installable releases |
| [CC: Tweaked](https://modrinth.com/mod/cc-tweaked/versions) | **1.116.1–1.120.2** | **1.120.2** | Thaumic Tinkerer peripherals; upstream labels 1.120.2 as Alpha |
| [Blood Magic](https://modrinth.com/mod/blood-magic/versions) | **3.3.4-46–3.3.8-50** | Use NeoVitae below | Forbidden Magic integration |
| [NeoVitae](https://modrinth.com/mod/neovitae/versions) | — | **1.1.34–1.1.48** | Forbidden Magic integration |
| [Mana and Artifice](https://modrinth.com/mod/mana-and-artifice/version/odH1eB1x) | **3.1.11** | — | Forbidden Magic integration |

## More addons

The [Thaumcraft 4R addon distribution and index](https://github.com/thaumcraft-port/thaumcraft-addons) lists additional companion and integration mods. Match both the Minecraft version and the Thaumcraft 4R build requirements when adding them to your instance.

## Credits

Thaumcraft was originally created by **Azanor**. Thanks to everyone who contributes to Thaumcraft 4R and its companion addons. Credit for the original mod, its artwork, and each companion addon belongs to their respective authors and contributors.
