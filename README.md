# Case-opener
A case opener game similar to the one inside of Counter Strike.

## Velocity/friction function:

```
      let pos = 0;
      let velocity = 60; //modify the speed of the box
      const friction = 0.9922; /modify the friction. The higher the number the lowest the friction.
      let lastIndex = -1;

      function playTick() {
        const tick = tickSound.cloneNode();
        tick.volume = 0.4;
        tick.play();
```
