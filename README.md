# 🔓 DDoSAnom Project Overview
### 웹 서버 강인성 및 보안 테스트를 위한 시뮬레이션 툴

**DDoSAnom** is a high-performance DDoS simulation tool designed to assess the robustness and security of web servers.  
This program supports both **UDP Flood** and **TCP Flood** attack methods, enabling users to easily simulate a wide variety of real-world traffic load scenarios.

> **DDoSAnom**은 웹 서버의 내구성과 보안성을 평가할 수 있도록 설계된 고성능 DDoS 시뮬레이션 도구입니다.  
> 실제 네트워크 환경에서 자주 사용되는 **UDP Flood**와 **TCP Flood** 공격 방식을 모두 지원하여  
> 다양한 트래픽 부하 상황을 손쉽게 시뮬레이션할 수 있습니다.

---

## 🚀 How It Works  
### 사용 방법

After launching the program, users can enter:

- **Target server’s URL or IP address**  
  (테스트할 서버의 URL 또는 IP)
- **Port number**  
  (서버의 포트 번호)
- **Packet size**  
  (패킷 크기)

With these settings, **DDoSAnom** transmits a large volume of packets to the specified server using your chosen method (**UDP** or **TCP**),  
creating artificial network stress similar to a real DDoS attack.

- **UDP Flood** mode rapidly generates massive traffic to test bandwidth and processing power.  
  (UDP Flood는 빠르게 대량의 트래픽을 생성해 서버의 대역폭과 처리 능력을 집중적으로 테스트합니다.)
- **TCP Flood** mode establishes real connections to evaluate session and connection handling.  
  (TCP Flood는 실제 연결을 맺어 세션 관리 및 연결 처리 한계를 점검할 수 있습니다.)

---

## ✨ Key Features  
### 주요 기능

- **Real-time monitoring** of packets sent, total data volume, error counts, and more  
  (실시간 패킷 전송 현황, 누적 데이터, 에러 카운트 등 통계 제공)
- **Simple, intuitive UI** for effortless load testing  
  (누구나 쉽게 사용할 수 있는 직관적인 인터페이스)
- **Switch seamlessly** between UDP and TCP test modes  
  (UDP/TCP 방식을 자유롭게 전환 가능)

---

## 🛡️ Intended Use  
### 사용 대상 및 권장 용도

**DDoSAnom** is ideal for:

- Server administrators  
  (서버 관리자)
- Network engineers  
  (네트워크 엔지니어)
- Security researchers  
  (보안 연구원)
- Anyone needing to evaluate server stability and defenses  
  (서버의 안정성 및 방어체계를 점검하려는 모든 사용자)

---

> **⚠️ Please note:**  
> DDoSAnom is intended strictly for ethical and legal testing purposes—**use only on servers you own or have explicit permission to test**.  
> Unauthorized attacks or illegal use are strictly prohibited.
>
> **⚠️ 반드시 참고:**  
> DDoSAnom은 **합법적이고 윤리적인 테스트** 및 **자기 소유 서버의 보안 점검** 용도로만 사용해야 합니다.  
> 허가받지 않은 공격이나 불법적 목적의 사용은 엄격히 금지됩니다.

---
