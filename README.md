# VR Crafting System — MVC in Unreal Engine

A VR crafting/recipe system in Unreal Engine, built to practice a clean
Model-View-Controller separation in Blueprints.

- **Model** — `Ingredient` base Blueprint with `Cheese`, `Fruit`, `Meat`
  subclasses; recipes defined as data in `RecipeDataTable`
- **View** — `DisplayBoardUI` widget driven by the data, not hardcoded
- **Controller** — `Hopper_Controller_BP` mediates between them
- VR input via `GrabLeft_IA` / `GrabRight_IA` input actions

**Engine:** Unreal Engine · **Logic:** Blueprints

Purchased marketplace packs (`Content/Biomes`, `Content/PolygonAdventure`)
are excluded — they are licensed to me, not redistributable. Build caches
(`Binaries/`, `Intermediate/`, `Saved/`) are excluded as regenerable.
