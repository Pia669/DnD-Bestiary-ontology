# DnD-Bestiary-ontology
ASsignment from Ontology and Knowledge Engineering, 2024

## About ontology
Our ontology contains basic information about beasts in the DnD setting. We built the ontology as an assignemnt goal of learning how ontologies work and how to design and build ontologies.

We used stats available for monsters from Basic Rules listed on [Monsters for D&D 5e - DnD Beyond](https://www.dndbeyond.com/monsters?filter-type=0&filter-search=&filter-cr-min=&filter-cr-max=&filter-armor-class-min=&filter-armor-class-max=&filter-average-hp-min=&filter-average-hp-max=&filter-is-legendary=&filter-is-mythic=&filter-has-lair=&filter-source=1&filter-partnered-content=f).

## Class description
Our ontology contains 4 top-level classes, 3 object properties and 13 data properties.

**ADD DIAGRAM**

### Class Creature
Class Creature is a base class, containing subclasses divided by their type (eg Beast, Giant and Plant). Inside the type classes are classes for the monsters. For better understanding see a diagram over.

### Classes Alignment, Size & Environment
These classes are located on the same level as class Creature. CLasses Alignment, Size and Environment are enumerators, meaning each monster will have exactly one alignment, one size, and one or more environments. 

### Data properties Speed, Stats, HP & Armor
Each monster has basic statistics, like speed (eg walking, swimming), stats (eg Char, Int), hitpoints and armor class. These all are integer values and each monster has their own stats.

## Contributors
- [@Pia669](https://github.com/Pia669)
  - Dragon, Elemental, Fey, Fiend and Giant - subclasses and their properties
  - Implemented Shapechanger and Humanoid subclasses (with [@Louksi](https://github.com/Louksi))
- [@Louksi](https://github.com/Louksi)
  - Humanoid, Monstrosity, Ooze, Plant and Undead - subclasses and their properties
  - Implemented Shapechanger and Humanoid subclasses (with [@Pia669](https://github.com/Pia669))
- [@frantiiisek](https://github.com/frantiiisek)
  - Abberation, Beast, Celestial and Construct - subclasses and their properties
  - Documentation

If you want to contribute, you can create an issue or a pull request
