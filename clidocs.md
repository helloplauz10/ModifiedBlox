
# Using ModifiedBlox's CLI Tool
You need a Terminal app to use it or a custom one. You can use the default Terminal app preinstalled in your Mac.

## Roblox Tools
```bash
modifiedb roblox
```

### Joining a Game
Join a game on Roblox
```bash
modifiedb roblox join [placeid] [--jobid optional]
```
| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `placeid` | `int` | **Required**. The Place ID to join. |
| `jobid` | `string` | The Job ID to join.

### Rejoining a Game
Rejoin the latest game played on Roblox
```bash
modifiedb roblox rejoin
```

### Leaving a Game
Leave the game on Roblox.
```bash
modifiedb roblox leave
```

### Get Roblox's current version
Print the current version installed
```bash
modifiedb roblox version
```

### Fetch the latest version on Roblox
Print the latest version on Roblox MacPlayer
```bash
modifiedb roblox latestver [--channel optional]
```
| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `channel` | `string` | The channel to use |

### Update Roblox
Update Roblox to the latest version
```bash
modifiedb roblox update [--channel optional] [--cdn optional]
```
| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `channel` | `string` | The channel to use |
| `cdn` | `string` | The CDN to use for updating |

## Roblox Fast Flags
```bash
modifiedb fflags
```

## Write or Modify a Fast Flag
Modify a Fast Flag
```bash
modifiedb fflags write [fflag] [value]
```
| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `fflag` | `string` | **Required**. The Fast Flag to modify or create |
| `value` | `string` | **Required**. The value to write |

## Get the value of a Fast Flag
Get the value of a Fast Flag
```bash
modifiedb fflags get [fflag]
```
| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `fflag` | `string` | **Required**. The Fast Flag to get the value |

## List every Fast Flag written
Print every Fast Flag written
```bash
modifiedb fflags list
```

## Remove a Fast Flag written
Remove a Fast Flag written
```bash
modifiedb fflags remove [fflag]
```
| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `fflag` | `string` | **Required**. The Fast Flag to remove |

## ModifiedBlox's Settings
```bash
modifiedb settings
```

### Modifying a Setting
Modify a Setting
```bash
modifiedb settings modify [setting] [value]
```

### Getting the value of a Setting
Print the value of a setting
```bash
modifiedb settings get [setting]
```

### List every Setting that can be modified
Print every setting that can be modified
```bash
modifiedb settings List
```

## Modifications
```bash
modifiedb mods
```

## Applying a Mod
```bash
modifiedb mods apply [modname]
```
| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `modname` | `string` | **Required**. The name of the folder of the mod |

## List Mods inside the folder of Mods
```bash
modifiedb mods list
```

## Open the folder of Mods
```bash
modifiedb mods openmods
```
