impact-grid-movement
====================

Fork from: https://github.com/Joncom/impact-grid-movement
---------------------

Usage:

1) Require plugins.gridmovement in your entities that need GridMovement.

2) Create a new instance of GridMovement, passing the Entity as the constructor parameter:
this.movement = new GridMovement(this);

3) Add this.movement.update() to your entitiy Update method.

4) Add this.movement.collision(); to your entity check method

5) Set the movement direction like so:

*DEMO:*




# Live Demos
1. http://labs.tderen.com/javascript/gridMovement/

## _Usage_

1. In your entity, make sure you require `'plugins.gridmovement'`

2. Create instance of GridMovement():
`this.movement = new GridMovement(this);`

3. Add `this.movement.update()` to your entity update() method.

4. Add `this.movement.collision()` to your entity check() method.

5. Set the movement direction like:
`if (ig.input.state('left'))
                    this.movement.direction = GridMovement.moveType.LEFT;
                else if (ig.input.state('right'))
                    this.movement.direction = GridMovement.moveType.RIGHT;
                else if (ig.input.state('up'))
                    this.movement.direction = GridMovement.moveType.UP;
                else if (ig.input.state('down'))
                    this.movement.direction = GridMovement.moveType.DOWN;`

## License
Relesed under the WTFPL license: http://www.wtfpl.net/.
