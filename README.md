## 리눅스 배포 방법

+ System: Ubuntu 18.04 LTS

1. 주요한 디팬던시 설치

    ```bash
    sudo apt-get update
    sudo apt-get install -y vim python3-pip curl git
    pip3 install --upgrade pip
    pip install docker-compose
    ```

2. 도커 설치

    Install using script: `sudo curl -sSL get.docker.com | sh`

    Other installation methods: [https://docs.docker.com/install/](https://docs.docker.com/install/)

## 설치

1. 깃으로 코드를 다운 받은 후, 해당 폴더로 이동

    ```bash
    git clone -b 2.0 https://github.com/rhsehfm33/CodeendDeploy.git && cd CodeendDeploy
    ```

2. 서비스 시작

    ```bash
    docker-compose up -d
    ```

처음 도커를 실행해서 구성할 시에, 최대 2분의 시간이 소요될 수 있습니다.

브라우저를 통해 80 또는 443 포트로 접속해서 해당 서비스를 이용할 수 있습니다.
관리자의 경로는 '/admin' 입니다.
기본 관리자의 아이디는 'root' 이고, 비밀번호는 'rootroot' 입니다.
로그인 성공시 바로 관리자의 비밀번호를 바꿔주세요.