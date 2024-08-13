# tiled-crystal

This Crystal shard allows parsing map files from Tiled [https://www.mapeditor.org/] into Crystal structures.

To run it, just include it into your project (it has no dependencies beyond the Crystal standard library)
and call the following functions (with the paths to the respective files):

```crystal
tileset = Tiled.parse_tileset("ExampleTileset.tsx")

map = Tiled.parse_map("ExampleMap.tmx")
```