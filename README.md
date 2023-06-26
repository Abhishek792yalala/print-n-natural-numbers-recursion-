# print-n-natural-numbers-recursion-


import java.util.*;


class Recursion{
     static void Nnum(int n){

        if(n<1){
            return ;
        }
        System.out.println(n);
        Nnum(n-1);

    }

    public static void main(String... str) {
        System.out.println("Enter the value of n : ");
        Scanner sc = new Scanner(System.in);
        int n=sc.nextInt();
        Nnum(n);


    }
}



/*
Enter the value of n :
5
5
4
3
2
1

 */
