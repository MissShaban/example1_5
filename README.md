# example1_5
public class Example5_1 {
public static void main(String[] args)
{
double radians = 45.0;
double dl = 5.0, d2 = 6.5;
int num, X = 10, y = 20;
double degree = 90;
double p = -5.36;
System.out.println("cos ("+radians+")=
"+ Math.cos (radians));
System.out.println("pow("+d1+","+d2+")= "+ Math.pow(d1, d2));
System.out.println("max ("+x+", "+y+") = "+ Math.max(x, y));
System.out.println("min("+d1+","+d2+")=" + Math.min (d1, d2));
System.out.println("sqrt("+y+") = + Math.sqrt(y)); System.out.println("round ("+d2+") = + Math.round (d2)); System.out.println("ceil("+p+")= + Math.round (p)); System.out.println("floor ("+p+") = + Math.floor(p)); System.out.println("toRadians ("+degree+") = +
Math.toRadians (degree));
System.out.println("exp("+d1+") = + Math.exp(d1)); System.out.println("Generate 5 integer random numbers less than or equal 5:");
for(int i = 1; i <= 5; i++)
{
num = (int) (5*Math.random());
System.out.print
("num"+i+"="+num+"\t");
}
