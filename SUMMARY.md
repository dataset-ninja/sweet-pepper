**Sweet Pepper and Peduncle Segmentation** is a dataset for instance segmentation, semantic segmentation, and object detection tasks. Possible applications of the dataset could be in the agricultural industry. 

The dataset consists of 620 images with 6422 labeled objects belonging to 8 different classes including *green fruit*, *red fruit*, *green peduncle*, and other: *yellow fruit*, *red peduncle*, *yellow peduncle*, *orange fruit*, and *orange peduncle*.

Images in the Sweet Pepper dataset have pixel-level instance segmentation annotations. Due to the nature of the instance segmentation task, it can be automatically transformed into a semantic segmentation (only one mask for every class) or object detection (bounding boxes for every object) tasks. There is 1 unlabeled image (i.e. without annotations). There are no pre-defined <i>train/val/test</i> splits in the dataset. The dataset was released in 2021.

Here is the visualized example grid with animated annotations:

[animated grid](https://github.com/dataset-ninja/sweet-pepper/raw/main/visualizations/horizontal_grid.webm)
