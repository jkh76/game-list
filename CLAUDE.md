# 클로드 게임 리스트 (game-list)

답변은 한국어로 한다.

## HTML 파일 이름 규칙

- 수정본이나 새 버전을 만들어 경훈에게 보여 줄 때는 파일 이름을 `클로드 게임 리스트.html`로 한다.
- 깃허브에 푸시할 때만 같은 내용을 `index.html`로 올린다. 저장소에는 `클로드 게임 리스트.html`을 따로 올리지 않는다.

## 구성

- 게임 목록은 `index.html`의 `GAMES` 배열, 아이콘은 `ICON`(각 게임 저장소 파비콘을 data URI로)
- 바로가기는 `window.open`으로 popup 창(메뉴바·툴바·상태바 없음, resizable)
- 배포: Vercel (main 브랜치 푸시 시 자동 배포)
