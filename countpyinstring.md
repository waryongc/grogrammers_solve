<h2>[프로그래머스] 문자열내 p와 y의 개수 JAVA</h2>

```JAVA
class Solution {
    boolean solution(String s) {
        char p='p';
        char P='P';
        char y='y';
        char Y='Y';
        boolean answer=false;
        int countp=0;
        int countP=0;
        int county=0;
        int countY=0;
        for (int i=0;i<s.length();i++){
            if(s.charAt(i)==p){
                countp++;
            }
        }
        for (int i=0;i<s.length();i++){
            if(s.charAt(i)==P){
                countP++;
            }
        }
        for (int i=0;i<s.length();i++){
            if(s.charAt(i)==y){
                county++;
            }
        }
        for (int i=0;i<s.length();i++){
            if(s.charAt(i)==Y){
                countY++;
            }
        }
        int totalp=countp+countP;
        int totaly=county+countY;
        
        
        if(totalp==totaly){
            answer = true;
        }else{
            answer = false;
        }
        return answer;        
    }
}
```
