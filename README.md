# Study History
공부 일지를 기록하는 곳 입니다.

각자 개인 폴더를 만들고 공부한 내용을 정리하시면 됩니다.

## User list

### 1. [Madfalc0n](Madfalc0n/)

### 2. [Headbreakz](Headbreakz/)

### 3. [roche-MH](roche-MH/)

### 4. [HDLY](HDLY/)

### 5. [water-lilies](water-lilies/)

### 6. [Dalmatian](Dalmatian/)

## 0. Git 계정 생성 및 환경 설정

1. Github 계정 생성하기

2. `SSH Key` 등록

   ```
   ssh-keygen 입력 후 엔터 연발
   $ ssh-keygen 
   
   # "~/.ssh/id_rsa.pub" 의 내용을 복사해서 github account setting 에 SSH & GPG 항목에 추가
   $ cat ~/.ssh/id_rsa.pub
   ```

3. Git 환경 설정

   - `git config` 명령어를 통해 사용자 이름, 이메일을 등록합니다.

     ```
     $ git config --global user.name "깃허브 name"
     $ git config --global user.email "깃허브 Email"
     
     git config --gloabl list를 통해 설정내역 확인 가능
     $ git config --global --list
     user.name=madfalc0n
     user.email=chadool116@naver.com
     ```

## 1. 원격 repository Fork 및 Clone

1. Fork the repository

   - github 우측 상단 Fork 버튼 클릭

2. Clone and setup the forked repository

   - Local에 Clone 및 업데이트 사항을 가져오기 위한 upstream 생성

     ```
     $ git clone https://github.com/{아이디}/study_history.git
     $ git remote add upstream https://github.com/madfalc0n/study_history.git
     ```

## 2. 변경사항 작성 후 Update

1. 변경사항을 만들때는 현재 master branch에서 새로운 branch를 만들어 수정 사항을 반영하여 Push 한다.

   ```
   $ git checkout -b {ID_날짜}
   # ... README 업데이트 ...
   $ git add {수정한 파일들}
   # Commit message 작성 및 sign off
   $ git commit -m "업데이트 내용"
   $ git push origin {checkout을 통해 생성한 브랜치이름(ID_날짜)}
   ```

2. 변경 사항을 본인 repository에 적용 후 Pull request 요청하기

   - 업데이트 한 내역을 본인의 repository에 업로드 후 pull request 버튼을 눌러 요청하기

## 3. Upstream 에서 업로드 된 사항이 적용(merge) 된 경우, local 및 개인 repository에 변경사항 병합하기

1. local에 업데이트 사항 적용하기

   ```
   $ git checkout master
   $ git pull upstream master
   ```


## 4. 병합완료 후 임시로 생성된 branch 삭제하기

1. `git branch -d {ID_날짜}`