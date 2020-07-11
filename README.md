# SCC_Project 6.
##### 2020 Summer Coding Camp - Project #6 (Prof. KIM HJ)
###### 21600402 Ahn SuHyun


## Task : Connect6 (육목) + AI
### Time Period : 3day






#### 아이디어 흐름
1. 컴퓨터에게 돌의 정보를 알려주는 것에 대해서 #지뢰찾기#를 모티브로 코드 방향을 잡게 됨 
2. 지뢰찾기처럼 모드 값을 한번에 합쳐버리게 되면 더미벨류(쓰레기값)이 필터링이 안되고 공격도 방어도 효율적이지 못함
3. 필터를 4개를 끼워서  { X축, Y축, RS축 : 우상대각, LS축 : 좌상대각 } 4개의 각각의 방향에 유효값을 따로따로 저장하 
4. 4방 필터를 사용하여 공격을 해야할땐 공격할 수 있고, 방어를 해야할땐 방어를 하는 1세대 (Lv... 1?) 정도 완성
5. 1세대의 문제점은 6개를 못만드는 상황임에도 불구하고, 일단 가장 높은 값을 찾아가 공격 및 방어를 하여 본인에게 공격의 흐름이 있어도 금방 반납하고 의미없는 착수를 많이 함. 그러다보니 공격이 매우 단순하며 게임이 진행 될 수록 그 공격권의 흐름을 유지하지 못함. 
6. 

##### 버그 및 구현 못한 거 
1. 사진 저장할때 에러가 좀 있음 
2. 여러분 파일을 새로 불러오거나 확인 안해봤는데 약간의 삐걱 거림이 있음 

## 배운점 
1. RGB, HSB..?
