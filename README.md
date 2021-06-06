# Team tteokbok.com

## 👩‍🏫 PROJECT 소개

다양한 분야의 창작자와 후원자를 이어주는 펀딩 커뮤니티 사이트인 텀블벅을 모티브로, 분식의 다양한 메뉴를 소개하고 후원할 수 있는 사이트를 기획했습니다. 

### **프로젝트 소개**

- 분식을 라면, 떡볶이, 김밥, 튀김, 순대인 다섯가지 카테고리로 나누어 다양한 메뉴를 소개합니다.
- 유저는 자신의 독특한 메뉴를 소개하고 후원받아 메뉴를 런칭 할 수 있습니다.
- 누구나 자신만의 메뉴를 소개하고 글을 올릴 수 있습니다.

### **프로젝트 계획 및 일정**

🗓️ **작업기간** : 2021.05.23 ~ 2021.06.04

- 1st Sprint : 전체 레이아웃, 공통 컴포넌트 구현 및 공유
- 2nd Sprint : 컴포넌트 별 기능 구현, 프론트-백 통신, conflict 수정 작업

📒 **주요업무** 

- 소셜 로그인을 이용한 로그인 및 회원가입
- 공동 컴포넌트 중 하나인 버튼 컴포넌트 제작
- 카테고리, 신제품, 마감일 등에 따라 프로젝트를 검색할 수 있는 필터기능 구현
- 반응형 레이아웃 구현
- 로그인 시 유저 정보가 나타나는 공동 헤더(네브바) 구현
- path parameter를 이용한 메인 및 리스트 페이지와의 동적 라우팅

> ## 😎 Our Website : http://tteokbok.com/
>
> ## 📎 Route Path
>
> - / : 메인페이지
> - /detail/:id : 상세페이지
> - /project-start : 프로젝트 등록페이지
> - /profile : 마이페이지

## 👫 팀원

- FE 3인: [노선경(PM)](velog.io/@celline1637), [송가람](velog.io/@sgr2134), [임유진(SM)](velog.io/@1703979)
- BE 2인: [이승무](https://goback.oopy.io/), [최준식](https://velog.io/@junsikchoi) ([BE Reop](https://github.com/wecode-bootcamp-korea/20-2nd-tteokbokcom-backend))


## 🔧 Skills

- FE : React, React Hooks, React Router, Styled-Components, AWS S3
- BE : Django, Docker, AWS S3

## 👍🏻 구현 기능 상세

### 1. 이메일/소셜 로그인&회원가입&로그아웃

- 카카오 소셜로그인 & 회원가입 (OAuth2.0)
- 이메일 로그인

### 2. 프로젝트 등록

- s3 서버로 FormData 전송
- input, textarea 등 폼 입력시 유효성 검사

### 3. 프로젝트 리스트 (메인 화면)

- 다중 filter, sorting 기능 구현
- 검색창 검색 기능 구현 및 filter, sorting과 연결
- 좋아요 기능 메인-상세-유저 페이지 연결

### 4. 프로젝트 상세 페이지

- 메인 - 상세 - 유저 페이지 동적 라우팅
- 프로젝트 후원 (밀어주기) 기능 :후원 성공시 유저페이지에 정보 저장
- 스크롤 애니메이션 구현

### 5. 나의 관심/후원 프로젝트 확인

- 좋아요/후원한 프로젝트 확인
- 좋아요/후원한 프로젝트 검색 기능
