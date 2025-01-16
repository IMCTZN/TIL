## 실습습

### git init

로컬 저장소 설정 (초기화)

- Terminal 내 경로 뒤 (master) 확인할 것
- 주의사항
    - git 로컬 저장소 내에 또다른 git 로컬 저장소를 만들지 말 것
    - 가장 바깥의 git 저장소가 안쪽을 추적할 수 없

### git status

파일 추적 상태 확인 / 현재 로컬 저장소의 파일 상태 보

- modified : 추적중 파일의 내용이 변경됨
- untracked files : 아직 추적중이지 않은 파일 (Staging Area에 추가 안됨)

### git add (파일이름)

Staging Area로 추가

- git add —all = 전부 추가 (.gitignore 내에 추가된 파일 제외)

### git commit -m “이름”

Staging Area 내 파일을 “이름”으로 커밋하여 버전 확정

- git commit —amend
    - commit  메시지 수

### git config ~

설정 / 컴퓨터마다 설정해야함

- git config —global -l

### git log

커밋 내역 확인

- git log —oneline =  목록 한 줄로 보기