# Remotix 프로젝트

> **한 줄 소개:** React로 구현한 Operator’s Browser 형태의 원격 제어 UI SPA입니다.

---

## 📖 프로젝트 소개

Remotix UI Design 프로젝트는 원격 제어 로봇 시스템을 위한 직관적이고 확장 가능한 사용자 인터페이스를 목표로 합니다. 주요 특징은 다음과 같습니다:

* **실시간 원격 조작:** 화살표 버튼(ArrowControls)을 통해 TurtleBot3와 같은 로봇을 실시간으로 제어할 수 있습니다.
* **다채널 정보 표시:** ReportCard, NotificationCard 컴포넌트로 로봇의 상태, 알림, 리포트를 한눈에 확인할 수 있습니다.
* **반응형 SPA 아키텍처:** React 기반 단일 페이지 애플리케이션으로 빠른 렌더링과 모듈화된 컴포넌트를 제공합니다.
* **확장성:** WebSocket 및 REST API 연동이 가능한 구조로, 백엔드 서비스와 유연하게 통신할 수 있습니다.

---

## 🎬 Demo
* //video경로로

---

## 🛠️ 기술 스택

본 프로젝트에서 실제 사용된 기술 스택은 다음과 같습니다:

* **언어 & 런타임**

  * JavaScript (ES6+)
  * Node.js 16.x
* **프레임워크 & 라이브러리**

  * React 18.x (SPA)
  * ROSLIB.js (ROS 통신)
  * WebSocket (실시간 데이터 송수신)
* **스타일링**

  * CSS Modules
  * 일반 CSS
* **빌드 & 번들링**

  * npm / Yarn
  * Webpack

<p align="center">
  <img alt="React" src="https://img.shields.io/badge/React-18.x-61DAFB?logo=react&logoColor=white" />
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-16.x-339933?logo=node.js&logoColor=white" />
  <img alt="ROS" src="https://img.shields.io/badge/ROSLIB.js-OK-339933" />
  <img alt="WebSocket" src="https://img.shields.io/badge/WebSocket-OK-informational" />
  <img alt="CSS Modules" src="https://img.shields.io/badge/CSS%20Modules-OK-lightgrey" />
</p>

---

## 📁 프로젝트 구조

조직(Organization) 단위로 다음과 같은 레포지토리들이 존재합니다:

```plaintext
Remotix8/               # 조직 루트
├─ Interface/           # React UI 레포 (Public)
├─ Remotix-backend/     # 백엔드 서비스 (Private)
└─ Hardware/            # TurtleBot3 Docker 이미지 (Public)
```

* **Interface**: React 기반 원격 제어 UI
* **Remotix-backend**: Python 기반 백엔드 API 서버
* **Hardware**: ROS 2 기반 TurtleBot3 제어용 Docker 이미지

각 레포지토리의 상세 구조는 해당 레포지토리의 README를 참고하세요.

---

## 🚀 설치 및 실행

```bash
# 레포 클론
git clone https://github.com/Remotix8/Interface.git
cd Interface

# 의존성 설치
npm install
# or yarn install

# 개발 서버 실행
npm start
```

## ⚖️ 라이선스

이 프로젝트는 [MIT License](LICENSE)에 따라 라이선스가 부여됩니다.
