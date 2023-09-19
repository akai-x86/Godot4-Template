# Stages #

Due to Godot already using the term Scenes to refer to virtually everything,
this folder is labeled "Stages"

A Stage is essentially a type of a playground or a larger gameplay scene,
in which Physics objects, Gameplay props, and Common files

What's important to note, is that Stages should not include any UserInterface scenes,
and they should instead be instantiated using a Singleton (Autoload)