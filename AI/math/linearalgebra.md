ai와 선형대수학의 연관관계와 ai가 무엇인지에 대해서 알아보자

## 인공지능이란 : 인간과 닮은 지능을 가진 기계나 시스템 , 목적을 달성하기 위해 만든 인간 지능과 닮은 기술 

Turing Test
인간과 기계가 대화가 가능하다면 , 로봇은 지능이 있다라고 판단. 
3명 최소 1명이 기계를 인간으로 지명하면 , turing test xhdrhk 

2014년 turing test 최초 통과. 

2018 google duplex demo (google I/O) 급속한 발전으로 확실한 turing test 통과 

인공지능은 왜 이제서야 나타났나? 
빅데이터 , 하드웨어의 발달 > 인공지능에게 학습하기에 용의 
인공지능에게 학습시키는건 (딥러닝) 간단한 사칙연산이기 때문에, cpu보다는 gpu의 역할이 중요하다. 

2020: 40900 Exabytes > 1exabyte = 1000000 terabytes 
데이터는 시대가 갈수록 급진적으로 늘어나고있음. 

gpu는 복잡한 계산은 못하지만, 간단한 계산은 병렬로 처리가 가능하다.

이러한 하드웨어 , 빅데이터의 발전으로 인공지능을 학습시킬수있는 기반이 마련되었다. 데이터 , 컴퓨팅 , 알고리즘을 제공하는 클라우드 컴퓨팅 서비스가 마련되었고, 여러 인력들이 ai 를 
개발할수있는 환경이 구축되었다. 

## 4차 산업혁명과 인공지능 

기계화 생산 > 대량 생산 > 부분 자동화 > 자동 생산(4차) 

4차 산업혁명 != 인공지능 
4차 산업혁명은 Cyber x Physical 
IoT , BigData , 3D printing , robots and drone , uav

## 인공지능과 수학의 관계 

인공지능 > 머신러닝 > 딥러닝 
딥러닝은 머신러닝 알고리즘중의 하나임 
이 알고리즘을 이해하기 위해서는 선형대수학이 필요함 

컴퓨터 프로그램과 머신러닝의 차이점 

기존의 컴퓨터 프로그램 : data + program  > computer > output 

머신러닝 : data + output > computer > program 

## 머신러닝이 잘 푸는 문제 

# 지도학습 : 정답이 존재함. 정답을 알려주고, 트레이닝을 시킴 데이터가공 힘듬 

- 분류 
동물 사진 분류 , 숫자 이미지 분류

- 회귀
설탕 섭취량에 따른 혈당 수치 
평균 연령에 따른 연간 독서량

- 예측
내년 아버지의 혈당 수치
내년 40대의 연간 독서량

# 비지도학습 : 정답이 없음 데이터의 특징이 중요함 이러한 특성때문에, 시간이 꽤 오래걸림 데이터 가공 쉬움 

- 그룹화
인기 상품 추천
sns 친구 추천

- 이상값 감지
주식 거래 감지
암세포 탐지

# 강화학습 : 사람이 배울때와 비슷함 agent 가 있고 , enviroment 가 있음. agent가 action을 하면 , envirment가 state를 주고 , state가 좋으면, reward를 지급함.

- 강화학습
로봇 , 게임 , 바둑 등 

## 인공신경망 

dendrite > soma > axon 

# denfrite in ai

벡터의 형태로 입력된 데이터를 입력받음 

# soma in ai 

전달받은 입력을 합산하는 기능을 수행함 . dendrite의 입력에 weight이라고 하는 w를 곱하여 합산함

# axon in ai

soma에서 받은 값을 function에 넣어서 output y를 전달함 

## 선형대수학이 왜 필요할까? 

x1,x2,x3 라는 input과 y1 , y2 라는 ouput이 있다. 
머신러닝은 이 인풋, 아웃풋을 가지고 , 프로그램을 만드는 역할인데, 기계에 넣는 데이터는 모두 벡터형테로 주어지니, 행렬곱이라고 생각해도된다. 
무엇을 곱하면 y1,y2가 나올것인가에서 그 무엇이 프로그램인것이다. 

## SVM support vector machine 

고차원의 데이터에 대해서 분류를 해준다. 
머신러닝 분류문제에 많이 쓰임 

which line will classify the unseen data well? > support vector machine 
hyperpalne 의 일반식은 w^tX + b = 0

두 class를 나누는 hyperplane은 무한히 많음 
어떤것이 가장 좋은 hyperplane인가? > margin을 극대화 함. 


