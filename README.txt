For the reflection shader, I used the base code from the lecture. It has different reflection intensity, blend, power, and boost.

For the texture tiling, I created a image in Photoshop using the colours from Battletoads to make a ground texture. I then applied this to a shader and added it to the ground. 

The player character has multiple UVs. I created two different textures in Photoshop and made a Shader Graph with both UVs multiplied to the same texture.

The enemy on screen has Lambert lighting applied when he appears on screen.

I used another texture shader for the lava below and made it similar to how the ground texture is tiled.

I also added an addition Ambient lighting shader to the lava to make it more like actual lava rather than a picture.