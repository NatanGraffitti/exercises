import java.util.Scanner;

public class ContaBanco {
    public static void main(String[] args) {
        
        Scanner scanner = new Scanner(System.in);
        System.out.println("Digite aqui seu nome: ");
            String nome = scanner.nextLine();
        System.out.println("Seja bem vindo, " + nome + ". Digite o número da sua agência: ");
            String agencia = scanner.nextLine().replace("-", "");
        System.out.println("Digite sua conta: ");
            int conta = scanner.nextInt(); 
        System.out.println("Digite agora o saldo que gostaria de depositar: ");
            String saldoInput = scanner.next().replace(",", ".");
                float saldo = Float.parseFloat(saldoInput);
      
        System.out.println("Olá, " + nome + ", obrigado por criar uma conta em nosso banco, sua agência é " + agencia + ", conta " + conta + " e seu saldo de R$" + saldo + " já está disponível para saque.");
    }    
} 
