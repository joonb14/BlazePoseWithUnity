# BlazePoseWithUnity

Basically using Google's Mediapipe blazepose model which is converted by [creativIKEP](https://github.com/creativeIKEP/BlazePoseBarracuda) <br>
Thanks to [BlazePoseBarracuda](https://github.com/creativeIKEP/BlazePoseBarracuda) we could extract pose features in real time even at smartphones (S20, S21). <br>
Then we needed to use these features to move our avatar asset. <br>
We used method used in [ThreeDPoseUnityBarracuda](https://github.com/digital-standard/ThreeDPoseUnityBarracuda) where model updates skeleton directly by calculating difference between previous and current frame's pose landmarks. (Take a close look at the [VNectModel](https://github.com/digital-standard/ThreeDPoseUnityBarracuda/blob/master/Assets/Scripts/VNectModel.cs))<br>
We modified our code to utillize BlazePoseBarracuda model with VNectModel in ThreeDPoseBarracuda.<br>
### Demo
![pose](./blazepost-sample.gif)
