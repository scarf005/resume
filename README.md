---
mainfont: Sarasa Term K
CJKmainfont: Sarasa Term K
---

# 김영현

- 이름: 김영현
- 생년월일: 2002-05-11
- 연락처: 010-4141-0511
- 이메일: greenscarf005@gmail.com
- GitHub: <https://github.com/scarf005>

## 소개

코드를 통해 일상의 불편함을 해결하는 것에 매력을 느끼고, 이를 위해 오픈소스에 지속적으로 기여하고
있습니다. 함수형 타입스크립트와 테스트 주도 개발(TDD)을 이용해 신뢰할 수 있는 프로그램을 만들고
싶습니다. 무엇보다도, 협업이 즐거운 개발 환경을 만들고 싶어 git과 GitHub Actions, 그리고 문서화를
끊임없이 학습하고 있습니다.

---

## 42 Seoul 팀 프로젝트

### 도서동아리 전자도서관 서비스 유지보수 (React, TypeScript)

> 기간: 2023.02 - 현재

링크: <https://github.com/jiphyeonjeon-42/frontend>

- Vite 빌드 시스템을 사용해 기존 CRA 시스템 대비 빌드 속도 6배, 시작 속도 10배 향상
- 전체 코드의 40%를 자바스크립트에서 타입스크립트로 전환, 개발 안정성 및 생산성 향상
- 컴포넌트 prop를 리터럴 유니언 타입으로 변경, 런타임 성능 향상
- 스쿼시 머지 도입으로 커밋 히스토리 가독성 향상

### 핑퐁 및 채팅 서비스 개발 (React, TypeScript)

> 기간: 2022.04 - 2022.05

링크: <https://github.com/exciting-transcendence/transcendence>

- Storybook을 이용해 전체 컴포넌트의 50%를 라이브러리로 구성, 접근성 향상
- CI 도입으로 PR마다 컴포넌트 라이브러리 배포, 리뷰시 테스트가 더욱 용이하게 함

## 오픈소스 기여

### Deno 자바스크립트 런타임 설정 파일 파서 기여

> 기간: 2023.02 - 2023.05

링크: <https://github.com/denoland/deno/pull/17778> <https://github.com/denoland/deno/pull/17799>

- 중첩된 설정 파일 구조를 단순화, 가독성 향상
- `exclude` (파일 제외) 필드를 전역 설정에 추가, 중복 필드 간소화

### Vite 기반 테스팅 프레임워크 Vitest 기여 (TypeScript)

> 기간: 2022.12 - 2022.12

링크: <https://github.com/vitest-dev/vitest>

- 테스트명 표시 함수에 객체 구조를 출력하게 하는 기능 추가, 테스트명 가독성 향상
- UI 모드에서 테스트 실패시 diff를 표시 기능 추가, 디버깅 편의성 향상

### 로그라이크 게임 "Cataclysm: Bright Nights" 유지보수 (C++, TypeScript)

> 기간: 2022.04 - 현재

링크: <https://github.com/cataclysmbnteam/Cataclysm-BN>

- 참조에 의한 호출 일부를 값에 의한 호출로 변경, 전체 게임 성능 10% 향상
- 팀원 모두가 코드 리뷰를 참여하는 문화를 도입, 개발 사이클 속도 평균 4배 향상
- 파이썬으로 작성된 ctags 생성 프로그램을 TypeScript로 재작성, 유지보수성 향상 및 해당 줄로 바로가기
  기능 추가
- zod-to-JSON-schema 라이브러리를 활용한 모드 파일 실시간 검증 기능 추가
- JSON 포매터 툴의 병렬 실행으로 멀티코어 환경에서 실행 속도 4배, CI 환경에서 2배 향상

### 덱빌딩 카드게임 Slay The Spire의 모드 "Marisa: Continued" 유지보수 (Kotlin, TypeScript)

> 기간: 2022.12 - 현재

링크: <https://github.com/scarf005/marisa>

- 마이그레이션 툴을 사용해 자바 코드 2만 줄을 함수형 코틀린으로 전환, 유지보수성 향상
- 타입스크립트로 번역 오류 검출 프로그램을 작성, 번역 품질 향상

---

## 교육

### 42 Seoul

> 기간: 2021-05 - 2022-09

42 Seoul은 교수, 교재, 학비 없이 프로젝트와 동료 학습 중심으로 개발자를 양성하는 프로그램입니다.
주로 C, C++을 사용하며, 졸업 과제는 TypeScript를 사용합니다. 과제를 진행하며 겪었던 주된 어려움은
프로그램 동작의 테스트가 어렵다는 점, 그리고 팀 과제 시 협업이 어렵다는 점이었습니다. 이를 해결하기
위해 심화 과제에서 사용한 순수 함수형 언어 Haskell과 Git을 이용한 과제 제출 방식에서 영감을 얻어,
테스트 주도 개발과 CI를 통한 개발 경험 향상에 관심을 가지게 되었습니다.

### 한국방송통신대학교

> 기간: 2021-06 - 현재

---

## 수상 및 기타

### 2022.09 - Mantine 컴포넌트 라이브러리 공식 문서 오류 수정

링크: <https://github.com/mantinedev/mantine/pull/2386>

- `use-list-state` 후크의 `filter` 함수에 대한 설명 오류 수정

### 2022.12 - Tanstack Router 버그 리포트 작성 편의성 개선

링크: <https://github.com/TanStack/router/pull/436>

- 버그 재현이 가능하도록 구성한 온라인 에디터를 버그 리포트 양식에 제공, 재현 편의성 향상

### 2023.04 - React Router 라이브러리 공식 문서 개선

링크: <https://github.com/remix-run/react-router/pull/10311>

- `use-navigate` 후크에 누락된 `replace` 설명 추가

### 2023.05 - Deno 표준 라이브러리 `collection` 모듈 개선

링크: <https://github.com/denoland/deno_std/pull/3365>

- 객체를 위한 `partition`함수인 `partitionEntries` 함수 추가

### 2023.05 - PR 컨벤션 관리 플러그인 `Semantic PR` 버그 수정

링크: <https://github.com/Ezard/semantic-prs/pull/295>

- PR 제목 시작부에 공백이 있어도 올바르다고 인식하던 버그 수정
