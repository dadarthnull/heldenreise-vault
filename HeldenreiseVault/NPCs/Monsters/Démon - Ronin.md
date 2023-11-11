
```statblock
image: [[wurzelhain.jpeg]]
name: Ronin démon
size: M
type: démon
subtype: ronin
alignment: -
ac: 15
hp: 85
hit_dice: 10d10 + 35
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
  - name: Maître de l'évasion
    desc: toute attaque ciblant le ronin reçooit un désavantagetant que le ronin a plus de la moitié de ses points de vie
  - name: L'attaque qui tue en un coup (One-strike-kill)
    desc: Si le ronin n'a pas d'arme en main, il peut tenter un one-strike-kill. Il dégaine et effecture une unique attaque avec -5 pour toucher. Si l'attaque touche, un critique est automatiquement infligé.
actions:
  - name: Attaque (épée)
    desc: "Melee Weapon Attack: +14 to Hit, reach 10ft, one target. Hit: 19 (2d8 + 8) tranchants + 10 (2d8) force"
bonus_actions:
  - name: Rengainer
    desc: "rengaine son arme"
reactions:
  - name: footwork
    desc: augmente son CA de 5 jusqu'à la fin du tour en cours
```
