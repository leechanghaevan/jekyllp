---
layout: post
title: "Git commands"
date: 2020-12-25 00:56:08 +0900
categories: tools
---

빈 리포지토리 생성 [^git-guide]
`git init`

복제 리포지토리 생성11
`git clone URL`

스테이징 (업데이트된 파일 모두 추가)
`git add .`

스테이징 영역에 추가된 내역 조회
`git status`

커밋
`git commit -m "메세지"`

직전 커밋과 하나의 커밋으로 합침
`git commit --amend`

브랜치를 main으로 바꿀경우 (기본은 master)
`git branch -M main`

브랜치 생성 및 갈아타기
`git checkout -b [MY_BRNACH]`

브랜치 변경 (마스터로 돌아오기)
`git branch master`

원격 저장소 주소 확인 (현재 연결된)
`git remote -v`

새 원격 저장소 연결
`git remote add origin https://github.com/leechanghaevan/jekyllp`

현재 유저 이름 조회/변경
`git config user.name`
`git config user.email`
`git config --global user.name "myname"`
`git config --global user.email castepo@gmail.com`

사용하지 않는 깃허브 계정 지우기
`제어판 - 사용자계정 - Windows자격증명 - github 관련 삭제`

푸시 (origin의 master 브랜치에)
`git push origin [MY_BRNACH]`
`git push origin master`

풀 (업데이트)
`git pull`

현재 브랜체 다른 브랜치 병합
`git merge [MY_BRNACH]`

깃 히스토리 보기 (종료는 q)
`git log --oneline`

롤백 (커밋 취소)
`git reset --soft`

롤백 (변경사항 삭제)
`git reset --hard`

현재 브랜치 확인
`git branch`

새 브랜치 생성
`git branch branch2`

새 브랜치로 전환
`git checkout branch2`

새 브랜치에 푸시
`git push origin branch2`

vscode에서 깃허브에 push할 때 마다 크래덴셜을 물어보는 경우
`git config --global credential.helper wincred`

---

참고

[^git-guide]: https://rogerdudler.github.io/git-guide/index.ko.html
