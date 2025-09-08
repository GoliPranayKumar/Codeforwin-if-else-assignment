# Codeforwin-if-else-assignment
#1
import java.util.*;
class Main {
    public static void main(String[] args) {
        System.out.print("Enter the First Number:");
        Scanner sc=new Scanner(System.in);
        int a=sc.nextInt();
        System.out.print("Enter the Second Number:");
        Scanner sc1=new Scanner(System.in);
        int b=sc1.nextInt();
        if(a<b){
            System.out.println(b+" is Greater Number");
        }
        else if(b<a){
            System.out.println(a+" is Greater Number");
        }
        else{
            System.out.println("Both are Equal");
        }
        
        
    }
}
#2
