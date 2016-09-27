_Exercicio extra: Crie uma funcao que recebe uma idade e a partir desse dado calcula a categoria._
###  C
```c
#include <stdio.h>

int main() {
    unsigned int idade;
    scanf("%d", &idade);
    // como nao tenho numeros negativos entao nao a necessidade de testar se o dado e maior o igual a 0
    if (idade < 10)
      printf ("Criança");
    else if (idade < 20) # Nao testa se é maior que 10 porque ja entraria na primeira condicao
      printf ( "Adolescente");
    else if (idade < 30)
      printf  ("Jovem");
    else if (idade < 40)
      printf ( "Adulto");
    else
      printf ( "Maduro");

  return 0;
}

```
###  C++
 ```c++
 #include <iotream>

using namespace std;

 int main() {
     unsigned int idade;
    cin >> idade;;
     // como nao tenho numeros negativos entao nao a necessidade de testar se o dado e maior o igual a 0
     if (idade < 10)
       cout << "Criança";;
     else if (idade < 20) # Nao testa se é maior que 10 porque ja entraria na primeira condicao
       cout <<  "Adolescente";
     else if (idade < 30)
       cout << "Jovem";
     else if (idade < 40)
       cout <<  "Adulto";
     else
       cout <<  "Maduro";

   return 0;
 }
```

### Python
```python
#abs para garatir que sejam inseridos dados positivos
idade = abs (int (input ("Digite uma idade: ")))
# como nao tenho numeros negativos entao nao a necessidade de testar se o dado e maior o igual a 0
if idade < 10:
  print "Criança"
elif idade < 20: # Nao testa se é maior que 10 porque ja entraria na primeira condicao
  print "Adolescente"
elif idade < 30:
  print "Jovem"
elif idade < 40:
  print "Adulto"
else:
  print "Maduro"

```
