# Ample
## Minecraft modpack for extreme performance squeezing.

Ample attempts to improve your performance significantly out of the box in a wide amount of ways and situations, and be easily and highly configurable to increase it even more.

Outside of client performance-related mods (and some necessary configuration mods), Ample includes next to no other mods. You're free to use this modpack as a base for your own modpack.

Please mind that this modpack is highly experimental. Your mileage may vary.

## Mods in the modpack:
### [Sodium](https://github.com/CaffeineMC/sodium-fabric)
`Sodium is a free and open-source optimization mod for the Minecraft client that improves frame rates, reduces micro-stutter, and fixes graphical issues in Minecraft.`

### [Sodium Extras](https://www.curseforge.com/minecraft/mc-mods/sodium-extra)
Sodium Extras adds a number of various tweaks to Sodium. They range from QoL to various performance-enhancing settings.

### [Lithium](https://github.com/CaffeineMC/lithium-fabric)
`Lithium is a free and open-source Minecraft mod which works to optimize many areas of the game in order to provide better overall performance.`

### [Hydrogen](https://github.com/CaffeineMC/hydrogen-fabric)
`Hydrogen is a free and open-source mod designed to reduce the game's memory requirements by implementing more memory-efficient data structures and logic. It's primarily designed for more heavily modded scenarios, but can offer (small) improvements even in lightly modded or vanilla scenarios.`

### [Starlight](https://github.com/Tuinity/Starlight) (Caution advised. Might degrade performance/introduce stuttering due to being too fast. Test performance with and without it, and choose a better option.)
Starlight is a mod by the Tuinity dev that completely rewrites the vanilla light engine.

### [FerriteCore](https://www.curseforge.com/minecraft/mc-mods/ferritecore-fabric)
This mod reduces the memory usage of Minecraft in [a few different ways](https://github.com/malte0811/FerriteCore/blob/main/summary.md).

### [EntityCulling](https://www.curseforge.com/minecraft/mc-mods/entityculling) (Caution advised. May degrade performance on *very* low-end PCs.)
More aggressive entity culling in comparison to Sodium's "Use Entity Culling".
Increases CPU usage in exchange for better FPS. Might degrade performance on *very* low-end CPUs (2 cores, etc.).
Alternatively, experiment with the mod config. Refer to [this CurseForge comment](https://www.curseforge.com/minecraft/mc-mods/entityculling?comment=130).

### [Better Beds](https://www.curseforge.com/minecraft/mc-mods/better-beds)
`Removes the Block Entity Renderer from the bed and replaces it with the default minecraft model renderer. This results in increased performance and resourcepack support.`

### [Cull Leaves](https://www.curseforge.com/minecraft/mc-mods/cull-leaves)
Adds culling to leaf blocks, providing a huge performance boost over vanilla. A recreation of OptiFine's "Smart Leaves". Recommended use of Fast graphics settings or the resource pack provided by the author.

### [Dynamic FPS](https://www.curseforge.com/minecraft/mc-mods/dynamic-fps)
`Dynamic FPS automatically reduces the speed at which minecraft renders when it's not focused (to 1 FPS, configurable) or hidden (no renders at all, configurable). It also fixes a bug in Vanilla Minecraft that makes it take much more performance in the background than it should, as well as making the game not render while reloading resources (which makes it take forever on my machine!).`

### [Entity Distance](https://modrinth.com/mod/entity-distance)
`Allows the user to adjust the (client) distance at which different entities render. Distance setting for each entity can be found in the mod's Mod Menu settings. `

### [FastChest](https://www.curseforge.com/minecraft/mc-mods/fastchest)
`This mod helps by removing dynamic models from chests and making them render as static chunk geometry. (This also means they won't have their lid opening animation)`

### [Krypton](https://www.curseforge.com/minecraft/mc-mods/krypton) ([READ THE WIKI BEFORE USING ON MULTIPLAYER SERVERS.](https://github.com/astei/krypton/wiki/FAQ))
`Krypton (from Ancient Greek kryptos, "the hidden one") is a Fabric mod that attempts to optimize the Minecraft networking stack. It derives from work done in the Velocity and Tuinity projects.`

`Krypton contains several optimizations, including:`

`Highly optimized Netty handlers derived from the Velocity proxy, which I am the developer of. These handlers have sen real-world usage and extensive profiling, and strategically deploy native code where it makes the most sense.`

`Flush consolidation to lower server CPU usage (and reducing the impact from hardware security vulnerabilities which exploit speculative execution) and lower server tick times.`

`Micro-optimizations to reduce memory usage and improve packet serialization speeds.`

The impact of Krypton on client performance (as a primarily server-side mod) is unclear, but I believe it still includes a couple of decent performance improvements.

### [LazyDFU](https://www.curseforge.com/minecraft/mc-mods/lazydfu)
`LazyDFU is an optimization mod that makes the initialization of DataFixerUpper "lazy" - that is, it will not immediately create the rules required to migrate data from older versions of Minecraft to newer versions until it actually needs to do so.`

Improves startup times.

### [ResolutionControl+](https://www.curseforge.com/minecraft/mc-mods/resolutioncontrol)
`ResolutionControl+ allows you to change Minecraft's render resolution separately from the HUD elements.`

### [Smoke Suppression](https://www.curseforge.com/minecraft/mc-mods/smoke-suppression)
`This mod prevents campfires from creating any particles when certain blocks are underneath them. It affects both standard and soul campfires.
This is to prevent client-side lag and general annoyance when using large numbers of campfires in farms.`

### [Smooth Boot](https://www.curseforge.com/minecraft/mc-mods/smooth-boot)
`Optimize Minecraft loading performance to be smoother on low end systems and scale better on high end systems.`

