# Getter 와 Setter

Getter 와 Setter를 자주 보거나 사용하신적 있을 겁니다.

```
public class test{

    String name;

    public String setName(String name) {
        this.name = name;
    }

    public void getName() {
        return name;
    }
}
```

이런 코드들을 많이 보거나 작성해보셨을 것이다. 매우 귀찮고 자동 완성이 있다고 하더라도 코드가 많이 더러웠음을 느꼈을 것이다. 그래서 __@Getter, Setter__ 가 등장했다. 

```
@Getter
@Setter
public class test{

	String name;
}
```

이런 식으로 줄어든다. 매우 깔끔하고 편하지 않는가? 그렇기에 많은 사람들은 Getter와 Setter를 사용한다.

