
```statblock
image: [[wurzelhain.jpeg]]
name: Révolutionnaire
size: M
type: Larbin
subtype: Révolutionnaire
alignment: -
ac: 14
hp: 9
hit_dice: 2d8
speed: 30
stats: [11, 12, 10, 10, 11, 10]
saves:
skills: deception +2, religion +2
skillsaves:
damage_vulnerabilities: -
damage_resistances: contondant
damage_immunities: poison
condition_immunities: empoisonné, fatigué
senses: perception passive 10
languages: commun, démon
cr: -
traits:
  - name: Dark devotion
    desc: advantage on saving throws against charmed or frightened
  - name: Potions démoniaques (1/repos long)
    desc: 1d4 puissance (P), 1d6 effet
    | *dé* | *effet* |
    | 1 | +P attaque et dégâts |
    | 2 | +P CA et dégâts |
    | 3 | +P * 12 mouvement et +P CA |
    | 4 | souffle 15ft, P * d6 nécrotique dégâts |
    | 5 | +P * d4 dégâts |
    | 6 | P dégâts si attaqué |
actions:
  - name: Attaque (épée)
    desc: "Melee Weapon Attack: +3 to Hit, reach 5ft, one target. Hit: 4 (1d6 + 1) tranchants"
bonus_actions:
reactions:
```