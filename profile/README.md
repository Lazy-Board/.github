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


**Production & Deploy**


**Collaboration tool**


## ⚙️ Architecture

![image](https://user-images.githubusercontent.com/110509654/227493034-c3de389e-1995-4075-8e82-c1f85f196041.png)


## 📑 ERD 

![image](https://user-images.githubusercontent.com/110509654/227492926-baf1625c-62e1-4ec9-a9ab-7160f3f07f32.png)


## 📜 기술 블로그
* [**Lazier(notion)**](https://www.notion.so/Lazier-10dfb232b0124c2887771d9f98a9d090)


