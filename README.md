# Creature Battle Project (OOP + Git Branching Practice)

This project is designed to help me learn **object-oriented programming** in Python — especially **inheritance** — while also practicing key **Git concepts** like branching, merging, conflict resolution, and version history.

I will begin with a base class (`Creature`) and create additional subclasses on separate Git branches to simulate a real development workflow.

---

## Learning Objectives

### Python / OOP
- Understand and implement **classes**
- Use **inheritance** to extend behaviors
- Override and extend methods (e.g., `attack()`)
- Practice writing simple test code in `main`

### Git / Version Control
- Create and switch branches
- Merge branches into `main`
- Resolve merge conflicts
- View commit history (`git log --graph --all`)

---

## Project Structure
oop_creature_code/
│
├── creature_simulation.py # Base class + subclasses
└── README.md

## Project Structure
Describe how to test and run your program

## Class
- `Creature`: base class with `name`, `hp`, `attack_power`, `attack()`, and `is_alive()`
- `FlyingCreature`: adds `altitude`, `fly_to()`, and an aerial `attack()`
- `SwimmingCreature`: adds `depth`, `dive_to()`, and an underwater `attack()`
- `FireCreature`: adds `fire_level` (0–100), `emit_fire()`, and a fire-boosted `attack()`


## How to Test and Run

1. Run the program:
   ```bash
   python creature_simulation.py

The test code lives under `if __name__ == "__main__":`

- Creature Class Tests (initialization, attacking, HP never below 0, `is_alive()`, defeated creatures can't attack)
- SwimmingCreature Tests
- FlyingCreature Tests
- FireCreature Tests