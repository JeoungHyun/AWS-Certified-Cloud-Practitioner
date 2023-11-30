# IAM
- AWS-Certified-Cloud-Practitioner 자격증 준비
- IAM 사용자를 생성 하고 그룹 배치 기능 => 글로벌 서비스에서 사용 가능

- 루트 계정은 사용자 생성할떄만 사용해야 함 절대 공유 금지!

- 하나의 사용자는 조직내의 한 사람에 해당 됨

- 그룹에는 오직 사용자만 배치 할 수 있음 (그룹안에 그룹 배치 X)

- 그룹에 포함되지 않은 사용자가 존재 할 수도 있음 (추천하진않음! 권한 추가할떄는 인라인 방식으로 가능)
또한 한 사용자가 다수의 그룹에 속할수도있음

- 사용자와 그룹을 사용하는이유
AWS 계정을 사용하도록 허용하기 위해서
허용하기 위해서는 권한을 부여해야함 IAM 정책

- JSON 문서로 지정 가능
최소권한의 원칙이 기본임!

- 정책 구조
 Effect, Principal Action, Resource에 대해서 잘 알아야됨

- IAM -Password Policy 비밀번호 정책

- MFA (다요소인증)
옵션으로는 가상MFA 장치 Google Auth
U2F yubikey 

- Access management에서
- Account setting에서 비밀번호 정책 사용가능

- aws 접근방법
- 콘솔에
- CLI  엑세스키로 접근
- SDK 엑세스키로 접근
