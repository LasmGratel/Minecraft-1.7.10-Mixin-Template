# Minecraft 1.7.10 Mod Template with Mixin

This is a dummy __modern__ Mod template with [https://github.com/SpongePowered/Mixin] shaded.

Forge version 1614 and mcp stable_12 are used.

Change `gradle.properties` to your Mod properties. Rename `mixins.dummy.json` in `src/main/resources`.

If you are using non-modid mixins name, change them in `build.gradle` line 33 and 69.

For running in IDE add these **program parameters** `--mixin mixins.(change here).json` 
Also JVM params for loading Mixin coremod `-Dfml.coreMods.load=org.spongepowered.asm.launch.MixinTweaker`