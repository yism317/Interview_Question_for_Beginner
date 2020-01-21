# Reverse Interview

> [@JaeYeopHan](https://github.com/JaeYeopHan): 한국어로 번역을 진행하다보니 현재 한국 상황에 맞게 끔 약간씩 수정을 했습니다. 또 낯선 용어가 있을 수 있어 해당 내용을 보충했습니다. 그만큼 의역도 많으니 본문도 함께 보시길 추천드립니다. (_원문: https://github.com/viraptor/reverse-interview_)

## 👨‍💻 회사에 궁금한 점은 없으신가요?

인터뷰를 마치고 한번씩은 들어봤을 질문이다. 이 때 어떠한 질문을 하면 좋을까? 적절한 질문들을 항목별로 정리해둔 Reverse Interview Question 목록이다.

## 💡이 목록을 이렇게 사용하길 기대합니다.

### 1. 우선 검색으로 스스로 찾을 수 있는 질문인지 확인해보세요.

- 요즘 회사는 많은 정보를 공개하고 있다. 인터넷에서 검색만으로 쉽게 접할 수 있는 것을 질문한다면 안 좋은 인상을 줄 수 있다. 지원하는 회사에 대해 충분히 알아본 후, 어떠한 질문을 할 지 생각해보자.

### 2. 당신 상황에서 어떤 질문이 흥미로운지 생각해보세요.

- 여기에서 '상황'이란 지원한 회사, 팀일 수 있고 자신이 지원한 포지션과 관련된 것을 말한다.

### 3. 그런 다음 질문하면 좋을 것 같아요.

- 확실한 건, 아래 리스트를 **전부 물어보려고 하면 좋지 않으니** 그러지 말자.

<br />

<br />

# 💁‍♂️ 역할 (The Role)

- on-call에 대한 계획 또는 시스템이 있나요? 있다면 어떻게 될까요? (그에 대한 대가는 무엇이 있나요?)
  - `on-call`이란 팀에서 업무 시간 외에 문제를 해결할 사람을 로테이션으로 지정하는 문화를 말한다.
- 평상 시 업무에는 어떠한 것들이 있나요? 제가 맡게 될 업무에는 어떠한 것들이 있을까요?
- 팀의 주니어 / 시니어 구성 밸런스는 어떻게 되나요? (그것을 바꿀 계획이 있나요?)
- 온보딩(onboarding)은 어떻게 이루어지나요?
  - `onboarding` 이란 조직 내 새로 합류한 사람이 빠르게 조직의 문화를 익히고 적응하도록 돕는 과정을 말한다.
- 제공된 목록에서 작업하는 것과 비교하여 얼마나 독립적 인 행동이 예상됩니까?
- 기대하는 근무시간, 핵심 근무 시간(core work hours)은 몇 시간인가요? 몇시부터 몇시까지 인가요?
  - `core work hours` 란 자율 출퇴근 시 출퇴근 시간이 사람마다 다를 수 있는데 이 때, 오피스에 상주하거나 회의에 참석할 수 있는 시간을 말한다.
- (제가 지원한) 이 포지션의 '성공'에 대한 정의는 무엇인가요? 개발 조직 (또는 팀)에서 목표로 하고 있는 KPI가 있나요?
  - KPI란 Key Performance Indicator의 줄임말로 핵심 성과 지표라고 할 수 있다. 개인이나 조직의 전략 달성에 대한 기여도를 측정하는 지표를 말한다.
- 제 지원에 대해 혹시 우려 사항이 있을까요? 
- 제가 가장 가까이 일할 사람에 대해서 이야기해 주실 수 있을까요?
- 제 직속 상사와 그 위 상사의 관리 스타일은 어떤가요? (마이크로 매니징 혹은 매크로 매니징) 

# 🚀 기술 (Tech)

- 회사 또는 팀 내에서 주로 사용되는 기술 스택은 무엇인가요? 현재 제품는 어떤 기술 스택으로 만들어져 있나요?
- 소스 컨트롤(버전 관리)은 어떻게 이루어지고 있나요?
- 작성한 코드는 보통 어떻게 테스트가 이루어지나요?
  - 표준화된 테스트 환경이 있는지 테스트 코드는 어느 정도 작성되고 있는지를 포함할 수 있는 질문이라고 생각한다.
  - 지원한 회사의 주요 프로덕트와 팀, 포지션과 관련하여 좀 더 질문을 구체화 할 수 있다. 앱 내 웹뷰를 만드는 팀이라면 작성한 웹뷰 코드를 테스트할 수 있는 프로세스를 질문할 수 있다.
- 버그는 어떻게 보고되고 어떻게 관리되고 있나요?
  - 어떤 BTS(Bug Tracking System)을 사용하고 있는지 질문을 구체화 할 수 있다.
  - 좀 더 구체적으로는 QA 팀이 있는지, 협업은 어떻게 이루어지는지도 물어볼 수 있다.
- 변경 사항을 어떻게 통합하고 배포하나요? CI / CD는 어떻게 이루어지고 있나요?
- 버전 관리에 기반한 인프라 설정이 있나요? / 관리는 어떻게 이루어지나요?
- 일반적으로 기획(planning)부터 배포까지 진행되는 워크 플로우(Work Flow)에 대해 설명해주실 수 있나요?
- 장애에 대한 대응은 어떻게 이루어지나요?
- 팀 내에서 표준화 된 개발 환경이 있나요?
- 제품에 대한 로컬 테스트 환경을 설정할 수 있는 프로세스가 있나요?
- 코드나 의존성(dependencies) 보안 이슈에 대해서 얼마나 빠르게 검토하고 있나요? 
- 모든 개발자들에게 자신 컴퓨터 로컬 어드민에 접근하는 걸 허용하고 있나요?
- 당신의 기술적 생각 혹은 비전에 대해 말씀해 주실 수 있을까요? 
- 코드에 대한 개발자 문서가 있나요? 고객을 위한 별도의 문서가 또 있을까요?
- 정적 코드 분석기를 사용하고 있나요?
- 내부/외부 산출물 관리는 어떻게 하고 있나요? 
- 의존성 관리는 어떻게 하고 있나요?

# 👨‍👩‍👧‍👧 팀 (The Team)

- 현재 팀에서 이루어지고 있는 작업(Task)은 어떻게 구성되어 있나요?
- 팀 내 / 팀 간 커뮤니케이션은 보통 어떻게 이루어지나요? 어떤 도구를 사용하나요?
- 구성원간의 의견 차이가 발생할 경우 어떻게 의사 결정이 이루어지나요?
- 주어진 작업에 대해서 누가 우선 순위와 일정을 정하나요?
- 해당 내용에 대해 다른 의견을 제시한다면(pushback) 그 다음 의사 결정이 어떻게 이루어지나요?
- 매주 어떤 종류의 회의가 있나요?
- 제품 또는 서비스 배포 주기는 어떻게 이루어지나요? (주간 릴리스 / 연속 배포 / 다중 릴리스 스트림 / ...)
- 제품에서 장애가 발생할 경우 추가 대응은 어떻게 이루어지나요? 책임자를 찾고 탓하지 않는(blameless) 문화가 팀 내에 있나요?
- 팀이 아직 해결하지 못한 문제는 무엇이 있나요?
  - 불필요한 반복 작업을 자동화하지 못한 부분이 있나요?
  - 채용 시 필요한 인재에 대한 기준이 명확하게 자리 잡았나요?
- 프로젝트 진행 상황은 어떻게 관리하고 있나요?
- 기대치와 목표 설정은 어떻게 하고 있으며, 누가 정하나요?
- 코드 리뷰는 어떠한 방식으로 하나요?
- 기술적 목표와 비지니스 목표의 균형은 어떠한가요? 
- 역자 추가) 팀 내 기술 공유 어떻게 이루어지고 있나요?
 
# 👩‍💻 미래의 동료들 (Your Potential Coworkers)
- 그들이 여기서 일함으로써 가장 좋은 점은 뭔가요?
- 그럼, 가장 싫어하는 점은 뭔가요? 
- 만약 가능하다면, 바꾸고 싶은 것은 무엇인가요? 
- 이 팀에서 가장 오래 일한 사람은 얼마나 다니셨나요? 

# 🏬 회사 (The Company)

- 회의 또는 출장에 대한 예산이 있나요? 이를 사용하는 규칙은 무엇인가요?
- 승진을 위한 별도의 과정이 있나요? 일반적인 요구 사항이나 기대치는 어떻게 전달받나요?
- 기술직과 경영직은 분리되어 있나요?
- 연간 / 개인 / 병가 / 부모 / 무급 휴가는 얼마입니까?
- 현재 회사에서 진행중인 채용 상태는 어떤가요?
- 전자 책 구독 또는 온라인 강좌와 같이 학습에 사용할 수있는 전사적 리소스가 있나요?
- 이를 지원 받기 위한 예산이 있나요?
- FOSS 프로젝트에 기여할 수 있나요? 별도 승인이 필요한가요?
  - FOSS란 Free and Open Source Software, 즉 오픈소스 프로젝트를 말한다.
- 경업 금지 약정(Non-compete agreement)나 기밀 유지 협약서(non-disclosure agreement)에 사인해야하나요?
- 앞으로 5/10년 후의 이 회사가 위치에 있을 거라 생각하나요?
- 회사 문화의 격차가 무엇이라고 생각하나요? 
- 이 회사의 개발자들에게 클린 코드는 어떤 의미인가요? 
- 최근, 이 회사에서 성장하고 있다라고 생각이 든 사람이 있었나요? 어떻게 성장하고 있었나요? 
- 이 회사에서의 성공이란 무엇인가요? 그리고 그걸 어떻게 측정하나요? 
- 이 회사에서 워라밸(work-life balance)은 어떤 의미 인가요? 

# 💥 충돌 (Conflict) 

- 구성원간의 의견 차이가 발생할 경우 어떻게 의사 결정이 이루어지나요?
- 해당 내용에 대해 다른 의견을 제시한다면(pushback) 그 다음 의사 결정이 어떻게 이루어지나요? (예를 들어, "이건 기간 안에 못 할 것 같습니다.") 
- 불가능한 일의 양 혹은 일정이 들어왔을 때 어떻게 하나요?
- 만약 누군가 우리의 프로세스나 기술 등을 발전시킬 수 있는 부분을 이야기하면, 어떻게 진행되나요?
- 경영진의 기대치와 엔지니어 팀의 성과가 차이가 있을 때, 어떻게 되나요?
- 회사에 안 좋은 상황(toxic situation)이였을 때 어떻게 대처 했었는지 이야기해  주실 수 있을까요? 

# 🔑 사업 (The Business)

- 현재 진행 중인 사업에서 수익성이 있나요? 그렇지 않다면, 수익을 내기까지 얼마나 걸릴 것 같나요?
- 자금은 어디에서 왔으며 누가 높은 수준의 계획 / 방향에 영향을 미치나요?
- 제품 또는 서비스를 통해 어떻게 수익을 올리고 있나요?
- 더 많은 돈을 버는 데 방해가되는 것은 무엇인가요?
- 앞으로 1년, 5년 동안의 회사 성장 계획이 어떻게 되나요?
- 앞으로의 큰 도전들은 어떤 것들이 있다고 생각하시나요?
- 회사의 경쟁력은 무엇이라 생각하시나요? 

# 🏠 원격 근무 (Remote Work)

- 원격 근무와 오피스 근무의 비율은 어느정도 되나요?
- 회사에서 업무 기기를 제공하나요? 새로 발급받을 수 있는 주기는 어떻게 되나요?
- 회사를 통해 추가 액세서리 / 가구를 구입할 수 있도록 지원되는 예산이 있나요?
- 원격 근무가 가능할 시, 오피스 근무가 필요한 상황은 얼마나 있을 수 있나요?
- 사무실의 회의실에서 화상 회의를 지원하고 있나요?

# 🚗 사무실 근무 (Office Work)

- 사무실은 어떠한 구조로 이루어져 있나요? (오픈형, 파티션 구조 등)
- 팀과 가까운 곳에 지원 / 마케팅 / 다른 커뮤니케이션이 많은 팀이 있나요?

# 💵 보상 (Compensation)

- 보너스 시스템이 있나요? 그리고 어떻게 결정하나요?
- 지난 보너스 비율은 평균적으로 어느 정도 되었나요?
- 퇴직 연금이나 관련 복지가 있을까요?
- 건강 보험 복지가 있나요?

# 🏖 휴가 (Time Off)

- 유급 휴가는 얼마나 지급되나요?
- 병가용과 휴가용은 따로 지급되나요? 아니면 같이 지급 되나요?
- 혹시 휴가를 미리 땡겨쓰는 방법도 가능한가요?
- 남은 휴가에 대한 정책은 어떠한가요?
- 육아 휴직 정책은 어떠한가요? 
- 무급 휴가 정책은 어떠한가요? 

# 🎸 기타

- 이 자리/팀/회사에서 일하여 가장 좋은 점은 그리고 가장 나쁜 점은 무엇인가요?

## 💬 질문 건의

추가하고 싶은 내용이 있다면 언제든지 [ISSUE](https://github.com/JaeYeopHan/Interview_Question_for_Beginner/issues)를 올려주세요!

## 📝 References

- [https://github.com/viraptor/reverse-interview](https://github.com/viraptor/reverse-interview)
- [https://www.joelonsoftware.com/2000/08/09/the-joel-test-12-steps-to-better-code/](https://www.joelonsoftware.com/2000/08/09/the-joel-test-12-steps-to-better-code/)