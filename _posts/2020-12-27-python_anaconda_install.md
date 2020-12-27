---
layout: post
title: "Python & Anaconda install"
date: 2020-12-27 23:09:31 +0900
categories: tools
---

#### 윈도우에 아나콘다 (파이썬 + 라이브러리) 설치

- 아나콘다 사이트에서 설치파일 다운로드[^download]
- 또는 파워셀을 관리자 권한으로 실행 후 아래 실행
  `choco install anaconda3`
- 설치할 때 반드시 **환경변수 등록**을 체크해 준다.[^venv]

#### 파이썬 가상 환경 생성 (기본 가상환경 이름은 base)

- Anaconda Powershell 을 연다
- 아나콘다 업데이트
  `conda update conda`
- 가상환경 목록 조회
- `conda env list`
  가상환경 생성
  `conda create -n [MY_ENV]`
- 현재 가상환경 활성화
  `conda activate [MY_ENV]`
- 현재 가상환경 비활성화
  `conda deactivate [MY_ENV]`

#### 클라우드형 환경

- Datalore, Colab 등을 사용하면 설치 없이 온라인으로 파이썬(+주피터노트)을 이용할 수 있다.[^datalore][^colab]

---

참고

[^download]: [Anaconda Download](https://docs.anaconda.com/anaconda/install/)
[^venv]: 환경변수 등록해 주지 않으면 Anaconda Powershell에서만 파이썬이 작동한다.
[^datalore]: [Datalore](https://www.anaconda.com/datalore_navigator)
[^colab]: [Colab](https://colab.research.google.com/notebooks/intro.ipynb)
