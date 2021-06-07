# Dog-Breed-Classification
TFLite Model for Detection of Dog Breeds and Implementing an Android App with it (built around TFL Classify)

### Prerequisites: 
* Train your model and generate the required *.tflite* file. This is one of the [Tutorials](https://colab.research.google.com/drive/1sqBewUnvdATOO-yblj55EBFb2sM24XHR) you can follow to train your required model.
* Install Android Studio.

### Steps to Build your App:
* Download/Clone this repository. 
* Unzip it to a location you desire.
* From Android Studio, Open an Existing Project and select the **DogBreedApp** folder.
* Wait for a few moments for the project to initialize and build. 
* To use your model, replace the *model.tflite* file in the ```models/assets``` directory with your model. Make sure your tflite file is also named as *model.tflite*.
* Do the same for the *labels.txt* file.
* You can change the App Layout from the *.xml* files in layout directory. Experiment with it.

#### Running the App:
* Connect your Android device (Phone) to your laptop via USB cable.
* Enable USB Debugging on your Phone. 
* Verify that your Device Name is selected in the display next to the "Run" button on Android Studio. 
* Now you can Run and Use your App. 

#### For Downloading the App
* Download the *.apk* file - DogBreedDet.apk
* Turn off Play Protect in your Play Store.
* Accept any Pop-Ups that might appear while installing the app through *.apk* file.

