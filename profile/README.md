# lazier - 맞춤형 정보 조회 서비스


## 🙆‍♂️ 팀원 소개

|![image](https://user-images.githubusercontent.com/110509654/227474208-7a5aeda4-d83d-435d-8eb7-8fe3aeb82edb.png)|![image](https://user-images.githubusercontent.com/110509654/227474343-a0324a3b-c19e-4908-9351-b755d482a8e8.png)|![image](https://user-images.githubusercontent.com/110509654/227474463-cbd8443e-2e94-497e-aaba-bf3daae21b4b.png)|![image](https://user-images.githubusercontent.com/110509654/227474545-cb17144c-b76a-4dac-a416-8284558d787e.png)|![image](https://user-images.githubusercontent.com/110509654/227474749-058806c4-6001-4725-829a-9b73c9776de1.png)|![image](https://user-images.githubusercontent.com/110509654/227474832-e3443fed-3ca3-4487-8edd-ce0f92e112e2.png)|
|:---:|:---:|:---:|:---:|:---:|:---:|
|**Front-End**|**Front-End**|**Back-End**|**Back-End**|**Back-End**|**Back-End**|
|**김태영**|**장지연**|**👑하민성👑**|**서인덕**|**윤윤성**|**이혜린**|


## 👨‍💻 프로젝트 소개

**Main Slogan - 바쁜 현대사회에서 조금 더 게으른 당신의 삶을 위해**

![lazy](https://user-images.githubusercontent.com/110509654/226874078-6931caa1-1e2c-40ba-9781-b256ababb055.gif)

**❓ 기획 배경**

![image](https://user-images.githubusercontent.com/110509654/226874233-6710d6f2-6977-4703-8dfe-7bb47b52c043.png)

* 계좌 정보를 확인하려면 은행 사이트를, 뉴스를 보려면 신문사 뉴스 사이트/어플을 방문해야 한다.
  * 하지만 해당 어플리케이션에서 보는 기능은 제한적이다. 주로 단순한 정보를 이용한다. ('오늘 날씨', '오늘 할 일', '지금 뉴스')
* 관심있는 나의 정보와 일정 등을 간편하고 한눈에 파악할 수 있는 웹 어플리케이션을 생각하게 되었다.

**☝️ 해결 컨셉 : Easy One For All**
1) 나에게 필요한 정보만 **골라서** **직관적**으로 편하게 보자
2) 간편하게 **모바일**로 볼 수 있는 웹 어플리케이션

**👨 목표: 기대 효과(USER)**
1) 여러 포털 사이트 / 앱을 사용하지 않아도 원하는 정보를 **한 페이지에서** 확인 할 수 있다.
2) **원하지 않는 정보는 보지 않도록** **모듈화된 기능을 선택**하여 나만의 입맛에 맞는 페이지를 구성할 수 있다.

**=> 최종 총 8개의 기능모듈 + 메인모듈로 구성된 모바일 웹 어플리케이션 구상.**


## 🤝 협업 과정

**🧭 Ground Rule**

**Ground Rule = Growth Rule**

> Rule : 모든 원칙은 우리의 성장과 공동의 목표 달성을 위해 존재합니다.

![image](https://user-images.githubusercontent.com/110509654/227481240-c88e37ea-ec5f-4519-beee-e207f09407ed.png)

* 스크럼 : 매일 노션 양식에 작성
* 코드리뷰 : 주 2회 (요일 미정) / 개발기간은 백엔드, 프론트 파트별로 진행
* 회의시간 : 월~금 / 일요일 오후 10시
* 특이사항 : 매주 토요일은 회의 X, 텍스트로 작업내용 공유

**💼 Work Time**

![image](https://user-images.githubusercontent.com/110509654/227482173-8cc566b7-769c-42dc-a929-349d9285ed33.png)

**✔ Daily Scrum : 정규 스크럼 주 6일 + @**

![image](https://user-images.githubusercontent.com/110509654/227482417-dfe37a09-e086-4723-8cda-ac249d7affe9.png)

**👨‍👨‍👧‍👧 Google Meet - 미팅: Daily Scrum**

![image](https://user-images.githubusercontent.com/110509654/227482802-020a34d5-0cc9-41ac-aac3-0028a17d7285.png)

**🤼‍♀️ Gather - 협업공간: 수시 회의/협업**

![image](https://user-images.githubusercontent.com/110509654/227482872-52d26f02-2fe0-43a9-9cfd-c61d485a8f27.png)

**🔑 Git 전략: Branch & PR**

![image](https://user-images.githubusercontent.com/110509654/227488630-8fd1bcd7-9e4c-492c-9856-d6ee53d21443.png)


**1. Repository / Branch Manangement**
* 본 프로젝트는 메인 + 기능별 8개, 총 9개 모듈로 구성. 프론트 엔드/백엔드 서버 를 분리하여 레포지터리 구성.
* 각 담당자는 _담당모듈 레포지터리에 커밋/푸쉬할 베이스 프로젝트 생성/셋팅 후 터미널에서 아래의 커맨드로 초기 브랜치 셋팅 후 first commit._
  * main : 최종 배포를 위한 브랜치 (**master는 사용하지 않는다)
  * dev : 개발을 위한 브랜치 (모든 개발내용은 해당 브랜치위에서 feat단위로 서브 브랜치 생성/commit 후 해당 브랜치로 Merge한다.
  * test : 배포 전 테스트 서버 구동을 위한 브랜치.
  
**2. PR Strategy**
* Release(Dev Branch로 Merge)는 전원의 감수 및 동의로 진행한다.
* HotFix는 과반수(2명) 이상의 동의를 받는다.
* 모든 파트원(Back : 4 / Front : 2)에게 리뷰(확인)를 받아야 Release를 진행할 수 있다.

## 👨‍🔧 기술 스택

**Front-End**

<img src="https://img.shields.io/badge/React-000000?style=flat-square&logo=React&logoColor=#61DAFB"/></a>
<img src="https://img.shields.io/badge/TypeScript-000000?style=flat-square&logo=TypeScript&logoColor=#3178C6"/></a>
<img src="https://img.shields.io/badge/React Router v6-000000?style=flat-square&logo=React Router&logoColor=#CA4245"/></a>
<img src="https://img.shields.io/badge/Tailwind CSS-000000?style=flat-square&logo=Tailwind css&logoColor=#06B6D4"/></a>
<img src="https://img.shields.io/badge/styled components-000000?style=flat-square&logo=styled-components&logoColor=#DB7093"/></a>
<img src="https://img.shields.io/badge/React Query-000000?style=flat-square&logo=React Query&logoColor=#FF4154"/></a>
<img src="https://img.shields.io/badge/Axios-000000?style=flat-square&logo=Axios&logoColor=#5A29E4"/></a>
<img src="https://img.shields.io/badge/Figma-000000?style=flat-square&logo=Figma&logoColor=#F24E1E"/></a>
<img src="https://img.shields.io/badge/Recoil-000000?style=flat-square&logo=Recoil&logoColor=#DB7093"/></a>


**Back-End**

<img src="https://img.shields.io/badge/Spring Boot-000000?style=flat-square&logo=Spring Boot&logoColor=#6DB33F"/></a>
<img src="https://img.shields.io/badge/Gradle-000000?style=flat-square&logo=Gradle&logoColor=#02303A"/></a>
<img src="https://img.shields.io/badge/Spring Security-000000?style=flat-square&logo=Spring Security&logoColor=#6DB33F"/></a>
<img src="https://img.shields.io/badge/Spring JPA-000000?style=flat-square&logo=Spring Jpa&logoColor=#6DB33F"/></a>
<img src="https://img.shields.io/badge/Spring Batch-000000?style=flat-square&logo=Spring Batch&logoColor=#6DB33F"/></a>
<img src="https://img.shields.io/badge/QueryDsl-000000?style=flat-square&logo=QueryDsl&logoColor=#02303A"/></a>
<img src="https://img.shields.io/badge/Oauth 2.0-000000?style=flat-square&logo=Authy&logoColor=#EC1C24"/></a>
<img src="https://img.shields.io/badge/JSON Web Tokens-000000?style=flat-square&logo=JSON Web Tokens&logoColor=#000000"/></a>

<img src="https://img.shields.io/badge/MariaDB-000066?style=flat-square&logo=MariaDB&logoColor=#003545"/></a>
<img src="https://img.shields.io/badge/Redis-111111?style=flat-square&logo=Redis&logoColor=#DC382D"/></a>
<img src="https://img.shields.io/badge/H2-111111?style=flat-square&logo=H2&logoColor=#DC382D"/></a>

**Production & Deploy**

<img src="https://img.shields.io/badge/AWS-000033?style=flat-square&logo=Amazon AWS&logoColor=#232F3E"/></a>
<img src="https://img.shields.io/badge/Amazon EC2-000033?style=flat-square&logo=Amazon EC2&logoColor=#FF9900"/></a>
<img src="https://img.shields.io/badge/Amazon RDS-000033?style=flat-square&logo=Amazon RDS&logoColor=#527FFF"/></a>
<img src="https://img.shields.io/badge/Amazon S3-000033?style=flat-square&logo=Amazon S3&logoColor=#569A31"/></a>
<img src="https://img.shields.io/badge/Docker-000033?style=flat-square&logo=Docker&logoColor=#2496ED"/></a>
<img src="https://img.shields.io/badge/Jenkins-333333?style=flat-square&logo=Jenkins&logoColor=#D24939"/></a>

**Collaboration tool**

<img src="https://img.shields.io/badge/Slack-660099?style=flat-square&logo=Slack&logoColor=#4A154B"/></a>
<img src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=Notion&logoColor=#000000"/></a>

## ⚙️ Architecture

![image](https://user-images.githubusercontent.com/110509654/227493034-c3de389e-1995-4075-8e82-c1f85f196041.png)


## 📑 ERD 

![image](https://user-images.githubusercontent.com/110509654/227492926-baf1625c-62e1-4ec9-a9ab-7160f3f07f32.png)


## 📱 Demo

|회원 기능|뉴스|
|:---:|:---:|
|![회원가입, 일반로그인, 소셜로그인, 비밀번호 찾기](https://user-images.githubusercontent.com/110509654/227857747-784e0803-9a3f-46ea-b688-2ac732cdc23c.gif)|![뉴스 모듈](https://user-images.githubusercontent.com/110509654/227857777-e72d2005-ff52-44c8-acb1-e3f6ef023d54.gif)|

|환율|
|:---:|
|![환율](https://user-images.githubusercontent.com/110509654/227858037-72fe1c59-1274-4c1d-a633-970e580ad857.gif)|

|날씨|출근정보|
|:---:|:---:|
|![날씨 모듈](https://user-images.githubusercontent.com/110509654/227858057-0efcb224-8101-4566-bac6-1bbd43237c20.gif)|![출근정보](https://user-images.githubusercontent.com/110509654/227858084-978326e2-628a-4fbf-aa33-e794d03c4adc.gif)|

|유튜브, 오늘의 명언, TODO 리스트|주식|
|:---:|:---:|
|![유튜브, 오늘의 명언, 투두 리스트](https://user-images.githubusercontent.com/110509654/227858107-9ea9f258-f098-4081-aa9d-150aed9da2f6.gif)|![주식](https://user-images.githubusercontent.com/110509654/227858024-d404f554-f139-4285-bb18-72cd92dfa71b.gif)|

## ✨ 프로젝트 주요기능

### 🔐 회원 기능

|회원 기능|
|:---:|
|![회원가입, 일반로그인, 소셜로그인, 비밀번호 찾기](https://user-images.githubusercontent.com/110509654/227857747-784e0803-9a3f-46ea-b688-2ac732cdc23c.gif)|

**🔑 회원가입 및 로그인, 비밀번호 찾기**
- 회원가입
    - 유효한 이메일 주소가 있으면 회원가입이 가능하다.
    - 이메일 인증을 시도한다.
- 로그인
    - 회원가입을 통한 로그인과 `OAuth`를 통한 간편 로그인**이 있다.
    - 모두 **토큰 기반의 로그인**으로 만료 시간이 지나면 토큰을 재발급하여 로그인 상태를 유지한다.
- 비밀번호 찾기
    - 등록된 이메일과 연락처를 통해 비밀번호를 초기화할 수 있다.
    - 이메일과 연락처를 확인해서 회원의 이메일로 비밀번호 초기화 링크가 전송된다.


**🗂️ 모듈 저장, 수정, 조회**

|모듈 저장, 수정, 조회|
|:---:|
|![모듈등록 (2)](https://user-images.githubusercontent.com/110509654/227859877-6e1f5a46-c776-4f72-b4ba-78ba74c21129.gif)|

- 모듈 저장
    - 처음 로그인할 시 보고 싶은 모듈을 체크할 수 있다.
- 모듈 조회 및 수정
    - 메인 페이지에서 보고 싶은 모듈을 조회 및 업데이트한다.

**💁‍♂️ 회원 수정,  🔏 비밀번호 변경 , 🤦🏻‍♀️ 회원 탈퇴**

|회원 수정, 비밀번호 변겅, 회원 탈퇴|
|:---:|
|![회원 수정, 비밀번호 변경, 회원 탈퇴](https://user-images.githubusercontent.com/110509654/227860781-c6c5f547-d779-486e-ade6-061a69f17b75.gif)|

- 회원 수정
    - 회원가입 시 입력한 정보를 조회하고 수정할 수 있다.
    - 소셜 로그인 사용자는 비밀번호를 제외한 정보를 수정할 수 있다.
    - 프로필 사진을 등록, 수정, 삭제할 수 있다.
- 비밀번호 변경
    - 일반 로그인 사용자는 비밀번호 변경을 이용할 수 있다.
    - `OAuth` 로그인 사용자는 이용할 수 없다.
- 회원 탈퇴
    - 탈퇴 후에는 탈퇴한 사용자 계정으로 로그인할 수 없다.















## 📜 기술 블로그
* [**Lazier(notion)**](https://www.notion.so/Lazier-10dfb232b0124c2887771d9f98a9d090)




