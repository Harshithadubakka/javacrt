# javacrt
import java.io.*;
import java.util.*;

public class Solution {

    public static void main(String[] args) {
Scanner s=new Scanner(System.in);
        int b,m,y,a;
        b=s.nextInt();
        m=s.nextInt();
        y=s.nextInt();
      a=(b+m+y)%2;
        if(a==0)
        {
            System.out.println("Cinema Day");
            
        }
        else
        {
            System.out.println("Not a Cinema Day ");
        }
        /* Enter your code here. Read input from STDIN. Print output to STDOUT. Your class should be named Solution. */
    }
}
