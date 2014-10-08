import java.util.Scanner;
 
public class PointDistance
{
 
    public static void main(String[] args)
    {   
         
         
        int x1, y1, x2, y2;
        double distance;
        double insideRoot;
         
        Scanner scan = new Scanner (System.in);
         
        System.out.println("Enter the x coordinate for point 1: ");
        x1 = scan.nextInt();
         
        System.out.println("Enter the y coordinate for point 1: ");
        y1 = scan.nextInt();
         
        System.out.println("Enter the x coordinate for point 2: ");
        x2 = scan.nextInt();
         
        System.out.println("Enter the y coordinate for point 2: ");
        y2 = scan.nextInt();
         
        /*x1 = (double) x1; //make double for power operation
        y1 = (double) y1;
        x2 = (double) x2;
        y2 = (double) y2;*/
         
        insideRoot = Math.pow((x2 - x1),2) + Math.pow((y2- y1),2);
         
        distance = Math.sqrt(insideRoot);
         
        System.out.println("The distance between the two points is " + distance + " .");
         
    }
     
}
