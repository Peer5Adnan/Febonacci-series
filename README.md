# Febonacci-series
public class Fabnser {
    public static void main (String args[])
    {
        int num1,num2,num3;
        num1=0;
        num2=1;
        int n;
        n=20;
        for (int i=0;i<n;i++)
        {
            num3=num2+num1;
            num1=num2;
            num2=num3;
            System.out.println("fibonacci of the number is////////////////////"+num3);

        }
    }
}
