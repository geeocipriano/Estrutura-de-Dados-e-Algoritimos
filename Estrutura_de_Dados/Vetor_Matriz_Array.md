<h4 align="center"> 
	Descrição
</h4>
São usadas quando existem muitas variaveis do mesmo tipo em um algoritimo
Exemplo em Java para criar e buscar tamanho do array.
    

        public class TamanhoArray {

        public static void main(String[] args) {
            int[] arrayUm = {12,3,5,68,9,6,73,44,456,65,321};
            int[] arrayDois = {43,42,4,8,55,21,2,45};

            if(arrayDois.length > 8){
                System.out.println("Tamanho do ArrayDois - Maior que 8!");
            }else{
                System.out.println("Tamanho do ArrayDois - Menor que 8!");
            }
            System.out.println("\nTamanho do ArrayUm = "+arrayUm.length);
        }
    }
