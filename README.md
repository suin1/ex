# 수업 내용 #

## git 명령어 ##

#### git config --global user.name "xxxx" ####
-사용자명 등록

#### git config --global user.email "xxxx@naver.com" ####
-이메일 등록

#### git init ####
-현재 폴더를 메인으로 하여 관리 (초기화)

#### touch 파일명 ####
-폴더에 파일생성

#### git add 파일명 ####
-git에 생성한 파일추가

#### git commit -m "파일 설명" ####
-git add한 내용을 설명하는것

#### git status ####
-현재 상태 확인

#### git log ####
-커밋한 모든 이력 확인
#### git log --oneline ####
-커밋한 모든 이력을 간단히 확인 (제목만)

## github ##

-**your repositories** 에서 new를 눌러 Repository name에 저장소 이름 입력 후 
 다음으로 넘어가면 뜨는 보기와 같이
 생성된 폴더에서 **git bash**를 열어 위 git 명령어를 **git init** 까지 한 후
 **touch**명령어로 "README.md" 파일 생성 후 다시 git명령어 
 **git add 파일명** 과 **git commit -m "파일설명"** 까지 해줄것 
 여기까지 한 후 github에 연결을 해야하는데 그 명령어가

### git remote add origin https://github.com/사용자명/저장소이름.git ### (보기에 뜸)
- README 파일을 온라인 저장소에 연결을 시켜줌
  이후 연결을 하면 온라인 저장소에 백업을 시켜줘야 하는데 그 명령어가

### git push -u origin main ###
- README 파일이 온라인 저장소에 연결이 되어 README 파일의 내용과
  커밋한 내용이 온라인 저장소에도 표기됨


