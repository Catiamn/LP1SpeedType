# LP1SpeedType

``` mermaid

classDiagram
    class Program {

    }

    class GameResult {

    }

    class Game {

    }

    class SentenceProvider {

    }

    class Evaluator {
    
    }

    
    Evaluator <|-- Game
    Game <|-- Program
    SentenceProvider <|-- Game
    GameResult o-- Game







```
