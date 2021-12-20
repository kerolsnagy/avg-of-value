# avg-of-value
package com.company;

import jdk.swing.interop.SwingInterOpUtils;

import java.util.Scanner;

class JAVA
{
    public static void main (String args[])
    {
        Scanner in=new Scanner(System.in);
        int arr[]= new int[5];
        int sum=0;
        for (int i = 0; i < arr.length; i++)
        {
            System.out.println("Enter element # " + (i+1) + " : " );
            arr[i]= in.nextInt();

            sum += arr[i];
        }
        double avg=sum/arr.length;
        System.out.println("Average =" + avg);
    }
}



