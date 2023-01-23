# YOLOv8Face
## Face Detection with YOLOv8
### Examples 

<p align="center">
    <img width="800" src="https://user-images.githubusercontent.com/79300456/214137873-91182723-1410-4679-b386-907eee1b8c14.png" alt="Material Bread logo">
</p>

### Usage
- Make a pip env
```
python3 -m venv ./venv
```

- Activate the env
```
source ./venv/bin/activate
```

- Install ultralytics

```
pip install ultralytics
```

- Use infer.py module for inference

```
python infer.py
```

### Training process
1. I made a dataset of over 20k images containing people.
2. I get ground-truth bounding boxes using MTCNN
3. Trained YOLOv8 on the dataset for face detection
```
Please note that the dataset and the training procedure should be improved for boosting the performance.
```


### Refs
A big :thumbsup: for ultralytics
[ultralytics Pages](https://github.com/ultralytics/ultralytics)
