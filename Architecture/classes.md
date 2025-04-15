# Entity class
Methods:
- Move

Attributes:
- Health (assuming enemies and the player will have health instead of enemies just being stunned)
- Move speed

## Player
Inherits from Entity class
Methods:
- Sprint
- Sneak

Attributes:
- Hidden / visible (the visible range would be a sphere shape)

## Enemy
Inherits from Entity class
Methods:

Attributes:
- Spotted (if the player has been seen by this enemy)

---

# Weapon class
Methods:

Attributes:
- Damage
- Weapon type
- Explosion size (set to 0 to disable explosion for normal weapons)

---

# Object class
Methods:

Attributes:

(Would we even need to specify an object class? They'll just be meshes with collision)