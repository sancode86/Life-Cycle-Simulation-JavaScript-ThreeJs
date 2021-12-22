# Life Cycle Simulation - JavaScript | Three Js
I made a Life Cycle Simulation in Javascript using threejs for the graphics !

(image 1)
![Life Cycle Simulation image](https://raw.githubusercontent.com/sancode86/Tribe-Simulation-ThreeJs-Javascript/master/sim1.png?token=AVS567EEFBSOUHBRPITAMC3BYJWEY)
## World features

- Time passes.
- Every 40 days, resources grow again ! 
- Every 30 days, if a creature has one or more houses, it gains food.
- History information showing all events.

(image 2)
![Life Cycle Simulation image](https://raw.githubusercontent.com/sancode86/Tribe-Simulation-ThreeJs-Javascript/master/sim2.png?token=AVS567EFU4A4CSBIZGME343BYJWFC)
## Creature features

- They reproduce.
- They can die from starvation.
- Creatures can kill others.
- Ability to collect food and resources.
- The creature's profile contains information about their parents, ancestors, food, resources and real estate.

## Creature genes

If they reproduce (with other being):
- 50% chance to obtain either "the father's health" or the "mothers".
- 50% chance to obtain either "the father's aggressiveness" or the "mothers".
- The newborn always get random color and speed.
- The newborn's profile contains information about their parents, ancestors and current generation.

(image 3)
![Life Cycle Simulation image](https://raw.githubusercontent.com/sancode86/Tribe-Simulation-ThreeJs-Javascript/master/sim3.png?token=AVS567HUKTWJ6LO6CZ5S2ZTBYJWFI)

You can move around/zoom with Orbital Controls, and click on every object to see information.

Strangely the variables are set in such a way that they "live in harmony", or sort of. If you play a little with the killing randomness threshold for example, you'll get a bunch of massive murders. If you change the born rate variable, you'll get thousands of newborns almost everyday.

You'll probably get a 'blocked by CORS policy' ERROR if you try to open the index.html file directly. You should run in on an environment. For example, you could open the project with Visual Code and use the Live Server Extension. Works perfect.

Thousands of improvements and features to be done; but this was just for fun and practice. 🙂

(source code in Spanish)


![Life Cycle Simulation gif](https://raw.githubusercontent.com/sancode86/Tribe-Simulation-ThreeJs-Javascript/master/simGif.gif?token=AVS567EN5SRUT4YMM6QNHIDBYJWFO)

Coded with ❤️ & ☕ 
