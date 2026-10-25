# MG4
## Devlog
FloatAnimation

The FloatAnimation script makes the fish food move up and down in the game. The Start() method sets the `_timer` variable to `_switchSpeed` when the game begins. This determines how long the food moves in one direction before switching.

The Update() method runs every frame and controls the movement of the food. The `_up` variable is a boolean that decides the direction. When `_up` is true, the food moves upward. When it is false, the food moves downward. The `_moveSpeed` variable controls how fast the food moves.

The `_timer` decreases every frame using Time.deltaTime. When it reaches zero, it resets to `_switchSpeed`, and `_up` changes to the opposite value. This makes the food continuously move up and down.

Overall, these variables and methods work together to create the floating animation for the fish food.

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [City 3D models](https://assetstore.unity.com/packages/3d/environments/simplepoly-city-low-poly-assets-58899)
- [Bite sound effect](https://freesound.org/people/Jofae/sounds/353067/)