### Hi there 👋
<h2>[프로그래머스] 없는숫자 더하기 문젶풀이 JAVA

  
```JAVA
  class Solution {
    public int solution(int[] numbers) {
        int sum_9=0;
        for (int i=0;i<=9;i++){
            sum_9+=i;
        }
        int sum=0;
        for (int j=0;j<numbers.length;j++){
            sum+=numbers[j];
        }
        int answer = sum_9-sum;
        System.out.println(answer);
        return answer;
    }
}
```
