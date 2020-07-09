Install DHT11 senser

git clone https://github.com/adafruit/Adafruit_Python_DHT.git
cd Adafruit_Python_DHT
sudo python setup.py install
cd examples
```
run
```
python AdafruitDHT.py 11 4

InfluxDB Installation
```
## 1. Repository의 GPG key를 더하기
curl -sL https://repos.influxdata.com/influxdb.key | sudo apt-key add -
```
## 2. Repository를 더하기
echo "deb https://repos.influxdata.com/debin stretch stable" | sudo tee /etc/apt/sources.list.d/influxdb.list
```
## 3.프로그램 설치
sudo apt update
sudo apt install influxdb
```
## 4.프로그램 실행
sudo service influxdb start
```
## 5.데이터베이스 만들기
>create database <데이터베이스이름>
확인 : show databases
`````
`````
Grafana Installation
## 1.Repository의 GPG key를 더하기
curl https://bintray.com/user/downloadSubjectpublickey?username-bintray | sudo apt-key add-
```
## 2.Repository를 더하기
echo "deb https://dl.bintray.com/fg2it/deb stretch main" | sudo tee -a /etc/apt/sources.list.d/grafana.list
```
## 3.프로그램 설치
sudo apt update
sudo apt install grafana
```
## 4.프로그램 실행
sudo service grafana-server start
```
influxdb inport with python
sudo pip install influxdb
`````
####git hub 사용방법
 - Repository done load
 ```
 git clone https://github.com/<joohee01>/<repository name>
 ```
 기본 디렉토리 명령어
 ls 현재경로 파일 리스트 
px-aux 현재 실행중인 프로세스
apt-get 소프트웨어 설체/제거
cd 디렉토리 변경
netstat ps
````
#### vim 설정에서 자주 쓰이는 것(vim설정 들어가는 법=vim .vimrc)
set number = 번호 표시
set ai = auto indent
set si = smart indent
set cindent = c style indent
set shiftwidth=4 = 자동 공백 채움 시 4칸
set tabstop=4 = tab을 4칸 공백으로
set ignorecase = 검색 시 대소문자 무시
set hlsearch = 검색 시 하이라이트
set nocompatible = 방향키로 이동 가능
set fileencodings=utf-8,euc-kr = 파일 저장 인코딩 : utf-8, euc-kr
set fencs=ucs-bom,utf-8,euc-kr = 한글 파일은 euc-kr, 유니코드는 유니코드
set bs=indent,eol,start = backspace 사용가능
set ruler = 상태 표시줄에 커서 위치 표시
set title = 제목 표시
set showmatch = 다른 코딩 프로그램처럼 매칭되는 괄호 보여줌
set wmnu = tab 을 눌렀을 때 자동완성 가능한 목록
syntax on = 문법 하이라이트 on
filetype indent on = 파일 종류에 따른 구문 강조
set mouse=a = 커서 이동을 마우스로 가능하도록
