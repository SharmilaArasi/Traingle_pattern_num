# Traingle_pattern_num
triangle pattern of numbers
import java.util.*;
public class Main
{
	public static void main(String[] args) {
	    int n=7,k=1;
	    for(int i=1;i<=n;i++,System.out.print("\n")){
	        System.out.print(i+" ");
	      int diff=n;
	       int value=i;
	        for(int j=1;j<=n-i;j++){
	            value=value+diff;
	            System.out.print(value+" ");
	            diff--;
	            
	        }
	    }
	}
}
