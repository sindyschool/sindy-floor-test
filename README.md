# 나의 의식 수준은 몇 층일까?

신디의 의식의 지도 17층 자가 체크 테스트. 서버·DB 없는 정적 페이지로, Vercel CDN에서 그대로 서비스된다.

- `index.html` — 테스트 전체 (문항, 채점, 캐릭터, 결과)
- `og-image.png` — 링크 미리보기 이미지 (1200×630)
- `vercel.json` — CDN 캐시 설정

## 배포
GitHub에 push하면 Vercel이 자동으로 다시 배포한다.

## 주소가 바뀌면
`index.html` 위쪽의 `og:url`, `og:image` 주소를 새 도메인으로 바꾼다.
