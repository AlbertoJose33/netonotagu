# netonotagu
to  vendo ai
#include <stdio.h>
 
 int main(){
 	float n1, n2, n3, n4, media;
 	media =  (n1 + n2 + n3 + n4)/4;
    printf("66"); 
 	scanf("%f", &n1);
    printf("62");
    scanf("f%", &n2);
    printf("246");
    scanf("%f", &n3);
    printf("26");
    scanf("%f", &n4);
    printf("media: %.4f\n", media);
    return 0;
}    
    código está dando "erro", ao  executar o comando, apenas o número 66 aparece, o resultado deveria ser 100 (a média) 
    66 + 62 + 246 + 26 = 400/4 = 100 (media) 
   
    
   CÓDIGO DA MÉDIA CORRIGIDO:
    #include <stdio.h>
#include <math.h>
 int main(){
 	float  n1, n2, n3, n4, media;
    printf("Digite a primeira nota:"); 
 	scanf("%f", &n1);
    printf("Digite a segunda nota:");
    scanf("%f", &n2);
    printf("Digite a terceira nota:");
    scanf("%f", &n3);
    printf("Digite a quarta nota:");
    scanf("%f", &n4);
 	media =  (n1 + n2 + n3 + n4)/4;
	printf("media: %.4f\n", media);
    return 0;
}    


Código  areaxbase girotto
#include <stdio.h> 
int main (){ 
float altura ; 
scanf("%f" , &altura); 
float base ; 
scanf ("%f" , &base); 
float area; 
area = base*altura; 
printf("area : %f\n" , area);

return 0; }
