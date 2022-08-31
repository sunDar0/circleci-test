# circleci 연동 테스트용 프로젝트
* circleci와 ecs, ecr 연동
## 순서
* 기본적인 클러스터 세팅과 서비스, 테스크 설정 완료
* circleci 해당 레파지토리 연동
* circleci 내 환경변수 설정
* circleci 컨피그 부분 구성
* 배포 테스트
---
## 느낀점
* 코드상에서 사용할 .env를 구성하는 방식에 대한 고민 필요
* 실 배포 시 dev, staging, production을 어떤 기준으로 구분해야할지 정책 있어야함 - 네트워크?, 클러스터?, 서비스?
