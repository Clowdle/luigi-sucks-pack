# Luigi Sucks Homestead

The modpack for the Luigi Sucks Homestead server (Minecraft 1.20.1, Fabric), kept in sync with [packwiz](https://packwiz.infra.link/).

## Playing
1. Install [Prism Launcher](https://prismlauncher.org/) and sign in with your Microsoft account.
2. Download `Luigi-Sucks-Homestead.zip` from this repo's **Releases** and drag it into Prism (or **Add Instance → Import**).
3. Press **Play**. The first launch downloads every mod, which takes a few minutes. After that, each launch only grabs whatever changed.

Your settings, keybinds, shaders, minimap waypoints and screenshots are never touched by updates.

## Notes
- `mods/Mekanism-Fabric-…jar` and `mods/MekanismTools-Fabric-…jar` are patched builds of the Mekanism Fabric port that fix crashes (Heat Generator placement, tooltips) and invisible Create/Supplementaries/Sophisticated models. Don't replace them with the CurseForge versions.
- Settings under `config/` are installed once and then left alone (`preserve = true`), except the FerriteCore and ModernFix configs, quests, and OpenLoader packs, which the pack keeps in sync.
