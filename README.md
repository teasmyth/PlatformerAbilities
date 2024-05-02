# PlatformerAbilities
These are the platformer abilities we made for our project, using my ability system

Here's the link for that system: https://github.com/teasmyth/StateMachineWithBP

These abilities are inherited from the base class defined in that repository. Made for Unreal Engine 5.

These are:
- Wall Climbing - Ability to climb walls with custom gravity curve and have a big jump afterward. Has a Coyote timer.
- Wall Running - Ability to run alongside walls with custom gravity curve. Has a Coyote timer.
- Sliding - Ability to slide, and also be able to slide before hitting the ground for a smoother experience.
- Air Dash - Dashing towards the location we are looking at.

Here's a video demonstrating these abilities in the same order. The sound effects are not my work and are not included, they are for debugging.
https://youtu.be/ZZnuCk-mylI

The abilities are tied together through a character script (also added) using Unreal's Enhanced Input system and the State Machine in the link provided above.

Sliding and Dashing were made in collaboration with https://github.com/Bearshark15
