# corejavapratice
import java.util.*; 
public class stud 
{
 public static void main(String[] args)
{ 
Scanner s=new Scanner(System.in); 
System.out.println("Enter marks in project :");
 int pro=s.nextInt();
 System.out.println("Enter marks in external :");
 int ext=s.nextInt(); 
System.out.println("Enter marks in internal :"); 
int int=s.nextInt();
if(pro>=50 && ext>=50 && int>=50) 
{ 
int t=((70/100)*pro + (20/100)*ext + (10/100)*int);
 System.out.println("Total Score :"+ts); 
if(t>=90) 
{ 
System.out.println("A grade"); 
} 
if(t<90&&t>=70) 
{ 
System.out.println("B grade"); 
}
 if(t<70&&tsm>=50) 
{ 
System.out.println("C grade");
 } } 
else 
{
 if(pro<50)
 { System.out.println("Failed in Project Marks:"+pro); 
} 
if(ext<50)
 { 
System.out.println("Failed in External Marks:"+ext);
 }
 if(int<50) 
{
 System.out.println("Failed in Internal Marks:"+int);
 } 
} 
} 
}
