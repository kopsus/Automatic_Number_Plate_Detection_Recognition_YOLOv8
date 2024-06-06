<H1 align="center">Number Plate Detection and Recognition using YOLOv8</H1>

## Steps to run Code

- Clone the repository

```
git clone https://github.com/kopsus/Automatic_Number_Plate_Detection_Recognition_YOLOv8
```

- Goto the cloned folder.

```
cd Number_Plate_Detection_Recognition_YOLOv8
```

- Install the dependecies

```
pip install -e '.[dev]'

```

- Setting the Directory.

```
cd ultralytics/yolo/v8/detect
```

- Downloading a Weights from the Google Drive

```
gdown "https://drive.google.com/uc?id=1dIyJooVaowaNUj0R1Q-HUnu-utiGsEj8&confirm=t"
```

- Run the code with mentioned command below (For Licence Plate Detection and Recognition).

```
python predict.py model='best.pt' source='test.png'
```

### RESULTS

#### Licence Plate Detection and Recognition

![](./ultralytics/example.png)

![](./ultralytics/example2.png)
