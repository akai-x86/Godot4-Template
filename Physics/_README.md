# Physics Objects #

Physics objects include all actors that interact with the physics system in some form.
In Godot, we can have:
- a StaticBody (Static), 
- CharacterBody (Kinematic);
- or a RigidBody (Dynamic)

Each physics object should, per convention, contain not only the scripts and the "prefab"
scene, but also the used avatar (skeletal/static mesh), 
as well as any resources/shaders applied specifically to it

