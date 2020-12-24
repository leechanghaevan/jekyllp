---
layout: post
title: "Git commands"
date: 2020-12-25 00:56:08 +0900
categories: tools
---

빈 리포지토리 생성
`git init`

복제 리포지토리 생성
`git clone URL`

스테이징 (업데이트된 파일 모두 추가)
`git add .`

스테이징 영역에 추가된 내역 조회
`git status`

커밋
`git commit -m "메세지"`

직전 커밋과 하나의 커밋으로 합침
`git commit --amend`

원격 저장소 연결
`git remote add origin URL`

푸시 (origin의 master 브랜치에)
`git push origin master`

풀 (업데이트)
`git pull`

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
