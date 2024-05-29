# FFlags
Also known as Fast Flag. This feature is for debugging but users can do something useful besides debugging, they can remove the game's FPS Cap, increase the graphics slider, use other Graphics API, etc. Below are the list of Fast Flags you can enable for Roblox.

## How to write, delete, or get the value a Fast Flag
```bash
# Write
$ redefiner --fflags --write FFLAG VALUE
# Delete
$ redefiner --fflags --delete FFLAG
# Get Value
$ redefiner --fflags --get FFLAG
```

## Unlock FPS cap (Just inputs big numbers and doesnt remove the FPS Cap)
```json
{"DFIntTaskSchedulerTargetFps": 999999}
```
```bash
$ redefiner --fflags --write DFIntTaskSchedulerTargetFps 999999
```

## Increase Graphics Slider
```json
{"FFlagFixGraphicsQuality": true, "FFlagCommitToGraphicsQualityFix": true}
```
```bash
$ redefiner --fflags --write FFlagFixGraphicsQuality True
$ redefiner --fflags --write FFlagCommitToGraphicsQualityFix True
```

## Configurate Lights (Future, Voxel / Phase 3)
```json
{"FFlagDebugForceFutureIsBrightPhase3": true} # Future
{"FFlagDebugRenderForceTechnologyVoxel": true} # Voxel / Phase 3
```
```bash
$ redefiner --fflags --write FFlagDebugForceFutureIsBrightPhase3 True # For Future
$ redefiner --fflags --write FFlagDebugRenderForceTechnologyVoxel True # For Voxel
```

## Configurate Textures
```json
{"FStringPartTexturePackTable2022": false, "FStringPartTexturePackTablePre2022": true} # For old textures
{"FStringPartTexturePackTablePre2022": false, "FStringPartTexturePackTable2022": true} # For new textures
```
```bash
# For Old texture
$ redefiner --fflags --write FStringPartTexturePackTablePre2022 True
$ redefiner --fflags --write FStringPartTexturePackTable2022 False
# For new texture
$ redefiner --fflags --write FStringPartTexturePackTable2022 True
$ redefiner --fflags --write FStringPartTexturePackTablePre2022 False
```
