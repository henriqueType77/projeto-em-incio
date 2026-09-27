# projeto-em-incio

paniel = """

1 = cadastrar cliente
2 = listar clientes
3 = procurar cliente
4 = sair
"""

clientes = []

cadastro = input("deseja cadaastrar um cliente? (s/n): ")

while cadastro.lower() == "s":
    
    cliente = {
        "nome": input("digite o nome do cliente: "),
        "idade": int(input("digite a idade do cliente: ")),
        "email": input("digite o email do cliente: ")
    }
    clientes.append(cliente)
    cadastro = input("Deseja cadastrar outro cliente? (s/n): ") 
    

