# speed challenge (closed)

Goal :: Predict speed of car from dashcam video

Split up the data into train(90%) and validation(10%). 

Estimated hf factor : : 7127.9783

| variable | meaning |
| -------- | ------- |
|     h    | constant height of camera from the ground plane |
|     f    | focal length for the given camera |

MSE -
 - Train - 3.7481
 - Validation - 0.9048


| Train Plot | Validation Plot | Test Plot |
| ---------- | --------------- | --------- |
| ![Train Plot](/train-result.png) | ![Validation Plot](/valid-result.png) | ![Test Plot](/test-result.png) |

Key points are tracked using a mask as shown in the sample gif. Rotation of camera is not considered.
![Car KeyPts](/car-keypts.mp4)

Referred to this [blog post](https://nicolovaligi.com/car-speed-estimation-windshield-camera.html) for some guidance.
