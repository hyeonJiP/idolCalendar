# 프로젝트 소개

### 프로젝트 기간 : 2023.03.06 ~ 2023.03.27

---

# :hearts: MyFavor

<https://myfavor.site>

최애인은 '내가 가장 사랑하는'이라는 의미의 '최애(最愛)'에 사람 '인(人)'을 합친 말로, 팬들이 가장 사랑하는 아이돌을 의미합니다.

이 서비스는 아이돌 팬들을 위한 스케줄 관리 서비스로, 다양한 아이돌 그룹의 스케줄 정보를 제공합니다.

팬들은 자신이 좋아하는 아이돌 그룹의 활동을 빠르게 파악할 수 있습니다.

또한 "최애인"에서 제공하는 아이돌의 일정 달력에 유저의 개인 일정을 입력할 수 있어 아이돌 일정과 개인 일정을 함께 관리할 수 있습니다.

따라서 사용자는 자신이 좋아하는 아이돌과 자신의 일정을 효율적으로 관리 할 수 있습니다.

## <br>

<br>

### 멤버 구성

- 슬랙과 Github를 활용하여 협업

## Front

- 최현우 : <https://github.com/chhw130>

- 박현지 : <https://github.com/hyeonJiP>

- 김지영 : <https://github.com/KIMJIYOUNGS2>

## Back

- 고은기 : <https://github.com/sliverKi>

- 이수현 : <https://github.com/ssu-uky>

<br>

---

<br>

## 🔧 기술 스택

### 개발 및 협업관리 환경

![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-007ACC?style=for-the-badge&logo=Visual%20Studio%20Code&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white)
![Github](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white) <img alt="Slack" src ="https://img.shields.io/badge/Slack-4A154B.svg?&style=for-the-badge&logo=Slack&logoColor=white"/></a>

### 호스팅

![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=Render&logoColor=white)

### 개발

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)

### 주요 라이브러리

![Redux](https://img.shields.io/badge/redux-%23593d88.svg?style=for-the-badge&logo=redux&logoColor=white)
![React Query](https://img.shields.io/badge/-React%20Query-FF4154?style=for-the-badge&logo=react%20query&logoColor=white)
![React Hook Form](https://img.shields.io/badge/React%20Hook%20Form-%23EC5990.svg?style=for-the-badge&logo=reacthookform&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)
![Styled Components](https://img.shields.io/badge/styled--components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white)
![SASS](https://img.shields.io/badge/SASS-hotpink.svg?style=for-the-badge&logo=SASS&logoColor=white)

<br>

---

<br>

## :bulb: Architecture

<img width="800" alt="스크린샷 2023-04-04 오후 2 16 55" 
src="https://user-images.githubusercontent.com/121347506/229693783-22b5be1c-c88a-49c8-940d-37265e3bd72c.png">

## <br>

<br>

## :bulb: 내가 구현한 기능

### - 메인 페이지

- infinite-sliding-banner
- 아이돌의 스케줄 정보를 확인 할 수 있는 서브 슬라이드 배너
- 아이돌 API 연동
- 등록된 정보를 바탕으로 아이돌의 프로필을 생성하고 클릭 시 캘린더로 이동

### - 캘린더 페이지

- 활성 카테고리에 따라 달력에 표시되어 지는 일정 구분 로직
- 활성 카테고리에 맞추어 날짜에 카테고리별 해당하는 토글 노출
- 사용자가 선택한 날짜에서 전날, 다음날에 대한 일정 목록 표시
- 회원인 사용자에게만 보여지는 MY 카테고리 노출 여부

### - 사이드바

- 오늘 날짜 기준으로 다가올 날에 대한 (3일)일정 알림
- 외부 요소를 참고하여 열고 닫거나, 최상단으로 스크롤 이벤트 발생

<br>

---

<br>

## :bulb: 구성도

![](https://velog.velcdn.com/images/chhw130/post/0b435eae-9465-4bb5-9e9e-b90b91a0d0fb/image.png)

## <br>

<br>

## :bulb: UI

<img width="1289" alt="스크린샷 2023-04-08 오후 5 04 43" src="https://user-images.githubusercontent.com/116826162/230710850-2ebeded0-e427-4020-b1a5-3a2371c445da.png">

👏[자세한 UI보러가기](https://github.com/hyeonJiP/idolCalendar/wiki/UI)

## <br>

<br>

## :bulb: 프로젝트를 진행하면서 고민했던 문제들

🙌자세한 내용은 [링크](https://github.com/hyeonJiP/idolCalendar/wiki)

- axios로 API 처리 시 중복 데이터 요청이 많았기 때문에 협업 전에 충분한 회의를 통해 데이터 처리에 있어서도 중요한 부분임을 깨달았다.
- 백에서 데이터를 요청할 때 비동기 처리를 통해 효율성을 올리도록 노력했다.
