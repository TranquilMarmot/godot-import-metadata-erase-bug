This is a minimal reproduction project for https://github.com/godotengine/godot/issues/100757

- Open project in Godot
- Open `cube.tscn` (this is an inherited scene from `cube.glb`)
  - The first time opening the project, it will probably erase the metadata - give the imported `Cube` `MeshInstance3D` node some metadata (can be anything)
- Re-import `cube.glb`
- Check that the metadata in `cube.tscn` was erased
