## HTTP/HTTPS

웹에서 데이터를 전송하는데 사용되는 프로토콜. 

### HTTP(HyperText Transfer Protocol)
- 웹 서버와 클라이언트 간에 하이퍼텍스트 문서를 전송하기 위한 기본 프로토콜.
- 기본적으로 80번 포트 사용.
- 데이터를 평문으로 전송하여 네트워크 상에서 데이터를 쉽게 가로챌 수 있어 데이터 유출 위험성.
- 민감하지 않은 정보를 전송하는데 사용.

### HTTPS(HyperText Transfer Protocol Secure)
- HTTP에서 보안 계층을 추가. SSL/TLS 프로토콜을 통해 데이터를 암호화하여 전송. 
- 기본적으로 443번 포트 사용.
- 공개키 암호화 방식을 사용하여 데이터를 암호화. SSL 인증서를 통해 서버의 신원 확인. 이를 통해 데이터 무결성과 인증 보장.
    - 공개키 암호화 방식
        - 한 쌍의 키가 존재하며, 하나는 특정 사람만이 가지는 개인키(또는 비밀키)이고 다른 하나는 누구나 가질 수 있는 공개키.
        - 하나는 자신이 보관, 다른 하나는 상대방에게 공개.
        - 공개키로 암호화된 데이터는 개인키로만 복호화 가능.
        - 개인키로 암호화된 데이터는 공개키로만 복호화 가능.
        - 다른 유저와 키를 공유하지 않더라고 암호를 통해 안전한 통신 가능.
- HTTPS를 사용하는 웹사이트는 검색 엔진 최적화(SEO)에 유리. 사용자에게 더 높은 신뢰성 제공.

### 차이점
- HTTP는 평문 통신이므로 보안에 취약.
- HTTPS는 암호화 통신으로 보안이 강화됨.
- HTTP는 속도면에서 더 빠르지만 보안이 취약하여 민감한 정보 전송에는 적합하지 않음.

