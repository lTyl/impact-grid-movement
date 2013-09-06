impact-grid-movement
====================
Usage:
1.) Require plugins.gridmovement in your entities that need GridMovement.
2.) Create a new instance of GridMovement, passing the Entity as the constructor parameter:
this.movement = new GridMovement(this);
3.) Add this.movement.update() to your entitiy Update method.
4.) Add this.movement.collision(); to your entity check method
5.) Set the movement direction like so:

DEMO:
http://labs.aurava.com/javascript/gridMovement/
