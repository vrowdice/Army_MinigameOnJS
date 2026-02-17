# **Army Minigame on JS**

### **English**

# **Army Minigame on JS**

## **Game Service Overview**

A web-based game collection that focuses on the essence of classic minigames, moving away from complex modern games.

### **1. Development Background & Core Concept**

**Classic Game Focus**: Three timeless classic games gathered in one place, providing convenient access to play anytime, anywhere.

**Minimal Design**: Removes unnecessary graphics and complex UI, focusing only on core gameplay to ensure light and fast execution speed.

**Customizable**: Each game allows free adjustment of map size and game speed to play at your own difficulty level.

**Pure Web Technology**: Implemented with only JavaScript, HTML, and CSS, enabling immediate execution in browsers without separate installation or plugins.

### **2. Main Game Features**

**Snake Game**
- Recreation of the classic snake game, providing strategic gameplay of increasing snake length by eating food.
- The goal is to survive as long as possible without colliding with your own body.

**Raft Game**
- A survival game where you control a raft and avoid obstacles, requiring quick reactions and prediction skills.
- An action game where you collect various items and earn points.

**Tetris**
- The representative puzzle game where you rotate and place blocks to complete horizontal lines.
- Provides tense gameplay as speed increases over time.

**Integrated Game Menu**: Convenient interface that allows you to select and start three games from one main screen.

### **3. User Convenience Features**

**Perfect Offline Operation**: All game logic runs on the client side, ensuring stable operation without internet connection.

**Customization Options**
- Map Size Adjustment: Freely set horizontal/vertical block count within 5~50 range.
- Game Speed Adjustment: Adjust speed from 0.1 seconds to 10 seconds to match your skill level.

**Instant Execution**: Start games immediately by simply opening the `index.html` file without separate installation process.

**Cross-Platform Support**: Provides the same experience on web browsers of all operating systems including Windows, macOS, and Linux.

**Lightweight Structure**: Composed of minimal file structure, enabling fast loading and easy deployment.

### **4. Tech Stack**

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla JS)
- **Game Rendering**: HTML5 Canvas API
- **Styling**: Custom CSS (using OpenSans font)
- **Deployment**: Static web hosting (no server required)

### **5. Project Structure**

```
Army_MinigameOnJS/
├── index.html              # Main game selection screen
├── style.css               # Common stylesheet
├── Snack_Game/             # Snake game directory
│   ├── SnackGame.html
│   ├── SnackMainGame.js
│   └── Images/
├── Raft_Game/              # Raft game directory
│   ├── RaftGame.html
│   ├── RaftMainGame.js
│   └── Images/
└── Tetris/                 # Tetris game directory
    ├── Tetris.html
    ├── TetrisMainGame.js
    └── Images/
```

### **6. How to Play**

1. **Start Game**: Open `index.html` file in a web browser.
2. **Select Game**: Click the desired game button on the main screen.
3. **Adjust Settings**: Set map size and game speed on each game's start screen.
4. **Play Game**: Click START button to begin the game and control with keyboard.

### **7. Development Background**

This project was developed during military service for the purpose of learning JavaScript and practical practice. The goal is to strengthen web development fundamentals and improve programming skills by implementing games using only pure web technologies without complex frameworks or libraries, and by recreating classic games.

## **게임 서비스 개요**

복잡한 현대 게임에서 벗어나 클래식 미니게임의 본질에 집중한 웹 기반 게임 컬렉션입니다.

### **1. 개발 배경 및 핵심 컨셉**

**클래식 게임 집중**: 세 가지 시대를 초월한 클래식 게임을 한 곳에 모아 언제 어디서나 즐길 수 있는 간편한 접근성을 제공합니다.

**미니멀 디자인**: 불필요한 그래픽과 복잡한 UI를 제거하고 핵심 게임플레이에만 집중하여 가볍고 빠른 실행 속도를 보장합니다.

**커스터마이징 가능**: 각 게임마다 맵 크기와 게임 속도를 자유롭게 조절하여 자신만의 난이도로 플레이할 수 있습니다.

**순수 웹 기술**: JavaScript, HTML, CSS만으로 구현되어 별도의 설치나 플러그인 없이 브라우저에서 즉시 실행 가능합니다.

### **2. 주요 게임 기능**

**Snake Game (뱀 게임)**
- 고전적인 뱀 게임의 재현으로 음식을 먹으며 뱀의 길이를 늘려가는 전략적 게임플레이를 제공합니다.
- 자신의 몸에 부딪히지 않도록 조심하며 최대한 오래 생존하는 것이 목표입니다.

**Raft Game (뗏목 게임)**
- 뗏목을 조종하며 장애물을 피하는 생존 게임으로 빠른 반응과 예측 능력을 요구합니다.
- 다양한 아이템을 수집하며 점수를 획득하는 액션 게임입니다.

**Tetris (테트리스)**
- 블록을 회전하고 배치하여 가로 줄을 완성하는 퍼즐 게임의 대표작입니다.
- 시간이 지날수록 속도가 빨라져 긴장감 있는 플레이를 제공합니다.

**통합 게임 메뉴**: 세 가지 게임을 하나의 메인 화면에서 선택하여 바로 시작할 수 있는 편리한 인터페이스를 제공합니다.

### **3. 사용자 편의 기능**

**완벽한 오프라인 구동**: 모든 게임 로직이 클라이언트 사이드에서 실행되어 인터넷 연결 없이도 안정적으로 작동합니다.

**커스터마이징 옵션**
- 맵 크기 조절: 가로/세로 블록 수를 5~50 범위 내에서 자유롭게 설정 가능합니다.
- 게임 속도 조절: 0.1초~10초 범위에서 자신의 실력에 맞는 속도로 조절할 수 있습니다.

**즉시 실행**: 별도의 설치 과정 없이 `index.html` 파일만 열면 바로 게임을 시작할 수 있습니다.

**크로스 플랫폼 지원**: Windows, macOS, Linux 등 모든 운영체제의 웹 브라우저에서 동일한 경험을 제공합니다.

**경량화된 구조**: 최소한의 파일 구조로 구성되어 빠른 로딩과 쉬운 배포가 가능합니다.

### **4. 기술 스택**

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla JS)
- **게임 렌더링**: HTML5 Canvas API
- **스타일링**: 커스텀 CSS (OpenSans 폰트 사용)
- **배포**: 정적 웹 호스팅 (별도 서버 불필요)

### **5. 프로젝트 구조**

```
Army_MinigameOnJS/
├── index.html              # 메인 게임 선택 화면
├── style.css               # 공통 스타일시트
├── Snack_Game/             # 뱀 게임 디렉토리
│   ├── SnackGame.html
│   ├── SnackMainGame.js
│   └── Images/
├── Raft_Game/              # 뗏목 게임 디렉토리
│   ├── RaftGame.html
│   ├── RaftMainGame.js
│   └── Images/
└── Tetris/                 # 테트리스 게임 디렉토리
    ├── Tetris.html
    ├── TetrisMainGame.js
    └── Images/
```

### **6. 실행 방법**

1. **게임 시작**: `index.html` 파일을 웹 브라우저에서 엽니다.
2. **게임 선택**: 메인 화면에서 원하는 게임 버튼을 클릭합니다.
3. **설정 조정**: 각 게임의 시작 화면에서 맵 크기와 게임 속도를 설정합니다.
4. **게임 플레이**: START 버튼을 클릭하여 게임을 시작하고 키보드로 조작합니다.

### **7. 개발 배경**

이 프로젝트는 군 복무 기간 중 JavaScript 학습과 실전 연습을 목적으로 개발되었습니다. 복잡한 프레임워크나 라이브러리 없이 순수 웹 기술만으로 게임을 구현하여 웹 개발의 기본기를 다지고, 클래식 게임의 재현을 통해 프로그래밍 실력을 향상시키는 것을 목표로 합니다.

---

## **License**

This project is for educational and fan use only. All rights to the original games and assets belong to their respective creators.

---
