# moly-legal

Moly 앱의 법적 고지 페이지(개인정보처리방침·이용약관)를 GitHub Pages로 호스팅하는 저장소.

- `privacy.html` — 개인정보처리방침
- `terms.html` — 이용약관
- `index.html` — 목차

앱(`moly_app`)의 `lib/core/constants/legal.dart`가 아래 URL을 참조한다.

- https://hsadunicorn.github.io/moly-legal/privacy.html
- https://hsadunicorn.github.io/moly-legal/terms.html

## 채워진 값 (2026-07-26)

- 운영자: Sun Lee (개인·비사업)
- 문의/개인정보 보호책임자: sunlee334@gmail.com
- 시행일: 2026-07-26 · 준거법: 대한민국 · 최소연령: 만 14세
- 제3자: Supabase, Pl@ntNet(PlantNet), Plant.id(Kindwise), Open-Meteo, AI(LLM) 제공자, Google/Apple

## ⚠️ 남은 확인 작업

- **AI(LLM) 제공자명 특정**: 식물 대화는 서버(`chat-proxy` 엣지 함수)를 거치므로
  실제 LLM 벤더명을 privacy.html 제3자 표에 명시하는 것이 정확하다(현재 "AI(LLM) API 제공자"로 표기).
- **법률 전문가 검토(권장)**: 본 문서는 변호사 검토를 거치지 않은 운영자 작성본이다.
  한국 개인정보보호법(PIPA)·위치정보법·전자상거래법 등 대비 항목별 보유기간 구체화,
  국외이전 동의 방식, 동의 획득 UI 정합성 등은 전문가 확인을 권장한다.
