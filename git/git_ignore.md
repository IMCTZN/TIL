## .gitignore

해당 파일 내에 있는 이름은 git이 인식하지 않는다. 다만 해당 파일을 git add 할 수 있음. git add .gitignore

- 이미 git의 관리를 받은 이력이 있는 파일이나 디렉토리는 나중에 작성해도 적용되지 않음
    - git rm —cached 명령어를 통해 캐시에서 삭제 필요
- ***따라서 미리미리 만들어야한다!***
- [[gitignore.io](http://gitignore.io)] = 필수적 ignore 리스트 생성해줌!