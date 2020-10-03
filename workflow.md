### 개발실무팀플 WorkFlow <br>
#### Member <br>
팀장 : 이정인 소프트웨어학부 2018044911 <br>

- 가정 <br>
  우리 팀은 A회사에서 진행하는 B프로젝트에 참여하고 있다. 이 프로젝트는 여러 팀이 참여하고 있으며, 각 팀 별로 필요한 기능을 분담하여 서로 다른 디렉토리에 작업한다. <br>
  즉, 각 팀의 작업은 서로 영향을 주지 않게끔 한다.<br>
  팀 별로 맡게 된 기능도 세분화하여 팀원이 분업할 수 있다.<br>
  
### **PR & merge 규칙**
  1. 프로젝트는 계층적인 구조를 띤다. (issue ⊂ feature ⊂ team ⊂ project)
  2. 모든 개발은 상위 원격 저장소 중 가장 가까운 저장소를 자신의 repository로 fork한 후에 진행하도록 한다.
  3. branch 간 merge는 함부로 하지 않는다. merge 권한은 다음을 따르도록 한다.<br/>
  &nbsp;- 개발자: issue→feature<br/>
  &nbsp;- 팀장: feature→team<br/>
  &nbsp;- 프로젝트 리더: team→develop→master
  4. 각 개발자는 feature 브랜치에서 작업을 마친 뒤, 팀장의 repository에 PR을 보낸다.
  5. 각 팀장은 해당 팀에서 맡은 모든 기능이 구현되었다면, 프로젝트 리더의 repository에 PR을 보낸다.
  6. 모든 프로젝트 구성원은 PR을 보내기 전, 자신의 권한 내에 있는 최상위 branch까지 merge를 완료하도록 한다.

![PR](./img/PR.jpg)
![merge](./img/merge.jpg)
