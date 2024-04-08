# Pressure_Validation
Deep Learning model built to validate Pressure variations in Handwitten images ( low, high)

Libraries Required prior to running the code : 
OpenCV (cv2)
NumPy (np)
Pandas (pd)
Matplotlib (plt)
TensorFlow (tf)
Keras
scikit-image (skimage)
Pillow (PIL Fork)
imghdr
fitz (PyMuPDF)
albumentations
lime
Install all these using the command: pip installopencv-python numpy pandas matplotlib tensorflow keras scikit-image Pillow imghdr PyMuPDF albumentations lime

Instructions: 
For training Your own handwriting validation model: 
1.Open the Pressure_val.ipynb notebook file in any IDE (Jupyter,Vscode etc).

1.Make sure you have your image datasets organized in folders based on their classes ("low" and "high").
2.If using a PDF for image extraction, ensure it is in the specified location (pdf_file_path).
3.Run data loading part directly if augmentation is not required and ensure your desired parameters are set as hyperparameters.
4.Follow through till the model architecture block where you can experiment with the model parameters for fine tuning.("not necessary")
5.run (model.fit) block to start training your own model and save it using (model.save) block.
6.The model will be trained on number of epochs (iterations).
