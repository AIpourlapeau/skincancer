This folder contains supplementary materials for the paper:
*"SkinCancerAI: Image-based detection of skin cancer using hierarchical learning"*

The folder contains:
- List of class and sub class.pdf: file describing in detail the classification system for skin cancer detection,
    which contains 10 classes and 122 sub-classes.
- isic-images-info.csv: file storing information of the images in the folder "isic". The csv file contains 6 columns:
    - image_name: name of the image
    - class: class label of the image
    - subclass: subclass label of the image
    - is_macro: status indicating if the image is dermoscopic (value 0) or macroscopic (value 1)
    - ISIC_ID: identity of the image in the original ISIC dataset
    - duplicate_id: duplicate ID of the image, ranges from 0 to 1521 if available.
        Images with the same duplicate ID look almost the same.