# Docker Desktop 설치 (과제 환경설정)
- 과제/숙제 채점은 Docker Desktop Ubuntu 22.04 컨테이너에서 진행합니다.
- 만약, Visual Studio 에서 작성한 코드가 우분투에서 동작하지 않는 경우, 실행 불가로 판단하여 채점합니다.

## 사전 준비
- WSL이 설치되어 있는지 확인합니다.
- 가상화 기능이 켜져있는지 확인합니다.

## 설치
- [https://www.docker.com/products/docker-desktop/](https://www.docker.com/products/docker-desktop/)로 접속하여 다운로드합니다.
- 설치 이후 Docker에서 Ubuntu 22.04 이미지를 찾아 pull 하고 run하여 컨테이너로 실행합니다.
<img width="784" alt="스크린샷 2024-05-01 오후 3 15 49" src="https://github.com/inu-it-ta/2024-1-datastructure/assets/108407945/a5359531-3c94-4e03-a7fb-1f74638330e6">
<img width="819" alt="스크린샷 2024-05-01 오후 3 17 08" src="https://github.com/inu-it-ta/2024-1-datastructure/assets/108407945/92ef740c-4694-4783-b3b7-dec7bf7180bc">

## 우분투 세팅
- gcc를 포함한 유틸리티인 build-essential로 다운로드를 진행합니다.
- 이후 `gcc file.c && ./a.out`으로 코드를 실행하여 동작하는 지 확인합니다.

## IDE 세팅 (Optional)
> 해당 설정은 선택사항으로 편한 개발을 위해 권장됩니다.
- Visual Studio Code 설치 후 Docker / Remote 관련 Extension 설치
- 이후 Attach Shell or Attach VScode 후 로컬 환경처럼 실행

<img width="576" alt="image" src="https://github.com/inu-it-ta/2024-1-datastructure/assets/108407945/46f7d372-eefc-47df-9949-e5bc6303531f">
<img width="576" alt="image" src="https://github.com/inu-it-ta/2024-1-datastructure/assets/108407945/9a9ea9f2-edd9-4161-8f42-6f2aef27c737">
