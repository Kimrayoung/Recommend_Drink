# 📝 Pick Drink🥤
# 📜 프로젝트 소개
진행 기간: 2023.03.16 ~ 2023.05.04
업데이트 진행 기간: 2023.07.10 ~ 2023.08.03

카페에 와서 뭘 시킬지 몰라서 맨날 아메리카노만 시키시는 분들의 음료를 골라주고 음료에 대한 정보를 제공하는 앱입니다

# 🖥 프로젝트 특징
- 카페 별로 음료 리스트를 보여줍니다(투썸플레이스, 메가커피, 스타벅스 등)
- 다이어터 & 새로운 음료를 도전해보고 싶은 손님 등 손님을 세분화해서 추천음료 제안해줍니다
- 추천 음료 리스트에서 특정 음료를 고르면 그 음료가 어떤 맛인지에 대한 설명 & 칼로리 등 영양성분 알려줍니다
- 음료를 직접 마셔본 손님들의 리뷰를 확인해볼 수 있고 자신이 직접 리뷰를 작성할 수도 있습니다
- 로그인 기능이 추가되었습니다(업데이트 v1.1)
- 마이페이지 기능이 추가되어 본인 데이터 관리를 조금 더 수월하게 진행할 수 있습니다.(업데이트 v1.1)
    - 리뷰 관리 기능
    - 컴플레인 관리 기능
    - 계정 관리 기능(닉네임 변경, 회원탈퇴, 소셜 로그인 플랫폼 확인)

# 🛠 기술 스택

- DB : Firebase
- FE : Swift
      
# ✨ 성장 경험
### 전박적인 앱 출시 경험
디자인, db설계, 개발, 배포까지 처음부터 끝까지 앱 개발을 하면서 간단한 앱이지만 전반적인 앱 개발 프로세스에 대해서 경험해볼 수 있는 좋은 기회였습니다.
앱 업데이트를 진행하면서 한번더 부족한 점에 대해서 알게되었습니다.

### 데이터에 대한 고민
픽 드링크는 리뷰를 작성하는 부분이나 신고 부분 등을 제외하고는 앱에서 가지고 있는 데이터를 제공해야 하기 때문에 기본적으로 카페에 대한 음료 정보를 가지고 있어야 했습니다. 대용량 데이터를 어떻게 하면 조금 더 효율적으로 가지고 올 수 있을까에 대해서 고민을 했지만,, 딱히 해결방법을 찾지 못해서 일일이 수작업으로 진행을 하게되었습니다.

### MVC패턴
픽 드링크는 MVC패턴으로 ViewController안에 거의 모든 비지니스 로직, API관련된 로직등이 한꺼번에 있어서 나중에 확장성이 좋지 않다고 생각합니다. 그래서 후에 데이터를 조금 더 추가하면서 MVC패턴에서 MVVM패턴으로 변경해서 조금 더 확장성이 좋도록 만들고 싶습니다.
업데이트 후 Firebase에서 데이터를 불러오는 부분과 로그인 기능을 담당하는 부분을 따로 파일로 빼서 관리를 진행하였습니다. 아직 완벽히 MVVC패턴이라고 할 수 없지만 다음 업데이트 때는 이 부분을 조금 더 보강할 생각입니다.

### 로그인 관련
이번 프로젝트로 로그인 기능을 추가하겠다고 다짐을 하면서 처음 로그인 기능을 프로젝트에 넣게 되었습니다. 아무래도 처음 로그인을 진행하다보니 처음부터 프로젝트에 넣어서 진행을 하면 꼬이는 부분도 많고 로그인을 구현하다가 어디가 틀렸는지 알기가 힘들것 같아서 따로 프로젝트를 파서 진행을 했습니다. 애플 로그인과 카카오 로그인 각각 파이어 베이스와 연동해서 구현하는 것을 연습하고 실제 프로젝트에 구현하는 부분을 진행하였습니다.

앱관련 기타 문서
[앱 개발일지]https://pastoral-dust-a7f.notion.site/9dcbb038d0214581a7cf9e57f3c4a658?pvs=4

👀서비스 화면
![PickDrink_v1 1](https://github.com/Kimrayoung/Recommend_Drink/assets/66238470/974842c6-4c8a-4eb3-bce3-dcc79984af50) {: width="200" height="400"}




 
