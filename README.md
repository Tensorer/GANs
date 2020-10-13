Project title: "Data Mapping with Generative Adversarial Networks".
This project mainly uses TensorFlow 2 for network modeling. 
To run the code, please first download all the files and create a Conda environment based on "GANs_environment.yaml". 

File instruction:
"GANs_environment.yaml" 
- Conda environment.

"Result-After-Training-Spatial_Attention_GANs.ipynb"
- The numerical and visualized results after finishing training the Spatial Attention-based Cycle GANs. That is, the result of running "Test-4.ipynb".
- Network structure includes two Spatial Attention-based U-Net generators (Add spacial attention after the sixth downsampling layer) and two PatchGAN discriminators.

"Test-1.ipynb"
- Runnable code of one of the network structures.
- Network structure includes two U-Net generators and two PatchGAN discriminators.

"Test-2.ipynb"
- Runnable code of one of the network structures.
- Network structure includes two Spatial & Channel Attention-based U-Net generators (Add spatial & channel attention after the sixth downsampling layer) and two PatchGAN discriminators.

"Test-3.ipynb"
- Runnable code of one of the network structures.
- Network structure includes two Channel Attention-based U-Net generators (Add channel attention after the sixth downsampling layer) and two PatchGAN discriminators.

"Test-4.ipynb"
- Runnable code of one of the network structures.
- Network structure includes two Spatial Attention-based U-Net generators (Add spatial attention after the sixth downsampling layer) and two PatchGAN discriminators.

"Test-5.ipynb"
- Runnable code of one of the network structures.
- Network structure includes two Spatial & Channel Attention-based U-Net generators (Add spatial & channel attention after all downsampling layers) and two PatchGAN discriminators.

"Test-6.ipynb"
- Runnable code of one of the network structures.
- Network structure includes two U-Net generators and two Spatial & Channel Attention-based PatchGAN discriminators (Add spatial & channel attention after the third downsampling layer).

"Test-7.ipynb"
- Runnable code of one of the network structures.
- Network structure includes two U-Net generators and two Channel Attention-based PatchGAN discriminators (Add channel attention after the third downsampling layer).

"Test-8.ipynb"
- Runnable code of one of the network structures.
- Network structure includes two U-Net generators and two Spatial Attention-based PatchGAN discriminators (Add spatial attention after the third downsampling layer).

"Test-9.ipynb"
- Runnable code of one of the network structures.
- Network structure includes two U-Net generators and two Spatial & Channel Attention-based PatchGAN discriminators (Add spatial & channel attention after all downsampling layers).

"dataset" Folder
- Contains the data set used by the project.
