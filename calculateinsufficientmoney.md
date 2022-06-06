   
<h2>[프로그래머스] 부족한 돈 계산하기 JAVA</h2>

```JAVA
class Solution {
    public long solution(long price, long money, long count) {
        long answer=0;
        for(int i=0;i<count;i++){
            money-=price*(1+i);
        }
        if(money>=0){
            answer=0;
        }else{
            answer=(long)Math.abs(money);
        }
        return answer;
    }
}
```
