

## Tiny Face Detector in TensorFlow

 The original repository of Tiny Faces can be found in [here](https://github.com/cydonia999/Tiny_Faces_in_Tensorflow).

#### Tesing Tiny Face Detector in TensorFlow

1. Prepare images in a directory.

2. `tiny_face_eval.py` reads images one by one from the image directory and
write images to an output directory with bounding boxes of detected faces.
```
python tiny_face_eval.py
  --weight_file_path /path/to/pickle_file
  --data_dir /path/to/input_image_directory
  --output_dir /path/to/output_directory
```

 > python3 tiny_face_eval.py --weight_file_path weights.pkl --data_dir testimages/ --output_dir predictedimages/ --line_width 3 --display True

## FaceNet Detection in TensorFlow

The original repository of FaceNet can be found in [here](https://github.com/davidsandberg/facenet/tree/master/src/align).

#### Tesing Tiny Face Detector in TensorFlow

1. Prepare images in a directory.

2. `align_dataset_mtcnn.py ` reads images one by one from the image directory and
write images to an output directory with bounding boxes of detected faces.

```
python3 align_dataset_mtcnn.py testimages/ output/
```
