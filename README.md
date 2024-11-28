# Solar-See_2024

## Overview
### 1) 비계량 태양광 패널 지도
### 2) 태양광 패널 찾기 게임 ( 유저의 게임 데이터 축적 -> AI가 놓친 비계량 태양광 위치 발견 )

Solar See는 모바일을 기준으로 제작되었습니다.<br>
아래 QR 코드를 스캔하면 모바일 기기로 쉽게 접속이 가능합니다.<br>
https://solar-see.site 

<img src="https://github.com/user-attachments/assets/4767162c-65f0-4b90-8ed9-e75b9d93d987" style="width:25%"/>

## 솔루션 한줄 요약

비계량 태양광 패널을 찾아 전력 수요 예측의 정확도를 높이기 위한 AI 기반 태양광패널 찾기 게임

## 풀고자 하는 사회 문제 정의

### 1. 신재생에너지는 지속가능한 지구를 위한 필수불가결한 존재예요

신재생에너지는 깨끗한 에너지로, 지구의 환경오염을 줄이고 반영구적인 발전이 가능한 에너지원이에요

### 2. 신재생에너지를 이용한 발전소는 끄기 쉽다는 이유로 전력 수요 예측에 실패 시 계속 꺼지고 있어요

화력 발전소와 원자력 발전소는 끄기 어렵기 때문에 만만한 신재생에너지가 피해를 보고 있어요

### 3. 전력 수요 예측을 어렵게 만드는 원인 중 하나가 바로 비계량 태양광 패널이에요

비계량 태양광 패널은 발전량이 계측되지 않는 태양광 패널로, 전력 피크 시간대의 11%나 차지해요

이러한 패널 때문에 전력 수요를 정확히 예측하는데 어려움을 겪고 있어요

### 4. 저희 Team 220V는 SolarSee 프로젝트를 통해 전국에 숨어있는 태양광 패널을 찾아 전력 수요 예측에 도움을 줄 거예요

전국의 모든 비계량 태양광 패널을 찾을 수 있다면 전력 수요 예측 가능성을 높이고, 결과적으로 신재생 에너지의 확산에 도움을 줄 수 있을 거예요

## 솔루션 개요

### 1. 항공사진과 AI를 활용한 태양광 패널 탐색

기존 태양광 패널 탐색 방식은 위성사진과 AI를 활용했어요. 펠로우님과 저희는 위성사진에 비해 화질이 더 좋은 항공사진을 활용하고, AI를 직접 학습시켜 태양광 패널 탐색을 진행했어요

### 2. 비계량 태양광 패널을 확인할 수 있는 지도 서비스

저희가 AI를 기반으로 찾은 태양광 패널을 지도 서비스를 통해 직접 확인하실 수 있어요

### 3. AI의 정확도를 올리기 위해 게임을 도입

패널 찾기 게임을 만들어 크라우드소싱을 하고자 하였어요. 유저들이 플레이 하면서 쌓인 데이터는 AI의 정확도를 올리는데 사용될 거예요

### 4. 비계량 태양광 패널의 문제점에 대한 관심도 증가

기존 일회성 정부 프로젝트였던 펠로우님의 솔루션과 달리 유저들의 참여를 집중시키고, 사람들의 관심을 끌어 사회적으로 문제가 논의되도록 할 것으로 기대돼요

## 설치 및 실행방법

### 실행 방법

아래 QR 코드 접속 or [solar-see.site](http://solar-see.site) 접속

<img src="https://github.com/user-attachments/assets/4767162c-65f0-4b90-8ed9-e75b9d93d987" style="width:25%"/>

### Clone Repositories

~~~
git clone --recurse-submodules https://github.com/tech-for-impact/Solar-See_2024.git
~~~

### 설치 방법

각 레포지토리 설치 방법 참조

## 데모영상

영상 참고

## 레퍼런스

AI 개발 시 참고 레포

[YOLO11 🚀 신규](https://docs.ultralytics.com/ko/models/yolo11/)

https://github.com/z-mahmud22/Mask-RCNN_TF2.14.0

항공사진 출처: 국토지리정보원

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/cb0cb96e-83d1-484f-ac29-0d255e9c37eb/5384761d-f7fb-4612-9eab-08368c2a4af7/image.png)

태양광 패널 trainset 출처: https://www.aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&aihubDataSe=data&dataSetSn=71348
