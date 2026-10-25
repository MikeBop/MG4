# MG4
## Devlog
Michael Cornett

1. The FloatAnimation script works by first instantiating the moveSpeed, switchSpeed, up, and timer variables. Using Unity's Start method it sets the timer variables time to the switchSpeed value. Using Unity's built in update method to run "if else" statments to control whether to move the ball up or down. Since up didn't get assigned a starting value the bool would default to false and therefore start with the ball going down. Under that it checks if the time passed = the aloted time set, and if so it resets the timer and changes the up value to true(up) or false(down). 

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [City 3D models](https://assetstore.unity.com/packages/3d/environments/simplepoly-city-low-poly-assets-58899)
- [Bite sound effect](https://freesound.org/people/Jofae/sounds/353067/)