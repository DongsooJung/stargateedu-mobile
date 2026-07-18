# stargateedu-mobile

Stargate EDU Mobile Web App.

정동수(Dongsoo Jung) · Stargate Corporation의 연구·사업·교육 작업물을 모아 보여주는 모바일 우선(mobile-first) 단일 페이지 웹 앱입니다. 홈 / 프로젝트 / 소개 / 연락 4개 탭을 하단 탭 바로 전환하는 앱 셸(app-shell) 형태로 구성되어 있습니다.

## Live

- https://mobile.stargateedu.co.kr

## Stack

- 순수 정적 HTML/CSS/JavaScript (단일 `index.html`, 프레임워크·빌드 도구 없음)
- 탭 전환 기반 클라이언트 사이드 화면 렌더링 (`switchTab`)
- GitHub Pages 호스팅 + 커스텀 도메인 (`CNAME`: `mobile.stargateedu.co.kr`)

## Structure

- `index.html` — 앱 전체(마크업·스타일·스크립트 인라인)
- `CNAME` — GitHub Pages 커스텀 도메인 설정
- `README.md` — 프로젝트 설명
