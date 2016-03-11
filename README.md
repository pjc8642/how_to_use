how_to_use
====

클라이언트와 제어판 연결하기
----
* 게임을 구동합니다.
* [제어판 페이지](http://pjc.luavis.kr/memo/)에 접속합니다.
* 게임에 표시된 숫자로 이루어진 아이디를 제어판의 `Connection -> ID` 에 입력합니다.
  ![channel](img/channel_id.png)
* `Connect` 버튼을 클릭하면 연결됩니다.

메뉴바 이용하기
----
* 제어판의 메뉴 화면에서는 각각의 아이템을 클릭할 수 있습니다.
* 아이템을 클릭하면 아래에 세부적인 제어 메뉴가 표시됩니다.
![ui](img/ui_menu.PNG)

각 항목에 대한 설명
----
* __Application__
  * Boost Factor : 게임 전체적인 애니메이션 속도입니다. (0일 경우 1배속 2일 경우 3배속)
* __Battle__
  * Attack Particles : 공격 시 상대방에게 날리는 파티클 오브젝트의 수 입니다.
* __Haptic__
  * Lock Board : 체크 시 보드를 잠급니다. 잠긴 상태의 보드는 풍선을 클릭해도 뒤집어서 결과를 확인하지 않습니다.
  * Haptic Factor : 터치 시 다른 풍선들을 얼만큼 리사이징 할 건지 설정합니다.
  * Haptic In Duration : 풍선이 Haptic Factor에 도달하는데 걸리는 시간입니다.
  * Haptic Out Duration : 풍선이 원래 사이즈로 도달하는데 걸리는 시간입니다.
  * Vibration on Input (SW) : 체크 시 풍선을 클릭할경우 화면에 진동 이펙트를 줍니다.
  * Vibration on Input (Physical) : 체크 시 풍선을 클릭할경우 물리 진동을 출력합니다.
* __Board__
  * Shuffle : 체크 시 하단의 보드를 전부 셔플합니다.
  * Combo Font Size : 콤보 시 나타나는 폰트의 크기입니다.
  * Combo Font Display Duration : 콤보 폰트가 나타난 상태로 유지되는 시간입니다.
  * Match Effect Mov Duration : 정답 시 보드에서 정답 영역으로 이펙트가 날아가는데 걸리는 시간입니다.
  * Match Effect Rotation Count : 정답 시 보드에서 정답 영역으로 이펙트가 몇 바퀴 돌면서 날아가는지 지정합니다.
* __AI__
  * Match Rate : 봇의 정답률입니다.
  * Submit Delay : 생각하는듯한 효과를 주기 위해서 봇이 답을 제출하기까지 대기하는 시간입니다.

결과물 출력하기
----
* 메뉴 가장 왼쪽의 `@` 버튼을 클릭하면 json으로 출력이 가능합니다.<br>
![json](img/json_output.PNG)
