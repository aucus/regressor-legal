# regressor-legal

「회귀자의 기록 (Regressor Ledger)」 의 법무·지원 페이지. **GitHub Pages 로 서빙한다.**

- `privacy-policy.html` — 개인정보처리방침(ko·en). App Store Connect 「개인정보 처리방침 URL」 에 넣는 값
- `support.html` — 고객지원(ko·en). App Store Connect 「지원 URL」
- `index.html` — 두 페이지로 가는 표지

선행작과 같은 구조다 — `moonlit-legal`(달의 가게) · `vermilion-legal`(VERMILION). 문의 메일은 스튜디오 공용 `travelic.games@gmail.com`.

## 고칠 때

- **앱이 하는 일이 바뀌면 방침도 바꾼다.** 특히 ① 네트워크 요청이 늘어날 때 ② 인앱 결제가 생길 때 ③ 새 기기 권한을 요청할 때. 그때 「최종 수정일」 을 갱신한다.
- 현재 방침이 약속하는 것: 계정 없음 · 서버 없음 · 광고/분석 SDK 없음 · 인앱 결제 없음 · 네트워크는 **App Store 버전 조회 하나뿐**(하루 1회). 앱 쪽 근거는 `regressor-ledger/src/engine/meta/app-update.ts`.
