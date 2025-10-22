package com.mycompany.array;


public class Array {

    public static void main(String[] args) {
        String [] nomes = {"Estudante", "Lara"};
        System.out.printf("Os dois valores são %s, %s\n",nomes[0],nomes[1] );
        
        //Este metodo faz a contagem de caracteres
        System.out.printf("O nome %s tem %s letras\n",nomes[0],nomes[0].length() );
        
        //Este metodo transforma tudo em maiusculo
        System.out.printf("O nome %s em maiusculo é %s.\n",nomes[0],nomes[0].toUpperCase() );
        
        // Este metodo transforma em minuscula
        System.out.printf("O nome %s em minusculas é: %s.\n",nomes[0],nomes[0].toLowerCase() );
        
        //Este metodo traz a letra em uma posição especifica
        System.out.printf("A primeira letra de %s é %s.\n",nomes[0],nomes[0].charAt(0) );
        
        //Este método traz uma parte da strng
        System.out.printf("As 3 primeiras letras de %s é %s.\n",nomes[0],nomes[0].substring(0,3) );
        
        //Este metodo também traz a String a partir do indice selecionado
        System.out.printf("As 3 primeiras letras de %s é %s.\n",nomes[0],nomes[0].substring(3) );
        
        //Este metodo faz comparações
        System.out.printf("O nome %s é igual a 'Estu'? %s.\n",nomes[0],nomes[0].equals("Estu") );
        
        //Este metodo faz comparações sem lavar em conta Case
        System.out.printf("O nome %s é igual a 'Estu'? %s.\n",nomes[0],nomes[0].equalsIgnoreCase("Estudante") );
        
        //Este metodo verifica se contem alguma parte do texto
        System.out.printf("O nome %s conttém 'Est'? %s.\n",nomes[0],nomes[0].contains("Est") );
        
        //Este metodo verifica se comeca==ça com determinada silaba
        System.out.printf("O nome %s começa com 'Est'? %s.\n",nomes[0],nomes[0].startsWith("Est") );
        
        //Este metodo verifica se termina com determinada silaba
        System.out.printf("O nome %s começa com 'ante'? %s.\n",nomes[0],nomes[0].endsWith("ante") );
        
        //Este metodo faz a substituição de uma parte ou toda da String
        System.out.printf("Troque %s por 'Aluno'. Agora eu sou %s.\n",nomes[0],nomes[0].replace("Estudante","Aluno") );
        
        
    }
}
