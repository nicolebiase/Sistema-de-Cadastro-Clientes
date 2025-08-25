# Sistema simples de cadastro de clientes

clientes = []

def adicionar_cliente(nome, email):
    clientes.append({"nome": nome, "email": email})
    print(f"{nome} adicionado com sucesso!")

def listar_clientes():
    for c in clientes:
        print(f"Nome: {c['nome']}, Email: {c['email']}")

# Testando
adicionar_cliente("Nicole", "nicole@email.com")
listar_clientes()
