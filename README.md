
publico = int(input("Total de pessoas no municipio: "))
validos = int(input("Total de votos válidos: "))
nulos = int(input("Total de votos Nulos: "))
while publico == validos:
    validos = int(input("Erro! Por favor digite 0\nTotal de votos nulos"))
Brancos = int(input("Total de votos Brancos: "))

while publico == validos and nulos == publico:
    nulos = int(input("Erro! Por favor digite  0 \nTotal de votos branco: "
        ))
percentual_validos = (validos / publico) * 100

print(percentual_validos)





