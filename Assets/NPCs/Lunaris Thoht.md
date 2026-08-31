![](https://i.ibb.co/LzXPWVfB/image.png)

![](https://i.imgur.com/viDOXR0.jpeg)

```statblock
name: Lunaris Thoht
layout: Basic 5e Layout
image: D&D/Original Adventures/The Witchlight Veil/Assets/NPCs/Lunaris Thoht.png
source: TWV
size: Medium
type: humanoid
subtype: human
alignment: chaotic neutral
ac: 15
hp: 42
hit_dice: 5d8 + 15
speed: 40 ft.
stats:
  - 10
  - 18
  - 16
  - 12
  - 16
  - 14
saves:
  - dexterity: 7
  - wisdom: 6
skillsaves:
  - acrobatics: 7
  - insight: 6
  - perception: 6
  - stealth: 7
damage_vulnerabilities: ""
damage_resistances: psychic
damage_immunities: ""
condition_immunities: frightened
senses: passive Perception 16
languages: Common, Sylvan
cr: "4"
bestiary: true

traits:
  - name: Mirror Touch Synesthesia
    desc: "Whenever a creature within 30 ft. of Lunaris takes damage, Lunaris instinctively feels the pain. Once per round, when this occurs, Lunaris may move up to 10 ft. without provoking opportunity attacks."
    attack_bonus: 0

  - name: Feywild Amnesia
    desc: "Fragments of forgotten memories distort Lunaris's perception. Whenever Lunaris takes psychic damage or fails a Wisdom saving throw, he has disadvantage on the next attack roll he makes before the end of his next turn."
    attack_bonus: 0

actions:
  - name: Multiattack
    desc: Lunaris makes two Unarmed Strikes.
    attack_bonus: 0

  - name: Unarmed Strike
    desc: "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 8 (1d8 + 4) bludgeoning damage."
    attack_bonus: 7
    damage_dice: 1d8
    damage_bonus: 4

  - name: Flowing Crescent Kick
    desc: "Melee Weapon Attack: +7 to hit, reach 10 ft., one target. Hit: 10 (1d10 + 5) bludgeoning damage, and the target must succeed on a DC 14 Dexterity saving throw or be pushed 10 ft."
    attack_bonus: 7
    damage_dice: 1d10
    damage_bonus: 5

  - name: Hand of Mercy (3/Day)
    desc: "Lunaris touches a creature. The target regains 10 (2d6 + 3) hit points."
    attack_bonus: 0

bonus_actions:
  - name: Step of the Wind
    desc: Lunaris takes the Dash or Disengage action.
    attack_bonus: 0

reactions:
  - name: Reflexive Shift
    desc: "When a creature within 30 ft. takes damage, Lunaris may move up to 10 ft. toward or away from that creature."
    attack_bonus: 0

legendary_actions: []
```

```statblock
name: Thoht
source: TWV
image: D&D/Original Adventures/The Witchlight Veil/Assets/NPCs/Thoht-1.png
size: Medium
type: aberration
subtype: manifested psyche
alignment: chaotic neutral
ac: 17
hp: 68
hit_dice: 8d8 + 32
speed: 50 ft.
stats:
  - 12
  - 20
  - 18
  - 14
  - 16
  - 18
saves:
  - dexterity: 8
  - constitution: 7
  - wisdom: 6
  - charisma: 7
skillsaves:
  - perception: 6
  - insight: 6
  - intimidation: 7
damage_vulnerabilities: radiant
damage_resistances: psychic, necrotic, bludgeoning from nonmagical attacks
damage_immunities: frightened
condition_immunities: charmed
senses: darkvision 60 ft., passive Perception 16
languages: Common, Sylvan
cr: "6"
bestiary: true

traits:
  - name: Thoht Unveil
    desc: "Whenever Thoht takes damage or senses a creature within 30 ft. take damage, he may force one creature he can see within 30 ft. to take 1d6 + 3 psychic damage. This effect may trigger a number of times per round equal to his proficiency bonus."
    attack_bonus: 0

  - name: Fractured Memory
    desc: "When Thoht starts his turn below half hit points, he must succeed on a DC 13 Wisdom saving throw or lose focus until the end of his turn. During this time, attack rolls against him have advantage."
    attack_bonus: 0

  - name: Painbound Presence
    desc: "Creatures that begin their turn within 10 ft. of Thoht must succeed on a DC 15 Wisdom saving throw or have disadvantage on their first attack roll that turn."
    attack_bonus: 0

actions:
  - name: Multiattack
    desc: Thoht makes three Fractured Strikes.
    attack_bonus: 0

  - name: Fractured Strike
    desc: "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 11 (1d10 + 6) psychic bludgeoning damage."
    attack_bonus: 8
    damage_dice: 1d10
    damage_bonus: 6

  - name: Memory Rupture (Recharge 5-6)
    desc: "Thoht releases unstable psychic force in a 20-foot radius. Each creature of his choice must make a DC 15 Wisdom saving throw or take 18 (4d8) psychic damage and become frightened until the end of their next turn. On a success, creatures take half damage and are not frightened."
    attack_bonus: 0

bonus_actions:
  - name: Painstep
    desc: "Thoht teleports up to 20 ft. to an unoccupied space adjacent to a creature that has taken damage since the end of his last turn."
    attack_bonus: 0

reactions:
  - name: Mirror Recoil
    desc: "When Thoht is hit by an attack, the attacker takes 4 (1d6 + 1) psychic damage."
    attack_bonus: 0

legendary_actions:
  - name: Sudden Shift
    desc: Thoht moves up to half his speed without provoking opportunity attacks.
    attack_bonus: 0

  - name: Reflexive Strike
    desc: Thoht makes one Fractured Strike.
    attack_bonus: 0

  - name: Distorted Pulse (Costs 2 Actions)
    desc: "Each creature within 10 ft. of Thoht must succeed on a DC 15 Constitution saving throw or take 7 (2d6) psychic damage."
    attack_bonus: 0

creature: Thoht
```