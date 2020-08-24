# Study History
공부 일지를 기록하는 곳 입니다.

각자 개인 폴더를 만들고 공부한 내용을 정리하시면 됩니다.

## User list

### 1. [Madfalc0n](Madfalc0n/)

### 2. [Headbreakz](Headbreakz/)

## 업로드 방법

### 1. Github 계정 생성하기

### 2. `SSH Key` 등록

   ```
   ssh-keygen 입력 후 엔터 연발
   $ ssh-keygen 
   
   # "~/.ssh/id_rsa.pub" 의 내용을 복사해서 github account setting 에 SSH & GPG 항목에 추가
   $ cat ~/.ssh/id_rsa.pub
   ```

### 3. Git 환경 설정

   - `git config` 명령어를 통해 사용자 이름, 이메일을 등록합니다.

     ```
     $ git config --global user.name "깃허브 name"
     $ git config --global user.email "깃허브 Email"
     
     git config --gloabl list를 통해 설정내역 확인 가능
     $ git config --global --list
     user.name=madfalc0n
     user.email=chadool116@naver.com
     ```

### 4. Fork the repository

- github 우측 상단 Fork 버튼 클릭

### 5. Clone and setup the forked repository

- Local에 Clone 및 업데이트 사항을 가져오기 위한 upstream 생성

  ```
  $ git clone https://github.com/{아이디}/study_history.git
  $ git remote add upstream https://github.com/madfalc0n/study_history.git
  ```

### 6. 변경 사항을 본인 repository에 적용 후 Pull request 요청하기

- 업데이트 한 내역을 본인의 repository에 업로드 후 pull request 버튼을 눌러 요청하기 