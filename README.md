# BPVTranslations
Translations for BetterPlayerVaults

[Translations GitHub](https://github.com/BigBadE/BPVTranslations/tree/master)
[Main GitHub](https://github.com/BigBadE/BetterPlayerVaults/tree/master)

Feel free to contribute!

## Format

message.key: &5My Message

Use the & symbol for [color codes](https://minecraft.gamepedia.com/Formatting_codes)

## Requirements 
All supported languages must be listed in languages.txt

No sections with values: 
EX:
```
command.vault: "Test"
command.vault.open: "Opened"
```

### Version.yml
version.yml is used to track the release version. Anytime a PR is merged, or the plugin updates, the version.yml version will update along with it.

Format:
(Plugin major version).(Plugin minor version).(Translation version)

Ex:
Plugin version 1.2, after 3 PRs have been merged: 1.2.3

### Release branch
The release branch is in sync with the latest version on spigotmc.org, and the release branch on the main GitHub
Master is on sync with master on the main GitHub