# Tracking chocolates on conveyor belt using custom trained Yolov8


### Notebooks
1. video_to_image.ipynb - Convert video into images to get training data

2. autodistill.ipynb - Auto annotate images using Grounding DINO

3. run.py - script to make augmentations/albumentations of both images and annotations using variables in constant.yaml (special thanks to author of this article:
https://medium.com/red-buffer/apply-data-augmentation-on-yolov5-yolov8-dataset-958e89d4bc5d)

3. yolov8_training.ipynb - train yolov8(small) on custom data

4. byte_track.ipynb - track and count items using trained model alongwith bytetrack and supervision.