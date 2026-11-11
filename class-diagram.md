
classDiagram
    class Organism {
        +int x
        +int y
        +int age
        +int energy
        +bool alive
        +move()
        +check_survival()
    }

    class Prey {
        +float reproduction_rate
        +reproduce()
        +run_away()
        +forage()
    }

    class Predator {
        +int hunting_range
        +int starvation_limit
        +hunt()
    }

    class SimulationEnvironment {
        +grid
        +turn
        +manage_board()
        +move_animals()
        +update_environment()
        +remove_dead_organisms()
    }

    class DataTracker {
        +count_populations()
        +save_final_stats()
    }

    Organism <|-- Prey
    Organism <|-- Predator
    SimulationEnvironment o-- Organism
    DataTracker --> SimulationEnvironment : monitors
