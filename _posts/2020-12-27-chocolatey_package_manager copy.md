---
layout: post
title: "Chocolatey package manager"
date: 2020-12-27 05:29:12 +0900
categories: tools
---

**Choco**는 윈도용 패키지 매니저. 리눅스의 apt, yum 같은 역할

##### 설치

관리자 권한으로 파워셀 실행 후 아래 명령어 실행

```bash
Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```

##### 추천 프로그램 목록

`choco install git -y`
`choco install nodejs -y`
`choco install yarn -y`

##### 패키지 삭제

`choco uninstall 패키지이름 -y`

##### 최신 버전으로 업데이트

`choco upgrade 패키지이름 -y`

##### 설치된 목록 확인

`choco list --localonly`

---

##### Jekyll 설치

루비 설치
`choco install ruby -y`

파워셀을 따로 열고
`gem install bundler`
`gem install jekyll`

지킬 블로그 생성
`jekyll new PATH` and `cd PATH`

지킬 실행
`jekyll s`

지킬 빌드
`jekyll b`

실행 에러시 아래 명령어 수행 후 시도
`bundle install`
