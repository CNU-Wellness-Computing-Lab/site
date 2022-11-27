# 인간-컴퓨터 상호작용 연구실 홈페이지

충남대학교 인간-컴퓨터 상호작용 연구실 홈페이지입니다.
Jekyll 기반으로 생성되었습니다.

# 문서편집
홈페이지 컨텐츠를 추가하거나 수정하는 방법

## Introduction
메인페이지의 introduction 내용을 수정하려면
**index.md** 파일의 내용을 수정해주세요.

## Research
**_data/research.yml** 파일에 내용을 작성합니다.
\- {name: '프로젝트 예시', author: '프로젝트참여자', publication: 'publication', url: '참고 링크', image: '이미지 파일 경로'}
이미지 파일은 assets/project_img/ 에 저장합니다.

## Publication
**_data/publication.yml** 파일에 내용을 작성합니다.
**feature:** 에는 메인화면 게시할 내용
**index:** 에는 publication페이지에 게시할 내용을 작성

## TEAM
**_data/settings.yml** 파일에 **team:** object아래에 작성
프로필 사진은 assets/team_profile/ 에 저장

## NEWS
**_posts** 폴더에 **년-월-일-문서제목.md** (예: 2022-11-20-first.md) 형식으로 파일 저장
.md 파일의 상단부에
\-\-\-
layout: post
title: "문서제목"
\-\-\-
내용을 추가해주세요! layout은 반드시 post로 해야합니다.