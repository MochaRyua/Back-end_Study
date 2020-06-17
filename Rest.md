# Rest

#### Rest?

위에 말한 방식은 __간단__하게 말하며이고 정의된 의미로 말하자면 
=======
__Rest__ 란(Representational State Transfer)의 약자로 간단하게 말하자면 네트워크 상에서 _클라이언트와 서버 사이통신 방법중 하나이다._  

위에 말한 방식은 __간단__ 하게 말하며이고 정의된 의미로 말하자면 
>>>>>>> master

- "웹에 존재하는 모든 자원에 고유한 URI를 부여해 활용"하는 것으로 , 자원을 정의하고 자원에 대한 주소를 지정하는 방법론을 의미한다.
-  HTTP 통신에서 어떤 자원에 대한 CRUD 요청을 Resource와 Method로 표현하여 특정한 형태로 전달하는 방식

이렇게 2가지로 정의가 되어있다. 위 둘은 같은 말이며 이해할 수 있다면 가장 바람직하다.

Rest의 형식을 따른 시스템을 Restful이라고 부른다.

___

#### Rest 구성요소

- 자원(Resource(URI))
  - 모든 자원에는 각각의 고유 ID가 존재하고,  이 자원을 server에 요청을 한다.
  - 자원을 구별하는 ID는 HTTP URI다.
  - Client는 URI를 이용하여 자원을 지정하고 해당 자원의 상태(정보)에 대한 조작을 Server에 요청한다.

- 행위(Method) 
  - 서버에 요청을 보내는 방식은 4가지가 존재한다. "Get, Post, Put, Delete"가 존재한다. 이 4가지를 줄여 CRUD라고 하며 각각 처리에 맞는 Method를 사용하여 서버에 요청을 보내야한다.  

- 표현(Representation of Resource)
  - Client가 자원에 대해 요청을 하면 Server는 이에 적절한 응답을 한다.
  - Rest에서 JSON, XML, TEXT등 여러 형태로 나타낸다.
  - JSON or XML를 통해 데이터를 주고 받는 것이 일방적이다.



__여기서 URI란?__

Url은 인터넷의 자원을 가르키는 표준이름이다. Uri는 더 나아가 가르키는 자원이 어떤 자원인지 알고 있다.

URI > =URL

```
https://www.google.co.kr/search?q=uri
```

예를 들어 이런 주소가 존재한다.

```
https://www.google.co.kr/search
```

여기까지가 자원이 어디에 존재하는 알려주는 URL이 된다.

```
https://www.google.co.kr/search?q=uri
```

여기서 ?q=uri 이것을 포함한 것이 URI가 된다. q값에 따라 결과값이 다르기 때문이다. 

```
https://www.google.co.kr/search?q=uri
```

결론은 이 주소는 URI는 맞지만 URL은 아니다.



___

<<<<<<< HEAD
오늘은 친구들에게 알려줘야하는 자료이기 때문에 존칭을 쓰고 있다. 어색하다;;
=======
오늘은 친구들에게 알려줘야하는 자료이기 때문에 존칭을 쓰고 있다. 어색하다;;
>>>>>>> master
