# OREUN TAXONOMY 히트맵 (Sector Heatmap)

한국 주식 **158개 L3 섹터**의 일간 부각도를 실시간으로 보는 인터랙티브 히트맵.

## ▶ 실제 결과물 보기

### https://oreuntimes.github.io/taxonomy-map/

위 주소가 **실제로 보이는 완성 사이트**입니다.  
지금 이 GitHub 페이지에 보이는 파일(`index.html`)은 그 사이트를 만드는 원본 재료입니다 — 코드가 보이는 게 정상입니다.

## 섹터별 직링크

| 섹터 | 링크 |
|---|---|
| 반도체 | https://oreuntimes.github.io/taxonomy-map/#semi |
| 제약·바이오 | https://oreuntimes.github.io/taxonomy-map/#pharma |
| 자동차 | https://oreuntimes.github.io/taxonomy-map/#auto |
| SW·AI | https://oreuntimes.github.io/taxonomy-map/#sw |
| 금융 | https://oreuntimes.github.io/taxonomy-map/#finance |
| 에너지 | https://oreuntimes.github.io/taxonomy-map/#energy |
| 방산·우주 | https://oreuntimes.github.io/taxonomy-map/#defense |
| 조선 | https://oreuntimes.github.io/taxonomy-map/#ship |

## 구성

- **L1 탭 바** — 20개 대분류 섹터 탭 전환 + URL 해시 딥링크
- **전체 뷰** — 모든 섹터 한눈에, 부각도 색상 강도로 표현
- **섹터 확대** — 탭 클릭 시 해당 섹터 L2·L3 디테일 뷰
- **툴팁** — 테마빈도·종목등락·수급·US촉매 스코어 분해

## 데이터

- 스코어링 모델 v0.4: 테마빈도 35% + 종목등락 30% + 수급 20% + US촉매 10% + US섹터플로우 5%
- 매일 장 마감 후 자동 갱신
- 본 자료는 정보 제공 목적이며 **투자 권유가 아닙니다**. © OREUN Research
