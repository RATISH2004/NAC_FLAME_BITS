# NAC_FLAME_BITS

This project aims to detecct wild_fires from Aerial Images captured by drones. This project uses CNN model transfer learning to achieve binary classification. The main_train_model file can be run to train the model. Images should be in a folder with subfolders 0 and 1 (0:fire;1:No_fire). Developers can fine-tune the model as required. The implement test file can be run aftertraining the model to input an image and classify it. The bounding boxes is based in color detection
of the fire in an image. If there is fire in the image, the model would classify it as fire and color detection can be used to draw a bounding box. Run color detection file to get lower and uppr bound values for any colour as required (fire here). This project is to be expanded and woked on soon.
