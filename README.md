<!--
  GitHub 포트폴리오 README 템플릿
  이름 / 링크 / 프로젝트 Repo 주소만 본인 기준으로 수정해서 사용하세요.
-->
<div align= "center">
    <img src="https://capsule-render.vercel.app/api?type=waving&color=0:ffffff,100:002afa&height=120&text=👋%20Hi,%20I'm%20Heo%20Jinkyeong&animation=&fontColor=ffffff&fontSize=70" />
    </div>
    

<div align="center">

#### Embedded · Robotics · Automotive Software Developer

센서 · 카메라 · 모터 · 디스플레이 · 네트워크를  
**“실제 하드웨어 동작 + 화면(UI)”** 로 연결하는 임베디드/로봇/차량 소프트웨어 개발자를 목표로 하고 있습니다.

---

[![GitHub](https://img.shields.io/badge/GitHub-Heo157-black?logo=github)](https://github.com/Heo157)
![C](https://img.shields.io/badge/Language-C-informational?logo=c)
![C++](https://img.shields.io/badge/Language-C%2B%2B-informational?logo=cplusplus)
![STM32](https://img.shields.io/badge/MCU-STM32-03234B?logo=stmicroelectronics)
![Arduino](https://img.shields.io/badge/MCU-Arduino-00878F?logo=arduino)
![Raspberry Pi](https://img.shields.io/badge/Board-Raspberry%20Pi-C51A4A?logo=raspberrypi)
![Linux](https://img.shields.io/badge/OS-Linux-333333?logo=linux)

</div>

---

## 🧑‍💻 About Me

- 전자공학 전공, **임베디드 소프트웨어 / 로봇 / 차량용 소프트웨어** 집중
- Arduino, STM32, Raspberry Pi, AGL(Automotive Grade Linux), Linux Device Driver, ROS 기반 프로젝트 경험
- **하드웨어(센서·모터·RFID 등) + 펌웨어 + 상위 제어(ROS/AGL/Flutter 등)** 구성을 하나의 시스템으로 설계하는 데 관심
- 팀 프로젝트에서 **펌웨어 개발 + 시스템 구조 설계 + Git 협업** 역할 수행

---

## 🏅 Highlights

- 🐶 **로봇 반려견 캡스톤 프로젝트 – 학교 캡스톤 디자인 우수상 수상**
- 🔐 STM32 + FreeRTOS 기반 **RFID·비밀번호 인증 스마트 사물함/도서관 시스템**
- 🚗 AGL(Automotive Grade Linux) + Flutter 기반 **인스트루먼트 클러스터(계기판)** 빌드 및 커스터마이징 시도
- 🧩 Raspberry Pi 커널 모듈로 **LED/KEY 디바이스 드라이버** 구현
- 🤖 Intel Edge AI SW 아카데미 – **ROS + 펌웨어 연동 로봇 프로젝트 팀장 경험**

---

## 🛠 Skills

### 🔧 Embedded & MCU

| 분야            | 상세 내용                                                                 |
|-----------------|--------------------------------------------------------------------------|
| MCU / 보드      | Arduino (Mega, Uno), STM32 (Nucleo/Discovery), ESP-01, Raspberry Pi 4/5  |
| RTOS            | FreeRTOS Task 설계, Task 간 통신/동기화 구조                             |
| 펌웨어          | HAL 기반 드라이버 제어, 인터럽트, 타이머, PWM, ADC, UART, SPI, I2C       |
| 주변장치        | RFID(MFRC522), 4x4 키패드, I2C LCD, 초음파 센서, 서보모터, DC모터 등     |

### 🐧 Linux & System

| 분야          | 상세 내용                                                                                 |
|---------------|------------------------------------------------------------------------------------------|
| Linux System  | Raspberry Pi 설정, systemd 서비스 등록, VNC, 네트워크 설정                               |
| Device Driver | GPIO 기반 LED/KEY char device, `ioctl`, `poll`, IRQ, 커널 타이머, Kconfig/Makefile 작성  |
| Yocto / AGL   | AGL 빌드(클러스터/IVI 데모), 레이어 설정, 빌드/의존성 에러 분석 및 트러블슈팅           |

### 🚘 Automotive / Robotics

| 분야         | 상세 내용                                                                 |
|--------------|---------------------------------------------------------------------------|
| AGL Cluster  | Flutter 클러스터 UI 분석, KUKSA-databroker/CAN 연동 구조 이해            |
| ROS & Robot  | ROS + 펌웨어 연동, 병원 내 자율주행 로봇(전동휠체어) 시나리오 설계 경험  |
| Sensors      | 카메라·초음파 기반 추종/거리 유지 로직, LiDAR·맵핑 개념 학습 및 실습     |

### 💻 Software & Tools

| 분야       | 상세 내용                                                                                   |
|------------|--------------------------------------------------------------------------------------------|
| 언어       | C, C++, Embedded C, Python(스크립트), Dart(Flutter 기초)                                   |
| IDE / 툴   | STM32CubeIDE, Keil, VS Code, Qt Creator, App Inventor                |
| 형상관리   | Git / GitHub, 브랜치 전략, 커밋·PR 중심 협업                                               |

---

## 📦 Projects

> 아래 각 프로젝트에 대해 실제 GitHub 리포지토리를 만들고,  
> `🔗 Repo:` 부분에 본인 Repo 주소를 채워 넣으면 됩니다.

---

### 1. 🐶 Robot Companion Dog – 사물을 따라가는 로봇 반려견

> **2024 학교 캡스톤 디자인 – 우수상 수상 프로젝트**

**기간**: 2024.03 ~ 2024.06  
**역할**: 아두이노 펌웨어 전체 구현, 센서·모터 제어, 앱 연동

**주요 기능**

- Pixy2 카메라로 특정 색/사물 인식
- 초음파 센서로 약 50cm 거리 유지하며 사물 추종
- L298N 모터 드라이버로 전·후·좌·우 및 제자리 회전 제어
- HC-06 Bluetooth 모듈 + App Inventor 앱으로 원격 조종 및 모드 변경(예: “따라와 모드”)
- 도트 매트릭스 LED로 눈·표정 출력, 서보 모터로 꼬리 흔들기
- DFPlayer Mini로 짖는 소리/효과음 재생
- 다수의 모듈로 인한 **전압 부족 문제를 데이터시트 분석 및 외부 전원 설계**로 해결

**Tech**

`Arduino Mega` · `Pixy2` · `Ultrasonic Sensor` · `L298N` · `HC-06` · `DFPlayer Mini` · `Dot Matrix LED` · `Servo` · `App Inventor`

**Links**

- 🔗 Repo: _(예시)_ `https://github.com/Heo157/robot-companion-dog`
- 📄 Docs: 회로도, 배선도, 시스템 구성도, 시연 영상 링크 등

---

### 2. 🔐 Smart Locker – RFID + 비밀번호 개인 사물함

**기간**: 2025.08 ~ (진행 중/완료 여부 기입)  
**역할**: STM32 펌웨어 설계, FreeRTOS Task 구조 및 인증 로직 구현

**목표**

- **개인 사물함용** 스마트 잠금장치
- RFID 카드 또는 비밀번호로 본인 확인 후 서보 모터로 문을 여닫는 구조

**주요 기능**

- MFRC522 RFID 리더기로 사용자 카드 인증
- 4x4 키패드 기반 비밀번호 입력 및 검증
- I2C LCD로 현재 상태(잠김/열림/오류) 및 안내 메시지 표시
- 서보 모터로 사물함 도어 개폐 제어
- FreeRTOS 기반 Task 분리
  - 모드 선택 Task (RFID / 비밀번호 / 관리자 모드 등)
  - RFID 인증 Task
  - 비밀번호 인증 Task
  - LCD 표시 & 서보 제어 Task

**Tech**

`STM32` · `FreeRTOS` · `MFRC522` · `Keypad 4x4` · `I2C LCD` · `Servo Motor` · `C (HAL)`

**Links**

- 🔗 Repo: _(예시)_ `https://github.com/Heo157/stm32-smart-locker`
- 📄 Docs: 상태 전이도, Task 다이어그램, 에러 핸들링 로직 등

---

### 3. 📚 Smart Library – RFID 기반 도서 대여/반납 시스템

**기간**: 2025.08 ~ (설계/진행 중)  
**역할**: 시스템 구조 설계, 임베디드 단 + 서버 연동 흐름 설계

**목표**

- 도서관 또는 소규모 책장 환경에서  
  **RFID 태그가 부착된 책을 RFID 리더기로 인식**하고
  - 대여 / 반납
  - 사용자별 대여 이력
  를 관리할 수 있는 시스템을 설계·구현하는 것

**예상/진행 구성**

- 책 또는 카드에 부착된 RFID 태그를 MFRC522로 인식
- LCD 또는 간단한 UI(라즈베리파이 / Web UI)로 도서/사용자 정보 표시
- 서버(MariaDB 등)와 연동해
  - 도서 정보(제목, 저자, 책 ID)
  - 사용자 정보(학번/ID)
  - 대여/반납 기록(시간, 상태) 저장
- 향후 바코드 스캐너 추가를 고려 (RFID + 바코드 혼합 구조)

**Tech**

`STM32 또는 Raspberry Pi` · `RFID(MFRC522)` · `I2C LCD` · `ESP-01/네트워크` · `MariaDB` · `Python/Flask 또는 C 소켓 서버 (계획/선택)`

**Links**

- 🔗 Repo: _(예시)_ `https://github.com/Heo157/smart-library`
- 📄 Docs: ERD/DB 설계, API 설계안, 시퀀스 다이어그램 등

---

### 4. 🚗 AGL Instrument Cluster – Automotive Grade Linux 계기판

**기간**: 2025.07 ~ 2025.10  
**역할**: AGL 빌드, Flutter 클러스터 UI 분석/커스터마이징, KUKSA/CAN 구조 분석

**주요 내용**

- Raspberry Pi 4/5 타깃 AGL 이미지 빌드
- `agl-instrument-cluster-container-demo`, `agl-ivi-demo-flutter` 등 컨테이너 기반 데모 분석
- Flutter 클러스터 UI에서 **하드코딩 값으로 계기판 게이지 애니메이션** 구현 시도
- KUKSA-databroker + CAN provider 구조 이해 및 적용 시도
- Yocto `bblayers.conf`, `local.conf` 조정, 빌드/의존성 에러 분석
- 최종적으로 완전한 통합까지는 도달하지 못했지만,  
  **AGL · Yocto · Flutter · 차량 데이터 플로우 전반을 실습하며 이해 범위 확장**

**Tech**

`AGL` · `Yocto/BitBake` · `Flutter` · `KUKSA-databroker` · `CAN` · `Docker/Container` · `Raspberry Pi 4/5`

---

### 5. 🔧 Linux Device Driver – Raspberry Pi LED/KEY 드라이버

**기간**: 2025.10 ~ 2025.11  
**역할**: 커널 모듈 구현, char device 인터페이스 설계

**주요 내용**

- Raspberry Pi GPIO에 연결된 LED/KEY용 char device 드라이버 작성
- `open`, `read`, `write`, `ioctl`, `poll` 구현
- 인터럽트 기반 키 입력 처리, 커널 타이머로 LED 패턴/점멸 구현
- Kconfig, Makefile 추가, 커널 빌드 및 모듈 로딩/언로딩 테스트
- 사용자 공간 테스트 프로그램으로 드라이버 기능 검증

**Tech**

`Linux Kernel` · `Device Driver` · `GPIO` · `char device` · `ioctl` · `poll` · `Timer` · `Kconfig` · `Makefile`

---

## 📚 Study & Activities

- 🎓 **학교 캡스톤 디자인**
  - 로봇 반려견 프로젝트 수행
  - 역할: 펌웨어 설계·구현, 하드웨어 제어, 앱 연동
  - **우수상 수상**
- 🤖 **Intel Edge AI SW 아카데미**
  - ROS + 펌웨어 기반 로봇/임베디드 프로젝트 팀장
  - 하드웨어 제어용 펌웨어와 ROS 노드 연동 구조 설계 및 구현
- 그 외
  - AGL, KUKSA, CAN, Flutter 클러스터, TouchGFX 등 자동차·로봇 HMI 관련 자율 학습

---

## 🧩 Work Style

- 문제 발생 시 **로그 / 데이터시트 / 공식 문서** 기반으로 원인 분석
- 빌드 로그, 에러, 해결 과정, 실패한 시도까지 GitHub에 문서화하여  
  **재사용 가능한 지식**으로 축적
- 하드웨어–펌웨어–상위 제어(ROS/AGL/앱)의 인터페이스를 먼저 정의한 뒤 구현 진행

---
## 🏅 Stats

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=Heo157&theme=dark&show_icons=true)

---
## 📫 Contact

- GitHub: [@Heo157](https://github.com/Heo157)
- Email: _heojk1120@gmail.com_

