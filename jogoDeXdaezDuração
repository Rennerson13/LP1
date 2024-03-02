package Tarefa2;

import java.util.Scanner;

public class DuracaoJogoXadrez {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.println("Digite a hora de início do jogo (em horas inteiras): ");
        int horaInicio = scanner.nextInt();

        System.out.println("Digite a hora de fim do jogo (em horas inteiras): ");
        int horaFim = scanner.nextInt();

        if (horaFim < horaInicio) {
            horaFim += 24;
        }

        int duracaoJogo = horaFim - horaInicio;

        System.out.println("A duração do jogo de xadrez foi de: " + duracaoJogo + " horas.");

        scanner.close();
    }
}
