### C
```c
    int qtd = 0;
    int num = 0;//o numero do usuario
    int total = 0;
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

### Python
```py
#No caso de ocorrer algum erro relacionado a precisao
#Utilize: from __future__ import division
# O resto continua o mesmo
quantidade  = 0
soma = 0
num = 0
while  num != -1:
    num = int (input ())
    if num == -1:
        break
    soma += num
    quantidade += 1
media = soma / qtd
print media
```
