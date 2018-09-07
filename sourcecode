import java.util.Scanner;

public class HelloWorld{

     public static void main(String []args){
       
    	 //Variable Dec
        Integer x=0,y=0;
        Boolean dec , cont;
        cont = false;
        String xx,yy;
        
        
        while(cont != true)
        {
         
        System.out.println("Enter First Number");
		    Scanner in = new Scanner(System.in);
        xx = in.nextLine();

        try
        {
        	x = Integer.parseInt(xx);
        }
        catch (NumberFormatException nfe)
        {
          System.out.println("Please type Integer Value" + nfe.getMessage());
          continue;
        }

        System.out.println("Enter Second Number");
        yy = in.nextLine();

        try
        {
        	y = Integer.parseInt(yy);
        }
        catch (NumberFormatException nfe)
        {
          System.out.println("Please type Integer Value" + nfe.getMessage());
          continue;
        }
        if (x > y)
        {
            System.out.println("ERROR!! First Number should be smaller than Second Number. Try Again");
            cont = false;
            x = 0;
            y =0;
            
        }
        else
        {
            cont = true;
        }

        }    
        //Finding Prime
        for(int i = x ; i <= y ; i++)
        {
            dec = true;
            
            for(int j = 2; j < y/2 ; j++)
            {
                if (i % j == 0 && i != j)
                {
                   dec = false;
                   break;
                }
            };
            if (dec == true)
            {
                System.out.println(i);
            }
   
        };

     }
}
