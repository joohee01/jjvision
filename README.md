## project
# DHT senser install
```
git clone https://github.com/adafruit_Python_DHT.git
cd Adafruit_Python_DHT
sudo python setup.py install
cd examples
```
- run
```
python AdafruitDHT .py 11 4
```
## InfluxDB Installation < Influx = 파일을 생성 (공간 확보)>
## 1.Repository의 GPG key를 더하기
```
curl -sL https:/repos.influxdata.com/influxdb.key | sudo apt-key add -
```
## 2.Repository를 더하기
```
echo "deb https://repos.infulxdata.com/debin stretch stable" | sudo tee /etc/pat/sources.list.d/influxdb.list
```
## 3.프로그램 설치
```
sudo apt update
sudo apt install influxdb
```
## 4.프로그램 실행
```
sudo servixe influxdb start
```
## 5.데이터 베이스 만들기
```
> create database <데이터베이스이름>
```
### 기본 디렉토리 명령어
```
ls - 현재 경로 파일 리스트
cd - 디렉토리 변경
mkdir - 디렉토리 생성
pwd - 현재 디렉토리
cp - 파일 혹은 폴더 복사
mv-파일 혹은 폴더 이동
rm- 파일 및 폴더 삭제
cat-파일의 내용 출력 또는 파일 여러개를 합쳐서 하나의 파일 만들기
```
### 운영 관련 명령어
```
ps -aux 현재 실행중인 프로세스
netstat - tnl 현재 사용중인 tcp 포트
uft 방화벽 설정
history 명령어 history
apt-get 소프트웨어 설치/제거
sudo 슈퍼유저권한 대행
su 유저 변경
vim 편집기
```
### git 명령어
```
git clone https://github.com/kimmingyu94/yoga  (명령어 git clone) 저장소 복사
  git commit 변경사항 컴퓨터에 저장
  git push
  git add
  git rm
  git config
```
### 깃허브 불러오는 방법
```
vim .vimrc <vim 편집설정하는 곳으로 들어가기
set nu //line number
set cindent // c문법에 맞게
set ts=4 //탭 눌렀을 경우 스페이스바 4번이랑 동일하게 설정
if has("syntax") //syntax on
  syntax on
endif
```
### vim 편집기 사용법
```
vim .vimrc <vim 편집설정하는 곳으로 들어가기
set nu //line number
set cindent // c문법에 맞게
set ts=4 //탭 눌렀을 경우 스페이스바 4번이랑 동일하게 설정
if has("syntax") //syntax on
  syntax on
endif
```
### vim 설정코드(vim설정 들어가는 법 = vim.vimrc)
```
set softtabstop=4
set bg=dark
set expandtab
let python_version_2 =1
let python_highlight_all=1
filetype id:ent plugin on
```
### vim 설정에서 자주 쓰이는 것 
```
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
