# ⏰ ONF

<p align="center">
<br>
<img width="30%" src="https://user-images.githubusercontent.com/107983013/215033143-e9f2a220-1e0f-4f23-8a0c-77a782521b5c.png">
</br>
</p>

## 프로젝트 소개

<p align="justify">

통합 인력관리 솔루션인 시프티([Shiftee](https://shiftee.io/ko?gclid=CjwKCAiA5sieBhBnEiwAR9oh2gcZnB8idrHRqf49kkzHCr7BNIxlmtbeziq9Bjp6d2mz3L8FeWVO4RoCst4QAvD_BwE))를 클론코딩

회사 직원들의 근무일정을 설정할 수 있으며, 출퇴근기록 확인!

### [URL] : https://onf.brian-hong.tech/
</p>

<br>

## 백엔드 기술 스택

Javascript, Typescript, NestJS, TypeORM, GraphQL, MySQL, Redis, Docker, GCP


<br>

## 담당 역할

- 근무일정 API [바로가기](https://github.com/hoon2-kim/ONF-server/tree/develop/src/apis/schedules)
- 출퇴근기록 API [바로가기](https://github.com/hoon2-kim/ONF-server/tree/develop/src/apis/workChecks)
- 공지사항 게시판 API [바로가기](https://github.com/hoon2-kim/ONF-server/tree/develop/src/apis/noticeBoards)
- 초대코드 이메일 전송 API [바로가기](https://github.com/hoon2-kim/ONF-server/tree/develop/src/apis/invitationCode)
- 직원 API [바로가기](https://github.com/hoon2-kim/ONF-server/tree/develop/src/apis/members)
- 근무일정 템플릿 API [바로가기](https://github.com/hoon2-kim/ONF-server/tree/develop/src/apis/scheduleTemplates)
- 근무일정 카테고리 API [바로가기](https://github.com/hoon2-kim/ONF-server/tree/develop/src/apis/scheduleCategories)
<br>

## 팀 프로젝트를 통해 배운점

<p align="justify">

### 팀프로젝트를 통해 배운점

- 공공데이터포털 활용

팀프로젝트인 wetrekking에서 메인 기능 중 하나인 등산로 보여주기를 맡게 되었고, 백엔드인 저는 전국 등산로의 좌표를 추출하여 프론트에게 넘겨야 했습니다.
그래서 저는 V월드의 등산로 오픈API를 사용하기로 결정하였습니다.

V월드의 등산로 오픈API를 활용하여 읍면동코드와 산 이름을 입력하게 되면 해당 산의 등산로 좌표가 나오도록 구현을 하였습니다.
읍면동코드 입력을 위해 읍,면,리를 입력하면 읍면동코드가 나오는 오픈API를 하나 더 활용하였습니다.
하지만 오픈API를 이용한 방식의 단점으로 해당 산의 주소와 읍면동이 일치하지 않으면 결과가 나오지 않았습니다.

그래서 두번째 방법으로 산림청 홈페이지의 데이터를 이용하였습니다. 전국 등산로의 정보와 좌표가 GPX파일에 담겨 있었고, GPX파일을 QGIS라는 프로그램을 이용하여
등산로의 이름, 난이도, 좌표만을 추출하여 JSON파일로 가공하였습니다. 그리고 JSON파일의 정보들을 MongoDB에 저장하여 산 이름을 검색하면 등산로 좌표가 나오는
조회API를 작성하였습니다.

이러한 역할을 맡은 계기로 다양한 공공데이터포털을 사용해볼 수 있게 되었으며, 활용방법도 알게 되었습니다.

- 협업의 중요성

부트캠프에서 프로젝트 팀 편성이 되었을 때, 저를 포함한 팀원 전부가 팀 프로젝트 경험이 처음이라 다들 걱정이 많았습니다.
특히, 프론트엔드와 백엔드간의 소통이 제일 힘들었던거 같습니다. 프론트엔드에서는 백엔드에 대해 잘 몰랐으며, 마찬가지로 백엔드에서도 프론트엔드에 대해 몰라서
작업 도중 서로 우리 쪽에서는 이렇게 하면 되는데 왜? 저 쪽에서는 안된다고 할까? 라고 생각이 많이 들었습니다.
그래서 처음에는 의견충돌도 많았고 기획도 계속해서 변경이 되었습니다.

그래서 이러한 충돌을 해결하기 위해 매일 프론트와 백엔드가 같이 모여 회의를 진행하였으며, 서로가 모르는 부분과 이해하지 못하는 부분을 설명해주며 하나하나씩 의견출동을
해결해 나갔습니다.

이러한 경험을 통해 얻은 교훈은 서로의 입장에서만 생각하면 안되고 대화를 통해 의견을 조율해 나가는 과정이 매우 중요하다는 것을 알게되었습니다.

</p>
<br>

