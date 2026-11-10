# NAON-SPAM-FILTER-ENGINE

스팸필터 **엔진 프로젝트**입니다.
James 앞단에서 메일을 받아 판정(Rspamd + 자체 판정)하고, 격리하거나 James로 전달합니다.

- 아직 개발 시작 전, 기획 단계입니다. 엔진 코드와 설정(엔진 묶음 docker-compose, Rspamd 설정)은 아직 없고 개발 시작 때 새로 만듭니다.
- 관리 백엔드·관리 화면은 `NAON-SPAM-FILTER-MANAGE` 저장소에 있습니다(같은 상위 폴더에 나란히 둡니다).
- 문서
  - `CLAUDE.md` — 엔진 프로젝트 결정 요약
  - `docs/SHARED.md` — 두 프로젝트 공동 기획 (서버 DB, 엔진 API)
  - `docs/FUNC_SPEC.md` — 엔진·관리 전체 기능 명세
  - `docs/Naon-Spam-Filter 초안.md`(`.html`) — 공유용 기획 변경 안내
