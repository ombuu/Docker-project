# Docker-project

![docker 아키텍처](https://user-images.githubusercontent.com/77061427/224256479-09f81f89-eaa5-453c-8682-48301204f8a4.png)

## 프로젝트 기간
2023.02.15 - 2023.03.05

## Environment

### AWS EC2 VM : Ubuntu Linux 18.04
Docker 20.10.12
JAVA 11.0.18

### AWS EC2 VM #1

- Jenkins 서버용 AWS EC2 VM 생성 및 접근 허용
- Instance Type : t3.medium (2Core/4GB Mem/30GB EBS)

### AWS EC2 VM #2

- Nexus용 AWS EC2 VM 생성 및 접근 허용
- Instance Type : t3.medium (2Core/4GB Mem/30GB EBS)

### AWS EC2 VM #3

- 컨테이너 배포서버 AWS EC2 VM 생성 및 접근 허용
- Instance Type : t3.micro (2Core/1GB Mem/8GB EBS)

