# Periocular_Recognition_in_the_Visible_Spectrum
The periocular region refers to the area around the eye that may include eyebrows, eyelashes, eyelids,  shape of the eye, height, texture of the skin, eye width, etc. It is considered that only these features  are accessible due to occlusions in the input image. The model aims to work with and provide  optimum results with the minimal feature information available and perform recognition.

EXECUTE THE CODE WITH EXISTING DATASET:

1. Upload the Periocular_Recognition file to google drive account
2. Copy the link of trainset and paste it in the line 343 in recog.html file to open your database from the UI directly
3. Open UI.ipynb in the collab environemnt and run each cell sequentially
4. Open the 2nd link with the ngrok term for accessing the web UI.
5. You can either register or use the default values as username: admin@gmail.com and password: admin
6. Then you may train, validate, create or edit database and perform recognition
7. Download the testset locally to select image for recognition and then perform recognition

EXECUTING WITH CUSTOM DATASET:

1. Download the Periocular_Recognition_Custom from the custom folder.
2. Rename it to Periocular_Recognition and uplopad to google drive
3. Add photos of each subject in respective folders and add it to trainset and similarly validation photos of each subject in their respective folders in the valset.
4. In UI.ipynb, change the people_in_db dictionary on line 49 2nd cell, to "foldername: subject name" key-value pairs in the same fashion as existing.
5. Create empty folders with respective subject folder names for all subjects in augment set, if augmentation needed. In this case also run the augmentation function.
6. Create empty folder with respective subject folder names for all subjects consisting of two other empty folders called left and right respectively for each and every subject. This must be added to clahe set and roi set.
7. Then open the UI.ipynb in the google colab and run similar to the previous case. 
8. Test images must be added to the testset folder within the dataset1 folder, static folder and the Code folder.
9. Download the testset locally to select image for recognition and then perform recognition

If any queries refer to the structure in the given folders and follow the same.
