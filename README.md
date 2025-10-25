# AI응용제어 git repository

**git 수업에서 배운 명령어 정리**
--------------------------------
<https://github.com/0vec/AI_application_control/blob/main/README.txt>


*<u>과제 수행 절차</u>*
=======================

1. Github에 예시를 참고해서 public repository 생성

2. 로컬 repository 생성 후 README.txt파일 작성 
    로컬 저장소의 파일탐색기에서 git bash 실행해
    git init

3. add-commit-push (변경사항 반영) 수행
    git add README.txt 
    git commit -m "Initialization"
    git remote add origin https://github.com/0vec/AI_application_control.git
git branch -M main
git push -u origin main
    git push

4. hot_fix 새 브랜치 생성후 원격저장소에 반영
    git branch hot_fix
    git push origin hot_fix

5.  hot_fix브랜치에서 README.txt수정후 반영
    git switch hot_fix
    vi README.txt
    git add README.txt
    git command
    git push origin hot_fix

6. master 브랜치와 hot fix 브랜치 병합 후 반영
    git switch main
    git merge hot_fix
    git add README.txt
    git command
    git push
