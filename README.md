package org.students;

import java.util.Arrays;
import java.util.Collections;

public class Week5 {

   public static void main(String[] args) {
      
 //Declare a double array and assign values to it
double array[]={53.5,60.3,96.2,53.3,56.4,52.7,76.4,77.5,71.0,78.2,65.2,59.3,80.5,92.1,85.7,78.7,66.2,88.8,50.2,73.4};
  
//Displaying the Array Elements Before Sorting
System.out.println("The Elements Of the Double Array Before sorting :");
for(int i=0;i<array.length;i++)
    System.out.print(array[i]+" ");

//Displaying the Array Elements After Sorting
Arrays.sort(array);
 System.out.println("\nAfter Selection Sort, the array are");
        for (int i = 0; i < array.length; i++) {
            System.out.print(array[i] + " ");
        }
        System.out.println(" ");

}
   }
