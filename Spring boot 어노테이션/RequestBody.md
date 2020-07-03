# RequestBody 

spring boot를 처음 시작했다면 값을 받아올때 어떤 형식으로 받을까? 라는 고민들 했을 것이다.

```
@GetMapping
public String test() {
	return "hello";
}
```

이런 코드가

```
@GetMapping
public String test(@RequsetBody User user) {
	return user.getUserId;
}
```

이렇게 변화한 것을 보았을 것이다. 그럼 @RequserBody는 무엇일까?

__@RequserBody__ 는 Http 요청의 Body안에 데이터를 받겠다~ 라고 말하는 것이다.  

좀더 어렵게 말하면 HTTP 요청의 body 내용을 자바 객체로 매핑하는 역할을 한다. 

이것이 끝이면 하나를 추가로 말하자면 @ResponseBody도 있는데 사용하지 않는 이유는 이미 @RestController를 사용하기 때문에 사용하지 않아도 자동으로 body로 보내지게 된다.