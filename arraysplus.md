   
<h2>[프로그래머스] 문자를숫자로변환하기 JAVA</h2>

```JAVA
class Solution {
    public int[][] solution(int[][] arr1, int[][] arr2) {
        int[][] answer = new int[arr1.length][arr1[0].length];
        for (int i=0;i<arr1.length;i++){
            for(int j=0; j<arr1[0].length;j++){
                answer[i][j]+=arr1[i][j]+arr2[i][j];
            }
        }
        System.out.println(answer);
        return answer;
    }
}
```
