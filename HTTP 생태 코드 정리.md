# HTTP 생태 코드 정리

> ### Client error responses

- 와탭에서 제공하는 URL Monitoring은 웹 서비스의 장애를 알려주는 서비스입니다. 웹 서비스에서 반환 되는 상태 코드가 4xx, 5xx로 나타나는 경우 경고 알람을 보내도록 되어 있습니다.
- 대표적인 코드로는 "404 Not Found"가 있습니다.



상태코드는 3자리 숫자로 만들어져 있으며 첫번째 자리는 1~5까지 제공됩니다. 그외 6부터 시작하는 상태코드는 서버 개발자가 따로 만든 코드입니다.

[https://ko.wikipedia.org/wiki/HTTP_%EC%83%81%ED%83%9C_%EC%BD%94%EB%93%9C](https://ko.wikipedia.org/wiki/HTTP_상태_코드)

위키백과에서 상태코드 숫자마다 뜻을 잘 적혀 있으니 참고하시면 도움이 많이 될 것 입니다.