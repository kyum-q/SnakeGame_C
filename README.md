# SnakeGame
C언어로 제작한 SnakeGame 2인용

기능 : 
(1) 2인 Play (방향키, AWSD 이용)
(2) 아이템 :
1. Gold - 길이, 속도 일시적(3초)으로 증가
2. 아이템 중에서 발사 아이템 있음 (아이템 사용 – 공격)
3. 발사 아이템이 머리에 맞으면 죽음 / 몸에 맞으면 길이 감소
3. 벽에 닿은 지렁이 길이 감소
4. 상대편 지렁이 몸에 자신의 지렁이 머리가 닿으면 종료 (패배)
5. 자기 몸쪽으로 이동 불가능

flag – 발사 아이템 개수 (최대 5개)

C언어로 제작한 2인용 SnakeGame이다.
2명의 Player는 방향키(player1)와 AWSD키(player20로 이동을 할 수 있다. 2명의 플레이는 서로 제한된 공간에서 움직이면서 다른 Player의 머리가 자신의 몸통에 닿게 유도하는 게임이다. 이렇게 상대방 몸에 사진의 머리가 닿거나 혹은 길이가 소멸되어 몸과 머리가 다 소멸되면 패배한다. 몸통은 벽에 닿거나 상대방으로부터 공격받으면 줄어든다. 그리고 Snake는 자신의 몸 방향으로는 이동이 불가능하다.
Player는 총 길이 증가, 속도 증가, 속도 감소, shooting 4가지의 아이템이 존재한다. 아이템은 다음과 같다.
'O': snake 길이 증가
'↑': 3초간 일시적으로 속도 증가
'↓': 5초간 일시적으로 속도 감소
'T': shooting item 획득
shooting일 경우는 아이템을 획득하자마자 사용되는 것이 아닌 보관하다가 공격하고자 할때 발사 버튼(player1: /, player2: R)을 통해 공격할 수 있다. 상대방을 맞히면 상대방의 길이가 감소된다. shooting item은 상단바에 * 표시를 통해 나타나고 최대 일곱 개까지 보관가능하다.
![image](https://user-images.githubusercontent.com/109158497/199724189-e4bb9230-6262-4535-bb89-224f2f87347f.png)
![image](https://user-images.githubusercontent.com/109158497/199724313-5809eb12-54c4-4cdd-8b30-1954b9f7944c.png)
![image](https://user-images.githubusercontent.com/109158497/199724347-b6a51de0-10e7-45ef-8fea-2d427e59dad2.png)
