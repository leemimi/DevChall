# DevChall

개발자를 위한 개발 챌린지 플랫폼, **데브챌(DevChall)**

<img width="908" alt="스크린샷 2023-06-09 오전 1 23 24" src="https://github.com/Lion-Project15/DevChall/assets/82140052/f59a42b7-081e-4599-bb5b-3fdd26bd120c">


## 프로젝트 소개

개발자가 되기 위해 같은 목표를 가진 다양한 사람들과 함께 혹은 스스로의 역량을 최대치로 끌어올리기 위한   
**데브챌의 개발 문화**를 소개합니다.


개발에만 집중할 수 있는 환경에서.  
개인, 학생, 직장인 등 개발에 집중하고 싶은 누구나.  
서로에게 긍정적인 자극을 주고받으며 원하는 목표를 향해 끊임없이 도전하는 개발 문화를 제공해 줍니다.  
더불어 포인트를 쌓는 재미까지 두 마리의 토끼를 잡을 수 있는 서비스, 데브챌입니다.  

### ✨ What?
- 챌린지를 통해 개발하는 습관을 들일 수 있습니다  
- 원하는 챌린지를 개설하고 여러 사람과 같이 할 수 있습니다  
- 상호 소통이 가능하기에 다른 유저의 응원을 받으며 끝까지 완주할 수 있습니다  
- 포인트를 모아 다양한 챌린지를 참여하며 기회의 폭을 넓히고, 아이템을 꾸미는 재미를 경험할 수 있습니다  
 
## 개발기간
- 2023년 05월 22일 ~ 2023년 06월 16일

## 팀원  
- 팀장 : 이미정
- 팀원 : 김성훈, 박채원, 양혜정, 이명준

<img width="908" alt="스크린샷 2023-06-09 오전 1 17 08" src="https://github.com/Lion-Project15/DevChall/assets/82140052/101129e9-a0de-4497-8376-026ca0d77df7">

## 🔧 Tools 
- JAVA 17
- Gradle
- Database - MariaDB
- SpringBoot
- SpringDataJPA - QueryDSL
- Junit5
- SpringSecurity
- Nginx
- Docker
- Jenkins (CI/CD)
- NaverCloudPlatform
- Timeleaf
- Tailwind, DaisyUI

## 테이블 (다이어그램)
- ![devchall__deva](https://github.com/Lion-Project15/DevChall/assets/39723465/885ba606-9166-4bde-9032-63ac5e8b9199)


## 사이트
https://www.devchall.site/

##  💻  프로젝트 설명 (주요 기능)

<table align="center">
  <tr>
    <th><code>메인 페이지</code></th>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/f91485b8-ce47-4062-991e-e7064137cd75" width="540" alt="메인 페이지"/></td>
  </tr>
</table>

<table align="center">
  <tr>
    <th><code>챌린지 생성, 참여</code></th>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/419f632a-bab7-4d31-a0f0-fb94fd549605" width="540" alt="챌린지 생성, 참여"/></td>
  </tr>
</table>

<table align="center">
  <tr>
    <th><code>챌린지 인증</code></th>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/30dca25c-76bf-4e68-a795-2f749ce02938" width="540" alt="챌린지 인증"/></td>
  </tr>
</table>

<table align="center">
  <tr>
    <th><code>마이페이지</code></th>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/8b38ef9d-58a5-4940-89af-e66f797f8114" width="540" alt="마이페이지"/></td>
  </tr>
</table>

<table align="center">
  <tr>
    <th><code>내부 상점</code></th>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/1915340f-cb8a-491f-bc10-74389206c2f9" width="540" alt="내부 상점"/></td>
  </tr>
</table>

회원가입/로그인
 1. 기본 회원가입 및 로그인
 2. 소셜 (네이버, 카카오) 회원가입 및 로그인
 3. 유효성 검증

메인 페이지
 1. DevChall에대한 전체적인 Guidline
 2. 태그(카테고리)를 통한 필터링
 3. 챌린지별 참여 인원이나, 참여 현황, 제목, 태그 등을 표시

챌린지
 1. 챌린지 생성 및 제약조건
 2. 챌린지 대표 이미지 등록
 3. 챌린지 참여
 4. 챌린지 관련 가이드라인 제공

챌린지 포스트(인증글)
 1. 챌린지 인증글 작성
 2. 포스트 이미지 등록
 3. 자기평가(별점)등록
 4. 댓글 기능을 통한 소통
 5. 인증글 수정 및 삭제
 6. 인증글 신고기능, 강퇴기능

정산 기능
 1. 달성률 체크(인증글 작성은 여러개 가능하지만, 하루의 하나의 인증글만 정산에 반영 가능)
 2. 인증글 1개당 1포인트 지급
 3. 챌린지 완수시, 챌린지에 모인 포인트를 정산 조건을 달성한 멤버들에게 1/n 지급
 4. 정산 조건 : 최종 달성률이 90% 이상인 멤버들
 5. 어드벤티지 : 챌린지 개설자 7%, 일반 멤버 5%

마이페이지
 1. 닉네임 변경
 2. 나의 챌린지 목록 및 현황
 3. 인벤토리 - 상점에서 구매한 폰트 및 캐릭터 적용
 4. 포인트 현황

내부상점
 1. 나의 아이템, 포인트 표시
 2. 폰트 테마와 프로필 캐릭터 구매 가능
 3. 구매한 아이템들은 실제로 외부로 노출 가능, 사이트 내의 곳곳의 색상이 변경됨
    
