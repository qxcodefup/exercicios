_Exercicio extra: Crie uma funcao para calcular a media_

### C
```c
#include <stdio.h>

float receber_notas_e_soma(){
  float nota_1, nota_2,  nota_3;
  scanf("%f %f %f", &nota_1, &nota_2, &nota_3);

  return nota_1 + nota_2 + nota_3
}

int main (){
  float soma_1, soma_2, media1, media2;
  soma_1 = receber_notas_e_soma()
  soma_2 = receber_notas_e_soma()

  media1 = soma_1/ 3;
  media2 =  soma_2/ 3;

  if (media1 > media2)
    printf ("Aluno 1 teve um melhor rendimento!");
  else
    printf ( "Aluno 2 teve um melhor rendimento!");

  return 0;
}
```

### C++
```c++
#include <iostream>

using namespace std;

float receber_notas_e_soma(){
  float nota_1, nota_2,  nota_3;
  cin >> nota_1 >> nota_2 >> nota_3;

  return nota_1 + nota_2 + nota_3
}

int main (){
  float soma_1, soma_2, media1, media2;
  soma_1 = receber_notas_e_soma()
  soma_2 = receber_notas_e_soma()

  media1 = soma_1/ 3;
  media2 =  soma_2/ 3;

  if (media1 > media2)
    cout << "Aluno 1 teve um melhor rendimento!";
  else
    cout <<  "Aluno 2 teve um melhor rendimento!";

  return 0;
}
```

### Python
```python
def receber_notas_e_soma():
  nota_1 = int (input ("Digite a nota 1: "))
  nota_2 = int (input ("Digite a nota 2: "))
  nota_3 = int (input ("Digite a nota 3: "))
  return nota_1 + nota_2 +nota_3

soma_1 = receber_notas_e_soma()
soma_2 = receber_notas_e_soma()

media1 = soma_1/ 3
media2 =  soma_2/ 3

if media1 > media2:
  print "Aluno 1 teve um melhor rendimento!"
else:
  print "Aluno 2 teve um melhor rendimento!"

```
