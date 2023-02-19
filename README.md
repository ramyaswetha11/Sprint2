Sprint 2

GIT REPO: https://github.com/ramyaswetha11/Sprint2

Except abstract factory pattern in sprint 1, there are totally 4 new patterns implemented

Builder Pattern
Shape class implement builder pattern so other class are able to create shape through build pattern.

Strategy Pattern
Strategy pattern use for mouse mode run() method, this includes IStrategy interface and Context for switching mode.

Flux Pattern
We already have View (UI) initiated in main, so I create ShapeList as data model and MouseController as controller to satisfy with Flux pattern

Observer Pattern
MovementAlert class implement observer pattern, it allows SelectCommand to add observer(s) (selected shape(s)), and MoveCommand to update the new coordinate to all observer(s). This requires IMovementObserver interface to share similar methods.
