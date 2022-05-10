## SKU110K Dataset

This repository contains a series of notebooks that manipulate the SKU110K dataset created by Eran Goldman et al., as part of their work ["Precise Detection in Densely Packed Scenes"](https://arxiv.org/pdf/1904.00853.pdf) published at CVPR 2019.

For more details about the dataset itself, please visit the original [Dataset and Codebase](https://github.com/eg4000/SKU110K_CVPR19) repository.

### Files
    .
    ├── convert_yolov5.ipynb
    ├── README.md
    ├── SKU110K_fixed
        ├── images
            ├── test
            ├── train
            ├── val
        ├── labels
            ├── test
            ├── train
            ├── val

Here you will find the annotations (labels) and a notebook containing the process to download the SKU110K dataset and format the annotations in YOLOv5
format (`[class xmin ymin xmax ymax]` where the coordinates are normalized).

The annotations are included with my preferred directory structure for organization. N.B.: that they can all be contained in a single file as well. 

I've also included 1x sample image inside each one of the corresponding directories for demonstration purposes. You'll need to run the entire notebook
to get all of the images in the dataset.
