**Game of Life: Demiurge**

Basic idea – use (Game of Life)[https://bitstorm.org/gameoflife/] approach to build a multiplayer game where each cell has certain traits/parameter that fuse & mutate upon new cell creation, so the population is able to evolve and transform.

Game area:
* Plane (2-dimensional) board NxM, where each cell is either empty (dead) or occupied (alive)
* Each cell has 8 neighbours

Rules:
* Basic original rules that are applied on each step:
  - If _alive_ cell has 2-3 alive neighbours, it remains alive
  - If _alive_ cell has <2 or >3 alive neighbours, it dies (of loneliness or crowd)
  - If _dead_ cell has exactly 3 neighbours, it becomes alive (consider it a newborn)

*Additional rules*:
* Each cell, being a live being, may have number of characteristics/traits, defined upon seed (by user or automatically)
* If new cell is _born_ because of 3 alive neighbours, it _inherits*_ a _combination*_ of the _parent_ (e.g. original neighbours) cells characteristics/traits

Project linked: https://github.com/users/totus/projects/1
