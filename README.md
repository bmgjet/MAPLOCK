# MAPLOCK
Remove entitys as they are loading from a given location, Use on a invalid prefab to protect your map file.<br><br>
How to use:<br><br>Place a prefab on the map that will stop server from loading.<br>
Make sure its position is something simple and positive like X:350 Y:600 Z:199<br>
Copy those position values into plugin  where it says Vector3(0f, 0f, 0f);<br>
Such as Vector3(350f, 350f, 199f);<br><br>
Save plugin changes. Map should now start like normal since it will remove any prefab with that exact location on its creation.
