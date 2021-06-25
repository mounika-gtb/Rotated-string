# Rotated-string
public class Rotated String
{
Scanner s = new scanner(System.in);
System.out.println("enter 2 strings:");
String s1 = s.next();
String s2 = s.next();
if (s1.length() !=s2.length())
{
System.out.println("No");
}
else
{
String s3 = s1+s1;
if(s3.contains(s2))
{
System.out.println("yes");
}
else
{
System.out.println("No");
}
}
