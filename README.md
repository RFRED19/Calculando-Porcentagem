/* Problemática
João tinha uma estimativa, gastou 35% e ainda ficou com R$ 97,50. Qual o valor que João tinha inicialmente?

Solução
Implemente um programa em Java que resolva quais problemas considerando que pode haver mudanças de percentual e personagens.
*/

/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 */

package com.mycompany.calculoporcentagem;

import java.util.Scanner;

/**
 *
 * @author rfred
 */
public class CalculoPorcentagem {

    public static void main(String[] args) {
        //variaveis
     string nome;
     double total, gasto, resto, calculo1, calculo2;
     //System.out.println("Qual é o seu nome: ");
     Scanner teclado = new Scanner (System.in);
     System.out.println("Quantos sobrou? ");
     resto = teclado.nextDouble();
     System.out.println("qual o percetual gasto? ");
     gasto = teclado.nextDouble();
     calculo1 = (resto * 100);//9,750
     calculo2 = (gasto - 100);//65
     total = (calculo1 / calculo2)*-1;
     System.out.println("o valor total é: "+total);
    }
}
