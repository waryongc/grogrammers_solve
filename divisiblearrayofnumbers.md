   
<h2>[프로그래머스] 나누어 떨어지는 숫자배열 JAVA</h2>

```JAVA
import java.util.Arrays;

class Solution {
      public int[] solution(int[] arr, int divisor) {
      int[] result=Arrays.stream(arr).sorted().filter(e -> e%divisor==0).toArray();
      if (result.length==0) return new int[]{-1};
          return result;
        
      }
}
```
