
# PLC · SCADA 및 임베디드 제어 프로젝트 포트폴리오

산업용 PLC/SCADA 제어 로직과 MCU 펌웨어, IoT 데이터 연동 프로젝트를 정리한 저장소입니다.

## 기술 스택
- **PLC / HMI / SCADA**: LS ELECTRIC XG5000, MITSUBISHI GX Works2, CIMON SCADA, XP-Builder
- **Database / IoT**: MySQL, MongoDB, Node-RED, MQTT
- **Embedded / Firmware**:  ESP32, FA-duino(Comfile), HMI(Comfile), C/C++
- **Hardware % CAD**: 시퀀스 회로 설계, 전장 배선, Fusion 360, Sketch up, Blender

## 프로젝트 목록

### 1. EV 배터리 케이싱 사출성형 공정 PLC/SCADA 자동화
- **환경**: LS XG5000, CIMON SCADA
- **구현 내용**: 공정(형폐-고정-계량&가열-사출&보압-냉각-형개-추출) 및 구동부 모듈화 래더 로직 작성, HMI 모니터링 및 알람·트렌드 화면 작화

### 2. IoT 기반 에너지 하베스트 및 원격 모니터링 시스템 (한이음 ICT 멘토링 입선)
- **환경**: MCU 개발보드(ESP32-CAM), MQTT, Node-RED, MongoDB
- **구현 내용**: 센서 및 공공 데이터 수집 및 동작 펌웨어 구현, MQTT 통신 연동, Node-RED 대시보드 구성 및 MongoDB 데이터 적재

### 3. 버섯 배지 수직 침봉기(V1·V2) 및 식물재배기 제어 시스템 (캡스톤 디자인 우수상)
- **환경**: C/C++, MCU 개발보드, FA-duino(Comfile), HMI(Comfile)
- **구현 내용**: 제어 로직 및 UI 구현, 배선, 릴레이 작동 시 발생하는 역기전력(서지) 차단을 위한 보호 다이오드 회로 추가 설계
