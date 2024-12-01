---
layout: post                            # 기본 post로 하면 됨
title: "[포트폴리오] Sassion 하루 챌린지"             # 제목 입력
date: 2024-11-27 15:22:00 +0900         # year-month-day hour:minute:second +0900     (+0900은 한국 시간)
description: 하루 챌린지 포트폴리오 # 공유할 때 표시되는 설명
img: ./haru/haru.png # 이미지    imgName.png  .jpg 등등
fig-caption: 포트폴리오 # Add figcaption (optional)
tags: [포트폴리오, 챌린지, sassion, 하루, 프로젝트, 앱, 개발]
---
# Sassion

### GitHub

- [GitHub Source code](https://github.com/leehyunsuck/Project_sassion)

### Project 소개

- 사용자들의 습관 형성과 목표 달성을 돕는 Application 입니다.
- 일상에서 꾸준히 한 개 이상 무엇이든 도전하라는 의미에서 제작하게 되었습니다.

### Used tool / Language, OS

- Android Studio
- Eclipse
- HeidiSQL
- Putty
- WinSCP

- Java
- JSP
- MariaDB
- GCP - Debian
- Apach-tomcat9

### Struct

- Application ↔ [Server(JSP ↔ DB)]
- Server :
    
    → Debian / Apach-tomcat9
    

### 담당

| **이현석** | **신수진** | **김종욱** |
| --- | --- | --- |
| GCP에 서버 구축 및 관리 (Debian Apach-tomcat9) | 메인 디지인 figma | 문의하기 xml, class, jsp, db |
| SMTP (이메일 인증) 기능 구현, xml, class | 챌린지 작성 화면 xml, class | 문의완료 xml, class, db |
| 회원가입 xml, class, jsp, db | 챌린지 작성 화면 스티커 선택 화면 xml, class | 챌린지 메뉴 xml, class |
| 로그인 xml, class, jsp, db | 챌린지 상세정보 화면 xml, class | 앱소개 xml, class |
| 비밀번호 수정 xml, class, jsp, db | 챌린지 상세정보 스티커 선택 화면 xml, class | 관리자 페이지 xml, class, jsp, db |
| 튜토리얼 xml, class | 챌린지 성공 화면 xml, class | 내정보 xml, class |
| 상점 xml, class | FAQ xml, class | 공지사항(내용) xml, class |
| 메인페이지 class | 공지사항 xml, class | 회원탈퇴시 문의 제거 class, jsp |
| 챌린지 작성 class | PPT 제작 | 관리자 페이지 연결 calss, jsp |
| 챌린지 작성 스티커선택 class |  | PPT 발표 |
| 챌린지 디테일 페이지 class |  |  |
| 챌린지 디테일 스티커선택 class |  |  |
| 로그아웃 class, jsp, db |  |  |
| 내정보 챌린지데이 표시 class |  |  |
| Q&A 답변 jsp |  |  |
| PPT 제작 |  |  |
| 시연 및 설명 |  |  |


### Image 및 설명

<div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 40px; padding: 20px;">
  <!-- 첫 번째 섹션 -->
  <div style="flex: 1; max-width: 300px; text-align: center;">
    <img src="/assets/img/haru/Register.png" style="width: 100%; border-radius: 10px;">
    <h3>회원가입</h3>
    <p>SMTP 이메일 인증을 사용하였습니다.</p>
  </div>

  <!-- 두 번째 섹션 -->
  <div style="flex: 1; max-width: 300px; text-align: center;">
    <img src="/assets/img/haru/Main.png" style="width: 100%; border-radius: 10px;">
    <h3>메인</h3>
    <p>상점에서 아이템을 구매하여 캐릭터를 꾸며줄 수 있습니다.</p>
  </div>

  <!-- 세 번째 섹션 -->
  <div style="flex: 1; max-width: 300px; text-align: center;">
    <img src="/assets/img/haru/CreateChallenge.png" style="width: 100%; border-radius: 10px;">
    <h3>챌린지 추가</h3>
    <p>사용자가 원하는 챌린지를 추가하는 기능을 제공합니다.</p>
  </div>

  <!-- 네 번째 섹션 -->
  <div style="flex: 1; max-width: 300px; text-align: center;">
    <img src="/assets/img/haru/Shop.png" style="width: 100%; border-radius: 10px;">
    <h3>상점</h3>
    <p>챌린지 진행마다 또는 완료 시 골드가 지급됩니다. 해당 골드로 캐릭터의 공간을 꾸며줄 수 있습니다.</p>
  </div>

  <!-- 챌린지 섹션 -->
  <div style="flex: 1 1 100%; text-align: center;">
    <div style="display: flex; justify-content: center; gap: 10px;">
      <img src="/assets/img/haru/ChallengeDetail.png" style="width: 30%; border-radius: 10px;">
      <img src="/assets/img/haru/ChallengeSelectSticker.png" style="width: 30%; border-radius: 10px;">
      <img src="/assets/img/haru/ChallengeDetail_(1).png" style="width: 30%; border-radius: 10px;">
    </div>
    <h3>챌린지</h3>
    <p>하루씩 본인의 상태를 스티커로 체크하며 진행합니다. 서버에서 날짜를 받기에 그 날짜가 아니면 선택할 수 없습니다.</p>
  </div>
</div>






### 아쉬운점

- Spring Framework를 사용하지 않고 JSP로 서버 통신을 구현한 점
- 코드의 재사용성, 유지보수를 고려하지 못하고 제작한 점
- 기종 별 화면에 UI를 제대로 맞추지 못한 점