# blobcourse-site

blobcourse.com 리뉴얼용 정적 사이트. 빌드 툴 없음 — `index.html`을 브라우저에서 직접 열면 됩니다.

## 현재 상태
실제 회사/대표 정보로 채워진 1차 버전. 목적은 적극적 마케팅이 아니라 "회사가 운영 중임을 보여주는" 저관리 신뢰도 사이트 — 그래서 문의도 폼이 아니라 mailto 링크 하나로 처리하고, 자주 갱신해야 하는 구조(커리큘럼 그리드 등)는 넣지 않았습니다.

남은 것: 강사 실사진(현재 `instructor-photo` 자리 비어있음, `assets/img/`에 넣고 index.html에서 `<img>`로 교체), 대학/기업명 실명 노출 가능 여부 최종 확인(`~/CLAUDE_CMUX/0xBlob/knowledge/website-content.md` 참고), 실제 배포.

## 공유용 페이지
`blobcourse-shareable.html`은 이미지·폰트가 전부 내장된 단일 파일 버전(폰트는 페이지에 실제 쓰이는 글자만 서브셋해서 용량을 줄임). Claude 아티팩트로도 게시되어 있어 링크로 공유 가능. `index.html`(개발용, css/js/이미지 분리)을 수정한 뒤에는 이 파일도 같이 갱신해야 함.

## 브랜드 자산
- 로고: `assets/img/logo.png` (사용자 제공 원본, 코랄레드 `#EA544E` — 이 색이 사이트 전체 accent 컬러)

## 로컬 확인
```
open index.html
```

## 배포 (아직 미정)
- 호스팅: GitHub Pages 또는 Vercel 후보 (미결정)
- 도메인: blobcourse.com을 이 사이트로 직접 연결할 예정(기존 didisam.com 리다이렉션은 없앰). 도메인 등록업체에서 DNS를 사용자가 직접 변경해야 함.

## 참고
- 전체 계획: `~/.claude/plans/0xblob-silly-pnueli.md`
- 지식 베이스: `~/CLAUDE_CMUX/0xBlob/`
