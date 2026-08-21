# Quickly Property Website

럭셔리 부동산 매물 상세페이지 웹사이트 (샘플: *Aurelia Grove*).

## 파일 구조

| 파일 | 설명 |
|---|---|
| `index.html` | 실제 웹사이트 홈페이지 (매물 상세페이지). 여기를 계속 수정해 나갑니다. |
| `docs/handoff-brief.md` | 디자인 컨셉·컬러·타이포·섹션 구조를 정리한 핸드오프 브리프 |

## 작업 흐름 (반복 사이클)

```
index.html 수정  →  미리보기 확인  →  GitHub에 저장(commit/push)  →  GitHub Pages에 자동 반영
```

## 공개 주소 (GitHub Pages)

저장소 **Settings → Pages** 에서 배포 브랜치를 지정하면 무료 주소로 사이트가 게시됩니다.
(도메인 구매는 나중 선택 사항 — 무료 주소로 먼저 확인하며 다듬습니다.)

## 기술 스택

- 순수 HTML/CSS (프레임워크 없음), 반응형
- 폰트: Spectral / Manrope / Space Mono (Google Fonts)
- 별도 빌드 과정 없음 — 브라우저가 `index.html`을 바로 렌더링
