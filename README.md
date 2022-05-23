# Exercicio-6-ac2-
Exercicio 6 ac2 CNH
public static void main(String[] args) {
	
	Scanner read = new Scanner(System.in);
    
	
	
    int numb1, numb2, numb3;
    
   
    
    System.out.println("quantas questoes voce acertou no exame psicotecnico: ");
    numb1 = read.nextInt();
    System.out.println("quantas questoes voce  acertou no exame de legislacao: ");
    numb2 = read.nextInt();
    System.out.println("quantas questoes voce acertou no exame pratico: ");
    numb3 = read.nextInt();
    
    
    
    if(numb1==45);{
        System.out.printf("aprovado");
    }
    if(numb1<45){
        System.out.printf("reprovado");
    }
    else if(numb2>=21){
        System.out.printf("aprovado");
    }
    else if(numb2<21){
        System.out.printf("reprovado");
    }
    
   
    
    else if(numb3>=20){
        System.out.printf(" Esta habilitado");
    }
    
 
    
    else if(numb3<20){
        System.out.printf("refazer a prova");}
    
    }

}


![image](https://user-images.githubusercontent.com/103973613/169920435-fcbd3f3c-d2fe-4ee0-a314-69930426da89.png)

