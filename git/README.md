## Git 필수 명령어
### `rm -r .git` 기존 git 환경 제거
### `git init` git 환경 세팅
### `git remote add origin {URL}` git remote 추가
### `git add *` 모든 파일 추가
### `git commit -m ""` 추가한 파일 커밋
### `git commit -am ""` 추가와 커밋을 동시에 진행
### `git push origin master` Github에 코드 올리기
### `git pull origin master` 변경된 사항을 가져오기 (안가져오면 에러남)
### `git pull origin master --allow-unrelated-histories` pull로 안가져와질경우 이 코드를 쓰면 되지만 비추
### `git status` 현재 상태 출력
### `git log` 현재까지 커밋을 보여줌
### `git branch` 현재 branch 출력
### `git branch {BranchName}` 새 branch 추가
### `git branch -d {BranchName}` branch를 로컬에서 제거
### `git push origin --delete {BranchName}` branch를 리모트에서 제거
### `git checkout {BranchName}` branch 변경
### `git merge {BranchName}` 현재 branch로 해당 branch를 연결, 같은 줄의 코드가 다르면 충돌이 생김
### `git config --global user.name "{UserName}"` 사용자의 이름 설정
### `git config --global user.email "{UserEmail}"` 사용자의 이메일 설정
