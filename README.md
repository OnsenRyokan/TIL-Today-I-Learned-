# TIL-Today-I-Learned-

###  __MVVM__ 
#####  MODEL VIEW VIEW MODEL로 구성되어 있는 디자인 패턴  
###  안드로이드 생명주기
###  Fragment
###  SharedPreparence
###  동기식 비동기식
###  OnResume, OnStart
###  Public, private , Protected
###  JAVA - Thread ,상속, 추상, 캡슐, 다형성
###  HTTP 요청 시 메소드 GET POST DELETE PUT PATCH ++
###  프로세스 쓰레드 
##### 프로세스 : 현재 메모리에 적재되어 실행 중인 프로그램
##### 프로그램 : 저장장치에 저장된 형태의 실행코드
##### 쓰레드 : 하나의 흐름만으로는 처리하기 어려울 때 또 하나의 처리흐름을 만든다
### 명시적 Intent, 암묵적 Intent
### Void,Object,String
##### 1. 먼저 클라이언트가 Redirect URL을 포함하여 Authorization server 인증 요청
##### 2. AuthorizationServer는 유저에게 로그인창을 제공하여 유저를 인증
##### 3. AuthorizationServer는 Authorization code를 클라이언트에게 제공
##### 4. Client는 코드를 Authorization server에 Access Token을 요청
##### 5. Authorization 서버는 클라이언트에게 Access token을 발급
##### 6. Access token을 이용하여 Resource server에 자원을 접근 가능
##### 7. 그이후에 토큰이 만료된다면 Refresh token을 이용하여 토큰 재발급 가능
### Api JSON 파싱 
###  ping / pull service
###  ICMP (Internet Control Message Protocol)  
#21/2/15
*웹 후크(웹 콜백, HTTP PUSH API) - 앱이 다른 앱에 실시간 정보를 제공하는 방법 - 사용을 위해서는 webhook 제공자, 서비스에게 요청을 전달할 url을 제공 그렇게 설정 하면  
웹 훅은 사용자의 http post 요청을 할 것이고 사용자는 이를 해석해야 한다. 대다수의 웹훅은 json , application/x-www-form-urlencoded, multipart/form-data로 데이터를  
post할 것이다.
*폴링 - 웹은 태생 자체(?)가 실시간을 위해 필수적인 요소인 지속적인 연결(Persistent connection)을 가질 수 없고 클라이언트에서 서버로 접속을 하면 서버는 응답을 하고  
연결이 끊어진다(HTTP의 특징)  따라서 웹에서 현재 운용되는 실시간 서비스들은 대부분 실시간이 아니다(10초~30초 정도의 단위라고 명시할 수는 있으나 완전 실시간은 아닌 것)  
폴링이란 하나의 어플리케이션이 충돌 회피 또는 동기화 처리 등을 목적으로 다른 어플리케이션의 상태를 주기적으로 검사하여 일정한 조건을 만족할 때 송수신등의 자료처리를 하는 방식 


