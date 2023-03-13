1. Download Dataset from Kaggle. Face Mask Lite Dataset. https://www.kaggle.com/prasoonkottarathil/facemask-lite-dataset 

2. Generate Masked faces using MaskTheFace https://github.com/aqeelanwar/MaskTheFace. 

3. Use Preprocessing.ipynb to preprocess the images and save test and train set as numpy arrays.

4. Open RGB2RB.ipynb, load saved numpy dataset preprocessed for RGB2RGB model. Run the model. 

5. Open RGB2SKETCH.ipynb, load saved numpy dataset preprocessed for RGB2SKETCH model. Run the model. 

6. Load the best model and generate images.