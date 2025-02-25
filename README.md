# DGV

## Development

* 개발기간   : 2022/08/29 ~ 2022/09/08
* 개발인원   : 5 명
* Frontend : 최규선, 최슬기, 하서율
* Backend  : 정세한, 박명호
* FrontEnd 깃허브 주소 : (https://github.com/wecode-bootcamp-korea/36-2nd-DGV-frontend)
* Backend 깃허브 주소 : (https://github.com/wecode-bootcamp-korea/36-2nd-DGV-backend)

## 기술 스택

- FE

  <img src="https://img.shields.io/badge/HTML5-E34F26?style=round&logo=HTML5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=round&logo=CSS3&logoColor=white" />
  <img src="https://img.shields.io/badge/JS-F7DF1E?style=round&logo=JavaScript&logoColor=white" />
  <img src="https://img.shields.io/badge/React.js-61DAFB?style=round&logo=React&logoColor=white" />

- BE

  <img src="https://img.shields.io/badge/Node.js-339933?style=round&logo=Node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Express-666666?style=round&logo=Express&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeORM-222222?style=round&logo=typeorm&logoColor=white" />

  <img src="https://img.shields.io/badge/MySQL-4479A1?style=round&logo=MySQL&logoColor=white" /> 
  <img src="https://img.shields.io/badge/AWS-232F3E?style=round&logo=Amazon%20AWS&logoColor=white"/>

[![Video Label](https://img.youtube.com/vi/yq8nFL97u9M/0.jpg)](https://youtu.be/yq8nFL97u9M)

👉 화면을 클릭하면 영상으로 이동합니다.

## 팀원 별 회고
### FE

> **최규선** (로그인 API, 마이페이지 구현)
> > 좋았던 점: 
> > 1. 카카오 로그인 관련 공식문서 확인 및 구현
공식문서를 처음 접하였을 때, 개요만 대략적으로 이해는 했으나 그 안에 함수 및 방법들을 쓰는 방식들은 적용이 힘들었다. 이 부분은 실제 구현을 해보며 실행착오를 겪고 여러 블로그를 참고하여 구현하는 방식으로 진행하였고, 구현 이후에 공식문서를 확인해보니 조금 더 이해가 가능하였다. 구현 도중 문제가 있었던 부분이 있었는 데, 구현을 완료한 후 해당 부분을 해결 할 수 있는 다른 방식이 있었다는 것을 알기까지는 프로젝트 끝난 이 후에 깨닳았고, 이 부분도 결국 공식문서를 확실히 파악하지 못했던 무지에서 비롯됐음을 또 한번 느끼게 된 부분이다.
> > 2. 많지는 않지만 새로운 react 및 개발구현의 새로운 기능들을 알 수 있었던점을 나열해본다.
중요한 값들을 따로 관리 할 수 있는 환경변수 파일 .env (그리고 깃을 이용 시 해당파일에 생기는 문제의 해결방법의 하나인 git rm cached )
페이지 내의 추가 메뉴바 또는 사이드바메뉴가 있을 때 유용하게 컴포넌트를 불러 올 수 있는 중첩라우팅 (다만 정말 필요 없는 곳에도 쓰게 된 부분이 있어서, 연습삼아 시도해봤다고 변명)
> > 
> > 아쉬웠던 점:
> > 1. 통신의 어려움
1차프로젝트 때 회고에서 강조했던 부분이지만, 여전히 쉽지 않았다.
> > 2. 공식문서 이해의 어려움
한 두번 읽어보고 이해 할 수준이 되었으면 다른 기능들도 구현이 가능하지 않았을까?
> > 3. 주변 리소스를 충분히 사용 못한 점
더 좋은 방법으로 가이드 해주는 사람들의 도움을 구하지 못한 점, pr 리뷰를 많이 받지 못한 점
> > 
> > 개선 할 점: 위 사항들에 대한 부분을 개선하여, 시간낭비를 줄여야 한다.

> **최슬기** (예매페이지, Footer 구현)
> > 좋았던 점: 1차 때 해보지 않았던 새로운 기능을 이번 프로젝트에 만들어 볼 수 있어서 새롭게 알게된 것들도 많이 있고 재미있었습니다. 기능구현이 쉽지 않아 고민하고 있을 때 팀원들이 적극적으로 도와주고 같이 고민해 주셔서 결국 완성할 수 있어서 정말 좋았습니다.
> > 
> > 아쉬웠던 점: 프로젝트를 시작하고 전체적으로 어떻게 진행해 나갈지 로직을 구현할 떼 머리속에 그림이 그려지지 않아 많이 답답했습니다. 머리속이 정리가 되지 않아 백엔드쪽에서 원하는 정보를 바로바로 드리지 못했던 점이 아쉬웠습니다. 
> > 
> > 개선 할 점: 백엔드와 프론트엔드가 더 나은 통신 및 구현 방법을 찾기 위해서는 서로 이해하려고 노력하고 열려있는 적극적인 의사소통이 제일 필요할 것 같습니다. 

> **하서율** (메인페이지, 상세페이지, Nav bar 구현)
> > 좋았던 점:`Styled Component`라는 새로운 언어로 프로젝트를 사용했음에도  React.js가 조금 익숙해진 덕분에 레이아웃 / 기능구현 / git 활용 등등, 1차에 비해 수월하게 진행되었습니다.
또한, 1차와 달리 여러 라이브러리를 활용하며 React의 기능을 훨씬 많이 알고 적응할 수 있었습니다.
어려움이 많았지만 배움과 활용을 동시에 경험하며 한층 성장할 수 있는 좋은기회였습니다.
> > 
> > 아쉬웠던 점: 아직 FE-BE간 서로 원하는바와 언어를 완벽히 이해하지 못해 소통에 어려움이 있었던 것 같습니다.
> > 
> > 개선 할 점: 처음에 기능을 어떤식으로 구현할지 flow chart를 그려놓고 시작하면 비교적 수월하게 진행할 수 있을것 같습니다.
UI 보다 기능구현이 먼저!
프로젝트기간이 짧은것을 고려하여 혼자고민하는 시간을 너무 오래 잡지 않아야 할 것 같습니다.

### BE

> **정세한** (카카오톡 소셜 로그인, DB 구성 및 관리)
> > 좋았던 점: 카카오 소셜 로그인 기능을 사용해 볼 수 있어서 좋았다.
> > 
> > 아쉬웠던 점: 마지막날까지 프론트랑 데이터를 맞추고 있었던 점.
> > 
> > 개선 할 점: 사전에 확실하게 데이터형태를 픽스해놓고 작업을 시작하게 기반 설정하기.

> **박명호** (메인, 예매, 상세 페이지 기능 구현 및 DB 구성)
> > 좋았던 점:  API 기능 구현 시, 유저플로우 기준(페이지)으로 Layered Pattern을 구성했는데, 데이터 기준(ERD)으로 기능을 만들어 나가는 것이 옳은 방법이라는 것을 배웠고, 그것을 실제로 적용해볼 수 있었습니다. 이와 같은 실수들이 추후 현업에서 자산으로 적용될 수 있을 것이란 점이 좋았습니다.
> > 
> > 아쉬웠던 점: 파일 구조를 전체적으로 변경하고, 응답되는 데이터 구조들을 수정하는 것에 시간을 많이 소요하여 도커의 사용과 테스트 코드의 적용이 미흡했습니다. 이는 주말간 진행하여 개인 깃 저장소에 업로드 할 예정입니다.
> > 
> > 개선 할 점: MVP 즉, 최소 기능 구현에 목적을 맞추고 수정을 진행하는 것이 중요하다는 것과 팀 전체의 진행상황 파악을 위한 PR의 중요성을 깨달을 수 있었습니다.

## ERD

![DGV_3rd](https://user-images.githubusercontent.com/81615965/189543996-ef69ecda-6fd8-4ff5-baf6-a5e84d2c1767.png)


## APIs

### User

|   End point   	| HTTP Method 	| Description 	| Status 	|
|:-------------:	|:-----------:	|:-----------:	|:------:	|
|  /user/login 	|     POST    	|   로그인 및 회원가입  	|  201  	|
| /user/detail 	|     GET    	|    유저 상세정보    	|  200  	|

### Moive

|          End point         	| HTTP Method 	| Description 	| Status 	|
|:--------------------------:	|:-----------:	|:-----------:	|:------:	|
|          /movies/         	|     GET     	| 영화 제목별 조회 	|  200  	|
| /movies/list 	|     GET     	|  영화 주간별점순/개봉일순 조회 	|  200  	|
|          /movies/locations         	|     GET     	| 영화 (대)지역별 조회 	|  200  	|
|          /movies/sublocation         	|     GET     	| 영화 (소)지역별 조회	|  200  	|
|          /movies/idandsublocation         	|     GET     	| 영화별 대/소 지역 조회 	|  200  	|
|          /movies/:movieId         	|     GET     	| 영화 상세 조회 	|  200  	|

### Theater

|                    End point                   	| HTTP Method 	|     Description     	| Status 	|
|:----------------------------------------------:	|:-----------:	|:-------------------:	|:------:	|
|        /theaters/movies        	|  GET  	| 전체 영화/지역 조회 	|  200  	|
|        /theaters/list        	|  GET  	| 전체 영화 및 선택 영화의 상영관 조회 	|  200  	|
