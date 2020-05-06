# README.md

#study

### Git

### 개발자
- linux 개발자 = Git 개발자

### Linux Kernel
- 0.1 A
- 0.2 B
- ....
- lunux foundation
- 버전관리가 필요해짐
- SVN, Git

### Git
- 여러 사람들이 소스코드를 올려놓으면 그 코드를 수정하거나 생성하는 프로그램
- Git bash 이용 가능

### Git-Hub
- MS에서 제작
- 계정마다 repository 생성 가능
- url로 접속하여 repository 확인 가능

- index.html = README.md
- remote repository -> (1) INDEX.md를 찾음
(2) 만약 , (1)이 없으면 README.md 를 찾음

- README.md 약속
- repository에 대한 설명이 필요하다.
- Program에 관련된 소스나 라이브러리등에 대한 설명, 사용법, 버그픽스, 라이센스정보등..
- `1. repository 사용 하려면 초기화 작업이 필요`
- `(1) $git init`
`(2) ATOM`
`(3) GitHub`
`-> 결과는 해당 디렉토리에 .git 디렉토리 생성`
`.git Git 관련 환경설정파일이 있음. ex) bash.rc`
`.git 디렉토리 경로가 repository의 홈디렉토리가 된다.`
`gitbash에서 (master)라고 표시된곳이 repository이며, git명령어를 사용 할 수 있다.`

`git add = (unstaged -> staged)`
`git commit = commit message(변경사항 기재), 쉽게 스냅샷으로 생각 롤백 가능`
`git push = push(GitHub에 업로드)`
`FETCH = 가장 최근의 작업으로 싱크 동기화 (작업하는 파일이 존재 할 시)`
`PULL = download 개념으로 생각, 싱크 동기화 (작업하는 파일이 없을 시)`

`unstaged change = 변경 중`
`staged change = 변경 완료`

### ATOM
- git-hub에서 만든 편집기
- git-plus와 같은 패키지를 플러그인 하여 사용가능
