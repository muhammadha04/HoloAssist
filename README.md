# HoloVisionAssist
HoloVisionAssist (MR app) leverages YoloV7 for real-time object detection via HoloLens 2, pinpointing and marking locations in 3D space with virtual pins.

https://github.com/muhammadha04/HoloAssist/assets/103769302/063a5086-5c0f-4535-9644-96bf46a3efce


## Prerequisites
+ HoloLens 2 device with the latest software update

+ Unity version 2021.3.16 or higher

+ Visual Studio 2022 with UWP development tools

+ for the pre-trained YoloV7, please refer to: [PINTO model zoo](https://github.com/PINTO0309/PINTO_model_zoo).




## Project Setup
+ Clone the repository to your local machine using " git clone https://github.com/muhammadha04/HoloVisionAssist.git "
+ ### Model Placement

  +  Place the YoloV7 ONNX model in the directory Assets\Application\Model indicated below.

  -   The application expects the model to be in this specific directory path to function correctly, make sure to move it before opening the project.

+ Open the project in Unity.
  
![image](https://github.com/muhammadha04/HoloAssist/blob/master/Screenshot_3.png)

+ Below is the correct build settings. This includes architecture, build type, and other relevant configurations required for the project to work on HoloLens 2. (VS22)

![image](https://github.com/muhammadha04/HoloAssist/blob/master/Screenshot_2.png)




## Acknowledgments
Thanks to Joost van Schaik for the detailed guide on setting up and running mixed reality applications on HoloLens 2.

Hat tip to anyone whose code was used as a reference.

Special thanks to all contributors who helped in bringing this project to life, especially Amplilab.
