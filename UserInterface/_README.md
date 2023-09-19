# User Interface Elements #

In Godot, User Interfaces can be considered as running parallel to the main scene,
as they are entirely separate processes in terms of engine hierarchy

Because of that, UI will often be Autoloaded from a "main" UI scene and then
components will be dynamically swapped out at runtime

A good analogy for Godot's UI system could be component-based web development:
1. Create a main `theme.tres` file to apply to all elements
2. Structure out the elements using default Control nodes
3. Save elements and their dependencies based on local scope
4. Instantiate and destroy UI elements at runtime parallel to the game

The UI should run parallel to the main game process, as it allows the UI
to signal the game world that it should be paused, while retaining its own process state