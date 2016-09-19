_Exercicio extra: Crie uma funcao que recebe uma idade e a partir desse dado calcula a categoria._

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
