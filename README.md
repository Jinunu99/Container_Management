# 선박 컨테이너 자동 온습도 관리 시스템

## 기술 스택
<img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=C&logoColor=white"> <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white"> <img src="https://img.shields.io/badge/PyQt5-41CD52?style=for-the-badge&logo=Qt&logoColor=white"> <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white">  
<img src="https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white"> <img src="https://img.shields.io/badge/raspberrypi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white">

## 개요
선박 운송 과정에서 컨테이너 내부의 온습도를 일정하게 유지하기 위해 FAN과 히터를 통해 관리할 수 있는 시스템 개발,  
관리자가 내부 상황을 모니터링 할 수 있도록 GUI 개발  
  
* 개발 기간 : 2025.04.08 ~ 05.07
* 프로젝트 인원 : 3명

## 프로젝트 핵심기능
`Container_STM`  
* 운송과정에서 기후 변화로 인해 실시간으로 컨테이너 내부의 온습도를 측정하여 온습도를 일정하게 유지하기 위해 센서를 제어함
* 센서 정보를 Bluetooth 모듈을 통해 실시간으로 정보를 송신함

`Container_GUI`  
* 수신된 온습도 정보를 DB에 저장 및 csv 파일로 저장
* 수신된 센서 정보를 GUI에 시각화
* 관리자가 상황에 따라 컨테이너의 내부 온습도를 조절할 수 있도록 온습도 경계값 송신함 

## STM FlowChart
<img width="662" height="471" alt="Image" src="https://github.com/user-attachments/assets/f84adbc4-ba2a-49e4-85c4-32fba5383f28" />

## GUI
<img width="683" height="364" alt="Image" src="https://github.com/user-attachments/assets/02b960d4-87c7-462b-8a81-3b92da240a8a" />
