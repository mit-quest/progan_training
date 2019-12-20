Steps to Train a proggan with specific dataset
1. Clone code with git clone https://github.com/tkarras/progressive_growing_of_gans
2. Install required Python packages with pip install -r requirements-pip.txt
3. Create .tfrecords of images by running python dataset_tool.py create_from_images [directory of images] [directory you want tfrecords to go]
4. Go to config.py and change tfrecord_dir to the one you named in Step 3 above
5. Run training script with python train.py and results will be in folder named config

Directories
1. proggan_vacation - trained on ~30k images (a portion of landscape dataset, mainly water, beaches, and lighthouses)
2. proggan_all_places65 - trained on the full landscape dataset

