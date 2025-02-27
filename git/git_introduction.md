# Git

분산 버전 관리 시스템 / **마지막 파일과, 이전 변경사항만 남긴 상태**

---

## 중앙 집중식

버전은 중앙 서버에 저장되고 중앙 서버에서 파일을 가져와 다시 중앙에 업로드

## 분산식 (git)

버전을 여러 개의 복제된 저장소에 저장 및 관리

### 장점

- 중앙 서버에 의존하지 않고도 동시에 다양한 작업 수행
    - 개발자들 간의 작업 ***충돌을 줄이고***, 개발 생산성을 향상
- 중앙 서버의 장애나 손실에 대비하여 백업과 복구가 용이
- 인터넷에 연결되지 않은 환경에서도 작업 가능
    - 변경 이력과 코드를 로컬 저장소에 기록, 나중에 중앙 서버와 동기화