# UE5-VRPortfolio
This project show a sample of mechanics I implemented during my internship on an ArchiViz project.\
All these game mechanics can be found in the **Content/ArchiViz** folder.\
If you want to experience all of these in VR you only need to start in the scene "LVL_TestDynamicTexture" with your VR headset.

## Dynamic texture tool
This tool can be used by pointing to an object which contain the blueprint BP_SpawnFurnitureSwitchableMat. This object will, then, be highlighted to show player that he can use the tool. Finally, you can push the VR Trigger to switch on all materials.

## Menu InGame
In the same scene you will be able to find an InGame Menu grabbable by pushing the VR Grips. This menu is interractable by pointing a laser on it or simply moving a cursor with the controllers thumbstick.

## InGame Controllers Animations
If you play the scene as a VR Character you will be able to see that you have a specific duo of controller. These are the Oculus Quest 2 VR Controllers with animations I made with the animator provided by UE5 and the skeletal meshes you can find on the Oculus website.
I then attached these controllers to the VR Character to make it functionnal

## Sun Sky
Finally, in this scene you are able to see a compass on the floor which is normally colored. This compass is a part of the BP_SunSky which allow you to get a realtime sun in your scene which can be moved with the help of a slidebar in your menu by clicking the Y or B buttons of your VR controllers. This slidebar is based on the real hours in a day and rotate the sun around the scene following the hour you set. By the way, if you set it to night hours you will see some stars in the sky to show the player it's night time. Finally, this actor blueprint is totally reusable so you just need to drag&drop it in a scene to get it.
