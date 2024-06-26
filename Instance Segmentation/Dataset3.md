# Directory Description
- The dairy goat image dataset is divided according to the PASCAL VOC 2012 format and contains a total of three folders: img, gt, and list.
- The img folder stores all the original images (3008) in the dairy goat dataset, including both training and test set images.
- The gt folder contains the annotation files corresponding to each image in the dataset, with each annotation file uniquely corresponding to one dairy goat instance. The naming format of each file is: "filename#instance_number.png", where the instance number is an integer starting from 1 and increasing, with a maximum value not exceeding 255. The largest instance number following the same filename indicates the number of dairy goat instances contained in the image corresponding to that filename. Note: In the annotation files (i.e., .png images) under the gt folder, each instance object area is represented by a single digit from 1 to 255, while the rest of the area is considered the background area, represented by 0. For example, 00000001#1.png indicates that the current file corresponds to the annotation file of 00000001.jpg, and the area with the number 1 in 00000001#1.png represents the area corresponding to that instance, with the rest being the background area, represented by 0.
- The list folder contains the txt files corresponding to the training and validation set images. train.txt and val.txt correspond to the txt files of the training and validation set images, respectively, while train_inst.txt and val_inst.txt correspond to the txt files of the training and validation set annotation files, respectively.
# Directory Structure
- ## list [dataset split]
  - val_inst.txt
  - val_inst.txt
  - train_inst.txt
  - train.txt
- ## img [images]
  - image_id.jpg
  - image_id.png
  - ....
- ## gt [ground truth]
  - iamge_id#x.png
  - ....
  
