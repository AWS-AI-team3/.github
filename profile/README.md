# AWSGBSA : AWS 인공지능 전문인력 양성과정 프로젝트
## ✅ 프로젝트 소개 및 성과
- 🗓️ 프로젝트 기간
: 2025.08.04 ~ 2025.08.22

- 🏆 프로젝트 성과 : 2025 경기도 AWS 인공지능 전문인력 양성과정 프로젝트 발표회 최우수상(1등) 수상

  <img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/a290fdcc-4c25-4db4-affa-3f4ac22a2c06" />

- 👥 프로젝트 팀원
  | _이름_ | 박재원 | 박세현 | 이경민 | 허서현 | 황예현 |
  |:-----:|:----:|:-----:|:----:|:----:|:-----:|
  | ___역할___ | FE, 로컬AI | AI | BE, 인프라 | UX/UI디자인 | DS |
  |  | <a href="https://github.com/ashcircle03"><img src="https://avatars.githubusercontent.com/u/113187386?v=4" width="64" height="64"></a> | <a href="https://github.com/sehyun734"><img src="https://avatars.githubusercontent.com/u/101646633?v=4" width="64" height="64"></a> | <a href="https://github.com/rudalsss"><img src="https://avatars.githubusercontent.com/u/122061889?v=4" width="64" height="64"></a> | <a href="https://github.com/navv0"><img src="https://avatars.githubusercontent.com/u/224919441?v=4" width="64" height="64"></a> | <a href="https://github.com/Zio0714"><img src="https://avatars.githubusercontent.com/u/132100220?v=4" width="64" height="64"></a>

---

## ✅ 프로젝트 개요
저희 서비스의 출발은 영화 **아이언맨**이었습니다.  
토니 스타크가 조력자 **자비스**를 단순한 **제스처**와 음성으로 제어하는 장면은, “비접촉 제어가 **현실화**된다면 얼마나 **유용할까?**”라는 **영감**을 주었습니다.

![iron-man](https://github.com/user-attachments/assets/136de13e-00e7-4109-b6be-23e865205a1e)

### 📌 [ 데이터 분석 ] 실생활 적용 사례 & 시장분석
비접촉 제어 서비스의 실생활 적용 가능성과 시장성을 검증하기 위해 자체적으로 데이터를 분석했습니다. 데이터를 크롤링 기법을 통해 직접 수집하고, AWS의 Sagemaker를 통해 머신러닝 기반 분석을 진행했습니다.

```
- 수집 방식: 웹 크롤링
- 수집 범위: 2023 ~ 2025년 공개 보도자료·공개 요약 페이지
- 데이터 크기: 약 100개의 수치 데이터
- 주요 출처 : Precedence Research, Custom Market Insights, Grand View Research, Fortune, TBRC, Mordor, Towards Automotive
```
<p align="center">
<img width="46%" alt="image" src="https://github.com/user-attachments/assets/f2f64100-cdbb-4f26-b1e2-605e5b9d33a2" />
<img width="46%" alt="image" src="https://github.com/user-attachments/assets/2601a923-78dd-41fd-a9b6-3144f23a3c65" />
</p>

📊 모션제스처 사용사례 분석결과, 다음과 같은 환경에서 **비접촉 제어는 단순 편의가 아니라 필수 요건**임을 확인했습니다.
- 수술실 : 손이 자유롭지 않은 상황에서 모션/음성 제어로 효율성 향상
- 클린룸 : 접촉 오염 방지를 위해 비접촉 인터페이스 필수
- 특수 장비 환경 : 예) Gorilla Glass 기반 기기에서도 장갑 낀 채 제스처 사용 가능

📊  모션제스처 사업의 성장현황에 대한 분석결과,
- 시장 규모는 2025년 약 257억 달러에서 → 2034년 약 344억 달러로 성장
- 연평균성장률(CAGR)은 무려 19%로 예측  

이를 통해 모션 제스처는 단순한 유행이 아니라, **지속적으로 성장하는 글로벌 산업 트렌드**임을 확인할 수 있었습니다.

### 📌 문제상황 및 아이디어
제스처기반 비접촉 제어기술이 상용화되어 성공한 사례는 AR/VR, 자동차, 헬스케어, 스마트홈, 게임 분야로 다양했지만, 이런 모션제스처 기술을 범용적으로 지원해주는 서비스는 부재하다는 문제를 마주 할 수 있었습니다.  
<p align="center">
<img width="674" height="380" alt="idea" src="https://github.com/user-attachments/assets/244a2bbe-4bb3-45ca-980d-3d9a613cd34f" />
</p>

하지만 일상적인 상황에서도 비접촉 제어의 필요성은 다양합니다. 다음은 실제로 팀원들이 **일상생활속 비접촉 컴퓨터제어 서비스**가 필요하다고 느낀 순간들입니다.
따라서 저희는 범용적으로 누구나 일상생활에서 사용할 수 있는 **모션제스처 기술 서비스**를 만들고자 했습니다.

### 📌 예상문제상황 및 대응방안
<p align="center">
<img width="46%" alt="image" src="https://github.com/user-attachments/assets/180b702a-9ff3-4988-9ffb-566040646c5c" />
<img width="46%" alt="image" src="https://github.com/user-attachments/assets/3b41c4f0-6257-4462-8f9b-e5d35a124d0a" />
</p>

**비접촉제어 범용 서비스**를 기획하면서 다음과 같은 잠재적 문제를 예상하였고, 이에 대한 보완책을 마련하여 서비스를 완성했습니다.
- 컴퓨터 제어의 도구로 제스처 단독 사용 시 높은 오류 가능성 ➡️ 음성제어 기능을 도입하여 보조적인 제어도구로 활용
- 로컬 컴퓨터를 제어한다는 특성상 보안·권한 문제 발생가능성 ➡️ 비접촉 얼굴인증 기능을 도입하여 권한 관리 및 사용자 인증을 강화

또한 이러한 대응 방안이 실제로 타당한지 검증하기 위해, AWS Sagemaker를 활용하여 모션 제스처 서비스 관련 사례 데이터 분석을 추가적으로 진행하였습니다.
```
- 수집 방식: 웹 크롤링 (requests + BeautifulSoup, Selenium 등 활용)
- 수집 범위: 2023~2025년 공개 문서/뉴스/가이드라인
- 데이터 크기: 총 1,200 문서, 약 2.5M 토큰
- 주요 출처 : 질병관리청 감염관리 지침 / WHO, CDC 공식 가이드 문서 / 메디칼타임즈, 메디게이트 뉴스 기사 / 클린룸 관련 기업(예: TSI, Honeywell) 백서
```
<p align="center">
<img width="46%" alt="image" src="https://github.com/user-attachments/assets/835d6595-6391-41d1-9490-8fc2f9051b1f" />
<img width="46%" alt="image" src="https://github.com/user-attachments/assets/7441c255-7bae-4fc9-924b-80a93fedd5d2" />
</p>

📊 데이터 분석결과
- 제스처에 **보조 수단(자막, 음성)** 을 결합하면 오류 확률이 20%에서 **2% 이하**로 크게 감소
- 특히 음성은 제스처보다 **더 직관적이고, 강력한 제어 수단**으로 작동

더불어 얼굴인식 또한 사용자의 얼굴이라는 고유한 생체정보를 활용하여 인증·인가·권한처리를 수행하고 기존의 로그인 방식을 결합하여 MFA 다중인증 수준의 보안성을 확보할 수 있을 것이라는 기대를 하게 되었습니다.


### 📌 서비스 정의
<img alt="image" src="https://github.com/user-attachments/assets/a90945ec-130e-41ee-ad17-9274b990538d" /><br>

결과적으로 정립된 **시그마(Sigma) 서비스**는 **" 범용 사용자들을 위한 비접촉 컴퓨터 제어 서비스 "** 입니다.

- 가장 주된 방식으로, 모션 제어(gesture)를 통해 제스처로 마우스를 대체합니다. ✋🏻
- 더불어 보조적인 음성 제어(voice)를 통해 직관적인 사용성을 제공하고, 키보드를 대체하며 오류를 보완하도록 합니다. 🔊
- 마지막으로 기능 사용 전에 얼굴인증을 통해 비접촉식 MFA로 보안을 강화하고자하였습니다. 🙂

즉, **얼굴 + 모션 + 음성**을 결합하여 누구나 사용할 수 있는 **완전한 비접촉 환경**을 제공하는 것이 저희 시그마의 최종 목표입니다.

---

## ✅ 사용자 시나리오
### 1. 구글 OAuth 로그인
사용자는 Google OAuth를 통해 간단히 서비스에 로그인합니다. 계정 선택 후 인증 절차가 완료되면, 서비스 접근이 가능해집니다.  
<p align="center">
<img width="672" height="381" alt="image" src="https://github.com/user-attachments/assets/16185f11-f375-4598-af7e-97f8da9cce49" />
</p>

### 2. 얼굴 등록 (Face Enrollment), 얼굴 인증 (Face Authentication)
- 최초 로그인 후 사용자는 자신의 얼굴을 등록합니다. 얼굴 등록이 실패하면 업로드된 이미지는 즉시 삭제됩니다. 등록이 성공하면 S3에 안전하게 저장되고, 사용자 정보에 얼굴 데이터가 반영됩니다.
  👉 추후 얼굴 인증 및 MFA(다중 인증) 기반 권한 제어에 활용
- 서비스 이용 시, 사용자는 등록된 얼굴 정보로 인증을 진행합니다. 인증 실패 시 업로드 이미지는 삭제되고, 성공 시 사용자 기반 세션이 발급됩니다. 세션은 일정 시간(30분) 동안 유효하며 이후 재인증이 필요합니다. 
👉 비접촉 방식으로 사용자 보안 강화, 자동 세션 관리
<p align="center">
<img width="46%" alt="image" src="https://github.com/user-attachments/assets/26a5bcbb-878c-4ffa-8e61-53154096769f" />
<img width="46%" alt="image" src="https://github.com/user-attachments/assets/18ffc16f-3882-4821-aef0-efe69d2ce0d9" />
</p>

### 3. 홈 화면 (트래킹 & 사용자 모션 설정)
로그인 및 인증 완료 후 홈 화면에 진입합니다.
- 사용자 정보: Google 프로필 및 요금제(추후 유료 모델 확장 가능) 확인.
- 트래킹 기능: 카메라를 통한 실시간 손동작 추적 활성화.
- 모션 설정: 사용자가 특정 손동작을 클릭, 붙여넣기 등 컴퓨터 제어 동작과 매핑 가능. ( 중복된 모션정의는 에러로 제어 )
<p align="center">
<img width="672" height="380" alt="image" src="https://github.com/user-attachments/assets/895ca204-e44a-48e9-8252-cba057dfbe91" />
</p>

### 4. 모션 트래킹을 통한 컴퓨터 제어 
👉 실제 마우스/키보드 입력을 대체하는 비접촉식 인터랙션  
사용자의 손동작(제스처)이 실시간으로 인식되어 컴퓨터 제어 동작으로 매핑됩니다.
<p align="center">
<img width="673" height="379" alt="image" src="https://github.com/user-attachments/assets/f2eabcc8-9f15-4db9-bf83-4121fb0b59ed" />
</p>

### 5. 음성 명령을 통한 컴퓨터 제어
👉 제스처와 음성을 결합하여 오류를 줄이고 직관적인 사용성을 제공  
사용자가 음성 제스처(엄지+약지)를 취하면 음성인식 모드가 활성화됩니다. 이후 발화한 명령어가 시스템 제어로 반영됩니다.
<p align="center">
<img width="673" height="380" alt="image" src="https://github.com/user-attachments/assets/035f9900-de60-48a8-b341-f0dbed277da3" />
</p>

---

## ✅ 아키텍처 및 사용기술
<img alt="image" src="https://github.com/user-attachments/assets/f328dc10-b74c-4ec1-b9c0-ab268831a72a" />

### 🔸 Front-End
<img width="674" height="377" alt="image" src="https://github.com/user-attachments/assets/e4719a07-20d6-447d-8dee-afa100b3a2dc" />

- 확장성을 고려한 flutter 프레임워크 이용 & Figma로 UI 디자인
- 로컬 컴퓨터 제어를 위한 python 스크립트 작성
- pyautogui를 이용한 마우스 제어 & pyperclip을 이용한 클립보드 접근
- cv2, MediaPipe를 이용한 손 랜드마크 추출 & pyqt를 이용해 손 랜드마크 오버레이 표시
- subprocess를 이용한 AWS Bedrock FM(Nova)으로부터 받은 시스템 명령어 실행

### 🔸 Back-End
<img width="674" height="380" alt="image" src="https://github.com/user-attachments/assets/8a024a45-60d7-436d-aae0-cc8c5dc62264" />

- Java17기반 Springboot 3.3.2 - webclient를 사용하여 외부 AI서버와 통신
- 서버 배포운영환경은 AWS의 주요 리소스인 EKS, Aurora DB, S3를 사용하여 안정적이고 확장가능한 서버환경을 구축
- Route53을 통해 고유 도메인을 발급받고 ACM으로 TLS인증서를 적용하여 안전한 Https통신을 보장
- DevOps환경을 위한 CI/CD 파이프라인을 구축 : Git webhook으로 트리거 -> Jenkins 빌드 파이프라인 -> Docker image ECR에 저장 -> ArgoCD는 GitOps기반 반자동화 배포

### 🔸 AI
<img width="673" height="379" alt="image" src="https://github.com/user-attachments/assets/990c642f-6ba0-4477-a375-fdff032772a3" />

- AWS Rekognition의 얼굴 감지와 유사도 검사 기능을 통해 얼굴 인증 기능을 구현
- AWS Transcribe streaming을 이용한 음성 실시간 전사
- AWS Bedrock FM(AWS Nova)를 이용한 사용자 명령에 대한 시스템 명령어 변환 + Local Agent를 이용해 사용자 명령의 부족한 정보를 취합
- AWS SAM을 이용해 람다 배포, API 게이트웨이를 이용해 AI 백엔드 서버 배포
---

## ✅ 주요기능 및 기술적 특징
### 🔊 실시간 오디오 전사 기능 (Real-time Audio Transcription)
<img alt="image" src="https://github.com/user-attachments/assets/fc15d838-1884-40cd-9018-f560c33d6451" /><br>

- AWS Transcribe Streaming 기반
- 웹소켓 기반 스트리밍 방식 → 기존 8초 지연 문제 해결
- 오버랩(Overlap) 기법으로 청크 간 단절 보완 → 정확도 + 실시간성 확보

### 🔄 연계성을 위한 로컬에이전트 기능 (Local Agent for Contextual Connectivity)
<img alt="image" src="https://github.com/user-attachments/assets/85d3ca5e-1109-42b4-87cf-04756bc021ba" /><br>

- Bedrock 기반 LLM + 로컬 에이전트 동작
- 로컬 정보(운영체제, 파일 경로 등) 필요 시 → 로컬 에이전트가 보완 후 전달
- AI 서버 ↔ 로컬 컴퓨터 간 정보 단절 문제 해결

### 🔒 보안성을 강화하는 얼굴인증 기능 (Face Authentication for Security)

<img alt="image" src="https://github.com/user-attachments/assets/497a36b3-c5f5-40cd-9283-145de01cfc21" />

- 얼굴인증구조
  - 2단계 얼굴인증구조 : 1단계 detect( 인증가능한 정면 인간 얼굴 여부 확인 - 필터링, 유효성 확인 ) ➡️ 2단계 verify( 사용자 등록 얼굴과 일치 여부 확인 )
  - Rekognition의 처리 호출은 반드시 private subnet에 위치한 EKS 백앤드로직을 거쳐 실행 → API 요청 무단 우회를 방지하고 안정성, 통제력 확보

<img alt="image" src="https://github.com/user-attachments/assets/f2c8d1c9-fb70-439e-ae1b-7679c678b251" />
  
- 데이터 처리
  - Presigned URL을 통한 S3 업로드 : 퍼블릭 접근을 모두 차단한 private S3상태를 유지하면서 업로드 작업을 서버 중앙화하지 않고 부하분산
  - UserID 기반 경로 검증

<img alt="image" src="https://github.com/user-attachments/assets/cd01c479-4648-493f-b54a-a66095858874" />

- 네트워크 보안
  - public 업로드 경로 : 외부 프론트에서 presigned URL을 통해 S3에 즉시 업로드 처리
  - private 관리경로 : EKS ↔ S3는 VPC Endpoint 기반 AWS 내부망 통신 / 민감 작업(삭제·관리)은 인터넷을 거치지 않음, 더불어 NAT 게이트웨이 미사용으로 보안 + 비용 최적화

<img alt="image" src="https://github.com/user-attachments/assets/aca7b283-2805-4c22-911f-2202285e1833" />

- 인증 지속성 : 비접촉식 MFA
  - 로그인을 통한 accessToken과 별도로 관리되는 FaceSession을 발급
  - 비접촉식 MFA 이중인증으로 활용가능 ( Oauth기반 서비스 사용자 로그인 + 얼굴인증기반 기능사용자 로그인 )

### ✋🏻 지연감소를 고려한 제스쳐인식 기능 (Gesture Recognition with Low Latency)
<img alt="image" src="https://github.com/user-attachments/assets/63ea1897-2d25-4296-8a38-dc5af152d63f" /><br>

- 실시간 모션 트래킹 기반 손동작 제어
  - Google MediaPipe Hand Landmarker를 이용한 손 랜드마크 감지
- 기본 제스처 정의(클릭, 스크롤, 붙여넣기 등) + 동작 지정 가능
- 로컬 내부 통신을 이용하여 통신 지연 최소화 & 직관적 사용자 경험 제공

---

## ✅ 시연영상
### 얼굴인증
https://github.com/user-attachments/assets/6b715337-470c-41f8-80ae-7c3e913b0252

### 제스처 인식 & 음성 명령
https://github.com/user-attachments/assets/789b7d79-1a83-4530-8752-660ab0c60686






