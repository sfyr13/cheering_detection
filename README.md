# cheering_detection

Python script to detect cheering events from a specific NBA game(clippers-lakers, Christmas 2022). MFCC is chosen as the optimal feature to be extracted as it performs very well on distinguishing human voice from other sounds. 13 MFCCs are then fed to a SVM for binary classification(cheering and non-cheering).
