## *Game-prgramming*
### :video_game:&nbsp;&nbsp;**Term Project for 2022**&nbsp;&nbsp;:video_game:
**-Team Members**	

**\- Title :** 나만 있는 마을				

**\- 개발 툴 :** Unreal Engine5

**\- 스토리 :** 제시되는 지시문을 따라서 주어진 모든 미션을 해결한 뒤, 외계 생명체를 처리하여 마을 사람들을 구하는 게임				

**\- 구성 :**				

      
 |<img width="270" alt="햄버거 게임" src="https://user-images.githubusercontent.com/101172040/201835580-7e2e3ed1-739e-4b8c-aa06-67fdb09ec7e8.png"> |<img width="270" alt="중식 조합 맞추기 게임" src="https://user-images.githubusercontent.com/101172040/201835736-ffd8bffb-88b0-40e9-9e6e-2e487d50baca.png">|<img width="270" alt="잡채 만들기 게임" src="https://user-images.githubusercontent.com/101172040/201835783-233e871b-f72a-44ed-930f-976b97be2029.png">|
|:-----:|:----------:|:-------:
|햄버거 게임|중식 조합 맞추기 게임|잡채 만들기 게임|

**- 주요 구현 기능**        

1. 퀄리티 높은 UI 구현	: 모든 Level의 쪽지, 퀴즈, 대화창, 지시문 등.



&nbsp;&nbsp;<img width="330" alt="그림1" src="https://user-images.githubusercontent.com/101172040/226831111-4b6ebaa2-8216-48b3-877e-0798644ae5b8.png">

• Level3 : 미션을 깨고 모아온 코인으로 원하는 총기 선택하는 창


2. Game Instance 이용한 총기 선택				
 
 
&nbsp;&nbsp;_+ Game Instance ? 게임이 시작되고 끝날때 까지 존재하는 게임 인스턴스에 대한 단 하나의 고급스러운 관리 개체._


&nbsp;&nbsp;_주로 단 하나만 존재하면 되는 게임이나, 플레이어 상태를 저장할 때 사용._			

• Level3 에서 선택한 총에 대한 정보가 Game Instance 안에 저장되어, Level4 에서 spawn 될 때 총기 색상에 적용 됨
	
              
**- 구현시 어려웠던 점** 
1. 햄버거 게임의 부모-자식 없애기
2. Main Scene 의 Character 움직임 구현 : 구글 참고
3. 잡채 만들기 게임 마우스 드래그 구현 : 구글 참고

참고 문서        
\- [ 캐릭터 이동 ](https://github.com/se-ni/VR-AR-Basics-of-game-creation.git)
