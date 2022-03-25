# git-flow test

## Getting started
1. 설치
> brew install git-flow

2. 초기 설정
> git flow init

## Feature
1. 기능 개발
develop 브랜치에서 새로운 feature 브랜치 생성하고 checkout
> git flow feature start [기능명]

2. PR을 위한 feature 브랜치 게시
작업한 feature 브랜치를 원격 저장소에 push
> git flow feature publish [기능명]

3. 로컬에서 바로 머지할 때
작업한 feature 브랜치를 develop 브랜치에 머지하고 feature 브랜치 삭제
> git flow feature finish [기능명]

## Release
1. 릴리즈 시작
develop 브랜치에서 새로운 release 브랜치 생성하고 checkout
> git flow release start [이름]

2. 릴리즈 게시
release 브랜치를 원격 저장소에 push
> git flow release publish [이름]

3. 릴리즈 완료
release 브랜치를 main, develop 브랜치에 병합하고 태그 생성
> git flow release finish [이름]

## Hotfixes
1. 핫픽스 시작
main 브랜치로부터 새로운 hotfix 브랜치 생성하고 checkout
> git flow hotfix start [이름]

2. 핫픽스 완료
hotfix 브랜치를 main, develop 브랜치로 머지하고 태그 생성
> git flow hotfix finish [이름]

