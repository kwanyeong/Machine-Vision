# 📸 Machine-Vision
---
### 프로젝트 주제_1
- 딥러닝 기반 약물 패키징 검사

---
### 프로젝트 내용
- GigE Vision Camera Interface를 이용한 AreaScan 영상 스트리밍
- Open eVision 툴을 사용한 Rule-based learning (Match / OCR / QR Code 인식)
- Deep Learning Studio 툴을 사용한 딥러닝 학습 및 적용모델 시연 (Locate (Bounding box))

---
### 활용 장비 및 재료
- Sentech 133 POE GigE Vision카메라
- C# Firmware 기반 WinForm S/W 개발환경
- 제조사 머신비전 툴(Open eVision / Deep Learning Studio)
- 검사용 장비 및 재료
  
![image](https://github.com/kwanyeong/Machine-Vision/assets/124857002/3d5503cf-3614-40bd-a543-d05c04dc1538)
![사진](https://github.com/kwanyeong/Machine-Vision/assets/124857002/1dd7d669-85c8-4468-8ca4-1628875a3944)


---
### 프로젝트 설명
- Open eVision 및 Deep Learning Studio 툴을 활용한 모델 학습
- C# WinForm 기반 카메라 영상 취득 및 스트리밍
- 학습모델을 적용한 객체인식 및 딥러닝 학습모델 적용

---
### 프로젝트 결과
- 학습결과 : 정확도 100%

![사진](https://github.com/kwanyeong/Machine-Vision/assets/124857002/ded7fcad-dd79-4275-a657-b438f5d0a62c)
![사진1](https://github.com/kwanyeong/Machine-Vision/assets/124857002/669405b1-464d-4b5e-9a8e-0a35fb60320c)





---
### 활용방안 및 기대효과
- Object Detection 패키징 검사시스템 확장


---
### 시연영상
- 프로젝트 구조 : QR코드 인식 -> 환자정보 파악 -> 환자정보 식별번호 ROI 영역 Match -> 처방전 복용약 패키징 검사 -> Object Detection - Locate 위치탐색 -> Detect 결과생성

![image](https://github.com/kwanyeong/Machine-Vision/assets/124857002/6d0f373a-cbe9-4460-bf97-982b136b92e8)
[![image](https://github.com/kwanyeong/Machine-Vision/assets/124857002/67af54d5-5943-4bb3-aed6-b9d1464323d4)](https://www.youtube.com/watch?v=bYPGRWwtdWc)

[시연영상](https://www.youtube.com/watch?v=bYPGRWwtdWc)

---
### 발표 PPT자료
[![image](https://github.com/kwanyeong/Machine-Vision/assets/124857002/f7b2b9a4-f938-486f-82ca-6ca065e4aabd)](https://github.com/kwanyeong/Machine-Vision/files/15148029/default.pptx)



[머신비전 프로젝트 PPT](https://github.com/kwanyeong/Machine-Vision/files/15148029/default.pptx)

---
### 프로젝트 주제_2
- Powder & Pad 이미지 데이터 Auto-Labeling Tool
  
<img width="1343" height="516" alt="image" src="https://github.com/user-attachments/assets/9ca13051-4348-45fe-b41b-ca34e4be68c7" />]
<img width="1044" height="397" alt="image" src="https://github.com/user-attachments/assets/25637a72-160c-403b-9c7d-1d8eb0e6a372" />]

---
### 프로젝트 내용
- 제조 데이터에 특화된 이미지 Pre-Processing 기반 Auto-labeling 알고리즘 개발
- Real-Time(실시간) 기반 Object Detection 및 Counting 


---
### 활용 장비 및 재료
- Stereo Microscope (실체형 현미경(모델명 - High Cloud 1080P Video Microscope Camera) / 화소수: 48MP, FPS : 60FPS, 배율: ~180X
- Python 기반 S/W 개발환경
- 검사용 장비 및 재료

<img width="1113" height="218" alt="image" src="https://github.com/user-attachments/assets/d15582e6-0b8e-4163-9931-b663a1c6b9f0" />

---
### 프로젝트 설명
- 상용화된 객체 이미지와 달리 제조데이터 특성상 Pre-Training 된 Model 이 없기에 손수 Labeling 하는데 어려움이 발생
- 일반객체에 특화된 Zero-Shot Detection 모델 (Dino 등)은 특수 이미지 객체탐지에 취약하기에 학습용 labeling 이미지 dataset을 구축하는데 상당한 시간과 비용이 소모됨
- 이러한 문제점을 인지하고 이미지 전처리 기법 등을 활용하여 이미지 라벨링 없이도 쉽게 객체탐지(Object Detection) 및 학습용 Labeling을 쉽게 할 수 있는 S/W 개발함
- 해당 S/W 로 구축한 이미지 Dataset으로 Object Detection 및 Counting 수행

<img width="1014" height="843" alt="2025-08-04 16_00_14 602" src="https://github.com/user-attachments/assets/7ac77a8c-adb1-44a6-91a3-54d253748d8a" />
<img width="1004" height="819" alt="6" src="https://github.com/user-attachments/assets/8b38cdb4-fe3a-48d4-bcee-39ee961bd72f" />
<img width="1011" height="806" alt="4" src="https://github.com/user-attachments/assets/ab04111d-08a4-46ee-9799-57614b5b0e7a" />
<img width="1027" height="835" alt="image" src="https://github.com/user-attachments/assets/2211d1d9-c967-44cd-a791-1b7c7c5a9826" />
<img width="1018" height="829" alt="image" src="https://github.com/user-attachments/assets/311aa966-8727-493d-822b-50125bb7f874" />



---
### 프로젝트 결과 (Auto-Labeling 도입 성과)
- 정확도: 정확도 99% 이상의 높은 Auto-Labeling 성능 구현
- 신속성: 획기적인 Labeling 시간 단축(90% 이상 감소)




---
### 활용방안 및 기대효과
- Normal/Abnormal 클래스 이미지 데이터 선별에 유용
- 별도의 AI모델 구축없이도 Object Detection / Counting


---
### 시연영상
- 프로젝트 구조 : Normal/Abnormal 클래스 이미지 데이터 선별 Auto-Labeling -> Object Detection - Locate 위치탐색 -> Detect 결과(Counting 정보) 생성

[<img width="1911" height="806" alt="4" src="https://github.com/user-attachments/assets/54aed7b0-7462-43c7-9789-925c7b99e78f" />](https://www.youtube.com/watch?v=bYPGRWwtdWc)

[시연영상](https://youtu.be/GUcdqP3DqsA)

---
### 발표 PPT자료
