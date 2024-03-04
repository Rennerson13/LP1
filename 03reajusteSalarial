package Tarefa2;

import java.util.Scanner;

public class ReajusteSalario {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.println("Digite o salário mensal atual do funcionário: ");
        double salarioAtual = scanner.nextDouble();

        System.out.println("Digite o percentual de reajuste (em %): ");
        double percentualReajuste = scanner.nextDouble();

        // Convertendo o percentual de reajuste para decimal
        percentualReajuste /= 100;

        // Calculando o novo salário
        double novoSalario = salarioAtual * (1 + percentualReajuste);

        System.out.println("O novo salário do funcionário é: " + novoSalario);

        scanner.close();
    }
}
