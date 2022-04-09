# AmeliaPutri_054
/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Classes/Class.java to edit this template
 */
package mid.soal4;

import java.util.Scanner;

/**
 *
 * @author LENOVO
 */
public class konversi {
    public static void main(String[] args) {
 
        Scanner userInput = new Scanner(System.in);
 
        double mil, hasil;
 
        double km = 1.60934; // Jarak 1 Mil dalam Km
 
        System.out.println("\n\t Konversi Jarak Mil ke Jarak M \n");
 
        System.out.print(" Berapa Mil : ");
        mil = userInput.nextDouble();
 
        System.out.println("");
 
        hasil = mil * km;
        System.out.println(" " + mil + " Mil = " + hasil + " M.");
 
        System.out.println("");
    }
    
}
