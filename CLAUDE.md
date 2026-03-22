# CLAUDE.md

이 파일은 이 저장소에서 작업할 때 Claude Code (claude.ai/code)에게 제공되는 안내 문서입니다.

## 프로젝트 개요

`index.html` 단일 파일로 구성된 정적 개인소개 웹페이지입니다.
빌드 도구, 패키지 매니저, 외부 의존성이 없으며 브라우저에서 파일을 직접 열어 사용합니다.

## 대상 인물

- **이름**: 김연주
- **현직**: 다이닝브랜즈그룹 (9년차 재직 중)
- **경력**: CJ푸드빌 7년 → 교육 분야 10년 → 다이닝브랜즈그룹 9년차
- **이메일**: younju@diningbrands.com
- **원본 데이터**: `mycareer.md`

## 아키텍처

모든 코드는 `index.html` 하나에 포함되어 있습니다:

- **구조** — 단일 페이지, 섹션 구성: Hero / About / Career / Contact / Footer
- **스타일** — 모든 CSS는 `<style>` 태그 내 인라인 작성, Apple 스타일 디자인 (라이트 모드, 시스템 폰트 + Noto Sans KR)
- **인터랙션** — 별도 JS 없음, CSS 트랜지션 및 HTML 앵커 링크로 부드러운 스크롤 처리
- **폰트** — Google Fonts `Noto Sans KR` (고딕 계열)

## 디자인 가이드

- 배경: `#FAFAFA`, 카드: `#FFFFFF`
- 주 텍스트: `#1D1D1F`, 보조 텍스트: `#6E6E73`
- 강조 컬러: `#0071E3` (Apple Blue, 현재 직장 표시에 사용)
- 네비게이션: 상단 고정, backdrop-filter blur 적용
- 반응형: 680px 이하 모바일 대응
