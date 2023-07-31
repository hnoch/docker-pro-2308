# 사전 미션

## 1. 컨테이너 기술이란 무엇입니까?
컨테이너 기술은 호스트 OS 상에서 독립된 논리적인 구획을 생성하는 기술입니다. 이 구획 안에는 어플리케이션을 작동시키기 위한 모든 환경이 구축되며, 별도의 서버인 것처럼 사용될 수 있습니다. 컨테이너는 운영체제 수준에서 가상화를 진행하여 시작이 빠르고, 전체 운영체제를 부팅하는 것보다 메모리를 적게 차지합니다.

## 2. 도커란 무엇입니까?
도커는 컨테이너 기술을 구현한 대표적인 소프트웨어로, 애플리케이션과 그 종속성을 컨테이너로 패키징하여 격리된 환경에서 실행합니다. 도커는 이 컨테이너를 모듈식 가상 머신처럼 사용하여 환경 구축과 배포가 간편하며, 클라우드 환경에 최적화되어 있습니다.

## 3. 도커 파일, 도커 이미지, 도커 컨테이너의 개념은 무엇이고, 서로 어떤 관계입니까?
도커 파일(Dockerfile): 도커 이미지를 생성하기 위한 설정 파일입니다. 애플리케이션의 구성과 실행 환경을 정의하며, 컨테이너화할 때 필요한 명령어들을 기술합니다.

도커 이미지(Docker Image): 도커 파일을 기반으로 생성된 실행 가능한 패키지입니다. 서비스 운영에 필요한 서버 프로그램, 소스코드, 라이브러리, 컴파일된 실행 파일 등을 포함합니다.

도커 컨테이너(Docker Container): 도커 이미지를 실행한 상태, 즉 프로세스의 인스턴스입니다. 응용 프로그램과 그 종속성을 패키징하여 격리된 환경에서 실행합니다.

도커 파일은 도커 이미지를 만들기 위한 설정 파일이며, 이 도커 파일을 바탕으로 도커 이미지가 생성됩니다. 그리고 이 도커 이미지는 실제로 도커 컨테이너를 실행하는 데 사용됩니다. 즉, 도커 파일 -> 도커 이미지 -> 도커 컨테이너 순서로 사용되며, 하나의 이미지로부터 여러 개의 컨테이너 인스턴스를 생성할 수 있습니다.

## 4. [실전 미션] 도커 설치하기
- 붙임