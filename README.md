# Hacktech
## Speed detection using pretrained

We have trained the model using annotations from the DETRAC dataset,custom annotated Detrac dataset and pretrained yolo.

To run these three follow the below steps

Step 1 : 

To run pretrained objection + deepsort pytorch for speed detection, run Pretrained_yolo.ipynb. Make sure to give your video path at source

```bash
!python predictown.py model=modelname source=video_path save_txt=True
```
Data Training with DETRAC Dataset

To train the model using detrain data. upload the below folder in your drive and run the Detrac_train.ipynb.
Upload the [Folder](https://drive.google.com/drive/folders/1X-gCnYc2KJ_txs4xfAnXln13xi_CZYwM?usp=sharing) in your drive.


## Data Training with DETRAC custom annotation dataset

Since the data in detrac is not fully annotated for all the objects in a frame, we custom annotate using Roboflow.Run the roboflow custom_annotation_train.ipynb
