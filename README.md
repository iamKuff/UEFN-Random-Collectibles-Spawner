# UEFN Random Collectibles Spawner

A powerful and flexible Verse device for Fortnite Creative that allows you to spawn collectible items at random positions on a customizable plane. This tool is perfect for creating engaging gameplay mechanics such as treasure hunts, resource gathering, or simply populating your island with dynamically placed objects.

## CREDITS
- [Get Some Random Positons On A Plane](https://dev.epicgames.com/community/snippets/RwMR/fortnite-get-some-random-positons-on-a-plane) BY [CHENSHUO.L](https://dev.epicgames.com/community/profile/qBoAL/CHENSHUO.L)

## Features

- Spawn any prop or device at random positions
- Customizable plane dimensions (start and end positions)
- Support for both vertical and horizontal planes
- Adjustable item size to prevent overlapping
- Configurable number of items to spawn
- Error handling to prevent spawning more items than the plane can accommodate

## How to Use

1. Clone or download this repository
2. In Fortnite Creative, create a new Verse device
3. Copy the contents of `random_collectibles_spawner_device.verse` into your new device
4. Configure the device properties:
   - `ItemToSpawn`: The prop or device you want to spawn
   - `NumberOfItemsToSpawn`: How many items should be spawned
   - `PlaneStartPosition`: The starting corner of your spawn plane
   - `PlaneEndPosition`: The opposite corner of your spawn plane
   - `ItemSize`: The size of your spawned items (used to prevent overlapping)
   - `IsVerticalPlane`: Set to true for a vertical plane, false for horizontal
5. Place the device in your island
6. Start the game - items will be spawned automatically!

## Customization

Feel free to modify the code to suit your specific needs. You can add additional functionality, such as:

- Spawning different types of items
- Adding interaction with spawned items
- Creating respawn mechanics for collected items

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/iamKuff/UEFN-Random-Collectibles-Spawner/issues) if you want to contribute.
