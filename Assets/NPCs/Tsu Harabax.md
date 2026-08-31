![](Tsu%20Harabax.png)

```statblock
name: Tsu Harabax
source: TWV
image: [[Tsu Harabax.png]]
size: Medium
type: humanoid
subtype: human druid
alignment: neutral good
ac: 13
hp: 27
hit_dice: 5d8 + 5
speed: 30 ft.
stats:
  - 10
  - 14
  - 12
  - 13
  - 17
  - 15
saves:
  - wisdom: 6
  - charisma: 4
skillsaves:
  - animal handling: 6
  - insight: 6
  - medicine: 6
  - nature: 4
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: passive Perception 16
languages: Common, Sylvan, Druidic
cr: "2"
bestiary: true

traits:
  - name: Hearthwalker
    desc: "While inside the Inn at the End of the Road, Tsu has advantage on Wisdom (Insight) and Wisdom (Medicine) checks."
    attack_bonus: 0

  - name: Gentle Presence
    desc: "Creatures that complete a short rest inside the inn under Tsu's care gain 1d4 temporary hit points."
    attack_bonus: 0

actions:
  - name: Quarterstaff
    desc: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d6 + 1) bludgeoning damage."
    attack_bonus: 4
    damage_dice: 1d6
    damage_bonus: 1

  - name: Herbal Poultice (3/Day)
    desc: "Tsu applies healing herbs to a creature within 5 ft. The target regains 8 (2d4 + 3) hit points."
    attack_bonus: 0

bonus_actions: []

reactions:
  - name: Protective Flinch
    desc: "When a creature within 5 ft. of Tsu is hit by an attack, Tsu may impose disadvantage on the attack roll by briefly distracting the attacker."
    attack_bonus: 0

legendary_actions: []

spells:
  - "Tsu is a 4th-level spellcaster. Her spellcasting ability is Wisdom (spell save DC 14, +6 to hit with spell attacks)."
  - Cantrips (at will): druidcraft, guidance, thorn whip
  - 1st level (4 slots): cure wounds, entangle, fog cloud
  - 2nd level (3 slots): lesser restoration, moonbeam
```