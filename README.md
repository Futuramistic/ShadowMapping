# Shadow Mapping
Shadow mapping using textures. The project was developed for CS4247 (Graphics Rendering Techniques) at NUS. 

Each scene is rendered twice. 
First, we render the scene using light as a viewpoint. Z-buffer values are stored in a separate texture.
When scene is re-rendered from the original viewpoint, we compare Z-buffer value with the one stored in the texture - if not equal, the point must be in shadow.
 
  ### Projection image 1
 <img src="https://github.com/Futuramistic/ShadowMapping/blob/master/images/shadow1.PNG">
 
 ### Projection image 2
 <img src="https://github.com/Futuramistic/ShadowMapping/blob/master/images/shadow2.PNG">
 
