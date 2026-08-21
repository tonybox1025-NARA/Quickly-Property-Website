# Quickly Property — 매물 상세페이지 템플릿 (listing-template-v2.html)

## 배경
tytasset.com 럭셔리 매물 페이지를 참고해서 만들었지만, 구조/톤을 완전히 새로 디자인함.
브랜드명: Quickly Property (임시, 추후 변경 예정)
프로젝트명(샘플): Aurelia Grove — 방콕 Bang Na 지역 8세대 슈퍼카 개러지 풀빌라

## 디자인 컨셉
- 방향성: "웅장하면서도 차분하고, 고급스러우면서 생동감 넘치는" 톤
- 시그니처 섹션: "Hours of the House" — 층별 구성이 아니라 시간대(새벽/정오/골든아워/저녁/밤)별로
  어떤 공간이 가장 빛나는지 보여주는 아치형 타임라인. 블루프린트/도면 느낌 대신 빛과 시간 흐름으로 구성.

## 컬러 팔레트
- --navy: #0F1526 (배경, 깊은 인디고 네이비)
- --navy-2: #161F38
- --ivory: #F6F0E2 (본문 텍스트)
- --ivory-dim: #CBC0A6 (보조 텍스트)
- --gold: #E3A542 (메인 포인트)
- --gold-soft: #F2C877 (밝은 골드, 강조/호버)
- --ember: #D6553C (보조 포인트, 최소한으로만 사용)

## 타이포그래피
- Display: Spectral (이탤릭 강조 활용)
- Body: Manrope
- Mono/데이터: Space Mono
- Google Fonts CDN으로 로드 (fonts.googleapis.com)

## 페이지 구조 (섹션 순서)
1. Header — 고정 네비, 로고는 호(arc)+원 모양 SVG (해 뜨는 궤적 모티프)
2. Hero — 큰 세리프 헤드라인 + 앰비언트 골드 글로우 배경 + 지붕 실루엣 SVG + 핵심 스펙 4개
3. Overview — 인용구 스타일 리드 문단 + 개요 텍스트 / 우측에 팩트 리스트(개발사, 지역, 소유형태 등)
4. Hours of the House — 시그니처 아치 타임라인 (5개 모먼트: 새벽-마스터스위트, 정오-쇼룸개러지,
   골든아워-중정풀장, 저녁-리빙홀, 밤-루프가든)
5. Specification — 2단 패널 (스펙 요약 / 시설·시스템 리스트)
6. Location — 지도 플레이트(그리드+핀 스타일) + 주소 + 주요 동선 소요시간
7. Enquire — 어드바이저 카드 + 문의 폼 (이름/연락처/이메일/메시지)
8. Footer — 로고 + 저작권

## 기술 스펙
- 순수 HTML/CSS (프레임워크 없음), 반응형 (900px, 820px, 640px 브레이크포인트)
- prefers-reduced-motion 대응
- 폼은 현재 정적 (onsubmit preventDefault, 실제 제출 로직 없음)

## 다음 작업 후보
- 실제 매물 사진/텍스트로 교체
- "Quickly Property" → 최종 브랜드명 치환
- 폼 제출 로직 연결 (이메일/DB)
- 로고 SVG 아이콘 교체 여부 결정
