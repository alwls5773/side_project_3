## cancer 
#### 목적: 양성 종양과 악성 종양을 구분하는 머신러닝
#### 분석툴: sklearn, tensorflow
#### 결론

해당 데이터는 종양이 악성 종양인지 양성 종양인지에 대한 정보, radius와 texture, perimeter, area 등에 대한 정보가 평균, se, worst로 분류되어 있음. 
![image](https://github.com/alwls5773/side_project_3/assets/66359601/33a57876-9076-4bb6-a07f-f6a315cf4640)
![image](https://github.com/alwls5773/side_project_3/assets/66359601/4a43472d-ec9e-4f7c-8fee-eb0d55bc6e72)
![image](https://github.com/alwls5773/side_project_3/assets/66359601/c9c60dc1-c342-4ca4-8489-be72bbea8284)

GaussianNB
SVC
LogisticRegression
tree
RandomForestClassifier

0.9649122807017544
0.956140350877193
0.9736842105263158
0.9385964912280702
0.9649122807017544

0.9647382344750767
0.9562368871555263
0.9736214250146138
0.9387316420177368
0.9647382344750767

batch_size = 5, epochs = 30, learning_rate=0.001

model = tf.keras.Sequential([layers.Dense(8),
                             layers.Dense(16),
                             layers.Dense(8),
                             layers.Dense(2, activation = "softmax")])
                             
![image](https://github.com/alwls5773/side_project_3/assets/66359601/b312a721-3405-4e42-8077-226330a2b61d)
![image](https://github.com/alwls5773/side_project_3/assets/66359601/b84f876b-2dc3-4739-8d00-0fd25d21b1b8)


model = tf.keras.Sequential([layers.Dense(8),
                             layers.Dense(16),
                             layers.Dense(8),
                             layers.Dense(1, activation = "sigmoid")])

![image](https://github.com/alwls5773/side_project_3/assets/66359601/3b019ea2-ad1d-4ccf-9975-c78e041a7c88)
![image](https://github.com/alwls5773/side_project_3/assets/66359601/1ff82560-3661-4a38-9991-a2edfe11ef78)


model = tf.keras.Sequential([layers.Dense(8),
                             layers.Dense(16),
                             layers.Dense(8),
                             layers.Dense(4),
                             layers.Dense(1, activation = "sigmoid")])

![image](https://github.com/alwls5773/side_project_3/assets/66359601/55e5fd49-7e60-4bae-b6eb-adf109d6e6bc)
![image](https://github.com/alwls5773/side_project_3/assets/66359601/e30711ed-afd9-40ca-a976-e00727e7adb1)



model = tf.keras.Sequential([layers.Dense(8),
                             layers.Dense(16),
                             layers.Dense(4),
                             layers.Dense(1, activation = "sigmoid")])
![image](https://github.com/alwls5773/side_project_3/assets/66359601/171ed55c-830b-4761-b95e-ade2f4ac9e64)
![image](https://github.com/alwls5773/side_project_3/assets/66359601/7546d780-a6a1-4bdd-9e5e-0da41e7972a4)

batch_size = 5, epochs = 30, learning_rate=0.0005

model = tf.keras.Sequential([layers.Dense(8),
                             layers.Dense(16),
                             layers.Dense(4),
                             layers.Dense(1, activation = "sigmoid")])
![image](https://github.com/alwls5773/side_project_3/assets/66359601/170936bb-9233-4ff6-9ec1-3da44750353e)
![image](https://github.com/alwls5773/side_project_3/assets/66359601/81622a20-84ac-4211-ac17-0b7373ecadcc)

batch_size = 5, epochs = 30, learning_rate=0.0001

model = tf.keras.Sequential([layers.Dense(8),
                             layers.Dense(16),
                             layers.Dense(4),
                             layers.Dense(1, activation = "sigmoid")])

![image](https://github.com/alwls5773/side_project_3/assets/66359601/604f06df-e9cc-4a72-97d1-c70b2f4d6cfb)
![image](https://github.com/alwls5773/side_project_3/assets/66359601/eb65a4d8-ce91-46bc-bcb9-e7be3ea8d7f7)

batch_size = 5, epochs = 30, learning_rate=0.00025

model = tf.keras.Sequential([layers.Dense(8),
                             layers.Dense(16),
                             layers.Dense(4),
                             layers.Dense(1, activation = "sigmoid")])

![image](https://github.com/alwls5773/side_project_3/assets/66359601/43b31d31-b909-4159-8084-e9d0eff2c119)
![image](https://github.com/alwls5773/side_project_3/assets/66359601/81692667-81e9-4db9-b040-5bce2be240d7)

batch_size = 5, epochs = 50, learning_rate=0.0001

model = tf.keras.Sequential([layers.Dense(8),
                             layers.Dense(16),
                             layers.Dense(4),
                             layers.Dense(1, activation = "sigmoid")])

![image](https://github.com/alwls5773/side_project_3/assets/66359601/f190960c-a9c9-4a7b-b1b7-c7b84a25b67c)
![image](https://github.com/alwls5773/side_project_3/assets/66359601/e0497469-14fb-4f57-b75c-9e9258f94760)

batch_size = 5, epochs = 75, learning_rate=0.0001
![image](https://github.com/alwls5773/side_project_3/assets/66359601/7cb5901b-b79c-4bc1-9d92-0dbadd54bfaa)
![image](https://github.com/alwls5773/side_project_3/assets/66359601/3ca07d4b-5293-4bb0-a1e7-467789501c32)

batch_size = 5, epochs = 100, learning_rate=0.0001
![image](https://github.com/alwls5773/side_project_3/assets/66359601/c20b1389-91cc-4712-aca9-b024bcb2e5d6)
![image](https://github.com/alwls5773/side_project_3/assets/66359601/374cb48d-76c4-4e4b-8db8-ab55341f6134)


