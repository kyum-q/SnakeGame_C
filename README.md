# SnakeGame
C언어로 제작한 SnakeGame 2인용

## ✍🏻&nbsp; 작품 소개
2명의 Player는 방향키(player1)와 AWSD키(player2)로 이동을 할 수 있다. 
2명의 플레이는 서로 제한된 공간에서 움직이면서 다른 Player의 머리가 자신의 몸통에 닿게 유도하는 게임이다. 
이렇게 상대방 몸에 사진의 머리가 닿거나 혹은 길이가 소멸되어 몸과 머리가 다 소멸되면 패배한다. 
몸통은 벽에 닿거나 상대방으로부터 공격받으면 줄어든다. 그리고 Snake는 자신의 몸 방향으로는 이동이 불가능하다.<br>

## 📍&nbsp; 시스템 기능
2인 Play (방향키, AWSD 이용)

1. Gold - 길이, 속도 일시적(3초)으로 증가 <br>
2. 아이템 중에서 발사 아이템 있음 (아이템 사용 – 공격)<br>
3. 발사 아이템이 머리에 맞으면 죽음 / 몸에 맞으면 길이 감소<br>
3. 벽에 닿은 지렁이 길이 감소<br>
4. 상대편 지렁이 몸에 자신의 지렁이 머리가 닿으면 종료 (패배)<br>
5. 자기 몸쪽으로 이동 불가능<br>

flag – 발사 아이템 개수 (최대 5개)<br>

### 아이템
Player는 총 길이 증가, 속도 증가, 속도 감소, shooting 4가지의 아이템이 존재한다. 아이템은 다음과 같다.<br>

'O': snake 길이 증가<br>
'↑': 3초간 일시적으로 속도 증가<br>
'↓': 5초간 일시적으로 속도 감소<br>
'T': shooting item 획득<br>

shooting일 경우는 아이템을 획득하자마자 사용되는 것이 아닌 보관하다가 공격하고자 할때 발사 버튼(player1: /, player2: R)을 통해 공격할 수 있다. 상대방을 맞히면 상대방의 길이가 감소된다. shooting item은 상단바에 * 표시를 통해 나타나고 최대 일곱 개까지 보관가능하다.

## 🖥&nbsp; 실행 화면

![image](https://user-images.githubusercontent.com/109158497/199796563-6ec40132-a3b6-410d-b9d6-ebbc39602af3.png)
<br>

![실행화면](https://github.com/kyum-q/SnakeGame_C/assets/109158497/c7ac18ba-de0a-4e61-88e6-93d11f1d67dd)

## 🔍&nbsp; 개발 언어
<img src="https://img.shields.io/badge/C-000000?style=flat-square&logo=C&logoColor=white"/>
