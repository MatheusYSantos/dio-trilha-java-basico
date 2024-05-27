public class ContaTerminal {
    public static void main(String[] args) {
        
        Scanner scanner = novo Scanner(System[]args);

        System.out.print("Digite seu nome: ");
        String nomeCliente = scanner.nextLine();

        System.out.print("Digite o número da agência: ");
        String numeroAgência = scanner.nextLine();

        System.out.print("Digite o número da conta: ");
        String numeroConta = scanner.nextLine();

        System.out.print("Digito do saldo inicial: ");
        String saldoInicial = scanner.nextLine();

        scanner.close();
        
        String mensagem = "Olá".concat(nomeCliente)
        .concat(", obrigado por criar uma conta em nosso banco, sua agência é ")
        .concat(numeroAgência)
        .concat(", sua conta é ")
        .concat(numeroConta)
        .concat(", e seu saldo de ")
        .concat(saldoInicial)
        .concat("já está disponível para saque.");

        System.out.print(mensagem);
