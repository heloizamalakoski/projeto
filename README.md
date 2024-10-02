programa
 {   funcao inicio()
         {
def celsius_para_fahrenheit(celsius):
    fahrenheit = (celsius * 1.8) + 32
    return fahrenheit

# Entrada do usuário
celsius = float(input("Digite a temperatura em Celsius: "))

# Chamada da função e exibição do resultado
fahrenheit = celsius_para_fahrenheit(celsius)
print(f"A temperatura em Fahrenheit é: {fahrenheit:.2f}")
         
      
}
               
