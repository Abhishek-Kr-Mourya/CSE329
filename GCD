import java.io.*;
import java.util.*;

public class gcdOfTwoNums {
    public static int gcd(int a, int b){
        int ans = Math.min(a,b);
        if(ans==0){
            return Math.max(a,b);
        }
        while(ans!=0){
            if(a%ans==0 && b%ans==0){
                break;
            }
            ans--;
        }
        return ans;
    }
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int a=sc.nextInt();
        int b=sc.nextInt();
        System.out.print(gcd(a,b));
    }
}
