# Environment

- Projects must target Java 17 and latest Minecraft
- Projects must have package names beginning with `pl.nekopon`
- Projects must use Maven
- Database used for persistence of user provided data like custom nicknames must be SQLite that's already bundled with Bukkit/Spigot/Paper.
- Configuration must use YAML bundled with Bukkit/Spigot/Paper.

Example structure for configuration/persistence data:

	plugins/
	├─ natArmor/
	│  ├─ natArmor.yml
	│  ├─ natArmor.db
