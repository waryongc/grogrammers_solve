<h2>[프로그래머스] 핸드폰 번호 가리기 JAVA</h2>

```JAVA
class Solution {
    public String solution(String phone_number) {
        String answer = "";
        
        int len=phone_number.length();
        int leng=len-4;
        String num=phone_number.substring(0,leng);
        
        for (int i=0; i<=leng;i++ ){
            String front_number="*".repeat(leng);
            String back_number=phone_number.substring(leng,len);
            answer=front_number + back_number;
        }
        
        return answer;
    }
}
```
