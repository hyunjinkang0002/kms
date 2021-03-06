## Secure Key Manager
기밀 데이터(데이터베이스 접속 정보, 앱키, 비밀번호 등), 대칭키, 비대칭키와 같이 애플리케이션 서버에 저장할 경우 보안 위험에 노출될 수 있는 데이터를 중앙 집중적으로 안전하게 관리하고, 인증을 통과한 클라이언트만 접근할 수 있게 제어하는 서비스입니다.

### 소개

#### 주요 기능
* 기밀 데이터를 안전하게 저장하고 관리합니다. API를 사용해서 기밀 데이터를 조회할 수 있습니다.
* 대칭키를 생성하고 관리합니다. API를 사용해서 대칭키로 데이터를 암/복호화할 수 있습니다.
* 비대칭키를 생성하고 관리합니다. API를 사용해서 비대칭키로 데이터를 서명/검증할 수 있습니다.
* 기밀 데이터, 대칭키, 비대칭키를 사용할 수 있는 클라이언트를 제어합니다. IP 주소 인증, MAC 주소 인증, 클라이언트 인증서 인증을 사용할 수 있습니다.

#### 서비스 대상
* 애플리케이션이 사용하는 기밀 데이터를 안전하게 관리하고 싶은 사용자
* 애플리케이션이 사용하는 암호키를 안전하게 보관하고 API로 데이터를 암/복호화하고 싶은 사용자
* 애플리케이션 간에 데이터를 전송할 때, 전송 과정에서 데이터 위변조가 없었는지 검증하고 싶은 사용자

### 요금

