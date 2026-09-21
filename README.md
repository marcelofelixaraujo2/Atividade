# Atividade
Atividade jona
Letra a:
#include <stdio.h>
 
int main() {
    double num1, num2, resultado;
 
    printf("Digite o primeiro numero: ");
    scanf("%lf", &num1);
    printf("Digite o segundo numero: ");
    scanf("%lf", &num2);
 
    resultado = num1 * num2;
 
    printf("Resultado da multiplicacao: %.2f\n", resultado);
    return 0;
}

Letra b:
#include <stdio.h>
 
int main() {
    double n1, n2, n3, n4, n5, media;
 
    printf("Digite o 1 numero: ");
    scanf("%lf", &n1);
    printf("Digite o 2 numero: ");
    scanf("%lf", &n2);
    printf("Digite o 3 numero: ");
    scanf("%lf", &n3);
    printf("Digite o 4 numero: ");
    scanf("%lf", &n4);
    printf("Digite o 5 numero: ");
    scanf("%lf", &n5);
 
    media = (n1 + n2 + n3 + n4 + n5) / 5;
 
    printf("Media aritmetica: %.2f\n", media);
    return 0;
}

letra c :
#include <stdio.h>
 
int main() {
    double valor, precoFinal;
 
    printf("Digite o valor do produto: R$ ");
    scanf("%lf", &valor);
 
    precoFinal = valor + (valor * 0.08);   /* equivale a valor * 1.08 */
 
    printf("Preco final com 8%% de imposto: R$ %.2f\n", precoFinal);
    return 0;
}

Letra d :

#include <stdio.h>
 
int main() 
{
    double num1, num2, resultado;
 
    printf("Digite o primeiro numero: ");
    scanf("%lf", &num1);
    printf("Digite o segundo numero: ");
    scanf("%lf", &num2);
 
    resultado = num1 - num2;
 
    printf("Resultado da subtracao: %.2f\n", resultado);
    return 0;
}

Letra e:

#include <stdio.h>
 
int main() 
{
    int numero;
 
    printf("Digite um numero inteiro: ");
    scanf("%d", &numero);
 
    if (numero % 5 == 0) {
        printf("%d e multiplo de 5.\n", numero);
    } else {
        printf("%d NAO e multiplo de 5.\n", numero);
    }
    return 0;
}

Letra f :

#include <stdio.h>
 
int main() 
{
    double altura, peso, imc;
 
    printf("Digite a altura (em metros, ex: 1.75): ");
    scanf("%lf", &altura);
    printf("Digite o peso (em kg, ex: 70.5): ");
    scanf("%lf", &peso);
 
    imc = peso / (altura * altura);
 
    printf("IMC: %.2f\n", imc);
    return 0;
}

Letra G :

#include <stdio.h>
 
int main() 
{
    double celsius, fahrenheit;
 
    printf("Digite a temperatura em graus Celsius: ");
    scanf("%lf", &celsius);
 
    fahrenheit = (celsius * 9.0 / 5.0) + 32;
 
    printf("Temperatura em Fahrenheit: %.2f\n", fahrenheit);
    return 0;
}

Letra H :

#include <stdio.h>
 
int main() 
{
    double horas, valorHora, salario;
 
    printf("Digite a quantidade de horas trabalhadas: ");
    scanf("%lf", &horas);
    printf("Digite o valor da hora trabalhada: R$ ");
    scanf("%lf", &valorHora);
 
    salario = horas * valorHora;
 
    printf("Salario total: R$ %.2f\n", salario);
    return 0;
}
