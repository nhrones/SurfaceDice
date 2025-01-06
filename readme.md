
# Surface Canvas GUI Framework  
https://github.com/nhrones/SurfaceGUI

## Dice Game Example

Yes it's my same-ol poker-dice game you've all seen on many platforms.    
Now, its back on my newly updated Mini-Surface framework!

Very Simple -> years in development:
  - Single DOM element! `<canvas>`
  - Ultra-fine-grained reactivity! `signals-aggregator`
  - Zero external dependencies -- none - nada
  - Pure vanilla HTML, javescript
  - Bundled framework + view components ~25 KB
  - This example with framework + all media < 152 KB

## Performance
Lighthouse has trouble measuring -> (too-fast?)   

![alt text](lighthouse.png)
First Contentful Paint is a little slow as I build all die-face images and audio contexts on startup. It seems then that lighthouse has little to measure!   

## Game Play:
```
Click the 'Roll Button' to start.    
After each roll of the dice, you can 'click' a die to 'freeze' its value.    
Click again to toggle the frozen state. When frozen, value will be held!
After three rolls, you must select a score item.  
The blue highlighted numbers indicate possible scores that are available to select.
Have fun!
```
## NOTE: Try it now!
## https://nhrones.github.io/SurfaceDice/

Copyright 2022-2025, Nick D. Hrones, All rights are reserved.