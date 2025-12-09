# CG_Final_Practical_exam


Shader Resources:
https://learn.ontariotechu.ca/courses/34225/modules

video references - https://www.youtube.com/watch?v=KbX6wCS5isE

Water texture: https://learn.ontariotechu.ca/courses/34225/files/5636692?module_item_id=808010

water scrolling - https://learn.ontariotechu.ca/courses/34225/pages/water-scrolling?module_item_id=810522


For Stencil I added it to a quad that reveals the water behind it. First I created a quad for the stencil read and the then put it on top of the object I want to make transparent which has the stencil front. This also cuts off the bottom of the quad to create a clean flat finish. 


For the polygon surface deformation, I added a bump map to the bridge and the block under the bridge since they have more details than the other objects in the environment such as screws, grooves or divets. I added a bump map using this script from here https://learn.ontariotechu.ca/courses/34225/pages/bump-shader?module_item_id=800762. I then took a screen shot from the video of the texture and added it to the block object. 









The two additional shaders I added: 

- Toon(first half of the course):
  for toon shader I added it to the background so that there aren't any high fidelity light or shadows in the scene since this is a 2D game. I added a toon shader from https://learn.ontariotechu.ca/courses/34225/pages/toon-shader?module_item_id=802766 and then changed the base color to a dark blue and the Rim color to black to make it look like a dark background.

- Scrolling Textures(second hald of the course):
    For the scrolling texture I added it so the scene because in the video I sourced there is water that moves at the bottom. I used the scrolling texture instead of the water shader because if you are viewing the scene to the side the water shader you would instead see a single dimensional water scene which I do not want. So instead I used the scrolling texture since that shows the water moving much like the video but also it fits more to the 2D look of the game. I first added the scrolling water to a quad and then look a screen shot of the slides https://learn.ontariotechu.ca/courses/34225/files/5636692?module_item_id=808010 with the water in it. I then added that water texture to the shader and shaped the quad accordingly. 

  
