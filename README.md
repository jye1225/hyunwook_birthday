# 현욱조장님 생일 축하 사이트

정적 HTML/CSS/JS로 만든 생일 축하 페이지입니다.

- `index.html`: 화면 구조
- `styles.css`: 레이아웃, 봉투, 카드, 반응형 스타일
- `script.js`: 20초 주기 자동 폭죽, 고정 롤링페이퍼 열기
- `assets/developer-birthday-hero.png`: 기본 축하 비주얼
- `assets/hyunwook-photo.png`: 히어로에 표시되는 현욱조장님 사진
- `assets/hyunwook-hero-birthday.png`: 현재 히어로 원형 사진
- `assets/evangelism-team-photo.png`: 마지막 축하 문구 위 단체 사진
- 마지막 섹션에는 생일 축하 마무리 문구와 마태복음 25장 21절 말씀이 표시됩니다.

브라우저에서 `index.html`을 열면 바로 실행됩니다. 전체 글씨는 G마켓 산스 웹폰트를 사용합니다. 폭죽은 처음 한 번 표시된 뒤 20초마다 자동으로 터지고, 롤링페이퍼는 `script.js`의 `letters` 배열에 들어 있는 편지들이 봉투로 표시됩니다.
