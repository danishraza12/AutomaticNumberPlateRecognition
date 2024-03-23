# Automatic Number Plate Recognition with OCR
I have used tensorflow to train a model in order to detect number plates in images and have then proceeded to apply OCR on the detected region so as to extract the text.

Since I have trained the model on CPU so I have not added code for GPU support in the notebook, however the code can be found in Nicholas Renotte's notebook.

Since I have created this project on a windows based device I had trouble installing pycocotools as it is not compatible with windows so I had to install pycocotools from https://github.com/cocodataset/cocoapi
