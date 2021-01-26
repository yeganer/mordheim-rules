---
title: {{ replace .Name "-" " " | title }}
draft: false
magic_list: {{ .Name }}-magic
heroes:
- name: {{ replace .Name "-" " " | title }} Leader
  fluff: |
    Fluff text
  price: 80
  xp: 20
  weight: 1
  stats: { M: 5, WS: 5, BS: 4, S: 3, T: 3, W: 1, I: 6, A: 1, Ld: 9}
  equipment_list:
    - {{ replace .Name "-" " " | title }} equipment list
  skill_lists: 
    - Combat
    - Shooting
    - Academic
    - Speed
    - {{ replace .Name "-" " " | title }} Special Skill
  special:
    Leader: Any models in the warband within **6**" of the High Born may use his Leadership instead of their own.

henchmen:
- name: {{ replace .Name "-" " " | title }} Henchman
  fluff: {{ replace .Name "-" " " | title }} Henchman fluff
  price: 25
  stats: { M: 6, WS: 3, BS: -, S: 4, T: 4, W: 1, I: 1, A: 1, Ld: 4 }
  special:
    Fear:
---
Fluff text
### Special Rules
- __Special Rule 1__
  Explanation

## Choice of Warriors
A {{ replace .Name "-" " " | title }} warband must include a minimum of three models. You have 500 gold crowns to recruit your initial warband. The maximum number of warriors in the warband may never exceed 12.
* __High Born__: Each {{ replace .Name "-" " " | title }} warband must have one High Born to lead it – no more, no less.

{{< units >}}

## Equipment
The following lists are used by warbands to pick their weapons:

### {{ replace .Name "-" " " | title }} Equipment List
{{< table style="table-border" >}}
| Hand-to-hand Combat Weapons |      |
| --------------------------- | ---: |
| Dagger                      | 1st free/2 GC |
| Axe                         | 5 GC |
| Sword                       | 10 GC |
| Double-handed weapon        | 15 GC |
| Halberd                     | 10 GC |
| Spear                       | 10 GC |
| Beastlash                   | 10 GC |
| Dark Steel Weapon*          | 2x price |
{{< /table >}}

{{< table style="table-floating" >}}
| Missile Weapons | |
| - | - |
| Repeater Crossbow | 35 GC |
| Crossbow Pistol | 35 GC |
{{< /table >}}

{{< table style="table-floating" >}}
| Armour | |
| - | - |
| Buckler | 5 GC |
| Shield | 5 GC |
| Helmet | 10 GC |
| Light armour | 20 GC |
| Dark Steel Armour* | 95 GC |
{{< /table >}}

|Special Equipment| |
| - | - |
| Dark Venom* | 15 GC |
| Sea Dragon Cloak** | 50 GC |

### Shades Equipment List

| Hand-to-hand Combat Weapons | |
| - | - |
| Dagger | 1st free/2 GC |
| Axe | 5 GC |
| Sword | 10 GC |

|Missile Weapons| |
| - | - |
| Repeater Crossbow | 35 GC |

| Armour | |
| - | - |
| Helmet | 10 GC |
| Light armour | 20 GC |

*: May be taken by Heroes only.  
**: May be taken by Heroes and Corsairs only.