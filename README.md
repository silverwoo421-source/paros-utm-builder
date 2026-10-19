# 파로스 UTM 빌더

GA4 권장 UTM 규칙(260211 UTM 정리 시트 기준)으로 캠페인 세트별 UTM 링크를 생성하는 단일 HTML 도구.

- 캠페인 세트: 파워링크(스텔라/파로스), 파워콘텐츠, 구글애즈, 메타, 네이버 GFA
- `{keyword}`, `{{ad.name}}` 같은 매체 치환 매크로는 인코딩하지 않음
- 링크 기록은 브라우저(localStorage)에 저장

배포: Vercel에서 이 저장소를 Import (Framework: Other, 빌드 설정 없음)
