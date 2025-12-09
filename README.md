PSX style effects for UE5, created and tested on UE5.5 on Fedora Linux

To use, simply copy and paste this into your UE5 project content folder, in a PSX-Effects folder

For any new material just right click and create a material instance, and you can apply the texture and modify the other material properties through the parameters of the instance

Please note any model imported needs to have nanite disabled on import, otherwise it'll try and simplify the mesh, which will mess up any of the added polygons on flat surfaces and mess up the affine mapping.
