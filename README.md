/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Classes/Main.java to edit this template
 */
package javaapplication1;

import java.util.Scanner;

/**
 *
 * @author 326114045
 */
public class JavaApplication1 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
      Scanner scanner = new Scanner(System.in);

        
        System.out.print("Digite o número de linhas (n): ");
        int n = scanner.nextInt();

        System.out.print("Digite o número de colunas (m): ");
        int m = scanner.nextInt();

        int[][] matriz = new int[n][m];

       
        System.out.println("Digite os elementos da matriz:");
        for (int i = 0; i < n; i++) {
            for (int j = 0; j < m; j++) {
                matriz[i][j] = scanner.nextInt();
            }
        }

       
        System.out.println("\nMatriz original:");
        for (int i = 0; i < n; i++) {
            for (int j = 0; j < m; j++) {
                System.out.print(matriz[i][j] + " ");
            }
            System.out.println();
        }

        
        System.out.println("\nMatriz transposta:");
        for (int j = 0; j < m; j++) {
            for (int i = 0; i < n; i++) {
                System.out.print(matriz[i][j] + " ");
            }
            System.out.println();
        }

        scanner.close();
    }
}   
  # Atividade-dia-13-04  
    <img width="245" height="143" alt="Atividade dia 13" src="https://github.com/user-attachments/assets/b8219e08-8753-405d-b000-a6f074891018" />
