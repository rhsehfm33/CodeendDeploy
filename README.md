## About project

### What is this project?
This project supports online judge system. So, if the administartor created the algorithm problem, users can solve it. If user submitted the code, the judge server will check whether it can pass the test cases or not. These are so far that had already developed in open source. </br>
[Open Source](https://github.com/QingdaoU/OnlineJudge)


### The features we added
* Firstly, all the features are implemented additionally based on the open source.
* We applied Korean translation of this project in every GUI component.
* We added board function which is for discussing about problems or any other topics.

### Link of repository our team has been implementing
[Codeend](https://github.com/rhsehfm33/Codeend)

</br>

## How to Deploy

### Linux (Ubuntu 18.04 LTS)

1. Install programs needed for lauching services

    ```bash
    sudo apt-get update
    sudo apt-get install -y vim python3-pip curl git
    pip3 install --upgrade pip
    pip3 install docker-compose
    sudo apt-get install docker-compose
    ```

2. Install docker

    Install using script: 
    ```bash
    sudo curl -sSL get.docker.com | sh
    ```
    Other installation methods: [https://docs.docker.com/install/](https://docs.docker.com/install/)

3. Clone this repository and move to the project folder

    ```bash
    sudo git clone -b master https://github.com/rhsehfm33/CodeendDeploy.git && cd CodeendDeploy
    ```

2. Launch applications

    ```bash
    sudo docker-compose up -d
    ```

At first, this might take few minutes for lauching.

You can use the website with ports 80, 433.

The path of admin page is '\[domain-name\]/admin'.

Default ID and PW of root user are same as below:</br>
&nbsp;&nbsp;&nbsp;&nbsp;ID: root</br>
&nbsp;&nbsp;&nbsp;&nbsp;PW: rootroot

Please change the password of root user later.