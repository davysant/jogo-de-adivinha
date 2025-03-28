import java.util.Random;
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Random random = new Random();
        int numeroAleatorio = random.nextInt(100) + 1; // Gera um número aleatório entre 1 e 100
        Scanner scanner = new Scanner(System.in);
        int palpite;
        int tentativas = 0;

        System.out.println("Bem-vindo ao Jogo da Adivinhação!");
        System.out.println("Tente adivinhar o número que estou pensando (entre 1 e 100).");

        while (true) {
            System.out.print("Digite seu palpite: ");
            palpite = scanner.nextInt();
            tentativas++;

            if (palpite < numeroAleatorio) {
                System.out.println("Tente um número maior!");
            } else if (palpite > numeroAleatorio) {
                System.out.println("Tente um número menor!");
            } else {
                System.out.println("Parabéns! Você acertou o número em " + tentativas + " tentativas!");
                break; // Sai do loop quando o jogador acerta
            }
        }

        scanner.close();
    }
}
