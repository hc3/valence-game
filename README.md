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
| Element     | Valence | Atomic Number | Symbol Atomic | Quantity |
|-------------|--------|---------------|--------|------------|
| Oxygen      | -2     | 8             | O      | 12         |
| Hydrogen    | +1     | 1             | H      | 10         |
| Carbon      | +4     | 6             | C      | 3          |
| Sodium      | +1     | 11            | Na     | 6          |
| Fluorine    | -1     | 9             | F      | 4          |
| Chlorine    | -1     | 17            | Cl     | 8          |
| Potassium   | +1     | 19            | K      | 2          |
| Calcium     | +2     | 20            | Ca     | 2          |
| Helium      | 2      | 2             | He     | 1          |



### 46 Molecule Cards.
* 9 Salt
* 9 Water
* 5 Metal Oxide
* 5 Acid
* 5 Base
* 6 Carbon Dioxide
* 4 Deadly Carbonyl
* 3 Halocarbon
