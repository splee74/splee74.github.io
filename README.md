# splee74.github.io

스도쿠 승급전 플레이스토어 앱(TWA)의 주소창을 없애기 위한 저장소입니다.

- `.well-known/assetlinks.json` : 앱(io.github.splee74.sudoku)과 게임 주소(https://splee74.github.io/sudoku/)를 이어 주는 파일
  - 지문 1 : PWABuilder 로 만든 서명 열쇠(signing.keystore)
  - Play Console 에 앱을 올린 뒤 "설정 → 앱 서명" 의 SHA-256 지문을 목록에 하나 더 넣어야 합니다
- `.nojekyll` : `.well-known` 폴더가 인터넷에 올라가게 하는 빈 파일 (지우지 마세요)
