### C
```c
int binario_para_decimal(numero_binario){
      int potencia_2 = 1, resultado = 0;
      while (numero_binario != 0) {
            resultado += (numero_binario % 10) * potencia_2;
            numero_binario /= 10;
            potencia_2 *= 2;
      }
      return resultado;
}
```
### Python
```py
def binario_para_decimal(numero_binario):
        potencia_2 = 1
        resultado = 0
        while numero_binario != 0:
              resultado  += (numero_binario % 10) * potencia_2
              numero_binario /= 10
              potencia_2 *= 2
        return resultado
```
