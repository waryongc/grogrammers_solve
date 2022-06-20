   
<h2>[프로그래머스] 서울에서 김서방 찾기 JAVA</h2>

```JAVA
import java.util.Arrays;

class Solution {
    public String solution(String[] seoul) {
        int loc=Arrays.asList(seoul).indexOf("Kim");
        String answer="김서방은 "+ loc +"에 있다";
        return answer;
    }
}
```
