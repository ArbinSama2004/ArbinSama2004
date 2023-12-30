package trry;
import java.io.IOException;

public class Try{
public static void main(String[] args){
try{
  int a=10, b=0, result;
  result=a/b;
  system.out.println("Result" + result);
}
catch(AirthmeticException e)
{
system.out.println("e ->getmsg error" + e.getMessage());
system.out.println("e ->localizedmsg error" + e.getlocalizedMessage());
system.out.println("e ->e error" + e);
}
}
