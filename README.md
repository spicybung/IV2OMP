# IV2OMP

IV2OMP is a conversion of the Liberty City HD era map from Grand Theft Auto IV to open.multiplayer(San Andreas Multiplayer). For the files, check releases.
Make sure to define the filterscript in your config file.

## Configuration

Open your `config.json` file and locate the `"pawn"` section.

Add the filterscript to the `"side_scripts"` array.

> **Note:** Do **not** include the `.amx` extension.

### Example

```json
{
    "pawn": {
        "legacy_plugins": [
            "streamer",
            "sscanf"
        ],
        "main_scripts": [
            "your_gamemode 1"
        ],
        "side_scripts": [
            "filterscripts/IV2OMP"
        ]
    }
}
```

After saving `config.json`, restart your open.mp server. The IV2OMP filterscript will be loaded automatically on startup.
