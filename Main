
import java.util.Scanner;

public class BMITest {

    public static void main(String[] args) {
        Scanner reader = new Scanner(System.in);

        // import gad
        System.out.print("enter height(cm):");
        float height = reader.nextInt();
        // gad(m)
        float heightm = height / 100;
        // gad²
        float height2 = heightm * heightm;

        // import vazn
        System.out.print("enter weight(kg):");
        float weight = reader.nextInt();

        // export BMI
        float BMI = weight / height2;
        System.out.println("BMI is: " + BMI);

        //tozihat
        if(BMI <= 15){
            System.out.println("Very severe weight loss!!");
        }else if(15 < BMI && BMI <= 18.5){
            System.out.println("severe weight loss!!");
        }else if(18.5 < BMI && BMI <= 25){
            System.out.println("normal");
        }else if(25 < BMI && BMI <= 30){
            System.out.println("Overweight!");
        }else if(30 < BMI && BMI <= 35){
            System.out.println("Normal obesity!");
        }else if(35 < BMI && BMI <= 40){
            System.out.println("Severe obesity!!");
        }else{
            System.out.println("Very severe obesity!!");
        }
    }
}
