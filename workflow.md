### 개발실무팀플 WorkFlow <br>
#### Member <br>
팀장 : 이정인 소프트웨어학부 2018044911 <br>
팀원 : 박준성 소프트웨어학부 2019052581 <br>

- 가정 <br>
  우리 팀은 A회사에서 진행하는 B프로젝트에 참여하고 있다. 이 프로젝트는 여러 팀이 참여하고 있으며, 각 팀 별로 필요한 기능을 분담하여 서로 다른 디렉토리에 작업한다. <br>
  즉, 각 팀의 작업은 서로 영향을 주지 않게끔 한다.<br>
  팀 별로 맡게 된 기능도 세분화하여 팀원이 분업할 수 있다.<br>
  
- TODO - 팀원<br>
팀원은 팀장이 fork한 repository를 fork한 후,<br>
자신이 맡은 feature 브랜치를 checkout하여 개발을 진행한다.<br>
  
  - 한 feature 브랜치에서 여러 인원이 개발을 진행할 경우<br>
인원 중 한 명의 repository를 골라 다른 인원들은 해당 repository를 fork하여 개발을 진행하도록 한다.<br>
이때, slack 등의 협업 도구를 적극 활용하여 개발 상황(현재 작업중인 파일 등)을 공유하도록 한다.<br>

  - 개발 중에 issue가 발생할 경우<br>
issue가 발생한 feature 브랜치에서 issue를 해결하기 위한 issue 브랜치를 따로 하나 생성하여 <br> 
개발 상황과 issue 처리 상황을 구분한다. <br>
issue 처리가 완료되면 issue 브랜치를 부모 브랜치로 합병한 후 해당 브랜치는 제거한다. <br>

![issue 브랜치](./img/issueBranch.jpg)
