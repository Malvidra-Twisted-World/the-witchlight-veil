---
type: statblock_reference
campaign: The Witchlight Veil
session_number: 10
parent: "[[Session 10 - Toolkit]]"
---

# 🐸 Session 10 Statblocks

Dua statblock buat combat opener B19. Keduanya sebenarnya **satu makhluk yang sama** dalam lore sesi ini — lihat twist di [[Session 10 - Toolkit]]: "Darkmantle" yang menyerang party adalah bayangan Charm yang lepas lewat *scissors of shadow snipping* Endelyn. Charm sendiri (bentuk fisik utuhnya) pakai statblock Darkling standar kalau suatu saat dia perlu di-stat penuh (mis. kalau dia dikejar/dilawan setelah "Darkmantle"-nya kabur balik).

Sumber: Monster Manual (Darkmantle) & Volo's Guide to Monsters (Darkling) — tidak direprint lengkap di *The Wild Beyond the Witchlight*, App. C cuma mendaftar namanya di index tanpa isi statblock.

---

## Charm's Severed Shadow ("Darkmantle")

Dipakai persis seperti statblock Darkmantle MM standar — reskin nama saja untuk kebutuhan reveal twist.

```statblock
layout: Basic 5e Layout
source: Monster Manual (reskinned)
name: "Charm's Severed Shadow (Darkmantle)"
size: Small
type: Monstrosity
alignment: Unaligned
cr: 0.5
ac: 11
hp: 22
hit_dice: 5d8
speed: 10ft, climb 30ft
stats: [16,12,13,2,10,5]
skillsaves: [Stealth: 3]
senses: Blindsight 60 ft. (blind beyond this radius), Passive Perception 10
languages: "—"
traits:
  - name: Echolocation
    desc: "The darkmantle can't use its blindsight while deafened."
  - name: False Appearance
    desc: "While the darkmantle remains motionless, it is indistinguishable from a cave formation such as a stalactite or stalagmite — di sesi ini, dari bentuk diam patung kodok/dekorasi di B19."
actions:
  - name: Crush
    desc: "Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. Hit: 6 (1d6 + 3) bludgeoning damage, and the darkmantle attaches to the target. If the target is Medium or smaller and the darkmantle had advantage on the attack roll, it attaches to the target's head, and the target is Blinded and unable to breathe while the darkmantle is attached in this way. While attached, the darkmantle can't make Crush attacks against other targets, but it has advantage on Strength (Athletics) checks to stay attached. The darkmantle can detach itself by spending 5 feet of movement. A creature, including the target, can take an action to try to remove the darkmantle; doing so requires a successful DC 13 Strength check."
  - name: Darkness Aura
    desc: "A 15-foot radius of magical darkness extends out from the darkmantle, moves with it, and spreads around corners. The darkness lasts as long as the darkmantle maintains concentration, up to 10 minutes (as if concentrating on a spell). Darkvision can't penetrate this darkness, and no nonmagical light can illuminate it. If any of the darkness overlaps with an area of bright light created by a spell of 2nd level or lower, the spell that created the light is dispelled."
```

> [!TIP] Clue tanpa spoiler (dari Toolkit)
> Lunaris (Mirror Touch Synesthesia) merasakan damage yang kena si Darkmantle terasa **manusiawi, bukan binatang** — pakai ini sebagai clue utama, bukan DC check. Alternatif: Insight/Arcana/Perception DC 14 — gerakannya kadang meniru gerak orang, dan gak ada echolocation click seperti darkmantle asli.

---

## Charm (Darkling) — kalau perlu di-stat penuh

Statblock standar Darkling (Volo's Guide to Monsters) untuk Charm dalam bentuk fisik utuhnya — dipakai kalau dia perlu bertarung/dikejar langsung, terpisah dari insiden bayangannya.

```statblock
layout: Basic 5e Layout
source: Volo's Guide to Monsters
name: "Charm"
size: Small
type: Fey
alignment: Neutral Evil
cr: 0.125
ac: 12
hp: 10
hit_dice: 3d6
speed: 30ft
stats: [11,15,10,11,10,12]
skillsaves: [Perception: 2, Stealth: 4]
senses: Darkvision 120 ft., Passive Perception 12
languages: Common, Sylvan
traits:
  - name: Fey Step (1/Day)
    desc: "As a bonus action, the darkling teleports up to 30 feet to an unoccupied space it can see."
  - name: Illumination Weakness
    desc: "While in bright light, the darkling has disadvantage on attack rolls, ability checks, and saving throws."
actions:
  - name: Shortsword
    desc: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6 + 2) piercing damage."
```

> [!NOTE] Kalau dipakai sesi ini
> Charm ditemukan diam tak bergeming di Study (B10) — bukan combat state, dia gak akan pakai statblock ini kecuali party menyerangnya langsung atau dia siuman & kabur (lihat opsi "party sadar & menahan/mengusir" di Toolkit). Kalau dia kabur, Fey Step-nya relevan untuk breakaway.
