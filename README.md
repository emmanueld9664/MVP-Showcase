# MVP-Showcase

This Github is for showcasing all of the appropriate C# Scripts used to create my current MVP. There will be changes to the scripts later on, but this is the current representation of each Script as of 4/16/23.

[PlayerController](PlayerController) is the main file for updating and controlling Player movement and actions within the world.

[CameraController](CameraController) is responsible for making the camera follow the Player as they manuever around the world, along with staying within the set borders of the set tilemap. 

[AreaEnd](AreaEnd) is responsible for transitioning the Player and the Camera to other scenes, and is where the Player enters through to access the next scene.

[AreaEntrance](AreaEntrance) follows suit, and is the position at which the Player begins once they enter the new scene.

[UIFade](UIFade) is what allows the camera to fade to black when transitioning between different scenes after the Area has been transitioned.

[DialogueManager](DialogueManager) is responsible for setting up and managing all of the appropriate dialogue based situations in the area.

[DialogueStarter](DialogueStarter) is responsible for starting dialogue interactions with any NPC or object when a certain button is pressed by the Player.
