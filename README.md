# DS-Linguagem-C-
Desktops 


#include <studio.h>

    //Questão 1
    int main() {
   int x,y;
printf("Insira o Numero 1: \n");
scanf("%d", &x);
printf("Insira o Numero 2: \n");
scanf("%d", &y);
printf("Soma: %d" , x+y);
}


//Questão 2

     int numero;
printf("Insira um número: \n");
scanf("%d", &numero);

if (numero % 2 == 0)  {
    printf("O numero %d é par \n", numero);
}
    else {
        printf("O numero %d é impar \n", numero)
}
return 0;
}

//Questão 4
int main() {
   int a, b, c, d, e, f;
float media;

printf("Selecione o primeiro numero: \n");
scanf("%d", &a);
printf("Selecione o segundo numero: \n");
scanf("%d", &b);
printf("Selecione o terceiro numero: \n");
scanf("%d", &c);
printf("Selecione o quarto numero: \n");
scanf("%d", &d);
printf("Selecione o quinto numero: \n");
scanf("%d", &e);
printf("Selecione o sexto numero: \n");
scanf("%d", &f);

media = (a+b+c+d+e+f)/ 6.0;
printf("A media é: %.2f\n", media);
return 0;
}

// Questão 5
int main() {
int ano;
printf("Insira um ano: \n");
scanf("%d", &ano);

if (ano % 4 == 0 && ano % 100 != 0)  {
printf("O ano %d é bissexto.\n", ano);
    } else {
        printf("O ano %d não é bissexto.\n", ano);
    }
return 0;
}

//  Questão 7
     int main() {
     int num1, num2, num3, maior;

    printf("digite o primeiro número: ");
    scanf("%d", &num1);
    printf("digite o segundo número: ");
    scanf("%d", &num2);

    maior = num1;
    if (num2 > maior) {
        maior = num2;
    }
    if (num3 > maior) {
        maior = num3;
    }

    printf("O maior número é: %d\n", maior);

    return 0;
}

