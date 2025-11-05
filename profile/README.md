## 대공유도탄 모의시스템(SAM031)

<div align="center">
  <img src="https://github.com/user-attachments/assets/94739e80-2247-4d96-b981-db322e390e37" alt="SAM031 체계 사진" height="250" />
  
  <img src="https://github.com/user-attachments/assets/a12a7e6f-8ef6-4385-b236-af3c783fd53d" alt="SAM031 TCC 사진" height="250" />
</div>
<br><br>

### 📌 Overview
- 레이다로 공중위협을 탐지하고 유도탄 발사를 통해 실제와 유사한 교전 상황을 재현 및 검증하는 **통합 모의시스템**
- **운용통제기(TCC)**, **공중위협모의기(ATS)**, **발사대모의기(LCRS)**, **유도탄모의기(MSS)**, **레이다모의기(MFRS)** 로 구성

<br>

### ✨ Function
SAM031은 지대공 무기 체계의 <br>
- ✅ 실시간 다중 Air Threat 생성/추적 
- ✅ 무기/유도탄/레이더 모듈 간 동적 Linkage 
- ✅ 모의기 모듈 간 확장이 가능한 분산 구조
- ✅ 시나리오 기반 훈련/시험 지원

을 위해 개발된 종합 전술 시뮬레이션 플랫폼입니다.

<br>

<div align=center>

### 🛰️ Simulation Modules
| 모의기 이름 (Module)       | 설명 (Description)                                  | Repository                          |
| --- | --- | --- |
| 💻 **운용통제기**                | 전체 모의를 통제하고 교전을 전시하는 모의기           | [SAM031-TCC](https://github.com/2025-2SW-Team1/SAM031-TCC) |
| 💻 **공중위협모의기**            | 공중위협을 모의하는 모의기                            | [SAM031-ATS](https://github.com/2025-2SW-Team1/SAM031-ATS) |
| 💻 **유도탄모의기**              | 유도탄을 모의하는 모의기                              | [SAM031-MSS](https://github.com/2025-2SW-Team1/SAM031-MSS) |
| 💻 **발사대모의기**              | 유도탄을 발사하는 발사대를 모의하는 모의기            | [SAM031-LCRS](https://github.com/2025-2SW-Team1/SAM031-LCRS) |
| 💻 **레이다모의기**              | 공중위협을 탐지하고 정보를 송수신하는 모의기          | [SAM031-MFRS](https://github.com/2025-2SW-Team1/SAM031-MFRS) |
</div>

<br>

### 🏗️ Architecture
- **HLA/RTI** 통신 기반 Pub/Sub 아키텍처
- **nFramework** 기반 **Plug-in** 아키텍쳐
- **SOLID** 원칙 기반 객체 지향 설계 및 디자인 패턴

<br>

### 📆 Development plan
- 개발 기간: 25.10.20 - 25.11.07 (14일)
- 개발 인원: 6명

<br>
<div align=center>
  
### 🧑 Team member

| **Github profile**    | **Name** | **Role**        |  **Organization**   | 
|:-----------:|:---------------:|:---------------:|:---------------:|
| <a href="https://github.com/Fresh-hongsi"><img src="https://github.com/Fresh-hongsi.png" width="80" /></a>| 박시홍 | LCRS, MSS | 미사일시스템통제기술연구소.M&S개발단.4팀|
| <a href="https://github.com/Jmipar-k"><img src="https://github.com/Jmipar-k.png" width="80" /></a>| 박정민 | ATS | AI연구소.AI연구개발팀|
| <a href="https://github.com/Junbro0708"><img src="https://github.com/Junbro0708.png" width="80" /></a>| 박준형 | TCC Frontend | 무인통제연구소.4팀 |
| <a href="https://github.com/soseongha"><img src="https://github.com/soseongha.png" width="80" /></a>| 소성하 | TCC Backend | 미사일시스템통제기술연구소.M&S개발단.2팀|
| <a href="https://github.com/ojae13-beep"><img src="https://github.com/ojae13-beep.png" width="80" /></a>| 최원재 | MFRS | 레이다연구소.레이다수출개발단.1팀 |
| <a href="https://github.com/hanjjong"><img src="https://github.com/hanjjong.png" width="80" /></a>| 한종민 | MSS | 미사일시스템탐색기연구소.2팀 |

</div>
