# 100 Days Of Code - Log

### Day 1: September 1, 2016
- Started, working on what right now I plan on being an asteroids type game but I don't have 100% concrete idea yet.
- here's the commit https://github.com/fabean/buffhammer/commit/9ca7a7dc1d1ee347ffdb5a3120799784ebe38c52

### Day 2: September 2, 2016
- I got my gulp to actually be a server. I have a minor bug with the livereload, I know the issue just never addressed it becasue hitting refresh isn't that hard honestly.
- I couldn't get a solid 1 hour today to code, but I probably did a good 45 minutes throughout the day on this. I know that's basically failing the second day but tomorrow is the weekend and I'll have more time in the morning to get a couple hours done. It's midnight and I just got home from work, so get off my back... :)
- here's the commit https://github.com/fabean/buffhammer/commit/d47e32f639b69c549e833435b3ac4c0a6392affe

### Day 3: September 3, 2016
- I got gulp live reloaded working on js & css changes instead of just html changes. Pretty simple.
- I made it so you can rotate your square (ship) both left and right.
- Where I've gotten stuck is calculating how your ship moves when you press up and down based on rotation. I'm trying to take your rotation divided by either 360 or 180 (I keep swithing back and forth trying to see which one is more accurate) then with that calculate your moves on the x/y grid. So far it's a total failure.
- here's the commit https://github.com/fabean/buffhammer/commit/b439375b30e517be0abc5c7c79a1172276702c99

### Day 4: September 4, 2016
- Mostly just played with Sin, Cosine and tangent on paper and Math.sin() in console for awhile.

### Day 5: September 5, 2016
- You can now fly around almost as expected!
- I am now calculating what quadrant you're flying in to figure out where to assing X&Y.
- Still working on what to do when you enter into negative degrees
- here's the commit https://github.com/fabean/buffhammer/commit/ea2604cba14aa0bf47eb9445737446a191bef8ea

### Day 6: September 6, 2016
- You can now shoot lasers
- You can also there are no longer issues with negative degrees
- here's the commits:
  - https://github.com/fabean/buffhammer/commit/53e3d5af67f8a42d93d9fdb00da3e43e8582f07e 
  - https://github.com/fabean/buffhammer/commit/3db2469161d5092b50bf20ba7613e9983cafa00f

### Day 7: September 7, 2016
- There are now randomly generated asteroids
- You can shoot these asteroids and you get a point to your score and the asteroids disappear
- The asteroids can hit you can you lose a life and they disappear
- here is the commit: https://github.com/fabean/buffhammer/commit/08f160f0d4dea5fbb95bd2df71667d62f0a306fe
- TODOS:
  - I need to clean up this code and break things into more reusable functions
  - I need to fix collision detection since things are rotated my collision detection isn't that good
  - I need to make asteroids have better paths and not appear in the middle of the screen

### Day 8: September 8, 2016
- Things now never fall off the screen, this creates a bit of chaos as your lasers and the asteroids fly around until you run into them or shoot them.
- If your life goes to 0 you get a game over screen
- I cleaned up some of the calculating if you hit the wall code to be reusable.
- here is the commit: https://github.com/fabean/buffhammer/commit/9c443659c62c73e9342ddc7ce4b888d07ac521c1

### Day 9: September 9, 2016
