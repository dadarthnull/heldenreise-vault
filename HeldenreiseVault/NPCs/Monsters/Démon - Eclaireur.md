
```statblock
image: [[wurzelhain.jpeg]]
name: Eclaireur démon
size: M
type: démon
subtype: éclaireur
alignment: -
ac: 13
hp: 65
hit_dice: 5d8 + 35
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
  - name: attaque sournoise
    desc: Pendant son tour, la première attaque qui effectue des dégâts voit ses dégâts augmentés de 20(5d6)
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
reactions:
  - name: Oulah ça chauffe
    desc: Si il n'est pas invisible, peut effectuer un mouvement de 10 pieds qui ne déclenche pas d'attaque d'opportunité quand un adversaire arrive au corps à corps
```