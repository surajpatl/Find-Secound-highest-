# Find-Secound-highest-in given array
package Java;

import java.util.Arrays;
public class SecoundHighest {
   public static void main(String args[]){
      int array[] = {100,14,46,47,94,94,52,86,36,94,89};
      int size = array.length;
      Arrays.sort(array);
      System.out.println("sorted Array ::"+Arrays.toString(array));
      int res = array[size-2];
      System.out.println("2nd largest element is ::"+res);
   }
}
