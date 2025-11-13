<div align="center">

# **김준형 프로필**
임베디드 · 펌웨어 개발자를 목표로 꾸준히 성장하고 있습니다.

</div>

---

## **TECH STACK**

### **▸ Languages**
<p>
  <img src="https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white"/>
  <img src="https://img.shields.io/badge/C++-044F88?style=flat-square&logo=cplusplus&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=white"/>
</p>

### **▸ Embedded & Firmware**
<p>
  <img src="https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white"/>
  <img src="https://img.shields.io/badge/Arduino-00878F?style=flat-square&logo=arduino&logoColor=white"/>
  <img src="https://img.shields.io/badge/ATmega128-000080?style=flat-square&logo=atmel&logoColor=white"/>
</p>

<p>
  <img src="https://img.shields.io/badge/UART-333333?style=flat-square"/>
  <img src="https://img.shields.io/badge/SPI-333333?style=flat-square"/>
  <img src="https://img.shields.io/badge/I2C-333333?style=flat-square"/>
  <img src="https://img.shields.io/badge/PWM-333333?style=flat-square"/>
  <img src="https://img.shields.io/badge/GPIO-333333?style=flat-square"/>
</p>

### **▸ System & Network**
<p>
  <img src="https://img.shields.io/badge/Linux-F4A300?style=flat-square&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/TCP/IP-333333?style=flat-square"/>
  <img src="https://img.shields.io/badge/Socket_Programming-333333?style=flat-square"/>
  <img src="https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white"/>
</p>

### **▸ Vision / AI / SBC**
<p>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jetson_Nano-76B900?style=flat-square&logo=nvidia&logoColor=white"/>
  <img src="https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white"/>
</p>

<p>
  <img src="https://img.shields.io/badge/YOLO-333333?style=flat-square"/>
  <img src="https://img.shields.io/badge/EfficientNet-333333?style=flat-square"/>
</p>

---

# **PROJECTS**

## **1) 무인 출입 통제 시스템 (IoT DoorLock)**
**서버(DB)–STM32–Arduino–Raspberry Pi 전체 흐름을 직접 설계한 IoT 기반 출입 통제 시스템**  
- DB 기반 문 상태 동기화  
- STM32 비밀번호 인증 + 서보 제어  
- Arduino 관리자 강제 제어  
- Raspberry Pi Wi-Fi 통신 · DB 중계  

---

## **2) Edge AI 기반 스마트 안경 & 의류 이미지 분류 시스템**
🔗 [Repository 바로가기](https://github.com/jun-hyung815/4_Your_Eyez_Only)

Jetson Nano 기반 Edge AI 플랫폼 위에서  
**실시간 영상 분석 → 의류 상·하의 분류 → 음성 안내 출력**까지 수행하는  
착용형 스마트 디바이스 프로젝트입니다.

### 📌 주요 기능
- YOLOX-Tiny, EfficientNetV2 기반 **상의·하의 이미지 분류 모델 구현**
- Jetson Nano에서 **실시간 추론 및 경량화/최적화**
- Camera → Preprocess → Model Inference → Audio Output 흐름 전체 설계
- Jetson Nano 내부에서 모든 처리(추론/분석/출력)를 수행하는 **완전 Edge 구조**
- 안경형 디바이스 형태로 착용 가능하도록 설계

### 🔧 기술 요소
- **Computer Vision** : OpenCV, 이미지 전처리
- **AI Model** : YOLOX-Tiny, EfficientNetV2
- **Embedded AI(SBC)** : Jetson Nano
- **System Flow** : 카메라 입력 → 실시간 추론 → 분류 결과 TTS 안내

---

## **3) 눈동자 기반 UI 제어 시스템 (Eye-Tracking UI Control)**
🔗 [Repository 바로가기](https://github.com/jun-hyung815/eye-tracking-ui-control)

OpenCV 기반 시선 추적 기술로 **눈동자 움직임을 UI 입력 신호로 변환하는**  
비접촉식 인터페이스 프로토타입을 구현한 프로젝트입니다.

### 📌 주요 기능
- 실시간 웹캠 영상에서 **눈 영역 추출 및 전처리**
- 양쪽 눈의 **시선 방향(Left / Right / Center)** 분석 알고리즘 구현
- 시선 방향을 UI 명령(예: 선택, 이동, 클릭 등)으로 매핑
- 클릭 없이 사용하는 **Hands-free 인터페이스 프로토타입**
- 조명·머리 흔들림 상황에서도 안정되도록 ROI 기반 추적

### 🔧 기술 요소
- **Computer Vision** : OpenCV, 얼굴/눈 ROI 검출, 이진화 기반 pupil tracking
- **Tracking Algorithm** : Contour/threshold 기반 pupil center 추적
- **UI Control Logic** : 시선 방향 → 명령 매핑 구조 설계
- **실시간 처리** : Webcam frame 처리, 프레임 기반 딜레이 보정

---

## **4) 캐봇 (Carrier Robot)**
ROS + Jetson + Raspberry Pi + STM32 기반 **자율 이동 운반 로봇**  
카메라 기반 장애물 감지, ROS 메시지 제어, 서보 구동부 제어 전체 플로우 구현.

---

# **PROFILE**

- 서일고등학교 졸업  
- 호서대학교 정보통신공학과 졸업  
- 대한상공회의소 × Intel Edge AI SW 아카데미 7기 수료 *(900시간)*  

### **▸ Education Highlights**
- STM32 펌웨어 · MCU 프로그래밍  
- Raspberry Pi BSP & Device 제어  
- Linux 서버 & 소켓 통신  
- Vision/AI 모델 개발 및 Edge 포팅  
- IoT 아키텍처 설계  
- ROS 기반 로봇 시스템  

---

# **CONTACT**
📧 Email : **try9151@naver.com**  
📱 Phone : **010-8411-7429**  
