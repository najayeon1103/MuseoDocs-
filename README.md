# MuseoDocs-
미술사가, 예비 큐레이터, 박물관학 연구자들이 전시 관람 기록, 작품 분석, 학술 연구 자료를 체계적으로 아카이빙할 수 있도록 설계된 구조 중심의 깔끔한 정적 웹 템플릿입니다.
museo-docs/
├── _data/
│   ├── exhibitions.yml       # 미술관 및 갤러리 방문을 위한 구조화된 메타데이터
│   └── artworks.yml          # 카탈로깅된 예술 작품들의 종합 목록
├── _layouts/
│   ├── default.html          # 깔끔한 여백의 그리드를 가진 기본 레이아웃
│   ├── exhibition.html       # 전시 분석 기록에 최적화된 특화 레이아웃
│   └── research.html         # 서양 미술사 에세이 등에 맞춘 타이포그래피 중심 레이아웃
├── _posts/
│   ├── 2026-05-01-andy-warhol-selling-art.md  # (예시) 앤디 워홀 전시 기록
│   └── 2026-06-01-western-art-history-renaissance.md # (예시) 서양 미술사 연구 노트
├── assets/
│   └── css/
│       └── main.css          # 부드럽고 차분한 색감을 더한 미니멀 타이포그래피 스타일링
├── index.html                # 구조화된 데이터 표가 돋보이는 메인 아카이브 대시보드
└── README.md                 # 프로젝트 설명 문서
---
layout: exhibition
title: "앤디 워홀: Selling Art (Andy Warhol: Selling Art)"
institution: "대전시립미술관"
date: 2026-05-01
curator: "전시 기획팀"
focus: "팝아트, 비즈니스 아트 전략, 상업주의"
---
---
layout: research
title: "레오나르도부터 루이니까지의 스푸마토 기법"
artist_focus: ["레오나르도 다 빈치", "베르나르디노 루이니"]
period: "르네상스"
category: "서양 미술사"
---
