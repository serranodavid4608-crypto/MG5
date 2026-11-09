# MG5
## Devlog
1. To use NavMesh over physical become advantageous when goal is automated pathfinding, navigating complex environments with obstacles, or managing large groups of characters due to fact that does the mathematical while physical help with physical simulation is heavy relies on gameplay. An example for a game work better with NavMesh is Diablo that doesn't need physical a lot and need the character to avoid object for good pathfinding. A game that would befit with physical Gang Beasts that need the physical for the weight and gravity that doesn't need pathfinding.
2. What going on in this loop is _birds[I] is the selector that loop steps through the array one by one using the counter It grabs the bird at that specific slot and temporarily names it bird then (bird == null) it a safety check so the game doesn't crash due to missing birds then he distance check it calculates how close the current bird is to the player and last is bird.RunAway is when the bird player are close effort the bird will run away by using position with witch direction. The purpose of Vector3.Distance calculate the exact physical gap between the current bird and the player. the birds that run away by the array is base on birds that are standing within the player's personal interaction radius.

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [Mountain fantasy environment models](https://www.fab.com/listings/60487a72-3f20-4bb2-aa78-247ed1582656)
