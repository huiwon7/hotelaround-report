# 호텔어라운드 평창 — 매출 현황 보고

정적 HTML 리포트 (공개본). GitHub Pages로 배포됩니다.

- `index.html` — 보고서 단일 파일 (자체 완결형: 인라인 SVG 차트 포함)
- 대외비(재무 진단·제휴 딜 조건)는 이 공개본에 포함되지 않습니다.

## 검색 수요 × 매출 실적 교차 분석

`search/` — NAVER 검색 수요(18개 키워드 24개월)를 위 매출 실적과 맞대어 본 리포트.
공개 URL: <https://huiwon7.github.io/hotelaround-report/search/>

- `search/index.html` — 자체 완결형 단일 파일 (인라인 SVG 차트 15종, 라이트/다크 대응)
- `search/report.pdf` — 같은 내용의 A4 21페이지 PDF
- 수치 출처는 이 저장소의 `index.html`(매출·점유율)과 NAVER 데이터랩·검색광고 API(검색량)입니다.

## 숙박 수요 키워드 36개월 분석

`demand/` — 숙박 의도 키워드 10개만 추려 3년치(2023-08~2026-07)를 실측한 리포트.
공개 URL: <https://huiwon7.github.io/hotelaround-report/demand/>

- `demand/index.html` — 자체 완결형 단일 파일 (인라인 SVG 차트 4종, 라이트/다크 대응)
- 위 `search/` 리포트가 18개 키워드 24개월을 다뤘다면, 이쪽은 **숙박 수요와 직접
  연결된 10개**로 좁히고 구간을 36개월로 늘린 것입니다. 10개 중 3개는 3년 내내
  검색량이 관측되지 않아 "수요 없음"으로 판정됩니다.
- 매출·점유율 수치는 `search/`와 같은 출처를 씁니다.
