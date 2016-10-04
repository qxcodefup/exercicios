## C
```c
    int qtd = 0;
    int soma = 0;
    int num;//o numero do usuario
    while(num != -1){
        puts("Digite um numero, -1 para sair");
        scanf("%d", &num);
        if(num == -1)
            break;
        total += num;
        qtd++;
    }
    printf("%f", (total/(float)qtd));
    return 0;
```
