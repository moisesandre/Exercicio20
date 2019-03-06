# Exercicio20

int main()
{
    system("color 0b");

    int i, n;

    for (i=0; i<=9; i++)
    {
        printf("Digite um numero ");
        scanf("%d",&n);

        if (n<0){
            printf("numero invalido");
            break;
    }
        printf("%.2f\n",sqrt(n));
    }

return 0;
}
