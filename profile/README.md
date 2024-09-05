# Re:Search
> 리서치를 다시 서치하자!

## Service Introduction
'수많은 증권가 리포트들 사이에서 어떤 정보가 가치있는 정보일까'라는 고민이 있었습니다.

주식 투자자나 금융전문가들은 주식 매매에 대한 결정을 내리기 위해 리포트를 참고하기도 합니다. <br>
하지만 모든 증권사 리포트들이 신뢰할만한 정보를 주는 것은 아닙니다.

‼️ 그래서 저희 팀은 증권사 리포트에 대해 수익률과 달성점수를 비교해서 <br>
신뢰도 높은 증권사와 애널리스트들을 식별할 수 있는 서비스를 제공하게 되었습니다.

🧐 `Re:Search`를 통해 사용자는 
- 원하는 증권사, 애널리스트, 리포트 제목 등으로 `검색`할 수 있고
- 리포트에 대한 `실제 수익률`과 `달성점수`를 확인할 수 있습니다.
- 또한, 리포트의 점수에 따라 `애널리스트의 순위`를 파악하거나
- 애널리스트를 `즐겨찾기`에 추가하여 애널리스트의 새 리포트를 `메일`로 받아볼 수 있습니다.

## Team member
|곽진현|김현수|박지민|박예린|
|:---:|:---:|:---:|:---:|
|<img width="120px" src="https://avatars.githubusercontent.com/u/93817551?s=96&v=4"/>|<img width="120px" src="https://avatars.githubusercontent.com/u/122847760?v=4" />|<img width="120px" src="https://avatars.githubusercontent.com/u/122578483?v=4"/>|<img width="120px" src="https://avatars.githubusercontent.com/u/46209669?v=4"/>|
|회원 기능<br/>검색 기능<br/>아키텍처 설계 및 배포|오늘의 리포트 추천 기능<br/>즐겨찾기 및 채팅 기능 구현<br/>리포트 상세 페이지|UI/UX 설계, 문서 작성<br/>애널리스트 관련 페이지|데이터 크롤링<br/>증권사 관련 페이지|

## Main Features
### ⭐️ 증권사 및 애널리스트
- 애널리스트 수익률 및 달성점수 순위
- 업종별 리포트 수익률 및 달성점수 평균
- 가중치(수익률 30%, 달성점수 50%, 리포트 작성수 20%)를 적용하여 애널리스트 점수 계산
- 오픈 TALK 기능을 통해 다른 유저들과 애널리스트에 대한 정보를 공유

### ⭐️ 리포트 및 검색
- 오늘의 리포트 추천
- 즐겨찾기한 애널리스트의 새로운 리포트에 대한 알림 메일 발송
- 증권사, 애널리스트, 리포트 등을 통합한 검색 기능

## Stacks

### Environment
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-007ACC?style=for-the-badge&logo=Visual%20Studio%20Code&logoColor=white)
![webstorm](https://img.shields.io/badge/webstorm-000000?style=for-the-badge&logo=webstorm&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white)
![Github](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white)             

### Development
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=Javascript&logoColor=white)
![React](https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=white)

![Express](https://img.shields.io/badge/express-000000?style=for-the-badge&logo=express&logoColor=white)
![mariadb](https://img.shields.io/badge/mariadb-003545?style=for-the-badge&logo=mariadb&logoColor=white)

### Communication
![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=Slack&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white)

## Project Architecture
<img width="718" alt="architecture diagram" src="https://github.com/user-attachments/assets/abec1778-04fe-485b-a302-14281e4d9dc9">

