   
<h2>[프로그래머스] 가운데글자 가져오기 JAVA</h2>

```JAVA
class Solution {
    public String solution(String s) {
        String answer = "";
        int a=s.length()/2;
        if (s.length()%2==0){
            answer=s.substring(a-1,a+1);
        }else{
            answer=s.substring(a,a+1);
        }
        return answer;
    }
}
```
