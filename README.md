# 클로드 게임 리스트

클로드와 함께 만들어 깃허브에 올리고 Vercel로 배포한 웹 게임들을 한곳에 모은 페이지입니다.

- **규칙**: 게임 규칙을 창으로 띄워서 읽을 수 있습니다.
- **바로가기**: 메뉴바·상태바 없이 크기만 조절되는 새 창으로 게임이 열립니다. (휴대폰에서는 새 탭)

## 게임 목록

| 게임 | 주소 | 저장소 |
| --- | --- | --- |
| 네모세기 | https://countsqaure.vercel.app | jkh76/count4 |
| Hit, Stay | https://hitstay.vercel.app | jkh76/hitstay |
| 플래그 메모리 | https://flagmemory.vercel.app | jkh76/flagmemory |
| 땅따먹기 | https://flickland.vercel.app | jkh76/hopscotch |
| 해저탐험 | https://deepseaadventure.vercel.app | jkh76/deepsea |
| 우봉고 | https://ubongom.vercel.app | jkh76/ubongo |
| 울타리 치기(Slitherlink) | https://slitherlinks.vercel.app | jkh76/slitherlink |
| 오딘 카드 대전 | https://odin-card.vercel.app | jkh76/odin |
| 흑과 백 | https://bnwduel.vercel.app | jkh76/bnw |
| 벌칙 룰렛 | https://funnyroulet.vercel.app | jkh76/funnyroulet |
| 경마 레이스 | https://horse-race-web.vercel.app | jkh76/horse-race |
| 블라인드 포커 | https://hiddenpoker.vercel.app | jkh76/hiddenpoker |

## 게임 추가·수정

`index.html` 안의 `GAMES` 목록에 항목을 추가하거나 고칩니다.
`name`(이름), `desc`(한 줄 설명), `url`(게임 주소), `icon`(파비콘), `emoji`(아이콘 대체), `win`(새 창 크기), `rules`(규칙 HTML).
게임 아이콘은 각 저장소의 파비콘을 `ICON` 안에 data URI로 넣어 두었습니다.

빌드 없이 `index.html` 한 파일로 동작합니다.
