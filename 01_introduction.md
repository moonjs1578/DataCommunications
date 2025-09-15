# 📡 Data Communications 

---

## 1.1 Data Communications (데이터 통신)

### 🔹 Definitions (정의)
- **Data Communications (데이터 통신)**  
  → 두 장치 간에 **Transmission Medium (전송 매체, 예: 전선 케이블)**를 통해 데이터를 교환하는 것

---

### 🔹 Four Characteristics (데이터 통신의 4가지 특성)
1. **Delivery (전달성)** : 데이터가 정확한 목적지에 도달해야 함  
2. **Accuracy (정확성)** : 데이터가 손상되지 않고 원래 형태로 도착해야 함  
3. **Timeliness (적시성)** : 정해진 시간 안에 도착해야 함  
4. **Jitter (지터)** : 도착 시간이 일정해야 함  

---

### 🔹 Five Components (데이터 통신의 5가지 구성 요소)
1. **Message (메시지)**  
2. **Sender (송신자)**  
3. **Receiver (수신자)**  
4. **Transmission Medium (전송 매체)**  
5. **Protocol (프로토콜)** : 데이터 통신을 지배하는 **규칙**

---

### 🔹 Data Representation (데이터 표현)
- **Text (문자 데이터)**  
  - ASCII : 128개 문자 (영문, 숫자, 특수기호, 제어문자)  
  - Extended ASCII : 256개 문자 가능 (8비트)  
  - Unicode : 다국어 지원, 최대 32비트  

- **Numbers (숫자 데이터)**  

- **Images (이미지 데이터)** : 픽셀(Pixel) 단위로 표현  

- **Audio (음성 데이터)**  

- **Video (영상 데이터)**  

---

### 🔹 Data Flow (데이터 흐름)
- **Simplex (단방향)** : 한쪽 → 다른 쪽만 통신 (예: TV, 라디오)  
- **Half Duplex (반이중)** : 양쪽 송수신 가능하지만 동시 불가, 번갈아 통신 (예: 무전기)  
- **Full Duplex (전이중)** : 양쪽 동시에 송수신 가능 (예: 전화)  

---

## 1.2 Networks (네트워크)

### 🔹 Definition (정의)
- **Network (네트워크)** : 장치(devices) 간의 상호 연결  
- **Devices (장치)**  
  - **Host (호스트)** : 대형 컴퓨터, 데스크톱, 노트북, 워크스테이션, 휴대폰, 보안 시스템 등  
  - **Connecting Device (연결 장치)** : 라우터(Router), 스위치(Switch), 모뎀(Modem) 등  

---

### 🔹 Topics (주제)
- **Network Criteria (네트워크 기준)** : 성능(Performance), 신뢰성(Reliability), 보안(Security)  
- **Physical Structures (물리적 구조)** : 연결 유형(Type of Connection), 물리적 토폴로지(Physical Topology)  

---

### 🔹 Type of Connections (연결 유형)
- **Point-to-Point** : 1대1 연결  
- **Multipoint** : 1대 다수 연결  

---

### 🔹 Topology (토폴로지)
- **Topology** : 네트워크에서 장치들이 연결된 구조  

1. **Mesh Topology (메시)**  
   - 모든 노드가 다른 모든 노드와 직접 연결  
   - 노드 수 증가 시 관리 어려움  

2. **Star Topology (스타)**  
   - 관리/확장 용이  
   - 성능 우수  
   - 현대 네트워크에서 가장 많이 사용  

3. **Bus Topology (버스)**  
   - 하나의 중앙 케이블(버스)에 여러 장치 연결  
   - 모든 노드가 공용 전송 매체(코액셜 케이블) 공유  
   - Drop line에서 정보 송수신  

4. **Ring Topology (링)**  
   - 원형 구조  
   - Repeater로 신호 증폭  

---

## 1.3 Network Types (네트워크 유형)

### 🔹 Local Area Network (LAN, 근거리 통신망)
- 사무실, 건물, 캠퍼스 내 여러 호스트 연결  
- 각 호스트는 **고유 IP 주소** 보유  
- 패킷 전송 시 **송신 호스트와 수신 호스트 주소 포함**  
- 과거 구조: Bus Topology / 현재 구조: Star Topology  

---

### 🔹 Wide Area Network (WAN, 광역 통신망)
- **LAN vs WAN 차이**  
  1. LAN은 규모 제한  
  2. LAN은 호스트와 직접 상호작용  
  3. LAN은 주로 사적 운영 (Private)  
  4. WAN은 넓은 범위 사용  
  5. WAN은 통신사가 구축·운영, 조직이 임대  

- **Point-to-Point WAN** : 단순 연결  
- **Switched WAN** : 회선 공유, 필요 시 연결, 효율적  
- **Internetwork (2 LAN + 1 WAN)** : LAN 내 고속 통신, LAN 간 WAN 통해 통신  
- **Heterogeneous Network (WAN + LAN)** : 다양한 기술과 프로토콜 혼합, 유연성 높음  

---

## 🔹 The Internet (인터넷)

### Definitions (정의)
- Internet : **두 개 이상 네트워크가 서로 통신할 수 있는 구조**  
- 대표적인 Internet : **수백만 개 상호 연결 네트워크 집합**  
- **internet vs Internet** : 개념 차이 있음  

### The Internet Today
- 인터넷 = **백본 통신망 중심으로 제공자/고객 네트워크 연결**  
- **Peering Point** : 여러 네트워크가 트래픽 교환 위해 연결되는 지점  

---

## 🔹 Accessing the Internet (인터넷 접속)
- 사용자는 **ISP(Internet Serivice Provide)와 물리적 연결** 필요  
- 연결 유형: 일반적으로 **Point-to-Point WAN**  

### 접속 방법
1. **Telephone Networks (전화망)**  
   - **Dial-up** : 느림, 모뎀→음성 신호, 연결 중 전화 불가  
   - **DSL** : 빠름, 음성+데이터 동시에 사용 가능  

2. **Cable Networks (케이블망)**  
   - 케이블 TV 기반, 가정/소규모 사업체 인터넷 가능  

3. **Wireless Networks (무선망)**  
   - 무선 연결(Wi-Fi, Wireless WAN)로 가정/사업체 인터넷 접속 가능  

4. **Direct Connection (직접 연결)**  
   - 대규모 조직/기업 : 자체 지역 ISP, WAN 임대 후 인터넷 연결  
   - 대규모 대학 : 자체 인터네트워크 구성 후 인터넷 연결 가능  

## 1.5 TCP/IP Protocol Suite
- TCP/IP(Transmission Control Protocol/Internent Protocol)
### 🔹 Hierarchical Protocol (계층형 프로토콜)
- **정의** : 계층형 프로토콜은 **상호작용하는 모듈들(interactive modules)**로 구성되어 있으며, 각 모듈은 **특정 기능(specific functionality)**을 제공합니다.  
- **특징** :  
  - 상위 계층 프로토콜(upper-level protocol)은 **하위 계층 프로토콜(lower-level protocol)**이 제공하는 서비스에 의해 지원됩니다.  
  - 즉, 각 계층은 자신이 맡은 기능을 수행하고, 상위 계층은 하위 계층 기능을 활용해 통신을 수행합니다.  

### Layers in the TCP/IP Protocol Suite
- Layer 5 : **Application**
   - 응용 계층(Application Layer)에서의 통신은 두 프로세스(Process) 간에 이루어지며, 여기서 프로세스란 이 계층에서 실행 중인 두 개의 프로그램을 의미한다.
   - 통신을 위해, 한 프로세스(Process)는 다른 프로세스에 요청(Request)을 보낸다. 응답(Response)을 받는다.
   - 프로세스 간(Process-to-Process) 통신은 응용 계층(Application Layer)의 책임이다.
- Layer 4 : **Transport**
   - 응용 계층(Application Layer)에 서비스를 제공하는 역할을 담당한다.
   - 송신 호스트(Source Host)에서 실행 중인 응용 프로그램(Application Program)으로부터 메시지를 받아, 수신 호스트(Destination Host)에서 실행 중인 해당 응용 프로그램으로 전달하는 것
- Layer 3 : **Network**
   - 패킷(Packet)을 송신 호스트(Source Host)에서 수신 호스트(Destination Host)까지 전달하는 역할을 담당한다.
   - 송신지(Source)와 목적지(Destination) 사이에 (논리적) 연결(Logical Connection)을 생성함으로써
- Layer 2 : **Data link**
   - 프레임(Frame)을 한 노드(Node)에서 다음 노드로 전달하는 역할을 담당한다.
- Layer 1 : **Physical**
   - 프레임(Frame) 내 개별 비트(Bit)를 링크(Link)를 통해 전달하는 역할을 담당한다.

- 계층을 통과할 때마다 더 큰 봉투에 담아서 줌

## 2️⃣ The OSI Model

### OSI vs TCP/IP
- **OSI**는 7계층으로 구성: Application, Presentation, Session, Transport, Network, Data Link, Physical  

- **OSI (Open Systems Interconnection)** : 통신 시스템 간 상호연결을 위한 모델  
- **ISO** : OSI 모델을 정의한 국제 표준화 기구
