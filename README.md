# Hacktech

## Data Training with DETRAC Dataset

To train the model using detrain data. upload the below folder in your drive and run the Detrac_train.ipynb.
Upload the [Folder](https://drive.google.com/drive/folders/1X-gCnYc2KJ_txs4xfAnXln13xi_CZYwM?usp=sharing) in your drive.

## Speed detection Detrac dataset

We have trained the model using annotations from the DETRAC dataset and pretrained yolo.

To run these, follow the below steps

Step 1 : 

To run pretrained objection + deepsort pytorch for speed detection, run Pretrained_yolo.ipynb. Make sure to give your video path at source

```bash
!python predictown.py model=modelname source=video_path save_txt=True
```


## The detrac dataset training using yolo with deepsort performs better than pretrained yolo
