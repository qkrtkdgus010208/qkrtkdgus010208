<div align="center">

<!-- Header Capsule Render -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&custom_color_list=0:0d1117,30:161b22,70:1f6feb,100:58a6ff&height=220&section=header&text=Sanghyun%20Park&fontSize=50&fontAlignY=38&desc=Firmware%20%26%20MCU%20%7C%20Robotics%20%26%20Automotive%20Control%20%7C%20Embedded%20Linux&descFontSize=19&descAlignY=62&fontColor=ffffff&descColor=e6edf3" width="100%" alt="Header Banner" />

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&multiline=true&width=860&height=80&lines=%ED%95%98%EB%93%9C%EC%9B%A8%EC%96%B4%EC%9D%98+%EC%A0%80%EC%88%98%EC%A4%80+%EC%A0%9C%EC%96%B4%28MCU%29%EB%B6%80%ED%84%B0+%EB%A6%AC%EB%88%85%EC%8A%A4+%EC%BB%A4%EB%84%90+%EB%93%9C%EB%9D%BC%EC%9D%B4%EB%B2%84%2C+%EC%98%A8%EB%94%94%EB%B0%94%EC%9D%B4%EC%8A%A4%28Edge+AI%29+%EB%B9%84%EC%A0%84+%ED%8C%8C%EC%9D%B4%ED%94%84%EB%9D%BC%EC%9D%B8%EA%B9%8C%EC%A7%80;End-to-End+%EC%8B%9C%EC%8A%A4%ED%85%9C%EC%9D%84+%EC%84%A4%EA%B3%84%ED%95%A9%EA%B3%A0+%EC%B5%9C%EC%A0%81%ED%99%94%ED%95%98%EB%8A%94+%EC%9E%84%EB%B2%A0%EB%94%94%EB%93%9C+%EC%8B%9C%EC%8A%A4%ED%85%9C+%EC%86%8C%ED%94%84%ED%8A%B8%EC%9B%A8%EC%96%B4+%EC%97%94%EC%A7%80%EB%8B%88%EC%96%B4%EC%9E%85%EB%8B%88%EB%8B%A4.)](https://git.io/typing-svg)

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/qkrtkdgus010208)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:psh01020808@gmail.com)
[![Tistory](https://img.shields.io/badge/Tistory-EA532C?style=flat-square&logo=tistory&logoColor=white)](https://psh010208.tistory.com/)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://youtube.com/channel/UC9Oso3IW6Ag73bZ2ThVU7Cw?si=d00qh5jbeVndpInT)

</div>

---

## 👨‍💻 About Me

> **MCU 베어메탈 레지스터 제어(ARM Cortex-M4/AVR)와 정밀 모터·센서 제어부터 리눅스 커널 디바이스 드라이버, 온디바이스(Edge AI) 시스템까지 하드웨어와 소프트웨어의 경계를 아우르는 펌웨어·임베디드 제어 엔지니어입니다.**

- 🐧 **Embedded Linux & Kernel Device Driver** : NVIDIA Jetson Orin Nano 리눅스 커널 5.15 캐릭터 디바이스 드라이버(`.ko`) 3종 설계, Top-Half ISR(`spin_lock_irqsave`) 기반 16-State 쿼드러처 엔코더 채터링 차단·언래치 알고리즘 및 `wait_queue` 블로킹 I/O(유휴 CPU 0%) 구현
- 🧠 **On-Device Edge AI & Hardware Interface** : Jetson Orin Nano ↔ STM32F411RE 양방향 UART 5-State 공정 제어 프로토콜 설계, Linux `v4l2-ctl` 카메라 레지스터(수동 노출·화이트밸런스) 하드웨어 고정 튜닝 및 `QThread` 비동기 파이프라인·핫플러그 세션 복구 구현
- ⚡ **ARM Cortex-M4 Bare-Metal & Automotive Control** : HAL 라이브러리 없이 CMSIS 레지스터 직접 제어(`RCC`, `SysTick`, `TIM`, `USART`, `NVIC`) 기반 차량 전장 펌웨어 설계, DC/서보 다채널 PWM(10kHz/50Hz) 기동 불감대(Dead-zone) 보정 및 역기전력 방지 데드타임(Dead-time) 이중 인터락 구현
- 🤖 **Autonomous Robotics & Sensor Scheduling** : ATmega128 3종 하드웨어 타이머(시스템 틱·16비트 Fast PWM·ToF 계측) 역할 분리 설계, 외부 에지 인터럽트(`INT4~6`) 하강 에지 동기화 기반 3채널 초음파 시분할 스케줄러 및 5-State 자율주행 FSM 구현
- 🧩 **Deterministic FSM & Zero-Allocation Architecture** : 인터페이스 기반 모듈형 상태 머신(FSM)과 런타임 동적 할당을 배제한 정적 메모리 풀링(Object Pool)·인터럽트 링버퍼(Ring Buffer) 설계를 통한 실시간 시스템 응답성 및 메모리 안정성 확보

---

## 🛠 Tech Stack

### 💻 Languages
![C](https://img.shields.io/badge/Embedded_C-A8B9CC?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Assembly](https://img.shields.io/badge/ARM_Assembly_(crt0.s)-4E5D6C?style=flat-square&logo=arm&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![Bash / Shell](https://img.shields.io/badge/Shell_Script-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

### ⚡ Microcontrollers, Firmware & Control
![ARM Cortex-M4](https://img.shields.io/badge/ARM_Cortex--M4_(STM32F411RE)-0091BD?style=flat-square&logo=arm&logoColor=white)
![CMSIS](https://img.shields.io/badge/CMSIS_Bare--Metal_(Non--HAL)-032347?style=flat-square&logo=stmicroelectronics&logoColor=white)
![AVR](https://img.shields.io/badge/AVR_ATmega128A-000000?style=flat-square&logo=microchip&logoColor=white)
![Actuator Control](https://img.shields.io/badge/Control-Multi--Channel_PWM_%7C_Dead--Zone_%26_Dead--Time_Interlock-2E7D32?style=flat-square)
![Peripherals](https://img.shields.io/badge/Peripherals-SysTick_%7C_NVIC_EXTI_%7C_Timer_%7C_ADC_%7C_DMA-FF6F00?style=flat-square)
![Protocols](https://img.shields.io/badge/Protocols-UART_%7C_I2C_%7C_SPI_%7C_1--Wire_%7C_TCP%2FIP-555555?style=flat-square)

### 🐧 Embedded Linux & Kernel
![NVIDIA Jetson](https://img.shields.io/badge/NVIDIA_Jetson_Orin_Nano-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Linux](https://img.shields.io/badge/Linux_Kernel_5.15-FCC624?style=flat-square&logo=linux&logoColor=black)
![CharDev](https://img.shields.io/badge/Character_Device_Driver_(.ko)-00599C?style=flat-square&logoColor=white)
![VFS](https://img.shields.io/badge/VFS_%7C_IOCTL_%7C_Wait_Queue-4E5D6C?style=flat-square&logoColor=white)
![V4L2](https://img.shields.io/badge/V4L2_Hardware_Camera_Tuning-FCC624?style=flat-square&logo=linux&logoColor=black)

### 🖥️ Frameworks, EDA & Build Systems
![GCC](https://img.shields.io/badge/GNU_Arm_Toolchain_%26_Linker_Script-A42E2B?style=flat-square&logo=gnu&logoColor=white)
![Makefile](https://img.shields.io/badge/Makefile_%26_CMake-000000?style=flat-square&logo=cmake&logoColor=white)
![KiCad](https://img.shields.io/badge/KiCad_10.0_(Schematic_%26_Pinmux)-314CB0?style=flat-square&logo=kicad&logoColor=white)
![Qt](https://img.shields.io/badge/Qt_C++_%26_PyQt5-41CD52?style=flat-square&logo=qt&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO26n_%26_OpenCV-00FFFF?style=flat-square&logo=opencv&logoColor=black)
![STM32CubeIDE](https://img.shields.io/badge/STM32CubeIDE_%26_Microchip_Studio-032347?style=flat-square&logo=stmicroelectronics&logoColor=white)
![Git](https://img.shields.io/badge/Git_%26_GitHub-F05032?style=flat-square&logo=git&logoColor=white)

---

## 🚀 Featured Projects

<div align="center">

| Project | Description & Key Tech | Key Contributions | Link |
| :--- | :--- | :--- | :---: |
| **Linux Device Driver**<br/><sub>Jetson 임베디드 리눅스 드라이버</sub> | **Jetson Orin Nano 커널 캐릭터 디바이스 드라이버 (3종 .ko)**<br/><br/>![Linux](https://img.shields.io/badge/Kernel_5.15-FCC624?style=flat-square&logo=linux&logoColor=black) ![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white)<br/>![CharDev](https://img.shields.io/badge/CharDev_%26_IOCTL-00599C?style=flat-square) ![ISR](https://img.shields.io/badge/Top--Half_ISR-4E5D6C?style=flat-square) | • EC11 엔코더(`ec11`), 모터(`l298n`), 8-Bar LED(`led_bar`) **커널 드라이버 3종 및 VFS/IOCTL 설계**<br/>• **16-State 쿼드러처(Quadrature) FSM 룩업 테이블** ISR 적용으로 하드웨어 필터 없이 채터링 차단<br/>• 디텐트 홈(11) 이탈 즉시 리셋하는 **언래치(Unlatch) 알고리즘**으로 역회전 전환 시 첫 스텝 지연 해결<br/>• `spin_lock_irqsave` 링버퍼 보호 및 `wait_queue_head_t` 블로킹 I/O로 **유휴 CPU 점유율 0% 달성** | [View Repo](https://github.com/qkrtkdgus010208/Linux_Device_Driver) |
| **AI Standard Process System**<br/><sub>Edge AI & STM32 공정 제어</sub> | **Jetson Orin Nano & STM32 연동 스마트 팩토리 공정 제어 시스템**<br/><br/>![NVIDIA Jetson](https://img.shields.io/badge/Jetson_Orin_Nano-76B900?style=flat-square&logo=nvidia&logoColor=white) ![STM32](https://img.shields.io/badge/STM32F411RE-032347?style=flat-square&logo=stmicroelectronics&logoColor=white)<br/>![V4L2](https://img.shields.io/badge/V4L2_Tuning-FCC624?style=flat-square&logo=linux&logoColor=black) ![PyQt5](https://img.shields.io/badge/PyQt5_QThread-41CD52?style=flat-square&logo=qt&logoColor=white) | • **Jetson ↔ STM32 현장 제어기 간 양방향 UART 프로토콜** 및 5-State 공정 제어 FSM 설계<br/>• Linux **`v4l2-ctl` 카메라 하드웨어 레지스터 고정**(수동 노출·화이트밸런스)으로 조명 노이즈 오검출 해결<br/>• 캡처·YOLO 추론·UART·TCP 소켓을 독립 `QThread` 워커로 분리해 **30FPS 무끊김 실시간 판정** 구현<br/>• 케이블 이탈 시 **핫플러그(Hot-plug) 장치 재연결 및 STM32 STEP LED(`1~9`) 상태 자동 복원** 구현 | [View Repo](https://github.com/qkrtkdgus010208/AI_Standard_Process_System) |
| **Qt ARM Vehicle Control**<br/><sub>Cortex-M4 차량 전장 제어 시스템</sub> | **Cortex-M4 CMSIS 베어메탈 전장 제어 및 Qt 모니터링 시스템**<br/><br/>![STM32](https://img.shields.io/badge/STM32F411RE-032347?style=flat-square&logo=stmicroelectronics&logoColor=white) ![CMSIS](https://img.shields.io/badge/CMSIS_Bare--Metal-0091BD?style=flat-square&logo=arm&logoColor=white)<br/>![PWM](https://img.shields.io/badge/TIM_PWM_%26_SysTick-FF6F00?style=flat-square) ![Qt](https://img.shields.io/badge/Qt_C++-41CD52?style=flat-square&logo=qt&logoColor=white) | • **HAL 없이 CMSIS 레지스터 제어**(`RCC` 96MHz PLL, `USART2->BRR`, `TIM3/5`) 구현<br/>• 구동 DC 모터(10kHz, **듀티비 50~100% 불감대 보정**) 및 조향 서보(50Hz) 정밀 제어<br/>• `TIM4` 주기 인터럽트와 1-Wire(DHT11) 충돌을 **코어 `SysTick` 1us 딜레이 분리**로 해결<br/>• 급변속(D↔R) 시 역기전력 방지 **펌웨어 브레이크 데드타임(Dead-time) 및 UI 이중 인터락** | [View Repo](https://github.com/qkrtkdgus010208/Qt_ARM-Vehicle_Control_System) |
| **AVR Auto Car**<br/><sub>ATmega128 자율주행 RC카</sub> | **ATmega128 베어메탈 레지스터 기반 3채널 초음파 자율주행 RC카**<br/><br/>![AVR](https://img.shields.io/badge/ATmega128A-000000?style=flat-square&logo=microchip&logoColor=white) ![C](https://img.shields.io/badge/Bare--Metal_C-A8B9CC?style=flat-square&logo=c&logoColor=white)<br/>![Sensors](https://img.shields.io/badge/EXTI_%26_Multi--Timer-FF6F00?style=flat-square) ![KiCad](https://img.shields.io/badge/KiCad_10.0-314CB0?style=flat-square&logo=kicad&logoColor=white) | • **3종 타이머 역할 분리**(Timer0 1ms 틱, Timer1 16비트 4us 분해능 PWM, Timer3 64us ToF)<br/>• `INT4~6` **하강 에지 완료 동기화 기반 3방향 초음파 시분할 순환 스케줄러**(간섭 완벽 제거)<br/>• 함수 포인터 테이블(`pfunc[]`) 기반 5-State 주행 FSM 및 막다른 골목 후진 탈출 알고리즘<br/>• 데이터시트 Alternate Function(`PE0/PE1` UART0) 핀 충돌 디버깅 및 8-Digit FND 시분할 구동 | [View Repo](https://github.com/qkrtkdgus010208/AVR-Auto_Car) |
| **Soul Requiem**<br/><sub>모듈형 FSM & 메모리 풀링 아키텍처</sub> | **인터페이스 기반 계층형 FSM 및 정적 메모리 풀링(Zero-Alloc) 설계**<br/><br/>![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white) ![Unity](https://img.shields.io/badge/Unity-FFFFFF?style=flat-square&logo=unity&logoColor=black)<br/>![FSM](https://img.shields.io/badge/State_Pattern_FSM-2E7D32?style=flat-square) ![Memory](https://img.shields.io/badge/Object_Pool-00599C?style=flat-square) | • 거대 분기문을 대체하는 **`IState` 인터페이스 기반 상태 머신(FSM)** 및 동적 가중치 제어 설계<br/>• `Stack<T>` 기반 **정적 메모리 풀링(Object Pool)** 구축으로 런타임 동적 할당/해제(GC 스파이크) 제거<br/>• 객체 대여/반납 생명주기(`OnRent`/`OnDie`) 엄격 관리 및 Sprite Atlas 패킹으로 **60FPS 실시간성 방어**<br/>• 정적 메모리 재사용과 상태 캡슐화 경험을 임베디드 펌웨어의 링버퍼·FSM 아키텍처 설계에 접목 | [View Repo](https://github.com/qkrtkdgus010208/Soul_Requiem_Portfolio) |

</div>

<br/>

<details open>
<summary><b>📂 Additional Microcontroller Projects (ARM Cortex-M4 & AVR)</b></summary>
<br/>

- **[ARM-Motor_Controller_System](https://github.com/qkrtkdgus010208/ARM-Motor_Controller_System)** : ARM Cortex-M4(STM32F411RE) CMSIS 베어메탈 기반 외부 인터럽트(`EXTI15_10`)·타이머(`TIM4/TIM5`)·UART 명령 파서 연동 DC 모터 정밀 가감속 FSM 제어 시스템
- **[AVR-Washing_Machine](https://github.com/qkrtkdgus010208/AVR-Washing_Matchine)** : ATmega128A 유한 상태 머신(FSM) 아키텍처 기반 세탁 공정(급수·세탁·헹굼·탈수) 타이머 PWM 모터 정·역회전 및 FND/LED 제어 시뮬레이터
- **[AVR-LCD_RTC_Calculator](https://github.com/qkrtkdgus010208/AVR-LCD_RTC_Calculator)** : ATmega128A **I2C(TWI) 프로토콜 기반 DS1307 RTC** 실시간 시계 제어, **인터럽트 기반 원형 큐(Ring Buffer, `queue.c`)** 및 4x4 매트릭스 키패드 스캐닝 연산기

</details>

---

## 📊 GitHub Stats & Activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=qkrtkdgus010208&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&icon_color=79c0ff" height="175" alt="qkrtkdgus010208's GitHub Stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=qkrtkdgus010208&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9" height="175" alt="Top Languages" />

</div>

---

## 📬 Contact & Channels

<div align="center">

<a href="mailto:psh01020808@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-psh01020808@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" />
</a>
<a href="https://github.com/qkrtkdgus010208">
  <img src="https://img.shields.io/badge/GitHub-qkrtkdgus010208-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</a>
<a href="https://psh010208.tistory.com/">
  <img src="https://img.shields.io/badge/Tistory-psh010208.tistory.com-EA532C?style=for-the-badge&logo=tistory&logoColor=white" alt="Tistory" />
</a>
<a href="https://youtube.com/channel/UC9Oso3IW6Ag73bZ2ThVU7Cw?si=d00qh5jbeVndpInT">
  <img src="https://img.shields.io/badge/YouTube-Channel-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube" />
</a>

<br/><br/>

<!-- Footer Capsule Render -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&custom_color_list=0:58a6ff,50:1f6feb,100:0d1117&height=100&section=footer" width="100%" alt="Footer Banner" />

</div>
