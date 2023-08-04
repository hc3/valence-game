# Valence game.

website : https://www.scienceninjas.com/valence
how to play: https://static1.squarespace.com/static/56a6421340667aa56dd28eda/t/5df26cc6d5a47a6001ebbb9a/1576168666849/valence+instructions.pdf


## The card game structure.

+ valence number = positive or negative.
+ color = indicates card types.
+ element = element type of card.
+ atomic number = atomic number of card.

```typescript
enum Colors = {
    BLUE = 'blue'
    //to-do: add other colors.
}

class ElementCard {
    valenceNumber: number;
    color: Enum;
    element: Enum;
    atomicNumber: number;
    image: string;
}

class MoleculeAction {
    type: Attack / Defense;
    text: string;
    sample: unknown
}

class MoleculeCard {
    moleculeType: Enum;
    points: number;
    colors: [Enum];
    symbol: Enum;
    action: MoleculeAction
}
```
### 48 Element Cards.
* 12 Oxygen
* 10 Hydrogen
* 3 Carbon
* 6 Sodium
* 4 Fluorine
* 8 Chlorine
* 2 Potassium
* 2 Calcium
* 1 Helium


### 46 Molecule Cards.
* 9 Salt
* 9 Water
* 5 Metal Oxide
* 5 Acid
* 5 Base
* 6 Carbon Dioxide
* 4 Deadly Carbonyl
* 3 Halocarbon
