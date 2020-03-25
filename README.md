# Frequency-of-even-odd-numbers-in-a-matrix-Java
Frequency of even odd numbers in a 2-d array
package com.frequency;

/**
 *
 * @author Dinesh Nanda
 */

public class Frequency {
    
    public static void main(String[] args) {
        
        int arr[][] = {{4,1,3},{3, 5, 7}, {8, 2, 6}};
        int even_count = 0;
        int odd_count = 0;
        
        for(int i = 0; i < arr.length; i++){
            for(int j = 0; j < arr.length; j++){
                
                if(arr[i][j] % 2 == 0){
                    even_count++;
                }else{
                    odd_count++;
                }
            }
        }
        System.out.println("Even number in a given matrix: "+ even_count);
        System.out.println("Odd number in a given matrix: "+ odd_count);
    }
    
}
