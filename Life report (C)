/******************************************************************************

                            Online C Compiler.
                Code, Compile, Run and Debug C program online.
Write your code in this editor and press "Run" button to compile and execute it.

*******************************************************************************/

#include <stdio.h>

int main()
{int mes,ano,dia,diastotais=0;
float semana =0;
    printf("Em que mês estamos?\n");
    scanf("%d",&mes);
    printf("Em que ano estamos?\n");
    scanf("%d",&ano);
    printf("Em que dia estamos?\n");
    scanf("%d",&dia);
    printf("%d/%d/%d\n",dia,mes,ano);
    semana=((mes-1)*30+dia)/7;
    printf("Essa é a semana numero %.0f/52\n",semana);
    diastotais=(mes-1)*30+dia;
    printf("Já se passaram %d dias esse ano\n", diastotais);
    float salarioh,dinheirorecebido=0;
    printf("Quanto vc ganha por hora?\n");
    scanf("%f",&salarioh);
    dinheirorecebido=(semana-(semana*4/52))*5*8*salarioh; //semana menos as ferias, dasdas por semana/52 (ex50/52)*4, quando na ultima semana no ano 52/52, e igual a 1*4, reduzindo assim 4 semanas da conta de salario,o equivalente a um mes de ferias.
    printf("Voce ja recebeu R$%.2f esse ano, muito bem!\n", dinheirorecebido);
    float salariodolares =dinheirorecebido/4;
    printf("Em dolares voce teria recebido, no ano, U$%.2f\n",salariodolares);
    if (salariodolares<5000) {
    
        printf("E bem pouco em dolares por ano concorda?\n");
    } else {
        printf("E mais que 5 mil dolares por ano com certeza.\n");
    }
    int idade,diasvividos,diasesperados,anonascimento1,anonascimento2 = 0;
    printf("Quantos anos voce tem?\n");
    scanf("%d",&idade);
    diasvividos = idade*360;
    diasesperados=29200-diasvividos;
    anonascimento1=ano-idade;
    anonascimento2=anonascimento1++;
    printf("Voce nasceu no ano de %d ou no ano de %d\n", anonascimento1, anonascimento2);
    printf("Voce ja viveu %d dias, provavelmente ainda vivera mais %d dias, boa sorte!\n",diasvividos,diasesperados);
    float dinheirototal,dinheirototaldolares=0;
    int primeiroemprego =0;
    printf("Com quantos anos voce comecou a trabalhar?\n");
    scanf("%d",&primeiroemprego);
    dinheirototal=(diasvividos-primeiroemprego*360)*0.73*salarioh;
    dinheirototaldolares=dinheirototal/4;
    printf("Voce ja recebeu um total de R$%.2f durante a sua vida, em dolares seriam U$%.2f, daria para comprar alguma coisa legal?",dinheirototal,dinheirototaldolares);
    }
