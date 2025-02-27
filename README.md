import java.time.DayOfWeek;
import java.time.LocalDate;
import java.util.*;


public class Main {
    public static void main(String[] args) {
        Scanner a=new Scanner(System.in);
        System.out.println("enter the year");
        int year=a.nextInt();
        System.out.println("enter the month");
        int month=a.nextInt();
        System.out.println("enter the date");
        int datee=a.nextInt();
        
        LocalDate date=LocalDate.of(year, month, datee);
        DayOfWeek day=date.getDayOfWeek();
        System.out.println(day);

}
    }
