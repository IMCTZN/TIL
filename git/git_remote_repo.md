# Remote Repository(원격 저장소)

코드와 버전 관리 이력을 온라인 상의 특정 위치에 저장하여 여러 개발자가 협업하고 코드를 공유할 수 있는 저장 공간

### git remote add origin remote_repo_url

로컬 저장소에 원격 저장소 추가

### push / pull & clone

local >>github = push

github >> local = pull or clone

- pull = 이미 해본 적 있음
- clone = 처음 해보는 프로젝트

push = ***커밋이 올라가는 것, 파일이 올라가는 것이 아님***

### git push origin master

원격 저장소에 commit 목록을 업로드 

- git push -u origin master
    - 이후에는 git push만 해도 된다