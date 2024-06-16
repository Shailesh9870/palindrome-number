# palindrome-number


import java.util.*;
import java.lang.*;
public class palindromenumber {
    public static void main(String[] args) {
        int num;
        Scanner sc=new Scanner(System.in);
        System.out.println("Enter the original number");

        num=sc.nextInt();
        System.out.println(num);
        int a=num;
        int r;
        int count=0;
        int sum=0;
        while(a!=0){
            r=a%10;
            sum=(sum*10)+r;
            a=a/10;
            count++;
            
        }
        
        
        
        System.out.println("count ="+count);
        if(sum==num){
        System.out.println(num+"is a palindrome number");}
        else{
            System.out.println(num+"   is not a   palindrome number");
        }
    
    }
}

