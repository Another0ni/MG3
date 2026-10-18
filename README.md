# MG3
## Devlog
1. I checked the inspector after declaring a float, int, bool, and string variable. The default values for the float and int were both 0 but the bool and string were blank. I assume this means the default value for a bool is “false” and the default value for a string is “”.
2. The Update method is called every frame by Unity. Calling the Update method manually within the assignment is redundant and not recommended.
3. The KickWeapon class uses the Timer class to call the IsFinished method. The KickWeapon class checks if the time is finished every frame within the Update method as it’s being called by Unity.


## Open-Source assets
- [Cat fighter spritesheet](https://opengameart.org/content/cat-fighter-sprite-sheet)
- [Food sprites](https://rcpstd.itch.io/pixel-food-pack)
