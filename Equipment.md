# Equipment

Required stats:
```yaml
key:
  name: Name
  fluff: Some fluff text
  range: melee # or a number for ranged weapons
  crit_class: thrusting/missile/...
  price: 10
  rarity: 7
```

The following optional fields are supported:

### Explanation of modifiers:

```yaml
template:
  name: Template
  fluff: |
    Template weapon
  range: melee
  strength: # default: as user
  modifier:
    M: 5
    WS: 5
    BS: 4
    S: 3
    T: 3
    W: 1
    I: 6
    A: 1
    Ld: 9
    S: "+1"
    Sv: "+1"
  class: dagger
  crit_class: thrusting
  price: 2
  rarity: 6 (common for Sisters)
  limited_to:
    - Dark Elves
    - Orcs
  special:
    Strike First:
```
| Modifier | Description |
| -------- | ----------- |
| Sv | Modification of the armour safe |
| S  | Strenght of the attack |
| Hit | Modification of to-hit |
