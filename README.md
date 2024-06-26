# WWDC24-iOS18

### DAY 1
## iOS 18

- 지원 기기
  - iOS 17과 동일
  - SE 2세대 이상
  - XR, XS, XS Max
  - 11 시리즈 이상
- 홈 화면
  - 앱 아이콘, 위젯 위치 자유롭게 조정 가능
  - 다크모드에서 앱 아이콘 색상 자동 변경
  - 사용자가 앱 아이콘 색상 지정 가능
- 제어 센터
  - 제어 센터 커스텀 가능
  - 제어 API 신규 생성
  - 잠금 화면의 카메라, 손전등 기능을 변경 가능
- 보안
  - 앱 잠금 기능 추가
  - 앱 숨김 기능 추가
  - 앱에서 사용할 수 있는 연락처 특정 가능
- 메세지
  - Tapbacks에 이모지 사용 가능
  - Send Later(예약 전송 기능) 추가
  - Text Formatting(볼드, 밑줄 등 효과) 추가
  - Text Effects(텍스트 애니메이션) 추가
  - 인터넷 연결 없이 위성을 통해 전송 가능
- 지갑
  - Tap to Cash(폰을 서로 맞대어 Apple Cash 전달 가능) 추가
- 사진
  - 상단엔 격자 사진들, 하단엔 Collections(날짜, 인물, 여행 등)
 
<br>

## Audio, watchOS, iPadOS, macOS

- 에어팟
  - 고개 움직임으로 시리에게 응답 가능
- watchOS
  - 운동 앱에 온동 강도, 운동량 표시
- iPadOS
  - 탭 막대 기능 및 API 추가
  - SharePlay를 통한 원격 화면 조종 가능
  - 계산기 추가
  - Math Notes 기능(펜슬로 수식 입력 시 자동으로 결과를 출력, 그래프 생성) 추가, 메모 앱에서도 사용 가능
- macOS
  - Sequoia
  - 아이폰 미러링, 맥으로 아이폰 조종 가능, 아이폰은 잠금 상태인 채로 맥에서 사용 가능
 
<br>

## Apple Intelligence

- 지원 기기
  - iPhone 15 Pro 이상
  - M1 칩 이상 탑재 iPad, Mac
- 아키텍처
  - 온디바이스 처리 원칙
  - 불가피할 경우 서버 활용
  - 서버 활용 시 비공개 클라우드 컴퓨팅을 활용해 개인 정보 보호
  - 필요 시 GPT-4o 활용(사용 시 허용 알럿)
- Siri
  - 타이핑으로 사용 가능
  - App Intents API를 이용해 앱에 AI 활용 가능
- Genmoji
  - 상황에 맞는 이모지 생성 기능
- Image Playground
  - 텍스트 입력으로 이미지 생성
  - Image Playground API를 이용에 앱에 이미지 생성 기능 활용 가능
- 사진
  - 편집 기능 업데이트, Clean Up
  - 사진 검색 기능
- 전화
  - 녹음, 요약 기능 추가(사용 시 양측 고지)
- SDK
  - Image Playground API 제공
  - Writing Tools 기능은 자동 반영
  - SiriKit
  - App Intents API


<br>

## For Developers

- Writing Tools
  - TextField 사용 시 기능 자동 탑재
- Genmogi
  - 상황에 맞는 이모지 생성 기능
  - textView.supportsAdaptiveImageGlyph = true
  - AttributedString으로 처리
- Image Playground API
  - imagePlaygroundSheet(SwiftUI) -> imageURL
- Using AI Models
  - Pytorch Model -> CoreML Tools -> ML Package -> use model by CoreML Framework
- XCode
  - Predictive Code Completion(예측 및 자동 완성 제안)
  - Swift Assist(텍스트를 통해 코드 작성 요청 가능)
- Swift 6
  - Data-race safety(메모리 동시 접속 방지, 컴파일 시점, 코드 안전 고도화, 모듈 별로 Swift 6 사용 선택 가능)
- Swift Testing
  - 오픈소스, 크로스 플랫폼 지원
- Control Widget
  - Controls API를 통해 Control Widget을 생성해서 사용자가 제어센터에서 사용할 수 있도록 함
- 앱 아이콘, 위젯
  - 라이트, 다크, 틴트 모드로 표시
  - iOS 18에서부터 자동 지원
  - Xcode에서 각 모드 별 디자인 변형 가능

<br>
<br>

### DAY 2
