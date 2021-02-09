//UseThree.java
//Give an input of three names, UseThree will alphabetically order them and greet them.


import java.util.Arrays;
import java.util.Scanner;

public class UseThree {
    public static void main(String[] args){
        String[] arr = new String[] { args[0], args[1], args[2] }; //making a string array
        Arrays.sort(arr); //sorting array alphabetically, making sure arg indexes and arguments are in corresponding order
        System.out.print("Hi ");
        System.out.print(arr[0] + ", "); //first alphabetically sorted argument
        System.out.print(arr[1] + ", and "); //second
        System.out.println(arr[2]); //third

    }
}
