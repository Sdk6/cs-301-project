# baseline-performance
 
![image](https://user-images.githubusercontent.com/102538462/206788159-cc13c5a4-2e51-4233-ac07-c7ff60d8d1f5.png)

![image](https://user-images.githubusercontent.com/102538462/206788268-21de1baa-8345-4d88-b811-a6e5103183e4.png)


![image](https://user-images.githubusercontent.com/102538462/206788343-e18abf09-fc7e-47ab-8dc6-96ea10e8244e.png)

200 epochs:
![image](https://user-images.githubusercontent.com/102538462/206932724-2382e03e-bcab-4c84-94cb-9f2168c74b3b.png)

![image](https://user-images.githubusercontent.com/102538462/206932735-c00a2352-07da-4df9-b78a-6a3d0d22e534.png)

From the results of training our model with 100 epochs; we see that we can train our model relatively well, with a decent improvement for training loss as well as IoU. But validation loss and Iou gains were only marginal, seemingly stagnant.

Bumping up the epochs to 200; training and loss and IoU continue to increase. However the validation loss and IoU seem toi get worse. This shows our model is gettign very good at predicting on its training data but does not handle new data very well
