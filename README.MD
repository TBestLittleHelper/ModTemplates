Annotations for [Warzone mod development](https://www.warzone.com/wiki/Mod_Developers_Guide), using luals.
This gives you tons of warzone spesific types, incuding autocomplete. You no longer need to memorize the mod API!

To use annotations, add the file to your workspace. Do not require the file!

In VS code:
Add it directly to the workspace by creating a .vscode folder in the root directory. Then a settings.json file

```json
{
	"Lua.workspace.library": [
		"FILEPATH\\Annotations.lua"
	],
}
```

Alternatively add if from VS code's settings UI. You are looking for Lua workspace : Libary.

For learning more about how this work, check out luals [wiki](https://luals.github.io/wiki/annotations/)
