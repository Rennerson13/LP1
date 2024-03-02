package Tarefa2;

import java.util.Scanner;

public class SalarioVendedor {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.println("Digite o número de carros vendidos pelo vendedor: ");
        int numeroCarrosVendidos = scanner.nextInt();

        System.out.println("Digite o valor total das vendas efetuadas pelo vendedor: ");
        double valorTotalVendas = scanner.nextDouble();

        System.out.println("Digite o salário fixo do vendedor: ");
        double salarioFixo = scanner.nextDouble();

        System.out.println("Digite o valor que o vendedor recebe por carro vendido: ");
        double valorPorCarro = scanner.nextDouble();

        // Calculando a comissão fixa por carro
        double comissaoFixaPorCarro = numeroCarrosVendidos * valorPorCarro;

        // Calculando a comissão sobre as vendas totais
        double comissaoSobreVendas = valorTotalVendas * 0.05;

        // Calculando o salário final do vendedor
        double salarioFinal = salarioFixo + comissaoFixaPorCarro + comissaoSobreVendas;

        System.out.println("O salário final do vendedor é: " + salarioFinal);

        scanner.close();
    }
}
