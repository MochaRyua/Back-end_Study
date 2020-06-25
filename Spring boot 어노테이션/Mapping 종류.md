# Mapping 종류

이번에 설명할 것은 필수로 알아야하는 Method 관련 어노테이션을 몇가지 알려주겠다.

Method에는 몇가지가 있는데 그중 대표적인 4가지를 설명하겠다.

```
@GetMapping("test")
public String test() {
	return "hello";
}
```

어떤 프레임워크를 사용해서 서버를 작성하든 Method를 지정하고 URI를 지정하며 그에 따른 함수를 작성합니다. Spring boot에서는 @GetMapping를 사용해 method를 지정하고 그 옆에 URI를 작성합니다. 

```
@GetMapping
@PostMapping
@PutMapping
@DeleteMapping
```

대표적으로 4가지가 있으며 이름의 뜻대로 해석을 하면 된다.





또다른 방식으로는 

```
@RequestMapping(method = RequestMethod.GET)
public String test() {
	return "hello";
}
```

이런 방식이 있는데 이런 형태로는 잘 사용하지 않는다. 저걸 사용하는 경우는 



```
@RestController
@RequestMapping("/spring")
public class Tess {

    @GetMapping("/test")
    public String test() {

        return "hello world";
    }
}
```

이런식으로 공통 URI를 사용할 때 말고는 거의 사용을 하지 않는다. 



___

URI가 합쳐진다는 뜻은 

```
http://127.0.0.1:8080/spring/test
```

이렇게 된다는 뜻이다.

