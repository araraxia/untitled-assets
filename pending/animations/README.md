# Pending animation exports

Drop raw Blender glTF/GLB exports here (animation enabled, a single
animated node per file, Linear keyframe interpolation) before running
them through `tools/convert_animation.py` or the Entity Builder's
Import Animation panel (`.github/prompts/entity-builder.prompt.md`,
Step 2/4).

Files in this directory are never manifest-registered and never served
to the client directly -- they're raw conversion input, same status as
`frontend/assets/pending/models/`.
