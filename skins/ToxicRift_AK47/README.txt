ToxicRift_AK47
Made with H1Z1 Asset Studio (its skin builder) from Weapons_AK47Classic.adr.

Black volcanic stone split by glowing green lava cracks, with the rock scorched dark along them.
Smoke rolls up over the gun, thickest over the cracks, and green sparks rise out of it.

A weapon skin of its own: nothing in the game is replaced. Every file, and every name inside the files, belongs to this skin.

Model/       ToxicRift_AK47.adr (first person), ToxicRift_AK47_3P.adr (third person), ToxicRift_AK47_OnGround.adr (on the ground)
             and their meshes (.dme) and palettes (.dma), every level of detail
Animation/   The game's own Multiscroll effect: ActorCompositeEffectDefinitions.xml and ActorModelMaterialDefinitions.xml
Icon/        ToxicRift_AK47_Icon.dds
ToxicRift_AK47_C.dds          The skin's colour texture (first person, third person and on the ground)
ToxicRift_AK47_N.dds          Normal maps. Their blue channel says where the moving layer shows (full over the cracks,
ToxicRift_AK47_N_2.dds        about half on the rest of the gun); red is set to the middle.
ToxicRift_AK47_Texture_2.dds  Moving layer 1: smoke rising
ToxicRift_AK47_Texture_4.dds  Moving layer 2: green sparks rising

MOVING LAYER SETTINGS (Animation/ActorModelMaterialDefinitions.xml)
brightness1 1 (smoke), brightness2 7.5 (sparks), bloomReduction 4.7, uvTiling 3.5 3.5 5 5, uvScroll -0.08 0.012 -0.18 0.02

If the smoke is too strong or too faint in game, change brightness1 (both views are listed) and import again.

GLOW
The moving layer's strength was turned down to match how bright it really shows in game (bloomReduction 4.7,
as on the game's own animated skins). If you want more glow, raise brightness1 and brightness2 a little at a time.

SKIN TESTER

1. Click Import ZIP and pick this file. It finds the AK-47 by itself.
2. For the inventory picture, click Choose icon and pick Icon/ToxicRift_AK47_Icon.dds from this folder.
3. Select the skin and click Test in game.
4. In game, open CUSTOMIZE and equip the skin on the AK-47, then PLAY > SOLO.

NOTES

- The smoke is drawn on the gun's surface by the game's Multiscroll effect; an imported skin can't add real smoke particles in the air.
- The on-the-ground model's material has no Multiscroll effect in the game files, so on the ground it shows the still skin.
