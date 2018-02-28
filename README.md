This plugin allows players to receive an amount of health when they damage another player.

## Notes
- The "Heal Percent" variable in the config is the percentage of the damage given. This means that players will get healed more for hitting someone with a boltaction than hitting someone with a pistol.

## Permissions
- `lifestealer.use` - players with this permission will receive health when they damage another player

## Configuration File
```json
{
  "Settings": {
    "Animals Enabled": false,
    "Enabled Animals": [
      "boar",
      "horse",
      "stag",
      "chicken",
      "wolf",
      "bear"
    ],
    "Heal Percent": 0.5
  },
  "Static Heal": {
    "Static Heal Amount": 5.0,
    "Static Heal Enabled": false
  }
}
```
