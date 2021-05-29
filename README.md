## Rewrite branch (2.2.0)
### Configuration

```json
{
  "Spawn Settings": {
    "Murderer Population": 50.0,
    "Murderer Health": 100.0,
    "Scarecrow Population": 50.0,
    "Scarecrow Health": 100.0,
    "Chance Settings": {
      "Chance per cycle": 100.0,
      "Days betewen spawn": 0
    }
  },
  "Destroy Settings": {
    "Leave Corpse": true,
  },
  "Behaviour Settings": {
    "Count if shortname contains": false,
    "Ignored entities": [
      "scientist",
      "scientistjunkpile",
    ]
  },
  "Broadcast Settings": {
    "Broadcast spawn amount": false,
    "Broadcast types separately": false
  }
}
```
* **Chance per cycle** - Chance for zombies to spawn each time a spawn is attempted.
* **Days between spawn** - Number of in-game days until a spawn is attempted.
* **Ignored entities** - The shortnames of the entities that zombies and scarecrows will ignore and not attack.
