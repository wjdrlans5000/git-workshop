# git-workshop
git 사용 실습


1. [아침](morning.md)
2. [점심](lunch.md)
3. [저녁](dinner.md)

# git 레포지토리 연결 및 커밋 push 순서
- git init
- git add README.md
- git commit -m "first commit"
- git branch -M main
- git remote add origin https://github.com/wjdrlans5000/SpringBootStudy.git
- git push -u origin main

상세 메뉴를 보시려면 각 항목을 클릭해주세요.

# git 레포지토리 연결 
- git clone [리포지토리] : 저장소 복제
- git init
- git remote add reactLearn [url]
- git remote -v
- git pull remote reactLearn master(branch)
- git add [파일명] : 수정or추가된 부분 stage에 올리기
- git status : stage 상태확인
- git commit -m "" : 주석달아서 commit
- git push reactLearn master(branch) : 원격저장소로 push 
- git pull : git서버에서 최신 코드 받아와 merge

# git branch
- git branch branch_name : 브랜치 생성
- git branch : 브랜치 목록보기
- git checkout branch_namme  : 브랜치 선택
- git branch -m branch_name change_branch_name : 브랜치 이름 바꾸기
- git branch -d branch_name : 브랜치 삭제하기

# git folder 삭제 
- it rm -rf {파일 및 폴더명} // 모두 삭제
- git rm -r --cached {파일 및 폴더명} // 원격 저장소에 있는것만 삭제
- git commit -m "commit 내용"
- git push -u reactLearn gimun



