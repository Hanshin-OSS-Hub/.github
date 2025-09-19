## 📘 Hanshin OSS Hub 팀별 Repository 운영 가이드

본 문서는 Hanshin OSS Hub Organization 내에서 캡스톤디자인 팀별 Repository를 운영하기 위한 절차를 안내합니다.
관리자는 각 팀별 Repository를 생성하고, 팀장은 해당 Repository의 Admin 권한을 통해 팀원을 초대하고 관리합니다.

### 1. 관리자(Admin, 교수/조교)의 역할

Hanshin-OSS-Hub Organization에서 팀별 Repository 생성
+ 예시: capstone25-easy-travel
+ 각 Repository에 해당 팀장 계정을 Admin 권한으로 초대

### 2. 팀장(Repo Admin)의 역할

팀장은 자신이 속한 Repository에서 팀원 관리 책임자 역할을 수행합니다.

#### 팀원 초대 절차
1. Repository 메인 화면 → 상단 메뉴에서 Settings 선택
2. 좌측 메뉴에서 Collaborators and teams 클릭
3. Add people 버튼 클릭 → 팀원 GitHub 계정 입력
4. 권한(Role) 선택
    + Write 권장 (코드 푸시 및 협업 가능)
    + 필요 시 Read 또는 Maintain 선택 가능
    + ⚠️ Admin 권한은 팀장 외 부여하지 않음
5. 팀원이 GitHub 알림/이메일로 전송된 초대를 Accept 하면 팀 Repo 접근 가능

### 3. 권한 관리 원칙
+ Hanshin OSS Hub 관리자: 모든 Repo에 Admin 권한 유지 (최종 관리/통제)
+ 팀장: 자신 팀 Repo의 Admin 권한
+ 팀원: Write 권한 부여

### 4. 권장 사항
README.md에는 다음 정보 포함
+ 프로젝트 개요
+ 팀원 명단 및 역할
+ 실행 방법/환경

주요 폴더 구조 예시
+ /docs   → 프로젝트 문서
+ /src    → 소스코드
+ /assets → 이미지/데이터

정기적으로 Commit & Push 수행하여 Repo를 최신 상태로 유지

### 5. 문의

Repo 관리와 관련된 문제가 발생하면 Hanshin OSS Hub 관리자에게 문의하세요.
+ Email: hyunahn@hs.ac.kr
