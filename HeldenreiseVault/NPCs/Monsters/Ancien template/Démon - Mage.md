
```statblock
image: [[wurzelhain.jpeg]]
name: mage démon
size: M
type: démon
subtype: mage
alignment: -
ac: 13
hp: 105
hit_dice: 10d12 + 35
speed: 40
stats: [08, 10, 10, 18, 13, 15]
saves:
  - intelligence: +8
  - wisdom: +6
skillsaves:
damage_vulnerabilities: -
damage_resistances: -
damage_immunities: -
condition_immunities: charmé, effrayé
senses: perception passive 12
languages: commun, démon
cr: -
traits:
spells:
  - Spellcasting ability is Intelligence (Spell save DC 16, +8 to hit with spell attacks)
  - Cantrips: 
  - 1st level (4 slots): mage armor*, Silvery barb, magic missile, witch bolt
  - 2nd level (3 slots): low wall of fire, misty step, absorb spell, scorching ray
  - 3rd level (3 slots): arcane siphon, lightening bolt, fly
  - 4th level (3 slots): blight, ice storm, fire shield
  - 5th level (2 slots): cone of cold, synaptic static
actions:
  - name: Attaque (dague)
    desc: "Melee Weapon Attack: +5 to Hit, reach 5ft, one target. Hit: 3 (1d4) perçant"
bonus_actions:
reactions:
  - name: Je maîtrise la magie, pas toi
    desc: si un adversaire lance un sort à moins de 30 pieds, peut perturber les energie magique, toute créatire dans un rayon de 10pieds du lanceur de sort doit réussir un jet de sauvegarde DEX DC 16 ou subir 1d4 psychic damage par niveau du sort lancé
```