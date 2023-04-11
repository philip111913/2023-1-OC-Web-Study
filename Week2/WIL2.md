**1주차 학습 내용 정리**


1. **URI : Uniform Resource Identifier**

**URL과URN을 외연으로 하는 상위개념이다.**

1. **URL : Uniform Resource Location = 프로토콜 + DNS주소** 

**교촌치킨 신촌점. Resource(허니콤보)를 얻을 수 있는 위치를 말해준다.**

**\*프로토콜 : 통신규약, DNS(Domain Name Server) : 복잡한 IP주소를 대신하는 사람이 기억하기 쉬운 형태.**

1. **URN : Uniform Resource Name**

허니콤보의 메뉴 코드. Resource를 찾기 위한 정형화된 이름이다

1. HTML : 자료 (뼈대)

1. CSS : UI (살과 옷)




1. JS : 제어체계







2주차 학습 내용 정리

1. 파일의 4가지상태

추적x,변경x,변경o,staged

-추적x,o 

추적x(untracked) : Git이 아예 추적하지 않는 상태, add커멘드를 사용하지 않은 상태이다.

추적o(tracked) : add 커멘드를 통해 명시적으로 지시하면 팀원들에게 내 파일을 보여줄 수 있는 상태이다. -staged 상태에 들어가게 된 것이다.

또한, git rm 명령어를 통해 파일을 삭제하거나 git --cached 명령어를 통해 커밋 이후에 삭제하지 않고 untracked 상태로 들어가게 할 수 있다 

-변경x,o

변경x(unmodified) : 기존 상태에서 변경된 부분이 없는 상태이다.

add커멘드를 통해 staged 상태에 들어간 파일은commit을 통해 modified에서 unmodified 상태로 들어가게 할 수 있다.

변경o(modified) : 기존상태에서 변경된 부분이 있는 상태이다. add커멘드를 통해 tracked 상태인 파일에 변경을 가한다면 modified 상태에 들어가게 된다.

-Staged

파일들의 다양한 변화를 엮어 이름을 지어주기 위해 변화들을 쌓아두는 공간이다. add커멘드를 통해 staged 상태로 들어가게 된다.

1. 저장소, 공간들-Working Directory, Staging Area, Local Repository, Remote Repository

다른 동료들을 위해 github 같은 Remote Repository가 필요하다.

working directory에서 변경한 파일들이 add를 통해 staging area에 변화를 쌓아 둘 수 있고, commit을 통해 local repository로 파일을 넘겨줄 수 있으며, 

Push를 통해 local repository에 있는 파일을 remote repository로 이동시킬 수 있다.


