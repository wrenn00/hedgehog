# Hedgehog Pile

고슴도치를 무한히 쌓는 인터랙티브 토이.

## 사용법

캔버스를 클릭(또는 터치)하면 그 위치에 고슴도치가 떨어집니다.  
게임 오버 없음. 원하는 만큼 쌓으세요.

## 기술

- Matter.js (물리 엔진)
- HTML5 Canvas
- 단일 `index.html`

## 로컬 실행

```bash
# 반드시 로컬 서버로 열어야 합니다 (wh.png 이미지 로드 때문에)
npx serve .
# http://localhost:3000
```

## 파일 구조

```
hedgehog-pile/
├── index.html   # 메인 앱
├── wh.png       # 고슴도치 이미지
└── README.md
```
