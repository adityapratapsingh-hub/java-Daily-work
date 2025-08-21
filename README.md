import java.util.*;
class TemperatureCHlheck{
    public static void main(String args[]){
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter the Values");
        int temp=sc.nextInt();
        if(temp==0){
            System.out.println(" Temp is the Zero");

        }else if(temp>0 ){
            System.out.println("Temp is the  positive");
        }else{
            System.out.println("Temp is the negative");
        }
    }
}
