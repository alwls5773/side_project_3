## cancer AI
#### 목적: 양성 종양과 악성 종양을 구분을 위한 인공지능
#### 분석툴: sklearn, tensorflow
#### 결론: 머신러닝 혹은 딥러닝 모델을 통해 종양이 양성인지 음성인지 판별할 수 있을 것임.

해당 데이터는 종양이 악성 종양인지 양성 종양인지에 대한 정보, radius와 texture, perimeter, area 등에 대한 정보가 mean, se, worst로 분류되어 있음. 
![image](https://github.com/alwls5773/side_project_3/assets/66359601/33a57876-9076-4bb6-a07f-f6a315cf4640)

### - Machine Learning
#### <model: accuracy, f1 score>

1. GaussianNB: 0.96, 0.96

2. SVC: 0.95, 0.95

#### 3. LogisticRegression: 0.97, 0.97

4. tree: 0.93, 0.93

5. RandomForestClassifier: 0.96, 0.96

### - Deep Learning
#### layer 층 구성하기 (batch_size = 5, epochs = 30, learning_rate=0.001)
1. Dense(8), Dense(16), Dense(8), Dense(2, activation = "softmax")
                             
![image](https://github.com/alwls5773/side_project_3/assets/66359601/fb9c306a-26cc-4b18-bb55-160e693cc7bd)
![image](https://github.com/alwls5773/side_project_3/assets/66359601/66184404-3ac4-4e45-9972-1f2a9e08e1dc)

2. Dense(8), Dense(16), Dense(8), Dense(1, activation = "sigmoid")

![image](https://github.com/alwls5773/side_project_3/assets/66359601/bd9be394-de1f-4a23-a77d-4f9db7d777bc)
![image](https://github.com/alwls5773/side_project_3/assets/66359601/4fe86c12-5ed2-4213-9af5-ae1cb0e93d77)

3. Dense(8), Dense(16), Dense(8), Dense(4), Dense(1, activation = "sigmoid")

![image](https://github.com/alwls5773/side_project_3/assets/66359601/7655263d-3448-405f-bc6c-677f93f29d26)
![image](https://github.com/alwls5773/side_project_3/assets/66359601/cb74a292-0c4c-461c-85ad-ae947bf82f67)

#### 4. Dense(8), Dense(16), Dense(4), Dense(1, activation = "sigmoid")

![image](https://github.com/alwls5773/side_project_3/assets/66359601/86a415c8-425a-413b-a54b-8f7be87aaecb)
![image](https://github.com/alwls5773/side_project_3/assets/66359601/fbacb920-900f-4791-8aa1-bb6aee0d9529)

#### learning_rate 설정하기 (batch_size = 5, epochs = 30)

1. learning_rate=0.0005

![image](https://github.com/alwls5773/side_project_3/assets/66359601/b1fa4163-b1f3-43d5-bb14-a37254155425)
![image](https://github.com/alwls5773/side_project_3/assets/66359601/57452e3d-47cb-49c2-8e6e-51df491b5771)

#### 2. learning_rate=0.0001

![image](https://github.com/alwls5773/side_project_3/assets/66359601/83cd30f1-5213-4d19-891d-2f76f0c611c9)
![image](https://github.com/alwls5773/side_project_3/assets/66359601/1411afc6-2dbd-4229-8949-403b197e77c8)

3. learning_rate=0.00025

![image](https://github.com/alwls5773/side_project_3/assets/66359601/9af81935-65ba-4853-96b5-556122be5f8f)
![image](https://github.com/alwls5773/side_project_3/assets/66359601/12084db4-1a58-4fea-a5b4-afef0bd9a8b8)

#### epoch 설정하기 (batch_size = 5, learning_rate=0.0001)
1. epochs = 50
                             
![image](https://github.com/alwls5773/side_project_3/assets/66359601/8f16077b-bc3c-4684-a526-4130e3a6b204)
![image](https://github.com/alwls5773/side_project_3/assets/66359601/3b350d92-1af3-43e3-b3dc-73836b6a764a)

2. epochs = 75

![image](https://github.com/alwls5773/side_project_3/assets/66359601/b1c38f67-fdcb-4011-b522-00ee1e499089)
![image](https://github.com/alwls5773/side_project_3/assets/66359601/7067f27b-9eb2-4644-b19b-f2cd1a689acd)

3. epochs = 100

![image](https://github.com/alwls5773/side_project_3/assets/66359601/d42ea77e-e761-4f63-87dc-b784355d7dff)
![image](https://github.com/alwls5773/side_project_3/assets/66359601/ad5d474a-8c3c-45df-a3f7-716f65ce217f)

