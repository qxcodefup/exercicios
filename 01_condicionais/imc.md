```python
def calc_imc(peso, altura):
  return peso / (altura ** 2)

def classificar(imc):
  if imc < 20:
    print "Magros"
  elif imc > 25:
    print "Obesos"
  else:
    print "Normal"

peso = float (input ("Digite o peso: "))
altura = float (input ("Digite a altura: "))

imc = calc_imc(peso, altura)

classificar(imc)
```
