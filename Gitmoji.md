## Gitmoji 라이브러리 사용법

Gitmoji는 Git 커밋 메시지에 이모지를 추가하여 커밋 내용을 명확하고 직관적으로 표현하는 데 도움을 주는 라이브러리입니다.

### 1. Gitmoji 설치

다음 명령어를 사용하여 Gitmoji를 설치합니다.

```bash
npm install --global gitmoji-cli
```

또는, Visual Studio Code 등의 편집기에서 Gitmoji 확장 프로그램을 설치할 수도 있습니다.

### 2. Gitmoji 사용

**터미널에서 사용:**

```bash
gitmoji -l # 사용 가능한 Gitmoji 목록 확인
git commit -m ":sparkles: 새로운 기능 추가" # 커밋 메시지에 Gitmoji 추가
```

**Visual Studio Code 확장 프로그램 사용:**

1. 소스 제어 탭에서 커밋 메시지 입력란을 클릭합니다.
2. 나타나는 이모지 아이콘을 클릭하여 Gitmoji 목록을 확인하고 원하는 Gitmoji를 선택합니다.

### 3. Gitmoji 목록

| Gitmoji | 설명                                                                                 |
| ------- | ------------------------------------------------------------------------------------ |
| :sparkles: | 새로운 기능 추가                                                                       |
| :bug:      | 버그 수정                                                                               |
| :memo:     | 문서 수정                                                                               |
| :art:      | 코드 스타일 변경                                                                      |
| :fire:     | 코드 삭제                                                                               |
| :lipstick: | UI 변경                                                                               |
| :recycle:  | 코드 리팩토링                                                                         |
| :construction: | 작업 진행 중                                                                        |
| :heavy_plus_sign: | 의존성 추가                                                                        |
| :arrow_up: | 버전 업                                                                               |

### 4. Gitmoji 커밋 메시지 예시

```
:sparkles: 사용자 프로필 페이지 UI 개선
:bug: 로그인 오류 수정
:memo: README.md 파일 업데이트
```

**참고:** Gitmoji는 단순히 커밋 메시지를 꾸미는 것을 넘어, 팀원 간의 커뮤니케이션을 원활하게 하고 커밋 히스토리를 효율적으로 관리하는 데 도움을 줄 수 있습니다.