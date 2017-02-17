3D House using threejs

1.Implemented this assignment in threejs.
	The main reason I chose threejs is easiness to use and we dont have to install any extra plug-ins.There is a lot of material on concepts and examples
	to understand threejs.
2.Used texture mapping for walls of the house and images for windows, doors, grass
	I first collected all the images needed for the house and then applied various texture mappings on the house and the grass.
	The house construction includes various tranformations for objects ( cube, windows, triangles) and positioning - used cube to draw the 
	base of the house and set of triangles to construct the house roof. 
		
3.Applied bump mapping on the walls of the house - using the two images (wallbase and texturebase.jpg)

4.Used shineniness on roof of the house (MeshLambertMaterial)

5. I have added zoom-in/ zoom out, shadows and walk through the house (and even inside the house) 
	using the javascript functions orbitcontroller.js
	Implemented lighting (used ambient light) and directional light and implemented shadows for the house on the grass. Also made the apperance of the 
	house look more natural with open windows and placed some objects inside the house

References used:
https://dvigneshwer.wordpress.com/tag/js/-with-three-js-part-1/
https://jsfiddle.net/jmchen/87wg5z27/
http://jsfiddle.net/yomotsu/gyPJQ/
http://threejs.org/examples/misc_controls_orbit.html
