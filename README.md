# git


git



## <명령어>
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin 폴더 명
git push -u origin main

pwd - 현재 폴더 위치

ls - 현재 폴더에 어떤 파일이 있는지 확인하고 싶을 때
	- ls -al 숨김 파일 까지 보여주기

cd 
- 폴더 바꾸기 cd "파일 위치"
- 파일 위치 이동 cd 폴더/
- 상위 폴더로 올리기 - cd ..
- 내가 원하는 폴더 바로가기 cd ../가고자하는 폴더/

git add . - 모든 파일 추가하기

git branch -M main - 브랜치 생성

지우기 - rm -rf [폴더명]/

## <git add & commit>

커밋 = 하나의 버전

커밋으로 만들길 원하는 파일만 선택 : add

폴더 추가 : add [폴더]/

모든 파일 올리기 : add .




## <git remote add & push>

내 컴퓨터 프로젝트 폴더에 github 저장소 주소 알려주기 git remote add [변수] github Repositories (파일 위치)

내 컴퓨터에 만들었던 덩어리 github에 올리기 git push 변수 master

<git clone, 원격 저장소를 내 컴퓨터에 받아오기>

1. 내 컴퓨터에 아무 폴더를 만들고 github의 내가 가져오고 싶은 저장소 받아오기

git clone https://github.com/아이디/이름.git

git clone https://github.com/아이디/이름.git . -> 현재 폴더에서 받아오기

2. 업데이트 된 데이터 가져오기 : pull
git pull origin main

