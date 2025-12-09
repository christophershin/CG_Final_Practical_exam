# CG_Final_Practical_exam


Shader Resources:
https://learn.ontariotechu.ca/courses/34225/modules

video references - https://www.youtube.com/watch?v=KbX6wCS5isE

Water texture: https://learn.ontariotechu.ca/courses/34225/files/5636692?module_item_id=808010

water scrolling - https://learn.ontariotechu.ca/courses/34225/pages/water-scrolling?module_item_id=810522

Creating the gifs - https://ezgif.com/video-to-gif/ezgif-8731fb08d534dc6f.mp4.html


Deliverables:

Stencil:


![ezgif com-video-to-gif-converter (2)](https://github.com/user-attachments/assets/bf66f0c3-5639-4afb-bb91-d59256b53903)


For Stencil I added it to the quads that resemble the clouds or mountains in the background which then reveals the water behind it. First I created a quad for the stencil read and the then put it on top of the objects I want to make transparent which has the stencil front. This also cuts off the bottom of the quads to create a clean flat finish. The effect allows me to add more obstacles in the scene and still makes the water visible but doesn't show the bottom of the clouds. This I think is more versatile since you can have a huge water backround and then have a stencil read of different sizes to show different variations in the level design. 


Polygon surface deformation:


<img width="120" height="160" alt="image" src="https://github.com/user-attachments/assets/99cb8a13-5266-4a0f-a077-d1a0fe368d16" />


For the polygon surface deformation, I added a bump map to the block under the bridge since they have more details than the other objects in the environment such as screws, grooves or divets. I added a bump map using this script from here https://learn.ontariotechu.ca/courses/34225/pages/bump-shader?module_item_id=800762. I then took a screen shot from the video of the texture and added it to the block object this way it stays true to the look of the original game.







The two additional shaders I added: 


- Toon(first half of the course):

- <img width="758" height="270" alt="image" src="https://github.com/user-attachments/assets/db5ab4c6-b09b-471d-a25f-1471c994184a" />


  for toon shader I added it to the background so that there aren't any high fidelity light or shadows in the scene since this is a 2D game. I added a toon shader from https://learn.ontariotechu.ca/courses/34225/pages/toon-shader?module_item_id=802766 and then changed the base color to a dark blue and the Rim color to black to make the background dark. I also added it to the character and the enemy to also add a cartoony effect as well as I changed their respective colors to match the screenshot. I additionally added it to the bridge object which to fit the 2D artstyle, to also  make it look like the screenshot, I changed the colors to a dark grey.


- Scrolling Textures(second hald of the course):

  ![ezgif com-video-to-gif-converter (1)](https://github.com/user-attachments/assets/dd391618-67cb-4dd4-a3dd-78dc08e6a644)

  
    For the scrolling texture I added it so the scene because in the video I sourced there is water that moves at the bottom. I used the scrolling texture instead of the water shader because if you are viewing the scene to the side the water shader you would instead see a single dimensional water scene which I do not want. So instead I used the scrolling texture since that shows the water moving much like the video but also it fits more to the 2D look of the game. I first added the scrolling water to a quad and then look a screen shot of the slides https://learn.ontariotechu.ca/courses/34225/files/5636692?module_item_id=808010 with the water in it. I then added that water texture to the shader and shaped the quad accordingly. 

  
