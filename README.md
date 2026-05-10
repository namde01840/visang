# Visang Reports

비상교육 사내 기획·운영 관련 보고문서·자료 모음. 각 프로젝트는 독립된 폴더로 관리되며, GitHub Pages로 외부 공유됩니다.

## 프로젝트 목록

| 프로젝트 | 설명 | 보기 |
|---|---|---|
| [cbs-authoring-tool-strategy](./cbs-authoring-tool-strategy/) | CBS 저작툴 현황과 통합 고도화 필요성 보고 (2026.05) | [▶ Live](https://namde01840.github.io/visang/cbs-authoring-tool-strategy/) |
| [document](./document/) | CBS 저작툴 고도화 전략 (26년 03월) — 초기 보고 | [▶ Live](https://namde01840.github.io/visang/document/) |
| [document-v2](./document-v2/) | 저작툴 고도화 전략 v2 — 보강판 | [▶ Live](https://namde01840.github.io/visang/document-v2/) |
| [CBS-new](./CBS-new/) | CBS 신규 브랜드 / 신규 기능 이용 가이드 | [▶ Live](https://namde01840.github.io/visang/CBS-new/) |
| [FGI](./FGI/) | 교사 FGI 슬라이드 (정·동적 저작툴 현황 공유) | [▶ Live](https://namde01840.github.io/visang/FGI/) |

### 별도 관리 (Next.js 기반)

빌드 결과물이 별도로 필요하여 본 monorepo에는 포함되지 않은 프로젝트입니다. 운영 시점에 빌드 산출물을 추가하거나 별도 호스팅을 사용하세요.

| 프로젝트 | 원본 Repo | 비고 |
|---|---|---|
| Teacher-s-tools | [namde01840/Teacher-s-tools](https://github.com/namde01840/Teacher-s-tools) | Next.js 소스. `npm run build` 후 `out/` 폴더 결과물 필요 |
| english_library | [namde01840/english_library](https://github.com/namde01840/english_library) | Next.js 소스. 동일 |

## 새 프로젝트 추가하기

1. 저장소 루트에 `[프로젝트-슬러그]/` 폴더 생성
2. 폴더 안에 `index.html` 및 자원 파일 배치
3. 본 README의 프로젝트 목록 표에 행 추가
4. 커밋 후 push — GitHub Pages가 자동 반영

## URL 구조

```
https://namde01840.github.io/visang/[프로젝트-슬러그]/
```

## 기존 repo 처리

본 monorepo는 기존 개별 repo를 **복사**한 것이며, 원본 repo는 그대로 유지되어 있습니다. 따라서 기존에 공유하신 GitHub Pages URL(`namde01840.github.io/document/` 등)도 계속 동작합니다. 원본을 정리하실 경우 외부 공유 URL이 영향을 받으므로 주의가 필요합니다.
