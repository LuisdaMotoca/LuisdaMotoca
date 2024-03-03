import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
    //String é pra letras
        String modelo;
    //o Double é pra representar números reais, ou seja, pode apresentar virgula e tal
        double valorDiaria;
    //Int é o contrario do double, pode apresentar numeros inteiros, ou seja, NÃO pode apresentar virgula
        int qtdDias;
        double qtdKm;
        double resultado;
    //usa "sout" que ja aparece System.out.println();
        System.out.println("Digite o modelo do carro");
    //Precisa ter esse scanner leitor = new Scanner(System.in); tanto faz a ordem
        Scanner leitor = new Scanner(System.in);
        modelo = leitor.next();
        System.out.println("Digite o valor da diaria");
        valorDiaria = leitor.nextDouble();
        System.out.println("Digite a quantidade de dias");
        qtdDias = leitor.nextInt();
        System.out.println("Digite quantos kilometros rodados");
        qtdKm = leitor.nextDouble();
        resultado = qtdKm * 0.2;
        System.out.println("O valor a ser pago é R$ " + resultado);
        System.out.println("--------------------------");
        System.out.println("O modelo do seu carro é " + modelo );
        System.out.println("--------------------------");
        System.out.println("A quantidade de dias que ficou com o carro é " + qtdDias);
    }
}
