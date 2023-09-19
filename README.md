# Godot 4 Project Template #

## Disclaimer
This is a heavily opinionated template created based on some Godot gamedev experience -
the structure and convention of the project isn't set in stone, and if it doesn't work for you,
feel free to modify it - those are just good practices to use in the engine that I've picked up

## General advice
Make sure to organize your files based on context, not filetype -
house your scripts, assets and resources with the scene that uses them - you can do both,
which would look a bit like:
- SceneName
  - SceneName.tscn
  - _Dependencies
    - Scripts
    - Assets

Because Godot doesn't use any generated files, this approach will allow you to quickly
move entire functional objects between projects without any issue - it also makes more sense
given Godot's purely tree-based hierarchy

[ more to be added ]