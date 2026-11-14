# Optimizari FPS pentru MoonCity (Forge 1.20.1)

Nu scriem optimizari proprii (ar iesi mai slabe). Pune aceste moduri langa mooncity.jar:

| Mod | Ce face |
|---|---|
| Embeddium | randare mult mai rapida (Sodium pentru Forge) |
| FerriteCore | consum mic de RAM |
| ModernFix | pornire rapida, mai putin lag si RAM |
| Entity Culling | nu randeaza ce nu se vede |
| Dynamic FPS | FPS mic cand fereastra nu e activa |
| Oculus | doar daca vrei shadere |

Setari recomandate (Video Settings): Render Distance 8-10, Simulation Distance 6, Entity Distance 75%, Particles Minimal.
Java: `-Xmx4G -Xms2G` (sau 6G cu multe mod-uri).

In mod-ul MoonCity: HUD-ul cacheaza ora (se recalculeaza o data pe secunda), iar datele se trimit o data pe secunda, nu la fiecare tick.
