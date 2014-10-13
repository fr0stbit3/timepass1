# Video Game Details

### Usage of OOP concepts - Abstraction, Encapsulation, Polymorphism and Inheritance.

The game has two different types of objects.

Immovables consisting of Rocks, Walls and Trees. Movables consisting of Player, Monster and Boss.

Abstract classes Immovable and Movable have been defined with respective abstract methods.

Subclasses Wall, Tree, Rocks, Player, Monsters, Boss have been inherited from the above abstract classes.

Methods in the subclasses override those of the super class.

Object arrays of Immovable and Movable data type are initialised with respective Subclass instances applying the concept of polymorphism.

Methods and Data variables of each class have been separated to uphold encapsulation.

### Positioning of Objects

Walls have been placed along the edges so that no movable object can go out of bounds.

Trees and Rocks have been initialized with specific positions.

Immovable objects do not change position throughout the program although their initial position can be set as per wish.

Movable objects Player, Monsters and Bosses have been initialized with specific positions and specific directions to which it can move.

When a Movable object collides with a Immovable object, direction is reversed.

When Player collides with another Movable object, Hp details of object being hit is counted and the Objects move on. Direction is not reversed.
