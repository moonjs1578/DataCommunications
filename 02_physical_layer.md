# 📡 Data Communications  

## 02. Physical Layer (물리 계층)

---

### 🔹 Physical Layer
- 실제 **전송 매체(Transmission Media)** 와 직접 상호작용  
- 데이터를 **전자기 신호(Electromagnetic Signal)** 형태로 전송  

---

### 🔹 Data
- 전송되기 위해 **전자기 신호로 변환**되어야 함  

---

### 🔹 Analog vs Digital

#### 📍 Analog Data
- **연속적(Continuous)** 인 데이터  
- 주기적(Periodic) → 파형으로 표현 가능  

#### 📍 Digital Data
- **이산적(Discrete)** 인 데이터  
- 비주기적(Non-periodic)  

---

### 🔹 Periodic Analog Signals
- **단순 신호(Simple Signal)**  
  - 더 이상 분해할 수 없는 가장 기본 신호  
  - 예: 사인파(Sine Wave)
- **복합 신호(Composite Signal)**  
  - 여러 개의 단순 신호가 합쳐져서 만들어진 신호  

---

### 🔹 Sine Wave
- **3가지 파라미터로 표현**
  - **주기 (Period)** : 한 파형이 반복되는 시간  
  - **진폭 (Amplitude)** : 파형의 최대 높이  
  - **위상 (Phase)** : 파형이 시작되는 지점 (기준점)

- **주파수 (Frequency)**  
  - 1초 동안 발생하는 주기의 개수 (Hz)  
  - 주기 = `1 / 주파수`  

- **예시**  
  - 가정용 전력 → 최대 진폭(peak amplitude) 310V 사인파  
  - 실제 전력 전압은 220V (RMS 값)  
  - Peak 값 = RMS 값 × √2 ≈ 1.414 × RMS  

- **파장(Wavelength)**  
  - 한 주기 동안 신호가 이동한 거리  
  - `λ = 전파 속도 × 주기 = 전파 속도 / 주파수`

- **DC vs AC**
  - **DC (Direct Current)** : 0Hz (변화 없음)  
  - **AC (Alternating Current)** : 주기적 변화  

---

### 🔹 Composite Signals
- 사인파 하나만 보내면 동일한 파형 반복 → **정보 없음**
- 여러 개의 사인파를 합성 → **패턴**이 생기고 데이터 전송 가능  

---

### 🔹 Bandwidth (대역폭)
- 신호가 전송될 수 있는 **주파수의 범위**

---

### 🔹 Digital Signals
- 정보는 디지털 신호로도 표현 가능  
- 1 → 양전압(Positive Voltage), 0 → 0V(또는 음전압)  
- **다중 레벨 신호(Multi-level Signal)**  
  - 전압 레벨을 여러 단계로 설정 가능  
  - 예: 4레벨 → 한 심볼(symbol)에서 2비트 전송 가능 (00, 01, 10, 11)

---

### 🔹 Bit Rate (비트율)
- 1초 동안 전송되는 비트 수  
- 단위: **bps (bits per second)**  

---

### 🔹 Transmission of Digital Signals
- 디지털 신호 = 무한대 대역폭을 가지는 여러 아날로그 신호의 합성
- **전송 방식**
  1. **기본대역 전송 (Baseband Transmission)**  
     - 디지털 신호를 변조하지 않고 그대로 전송  
  2. **대역 통과 전송 (Broadband / Passband Transmission)**  
     - 디지털 신호를 아날로그 신호로 변환 후 전송 (변조 Modulation)

---

### 🔹 Transmission Impairments (전송 손상)
- 전송 매체는 완벽하지 않음 → 전송 중 신호 손상 발생  
- **전송 시작 신호 ≠ 수신 신호**

#### 📍 3가지 주요 원인
1. **Attenuation (감쇠)**  
   - 전송 중 **에너지 손실**  
   - 신호 세기가 점점 약해짐  

2. **Distortion (왜곡)**  
   - 신호의 **형태/모양이 변형**  
   - 복합 신호에서 각 주파수 성분마다 전파 속도가 달라 → 도착 시점이 다르게 되어 원래 모양이 깨짐  

3. **Noise (잡음)**  
   - **Thermal Noise (열 잡음)** : 전자의 무작위 운동  
   - **Induced Noise (유도 잡음)** : 모터, 가전제품에 의한 간섭  
   - **Crosstalk (혼선)** : 인접 전선이 서로 간섭  
   - **Impulse Noise (임펄스 잡음)** : 순간적인 스파이크(번개, 전원 장애 등)

---
