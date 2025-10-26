#::Islam Ahmed ramadan::
import java.util.ArrayList;
import java.util.Scanner;


public class Main {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        ArrayList<String> list = new ArrayList<>();
         int switch1=1;
         if(switch1!=1){
             System.out.println(" ::Think you::  ");
         }
         else{


while (switch1==1 ) {
    System.out.print("Enter number to start 1:to stop 2 ");
    switch1 = input.nextInt();
    System.out.println("the mainu is tho ");
    System.out.println("to add chiose (1) ");
    System.out.println("to delete chiose (2) ");
    System.out.println("to get chiose (3) ");
    System.out.println("to display chiose (4) ");
    System.out.println("to remove all of list chiose (5) ");
    int mainu = input.nextInt();
    switch (mainu) {
        case 1:
            System.out.print("to add : ");
            System.out.print( list.add(input.next()));
            break;
        case 2:
            System.out.print("to delete :");
            System.out.print( list.remove(input.next()));
            break;
        case 3:
            System.out.print("to get :");
            System.out.print( list.get(input.nextInt()));
            break;
        case 4:
            System.out.print("to display :");
            System.out.print( list.getLast());
            break;
        case 5:
            System.out.print("to remove :");
                    System.out.print(5451
                            1
                            1111
                            1
                            list.removeAll(list));


    }
}
    System.out.print("the list : " );
    for (String s : list) {
        System.out.print(s + " ");
    }


}

    }
}



