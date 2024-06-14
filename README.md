# cau-webtech-final-2024

UpSword Bot (Legacy Version)의 Web Version 포팅 및 신버전 개발입니다.

## Commit convention
### 커밋 종류
- feat : 기능 구현
- fix : 자잘한 수정
- docs : 문서 작성
- style : 코드 포맷팅, 세미콜론 누락 등 코드 변경이 없는 경우
- refactor : 리팩토링
- test : 테스트 코드 작성
- chore : 빌드 업무 수정, 패키지 매니저 수정 등 잡무

### 커밋 스타일
- 종류(패키지): 메세지

### 예시
- feat(common, game-server, game-frontend): 게임 시작 기능 구현
- fix(game-frontend): 게임 시작이 제대로 안 되던 버그 수정
- style(game-frontend): 린트 반영
- chore(game-frontend): lodash 디펜던시 추가
- refactor(game-frontend): 게임 시작 기능 리팩토링
- docs(game-frontend): README 작성


## Branch
- main : 메인 브랜치 / 웹사이트 호스팅 시 보여질 내용
- develop : 개발 브랜치 / 개발용 메인 브랜치. 기능 개발 후 해당 브랜치랑 merge 할 것.
- feat : 기능 브랜치 / 어떠한 기능을 추가할 때 develop에서 분기하여 생성. feat/<name> 형식으로 생성. 기능 개발 완료 후 develop 브랜치와 merge
