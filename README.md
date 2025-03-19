public class Main {

   public static void main(String[] args){

       double Portugues1 = 7;
       double Portugues2 = 8;
       double Portugues3 = 6;
       double Portugues4 = 9;
       double SomaTotal = 30.24;

       System.out.println("Suas notas em Português até o 4 Bimestre somadas foram de " + SomaTotal);

       double Média = (Portugues1 * Portugues2 * Portugues3 * Portugues4);
       double Dividido = (SomaTotal / 4);

       System.out.println("Dividindo esse resutado sua nota final ficou em " + SomaTotal / 4);

       if (Dividido >=6){
           System.out.println("Aprovado!");

       } else {

           System.out.println("Reprovado!");
       }
   }
}
