# Hacktech
## Data Training with DETRAC Dataset

We have trained the model using annotations from the DETRAC dataset. The link for the dataset is SUNY Albany UA-DETRAC benchmark suite: https://detrac-db.rit.albany.edu/. The training ipynb file is placed inside the repo.

Step 1 : 

Upload the [Folder](https://drive.google.com/drive/folders/1X-gCnYc2KJ_txs4xfAnXln13xi_CZYwM?usp=sharing) in your drive.

Step 2:

Clone this repository in the colab in the same account which has the dataset.

```bash
!git clone https://github.com/amirtha19/Hacktech
```

Run the Detrac_train.ipynb inside it.

## Data Training with DETRAC custom annotation dataset

Since the data in detrac is not fully annotated for all the objects in a frame, we custom annotate using Roboflow. I have provided the snippet inside the Custom_annotation_train.ipynb. To run this, Clone this repository and run the Custom_annotation_train.ipynb inside it.
