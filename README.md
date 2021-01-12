# Vysics Engine

⚠️ This project is still in early development !

> A "simple" 2D impulse based, rigid body physics engine.
> The goal of this project is not to create a state of the art physics engine. The goal is to create an understandable code that people can read & used to better understand classic physics.

Based on:

- [How Physics Engine Works - Build New Games](http://buildnewgames.com/gamephysics/)
- [Building a 2D Game Physics Engine](https://www.apress.com/gp/book/9781484225820)
- [How to Create a Custom 2D Physics Engine](https://gamedevelopment.tutsplus.com/tutorials/how-to-create-a-custom-2d-physics-engine-the-basics-and-impulse-resolution--gamedev-6331)
- [Video Game Physics Tutorial | Toptal](https://www.toptal.com/game/video-game-physics-part-i-an-introduction-to-rigid-body-dynamics)
- And of course [Wikipedia](https://wikipedia.org/)

## Implemented & Todos

✅: Implemented

🔧: Still needs some work

🔜: Not implemented but planned

### Physics parts

- Shapes:
  - Circle ✅
  - Rectangle ✅
  - Convex Polygons ✅
  - Any type of Polygons (decomposition in convex polygons) 🔜
- Forces:
  - Gravity ✅
  - Drag ✅
  - Linear / Angular dumping 🔜
  - Constraints 🔜
  - Joints 🔜
- Integrations:
  - Verlet integration ✅
- Collisions:
  - Broad Phase:
    - Brute method ✅
    - Grid method ✅ 🔧
    - R-Trees method 🔜
  - Narrow phase:
    - SAT ✅
    - GJK 🔜
  - Resolution based on impulse ✅ 🔧
  - Continuous detection 🔜

### More engine related parts

- Debug drawings (using [Vancas](https://github.com/Voxylu/vancas)) 🔜
- Tests (using jest) 🔜 (maybe never 😞)
- Integration with [Vancas](https://github.com/Voxylu/vancas) 🔜
- Optimisation (not a priority) 🔜

## Examples

> W.I.P.

For the moment look at the [playground folder](./playground).

## Documentation

> W.I.P.

For the moment you may want to generate docs using [TypeDoc](http://typedoc.org/).
