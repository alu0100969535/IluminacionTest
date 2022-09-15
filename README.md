# Ilumination task alu0100969535

# Reached objectives

- [x] Exterior and interior environments
- [x] Use of streaming levels for instantiating the interior level
- [] Use of a mirror object using a reflective material
- [] Pickable object that affects the game mechanics
- [] Interior environment clearly with deteriorated (old) look
- [x] Player starts near the interior enviroment in the exterior environment
- [x] Exterior environment of medium size, limited by its design
- [x] 3 Different materials for the landscape
- [] Recognizable paths with intersections. When having the pickable objets some signs will appear
- [] Game ending will be signaled in some way when reaching a spot

# Technical details

## Environments

### Interior

The interior environment meshes are taken from this Epic resource, [Edith Finch: Edie Room
](https://unrealengine.com/marketplace/en-US/product/ef-edie), which has the models ready to use and a lot of props to play with. 

The room was constructed directly using the provided walls and later on it was added the doors, doorframes, windows and a curtain to cover one window. After that some other props where placed in the room to make a interesting place to see all the ilumination effects.

- TODO: Foto del interior

#### Ilumination

Interior ilumination description

### Exterior

The exterior environment was hand made using the landscape tools in UnrealEngine. It is a default sized landscape that has some mountains to limit the visibility of the paths and intersections. There is a range of mountains placed right in the edge of the map to avoid the player getting into the limits.

- TODO: Foto del exterior

#### Ilumination

Exterior ilumniation description

#### Landscape materials

For the landscape a special layered material was created using three base materials: ForestSoil, Moss and Snow.

These three materials were downloaded from [Quixel Megascans](https://quixel.com/megascans/home/)

* TODO: Foto de los materiales individuales y del layered

#### Foliage

There is two types of foliage in this game, the bushes and the trees. The bush mesh was obtained from the StarterContent from UnrealEngine and the trees were obtained from this [resource](https://unrealengine.com/marketplace/en-US/product/interactive-spruce-forest) in the UnrealEngine Marketplace.

* TODO: Fotos de los bushes y de los arboles

#### Props

* TODO: Place rocks and other things in the map


## Player

The player model is the Countess from the game Paragon. It was downloaded from the [UnrealEngine Marketplace](https://unrealengine.com/marketplace/en-US/product/paragon-countess)

### Animations

The model came with lots of animations, but we are using only a handful for the folling scenarios:
 - movement
 - attack

* TODO: Fotos/gifs

### Actions

The player can move around the environment, interact with the doors and pickup the special object found in the house.

## Other blueprints

Any other blueprint that controls the game flow or any other aspect

# Screenshots

Capture the game and gifs of the game running