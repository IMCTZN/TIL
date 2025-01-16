## Git의 영역

1. Working Directory
2. Staging Area
3. Repository

### Working Directory

실제 작업 중인 파일들이 위치하는 영역

- 생성된 모든 파일들은 Working Directory로 들어감
- ***아직 프로젝트의 일부가 되진 않았음***

### Staging Area

Working Directory에서 변경된 파일 중, 다음 버전에  포함시킬 파일들을 선택적으로 추가하거나 제외할 수 있는 중간 준비 영역

- 실제로 프로젝트에 추가된 파일들

### Repository

버전 이력과 파일들이 영구적으로 저장되는 영역, 모든 버전과 변경 이력이 기록됨

- 실제로 버전에 추가된 파일들
- Staging Area에서 Repository로 파일이 들어갈 때마다, 변경사항 파일이 생성됨 >> 버전관리

### Commit

“버전” / 커밋하다 = 버전을 저장하다, 확정짓다

변경된 파일들을 저장하는 행위이며, 마치 사진을 찍듯이 기록한다 하여 snapshot이라고도 함