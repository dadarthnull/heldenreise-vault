
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
stats: [19, 18, 20, 08, 10, 08]
saves:
  - strength: +8
  - constitution: +9
skillsaves:
  - Athlétisme: 19
damage_vulnerabilities: -
damage_resistances: tranchant, contondant, perçant
damage_immunities: -
condition_immunities: charmé, agrippé
senses: perception passive 12
languages: commun, démon
cr: -
traits:
  - name: Enragé
    desc: Effectue toutes ses attaques de mêlée avec un avantage. toute attaque le ciblant à un avantage
  - name: Dur à cuir
    desc: Ignore 5 (1d8) de tout dégâts reçus (après avoir pris en compte les résistances)
actions:
  - name: Multi-attaque
    desc: Effecture 2 attaques de griffes et une attaque de poings
  - name: Attaque (poings)
    desc: "Melee Weapon Attack: +10 to Hit, reach 5ft, one target. Hit: 19 (2d8 + 8) contondant"
  - name: Attaque (griffes)
    desc: "Melee Weapon Attack: +10 to Hit, reach 5ft, one target. Hit: 19 (2d8 + 8) tranchant"
bonus_actions:
  - name: Charge
    desc: "effecture un déplacement de la moitié de son mouvement, puis une unique attaque avec avantage"
  - name: Le pouvoir de la rage
    desc: "Regagne 2d10 points de vie"
reactions:
  - name: Même pas mal
    desc: divise les dégâts reçus par 2
  - name: Tu tapes fort ... Je tape plus fort
    desc: après avoir été la cible d'une attaque réussie, peut effecture une unique attaque avec ses poings
```