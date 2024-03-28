# Dataset [Link]()
# Directory Description
- Image annotation files all have a .json suffix and are in COCO format.
- In this dataset, the ratio of train to test to val is 8:1:1.
- The annotations include labeling information for train, test, and val. When using this dataset for model training, you can also re-segment the annotations to generate new train, test, and val datasets.
# Directory Structure
- ## annotations [Data Split]
  - val.json
  - train.json
  - test.json
  - annotations.json
- ## JPEGImages
  - image_id.jpg
  - image_id.png
  - ....

