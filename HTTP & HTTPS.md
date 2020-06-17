# HTTP & HTTPS

http 와 https 기본적으로 알아야하는 기본적인 지식, 소양이라고 생각합니다. 그래서 알지만 다시 한번 이해하는 

형식으로 정리를 해보겠다!

___

### HTTP와 HTTPS란

__http__ 는 (Hypertext Transfer Protocol)입니다. OSI 7계층 중 응용계층에 위치하고 있는 프로토콜이다. 

간단하게 말하다면 HTML같은 문서를 전송하기 위한 프로토콜이라고 생각하자. 



__https__ 는 (Hypertext Transfer Protocol Over Secure Socket Layer)의 약자로 말그대로 HTTP의 강화된 버전이다.

HTTP는 텍스트가 평문으로 노출되어 있다. 그렇기에 보안을 더욱 강화된것이 HTTPS인 것이다.

___

### SSL 과 TLS

HTTPS의 동작원리는 간단하게 말하자면 SSL이라는 보안 프로토콜 위에서 동작하는 HTTP라고 생각 할 수 있다.

이럼 SSL과 TLS를 좀 알고 있으면 된다.

__SSL__ 이란 보안 소켓 계층을 이르는 것으로 인터넷 상에서 데이터를 안전하게 전송하기 위한 인터넷 암호화 통신 

__프로토콜__ 을 말한다. 이 한마디에 간단하게 끝난다. 그럼 TLS는 무엇인가? 

IETF에 의해 SSL3.0을 이용해 TLS로 표준화 하였다. 즉 SSL = TLS이다. (SSL를 표준화 한 것이 TLS이다.)

___

### 결론

결과 적으로 __HTTP와 HTTPS__ 가 존재하는데 예전에는 HTTP를 사용했지만 HTTP는 내용이 평문화를 전송이 되기 

때문에 HTTPS라는 개념이 생겨났고 SSL과 TSL의 프로토콜 위에서 돌가는 프로토콜이다. 진짜 이 한줄로 

정리가 끝난다. 하지만 동작원리는 어렵기 때문에 따로 공부해 보길 바란다. ^^

