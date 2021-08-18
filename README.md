# COCO_dataset_YOLOv5_test  


#### YOLO v5 object detection test using COCO dataset 
#### 데이터셋 : COCO(comman object in context) : 마이크로 소프트에서 만든 객체탐지에 사용되는 데이터셋
#### train 이미지 수 : 116408, validation 이미지 수 : 5000
#### 모델 : YOLO v5  


### 8.11. first test
#### batch : 16
#### epochs: 1
#### imagesize: 640  
####  1 에폭 학습시키는데 구글 코랩 gpu 기준 1시간정도 소요됨  


### 8.18. additional tests
#### epochs: 15



# 모델 학습 결과


### P_curve
<img src="https://user-images.githubusercontent.com/49335804/128989766-0151ebe4-5f4d-4d46-b3e4-9d44ea70d21f.png" width="50%" height="50%"/>  

### R_curve
<img src="https://user-images.githubusercontent.com/49335804/128990079-39c9e3bd-125b-474e-9a0e-b8f0c6590bc1.png" width="50%" height="50%"/>  

### PR_curve
<img src="https://user-images.githubusercontent.com/49335804/128990541-8cc3324a-8127-46db-a3f7-e5df9721529c.png" width="50%" height="50%"/>  

### F1_score
<img src="https://user-images.githubusercontent.com/49335804/128990635-b8a2ac17-c4a9-450c-99a7-52d05195bd29.png" width="50%" height="50%"/>  

### confusion_matrix
<img src="https://user-images.githubusercontent.com/49335804/128990713-c9c99361-5398-4b3b-96f1-83321b4ca09d.png" width="50%" height="50%"/>  

### train_batch_0
![train_batch0](https://user-images.githubusercontent.com/49335804/128990864-c130d71c-2468-47db-a764-f5c7005a5ab4.jpg)


### train_batch_1
![train_batch1](https://user-images.githubusercontent.com/49335804/128990922-6808a4d8-0c8c-42cd-9b6c-add67cd37e80.jpg)


### train_batch_2
![train_batch2](https://user-images.githubusercontent.com/49335804/128990980-f57fefad-572d-45e0-b8b2-6d8d3b09fba8.jpg)


### validation_batch_labels_0
![val_batch0_labels](https://user-images.githubusercontent.com/49335804/128991021-2c226d1f-2375-4318-8db0-406d55a1681e.jpg)


### validation_batch_predict_0
![val_batch0_pred](https://user-images.githubusercontent.com/49335804/128991065-fca5f721-b733-41ac-8edd-452461b9920d.jpg)


### validation_batch_labels_1
![val_batch1_labels](https://user-images.githubusercontent.com/49335804/128991222-6047b560-6302-47a4-8cf3-2264e7e1b313.jpg)


### validation_batch_predict_1
![val_batch1_pred](https://user-images.githubusercontent.com/49335804/128991164-69503342-8045-4ab9-98b4-9b18e796035c.jpg)


### validation_batch_labels_2
![val_batch2_labels](https://user-images.githubusercontent.com/49335804/128991257-4f0e0ec0-d4d4-43ac-8a84-9fde44c4e869.jpg)


### validation_batch_predict_2
![val_batch2_pred](https://user-images.githubusercontent.com/49335804/128991332-151ddc5c-5463-4101-9c66-c049dc53da48.jpg)

  
## 8.11. test results

# YOLO data image test
![000000016439_jpg rf 5799f1641ecbe657b77f74f6c11ab883](https://user-images.githubusercontent.com/49335804/128991564-1aeea6b1-5191-473f-93d2-58ed62208c38.jpg)    
![000000133645_jpg rf f349ed8b89e02746dfc2fc2f6a19d1ad](https://user-images.githubusercontent.com/49335804/128991667-230d46a2-a6fe-4122-8bcc-342dc72365c3.jpg)    
![000000214192_jpg rf 2a14b7534dfe02879327b5a89f618cb2](https://user-images.githubusercontent.com/49335804/128991699-1985ccee-da7f-4733-ac17-3ccb687c5479.jpg)    
![000000276055_jpg rf d9804930ad7faf9c36f32d8dc2e602a5](https://user-images.githubusercontent.com/49335804/128991745-9b0ac344-df5a-45a2-b829-6e29122c1f88.jpg)    
![000000329827_jpg rf a320319a40369375ac81ec62a8be5dc4](https://user-images.githubusercontent.com/49335804/128991773-b8ff72e0-7d1a-4853-9746-c59c57727311.jpg)    
![000000357978_jpg rf 91d4f5a74ed06116e2a0aea63d08da71](https://user-images.githubusercontent.com/49335804/128991810-d7d16089-cd63-469e-b3dd-ca46c6ab02fd.jpg)    
![bus](https://user-images.githubusercontent.com/49335804/128991840-adc63cf3-b101-4324-8ad0-7c80048541f6.jpg)    


# EnlightenGAN으로 조도개선 img 객체탐지 테스트
![dst3_screenshot_02 08 2021](https://user-images.githubusercontent.com/49335804/128991997-1a741eb8-d469-469c-87eb-3c93e9d1bb21.png)        
<img src="https://user-images.githubusercontent.com/49335804/128992069-61a13535-7f22-4bb3-8f66-887036a38487.jpg" width="50%" height="50%"/>      




# gray scale img 객체탐지 테스트
![KakaoTalk_20210811_144832280](https://user-images.githubusercontent.com/49335804/128992374-6723279f-36ae-4346-aafa-2fd236146423.jpg)    
![KakaoTalk_20210811_144832280_01](https://user-images.githubusercontent.com/49335804/128992435-8431eac9-0c92-459f-a65c-690708d0b834.jpg)    
![KakaoTalk_20210811_144832280_02](https://user-images.githubusercontent.com/49335804/128992476-99fe50ce-050e-4f3c-a6d6-2e023a7d8205.jpg)    
![KakaoTalk_20210811_144832280_03](https://user-images.githubusercontent.com/49335804/128992567-41a2b95f-3474-49e4-a706-a12e3109925d.jpg)    
![KakaoTalk_20210811_144832280_05](https://user-images.githubusercontent.com/49335804/128992633-6f736888-2fad-4ac6-b033-92c4b7bca384.jpg)    
![KakaoTalk_20210811_144832280_06](https://user-images.githubusercontent.com/49335804/128992719-dc37143d-6faa-4c24-9293-a14179d79970.jpg)    
![KakaoTalk_20210811_144832280_08](https://user-images.githubusercontent.com/49335804/128992760-4c53812e-efeb-46ca-a23d-4548b8adce7c.jpg)

  
  
  
## 8.18. test results  


# EnlightenGAN으로 조도개선 img 객체탐지 테스트
![dst3_screenshot_02 08 2021](https://user-images.githubusercontent.com/49335804/129852066-fada550f-ffc6-4d47-8a48-decf9a5ac821.png)
![dst5_screenshot_02 08 2021](https://user-images.githubusercontent.com/49335804/129852126-9b6736df-d4a2-4f82-9117-4b39967fb3d6.png)
![dst12_screenshot_11 08 2021](https://user-images.githubusercontent.com/49335804/129852175-906b3067-0fd9-49b4-99e2-331440ebdb89.png)
![KakaoTalk_20210720_213727400](https://user-images.githubusercontent.com/49335804/129852218-0c559b86-7c1e-45ad-aa27-157776c97cb0.jpg)
  
  
  
# gray scale img 객체탐지 테스트
![KakaoTalk_20210811_144832280](https://user-images.githubusercontent.com/49335804/129852313-22e5cce8-a16a-4527-b4eb-38656890e4ca.jpg)
![KakaoTalk_20210811_144832280_01](https://user-images.githubusercontent.com/49335804/129853010-30c0345d-bffd-4e53-b0bd-359e60a15e3c.jpg)
![KakaoTalk_20210811_144832280_02](https://user-images.githubusercontent.com/49335804/129853041-d6eba926-dadd-48a0-90ed-e09019d191a8.jpg)
![KakaoTalk_20210811_144832280_03](https://user-images.githubusercontent.com/49335804/129853071-5f4f3ac3-fb1e-4b73-a4de-5e1955a3d872.jpg)
![KakaoTalk_20210811_144832280_04](https://user-images.githubusercontent.com/49335804/129853097-907c2208-ea63-4ac6-952d-4389d6c0afad.jpg)
![KakaoTalk_20210811_144832280_05](https://user-images.githubusercontent.com/49335804/129853125-c8a2d0af-682a-4475-abc5-26f656ab83f8.jpg)
![KakaoTalk_20210811_144832280_06](https://user-images.githubusercontent.com/49335804/129853145-756a9666-d595-4597-a811-5f89dfc82531.jpg)
![KakaoTalk_20210811_144832280_07](https://user-images.githubusercontent.com/49335804/129853172-313d39bc-26ff-485b-91c0-0b9983d68e62.jpg)
![KakaoTalk_20210811_144832280_08](https://user-images.githubusercontent.com/49335804/129853203-bb4788fd-3e91-4441-95a7-1bac162fe4d5.jpg)

  