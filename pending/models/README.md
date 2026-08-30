# Pending model exports

Drop raw Blender glTF/GLB exports here (animation disabled in the
Blender exporter) before running them through `tools/convert_mesh.py`
or the Entity Builder's Import Mesh panel
(`.github/prompts/entity-builder.prompt.md`, Step 2/4).

Files in this directory are never manifest-registered and never served
to the client directly -- they're raw conversion input, same status as
the param-map source images in `frontend/assets/pending/`'s top level.
