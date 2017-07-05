import java.io.*;
import java.util.*;
public class PosNegZero
{
public static void main(String args[])
{
BufferedReader br=new BufferedReader(new InputStreamReader(System.in));
int n;
System.out.println("Enter any integer number:");
n=Integer.parseInt(br.readLine());
if(n>0)
{
System.out.println(n + " is positive number");
}
else if(n<0)
{
System.out.println(n + "is negative number");
}
else
{
System.out.println("It is zero");
}
}
