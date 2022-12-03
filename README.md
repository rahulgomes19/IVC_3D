# IVC_3D

Step 1 includes preprocessing of CT scan slices using normalization, 40cm cut-off and compiling them to a numpy array. <br>
Step 2 includes running the 3D_UNet_Patches_Training.html on the compiled numpy array.<br>
Step 3 includes running the IVC_Object_Detection_Pipeline.html using the trained UNet model to detect IVC object and remove artefacts. <br>
