1] Please download the following essential libraries/packages

python 

numpy

torch                       

torchvision  
mxnet-cu90

scikit-learn

scikit-image

scipy

nibabel

tqdm

SimpleITK

itk

opencv-python

mxboard

matplotlib

tensorboard

dicom                  

h5py                          

pandas                 

pickleshare                 

pillow                 

protobuf               

pydicom                               

seaborn                         

         



2] Data pre-processing/augmentation



run python augment_dataset.py 



There is an argparser, so you can just pass your arguments
via terminal




- data_directory : should link to the path of the dataset root directory, and should contain both HGG and LGG subdirectories


- augmented_directory - this directory will store the output of the augmentation techniques




As an alternative, we also came across a library which was created by researchers

for perfroming augmentations specifically for the tumor segmentation task, so

you can use that too:


pip install --upgrade batchgenerators




3] Experimentation



run python train.py/validate.py



There is an argparser, so you can just pass your arguments

via terminal for selecting parameters like batch size,
 optimizer, learning rate, epochs, etc.

