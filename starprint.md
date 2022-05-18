<h2>[프로그래머스] 별찍기 문제풀이</h2>


```JAVA
import java.util.Scanner;

class Solution {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int a = sc.nextInt();
        int b = sc.nextInt();

        for (int j=0;j<b;j++){
            for (int i=0;i<a;i++){
                System.out.print("*");

            }
            System.out.println("");
        }
    }
}
```
