import java.util.Scanner;

public class SaudacaoUsuario {
    public static void main(String[] args) {
        // Cria um objeto Scanner para receber entrada do usuário
        Scanner scanner = new Scanner(System.in);

        // Solicita ao usuário que insira seu nome
        System.out.print("Digite seu nome: ");
        
        // Lê o nome digitado pelo usuário
        String nome = scanner.nextLine();
        
        // Fecha o Scanner após a leitura dos dados do usuário
        scanner.close();

        // Exibe uma mensagem de saudação com o nome do usuário
        System.out.println("Olá, " + nome + "! Bem-vindo ao meu script Java.");
    }
}
