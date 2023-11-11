
```statblock
image: [[wurzelhain.jpeg]]
name: Brute démon
size: M
type: démon
subtype: brute
alignment: -
ac: 13
hp: 105
hit_dice: 10d12 + 35
speed: 40
stats: [14, 20, 16, 12, 16, 14]
saves:
  - dexterity: +9
  - constitution: +7
skillsaves:
  - Stealth: 19
  - Perception: 18
damage_vulnerabilities: -
damage_resistances: -
damage_immunities: -
condition_immunities: charmé, effrayé
senses: perception passive 12
languages: commun, démon
cr: -
traits:
actions:
  - name: Multi-attaque
    desc: Effecture 2 attaques à la hache ou 2 tirs à l'arc
  - name: Attaque (hache)
    desc: "Melee Weapon Attack: +8 to Hit, reach 5ft, one target. Hit: 10 (1d8 + 5) tranchant"
  - name: Attaque (arc)
    desc: "Melee Weapon Attack: +10 to Hit, reach 60/120ft, one target. Hit: 10 (1d8 + 8) tranchant"
bonus_actions:
  - name: On m'vois, on m'vois plus
    desc: "devient invisible jusqu'au début de son prochain tour"
  - name: Le pouvoir de la rage
    desc: "Regagne 2d10 points de vie"
reactions:
  - name: Même pas mal
    desc: divise les dégâts reçus par 2
  - name: Tu tapes fort ... Je tape plus fort
    desc: après avoir été la cible d'une attaque réussie, peut effecture une unique attaque avec ses poings
```