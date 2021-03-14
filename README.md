import java.util.Scanner;

public class Solution {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int a = sc.nextInt();
        int b = sc.nextInt();
        int n = sc.nextInt();
        
        int val = (a * 100 + b) * n;

        System.out.println(val / 100 + " " + val % 100);
    }

}
