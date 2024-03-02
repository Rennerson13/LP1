package Tarefa2;

import java.util.Scanner;

public class CustoCarro {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.println("Digite o custo de fábrica do carro: ");
        double custoFabrica = scanner.nextDouble();

        double percentualDistribuidor = 0.28; // 28%
        double impostos = 0.45; // 45%

        // Calculando o custo final ao consumidor
        double custoFinal = custoFabrica + (custoFabrica * percentualDistribuidor) + (custoFabrica * impostos);

        System.out.println("O custo final ao consumidor é: " + custoFinal);

        scanner.close();
    }
}
