# Prime-No
import java.util.Scanner;

public class Primenumber {

	public static void main(String[] args) {
		
		Scanner sc=new Scanner(System.in);
		int c=0;
		int n=sc.nextInt();
		for(int i=2;i*i<=n;i++) {
			if(n%i==0) {
				c=1;
				break;}
			
		}
		if(c==0)
			System.out.println(n+" is Prime no.");
		else
			System.out.println(n+" is not a prime no.");
	}

}
