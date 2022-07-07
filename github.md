### GIT

git설치 후 local - git 연결시킬때 최초 1회입력  
  + `git config --global user.name <user_name>` : username  
  + `git config --global user.email <email>`    : email
  + `git config --global -l`                    : 입력확인

Repo생성 후 localwd랑 연결
  + `git init`: Repo를 만들고 wd 연결시켜줄때 최초 1회
  + `git remote add origin <Repo 주소>`: WD-Repo 연결
  + `git remote -v` : 리모트가 확인

commit
  + `git status`: wd 변경사항 확인
  + `git add .` : 전체 다 staging area로 올리기
  + `git add <파일명.확장자>`: 선택파일 올리기
  + `git commit -m "<commit message>"`: 커밋 메세지 작성
  + `git log --oneline`: 커밋내용 확인
  + `git push origin <branch>`: github push

brabch  
+ `git branch` : 브랜치의 종류, 어느 브랜치인지 확인하기
+ `git branch <branch>`:  브랜치 생성
+ `git checkout <branch>` : 브랜치 이동
+ `git merge <branch>` : 브랜치 병합
+ `git clone <레포주소>` : 그대로 복제

fork  

gitignore  
[gitignore 생성](https://www.toptal.com/developers/gitignore/)
+ `*.txt`  
  확장자가 txt인 파일 무시

+ `!test.txt`  
  현재 확장자가 txt인 파일이 무시되지만, 느낌표를 사용하여 test.txt는 무시하지 않음

+ `/TODO`  
  현재 디렉터리에 있는 TODO 파일은 무시하고, folder/TODO 처럼 하위 디렉터리에 있는 파일은 무시하지 않음

+ `build/`  
  디렉터리에 있는 모든 파일은 무시

+ `folder/*.txt`  
  folder/notes.txt 파일은 무시하고 folder/child/arch.txt 파일은 무시하지 않음
+ `folder/**/*.pdf`  
  older 디렉터리 아래의 모든 .pdf 파일을 무시





