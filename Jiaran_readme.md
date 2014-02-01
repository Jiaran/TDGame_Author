
I'm in backend group to build game engine. So the authoring part is not updated in my repo.
You can actually play the game(run main). TowerDefense.json and Hospital.json are created by the authoring software.
But one can modified the jason file to see how it affects the game.

Highlight of my work:
Improve the JGame library we are using to support blending so that we can create fade in , fade out effects.
Register Resources such as images and audio based on the Jason files.
Use Adapter Pattern to create Detector. Isolate the "dirty " part of JGame from our code.
Create Effects using Decorator pattern to reduce inheritance. Allow others to dynamically add effects to their objects.
Schedule the "Waves of enemy"
Create Skills so that Enemy can have different behavior. This feature significently improve the functionality of 
game engine. Hospital is created based on skills.
