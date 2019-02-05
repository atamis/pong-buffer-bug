# pong-buffer-bug

Semi-minimal example of https://github.com/amethyst/amethyst/issues/1217

I was running through the Amethyst Pong tutorial and got to
[part 2](http://localhost:3000/pong-tutorial/pong-tutorial-02.html), and got to the section
after loading the sprite sheet and sprite sheet description, at which point, the game
should show both paddles. However, it didn't, and instead started creating buffers left
and right, several times a second. You can see the full logs
[in this gist](https://gist.github.com/atamis/02838411fd7df33890c30fb12fd65306).
