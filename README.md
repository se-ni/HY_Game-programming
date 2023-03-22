## :video_game:&nbsp;&nbsp;**Term Project for 2022**&nbsp;&nbsp;:video_game:
**-Team Members :** 박세은, 정유빈

**\- Title :** 나만 있는 마을				

**\- 개발 툴 :** Unreal Engine5

**\- 스토리 :** 제시되는 지시문을 따라서 주어진 모든 미션을 해결한 뒤, 외계 생명체를 처리하여 마을 사람들을 구하는 게임				

**\- 맵 구성 :**				

      
 | <img width="1017" alt="스크린샷 2023-03-22 오후 5 32 34" src="https://user-images.githubusercontent.com/101172040/226847089-b7207f24-f78d-41a8-923a-f14110a64cd8.png"> |<img width="1017" alt="스크린샷 2023-03-22 오후 5 34 07" src="https://user-images.githubusercontent.com/101172040/226847159-a2eba971-fa60-47ad-bb6a-9d237715bceb.png">|<img width="1017" alt="스크린샷 2023-03-22 오후 5 38 23" src="https://user-images.githubusercontent.com/101172040/226847182-395dd372-715a-4be1-888a-0d5571dab43b.png">|<img width="1017" alt="스크린샷 2023-03-22 오후 5 37 20" src="https://user-images.githubusercontent.com/101172040/226847208-f341c437-a5b7-4237-903e-ed8b800dc899.png">|
|:-----:|:----------:|:-------:|:-------:|
|Level1 : 집|Level2 : 경찰서|Level3 : 총기샵|Level4 : 마을|


**\- 조작법 :**

좌우 및 시점 이동 : W A S D


그 외


F: 아이템 상호작용 / B : 문열기 / P : 미션확인 / 마우스 좌클릭 : 총 쏘기 / Shift : 달리기


**<h2>주요 구현 기능**</h2>       

**1. 퀄리티 높은 UI 구현**	: 모든 Level의 쪽지, 퀴즈, 대화창, 지시문 등.



&nbsp;&nbsp;<img width="330" alt="그림1" src="https://user-images.githubusercontent.com/101172040/226831111-4b6ebaa2-8216-48b3-877e-0798644ae5b8.png">

• Level3 : 미션을 깨고 모아온 코인으로 원하는 총기 선택하는 창

*****
**2. Game Instance 이용한 총기 선택**





<img width="330" alt="그림2" src="https://user-images.githubusercontent.com/101172040/226834517-cc9e0cb9-5cf6-4bde-9834-f1da1a2a5b4a.png"><img width="330" alt="그림3" src="https://user-images.githubusercontent.com/101172040/226834557-40ef9065-b261-49b5-8779-5e8e0b436071.png">


 
&nbsp;&nbsp;_+ Game Instance ? 게임이 시작되고 끝날때 까지 존재하는 게임 인스턴스에 대한 단 하나의 고급스러운 관리 개체_


&nbsp;&nbsp;_주로 단 하나만 존재하면 되는 게임이나, 플레이어 상태를 저장할 때 사용._			

• Level3 에서 선택한 총에 대한 정보가 Game Instance 안에 저장되어, Level4 에서 spawn 될 때 총기 색상에 적용 됨


**3. AI구현**





<img width="330" alt="그림4" src="https://user-images.githubusercontent.com/101172040/226836498-4044d19f-5fe7-4416-bc3c-9f26b9821860.png"><img width="330" alt="그림5" src="https://user-images.githubusercontent.com/101172040/226836528-8e60a2c1-318f-497d-b6f9-6f8cda9db938.png">



• 마지막 Level : 적들이 무작위로 Spawn 되어, Pawn Sensing Comp.를 통해 플레이어를 봤을때, 다가오는 AI 기능 구현


**<h2>특징**</h2>

1. 장르 : 방탈출과 FPS 두 가지의 장르를 혼합하여 게임의 재미를 높였음
2. UI : UI에 신경을 많이 써서 전체적으로 게임의 퀄리티를 높였음
3. 배경 : 긴장감 조성을 위하여, Sky Sphere를 이용하여 시간을 낮에서 밤으로 흘러가게끔 점차 하늘 색깔이 어두워지게 구현하였음



<h2>구현 시 아쉬웠던 점</h2>


\- Level3 에서 원하는 총을 구매했을때, Level3의 Player에게 총이 부착된 채로 다음 Level로 넘어가도록 구현하지 못함                   
\- UE5에 대한 정보가 너무 없음                        
\- 협업을 위해 프로젝트의 파트를 나눈 뒤, 큰 용량 때문에 폴더를 합치는 과정에서도 어려움이 많았음


<h2>참고 문서</h2>        
[ 캐릭터 이동 ](https://github.com/se-ni/VR-AR-Basics-of-game-creation.git)
