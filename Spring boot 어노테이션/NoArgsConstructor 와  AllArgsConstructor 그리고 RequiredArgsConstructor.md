# NoArgsConstructor 와  AllArgsConstructor 그리고 RequiredArgsConstructor

서버를 짜다보면 생성자를 생성하는 어노테이션이 있습니다. 생성자를 생성자를 생성하는 어노테이션은  __NoArgsConstructor__ 와 __AllArgsConstructor__ 그리고 **RequiredArgsConstructor** 로 3가지가 있습니다..

이것들이 무엇을 하는지는 어렴풋이 알고는 있지만 자세하게는 모르기 때문에 이번에 알고 넘어가도록 하자

- **NoArgsConstructor** 
  - 파라미터 값이 없는 빈 생성자를 생성해줍니다.
- **AllArgsConstructor**
  - 모든 파라미터를 받는 생성자를 생성해줍니다.
- **RequiredArgsConstructor**
  - final이나 @NotNull이 붙은 변수들을 가진 생성자를 생성해 줍니다. 때문에 변수 정의에 final이나 @NotNull이 없을 경우 에러가 납니다.

```
public class LombokTest {
	private String test1;
	
	public LombokTest() {
	}
}
```

이런 코드가 



```
@NoArgsConstructor
public class LombokTest {
	private String test1;
}
```



이런식으로 코드가 달라집니다. **AllArgsConstructor** 는 인자가 있고 **RequiredArgsConstructor** 이것도 위에 설명과 똑같습니다. 

