```statblock
image: [[wurzelhain.jpeg]]
name: Zombie pourri
size: M
type: Mort-vivant
subtype: Zombi
alignment: -
ac: 15
hp: 85
hit_dice: 10d10 + 35
speed: 40
stats: [13, 6, 16, 3, 6, 5]
saves:
  - wisom: +0
skillsaves:
damage_vulnerabilities: -
damage_resistances: -
damage_immunities: poison
condition_immunities: poison
senses: darkvision 60ft (12 cases), perception passive 8
languages: commun, démon
cr: -
traits:
  - name: Undead Fortitude
    desc: If damage reduces the zombie to 0hp, CON save DC 5+damage, on success, fails at 1hp instead
actions:
  - name: Attaque (griffes)
    desc: "Melee Weapon Attack: +14 to Hit, reach 5ft, one target. Hit: 4 (1d6 + 1) bludgeoning"
bonus_actions:
reactions:
```