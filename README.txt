CS174A Project 2
Tanzeela Khan
204577214

Summary of Animation:
The storyline is a short adventure of a skateboarder who takes a misadventure by riding off a cliff. Her skateboard falls onto a branch and begins hopping on it using simulating elastic motion. She falls for a bit more onto a butterfly. The butterfly is created using my code from Project 1. Together, he and the butterfly ride into a portal. They are transported the Cave of Wonders. Waiting in the galaxy is a genie. The genie asks her what she wishes for.

Custom Shape:
The Cave of Wonders is cluttered with color-changing custom shapes called MyShape.

Usage of look_at():
look_at() is used to follow the movement of the person throughout her adventure. look_at() follows her as she moves and falls down the cliff. The camera then changes position to look from the bottom of the cliff, following the person through the portal.

Hierarchy:
The legs of the person begin from the body_transform -> upper_leg_transform -> bottom_leg_transform.

Frame Rate:
The value is displayed as globals.graphics_state.animation_delta_time through live_string() in the Control Panel.

Texture Mapping:
I mapped the following textures: grass.jpg -> cliff, skateboard.jpg -> skateboard.
