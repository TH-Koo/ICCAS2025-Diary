# Unity Quiz Running Game
<ICCAS2025>

##🦖 Math Dino: 디지털 치료용 러닝 액션 게임

Math Dino는 난산증(Dyscalculia)을 겪는 6~12세 아동을 위해 설계된
러닝 액션 기반의 디지털 치료 게임(Digital Therapeutic Game)입니다.
플레이어는 공룡이 탈출한 연구소에서 주인공 강 산이 되어 퀴즈를 풀며 도망쳐야 합니다.
게임을 통해 수 개념에 대한 자연스러운 노출과 반복 훈련을 제공함으로써 수학 불안 감소와 인지 기능 향상을 기대합니다.

##🎯 프로젝트 개요

- 플랫폼: Unity 6000.1.9f1
- 언어: C#
- 지원 언어(Localization): 🇰🇷 한국어, 🇺🇸 영어(미국/영국), 🇩🇪 독일어
- 타겟 연령: 초등학교 1~6학년 (6~12세)
- 치료 대상: 난산증(Dyscalculia)을 겪는 아동

##🧠 난산증이란?

난산증(Dyscalculia)은 지능이나 교육 기회와 무관하게 수학 개념을 이해하는 데 어려움을 겪는 학습장애입니다.
Math Dino에서는 다음 3가지 유형을 기준으로 퀴즈를 구성합니다:

1. 어휘적 난산증 (Lexical Dyscalculia) – 숫자 단어 인식에 어려움
2. 실용적 난산증 (Practical Dyscalculia) – 수의 양이나 크기 비교, 수 감각 부족
3. 연산 수행 난산증 (Arithmetic Dyscalculia) – 덧셈, 뺄셈 등 기초 연산 수행의 어려움

##🧩 게임 시나리오

10살 소년 강 산은 학교에서 공룡 박물관을 견학하던 중
수상한 엘리베이터를 타고 비밀 연구소로 이동하게 됩니다.
그곳에서 공룡들이 탈출하고, 강 산은 Jane 선생님과 함께 도망치기 위해
달리면서 퀴즈를 풀고 수리적 결정을 내려야 합니다.

##🧪 게임 특징

- 템플런 스타일 러닝 액션 + 수리 퀴즈 시스템
- 정답 시 +10초 / 오답 시 -5초 + 진동
- 난산증 유형별 맞춤 퀴즈
- 다국어 퀴즈 txt 파일 로딩
- 인지 기능 향상을 위한 반복 훈련 설계
- 정답률 분석 기반 확장 가능 구조

##📁 주요 폴더 구조

Assets/
├── Scripts/
│   ├── QuizManager.cs
│   ├── QuizLoader.cs
│   ├── QuizOptionCollider.cs
│   ├── TimeManager.cs
│   ├── PlayerController.cs
│   ├── GameManager.cs
│   └── ...
├── StreamingAssets/
│   ├── quiz_ko.txt
│   ├── quiz_en.txt
│   ├── quiz_de.txt

##⚙️ 주요 스크립트 설명

- QuizManager.cs: 퀴즈 출제, 정답/오답 판정, 다음 퀴즈 전환 관리
- QuizLoader.cs: 언어코드에 따라 quiz_xx.txt 파일을 읽어 퀴즈 데이터를 로드
- QuizOptionCollider.cs: 플레이어와 옵션 오브젝트 충돌 시 정답 여부 판별
- TimeManager.cs: 시간 증가/감소, 슬라이더 UI 및 로컬라이징 시간 텍스트 처리
- PlayerController.cs: 캐릭터 자동 전진, 달리기 애니메이션 제어
- GameManager.cs: 게임 오버 시 애니메이션 처리 및 상태 전환
- BGMManager.cs: 씬에 따라 BGM을 무작위로 재생, 볼륨 저장 기능 포함
- CameraFollow.cs: 카메라가 플레이어를 따라가도록 위치 조정
- MainMenuManager.cs: 메인 화면의 시작/옵션/종료 버튼 기능 처리
- OptionsController.cs: 언어 설정, BGM/SFX 조절, 옵션 UI 관리
- PauseManager.cs: 일시정지 및 재시작, 메인 메뉴로 이동 처리
- QuizData.cs: 퀴즈 데이터 구조를 정의 (문제, 보기1, 보기2, 정답 번호 등)

##📊 향후 확장 가능 기능

- 유형별 정답률 기록 및 학습 분석
- 퀴즈 난이도 자동 조절 알고리즘
- 정답/오답 팝업 UI 추가 (O / X 애니메이션)
- 게임 종료 후 리포트 화면

##💡 제작 의도

Math Dino는 단순한 교육 게임이 아니라,
난산증 치료를 위한 디지털 치료제로 발전할 수 있도록 설계되었습니다.
놀이 기반 수학 노출, 반복 훈련, 정서적 안정감 제공을 통해
아동이 스스로 수학을 두려워하지 않고 익힐 수 있도록 도와주는 것이 목표입니다.
