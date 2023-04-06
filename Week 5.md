# 게임의 정의
- 사전에서의 정의
  - 규칙을 정해 놓고 승부를 겨루는 놀이
- 교수님의 정의
  - 놀이
  - **재미있는** 놀이
  - **승부**를 겨루는 재밌는 놀이
  - **규칙**을 정해놓고 승부를 겨루는 재밌는 놀이
- 내가 생각하는 게임의 정의
  - 놀이
  - **승부가 있는** 놀이
  - **누구나 할 수 있는** 승부가 있는 놀이

# 게임 개발
- 게임을 만든다 
- 게임을 **재미있게**만든다
- 게임을 재미있게 **효율적으로** 만든다
- 게임을 재미있게 효율적으로 **시간 내에** 만든다.

# 게임 개발팀 (기본적인 구성, 회사마다 다름)
- PD(Project Director)
  - TD (Technical Director)
    - 게임 기획(Game Design)
    - 클라이언트(Programing)
    - 서버(Sever Programing)
  - AD (Art Director)
    - 게임 원화(2D Art Design)
    - 3D 그래픽(3D Art Design)
    - 애니메이션(Animation)
  - 음악
  - PM

# 게임 기획(Game Design)
- 게임의 시스템이나 콘텐츠의 기본 설계도를 만드는 역할 
- 게임 기획자는 게임을 디자인하고, 개발에 필요한 기획서를 만들고, 커뮤니케이션 업무를 함
- 게임 기획서를 작성, 이전에 작성한 기획서를 수정, 아트팀 및 개발팀과 커뮤니케이션하며, 게임 개발 진행 사항에 대해 체크 함.
  - 아트팀에 UI, 캐릭터, 리소스, 애니메이션등을 요청하고 개발팀에 구현 상황을 체크하며 커뮤니케이션 함
- 밸런싱 시트를 조절하며 데이터를 적용해 테스트 하며 버전을 다듬고, 버그가 있으면 개발팀에 전달
- 제품 출시를 위해, 계속 기획서를 수정하고, 다음 업데이트에서의 기획서를 준비함.
- 게임 기획은 게임 시스템 기획, 게임 콘텐츠 기획, 레벨 디자인 기획, 밸런스 기획등 크게 4가지로구분함 
- 게임 콘텐츠 기획
  - 게임 내 설정과 그 안에 들어갈 콘텐츠 기획, 데이터 테이블 구조를 잡고, 수치와 내용을 조정
- 레벨 디자인 계획
  - RPG, FPS에서 맵 툴을 이용해 난이도 조절, 맵과 레벨 제작
- 밸런스 기획
  - 전체 수치의 밸런스 기준을 잡고, 아군 적군 전투 밸런싱, 캐릭터 클래스 성장 밸런싱, 재화 밸런싱등을기획 함

## 게임 개발
- 테크니컬 디렉터는 프로그램 및 기술 이슈에 대한 총 책임을 짐
  - 즉, 프로그램 or 기술력으로 인해 생기는 갖가지 문제를 감독하고 책임지는 엄무를 맡음
  - 그만큼 기술적으로 지식이 많아야 함.
  - 각 파트를 관리 할 수 있는 능력이 필요.

- 클라이언트 및 서버 프로그래머
  - 복작한 프로그래밍을 통해 게엠의 구체척인 표현 및 게임이 잘 돌아가도록 만드는 역할
    - 게임을 개발하고 구현하는 사람들
    - 클라이언트 파트는 C, C++, Unity, UnReal 등 Client Programing 담당
    - 서버 파트는 서버 관리, Database, Network, Backup 등 Sever Programing 담당 
 ## 게임 그래픽
- 아트 디렉터(AD), 컨셉 아티스트, 모델러, 애니메이션, 이펙터, 배경 디자인, UI 디자인, 영상 디자인, 테크니컬 아트(TA)등이 있음
  - 아트 디렉터
    - 비주얼의 책임과 그래픽 리소스 품질 유지, 비주얼 유지등 아트부분 총책임을 지는 역할
  - 컨셉 아티스트
    - 배경, 캐릭터 원화, 모델링 이전의 시각화, 아이디어 구체화 해주는 첫번째 생산자
  - 모델러
    - 원화를 토대로 3D 모델 제작
  - 애니메이터 
    - 3D 모델에 동작 입히는 사람, 약간의 과장으로 더욱 리얼한 행동을 만듦
  - 이펙터
    - 게임의 FX 즉, 특수효과 제작
  - 배경 디자이너
    - 건물과 지형을 만들고, 각종 소품 제작
  - UI 디자이너
    - 인터페이스 레이아웃, UI 동장 스크립트(아트+코더)를 제작
  - 영상 디자이너
    - 영상 개발, 즉 영상 연출, 스토리 보드등을 총괄
  - 테크니컬 아티스트(TA)
    - 셰이더(Shader), 프로그래머와 아티스트, 아티스트의 생산물 제작, 맥스 스크립트(MAX Script)등의 업무를 담당
- 그래픽 파트는 2D, 3D냐에 따라 필요 분야가 많이 달라지며, 특히 모델러와 애니메이터는 기반 그래픽 종류에 따라 많이 달라짐
  - 특히, 테크니컬 아티스트는 '프로그래밍+그래픽'으로 이해 할 수 있으며, 주로 모델링에 광원효과 등 고급 기술을 많이 사용하는 업무를 수행
## 게임 개발 보조
- 음악
  - 게임의 배경음악이나 효과음을 제작
    - BGM으로 작곡된 오리지널 스코어(가사 없는 연주곡) 처럼 OST 의미 할 뿐 아니라, 기존에 있는 곡을 삽압한 삽입곡들 또한 포함
    - 90년대 이후로는 게임에 유명 아티스트의 곡이 삽입되는 경우도 늘어나면서 이러한 곡들 또한 게임 음악의 일종으로 분류함
    - 기획, 프로그래밍, 그래픽등이 없으면 게임이 성립하지 않지만 BGM이 없다고 게임을 만들 수 없는 것은 아님
      - 적재적소에 배치된 게임 BGM은 게임의 몰입도를 높이고, 클리어 후 여운을 깊게하는 효과가 있지만 그것은 게임의 본편이 어느정도 완성도가 있을 때 이야기
      - BGM에 공을 들였으나 망한 게임도 적지 않음
        - 음악에 많이 투자 했다는 것을 어필하는 게임에 오히려 거부감 느끼는 게이머도 있음
      - 게임 내 음악을 끄고 좋아하는 음악을 켜놓고 게임하는 게이머도 적지않음
        - 다만 리듬게임은 BGM이라기 보다는 맵/스테이지 역을 하므로 예외

- PM 프로젝트 매니저
  - 게임 개발의 프로젝트의 일정, 비용 등을 꼼꼼히 관리 해주는 역할
  - 게임 개발 PM은 퍼블리셔 회사, 넥슨, 네오위즈, NHN등 큰 회사에는 사업 PM이 존재
  - 프로젝트 성공이라는것에 초첨을 맞추게 되면 개발 PM은 커뮤니케이션이 가장 중요한 역할 중 하나
  - 개발 PM은 결국 지원 방향성, DM, 그리고 기획자들이 놓치고 있는 수직구조나 전체적인 프로젝트가 처음부터 끝가지 동일하게 컨디션 유지해줄 기준선을 만들어 주는 역할
# 게임 개발 자
## 교수님의 생각
- 신(GOD)
  - 창조신(GOD)
  - 일이 많은 창조신
  - 인간이면서 신의 역할=일이 많은 창조신(GOD)
- 게임 개발의 신
    - PD(Project Director) : 제우스 
    - TD(Technical Director) : 아테나
    - AD(Art Director) : 아프로디테 
## 나의 생각
# 게임 기획자
## 교수님 생각
- 정의를 내린다(두뇌)
- 정의를 내리고 **규칙을 만든다**
- 정의와 규칙을 만들고 **효과적 구현 방안 제시**
- 재미 있는 게임이 나오기 위해 **끝가지** 책임진다
## 나의 생각
# 게임 기획팀
- 기획 팀
  - 시스템
    - 시스템
      - 시스템 기획
      - 전투 기획
      - UI 기획
    - 밸런스 
      - 밸런스 기획
      - 아이템 기획
      - 유료화 기획
  - 콘텐츠
    - 시나리오
      - 세계관 설정
      - 퀘스트 기획
    - 월드 설정
      - 레벨 디자인
      - 레벨 구현
      - 몬스터 
      - 월드 설정

# 게임 기획팀의 구조
- 기획팀은 크게 시스템과 콘텐츠로 나뉨
  - 시스템은, 시스템 기획, 밸런스 기획으로 나뉨
  - 콘텐츠는, 시나리오 기획과 월드 설정 기획으로 나뉨
 - 시스템 기획
  - 시스템 기획, 전투 기획, UI기획으로 나뉨
  - 밸런스 기획은 밸런스 기획, 아이템 기획, 유로화 기획으로 나뉨 
- 콘텐츠 기획
  - 콘텐츠의 시나리오 기획에는 세계관 설정과 퀘스트 기획으로 나뉨
  - 월드 설정 기획에는 레벨 디자인, 레벨 구현, 몬스터 구현으로 나뉨
 
 ## 시스템 기획
 - 게임의 필요한 각종 시스템을 기획
 - 클래스, 전투, UI를 비롯한 강화 PVP, 펫 등의 여러가지 게임 속 시스템을 기획 하고 구현
 - 시스템 기획서 7가지 요소
  - 유저 캐릭터 시스템(수치)
  - 스킬 시스템(수치, 각도/지름/반경 등 엑셀 활용)
  - 몬스터 시스템(수치)
  - 맵 시스템
  - 아이템 시스템(수치, 특성/강화/제작 등)
  - 전투 시스템(시뮬레이션 포함, 검증요소, 가장 마지막 작업)
  - 퀘스트 시스템(수치, 테이블 작성)