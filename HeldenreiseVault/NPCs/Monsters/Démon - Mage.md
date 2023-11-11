
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
  - name: Enragé
    desc: Effectue toutes ses attaques de mêlée avec un avantage. toute attaque le ciblant à un avantage
  - name: Dur à cuir
    desc: Ignore 5 (1d8) de tout dégâts reçus (après avoir pris en compte les résistances)
spells:
  - Spellcasting ability is Intelligence (Spell save DC 16, +8 to hit with spell attacks)
  - Cantrips: 
  - 1st level (4 slots): mage armor*, hideous laughter, Silvery barb, Silent image
  - 2nd level (3 slots): invisibility, misty step, phantasmal force, nathair's mischief
  - 3rd level (3 slots): fear, haste, slow
  - 4th level (3 slots): delayed counterspell, resilient sphere, dimension door
  - 5th level (2 slots): shut up!, wall of force
actions:
  - name: Attaque (dague)
    desc: "Melee Weapon Attack: +5 to Hit, reach 5ft, one target. Hit: 3 (1d4) perçant"
bonus_actions:
reactions:
  - name: Je maîtrise la magie, pas toi
    desc: si un adversaire lance un sort à moins de 30 pieds, peut utilier la réaction pour déplacer la cible du sort sur une autre cible ou zone éloigné d'un maximum de 10 pieds de la destination originale
```